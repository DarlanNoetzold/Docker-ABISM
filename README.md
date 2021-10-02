# Docker-ABISM
## Projeto:
Pulgões de cereais (Hemiptera: Aphididae) são pragas economicamente importantes em todas as regiões produtoras de trigo do Brasil. Para ter medidas de controle ecologicamente corretas, como o controle biológico e diminuir a utilização de inseticidas se faz necessária a compreensão de sua dinâmica populacional. Para isso, a comunidade acadêmica realizou experimentos para desenvolver modelos de previsão ou sistemas especialistas para identificar a população, as taxas de crescimento e os danos decorrentes. A informática oferece uma maneira eficaz e eficiente de resolver os problemas complexos dos sistemas agrícolas, especialmente na dinâmica populacional. Embora estes sistemas sejam capazes de atender a necessidades específicas, ainda há muito a ser feito para melhorar uma representação mais detalhada da heterogeneidade espacial e seus impactos nas culturas e no desempenho ambiental. Este trabalho apresenta uma proposta de um framework de acoplamento entre modelos de simulação para que possam contribuir no entendimento das interações entre o patossistema vetor(pulgão)-vírus-planta. Ao integrar esses modelos de simulação pretende-se validar os resultados com dados oriundos de experimentos realizados a campo e, a partir disto, auxiliar na avaliação do impacto da aplicação de inseticida sobre a população de vetores e constatar a incidência da virose nas culturas.

## Desenvolvilemnto:
* Projeto de integração com a EMBRAPA e o IFSul no qual apliquei os seguintes conhecimentos e ferramentas:
* O modelo ABISM foi desenvolvido com Java.
* O gerenciamento de dados foi feito com PostgreSQL.
* Uso de API’s e arquivos JSON.
* Foi colocado em produção com Docker.
* Acoplamento com MPI.

## Execução:
 No repositório contém os arquivos utilizados na execução do ABISM através de um imagem no Docker Hub. 
 Para baixar a imagem:
 docker push darlannoetzold/abism:tagname
 <br>
 tagname: 5.1

---

⭐️ From [DarlanNoetzold](https://github.com/DarlanNoetzold)
