# Opencart Inpost - moduł obsługi paczkomatów Inpost
Przedstawiam Państwu mój autorski moduł wysyłki Inpost - paczkomaty do Opencarta w wersji 3.0. Moduł można wykorzystywać w celach komercyjnych.

# Wsparcie
Moduł Opencart Inpost został udostępniony za darmo, dlatego prosimy wszystkich jego użytkowników o dobrowolne finansowe wsparcie autora. Dzięki waszym datkom będę w stanie dalej rozwijać ten i pozostałe darmowe moduły do Opencarta.

Wesprzyj rozwój tego oprogramowania - https://paypal.me/pools/c/8p6PzJtLZ3

# Instalacja
Pobierz paczkę zip do Twojej wersji opencarta i zainstaluj ją korzystając z instalatora wbudowanego w Opencart

# Możliwe problemy
Jeżeli po instalacji, brakuje opisów, skopiuj pliki tłumaczenia language/pl-PL/extension/shipping do właściwego katalogu w Twoim sklepie.

Znalazłeś(aś) błąd ? Zgłoś go: https://github.com/avatec/opencart-inpost/issues

# Modyfikacje podstawowej wersji plików
1. catalog/controller/checkout/checkout.php
   Dodano kod ładowania pliku inpost.js zaraz pod function index()

# Funkcje
1. Możliwość zdefiniowania wyświetlania listy radio buttonów według podanej wcześniej miejscowości
2. Możliwość wyboru z mapy na podstawie geolokalizacji (witryna musi posiadać certyfikat SSL i być wywołana poprzez https)
