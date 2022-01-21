# PERGUNTA_10
-- Create table tab
create TABLE tab(
  id int,
  codid INT );

-- Inserir na tabela
insert into tab values (1,1);
commit;
insert into tab values (2,2);

--Eliminar a data
truncate table  tab;
-- Inserir na tabela
insert into tab values (3,3);
--Retroceder aos ultimos modificacion
rollback;
-- Inserir na tabela
insert into tab values (4,4);
-- Fazer consulta
select count(*) from tab

-- A resposta: executado na mesma sessão 2 
-- executado em outra sessã: VAZIO
