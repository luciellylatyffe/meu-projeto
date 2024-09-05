# meu-projeto
#incluir <ultrassônico.h>
#incluir <servo.h>
#incluir "notas_musicas.h"
#definir pinoverso 7
#definir trigonometria 2
#definir eco 3
#definir b1a 8
#definir b1b 9
#definir a1a 10
#definir a1b 11

inteirodistanciaD
inteirodistanciaE
inteiropino de campanhia =6;

flutuadordistancia0bstáculo =35;

ultrassônicouultrassônico(trig, eco);

servo servo;

vazio configurar() {
    serial.começar(9600);

    servo.anexar(pinoservo);
    //pinos da ponte h
    modo pin(b1a, saida);
    modo pin(b1b, saida);
    modo pin(a1a, saida);
    modo pin(a1b, saida);
    modo pin(buzzerpin, saida);

    servo.escrever(90);
    //radar();
    }

    vazio laço() {
    
    
