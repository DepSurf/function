# Function: <code>pci_vpd_srdt_size</code>

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
Location: include/linux/pci.h:1877
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
In drivers/pci/access.c (0)
Location: include/linux/pci.h:1963
Inline: True
```
```
In drivers/pci/vpd.c (0)
Location: include/linux/pci.h:1963
Inline: True
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
In drivers/pci/access.c (0)
Location: include/linux/pci.h:2039
Inline: True
```
```
In drivers/pci/vpd.c (0)
Location: include/linux/pci.h:2039
Inline: True
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
In drivers/pci/access.c (0)
Location: include/linux/pci.h:2071
Inline: True
```
```
In drivers/pci/vpd.c (0)
Location: include/linux/pci.h:2071
Inline: True
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
In drivers/pci/access.c (0)
Location: include/linux/pci.h:2127
Inline: True
```
```
In drivers/pci/vpd.c (0)
Location: include/linux/pci.h:2127
Inline: True
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
In drivers/pci/vpd.c (ffffffff81525300)
Location: include/linux/pci.h:2131
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
In drivers/pci/vpd.c (ffffffff8153b190)
Location: include/linux/pci.h:2178
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
In drivers/pci/vpd.c (ffffffff8156ac13)
Location: include/linux/pci.h:2252
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
In drivers/pci/vpd.c (ffffffff8158bbe3)
Location: include/linux/pci.h:2226
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
In drivers/pci/vpd.c (ffffffff81632bc6)
Location: include/linux/pci.h:2250
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
In drivers/pci/vpd.c (ffffffff81657d16)
Location: include/linux/pci.h:2254
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
In drivers/pci/vpd.c (ffffffff8163aa29)
Location: include/linux/pci.h:2293
Inline: True
Inline callers:
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
In drivers/pci/vpd.c (ffffffff816ab142)
Location: drivers/pci/vpd.c:31
Inline: True
Inline callers:
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
In drivers/pci/vpd.c (ffffffff817ce1f0)
Location: drivers/pci/vpd.c:31
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
In drivers/pci/vpd.c (ffffffff818edbff)
Location: drivers/pci/vpd.c:31
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
In drivers/pci/vpd.c (ffffffff819310ff)
Location: drivers/pci/vpd.c:31
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
In drivers/pci/vpd.c (ffffffff81979c1f)
Location: drivers/pci/vpd.c:31
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
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/vpd.c (ffff8000106f0b48)
Location: include/linux/pci.h:2226
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
In drivers/pci/vpd.c (c088b5a0)
Location: include/linux/pci.h:2226
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
In drivers/pci/vpd.c (c00000000086e1b4)
Location: include/linux/pci.h:2226
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
In drivers/pci/vpd.c (ffffffe0004c458e)
Location: include/linux/pci.h:2226
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
In drivers/pci/vpd.c (ffffffff8157fa63)
Location: include/linux/pci.h:2226
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
In drivers/pci/vpd.c (ffffffff8156e843)
Location: include/linux/pci.h:2226
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
In drivers/pci/vpd.c (ffffffff8157f933)
Location: include/linux/pci.h:2226
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
In drivers/pci/vpd.c (ffffffff81599de3)
Location: include/linux/pci.h:2226
Inline: True
Inline callers:
  - drivers/pci/vpd.c:pci_vpd_find_tag
  - drivers/pci/vpd.c:pci_vpd_size
```
</details>
</li>
</ul>

## Differences
