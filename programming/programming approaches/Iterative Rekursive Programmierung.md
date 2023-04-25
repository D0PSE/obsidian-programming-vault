#iterative #rekursive #approaches 

# Iterativ
Umsetzung mit **Schleife**

```ad-info
title: Erweiterte Info
collapse: closed

Eine iterative Lösung verwendet eine Schleife, um eine Aufgabe wiederholt auszuführen, bis ein bestimmtes Ziel erreicht ist.
```


Iteratives berechnen der [[Fakultät]] einer Zahl
```java
public static int factorialIterative(int n) {
	int result = 1;
	for (int i = 2; i <= n; i++) {
		result *= i;
	}
	return result;
}
```


# Rekursiv
Umsetzung mit **Selbstaufruf**

```ad-info
title: Erweiterte Info
collapse: closed

Eine rekursive Lösung basiert auf der Idee, dass ein Problem in kleinere, ähnlichere Teilprobleme unterteilt werden kann, die dann rekursiv gelöst werden können.

Das bedeutet, dass eine Funktion sich selbst aufruft, um ein Problem zu lösen, bis eine Abbruchbedingung erfüllt ist.
```


Rekursives berechnen der [[Fakultät]] einer Zahl
```java
public static int factorialRecursive(int n) {
	if (n == 0) {
		return 1;
	} else {
		return n * factorialRecursive(n-1);
	}
}
```
