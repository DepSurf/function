# Function: <code>dbc_ep_queue</code>

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
int dbc_ep_queue(struct dbc_ep *dep, struct dbc_request *req, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (ffffffff81773c60)
Location: drivers/usb/host/xhci-dbgcap.c:328
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgtty.c:dbc_start_rx
  - drivers/usb/host/xhci-dbgtty.c:dbc_start_tx
```
**Symbols:**

```
ffffffff81773c60-ffffffff8177402c: dbc_ep_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int dbc_ep_queue(struct dbc_ep *dep, struct dbc_request *req, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (ffffffff817b42b0)
Location: drivers/usb/host/xhci-dbgcap.c:329
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgtty.c:dbc_start_rx
  - drivers/usb/host/xhci-dbgtty.c:dbc_start_tx
```
**Symbols:**

```
ffffffff817b42b0-ffffffff817b4688: dbc_ep_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int dbc_ep_queue(struct dbc_ep *dep, struct dbc_request *req, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (ffffffff817da820)
Location: drivers/usb/host/xhci-dbgcap.c:329
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgtty.c:dbc_start_rx
  - drivers/usb/host/xhci-dbgtty.c:dbc_start_tx
```
**Symbols:**

```
ffffffff817da820-ffffffff817dabd3: dbc_ep_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int dbc_ep_queue(struct dbc_ep *dep, struct dbc_request *req, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (0)
Location: drivers/usb/host/xhci-dbgcap.c:329
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgtty.c:dbc_start_rx
  - drivers/usb/host/xhci-dbgtty.c:dbc_start_tx
```
**Symbols:**

```
ffffffff8181b7a1-ffffffff8181b818: dbc_ep_queue.cold (STB_LOCAL)
ffffffff8181af50-ffffffff8181b25d: dbc_ep_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int dbc_ep_queue(struct dbc_ep *dep, struct dbc_request *req, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (ffffffff8184c5d0)
Location: drivers/usb/host/xhci-dbgcap.c:328
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgtty.c:dbc_start_rx
  - drivers/usb/host/xhci-dbgtty.c:dbc_start_tx
```
**Symbols:**

```
ffffffff8184c5d0-ffffffff8184c690: dbc_ep_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int dbc_ep_queue(struct dbc_ep *dep, struct dbc_request *req, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (ffffffff8191f160)
Location: drivers/usb/host/xhci-dbgcap.c:328
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgtty.c:dbc_start_rx
```
**Symbols:**

```
ffffffff8191f160-ffffffff8191f220: dbc_ep_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int dbc_ep_queue(struct dbc_request *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (ffffffff819268e0)
Location: drivers/usb/host/xhci-dbgcap.c:332
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgtty.c:dbc_start_rx
```
**Symbols:**

```
ffffffff819268e0-ffffffff819269a7: dbc_ep_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int dbc_ep_queue(struct dbc_request *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (ffffffff81909fc0)
Location: drivers/usb/host/xhci-dbgcap.c:332
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgtty.c:dbc_start_rx
```
**Symbols:**

```
ffffffff81909fc0-ffffffff8190a087: dbc_ep_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int dbc_ep_queue(struct dbc_request *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (ffffffff819aa880)
Location: drivers/usb/host/xhci-dbgcap.c:332
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgtty.c:dbc_start_rx
```
**Symbols:**

```
ffffffff819aa880-ffffffff819aa941: dbc_ep_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int dbc_ep_queue(struct dbc_request *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (ffffffff81b08920)
Location: drivers/usb/host/xhci-dbgcap.c:332
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgtty.c:dbc_start_rx
```
**Symbols:**

```
ffffffff81b08920-ffffffff81b089fd: dbc_ep_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int dbc_ep_queue(struct dbc_request *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (ffffffff81c98520)
Location: drivers/usb/host/xhci-dbgcap.c:332
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgtty.c:dbc_start_rx
```
**Symbols:**

```
ffffffff81c98520-ffffffff81c985fd: dbc_ep_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int dbc_ep_queue(struct dbc_request *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (ffffffff81cff890)
Location: drivers/usb/host/xhci-dbgcap.c:332
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgtty.c:dbc_start_rx
```
**Symbols:**

```
ffffffff81cff890-ffffffff81cff970: dbc_ep_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int dbc_ep_queue(struct dbc_request *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (ffffffff81db5310)
Location: drivers/usb/host/xhci-dbgcap.c:347
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgtty.c:dbc_start_rx
```
**Symbols:**

```
ffffffff81db5310-ffffffff81db53f0: dbc_ep_queue (STB_GLOBAL)
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
int dbc_ep_queue(struct dbc_ep *dep, struct dbc_request *req, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (ffff800010a8b8e0)
Location: drivers/usb/host/xhci-dbgcap.c:328
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgtty.c:dbc_start_rx
  - drivers/usb/host/xhci-dbgtty.c:dbc_start_tx
```
**Symbols:**

```
ffff800010a8b8e0-ffff800010a8bd68: dbc_ep_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int dbc_ep_queue(struct dbc_ep *dep, struct dbc_request *req, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (c0b5ea60)
Location: drivers/usb/host/xhci-dbgcap.c:328
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgtty.c:dbc_start_rx
  - drivers/usb/host/xhci-dbgtty.c:dbc_start_tx
```
**Symbols:**

```
c0b5ea60-c0b5eb5c: dbc_ep_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int dbc_ep_queue(struct dbc_ep *dep, struct dbc_request *req, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (c000000000b67840)
Location: drivers/usb/host/xhci-dbgcap.c:328
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgtty.c:dbc_start_rx
  - drivers/usb/host/xhci-dbgtty.c:dbc_start_tx
```
**Symbols:**

```
c000000000b67840-c000000000b67d58: dbc_ep_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int dbc_ep_queue(struct dbc_ep *dep, struct dbc_request *req, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (ffffffe0006a068c)
Location: drivers/usb/host/xhci-dbgcap.c:328
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgtty.c:dbc_start_rx
  - drivers/usb/host/xhci-dbgtty.c:dbc_start_tx
```
**Symbols:**

```
ffffffe0006a068c-ffffffe0006a0a04: dbc_ep_queue (STB_GLOBAL)
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
int dbc_ep_queue(struct dbc_ep *dep, struct dbc_request *req, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (ffffffff817c9b20)
Location: drivers/usb/host/xhci-dbgcap.c:328
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgtty.c:dbc_start_rx
  - drivers/usb/host/xhci-dbgtty.c:dbc_start_tx
```
**Symbols:**

```
ffffffff817c9b20-ffffffff817c9be0: dbc_ep_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int dbc_ep_queue(struct dbc_ep *dep, struct dbc_request *req, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (ffffffff81841450)
Location: drivers/usb/host/xhci-dbgcap.c:328
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgtty.c:dbc_start_rx
  - drivers/usb/host/xhci-dbgtty.c:dbc_start_tx
```
**Symbols:**

```
ffffffff81841450-ffffffff81841510: dbc_ep_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int dbc_ep_queue(struct dbc_ep *dep, struct dbc_request *req, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (ffffffff8185b9a0)
Location: drivers/usb/host/xhci-dbgcap.c:328
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgtty.c:dbc_start_rx
  - drivers/usb/host/xhci-dbgtty.c:dbc_start_tx
```
**Symbols:**

```
ffffffff8185b9a0-ffffffff8185ba6b: dbc_ep_queue (STB_GLOBAL)
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
<b>Param removed. </b>
<code>struct dbc_ep *dep</code>
</li>
<li>
<b>Param removed. </b>
<code>gfp_t gfp_flags</code>
</li>
<li>
<b>Param reordered. </b>
<code>dep, req, gfp_flags</code> ➡️ <code>req</code>
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
