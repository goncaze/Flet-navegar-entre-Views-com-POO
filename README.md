# A flet_views_poo Flet app

Depois de muitos testes procurei escrever este pequeno exemplo de como fiz para lidar com o paradigma da programação orientada a objeto (POO) no Flet.

Criei uma classe App que é instanciada no arquivo main.py pela função main. No passo seguinte, em três módulos criei classes que herdam de ft.View para organizar os componentes visuais (ViewUm, ViewDois e ViewTrês).

Para além do uso de telas em diferentes módulos e classes, empreguei o uso de TemplateRoute do Flet para demonstrar a passagem de dados entre as diferentes instâncias de views.

Ao executar o projeto: haverá quatro botões. Dois para redirecionamento entre as telas e dois para demonstrar a passagem de um id.

Advertência: não sei se esta é a melhor maneira de usar POO com flet, mas depois de tanto pesquisar e testar foi o que consegui fazer de melhor até agora.


To run the app:

```
flet run [app_directory]
```