main
    int numeroSecreto = random(1, 101)  // 10
    int intentos = 7, numJugador
    bool adivinado = FALSE

    Mientras que intentos > 0 && !adivinado
        mostrar "bienvenida"
        mostrar "ingresa un número"
        leer numeroSecreto  // 50
        Si (numJugador < numeroSecreto)
            --intentos
            mostrar "Demasiado Bajo"
        FinSi
    FinMientras
    --intentos

finMain
