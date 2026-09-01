# Fernando Almeida — landing page

Página de captação focada no cliente final: tráfego pago, agentes de IA,
automação e sistemas sob medida.

**No ar:** https://nando710.github.io/lp-fernando-almeida/

## Como rodar

Precisa ser servida por HTTP (os módulos JS não carregam por `file://`):

```bash
npx serve .
```

## Estrutura

| pasta | o que tem |
|---|---|
| `index.html` | a página inteira |
| `fa-3d/` | vídeos e animações do avatar 3D |
| `fonts/` | Plus Jakarta Sans e Space Grotesk, hospedadas localmente |
| `_ext/` | bibliotecas de apoio (GSAP, jQuery) |

## Notas

- Sem requisições a domínios externos: fontes e bibliotecas são servidas do próprio repositório.
- Âncoras de navegação: `#topo` `#maquina` `#pilares` `#servicos` `#metodo` `#sobre` `#processo` `#cases` `#faq` `#contato`
- O botão "Agendar call" ainda aponta para a seção de contato; falta a URL de agendamento.
