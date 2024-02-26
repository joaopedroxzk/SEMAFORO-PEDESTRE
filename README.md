# SEMAFORO-PEDESTRE

// C++ code // void setup() { pinMode(13, OUTPUT);//AMARELO 1 pinMode(11, OUTPUT);//VERDE 1 pinMode(12, OUTPUT);//VERMELHO 1 pinMode(8, OUTPUT);//VERDE 2 pinMode(9, OUTPUT);//AMARELO 2 pinMode(10, OUTPUT);//VERMELHO 2 pinMode(7, OUTPUT);//VERMELHO 1.1 pinMode(6, OUTPUT);//VERDE 1.1 pinMode(5, OUTPUT);//VERMELHO 2.1 pinMode(4, OUTPUT);//VERDE 2.1 }

void loop() { //SEMAFORO 1 digitalWrite(13, LOW);//AMARELO 1 digitalWrite(11, HIGH);//VERDE 1 digitalWrite(12, LOW);//VERMELHO 1 //SEMAFORO 2 digitalWrite(9, LOW);//AMARELO 2 digitalWrite(8, LOW);//VERDE 2 digitalWrite(10, HIGH);//VERMELHO 2 //PEDESTRE 1 digitalWrite(7, HIGH);//VERMELHO 1.1 digitalWrite(6, LOW);//VERDE 1.1 //PEDESTRE 2 digitalWrite(5, LOW);//VERMELHO 2.1 digitalWrite(4, HIGH);//VERDE 2.1 delay(3000);

//SEMAFORO 1 digitalWrite(13, HIGH);//AMARELO 1 digitalWrite(11, LOW);//VERDE 1 digitalWrite(12, LOW);//VERMELHO 1] //SEMAFORO 2 digitalWrite(9, LOW);//AMARELO 2 digitalWrite(8, LOW);//VERDE 2 digitalWrite(10, HIGH);//VERMELHO 2 //PEDESTRE 1 digitalWrite(7, HIGH);//VERMELHO 1.1 digitalWrite(6, LOW);//VERDE 1.1 //PEDESTRE 2 digitalWrite(5, LOW);//VERMELHO 2.1 digitalWrite(4, HIGH);//VERDE 2.1 delay(1500);

//SEMAFORO 1 digitalWrite(13, LOW);//AMARELO 1 digitalWrite(11, LOW);//VERDE 1 digitalWrite(12, HIGH);//VERMELHO 1 //SEMAFORO 2 digitalWrite(9, LOW);//AMARELO 2 digitalWrite(8, HIGH);//VERDE 2 digitalWrite(10, LOW);//VERMELHO 2 //PEDESTRE 1 digitalWrite(7, LOW);//VERMELHO 1.1 digitalWrite(6, HIGH);//VERDE 1.1 //PEDESTRE 2 digitalWrite(5, HIGH);//VERMELHO 2.1 digitalWrite(4, LOW);//VERDE 2.1 delay(3000);

//SEMAFORO 1 digitalWrite(13, LOW);//AMARELO 1 digitalWrite(11, LOW);//VERDE 1 digitalWrite(12, HIGH);//VERMELHO 1 //SEMAFORO 2 digitalWrite(9, HIGH);//AMARELO 2 digitalWrite(8, LOW);//VERDE 2 digitalWrite(10, LOW);//VERMELHO 2 //PEDESTRE 1 digitalWrite(7, LOW);//VERMELHO 1.1 digitalWrite(6, HIGH);//VERDE 1.1 //PEDESTRE 2 digitalWrite(5, HIGH);//VERMELHO 2.1 digitalWrite(4, LOW);//VERDE 2.1 delay(1500); }
