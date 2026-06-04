<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Andresa Ferreira Studio | Links & Serviços</title>
    <!-- Importando ícones elegantes para os botões -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.2/css/all.min.css">
    <style>
        /* Paleta de Cores Premium (Preto, Off-White e Dourado Soft) */
        :root {
            --cor-fundo: #0a0a0a;       /* Preto absoluto para o fundo */
            --cor-card: #141414;        /* Preto mais suave para os blocos */
            --cor-primaria: #ffffff;    /* Branco puro para textos principais */
            --cor-secundaria: #d4af37;  /* Dourado elegante para detalhes e destaques */
            --cor-texto-mutado: #a0a0a0;/* Cinza claro para descrições */
            --verde-whatsapp: #128c7e;
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Roboto, Helvetica, Arial, sans-serif;
        }

        body {
            background-color: var(--cor-fundo);
            color: var(--cor-primaria);
            display: flex;
            justify-content: center;
            padding: 20px;
        }

        /* Container que simula tela de celular */
        .container {
            width: 100%;
            max-width: 450px;
            text-align: center;
            padding-bottom: 50px;
        }

        /* Cabeçalho */
        .header {
            margin-top: 30px;
            margin-bottom: 35px;
        }

        .avatar {
            width: 120px;
            height: 120px;
            border-radius: 50%;
            object-fit: cover;
            border: 2px solid var(--cor-secundaria);
            box-shadow: 0 0 20px rgba(212, 175, 55, 0.2);
        }

        .nome-salao {
            font-size: 1.6rem;
            font-weight: 600;
            color: var(--cor-primaria);
            margin-top: 15px;
            text-transform: uppercase;
            letter-spacing: 2px;
        }

        .subtitulo {
            font-size: 0.85rem;
            color: var(--cor-secundaria);
            margin-top: 6px;
            text-transform: uppercase;
            letter-spacing: 1px;
        }

        /* Seção de Links Rápidos (Botões) */
        .links-rapidos {
            display: flex;
            flex-direction: column;
            gap: 14px;
            margin-bottom: 40px;
        }

        .btn {
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 10px; /* Espaço entre o ícone e o texto */
            padding: 16px;
            border-radius: 50px; /* Estilo pílula moderno */
            text-decoration: none;
            font-weight: 600;
            font-size: 0.95rem;
            letter-spacing: 0.5px;
            transition: transform 0.2s, background-color 0.2s, box-shadow 0.2s;
        }

        /* Botão de Destaque: WhatsApp */
        .btn-whatsapp {
            background-color: var(--verde-whatsapp);
            color: #ffffff;
        }

        .btn-whatsapp:hover {
            background-color: #0e7064;
            transform: translateY(-2px);
            box-shadow: 0 5px 15px rgba(18, 140, 126, 0.4);
        }

        /* Botões Secundários */
        .btn-secundario {
            background-color: transparent;
            color: var(--cor-primaria);
            border: 1px solid rgba(255, 255, 255, 0.2);
        }

        .btn-secundario:hover {
            background-color: rgba(255, 255, 255, 0.05);
            border-color: var(--cor-secundaria);
            transform: translateY(-2px);
            box-shadow: 0 5px 15px rgba(212, 175, 55, 0.1);
        }

        /* Título do Cardápio de Serviços */
        .cardapio-titulo {
            font-size: 1.1rem;
            text-transform: uppercase;
            letter-spacing: 3px;
            color: var(--cor-primaria);
            margin-bottom: 25px;
        }

        .cardapio-titulo::after {
            content: '';
            display: block;
            width: 40px;
            height: 1px;
            background-color: var(--cor-secundaria);
            margin: 10px auto 0 auto;
        }

        /* Blocos de Categorias */
        .categoria-bloco {
            background-color: var(--cor-card);
            border-radius: 16px;
            padding: 24px;
            margin-bottom: 24px;
            text-align: left;
            border: 1px solid rgba(255, 255, 255, 0.03);
        }

        .categoria-nome {
            font-size: 1rem;
            color: var(--cor-secundaria);
            font-weight: 600;
            margin-bottom: 20px;
            text-transform: uppercase;
            letter-spacing: 1.5px;
            border-bottom: 1px solid rgba(212, 175, 55, 0.15);
            padding-bottom: 8px;
        }

        /* Linhas do Menu de Serviços */
        .item-menu {
            display: flex;
            justify-content: space-between;
            align-items: flex-start;
            margin-bottom: 18px;
        }

        .item-menu:last-child {
            margin-bottom: 0;
        }

        .item-detalhes {
            flex: 1;
            padding-right: 20px;
        }

        .item-nome {
            font-weight: 500;
            font-size: 0.95rem;
            color: var(--cor-primaria);
        }

        .item-descricao {
            font-size: 0.8rem;
            color: var(--cor-texto-mutado);
            margin-top: 4px;
            line-height: 1.3;
        }

        .item-preco {
            font-weight: 600;
            font-size: 0.95rem;
            color: var(--cor-secundaria);
            white-space: nowrap;
        }

        /* Rodapé */
        .footer {
            font-size: 0.75rem;
            color: #555;
            margin-top: 40px;
            letter-spacing: 1px;
        }
    </style>
</head>
<body>

    <div class="container">
        
        <!-- Cabeçalho principal -->
        <div class="header">
            <img src="https://images.unsplash.com/photo-1562322140-8baeececf3df?w=200" alt="Andresa Ferreira Studio" class="avatar">
            <h1 class="nome-salao">Andresa Ferreira</h1>
            <p class="subtitulo">Studio de Beleza</p>
        </div>

        <!-- Links Rápidos (Botões da Bio) -->
        <div class="links-rapidos">
            
            <!-- Link do WhatsApp -->
            <a href="https://wa.me/5585991193785?text=Olá,%20Andresa!%20Gostaria%20de%20agendar%20um%20horário." target="_blank" class="btn btn-whatsapp">
                <i class="fab fa-whatsapp"></i> Agende seu Horário via WhatsApp
            </a>
            
            <!-- Link do Instagram -->
            <a href="https://www.instagram.com/andresaferreirastudio" target="_blank" class="btn btn-secundario">
                <i class="fab fa-instagram"></i> Siga-nos no Instagram
            </a>
            
            <!-- Link de Localização -->
            <a href="https://maps.google.com" target="_blank" class="btn btn-secundario">
                <i class="fas fa-map-marker-alt"></i> Localização do Studio
            </a>
            
        </div>

        <!-- Seção do Cardápio / Tabela de Preços -->
        <h2 class="cardapio-titulo">Serviços & Valores</h2>

        <!-- Categoria 1: Cabelo -->
        <div class="categoria-bloco">
            <h3 class="categoria-nome">Cabelos</h3>
            
            <div class="item-menu">
                <div class="item-detalhes">
                    <p class="item-nome">Corte & Visagismo</p>
                    <p class="item-descricao">Corte personalizado para valorizar as linhas do seu rosto, incluindo lavagem e finalização.</p>
                </div>
                <p class="item-preco">R$ 80,00</p>
            </div>

            <div class="item-menu">
                <div class="item-detalhes">
                    <p class="item-nome">Mechas & Iluminada</p>
                    <p class="item-descricao">Técnicas modernas de descoloração com proteção da fibra capilar. Requer avaliação.</p>
                </div>
                <p class="item-preco">Sob Consulta</p>
            </div>

            <div class="item-menu">
                <div class="item-detalhes">
                    <p class="item-nome">Tratamento Cronograma Capilar</p>
                    <p class="item-descricao">Nutrição profunda e reconstrução imediata com produtos de linha profissional.</p>
                </div>
                <p class="item-preco">R$ 120,00</p>
            </div>
        </div>

        <!-- Categoria 2: Especialidades / Estética -->
        <div class="categoria-bloco">
            <h3 class="categoria-nome">Design & Estética</h3>
            
            <div class="item-menu">
                <div class="item-detalhes">
                    <p class="item-nome">Design de Sobrancelhas</p>
                    <p class="item-descricao">Alinhamento perfeito seguindo a proporção natural do seu olhar.</p>
                </div>
                <p class="item-preco">R$ 45,00</p>
            </div>

            <div class="item-menu">
                <div class="item-detalhes">
                    <p class="item-nome">Manicure & Alongamento</p>
                    <p class="item-descricao">Cutilagem fina e aplicação de técnicas de alongamento de alta durabilidade.</p>
                </div>
                <p class="item-preco">A partir de R$ 50</p>
            </div>
        </div>

        <!-- Rodapé -->
        <p class="footer">© 2026 ANDRESA FERREIRA STUDIO<br>Todos os direitos reservados.</p>

    </div>

</body>
</html>
padding: 16px;
            border-radius: 50px; /* Estilo pílula moderno */
            text-decoration: none;
            font-weight: 600;
            font-size: 0.95rem;
            letter-spacing: 0.5px;
            transition: transform 0.2s, background-color 0.2s;
        }

        /* Botão de Destaque: WhatsApp */
        .btn-whatsapp {
            background-color: var(--verde-whatsapp);
            color: #ffffff;
        }

        .btn-whatsapp:hover {
            background-color: #0e7064;
            transform: scale(1.02);
        }

        /* Botões Secundários */
        .btn-secundario {
            background-color: transparent;
            color: var(--cor-primaria);
            border: 1px solid rgba(255, 255, 255, 0.2);
        }

        .btn-secundario:hover {
            background-color: rgba(255, 255, 255, 0.05);
            border-color: var(--cor-secundaria);
            transform: scale(1.02);
        }

        /* Título do Cardápio de Serviços */
        .cardapio-titulo {
            font-size: 1.1rem;
            text-transform: uppercase;
            letter-spacing: 3px;
            color: var(--cor-primaria);
            margin-bottom: 25px;
        }

        .cardapio-titulo::after {
            content: '';
            display: block;
            width: 40px;
            height: 1px;
            background-color: var(--cor-secundaria);
            margin: 10px auto 0 auto;
        }

        /* Blocos de Categorias */
        .categoria-bloco {
            background-color: var(--cor-card);
            border-radius: 16px;
            padding: 24px;
            margin-bottom: 24px;
            text-align: left;
            border: 1px solid rgba(255, 255, 255, 0.03);
        }

        .categoria-nome {
            font-size: 1rem;
            color: var(--cor-secundaria);
            font-weight: 600;
            margin-bottom: 20px;
            text-transform: uppercase;
            letter-spacing: 1.5px;
            border-bottom: 1px solid rgba(212, 175, 55, 0.15);
            padding-bottom: 8px;
        }

        /* Linhas do Menu de Serviços */
        .item-menu {
            display: flex;
            justify-content: space-between;
            align-items: flex-start;
            margin-bottom: 18px;
        }

        .item-menu:last-child {
            margin-bottom: 0;
        }

        .item-detalhes {
            flex: 1;
            padding-right: 20px;
        }

        .item-nome {
            font-weight: 500;
            font-size: 0.95rem;
            color: var(--cor-primaria);
        }

        .item-descricao {
            font-size: 0.8rem;
            color: var(--cor-texto-mutado);
            margin-top: 4px;
            line-height: 1.3;
        }

        .item-preco {
            font-weight: 600;
            font-size: 0.95rem;
            color: var(--cor-secundaria);
            white-space: nowrap;
        }

        /* Rodapé */
        .footer {
            font-size: 0.75rem;
            color: #555;
            margin-top: 40px;
            letter-spacing: 1px;
        }
    </style>
</head>
<body>

    <div class="container">
        
        <!-- Cabeçalho principal -->
        <div class="header">
            <!-- Link da foto de perfil (pode ser substituído pela foto real ou logo) -->
            <img src="https://images.unsplash.com/photo-1562322140-8baeececf3df?w=200" alt="Andresa Ferreira Studio" class="avatar">
            <h1 class="nome-salao">Andresa Ferreira</h1>
            <p class="subtitulo">Studio de Beleza</p>
        </div>

        <!-- Links Rápidos (Botões da Bio) -->
        <div class="links-rapidos">
            
            <!-- Link do WhatsApp -->
            <a href="https://wa.me/5585999999999?text=Olá,%20Andresa!%20Gostaria%20de%20agendar%20um%20horário." target="_blank" class="btn btn-whatsapp">
                Agende seu Horário via WhatsApp
            </a>
            
            <!-- Link do Instagram -->
            <a href="https://www.instagram.com/andresaferreirastudio" target="_blank" class="btn btn-secundario">
                Siga-nos no Instagram
            </a>
            
            <!-- Link de Localização -->
            <a href="https://maps.google.com" target="_blank" class="btn btn-secundario">
                Localização do Studio
            </a>
            
        </div>

        <!-- Seção do Cardápio / Tabela de Preços -->
        <h2 class="cardapio-titulo">Serviços & Valores</h2>

        <!-- Categoria 1: Cabelo -->
        <div class="categoria-bloco">
            <h3 class="categoria-nome">Cabelos</h3>
            
            <div class="item-menu">
                <div class="item-detalhes">
                    <p class="item-nome">Corte & Visagismo</p>
                    <p class="item-descricao">Corte personalizado para valorizar as linhas do seu rosto, incluindo lavagem e finalização.</p>
                </div>
                <p class="item-preco">R$ 80,00</p>
            </div>

            <div class="item-menu">
                <div class="item-detalhes">
                    <p class="item-nome">Mechas & Iluminada</p>
                    <p class="item-descricao">Técnicas modernas de descoloração com proteção da fibra capilar. Requer avaliação.</p>
                </div>
                <p class="item-preco">Sob Consulta</p>
            </div>

            <div class="item-menu">
                <div class="item-detalhes">
                    <p class="item-nome">Tratamento Cronograma Capilar</p>
                    <p class="item-descricao">Nutrição profunda e reconstrução imediata com produtos de linha profissional.</p>
                </div>
                <p class="item-preco">R$ 120,00</p>
            </div>
        </div>

        <!-- Categoria 2: Especialidades / Estética se houver -->
        <div class="categoria-bloco">
            <h3 class="categoria-nome">Design & Estética</h3>
            
            <div class="item-menu">
                <div class="item-detalhes">
                    <p class="item-nome">Design de Sobrancelhas</p>
                    <p class="item-descricao">Alinhamento perfeito seguindo a proporção natural do seu olhar.</p>
                </div>
                <p class="item-preco">R$ 45,00</p>
            </div>

            <div class="item-menu">
                <div class="item-detalhes">
                    <p class="item-nome">Manicure & Alongamento</p>
                    <p class="item-descricao">Cutilagem fina e aplicação de técnicas de alongamento de alta durabilidade.</p>
                </div>
                <p class="item-preco">A partir de R$ 50</p>
            </div>
        </div>

        <!-- Rodapé -->
        <p class="footer">© 2026 ANDRESA FERREIRA STUDIO<br>Todos os direitos reservados.</p>

    </div>

</body>
</html>
