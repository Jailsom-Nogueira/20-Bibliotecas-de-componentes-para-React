# 20+ Bibliotecas de estilo para React
🎨 Repositório de bibliotecas de estilo para React 🎨

- Se você está em busca de uma boa biblioteca de estilo para seu projeto React, esse é o lugar certo!:shipit:
- Aqui você vai encontrar tudo o que precisa para deixar sua aplicação com aquela cara profissional sem gastar muito tempo criando tudo do zero.⏳
- Agora é só clicar no nome de cada uma e escolher a que melhor se encaixa nas suas necessidades.🎉

Sentiu falta de alguma biblioteca? Notou algum link quebrado? Vem falar comigo [AQUI](https://www.linkedin.com/in/jailsom-nogueira)!😉 

## 1- [Gestalt](https://gestalt.netlify.app/Installation)
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

## 2- [Grommet](https://v2.grommet.io/components)
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

## 3- [FluentUI](https://github.com/microsoft/fluentui)
Você conhece o Office, certo? Se você deseja criar uma interface de usuário semelhante ao Office, tá aí a FluentUI, que vem de um dos grandes, a Microsoft. 
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

## 4- [Material-UI](https://material-ui.com/)
O Material-UI foi criado com base no Material Design do Google. Se você deseja criar seu site seguindo este princípio e aproveitar uma UI já consagrada, aqui está a resposta.
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

## 5- [Rebass](https://rebassjs.org/)
Rebass vem com um punhado de componentes fundamentais. Esses componentes são extensíveis, o que proporciona a capacidade de criar um grande conjunto de elementos de IU.
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

## 6- [React Suite](https://rsuitejs.com/en/guide/introduction)
O React Suite fornece uma interface de usuário amigável e foi projetada para produtos de sistema corporativo. Também é cheia de componentes, como dicas de ferramentas, loaders, ícones, botões, etc.
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

## 7- [PrimeReact](https://primefaces.org/primereact/)
O PrimeReact oferece uma grande variedade de componentes com temas exclusivos para você escolher. Você também pode personalizar esses temas e componentes para usar de acordo com suas necessidades.
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

## 8- [Shards React](https://designrevision.com/docs/shards-react/getting-started)
O Shards React deixa sua IU com a mais alta qualidade e vai te economizar muito tempo ao fornecer uma lista enorme de componentes. Você pode construir quase todos os tipos de interface com esta biblioteca.
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

## 9- [Carbon Components React](https://react.carbondesignsystem.com/?path=/story/accordion--accordion)
Carbon Components React representa o sistema de design Carbon da IBM. Esses componentes visam criar consistência no design e garantir que os designers e desenvolvedores estejam se entendendo.
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

## 10- [Onsen UI](https://onsen.io/v2/guide/react/)
O material e o design plano vêm em um só lugar na IU do Onsen. O legal dessa biblioteca é que ela faz com que seu aplicativo web pareça nativo. Então, se você está optando por dispositivos móveis primeiro, escolha este.
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

## 11- [Atlaskit](https://atlaskit.atlassian.com/)
Atlaskit é uma biblioteca de componentes de interface do usuário que ajuda a implementar o Atlassian Design Guideline. Esta vem com algumas particularidades:
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

## 12- [Blueprint](https://blueprintjs.com/)
No Blueprint, os componentes são feitos de TypeScript e estilizados com Sass para acelerar o desenvolvimento. Esta biblioteca se concentra na apresentação de dados em aplicativos de desktop executados em navegadores modernos.
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

## 13- [Belle](http://nikgraf.github.io/belle/#/?_k=vs3lom)
Belle oferece uma ampla gama de componentes, que são otimizados para funcionar bem em desktops e dispositivos móveis. Você pode personalizar esses componentes todos de uma vez ou cada um individualmente.
### Instalação:
```
npm i belle
```
### Exemplo de uso:
```
import { Button } from ‘belle’;
export default function CloseButton() {
  return (
    <Button>Close</Button>
  );
};
```

## 14- [React Toolbox](http://react-toolbox.io/#/)
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

## 15- [React Bootstrap](https://react-bootstrap.github.io/)
React Bootstrap como o nome já indica, é uma boa maneira de usar o bootstrap, não da maneira original mas sim a do React.
### Instalação:
```
npm i react-bootstrap
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

## 16- [React Desktop](http://reactdesktop.js.org/)
O React Desktop aproveita a IU do macOS e do Windows para trazer o aplicativo de desktop nativo para a web.
### Instalação:
```
npm i react-desktop
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

## 17- [Reactstrap](https://reactstrap.github.io/)
Reactstrap é todo baseado em Bootstrap 4. Se você estiver familiarizado com bootstrap, não preciso dizer mais nada.
### Instalação:
```
npm i reactstrap react react-dom
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

## 18- [Elemental UI](http://elemental-ui.com/)
Elemental UI está cheia de componentes básicos, mas você ainda pode criar uma IU maravilhosa usando um único componente ou misturando alguns deles.
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

## 19- [Evergreen](https://evergreen.segment.com/)
Evergreen está cheio de componentes flexíveis e combináveis. Inclui quase tudo que você precisa para começar a construir uma interface de usuário para um site.
### Instalação:
```
#npm
npm i evergreen-ui
#yarn
yarn add evergreen-ui
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

## 20- [KendoReact](https://www.telerik.com/kendo-react-ui/)
Agora é a vez de uma premium, KendoReact. Quando se trata de visualização de dados, esta é a pedida. O preço começa em U$899 e vale muito a pena. Inclusive, algumas grandes empresas a usam, como Microsoft, IBM, NASA, SONY, etc. Mas tem um free trial para nós pobres mortais também hehe.
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

## 21- [React Virtualized](https://github.com/bvaughn/react-virtualized)
O React Virtualized se concentra na apresentação de grandes conjuntos de dados. É a biblioteca perfeita para renderizar tabelas, listas e grids enormes.
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

## 22- [Ant Design](https://ant.design/)
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

## 23- [Chakra UI](https://chakra-ui.com/)
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

## 24- [React Admin](https://marmelab.com/react-admin/)
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
