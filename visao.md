# Sleep Well - Documento do Projeto

## 1. Introdução
O **Sleep Well** é um aplicativo para monitoramento do sono e despertador inteligente, ajudando os usuários a acordarem no momento ideal e melhorarem a qualidade do sono.

## 2. Justificativa do Problema
O sono desempenha um papel fundamental no bem-estar das pessoas. Muitos enfrentam desafios como:
- Interrupção de ciclos do sono, resultando em fadiga e dificuldade de concentração.
- Falta de informações sobre os melhores horários para dormir e acordar.
- Carência de ferramentas intuitivas que auxiliem no monitoramento do sono.

## 3. Solução Proposta
O **Sleep Well** oferece um conjunto de funcionalidades para melhorar a rotina de descanso:
- **Monitoramento de Ciclos de Sono**: Sugestão de horários ideais para acordar.
- **Despertador Inteligente**: Configuração de alarmes baseados no fim dos ciclos.
- **Histórico de Sono**: Relatórios sobre padrões de sono ao longo do tempo.
- **Diário de Sonhos**: Registro de experiências durante o sono.
- **Dicas para Melhorar o Sono**: Recomendações personalizadas para otimizar a qualidade do sono.

## 4. Arquitetura do Sistema
O aplicativo segue a arquitetura MVVM:

![Diagrama da Arquitetura do Sistema](/arquiteturaSistemaSVG.svg)

## 5. Requisitos de Software e Casos de Uso
### 5.1 Usuários Identificados
- **Usuário Comum**: Utiliza o app para monitorar ciclos de sono e configurar despertadores.
- **Administrador**: Responsável pela manutenção do sistema e atualização de conteúdos.

### 5.2 Requisitos Funcionais
| **Requisito** | **Descrição** | **Critérios de Aceitação** |
|--------------|--------------|---------------------------|
| RF01 - Realizar Login | O usuário pode realizar login com e-mail e senha. | O sistema valida credenciais e permite acesso. |
| RF02 - Cadastro de Usuário | O sistema deve permitir cadastro de novos usuários. | O usuário insere nome, e-mail e senha. |
| RF03 - Monitoramento de Ciclos | O sistema calcula ciclos de sono baseados no horário de dormir. | Exibição de horários ideais para acordar. |
| RF04 - Configuração de Despertador | O usuário pode configurar um despertador baseado nos ciclos de sono. | O sistema sugere horários de acordo com ciclos de 90 minutos. |
| RF05 - Histórico de Sono | O usuário pode visualizar dados sobre seus padrões de sono. | Relatórios diários, semanais e mensais. |
| RF06 - Registro de Diário de Sonhos | O usuário pode registrar seus sonhos. | O sistema armazena e exibe os registros. |
| RF07 - Notificações de Alarme | O sistema envia alertas para acordar o usuário. | Notificações sonoras e visuais no horário configurado. |
| RF08 - Lembretes de Sono | O sistema avisa sobre horários recomendados para dormir. | Alertas configuráveis pelo usuário. |

## 6. Diagrama de Casos de Uso

![Diagrama de Casos de Uso](/casosDeUsoSleepWellSVG.svg)

## 7. Wireframe do Aplicativo


## 8. Considerações Finais
O **Sleep Well** combina tecnologia moderna e interface intuitiva para melhorar a qualidade do sono. Com funcionalidades inovadoras, ele permite aos usuários despertarem no momento ideal, acompanharem seu histórico de sono e adotarem hábitos saudáveis.
