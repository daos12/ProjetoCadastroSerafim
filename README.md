
package pessoaprojeto;


public class PessoaProjeto {

    
private String nome;
private int idade;
private String  cpf;

public void dados (){
    System.out.println("nome:" + getnome());
    System.out.println("cpf:" + getcpf());
    System.out.println("idade:" + getidade ());
}
public Pessoa(String nome, int idade, String cpf){
        this.nome = nome;
        this.idade = idade;
        this.cpf = cpf;
}
public String getnome (){
    return nome;
}

public void setnome (String nome) {
    this.nome = nome;

}


public int getidade (){
    return idade;
    
}

public void setidade (int idade){
    if(idade > 18){
    this.idade = idade;
}else{
        System.out.println(" Menor idade");
    }
    }
    
public String getcpf (){
    return cpf;
}
public void setcpf (String cpf){
    this.cpf = cpf;
}
}


