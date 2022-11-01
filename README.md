# Internet Protocol Suite: TCP + IP

Estabelece as regras de empacotamento, endereçamento, transmissão, roteamento e recebimento de dados entre redes.

## TCP: Transmition Control Protocol

 - Possibilita a comunicação entre programas e aparelhos através de uma **rede**.
 - É usado para mandar pacotes pela internet.
 - Garante a integridade da informação sendo comunicada na rede.

Em primeiro lugar, o TCP estabelece uma conexão segura entre a fonte e o destino da informação. Essa conexão permanecerá ativa até o início da comunicação. Em segundo lugar, a informação é quebrada em pequenos pacotes, garantindo a entrega dos dados sem perda.

## IP

É uma ferramenta de endereçamento que designa de maneira lógica endereços para aparelhos numa rede. **Cada aparelho terá um endereço de IP único, que o identificará.**

O IPv4 é composto por 32 bits, variam entre 0 e 1. Assim, há 4 bilhões de possíveis combinações para endereços de IP na sua versão v4.

|  Primeiro octeto|Segundo octeto  | Terceiro octeto | Quarto octeto 
|--|--|--|--|
|00000000|00000000  |00000000 |00000000

No IPv4, existem quatros octetos com 256 possibilidades em cada um, quando considerados em números decimais.

|  Primeiro octeto|Segundo octeto  | Terceiro octeto | Quarto octeto 
|--|--|--|--|
|0 a 255.|0 a 255.  |0 a 255. |0 a 255.

**Existem IPs públicos e privados**. Um IP público pode ser acessado diretamente através da internet e é designado pelo provedor de internet (ISP). Já o IP privado é o número designado pelo roteador para um aparelho e permite a comunicação entre aparelhos que compartilham a mesma rede interna. Os IPs privados não são roteáveis que há números reservados para eles. Seguem:

|IPs reservados|
|--|
|10.0.0.1 a 10.255.255.255|
|172.16.0.0 a 172.31.255.255|
|192.168.0.0 a 192.158.255.255|

Os endereços de IP mais usados no Brasil começam com o octetos 200, 201, 199 e 198. 

## Usando a BC

BC (Basic Calculator) é a calculadora básica que pode ser usada via linha de comando em sistemas Unix. É permitido usar esse recurso durante a defesa do projeto. Para acessá-la basta usar o comando `bc` em qualquer terminal.

É possível utilizar a bc para fazer conversão de números decimais em binários e vice-versa utilizando os seguintes comandos:

 - Para conversão de decimais em binários:

>  obase=2;"número"

exemplo:

![Captura de Tela 2022-11-01 às 17 11 53](https://user-images.githubusercontent.com/85964972/199332470-b6eea289-da11-415e-aec9-487f89205784.png)

- Para conversão de binários em decimais:

> ibase=2;obase=A;"número"

exemplo:

![Captura de Tela 2022-11-01 às 17 17 32](https://user-images.githubusercontent.com/85964972/199332745-fed13694-1322-490a-9662-4acc534869f0.png)

Em que `ibase` significa *input base* e `obase`, *output base*. 


