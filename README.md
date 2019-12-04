# calcular_horas_minutos_segundo
Calcular horas, minutos y segundos
package tiempoSegundos;

public class tiempoSegundos {

	public static void main(String[] args) {
		int t = 6002, segundos, minutos, horas;
		
		horas = (t / 3600);
	    minutos = ((t-horas*3600)/60);
	    segundos = t-(horas*3600+minutos*60);
		System.out.println(+t+ " segundos son: " +horas+ "horas, " +minutos+ "minutos y " +segundos+ " segundos.");
	}

}
