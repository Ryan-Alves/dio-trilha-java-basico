O arquivo se encontra comprimido, com suas respectivas pastas.

Segue o código do programa em texto:

package dio.java_basico.conta_banco;
import java.util.Scanner;

public class ContaTerminal {
	
	public static void main(String args[]) {
		
		
		String nomeCliente;
		String agencia;
		int numeroDaConta;
		float saldo;
		
		System.out.println("----------------------------------------------------------------------------------\n");
		System.out.println("Digite o seu nome: \n");
		Scanner sc = new Scanner(System.in);
		nomeCliente= sc.next();
		System.out.println("\nAgora, digite a sua agência: \n");
		agencia = sc.next();
		System.out.println("\nDigite o número da conta: \n");
		numeroDaConta = sc.nextInt();
		System.out.println("\nAgora, digite o valor a ser depositado: \n");
		saldo = sc.nextFloat();
		System.out.println("----------------------------------------------------------------------------------\n");
		
		System.out.println("Olá " + nomeCliente + ", obrigado por criar uma conta em nosso banco, sua agência é " + agencia+ ", conta " + numeroDaConta + ", e seu saldo (" + saldo + ") já está disponível para saque");

		
		
	}
}
