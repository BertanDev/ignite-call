# 📅 Ignite Call

Aplicação criada durante o curso Ignite da Rocketseat

Trata-se de uma aplicação de agendamento, integrado a api de agendamentos do google.
Todo agendamento criado no calendário de um usuário dentro da aplicação, ira refletir em seu calendário no Google Calendar.
O próprio usuário ao criar sua conta, define os horários em que outros poderão agendar compromissos com ele.

> É permitido pela aplicação, criar um agendamento com outro usuário, quando o horário cumpra as seguintes determinações:
> - O usuário tenha disponibilizado esse horário quando realizou seu cadastro
> - Não há nenhum outro agendamento(criado pelo Ignite Call) daquele usuário neste horário
> - O horário é posterior ao momento atual

## ▶️ Testando a aplicação

> Executar aplicação na máquina local:

 Para rodar a aplicação será necessária a conexão com um banco de dados local ou container Docker,
 além da criação do projeto no Google Cloud Platform para coletar as credenciais necessárias para login e integração com a plataforma Google.
 
 com o projeto em seu computador, rode na raíz:
 ```
 npm install
 ```
 em seguida:
 ```
 npm run dev
 ```
 O Next.js por padrão executa na port ```3000```, para mais informações da ferramenta, consulte a [documentação](https://nextjs.org/)
 
 > Utilizar projeto em funcionamento: [Ignite Call](https://nextjs-ignite-call.vercel.app/)
 
 ## 💠 Funcionalidades da aplicação
  - Realizar o cadastro do seu usuário
  - Conectar sua conta com sua agenda Google
  - Marcar um compromisso na agenda de outro usuário
  - Selecionar os dias e horario que outros usuários podem marcar compromissos com você
 
## 🔱 Ferramentas utilizadas
 - React JS com NextJS
 - TypeScript
 - Next auth
 - Next seo
 - Eslint
 - React hook form
 - Zod
 - Nookies
 - Phosphor react
 - Axios
 - Dayjs
 - Prisma ORM
 
 ### Tela inicial da aplicação | Cadastro 1/5
 ![home](https://user-images.githubusercontent.com/72395637/212488751-b2169026-ca8a-4b1d-b1de-e46c3ba9291a.JPG)

### Confirmação de username | Cadastro 2/5
![1-4](https://user-images.githubusercontent.com/72395637/212488921-12698aaf-5762-4692-a82d-d0450c0b2bd8.png)

### Conexão com agenda do google | Cadastro 3/5
![3-4](https://user-images.githubusercontent.com/72395637/212488976-3f076f31-dc97-43fc-9eb9-92b02d5ebe57.png)

### Seleção de horários com disponibilidade | Cadastro 4/5
![hortario](https://user-images.githubusercontent.com/72395637/212489328-d481850e-64c3-4566-9551-b5d332094d68.png)

### Sobre você | Cadastro 5/5
![5-5](https://user-images.githubusercontent.com/72395637/212490159-52c88c4f-d8a0-4d9c-a318-e1cbb51aadc5.png)

### Calendário do usuário com os dias e horários disponíveis
![c1](https://user-images.githubusercontent.com/72395637/212490194-4214cac0-84ff-4c94-b60d-1efd6dd626e8.png)

### Horários disponíveis dentro do dia selecionado
![c2](https://user-images.githubusercontent.com/72395637/212490256-9815d9a9-6ec4-48e7-b6d5-938d3b49c3f4.png)

### Confirmção da reserva na agenda do usuário
![c3](https://user-images.githubusercontent.com/72395637/212490388-cb2984b9-7f9f-4f0a-ace1-3c394a339adc.png)




 
 
 
 
