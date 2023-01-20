# Central de Ferramentas
![Captura de tela_20230119_210710](https://user-images.githubusercontent.com/119439605/213599980-c82b9ed9-86db-449c-b054-cd4ba73c7b26.png)

Esta é uma interface gráfica conectada ao banco de dados no PostgreSQL para gerenciar o empréstimo de ferramentas aos técnicos já cadastrados.

O programa apresenta as operações de cadastro, atualização, consulta e exclusão tanto para técnicos como para as ferramentas presentes na central da empresa. Sendo possível a verificação se o cpf e o número de contato informado durante o cadastrado são válidos.

![Captura de tela_20230119_211200](https://user-images.githubusercontent.com/119439605/213600611-d3842c43-2777-4e86-9861-5df460f7a561.png)

![Captura de tela_20230119_211431](https://user-images.githubusercontent.com/119439605/213600648-b3b87ced-8496-47c5-bb60-6fb480074f7b.png)


Além de possibilitar fazer reservas, consultá-las e excluí-las (sobre a condição de que o pedido da exclusão da reserva seja feito antes da retirada ou após a devolução), também é possível exportar um arquivo excel com a lista de reservas feitas. Podendo ser distribuído o arquivo para as diferentes equipes de técnicos da empresa e assim fazerem o planejamento.

![Captura de tela_20230119_211809](https://user-images.githubusercontent.com/119439605/213601455-404b2b14-d0d7-469f-b782-30eb2b2d57fd.png)


Os pacotes usados foram: Tkinter, Tkcalendar, Datetime, Psycopeg 2, Pandas.

Segue link para um vídeo demonstrativo --> https://www.youtube.com/watch?v=Z5KsAPTGkCU

OBS: No momento ainda não foi criado um banco com acesso remoto, apenas local.


![Captura de tela_20230119_211934](https://user-images.githubusercontent.com/119439605/213602237-3a00d91c-edac-453d-8616-9a50216f11c7.png)
