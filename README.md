# Encryptor

Sistema para encriptar arquivos de forma fácil utilizando o padrão
Pretty Good Privacy (PGP).

* Crie um arquivo na pasta do executável com o nome __PublicKey__,
o conteúdo do arquivo deverá ser como no exemplo abaixo:
```text
-----BEGIN PGP PUBLIC KEY BLOCK-----
Version: BCPG C# v1.6.1.0

mQENBFxdsKMBCACRLct0nwmx2HjswG6qjJne8xqKCJltir9K7rKvxieOIjCw1QFP
Dlv4xQbQIM8eoRxnJJGB15b764o9x376gofGLffETZL83RgfFn4sMO04oAqBGKzI
CZCnxr3O9FvCZsFi5noCjP7iSSivwHo/dWRQMCbnC49NNrhiRoudOVtNSOxIInZI
4WlnytAxW64BXNL7xm5qxGVUiadvLk3yEh5VaGoot2dg6N1edYWWRr0EZw86LlPp
8kyc2So8MJSCpQuKysbWQ8xJFfSf9VraNCSv+0QaMRu7CakXdG+ZOMuuZG5jpkB5
jWyjSO80fvqte4Xkkyj6qn4DFph/3yOmbL3nABEBAAG0AIkBHAQQAQIABgUCXF2w
owAKCRAcdhJ8khzkpN3qB/sHTE7yg3rKjBxlf8oshs0YHKgHS6MTq88A2ZWxGfxZ
BYrOjOpqWTsDxiRdaIiuSKUarCg2mwdxsbpkQcgY98arL8PPcW9SYMMqkhaRPB6U
FjAlRdRLxiXu1Jldf8/Rd+E3yhCcrt4YGP7A0B1tYtLwCrXXJ+5oyi0hxhuKv8jN
4nVPbLuJoGppluPpkUjQBEYBz2CZO4kpYQw49Dh4hlpPMmKzLU+g/AEpNKRwPyxh
IxsEitwU9vuDGRyXu7Wc01G9WLPMXAylpPQMqKVj+aPX2hexV5LhaSxH1h7jUGTl
XadsnnbNEHWv2WqK16mPg3uOdwMpIaGoPyFuTGhGHFqu
=RsCq
-----END PGP PUBLIC KEY BLOCK-----

```
* Coloque o arquivo que deseja criptografar na pasta __Input__;
    * O aplicativo detectará a inclusão do arquivo.
* Aguarde a aplicação finalizar o processo;
* Obtenha o arquivo encriptado na pasta __Output__.