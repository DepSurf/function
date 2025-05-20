# Function: <code>pci_pm_init</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void pci_pm_init(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81437360)
Location: drivers/pci/pci.c:2163
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_device_add
```
**Symbols:**

```
ffffffff81437360-ffffffff814375a3: pci_pm_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void pci_pm_init(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81482f60)
Location: drivers/pci/pci.c:2342
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_device_add
```
**Symbols:**

```
ffffffff81482f60-ffffffff814831ff: pci_pm_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void pci_pm_init(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814a46c0)
Location: drivers/pci/pci.c:2380
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_device_add
```
**Symbols:**

```
ffffffff814a46c0-ffffffff814a495f: pci_pm_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void pci_pm_init(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814ae780)
Location: drivers/pci/pci.c:2397
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_device_add
```
**Symbols:**

```
ffffffff814ae780-ffffffff814ae9dd: pci_pm_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void pci_pm_init(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814edb50)
Location: drivers/pci/pci.c:2406
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_device_add
```
**Symbols:**

```
ffffffff814edb50-ffffffff814eddad: pci_pm_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void pci_pm_init(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8151d780)
Location: drivers/pci/pci.c:2481
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_device_add
```
**Symbols:**

```
ffffffff8151d780-ffffffff8151d9e3: pci_pm_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void pci_pm_init(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81532ec0)
Location: drivers/pci/pci.c:2671
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_device_add
```
**Symbols:**

```
ffffffff81532ec0-ffffffff81533145: pci_pm_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void pci_pm_init(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (0)
Location: drivers/pci/pci.c:2786
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_device_add
```
**Symbols:**

```
ffffffff81564b01-ffffffff81564bf6: pci_pm_init.cold (STB_LOCAL)
ffffffff81562630-ffffffff815627b1: pci_pm_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void pci_pm_init(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (0)
Location: drivers/pci/pci.c:2782
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_device_add
```
**Symbols:**

```
ffffffff81585e1c-ffffffff81585f11: pci_pm_init.cold (STB_LOCAL)
ffffffff815837d0-ffffffff81583951: pci_pm_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void pci_pm_init(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (0)
Location: drivers/pci/pci.c:2852
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_init_capabilities
```
**Symbols:**

```
ffffffff8162cc7e-ffffffff8162cd75: pci_pm_init.cold (STB_LOCAL)
ffffffff8162a330-ffffffff8162a4df: pci_pm_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void pci_pm_init(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (0)
Location: drivers/pci/pci.c:3019
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_init_capabilities
```
**Symbols:**

```
ffffffff81bf7e05-ffffffff81bf7efc: pci_pm_init.cold (STB_LOCAL)
ffffffff81650790-ffffffff81650942: pci_pm_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void pci_pm_init(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (0)
Location: drivers/pci/pci.c:3049
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_device_add
```
**Symbols:**

```
ffffffff81be9cac-ffffffff81be9da7: pci_pm_init.cold (STB_LOCAL)
ffffffff816333a0-ffffffff81633538: pci_pm_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void pci_pm_init(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (0)
Location: drivers/pci/pci.c:3091
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_device_add
```
**Symbols:**

```
ffffffff81ce4933-ffffffff81ce4a2e: pci_pm_init.cold (STB_LOCAL)
ffffffff816a3540-ffffffff816a36d8: pci_pm_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void pci_pm_init(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (0)
Location: drivers/pci/pci.c:3178
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_device_add
```
**Symbols:**

```
ffffffff81eab398-ffffffff81eab493: pci_pm_init.cold (STB_LOCAL)
ffffffff817c57a0-ffffffff817c5958: pci_pm_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void pci_pm_init(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff818e28c0)
Location: drivers/pci/pci.c:3128
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_device_add
```
**Symbols:**

```
ffffffff818e28c0-ffffffff818e2b77: pci_pm_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void pci_pm_init(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81925d00)
Location: drivers/pci/pci.c:3166
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_device_add
```
**Symbols:**

```
ffffffff81925d00-ffffffff81925fb7: pci_pm_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void pci_pm_init(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8196e480)
Location: drivers/pci/pci.c:3279
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_device_add
```
**Symbols:**

```
ffffffff8196e480-ffffffff8196e747: pci_pm_init (STB_GLOBAL)
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
void pci_pm_init(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffff8000106e77c8)
Location: drivers/pci/pci.c:2782
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_device_add
```
**Symbols:**

```
ffff8000106e77c8-ffff8000106e7a40: pci_pm_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void pci_pm_init(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (c08828a4)
Location: drivers/pci/pci.c:2782
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_device_add
```
**Symbols:**

```
c08828a4-c0882b48: pci_pm_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void pci_pm_init(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (c000000000861fb0)
Location: drivers/pci/pci.c:2782
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_device_add
```
**Symbols:**

```
c000000000861fb0-c0000000008622e8: pci_pm_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void pci_pm_init(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffe0004bdea0)
Location: drivers/pci/pci.c:2782
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_device_add
```
**Symbols:**

```
ffffffe0004bdea0-ffffffe0004be13a: pci_pm_init (STB_GLOBAL)
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
void pci_pm_init(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (0)
Location: drivers/pci/pci.c:2782
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_device_add
```
**Symbols:**

```
ffffffff8157a33c-ffffffff8157a431: pci_pm_init.cold (STB_LOCAL)
ffffffff81577cf0-ffffffff81577e71: pci_pm_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void pci_pm_init(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (0)
Location: drivers/pci/pci.c:2782
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_device_add
```
**Symbols:**

```
ffffffff81568a7c-ffffffff81568b71: pci_pm_init.cold (STB_LOCAL)
ffffffff81566430-ffffffff815665b1: pci_pm_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void pci_pm_init(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (0)
Location: drivers/pci/pci.c:2782
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_device_add
```
**Symbols:**

```
ffffffff81579b6c-ffffffff81579c61: pci_pm_init.cold (STB_LOCAL)
ffffffff81577520-ffffffff815776a1: pci_pm_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void pci_pm_init(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (0)
Location: drivers/pci/pci.c:2782
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_device_add
```
**Symbols:**

```
ffffffff8159401c-ffffffff81594111: pci_pm_init.cold (STB_LOCAL)
ffffffff815919e0-ffffffff81591b61: pci_pm_init (STB_GLOBAL)
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
