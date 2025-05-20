# Function: <code>pci_configure_ltr</code>

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
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff814e6bc9)
Location: drivers/pci/probe.c:1878
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
In drivers/pci/probe.c (ffffffff81516136)
Location: drivers/pci/probe.c:2021
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
In drivers/pci/probe.c (ffffffff8152b916)
Location: drivers/pci/probe.c:2070
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
In drivers/pci/probe.c (ffffffff8155a672)
Location: drivers/pci/probe.c:2280
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
In drivers/pci/probe.c (ffffffff8157b702)
Location: drivers/pci/probe.c:2025
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_configure_device
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void pci_configure_ltr(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8161f9f0)
Location: drivers/pci/probe.c:2093
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_configure_device
```
**Symbols:**

```
ffffffff8161f9f0-ffffffff8161fb40: pci_configure_ltr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void pci_configure_ltr(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff81646300)
Location: drivers/pci/probe.c:2096
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_configure_device
```
**Symbols:**

```
ffffffff81646300-ffffffff81646464: pci_configure_ltr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void pci_configure_ltr(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff81628f10)
Location: drivers/pci/probe.c:2139
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_configure_device
```
**Symbols:**

```
ffffffff81628f10-ffffffff81629074: pci_configure_ltr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void pci_configure_ltr(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff816988c0)
Location: drivers/pci/probe.c:2174
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_configure_device
```
**Symbols:**

```
ffffffff816988c0-ffffffff81698a2a: pci_configure_ltr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void pci_configure_ltr(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff817b9e40)
Location: drivers/pci/probe.c:2147
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_configure_device
```
**Symbols:**

```
ffffffff817b9e40-ffffffff817b9fc6: pci_configure_ltr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void pci_configure_ltr(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff818d4cd0)
Location: drivers/pci/probe.c:2153
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_configure_device
```
**Symbols:**

```
ffffffff818d4cd0-ffffffff818d4e56: pci_configure_ltr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void pci_configure_ltr(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff81918400)
Location: drivers/pci/probe.c:2163
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_configure_device
```
**Symbols:**

```
ffffffff81918400-ffffffff81918586: pci_configure_ltr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void pci_configure_ltr(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff81960900)
Location: drivers/pci/probe.c:2212
Inline: False
Direct callers:
  - drivers/pci/probe.c:pci_configure_device
```
**Symbols:**

```
ffffffff81960900-ffffffff81960a86: pci_configure_ltr (STB_LOCAL)
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
In drivers/pci/probe.c (ffff8000106deb6c)
Location: drivers/pci/probe.c:2025
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
In drivers/pci/probe.c (c087a864)
Location: drivers/pci/probe.c:2025
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
In drivers/pci/probe.c (0)
Location: drivers/pci/probe.c:2025
Inline: True
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
In drivers/pci/probe.c (ffffffe0004b6cfa)
Location: drivers/pci/probe.c:2025
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
In drivers/pci/probe.c (ffffffff8156fc22)
Location: drivers/pci/probe.c:2025
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
In drivers/pci/probe.c (ffffffff8155e382)
Location: drivers/pci/probe.c:2025
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
In drivers/pci/probe.c (ffffffff8156f452)
Location: drivers/pci/probe.c:2025
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
In drivers/pci/probe.c (ffffffff81589932)
Location: drivers/pci/probe.c:2025
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
