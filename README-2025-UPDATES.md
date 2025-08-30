# Cordova FCM Plugin - 2025 Updated Version

Este é um fork atualizado do plugin `cordova-plugin-fcm-with-dependecy-updated` especificamente modificado para compatibilidade com:

## Versões Compatíveis

- **Cordova Android**: 14.0.1+ (Android API 34)
- **Firebase BOM**: 32.7.0+ (versão mais recente)
- **Google Services**: 4.4.0+
- **Android Gradle Tools**: 8.2.0+
- **Firebase iOS**: 10.0+

## Principais Alterações

### Android
- ✅ Firebase BOM atualizado de `26.0.0` para `32.7.0`
- ✅ Google Services atualizado de `4.3.4` para `4.4.0`
- ✅ Android Gradle Tools atualizado de `4.1.0` para `8.2.0`
- ✅ FCM Version atualizado de `21.0.0` para `23.4.0`
- ✅ Removido suporte para versões antigas do Gradle (< 5.0)
- ✅ Removido jcenter (descontinuado) dos repositórios
- ✅ Adicionado gradlePluginPortal() para melhor compatibilidade
- ✅ Corrigido android:exported para Android 12+

### iOS
- ✅ Firebase dependency atualizada para `~> 10.0`
- ✅ Mantida compatibilidade com versões modernas do iOS

### Compatibilidade de Engine
- ✅ Cordova mínimo: `12.0.0` (era `8.1.0`)
- ✅ Cordova Android mínimo: `12.0.0` (era `6.4.0`)
- ✅ Cordova iOS mínimo: `7.0.0` (era `5.0.0`)

## Instalação

```bash
# Instalar diretamente do GitHub
cordova plugin add https://github.com/Vinidev-AL/cordova-plugin-fcm-with-dependecy-updated

# Ou clonar e instalar localmente
git clone https://github.com/Vinidev-AL/cordova-plugin-fcm-with-dependecy-updated.git
cordova plugin add ./cordova-plugin-fcm-with-dependecy-updated
```

## Configuração de Dependências

Se você quiser customizar as versões, adicione no seu `package.json`:

```json
{
  "cordova": {
    "plugins": {
      "cordova-plugin-fcm-updated-2025": {
        "ANDROID_FIREBASE_BOM_VERSION": "32.7.0",
        "ANDROID_GOOGLE_SERVICES_VERSION": "4.4.0",
        "ANDROID_GRADLE_TOOLS_VERSION": "8.2.0",
        "ANDROID_FCM_VERSION": "23.4.0"
      }
    }
  }
}
```

## Problemas Resolvidos

- ✅ Build failures com Cordova Android 14+
- ✅ Incompatibilidade de versões do Firebase BOM
- ✅ Problemas com Gradle 8.x
- ✅ Uso de repositórios descontinuados (jcenter)
- ✅ Dependências desatualizadas do Google Services

## Notas Importantes

1. **Backup**: Sempre faça backup do seu projeto antes de atualizar plugins
2. **Teste**: Teste as notificações push após a instalação
3. **Google Services**: Certifique-se de que seu `google-services.json` está atualizado
4. **Firebase Console**: Verifique se seu projeto Firebase está usando versões compatíveis

## Créditos

## 🔗 Repositório

**GitHub:** https://github.com/Vinidev-AL/cordova-plugin-fcm-with-dependecy-updated

## 🏆 Créditos

Baseado no trabalho original de:
- André Augusto Tissot (cordova-plugin-fcm-with-dependecy-updated)
- Felipe Nascimento (cordova-plugin-fcm)

Atualizado para compatibilidade 2025 por **Vinidev-AL** com suporte à:
- Cordova Android 14.0.1+
- Firebase BOM 32.7.0+
- Android API 34
- Gradle 8.x

**🔥 Dica:** Execute `runCompleteTest()` sempre que quiser verificar o status completo do FCM!
