# Requisitos funcionais 

&emsp; Requisitos funcionais definidos pelo grupo para o projeto deste módulo:

| **Identificador** | **Requisito** | **Classificação** |
|-------------------|---------------|-------------------|
| RF01 | O sistema deve identificar e classificar as fissuras. | Essencial |
| RF02 | O sistema deve permitir o upload de arquivos para a identificação e classificação. | Essencial |
| RF03 | O sistema deve fazer análise das imagens de forma síncrona. | Desejável |
| RF04 | O sistema deve guardar o histórico de todas as expedições. | Essencial |
| RF05 | O sistema deve mostrar as estatísticas sobre as expedições. | Importante |
| RF06 | O sistema deve relacionar as fissuras detectadas com suas possíveis causas. | Desejável |
| RF07 | O sistema deve identificar a espessura da fissura. | Desejável |
| RF08 | O sistema deve ter um mecanismo de login. | Importante |

***

# Requisitos não funcionais

| **Identificador** | **Requisito Funcional Associado** | **Descrição** | **Método de Teste** |
|-------------------|-----------------------------------|---------------|---------------------|
| RNF01 | RF03 | O tempo de delay entre a imagem real e a recebida pelo computador deve ser inferior a 3 segundos.| É preciso medir em segundos o tempo de atualização da imagem, uma maneira de fazer isso é iniciar um timer em qualquer dispositivo eletrônico, rodar o drone 90º e medir a diferença de tempo entre o fim da movimentação real do drone e a apresentada na tela.|
| RNF02 | RF01 | O processo de identificação de fissuras deve apresentar uma taxa de verdadeiros positivos acima de 80%. | Utilizar imagens diferentes das utilizadas para treinamento para testar a eficácia do modelo, como por exemplo imagens que possuam diferentes luminosidades, tamanhos de fissuras e cores de fundo.|
| RNF03 | RF02 | O sistema deve suportar o upload de arquivos de no mínimo 10 MB sem falhas ou travamentos. |Realizar testes de upload utilizando arquivos de tamanhos variados (5 MB, 10 MB, 15 MB) e verificar se o sistema realiza o upload corretamente, sem apresentar erros ou lentidão excessiva.|

