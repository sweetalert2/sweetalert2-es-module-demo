# Demonstration of using [SweetAlert2](https://github.com/sweetalert2/sweetalert2) with [ECMAScript modules](https://jakearchibald.com/2017/es-modules-in-browsers/)

[![Build Status](https://github.com/sweetalert2/sweetalert2-es-module-demo/workflows/test/badge.svg)](https://github.com/sweetalert2/sweetalert2-es-module-demo/actions)

[![Netlify Status](https://api.netlify.com/api/v1/badges/f4a5ac2c-af3e-4512-b5f9-7f88359be571/deploy-status)](https://app.netlify.com/sites/sweetalert2-es-module-demo/deploys)

```html
<script type="module">
  import Swal from './sweetalert2/src/sweetalert2.js'
  Swal.fire('Hi from ES module!')
</script>
```

---

Live demo: https://sweetalert2-es-module-demo.netlify.app/
