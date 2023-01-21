
## 💻 Dev Freela Payments Microservice

Repository developed during the ASP .NET Core course maintained by the company [Luis Dev](https://www.linkedin.com/in/luisdeol/). This project was developed in the microservices module of the course, to simulate a payments microservice from the project [DevFreela](https://github.com/AllanDutra/dev-freela) using RabbitMQ.

## 📫  Routes

### Payments Controller

<img src="https://img.shields.io/badge/-POST-%2349CC90" height="30" />

**"/api/payments"**

_Simulates the processing of a payment microservice_

**body:**

```
{
  "idProject": int,
  "creditCardNumber": string,
  "cvv": string,
  "expiresAt": string,
  "fullName": string,
  "amount": decimal
}
```

**response:**

_No content_

## 🌐 Status
<p>Finished project ✅</p>

## 🧰 Prerequisites

- .NET 7.0 or +

- RabbitMQ

## 🔧 Installation
`$ git clone https://github.com/AllanDutra/dev-freela-payments.git`

`$ cd dev-freela-payments/DevFreela.Payments.API`

`$ dotnet restore`

`$ dotnet run`

**Server listenning at  [http://localhost:5001/](http://localhost:5001/)!**

## 🔨 Tools used

<div>
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/csharp/csharp-original.svg" width="80" /> 
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/dotnetcore/dotnetcore-original.svg" width="80" />
<img src="https://cdn.freebiesupply.com/logos/large/2x/rabbitmq-logo-png-transparent.png" height="80" />

</div>
