# Function: <code>vfio_user_config_write</code>

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
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int vfio_user_config_write(struct pci_dev *pdev, int offset, __le32 val, int count);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_config.c (ffffffff817da340)
Location: drivers/vfio/pci/vfio_pci_config.c:153
Inline: True
Direct callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_raw_config_write
  - drivers/vfio/pci/vfio_pci_config.c:vfio_default_config_write
```
**Symbols:**

```
ffffffff817da340-ffffffff817da37a: vfio_user_config_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int vfio_user_config_write(struct pci_dev *pdev, int offset, __le32 val, int count);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_config.c (ffffffff818a901d)
Location: drivers/vfio/pci/vfio_pci_config.c:153
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_raw_config_write
Direct callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_default_config_write
```
**Symbols:**

```
ffffffff818a8220-ffffffff818a825a: vfio_user_config_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int vfio_user_config_write(struct pci_dev *pdev, int offset, __le32 val, int count);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_config.c (ffffffff818b7f4d)
Location: drivers/vfio/pci/vfio_pci_config.c:153
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_raw_config_write
Direct callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_default_config_write
```
**Symbols:**

```
ffffffff818b7050-ffffffff818b708a: vfio_user_config_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int vfio_user_config_write(struct pci_dev *pdev, int offset, __le32 val, int count);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_config.c (ffffffff8189b3ae)
Location: drivers/vfio/pci/vfio_pci_config.c:153
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_raw_config_write
Direct callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_default_config_write
```
**Symbols:**

```
ffffffff8189a520-ffffffff8189a55a: vfio_user_config_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int vfio_user_config_write(struct pci_dev *pdev, int offset, __le32 val, int count);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_config.c (ffffffff8192f4ae)
Location: drivers/vfio/pci/vfio_pci_config.c:153
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_raw_config_write
Direct callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_default_config_write
```
**Symbols:**

```
ffffffff8192e270-ffffffff8192e2aa: vfio_user_config_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int vfio_user_config_write(struct pci_dev *pdev, int offset, __le32 val, int count);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_config.c (ffffffff81a85e31)
Location: drivers/vfio/pci/vfio_pci_config.c:153
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_raw_config_write
Direct callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_default_config_write
```
**Symbols:**

```
ffffffff81a84a50-ffffffff81a84aba: vfio_user_config_write (STB_LOCAL)
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
int vfio_user_config_write(struct pci_dev *pdev, int offset, __le32 val, int count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_config.c (c000000000aba820)
Location: drivers/vfio/pci/vfio_pci_config.c:153
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_raw_config_write
  - drivers/vfio/pci/vfio_pci_config.c:vfio_default_config_write
```
**Symbols:**

```
c000000000aba820-c000000000aba8e8: vfio_user_config_write (STB_LOCAL)
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
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int vfio_user_config_write(struct pci_dev *pdev, int offset, __le32 val, int count);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_config.c (ffffffff817843f0)
Location: drivers/vfio/pci/vfio_pci_config.c:153
Inline: True
Direct callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_raw_config_write
  - drivers/vfio/pci/vfio_pci_config.c:vfio_default_config_write
```
**Symbols:**

```
ffffffff817843f0-ffffffff8178442a: vfio_user_config_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int vfio_user_config_write(struct pci_dev *pdev, int offset, __le32 val, int count);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_config.c (ffffffff817cf1c0)
Location: drivers/vfio/pci/vfio_pci_config.c:153
Inline: True
Direct callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_raw_config_write
  - drivers/vfio/pci/vfio_pci_config.c:vfio_default_config_write
```
**Symbols:**

```
ffffffff817cf1c0-ffffffff817cf1fa: vfio_user_config_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int vfio_user_config_write(struct pci_dev *pdev, int offset, __le32 val, int count);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_config.c (ffffffff817e9460)
Location: drivers/vfio/pci/vfio_pci_config.c:153
Inline: True
Direct callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_raw_config_write
  - drivers/vfio/pci/vfio_pci_config.c:vfio_default_config_write
```
**Symbols:**

```
ffffffff817e9460-ffffffff817e949a: vfio_user_config_write (STB_LOCAL)
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
