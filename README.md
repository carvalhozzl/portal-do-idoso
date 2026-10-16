[README (1).md](https://github.com/user-attachments/files/33566668/README.1.md)
# portal-do-idoso# Portal da Terceira Idade

Protótipo navegável de um portal de voluntariado que conecta pessoas aposentadas a ONGs locais para doar tempo e conhecimento. Feito para o seminário de **Interação Humano-Computador (IHC)**.

## Persona

**Seu Geraldo, 73 anos** — professor aposentado, com tremor essencial leve nas mãos (pouca precisão motora fina) e perda auditiva progressiva.

## Como abrir

Abra o arquivo `index.html` no navegador. Não precisa instalar nada.

## Páginas

- **Início** — próximo compromisso, atalhos principais e atividades recomendadas
- **Encontrar atividades** — filtros de um clique e filtro "só adequadas a mim"
- **Detalhe da atividade** — vídeo com legenda, transcrição e forma de contato da ONG
- **Inscrição em 3 passos** — escolha do dia, forma de contato e revisão, com opção de desfazer
- **Minhas atividades** — compromissos, horas doadas e cancelamento com confirmação
- **Mensagens** — respostas rápidas, ditado e avisos visuais (sem depender de som)
- **Perfil e acessibilidade** — tamanho do texto, alto contraste, ignorar toques repetidos e legendas
- **Ensinar o que sei** — o voluntário oferece aulas, com prévia ao vivo

## Decisões de IHC

O botão amarelo **"Notas de IHC"**, no canto da tela, abre a lista das decisões de design de cada página, com referência às heurísticas de Nielsen, à WCAG 2.1 e ao eMAG. Os números amarelos na tela correspondem a essas notas.

Destaques:

- Alvos de clique com 64 px ou mais, para quem tem tremor nas mãos
- Nenhuma informação só por som: legendas, transcrição e avisos visuais
- Barra de acessibilidade em todas as páginas
- Prevenção de erros: conflito de horário bloqueado, revisão antes de confirmar e desfazer sem prazo
- Animações desligadas quando o sistema pede movimento reduzido

> Os dados (ONGs, pessoas e mensagens) são fictícios, apenas para demonstração.
