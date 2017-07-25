# React Simple Chatbot

<a href="https://travis-ci.org/LucasBassetti/react-simple-chatbot"><img src="https://travis-ci.org/LucasBassetti/react-simple-chatbot.svg?branch=master" alt="Travis CI" /></a> <a href="https://badge.fury.io/js/react-simple-chatbot"><img src="https://badge.fury.io/js/react-simple-chatbot.svg" alt="npm version"></a>
  <img src="https://codecov.io/gh/LucasBassetti/react-simple-chatbot/branch/master/graph/badge.svg" alt="Codecov" />
</a>

A simple chatbot component to create conversation chats

<img src="https://cloud.githubusercontent.com/assets/1014326/25716667/2d4bb4c4-30d6-11e7-996e-30c8fb316361.gif" height="400" />

## Getting Start

```bash
npm install react-simple-chatbot --save
```

## Usage

There are several examples on the [website](http://lucasbassetti.com.br/react-simple-chatbot). Here is the first one to get you started:

``` javascript
import ChatBot from 'react-simple-chatbot';

const steps = [
  {
    id: '0',
    message: 'Welcome to react chatbot!',
    trigger: '1',
  },
  {
    id: '1',
    message: 'Bye!',
    end: true,
  },
];

ReactDOM.render(
  <div>
    <ChatBot steps={steps} />
  </div>,
  document.getElementById('root')
);
```

## Build with `react-simple-chatbot`

1. [Seth Loh Website](https://github.com/lackdaz/lackdaz.github.io) - Personal website of Seth Loh ([demo](https://www.sethloh.com))

## How to Contribute

Please check the [contributing guide](https://github.com/LucasBassetti/react-simple-chatbot/blob/master/contributing.md)

## Authors

| ![Lucas Bassetti](https://avatars3.githubusercontent.com/u/1014326?v=3&s=150)|
|:---------------------:|
|  [Lucas Bassetti](https://github.com/LucasBassetti/)   |

See also the list of [contributors](https://github.com/LucasBassetti/react-simple-chatbot/contributors) who participated in this project.

## Donate

If you liked this project, you can donate to support it :heart:

[![paypal](https://www.paypalobjects.com/en_US/i/btn/btn_donateCC_LG.gif)](https://www.paypal.com/cgi-bin/webscr?cmd=_donations&business=lucasbr%2edafonseca%40gmail%2ecom&lc=US&item_name=Lucas%20Bassetti&item_number=GitHub&currency_code=USD&bn=PP%2dDonationsBF%3abtn_donateCC_LG%2egif%3aNonHosted)

## License

MIT · [Lucas Bassetti](http://lucasbassetti.com.br)
