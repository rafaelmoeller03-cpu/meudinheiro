<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Termos de Uso - Meu Dinheiro</title>
  <style>
    :root {
      --bg: #181c24;
      --card: #0d1322;
      --line: #00c2ff;
      --line-soft: rgba(0, 194, 255, 0.35);
      --text: #f5f8ff;
      --muted: #aab7d3;
      --orange: #ff9800;
      --ok: #1dff9a;
    }

    * { box-sizing: border-box; }

    body {
      margin: 0;
      font-family: Roboto, "Segoe UI", Arial, sans-serif;
      background: radial-gradient(circle at top, #1f2a44 0%, var(--bg) 42%, #0a0f1f 100%);
      color: var(--text);
      line-height: 1.6;
    }

    .wrap {
      width: min(980px, 92vw);
      margin: 24px auto 40px;
    }

    .hero {
      border: 1.5px solid var(--line);
      border-radius: 18px;
      background: linear-gradient(160deg, #0e1730 0%, #0b1222 100%);
      padding: 22px;
      box-shadow: 0 0 0 1px rgba(0,0,0,.2), 0 14px 40px rgba(0, 194, 255, 0.15);
    }

    .chip {
      display: inline-block;
      padding: 5px 10px;
      border-radius: 999px;
      border: 1px solid var(--line-soft);
      color: #84ddff;
      font-size: 12px;
      font-weight: 700;
      letter-spacing: .3px;
      text-transform: uppercase;
    }

    h1 {
      margin: 10px 0 6px;
      font-size: clamp(24px, 3.6vw, 38px);
      line-height: 1.2;
    }

    .sub {
      margin: 0;
      color: var(--muted);
      font-size: 15px;
    }

    .grid {
      display: grid;
      grid-template-columns: 1fr;
      gap: 14px;
      margin-top: 14px;
    }

    .card {
      border: 1px solid var(--line-soft);
      border-radius: 14px;
      background: var(--card);
      padding: 16px;
    }

    .card.orange {
      border-color: rgba(255, 152, 0, .7);
      background: linear-gradient(160deg, rgba(255,152,0,.12) 0%, rgba(255,152,0,.04) 100%), var(--card);
    }

    h2 {
      margin: 0 0 8px;
      font-size: 19px;
      color: #dff6ff;
    }

    p { margin: 0 0 10px; color: var(--muted); }

    ul { margin: 0; padding-left: 18px; }
    li { margin: 6px 0; color: var(--muted); }

    strong { color: var(--text); }

    .notice {
      border-left: 4px solid var(--orange);
      background: rgba(255, 152, 0, 0.12);
      padding: 12px;
      border-radius: 10px;
      color: #ffd8a5;
      margin-top: 10px;
    }

    .ok {
      border-left-color: var(--ok);
      background: rgba(29, 255, 154, 0.08);
      color: #b6ffd9;
    }

    a { color: var(--line); text-decoration: underline; }

    .footer {
      margin-top: 14px;
      color: #8ea5c8;
      font-size: 13px;
    }
  </style>
</head>
<body>
  <main class="wrap">
    <section class="hero">
      <span class="chip">Meu Dinheiro</span>
      <h1>Termos de Uso</h1>
      <p class="sub">Ultima atualizacao: 29 de marco de 2026</p>
    </section>

    <section class="grid">
      <article class="card">
        <h2>1. Aceitacao</h2>
        <p>Ao usar o app <strong>Meu Dinheiro</strong>, voce declara que leu e concorda com estes Termos de Uso e com a <a href="politica-de-privacidade.html">Politica de Privacidade</a>.</p>
      </article>

      <article class="card">
        <h2>2. Objeto do app</h2>
        <p>O app oferece recursos de organizacao financeira pessoal, incluindo registro de movimentacoes, categorias, historico, resumo, metas, contas parceladas, diagnostico, projecao futura, compartilhamento e desafios financeiros.</p>
        <p>O app e ferramenta de apoio e <strong>nao constitui consultoria financeira, contabil, juridica ou de investimento</strong>.</p>
      </article>

      <article class="card">
        <h2>3. Plano gratuito e Premium</h2>
        <p>O app possui recursos gratuitos e recursos Premium, com regras locais de acesso e limites do plano free.</p>
        <ul>
          <li>Plano free possui limites de uso em funcionalidades especificas.</li>
          <li>Plano Premium libera recursos completos conforme disponibilidade no app.</li>
          <li>Limites gratuitos consumidos podem permanecer registrados localmente mesmo apos exclusao de itens internos.</li>
        </ul>
      </article>

      <article class="card orange">
        <h2>4. Assinatura, renovacao, cancelamento e reembolso</h2>
        <p>Assinaturas sao vendidas e processadas pela <strong>Google Play Billing</strong>. O app nao coleta nem processa dados de cartao de credito diretamente.</p>
        <ul>
          <li>Planos previstos no app: mensal e anual (com valores exibidos no app e/ou Play Store).</li>
          <li>A assinatura pode ter renovacao automatica conforme regra da Google Play e configuracao da conta do usuario.</li>
          <li>O cancelamento deve ser feito pelo usuario na conta Google Play.</li>
          <li>Recursos Premium sao liberados quando a compra e reconhecida como ativa.</li>
          <li>O botao "Restaurar compras" tenta revalidar assinaturas ativas na Google Play.</li>
        </ul>
        <div class="notice">
          <strong>Reembolso - regra importante:</strong> qualquer pedido de reembolso deve seguir as politicas oficiais da Google Play e a legislacao aplicavel. O desenvolvedor nao realiza cobranca fora da loja nem estorno fora dos canais oficiais da plataforma.
        </div>
      </article>

      <article class="card">
        <h2>5. Responsabilidades do usuario</h2>
        <ul>
          <li>informar dados corretos e revisar lancamentos antes de salvar;</li>
          <li>manter seguranca do proprio aparelho e da conta Google;</li>
          <li>usar o app de forma licita, sem tentativa de fraude, engenharia reversa ou abuso da plataforma;</li>
          <li>compreender que resultados de projecoes e diagnosticos dependem dos dados inseridos e sao estimativas.</li>
        </ul>
      </article>

      <article class="card">
        <h2>6. Limitacao de responsabilidade</h2>
        <p>Na extensao permitida por lei, o app nao garante lucro, economia especifica, ausencia de perdas ou resultado financeiro determinado.</p>
        <p>O usuario e responsavel pelas decisoes financeiras tomadas com base nos dados e analises apresentados.</p>
      </article>

      <article class="card">
        <h2>7. Propriedade intelectual</h2>
        <p>Marca, layout, codigo, textos e elementos visuais do app sao protegidos por direitos aplicaveis. Nao e permitido copiar, revender, sublicenciar ou explorar comercialmente sem autorizacao.</p>
      </article>

      <article class="card">
        <h2>8. Suspensao e encerramento</h2>
        <p>Podemos limitar ou encerrar o acesso a funcionalidades em caso de uso indevido, fraude, violacao destes termos ou exigencia legal.</p>
      </article>

      <article class="card">
        <h2>9. Alteracoes destes termos</h2>
        <p>Estes termos podem ser atualizados periodicamente por motivos legais, tecnicos ou operacionais. A data da versao vigente sera sempre informada.</p>
      </article>

      <article class="card">
        <h2>10. Suporte e contato</h2>
        <p>Canal oficial de suporte: <strong>suportemeudinheiro@gmail.com</strong>.</p>
        <p>Para temas de pagamento, assinatura e reembolso, podem ser exigidos tambem os canais oficiais da Google Play.</p>
      </article>

      <article class="card">
        <h2>11. Foro e legislacao aplicavel</h2>
        <p>Estes termos sao regidos pela legislacao aplicavel no Brasil, sem prejuizo de direitos obrigatorios do consumidor previstos em lei.</p>
      </article>
    </section>

    <p class="footer">Suporte oficial: suportemeudinheiro@gmail.com | Documento complementar: <a href="politica-de-privacidade.html">Politica de Privacidade</a></p>
  </main>
</body>
</html>
