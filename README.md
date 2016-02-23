# hello-word
just another repository
Module Module1

    Sub Main ()

        'ArgumentException não é lançada em DivideByTwo porque 10 é 
        "um número par. 
        Console.WriteLine ( "10 dividido por 2 é {0}" , DivideByTwo (10))
         Experimente 
            'ArgumentException é lançada em DivideByTwo porque 7 é 
            'não é um número par . 
            Console.WriteLine ( "7 dividido por 2 é {0}" , DivideByTwo (7))
         Pegar Argex Como ArgumentException
             'Diga ao usuário que for encontrado algum problema. 
            Console.WriteLine ( "7 não pode ser igualmente dividido por 2." )
            Console.WriteLine ( "Mensagem de exceção:" & argEx.Message)
         End  Try 
        'Descomente a próxima instrução para ver o que acontece se você chama de 
        'DivideByTwo diretamente. 
        "Console.WriteLine (DivideByTwo (7))

    End  Sub

    Função DivideByTwo ( ByVal num Como  Integer ) Como  Integer

        "Se num é um número ímpar, jogar um ArgumentException. A 
        "classe ArgumentException fornece um número de construtores 
        ", que você pode escolher. 
        Se num Mod 2 = 1 Em seguida, 
            jogue  New ArgumentException ( "Argumento para num deve ser" & _
                 "um número par." )
         End  Se

        'Valor de num é mesmo, então devolver metade do seu valor. 
        Retornar num / 2

    End  Function

End  Module

