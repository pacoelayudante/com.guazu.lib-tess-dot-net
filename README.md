_Unity Game Engine Package_
# Lib Tess Dot Net
#### _extraído del https://github.com/speps/LibTessDotNet de Rémi Gillig_
###### _convertido en unity package por Paco Álavarez Lojo de [Team Guazú](https://teamguazu.com/)_

Version para C# del famoso Teselador GLU, esto es un repo que no hace mas que agregar el `package.json` para el Unity UPM. Mas abajo explico como _instalarlo_ usando el [Unity Package Manager](https://docs.unity3d.com/Manual/upm-ui.html) (versiones mayor a `2018.1`)

Con este teselador se pueden describir contornos arbitrarios, combinarse entre si o calar una figura de otra, para luego extraer una descripcion de la figura resultante como una serie de poligonos convexos, ideal para renderizar o realizar otros procesos.

Para ver una explicación mas detallada de la libraria, vistá el repositorio original: [LibTessDotNet](https://github.com/speps/LibTessDotNet)

## Instalación usando el UPM
Abrir `<project>/Packages/manifest.json` y agregar el scope para los paquetes de guazu.
```json
{
  "scopedRegistries": [
    {
      "name": "Paquetes de Guazu",
      "url": "https://registry.npmjs.org/",
      "scopes": [
        "com.guazu"
      ]
    }
    // ...
  ],
  "dependencies": {
    // ...
  }
}
```

Luego en el Unity Editor abrir `Window > Package Manager` y podras ver los paquetes de Guazu listos para ser instalados