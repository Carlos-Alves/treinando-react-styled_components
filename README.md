# Projeto da Aula React Styled Components

##Bootcamp React Web Developer - Digital Innovation One

###Criando uma home com Styled Components


####Linguagens e tecnologias utilizadas:
- HMTL
- CSS
- React
- Styled Components



**Principal dependência:**  **npm i styled-components**



#####Tela 
![](https://i.imgur.com/LuNTVzV.png)



#####Exemplo do código

```javascript
import React from 'react';
import styled from 'styled-components';

const Nav = styled.div `
background-color: #aa2e25;
position: relative;
display: flex;
justify-content: space-between;
width: 100%;
height: 60px;

`
const Item = styled.a `
font-size: 16px;
font-family: 'Read';
font-weight: bold;
color: #f8d5d3;
padding: 10px;
margin-top: 10px; 

`

export default function header() {
    return(
        <Nav>
            <Item>Home</Item>
            <Item>Sobre</Item>
            <Item>Contato</Item>
        </Nav>
    );
}

```


