# Fakedatajs
Validar CPF com java script 
const faker = require('faker');

const gerarDados = () => {
  const nome = faker.name.findName();
  const endereco = faker.address.streetAddress();
  const cidade = faker.address.city();
  const estado = faker.address.state();
  const cep = faker.address.zipCode();
  const telefone = faker.phone.phoneNumber();
