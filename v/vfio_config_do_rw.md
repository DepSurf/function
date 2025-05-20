# Function: <code>vfio_config_do_rw</code>

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
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_config.c (ffffffff817dbbca)
Location: drivers/vfio/pci/vfio_pci_config.c:1749
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_pci_config_rw
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
ssize_t vfio_config_do_rw(struct vfio_pci_device *vdev, char *buf, size_t count, loff_t *ppos, bool iswrite);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_config.c (ffffffff818a9960)
Location: drivers/vfio/pci/vfio_pci_config.c:1798
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_pci_config_rw
```
**Symbols:**

```
ffffffff818a9960-ffffffff818a9c3b: vfio_config_do_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
ssize_t vfio_config_do_rw(struct vfio_pci_device *vdev, char *buf, size_t count, loff_t *ppos, bool iswrite);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_config.c (ffffffff818b8890)
Location: drivers/vfio/pci/vfio_pci_config.c:1805
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_pci_config_rw
```
**Symbols:**

```
ffffffff818b8890-ffffffff818b8b6b: vfio_config_do_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
ssize_t vfio_config_do_rw(struct vfio_pci_device *vdev, char *buf, size_t count, loff_t *ppos, bool iswrite);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_config.c (ffffffff8189bd30)
Location: drivers/vfio/pci/vfio_pci_config.c:1805
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_pci_config_rw
```
**Symbols:**

```
ffffffff8189bd30-ffffffff8189c029: vfio_config_do_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
ssize_t vfio_config_do_rw(struct vfio_pci_core_device *vdev, char *buf, size_t count, loff_t *ppos, bool iswrite);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_config.c (ffffffff8192fe60)
Location: drivers/vfio/pci/vfio_pci_config.c:1805
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_pci_config_rw
```
**Symbols:**

```
ffffffff8192fe60-ffffffff81930271: vfio_config_do_rw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
ssize_t vfio_config_do_rw(struct vfio_pci_core_device *vdev, char *buf, size_t count, loff_t *ppos, bool iswrite);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_config.c (ffffffff81a86800)
Location: drivers/vfio/pci/vfio_pci_config.c:1855
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_pci_config_rw
```
**Symbols:**

```
ffffffff81a86800-ffffffff81a86c63: vfio_config_do_rw (STB_LOCAL)
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
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_config.c (c000000000abcf54)
Location: drivers/vfio/pci/vfio_pci_config.c:1749
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_pci_config_rw
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
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_config.c (ffffffff81785c7a)
Location: drivers/vfio/pci/vfio_pci_config.c:1749
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_pci_config_rw
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
In drivers/vfio/pci/vfio_pci_config.c (ffffffff817d0a4a)
Location: drivers/vfio/pci/vfio_pci_config.c:1749
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_pci_config_rw
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
In drivers/vfio/pci/vfio_pci_config.c (ffffffff817eacea)
Location: drivers/vfio/pci/vfio_pci_config.c:1749
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_config.c:vfio_pci_config_rw
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
