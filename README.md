<h1>Detector de Pessoas com MQTT</h1>

<h2>Descrição 💻</h2>
Esse projeto tem como objetivo vizualizar um vídeo para detecção de pessoas. Se uma pessoa for detectada, uma mensagem e um sinal são enviados para a plataforma AdafruitIo via MQTT, epara alertar que uma pessoa foi detectada bem como para ativar um atuador.

Bibliotecas utilizadas:
- numpy
- cv2
- imutils
- FPS (de imutils.video)
- Client (de Adafruit_IO)
- time
- b64encode (de base64)

<h2>Como rodar 👨‍💻</h2>
Basta ter o python 3 instalado em sua maquina, e garantir que haja um vídeo "pessoavideo.mp4" na pasta de video, ou colocar um vídeo com nome diferente e mudar o nome no código.

<h2>Outras funcionalidade 📝</h2>
Esse código permite não só a detecção de pessoas, mas a detecção de varias outras coisas que podem ser uteis em outras aplicações. Os itens que podem ser detectados são: cenario, avião, bicicleta, pássaro, barco, garrafa, ônibus, carro, gato, cadeira, vaca, mesa de jantar, cachorro, cavalo, moto, pessoa, vaso de planta, ovelha, sofá, trem e televisão.
Para detectar algum desses itens basta substituir a variavel "itemIdentificado" para o respectivo item que é listado no array "CLASSES".

<br>Autor:<br>
<a href="https://github.com/JoabUrbano">Joab Urbano</a><br>

Código baseado no trabalho de <a href="https://pyimagesearch.com/2017/09/11/object-detection-with-deep-learning-and-opencv/">Adrian Rosebrock</a>.
