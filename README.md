# att-tech-gantt

gantt
    title Projeto - Sistema de Cadastro de Empresas Parceiras
    dateFormat  YYYY-MM-DD
    axisFormat  %W
    excludes    weekends

    section Preparação
    Levantamento de requisitos        :a1, 2025-01-01, 14d
    Documentação funcional             :a2, after a1, 10d
    Protótipos de interface            :a3, after a2, 14d

    section Desenvolvimento
    Configuração do ambiente           :b1, after a3, 7d
    Criação do banco de dados          :b2, after b1, 7d

    section Entregas Crystal
    Entrega 1 - Login                  :milestone, 2025-01-21, 1d
    Entrega 2 - CRUD Empresas          :milestone, 2025-02-11, 1d
    Entrega 3 - Upload Logotipo        :milestone, 2025-02-25, 1d
    Entrega 4 - Relatórios PDF/Excel   :milestone, 2025-03-11, 1d
    Entrega 5 - Painel Administrativo  :milestone, 2025-03-25, 1d

    section Testes e Implantação
    Testes unitários e integração      :c1, 2025-04-01, 21d
    Testes de usabilidade              :c2, after c1, 14d
    Entrega Final - Sistema Implantado :milestone, 2025-06-30, 1d
