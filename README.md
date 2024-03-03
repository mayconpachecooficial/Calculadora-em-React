Para criar este projeto de calculadora em React, iniciei com uma estrutura básica usando o Create React App, que me forneceu uma base sólida e configurou automaticamente o ambiente de desenvolvimento necessário, incluindo Babel para transpilação e Webpack para empacotamento.

Dentro da pasta src, criei um diretório components para organizar os elementos da interface do usuário da calculadora. Cada componente foi cuidadosamente desenvolvido para ser reutilizável e modular. Por exemplo, criei o componente Button em seu próprio subdiretório, que inclui tanto a lógica do componente (index.js) quanto o seu estilo (styles.js). O mesmo foi feito para o componente Input, que é usado para exibir a saída da calculadora.

No coração do aplicativo está o App.js, onde os componentes Button e Input são utilizados para montar a interface da calculadora. Além disso, mantive o estado da calculadora, incluindo as entradas do usuário e os cálculos, diretamente neste componente raiz.

Para garantir que o estilo fosse consistente em todo o aplicativo, utilizei um arquivo global.js para definir estilos globais e importei-os no ponto de entrada do aplicativo, index.js. Isso me permitiu manter um tema consistente e facilitar mudanças globais de estilo sem alterar cada componente individualmente.

O gerenciamento de dependências foi tratado pelo yarn, e a configuração do projeto foi controlada pelo package.json, que também contém scripts úteis para a execução de tarefas de desenvolvimento e construção do projeto.

Para manter o código organizado e evitar subir arquivos desnecessários ao repositório, configurei um .gitignore apropriado. Também adicionei um arquivo .gitattributes para garantir que os atributos dos arquivos sejam consistentes, independentemente do ambiente onde o Git está sendo executado.

Após a codificação e os testes iniciais para garantir que a interface do usuário e a lógica matemática funcionassem como esperado, finalizei o projeto. Além disso, fiz questão de documentar o processo e as instruções de uso no README.md, facilitando para qualquer um entender e contribuir com o projeto no futuro.
