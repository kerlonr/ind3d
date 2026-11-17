<div align="center">

# 🖨️ Ind3D

**Painel de acesso às impressoras 3D: abre a interface de controle e a câmera ao vivo de cada máquina.**

[![Site](https://img.shields.io/badge/Acessar_site-ind3d.vercel.app-799EEB?style=for-the-badge&logo=googlechrome&logoColor=white)](https://ind3d.vercel.app)

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)

</div>

---

## Sobre

O **Ind3D** reúne num só lugar o acesso às impressoras 3D da oficina. Cada card mostra uma
impressora com dois botões:

- **Acessar**: abre a interface web de controle da impressora
- **Assistir**: abre a câmera para acompanhar a impressão ao vivo

## Impressoras

| Card | Máquina |
|---|---|
| Ender 3 V3 | Creality Ender 3 V3 SE |
| Laranja | impressora identificada pela cor |
| K1 Max | Creality K1 Max |
| Ender 3 S1 | Creality Ender 3 S1 |
| Azul | impressora identificada pela cor |

Links ainda não configurados levam para a página `404.html` ("Estamos trabalhando nisso").

## Estrutura

```text
.
|-- index.html     cards das impressoras
|-- style.css
`-- 404.html       página para links ainda não configurados
```

## Rodando Localmente

Projeto estático, sem dependências: basta abrir o `index.html` no navegador.
