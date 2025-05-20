# Function: <code>rfkill_update_global_state</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/rfkill/core.c (ffffffff81884a48)
Location: net/rfkill/core.c:305
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_fop_write
  - net/rfkill/core.c:__rfkill_switch_all
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/rfkill/core.c (ffffffff818b92b8)
Location: net/rfkill/core.c:305
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_fop_write
  - net/rfkill/core.c:__rfkill_switch_all
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/rfkill/core.c (ffffffff818dfe30)
Location: net/rfkill/core.c:363
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_fop_write
  - net/rfkill/core.c:__rfkill_switch_all
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/rfkill/core.c (ffffffff81965b40)
Location: net/rfkill/core.c:363
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_fop_write
  - net/rfkill/core.c:__rfkill_switch_all
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/rfkill/core.c (ffffffff827439a0)
Location: net/rfkill/core.c:377
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_init
  - net/rfkill/core.c:rfkill_fop_write
  - net/rfkill/core.c:__rfkill_switch_all
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/rfkill/core.c (ffffffff828fdcbe)
Location: net/rfkill/core.c:379
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_init
  - net/rfkill/core.c:rfkill_init
  - net/rfkill/core.c:rfkill_fop_write
  - net/rfkill/core.c:rfkill_fop_write
  - net/rfkill/core.c:__rfkill_switch_all
  - net/rfkill/core.c:__rfkill_switch_all
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/rfkill/core.c (ffffffff8291a89f)
Location: net/rfkill/core.c:367
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_init
  - net/rfkill/core.c:rfkill_init
  - net/rfkill/core.c:rfkill_fop_write
  - net/rfkill/core.c:rfkill_fop_write
  - net/rfkill/core.c:__rfkill_switch_all
  - net/rfkill/core.c:__rfkill_switch_all
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/rfkill/core.c (ffffffff8292470e)
Location: net/rfkill/core.c:367
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_init
  - net/rfkill/core.c:rfkill_init
  - net/rfkill/core.c:rfkill_fop_write
  - net/rfkill/core.c:rfkill_fop_write
  - net/rfkill/core.c:__rfkill_switch_all
  - net/rfkill/core.c:__rfkill_switch_all
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/rfkill/core.c (ffffffff82d30958)
Location: net/rfkill/core.c:367
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_init
  - net/rfkill/core.c:rfkill_fop_write
  - net/rfkill/core.c:rfkill_fop_write
  - net/rfkill/core.c:__rfkill_switch_all
  - net/rfkill/core.c:__rfkill_switch_all
Direct callers:
  - net/rfkill/core.c:rfkill_init
```
**Symbols:**

```
ffffffff81b972a0-ffffffff81b972c1: rfkill_update_global_state.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/rfkill/core.c (ffffffff8301f528)
Location: net/rfkill/core.c:369
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_init
  - net/rfkill/core.c:rfkill_fop_write
  - net/rfkill/core.c:rfkill_fop_write
  - net/rfkill/core.c:__rfkill_switch_all
  - net/rfkill/core.c:__rfkill_switch_all
Direct callers:
  - net/rfkill/core.c:rfkill_init
```
**Symbols:**

```
ffffffff81ba6f40-ffffffff81ba6f61: rfkill_update_global_state.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/rfkill/core.c (ffffffff8322a666)
Location: net/rfkill/core.c:370
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_init
  - net/rfkill/core.c:rfkill_fop_write
  - net/rfkill/core.c:rfkill_fop_write
  - net/rfkill/core.c:__rfkill_switch_all
  - net/rfkill/core.c:__rfkill_switch_all
Direct callers:
  - net/rfkill/core.c:rfkill_init
```
**Symbols:**

```
ffffffff81b960d0-ffffffff81b960f1: rfkill_update_global_state.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/rfkill/core.c (ffffffff83314d62)
Location: net/rfkill/core.c:370
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_init
  - net/rfkill/core.c:rfkill_fop_write
  - net/rfkill/core.c:rfkill_fop_write
  - net/rfkill/core.c:__rfkill_switch_all
  - net/rfkill/core.c:__rfkill_switch_all
Direct callers:
  - net/rfkill/core.c:rfkill_init
```
**Symbols:**

```
ffffffff81c629a0-ffffffff81c629df: rfkill_update_global_state.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/rfkill/core.c (ffffffff834cf2cd)
Location: net/rfkill/core.c:370
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_init
  - net/rfkill/core.c:rfkill_fop_write
  - net/rfkill/core.c:rfkill_fop_write
  - net/rfkill/core.c:__rfkill_switch_all
  - net/rfkill/core.c:__rfkill_switch_all
Direct callers:
  - net/rfkill/core.c:rfkill_init
```
**Symbols:**

```
ffffffff81e05290-ffffffff81e052d7: rfkill_update_global_state.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/rfkill/core.c (ffffffff83f12a37)
Location: net/rfkill/core.c:370
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_init
  - net/rfkill/core.c:rfkill_init
  - net/rfkill/core.c:rfkill_fop_write
  - net/rfkill/core.c:rfkill_fop_write
  - net/rfkill/core.c:__rfkill_switch_all
  - net/rfkill/core.c:__rfkill_switch_all
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/rfkill/core.c (ffffffff837390e7)
Location: net/rfkill/core.c:370
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_init
  - net/rfkill/core.c:rfkill_init
  - net/rfkill/core.c:rfkill_fop_write
  - net/rfkill/core.c:rfkill_fop_write
  - net/rfkill/core.c:__rfkill_switch_all
  - net/rfkill/core.c:__rfkill_switch_all
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/rfkill/core.c (ffffffff8396d8b7)
Location: net/rfkill/core.c:382
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_init
  - net/rfkill/core.c:rfkill_init
  - net/rfkill/core.c:rfkill_fop_write
  - net/rfkill/core.c:rfkill_fop_write
  - net/rfkill/core.c:__rfkill_switch_all
  - net/rfkill/core.c:__rfkill_switch_all
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/rfkill/core.c (ffff8000114b58b8)
Location: net/rfkill/core.c:367
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_init
  - net/rfkill/core.c:rfkill_init
  - net/rfkill/core.c:rfkill_fop_write
  - net/rfkill/core.c:rfkill_fop_write
  - net/rfkill/core.c:__rfkill_switch_all
  - net/rfkill/core.c:__rfkill_switch_all
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/rfkill/core.c (c15babac)
Location: net/rfkill/core.c:367
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_init
  - net/rfkill/core.c:rfkill_init
  - net/rfkill/core.c:rfkill_fop_write
  - net/rfkill/core.c:rfkill_fop_write
  - net/rfkill/core.c:__rfkill_switch_all
  - net/rfkill/core.c:__rfkill_switch_all
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/rfkill/core.c (c0000000013c7bb0)
Location: net/rfkill/core.c:367
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_init
  - net/rfkill/core.c:rfkill_init
  - net/rfkill/core.c:rfkill_fop_write
  - net/rfkill/core.c:rfkill_fop_write
  - net/rfkill/core.c:__rfkill_switch_all
  - net/rfkill/core.c:__rfkill_switch_all
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/rfkill/core.c (ffffffe0000446a0)
Location: net/rfkill/core.c:367
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_init
  - net/rfkill/core.c:rfkill_init
  - net/rfkill/core.c:rfkill_fop_write
  - net/rfkill/core.c:rfkill_fop_write
  - net/rfkill/core.c:__rfkill_switch_all
  - net/rfkill/core.c:__rfkill_switch_all
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/rfkill/core.c (ffffffff82909412)
Location: net/rfkill/core.c:367
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_init
  - net/rfkill/core.c:rfkill_init
  - net/rfkill/core.c:rfkill_fop_write
  - net/rfkill/core.c:rfkill_fop_write
  - net/rfkill/core.c:__rfkill_switch_all
  - net/rfkill/core.c:__rfkill_switch_all
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/rfkill/core.c (ffffffff82901760)
Location: net/rfkill/core.c:367
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_init
  - net/rfkill/core.c:rfkill_init
  - net/rfkill/core.c:rfkill_fop_write
  - net/rfkill/core.c:rfkill_fop_write
  - net/rfkill/core.c:__rfkill_switch_all
  - net/rfkill/core.c:__rfkill_switch_all
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/rfkill/core.c (ffffffff8291ed5c)
Location: net/rfkill/core.c:367
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_init
  - net/rfkill/core.c:rfkill_init
  - net/rfkill/core.c:rfkill_fop_write
  - net/rfkill/core.c:rfkill_fop_write
  - net/rfkill/core.c:__rfkill_switch_all
  - net/rfkill/core.c:__rfkill_switch_all
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/rfkill/core.c (ffffffff8292577e)
Location: net/rfkill/core.c:367
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_init
  - net/rfkill/core.c:rfkill_init
  - net/rfkill/core.c:rfkill_fop_write
  - net/rfkill/core.c:rfkill_fop_write
  - net/rfkill/core.c:__rfkill_switch_all
  - net/rfkill/core.c:__rfkill_switch_all
```
</details>
</li>
</ul>

## Differences
