* Inserir dados em um banco de dados.
* Usando SimpleDateFormat para formatar um new java.sql.Date(sdf.parse("00/00/00"));
* Usando Connection conn para iniciar uma conexão com o banco de dados.
* Usando o PreparedStatement st para inserir valores no bd e retornando um Statement.RETURN_GENERATED_KEYS com a chave de valor do elemento criado.
* Inserindo valores aos campos com st.setStrind, st.setDouble, st.setInt entre outros.
* Ao usar um st.executeUpdate ele retorna um int para dizer quantas linhas foram alteradas.
* Aprendendo a sempre fechar a conexão por último.  