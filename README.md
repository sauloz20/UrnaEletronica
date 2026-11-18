# Simulador de Urna Eletrônica

![JavaScript](https://img.shields.io/badge/linguagem-JavaScript-blue)

Simulador educacional de votação e apuração executado no navegador. O projeto demonstra a digitação de números, correção, voto em branco, confirmação e exibição dos resultados.

## Tecnologias e requisitos

HTML, CSS e JavaScript em uma página, com Tailwind CSS e fontes carregadas de serviços externos. Use um navegador moderno e conexão à internet para esses recursos.

## Executar localmente

Com Git e Python 3 instalados:

```sh
git clone https://github.com/sauloz20/UrnaEletronica.git
cd UrnaEletronica
python -m http.server 8000
```

Abra `http://localhost:8000/`. A pasta também pode ser servida pelo Apache/XAMPP.

## Estrutura

- `index.html`: interface, estilos e lógica do simulador.

## Limitações

Os candidatos e resultados são demonstrativos. Os votos são mantidos na memória da página, sem banco de dados ou persistência após atualização. Este projeto não é um sistema oficial de votação.
