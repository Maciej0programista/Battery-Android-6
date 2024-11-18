# Battery App

## Opis

Aplikacja Battery to prosta aplikacja na Androida 6, która monitoruje poziom naładowania baterii i powiadamia użytkownika, gdy poziom ten przekroczy 85%. Aplikacja odtwarza również 10-sekundową melodię za każdym razem, gdy poziom baterii wzrośnie powyżej 85%.

## Funkcje

* Monitorowanie poziomu baterii w czasie rzeczywistym.
* Wysyłanie powiadomień, gdy poziom baterii przekroczy 85%.
* Odtwarzanie 10-sekundowej melodii, gdy poziom baterii wzrośnie powyżej 85%.
* Wyłączanie powiadomień i melodii po odłączeniu urządzenia od ładowania.

## Wymagania

* Urządzenie z systemem Android 6.0 (API 23) lub nowszym.

## Instalacja

1. Pobierz plik APK aplikacji.
2. Zainstaluj aplikację na swoim urządzeniu.
3. Uruchom aplikację i przyznaj jej niezbędne uprawnienia.

## Użycie

Aplikacja działa w tle i automatycznie monitoruje poziom baterii. Gdy poziom baterii przekroczy 85%, otrzymasz powiadomienie i usłyszysz melodię. Aby wyłączyć powiadomienia i melodię, odłącz urządzenie od ładowania.

## Dodatkowe informacje

* Aplikacja korzysta z `BroadcastReceiver` do monitorowania poziomu baterii.
* Aplikacja korzysta z `MediaPlayer` do odtwarzania melodii.
* Aplikacja korzysta z `NotificationCompat.Builder` do tworzenia powiadomień.
* Aplikacja korzysta z usługi pierwszoplanowej, aby działać w tle.

## Znane problemy

* Aplikacja może nie działać poprawnie na urządzeniach z mocno zmodyfikowanym systemem Android.
* Aplikacja może zużywać więcej baterii niż inne aplikacje.

## Licencja

Aplikacja jest udostępniana na licencji MIT.

## Kontakt

Jeśli masz jakieś pytania lub sugestie, skontaktuj się ze mną pod adresem Bosyjjakub@gmail.com
