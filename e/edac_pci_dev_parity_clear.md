# Function: <code>edac_pci_dev_parity_clear</code>

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
<summary>In <code>4.13</code>: ✅</summary>

```c
void edac_pci_dev_parity_clear(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_pci_sysfs.c (ffffffff817602e0)
Location: drivers/edac/edac_pci_sysfs.c:509
Inline: False
Direct callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_clear_parity_errors
```
**Symbols:**

```
ffffffff817602e0-ffffffff8176034d: edac_pci_dev_parity_clear (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void edac_pci_dev_parity_clear(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_pci_sysfs.c (ffffffff817d2370)
Location: drivers/edac/edac_pci_sysfs.c:509
Inline: False
Direct callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_clear_parity_errors
```
**Symbols:**

```
ffffffff817d2370-ffffffff817d23dd: edac_pci_dev_parity_clear (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void edac_pci_dev_parity_clear(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_pci_sysfs.c (ffffffff8181b020)
Location: drivers/edac/edac_pci_sysfs.c:509
Inline: False
Direct callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_clear_parity_errors
```
**Symbols:**

```
ffffffff8181b020-ffffffff8181b08d: edac_pci_dev_parity_clear (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void edac_pci_dev_parity_clear(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_pci_sysfs.c (ffffffff81846810)
Location: drivers/edac/edac_pci_sysfs.c:509
Inline: False
Direct callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_clear_parity_errors
```
**Symbols:**

```
ffffffff81846810-ffffffff8184687d: edac_pci_dev_parity_clear (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void edac_pci_dev_parity_clear(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_pci_sysfs.c (ffffffff818895b0)
Location: drivers/edac/edac_pci_sysfs.c:509
Inline: False
Direct callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_clear_parity_errors
```
**Symbols:**

```
ffffffff818895b0-ffffffff8188961f: edac_pci_dev_parity_clear (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void edac_pci_dev_parity_clear(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_pci_sysfs.c (ffffffff818bb560)
Location: drivers/edac/edac_pci_sysfs.c:509
Inline: False
Direct callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_clear_parity_errors
```
**Symbols:**

```
ffffffff818bb560-ffffffff818bb5cf: edac_pci_dev_parity_clear (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_pci_sysfs.c (ffffffff8198c19b)
Location: drivers/edac/edac_pci_sysfs.c:509
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_clear_parity_errors
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_pci_sysfs.c (ffffffff8198fccb)
Location: drivers/edac/edac_pci_sysfs.c:509
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_clear_parity_errors
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_pci_sysfs.c (ffffffff819742ab)
Location: drivers/edac/edac_pci_sysfs.c:509
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_clear_parity_errors
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_pci_sysfs.c (ffffffff81a1cfab)
Location: drivers/edac/edac_pci_sysfs.c:509
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_clear_parity_errors
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_pci_sysfs.c (ffffffff81b86189)
Location: drivers/edac/edac_pci_sysfs.c:511
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_clear_parity_errors
  - drivers/edac/edac_pci_sysfs.c:edac_pci_clear_parity_errors
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_pci_sysfs.c (ffffffff81d255c9)
Location: drivers/edac/edac_pci_sysfs.c:511
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_clear_parity_errors
  - drivers/edac/edac_pci_sysfs.c:edac_pci_clear_parity_errors
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_pci_sysfs.c (ffffffff81d8e809)
Location: drivers/edac/edac_pci_sysfs.c:515
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_clear_parity_errors
  - drivers/edac/edac_pci_sysfs.c:edac_pci_clear_parity_errors
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_pci_sysfs.c (ffffffff81e46119)
Location: drivers/edac/edac_pci_sysfs.c:515
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_clear_parity_errors
  - drivers/edac/edac_pci_sysfs.c:edac_pci_clear_parity_errors
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
void edac_pci_dev_parity_clear(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_pci_sysfs.c (ffff800010b13c18)
Location: drivers/edac/edac_pci_sysfs.c:509
Inline: False
Direct callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_clear_parity_errors
```
**Symbols:**

```
ffff800010b13c18-ffff800010b13c9c: edac_pci_dev_parity_clear (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void edac_pci_dev_parity_clear(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_pci_sysfs.c (c0bf1cbc)
Location: drivers/edac/edac_pci_sysfs.c:509
Inline: False
Direct callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_clear_parity_errors
```
**Symbols:**

```
c0bf1cbc-c0bf1d44: edac_pci_dev_parity_clear (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void edac_pci_dev_parity_clear(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_pci_sysfs.c (c000000000c08b70)
Location: drivers/edac/edac_pci_sysfs.c:509
Inline: False
Direct callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_clear_parity_errors
```
**Symbols:**

```
c000000000c08b70-c000000000c08c18: edac_pci_dev_parity_clear (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void edac_pci_dev_parity_clear(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_pci_sysfs.c (ffffffe000700692)
Location: drivers/edac/edac_pci_sysfs.c:509
Inline: False
Direct callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_clear_parity_errors
```
**Symbols:**

```
ffffffe000700692-ffffffe0007006f2: edac_pci_dev_parity_clear (STB_LOCAL)
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
void edac_pci_dev_parity_clear(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_pci_sysfs.c (ffffffff818613e0)
Location: drivers/edac/edac_pci_sysfs.c:509
Inline: False
Direct callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_clear_parity_errors
```
**Symbols:**

```
ffffffff818613e0-ffffffff8186144f: edac_pci_dev_parity_clear (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void edac_pci_dev_parity_clear(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_pci_sysfs.c (ffffffff81828990)
Location: drivers/edac/edac_pci_sysfs.c:509
Inline: False
Direct callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_clear_parity_errors
```
**Symbols:**

```
ffffffff81828990-ffffffff818289ff: edac_pci_dev_parity_clear (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void edac_pci_dev_parity_clear(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_pci_sysfs.c (ffffffff818b0a10)
Location: drivers/edac/edac_pci_sysfs.c:509
Inline: False
Direct callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_clear_parity_errors
```
**Symbols:**

```
ffffffff818b0a10-ffffffff818b0a7f: edac_pci_dev_parity_clear (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void edac_pci_dev_parity_clear(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_pci_sysfs.c (ffffffff818ccca0)
Location: drivers/edac/edac_pci_sysfs.c:509
Inline: False
Direct callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_clear_parity_errors
```
**Symbols:**

```
ffffffff818ccca0-ffffffff818ccd0f: edac_pci_dev_parity_clear (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
