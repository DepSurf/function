# Function: <code>pci_pme_capable</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
bool pci_pme_capable(struct pci_dev *dev, pci_power_t state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814334c0)
Location: drivers/pci/pci.c:1706
Inline: True
Inline callers:
  - drivers/pci/pci.c:__pci_enable_wake
```
**Symbols:**

```
ffffffff814334c0-ffffffff814334e1: pci_pme_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
bool pci_pme_capable(struct pci_dev *dev, pci_power_t state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8147eecb)
Location: drivers/pci/pci.c:1727
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_dev_check_d3cold
```
**Symbols:**

```
ffffffff8147ed30-ffffffff8147ed57: pci_pme_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
bool pci_pme_capable(struct pci_dev *dev, pci_power_t state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814a05b7)
Location: drivers/pci/pci.c:1752
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_dev_check_d3cold
  - drivers/pci/pci.c:pci_dev_run_wake
```
**Symbols:**

```
ffffffff814a03d0-ffffffff814a03f7: pci_pme_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
bool pci_pme_capable(struct pci_dev *dev, pci_power_t state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814aa267)
Location: drivers/pci/pci.c:1750
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_dev_check_d3cold
  - drivers/pci/pci.c:pci_dev_run_wake
```
**Symbols:**

```
ffffffff814aa200-ffffffff814aa227: pci_pme_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
bool pci_pme_capable(struct pci_dev *dev, pci_power_t state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814e94c7)
Location: drivers/pci/pci.c:1753
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_dev_check_d3cold
  - drivers/pci/pci.c:pci_dev_run_wake
```
**Symbols:**

```
ffffffff814e9460-ffffffff814e9487: pci_pme_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
bool pci_pme_capable(struct pci_dev *dev, pci_power_t state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81518c57)
Location: drivers/pci/pci.c:1817
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_dev_check_d3cold
  - drivers/pci/pci.c:pci_dev_run_wake
```
**Symbols:**

```
ffffffff81518bf0-ffffffff81518c17: pci_pme_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
bool pci_pme_capable(struct pci_dev *dev, pci_power_t state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8152e6c7)
Location: drivers/pci/pci.c:1990
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_dev_check_d3cold
  - drivers/pci/pci.c:pci_dev_run_wake
```
**Symbols:**

```
ffffffff8152e660-ffffffff8152e687: pci_pme_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
bool pci_pme_capable(struct pci_dev *dev, pci_power_t state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8155de77)
Location: drivers/pci/pci.c:2063
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_dev_check_d3cold
  - drivers/pci/pci.c:pci_dev_run_wake
```
**Symbols:**

```
ffffffff8155de10-ffffffff8155de37: pci_pme_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
bool pci_pme_capable(struct pci_dev *dev, pci_power_t state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8157eee7)
Location: drivers/pci/pci.c:2059
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_dev_check_d3cold
  - drivers/pci/pci.c:pci_dev_run_wake
```
**Symbols:**

```
ffffffff8157ee80-ffffffff8157eea7: pci_pme_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool pci_pme_capable(struct pci_dev *dev, pci_power_t state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff816244e7)
Location: drivers/pci/pci.c:2129
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_dev_check_d3cold
  - drivers/pci/pci.c:pci_dev_run_wake
```
**Symbols:**

```
ffffffff816242f0-ffffffff81624317: pci_pme_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool pci_pme_capable(struct pci_dev *dev, pci_power_t state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8164a0a7)
Location: drivers/pci/pci.c:2273
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_dev_check_d3cold
  - drivers/pci/pci.c:pci_dev_run_wake
```
**Symbols:**

```
ffffffff81649eb0-ffffffff81649ed7: pci_pme_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool pci_pme_capable(struct pci_dev *dev, pci_power_t state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8162cc77)
Location: drivers/pci/pci.c:2303
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_dev_check_d3cold
  - drivers/pci/pci.c:pci_dev_run_wake
```
**Symbols:**

```
ffffffff8162ca60-ffffffff8162ca87: pci_pme_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool pci_pme_capable(struct pci_dev *dev, pci_power_t state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (ffffffff8169e7b2)
Location: drivers/pci/pci.c:2334
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_dev_check_d3cold
  - drivers/pci/pci.c:pci_dev_check_d3cold
  - drivers/pci/pci.c:pci_dev_run_wake
  - drivers/pci/pci.c:pci_dev_run_wake
```
**Symbols:**

```
ffffffff81ce4667-ffffffff81ce4686: pci_pme_capable.cold (STB_LOCAL)
ffffffff8169e820-ffffffff8169e85d: pci_pme_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool pci_pme_capable(struct pci_dev *dev, pci_power_t state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (ffffffff817c061c)
Location: drivers/pci/pci.c:2396
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_dev_check_d3cold
  - drivers/pci/pci.c:pci_dev_check_d3cold
  - drivers/pci/pci.c:pci_dev_run_wake
  - drivers/pci/pci.c:pci_dev_run_wake
  - drivers/pci/pci.c:__pci_enable_wake
  - drivers/pci/pci.c:__pci_enable_wake
  - drivers/pci/pci.c:__pci_enable_wake
  - drivers/pci/pci.c:__pci_enable_wake
```
**Symbols:**

```
ffffffff81eaafff-ffffffff81eab018: pci_pme_capable.cold (STB_LOCAL)
ffffffff817c0780-ffffffff817c07d1: pci_pme_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool pci_pme_capable(struct pci_dev *dev, pci_power_t state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (ffffffff818dce2c)
Location: drivers/pci/pci.c:2370
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_dev_check_d3cold
  - drivers/pci/pci.c:pci_dev_check_d3cold
  - drivers/pci/pci.c:pci_dev_run_wake
  - drivers/pci/pci.c:pci_dev_run_wake
  - drivers/pci/pci.c:__pci_enable_wake
  - drivers/pci/pci.c:__pci_enable_wake
  - drivers/pci/pci.c:__pci_enable_wake
  - drivers/pci/pci.c:__pci_enable_wake
```
**Symbols:**

```
ffffffff8208f04d-ffffffff8208f066: pci_pme_capable.cold (STB_LOCAL)
ffffffff818dcfc0-ffffffff818dd011: pci_pme_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool pci_pme_capable(struct pci_dev *dev, pci_power_t state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (ffffffff819201de)
Location: drivers/pci/pci.c:2408
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_dev_check_d3cold
  - drivers/pci/pci.c:pci_dev_check_d3cold
  - drivers/pci/pci.c:pci_dev_run_wake
  - drivers/pci/pci.c:pci_dev_run_wake
  - drivers/pci/pci.c:__pci_enable_wake
  - drivers/pci/pci.c:__pci_enable_wake
  - drivers/pci/pci.c:__pci_enable_wake
  - drivers/pci/pci.c:__pci_enable_wake
```
**Symbols:**

```
ffffffff8210f3b7-ffffffff8210f3d0: pci_pme_capable.cold (STB_LOCAL)
ffffffff819204a0-ffffffff819204f1: pci_pme_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool pci_pme_capable(struct pci_dev *dev, pci_power_t state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (ffffffff8196836e)
Location: drivers/pci/pci.c:2505
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_dev_check_d3cold
  - drivers/pci/pci.c:pci_dev_check_d3cold
  - drivers/pci/pci.c:pci_dev_run_wake
  - drivers/pci/pci.c:pci_dev_run_wake
  - drivers/pci/pci.c:__pci_enable_wake
  - drivers/pci/pci.c:__pci_enable_wake
  - drivers/pci/pci.c:__pci_enable_wake
  - drivers/pci/pci.c:__pci_enable_wake
```
**Symbols:**

```
ffffffff821ed03e-ffffffff821ed057: pci_pme_capable.cold (STB_LOCAL)
ffffffff81968630-ffffffff81968683: pci_pme_capable (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
bool pci_pme_capable(struct pci_dev *dev, pci_power_t state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffff8000106e197c)
Location: drivers/pci/pci.c:2059
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_dev_check_d3cold
  - drivers/pci/pci.c:pci_dev_run_wake
```
**Symbols:**

```
ffff8000106e18d8-ffff8000106e1928: pci_pme_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
bool pci_pme_capable(struct pci_dev *dev, pci_power_t state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (c087d4d8)
Location: drivers/pci/pci.c:2059
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_dev_check_d3cold
  - drivers/pci/pci.c:pci_dev_run_wake
```
**Symbols:**

```
c087d458-c087d48c: pci_pme_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
bool pci_pme_capable(struct pci_dev *dev, pci_power_t state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (c00000000085ad18)
Location: drivers/pci/pci.c:2059
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_dev_check_d3cold
  - drivers/pci/pci.c:pci_dev_run_wake
```
**Symbols:**

```
c00000000085ac80-c00000000085acb8: pci_pme_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
bool pci_pme_capable(struct pci_dev *dev, pci_power_t state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffe0004b94a6)
Location: drivers/pci/pci.c:2059
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_dev_check_d3cold
  - drivers/pci/pci.c:pci_dev_run_wake
```
**Symbols:**

```
ffffffe0004b9420-ffffffe0004b945a: pci_pme_capable (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
bool pci_pme_capable(struct pci_dev *dev, pci_power_t state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81573407)
Location: drivers/pci/pci.c:2059
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_dev_check_d3cold
  - drivers/pci/pci.c:pci_dev_run_wake
```
**Symbols:**

```
ffffffff815733a0-ffffffff815733c7: pci_pme_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
bool pci_pme_capable(struct pci_dev *dev, pci_power_t state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81561b67)
Location: drivers/pci/pci.c:2059
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_dev_check_d3cold
  - drivers/pci/pci.c:pci_dev_run_wake
```
**Symbols:**

```
ffffffff81561b00-ffffffff81561b27: pci_pme_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
bool pci_pme_capable(struct pci_dev *dev, pci_power_t state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81572c37)
Location: drivers/pci/pci.c:2059
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_dev_check_d3cold
  - drivers/pci/pci.c:pci_dev_run_wake
```
**Symbols:**

```
ffffffff81572bd0-ffffffff81572bf7: pci_pme_capable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
bool pci_pme_capable(struct pci_dev *dev, pci_power_t state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8158d117)
Location: drivers/pci/pci.c:2059
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_dev_check_d3cold
  - drivers/pci/pci.c:pci_dev_run_wake
```
**Symbols:**

```
ffffffff8158d0b0-ffffffff8158d0d7: pci_pme_capable (STB_GLOBAL)
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
