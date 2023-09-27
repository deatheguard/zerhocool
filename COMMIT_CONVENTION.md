# 📌 Git Commit Message Convention

> This is adapted from [Angular's commit convention](https://github.com/conventional-changelog/conventional-changelog/tree/master/packages/conventional-changelog-angular).

## 📌 TL;DR

Messages must be matched by the following regex:

```js
/^(revert: )?(feat|fix|polish|docs|style|refactor|perf|test|workflow|ci|chore|types)(\(.+\))?: .{1,50}/;
```

### 📌 Examples

Appears under "Features" header, `compiler` subheader:

feat(compiler): add 'comments' option

Appears under "Bug Fixes" header, `v-model` subheader, with a link to issue #28:

fix(v-model): handle events on blur

close #28

Appears under "Performance Improvements" header, and under "Breaking Changes" with the breaking change explanation:

perf(core): improve vdom diffing by removing 'foo' option

BREAKING CHANGE: The 'foo' option has been removed.

The following commit and commit `667ecc1` do not appear in the changelog if they are under the same release. If not, the revert commit appears under the "Reverts" header.

\*\*revert: feat(compiler): add 'comments' option

This reverts commit 667ecc1654a317a13331b17617d973392f415f02.\*\*

## 📌Full Message Format

A commit message consists of a **header**, **body** and **footer**. The header has a **type**, **scope** and **subject**:

type scope: subject
BLANK LINE
body
BLANK LINE
footer

The **header** is mandatory and the **scope** of the header is optional.

## 📌 Revert

If the commit reverts a previous commit, it should begin with `revert:`, followed by the header of the reverted commit. In the body, it should say: `This reverts commit <hash>.`, where the hash is the SHA of the commit being reverted.

## 📌 Type

If the prefix is `feat`, `fix` or `perf`, it will appear in the changelog. However, if there is any BREAKING CHANGE (#footer), the commit will always appear in the changelog.

Other prefixes are up to your discretion. Suggested prefixes are `docs`, `chore`, `style`, `refactor`, and `test` for non-changelog related tasks.

## 📌 Scope

The scope could be anything specifying the place of the commit change. For example `core`, `compiler`, `ssr`, `v-model`, `transition` etc...

## 📌 Subject

The subject contains a succinct description of the change:

- use the imperative, present tense: "change" not "changed" nor "changes"
- don't capitalize the first letter
- no dot (.) at the end

## 📌 Body

Just as in the **subject**, use the imperative, present tense: "change" not "changed" nor "changes".
The body should include the motivation for the change and contrast this with previous behavior.

## 📌 Footer

The footer should contain any information about **Breaking Changes** and is also the place to
reference GitHub issues that this commit **Closes**.

**Breaking Changes** should start with the word `BREAKING CHANGE:` with a space or two newlines. The rest of the commit message is then used for this.

## Licencia 📄

- Licencia GNU GPL V.3 Copyright (c) 2023 Andres Antonio Cardoso <https://github.com/zerhocool>
- Licencia Copyleft Copyright (c) 2023 Andres Antonio Cardoso <https://github.com/zerhocool>
- Licencia de Creative Commons Reconocimiento-NoComercial-CompartirIgual 4.0 Internacional Copyright (c) 2023 Andres Antonio Cardoso <https://github.com/zerhocool>

**Diseño y Desarrollo ZERHO COOL - Copyrigh © 1999-2023 ZERHO COOL - Todos los derechos reservados.**

**Copyrigh © 2022 ZERHO COOL OÜ, Empresa en Tallin, Estonia - Todos los derechos reservados.**

---

<a rel="licencia" href="https://www.gnu.org/"><img alt="Licencia GNU General Publica " style="border-width:0" src="https://cdn.discordapp.com/attachments/1072960128820715602/1092305619681300520/gplv3-with-text-136x68.png" />⠀⠀⠀⠀⠀<img alt="Licencia Copyleft " style="border-width:0" src="https://cdn.discordapp.com/attachments/1072960128820715602/1092463443912708116/copyleftorg-green-stylized.png" />⠀⠀⠀⠀<img alt="Licencia Copyleft " style="border-width:0" src="https://cdn.discordapp.com/attachments/1072960128820715602/1092474752779694181/conservancy-header.png" />⠀⠀⠀⠀⠀</a><br />Esta obra está bajo <a rel="licencia" href="https://www.gnu.org/licenses/gpl-3.0.html">Licencia GNU General Publica (GNU GPL v3.0)-</a>
<a rel="licencia" href="http://next.copyleft.org/pages/current-release.html">Licencia Copyletf-</a>
<a rel="licencia" href="http://next.copyleft.org/pages/current-release.html">Software Freedom Conservancy.</a>

<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Licencia de Creative Commons" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a><br />Este obra está bajo una <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">licencia de Creative Commons Reconocimiento-NoComercial-CompartirIgual 4.0 Internacional.</a>

<a rel="licencia" href="https://opensource.org//"><img alt="Open Source" style="border-width:0" src="https://cdn.discordapp.com/attachments/1072960128820715602/1156244833363566716/os5.png?ex=6514446a&is=6512f2ea&hm=8e7ac1e9d3a95477e0c058cf8b83b9f98b9b84a87f6669c556673483d828c320&" width="100" />⠀⠀⠀<img alt="Clearly Licensed " style="border-width:0" src="https://cdn.discordapp.com/attachments/1072960128820715602/1156319005875896411/ClearlyLicensed_color_h.png?ex=6514897e&is=651337fe&hm=e52082d0d4d77a6c6dfc4d0786a39a5d2db817ebd766a65b460f6f4cf975b8f0&" width="250" />⠀⠀⠀</a><br />Brindamos nuestro apoyo a: <a rel="licencia" href="https://opensource.org/programs/">Open Source Iniative-</a>
<a rel="licencia" href="https://clearlydefined.io/about">Clearly Defined.</a>

<p align="right">
  <a rel="licencia" href="https://www.geocerts.com/geotrust/geotrust-ov-wildcard-ssl"><img alt="Open Source " style="border-width:0" src="https://cdn.discordapp.com/attachments/1072960128820715602/1156311180692951170/geotrust-trust-seal1.png?ex=65148234&is=651330b4&hm=d0a8894085f01ef224318775176625b2b644b0b254991f927576dade460c800f&" width="90" /></a>
</p>
