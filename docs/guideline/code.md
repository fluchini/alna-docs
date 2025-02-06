# Código

Podemos criar blocks de código para manter a formatação e os destaques de cores de cada fragmento de código.

### Criando Bloco de Código


#### Exemplo
```
    ``` java
    class Main
    {
        public static void main(String[] args)
        {
            System.out.println("My First Java Program.");
        }
    }
    ```
```

#### Resultado

``` java
class Main
{
    public static void main(String[] args)
    {
        System.out.println("My First Java Program.");
    }
}
```


### Adicionando Título e Linas

#### Exemplo

```
    ``` py title="bubble_sort.py" linenums="1"
    def bubble_sort(items):
        for i in range(len(items)):
            for j in range(len(items) - 1 - i):
                if items[j] > items[j + 1]:
                    items[j], items[j + 1] = items[j + 1], items[j]
    ```
```

#### Resultado

``` py title="bubble_sort.py" linenums="1"
def bubble_sort(items):
    for i in range(len(items)):
        for j in range(len(items) - 1 - i):
            if items[j] > items[j + 1]:
                items[j], items[j + 1] = items[j + 1], items[j]
```


### Grifando Linhas Específicas

#### Exemplo

```
    ``` py hl_lines="2 3"
    def bubble_sort(items):
        for i in range(len(items)):
            for j in range(len(items) - 1 - i):
                if items[j] > items[j + 1]:
                    items[j], items[j + 1] = items[j + 1], items[j]
    ```
```

#### Resultado

``` py linenums="1" hl_lines="2 3"
def bubble_sort(items):
    for i in range(len(items)):
        for j in range(len(items) - 1 - i):
            if items[j] > items[j + 1]:
                items[j], items[j + 1] = items[j + 1], items[j]
```


### Agrupando em Abas

#### Exemplo

```
    === "C"
    
        ``` c
        #include <stdio.h>
    
        int main(void) {
          printf("Hello world!\n");
          return 0;
        }
        ```
    
    === "C++"
    
        ``` c++
        #include <iostream>
    
        int main(void) {
          std::cout << "Hello world!" << std::endl;
          return 0;
        }
        ```
```

#### Resultado

=== "C"

    ``` c
    #include <stdio.h>

    int main(void) {
      printf("Hello world!\n");
      return 0;
    }
    ```
    
=== "C++"

    ``` c++
    #include <iostream>

    int main(void) {
      std::cout << "Hello world!" << std::endl;
      return 0;
    }
    ```
