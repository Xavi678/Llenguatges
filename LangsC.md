# LLENGUATGES DE PROGRAMACIÓ

Els 10 llenguatges de programació més utilitzats són:

+ JAVA
+ PYTHON
+ JAVASCRIPT
+ C++
+ C#
+ PHP
+ PERL
+ SWIFT
+ R
+ RUST

 El c és un llenguatge molt utilitzat actualment, creat l'any 1972 que s'utilitzava per crear Sistemes Operatius.
 - Codi d'exemple:

    int main() {
        int num1=2;
        int num3=2;
        int res=0;
        res=num1+num3;

        printf("El Resultat és: %d",res);


    }

  El Javascript és un llenguatge que s'utilitza per la creació de pàgines webs, va néixer l'any 1995 per tal d'utilitzar com a eina per crear aplicacions web dinàmiques.
- Codi d'exemple
  <!DOCTYPE html>
<html>
<body>

<h2>Dona la data actual</h2>

<button type="button"
onclick="document.getElementById('demo').innerHTML = Date()">
Clica per obtenir la data actual</button>

<p id="demo"></p>

</body>
</html>

El JAVA és el llenguatge de programació més important actualment i dels més utilitzats, va sorgir l'any 1996, com una einada usada en un projecte de programació.
- Codi d'exemple
-public class Factorial {

	public static void main(String[] args) {
		Scanner entrada=new Scanner(System.in);

		System.out.print("Indica el numero a calcular su factorial ");

		int valorCalcular=0;

		// bucle mientras valorCacular es inferior a 1
		while(valorCalcular<1) {
			try {
				// Solicitamos un entero
				valorCalcular=entrada.nextInt();

				// Indicamos que es incorrecto si el valor es inferior a1
				if(valorCalcular<1)
					System.out.println("El valor tiene que ser superior a 0");
			}catch(InputMismatchException e) {
				// Controlamos que siempre introduzca un valor numerico
				System.out.println("El valor tiene que ser numerico...");
				entrada.nextLine();
			}
		}

		long factorial=1L;
		for(int i=valorCalcular;i>0;i--) {
			factorial=factorial*i;
		}

		System.out.println("El factorial de " + valorCalcular + " es " + factorial);
	}

}

- Llenguatges de Programació Orientat a Objectes
  1. JAVA
  2. C++
  3. C#
  4. PYTHON
  5. OBJECTIVE-C
- Llenguatges de Programació Orientats a Servidors
  1. ASP .NET
  2. PHP
  3. JavaScript
  4. RUBY
  5. JSP
