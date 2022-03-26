<p align="center">  
<img src="https://miro.medium.com/max/566/1*Dkmqx1iM4P15wthwBWGCEQ.gif" width="282"/>
</p>
# Os estágios do desenvolvimento seguro
O número e a ‘profundidade’ das medidas serão diferentes dependendo do nível de segurança que se deseja alcançar. Abaixo, você pode encontrar uma visão geral dos aspectos e práticas de desenvolvimento seguro comumente recomendados.

# Coleta, priorização e análise de requisitos
No estágio de coleta de requisitos, os especialistas preparam um perfil de risco do aplicativo. O documento descreve os possíveis pontos de entrada para invasores e categoriza os riscos por nível de gravidade, incluindo seu impacto e probabilidade.

Contando com o perfil de risco, bem como com as políticas e padrões de segurança e privacidade da organização, requisitos regulatórios (por exemplo, LGPD), analistas de negócios documentam requisitos.

# Projeto: modelagem de ameaças e planejamento de recursos
A modelagem de ameaças ocorre depois que a arquitetura de software de alto nível é projetada e os principais fluxos de dados e pontos de entrada de dados no aplicativo futuro são estabelecidos. Normalmente, inclui as seguintes etapas principais:

decompor a arquitetura planejada do aplicativo em componentes funcionais, determinando ameaças a cada um dos componentes;

categorizar e priorizar ameaças;

planejar e priorizar controles e contramedidas para possíveis ataques.

Com base nos requisitos de segurança e resiliência descritos e nas atividades de modelagem de ameaças, são planejados:

arquitetura de software segura (por exemplo, empregando particionamento de aplicativos, abordagem baseada em contêiner).

recursos de segurança (criptografia, auditoria/registro, identificação do usuário, verificação e autorização (baseada em senha, multifator, baseada em certificado, baseada em token, biométrica).

casos de teste a serem executados nas fases de teste e manutenção.

A modelagem de ameaças é tipicamente iterativa e abrange todo o ciclo de desenvolvimento, começando com uma arquitetura de alto nível (interação entre módulos de software), através do design de arquitetura detalhado e implementação (funções e métodos de código específicos).

# Desenvolvimento: práticas seguras de codificação, análise estática e revisão por pares regulares
Neste estágio, os desenvolvedores precisam:

empregar práticas de codificação seguras para mitigar ou minimizar vulnerabilidades de alto risco no nível de implementação;

usar apenas ferramentas de desenvolvimento seguras (bibliotecas, frameworks, etc.);

executar testes de unidade regulares;

realizar análises de código estático automatizadas;

fazer revisões de pares de código baseadas em listas de verificação específicas de um idioma para detectar tipos de vulnerabilidades que não podem ser identificadas por ferramentas de revisão de segurança automatizadas.

# Implantação e suporte: teste de penetração, revisão final de segurança e um plano de resposta a incidentes
O conjunto de práticas sugerido nesta etapa “pós-desenvolvimento” geralmente gira em torno desses tópicos:

realização de testes de penetração do software e de sua infraestrutura, correção de problemas de segurança identificados e condução de testes de regressão. Se o desenvolvimento de software for construído interativamente, essas atividades devem ser realizadas em cada construção.

revisão final de segurança por especialistas para verificar se os riscos de segurança identificados no curso das atividades de segurança anteriores foram devidamente tratados (corrigidos ou têm um plano de mitigação em vigor).

criação de um procedimento de resposta a incidentes;

configuração do monitoramento de segurança de aplicativos, realizando testes de regressão de segurança manuais e automatizados;

estabelecimento de um processo de feedback e ferramentas para usuários, hackers, etc. para relatar sobre vulnerabilidades reveladas.

# Resumindo
O desenvolvimento seguro visa garantir que as aplicações desenvolvidas sejam de fato seguras, de ponta a ponta. Ao mesmo tempo, ele diz respeito à operação de desenho e criação seja confiável, produtiva e livre de problemas.

Neste sentido, todas as etapas do desenvolvimento devem ter a segurança como eixo principal. Para isso, é importante que tudo seja realizado com foco na identificação de problemas, evitando os custos de remediar e impactos negativos.

Por fim, é bastante recomendável recorrer a especialistas no tema do desenvolvimento seguro, especialmente quando se busca técnicas, métodos e soluções de software para auxiliar nisto.

