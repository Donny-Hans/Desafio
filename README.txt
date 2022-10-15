EU FIZ O DESAFIO DE DADOS MAS NAO DEU TEMPO DE CONCLUIR EU FIZ O BANCO DE DADOS NO BIGQUERY


QUERY A

SELECT a.*, b.teachingability FROM(
SELECT 
  DISTINCT(prof_id),COUNT(*) TOTALGERALESTUDANTE

FROM `coursera-361123.DadosUniversity.RA`

GROUP BY prof_id
) a left join `coursera-361123.DadosUniversity.Prof`  b on a.prof_id = b.prof_id;

QUERY B
SELECT count(*)prof_id

FROM REGISTRATION;

