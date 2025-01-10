# Amazon Rekognition

[PDF](https://docs.aws.amazon.com/pt_br/prescriptive-guidance/latest/image-classification/image-classification.pdf#rekognition)[RSS](https://docs.aws.amazon.com/pt_br/prescriptive-guidance/latest/image-classification/image-classification.rss)



Para classificação de imagens no espectro visível, os modelos são frequentemente criados com aprendizado por transferência e ajuste fino de uma rede neural pré-treinada. Você pode automatizar a tarefa de seleção e treinamento de rede usando o serviço [Amazon Rekognition](https://docs.aws.amazon.com/rekognition/latest/dg/what-is.html).

O Amazon Rekognition fornece um conjunto padrão de rótulos de classificação. Um *rótulo* é um objeto ou conceito (incluindo cenas e ações) encontrado em uma imagem ou vídeo com base em seu conteúdo. Por exemplo, uma imagem de pessoas em uma praia tropical pode conter rótulos como `Palm Tree` (objeto), `Beach` (cena), `Running` (ação) e `Outdoors` (conceito). Para obter mais informações sobre os rótulos compatíveis com o Amazon Rekognition[, consulte Detecção](https://docs.aws.amazon.com/rekognition/latest/dg/labels.html) de objetos e conceitos na documentação do serviço.

Para tarefas que exigem rótulos padrão no Amazon Rekognition, vale a pena testar esse serviço. Se o Amazon Rekognition puder atender aos seus requisitos, a seleção, o treinamento e a manutenção do modelo serão resumidos. Ele fornece um serviço pré-treinado para inferência e AWS gerencia a manutenção do serviço. Obter previsões do Amazon Rekognition é simples.

A seguir estão as vantagens do Amazon Rekognition:

- Imediatamente disponível e escalável
- Não é necessário treinamento ou configuração
- Suporta classificação de vários rótulos

A seguir estão as desvantagens do Amazon Rekognition:

- Conjunto fixo de classes previstas
- As unidades de inferência oferecem grandes quantidades de capacidade, e a menor unidade pode ser cara para uma pequena taxa de transferência

Para obter mais informações, consulte:

- [Introdução ao Amazon Rekognition no Guia do desenvolvedor do](https://docs.aws.amazon.com/rekognition/latest/dg/getting-started.html) *Amazon Rekognition*
- [DetectLabels](https://docs.aws.amazon.com/rekognition/latest/APIReference/API_DetectLabels.html)na Referência do *Amazon Rekognition API*