# Operações Pontuais e Filtro utilizando *OpenCV*
Para que possa acontecer as transformações é necessário o uso da biblioteca open-source de Python chamada OpenCV (Open Source Computer Vision Libary), criada para auxiliar em soluções visuais em computadores e também para acelerar a percepcão do uso de máquinas em produtos comerciais. Essa biblioteca tem funcões para processar imagens e também videos, identificando objetos, escritas e rostos. Além disso, para exportar o máximo de sua capacidade se utilza outras bibliotecas como **NumPy** para ajudar a processas os arrays do OpenCV.

### Nesse código é demonstrado alguns tipos transformações aplicando a biblioteca **OpenCV e NumPy** como:
1. Conversão de imagens RGB em Greyscale, convertendo imagens coloridas em imagens preto e branco;
2. Negativo de imagens, invertendo suas cores originais;
3. Mudança de contraste e brilho da imagem, mexendo na intensidade das cores e na luminosidade;
4. Suavização, aplicando um blur.

Ao abrir o código no Colab, para se poder ver as transformações, é preciso baixar uma imagem na pasta que se encontra no canto esquerdo da tela (melhor se forem imagens mais leves) e 
mudar o endereço da mesma nas partes do código onde se encontra o:
`img = cv2.imread('xxx.png',1)`
Após esses passos, basta clicar no botão que está nas células e esperar que a máquina se conecte.
   
Para mais explicações sobre o funcionamento do código, o mesmo está inteiramente documentado. E caso deseje mais detalhes, todos os processos de operções usando OpenCV estão documetados no [Site](https://opencv.org/) do mesmo.
