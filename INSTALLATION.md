# 🔥 Cordova FCM Plugin - 2025 Updated

## 🚀 Instalação Rápida

```bash
# Método 1: Instalar diretamente do GitHub (Recomendado)
cordova plugin add https://github.com/Vinidev-AL/cordova-plugin-fcm-with-dependecy-updated

# Método 2: Clonar e instalar localmente
git clone https://github.com/Vinidev-AL/cordova-plugin-fcm-with-dependecy-updated.git
cordova plugin add ./cordova-plugin-fcm-with-dependecy-updated
```

## ✅ Compatibilidade

- ✅ **Cordova Android**: 14.0.1+
- ✅ **Android API**: 34+
- ✅ **Firebase BOM**: 32.7.0+
- ✅ **Google Services**: 4.4.0+
- ✅ **Gradle**: 8.x
- ✅ **Firebase iOS**: 10.0+

## 🎯 Principais Melhorias

1. **Dependências Modernas**: Firebase BOM 32.7.0, Google Services 4.4.0
2. **Gradle 8.x**: Compatibilidade total com versões atuais
3. **Android 12+**: Atributo `android:exported` corrigido
4. **Repositórios Atualizados**: Removido jcenter descontinuado
5. **Build Otimizado**: Configurações simplificadas

## 🔧 Teste Rápido

Após a instalação, teste no console do navegador:

```javascript
// Verificar disponibilidade
console.log("FCM disponível:", typeof FCM !== 'undefined');

// Obter token
FCM.getToken(function(token) {
    console.log("Token FCM:", token);
});

// Configurar listener
FCM.onNotification(function(data) {
    console.log("Notificação:", data);
});
```

## 📖 Documentação Completa

Veja o arquivo `README-2025-UPDATES.md` para documentação detalhada.

## 🐛 Issues

Reporte problemas em: https://github.com/Vinidev-AL/cordova-plugin-fcm-with-dependecy-updated/issues

---

⭐ **Se funcionou para você, deixe uma estrela no GitHub!**
