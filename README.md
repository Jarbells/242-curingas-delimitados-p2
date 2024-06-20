## Curingas delimitados / bounded wildcards.  
### Copiando de uma lista para outra.  
### public static void copy(List<? extends Number> source, List<? super Number> destiny) {
		for (Number number : source) {
			destiny.add(number);
		}
	}
