# Function: <code>vfio_virqfd_disable</code>

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
void vfio_virqfd_disable(struct virqfd **pvirqfd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/virqfd.c (ffffffff817d2740)
Location: drivers/vfio/virqfd.c:195
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_disable
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_disable
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_disable
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_intx_disable
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_intx_disable
  - drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_ioeventfd
```
**Symbols:**

```
ffffffff817d2740-ffffffff817d27a2: vfio_virqfd_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void vfio_virqfd_disable(struct virqfd **pvirqfd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/virqfd.c (ffffffff8189d7f0)
Location: drivers/vfio/virqfd.c:195
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_disable
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_intx_trigger
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_intx_trigger
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_intx_trigger
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_intx_trigger
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_disable
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_disable
  - drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_ioeventfd
```
**Symbols:**

```
ffffffff8189d7f0-ffffffff8189d852: vfio_virqfd_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void vfio_virqfd_disable(struct virqfd **pvirqfd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/virqfd.c (ffffffff818ac3d0)
Location: drivers/vfio/virqfd.c:198
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_disable
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_intx_trigger
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_intx_trigger
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_intx_trigger
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_intx_trigger
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_disable
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_disable
  - drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_ioeventfd
```
**Symbols:**

```
ffffffff818ac3d0-ffffffff818ac432: vfio_virqfd_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void vfio_virqfd_disable(struct virqfd **pvirqfd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/virqfd.c (ffffffff8188f4f0)
Location: drivers/vfio/virqfd.c:198
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_disable
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_intx_trigger
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_intx_trigger
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_intx_trigger
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_intx_trigger
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_disable
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_disable
  - drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_ioeventfd
```
**Symbols:**

```
ffffffff8188f4f0-ffffffff8188f552: vfio_virqfd_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void vfio_virqfd_disable(struct virqfd **pvirqfd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/virqfd.c (ffffffff81922df0)
Location: drivers/vfio/virqfd.c:198
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_disable
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_intx_trigger
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_intx_trigger
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_intx_trigger
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_intx_trigger
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_disable
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_disable
  - drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_ioeventfd
```
**Symbols:**

```
ffffffff81922df0-ffffffff81922e52: vfio_virqfd_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void vfio_virqfd_disable(struct virqfd **pvirqfd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/virqfd.c (ffffffff81a788e0)
Location: drivers/vfio/virqfd.c:198
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_disable
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_intx_trigger
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_intx_trigger
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_intx_trigger
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_intx_trigger
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_intx_unmask
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_disable
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_disable
  - drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_ioeventfd
```
**Symbols:**

```
ffffffff81a788e0-ffffffff81a7894e: vfio_virqfd_disable (STB_GLOBAL)
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
void vfio_virqfd_disable(struct virqfd **pvirqfd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/virqfd.c (c000000000ab1a40)
Location: drivers/vfio/virqfd.c:195
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_disable
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_disable
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_disable
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_intx_disable
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_intx_disable
  - drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_ioeventfd
```
**Symbols:**

```
c000000000ab1a40-c000000000ab1aec: vfio_virqfd_disable (STB_GLOBAL)
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
void vfio_virqfd_disable(struct virqfd **pvirqfd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/virqfd.c (ffffffff8177c7f0)
Location: drivers/vfio/virqfd.c:195
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_disable
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_disable
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_disable
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_intx_disable
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_intx_disable
  - drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_ioeventfd
```
**Symbols:**

```
ffffffff8177c7f0-ffffffff8177c852: vfio_virqfd_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void vfio_virqfd_disable(struct virqfd **pvirqfd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/virqfd.c (ffffffff817c75c0)
Location: drivers/vfio/virqfd.c:195
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_disable
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_disable
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_disable
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_intx_disable
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_intx_disable
  - drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_ioeventfd
```
**Symbols:**

```
ffffffff817c75c0-ffffffff817c7622: vfio_virqfd_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void vfio_virqfd_disable(struct virqfd **pvirqfd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/virqfd.c (ffffffff817e1a70)
Location: drivers/vfio/virqfd.c:195
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_disable
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_disable
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_msi_disable
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_intx_disable
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_intx_disable
  - drivers/vfio/pci/vfio_pci_rdwr.c:vfio_pci_ioeventfd
```
**Symbols:**

```
ffffffff817e1a70-ffffffff817e1ad2: vfio_virqfd_disable (STB_GLOBAL)
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
