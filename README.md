# Ransomware-na-Pratica-com-Python

"O objetivo deste código é simular o processo de descriptografar um arquivo que foi criptografado por um ransomware, usando Python.

1. **Chave para descriptografia**: O código utiliza uma chave predefinida (`testeransomwares`) para realizar a descriptografia através do algoritmo AES (Advanced Encryption Standard). Essa chave é fundamental para restaurar os dados criptografados.

2. **Descriptografar os dados**: A criptografia AES é feita em modo CTR (Counter), e a chave fornecida é usada para descriptografar o conteúdo do arquivo original.

3. **Remover o arquivo criptografado**: Após a descriptografia, o arquivo criptografado (com a extensão `.ransom`) é removido do sistema para evitar que ele seja acessado acidentalmente.

4. **Criar o arquivo descriptografado**: Finalmente, o código cria um novo arquivo (no caso, `teste.txt`) contendo os dados descriptografados, restaurando o conteúdo original do arquivo criptografado."
