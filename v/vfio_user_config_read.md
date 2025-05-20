# Function: <code>vfio_user_config_read</code>

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
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int vfio_user_config_read(struct pci_dev *pdev, int offset, __le32 *val, int count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_config.c (ffffffff817d9e30)
Location: drivers/vfio/pci/vfio_pci_config.c:122
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_raw_config_read
  - drivers/vfio/pci/vfio_pci_config.c:vfio_default_config_write
  - drivers/vfio/pci/vfio_pci_config.c:vfio_default_config_read
```
**Symbols:**

```
ffffffff817d9e30-ffffffff817d9eb6: vfio_user_config_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int vfio_user_config_read(struct pci_dev *pdev, int offset, __le32 *val, int count);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_config.c (ffffffff818a98e7)
Location: drivers/vfio/pci/vfio_pci_config.c:122
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_raw_config_read
Direct callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_default_config_write
  - drivers/vfio/pci/vfio_pci_config.c:vfio_default_config_read
```
**Symbols:**

```
ffffffff818a8010-ffffffff818a8095: vfio_user_config_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int vfio_user_config_read(struct pci_dev *pdev, int offset, __le32 *val, int count);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_config.c (ffffffff818b8817)
Location: drivers/vfio/pci/vfio_pci_config.c:122
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_raw_config_read
Direct callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_default_config_write
  - drivers/vfio/pci/vfio_pci_config.c:vfio_default_config_read
```
**Symbols:**

```
ffffffff818b6e60-ffffffff818b6ee5: vfio_user_config_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int vfio_user_config_read(struct pci_dev *pdev, int offset, __le32 *val, int count);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_config.c (ffffffff8189bcb8)
Location: drivers/vfio/pci/vfio_pci_config.c:122
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_raw_config_read
Direct callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_default_config_write
  - drivers/vfio/pci/vfio_pci_config.c:vfio_default_config_read
```
**Symbols:**

```
ffffffff8189a320-ffffffff8189a3a5: vfio_user_config_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int vfio_user_config_read(struct pci_dev *pdev, int offset, __le32 *val, int count);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_config.c (ffffffff8192fde8)
Location: drivers/vfio/pci/vfio_pci_config.c:122
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_raw_config_read
Direct callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_default_config_write
  - drivers/vfio/pci/vfio_pci_config.c:vfio_default_config_read
```
**Symbols:**

```
ffffffff8192e160-ffffffff8192e1e5: vfio_user_config_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int vfio_user_config_read(struct pci_dev *pdev, int offset, __le32 *val, int count);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_config.c (ffffffff81a86c9b)
Location: drivers/vfio/pci/vfio_pci_config.c:122
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_raw_config_read
  - drivers/vfio/pci/vfio_pci_config.c:vfio_direct_config_read
Direct callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_default_config_write
  - drivers/vfio/pci/vfio_pci_config.c:vfio_default_config_read
```
**Symbols:**

```
ffffffff81a84920-ffffffff81a849bb: vfio_user_config_read (STB_LOCAL)
```
</details>
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int vfio_user_config_read(struct pci_dev *pdev, int offset, __le32 *val, int count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_config.c (c000000000aba3b0)
Location: drivers/vfio/pci/vfio_pci_config.c:122
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_raw_config_read
  - drivers/vfio/pci/vfio_pci_config.c:vfio_default_config_write
  - drivers/vfio/pci/vfio_pci_config.c:vfio_default_config_read
```
**Symbols:**

```
c000000000aba3b0-c000000000aba4c8: vfio_user_config_read (STB_LOCAL)
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int vfio_user_config_read(struct pci_dev *pdev, int offset, __le32 *val, int count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_config.c (ffffffff81783ee0)
Location: drivers/vfio/pci/vfio_pci_config.c:122
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_raw_config_read
  - drivers/vfio/pci/vfio_pci_config.c:vfio_default_config_write
  - drivers/vfio/pci/vfio_pci_config.c:vfio_default_config_read
```
**Symbols:**

```
ffffffff81783ee0-ffffffff81783f66: vfio_user_config_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int vfio_user_config_read(struct pci_dev *pdev, int offset, __le32 *val, int count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_config.c (ffffffff817cecb0)
Location: drivers/vfio/pci/vfio_pci_config.c:122
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_raw_config_read
  - drivers/vfio/pci/vfio_pci_config.c:vfio_default_config_write
  - drivers/vfio/pci/vfio_pci_config.c:vfio_default_config_read
```
**Symbols:**

```
ffffffff817cecb0-ffffffff817ced36: vfio_user_config_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int vfio_user_config_read(struct pci_dev *pdev, int offset, __le32 *val, int count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_config.c (ffffffff817e8f50)
Location: drivers/vfio/pci/vfio_pci_config.c:122
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_raw_config_read
  - drivers/vfio/pci/vfio_pci_config.c:vfio_default_config_write
  - drivers/vfio/pci/vfio_pci_config.c:vfio_default_config_read
```
**Symbols:**

```
ffffffff817e8f50-ffffffff817e8fd6: vfio_user_config_read (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
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
