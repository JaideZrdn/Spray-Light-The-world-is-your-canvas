# Spray-Light-The-world-is-your-canvas

**Spray Light**, vejas seus grafites ganharam vida com Realidade Aumentada!

Nós vivemos em um espaço que está cada vez mais sendo tomado por prédios altos, céu cinza, multidões andando de um lado para o outro onde todas essas pessoas estão sempre ocupadas em uma espécie de "piloto automático".

No meio de toda essa monotonia existe o grafite, ele é uma arte feita para ser vista, ser apreciada, porém, muitos grafiteiros não conseguem obter tal reconhecimento e acabam sendo mal vistos pela sociedade onde ele tinha o simples e belo papel de colorir um pouco o dia de alguém.

Então, buscando ressignificar como a sociedade enxerga o Grafite e tirar um pouco desse "piloto automático" criamos o *Spray Light*.

No *Spray Light* você consegue **espalhar** grafites pelos muros da cidade, fazendo com que seja possível a visualização deles usando **Realidade Aumentada**. A cada grafite que você posiciona um **pin** é deixado no **mapa** para você lembrar onde postou, ao chegar perto e ativar o modo de AR conseguirá vê-los.

Com ele, buscamos **mudar** um pouco a **visão marginalizada** que a sociedade tem perante o grafite e também **estimular** que **novos grafiteiros** surjam, colocando incialmente suas artes de **modo virtual!**

Spray Light está disponível para download na AppStore!

Sobre as tecnologias usadas:
- **SwiftUI**: Para o desenvolvimento da UI do App no geral
- **RealityKit & ARKit**: Para gerenciar quaisquer processos envolvendo toda a dinâmica de Realidade Aumentada como o post, translação, rotação do objeto, criação de novas entidades entre outras tarefas.
- **SwiftData & DTO**: Para salvar os graffitis localmente e Data Transfer Object (DTO) para realizar uma transferência segura de dados pelo aplicativo usando Sendables
- **UIKit**: Usado para iniciar as ARView em UIViewRepresentables
- **TipKit**: Para facilitar a experiência do usuário e o entendimento de algumas features durante o uso do app

Em versões testes que não entraram no MVP disponível na AppStore:
- **CloudKit**: Testes de compartilhamento via nuvem de ARWorldMap
