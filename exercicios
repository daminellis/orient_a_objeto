exercicio 1

#Escreva um metodo para a classe ContaCorrente() vista em aula, que permita a transferencia de valores entre duas contas (objetos).
#Esse metodo devera receber como parametro: valor, origem e destino.

class ContaCorrente:
    def __init__ (self, saldo_origem, saldo_destino):
        self.saldo_origem = saldo_origem
        self.saldo_destino = saldo_destino
    
    def transferir(self, valor):
        if self.saldo_origem >= valor:
            self.saldo_origem -= valor
            self.saldo_destino += valor
            print("Transferência realizada com sucesso!")
        else:
            print("Saldo insuficiente para realizar a transferência.")
    
    def mostrar_saldos(self):
        print(f"Saldo na conta de origem: {self.saldo_origem}")
        print(f"Saldo na conta de destino: {self.saldo_destino}")

# Obtendo valores iniciais das contas do usuário
saldo_origem = float(input("Digite o saldo da conta de origem: "))
saldo_destino = float(input("Digite o saldo da conta de destino: "))

# Criando instância da classe ContaCorrente
conta = ContaCorrente(saldo_origem, saldo_destino)

# Solicitando o valor da transferência e realizando-a
valor_transferencia = float(input("Digite o valor a ser transferido: "))
conta.transferir(valor_transferencia)

# Mostrando saldos após a transferência
conta.mostrar_saldos()
=================================================================================================================================================
=================================================================================================================================================
exercicio 2

# Crie uma classe chamada Aluno() com os seguintes atributos:Nome Idade Nota 1 Nota 2
# Crie os seguintes métodos: Calcula média, retornando a média aritmética entre as notas.
# Mostra dados, que somente imprime o valor de todos os atributos.
# Resultado, que verifica se o aluno está aprovado ou reprovado (se a média for maior ou igual a 6.0, o aluno está aprovado).
# Crie dois objetos (aluno1 e aluno2) e teste todos os métodos.

class Aluno:
    def __init__(self, nome, idade, nota1, nota2):
        self.nome = nome
        self.idade = idade
        self.nota1 = nota1
        self.nota2 = nota2
    
    def calcula_media(self):
        return (self.nota1 + self.nota2) / 2
    
    def mostra_dados(self):
        print("Dados do Aluno:")
        print(f"Nome: {self.nome}")
        print(f"Idade: {self.idade}")
        print(f"Nota 1: {self.nota1}")
        print(f"Nota 2: {self.nota2}")
    
    def resultado(self):
        media = self.calcula_media()
        if media >= 6.0:
            return "Aprovado"
        else:
            return "Reprovado"


aluno1 = Aluno(nome="João", idade=18, nota1=7.5, nota2=8.0)
aluno2 = Aluno(nome="Maria", idade=19, nota1=5.0, nota2=6.5)

aluno1.mostra_dados()
print(f"Média: {aluno1.calcula_media()}")
print(f"Resultado: {aluno1.resultado()}")

print("\n")

aluno2.mostra_dados()
print(f"Média: {aluno2.calcula_media()}")
print(f"Resultado: {aluno2.resultado()}")

=================================================================================================================================================
=================================================================================================================================================
import java.util.ArrayList;
import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

        ArrayList<Integer> gab = new ArrayList<>();
        System.out.println("Digite as respostas da aposta (5 numeros):");
        for (int i = 0; i < 5; i++) {
            gab.add(scanner.nextInt());
        }

        ArrayList<Integer> aposta = new ArrayList<>();
        System.out.println("Digite os numeros em que deseja apostar (10 numeros):");
        for (int i = 0; i < 10; i++) {
            aposta.add(scanner.nextInt());
        }

        int pontos = calcPontos(gab, aposta);

        System.out.println("Pontuação do apostador: " + pontos);

        scanner.close();
    }

    public static int calcPontos(ArrayList<Integer> gab, ArrayList<Integer> aposta) {
        int pontos = 0;
        for (Integer numeroAposta : aposta) {
            if (gab.contains(numeroAposta)) {
                pontos++;
            }
        }
        return pontos;
    }
}
=================================================================================================================================================
=================================================================================================================================================
import java.util.ArrayList;
import java.util.Scanner;

public class Main {
    public static void main(String[] args) {

        Scanner scanner = new Scanner(System.in);

        ArrayList<Integer> vetorD = new ArrayList<>();

        for (int i = 0; i < 10; i++) {
            System.out.print("Digite o valor desejado : ");
            int valor = scanner.nextInt();
            vetorD.add(valor);
        }
        
        scanner.close();

        for (int i = vetorD.size() - 1; i >= 0; i--) {
            if (vetorD.get(i) <= 0) {
                vetorD.remove(i);
            }
        }

        System.out.print("Vetor D: ");
        for (int i = 0; i < vetorD.size(); i++) {
            System.out.print(vetorD.get(i));
            if (i < vetorD.size() - 1) {
                System.out.print(" ");
            }
        }
    }
}

=================================================================================================================================================
=================================================================================================================================================

import java.util.ArrayList;
import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        int tamanho = 5;

        ArrayList<Integer> vetorA = new ArrayList<>();
        ArrayList<Integer> vetorB = new ArrayList<>();

        for (int i = 0; i < tamanho; i++) {
            System.out.print("Digite o número inteiro: ");
            int numero = scanner.nextInt();
            vetorA.add(numero);
        }

        for (int i = tamanho - 1; i >= 0; i--) {
            vetorB.add(vetorA.get(i));
        }

        System.out.println("Elementos do vetor A:");
        for (int numero : vetorA) {
            System.out.println(numero);
        }

        System.out.println("Elementos do vetor B (invertidos):");
        for (int numero : vetorB) {
            System.out.println(numero);
        }
    }
}
=================================================================================================================================================
=================================================================================================================================================

import java.util.ArrayList;
import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

        ArrayList<String> nomes = new ArrayList<>();
        ArrayList<Double> medias = new ArrayList<>();

        for (int i = 0; i < 7; i++) {
            System.out.print("Digite o nome do aluno " + (i + 1) + ": ");
            String nome = scanner.nextLine();
            nomes.add(nome);

            System.out.print("Digite a média final de " + nome + ": ");
            double media = scanner.nextDouble();
            scanner.nextLine(); // Consumir a quebra de linha
            medias.add(media);
        }

        int indiceMaiorMedia = 0;
        double maiorMedia = medias.get(0);
        for (int i = 1; i < medias.size(); i++) {
            if (medias.get(i) > maiorMedia) {
                maiorMedia = medias.get(i);
                indiceMaiorMedia = i;
            }
        }

        System.out.println("O aluno com a maior média é: " + nomes.get(indiceMaiorMedia));

        System.out.println("Alunos que precisam fazer exame final:");
        for (int i = 0; i < 7; i++) {
            double media = medias.get(i);
            if (media < 7) {
        
double notaExame = 5 - (0.6 * media); // Fórmula para calcular a nota necessária no exame
                System.out.println(nomes.get(i) + " precisa tirar " + notaExame + " no exame final.");
            }
        }

        scanner.close();
    }
}

=================================================================================================================================================
=================================================================================================================================================

import java.util.ArrayList;
import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        ArrayList<Integer> lista = new ArrayList<>();

        for (int i = 0; i < 20; i++) {
            System.out.print("Digite o valor para a posição " + (i + 1) + ": ");
            int valor = sc.nextInt();
            lista.add(valor);
        }

        int maiorValor = lista.get(0);
        int menorValor = lista.get(0);
        int posicaoMaior = 0;
        int posicaoMenor = 0;

        for (int i = 1; i < lista.size(); i++) {
            int valorAtual = lista.get(i);
            if (valorAtual > maiorValor) {
                maiorValor = valorAtual;
                posicaoMaior = i;
            }
            if (valorAtual < menorValor) {
                menorValor = valorAtual;
                posicaoMenor = i;
            }
        }

=================================================================================================================================================
=================================================================================================================================================

=================================================================================================================================================
=================================================================================================================================================

=================================================================================================================================================
=================================================================================================================================================

=================================================================================================================================================
=================================================================================================================================================

=================================================================================================================================================
=================================================================================================================================================

=================================================================================================================================================
=================================================================================================================================================

=================================================================================================================================================
=================================================================================================================================================

=================================================================================================================================================
=================================================================================================================================================

=================================================================================================================================================
=================================================================================================================================================

=================================================================================================================================================
=================================================================================================================================================


