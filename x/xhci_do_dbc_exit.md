# Function: <code>xhci_do_dbc_exit</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void xhci_do_dbc_exit(struct xhci_hcd *xhci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (ffffffff81772b30)
Location: drivers/usb/host/xhci-dbgcap.c:814
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_exit
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_init
```
**Symbols:**

```
ffffffff81772b30-ffffffff81772b79: xhci_do_dbc_exit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void xhci_do_dbc_exit(struct xhci_hcd *xhci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (ffffffff817b30c0)
Location: drivers/usb/host/xhci-dbgcap.c:823
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_exit
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_init
```
**Symbols:**

```
ffffffff817b30c0-ffffffff817b3109: xhci_do_dbc_exit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void xhci_do_dbc_exit(struct xhci_hcd *xhci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (ffffffff817d9700)
Location: drivers/usb/host/xhci-dbgcap.c:824
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_exit
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_init
```
**Symbols:**

```
ffffffff817d9700-ffffffff817d9749: xhci_do_dbc_exit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void xhci_do_dbc_exit(struct xhci_hcd *xhci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (ffffffff8181a060)
Location: drivers/usb/host/xhci-dbgcap.c:822
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_exit
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_init
```
**Symbols:**

```
ffffffff8181a060-ffffffff8181a0a9: xhci_do_dbc_exit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void xhci_do_dbc_exit(struct xhci_hcd *xhci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (ffffffff8184b400)
Location: drivers/usb/host/xhci-dbgcap.c:821
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_exit
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_init
```
**Symbols:**

```
ffffffff8184b400-ffffffff8184b449: xhci_do_dbc_exit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (ffffffff8191f2fe)
Location: drivers/usb/host/xhci-dbgcap.c:821
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_exit
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (ffffffff81926a99)
Location: drivers/usb/host/xhci-dbgcap.c:917
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_exit
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (ffffffff8190a179)
Location: drivers/usb/host/xhci-dbgcap.c:917
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_exit
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (ffffffff819aaa39)
Location: drivers/usb/host/xhci-dbgcap.c:917
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_exit
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_init
```
</details>
</li>
<li>
In <code>5.19</code>: Absent ⚠️
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
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void xhci_do_dbc_exit(struct xhci_hcd *xhci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (ffff800010a8a7d0)
Location: drivers/usb/host/xhci-dbgcap.c:821
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_exit
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_init
```
**Symbols:**

```
ffff800010a8a7d0-ffff800010a8a878: xhci_do_dbc_exit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void xhci_do_dbc_exit(struct xhci_hcd *xhci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (c0b5d4d0)
Location: drivers/usb/host/xhci-dbgcap.c:821
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_exit
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_init
```
**Symbols:**

```
c0b5d4d0-c0b5d518: xhci_do_dbc_exit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void xhci_do_dbc_exit(struct xhci_hcd *xhci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (c000000000b65de0)
Location: drivers/usb/host/xhci-dbgcap.c:821
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_exit
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_init
```
**Symbols:**

```
c000000000b65de0-c000000000b65e5c: xhci_do_dbc_exit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void xhci_do_dbc_exit(struct xhci_hcd *xhci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (ffffffe00069f468)
Location: drivers/usb/host/xhci-dbgcap.c:821
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_exit
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_init
```
**Symbols:**

```
ffffffe00069f468-ffffffe00069f4c0: xhci_do_dbc_exit (STB_LOCAL)
```
</details>
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
void xhci_do_dbc_exit(struct xhci_hcd *xhci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (ffffffff817c8950)
Location: drivers/usb/host/xhci-dbgcap.c:821
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_exit
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_init
```
**Symbols:**

```
ffffffff817c8950-ffffffff817c8999: xhci_do_dbc_exit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void xhci_do_dbc_exit(struct xhci_hcd *xhci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (ffffffff81840280)
Location: drivers/usb/host/xhci-dbgcap.c:821
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_exit
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_init
```
**Symbols:**

```
ffffffff81840280-ffffffff818402c9: xhci_do_dbc_exit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void xhci_do_dbc_exit(struct xhci_hcd *xhci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (ffffffff8185a750)
Location: drivers/usb/host/xhci-dbgcap.c:821
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_exit
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_init
```
**Symbols:**

```
ffffffff8185a750-ffffffff8185a799: xhci_do_dbc_exit (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
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
