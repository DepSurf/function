# Function: <code>pci_configure_mps</code>

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
In drivers/pci/probe.c (ffffffff8142fbc6)
Location: drivers/pci/probe.c:1333
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_configure_device
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
In drivers/pci/probe.c (ffffffff8147b326)
Location: drivers/pci/probe.c:1354
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_configure_device
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
In drivers/pci/probe.c (ffffffff8149c7a6)
Location: drivers/pci/probe.c:1475
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_configure_device
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff814a6666)
Location: drivers/pci/probe.c:1552
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_configure_device
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff814e6b76)
Location: drivers/pci/probe.c:1594
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_configure_device
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff815160db)
Location: drivers/pci/probe.c:1725
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_configure_device
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8152b8bb)
Location: drivers/pci/probe.c:1774
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_configure_device
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8155a61b)
Location: drivers/pci/probe.c:1873
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_configure_device
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8157b6ab)
Location: drivers/pci/probe.c:1887
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_configure_device
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void pci_configure_mps(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/probe.c (0)
Location: drivers/pci/probe.c:1935
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_configure_device
```
**Symbols:**

```
ffffffff8161fbb0-ffffffff8161fd1f: pci_configure_mps (STB_LOCAL)
ffffffff8162305d-ffffffff816230e3: pci_configure_mps.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void pci_configure_mps(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/probe.c (0)
Location: drivers/pci/probe.c:1938
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_configure_device
```
**Symbols:**

```
ffffffff81646190-ffffffff816462fb: pci_configure_mps (STB_LOCAL)
ffffffff81bf7243-ffffffff81bf72c9: pci_configure_mps.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void pci_configure_mps(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/probe.c (0)
Location: drivers/pci/probe.c:1981
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_configure_device
```
**Symbols:**

```
ffffffff81628da0-ffffffff81628f0b: pci_configure_mps (STB_LOCAL)
ffffffff81be8e45-ffffffff81be8ecb: pci_configure_mps.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void pci_configure_mps(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/probe.c (0)
Location: drivers/pci/probe.c:2016
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_configure_device
```
**Symbols:**

```
ffffffff81698750-ffffffff816988bb: pci_configure_mps (STB_LOCAL)
ffffffff81ce325b-ffffffff81ce32e1: pci_configure_mps.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void pci_configure_mps(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/probe.c (0)
Location: drivers/pci/probe.c:1989
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_configure_device
```
**Symbols:**

```
ffffffff817b9cb0-ffffffff817b9e3c: pci_configure_mps (STB_LOCAL)
ffffffff81ea9d71-ffffffff81ea9df7: pci_configure_mps.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void pci_configure_mps(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff818d4ac0)
Location: drivers/pci/probe.c:1995
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_configure_device
```
**Symbols:**

```
ffffffff818d4ac0-ffffffff818d4cb4: pci_configure_mps (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void pci_configure_mps(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff81917d10)
Location: drivers/pci/probe.c:2005
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_configure_device
```
**Symbols:**

```
ffffffff81917d10-ffffffff81917f04: pci_configure_mps (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void pci_configure_mps(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff81960320)
Location: drivers/pci/probe.c:2054
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_configure_device
```
**Symbols:**

```
ffffffff81960320-ffffffff81960514: pci_configure_mps (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffff8000106deb1c)
Location: drivers/pci/probe.c:1887
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_configure_device
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (c087a7f8)
Location: drivers/pci/probe.c:1887
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_configure_device
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (c0000000008577c4)
Location: drivers/pci/probe.c:1887
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_device_add
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffe0004b6cb0)
Location: drivers/pci/probe.c:1887
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_configure_device
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8156fbcb)
Location: drivers/pci/probe.c:1887
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_configure_device
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8155e32b)
Location: drivers/pci/probe.c:1887
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_configure_device
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8156f3fb)
Location: drivers/pci/probe.c:1887
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_configure_device
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff815898db)
Location: drivers/pci/probe.c:1887
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_configure_device
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
