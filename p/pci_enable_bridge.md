# Function: <code>pci_enable_bridge</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void pci_enable_bridge(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81437e70)
Location: drivers/pci/pci.c:1298
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_enable_bridge
  - drivers/pci/pci.c:pci_enable_device_flags
```
**Symbols:**

```
ffffffff81437e70-ffffffff81437ef8: pci_enable_bridge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void pci_enable_bridge(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81483b00)
Location: drivers/pci/pci.c:1319
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_enable_device_flags
  - drivers/pci/pci.c:pci_enable_bridge
```
**Symbols:**

```
ffffffff81483b00-ffffffff81483b88: pci_enable_bridge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void pci_enable_bridge(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814a5260)
Location: drivers/pci/pci.c:1344
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_enable_device_flags
  - drivers/pci/pci.c:pci_enable_bridge
```
**Symbols:**

```
ffffffff814a5260-ffffffff814a52e8: pci_enable_bridge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void pci_enable_bridge(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814af270)
Location: drivers/pci/pci.c:1342
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_enable_device_flags
  - drivers/pci/pci.c:pci_enable_bridge
```
**Symbols:**

```
ffffffff814af270-ffffffff814af2fa: pci_enable_bridge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void pci_enable_bridge(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814ee790)
Location: drivers/pci/pci.c:1345
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_enable_device_flags
  - drivers/pci/pci.c:pci_enable_bridge
```
**Symbols:**

```
ffffffff814ee790-ffffffff814ee81a: pci_enable_bridge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void pci_enable_bridge(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8151e410)
Location: drivers/pci/pci.c:1396
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_enable_device_flags
  - drivers/pci/pci.c:pci_enable_bridge
```
**Symbols:**

```
ffffffff8151e410-ffffffff8151e498: pci_enable_bridge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void pci_enable_bridge(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff815341a0)
Location: drivers/pci/pci.c:1569
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_enable_device_flags
  - drivers/pci/pci.c:pci_enable_bridge
```
**Symbols:**

```
ffffffff815341a0-ffffffff81534228: pci_enable_bridge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void pci_enable_bridge(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (0)
Location: drivers/pci/pci.c:1643
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_enable_device_flags
  - drivers/pci/pci.c:pci_enable_bridge
```
**Symbols:**

```
ffffffff81563680-ffffffff815636fe: pci_enable_bridge (STB_LOCAL)
ffffffff81564d97-ffffffff81564db2: pci_enable_bridge.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void pci_enable_bridge(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (0)
Location: drivers/pci/pci.c:1639
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_enable_device_flags
  - drivers/pci/pci.c:pci_enable_bridge
```
**Symbols:**

```
ffffffff81584840-ffffffff815848be: pci_enable_bridge (STB_LOCAL)
ffffffff815860b2-ffffffff815860cd: pci_enable_bridge.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void pci_enable_bridge(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (0)
Location: drivers/pci/pci.c:1709
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_enable_device_flags
  - drivers/pci/pci.c:pci_enable_bridge
```
**Symbols:**

```
ffffffff8162b410-ffffffff8162b497: pci_enable_bridge (STB_LOCAL)
ffffffff8162cdc0-ffffffff8162cddb: pci_enable_bridge.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void pci_enable_bridge(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (0)
Location: drivers/pci/pci.c:1845
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_enable_device_flags
  - drivers/pci/pci.c:pci_enable_bridge
```
**Symbols:**

```
ffffffff81651110-ffffffff81651197: pci_enable_bridge (STB_LOCAL)
ffffffff81bf7f47-ffffffff81bf7f62: pci_enable_bridge.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void pci_enable_bridge(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (0)
Location: drivers/pci/pci.c:1875
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_enable_device_flags
  - drivers/pci/pci.c:pci_enable_bridge
```
**Symbols:**

```
ffffffff81633b50-ffffffff81633bd7: pci_enable_bridge (STB_LOCAL)
ffffffff81be9df2-ffffffff81be9e0d: pci_enable_bridge.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void pci_enable_bridge(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (0)
Location: drivers/pci/pci.c:1910
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_enable_device_flags
  - drivers/pci/pci.c:pci_enable_bridge
```
**Symbols:**

```
ffffffff816a3d00-ffffffff816a3d87: pci_enable_bridge (STB_LOCAL)
ffffffff81ce4a8d-ffffffff81ce4aa8: pci_enable_bridge.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void pci_enable_bridge(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (0)
Location: drivers/pci/pci.c:1975
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_enable_device_flags
  - drivers/pci/pci.c:pci_enable_bridge
```
**Symbols:**

```
ffffffff817c60a0-ffffffff817c613a: pci_enable_bridge (STB_LOCAL)
ffffffff81eab508-ffffffff81eab522: pci_enable_bridge.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void pci_enable_bridge(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff818e33e0)
Location: drivers/pci/pci.c:1949
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_enable_device_flags
  - drivers/pci/pci.c:pci_enable_bridge
```
**Symbols:**

```
ffffffff818e33e0-ffffffff818e348d: pci_enable_bridge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void pci_enable_bridge(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81926830)
Location: drivers/pci/pci.c:1987
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_enable_device_flags
  - drivers/pci/pci.c:pci_enable_bridge
```
**Symbols:**

```
ffffffff81926830-ffffffff819268dd: pci_enable_bridge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void pci_enable_bridge(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8196efd0)
Location: drivers/pci/pci.c:2084
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_enable_device_flags
  - drivers/pci/pci.c:pci_enable_bridge
```
**Symbols:**

```
ffffffff8196efd0-ffffffff8196f07d: pci_enable_bridge (STB_LOCAL)
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
void pci_enable_bridge(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffff8000106e8db0)
Location: drivers/pci/pci.c:1639
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_enable_device_flags
  - drivers/pci/pci.c:pci_enable_bridge
```
**Symbols:**

```
ffff8000106e8db0-ffff8000106e8e54: pci_enable_bridge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void pci_enable_bridge(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (c0883de0)
Location: drivers/pci/pci.c:1639
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_enable_device_flags
  - drivers/pci/pci.c:pci_enable_bridge
```
**Symbols:**

```
c0883de0-c0883e80: pci_enable_bridge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void pci_enable_bridge(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (c000000000863b20)
Location: drivers/pci/pci.c:1639
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_enable_device_flags
  - drivers/pci/pci.c:pci_enable_bridge
```
**Symbols:**

```
c000000000863b20-c000000000863c04: pci_enable_bridge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void pci_enable_bridge(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffe0004bf25c)
Location: drivers/pci/pci.c:1639
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_enable_device_flags
  - drivers/pci/pci.c:pci_enable_bridge
```
**Symbols:**

```
ffffffe0004bf25c-ffffffe0004bf2fc: pci_enable_bridge (STB_LOCAL)
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
void pci_enable_bridge(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (0)
Location: drivers/pci/pci.c:1639
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_enable_device_flags
  - drivers/pci/pci.c:pci_enable_bridge
```
**Symbols:**

```
ffffffff81578d60-ffffffff81578dde: pci_enable_bridge (STB_LOCAL)
ffffffff8157a5d2-ffffffff8157a5ed: pci_enable_bridge.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void pci_enable_bridge(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (0)
Location: drivers/pci/pci.c:1639
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_enable_device_flags
  - drivers/pci/pci.c:pci_enable_bridge
```
**Symbols:**

```
ffffffff815674a0-ffffffff8156751e: pci_enable_bridge (STB_LOCAL)
ffffffff81568d12-ffffffff81568d2d: pci_enable_bridge.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void pci_enable_bridge(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (0)
Location: drivers/pci/pci.c:1639
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_enable_device_flags
  - drivers/pci/pci.c:pci_enable_bridge
```
**Symbols:**

```
ffffffff81578590-ffffffff8157860e: pci_enable_bridge (STB_LOCAL)
ffffffff81579e02-ffffffff81579e1d: pci_enable_bridge.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void pci_enable_bridge(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (0)
Location: drivers/pci/pci.c:1639
Inline: False
Direct callers:
  - drivers/pci/pci.c:pci_enable_device_flags
  - drivers/pci/pci.c:pci_enable_bridge
```
**Symbols:**

```
ffffffff81592a50-ffffffff81592ace: pci_enable_bridge (STB_LOCAL)
ffffffff815942b2-ffffffff815942cd: pci_enable_bridge.cold (STB_LOCAL)
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
