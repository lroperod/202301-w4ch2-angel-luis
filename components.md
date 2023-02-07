## Listado de componentes:

- Used letters
- Hangman
- Guessed letters
- Result
- Letters
- App

  1.**Used** **Letters**: este componente siempre guarda las letras que hemos usado durante una partida del juego, se define como un array que almacena los elementos usados. En este caso, las letras que recibe del componente . Las letras almacenadas se desactiven del array de letras inicial y comparando con el componente letras adivinadas

Mecánica del Algoritmo:

2. **Hangman:** Muestra de manera visual nuestro estado en el juego. Si no aciertas las letras la figura se va completando. Este componente se compara con el componente de **Guessed Letters** y si no son iguales se completa una porción de la figura. A su vez cuando se complete la figura debe mostrar que has muerto en **Result.**

3. **Guessed letters:** Almacena las letras que hemos adivinado. Recibe de **Letters** y las compara , si son correctas mediante un Used State.

4. **Result:** Muestra el resultado final si has llegado a completarlo y solo muestras dos valores _“You win”_ o _“You ´re dead”_ y se compara con **Guessed Letters** y **Hangman.**

5. **Letters:** Nos muestra las letras que tenemos disponibles para completar nuestro juego. Activa como input y las almacena en el array Guessed Letter, cuando están seleccionas y son correctas. Las letras que están almacenadas en **Used Letters** se desactivan del **Letters.**

6. **App:** Empaqueta todos los componentes. Renderiza todos los componentes.
