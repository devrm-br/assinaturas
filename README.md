# Assinaturas de e-mail Mouves

Endereço oficial do kit de assinaturas da Mouves Contabilidade, Finanças e Consultoria. A página gera o bloco pronto para colar no Gmail, Outlook e Apple Mail. O logo fica hospedado aqui mesmo, no arquivo `logo-assinatura-mouves.png`, e a página o encontra sozinha.

## Endereço

Depois de publicado, o kit responde em:

```
https://SEU-USUARIO.github.io/assinaturas/
```

E o logo em:

```
https://SEU-USUARIO.github.io/assinaturas/logo-assinatura-mouves.png
```

Troque `SEU-USUARIO` pelo usuário ou pela organização que hospeda o repositório.

## Arquivos

| Arquivo | Função |
| --- | --- |
| `index.html` | Página que monta e copia as assinaturas |
| `logo-assinatura-mouves.png` | Logo usado dentro da assinatura, 230 por 58 pixels |
| `robots.txt` | Pede que buscadores não indexem a página |
| `.nojekyll` | Desliga o processamento do Jekyll no GitHub Pages |

## Como publicar

1. No GitHub, clique em **New repository**. Nome `assinaturas`, visibilidade **Public**, sem README.
2. Na tela seguinte, clique em **uploading an existing file** e arraste os quatro arquivos desta pasta, inclusive o `.nojekyll`. Confirme em **Commit changes**.
3. Abra **Settings**, menu lateral **Pages**. Em Source escolha **Deploy from a branch**, branch `main`, pasta `/ (root)`, e salve.
4. Espere de um a dois minutos e recarregue a tela de Pages. O endereço publicado aparece no topo.
5. Abra o endereço. A linha logo abaixo do título mostra o endereço oficial e o campo do logo já vem preenchido.

## Como a equipe usa

1. Abrir o endereço oficial.
2. Ajustar nome, cargo, telefones e e-mail no cartão correspondente.
3. Clicar em **Copiar assinatura**.
4. Colar no editor de assinatura do cliente de e-mail. As instruções de cada programa estão no fim da própria página.

## Regras de manutenção

O arquivo `logo-assinatura-mouves.png` não pode ser apagado nem renomeado. Toda assinatura já enviada aponta para esse endereço. Se ele deixar de existir, o logo desaparece das mensagens antigas em todas as caixas de entrada que as receberam.

Para atualizar o logo, substitua o arquivo mantendo exatamente o mesmo nome. As assinatura antigas passam a exibir a nova imagem sem que ninguém precise refazer nada.

Para mudar telefones, cargos ou a lista de pessoas, edite o objeto `DADOS` dentro de `index.html`.

## Visibilidade

O GitHub Pages em conta gratuita exige repositório público. A página traz `noindex` e o `robots.txt` bloqueia buscadores, então ela não aparece no Google. Ainda assim qualquer pessoa com o endereço consegue abrir e ver os telefones e e-mails cadastrados. Se isso não for aceitável, retire os dados pessoais do objeto `DADOS` e deixe os campos em branco para cada pessoa preencher os próprios.
