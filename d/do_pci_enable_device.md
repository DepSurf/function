# Function: <code>do_pci_enable_device</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int do_pci_enable_device(struct pci_dev *dev, int bars);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81436af0)
Location: drivers/pci/pci.c:1249
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_enable_device_flags
```
**Symbols:**

```
ffffffff81436af0-ffffffff81436bf9: do_pci_enable_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int do_pci_enable_device(struct pci_dev *dev, int bars);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81482680)
Location: drivers/pci/pci.c:1270
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_enable_device_flags
```
**Symbols:**

```
ffffffff81482680-ffffffff81482789: do_pci_enable_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int do_pci_enable_device(struct pci_dev *dev, int bars);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814a3c10)
Location: drivers/pci/pci.c:1295
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_enable_device_flags
```
**Symbols:**

```
ffffffff814a3c10-ffffffff814a3d19: do_pci_enable_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int do_pci_enable_device(struct pci_dev *dev, int bars);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814adc40)
Location: drivers/pci/pci.c:1293
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_enable_device_flags
```
**Symbols:**

```
ffffffff814adc40-ffffffff814add36: do_pci_enable_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int do_pci_enable_device(struct pci_dev *dev, int bars);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814ed020)
Location: drivers/pci/pci.c:1296
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_enable_device_flags
```
**Symbols:**

```
ffffffff814ed020-ffffffff814ed116: do_pci_enable_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int do_pci_enable_device(struct pci_dev *dev, int bars);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8151cc40)
Location: drivers/pci/pci.c:1347
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_enable_device_flags
```
**Symbols:**

```
ffffffff8151cc40-ffffffff8151cd38: do_pci_enable_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int do_pci_enable_device(struct pci_dev *dev, int bars);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81532340)
Location: drivers/pci/pci.c:1520
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_enable_device_flags
```
**Symbols:**

```
ffffffff81532340-ffffffff81532438: do_pci_enable_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int do_pci_enable_device(struct pci_dev *dev, int bars);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81561a10)
Location: drivers/pci/pci.c:1594
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_enable_device_flags
```
**Symbols:**

```
ffffffff81561a10-ffffffff81561b0f: do_pci_enable_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int do_pci_enable_device(struct pci_dev *dev, int bars);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81582bb0)
Location: drivers/pci/pci.c:1590
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_enable_device_flags
```
**Symbols:**

```
ffffffff81582bb0-ffffffff81582caf: do_pci_enable_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (ffffffff8162b589)
Location: drivers/pci/pci.c:1660
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_enable_device_flags
Direct callers:
  - drivers/pci/pci.c:pci_enable_device_flags
```
**Symbols:**

```
ffffffff81629750-ffffffff8162982f: do_pci_enable_device.part.0 (STB_LOCAL)
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
In drivers/pci/pci.c (ffffffff81651289)
Location: drivers/pci/pci.c:1796
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_enable_device_flags
Direct callers:
  - drivers/pci/pci.c:pci_enable_device_flags
```
**Symbols:**

```
ffffffff8164fb20-ffffffff8164fbff: do_pci_enable_device.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int do_pci_enable_device(struct pci_dev *dev, int bars);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff816326d0)
Location: drivers/pci/pci.c:1826
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_enable_device_flags
```
**Symbols:**

```
ffffffff816326d0-ffffffff816327cf: do_pci_enable_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int do_pci_enable_device(struct pci_dev *dev, int bars);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff816a2830)
Location: drivers/pci/pci.c:1861
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_enable_device_flags
```
**Symbols:**

```
ffffffff816a2830-ffffffff816a292f: do_pci_enable_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int do_pci_enable_device(struct pci_dev *dev, int bars);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff817c4920)
Location: drivers/pci/pci.c:1926
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_enable_device_flags
```
**Symbols:**

```
ffffffff817c4920-ffffffff817c4a2c: do_pci_enable_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int do_pci_enable_device(struct pci_dev *dev, int bars);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff818e18a0)
Location: drivers/pci/pci.c:1900
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_enable_device_flags
```
**Symbols:**

```
ffffffff818e18a0-ffffffff818e19ac: do_pci_enable_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int do_pci_enable_device(struct pci_dev *dev, int bars);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81924ce0)
Location: drivers/pci/pci.c:1938
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_enable_device_flags
```
**Symbols:**

```
ffffffff81924ce0-ffffffff81924dec: do_pci_enable_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int do_pci_enable_device(struct pci_dev *dev, int bars);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8196d3b0)
Location: drivers/pci/pci.c:2035
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_enable_device_flags
```
**Symbols:**

```
ffffffff8196d3b0-ffffffff8196d4be: do_pci_enable_device (STB_LOCAL)
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
int do_pci_enable_device(struct pci_dev *dev, int bars);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffff8000106e68b0)
Location: drivers/pci/pci.c:1590
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_enable_device_flags
```
**Symbols:**

```
ffff8000106e68b0-ffff8000106e69b8: do_pci_enable_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int do_pci_enable_device(struct pci_dev *dev, int bars);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (c0881b80)
Location: drivers/pci/pci.c:1590
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_enable_device_flags
```
**Symbols:**

```
c0881b80-c0881c9c: do_pci_enable_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int do_pci_enable_device(struct pci_dev *dev, int bars);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (c000000000860d10)
Location: drivers/pci/pci.c:1590
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_enable_device_flags
```
**Symbols:**

```
c000000000860d10-c000000000860e34: do_pci_enable_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int do_pci_enable_device(struct pci_dev *dev, int bars);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffe0004bd252)
Location: drivers/pci/pci.c:1590
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_enable_device_flags
```
**Symbols:**

```
ffffffe0004bd252-ffffffe0004bd336: do_pci_enable_device (STB_LOCAL)
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
int do_pci_enable_device(struct pci_dev *dev, int bars);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff815770d0)
Location: drivers/pci/pci.c:1590
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_enable_device_flags
```
**Symbols:**

```
ffffffff815770d0-ffffffff815771cf: do_pci_enable_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int do_pci_enable_device(struct pci_dev *dev, int bars);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81565830)
Location: drivers/pci/pci.c:1590
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_enable_device_flags
```
**Symbols:**

```
ffffffff81565830-ffffffff8156592f: do_pci_enable_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int do_pci_enable_device(struct pci_dev *dev, int bars);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81576900)
Location: drivers/pci/pci.c:1590
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_enable_device_flags
```
**Symbols:**

```
ffffffff81576900-ffffffff815769ff: do_pci_enable_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int do_pci_enable_device(struct pci_dev *dev, int bars);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81590de0)
Location: drivers/pci/pci.c:1590
Inline: True
Direct callers:
  - drivers/pci/pci.c:pci_enable_device_flags
```
**Symbols:**

```
ffffffff81590de0-ffffffff81590edf: do_pci_enable_device (STB_LOCAL)
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
