Opis aplikacji:
W głównym oknie są listy z aktywami, inwestorami i funduszami.
Po wcisnięciu "dodaj obiekt" w nowym oknie wybiera się z checkboxa jaki obiekt chce się dodać i wypełnia się pola, albo są one same losowane. Kolejne "dodaj obiekt" tworzy obiekt (jeżeli ma wątek, to go uruchamia). 
Aby zobaczyć obiekty w oknie głównym, trzeba użyć odświeżania. "Odśwież aktywa" odświeża również rynki wyświetlane nad listami aktywów, przy czym w programie działa tylko 1 rynek każdego typu, można ich tworzyć więcej, ale "aktywny" jest zawsze pierwszy z listy. Wciśnięcie "Odśwież aktywa" tworzy również inwestorów i fundusze proporcjonalnie do liczby aktywów na rynku i uruchamia ich wątki.
"Odśwież inwestorów" tylko odświeża listy inwestorów i funduszy.
Po wybraniu aktywa na liście, na dole wyświetlą się informacje o nim. Po zaznaczeniu spółki można pod listą spółek wpisać kwotę, za którą wybrana spółka ma odkupić swoje akcje.
Po wybraniu inwestora/funduszu po prawej wyświetlą się informacje o jednym z nich, wraz z listą posiadanych aktywów.
Przycisk "Stop" zatrzymuje działanie wątków (do serializacji), ale nie od razu. Po wciśnięciu należy poczekać (co najmniej 10 sekund), żeby mieć pewność, że wsyztskie wątki przestały działać.
Przycisk "zapisz" dokonuje zapisu-serializacji, "wczytaj" powinien dokonywać odczytu-serializacji, ale działa tylko "częściowo" i wyskakują błędy.

Działania spółek/inwestorów/funduszy wyświetlają się w konsoli.
