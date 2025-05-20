# Function: <code>spi_mem_dirmap_destroy</code>

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
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void spi_mem_dirmap_destroy(struct spi_mem_dirmap_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi-mem.c (ffffffff817566b0)
Location: drivers/spi/spi-mem.c:545
Inline: False
```
**Symbols:**

```
ffffffff817566b0-ffffffff817566ea: spi_mem_dirmap_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void spi_mem_dirmap_destroy(struct spi_mem_dirmap_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi-mem.c (ffffffff81792da0)
Location: drivers/spi/spi-mem.c:544
Inline: False
Direct callers:
  - drivers/spi/spi-mem.c:devm_spi_mem_dirmap_release
```
**Symbols:**

```
ffffffff81792da0-ffffffff81792dea: spi_mem_dirmap_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void spi_mem_dirmap_destroy(struct spi_mem_dirmap_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi-mem.c (ffffffff817b68f0)
Location: drivers/spi/spi-mem.c:544
Inline: False
Direct callers:
  - drivers/spi/spi-mem.c:devm_spi_mem_dirmap_release
```
**Symbols:**

```
ffffffff817b68f0-ffffffff817b693a: spi_mem_dirmap_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void spi_mem_dirmap_destroy(struct spi_mem_dirmap_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/spi/spi-mem.c (ffffffff8187dc20)
Location: drivers/spi/spi-mem.c:547
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:devm_spi_mem_dirmap_release
```
**Symbols:**

```
ffffffff8187d720-ffffffff8187d76a: spi_mem_dirmap_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void spi_mem_dirmap_destroy(struct spi_mem_dirmap_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/spi/spi-mem.c (ffffffff8188c180)
Location: drivers/spi/spi-mem.c:552
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:devm_spi_mem_dirmap_release
```
**Symbols:**

```
ffffffff8188bc40-ffffffff8188bc8a: spi_mem_dirmap_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void spi_mem_dirmap_destroy(struct spi_mem_dirmap_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/spi/spi-mem.c (ffffffff8186eae0)
Location: drivers/spi/spi-mem.c:569
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:devm_spi_mem_dirmap_release
```
**Symbols:**

```
ffffffff8186e5a0-ffffffff8186e5ea: spi_mem_dirmap_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void spi_mem_dirmap_destroy(struct spi_mem_dirmap_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/spi/spi-mem.c (ffffffff818febf0)
Location: drivers/spi/spi-mem.c:570
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:devm_spi_mem_dirmap_release
```
**Symbols:**

```
ffffffff818fe640-ffffffff818fe68a: spi_mem_dirmap_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void spi_mem_dirmap_destroy(struct spi_mem_dirmap_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/spi/spi-mem.c (ffffffff81a51550)
Location: drivers/spi/spi-mem.c:583
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:devm_spi_mem_dirmap_release
```
**Symbols:**

```
ffffffff81a4ff40-ffffffff81a4ff92: spi_mem_dirmap_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void spi_mem_dirmap_destroy(struct spi_mem_dirmap_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/spi/spi-mem.c (ffffffff81bda7a0)
Location: drivers/spi/spi-mem.c:583
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:devm_spi_mem_dirmap_release
```
**Symbols:**

```
ffffffff81bd9040-ffffffff81bd9092: spi_mem_dirmap_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void spi_mem_dirmap_destroy(struct spi_mem_dirmap_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/spi/spi-mem.c (ffffffff81c31240)
Location: drivers/spi/spi-mem.c:583
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:devm_spi_mem_dirmap_release
```
**Symbols:**

```
ffffffff81c2fa40-ffffffff81c2fa92: spi_mem_dirmap_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void spi_mem_dirmap_destroy(struct spi_mem_dirmap_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/spi/spi-mem.c (ffffffff81ce40d0)
Location: drivers/spi/spi-mem.c:583
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:devm_spi_mem_dirmap_release
```
**Symbols:**

```
ffffffff81ce2900-ffffffff81ce2952: spi_mem_dirmap_destroy (STB_GLOBAL)
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
void spi_mem_dirmap_destroy(struct spi_mem_dirmap_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi-mem.c (ffff8000109ca4e8)
Location: drivers/spi/spi-mem.c:544
Inline: False
Direct callers:
  - drivers/spi/spi-mem.c:devm_spi_mem_dirmap_release
```
**Symbols:**

```
ffff8000109ca4e8-ffff8000109ca540: spi_mem_dirmap_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void spi_mem_dirmap_destroy(struct spi_mem_dirmap_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi-mem.c (c0ab3a6c)
Location: drivers/spi/spi-mem.c:544
Inline: False
Direct callers:
  - drivers/spi/spi-mem.c:devm_spi_mem_dirmap_release
```
**Symbols:**

```
c0ab3a6c-c0ab3ac4: spi_mem_dirmap_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void spi_mem_dirmap_destroy(struct spi_mem_dirmap_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi-mem.c (c000000000a8bd60)
Location: drivers/spi/spi-mem.c:544
Inline: False
Direct callers:
  - drivers/spi/spi-mem.c:devm_spi_mem_dirmap_release
```
**Symbols:**

```
c000000000a8bd60-c000000000a8bde4: spi_mem_dirmap_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void spi_mem_dirmap_destroy(struct spi_mem_dirmap_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi-mem.c (ffffffe000619eea)
Location: drivers/spi/spi-mem.c:544
Inline: False
Direct callers:
  - drivers/spi/spi-mem.c:devm_spi_mem_dirmap_release
```
**Symbols:**

```
ffffffe000619eea-ffffffe000619f2e: spi_mem_dirmap_destroy (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void spi_mem_dirmap_destroy(struct spi_mem_dirmap_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi-mem.c (ffffffff8177b3d0)
Location: drivers/spi/spi-mem.c:544
Inline: False
Direct callers:
  - drivers/spi/spi-mem.c:devm_spi_mem_dirmap_release
```
**Symbols:**

```
ffffffff8177b3d0-ffffffff8177b41a: spi_mem_dirmap_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void spi_mem_dirmap_destroy(struct spi_mem_dirmap_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi-mem.c (ffffffff8175b180)
Location: drivers/spi/spi-mem.c:544
Inline: False
Direct callers:
  - drivers/spi/spi-mem.c:devm_spi_mem_dirmap_release
```
**Symbols:**

```
ffffffff8175b180-ffffffff8175b1ca: spi_mem_dirmap_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void spi_mem_dirmap_destroy(struct spi_mem_dirmap_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi-mem.c (ffffffff817ab770)
Location: drivers/spi/spi-mem.c:544
Inline: False
Direct callers:
  - drivers/spi/spi-mem.c:devm_spi_mem_dirmap_release
```
**Symbols:**

```
ffffffff817ab770-ffffffff817ab7ba: spi_mem_dirmap_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void spi_mem_dirmap_destroy(struct spi_mem_dirmap_desc *desc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi-mem.c (ffffffff817c5700)
Location: drivers/spi/spi-mem.c:544
Inline: False
Direct callers:
  - drivers/spi/spi-mem.c:devm_spi_mem_dirmap_release
```
**Symbols:**

```
ffffffff817c5700-ffffffff817c574a: spi_mem_dirmap_destroy (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
