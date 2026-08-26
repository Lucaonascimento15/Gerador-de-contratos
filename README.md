# Gerador-de-contratos
Gerador de contratos padronizados
Ferramenta que transforma o preenchimento manual de contratos de locação de stand em um formulário simples com preview em tempo real. Feita para reduzir um processo que levava horas para poucos minutos.

O problema

A cada edição do evento Boulevard Geek XP, cada expositor (stands, mercadinhos/artistas e categoria alimentação) precisa de um contrato individual, com dados e condições próprias: nome, CPF/CNPJ, endereço, valor, prazos, horários de funcionamento, mesas e cadeiras cedidas, entre outras cláusulas. Editar contrato por contrato manualmente, a partir de modelos em PDF, consumia cerca de 7 horas por rodada de expositores.

A solução

Um app de página única (HTML/CSS/JS, sem backend) que:

Oferece três modelos pré-configurados de contrato: Stand grande, Mercadinho/Artista e Alimentação (com cláusula de valor fixo + percentual sobre vendas).
Gera o texto do contrato automaticamente a partir dos dados preenchidos, com numeração de cláusulas ajustada dinamicamente (ex: a cláusula de restrição de alimentos só entra na numeração quando ativada).
Permite adicionar/remover dinamicamente horários de funcionamento por dia e cláusulas adicionais específicas de cada contrato.
Sinaliza em destaque qualquer campo obrigatório que ainda não foi preenchido, para evitar contratos incompletos.
Exporta o resultado por cópia direta, download em .txt ou impressão/exportação em PDF, já com marca d'água da logo do evento.

O que antes era um processo manual de ~7 horas por rodada de expositores passou a levar cerca de 20 minutos.

Como usar
Baixe e abra o arquivo gerador-contratos.html em qualquer navegador — não precisa de instalação nem servidor.
Escolha o modelo de contrato no topo (Stand, Mercadinho/Artista ou Alimentação).
Preencha os dados do expositor e as condições comerciais do evento.
Acompanhe o contrato sendo montado em tempo real no papel ao lado.
Use os botões no rodapé do formulário para copiar o texto, baixar em .txt ou imprimir/salvar em PDF.
Tecnologias

HTML, CSS e JavaScript puros — um único arquivo, sem dependências externas, rodando inteiramente no navegador.

Personalização

Os modelos de contrato (textos fixos, valores padrão, cláusulas) ficam centralizados no objeto PRESETS do arquivo. Cores, fontes e a marca d'água também podem ser ajustadas diretamente no CSS/HTML, sem necessidade de outras ferramentas.

Autor

Feito por Lucas Nascimento — gestão de tráfego pago e automações para negócios locais.
