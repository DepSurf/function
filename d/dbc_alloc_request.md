# Function: <code>dbc_alloc_request</code>

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
struct dbc_request *dbc_alloc_request(struct dbc_ep *dep, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (ffffffff81773b20)
Location: drivers/usb/host/xhci-dbgcap.c:190
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_alloc_requests
```
**Symbols:**

```
ffffffff81773b20-ffffffff81773be8: dbc_alloc_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct dbc_request *dbc_alloc_request(struct dbc_ep *dep, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (ffffffff817b4170)
Location: drivers/usb/host/xhci-dbgcap.c:191
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_alloc_requests
```
**Symbols:**

```
ffffffff817b4170-ffffffff817b4238: dbc_alloc_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct dbc_request *dbc_alloc_request(struct dbc_ep *dep, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (ffffffff817da6d0)
Location: drivers/usb/host/xhci-dbgcap.c:191
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_alloc_requests
```
**Symbols:**

```
ffffffff817da6d0-ffffffff817da7ac: dbc_alloc_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct dbc_request *dbc_alloc_request(struct dbc_ep *dep, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (ffffffff8181ae00)
Location: drivers/usb/host/xhci-dbgcap.c:191
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_alloc_requests
```
**Symbols:**

```
ffffffff8181ae00-ffffffff8181aedd: dbc_alloc_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct dbc_request *dbc_alloc_request(struct dbc_ep *dep, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (ffffffff8184c480)
Location: drivers/usb/host/xhci-dbgcap.c:190
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_alloc_requests
```
**Symbols:**

```
ffffffff8184c480-ffffffff8184c55d: dbc_alloc_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct dbc_request *dbc_alloc_request(struct dbc_ep *dep, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (ffffffff8191f010)
Location: drivers/usb/host/xhci-dbgcap.c:190
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_alloc_requests
```
**Symbols:**

```
ffffffff8191f010-ffffffff8191f0ed: dbc_alloc_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct dbc_request *dbc_alloc_request(struct xhci_dbc *dbc, unsigned int direction, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (ffffffff81926790)
Location: drivers/usb/host/xhci-dbgcap.c:189
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_alloc_requests
```
**Symbols:**

```
ffffffff81926790-ffffffff8192687a: dbc_alloc_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct dbc_request *dbc_alloc_request(struct xhci_dbc *dbc, unsigned int direction, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (ffffffff81909e70)
Location: drivers/usb/host/xhci-dbgcap.c:189
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_alloc_requests
```
**Symbols:**

```
ffffffff81909e70-ffffffff81909f5a: dbc_alloc_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct dbc_request *dbc_alloc_request(struct xhci_dbc *dbc, unsigned int direction, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (ffffffff819aa6e0)
Location: drivers/usb/host/xhci-dbgcap.c:189
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_alloc_requests
```
**Symbols:**

```
ffffffff819aa6e0-ffffffff819aa817: dbc_alloc_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct dbc_request *dbc_alloc_request(struct xhci_dbc *dbc, unsigned int direction, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (ffffffff81b08760)
Location: drivers/usb/host/xhci-dbgcap.c:189
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_alloc_requests
```
**Symbols:**

```
ffffffff81b08760-ffffffff81b088ac: dbc_alloc_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct dbc_request *dbc_alloc_request(struct xhci_dbc *dbc, unsigned int direction, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (ffffffff81c98340)
Location: drivers/usb/host/xhci-dbgcap.c:189
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_alloc_requests
```
**Symbols:**

```
ffffffff81c98340-ffffffff81c9848d: dbc_alloc_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct dbc_request *dbc_alloc_request(struct xhci_dbc *dbc, unsigned int direction, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (ffffffff81cff6b0)
Location: drivers/usb/host/xhci-dbgcap.c:189
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_alloc_requests
```
**Symbols:**

```
ffffffff81cff6b0-ffffffff81cff7fe: dbc_alloc_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct dbc_request *dbc_alloc_request(struct xhci_dbc *dbc, unsigned int direction, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (ffffffff81db5110)
Location: drivers/usb/host/xhci-dbgcap.c:204
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_alloc_requests
```
**Symbols:**

```
ffffffff81db5110-ffffffff81db5275: dbc_alloc_request (STB_GLOBAL)
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
struct dbc_request *dbc_alloc_request(struct dbc_ep *dep, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (ffff800010a8b738)
Location: drivers/usb/host/xhci-dbgcap.c:190
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_alloc_requests
```
**Symbols:**

```
ffff800010a8b738-ffff800010a8b834: dbc_alloc_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct dbc_request *dbc_alloc_request(struct dbc_ep *dep, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (c0b5e8cc)
Location: drivers/usb/host/xhci-dbgcap.c:190
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_alloc_requests
```
**Symbols:**

```
c0b5e8cc-c0b5e9c0: dbc_alloc_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct dbc_request *dbc_alloc_request(struct dbc_ep *dep, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (c000000000b67640)
Location: drivers/usb/host/xhci-dbgcap.c:190
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_alloc_requests
```
**Symbols:**

```
c000000000b67640-c000000000b67770: dbc_alloc_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct dbc_request *dbc_alloc_request(struct dbc_ep *dep, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (ffffffe0006a0534)
Location: drivers/usb/host/xhci-dbgcap.c:190
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_alloc_requests
```
**Symbols:**

```
ffffffe0006a0534-ffffffe0006a0608: dbc_alloc_request (STB_GLOBAL)
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
struct dbc_request *dbc_alloc_request(struct dbc_ep *dep, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (ffffffff817c99d0)
Location: drivers/usb/host/xhci-dbgcap.c:190
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_alloc_requests
```
**Symbols:**

```
ffffffff817c99d0-ffffffff817c9aad: dbc_alloc_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct dbc_request *dbc_alloc_request(struct dbc_ep *dep, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (ffffffff81841300)
Location: drivers/usb/host/xhci-dbgcap.c:190
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_alloc_requests
```
**Symbols:**

```
ffffffff81841300-ffffffff818413dd: dbc_alloc_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct dbc_request *dbc_alloc_request(struct dbc_ep *dep, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (ffffffff8185b830)
Location: drivers/usb/host/xhci-dbgcap.c:190
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_alloc_requests
```
**Symbols:**

```
ffffffff8185b830-ffffffff8185b91c: dbc_alloc_request (STB_GLOBAL)
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
<b>Param added. </b>
<code>unsigned int direction</code>
</li>
<li>
<b>Param added. </b>
<code>gfp_t flags</code>
</li>
<li>
<b>Param removed. </b>
<code>struct dbc_ep *dep</code>
</li>
<li>
<b>Param removed. </b>
<code>gfp_t gfp_flags</code>
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
