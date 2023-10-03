
Conversa aberta. Uma mensagem lida.

Pular para o conteúdo
Como usar o Gmail com leitores de tela
in:sent 
5 de 20
matheus augusto daminelli e joao carlos rodrigues martins

Matheus Augusto daminelli <matheus.daminelli@gmail.com>
seg., 18 de set., 22:45
para christine.vieira

import java.util.ArrayList;
import java.util.Scanner;

    public class desafioArray {
        public static void main(String[] args) {
            Scanner scanner = new Scanner(System.in);
            ArrayList<String> lista = new ArrayList<>();

            while (true) {
                System.out.println("1 - Inserir numero");
                System.out.println("2 - Pesquisar por posição");
                System.out.println("3 - Excluir");
                System.out.println("4 - Imprimir lista");
                System.out.println("0 - Encerrar programa");
                System.out.println("Selecione uma das opções:");

                int op = scanner.nextInt();

                switch (op) {
                    case 1:
                        menuInserir(lista, scanner);
                        break;
                    case 2:
                        System.out.print("Digite a posição que deseja pesquisar: ");
                        int posicao = scanner.nextInt();
                        if (posicao >= 0 && posicao < lista.size()) {
                            System.out.println("Elemento na posição " + posicao + ": " + lista.get(posicao));
                        } else {
                            System.out.println("Posição inválida.");
                        }
                        break;
                    case 3:
                        menuExcluir(lista, scanner);
                        break;
                    case 4:
                        System.out.println("Lista dos numeros completa:");
                        for (String item : lista) {
                            System.out.println(item);
                        }
                        break;
                    case 0:
                        System.out.println("Encerrando o programa.");
                        scanner.close();
                        System.exit(0);
                    default:
                        System.out.println("Opção inválida, tente novamente.");
                        break;
                }
            }
        }

        private static void menuInserir(ArrayList<String> lista, Scanner scanner) {
            System.out.println("Selecione uma opção de inserção:");
            System.out.println("1 - Inserir na ultima posição");
            System.out.println("2 - Inserir em uma posição específica");

            int opcaoInserir = scanner.nextInt();

            switch (opcaoInserir) {
                case 1:
                    System.out.print("Digite o elemento a ser inserido na ultima posição: ");
                    String elementoUltimaPosicao = scanner.next();
                    lista.add(elementoUltimaPosicao);
                    System.out.println("Elemento inserido na ultima posição.");
                    break;
                case 2:
                    System.out.print("Digite o elemento a ser inserido: ");
                    String elementoInserir = scanner.next();
                    System.out.print("Digite a posição desejadad de inserção: ");
                    int posicaoInserir = scanner.nextInt();

                    if (posicaoInserir >= 0 && posicaoInserir <= lista.size()) {
                        lista.add(posicaoInserir, elementoInserir);
                        System.out.println("Elemento inserido na posição " + posicaoInserir + ".");
                    } else {
                        System.out.println("Posição inválida. Elemento não inserido.");
                    }
                    break;
                default:
                    System.out.println("Opção de inserção inválida. Tente novamente.");
                    break;
            }
        }

        private static void menuExcluir(ArrayList<String> lista, Scanner scanner) {
            System.out.println("Selecione uma opção de exclusão:");
            System.out.println("1 - Excluir por elemento");
            System.out.println("2 - Excluir por posição");

            int opExcluir = scanner.nextInt();

            switch (opExcluir) {
                case 1:
                    System.out.print("Digite o elemento a ser excluído: ");
                    String elementoExcluir = scanner.next();
                    if (lista.remove(elementoExcluir)) {
                        System.out.println("Elemento removido.");
                    } else {
                        System.out.println("Elemento não encontrado na lista.");
                    }
                    break;
                case 2:
                    System.out.print("Digite a posição a ser excluída, começando do 0: ");
                    int posicaoExcluir = scanner.nextInt();
                    if (posicaoExcluir >= 0 && posicaoExcluir < lista.size()) {
                        lista.remove(posicaoExcluir);
                        System.out.println("Elemento na posição " + posicaoExcluir + " removido.");
                    } else {
                        System.out.println("Posição inválida.");
                    }
                    break;
                default:
                    System.out.println("Opção de exclusão inválida. Tente novamente.");
                    break;
=====================================================================================================================================
=====================================================================================================================================
exer 2


=====================================================================================================================================
=====================================================================================================================================

=====================================================================================================================================
=====================================================================================================================================

=====================================================================================================================================
=====================================================================================================================================

=====================================================================================================================================
=====================================================================================================================================

=====================================================================================================================================
=====================================================================================================================================

=====================================================================================================================================
=====================================================================================================================================

=====================================================================================================================================
=====================================================================================================================================



