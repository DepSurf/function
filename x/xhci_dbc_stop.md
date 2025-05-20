# Function: <code>xhci_dbc_stop</code>

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
void xhci_dbc_stop(struct xhci_hcd *xhci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (ffffffff81772be0)
Location: drivers/usb/host/xhci-dbgcap.c:542
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_suspend
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_suspend
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_exit
  - drivers/usb/host/xhci-dbgcap.c:dbc_store
```
**Symbols:**

```
ffffffff81772be0-ffffffff81772d6a: xhci_dbc_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void xhci_dbc_stop(struct xhci_hcd *xhci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (ffffffff817b3170)
Location: drivers/usb/host/xhci-dbgcap.c:547
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_suspend
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_exit
  - drivers/usb/host/xhci-dbgcap.c:dbc_store
```
**Symbols:**

```
ffffffff817b3170-ffffffff817b3338: xhci_dbc_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void xhci_dbc_stop(struct xhci_hcd *xhci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (ffffffff817d97b0)
Location: drivers/usb/host/xhci-dbgcap.c:546
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_suspend
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_exit
  - drivers/usb/host/xhci-dbgcap.c:dbc_store
```
**Symbols:**

```
ffffffff817d97b0-ffffffff817d991b: xhci_dbc_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void xhci_dbc_stop(struct xhci_hcd *xhci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (0)
Location: drivers/usb/host/xhci-dbgcap.c:544
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_suspend
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_exit
  - drivers/usb/host/xhci-dbgcap.c:dbc_store
```
**Symbols:**

```
ffffffff8181a110-ffffffff8181a281: xhci_dbc_stop (STB_LOCAL)
ffffffff8181b4b6-ffffffff8181b4c9: xhci_dbc_stop.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void xhci_dbc_stop(struct xhci_hcd *xhci);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (ffffffff8184b4b0)
Location: drivers/usb/host/xhci-dbgcap.c:543
Inline: True
Direct callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_suspend
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_exit
  - drivers/usb/host/xhci-dbgcap.c:dbc_store
```
**Symbols:**

```
ffffffff8184b4b0-ffffffff8184b628: xhci_dbc_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void xhci_dbc_stop(struct xhci_hcd *xhci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (ffffffff8191de20)
Location: drivers/usb/host/xhci-dbgcap.c:543
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_suspend
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_exit
  - drivers/usb/host/xhci-dbgcap.c:dbc_store
```
**Symbols:**

```
ffffffff8191de20-ffffffff8191df98: xhci_dbc_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void xhci_dbc_stop(struct xhci_dbc *dbc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (ffffffff81925ce0)
Location: drivers/usb/host/xhci-dbgcap.c:629
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_suspend
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_exit
  - drivers/usb/host/xhci-dbgcap.c:dbc_store
```
**Symbols:**

```
ffffffff81925ce0-ffffffff81925e9d: xhci_dbc_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void xhci_dbc_stop(struct xhci_dbc *dbc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (ffffffff819093d0)
Location: drivers/usb/host/xhci-dbgcap.c:629
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_suspend
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_exit
  - drivers/usb/host/xhci-dbgcap.c:dbc_store
```
**Symbols:**

```
ffffffff819093d0-ffffffff8190958d: xhci_dbc_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void xhci_dbc_stop(struct xhci_dbc *dbc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (ffffffff819a9c50)
Location: drivers/usb/host/xhci-dbgcap.c:629
Inline: True
Direct callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_suspend
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_exit
  - drivers/usb/host/xhci-dbgcap.c:dbc_store
```
**Symbols:**

```
ffffffff819a9c50-ffffffff819a9e0d: xhci_dbc_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void xhci_dbc_stop(struct xhci_dbc *dbc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (ffffffff81b07bf0)
Location: drivers/usb/host/xhci-dbgcap.c:629
Inline: True
Direct callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_suspend
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_remove
  - drivers/usb/host/xhci-dbgcap.c:dbc_store
```
**Symbols:**

```
ffffffff81b07bf0-ffffffff81b07d9c: xhci_dbc_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void xhci_dbc_stop(struct xhci_dbc *dbc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (ffffffff81c97630)
Location: drivers/usb/host/xhci-dbgcap.c:629
Inline: True
Direct callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_suspend
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_remove
  - drivers/usb/host/xhci-dbgcap.c:dbc_store
```
**Symbols:**

```
ffffffff81c97630-ffffffff81c976dc: xhci_dbc_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void xhci_dbc_stop(struct xhci_dbc *dbc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (ffffffff81cfe950)
Location: drivers/usb/host/xhci-dbgcap.c:629
Inline: True
Direct callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_suspend
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_remove
  - drivers/usb/host/xhci-dbgcap.c:dbc_store
```
**Symbols:**

```
ffffffff81cfe950-ffffffff81cfea05: xhci_dbc_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void xhci_dbc_stop(struct xhci_dbc *dbc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (ffffffff81db4970)
Location: drivers/usb/host/xhci-dbgcap.c:640
Inline: True
Direct callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_suspend
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_remove
  - drivers/usb/host/xhci-dbgcap.c:dbc_store
```
**Symbols:**

```
ffffffff81db4970-ffffffff81db4a25: xhci_dbc_stop (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void xhci_dbc_stop(struct xhci_hcd *xhci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (ffff800010a8a878)
Location: drivers/usb/host/xhci-dbgcap.c:543
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_suspend
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_exit
  - drivers/usb/host/xhci-dbgcap.c:dbc_store
```
**Symbols:**

```
ffff800010a8a878-ffff800010a8aa14: xhci_dbc_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void xhci_dbc_stop(struct xhci_hcd *xhci);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (c0b5d578)
Location: drivers/usb/host/xhci-dbgcap.c:543
Inline: True
Direct callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_suspend
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_exit
  - drivers/usb/host/xhci-dbgcap.c:dbc_store
```
**Symbols:**

```
c0b5d578-c0b5d6d8: xhci_dbc_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void xhci_dbc_stop(struct xhci_hcd *xhci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (c000000000b65e60)
Location: drivers/usb/host/xhci-dbgcap.c:543
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_suspend
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_exit
  - drivers/usb/host/xhci-dbgcap.c:dbc_store
```
**Symbols:**

```
c000000000b65e60-c000000000b66000: xhci_dbc_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void xhci_dbc_stop(struct xhci_hcd *xhci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (ffffffe00069f4c0)
Location: drivers/usb/host/xhci-dbgcap.c:543
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_suspend
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_exit
  - drivers/usb/host/xhci-dbgcap.c:dbc_store
```
**Symbols:**

```
ffffffe00069f4c0-ffffffe00069f61e: xhci_dbc_stop (STB_LOCAL)
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
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void xhci_dbc_stop(struct xhci_hcd *xhci);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (ffffffff817c8a00)
Location: drivers/usb/host/xhci-dbgcap.c:543
Inline: True
Direct callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_suspend
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_exit
  - drivers/usb/host/xhci-dbgcap.c:dbc_store
```
**Symbols:**

```
ffffffff817c8a00-ffffffff817c8b78: xhci_dbc_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void xhci_dbc_stop(struct xhci_hcd *xhci);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (ffffffff81840330)
Location: drivers/usb/host/xhci-dbgcap.c:543
Inline: True
Direct callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_suspend
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_exit
  - drivers/usb/host/xhci-dbgcap.c:dbc_store
```
**Symbols:**

```
ffffffff81840330-ffffffff818404a8: xhci_dbc_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void xhci_dbc_stop(struct xhci_hcd *xhci);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (ffffffff8185a800)
Location: drivers/usb/host/xhci-dbgcap.c:543
Inline: True
Direct callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_suspend
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_exit
  - drivers/usb/host/xhci-dbgcap.c:dbc_store
```
**Symbols:**

```
ffffffff8185a800-ffffffff8185a978: xhci_dbc_stop (STB_LOCAL)
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
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct xhci_dbc *dbc</code>
</li>
<li>
<b>Param removed. </b>
<code>struct xhci_hcd *xhci</code>
</li>
</ul>
</details>
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
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
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
