Projeto de Phishing com ESP32

Visão Geral
O Projeto de Phishing com ESP32 é uma ferramenta educacional projetada para demonstrar como ataques de phishing podem ser conduzidos usando um microcontrolador ESP32. Este projeto visa aumentar a conscientização sobre ameaças de segurança cibernética e educar os usuários sobre a importância de proteger suas redes e dispositivos.

Recursos

Portal Cativo: O ESP32 cria um ponto de acesso Wi-Fi com um portal cativo que imita uma página de login legítima.
Captura de Credenciais: Armazena as credenciais inseridas para análise e propósitos educacionais.
Registro de Dados: Registra as credenciais capturadas em uma memória interna para posterior análise.
Interface Amigável: Interface simples e fácil de usar, permitindo a configuração rápida e eficiente.

Instalação

Clone este repositório: git clone https://github.com/seu-usuario/seu-repositorio.git
Abra o projeto na IDE do Arduino.

Instale as seguintes bibliotecas:

WiFi.h
WebServer.h
DNSServer.h
FS.h
SPIFFS.h

Configure suas credenciais de Wi-Fi no código.
Carregue o código no seu ESP32.

Uso
Ligue o ESP32 e conecte-se ao ponto de acesso Wi-Fi criado pelo dispositivo.
Acesse a página de login através do navegador.
Insira as credenciais para ver o funcionamento do portal cativo.
As credenciais inseridas serão registradas para análise educacional.
Para ver as senhas salvas, adicione /list na barra de endereço do navegador para acessar a lista de credenciais salvas.

Aviso Legal
Este projeto é estritamente para fins educacionais. O uso desta ferramenta para fins maliciosos ou ilegais é estritamente proibido. O autor não se responsabiliza por qualquer uso inadequado deste projeto.

