# Function: <code>xhci_free_erst</code>

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
void xhci_free_erst(struct xhci_hcd *xhci, struct xhci_erst *erst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff817650b0)
Location: drivers/usb/host/xhci-mem.c:1800
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_stop
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start
```
**Symbols:**

```
ffffffff817650b0-ffffffff81765121: xhci_free_erst (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void xhci_free_erst(struct xhci_hcd *xhci, struct xhci_erst *erst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff817a5410)
Location: drivers/usb/host/xhci-mem.c:1821
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_stop
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start
```
**Symbols:**

```
ffffffff817a5410-ffffffff817a5481: xhci_free_erst (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void xhci_free_erst(struct xhci_hcd *xhci, struct xhci_erst *erst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff817cb620)
Location: drivers/usb/host/xhci-mem.c:1821
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_stop
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_start
```
**Symbols:**

```
ffffffff817cb620-ffffffff817cb659: xhci_free_erst (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void xhci_free_erst(struct xhci_hcd *xhci, struct xhci_erst *erst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff8180b9e0)
Location: drivers/usb/host/xhci-mem.c:1821
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_stop
```
**Symbols:**

```
ffffffff8180b9e0-ffffffff8180ba19: xhci_free_erst (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void xhci_free_erst(struct xhci_hcd *xhci, struct xhci_erst *erst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff8183c9a0)
Location: drivers/usb/host/xhci-mem.c:1827
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
```
**Symbols:**

```
ffffffff8183c9a0-ffffffff8183c9d9: xhci_free_erst (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void xhci_free_erst(struct xhci_hcd *xhci, struct xhci_erst *erst);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff8190f460)
Location: drivers/usb/host/xhci-mem.c:1827
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
Direct callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_stop
```
**Symbols:**

```
ffffffff8190f3f0-ffffffff8190f42c: xhci_free_erst (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void xhci_free_erst(struct xhci_hcd *xhci, struct xhci_erst *erst);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff81916fc0)
Location: drivers/usb/host/xhci-mem.c:1835
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
```
**Symbols:**

```
ffffffff81916f50-ffffffff81916f8c: xhci_free_erst (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void xhci_free_erst(struct xhci_hcd *xhci, struct xhci_erst *erst);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff818fa440)
Location: drivers/usb/host/xhci-mem.c:1822
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
```
**Symbols:**

```
ffffffff818fa3d0-ffffffff818fa40c: xhci_free_erst (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void xhci_free_erst(struct xhci_hcd *xhci, struct xhci_erst *erst);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff819991c0)
Location: drivers/usb/host/xhci-mem.c:1822
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
```
**Symbols:**

```
ffffffff81999150-ffffffff8199918c: xhci_free_erst (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void xhci_free_erst(struct xhci_hcd *xhci, struct xhci_erst *erst);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff81af61e4)
Location: drivers/usb/host/xhci-mem.c:1813
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
```
**Symbols:**

```
ffffffff81af6160-ffffffff81af61ad: xhci_free_erst (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void xhci_free_erst(struct xhci_hcd *xhci, struct xhci_erst *erst);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff81c83b74)
Location: drivers/usb/host/xhci-mem.c:1822
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
```
**Symbols:**

```
ffffffff81c83ae0-ffffffff81c83b2d: xhci_free_erst (STB_GLOBAL)
```
</details>
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
void xhci_free_erst(struct xhci_hcd *xhci, struct xhci_erst *erst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffff800010a7a850)
Location: drivers/usb/host/xhci-mem.c:1827
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_stop
```
**Symbols:**

```
ffff800010a7a850-ffff800010a7a8a0: xhci_free_erst (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void xhci_free_erst(struct xhci_hcd *xhci, struct xhci_erst *erst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (c0b4e148)
Location: drivers/usb/host/xhci-mem.c:1827
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
```
**Symbols:**

```
c0b4e148-c0b4e1a0: xhci_free_erst (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void xhci_free_erst(struct xhci_hcd *xhci, struct xhci_erst *erst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (c000000000b52310)
Location: drivers/usb/host/xhci-mem.c:1827
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_stop
```
**Symbols:**

```
c000000000b52310-c000000000b5237c: xhci_free_erst (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void xhci_free_erst(struct xhci_hcd *xhci, struct xhci_erst *erst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffe000691e6e)
Location: drivers/usb/host/xhci-mem.c:1827
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_stop
```
**Symbols:**

```
ffffffe000691e6e-ffffffe000691eb4: xhci_free_erst (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void xhci_free_erst(struct xhci_hcd *xhci, struct xhci_erst *erst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff817f4d50)
Location: drivers/usb/host/xhci-mem.c:1827
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
```
**Symbols:**

```
ffffffff817f4d50-ffffffff817f4d89: xhci_free_erst (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void xhci_free_erst(struct xhci_hcd *xhci, struct xhci_erst *erst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff817b9ef0)
Location: drivers/usb/host/xhci-mem.c:1827
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
```
**Symbols:**

```
ffffffff817b9ef0-ffffffff817b9f29: xhci_free_erst (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void xhci_free_erst(struct xhci_hcd *xhci, struct xhci_erst *erst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff81831820)
Location: drivers/usb/host/xhci-mem.c:1827
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
```
**Symbols:**

```
ffffffff81831820-ffffffff81831859: xhci_free_erst (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void xhci_free_erst(struct xhci_hcd *xhci, struct xhci_erst *erst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff8184ba00)
Location: drivers/usb/host/xhci-mem.c:1827
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_mem_cleanup
```
**Symbols:**

```
ffffffff8184ba00-ffffffff8184ba39: xhci_free_erst (STB_GLOBAL)
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
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
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
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
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
