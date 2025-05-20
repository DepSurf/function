# Function: <code>xdbc_get_page</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void *xdbc_get_page(dma_addr_t *dma_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/early/xhci-dbc.c (ffffffff828ea6a1)
Location: drivers/usb/early/xhci-dbc.c:93
Inline: False
Direct callers:
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
```
**Symbols:**

```
ffffffff828ea6a1-ffffffff828ea6f7: xdbc_get_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void *xdbc_get_page(dma_addr_t *dma_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/early/xhci-dbc.c (ffffffff829050cd)
Location: drivers/usb/early/xhci-dbc.c:93
Inline: False
Direct callers:
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
```
**Symbols:**

```
ffffffff829050cd-ffffffff82905123: xdbc_get_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void *xdbc_get_page(dma_addr_t *dma_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/early/xhci-dbc.c (ffffffff8290eb08)
Location: drivers/usb/early/xhci-dbc.c:93
Inline: False
Direct callers:
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
```
**Symbols:**

```
ffffffff8290eb08-ffffffff8290eb5e: xdbc_get_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void *xdbc_get_page(dma_addr_t *dma_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/early/xhci-dbc.c (ffffffff82d22d06)
Location: drivers/usb/early/xhci-dbc.c:92
Inline: False
Direct callers:
  - drivers/usb/early/xhci-dbc.c:xdbc_early_setup
  - drivers/usb/early/xhci-dbc.c:xdbc_early_setup
  - drivers/usb/early/xhci-dbc.c:xdbc_alloc_ring
```
**Symbols:**

```
ffffffff82d22d06-ffffffff82d22d5c: xdbc_get_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void *xdbc_get_page(dma_addr_t *dma_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/early/xhci-dbc.c (ffffffff830109a7)
Location: drivers/usb/early/xhci-dbc.c:94
Inline: False
Direct callers:
  - drivers/usb/early/xhci-dbc.c:xdbc_early_setup
  - drivers/usb/early/xhci-dbc.c:xdbc_early_setup
  - drivers/usb/early/xhci-dbc.c:xdbc_alloc_ring
```
**Symbols:**

```
ffffffff830109a7-ffffffff830109fd: xdbc_get_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void *xdbc_get_page(dma_addr_t *dma_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/early/xhci-dbc.c (ffffffff8321b8c4)
Location: drivers/usb/early/xhci-dbc.c:94
Inline: False
Direct callers:
  - drivers/usb/early/xhci-dbc.c:xdbc_alloc_ring
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
```
**Symbols:**

```
ffffffff8321b8c4-ffffffff8321b91a: xdbc_get_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void *xdbc_get_page(dma_addr_t *dma_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/early/xhci-dbc.c (ffffffff83305513)
Location: drivers/usb/early/xhci-dbc.c:93
Inline: False
Direct callers:
  - drivers/usb/early/xhci-dbc.c:xdbc_alloc_ring
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
```
**Symbols:**

```
ffffffff83305513-ffffffff83305569: xdbc_get_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void *xdbc_get_page(dma_addr_t *dma_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/early/xhci-dbc.c (ffffffff834be652)
Location: drivers/usb/early/xhci-dbc.c:93
Inline: False
Direct callers:
  - drivers/usb/early/xhci-dbc.c:xdbc_alloc_ring
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
```
**Symbols:**

```
ffffffff834be652-ffffffff834be6b2: xdbc_get_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/early/xhci-dbc.c (ffffffff83efcab1)
Location: drivers/usb/early/xhci-dbc.c:93
Inline: True
Inline callers:
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/early/xhci-dbc.c (ffffffff837228b1)
Location: drivers/usb/early/xhci-dbc.c:93
Inline: True
Inline callers:
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/early/xhci-dbc.c (ffffffff839566e1)
Location: drivers/usb/early/xhci-dbc.c:93
Inline: True
Inline callers:
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
```
</details>
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
In <code>ppc64el</code>: Absent ⚠️
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
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void *xdbc_get_page(dma_addr_t *dma_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/early/xhci-dbc.c (ffffffff8290fb6a)
Location: drivers/usb/early/xhci-dbc.c:93
Inline: False
Direct callers:
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
```
**Symbols:**

```
ffffffff8290fb6a-ffffffff8290fbc0: xdbc_get_page (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
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
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
