##  Modificadores de Acesso
  - private : Acesso somente dentro da própria classe;
  - package : No mesmo pacote;
  - protected : somente por Subclasses;
  - public : pode ser acessado em qualquer lugar;

## Herança



 >Em Java se faz o uso da palavra reservada **extends** para representar uma herança entre os objetos.

~~~Java
public class Chicken {
    public int penas;
    public void getSownd(){
        System.out.println("Po Po");
    }
}


public class Chick extends Chicken{

}

~~~

Agora ao tentar instaciar o Chick, teremos através dele os métodos e atributos da Classe pai/mãe.
