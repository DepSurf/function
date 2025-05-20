# Function: <code>vfio_send_intx_eventfd</code>

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
void vfio_send_intx_eventfd(void *opaque, void *unused);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_intrs.c (ffffffff817d8440)
Location: drivers/vfio/pci/vfio_pci_intrs.c:28
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_intx_trigger
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_intx_handler
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_intx_unmask
```
**Symbols:**

```
ffffffff817d8440-ffffffff817d8473: vfio_send_intx_eventfd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void vfio_send_intx_eventfd(void *opaque, void *unused);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_intrs.c (ffffffff818a6be3)
Location: drivers/vfio/pci/vfio_pci_intrs.c:28
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_intx_trigger
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_intx_handler
```
**Symbols:**

```
ffffffff818a5f50-ffffffff818a5f83: vfio_send_intx_eventfd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void vfio_send_intx_eventfd(void *opaque, void *unused);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_intrs.c (ffffffff818b5ad3)
Location: drivers/vfio/pci/vfio_pci_intrs.c:28
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_intx_trigger
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_intx_handler
```
**Symbols:**

```
ffffffff818b4e60-ffffffff818b4e93: vfio_send_intx_eventfd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void vfio_send_intx_eventfd(void *opaque, void *unused);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_intrs.c (ffffffff81898f84)
Location: drivers/vfio/pci/vfio_pci_intrs.c:28
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_intx_trigger
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_intx_handler
```
**Symbols:**

```
ffffffff81898300-ffffffff81898333: vfio_send_intx_eventfd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void vfio_send_intx_eventfd(void *opaque, void *unused);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/vfio/pci/vfio_pci_intrs.c (ffffffff8192cb35)
Location: drivers/vfio/pci/vfio_pci_intrs.c:28
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_intx_trigger
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_intx_trigger
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_intx_handler
```
**Symbols:**

```
ffffffff8192c040-ffffffff8192c08b: vfio_send_intx_eventfd (STB_LOCAL)
ffffffff81d122db-ffffffff81d122f0: vfio_send_intx_eventfd.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void vfio_send_intx_eventfd(void *opaque, void *unused);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/vfio/pci/vfio_pci_intrs.c (ffffffff81a8337a)
Location: drivers/vfio/pci/vfio_pci_intrs.c:28
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_intx_trigger
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_intx_trigger
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_intx_unmask
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_intx_unmask
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_intx_handler
```
**Symbols:**

```
ffffffff81a82790-ffffffff81a827ef: vfio_send_intx_eventfd (STB_LOCAL)
ffffffff81edd021-ffffffff81edd036: vfio_send_intx_eventfd.cold (STB_LOCAL)
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
void vfio_send_intx_eventfd(void *opaque, void *unused);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_intrs.c (c000000000ab7e30)
Location: drivers/vfio/pci/vfio_pci_intrs.c:28
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_intx_trigger
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_intx_handler
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_intx_handler
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_intx_unmask
```
**Symbols:**

```
c000000000ab7e30-c000000000ab7e88: vfio_send_intx_eventfd (STB_LOCAL)
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
void vfio_send_intx_eventfd(void *opaque, void *unused);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_intrs.c (ffffffff817824f0)
Location: drivers/vfio/pci/vfio_pci_intrs.c:28
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_intx_trigger
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_intx_handler
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_intx_unmask
```
**Symbols:**

```
ffffffff817824f0-ffffffff81782523: vfio_send_intx_eventfd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void vfio_send_intx_eventfd(void *opaque, void *unused);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_intrs.c (ffffffff817cd2c0)
Location: drivers/vfio/pci/vfio_pci_intrs.c:28
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_intx_trigger
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_intx_handler
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_intx_unmask
```
**Symbols:**

```
ffffffff817cd2c0-ffffffff817cd2f3: vfio_send_intx_eventfd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void vfio_send_intx_eventfd(void *opaque, void *unused);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vfio/pci/vfio_pci_intrs.c (ffffffff817e7560)
Location: drivers/vfio/pci/vfio_pci_intrs.c:28
Inline: False
Direct callers:
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_set_intx_trigger
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_intx_handler
  - drivers/vfio/pci/vfio_pci_intrs.c:vfio_pci_intx_unmask
```
**Symbols:**

```
ffffffff817e7560-ffffffff817e7593: vfio_send_intx_eventfd (STB_LOCAL)
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
