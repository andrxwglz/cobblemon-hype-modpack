# Cobblemon HYPE — Modpack oficial

Repositorio de distribución del **modpack de cliente** de [Cobblemon HYPE](https://cobblemonhype.com/).

- **Servidor Minecraft:** `play.cobblemonhype.com`
- **Minecraft Java:** 1.21.1
- **Fabric Loader:** 0.20.1
- **Launcher:** Cobblemon HYPE Launcher
- **Distribución:** [GitHub Releases](https://github.com/andrxwglz/cobblemon-hype-modpack/releases)

## Publicación inicial del modpack

El launcher detecta una **Release pública y estable** y busca dentro de ella un archivo que se llame **exactamente** `Cobblemon-HYPE-Modpack.zip`.

1. Pulsa **[Crear una Release](https://github.com/andrxwglz/cobblemon-hype-modpack/releases/new)**.
2. Crea el tag `pack-v1.0.0`, selecciona `main` y pon de título `Modpack HYPE 1.0.0`.
3. Adjunta como *asset* el ZIP de cliente depurado, renombrado a `Cobblemon-HYPE-Modpack.zip`. No extraigas el ZIP.
4. Publica una versión normal: **no** marcada como *pre-release*.
5. Comprueba que aparece el ZIP en la lista **Assets**.

**No subas el ZIP como archivo normal del repositorio**, ya que contiene binarios grandes. Adjunta el archivo únicamente a una Release.

### ZIP de cliente preparado para la primera publicación

- Tamaño esperado: **243092820 bytes**
- SHA-256 esperado: `d744ab88a5de6db04f1b537ddb801cc741caa2f8f0849cd8e95206e0a08e2800`

El hash corresponde a `Cobblemon-HYPE-Modpack-CLIENTE-v0.2.zip` preparado durante la configuración. Si publicas un ZIP nuevo o modificado, el hash cambiará (es normal).

## Próximas actualizaciones

Publica otra Release estable con tag distinto, por ejemplo `pack-v1.0.1`, que contenga un nuevo archivo **con el mismo nombre exacto** `Cobblemon-HYPE-Modpack.zip`. El launcher comprobará el SHA-256 que GitHub asigna al asset, descargará la nueva versión y la instalará.

**Nota:** las actualizaciones descargan el ZIP completo; no son diferenciales. Los usuarios conservan el método de importación local como alternativa.

## Distribución y privacidad

Publica únicamente los archivos de cliente que tengas derecho a redistribuir (licencias de los mods, paquetes de recursos y otros contenidos). No incluyas partidas, registros, credenciales, información privada ni configuraciones de servidor.

Este proyecto comunitario no es oficial de Mojang ni de Microsoft.
