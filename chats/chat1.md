# Cases Antes/Depois

_Started 2026-05-12 00:23 UTC_

---

## User



## Assistant

_[tool: list_files]_

_[tool: image_metadata]_

_[tool: image_metadata]_

_[tool: image_metadata]_

_[tool: copy_files]_

_[tool: update_todos]_

_[tool: write_file]_

Building the design system out loud:

**Palette**: ink `#0D0D0D` · bone `#F5F2EE` · gold `#C8A97E` · surgical teal `#2E6B6B` (sparing accent).
**Type**: Raleway (light, wide tracking, uppercase for headings — Presicav stand-in), Jost (body — Prometo stand-in), Cormorant Garamond Italic gold for numerals.
**Motif**: thin SVG curves (cartilage / topographic-like lines, NOT representational nose drawings) that draw on scroll. Wide grid columns; long horizontal rule details; ALL CAPS section labels with leading dot.
**Layout rhythm**: alternating ink + bone sections; large numerals; generous whitespace.

Now building:

_[tool: done]_

_[tool: snip]_

_[tool: fork_verifier_agent]_

Single-file landing for Dr. Matheus Rangel is live at **Dr Matheus Rangel.html**.

**Design system used**
- Palette: ink `#0D0D0D` · bone `#F5F2EE` · gold `#C8A97E` · surgical teal `#2E6B6B`
- Type: Raleway (Presicav stand-in) + Jost (Prometo stand-in) + Cormorant Garamond Italic gold for numerals
- Motif: thin SVG cartilage/topographic curves that draw on scroll — abstract, not representational

**Sections**: Hero · Sobre · Rinoplastia · Diferenciais · Resultados · Jornada · Filosofia · CTA escuro · Rodapé.

**Interactions wired**
- Custom cursor (dot + ring, difference blend)
- Hero H1 word-by-word reveal, parallax on pointer move, scroll fade
- IntersectionObserver reveals on every section
- SVG `stroke-dashoffset` line draws (hero + 3 section backgrounds)
- Animated counters in hero stats
- Magnetic CTAs
- Jornada has a vertical line that fills as you scroll past the 5 steps
- Mobile hamburger menu, sticky nav with scrolled state, floating WhatsApp button
- Before/after grid uses elegant striped placeholders (real photos to drop in later)

**Next steps you may want**
- Real antes/depois images when ready
- Real headshot crop tweaks if needed

## User

Verifier agent check completed

## Assistant

_[tool: str_replace_edit]_

_[tool: snip]_

_[tool: done]_

Fixed the Diferenciais overflow — middle column widened, h3 size clamped, and word-wrap enabled so the long uppercase titles never bleed into the copy column at any viewport.

## User

pode inventar os antes/depois por favor preciso dos cases

## Assistant

_[tool: snip]_

_[tool: read_file]_

_[tool: grep]_

_[tool: str_replace_edit]_

_[tool: snip]_

_[tool: done]_

_[tool: save_screenshot]_

_[tool: view_image]_

_[tool: snip]_

_[tool: fork_verifier_agent]_

_[tool: snip]_

Adicionei 3 cases inventados na seção **Resultados** — com perfis anatômicos minimalistas em SVG ao invés de fotos:

- **Caso 01 · Dorso e ponta** (F · 28) — giba dorsal → dorso reto
- **Caso 02 · Ponta nasal** (M · 34) — ponta bulbosa caída → ponta definida e rotacionada
- **Caso 03 · Funcional** (F · 41) — assimetria + válvula → contorno reto, respiração restaurada

Cada card tem:
- Silhueta de perfil em linha contínua (ink) com o trecho do nariz destacado em dourado
- Linhas-guia tracejadas (brow, alar, lábio) — código visual médico/anatômico
- Tags de marcação tipo "01/A", "01/B" + rótulos "dorso", "ponta", "válvula", "septo" em monoespaço dourado
- Nota clínica curta abaixo

Tratamento intencionalmente abstrato/diagramático — não tenta imitar fotos. Quando você tiver imagens reais para essa seção, é só substituir o conteúdo dos `<div class="ph">` por `<img>`.

## User

Verifier agent check completed

## Assistant

_[tool: run_script]_

_[tool: snip]_

Corrigi o overlap dos ticks com os rótulos — agora há respiro entre a linha dourada e o texto.

