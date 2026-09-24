# cerbsim_ngapp_style

CerbSIM design system for ngapp: raw palette, light/dark semantic tokens as CSS
custom properties, IBM Plex fonts, Quasar brand mapping and component classes.

```python
import cerbsim_ngapp_style as cb
cb.install(app)          # once after App.__init__
bar.ui_class = cb.app_bar
```

Only depends on `ngapp`, so it is usable in pyodide frontends.
