# VGA Tester

Program do testowania monitora VGA.
Bazą do testów jest płytka Nucleo z procesorem STM32L476RG.
 
##11.03.2026

Do generowania sygnałów synchronizacji wykorzystano Timer 1 i Timer 2.
Obraz generowany jest z użyciem SPI1 i DMA.
Sygnały R, G i B połączono razem co powoduje wyświetlanie jedyni ekoloru białego. Do testów w zupełności to wystarczy.