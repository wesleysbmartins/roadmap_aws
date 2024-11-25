# Roadmap Cloud AWS
A Cloud Computing ou computação em nuvem é uma tecnologia que permite acessar recursos de computação como servidores, armazenamento de dados, redes e software pela internet, em vez de usar recursos locais no seu computador ou data center físico. De forma simples, em vez de comprar e manter servidores caros, você "aluga" os recursos que precisa de provedores de nuvem, você paga apenas pelo que usa, como se fosse uma conta de energia elétrica.

A AWS (Amazon Web Services) é um dos maiores provedores de serviços de nuvem do mundo, criado pela Amazon em 2006. Ela oferece uma ampla variedade de serviços em nuvem, que vão desde infraestrutura básica como servidores e armazenamento até soluções mais avançadas como inteligência artificial, big data e IoT.

A AWS foi pioneira na popularização da computação em nuvem, ajudando empresas a economizar custos e a inovar rapidamente.

## Vantagens

- **Escalabilidade**: Você pode aumentar ou diminuir os recursos conforme a necessidade. Por exemplo, durante a Black Friday, um site pode "escalar" para suportar mais visitantes e, depois, reduzir os recursos para economizar.

- **Acesso remoto**: Você pode acessar os recursos de qualquer lugar do mundo, desde que tenha internet.

- **Economia de custos**: Sem necessidade de comprar hardware caro, você reduz gastos iniciais e a manutenção dos servidores é feita pelo provedor.

- **Pagamento sob demanda**: Você paga pelo que usa, seja por hora, mês ou volume de dados.

- **Confiabilidade**: Provedores de nuvem costumam ter redundância e backup de dados, reduzindo riscos de perda.

## Principais Recursos da AWS

- **IAM (Identity and Access Management)**: Gerenciamento de acesso e segurança. Possibilitando controlar quem pode acessar os recursos da sua conta AWS.
    > [Documentação para criar sua conta AWS e configurar seu IAM.](https://docs.aws.amazon.com/pt_br/IAM/latest/UserGuide/getting-started-account-iam.html).

- **EC2 (Elastic Compute Cloud)**: Servidores virtuais para hospedar aplicações.

    Para este recurso eu desenvolvi uma aplicação e a hospedei em um servidor Linux Ubuntu, onde usando o Jenkins eu implementei uma Pipeline de CI/CD para automatizar atualizações em produção, onde minha aplicação estava sendo executada em um container Docker.

    Para tornar a aplicação acessível eu configurei uma porta através do Security Groups, onde eu uso o DNS ou IP publico da maquina e a porta para acessar a aplicação, por exemplo **"http://aws-dns.com:8000"**.

    > [Aplicação de exemplo com Jenknsfile na raiz do projeto.](https://github.com/wesleysbmartins/node_with_jenkins)

    > [Documentação para criar seu EC2.](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/EC2_GetStarted.html?icmpid=docs_ec2_console)
