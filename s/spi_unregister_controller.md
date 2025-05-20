# Function: <code>spi_unregister_controller</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void spi_unregister_controller(struct spi_controller *ctlr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff8168ad20)
Location: drivers/spi/spi.c:2192
Inline: False
Direct callers:
  - drivers/spi/spi.c:devm_spi_unregister
```
**Symbols:**

```
ffffffff8168ad20-ffffffff8168adba: spi_unregister_controller (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void spi_unregister_controller(struct spi_controller *ctlr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff816f45e0)
Location: drivers/spi/spi.c:2247
Inline: False
Direct callers:
  - drivers/spi/spi.c:devm_spi_unregister
```
**Symbols:**

```
ffffffff816f45e0-ffffffff816f4723: spi_unregister_controller (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void spi_unregister_controller(struct spi_controller *ctlr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff81731040)
Location: drivers/spi/spi.c:2302
Inline: False
Direct callers:
  - drivers/spi/spi.c:devm_spi_unregister
```
**Symbols:**

```
ffffffff81731040-ffffffff8173114d: spi_unregister_controller (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void spi_unregister_controller(struct spi_controller *ctlr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff81753a30)
Location: drivers/spi/spi.c:2368
Inline: False
Direct callers:
  - drivers/spi/spi.c:devm_spi_unregister
```
**Symbols:**

```
ffffffff81753a30-ffffffff81753b3d: spi_unregister_controller (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void spi_unregister_controller(struct spi_controller *ctlr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (0)
Location: drivers/spi/spi.c:2577
Inline: False
Direct callers:
  - drivers/spi/spi.c:devm_spi_unregister
```
**Symbols:**

```
ffffffff81792821-ffffffff81792835: spi_unregister_controller.cold (STB_LOCAL)
ffffffff8178ed60-ffffffff8178ee5c: spi_unregister_controller (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void spi_unregister_controller(struct spi_controller *ctlr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (0)
Location: drivers/spi/spi.c:2581
Inline: False
Direct callers:
  - drivers/spi/spi.c:devm_spi_unregister
```
**Symbols:**

```
ffffffff817b63c3-ffffffff817b63d7: spi_unregister_controller.cold (STB_LOCAL)
ffffffff817b2920-ffffffff817b2a1c: spi_unregister_controller (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void spi_unregister_controller(struct spi_controller *ctlr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (0)
Location: drivers/spi/spi.c:2779
Inline: False
Direct callers:
  - drivers/spi/spi.c:devm_spi_unregister
```
**Symbols:**

```
ffffffff8187d1d1-ffffffff8187d1f4: spi_unregister_controller.cold (STB_LOCAL)
ffffffff81879790-ffffffff818798bc: spi_unregister_controller (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void spi_unregister_controller(struct spi_controller *ctlr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (0)
Location: drivers/spi/spi.c:2860
Inline: False
Direct callers:
  - drivers/spi/spi.c:devm_spi_unregister
```
**Symbols:**

```
ffffffff81c18c19-ffffffff81c18c3c: spi_unregister_controller.cold (STB_LOCAL)
ffffffff81887eb0-ffffffff81887ff9: spi_unregister_controller (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void spi_unregister_controller(struct spi_controller *ctlr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (0)
Location: drivers/spi/spi.c:2868
Inline: False
```
**Symbols:**

```
ffffffff81c0a98e-ffffffff81c0a9b1: spi_unregister_controller.cold (STB_LOCAL)
ffffffff8186a710-ffffffff8186a843: spi_unregister_controller (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void spi_unregister_controller(struct spi_controller *ctlr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (0)
Location: drivers/spi/spi.c:2997
Inline: False
```
**Symbols:**

```
ffffffff81d0f9b1-ffffffff81d0f9fd: spi_unregister_controller.cold (STB_LOCAL)
ffffffff818faa80-ffffffff818fabe6: spi_unregister_controller (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void spi_unregister_controller(struct spi_controller *ctlr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (0)
Location: drivers/spi/spi.c:3111
Inline: False
Direct callers:
  - drivers/spi/spi.c:devm_spi_unregister
```
**Symbols:**

```
ffffffff81eda70a-ffffffff81eda757: spi_unregister_controller.cold (STB_LOCAL)
ffffffff81a4c5b0-ffffffff81a4c730: spi_unregister_controller (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void spi_unregister_controller(struct spi_controller *ctlr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (0)
Location: drivers/spi/spi.c:3302
Inline: False
Direct callers:
  - drivers/spi/spi.c:devm_spi_unregister
```
**Symbols:**

```
ffffffff8209d13e-ffffffff8209d168: spi_unregister_controller.cold (STB_LOCAL)
ffffffff81bd55a0-ffffffff81bd573b: spi_unregister_controller (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void spi_unregister_controller(struct spi_controller *ctlr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (0)
Location: drivers/spi/spi.c:3308
Inline: False
Direct callers:
  - drivers/spi/spi.c:devm_spi_unregister
```
**Symbols:**

```
ffffffff8211e015-ffffffff8211e03f: spi_unregister_controller.cold (STB_LOCAL)
ffffffff81c2c2d0-ffffffff81c2c46b: spi_unregister_controller (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void spi_unregister_controller(struct spi_controller *ctlr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (0)
Location: drivers/spi/spi.c:3459
Inline: False
Direct callers:
  - drivers/spi/spi.c:devm_spi_unregister
```
**Symbols:**

```
ffffffff821ff5b3-ffffffff821ff5dd: spi_unregister_controller.cold (STB_LOCAL)
ffffffff81cdebf0-ffffffff81cded8b: spi_unregister_controller (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void spi_unregister_controller(struct spi_controller *ctlr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffff8000109c7f80)
Location: drivers/spi/spi.c:2581
Inline: False
Direct callers:
  - drivers/spi/spi.c:devm_spi_unregister
```
**Symbols:**

```
ffff8000109c7f80-ffff8000109c80a8: spi_unregister_controller (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void spi_unregister_controller(struct spi_controller *ctlr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (c0ab03b4)
Location: drivers/spi/spi.c:2581
Inline: False
Direct callers:
  - drivers/spi/spi.c:devm_spi_unregister
```
**Symbols:**

```
c0ab03b4-c0ab04a4: spi_unregister_controller (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void spi_unregister_controller(struct spi_controller *ctlr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (c000000000a868c0)
Location: drivers/spi/spi.c:2581
Inline: False
Direct callers:
  - drivers/spi/spi.c:devm_spi_unregister
```
**Symbols:**

```
c000000000a868c0-c000000000a86a80: spi_unregister_controller (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void spi_unregister_controller(struct spi_controller *ctlr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffe000616822)
Location: drivers/spi/spi.c:2581
Inline: False
Direct callers:
  - drivers/spi/spi.c:devm_spi_unregister
```
**Symbols:**

```
ffffffe000616822-ffffffe00061693a: spi_unregister_controller (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void spi_unregister_controller(struct spi_controller *ctlr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (0)
Location: drivers/spi/spi.c:2581
Inline: False
Direct callers:
  - drivers/spi/spi.c:devm_spi_unregister
```
**Symbols:**

```
ffffffff8177aea3-ffffffff8177aeb7: spi_unregister_controller.cold (STB_LOCAL)
ffffffff81777400-ffffffff817774fc: spi_unregister_controller (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void spi_unregister_controller(struct spi_controller *ctlr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (0)
Location: drivers/spi/spi.c:2581
Inline: False
Direct callers:
  - drivers/spi/spi.c:devm_spi_unregister
```
**Symbols:**

```
ffffffff8175ac53-ffffffff8175ac67: spi_unregister_controller.cold (STB_LOCAL)
ffffffff817571b0-ffffffff817572ac: spi_unregister_controller (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void spi_unregister_controller(struct spi_controller *ctlr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (0)
Location: drivers/spi/spi.c:2581
Inline: False
Direct callers:
  - drivers/spi/spi.c:devm_spi_unregister
```
**Symbols:**

```
ffffffff817ab243-ffffffff817ab257: spi_unregister_controller.cold (STB_LOCAL)
ffffffff817a77a0-ffffffff817a789c: spi_unregister_controller (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void spi_unregister_controller(struct spi_controller *ctlr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (0)
Location: drivers/spi/spi.c:2581
Inline: False
Direct callers:
  - drivers/spi/spi.c:devm_spi_unregister
```
**Symbols:**

```
ffffffff817c51d3-ffffffff817c51e7: spi_unregister_controller.cold (STB_LOCAL)
ffffffff817c1620-ffffffff817c171c: spi_unregister_controller (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
