# Llenguatges més utilitzats actualment.

[Pàgina informació](https://stackify.com/popular-programming-languages-2018/)

## Java.

	El Java és un llenguatge de programació dissenyat el 1990 per James Gosling amb altres companys de Sun Microsystems a partir del llenguatge C. Des del seu naixement fou pensat com un llenguatge orientat a objectes.
    Exemple:
    public static void main(String[] args){
    	String str = holaMon();
        System.out.println(str);
    }
    public static String holaMon(){
    	return "Hola món!!";
    }
    
## C.
	El llenguatge de programació C o llenguatge C, va ser creat per Dennis Ritchie i Ken Thompson als Laboratoris Bell d'AT&T, a principis de la dècada dels 70. C està basat en un llenguatge que havia creat Ken Thompson anomenat llenguatge B el 1970. El llenguatge C es va crear per la necessitat de tenir-ne un que fos més flexible que l'assemblador a l'hora de programar, però que mantingués la característica de ser un llenguatge proper a la màquina.
    Exemple:
    const char * holaMon()
	{
    	return "Hola món!!";
	}
	int main() 
	{
    	const char* str = holaMon();
    	printf("%s", str);
	}
    
## Python.
	Python és un llenguatge de programació d'alt nivell i propòsit general molt utilitzat. Va ser creat per Guido van Rossum l'any 1991. La seva filosofia de disseny busca llegibilitat en el codi i la seva sintaxi permet als programadors expressar conceptes en menys línies de codi del que seria possible en llenguatges com C.
    Exemple:
    def holaMon():
    	print("Hola món!!")
	holaMon()

## C#.
	C# (llegit "sé xarp" per l'original anglès sharp, o bé "sé sostingut") és un llenguatge de programació orientat a objectes desenvolupat per Microsoft i estandarditzat, com a part de la seva plataforma .NET. La seva sintaxi bàsica deriva de C/C++ i utilitza el model d'objectes de la plataforma .NET el qual és similar al de Java però inclou millores derivades d'altres llenguatges.
    Exemple:
    static void Main(string[] args)
    {
    	var str = holaMon();
    }
    public String holaMon(){
    	return "Hola món";
    }

# Llenguatges orientats a servidors
## JSP.
	JavaServer Pages (JSP) és una tecnologia que permet als desenvolupadors de pàgines web, generar respostes dinàmicament a peticions HTTP. La tecnologia permet que codi Java i certes accions predefinides siguin incrustades en un context estàtic.
    Exemple:
    <%@ page language="java" contentType="text/html; charset=ISO-8859-1"
    pageEncoding="ISO-8859-1"%>
	<!DOCTYPE html>
	<html>
		<head>
			<meta http-equiv="Content-Type" content="text/html; charset=ISO-8859-1">
			<title>JSP</title>
            <% 
            	public String holaMon() {
                	return "Hola món!!";
                }
            %>
		</head>
		<body>
			<%= holaMon() %>
		</body>
	</html>

## PHP.
	PHP és un llenguatge de programació interpretat que s'utilitza per a generar pàgines web de forma dinàmica. S'executa al cantó del servidor, per aquest motiu al navegador web ja l'hi arriba la pàgina en format HTML, no podent visualitzar-ne el codi php.
    Exemple:
    <?php
		function holaMon() {
    		echo "Hola món!!";
		}
		holaMon();
	?>
# Llenguatges orientats a objectes
## JavaScript.
	JavaScript és un llenguatge script basat en objectes implementat originàriament per Netscape Communications Corporation, i que va derivar en l'estàndard ECMAScript.
    Exemple:
    <input type="date" id="data" />
    function getDate(){
    	return new Date();
    }
    document.getElementById("data").valueAsDate = getDate();