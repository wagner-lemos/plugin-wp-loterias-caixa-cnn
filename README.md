### Plugin Wordpress Loterias Caixa - CNN

Plugin Wordpress desenvolvido para o portal CNN, tem como objetivo consultar todas as loterias da caixa, e ter como retorno os resultados.

#### Funcionalidades
```
• Exibição de resultados das loterias da Caixa Econômica Federal.
• Layout dos resultados.
• Suporte para shortcodes e widgets.
• Cache de resultados para otimizar o desempenho.
```
#### Instalação
```
• Baixe o plugin, copie para dentro da pasta de plugins do Wordpress, e ative.
```
#### Exemplo de uso
```php
[loterias loteria="megasena" concurso="2500"]
```
• Para incluir o shortcode em um arquivo PHP, utilize a seguinte função nativa do WordPress:
```php
 <?php echo do_shortcode('[loterias loteria="lotofacil" concurso="2500"]'); ?>
```
#### O parâmetro "concurso" nao é obrigatório, caso o campo esteja vazio ele traz o último concurso

• No parâmentro "loteria" adicione a loteria desejada. Abaixo loterias compatíveis:
```
  "maismilionaria", "megasena", "lotofacil", "quina", "lotomania", "timemania", "duplasena", "federal", "diadesorte", "supersete"
```