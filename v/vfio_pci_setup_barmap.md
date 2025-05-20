# Function: <code>vfio_pci_setup_barmap</code>

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
int vfio_pci_setup_barmap(struct vfio_pci_device *vdev, int bar);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_rdwr.c (ffffffff817d9390)
Location: drivers/vfio/pci/vfio_pci_rdwr.c:132
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_ioeventfd
  - drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_bar_rw
```
**Symbols:**

```
ffffffff817d9390-ffffffff817d9422: vfio_pci_setup_barmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int vfio_pci_setup_barmap(struct vfio_pci_device *vdev, int bar);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_rdwr.c (ffffffff818a70d0)
Location: drivers/vfio/pci/vfio_pci_rdwr.c:203
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_ioeventfd
  - drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_bar_rw
```
**Symbols:**

```
ffffffff818a70d0-ffffffff818a7160: vfio_pci_setup_barmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int vfio_pci_setup_barmap(struct vfio_pci_device *vdev, int bar);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_rdwr.c (ffffffff818b5f90)
Location: drivers/vfio/pci/vfio_pci_rdwr.c:203
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_ioeventfd
  - drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_bar_rw
```
**Symbols:**

```
ffffffff818b5f90-ffffffff818b6020: vfio_pci_setup_barmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int vfio_pci_setup_barmap(struct vfio_pci_device *vdev, int bar);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_rdwr.c (ffffffff81899440)
Location: drivers/vfio/pci/vfio_pci_rdwr.c:203
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_ioeventfd
  - drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_bar_rw
```
**Symbols:**

```
ffffffff81899440-ffffffff818994d7: vfio_pci_setup_barmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int vfio_pci_setup_barmap(struct vfio_pci_core_device *vdev, int bar);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vfio/pci/vfio_pci_rdwr.c (0)
Location: drivers/vfio/pci/vfio_pci_rdwr.c:203
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_ioeventfd
  - drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_bar_rw
```
**Symbols:**

```
ffffffff8192cf60-ffffffff8192d056: vfio_pci_setup_barmap (STB_LOCAL)
ffffffff81d12483-ffffffff81d124c5: vfio_pci_setup_barmap.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int vfio_pci_setup_barmap(struct vfio_pci_core_device *vdev, int bar);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vfio/pci/vfio_pci_rdwr.c (0)
Location: drivers/vfio/pci/vfio_pci_rdwr.c:203
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_ioeventfd
  - drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_bar_rw
```
**Symbols:**

```
ffffffff81a836a0-ffffffff81a83792: vfio_pci_setup_barmap (STB_LOCAL)
ffffffff81edd1bb-ffffffff81edd1ed: vfio_pci_setup_barmap.cold (STB_LOCAL)
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
int vfio_pci_setup_barmap(struct vfio_pci_device *vdev, int bar);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_rdwr.c (c000000000ab9600)
Location: drivers/vfio/pci/vfio_pci_rdwr.c:132
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_ioeventfd
  - drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_bar_rw
```
**Symbols:**

```
c000000000ab9600-c000000000ab9710: vfio_pci_setup_barmap (STB_LOCAL)
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
int vfio_pci_setup_barmap(struct vfio_pci_device *vdev, int bar);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_rdwr.c (ffffffff81783440)
Location: drivers/vfio/pci/vfio_pci_rdwr.c:132
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_ioeventfd
  - drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_bar_rw
```
**Symbols:**

```
ffffffff81783440-ffffffff817834d2: vfio_pci_setup_barmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int vfio_pci_setup_barmap(struct vfio_pci_device *vdev, int bar);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_rdwr.c (ffffffff817ce210)
Location: drivers/vfio/pci/vfio_pci_rdwr.c:132
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_ioeventfd
  - drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_bar_rw
```
**Symbols:**

```
ffffffff817ce210-ffffffff817ce2a2: vfio_pci_setup_barmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int vfio_pci_setup_barmap(struct vfio_pci_device *vdev, int bar);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_rdwr.c (ffffffff817e84b0)
Location: drivers/vfio/pci/vfio_pci_rdwr.c:132
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_ioeventfd
  - drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_bar_rw
```
**Symbols:**

```
ffffffff817e84b0-ffffffff817e8542: vfio_pci_setup_barmap (STB_LOCAL)
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
