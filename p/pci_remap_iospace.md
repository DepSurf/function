# Function: <code>pci_remap_iospace</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int pci_remap_iospace(const struct resource *res, phys_addr_t phys_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81437d60)
Location: drivers/pci/pci.c:3035
Inline: False
```
**Symbols:**

```
ffffffff81437d60-ffffffff81437d9e: pci_remap_iospace (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int pci_remap_iospace(const struct resource *res, phys_addr_t phys_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814839e0)
Location: drivers/pci/pci.c:3328
Inline: False
```
**Symbols:**

```
ffffffff814839e0-ffffffff81483a1e: pci_remap_iospace (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int pci_remap_iospace(const struct resource *res, phys_addr_t phys_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814a5140)
Location: drivers/pci/pci.c:3366
Inline: False
```
**Symbols:**

```
ffffffff814a5140-ffffffff814a517e: pci_remap_iospace (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int pci_remap_iospace(const struct resource *res, phys_addr_t phys_addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814ac530)
Location: drivers/pci/pci.c:3420
Inline: True
```
**Symbols:**

```
ffffffff814ac530-ffffffff814ac564: pci_remap_iospace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int pci_remap_iospace(const struct resource *res, phys_addr_t phys_addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814eb600)
Location: drivers/pci/pci.c:3435
Inline: True
```
**Symbols:**

```
ffffffff814eb600-ffffffff814eb634: pci_remap_iospace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
int pci_remap_iospace(const struct resource *res, phys_addr_t phys_addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (ffffffff8151afe5)
Location: drivers/pci/pci.c:3581
Inline: True
Inline callers:
  - drivers/pci/pci.c:devm_pci_remap_iospace
Direct callers:
  - drivers/pci/pci.c:devm_pci_remap_iospace
```
**Symbols:**

```
ffffffff8151af60-ffffffff8151af80: pci_remap_iospace.part.26 (STB_LOCAL)
ffffffff8151af80-ffffffff8151afa4: pci_remap_iospace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
int pci_remap_iospace(const struct resource *res, phys_addr_t phys_addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (ffffffff81530d55)
Location: drivers/pci/pci.c:3846
Inline: True
Inline callers:
  - drivers/pci/pci.c:devm_pci_remap_iospace
Direct callers:
  - drivers/pci/pci.c:devm_pci_remap_iospace
```
**Symbols:**

```
ffffffff81530cd0-ffffffff81530cf0: pci_remap_iospace.part.27 (STB_LOCAL)
ffffffff81530cf0-ffffffff81530d14: pci_remap_iospace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int pci_remap_iospace(const struct resource *res, phys_addr_t phys_addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (ffffffff81560697)
Location: drivers/pci/pci.c:3942
Inline: True
Inline callers:
  - drivers/pci/pci.c:devm_pci_remap_iospace
Direct callers:
  - drivers/pci/pci.c:devm_pci_remap_iospace
```
**Symbols:**

```
ffffffff81560610-ffffffff81560630: pci_remap_iospace.part.0 (STB_LOCAL)
ffffffff81560630-ffffffff81560654: pci_remap_iospace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int pci_remap_iospace(const struct resource *res, phys_addr_t phys_addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (ffffffff815817b7)
Location: drivers/pci/pci.c:3938
Inline: True
Inline callers:
  - drivers/pci/pci.c:devm_pci_remap_iospace
Direct callers:
  - drivers/pci/pci.c:devm_pci_remap_iospace
```
**Symbols:**

```
ffffffff81581730-ffffffff81581750: pci_remap_iospace.part.0 (STB_LOCAL)
ffffffff81581750-ffffffff81581774: pci_remap_iospace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int pci_remap_iospace(const struct resource *res, phys_addr_t phys_addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81626195)
Location: drivers/pci/pci.c:4009
Inline: True
Inline callers:
  - drivers/pci/pci.c:devm_pci_remap_iospace
  - drivers/pci/pci.c:devm_pci_remap_iospace
```
**Symbols:**

```
ffffffff81626fe0-ffffffff81627014: pci_remap_iospace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int pci_remap_iospace(const struct resource *res, phys_addr_t phys_addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8164bea5)
Location: drivers/pci/pci.c:4077
Inline: True
Inline callers:
  - drivers/pci/pci.c:devm_pci_remap_iospace
  - drivers/pci/pci.c:devm_pci_remap_iospace
```
**Symbols:**

```
ffffffff8164cbb0-ffffffff8164cbe4: pci_remap_iospace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int pci_remap_iospace(const struct resource *res, phys_addr_t phys_addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8162eb25)
Location: drivers/pci/pci.c:4109
Inline: True
Inline callers:
  - drivers/pci/pci.c:devm_pci_remap_iospace
  - drivers/pci/pci.c:devm_pci_remap_iospace
```
**Symbols:**

```
ffffffff8162f730-ffffffff8162f764: pci_remap_iospace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int pci_remap_iospace(const struct resource *res, phys_addr_t phys_addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (ffffffff8169ee4d)
Location: drivers/pci/pci.c:4159
Inline: True
Inline callers:
  - drivers/pci/pci.c:devm_pci_remap_iospace
  - drivers/pci/pci.c:devm_pci_remap_iospace
```
**Symbols:**

```
ffffffff81ce44ea-ffffffff81ce44fe: pci_remap_iospace.cold (STB_LOCAL)
ffffffff8169e2d0-ffffffff8169e31a: pci_remap_iospace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
int pci_remap_iospace(const struct resource *res, phys_addr_t phys_addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (ffffffff817c0ca6)
Location: drivers/pci/pci.c:4254
Inline: True
Inline callers:
  - drivers/pci/pci.c:devm_pci_remap_iospace
  - drivers/pci/pci.c:devm_pci_remap_iospace
```
**Symbols:**

```
ffffffff81eaaf0f-ffffffff81eaaf23: pci_remap_iospace.cold (STB_LOCAL)
ffffffff817c03d0-ffffffff817c042a: pci_remap_iospace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
int pci_remap_iospace(const struct resource *res, phys_addr_t phys_addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (ffffffff818dd596)
Location: drivers/pci/pci.c:4197
Inline: True
Inline callers:
  - drivers/pci/pci.c:devm_pci_remap_iospace
  - drivers/pci/pci.c:devm_pci_remap_iospace
```
**Symbols:**

```
ffffffff8208efe5-ffffffff8208eff9: pci_remap_iospace.cold (STB_LOCAL)
ffffffff818dcc60-ffffffff818dccba: pci_remap_iospace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
int pci_remap_iospace(const struct resource *res, phys_addr_t phys_addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (ffffffff81920606)
Location: drivers/pci/pci.c:4235
Inline: True
Inline callers:
  - drivers/pci/pci.c:devm_pci_remap_iospace
  - drivers/pci/pci.c:devm_pci_remap_iospace
```
**Symbols:**

```
ffffffff8210f32d-ffffffff8210f341: pci_remap_iospace.cold (STB_LOCAL)
ffffffff8191ff40-ffffffff8191ff9a: pci_remap_iospace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int pci_remap_iospace(const struct resource *res, phys_addr_t phys_addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (ffffffff81968796)
Location: drivers/pci/pci.c:4345
Inline: True
Inline callers:
  - drivers/pci/pci.c:devm_pci_remap_iospace
  - drivers/pci/pci.c:devm_pci_remap_iospace
```
**Symbols:**

```
ffffffff821ecfd5-ffffffff821ecfe9: pci_remap_iospace.cold (STB_LOCAL)
ffffffff81968120-ffffffff8196817a: pci_remap_iospace (STB_GLOBAL)
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
int pci_remap_iospace(const struct resource *res, phys_addr_t phys_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffff8000106e5c90)
Location: drivers/pci/pci.c:3938
Inline: False
Direct callers:
  - drivers/pci/pci.c:devm_pci_remap_iospace
  - drivers/acpi/pci_root.c:acpi_pci_probe_root_resources
```
**Symbols:**

```
ffff8000106e5c90-ffff8000106e5da0: pci_remap_iospace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int pci_remap_iospace(const struct resource *res, phys_addr_t phys_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (c087ea3c)
Location: drivers/pci/pci.c:3938
Inline: False
Direct callers:
  - drivers/pci/pci.c:devm_pci_remap_iospace
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_probe
```
**Symbols:**

```
c087ea3c-c087eaac: pci_remap_iospace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
int pci_remap_iospace(const struct resource *res, phys_addr_t phys_addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (c00000000085efd0)
Location: drivers/pci/pci.c:3938
Inline: True
Inline callers:
  - drivers/pci/pci.c:devm_pci_remap_iospace
Direct callers:
  - drivers/pci/pci.c:devm_pci_remap_iospace
```
**Symbols:**

```
c00000000085eee0-c00000000085ef2c: pci_remap_iospace.part.0 (STB_LOCAL)
c00000000085ef30-c00000000085ef84: pci_remap_iospace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int pci_remap_iospace(const struct resource *res, phys_addr_t phys_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffe0004ba4fa)
Location: drivers/pci/pci.c:3938
Inline: False
Direct callers:
  - drivers/pci/pci.c:devm_pci_remap_iospace
```
**Symbols:**

```
ffffffe0004ba4fa-ffffffe0004ba558: pci_remap_iospace (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
int pci_remap_iospace(const struct resource *res, phys_addr_t phys_addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (ffffffff81575cd7)
Location: drivers/pci/pci.c:3938
Inline: True
Inline callers:
  - drivers/pci/pci.c:devm_pci_remap_iospace
Direct callers:
  - drivers/pci/pci.c:devm_pci_remap_iospace
```
**Symbols:**

```
ffffffff81575c50-ffffffff81575c70: pci_remap_iospace.part.0 (STB_LOCAL)
ffffffff81575c70-ffffffff81575c94: pci_remap_iospace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
int pci_remap_iospace(const struct resource *res, phys_addr_t phys_addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (ffffffff81564437)
Location: drivers/pci/pci.c:3938
Inline: True
Inline callers:
  - drivers/pci/pci.c:devm_pci_remap_iospace
Direct callers:
  - drivers/pci/pci.c:devm_pci_remap_iospace
```
**Symbols:**

```
ffffffff815643b0-ffffffff815643d0: pci_remap_iospace.part.0 (STB_LOCAL)
ffffffff815643d0-ffffffff815643f4: pci_remap_iospace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
int pci_remap_iospace(const struct resource *res, phys_addr_t phys_addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (ffffffff81575507)
Location: drivers/pci/pci.c:3938
Inline: True
Inline callers:
  - drivers/pci/pci.c:devm_pci_remap_iospace
Direct callers:
  - drivers/pci/pci.c:devm_pci_remap_iospace
```
**Symbols:**

```
ffffffff81575480-ffffffff815754a0: pci_remap_iospace.part.0 (STB_LOCAL)
ffffffff815754a0-ffffffff815754c4: pci_remap_iospace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
int pci_remap_iospace(const struct resource *res, phys_addr_t phys_addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (ffffffff8158fad7)
Location: drivers/pci/pci.c:3938
Inline: True
Inline callers:
  - drivers/pci/pci.c:devm_pci_remap_iospace
Direct callers:
  - drivers/pci/pci.c:devm_pci_remap_iospace
```
**Symbols:**

```
ffffffff8158fa50-ffffffff8158fa70: pci_remap_iospace.part.0 (STB_LOCAL)
ffffffff8158fa70-ffffffff8158fa94: pci_remap_iospace (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
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
