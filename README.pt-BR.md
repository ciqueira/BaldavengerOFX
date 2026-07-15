# BaldavengerOFX para DaVinci Resolve

[English](README.md) · [Português](README.pt-BR.md)

Builds multiplataforma de plugins selecionados da suíte BaldavengerOFX para
DaVinci Resolve.

Este fork fornece builds mantidos de forma independente para macOS e Windows.
Os plugins utilizam os serviços Nexus para distribuição e associação de chaves
técnicas, e o aplicativo
[MCNexus](https://github.com/ciqueira/MCNexus) para downloads, atualizações e
instalação específica por plataforma.

O código-fonte original do BaldavengerOFX foi criado por Paul Dore:
[baldavenger/BaldavengerOFX](https://github.com/baldavenger/BaldavengerOFX).
Este fork e o serviço de suporte prestado por Magno Ciqueira são independentes
e não possuem afiliação ou endosso do autor original.

## Plugins Incluídos

| Plugin | Distribuição | Obter Chave |
| --- | --- | --- |
| VideoGrade | OpenKey | [Obter Chave](https://bridge.magnociqueira.com.br/github/claim?t=baldavengerofx&tmpl=76bda215-5c6b-4a80-b35d-de4942ee0be6&sig=14aabec3a222872e) |
| HueConverge | OpenKey | [Obter Chave](https://bridge.magnociqueira.com.br/github/claim?t=baldavengerofx&tmpl=c1ec264e-ccf9-4c9a-bfe0-180877bb3b2d&sig=ee04aca36d7d28ae) |
| FilmGrade | OpenKey | [Obter Chave](https://bridge.magnociqueira.com.br/github/claim?t=baldavengerofx&tmpl=a5b1c083-a666-44fa-8948-12a94768ec9e&sig=ab4bb6e904a42a34) |
| FreqSep | OpenKey | [Obter Chave](https://bridge.magnociqueira.com.br/github/claim?t=baldavengerofx&tmpl=61e768d4-4132-4bbb-ad5b-53cccc54b49f&sig=a82373ddfc7a19f8) |
| FreqEQ | OpenKey | [Obter Chave](https://bridge.magnociqueira.com.br/github/claim?t=baldavengerofx&tmpl=c9bf68b5-ec7d-4b71-aa40-a9f19673adac&sig=929fab384d2224c8) |
| Matrix | OpenKey | [Obter Chave](https://bridge.magnociqueira.com.br/github/claim?t=baldavengerofx&tmpl=79a22a0d-e988-495b-a319-d21bad22eb94&sig=da5e810a0191e9a0) |
| Qualifier | OpenKey | [Obter Chave](https://bridge.magnociqueira.com.br/github/claim?t=baldavengerofx&tmpl=cc82944c-7b63-4a31-9618-43fda25d5f6f&sig=8c678dfce1b070e3) |
| Replace | OpenKey | [Obter Chave](https://bridge.magnociqueira.com.br/github/claim?t=baldavengerofx&tmpl=002ef62d-b23b-4f32-89a3-db00e531b0ef&sig=3052a2dc5b32f16a) |
| ResolveMath | OpenKey | [Obter Chave](https://bridge.magnociqueira.com.br/github/claim?t=baldavengerofx&tmpl=c60ebcca-5ceb-41c8-94ab-294ad70a76b2&sig=a29898eeebba5cca) |
| ResolveMathxtra | OpenKey | [Obter Chave](https://bridge.magnociqueira.com.br/github/claim?t=baldavengerofx&tmpl=30be0b1a-da63-48da-b1fd-f3525654ebac&sig=93c6b132cd36df08) |
| Scan | OpenKey | [Obter Chave](https://bridge.magnociqueira.com.br/github/claim?t=baldavengerofx&tmpl=f64c0dce-fcca-48f0-83a5-e3ef8dc6b565&sig=21a036b7e677ae07) |
| SoftClip | OpenKey | [Obter Chave](https://bridge.magnociqueira.com.br/github/claim?t=baldavengerofx&tmpl=e31e7e72-ec9b-4558-8d92-6ce14c80693e&sig=42e9d4a461a0265c) |

Mais plugins da suíte original poderão ser adicionados em releases futuros.

[Torne-se um apoiador dos builds BaldavengerOFX](https://bridge.magnociqueira.com.br/commerce/start?t=baldavengerofx&offer=baldavenger-ofx-supporter)

## Plataformas

Os builds atuais estão disponíveis para:

- macOS, incluindo Macs Intel e Apple Silicon;
- Windows x64.

Backends de processamento:

- Metal no macOS para plugins acelerados por GPU;
- CUDA no Windows para GPUs NVIDIA;
- CPU para plugins como ResolveMath e ResolveMathxtra.

## Instalação e Ativação

Cada plugin possui seu próprio registro técnico OpenKey, mesmo quando vários
plugins são publicados no mesmo pacote. Esses registros facilitam a
distribuição e não substituem nem limitam os direitos da GNU GPLv3.

1. Clique em `Obter Chave` para o plugin desejado.
2. Autorize usando sua conta GitHub.
3. Copie a chave gratuita emitida.
4. Abra o MCNexus e ative o plugin com essa chave.
5. Instale ou atualize o plugin pelo MCNexus.

Perdeu a chave? Abra novamente o mesmo link usando a mesma conta GitHub para
recuperá-la.

## Torne-se um apoiador dos builds BaldavengerOFX

Todos os plugins listados permanecem disponíveis sob GNU GPLv3 sem a compra de
suporte. Se estes builds forem úteis, uma única compra de suporte aos builds
BaldavengerOFX cobre todos os plugins atualmente listados neste README.

O benefício inclui:

- suporte prioritário e privado por 12 meses, prestado por Magno Ciqueira
  para estes builds; e
- comunicações operacionais sobre releases, compatibilidade, manutenção,
  segurança e alterações materiais dos builds e do serviço.

Como esta é uma oferta `support_only`, obtenha ao menos uma chave gratuita do
BaldavengerOFX antes de iniciar o checkout. Chaves separadas por plugin não
exigem compras separadas de suporte. O pagamento não compra o software, não
restringe redistribuição, não adiciona recursos exclusivos e não representa
suporte oficial de Paul Dore.

[Torne-se um apoiador dos builds BaldavengerOFX](https://bridge.magnociqueira.com.br/commerce/start?t=baldavengerofx&offer=baldavenger-ofx-supporter)

Estes builds e o suporte relacionado são mantidos de forma independente por
**Magno Ciqueira**. A distribuição e as chaves técnicas utilizam os serviços
Nexus, enquanto o MCNexus é o aplicativo usado para instalar e atualizar os
plugins.

Antes da compra, leia os
[termos do produto](https://legal.magnociqueira.com.br/pt-BR/products/baldavenger-ofx/terms/),
a [política de suporte](https://legal.magnociqueira.com.br/pt-BR/products/baldavenger-ofx/support/),
o [aviso de privacidade](https://legal.magnociqueira.com.br/pt-BR/products/baldavenger-ofx/privacy/)
e a [política de cancelamento e reembolso](https://legal.magnociqueira.com.br/pt-BR/products/baldavenger-ofx/refunds/).

## Licença e Código-fonte Correspondente

O fork permanece licenciado pela
[GNU General Public License versão 3](LICENSE). Nenhum pagamento é necessário
para exercer os direitos concedidos por essa licença.

O código-fonte correspondente completo dos binários distribuídos pelo Nexus
é mantido neste repositório. Cada release binário deve identificar a tag ou o
commit usado no build. Consulte [SOURCE.md](SOURCE.md),
[MODIFICATIONS.md](MODIFICATIONS.md) e [DISTRIBUTION.md](DISTRIBUTION.md).

## Créditos

Plugins e código-fonte originais:  
Paul Dore / Baldavenger  
https://github.com/baldavenger/BaldavengerOFX

Distribuição Nexus e integração MCNexus/OpenKey:  
Magno Ciqueira  
https://github.com/ciqueira/MCNexus
