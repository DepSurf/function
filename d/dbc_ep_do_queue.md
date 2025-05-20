# Function: <code>dbc_ep_do_queue</code>

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
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (ffffffff81773c9f)
Location: drivers/usb/host/xhci-dbgcap.c:289
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (ffffffff817b42f3)
Location: drivers/usb/host/xhci-dbgcap.c:290
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (ffffffff817da863)
Location: drivers/usb/host/xhci-dbgcap.c:290
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (ffffffff8181af85)
Location: drivers/usb/host/xhci-dbgcap.c:290
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int dbc_ep_do_queue(struct dbc_ep *dep, struct dbc_request *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (0)
Location: drivers/usb/host/xhci-dbgcap.c:289
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue
```
**Symbols:**

```
ffffffff8184bc20-ffffffff8184bf15: dbc_ep_do_queue (STB_LOCAL)
ffffffff8184c92b-ffffffff8184c962: dbc_ep_do_queue.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int dbc_ep_do_queue(struct dbc_ep *dep, struct dbc_request *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (0)
Location: drivers/usb/host/xhci-dbgcap.c:289
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue
```
**Symbols:**

```
ffffffff8191ea70-ffffffff8191ec11: dbc_ep_do_queue (STB_LOCAL)
ffffffff8191f4af-ffffffff8191f4e7: dbc_ep_do_queue.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int dbc_ep_do_queue(struct dbc_request *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (0)
Location: drivers/usb/host/xhci-dbgcap.c:295
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue
```
**Symbols:**

```
ffffffff819260d0-ffffffff81926286: dbc_ep_do_queue (STB_LOCAL)
ffffffff81c22674-ffffffff81c226b5: dbc_ep_do_queue.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int dbc_ep_do_queue(struct dbc_request *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (0)
Location: drivers/usb/host/xhci-dbgcap.c:295
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue
```
**Symbols:**

```
ffffffff819097a0-ffffffff81909953: dbc_ep_do_queue (STB_LOCAL)
ffffffff81c1486b-ffffffff81c148ac: dbc_ep_do_queue.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int dbc_ep_do_queue(struct dbc_request *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (0)
Location: drivers/usb/host/xhci-dbgcap.c:295
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue
```
**Symbols:**

```
ffffffff819aa010-ffffffff819aa1d0: dbc_ep_do_queue (STB_LOCAL)
ffffffff81d21d49-ffffffff81d21d9e: dbc_ep_do_queue.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int dbc_ep_do_queue(struct dbc_request *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (0)
Location: drivers/usb/host/xhci-dbgcap.c:295
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue
```
**Symbols:**

```
ffffffff81b08570-ffffffff81b08751: dbc_ep_do_queue (STB_LOCAL)
ffffffff81eedb0e-ffffffff81eedb6b: dbc_ep_do_queue.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int dbc_ep_do_queue(struct dbc_request *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (0)
Location: drivers/usb/host/xhci-dbgcap.c:295
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue
```
**Symbols:**

```
ffffffff81c97ad0-ffffffff81c97cdf: dbc_ep_do_queue (STB_LOCAL)
ffffffff820a5dc7-ffffffff820a5de4: dbc_ep_do_queue.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int dbc_ep_do_queue(struct dbc_request *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (0)
Location: drivers/usb/host/xhci-dbgcap.c:295
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue
```
**Symbols:**

```
ffffffff81cfee00-ffffffff81cff013: dbc_ep_do_queue (STB_LOCAL)
ffffffff82127175-ffffffff8212718a: dbc_ep_do_queue.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int dbc_ep_do_queue(struct dbc_request *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (0)
Location: drivers/usb/host/xhci-dbgcap.c:310
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue
```
**Symbols:**

```
ffffffff81db3f00-ffffffff81db4113: dbc_ep_do_queue (STB_LOCAL)
ffffffff82208acc-ffffffff82208ae1: dbc_ep_do_queue.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (ffff800010a8b944)
Location: drivers/usb/host/xhci-dbgcap.c:289
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int dbc_ep_do_queue(struct dbc_ep *dep, struct dbc_request *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (c0b5dd24)
Location: drivers/usb/host/xhci-dbgcap.c:289
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue
```
**Symbols:**

```
c0b5dd24-c0b5e0c0: dbc_ep_do_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (c000000000b678ac)
Location: drivers/usb/host/xhci-dbgcap.c:289
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (ffffffe0006a06d2)
Location: drivers/usb/host/xhci-dbgcap.c:289
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue
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
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int dbc_ep_do_queue(struct dbc_ep *dep, struct dbc_request *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (0)
Location: drivers/usb/host/xhci-dbgcap.c:289
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue
```
**Symbols:**

```
ffffffff817c9170-ffffffff817c9465: dbc_ep_do_queue (STB_LOCAL)
ffffffff817c9e7b-ffffffff817c9eb2: dbc_ep_do_queue.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int dbc_ep_do_queue(struct dbc_ep *dep, struct dbc_request *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (0)
Location: drivers/usb/host/xhci-dbgcap.c:289
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue
```
**Symbols:**

```
ffffffff81840aa0-ffffffff81840d95: dbc_ep_do_queue (STB_LOCAL)
ffffffff818417ab-ffffffff818417e2: dbc_ep_do_queue.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int dbc_ep_do_queue(struct dbc_ep *dep, struct dbc_request *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (0)
Location: drivers/usb/host/xhci-dbgcap.c:289
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue
```
**Symbols:**

```
ffffffff8185af70-ffffffff8185b281: dbc_ep_do_queue (STB_LOCAL)
ffffffff8185bd0b-ffffffff8185bd42: dbc_ep_do_queue.cold (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct dbc_ep *dep</code>
</li>
<li>
<b>Param reordered. </b>
<code>dep, req</code> ➡️ <code>req</code>
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
No changes between <code>amd64</code> and <code>armhf</code> ✅
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
