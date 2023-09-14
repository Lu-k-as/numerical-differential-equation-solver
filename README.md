# Numerischer Differentialgleichungslöser

## Beschreibung
Die Lösung von Differentialgleichungen ist ein zentrales Thema in der Mathematik. Gewöhnliche Differentialgleichungen beschreiben die Beziehung zwischen einer unbekannten Funktion und ihren Ableitungen. 
Oftmals sind Randwertprobleme von Interesse, bei denen die Lösung der Differentialgleichung an bestimmten Punkten oder mit bestimmten Randbedingungen gesucht wird.

Die analytische Lösung von ODEs ist jedoch nicht immer möglich oder praktikabel. In solchen Fällen bietet die numerische Lösung eine wertvolle Alternative. 
Die numerische Lösungsmethode basiert auf der Approximation der unbekannten Funktion durch eine diskrete Menge von Werten. 
Für Randwertprobleme müssen zusätzlich zu den Differentialgleichungen auch Randbedingungen definiert werden. Diese Randbedingungen können den Wert der Funktion oder ihrer Ableitungen an bestimmten Punkten festlegen. 

## Anwendungsmöglichkeit

In der folgenden Arbeit werden skalare Randwertprobleme für gewöhnliche Differentialgleichungen zweiter Ordnung numerisch gelöst. Folgendes Problem wird hier behandelt:

$$\frac{d^2}{dt^2}y(t) = a(t) y(t) + b(t)$$

Die Randwerte für die gewöhnliche Differentialgleichung werden wie folgt angegeben:

$$y(a) = \alpha, y(b) = \beta$$
