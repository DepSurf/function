# Function: <code>pci_vc_enable</code>

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
In drivers/pci/vc.c (ffffffff81440e7c)
Location: drivers/pci/vc.c:104
Inline: True
Inline callers:
  - drivers/pci/vc.c:pci_vc_do_save_buffer
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
In drivers/pci/vc.c (ffffffff8148cd89)
Location: drivers/pci/vc.c:104
Inline: True
Inline callers:
  - drivers/pci/vc.c:pci_vc_do_save_buffer
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
In drivers/pci/vc.c (ffffffff814ae579)
Location: drivers/pci/vc.c:104
Inline: True
Inline callers:
  - drivers/pci/vc.c:pci_vc_do_save_buffer
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
In drivers/pci/vc.c (ffffffff814b88f2)
Location: drivers/pci/vc.c:104
Inline: True
Inline callers:
  - drivers/pci/vc.c:pci_vc_do_save_buffer
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
In drivers/pci/vc.c (ffffffff814f8d42)
Location: drivers/pci/vc.c:104
Inline: True
Inline callers:
  - drivers/pci/vc.c:pci_vc_do_save_buffer
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
In drivers/pci/vc.c (ffffffff815298aa)
Location: drivers/pci/vc.c:101
Inline: True
Inline callers:
  - drivers/pci/vc.c:pci_vc_do_save_buffer
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
In drivers/pci/vc.c (ffffffff8153f75a)
Location: drivers/pci/vc.c:101
Inline: True
Inline callers:
  - drivers/pci/vc.c:pci_vc_do_save_buffer
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
In drivers/pci/vc.c (ffffffff8156f087)
Location: drivers/pci/vc.c:101
Inline: True
Inline callers:
  - drivers/pci/vc.c:pci_vc_do_save_buffer
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
In drivers/pci/vc.c (ffffffff815900a7)
Location: drivers/pci/vc.c:103
Inline: True
Inline callers:
  - drivers/pci/vc.c:pci_vc_do_save_buffer
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void pci_vc_enable(struct pci_dev *dev, int pos, int res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/vc.c (0)
Location: drivers/pci/vc.c:103
Inline: False
Direct callers:
  - drivers/pci/vc.c:pci_vc_do_save_buffer
```
**Symbols:**

```
ffffffff81637900-ffffffff81637b07: pci_vc_enable (STB_LOCAL)
ffffffff816380f5-ffffffff81638147: pci_vc_enable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void pci_vc_enable(struct pci_dev *dev, int pos, int res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/vc.c (0)
Location: drivers/pci/vc.c:103
Inline: False
Direct callers:
  - drivers/pci/vc.c:pci_vc_do_save_buffer
```
**Symbols:**

```
ffffffff8165c2c0-ffffffff8165c4cb: pci_vc_enable (STB_LOCAL)
ffffffff81bf8d60-ffffffff81bf8db2: pci_vc_enable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void pci_vc_enable(struct pci_dev *dev, int pos, int res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/vc.c (0)
Location: drivers/pci/vc.c:103
Inline: False
Direct callers:
  - drivers/pci/vc.c:pci_vc_do_save_buffer
```
**Symbols:**

```
ffffffff8163e870-ffffffff8163ea71: pci_vc_enable (STB_LOCAL)
ffffffff81beabb7-ffffffff81beac09: pci_vc_enable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void pci_vc_enable(struct pci_dev *dev, int pos, int res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/vc.c (0)
Location: drivers/pci/vc.c:103
Inline: False
Direct callers:
  - drivers/pci/vc.c:pci_vc_do_save_buffer
```
**Symbols:**

```
ffffffff816af400-ffffffff816af601: pci_vc_enable (STB_LOCAL)
ffffffff81ce5a4d-ffffffff81ce5a9f: pci_vc_enable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void pci_vc_enable(struct pci_dev *dev, int pos, int res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/vc.c (0)
Location: drivers/pci/vc.c:103
Inline: False
Direct callers:
  - drivers/pci/vc.c:pci_vc_do_save_buffer
```
**Symbols:**

```
ffffffff817d28b0-ffffffff817d2ad2: pci_vc_enable (STB_LOCAL)
ffffffff81eac512-ffffffff81eac563: pci_vc_enable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void pci_vc_enable(struct pci_dev *dev, int pos, int res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/vc.c (ffffffff818f3160)
Location: drivers/pci/vc.c:103
Inline: False
Direct callers:
  - drivers/pci/vc.c:pci_vc_do_save_buffer
```
**Symbols:**

```
ffffffff818f3160-ffffffff818f33c1: pci_vc_enable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void pci_vc_enable(struct pci_dev *dev, int pos, int res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/vc.c (ffffffff81936580)
Location: drivers/pci/vc.c:103
Inline: False
Direct callers:
  - drivers/pci/vc.c:pci_vc_do_save_buffer
```
**Symbols:**

```
ffffffff81936580-ffffffff819367f9: pci_vc_enable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void pci_vc_enable(struct pci_dev *dev, int pos, int res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/vc.c (ffffffff8197f3e0)
Location: drivers/pci/vc.c:104
Inline: False
Direct callers:
  - drivers/pci/vc.c:pci_vc_do_save_buffer
```
**Symbols:**

```
ffffffff8197f3e0-ffffffff8197f659: pci_vc_enable (STB_LOCAL)
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
In drivers/pci/vc.c (ffff8000106f522c)
Location: drivers/pci/vc.c:103
Inline: True
Inline callers:
  - drivers/pci/vc.c:pci_vc_do_save_buffer
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
In drivers/pci/vc.c (c088fca8)
Location: drivers/pci/vc.c:103
Inline: True
Inline callers:
  - drivers/pci/vc.c:pci_vc_do_save_buffer
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
In drivers/pci/vc.c (c000000000873d20)
Location: drivers/pci/vc.c:103
Inline: True
Inline callers:
  - drivers/pci/vc.c:pci_vc_do_save_buffer
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
In drivers/pci/vc.c (ffffffe0004c8048)
Location: drivers/pci/vc.c:103
Inline: True
Inline callers:
  - drivers/pci/vc.c:pci_vc_do_save_buffer
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
In drivers/pci/vc.c (ffffffff81583f27)
Location: drivers/pci/vc.c:103
Inline: True
Inline callers:
  - drivers/pci/vc.c:pci_vc_do_save_buffer
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
In drivers/pci/vc.c (ffffffff81572d07)
Location: drivers/pci/vc.c:103
Inline: True
Inline callers:
  - drivers/pci/vc.c:pci_vc_do_save_buffer
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
In drivers/pci/vc.c (ffffffff81583df7)
Location: drivers/pci/vc.c:103
Inline: True
Inline callers:
  - drivers/pci/vc.c:pci_vc_do_save_buffer
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
In drivers/pci/vc.c (ffffffff8159e2a7)
Location: drivers/pci/vc.c:103
Inline: True
Inline callers:
  - drivers/pci/vc.c:pci_vc_do_save_buffer
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
