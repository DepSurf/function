# Function: <code>spi_register_controller</code>

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
int spi_register_controller(struct spi_controller *ctlr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff8168cb40)
Location: drivers/spi/spi.c:2053
Inline: False
Direct callers:
  - drivers/spi/spi.c:devm_spi_register_controller
```
**Symbols:**

```
ffffffff8168cb40-ffffffff8168cfcf: spi_register_controller (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int spi_register_controller(struct spi_controller *ctlr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff816f64f0)
Location: drivers/spi/spi.c:2083
Inline: False
Direct callers:
  - drivers/spi/spi.c:devm_spi_register_controller
```
**Symbols:**

```
ffffffff816f64f0-ffffffff816f69b1: spi_register_controller (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int spi_register_controller(struct spi_controller *ctlr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff817318e0)
Location: drivers/spi/spi.c:2117
Inline: False
Direct callers:
  - drivers/spi/spi.c:devm_spi_register_controller
```
**Symbols:**

```
ffffffff817318e0-ffffffff81731e5f: spi_register_controller (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int spi_register_controller(struct spi_controller *ctlr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff817542d0)
Location: drivers/spi/spi.c:2183
Inline: False
Direct callers:
  - drivers/spi/spi.c:devm_spi_register_controller
```
**Symbols:**

```
ffffffff817542d0-ffffffff8175484f: spi_register_controller (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int spi_register_controller(struct spi_controller *ctlr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (0)
Location: drivers/spi/spi.c:2377
Inline: False
Direct callers:
  - drivers/spi/spi.c:devm_spi_register_controller
```
**Symbols:**

```
ffffffff817928ad-ffffffff8179296e: spi_register_controller.cold (STB_LOCAL)
ffffffff8178fa70-ffffffff81790085: spi_register_controller (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int spi_register_controller(struct spi_controller *ctlr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (0)
Location: drivers/spi/spi.c:2383
Inline: False
Direct callers:
  - drivers/spi/spi.c:devm_spi_register_controller
```
**Symbols:**

```
ffffffff817b643c-ffffffff817b64d0: spi_register_controller.cold (STB_LOCAL)
ffffffff817b3650-ffffffff817b3c6a: spi_register_controller (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int spi_register_controller(struct spi_controller *ctlr);
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
  - drivers/spi/spi.c:devm_spi_register_controller
```
**Symbols:**

```
ffffffff8187d365-ffffffff8187d3e9: spi_register_controller.cold (STB_LOCAL)
ffffffff8187ae50-ffffffff8187b349: spi_register_controller (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int spi_register_controller(struct spi_controller *ctlr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (0)
Location: drivers/spi/spi.c:2657
Inline: False
Direct callers:
  - drivers/spi/spi.c:devm_spi_register_controller
```
**Symbols:**

```
ffffffff81c18dfd-ffffffff81c18e3e: spi_register_controller.cold (STB_LOCAL)
ffffffff81889b80-ffffffff81889ff6: spi_register_controller (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int spi_register_controller(struct spi_controller *ctlr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (0)
Location: drivers/spi/spi.c:2679
Inline: False
```
**Symbols:**

```
ffffffff81c0ab8e-ffffffff81c0ac6c: spi_register_controller.cold (STB_LOCAL)
ffffffff8186c490-ffffffff8186c9f8: spi_register_controller (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int spi_register_controller(struct spi_controller *ctlr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (0)
Location: drivers/spi/spi.c:2813
Inline: False
```
**Symbols:**

```
ffffffff81d0fcc8-ffffffff81d0fdfb: spi_register_controller.cold (STB_LOCAL)
ffffffff818fc370-ffffffff818fc8ab: spi_register_controller (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int spi_register_controller(struct spi_controller *ctlr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (0)
Location: drivers/spi/spi.c:2921
Inline: False
Direct callers:
  - drivers/spi/spi.c:devm_spi_register_controller
```
**Symbols:**

```
ffffffff81eda9f3-ffffffff81edab21: spi_register_controller.cold (STB_LOCAL)
ffffffff81a4da20-ffffffff81a4df54: spi_register_controller (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int spi_register_controller(struct spi_controller *ctlr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (0)
Location: drivers/spi/spi.c:3104
Inline: False
Direct callers:
  - drivers/spi/spi.c:devm_spi_register_controller
```
**Symbols:**

```
ffffffff8209d3ea-ffffffff8209d431: spi_register_controller.cold (STB_LOCAL)
ffffffff81bd7f40-ffffffff81bd847d: spi_register_controller (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int spi_register_controller(struct spi_controller *ctlr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (0)
Location: drivers/spi/spi.c:3110
Inline: False
Direct callers:
  - drivers/spi/spi.c:devm_spi_register_controller
```
**Symbols:**

```
ffffffff8211e2a7-ffffffff8211e2ee: spi_register_controller.cold (STB_LOCAL)
ffffffff81c2e970-ffffffff81c2ee63: spi_register_controller (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int spi_register_controller(struct spi_controller *ctlr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (0)
Location: drivers/spi/spi.c:3277
Inline: False
Direct callers:
  - drivers/spi/spi.c:devm_spi_register_controller
```
**Symbols:**

```
ffffffff821ff838-ffffffff821ff87c: spi_register_controller.cold (STB_LOCAL)
ffffffff81ce16e0-ffffffff81ce1c1b: spi_register_controller (STB_GLOBAL)
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
int spi_register_controller(struct spi_controller *ctlr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffff8000109c76f8)
Location: drivers/spi/spi.c:2383
Inline: False
Direct callers:
  - drivers/spi/spi.c:devm_spi_register_controller
```
**Symbols:**

```
ffff8000109c76f8-ffff8000109c7ee4: spi_register_controller (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int spi_register_controller(struct spi_controller *ctlr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (c0ab06dc)
Location: drivers/spi/spi.c:2383
Inline: False
Direct callers:
  - drivers/spi/spi.c:devm_spi_register_controller
```
**Symbols:**

```
c0ab06dc-c0ab0e7c: spi_register_controller (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int spi_register_controller(struct spi_controller *ctlr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (c000000000a880c0)
Location: drivers/spi/spi.c:2383
Inline: False
Direct callers:
  - drivers/spi/spi.c:devm_spi_register_controller
```
**Symbols:**

```
c000000000a880c0-c000000000a88af0: spi_register_controller (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int spi_register_controller(struct spi_controller *ctlr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffe000617e84)
Location: drivers/spi/spi.c:2383
Inline: False
Direct callers:
  - drivers/spi/spi.c:devm_spi_register_controller
```
**Symbols:**

```
ffffffe000617e84-ffffffe00061857c: spi_register_controller (STB_GLOBAL)
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
int spi_register_controller(struct spi_controller *ctlr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (0)
Location: drivers/spi/spi.c:2383
Inline: False
Direct callers:
  - drivers/spi/spi.c:devm_spi_register_controller
```
**Symbols:**

```
ffffffff8177af1c-ffffffff8177afb0: spi_register_controller.cold (STB_LOCAL)
ffffffff81778130-ffffffff8177874a: spi_register_controller (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int spi_register_controller(struct spi_controller *ctlr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (0)
Location: drivers/spi/spi.c:2383
Inline: False
Direct callers:
  - drivers/spi/spi.c:devm_spi_register_controller
```
**Symbols:**

```
ffffffff8175accc-ffffffff8175ad60: spi_register_controller.cold (STB_LOCAL)
ffffffff81757ee0-ffffffff817584fa: spi_register_controller (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int spi_register_controller(struct spi_controller *ctlr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (0)
Location: drivers/spi/spi.c:2383
Inline: False
Direct callers:
  - drivers/spi/spi.c:devm_spi_register_controller
```
**Symbols:**

```
ffffffff817ab2bc-ffffffff817ab350: spi_register_controller.cold (STB_LOCAL)
ffffffff817a84d0-ffffffff817a8aea: spi_register_controller (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int spi_register_controller(struct spi_controller *ctlr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (0)
Location: drivers/spi/spi.c:2383
Inline: False
Direct callers:
  - drivers/spi/spi.c:devm_spi_register_controller
```
**Symbols:**

```
ffffffff817c524c-ffffffff817c52e0: spi_register_controller.cold (STB_LOCAL)
ffffffff817c2360-ffffffff817c297a: spi_register_controller (STB_GLOBAL)
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
