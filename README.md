Esse repositorio tem a finalidade de controlar o projeto AGV via controle de xbox ou qualquer outro que faça uso do middleware ROS.

Para fazer uso desse repositório deve criar primeiramente uma workspace ROS (considerando que o ROS esteja instalado na máquina).

- Criar workspace.
mkdir -p agv_move/src 
- Navegar para pasta src.
cd ~/agv_move/src
- Fazer o clone desse repositório.
git clone https://github.com/luschardt/agv_move

Informações adicionais a respeito da rede e transmissão de video:

Compressão de imagem 

H.264 - Imagem completa (- rápido)
H.265 - Somente areas onde houve movimento (+ rápido)

IP dos dispositivos

ip fixo agv - 10.0.0.1
ip fixo pc - 10.0.0.2
mascara subrede - 255.0.0.0

Ip da camera
http://10.0.0.5/

login: admin
senha: Intelbras

15fps é o sulficiente para os seres humanos terem a 
sensação de fluidez na imagem.
