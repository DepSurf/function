# Function: <code>vfio_virqfd_enable</code>

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
int vfio_virqfd_enable(void *opaque, int (*handler)(void *, void *), void (*thread)(void *, void *), void *data, struct virqfd **pvirqfd, int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/virqfd.c (ffffffff817d27b0)
Location: drivers/vfio/virqfd.c:104
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_ioeventfd
```
**Symbols:**

```
ffffffff817d27b0-ffffffff817d29c0: vfio_virqfd_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int vfio_virqfd_enable(void *opaque, int (*handler)(void *, void *), void (*thread)(void *, void *), void *data, struct virqfd **pvirqfd, int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/virqfd.c (ffffffff8189d910)
Location: drivers/vfio/virqfd.c:104
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_ioeventfd
```
**Symbols:**

```
ffffffff8189d910-ffffffff8189db20: vfio_virqfd_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int vfio_virqfd_enable(void *opaque, int (*handler)(void *, void *), void (*thread)(void *, void *), void *data, struct virqfd **pvirqfd, int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/virqfd.c (ffffffff818ac530)
Location: drivers/vfio/virqfd.c:107
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_ioeventfd
```
**Symbols:**

```
ffffffff818ac530-ffffffff818ac740: vfio_virqfd_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int vfio_virqfd_enable(void *opaque, int (*handler)(void *, void *), void (*thread)(void *, void *), void *data, struct virqfd **pvirqfd, int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/virqfd.c (ffffffff8188f650)
Location: drivers/vfio/virqfd.c:107
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_ioeventfd
```
**Symbols:**

```
ffffffff8188f650-ffffffff8188f85d: vfio_virqfd_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int vfio_virqfd_enable(void *opaque, int (*handler)(void *, void *), void (*thread)(void *, void *), void *data, struct virqfd **pvirqfd, int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/virqfd.c (ffffffff81922f50)
Location: drivers/vfio/virqfd.c:107
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_ioeventfd
```
**Symbols:**

```
ffffffff81922f50-ffffffff8192315d: vfio_virqfd_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int vfio_virqfd_enable(void *opaque, int (*handler)(void *, void *), void (*thread)(void *, void *), void *data, struct virqfd **pvirqfd, int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/virqfd.c (ffffffff81a78950)
Location: drivers/vfio/virqfd.c:107
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_intx_unmask
  - drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_ioeventfd
```
**Symbols:**

```
ffffffff81a78950-ffffffff81a78b67: vfio_virqfd_enable (STB_GLOBAL)
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
int vfio_virqfd_enable(void *opaque, int (*handler)(void *, void *), void (*thread)(void *, void *), void *data, struct virqfd **pvirqfd, int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/virqfd.c (c000000000ab1af0)
Location: drivers/vfio/virqfd.c:104
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_ioeventfd
```
**Symbols:**

```
c000000000ab1af0-c000000000ab1e74: vfio_virqfd_enable (STB_GLOBAL)
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
int vfio_virqfd_enable(void *opaque, int (*handler)(void *, void *), void (*thread)(void *, void *), void *data, struct virqfd **pvirqfd, int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/virqfd.c (ffffffff8177c860)
Location: drivers/vfio/virqfd.c:104
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_ioeventfd
```
**Symbols:**

```
ffffffff8177c860-ffffffff8177ca64: vfio_virqfd_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int vfio_virqfd_enable(void *opaque, int (*handler)(void *, void *), void (*thread)(void *, void *), void *data, struct virqfd **pvirqfd, int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/virqfd.c (ffffffff817c7630)
Location: drivers/vfio/virqfd.c:104
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_ioeventfd
```
**Symbols:**

```
ffffffff817c7630-ffffffff817c7840: vfio_virqfd_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int vfio_virqfd_enable(void *opaque, int (*handler)(void *, void *), void (*thread)(void *, void *), void *data, struct virqfd **pvirqfd, int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/virqfd.c (ffffffff817e1860)
Location: drivers/vfio/virqfd.c:104
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_ioeventfd
```
**Symbols:**

```
ffffffff817e1860-ffffffff817e1a65: vfio_virqfd_enable (STB_GLOBAL)
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
