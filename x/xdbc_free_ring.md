# Function: <code>xdbc_free_ring</code>

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
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/early/xhci-dbc.c (ffffffff828ea521)
Location: drivers/usb/early/xhci-dbc.c:187
Inline: True
Direct callers:
  - drivers/usb/early/xhci-dbc.c:xdbc_init
  - drivers/usb/early/xhci-dbc.c:xdbc_init
  - drivers/usb/early/xhci-dbc.c:xdbc_init
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
```
**Symbols:**

```
ffffffff828ea521-ffffffff828ea54f: xdbc_free_ring.isra.3 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/early/xhci-dbc.c (ffffffff82904f47)
Location: drivers/usb/early/xhci-dbc.c:187
Inline: True
Direct callers:
  - drivers/usb/early/xhci-dbc.c:xdbc_init
  - drivers/usb/early/xhci-dbc.c:xdbc_init
  - drivers/usb/early/xhci-dbc.c:xdbc_init
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
```
**Symbols:**

```
ffffffff82904f47-ffffffff82904f75: xdbc_free_ring.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/early/xhci-dbc.c (ffffffff8290e982)
Location: drivers/usb/early/xhci-dbc.c:187
Inline: True
Direct callers:
  - drivers/usb/early/xhci-dbc.c:xdbc_init
  - drivers/usb/early/xhci-dbc.c:xdbc_init
  - drivers/usb/early/xhci-dbc.c:xdbc_init
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
```
**Symbols:**

```
ffffffff8290e982-ffffffff8290e9b0: xdbc_free_ring.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void xdbc_free_ring(struct xdbc_ring *ring);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/early/xhci-dbc.c (ffffffff82d22ac2)
Location: drivers/usb/early/xhci-dbc.c:186
Inline: False
Direct callers:
  - drivers/usb/early/xhci-dbc.c:xdbc_init
  - drivers/usb/early/xhci-dbc.c:xdbc_init
  - drivers/usb/early/xhci-dbc.c:xdbc_init
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
```
**Symbols:**

```
ffffffff82d22ac2-ffffffff82d22af0: xdbc_free_ring (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void xdbc_free_ring(struct xdbc_ring *ring);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/early/xhci-dbc.c (ffffffff830108bb)
Location: drivers/usb/early/xhci-dbc.c:181
Inline: False
Direct callers:
  - drivers/usb/early/xhci-dbc.c:xdbc_init
  - drivers/usb/early/xhci-dbc.c:xdbc_init
  - drivers/usb/early/xhci-dbc.c:xdbc_init
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
```
**Symbols:**

```
ffffffff830108bb-ffffffff830108e9: xdbc_free_ring (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void xdbc_free_ring(struct xdbc_ring *ring);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/early/xhci-dbc.c (ffffffff8321b896)
Location: drivers/usb/early/xhci-dbc.c:181
Inline: False
Direct callers:
  - drivers/usb/early/xhci-dbc.c:xdbc_init
  - drivers/usb/early/xhci-dbc.c:xdbc_init
  - drivers/usb/early/xhci-dbc.c:xdbc_init
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
```
**Symbols:**

```
ffffffff8321b896-ffffffff8321b8c4: xdbc_free_ring (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void xdbc_free_ring(struct xdbc_ring *ring);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/early/xhci-dbc.c (ffffffff833054e5)
Location: drivers/usb/early/xhci-dbc.c:188
Inline: False
Direct callers:
  - drivers/usb/early/xhci-dbc.c:xdbc_init
  - drivers/usb/early/xhci-dbc.c:xdbc_init
  - drivers/usb/early/xhci-dbc.c:xdbc_init
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
```
**Symbols:**

```
ffffffff833054e5-ffffffff83305513: xdbc_free_ring (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void xdbc_free_ring(struct xdbc_ring *ring);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/early/xhci-dbc.c (ffffffff834be612)
Location: drivers/usb/early/xhci-dbc.c:188
Inline: False
Direct callers:
  - drivers/usb/early/xhci-dbc.c:xdbc_init
  - drivers/usb/early/xhci-dbc.c:xdbc_init
  - drivers/usb/early/xhci-dbc.c:xdbc_init
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
```
**Symbols:**

```
ffffffff834be612-ffffffff834be652: xdbc_free_ring (STB_LOCAL)
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
In drivers/usb/early/xhci-dbc.c (ffffffff83efc5c2)
Location: drivers/usb/early/xhci-dbc.c:188
Inline: True
Inline callers:
  - drivers/usb/early/xhci-dbc.c:xdbc_init
  - drivers/usb/early/xhci-dbc.c:xdbc_init
  - drivers/usb/early/xhci-dbc.c:xdbc_init
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
In drivers/usb/early/xhci-dbc.c (ffffffff837223c2)
Location: drivers/usb/early/xhci-dbc.c:188
Inline: True
Inline callers:
  - drivers/usb/early/xhci-dbc.c:xdbc_init
  - drivers/usb/early/xhci-dbc.c:xdbc_init
  - drivers/usb/early/xhci-dbc.c:xdbc_init
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
In drivers/usb/early/xhci-dbc.c (ffffffff839561f2)
Location: drivers/usb/early/xhci-dbc.c:188
Inline: True
Inline callers:
  - drivers/usb/early/xhci-dbc.c:xdbc_init
  - drivers/usb/early/xhci-dbc.c:xdbc_init
  - drivers/usb/early/xhci-dbc.c:xdbc_init
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
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/early/xhci-dbc.c (ffffffff8290f9e4)
Location: drivers/usb/early/xhci-dbc.c:187
Inline: True
Direct callers:
  - drivers/usb/early/xhci-dbc.c:xdbc_init
  - drivers/usb/early/xhci-dbc.c:xdbc_init
  - drivers/usb/early/xhci-dbc.c:xdbc_init
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
  - drivers/usb/early/xhci-dbc.c:early_xdbc_setup_hardware
```
**Symbols:**

```
ffffffff8290f9e4-ffffffff8290fa12: xdbc_free_ring.isra.0 (STB_LOCAL)
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
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
</ul>
