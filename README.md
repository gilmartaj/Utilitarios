# Utilitários

### BaixadorMultithread_v2.java
* Baixador multithread / continua "downloads" de onde parou
* Versão 2
* Nesta versão, cria um arquivo no disco do tamanho total do arquivo a ser baixado e vai pŕeenchendo com os bytes descarregados
* Na versão 1, eram baixados arquivos separados e depois juntados em um novo arquivo

* Compilação: javac BaixadorMultithread_v2.java
* Execução: java BaixadorMultithread_v2 [quantidade_threads] [nome_arquivo]
