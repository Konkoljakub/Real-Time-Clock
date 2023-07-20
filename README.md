# Real-Time-Clock VERILOG

Zaprojektowano i wykonano układ zegara czasu rzeczywistego, wyświetlającego czas w postaci : HH.MM. Kropka  miga z częstotliwością 1 Hz.

Przycisk BTNL - ustawianie godzin.
Przycisk BTNR - ustawianie minut.
Przycisk BTNU - przycisk testowy, powodujący przyspieszone (np. 1000 razy) działanie zegara w celu sprawdzenia działania zegara.
Przycisk BTNC - reset asynchroniczny.
Uwaga: Układ zabezpieczono przed drganiami przycisków (nie dotyczy resetu)! Założono, że po naciśnięciu przycisku, styki przycisku mogą drgać przez czas do 50 ms.

Napisano testbench.
Przed implementacją wykonano symulację układu z wykorzystaniem pliku testbench.

Płytka Digilent Nexys A7, układ Artix-7 XC7A100T-1CSG324C (obudowa: CSG324, speed grade:-1)
