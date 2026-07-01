# 🖥️ Enviar Hostname

Um aplicativo web simples e elegante para enviar informações do dispositivo para o [ntfy.sh](https://ntfy.sh), um serviço de notificações push gratuito.

🌐 **Site ao vivo:** [https://rubenbruno89.github.io/enviar-hostname/](https://rubenbruno89.github.io/enviar-hostname/)

## 📋 Sobre

Este projeto foi criado para facilitar o registro e identificação de dispositivos em ambientes de formatação e configuração de máquinas. Permite enviar rapidamente o hostname e informações do dispositivo para um tópico do ntfy.sh, onde podem ser consultados posteriormente.

## ✨ Funcionalidades

- ✅ **Envio de informações completas** do dispositivo:
  - Hostname/Identificador personalizável
  - Plataforma (Windows, Linux, macOS, Android, iOS, etc.)
  - Navegador utilizado
  - Idioma do sistema
  - Resolução da tela
  - Data e hora do envio

- ✅ **Tópicos personalizáveis** - Escolha para qual tópico do ntfy.sh enviar as notificações
- ✅ **Salvamento automático** - O tópico escolhido fica salvo no navegador
- ✅ **Notificações visuais** - Toast notifications confirmam o envio
- ✅ **Design responsivo** - Funciona perfeitamente em celulares, tablets e desktops
- ✅ **100% client-side** - Não requer servidor backend
- ✅ **Interface moderna** - Design com gradientes e animações suaves

## 🚀 Como Usar

### Online (Recomendado)

1. Acesse: [https://rubenbruno89.github.io/enviar-hostname/](https://rubenbruno89.github.io/enviar-hostname/)
2. Configure o tópico do ntfy.sh (padrão: `vixti`)
3. Digite ou confirme o hostname/identificador
4. Clique em "Enviar para ntfy.sh"
5. Pronto! A notificação será enviada

### Localmente

1. Clone este repositório:
```bash
git clone https://github.com/rubenbruno89/enviar-hostname.git
