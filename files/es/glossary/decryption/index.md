---
title: Descifrado
slug: Glossary/Decryption
tags:
  - Criptografía
  - Glosario
  - Seguridad
  - privacidad
translation_of: Glossary/Decryption
original_slug: Glossary/Descifrado
---

En {{glossary("cryptography" ,"criptografía")}}, el descifrado es la conversión de {{glossary("Ciphertext", "texto cifrado")}} en {{glossary("Plaintext", "texto simple")}}.

El descifrado es una primitiva criptográfica: transforma un mensaje de texto cifrado en texto simple utilizando un algoritmo criptográfico llamado {{glossary("cipher", "cifrado")}}. Al igual que el cifrado, el descifrado en cifrados modernos se realiza mediante un algoritmo específico y una {{glossary("Key", "clave")}}. Dado que el algoritmo suele ser público, la clave debe permanecer secreta si el cifrado se mantiene seguro.

![The decryption primitive.](https://mdn.mozillademos.org/files/9817/Decryption.png)

El descifrado es el reverso del {{glossary("Encryption", "cifrado")}} y si la clave permanece secreta, el descifrado sin conocer el secreto específico, entonces el descifrado es matemáticamente difícil de realizar. El grado de dificultad depende de la seguridad del algoritmo criptográfico elegido, que está en constante evolución mediante el progreso del {{glossary("cryptanalysis", "criptoanálisis")}}.

## Saber más

### Referencia técnica

- [Cifrado y descifrado](/es/docs/Archive/Security/Encriptación_y_Desencriptación)
