# Aplicativo para testar a internacionalização de idiomas

Só há uma frase na interface, a frase **"Olá, qual o seu nome?"**, o idioma padrão é **pt-BR**. Veja abaixo:


![ptbr](https://github.com/Matysys/dio-internationalization-app-test/assets/56893003/f4168ad1-8c59-4a2c-89a3-bb6ff91f3929)

As opções disponíveis além do idioma padrão são: **Inglês, Espanhol e Francês.**

## Inglês:

![ingles](https://github.com/Matysys/dio-internationalization-app-test/assets/56893003/30dd7f3f-589e-477f-9d68-279db3da2e04)

## Espanhol:

![espanhol](https://github.com/Matysys/dio-internationalization-app-test/assets/56893003/1f326854-0987-4c2b-801c-e609f067cf58)

## Francês:

![france](https://github.com/Matysys/dio-internationalization-app-test/assets/56893003/2de9e23b-b920-4093-acd9-bba69be38d34)

### Pequena conclusão
A internacionalização é feita com versões diferentes do mesmo arquivo ```strings.xml``` dentro de ```res\values\strings```. Cada versão pode ser usada para um idioma diferente, e o aplicativo vai usar o valor de referência utilizando ```@string/app_name``` no TextView em questão.


