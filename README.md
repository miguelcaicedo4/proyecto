# proyecto
Proyecto final de programacion identificador de pistas
import matplotlib.pyplot as plt
plt.rcParams['image.cmap'] = 'gray'
import numpy as np


size=(21,31)
imagen_negra = np.zeros(size) 
m = 0 #Variable de Metros, por cada pixel que se recorre el programa lo toma como un metro

def crearPista(x,y):#codigo que cambia un pixel de color negro a blanco
    if imagen_negra[x][y] == 0:
        imagen_negra [x][y] = 1
        
    else:
        print("hola")


#-----------------------------------------------------------------------------------------------------------------------------
#-----------------------------------------------------------------------------------------------------------------------------
#-----------------------------------------------------------------------------------------------------------------------------


#Codigos de pistas
#Esto es solo la creacion de la pista que va a recorrer el programa        
def Pista1():
    imagen_negra [2][23] = 0.5
    imagen_negra [3][23] = 0.5
    imagen_negra [2][25] = 0.5
    imagen_negra [3][25] = 0.5
    imagen_negra [6][23] = 0.5
    imagen_negra [6][24] = 0.5
    imagen_negra [6][25] = 0.5
    imagen_negra [5][22] = 0.5
    imagen_negra [5][26] = 0.5
    imagen_negra [3][17] = 0.5
    imagen_negra [2][18] = 0.5
    imagen_negra [3][18] = 0.5
    imagen_negra [4][18] = 0.5
    imagen_negra [5][18] = 0.5
    imagen_negra [6][17] = 0.5
    imagen_negra [6][18] = 0.5
    imagen_negra [6][19] = 0.5
    crearPista(1, 1)
    crearPista(1, 1)
    crearPista(1, 2)
    crearPista(1, 3)
    crearPista(2, 3)
    crearPista(3, 3)
    crearPista(4, 3)
    crearPista(4, 4)
    crearPista(4, 5)
    crearPista(4, 6)
    crearPista(4, 7)
    crearPista(5, 7)
    crearPista(6, 7)
    crearPista(7, 7)
    crearPista(8, 7)
    crearPista(8, 8)
    crearPista(8, 9)
    crearPista(8, 10)
    crearPista(8, 11)
    crearPista(9, 11)
    crearPista(10, 11)
    crearPista(11, 11)
    crearPista(12, 11)
    crearPista(12, 12)
    crearPista(12, 13)
    crearPista(12, 14)
    crearPista(12, 15)
    crearPista(13, 15)
    crearPista(14, 15)
    crearPista(15, 15)
    crearPista(16, 15)
    crearPista(16, 16)
    crearPista(16, 17)
    crearPista(16, 18)
    crearPista(16, 19)
    crearPista(17, 19)
    crearPista(18, 19)
    crearPista(19, 19)
    #Fin del codigo para la Pista 1
    
    
def Pista2():
    imagen_negra [3][14] = 0.5
    imagen_negra [2][15] = 0.5
    imagen_negra [2][16] = 0.5
    imagen_negra [3][17] = 0.5
    imagen_negra [4][17] = 0.5
    imagen_negra [5][16] = 0.5
    imagen_negra [6][15] = 0.5
    imagen_negra [7][14] = 0.5
    imagen_negra [8][14] = 0.5
    imagen_negra [8][15] = 0.5
    imagen_negra [8][16] = 0.5
    imagen_negra [8][17] = 0.5
    crearPista(1, 1)
    crearPista(1, 2)
    crearPista(1, 3)
    crearPista(2, 3)
    crearPista(3, 3)
    crearPista(4, 3)
    crearPista(5, 3)
    crearPista(6, 3)
    crearPista(7, 3)
    crearPista(8, 3)
    crearPista(9, 3)
    crearPista(10, 3)
    crearPista(11, 3)
    crearPista(12, 3)
    crearPista(13, 3)
    crearPista(14, 3)
    crearPista(15, 3)
    crearPista(16, 3)
    crearPista(17, 3)
    crearPista(18, 3)
    crearPista(19, 3)
    crearPista(19, 4)
    crearPista(19, 5)
    crearPista(19, 6)
    crearPista(19, 7)
    crearPista(19, 8)
    crearPista(19, 9)
    crearPista(19, 10)
    crearPista(19, 11)
    crearPista(19, 12)
    crearPista(19, 13)
    crearPista(19, 14)
    crearPista(19, 15)
    crearPista(19, 16)
    crearPista(19, 17)
    crearPista(19, 18)
    crearPista(19, 19)
    crearPista(19, 20)
    crearPista(19, 21)
    crearPista(19, 22)
    crearPista(19, 23)
    crearPista(19, 24)
    crearPista(19, 25)
    crearPista(19, 26)
    crearPista(19, 27)
    crearPista(19, 28)
    crearPista(18, 28)
    crearPista(17, 28)
    crearPista(16, 28)
    crearPista(15, 28)
    crearPista(14, 28)
    crearPista(13, 28)
    crearPista(12, 28)
    crearPista(11, 28)
    crearPista(10, 28)
    crearPista(9, 28)
    crearPista(8, 28)
    crearPista(7, 28)
    crearPista(6, 28)
    crearPista(5, 28)
    crearPista(4, 28)
    crearPista(3, 28)
    crearPista(2, 28)
    crearPista(1, 28)
    crearPista(1, 29)
    #fin del codigo para la pista 2
    

def Pista3():
    imagen_negra [8][14] = 0.5
    imagen_negra [7][15] = 0.5
    imagen_negra [7][16] = 0.5
    imagen_negra [8][17] = 0.5##
    imagen_negra [9][17] = 0.5
    imagen_negra [10][16] = 0.5
    imagen_negra [10][15] = 0.5
    imagen_negra [11][17] = 0.5
    imagen_negra [12][17] = 0.5
    imagen_negra [13][16] = 0.5
    imagen_negra [13][15] = 0.5
    imagen_negra [12][14] = 0.5
    crearPista(1, 1)
    crearPista(1, 2)
    crearPista(1, 3)
    crearPista(2, 3)
    crearPista(3, 3)
    crearPista(4, 3)
    crearPista(5, 3)
    crearPista(6, 3)
    crearPista(7, 3)
    crearPista(8, 3)
    crearPista(9, 3)
    crearPista(10, 3)
    crearPista(11, 3)
    crearPista(12, 3)
    crearPista(13, 3)
    crearPista(14, 3)
    crearPista(15, 3)
    crearPista(15, 4)
    crearPista(15, 5)
    crearPista(15, 6)
    crearPista(15, 7)
    crearPista(14, 7)
    crearPista(13, 7)
    crearPista(12, 7)
    crearPista(11, 7)
    crearPista(10, 7)
    crearPista(9, 7)
    crearPista(8, 7)
    crearPista(7, 7)
    crearPista(6, 7)
    crearPista(5, 7)
    crearPista(4, 7)
    crearPista(3, 7)
    crearPista(3, 8)
    crearPista(3, 9)
    crearPista(3, 10)
    crearPista(3, 11)
    crearPista(3, 12)
    crearPista(3, 13)
    crearPista(3, 14)
    crearPista(3, 15)
    crearPista(3, 16)
    crearPista(3, 17)
    crearPista(3, 18)
    crearPista(3, 19)
    crearPista(3, 20)
    crearPista(3, 21)
    crearPista(3, 22)
    crearPista(4, 22)
    crearPista(5, 22)
    crearPista(6, 22)
    crearPista(7, 22)
    crearPista(8, 22)
    crearPista(9, 22)
    crearPista(10, 22)
    crearPista(11, 22)
    crearPista(12, 22)
    crearPista(13, 22)
    crearPista(14, 22)
    crearPista(15, 22)
    crearPista(15, 23) 
    crearPista(15, 24)
    crearPista(15, 25)
    crearPista(14, 25)
    crearPista(13, 25)
    crearPista(12, 25)
    crearPista(11, 25)
    crearPista(10, 25)
    crearPista(9, 25)
    crearPista(8, 25)
    crearPista(7, 25)
    crearPista(6, 25)
    crearPista(5, 25)
    crearPista(4, 25)
    crearPista(3, 25)
    crearPista(2, 25)
    crearPista(1, 25)
    crearPista(1, 26)
    crearPista(1, 27)
    crearPista(1, 28)
    crearPista(1, 29)
    #Fin del codigo para la pista 3
    
def Pista4():
    imagen_negra [14][4] = 0.5
    imagen_negra [15][4] = 0.5
    imagen_negra [16][4] = 0.5
    imagen_negra [16][5] = 0.5
    imagen_negra [16][6] = 0.5
    imagen_negra [16][7] = 0.5
    imagen_negra [14][6] = 0.5
    imagen_negra [15][6] = 0.5
    imagen_negra [16][6] = 0.5
    imagen_negra [17][6] = 0.5
    imagen_negra [18][6] = 0.5
    crearPista(1, 1)
    crearPista(1, 2)
    crearPista(1, 3)
    crearPista(2, 3)
    crearPista(3, 3)
    crearPista(4, 3)
    crearPista(5, 3)
    crearPista(6, 3)
    crearPista(7, 3)
    crearPista(8, 3)
    crearPista(9, 3)
    crearPista(10, 3)
    crearPista(10, 4)
    crearPista(10, 5)
    crearPista(10, 6)
    crearPista(10, 7)
    crearPista(9, 7)
    crearPista(8, 7)
    crearPista(7, 7)
    crearPista(7, 8)
    crearPista(7, 9)
    crearPista(7, 10)
    crearPista(7, 11)
    crearPista(8, 11)
    crearPista(9, 11)
    crearPista(10, 11)
    crearPista(11, 11)
    crearPista(12, 11)
    crearPista(13, 11)
    crearPista(13, 12)
    crearPista(13, 13)
    crearPista(13, 14)
    crearPista(13, 15)
    crearPista(12, 15)
    crearPista(11, 15)
    crearPista(10, 15)
    crearPista(9, 15)
    crearPista(8, 15)
    crearPista(7, 15)
    crearPista(6, 15)
    crearPista(5, 15)
    crearPista(4, 15)
    crearPista(4, 16)
    crearPista(4, 17)
    crearPista(4, 18)
    crearPista(4, 19)
    crearPista(5, 19)
    crearPista(6, 19)
    crearPista(7, 19)
    crearPista(8, 19)
    crearPista(9, 19)
    crearPista(10, 19)
    crearPista(11, 19)
    crearPista(12, 19)
    crearPista(13, 19)
    crearPista(14, 19)
    crearPista(15, 19)
    crearPista(16, 19)
    crearPista(16, 20)
    crearPista(16, 21)
    crearPista(16, 22)
    crearPista(16, 23)
    crearPista(15, 23)
    crearPista(14, 23)
    crearPista(13, 23)
    crearPista(12, 23)
    crearPista(11, 23)
    crearPista(10, 23)
    crearPista(9, 23)
    crearPista(8, 23)
    crearPista(7, 23)
    crearPista(6, 23)
    crearPista(5, 23)
    crearPista(4, 23)
    crearPista(3, 23)
    crearPista(2, 23)
    crearPista(1, 23)
    crearPista(1, 24)
    crearPista(1, 25)
    crearPista(1, 26)
    crearPista(1, 27)
    crearPista(2, 27)
    crearPista(3, 27)
    crearPista(4, 27)
    crearPista(5, 27)
    crearPista(6, 27)
    crearPista(7, 27)
    crearPista(8, 27)
    crearPista(9, 27)
    crearPista(10, 27)
    crearPista(11, 27)
    crearPista(12, 27)
    crearPista(13, 27)
    crearPista(14, 27)
    crearPista(15, 27)
    crearPista(16, 27)
    crearPista(17, 27)
    crearPista(18, 27)
    crearPista(19, 27)
    crearPista(19, 28)
    crearPista(19, 29)
    #Fin del codigo para la pista 4

def pista5():
    crearPista(1,1)
    crearPista(1,2)
    crearPista(1,3)
    crearPista(1,4)
    crearPista(1,5)
    crearPista(2,5)
    crearPista(3,5)
    crearPista(4,5)
    crearPista(5,5)
    crearPista(6,5)
    crearPista(7,5)
    crearPista(8,5)
    crearPista(9,5)
    crearPista(10,5)
    crearPista(11,5)
    crearPista(12,5)
    crearPista(13,5)
    crearPista(13,6)
    crearPista(13,7)
    crearPista(13,8)
    crearPista(13,9)
    crearPista(13,10)
    crearPista(12,10)
    crearPista(11,10)
    crearPista(10,10)
    crearPista(9,10)
    crearPista(8,10)
    crearPista(7,10)
    crearPista(7,11)
    crearPista(7,12)
    crearPista(7,13)
    crearPista(7,14)
    crearPista(6,14)
    crearPista(5,14)
    crearPista(4,14)
    crearPista(4,13)
    crearPista(4,12)
    crearPista(3,12)
    crearPista(2,12)
    crearPista(1,12)
    crearPista(1,13)
    crearPista(1,14)
    crearPista(1,15)
    crearPista(1,16)
    crearPista(1,17)
    crearPista(1,18)
    crearPista(1,19)
    crearPista(1,20)
    crearPista(2,20)
    crearPista(3,20)
    crearPista(4,20)
    crearPista(5,20)
    crearPista(6,20)
    crearPista(7,20)
    crearPista(8,20)
    crearPista(9,20)
    crearPista(10,20)
    crearPista(11,20)
    crearPista(12,20)
    crearPista(13,20)
    crearPista(13,21)
    crearPista(13,22)
    crearPista(13,23)
    crearPista(13,24)
    crearPista(13,25)
    crearPista(13,26)
    crearPista(13,27)
    crearPista(13,28)
    crearPista(2,28)
    crearPista(2,27)
    crearPista(2,26)
    crearPista(2,25)
    crearPista(2,24)
    crearPista(3,24)
    crearPista(4,24)
    crearPista(5,24)
    crearPista(6,24)
    crearPista(6,25)
    crearPista(6,26)
    crearPista(6,27)
    crearPista(6,28)
    crearPista(7,28)
    crearPista(8,28)
    crearPista(9,28)
    crearPista(10,28)
    crearPista(10,27)
    crearPista(10,26)
    crearPista(10,25)
    crearPista(10,24)

def pista6():      
    crearPista(1,1)
    crearPista(1,2)
    crearPista(1,3)
    crearPista(1,4)
    crearPista(1,5)
    crearPista(2,5)
    crearPista(3,5)
    crearPista(4,5)
    crearPista(5,5)
    crearPista(6,5)
    crearPista(7,5)
    crearPista(8,5)
    crearPista(9,5)
    crearPista(10,5)
    crearPista(11,5)
    crearPista(12,5)
    crearPista(13,5)
    crearPista(14,5)
    crearPista(15,5)
    crearPista(16,5)
    crearPista(16,6)
    crearPista(16,7)
    crearPista(16,8)
    crearPista(16,9)
    crearPista(16,10)
    crearPista(16,11)
    crearPista(16,12)
    crearPista(15,12)
    crearPista(14,12)
    crearPista(13,12)
    crearPista(12,12)
    crearPista(11,12)
    crearPista(10,12)
    crearPista(9,12)
    crearPista(8,12)
    crearPista(7,12)
    crearPista(6,12)
    crearPista(6,13)
    crearPista(6,14)
    crearPista(6,15)
    crearPista(6,16)
    crearPista(6,17)
    crearPista(6,18)
    crearPista(6,19)
    crearPista(6,20)
    crearPista(6,21)
    crearPista(6,22)
    crearPista(6,23)
    crearPista(6,24)
    crearPista(5,24)
    crearPista(4,24)
    crearPista(3,24)
    crearPista(3,25)
    crearPista(3,26)
    crearPista(3,27)
    crearPista(3,28)
    crearPista(11,24)
    crearPista(11,23)
    crearPista(12,22)
    crearPista(13,21)
    crearPista(14,21)
    crearPista(15,21)
    crearPista(16,21)
    crearPista(17,21)
    crearPista(18,22)
    crearPista(18,23)
    crearPista(18,24)
    crearPista(17,25)
    crearPista(16,25)
    crearPista(15,25)
    crearPista(14,24)
    crearPista(14,23)
    crearPista(14,22)

def pista7():
    crearPista(1,1)
    crearPista(1,2)
    crearPista(1,3)
    crearPista(1,4)
    crearPista(1,5)
    crearPista(1,6)
    crearPista(1,7)
    crearPista(1,8)
    crearPista(1,9)
    crearPista(1,10)
    crearPista(1,11)
    crearPista(1,12)
    crearPista(1,13)
    crearPista(1,14)
    crearPista(1,15)
    crearPista(1,16)
    crearPista(1,17)
    crearPista(2,17)
    crearPista(3,17)
    crearPista(4,17)
    crearPista(5,17)
    crearPista(6,17)
    crearPista(6,16)
    crearPista(6,15)
    crearPista(6,14)
    crearPista(6,13)
    crearPista(6,12)
    crearPista(6,11)
    crearPista(7,11)
    crearPista(8,11)
    crearPista(9,11)
    crearPista(10,11)
    crearPista(11,11)
    crearPista(12,11)
    crearPista(13,11)
    crearPista(13,12)
    crearPista(13,13)
    crearPista(13,14)
    crearPista(13,15)
    crearPista(13,16)
    crearPista(13,17)
    crearPista(13,18)
    crearPista(13,19)
    crearPista(13,20)
    crearPista(13,21)
    crearPista(13,22)
    crearPista(13,23)
    crearPista(13,24)
    crearPista(13,25)
    crearPista(13,26)
    crearPista(13,27)
    crearPista(13,28)
    crearPista(7,3)
    crearPista(7,4)
    crearPista(7,5)
    crearPista(7,6)
    crearPista(8,6)
    crearPista(9,6)
    crearPista(10,6)
    crearPista(11,6)
    crearPista(12,6)
    
def pista8():
    crearPista(1,1)
    crearPista(1,2)
    crearPista(1,3)
    crearPista(2,3)
    crearPista(3,3)
    crearPista(4,3)
    crearPista(5,3)
    crearPista(6,3)
    crearPista(7,3)
    crearPista(8,3)
    crearPista(9,3)
    crearPista(10,3)
    crearPista(11,3)
    crearPista(12,3)
    crearPista(13,3)
    crearPista(13,4)
    crearPista(13,5)
    crearPista(13,6)
    crearPista(13,7)
    crearPista(13,8)
    crearPista(13,9)
    crearPista(13,10)
    crearPista(12,10)
    crearPista(11,10)
    crearPista(10,10)
    crearPista(9,10)
    crearPista(8,10)
    crearPista(7,10)
    crearPista(6,10)
    crearPista(5,10)
    crearPista(5,9)
    crearPista(5,8)
    crearPista(4,8)
    crearPista(3,8)
    crearPista(2,8)
    crearPista(2,9)
    crearPista(2,10)
    crearPista(2,11)
    crearPista(2,12)
    crearPista(2,13)
    crearPista(2,14)
    crearPista(2,15)
    crearPista(2,16)
    crearPista(2,17)
    crearPista(3,17)
    crearPista(4,17)
    crearPista(5,17)
    crearPista(5,16)
    crearPista(5,15)
    crearPista(5,14)
    crearPista(6,14)
    crearPista(7,14)
    crearPista(8,14)
    crearPista(9,14)
    crearPista(10,14)
    crearPista(11,14)
    crearPista(12,14)
    crearPista(13,14)
    crearPista(13,15)
    crearPista(13,16)
    crearPista(13,17)
    crearPista(13,18)
    crearPista(13,19)
    crearPista(13,20)
    crearPista(13,21)
    crearPista(12,21)
    crearPista(11,21)
    crearPista(11,22)
    crearPista(11,23)
    crearPista(11,24)
    crearPista(11,25)
    crearPista(11,26)
    crearPista(11,27)
    crearPista(11,28)
    crearPista(2,23)
    crearPista(2,24)
    crearPista(2,25)
    crearPista(2,26)
    crearPista(3,26)
    crearPista(4,26)
    crearPista(5,26)
    crearPista(6,26)
    crearPista(7,26)
    crearPista(8,26)
    crearPista(8,25)
    crearPista(8,24)
    crearPista(8,23)
    crearPista(7,23)
    crearPista(6,23)
    crearPista(5,23)
    crearPista(4,23)
    crearPista(3,23)
    crearPista(5,24)
    crearPista(5,25)
    
    
def Catalogo():#Este e sun catalogo para ver las pistas que estan disponibles.
    imagen_negra [3][3] = 0.5#Pista1
    imagen_negra [4][3] = 0.5
    imagen_negra [5][3] = 0.5
    imagen_negra [6][3] = 0.5
    imagen_negra [7][3] = 0.5
    imagen_negra [8][3] = 0.5
    imagen_negra [9][3] = 0.5
    imagen_negra [9][4] = 0.5
    imagen_negra [9][5] = 0.5
    imagen_negra [9][6] = 0.5
    imagen_negra [9][7] = 0.5
    imagen_negra [9][8] = 0.5
    imagen_negra [3][4] = 0.5
    imagen_negra [3][5] = 0.5
    imagen_negra [3][6] = 0.5
    imagen_negra [3][7] = 0.5
    imagen_negra [3][8] = 0.5
    imagen_negra [3][9] = 0.5
    imagen_negra [4][9] = 0.5
    imagen_negra [5][9] = 0.5
    imagen_negra [6][9] = 0.5
    imagen_negra [7][9] = 0.5
    imagen_negra [8][9] = 0.5
    imagen_negra [9][9] = 0.5
    crearPista(4, 4)
    crearPista(4, 5)
    crearPista(5, 5)
    crearPista(6, 5)
    crearPista(6, 6)
    crearPista(6, 7)
    crearPista(7, 7)
    crearPista(8, 7)
    crearPista(8, 8)#Pista1
    imagen_negra [3][9] = 0.5#Pista2
    imagen_negra [4][9] = 0.5
    imagen_negra [5][9] = 0.5
    imagen_negra [6][9] = 0.5
    imagen_negra [7][9] = 0.5
    imagen_negra [8][9] = 0.5
    imagen_negra [9][9] = 0.5
    imagen_negra [9][10] = 0.5
    imagen_negra [9][11] = 0.5
    imagen_negra [9][12] = 0.5
    imagen_negra [9][13] = 0.5
    imagen_negra [9][14] = 0.5
    imagen_negra [3][10] = 0.5
    imagen_negra [3][11] = 0.5
    imagen_negra [3][12] = 0.5
    imagen_negra [3][13] = 0.5
    imagen_negra [3][14] = 0.5
    imagen_negra [3][15] = 0.5
    imagen_negra [4][15] = 0.5
    imagen_negra [5][15] = 0.5
    imagen_negra [6][15] = 0.5
    imagen_negra [7][15] = 0.5
    imagen_negra [8][15] = 0.5
    imagen_negra [9][15] = 0.5
    crearPista(5, 10)
    crearPista(5, 11)
    crearPista(6, 11)
    crearPista(7, 11)
    crearPista(8, 11)
    crearPista(8, 12)
    crearPista(8, 13)
    crearPista(7, 13)
    crearPista(6, 13)
    crearPista(5, 13)
    crearPista(5, 14)#Pista2
    imagen_negra [3][9] = 0.5#Pista3
    imagen_negra [4][15] = 0.5
    imagen_negra [5][15] = 0.5
    imagen_negra [6][15] = 0.5
    imagen_negra [7][15] = 0.5
    imagen_negra [8][15] = 0.5
    imagen_negra [9][15] = 0.5
    imagen_negra [9][16] = 0.5
    imagen_negra [9][17] = 0.5
    imagen_negra [9][18] = 0.5
    imagen_negra [9][19] = 0.5
    imagen_negra [9][20] = 0.5
    imagen_negra [3][16] = 0.5
    imagen_negra [3][17] = 0.5
    imagen_negra [3][18] = 0.5
    imagen_negra [3][19] = 0.5
    imagen_negra [3][20] = 0.5
    imagen_negra [3][21] = 0.5
    imagen_negra [4][21] = 0.5
    imagen_negra [5][21] = 0.5
    imagen_negra [6][21] = 0.5
    imagen_negra [7][21] = 0.5
    imagen_negra [8][21] = 0.5
    imagen_negra [9][21] = 0.5
    crearPista(5, 16)
    crearPista(5, 17)
    crearPista(6, 17)
    crearPista(7, 17)
    crearPista(8, 17)
    crearPista(5, 18)
    crearPista(8, 19)
    crearPista(7, 19)
    crearPista(6, 19)
    crearPista(5, 19)
    crearPista(5, 20)#Pista3
    imagen_negra [3][9] = 0.5#Pista4
    imagen_negra [4][21] = 0.5
    imagen_negra [5][21] = 0.5
    imagen_negra [6][21] = 0.5
    imagen_negra [7][21] = 0.5
    imagen_negra [8][21] = 0.5
    imagen_negra [9][21] = 0.5
    imagen_negra [9][22] = 0.5
    imagen_negra [9][23] = 0.5
    imagen_negra [9][24] = 0.5
    imagen_negra [9][25] = 0.5
    imagen_negra [9][26] = 0.5
    imagen_negra [3][22] = 0.5
    imagen_negra [3][23] = 0.5
    imagen_negra [3][24] = 0.5
    imagen_negra [3][25] = 0.5
    imagen_negra [3][26] = 0.5
    imagen_negra [3][27] = 0.5
    imagen_negra [4][27] = 0.5
    imagen_negra [5][27] = 0.5
    imagen_negra [6][27] = 0.5
    imagen_negra [7][27] = 0.5
    imagen_negra [8][27] = 0.5
    imagen_negra [9][27] = 0.5
    crearPista(5, 22)
    crearPista(5, 23)
    crearPista(6, 23)
    crearPista(7, 23)
    crearPista(7, 24)
    crearPista(7, 25)
    crearPista(6, 25)
    crearPista(5, 25)
    crearPista(5, 26)#Pista4
    imagen_negra [12][3] = 0.5#Pista5
    imagen_negra [13][3] = 0.5
    imagen_negra [14][3] = 0.5
    imagen_negra [15][3] = 0.5
    imagen_negra [16][3] = 0.5
    imagen_negra [17][3] = 0.5
    imagen_negra [18][3] = 0.5
    imagen_negra [18][4] = 0.5
    imagen_negra [18][5] = 0.5
    imagen_negra [18][6] = 0.5
    imagen_negra [18][7] = 0.5
    imagen_negra [18][8] = 0.5
    imagen_negra [12][4] = 0.5
    imagen_negra [12][5] = 0.5
    imagen_negra [12][6] = 0.5
    imagen_negra [12][7] = 0.5
    imagen_negra [12][8] = 0.5
    imagen_negra [12][9] = 0.5
    imagen_negra [13][9] = 0.5
    imagen_negra [14][9] = 0.5
    imagen_negra [15][9] = 0.5
    imagen_negra [16][9] = 0.5
    imagen_negra [17][9] = 0.5
    imagen_negra [18][9] = 0.5#Pista5
    imagen_negra [12][9] = 0.5#Pista6
    imagen_negra [13][9] = 0.5
    imagen_negra [14][9] = 0.5
    imagen_negra [15][9] = 0.5
    imagen_negra [16][9] = 0.5
    imagen_negra [17][9] = 0.5
    imagen_negra [18][9] = 0.5
    imagen_negra [18][10] = 0.5
    imagen_negra [18][11] = 0.5
    imagen_negra [18][12] = 0.5
    imagen_negra [18][13] = 0.5
    imagen_negra [18][14] = 0.5
    imagen_negra [12][10] = 0.5
    imagen_negra [12][11] = 0.5
    imagen_negra [12][12] = 0.5
    imagen_negra [12][13] = 0.5
    imagen_negra [12][14] = 0.5
    imagen_negra [12][15] = 0.5
    imagen_negra [13][15] = 0.5
    imagen_negra [14][15] = 0.5
    imagen_negra [15][15] = 0.5
    imagen_negra [16][15] = 0.5
    imagen_negra [17][15] = 0.5
    imagen_negra [18][15] = 0.5#Pista6
    imagen_negra [12][9] = 0.5#Pista7
    imagen_negra [13][15] = 0.5
    imagen_negra [14][15] = 0.5
    imagen_negra [15][15] = 0.5
    imagen_negra [16][15] = 0.5
    imagen_negra [17][15] = 0.5
    imagen_negra [18][15] = 0.5
    imagen_negra [18][16] = 0.5
    imagen_negra [18][17] = 0.5
    imagen_negra [18][18] = 0.5
    imagen_negra [18][19] = 0.5
    imagen_negra [18][20] = 0.5
    imagen_negra [12][16] = 0.5
    imagen_negra [12][17] = 0.5
    imagen_negra [12][18] = 0.5
    imagen_negra [12][19] = 0.5
    imagen_negra [12][20] = 0.5
    imagen_negra [12][21] = 0.5
    imagen_negra [13][21] = 0.5
    imagen_negra [14][21] = 0.5
    imagen_negra [15][21] = 0.5
    imagen_negra [16][21] = 0.5
    imagen_negra [17][21] = 0.5
    imagen_negra [18][21] = 0.5#Pista7
    imagen_negra [12][9] = 0.5#Pista8
    imagen_negra [13][21] = 0.5
    imagen_negra [14][21] = 0.5
    imagen_negra [15][21] = 0.5
    imagen_negra [16][21] = 0.5
    imagen_negra [17][21] = 0.5
    imagen_negra [18][21] = 0.5
    imagen_negra [18][22] = 0.5
    imagen_negra [18][23] = 0.5
    imagen_negra [18][24] = 0.5
    imagen_negra [18][25] = 0.5
    imagen_negra [18][26] = 0.5
    imagen_negra [12][22] = 0.5
    imagen_negra [12][23] = 0.5
    imagen_negra [12][24] = 0.5
    imagen_negra [12][25] = 0.5
    imagen_negra [12][26] = 0.5
    imagen_negra [12][27] = 0.5
    imagen_negra [13][27] = 0.5
    imagen_negra [14][27] = 0.5
    imagen_negra [15][27] = 0.5
    imagen_negra [16][27] = 0.5
    imagen_negra [17][27] = 0.5
    imagen_negra [18][27] = 0.5#Pista8


#-----------------------------------------------------------------------------------------------------------------------------    
#-----------------------------------------------------------------------------------------------------------------------------
#-----------------------------------------------------------------------------------------------------------------------------
#Fin de codigos de pistas!
#-----------------------------------------------------------------------------------------------------------------------------   
#-----------------------------------------------------------------------------------------------------------------------------    
#-----------------------------------------------------------------------------------------------------------------------------
    
    
#Este es el codigo que crea al corredor el cual evaluasus cuatro direcciones buscando el camino y lo sigue hasta que completa la pista
def Corredor(x,y):
    m = 0
    imagen_negra[x][y] = 0.5
    while imagen_negra[x][y]: 
        x = x+1
        if imagen_negra[x][y] == 1:
            imagen_negra[x][y] = 0.5
            x= x-1
            imagen_negra[x][y] = 0.2
            x = x+1
            imagen_negra[x][y] = 0.5
            print("Se movio hacia abajo")
            m = m+1
        else:
            x=x-1
            y=y+1
            if imagen_negra[x][y] == 1:
                imagen_negra[x][y] = 0.5
                y=y-1
                imagen_negra[x][y] = 0.2
                y=y+1
                imagen_negra[x][y] = 0.5
                print("Se movio hacia la derecha")
                m = m+1
            else:
                y=y-2
                if imagen_negra[x][y] == 1:
                    imagen_negra[x][y] = 0.5
                    y=y+1
                    imagen_negra[x][y] = 0.2
                    y=y-1
                    imagen_negra[x][y] = 0.5
                    print("Se movio hacia la izquierda")
                    m = m+1
                else:
                    y =y+ 1
                    x=x-1
                    if imagen_negra[x][y] == 1:
                        imagen_negra[x][y]  = 0.5
                        x=x+1
                        imagen_negra[x][y] = 0.2
                        x=x-1
                        imagen_negra[x][y] = 0.5
                        print("Se movio hacia arriba")
                        m = m+1
    
    
    print("el numero de metros que recorio fue:", m)
            
            
            
#-----------------------------------------------------------------------------------------------------------------------------
#-----------------------------------------------------------------------------------------------------------------------------
#-----------------------------------------------------------------------------------------------------------------------------
#===>Este programa es un programa el cual evalua diferentes pistas y el mismo programa sin importar la pista que se le ingrese va a
#   seguir el camino hasta el momento en el que llegue al final de la pista y en ese momento nos dira la distancia recorrida.
#-----------------------------------------------------------------------------------------------------------------------------
#-----------------------------------------------------------------------------------------------------------------------------
#-----------------------------------------------------------------------------------------------------------------------------
#Ejecutable!
#Como usar este programa!
#===>Primero que nada si deseas ver el Catalogo disponible para elegir pistas solo escribe aca abajo <"Catalogo()"> Y te mostrara todas
#    las pistas que estan disponibles para usar.
#    """""ES IMPORTANTE BORRAR ESTE COMANDO SI SE VA A ULTILIZAR CUALQUIER OTRO COMANDO, PARA QUE NO OCURRAN FALLOS"""""
#===>Ahora para abrir la pista que deseas solo debes colocar abajo la pista que quieres; Ejemplo: "Pista2()" Hay hasta el momento 8
#    posibles pistas asi que los comandos son: <"Pista1()","Pista2()","Pista3()","Pista4","Pista5()","Pista6(), " Pista7()","Pista8()">
#===>Si solo colocas la pista que deseas vas a poder ver la pista con el camino en blanco que es lo que el "Corredor" debe reocrrer, para
#    hacer que el corredor inicie el recorrido y nos diga cuantos metros tiene la pista debemos colocar el comando <"Corredor(1, 1)">

#Diviertete!
#Coloca aca abajo tu ejecutable:

pista5()
Corredor(1, 0)

#-----------------------------------------------------------------------------------------------------------------------------
#-----------------------------------------------------------------------------------------------------------------------------
#-----------------------------------------------------------------------------------------------------------------------------

plt.imshow(imagen_negra,vmin=0,vmax=1)
plt.show
