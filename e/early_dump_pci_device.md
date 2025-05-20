# Function: <code>early_dump_pci_device</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void early_dump_pci_device(u8 bus, u8 slot, u8 func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/early.c (ffffffff816faa00)
Location: arch/x86/pci/early.c:59
Inline: False
Direct callers:
  - arch/x86/pci/early.c:early_dump_pci_devices
```
**Symbols:**

```
ffffffff816faa00-ffffffff816faabc: early_dump_pci_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void early_dump_pci_device(u8 bus, u8 slot, u8 func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/early.c (ffffffff8175f880)
Location: arch/x86/pci/early.c:59
Inline: False
Direct callers:
  - arch/x86/pci/early.c:early_dump_pci_devices
```
**Symbols:**

```
ffffffff8175f880-ffffffff8175f93f: early_dump_pci_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void early_dump_pci_device(u8 bus, u8 slot, u8 func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/early.c (ffffffff8178bdc0)
Location: arch/x86/pci/early.c:59
Inline: False
Direct callers:
  - arch/x86/pci/early.c:early_dump_pci_devices
```
**Symbols:**

```
ffffffff8178bdc0-ffffffff8178be7f: early_dump_pci_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void early_dump_pci_device(u8 bus, u8 slot, u8 func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/early.c (ffffffff817aad80)
Location: arch/x86/pci/early.c:59
Inline: False
Direct callers:
  - arch/x86/pci/early.c:early_dump_pci_devices
```
**Symbols:**

```
ffffffff817aad80-ffffffff817aae3f: early_dump_pci_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void early_dump_pci_device(u8 bus, u8 slot, u8 func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/early.c (ffffffff81822270)
Location: arch/x86/pci/early.c:60
Inline: False
Direct callers:
  - arch/x86/pci/early.c:early_dump_pci_devices
```
**Symbols:**

```
ffffffff81822270-ffffffff8182232f: early_dump_pci_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void early_dump_pci_device(u8 bus, u8 slot, u8 func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/early.c (ffffffff8186c5d9)
Location: arch/x86/pci/early.c:60
Inline: False
Direct callers:
  - arch/x86/pci/early.c:early_dump_pci_devices
```
**Symbols:**

```
ffffffff8186c5d9-ffffffff8186c6b9: early_dump_pci_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void early_dump_pci_device(struct pci_dev *pdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff81529fe0)
Location: drivers/pci/probe.c:1582
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_setup_device
```
**Symbols:**

```
ffffffff81529fe0-ffffffff8152a08e: early_dump_pci_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void early_dump_pci_device(struct pci_dev *pdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8155c69d)
Location: drivers/pci/probe.c:1683
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_setup_device
```
**Symbols:**

```
ffffffff8155c69d-ffffffff8155c74b: early_dump_pci_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void early_dump_pci_device(struct pci_dev *pdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8157d74e)
Location: drivers/pci/probe.c:1697
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_setup_device
```
**Symbols:**

```
ffffffff8157d74e-ffffffff8157d7fc: early_dump_pci_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void early_dump_pci_device(struct pci_dev *pdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff81622faf)
Location: drivers/pci/probe.c:1745
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_setup_device
```
**Symbols:**

```
ffffffff81622faf-ffffffff8162305d: early_dump_pci_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void early_dump_pci_device(struct pci_dev *pdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff81bf7195)
Location: drivers/pci/probe.c:1748
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_setup_device
```
**Symbols:**

```
ffffffff81bf7195-ffffffff81bf7243: early_dump_pci_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void early_dump_pci_device(struct pci_dev *pdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff81be8d97)
Location: drivers/pci/probe.c:1791
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_setup_device
```
**Symbols:**

```
ffffffff81be8d97-ffffffff81be8e45: early_dump_pci_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void early_dump_pci_device(struct pci_dev *pdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff81ce3191)
Location: drivers/pci/probe.c:1820
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_setup_device
```
**Symbols:**

```
ffffffff81ce3191-ffffffff81ce325b: early_dump_pci_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void early_dump_pci_device(struct pci_dev *pdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff81ea9c85)
Location: drivers/pci/probe.c:1793
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_setup_device
```
**Symbols:**

```
ffffffff81ea9c85-ffffffff81ea9d71: early_dump_pci_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void early_dump_pci_device(struct pci_dev *pdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff818d48f0)
Location: drivers/pci/probe.c:1799
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_setup_device
```
**Symbols:**

```
ffffffff818d48f0-ffffffff818d49e2: early_dump_pci_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void early_dump_pci_device(struct pci_dev *pdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff81917b40)
Location: drivers/pci/probe.c:1807
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_setup_device
```
**Symbols:**

```
ffffffff81917b40-ffffffff81917c32: early_dump_pci_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void early_dump_pci_device(struct pci_dev *pdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff81960150)
Location: drivers/pci/probe.c:1818
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_setup_device
```
**Symbols:**

```
ffffffff81960150-ffffffff81960242: early_dump_pci_device (STB_LOCAL)
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
void early_dump_pci_device(struct pci_dev *pdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffff8000106e1048)
Location: drivers/pci/probe.c:1697
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_setup_device
```
**Symbols:**

```
ffff8000106e1048-ffff8000106e1100: early_dump_pci_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void early_dump_pci_device(struct pci_dev *pdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (c087cd38)
Location: drivers/pci/probe.c:1697
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_setup_device
```
**Symbols:**

```
c087cd38-c087cdf8: early_dump_pci_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void early_dump_pci_device(struct pci_dev *pdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (c00000000085a264)
Location: drivers/pci/probe.c:1697
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_setup_device
```
**Symbols:**

```
c00000000085a264-c00000000085a340: early_dump_pci_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void early_dump_pci_device(struct pci_dev *pdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffe0004b8d0a)
Location: drivers/pci/probe.c:1697
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_setup_device
```
**Symbols:**

```
ffffffe0004b8d0a-ffffffe0004b8d90: early_dump_pci_device (STB_LOCAL)
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
void early_dump_pci_device(struct pci_dev *pdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff81571c6e)
Location: drivers/pci/probe.c:1697
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_setup_device
```
**Symbols:**

```
ffffffff81571c6e-ffffffff81571d1c: early_dump_pci_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void early_dump_pci_device(struct pci_dev *pdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff815603ce)
Location: drivers/pci/probe.c:1697
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_setup_device
```
**Symbols:**

```
ffffffff815603ce-ffffffff8156047c: early_dump_pci_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void early_dump_pci_device(struct pci_dev *pdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8157149e)
Location: drivers/pci/probe.c:1697
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_setup_device
```
**Symbols:**

```
ffffffff8157149e-ffffffff8157154c: early_dump_pci_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void early_dump_pci_device(struct pci_dev *pdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8158b97e)
Location: drivers/pci/probe.c:1697
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_setup_device
```
**Symbols:**

```
ffffffff8158b97e-ffffffff8158ba2c: early_dump_pci_device (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct pci_dev *pdev</code>
</li>
<li>
<b>Param removed. </b>
<code>u8 bus</code>
</li>
<li>
<b>Param removed. </b>
<code>u8 slot</code>
</li>
<li>
<b>Param removed. </b>
<code>u8 func</code>
</li>
</ul>
</details>
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
