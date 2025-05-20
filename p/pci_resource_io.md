# Function: <code>pci_resource_io</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
ssize_t pci_resource_io(struct file *filp, struct kobject *kobj, struct bin_attribute *attr, char *buf, loff_t off, size_t count, bool write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-sysfs.c (ffffffff8143af10)
Location: drivers/pci/pci-sysfs.c:1060
Inline: False
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_read_resource_io
  - drivers/pci/pci-sysfs.c:pci_write_resource_io
```
**Symbols:**

```
ffffffff8143af10-ffffffff8143afe5: pci_resource_io (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pci-sysfs.c (ffffffff814883c0)
Location: drivers/pci/pci-sysfs.c:1059
Inline: True
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_write_resource_io
  - drivers/pci/pci-sysfs.c:pci_read_resource_io
```
**Symbols:**

```
ffffffff814883c0-ffffffff8148848f: pci_resource_io.constprop.10 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pci-sysfs.c (ffffffff814a9ba0)
Location: drivers/pci/pci-sysfs.c:1061
Inline: True
Direct callers:
  - drivers/pci/pci-sysfs.c:pci_write_resource_io
  - drivers/pci/pci-sysfs.c:pci_read_resource_io
```
**Symbols:**

```
ffffffff814a9ba0-ffffffff814a9c6f: pci_resource_io.constprop.10 (STB_LOCAL)
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
In drivers/pci/pci-sysfs.c (ffffffff814b3f92)
Location: drivers/pci/pci-sysfs.c:1214
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pci_write_resource_io
  - drivers/pci/pci-sysfs.c:pci_read_resource_io
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
In drivers/pci/pci-sysfs.c (ffffffff814f379e)
Location: drivers/pci/pci-sysfs.c:1252
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pci_write_resource_io
  - drivers/pci/pci-sysfs.c:pci_read_resource_io
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
In drivers/pci/pci-sysfs.c (ffffffff815239ba)
Location: drivers/pci/pci-sysfs.c:1202
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pci_write_resource_io
  - drivers/pci/pci-sysfs.c:pci_read_resource_io
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
In drivers/pci/pci-sysfs.c (ffffffff8153981a)
Location: drivers/pci/pci-sysfs.c:1201
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pci_write_resource_io
  - drivers/pci/pci-sysfs.c:pci_read_resource_io
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
In drivers/pci/pci-sysfs.c (ffffffff8156913a)
Location: drivers/pci/pci-sysfs.c:1202
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pci_write_resource_io
  - drivers/pci/pci-sysfs.c:pci_read_resource_io
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
In drivers/pci/pci-sysfs.c (ffffffff8158a375)
Location: drivers/pci/pci-sysfs.c:1055
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pci_read_resource_io
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
In drivers/pci/pci-sysfs.c (ffffffff816314f5)
Location: drivers/pci/pci-sysfs.c:1040
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pci_read_resource_io
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
In drivers/pci/pci-sysfs.c (ffffffff81656b95)
Location: drivers/pci/pci-sysfs.c:1051
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pci_read_resource_io
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
In drivers/pci/pci-sysfs.c (ffffffff81639605)
Location: drivers/pci/pci-sysfs.c:1079
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pci_read_resource_io
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
In drivers/pci/pci-sysfs.c (ffffffff816a9b77)
Location: drivers/pci/pci-sysfs.c:1079
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pci_read_resource_io
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
In drivers/pci/pci-sysfs.c (ffffffff817cc9b7)
Location: drivers/pci/pci-sysfs.c:1074
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pci_read_resource_io
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
In drivers/pci/pci-sysfs.c (ffffffff818ebd77)
Location: drivers/pci/pci-sysfs.c:1082
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pci_read_resource_io
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
In drivers/pci/pci-sysfs.c (ffffffff8192f287)
Location: drivers/pci/pci-sysfs.c:1082
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pci_read_resource_io
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
In drivers/pci/pci-sysfs.c (ffffffff81977bf7)
Location: drivers/pci/pci-sysfs.c:1095
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pci_read_resource_io
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
In drivers/pci/pci-sysfs.c (ffff8000106eedb0)
Location: drivers/pci/pci-sysfs.c:1055
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pci_read_resource_io
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
In drivers/pci/pci-sysfs.c (c0889e18)
Location: drivers/pci/pci-sysfs.c:1055
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pci_read_resource_io
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
In drivers/pci/pci-sysfs.c (c00000000086b6c0)
Location: drivers/pci/pci-sysfs.c:1055
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pci_read_resource_io
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
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
In drivers/pci/pci-sysfs.c (ffffffff8157e205)
Location: drivers/pci/pci-sysfs.c:1055
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pci_read_resource_io
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
In drivers/pci/pci-sysfs.c (ffffffff8156cfd5)
Location: drivers/pci/pci-sysfs.c:1055
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pci_read_resource_io
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
In drivers/pci/pci-sysfs.c (ffffffff8157e0c5)
Location: drivers/pci/pci-sysfs.c:1055
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pci_read_resource_io
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
In drivers/pci/pci-sysfs.c (ffffffff81598575)
Location: drivers/pci/pci-sysfs.c:1055
Inline: True
Inline callers:
  - drivers/pci/pci-sysfs.c:pci_read_resource_io
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
