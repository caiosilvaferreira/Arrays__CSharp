# Arrays

```csharp
/*
                            Arrays
      var meuArray = new int[5] { 25,26,28,27,29}; // aqui conseguimos decidir os valores de cada array

            Console.WriteLine(meuArray[0]);
            Console.WriteLine(meuArray[1]);
            Console.WriteLine(meuArray[2]);
            Console.WriteLine(meuArray[3]);
            Console.WriteLine(meuArray[4]);
    
                Laço de repeticao para percorrer todo o array e mostrar o resultado na tela

    var meuArray = new int[5] { 25, 26, 28, 27, 29 }; 

            Console.WriteLine(meuArray.Length);
            for (var index = 0; index <meuArray.Length;index++) {

                Console.WriteLine(meuArray[index]);
            }
      lenght faz a contagem do resultado, por exemplo ele contou que temos 5 arrays e cada um tem valores. depois quando o index vai fazendo o calculo no for, ele automaticamente faz a impressao na condicao e mostra na tela o resultado de todos os arrays com o laço de repeticao

    
            var meuArray = new int[5] { 25, 26, 28, 27, 29 }; 

            USANDO O FOREACH COM ARRAYS METODO UM POUCO MELHOR QUE O FOR

            foreach (var item in meuArray ) { // em diferença com o for normal, o foreach deixa o codigo menor e faz com que a variavel item percorra todo os arrays do meuArray

                Console.WriteLine(item);
                
            }
            // nesse caso e muito melhor usar o foreach 
        }

     var funcionarios = new Funcionario[5];
    funcionarios[0] = new Funcionario() { Id = 2579, nome = "caio"};

            foreach (var funcionario in funcionarios ) { aqui ele vai percorrer todos os 5 arrays ele vai mostrar o id, nome, o restante do resultado deu 0 pois nao tem valor

                Console.WriteLine(funcionario.Id);
                Console.WriteLine(funcionario.nome);
            }
            
        }

        public struct Funcionario {     aqui usando uma struct para se comunicar
    public int Id { get; set; }

    public string nome { get; set; }
}
    */
```
