# Function: <code>pci_dma_configure</code>

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
In drivers/pci/probe.c (ffffffff8143159d)
Location: drivers/pci/probe.c:1701
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_device_add
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
In drivers/pci/probe.c (ffffffff8147ccc0)
Location: drivers/pci/probe.c:1723
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_device_add
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
In drivers/pci/probe.c (ffffffff8149e220)
Location: drivers/pci/probe.c:1874
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_device_add
```
</details>
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int pci_dma_configure(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff81520b30)
Location: drivers/pci/pci-driver.c:1591
Inline: False
```
**Symbols:**

```
ffffffff81520b30-ffffffff81520bab: pci_dma_configure (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int pci_dma_configure(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff81536960)
Location: drivers/pci/pci-driver.c:1588
Inline: False
```
**Symbols:**

```
ffffffff81536960-ffffffff815369d7: pci_dma_configure (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int pci_dma_configure(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff81566250)
Location: drivers/pci/pci-driver.c:1622
Inline: False
```
**Symbols:**

```
ffffffff81566250-ffffffff815662ca: pci_dma_configure (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int pci_dma_configure(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff815875b0)
Location: drivers/pci/pci-driver.c:1635
Inline: False
```
**Symbols:**

```
ffffffff815875b0-ffffffff8158762a: pci_dma_configure (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int pci_dma_configure(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff8162d3b0)
Location: drivers/pci/pci-driver.c:1600
Inline: False
```
**Symbols:**

```
ffffffff8162d3b0-ffffffff8162d42a: pci_dma_configure (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int pci_dma_configure(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff81652aa0)
Location: drivers/pci/pci-driver.c:1579
Inline: False
```
**Symbols:**

```
ffffffff81652aa0-ffffffff81652b1c: pci_dma_configure (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int pci_dma_configure(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff81635560)
Location: drivers/pci/pci-driver.c:1579
Inline: False
```
**Symbols:**

```
ffffffff81635560-ffffffff816355df: pci_dma_configure (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int pci_dma_configure(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff816a5470)
Location: drivers/pci/pci-driver.c:1593
Inline: False
```
**Symbols:**

```
ffffffff816a5470-ffffffff816a54ef: pci_dma_configure (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int pci_dma_configure(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci-driver.c (0)
Location: drivers/pci/pci-driver.c:1622
Inline: False
```
**Symbols:**

```
ffffffff817c8160-ffffffff817c8255: pci_dma_configure (STB_LOCAL)
ffffffff81eab7d9-ffffffff81eab7ed: pci_dma_configure.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int pci_dma_configure(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci-driver.c (0)
Location: drivers/pci/pci-driver.c:1628
Inline: False
```
**Symbols:**

```
ffffffff818e59a0-ffffffff818e5a95: pci_dma_configure (STB_LOCAL)
ffffffff8208f314-ffffffff8208f328: pci_dma_configure.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int pci_dma_configure(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci-driver.c (0)
Location: drivers/pci/pci-driver.c:1629
Inline: False
```
**Symbols:**

```
ffffffff81928fe0-ffffffff819290d5: pci_dma_configure (STB_LOCAL)
ffffffff8210f67a-ffffffff8210f68e: pci_dma_configure.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int pci_dma_configure(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci-driver.c (0)
Location: drivers/pci/pci-driver.c:1642
Inline: False
```
**Symbols:**

```
ffffffff819717e0-ffffffff819718d5: pci_dma_configure (STB_LOCAL)
ffffffff821ed30f-ffffffff821ed323: pci_dma_configure.cold (STB_LOCAL)
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
int pci_dma_configure(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffff8000106eb250)
Location: drivers/pci/pci-driver.c:1635
Inline: False
```
**Symbols:**

```
ffff8000106eb250-ffff8000106eb310: pci_dma_configure (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int pci_dma_configure(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (c0886d1c)
Location: drivers/pci/pci-driver.c:1635
Inline: False
```
**Symbols:**

```
c0886d1c-c0886d80: pci_dma_configure (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int pci_dma_configure(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (c000000000866960)
Location: drivers/pci/pci-driver.c:1635
Inline: False
```
**Symbols:**

```
c000000000866960-c0000000008669fc: pci_dma_configure (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int pci_dma_configure(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffe0004c0c64)
Location: drivers/pci/pci-driver.c:1635
Inline: False
```
**Symbols:**

```
ffffffe0004c0c64-ffffffe0004c0cc2: pci_dma_configure (STB_LOCAL)
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
int pci_dma_configure(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff8157b5e0)
Location: drivers/pci/pci-driver.c:1635
Inline: False
```
**Symbols:**

```
ffffffff8157b5e0-ffffffff8157b65a: pci_dma_configure (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int pci_dma_configure(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff8156a210)
Location: drivers/pci/pci-driver.c:1635
Inline: False
```
**Symbols:**

```
ffffffff8156a210-ffffffff8156a28a: pci_dma_configure (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int pci_dma_configure(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff8157b300)
Location: drivers/pci/pci-driver.c:1635
Inline: False
```
**Symbols:**

```
ffffffff8157b300-ffffffff8157b37a: pci_dma_configure (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int pci_dma_configure(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff81595910)
Location: drivers/pci/pci-driver.c:1635
Inline: False
```
**Symbols:**

```
ffffffff81595910-ffffffff8159598a: pci_dma_configure (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
