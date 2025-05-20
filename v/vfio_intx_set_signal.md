# Function: <code>vfio_intx_set_signal</code>

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
int vfio_intx_set_signal(struct vfio_pci_device *vdev, int fd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_intrs.c (ffffffff817d87d0)
Location: drivers/vfio/pci/vfio_pci_intrs.c:171
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_intx_trigger
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_intx_trigger
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_intx_disable
```
**Symbols:**

```
ffffffff817d87d0-ffffffff817d8987: vfio_intx_set_signal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int vfio_intx_set_signal(struct vfio_pci_device *vdev, int fd);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_intrs.c (ffffffff818a6cff)
Location: drivers/vfio/pci/vfio_pci_intrs.c:171
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_intx_trigger
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_intx_trigger
Direct callers:
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_intx_trigger
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_intx_trigger
```
**Symbols:**

```
ffffffff818a6320-ffffffff818a64d7: vfio_intx_set_signal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int vfio_intx_set_signal(struct vfio_pci_device *vdev, int fd);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_intrs.c (ffffffff818b5bef)
Location: drivers/vfio/pci/vfio_pci_intrs.c:171
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_intx_trigger
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_intx_trigger
Direct callers:
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_intx_trigger
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_intx_trigger
```
**Symbols:**

```
ffffffff818b5210-ffffffff818b53c7: vfio_intx_set_signal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int vfio_intx_set_signal(struct vfio_pci_device *vdev, int fd);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_intrs.c (ffffffff818990a2)
Location: drivers/vfio/pci/vfio_pci_intrs.c:171
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_intx_trigger
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_intx_trigger
Direct callers:
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_intx_trigger
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_intx_trigger
```
**Symbols:**

```
ffffffff818986b0-ffffffff81898866: vfio_intx_set_signal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int vfio_intx_set_signal(struct vfio_pci_core_device *vdev, int fd);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/vfio/pci/vfio_pci_intrs.c (ffffffff8192cc69)
Location: drivers/vfio/pci/vfio_pci_intrs.c:171
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_intx_trigger
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_intx_trigger
Direct callers:
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_intx_trigger
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_intx_trigger
```
**Symbols:**

```
ffffffff8192c090-ffffffff8192c26e: vfio_intx_set_signal (STB_LOCAL)
ffffffff81d122f0-ffffffff81d12344: vfio_intx_set_signal.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
int vfio_intx_set_signal(struct vfio_pci_core_device *vdev, int fd);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/vfio/pci/vfio_pci_intrs.c (ffffffff81a831c1)
Location: drivers/vfio/pci/vfio_pci_intrs.c:171
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_intx_trigger
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_intx_trigger
Direct callers:
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_intx_trigger
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_intx_trigger
```
**Symbols:**

```
ffffffff81a827f0-ffffffff81a829fb: vfio_intx_set_signal (STB_LOCAL)
ffffffff81edd036-ffffffff81edd07a: vfio_intx_set_signal.cold (STB_LOCAL)
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
int vfio_intx_set_signal(struct vfio_pci_device *vdev, int fd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_intrs.c (c000000000ab8420)
Location: drivers/vfio/pci/vfio_pci_intrs.c:171
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_intx_trigger
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_intx_trigger
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_intx_disable
```
**Symbols:**

```
c000000000ab8420-c000000000ab864c: vfio_intx_set_signal (STB_LOCAL)
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
int vfio_intx_set_signal(struct vfio_pci_device *vdev, int fd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_intrs.c (ffffffff81782880)
Location: drivers/vfio/pci/vfio_pci_intrs.c:171
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_intx_trigger
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_intx_trigger
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_intx_disable
```
**Symbols:**

```
ffffffff81782880-ffffffff81782a37: vfio_intx_set_signal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int vfio_intx_set_signal(struct vfio_pci_device *vdev, int fd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_intrs.c (ffffffff817cd650)
Location: drivers/vfio/pci/vfio_pci_intrs.c:171
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_intx_trigger
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_intx_trigger
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_intx_disable
```
**Symbols:**

```
ffffffff817cd650-ffffffff817cd807: vfio_intx_set_signal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int vfio_intx_set_signal(struct vfio_pci_device *vdev, int fd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_intrs.c (ffffffff817e78f0)
Location: drivers/vfio/pci/vfio_pci_intrs.c:171
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_intx_trigger
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_intx_trigger
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_intx_disable
```
**Symbols:**

```
ffffffff817e78f0-ffffffff817e7aa7: vfio_intx_set_signal (STB_LOCAL)
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
