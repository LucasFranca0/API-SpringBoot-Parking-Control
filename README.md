# Parking Control
API REST para controle de vaga de estacionamento. Conexão com banco de dados My SQL usando Java e o framework Spring Boot.

** **

### Visão geral do sistema

Pequeno sistema (API REST) de gerenciamento de vagas de estacionamento de um apartamento, com os seguintes casos de uso:

 **CRUD**
- [x] Paginação
- [x] Buscar pelo id
- [x] Inserir 
- [x] Deletar 
- [x] Alterar

<table>
<tr>
	<th>Ferramenta</th>
	<th>Versão</th>
</tr>
<tr>
	<td>Java JDK</td>
	<td>8+</td>
</tr>
<tr>
	<td>Git</td>
	<td>2.**</td>
</tr>
<tr>
	<td>Maven</td>
	<td>7.**</td>
</tr>
<tr>
	<td>Postman</td>
	<td>9.**</td>
</tr>
</table>


#### Configurações do banco de dados

```
spring.datasource.url= jdbc:mysql://localhost:3306/parking_control_db
spring.datasource.username= root
spring.datasource.password=
spring.jpa.hibernate.ddl-auto=update

spring.jpa.properties.hibernate.jdbc.lob.non_contextual_creation=true
```

<h3>Tecnologias Utilizadas</h3>

<table>
<tr>
	<th>Dependência</th>
	<th>Versão</th>
</tr>
<tr>
	<td>spring initialzr</td>
	<td><a href="https://start.spring.io/">https://start.spring.io/</a></td>
</tr>
<tr>
	<td>spring-boot-starter-web</td>
	<td>2.7.5</td>
</tr>
<tr>
	<td>spring-boot-starter-data-jpa</td>
	<td>2.7.5</td>
</tr>
<tr>
	<td>lombok</td>
	<td>1.18.24</td>
</tr>
<tr>
	<td>my sql driver</td>
	<td></td>
</tr>
</table>

### Postman documentação
https://documenter.getpostman.com/view/23628011/2s84LNUYUL
