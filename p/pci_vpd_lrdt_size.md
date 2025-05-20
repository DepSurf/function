# Function: <code>pci_vpd_lrdt_size</code>

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
In drivers/pci/vpd.c (0)
Location: include/linux/pci.h:1866
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff814794ac)
Location: include/linux/pci.h:1941
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_vpd_size
```
```
In drivers/pci/vpd.c (ffffffff81489b3f)
Location: include/linux/pci.h:1941
Inline: True
Inline callers:
  - drivers/pci/vpd.c:pci_vpd_find_tag
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff8149a93c)
Location: include/linux/pci.h:2017
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_vpd_size
```
```
In drivers/pci/vpd.c (ffffffff814ab32f)
Location: include/linux/pci.h:2017
Inline: True
Inline callers:
  - drivers/pci/vpd.c:pci_vpd_find_tag
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff814a45b5)
Location: include/linux/pci.h:2049
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_vpd_size
```
```
In drivers/pci/vpd.c (ffffffff814b5721)
Location: include/linux/pci.h:2049
Inline: True
Inline callers:
  - drivers/pci/vpd.c:pci_vpd_find_tag
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/access.c (ffffffff814e3361)
Location: include/linux/pci.h:2105
Inline: True
Inline callers:
  - drivers/pci/access.c:pci_vpd_size
```
```
In drivers/pci/vpd.c (ffffffff814f5121)
Location: include/linux/pci.h:2105
Inline: True
Inline callers:
  - drivers/pci/vpd.c:pci_vpd_find_tag
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
In drivers/pci/vpd.c (ffffffff81525320)
Location: include/linux/pci.h:2109
Inline: True
Inline callers:
  - drivers/pci/vpd.c:pci_vpd_find_tag
  - drivers/pci/vpd.c:pci_vpd_size
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
In drivers/pci/vpd.c (ffffffff8153b1b0)
Location: include/linux/pci.h:2156
Inline: True
Inline callers:
  - drivers/pci/vpd.c:pci_vpd_find_tag
  - drivers/pci/vpd.c:pci_vpd_size
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
In drivers/pci/vpd.c (ffffffff8156ac3b)
Location: include/linux/pci.h:2230
Inline: True
Inline callers:
  - drivers/pci/vpd.c:pci_vpd_find_tag
  - drivers/pci/vpd.c:pci_vpd_size
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
In drivers/pci/vpd.c (ffffffff8158bc0b)
Location: include/linux/pci.h:2204
Inline: True
Inline callers:
  - drivers/pci/vpd.c:pci_vpd_find_tag
  - drivers/pci/vpd.c:pci_vpd_size
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
In drivers/pci/vpd.c (ffffffff81632bed)
Location: include/linux/pci.h:2228
Inline: True
Inline callers:
  - drivers/pci/vpd.c:pci_vpd_find_tag
  - drivers/pci/vpd.c:pci_vpd_size
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
In drivers/pci/vpd.c (ffffffff81657d3d)
Location: include/linux/pci.h:2232
Inline: True
Inline callers:
  - drivers/pci/vpd.c:pci_vpd_find_tag
  - drivers/pci/vpd.c:pci_vpd_size
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
In drivers/pci/vpd.c (ffffffff8163a597)
Location: include/linux/pci.h:2271
Inline: True
Inline callers:
  - drivers/pci/vpd.c:pci_vpd_find_tag
  - drivers/pci/vpd.c:pci_vpd_size
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
In drivers/pci/vpd.c (ffffffff816aad60)
Location: drivers/pci/vpd.c:21
Inline: True
Inline callers:
  - drivers/pci/vpd.c:pci_vpd_find_ro_info_keyword
  - drivers/pci/vpd.c:pci_vpd_find_id_string
  - drivers/pci/vpd.c:pci_vpd_size
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
In drivers/pci/vpd.c (ffffffff817cdd12)
Location: drivers/pci/vpd.c:21
Inline: True
Inline callers:
  - drivers/pci/vpd.c:pci_vpd_find_ro_info_keyword
  - drivers/pci/vpd.c:pci_vpd_find_id_string
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
In drivers/pci/vpd.c (ffffffff818ed672)
Location: drivers/pci/vpd.c:21
Inline: True
Inline callers:
  - drivers/pci/vpd.c:pci_vpd_find_ro_info_keyword
  - drivers/pci/vpd.c:pci_vpd_find_id_string
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
In drivers/pci/vpd.c (ffffffff81930b72)
Location: drivers/pci/vpd.c:21
Inline: True
Inline callers:
  - drivers/pci/vpd.c:pci_vpd_find_ro_info_keyword
  - drivers/pci/vpd.c:pci_vpd_find_id_string
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
In drivers/pci/vpd.c (ffffffff819795a2)
Location: drivers/pci/vpd.c:21
Inline: True
Inline callers:
  - drivers/pci/vpd.c:pci_vpd_find_ro_info_keyword
  - drivers/pci/vpd.c:pci_vpd_find_id_string
  - drivers/pci/vpd.c:pci_vpd_available
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
In drivers/pci/vpd.c (ffff8000106f0b8c)
Location: include/linux/pci.h:2204
Inline: True
Inline callers:
  - drivers/pci/vpd.c:pci_vpd_find_tag
  - drivers/pci/vpd.c:pci_vpd_size
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
In drivers/pci/vpd.c (c088b5c0)
Location: include/linux/pci.h:2204
Inline: True
Inline callers:
  - drivers/pci/vpd.c:pci_vpd_find_tag
  - drivers/pci/vpd.c:pci_vpd_size
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
In drivers/pci/vpd.c (c00000000086e1e8)
Location: include/linux/pci.h:2204
Inline: True
Inline callers:
  - drivers/pci/vpd.c:pci_vpd_find_tag
  - drivers/pci/vpd.c:pci_vpd_size
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
In drivers/pci/vpd.c (ffffffe0004c45d4)
Location: include/linux/pci.h:2204
Inline: True
Inline callers:
  - drivers/pci/vpd.c:pci_vpd_find_tag
  - drivers/pci/vpd.c:pci_vpd_size
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
In drivers/pci/vpd.c (ffffffff8157fa8b)
Location: include/linux/pci.h:2204
Inline: True
Inline callers:
  - drivers/pci/vpd.c:pci_vpd_find_tag
  - drivers/pci/vpd.c:pci_vpd_size
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
In drivers/pci/vpd.c (ffffffff8156e86b)
Location: include/linux/pci.h:2204
Inline: True
Inline callers:
  - drivers/pci/vpd.c:pci_vpd_find_tag
  - drivers/pci/vpd.c:pci_vpd_size
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
In drivers/pci/vpd.c (ffffffff8157f95b)
Location: include/linux/pci.h:2204
Inline: True
Inline callers:
  - drivers/pci/vpd.c:pci_vpd_find_tag
  - drivers/pci/vpd.c:pci_vpd_size
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
In drivers/pci/vpd.c (ffffffff81599e0b)
Location: include/linux/pci.h:2204
Inline: True
Inline callers:
  - drivers/pci/vpd.c:pci_vpd_find_tag
  - drivers/pci/vpd.c:pci_vpd_size
```
</details>
</li>
</ul>

## Differences
