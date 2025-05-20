# Function: <code>pci_configure_extended_tags</code>

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
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff814a66ad)
Location: drivers/pci/probe.c:1748
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_configure_device
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int pci_configure_extended_tags(struct pci_dev *dev, void *ign);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff814e6a50)
Location: drivers/pci/probe.c:1790
Inline: True
Direct callers:
  - drivers/pci/probe.c:pci_configure_device
```
**Symbols:**

```
ffffffff814e6a50-ffffffff814e6b4a: pci_configure_extended_tags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int pci_configure_extended_tags(struct pci_dev *dev, void *ign);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff81515fb0)
Location: drivers/pci/probe.c:1933
Inline: True
Direct callers:
  - drivers/pci/probe.c:pci_configure_device
```
**Symbols:**

```
ffffffff81515fb0-ffffffff815160aa: pci_configure_extended_tags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int pci_configure_extended_tags(struct pci_dev *dev, void *ign);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8152b790)
Location: drivers/pci/probe.c:1982
Inline: True
Direct callers:
  - drivers/pci/probe.c:pci_configure_device
```
**Symbols:**

```
ffffffff8152b790-ffffffff8152b88a: pci_configure_extended_tags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int pci_configure_extended_tags(struct pci_dev *dev, void *ign);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/probe.c (ffffffff8155a598)
Location: drivers/pci/probe.c:2192
Inline: True
Direct callers:
  - drivers/pci/probe.c:pci_configure_device
```
**Symbols:**

```
ffffffff8155d29a-ffffffff8155d2f4: pci_configure_extended_tags.cold (STB_LOCAL)
ffffffff8155a540-ffffffff8155a5e7: pci_configure_extended_tags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int pci_configure_extended_tags(struct pci_dev *dev, void *ign);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/probe.c (ffffffff8157b628)
Location: drivers/pci/probe.c:1937
Inline: True
Direct callers:
  - drivers/pci/probe.c:pci_configure_device
```
**Symbols:**

```
ffffffff8157e354-ffffffff8157e3ae: pci_configure_extended_tags.cold (STB_LOCAL)
ffffffff8157b5d0-ffffffff8157b677: pci_configure_extended_tags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int pci_configure_extended_tags(struct pci_dev *dev, void *ign);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/probe.c (ffffffff816207d6)
Location: drivers/pci/probe.c:2005
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_configure_device
Direct callers:
  - drivers/pci/probe.c:pci_configure_device
```
**Symbols:**

```
ffffffff8161ff60-ffffffff8161ffe2: pci_configure_extended_tags.part.0 (STB_LOCAL)
ffffffff81623122-ffffffff8162317c: pci_configure_extended_tags.part.0.cold (STB_LOCAL)
ffffffff81621170-ffffffff816211d5: pci_configure_extended_tags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int pci_configure_extended_tags(struct pci_dev *dev, void *ign);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/probe.c (ffffffff81646df6)
Location: drivers/pci/probe.c:2008
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_configure_device
Direct callers:
  - drivers/pci/probe.c:pci_configure_device
```
**Symbols:**

```
ffffffff816466b0-ffffffff81646732: pci_configure_extended_tags.part.0 (STB_LOCAL)
ffffffff81bf7308-ffffffff81bf7362: pci_configure_extended_tags.part.0.cold (STB_LOCAL)
ffffffff81647ce0-ffffffff81647d45: pci_configure_extended_tags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int pci_configure_extended_tags(struct pci_dev *dev, void *ign);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/probe.c (ffffffff8162a756)
Location: drivers/pci/probe.c:2051
Inline: True
Direct callers:
  - drivers/pci/probe.c:pci_configure_device
```
**Symbols:**

```
ffffffff81be93dd-ffffffff81be9437: pci_configure_extended_tags.cold (STB_LOCAL)
ffffffff8162a700-ffffffff8162a7a5: pci_configure_extended_tags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int pci_configure_extended_tags(struct pci_dev *dev, void *ign);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/probe.c (ffffffff81699c36)
Location: drivers/pci/probe.c:2086
Inline: True
Direct callers:
  - drivers/pci/probe.c:pci_configure_device
```
**Symbols:**

```
ffffffff81ce3d83-ffffffff81ce3ddd: pci_configure_extended_tags.cold (STB_LOCAL)
ffffffff81699be0-ffffffff81699c85: pci_configure_extended_tags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int pci_configure_extended_tags(struct pci_dev *dev, void *ign);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/probe.c (0)
Location: drivers/pci/probe.c:2059
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_configure_device
```
**Symbols:**

```
ffffffff81eaa7d6-ffffffff81eaa82e: pci_configure_extended_tags.cold (STB_LOCAL)
ffffffff817bb1d0-ffffffff817bb290: pci_configure_extended_tags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int pci_configure_extended_tags(struct pci_dev *dev, void *ign);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff818d6b70)
Location: drivers/pci/probe.c:2065
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_configure_device
```
**Symbols:**

```
ffffffff818d6b70-ffffffff818d6c82: pci_configure_extended_tags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int pci_configure_extended_tags(struct pci_dev *dev, void *ign);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff81919df0)
Location: drivers/pci/probe.c:2075
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_configure_device
```
**Symbols:**

```
ffffffff81919df0-ffffffff81919f02: pci_configure_extended_tags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int pci_configure_extended_tags(struct pci_dev *dev, void *ign);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff819621f0)
Location: drivers/pci/probe.c:2124
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_configure_device
```
**Symbols:**

```
ffffffff819621f0-ffffffff81962302: pci_configure_extended_tags (STB_GLOBAL)
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
int pci_configure_extended_tags(struct pci_dev *dev, void *ign);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffff8000106de9e8)
Location: drivers/pci/probe.c:1937
Inline: True
Direct callers:
  - drivers/pci/probe.c:pci_configure_device
  - drivers/pci/probe.c:pci_configure_device
```
**Symbols:**

```
ffff8000106de9e8-ffff8000106deae4: pci_configure_extended_tags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int pci_configure_extended_tags(struct pci_dev *dev, void *ign);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (c087a6ac)
Location: drivers/pci/probe.c:1937
Inline: True
Direct callers:
  - drivers/pci/probe.c:pci_configure_device
```
**Symbols:**

```
c087a6ac-c087a7cc: pci_configure_extended_tags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int pci_configure_extended_tags(struct pci_dev *dev, void *ign);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (c0000000008572a0)
Location: drivers/pci/probe.c:1937
Inline: True
Direct callers:
  - drivers/pci/probe.c:pci_device_add
```
**Symbols:**

```
c0000000008572a0-c000000000857410: pci_configure_extended_tags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int pci_configure_extended_tags(struct pci_dev *dev, void *ign);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffe0004b6bca)
Location: drivers/pci/probe.c:1937
Inline: True
Direct callers:
  - drivers/pci/probe.c:pci_configure_device
```
**Symbols:**

```
ffffffe0004b6bca-ffffffe0004b6c90: pci_configure_extended_tags (STB_GLOBAL)
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
int pci_configure_extended_tags(struct pci_dev *dev, void *ign);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/probe.c (ffffffff8156fb48)
Location: drivers/pci/probe.c:1937
Inline: True
Direct callers:
  - drivers/pci/probe.c:pci_configure_device
```
**Symbols:**

```
ffffffff81572874-ffffffff815728ce: pci_configure_extended_tags.cold (STB_LOCAL)
ffffffff8156faf0-ffffffff8156fb97: pci_configure_extended_tags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
int pci_configure_extended_tags(struct pci_dev *dev, void *ign);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/probe.c (ffffffff8155e2a8)
Location: drivers/pci/probe.c:1937
Inline: True
Direct callers:
  - drivers/pci/probe.c:pci_configure_device
```
**Symbols:**

```
ffffffff81560fd4-ffffffff8156102e: pci_configure_extended_tags.cold (STB_LOCAL)
ffffffff8155e250-ffffffff8155e2f7: pci_configure_extended_tags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
int pci_configure_extended_tags(struct pci_dev *dev, void *ign);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/probe.c (ffffffff8156f378)
Location: drivers/pci/probe.c:1937
Inline: True
Direct callers:
  - drivers/pci/probe.c:pci_configure_device
```
**Symbols:**

```
ffffffff815720a4-ffffffff815720fe: pci_configure_extended_tags.cold (STB_LOCAL)
ffffffff8156f320-ffffffff8156f3c7: pci_configure_extended_tags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
int pci_configure_extended_tags(struct pci_dev *dev, void *ign);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/probe.c (ffffffff81589858)
Location: drivers/pci/probe.c:1937
Inline: True
Direct callers:
  - drivers/pci/probe.c:pci_configure_device
```
**Symbols:**

```
ffffffff8158c584-ffffffff8158c5de: pci_configure_extended_tags.cold (STB_LOCAL)
ffffffff81589800-ffffffff815898a7: pci_configure_extended_tags (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
