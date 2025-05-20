# Function: <code>pci_vpd_size</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
size_t pci_vpd_size(struct pci_dev *dev, size_t old_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff814793a0)
Location: drivers/pci/access.c:298
Inline: False
Direct callers:
  - drivers/pci/access.c:pci_vpd_write
  - drivers/pci/access.c:pci_vpd_read
```
**Symbols:**

```
ffffffff814793a0-ffffffff8147953c: pci_vpd_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
size_t pci_vpd_size(struct pci_dev *dev, size_t old_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff8149a830)
Location: drivers/pci/access.c:310
Inline: False
Direct callers:
  - drivers/pci/access.c:pci_vpd_write
  - drivers/pci/access.c:pci_vpd_read
```
**Symbols:**

```
ffffffff8149a830-ffffffff8149a9cc: pci_vpd_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
size_t pci_vpd_size(struct pci_dev *dev, size_t old_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff814a44a0)
Location: drivers/pci/access.c:318
Inline: False
Direct callers:
  - drivers/pci/access.c:pci_vpd_write
  - drivers/pci/access.c:pci_vpd_read
```
**Symbols:**

```
ffffffff814a44a0-ffffffff814a464d: pci_vpd_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
size_t pci_vpd_size(struct pci_dev *dev, size_t old_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff814e3240)
Location: drivers/pci/access.c:318
Inline: False
Direct callers:
  - drivers/pci/access.c:pci_vpd_write
  - drivers/pci/access.c:pci_vpd_read
```
**Symbols:**

```
ffffffff814e3240-ffffffff814e33f9: pci_vpd_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
size_t pci_vpd_size(struct pci_dev *dev, size_t old_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/vpd.c (ffffffff815253f0)
Location: drivers/pci/vpd.c:83
Inline: False
Direct callers:
  - drivers/pci/vpd.c:pci_vpd_write
  - drivers/pci/vpd.c:pci_vpd_read
```
**Symbols:**

```
ffffffff815253f0-ffffffff815255c4: pci_vpd_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
size_t pci_vpd_size(struct pci_dev *dev, size_t old_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/vpd.c (ffffffff8153b280)
Location: drivers/pci/vpd.c:83
Inline: False
Direct callers:
  - drivers/pci/vpd.c:pci_vpd_write
  - drivers/pci/vpd.c:pci_vpd_read
```
**Symbols:**

```
ffffffff8153b280-ffffffff8153b454: pci_vpd_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
size_t pci_vpd_size(struct pci_dev *dev, size_t old_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/vpd.c (0)
Location: drivers/pci/vpd.c:83
Inline: False
Direct callers:
  - drivers/pci/vpd.c:pci_vpd_write
  - drivers/pci/vpd.c:pci_vpd_read
```
**Symbols:**

```
ffffffff8156ad10-ffffffff8156ae48: pci_vpd_size (STB_LOCAL)
ffffffff8156b6d2-ffffffff8156b733: pci_vpd_size.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
size_t pci_vpd_size(struct pci_dev *dev, size_t old_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/vpd.c (0)
Location: drivers/pci/vpd.c:83
Inline: False
Direct callers:
  - drivers/pci/vpd.c:pci_vpd_write
  - drivers/pci/vpd.c:pci_vpd_read
```
**Symbols:**

```
ffffffff8158bce0-ffffffff8158be18: pci_vpd_size (STB_LOCAL)
ffffffff8158c6a2-ffffffff8158c706: pci_vpd_size.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
size_t pci_vpd_size(struct pci_dev *dev, size_t old_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/vpd.c (0)
Location: drivers/pci/vpd.c:83
Inline: False
Direct callers:
  - drivers/pci/vpd.c:pci_vpd_write
  - drivers/pci/vpd.c:pci_vpd_read
```
**Symbols:**

```
ffffffff816330a0-ffffffff816331d8: pci_vpd_size (STB_LOCAL)
ffffffff81633791-ffffffff816337f5: pci_vpd_size.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
size_t pci_vpd_size(struct pci_dev *dev, size_t old_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/vpd.c (0)
Location: drivers/pci/vpd.c:83
Inline: False
Direct callers:
  - drivers/pci/vpd.c:pci_vpd_write
  - drivers/pci/vpd.c:pci_vpd_read
```
**Symbols:**

```
ffffffff816581f0-ffffffff81658328: pci_vpd_size (STB_LOCAL)
ffffffff81bf85fb-ffffffff81bf865f: pci_vpd_size.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
size_t pci_vpd_size(struct pci_dev *dev, size_t old_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/vpd.c (0)
Location: drivers/pci/vpd.c:73
Inline: False
Direct callers:
  - drivers/pci/vpd.c:pci_vpd_write
  - drivers/pci/vpd.c:pci_vpd_read
```
**Symbols:**

```
ffffffff8163a9b0-ffffffff8163aaf3: pci_vpd_size (STB_LOCAL)
ffffffff81bea43d-ffffffff81bea4bc: pci_vpd_size.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
size_t pci_vpd_size(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/vpd.c (0)
Location: drivers/pci/vpd.c:55
Inline: False
Direct callers:
  - drivers/pci/vpd.c:pci_vpd_write
  - drivers/pci/vpd.c:pci_vpd_read
```
**Symbols:**

```
ffffffff816ab0a0-ffffffff816ab1f1: pci_vpd_size (STB_LOCAL)
ffffffff81ce52a0-ffffffff81ce533e: pci_vpd_size.cold (STB_LOCAL)
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
In drivers/pci/vpd.c (ffffffff817ce1a5)
Location: drivers/pci/vpd.c:55
Inline: True
Inline callers:
  - drivers/pci/vpd.c:pci_vpd_available
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
In drivers/pci/vpd.c (ffffffff818edbb5)
Location: drivers/pci/vpd.c:55
Inline: True
Inline callers:
  - drivers/pci/vpd.c:pci_vpd_available
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
In drivers/pci/vpd.c (ffffffff819310b5)
Location: drivers/pci/vpd.c:55
Inline: True
Inline callers:
  - drivers/pci/vpd.c:pci_vpd_available
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
In drivers/pci/vpd.c (ffffffff81979bd5)
Location: drivers/pci/vpd.c:55
Inline: True
Inline callers:
  - drivers/pci/vpd.c:pci_vpd_available
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
size_t pci_vpd_size(struct pci_dev *dev, size_t old_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/vpd.c (ffff8000106f0cd0)
Location: drivers/pci/vpd.c:83
Inline: False
Direct callers:
  - drivers/pci/vpd.c:pci_vpd_write
  - drivers/pci/vpd.c:pci_vpd_read
```
**Symbols:**

```
ffff8000106f0cd0-ffff8000106f0e98: pci_vpd_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
size_t pci_vpd_size(struct pci_dev *dev, size_t old_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/vpd.c (c088b6ec)
Location: drivers/pci/vpd.c:83
Inline: False
Direct callers:
  - drivers/pci/vpd.c:pci_vpd_write
  - drivers/pci/vpd.c:pci_vpd_read
```
**Symbols:**

```
c088b6ec-c088b8c0: pci_vpd_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
size_t pci_vpd_size(struct pci_dev *dev, size_t old_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/vpd.c (c00000000086e310)
Location: drivers/pci/vpd.c:83
Inline: False
Direct callers:
  - drivers/pci/vpd.c:pci_vpd_write
  - drivers/pci/vpd.c:pci_vpd_read
```
**Symbols:**

```
c00000000086e310-c00000000086e570: pci_vpd_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
size_t pci_vpd_size(struct pci_dev *dev, size_t old_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/vpd.c (ffffffe0004c46ec)
Location: drivers/pci/vpd.c:83
Inline: False
Direct callers:
  - drivers/pci/vpd.c:pci_vpd_write
  - drivers/pci/vpd.c:pci_vpd_read
```
**Symbols:**

```
ffffffe0004c46ec-ffffffe0004c4842: pci_vpd_size (STB_LOCAL)
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
size_t pci_vpd_size(struct pci_dev *dev, size_t old_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/vpd.c (0)
Location: drivers/pci/vpd.c:83
Inline: False
Direct callers:
  - drivers/pci/vpd.c:pci_vpd_write
  - drivers/pci/vpd.c:pci_vpd_read
```
**Symbols:**

```
ffffffff8157fb60-ffffffff8157fc98: pci_vpd_size (STB_LOCAL)
ffffffff81580522-ffffffff81580586: pci_vpd_size.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
size_t pci_vpd_size(struct pci_dev *dev, size_t old_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/vpd.c (0)
Location: drivers/pci/vpd.c:83
Inline: False
Direct callers:
  - drivers/pci/vpd.c:pci_vpd_write
  - drivers/pci/vpd.c:pci_vpd_read
```
**Symbols:**

```
ffffffff8156e940-ffffffff8156ea78: pci_vpd_size (STB_LOCAL)
ffffffff8156f302-ffffffff8156f366: pci_vpd_size.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
size_t pci_vpd_size(struct pci_dev *dev, size_t old_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/vpd.c (0)
Location: drivers/pci/vpd.c:83
Inline: False
Direct callers:
  - drivers/pci/vpd.c:pci_vpd_write
  - drivers/pci/vpd.c:pci_vpd_read
```
**Symbols:**

```
ffffffff8157fa30-ffffffff8157fb68: pci_vpd_size (STB_LOCAL)
ffffffff815803f2-ffffffff81580456: pci_vpd_size.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
size_t pci_vpd_size(struct pci_dev *dev, size_t old_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/vpd.c (0)
Location: drivers/pci/vpd.c:83
Inline: False
Direct callers:
  - drivers/pci/vpd.c:pci_vpd_write
  - drivers/pci/vpd.c:pci_vpd_read
```
**Symbols:**

```
ffffffff81599ee0-ffffffff8159a018: pci_vpd_size (STB_LOCAL)
ffffffff8159a8a2-ffffffff8159a906: pci_vpd_size.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>size_t old_size</code>
</li>
</ul>
</details>
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
