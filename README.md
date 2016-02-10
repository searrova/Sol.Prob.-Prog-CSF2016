# Sol.Prob.-Prog-CSF2016

void setup (){
  size(600,600);
  }
  void draw(){
    background(500); //Esto nos borra los circulos o cuadrados que estaban
    
    if (mouseX<300 && mouseY<300){
  ellipse(150,150,50,50);  //Genera un circulo en el primer cuadrante
    }
      else{
    if (mouseX>300 && mouseY>300){
       ellipse(450,450,50,50) ; }//Genera un circulo en el cuarto cuadrante
    else{
     if (mouseX<300 && mouseY<300){
      rect(450,150,50,50) ;} //Genera un rectangulo en el tercer cuadrante
      else{
    if (mouseX<300 && mouseY>300){
     rect(150,450,50,50);}//Genera un rectangulo en el cuarto cuadrante
       }
      }
    }
  }
  
