# AWS-


11.03:

✅ Co dzisiaj zrobiliśmy?
🔹 Stworzyliśmy DevContainer w VS Code

Użyliśmy Docker + Dev Containers, aby utworzyć izolowane środowisko do nauki DevOps.
Symulujemy tam środowisko, które pozwala na testowanie narzędzi bez konieczności instalowania ich na głównym systemie.
🔹 Skonfigurowaliśmy środowisko z GitLabem

Nie mogliśmy utworzyć konta na GitLabie, więc stworzyliśmy lokalną instancję GitLaba w kontenerze.
Dzięki temu możemy testować repozytoria, CI/CD i integrację bez konieczności używania zewnętrznej platformy.
🔹 Zaczęliśmy pracę z AWS

Zainstalowaliśmy AWS CLI w naszym DevContainerze.
Konfigurowaliśmy zmienne środowiskowe AWS (AWS_ACCESS_KEY_ID, AWS_SECRET_ACCESS_KEY, AWS_DEFAULT_REGION).
Próbowaliśmy wykonać pierwsze komendy AWS, ale musieliśmy poprawić instalację CLI.
🔹 Poprawiliśmy konfigurację Dockera

Docker nie był domyślnie instalowany w naszym DevContainerze, więc go doinstalowaliśmy.
Teraz Docker jest trwały i zawsze dostępny w naszym środowisku.
🔹 Pracowaliśmy z repozytorium na GitHub

Próbowaliśmy commitować i pushować zmiany.
Sprawdzaliśmy, jak zmieniać commit i jak zarządzać repozytorium.
🔹 Testowaliśmy zamykanie i ponowne uruchamianie środowiska

Dowiedzieliśmy się, jak zamknąć i ponownie otworzyć nasz DevContainer.
Sprawdzaliśmy, jak upewnić się, że Docker działa po restarcie.
