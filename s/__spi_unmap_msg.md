# Function: <code>__spi_unmap_msg</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff815e7208)
Location: drivers/spi/spi.c:800
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_finalize_current_message
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff81645b38)
Location: drivers/spi/spi.c:825
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_finalize_current_message
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
In drivers/spi/spi.c (ffffffff81676938)
Location: drivers/spi/spi.c:844
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_finalize_current_message
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
In drivers/spi/spi.c (ffffffff8168b037)
Location: drivers/spi/spi.c:871
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_finalize_current_message
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
In drivers/spi/spi.c (ffffffff816f49a7)
Location: drivers/spi/spi.c:875
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_finalize_current_message
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
In drivers/spi/spi.c (ffffffff81732a67)
Location: drivers/spi/spi.c:885
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_finalize_current_message
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
In drivers/spi/spi.c (ffffffff81755487)
Location: drivers/spi/spi.c:927
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_finalize_current_message
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
In drivers/spi/spi.c (ffffffff81791588)
Location: drivers/spi/spi.c:944
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_finalize_current_message
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
In drivers/spi/spi.c (ffffffff817b5188)
Location: drivers/spi/spi.c:945
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_finalize_current_message
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff8187c052)
Location: drivers/spi/spi.c:971
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_finalize_current_message
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
In drivers/spi/spi.c (ffffffff81889016)
Location: drivers/spi/spi.c:989
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_finalize_current_message
  - drivers/spi/spi.c:spi_transfer_one_message
Direct callers:
  - drivers/spi/spi.c:spi_finalize_current_message
  - drivers/spi/spi.c:spi_transfer_one_message
```
**Symbols:**

```
ffffffff81888020-ffffffff8188812f: __spi_unmap_msg.part.0 (STB_LOCAL)
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
In drivers/spi/spi.c (ffffffff8186aaf6)
Location: drivers/spi/spi.c:1001
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_finalize_current_message
  - drivers/spi/spi.c:spi_transfer_one_message
Direct callers:
  - drivers/spi/spi.c:spi_finalize_current_message
  - drivers/spi/spi.c:spi_transfer_one_message
```
**Symbols:**

```
ffffffff8186a920-ffffffff8186aa2f: __spi_unmap_msg.part.0 (STB_LOCAL)
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
In drivers/spi/spi.c (ffffffff818faf02)
Location: drivers/spi/spi.c:1065
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_finalize_current_message
  - drivers/spi/spi.c:spi_transfer_one_message
Direct callers:
  - drivers/spi/spi.c:spi_finalize_current_message
  - drivers/spi/spi.c:spi_transfer_one_message
```
**Symbols:**

```
ffffffff818facc0-ffffffff818fadcf: __spi_unmap_msg.part.0 (STB_LOCAL)
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
In drivers/spi/spi.c (ffffffff81a4cb9b)
Location: drivers/spi/spi.c:1105
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_finalize_current_message
  - drivers/spi/spi.c:spi_transfer_one_message
Direct callers:
  - drivers/spi/spi.c:spi_finalize_current_message
  - drivers/spi/spi.c:spi_transfer_one_message
```
**Symbols:**

```
ffffffff81a4c750-ffffffff81a4c89b: __spi_unmap_msg.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (0)
Location: drivers/spi/spi.c:1188
Inline: True
Direct callers:
  - drivers/spi/spi.c:spi_finalize_current_message
  - drivers/spi/spi.c:spi_transfer_one_message
```
**Symbols:**

```
ffffffff81bd2350-ffffffff81bd2458: __spi_unmap_msg.isra.0 (STB_LOCAL)
ffffffff8209d083-ffffffff8209d097: __spi_unmap_msg.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (0)
Location: drivers/spi/spi.c:1188
Inline: True
Direct callers:
  - drivers/spi/spi.c:spi_finalize_current_message
  - drivers/spi/spi.c:spi_transfer_one_message
```
**Symbols:**

```
ffffffff81c2b0a0-ffffffff81c2b1a8: __spi_unmap_msg.isra.0 (STB_LOCAL)
ffffffff8211df33-ffffffff8211df47: __spi_unmap_msg.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (0)
Location: drivers/spi/spi.c:1258
Inline: True
Direct callers:
  - drivers/spi/spi.c:spi_finalize_current_message
  - drivers/spi/spi.c:spi_transfer_one_message
```
**Symbols:**

```
ffffffff81cdd8f0-ffffffff81cdd9f8: __spi_unmap_msg.isra.0 (STB_LOCAL)
ffffffff821ff4d1-ffffffff821ff4e5: __spi_unmap_msg.isra.0.cold (STB_LOCAL)
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
In drivers/spi/spi.c (ffff8000109c88ec)
Location: drivers/spi/spi.c:945
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_finalize_current_message
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
In drivers/spi/spi.c (c0ab24c8)
Location: drivers/spi/spi.c:945
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_finalize_current_message
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
In drivers/spi/spi.c (c000000000a8a2e8)
Location: drivers/spi/spi.c:945
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_finalize_current_message
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
In drivers/spi/spi.c (ffffffe000618ce2)
Location: drivers/spi/spi.c:945
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_finalize_current_message
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
In drivers/spi/spi.c (ffffffff81779c68)
Location: drivers/spi/spi.c:945
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_finalize_current_message
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
In drivers/spi/spi.c (ffffffff81759a18)
Location: drivers/spi/spi.c:945
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_finalize_current_message
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
In drivers/spi/spi.c (ffffffff817aa008)
Location: drivers/spi/spi.c:945
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_finalize_current_message
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
In drivers/spi/spi.c (ffffffff817c3e98)
Location: drivers/spi/spi.c:945
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_finalize_current_message
```
</details>
</li>
</ul>

## Differences
