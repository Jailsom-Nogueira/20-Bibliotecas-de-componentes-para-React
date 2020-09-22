# 20+ Bibliotecas de componentes para React
🎨 Repositório de componentes de estilo para React 🎨

- Se você está em busca de uma boa biblioteca de componentes para seu projeto React, esse é o lugar certo!:shipit:
- Aqui você vai encontrar tudo o que precisa para deixar sua aplicação com aquela cara profissional sem gastar muito tempo criando tudo do zero.⏳
- Agora é só clicar no nome de cada uma e escolher a que melhor se encaixa nas suas necessidades.🎉

Considerações do autor levando em conta dificuldade de implementação e resultado:
- 👍 usaria ou já usei;
- 👎 mais facil fazer do zero;
- 🤏 legal, mas vai ser complicado.

Sentiu falta de alguma biblioteca? Notou algum link quebrado? Vem falar comigo [AQUI](https://www.linkedin.com/in/jailsom-nogueira)!😉 

## 1- [Gestalt](https://gestalt.netlify.app/Installation) 👍
Desenvolvido pela Pinterest o Gestalt segue as diretrizes de design interno da rede social para que devs e designers falem a mesma linguagem *se é que é possível hehe*. 
### Instalação:
```
npm i gestalt
ou
yarn add gestalt
```
### Exemplo de uso:
```
import { Avatar } from ‘gestalt’;
import ‘gestalt/dist/gestalt.css’;
export default function CustomAvatar() {
  return (
    <Avatar
      size=’sm’
      src=’image source’
      name=’Amy’
    />
  );
};
```

## 2- [Grommet](https://v2.grommet.io/components) 👍
Grommet se concentra principalmente em acessibilidade, temas e visual limpo.
### Instalação:
```
npm i grommet
```
### Exemplo de uso:
```
import { Grommet, Heading } from “grommet”
export default function CustomHeading() {
  return (
    <Grommet theme={theme}>
      <Heading level=’3’>Custom Heading</Heading>
    </Grommet>
  );
};
```

## 3- [FluentUI](https://developer.microsoft.com/en-us/fluentui#/controls/web) 🤏
Microsoft apresenta aqui a sua biblioteca TS com o visual do Microsoft Office que todo mundo já conhece. Robusta e um pouco mais complicada, como bom produto MS. :) 
### Instalação:
```
npm i @fluentui/react
ou
yarn add @fluentui/react
```
### Exemplo de uso:
```
import { Button } from ‘@fluentui/react/lib/Button’;
export default function DeleteButton() {
  return (
    <Button>Delete</Button>
  );
};
```

## 4- [Material-UI](https://material-ui.com/) 👍
Se você deseja criar seu site seguindo este princípio e aproveitar uma UI já consagrada, aqui está a resposta. O Material-UI foi criado com base no Material Design do Google. 
### Instalação:
```
npm i @material-ui/core
ou
yarn add @material-ui/core
```
### Exemplo de uso:
```
import Button from ‘@material-ui/core/Button’;
export default function CustomButton() {
  return (
    <Button color=’primary’>Custom Button</Button>
  );
};
```

## 5- [Rebass](https://rebassjs.org/) 👎
Rebass vem com um punhado de componentes são extensíveis, o que proporciona a capacidade de criar um grande conjunto de elementos de IU. Se você está com tempo de sobra e buscando um desafio, Rebass é uma boa pedida. 
### Instalação:
```
npm i rebass
```
### Exemplo de uso:
```
import { Label } from ‘@rebass/forms’;
export default function CustomLabel() {
  return (
    <Label>Username:</Label>
  );
};
```

## 6- [React Suite](https://rsuitejs.com/en/guide/introduction) 👎
React Suite é uma biblioteca projetada para plataforma intermediária e produtos de back-end. Comprometida em criar designs interativos e, ao mesmo tempo, fornecer aos desenvolvedores uma experiência de desenvolvimento amigável. 
### Instalação:
```
npm i rsuite
ou
yarn add rsuite
```
### Exemplo de uso:
```
import { Button } from ‘rsuite’;
import ‘rsuite/lib/styles/index.less’; // or ‘rsuite/dist/styles/rsuite-default.css’
export default function SignInButton() {
  return (
    <Button>Sign In</Button>
  );
}
```

## 7- [PrimeReact](https://primefaces.org/primereact/) 🤏🤏🤏
PrimeReact é um rico conjunto de componentes nativos de código aberto para React.
### Instalação:
```
npm i primereact
npm i primeicons
```
### Exemplo de uso:
```
import { InputText } from ‘primereact/inputtext’;
export default function PasswordInput() {
  return (
    <InputText
      value={‘value’}
      onChange={(event) => onPasswordChanged(‘value’)}
    />
  );
};
```

## 8- [Shards React](https://designrevision.com/docs/shards-react/getting-started) 🤏🤏
O Shards React fornece um lista enorme de componentes. Você pode construir quase todos os tipos de interface com esta biblioteca. Conta tembém com uma versão premium que traz 
mais de 120 blocos, mais de 350 componentes e 15 layouts de página.
### Instalação:
```
npm i shards-react
ou
yarn add shards-react
```
### Exemplo de uso:
```
import { Badge } from “shards-react”;
export default function VipBadge() {
  return (
    <Badge theme=’info’>VIP</Badge>
  );
};
```

## 9- [Carbon Components React](https://react.carbondesignsystem.com/?path=/story/accordion--accordion) 👍
Carbon Components React usa o sistema de design Carbon da IBM. Esses componentes visam criar consistência de design e garantir que designers e desenvolvedores estejam se entendendo.
### Instalação:
```
npm i carbon-components-react carbon-components carbon-icons
ou
yarn add carbon-components-react carbon-components carbon-icons
```
### Exemplo de uso:
```
import { Button } from “carbon-components-react”;
export default function ViewDetailButton() {
  return (
    <Button>View Detail</Button>
  );
};
```

## 10- [Onsen UI](https://onsen.io/v2/guide/react/) 🤏🤏
O legal dessa biblioteca é que ela faz com que seu aplicativo web pareça nativo. Lembre de testar Onsen em uma tela de celular! 
### Instalação:
```
npm i onsenui react-onsenui
```
### Exemplo de uso:
```
import { Page, Button } from “react-onsenui”
export default function CustomButton() {
  return (
    <Page>
      <Button>Custom Button</Button>
    </Page>
  );
};
```

## 11- [Atlaskit](https://atlaskit.atlassian.com/) 👍
Atlaskit é uma biblioteca de componentes que ajuda a implementar o Atlassian Design Guideline. Esta vem com algumas particularidades:
### A instalação é feita por pacotes e você instala os que preferir, [AQUI](https://atlaskit.atlassian.com/packages) você encontra uma lista deles:
```
npm i @atlaskit/button
ou
yarn add @atlaskit/button
```
### Exemplo de uso:
```
import Button from '@atlaskit/button';
export default function ConfirmButton() {
  return (
    <Button theme='dark'>Confirm</Button>
  );
};
```

## 12- [Blueprint](https://blueprintjs.com/) 👍👍
No Blueprint, os componentes são desenvolvidos em TypeScript e estilizados com Sass. Esta biblioteca se concentra na apresentação de dados em aplicativos de desktop executados em navegadores modernos.
### Instalação:
```
yarn add @blueprintjs/core react react-dom
```
### Exemplo de uso:
```
import { Button } from “@blueprintjs/core”;
export default function PlaceOrderButton() {
  return (
    <Button text=’Order’ onclick={order} />
  );
};
```

## 13- [React Toolbox](http://react-toolbox.io/#/) 🤏
Os componentes do React Toolbox seguem o Google Material Design. Esta biblioteca é construída sobre algumas das propostas mais modernas, como Módulos CSS, ES6 e Webpack.
### Instalação:
```
npm i react-toolbox
```
### Exemplo de uso:
```
import Dialog from ‘react-toolbox/lib/dialog’;
export default function CustomDialog() {
  return (
    <Dialog title=’Custom Dialog’>Content</Dialog>
  );
};
```

## 14- [React Bootstrap](https://react-bootstrap.github.io/) 👍
Cada componente foi construído do zero como um verdadeiro componente React. Como uma das bibliotecas React mais antigas, React-Bootstrap evoluiu e cresceu junto com React, tornando-se uma excelente escolha como sua base de IU.

### Instalação:
```
npm install react-bootstrap bootstrap
```
### Exemplo de uso:
```
import Button from “react-bootstrap/Button”;
export default function CustomButton() {
  return (
    <Button>Custom Button</Button>
  );
};
```

## 15- [React Desktop](http://reactdesktop.js.org/demo/) 👍
O React Desktop visa trazer uma experiência de desktop nativa para a web, apresentando muitos componentes com a cara do macOS Sierra e do Windows 10.
### Instalação:
```
npm install react-desktop --save
```
### Exemplo de uso:
```
import { Text } from ‘react-desktop/macOs’;
export default function CustomText() {
  return (
    <Text size=’18’>content</Text>
  );
};
```

## 16- [Reactstrap](https://reactstrap.github.io/) 👍
Reactstrap é todo baseado em Bootstrap 4. Se você estiver familiarizado com bootstrap vai ser bem tranquilo. Esta lib também conta com uma série de temas Premium bem bonitos.
### Instalação:
```
npm i reactstrap bootstrap
```
### Exemplo de uso:
```
import { Button } from ‘reactstrap’;
export default function RegisterButton() {
  return (
    <Button>Register</Button>
  );
};
```

## 17- [Elemental UI](http://elemental-ui.com/) 👎
Elemental UI está cheia de componentes bem básicos. Já que depois de muito tentar, não consegui fazer funcionar no codesandbox.io, essa vai para a lista de ~~cruz credo~~ menções honrosas.
### Instalação:
```
npm i elemental
```
### Exemplo de uso:
```
import { Button } from ‘elemental’;
export default function LogoutButton() {
  return (
    <Button size=’sm’ type=’primary’>Logout</Button>
  );
};
```

## 18- [Evergreen](https://evergreen.segment.com/) 👍👍
Evergreen está repleta de componentes flexíveis e combináveis. Inclui quase tudo que você precisa para começar a construir uma interface de usuário para um site.
### Instalação:
```
yarn add evergreen-ui
ou
npm install --save evergreen-ui
```
### Exemplo de uso:
```
import { Button } from ‘evergreen-ui’;
export default function CancelButton() {
  return (
    <Button>Cancel</Button>
  );
};
```

## 19- [KendoReact](https://www.telerik.com/kendo-react-ui/) 🤏🤏🤏
Agora é a vez de uma premium, KendoReact. Quando se trata de visualização de dados, esta é a pedida. Inclusive, algumas grandes empresas a usam, como Microsoft, IBM, NASA, SONY, etc. O preço começa em U$899 mas tem um free trial para nós pobres mortais também hehe.
### Instalação:
```
npm install --save @progress/kendo-react-grid @progress/kendo-data-query @progress/kendo-react-inputs @progress/kendo-react-intl @progress/kendo-react-dropdowns @progress/kendo-react-dateinputs @progress/kendo-drawing @progress/kendo-react-data-tools @progress/kendo-react-animation
ou
yarn add @progress/kendo-react-grid @progress/kendo-data-query @progress/kendo-react-inputs @progress/kendo-react-intl @progress/kendo-react-dropdowns @progress/kendo-react-dateinputs @progress/kendo-drawing @progress/kendo-react-data-tools @progress/kendo-react-animation
```
### Exemplo de uso:
```
import ‘@progress/kendo-theme-default/dist/all.css’;
import { Grid, GridColumn } from ‘@progress/kendo-react-grid’;
export default function CustomGrid() {
  return (
    <Grid data={products}>
      <GridColumn field=’ProductName’ />
      <GridColumn field=’ProductPrice’ />
      <GridColumn field=’ProductDiscount’ />
    </Grid>
  );
};
```

## 20- [React Virtualized](https://github.com/bvaughn/react-virtualized) 🤏🤏
O React Virtualized se concentra na apresentação de grandes conjuntos de dados. É a biblioteca perfeita para renderizar tabelas, listas e grids enormes. Vou ficar devendo o exemplo do codesandbox.io, este é mais um dos exemplos de muito código para pouca exemplo 😁.
### Instalação:
```
npm i react-virtualized
```
### Exemplo de uso:
```
import ‘react-virtualized/styles.css’;
import {Collection} from ‘react-virtualized’;
export default function UsersList() {
  function cellRenderer({index, key, style}) {
    return (
      <div key={key} style={style}>
        {list[index].name}
      </div>
    );
  }
  return (
    <Collection
      cellCount={100}
      cellRender={cellRenderer}
      width={256}
      height={256}
    />
  );
}
```

## 21- [Ant Design](https://ant.design/)
Ant Design é uma biblioteca UI de classe corporativa projetado para aplicativos da web e fornece mais de 50 componentes personalizáveis.
### Instalação:
```
npm install antd
ou
yarn add antd
```
### Exemplo de uso:
```
import { Button } from 'antd';

<Button type="primary">Primary Button</Button>
<Button>Default Button</Button>
<Button type="dashed">Dashed Button</Button>
```

## 22- [Chakra UI](https://chakra-ui.com/)
Chakra UI é uma biblioteca de componentes simples, modular e acessível que fornece todos os blocos de construção de que você precisa para desenvolver aplicativos React.
### Instalação:
```
npm install @chakra-ui/core @emotion/core @emotion/styled emotion-theming
```
### Exemplo de uso:
```
import { Button } from "@chakra-ui/core";
<Button variantColor="green">Button</Button>
```

## 23- [React Admin](https://marmelab.com/react-admin/)
Esta biblioteca é perfeita para construir aplicativos de administração business-to-business (B2B) sobre APIs REST / GraphQL e pode também ser personalizada. É construída sobre uma série de ferramentas além do React: Material UI, React Router, Redux e React Final Form. Lembrando que possui também uma versão Enterprise Edition que conta principalmente com suporte técnico.
### Instalação:
```
npm install react-admin
```
### Exemplo de uso:
```
// in app.js
import * as React from "react";
import { render } from 'react-dom';
import { Admin, Resource } from 'react-admin';
import simpleRestProvider from 'ra-data-simple-rest';

import { PostList, PostEdit, PostCreate, PostIcon } from './posts';

render(
    <Admin dataProvider={simpleRestProvider('http://localhost:3000')}>
        <Resource name="posts" list={PostList} edit={PostEdit} create={PostCreate} icon={PostIcon}/>
    </Admin>,
    document.getElementById('root')
);
```
