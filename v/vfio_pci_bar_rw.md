# Function: <code>vfio_pci_bar_rw</code>

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
ssize_t vfio_pci_bar_rw(struct vfio_pci_device *vdev, char *buf, size_t count, loff_t *ppos, bool iswrite);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_rdwr.c (ffffffff817d9720)
Location: drivers/vfio/pci/vfio_pci_rdwr.c:156
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_rw
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_rw
```
**Symbols:**

```
ffffffff817d9720-ffffffff817d9921: vfio_pci_bar_rw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
ssize_t vfio_pci_bar_rw(struct vfio_pci_device *vdev, char *buf, size_t count, loff_t *ppos, bool iswrite);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_rdwr.c (ffffffff818a77c0)
Location: drivers/vfio/pci/vfio_pci_rdwr.c:227
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_rw
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_rw
```
**Symbols:**

```
ffffffff818a77c0-ffffffff818a79e7: vfio_pci_bar_rw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
ssize_t vfio_pci_bar_rw(struct vfio_pci_device *vdev, char *buf, size_t count, loff_t *ppos, bool iswrite);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_rdwr.c (ffffffff818b6720)
Location: drivers/vfio/pci/vfio_pci_rdwr.c:227
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_rw
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_rw
```
**Symbols:**

```
ffffffff818b6720-ffffffff818b6947: vfio_pci_bar_rw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
ssize_t vfio_pci_bar_rw(struct vfio_pci_device *vdev, char *buf, size_t count, loff_t *ppos, bool iswrite);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_rdwr.c (ffffffff81899bd0)
Location: drivers/vfio/pci/vfio_pci_rdwr.c:227
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_rw
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_rw
```
**Symbols:**

```
ffffffff81899bd0-ffffffff81899df6: vfio_pci_bar_rw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
ssize_t vfio_pci_bar_rw(struct vfio_pci_core_device *vdev, char *buf, size_t count, loff_t *ppos, bool iswrite);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_rdwr.c (ffffffff8192d780)
Location: drivers/vfio/pci/vfio_pci_rdwr.c:227
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_rw
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_rw
```
**Symbols:**

```
ffffffff8192d780-ffffffff8192db22: vfio_pci_bar_rw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
ssize_t vfio_pci_bar_rw(struct vfio_pci_core_device *vdev, char *buf, size_t count, loff_t *ppos, bool iswrite);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_rdwr.c (ffffffff81a83f40)
Location: drivers/vfio/pci/vfio_pci_rdwr.c:227
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_rw
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_rw
```
**Symbols:**

```
ffffffff81a83f40-ffffffff81a842d9: vfio_pci_bar_rw (STB_GLOBAL)
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
ssize_t vfio_pci_bar_rw(struct vfio_pci_device *vdev, char *buf, size_t count, loff_t *ppos, bool iswrite);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_rdwr.c (c000000000ab9b40)
Location: drivers/vfio/pci/vfio_pci_rdwr.c:156
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_rw
```
**Symbols:**

```
c000000000ab9b40-c000000000ab9d90: vfio_pci_bar_rw (STB_GLOBAL)
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
ssize_t vfio_pci_bar_rw(struct vfio_pci_device *vdev, char *buf, size_t count, loff_t *ppos, bool iswrite);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_rdwr.c (ffffffff817837d0)
Location: drivers/vfio/pci/vfio_pci_rdwr.c:156
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_rw
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_rw
```
**Symbols:**

```
ffffffff817837d0-ffffffff817839d1: vfio_pci_bar_rw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
ssize_t vfio_pci_bar_rw(struct vfio_pci_device *vdev, char *buf, size_t count, loff_t *ppos, bool iswrite);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_rdwr.c (ffffffff817ce5a0)
Location: drivers/vfio/pci/vfio_pci_rdwr.c:156
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_rw
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_rw
```
**Symbols:**

```
ffffffff817ce5a0-ffffffff817ce7a1: vfio_pci_bar_rw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
ssize_t vfio_pci_bar_rw(struct vfio_pci_device *vdev, char *buf, size_t count, loff_t *ppos, bool iswrite);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_rdwr.c (ffffffff817e8840)
Location: drivers/vfio/pci/vfio_pci_rdwr.c:156
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_rw
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_rw
```
**Symbols:**

```
ffffffff817e8840-ffffffff817e8a41: vfio_pci_bar_rw (STB_GLOBAL)
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
