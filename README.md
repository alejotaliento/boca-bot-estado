# boca-bot-estado

Interruptor del bot. El bot lee `estado.json` al iniciar y cada minuto mientras busca.

```json
{
  "activo": true,
  "mensaje": "",
  "bloqueados": []
}
```

- `activo`: `true` el bot funciona, `false` no arranca y el que está buscando se detiene.
- `mensaje`: texto que ven los usuarios cuando está en `false` (ej. `"Vuelve el sábado"`). Opcional.
- `bloqueados`: IDs de PC (los que muestra la app, ej. `"K7QD-92MA-X4TP-0LZB"`) a los que se les corta el acceso. Opcional.

Para cambiarlo: abrí el archivo en github.com (o en la app de GitHub del celu), lápiz de editar, cambiá el valor y
"Commit changes". Tarda 1-3 minutos en tomarse (GitHub Pages publica y propaga).

Este repo es público: no pongas nombres ni datos de nadie, sólo IDs de PC.
