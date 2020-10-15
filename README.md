# FOLD STRUC MatrizPontos
### Cabecalho Pick

{IndexacaoHorizontal} FALSE-> Vertical / TRUE -> Horizontal

```c++
bool IndexacaoHorizontal = false;
```
{NumCaixas} numero de caixas para o pick (1,2,3,4,5...)

```c++
int NumCaixas = 4;
```

{ConfGarraOp} Opcao de abertura da garra (1,2,3,4,5...)

```c++
int ConfGarraOp = 0;
```

{PickOp} Opcao de pick na esteira (1,2,3,4,5...)

```c++
int PickOp = 1;
```

{FechaGarraOp} Opcao de abertura da garra (1,2,3,4,5...)

```c++
int FechaGarraOp = 1;
```

### Cabecalho Place

{AbreGarraOp} Opcao de abertura da garra (1,2,3,4,5...)

```c++
int AbreGarraOp = 1;
```

{SkipGoHome} Quando TRUE indica que deve fazer outro place antes de ir para a posicao de pick

```c++
bool SkipGoHome = false;
```

{SkipSobeRelativo} Quando TRUE indica que nao deve subir relativo para cima depois do place

```c++
bool SkipSobeRelativo = false;
```

### Cabecalho Pontos

{XApp1Place} Primeiro ponto de aproximacao de place

```c++
bool XApp1Place;
```

{XApp2Place} Segundo ponto de aproximacao de place

```c++
E6POS XApp2Place;
```

{XPlace} Ponto de place

```c++
E6POS XPlace;
```

## Criar Struct 

MatrizPontos[MOZAICOS,PONTOS]

```c++
const int MaxMatrizI = 8
const int MaxMatrizJ = 15  
DECL GLOBAL Matriz MatrizPontos[8,15];
```

# ENDFOLD