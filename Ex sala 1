package main

import (
	"bufio"
	"fmt"
	"os"
)

func main() {
	scanner := bufio.NewScanner(os.Stdin)
	fmt.Print("Digite uma frase: ")
	scanner.Scan()
	Frase1 := scanner.Text()

	fmt.Print("Digite outra frase: ")
	scanner.Scan()
	Frase2 := scanner.Text()

	s1 := Frase1 + " " + Frase2

	fmt.Print("A junção das frase é: ", s1)
}
