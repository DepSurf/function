# Function: <code>vfio_cap_len</code>

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
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int vfio_cap_len(struct vfio_pci_device *vdev, u8 cap, u8 pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vfio/pci/vfio_pci_config.c (0)
Location: drivers/vfio/pci/vfio_pci_config.c:1229
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_config_init
```
**Symbols:**

```
ffffffff817db1c0-ffffffff817db5cf: vfio_cap_len (STB_LOCAL)
ffffffff817dc0d8-ffffffff817dc102: vfio_cap_len.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int vfio_cap_len(struct vfio_pci_device *vdev, u8 cap, u8 pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vfio/pci/vfio_pci_config.c (0)
Location: drivers/vfio/pci/vfio_pci_config.c:1261
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_cap_init
```
**Symbols:**

```
ffffffff818a93b0-ffffffff818a95b4: vfio_cap_len (STB_LOCAL)
ffffffff818aa3a6-ffffffff818aa3d0: vfio_cap_len.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int vfio_cap_len(struct vfio_pci_device *vdev, u8 cap, u8 pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vfio/pci/vfio_pci_config.c (0)
Location: drivers/vfio/pci/vfio_pci_config.c:1266
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_cap_init
```
**Symbols:**

```
ffffffff818b82e0-ffffffff818b84e4: vfio_cap_len (STB_LOCAL)
ffffffff81c1a41b-ffffffff81c1a445: vfio_cap_len.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int vfio_cap_len(struct vfio_pci_device *vdev, u8 cap, u8 pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vfio/pci/vfio_pci_config.c (0)
Location: drivers/vfio/pci/vfio_pci_config.c:1266
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_cap_init
```
**Symbols:**

```
ffffffff8189b6c0-ffffffff8189b8c5: vfio_cap_len (STB_LOCAL)
ffffffff81c0c30a-ffffffff81c0c334: vfio_cap_len.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int vfio_cap_len(struct vfio_pci_core_device *vdev, u8 cap, u8 pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vfio/pci/vfio_pci_config.c (0)
Location: drivers/vfio/pci/vfio_pci_config.c:1266
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_cap_init
```
**Symbols:**

```
ffffffff8192f7c0-ffffffff8192f9c8: vfio_cap_len (STB_LOCAL)
ffffffff81d127ac-ffffffff81d127d6: vfio_cap_len.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int vfio_cap_len(struct vfio_pci_core_device *vdev, u8 cap, u8 pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vfio/pci/vfio_pci_config.c (0)
Location: drivers/vfio/pci/vfio_pci_config.c:1302
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_cap_init
```
**Symbols:**

```
ffffffff81a86170-ffffffff81a86388: vfio_cap_len (STB_LOCAL)
ffffffff81edd4e0-ffffffff81edd509: vfio_cap_len.cold (STB_LOCAL)
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
int vfio_cap_len(struct vfio_pci_device *vdev, u8 cap, u8 pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_config.c (c000000000abc230)
Location: drivers/vfio/pci/vfio_pci_config.c:1229
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_config_init
```
**Symbols:**

```
c000000000abc230-c000000000abc758: vfio_cap_len (STB_LOCAL)
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
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int vfio_cap_len(struct vfio_pci_device *vdev, u8 cap, u8 pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vfio/pci/vfio_pci_config.c (0)
Location: drivers/vfio/pci/vfio_pci_config.c:1229
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_config_init
```
**Symbols:**

```
ffffffff81785270-ffffffff8178567f: vfio_cap_len (STB_LOCAL)
ffffffff81786188-ffffffff817861b2: vfio_cap_len.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int vfio_cap_len(struct vfio_pci_device *vdev, u8 cap, u8 pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vfio/pci/vfio_pci_config.c (0)
Location: drivers/vfio/pci/vfio_pci_config.c:1229
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_config_init
```
**Symbols:**

```
ffffffff817d0040-ffffffff817d044f: vfio_cap_len (STB_LOCAL)
ffffffff817d0f58-ffffffff817d0f82: vfio_cap_len.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int vfio_cap_len(struct vfio_pci_device *vdev, u8 cap, u8 pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vfio/pci/vfio_pci_config.c (0)
Location: drivers/vfio/pci/vfio_pci_config.c:1229
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_config_init
```
**Symbols:**

```
ffffffff817ea2e0-ffffffff817ea6ef: vfio_cap_len (STB_LOCAL)
ffffffff817eb1f8-ffffffff817eb222: vfio_cap_len.cold (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct vfio_pci_device *vdev</code> ➡️ <code>struct vfio_pci_core_device *vdev</code>
</li>
</ul>
</details>
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
