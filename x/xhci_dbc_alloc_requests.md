# Function: <code>xhci_dbc_alloc_requests</code>

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
int xhci_dbc_alloc_requests(struct dbc_ep *dep, struct list_head *head, void (*fn)(struct xhci_hcd *, struct dbc_request *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgtty.c (ffffffff81774a60)
Location: drivers/usb/host/xhci-dbgtty.c:132
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device
```
**Symbols:**

```
ffffffff81774a60-ffffffff81774b11: xhci_dbc_alloc_requests (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int xhci_dbc_alloc_requests(struct dbc_ep *dep, struct list_head *head, void (*fn)(struct xhci_hcd *, struct dbc_request *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgtty.c (ffffffff817b4d20)
Location: drivers/usb/host/xhci-dbgtty.c:135
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device
```
**Symbols:**

```
ffffffff817b4d20-ffffffff817b4dd1: xhci_dbc_alloc_requests (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int xhci_dbc_alloc_requests(struct dbc_ep *dep, struct list_head *head, void (*fn)(struct xhci_hcd *, struct dbc_request *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgtty.c (ffffffff817db270)
Location: drivers/usb/host/xhci-dbgtty.c:135
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device
```
**Symbols:**

```
ffffffff817db270-ffffffff817db321: xhci_dbc_alloc_requests (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int xhci_dbc_alloc_requests(struct dbc_ep *dep, struct list_head *head, void (*fn)(struct xhci_hcd *, struct dbc_request *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgtty.c (ffffffff8181bc80)
Location: drivers/usb/host/xhci-dbgtty.c:135
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device
```
**Symbols:**

```
ffffffff8181bc80-ffffffff8181bd33: xhci_dbc_alloc_requests (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int xhci_dbc_alloc_requests(struct dbc_ep *dep, struct list_head *head, void (*fn)(struct xhci_hcd *, struct dbc_request *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgtty.c (ffffffff8184d050)
Location: drivers/usb/host/xhci-dbgtty.c:135
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device
```
**Symbols:**

```
ffffffff8184d050-ffffffff8184d0fc: xhci_dbc_alloc_requests (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int xhci_dbc_alloc_requests(struct dbc_ep *dep, struct list_head *head, void (*fn)(struct xhci_hcd *, struct dbc_request *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgtty.c (ffffffff8191f840)
Location: drivers/usb/host/xhci-dbgtty.c:135
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device
```
**Symbols:**

```
ffffffff8191f840-ffffffff8191f8ec: xhci_dbc_alloc_requests (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int xhci_dbc_alloc_requests(struct xhci_dbc *dbc, unsigned int direction, struct list_head *head, void (*fn)(struct xhci_dbc *, struct dbc_request *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgtty.c (ffffffff81926ce0)
Location: drivers/usb/host/xhci-dbgtty.c:143
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device
```
**Symbols:**

```
ffffffff81926ce0-ffffffff81926d97: xhci_dbc_alloc_requests (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int xhci_dbc_alloc_requests(struct xhci_dbc *dbc, unsigned int direction, struct list_head *head, void (*fn)(struct xhci_dbc *, struct dbc_request *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgtty.c (ffffffff8190a3c0)
Location: drivers/usb/host/xhci-dbgtty.c:143
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device
```
**Symbols:**

```
ffffffff8190a3c0-ffffffff8190a477: xhci_dbc_alloc_requests (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int xhci_dbc_alloc_requests(struct xhci_dbc *dbc, unsigned int direction, struct list_head *head, void (*fn)(struct xhci_dbc *, struct dbc_request *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgtty.c (ffffffff819aac10)
Location: drivers/usb/host/xhci-dbgtty.c:143
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device
```
**Symbols:**

```
ffffffff819aac10-ffffffff819aacc7: xhci_dbc_alloc_requests (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int xhci_dbc_alloc_requests(struct xhci_dbc *dbc, unsigned int direction, struct list_head *head, void (*fn)(struct xhci_dbc *, struct dbc_request *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgtty.c (ffffffff81b09170)
Location: drivers/usb/host/xhci-dbgtty.c:143
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device
```
**Symbols:**

```
ffffffff81b09170-ffffffff81b0922f: xhci_dbc_alloc_requests (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int xhci_dbc_alloc_requests(struct xhci_dbc *dbc, unsigned int direction, struct list_head *head, void (*fn)(struct xhci_dbc *, struct dbc_request *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgtty.c (ffffffff81c98e90)
Location: drivers/usb/host/xhci-dbgtty.c:143
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device
```
**Symbols:**

```
ffffffff81c98e90-ffffffff81c98f4f: xhci_dbc_alloc_requests (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int xhci_dbc_alloc_requests(struct xhci_dbc *dbc, unsigned int direction, struct list_head *head, void (*fn)(struct xhci_dbc *, struct dbc_request *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgtty.c (ffffffff81d00240)
Location: drivers/usb/host/xhci-dbgtty.c:143
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device
```
**Symbols:**

```
ffffffff81d00240-ffffffff81d002ff: xhci_dbc_alloc_requests (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int xhci_dbc_alloc_requests(struct xhci_dbc *dbc, unsigned int direction, struct list_head *head, void (*fn)(struct xhci_dbc *, struct dbc_request *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgtty.c (ffffffff81db5cf0)
Location: drivers/usb/host/xhci-dbgtty.c:143
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device
```
**Symbols:**

```
ffffffff81db5cf0-ffffffff81db5de4: xhci_dbc_alloc_requests (STB_LOCAL)
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
int xhci_dbc_alloc_requests(struct dbc_ep *dep, struct list_head *head, void (*fn)(struct xhci_hcd *, struct dbc_request *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgtty.c (ffff800010a8c290)
Location: drivers/usb/host/xhci-dbgtty.c:135
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device
```
**Symbols:**

```
ffff800010a8c290-ffff800010a8c358: xhci_dbc_alloc_requests (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int xhci_dbc_alloc_requests(struct dbc_ep *dep, struct list_head *head, void (*fn)(struct xhci_hcd *, struct dbc_request *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgtty.c (c0b5f504)
Location: drivers/usb/host/xhci-dbgtty.c:135
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device
```
**Symbols:**

```
c0b5f504-c0b5f5b0: xhci_dbc_alloc_requests (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int xhci_dbc_alloc_requests(struct dbc_ep *dep, struct list_head *head, void (*fn)(struct xhci_hcd *, struct dbc_request *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgtty.c (c000000000b68a00)
Location: drivers/usb/host/xhci-dbgtty.c:135
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device
```
**Symbols:**

```
c000000000b68a00-c000000000b68b10: xhci_dbc_alloc_requests (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int xhci_dbc_alloc_requests(struct dbc_ep *dep, struct list_head *head, void (*fn)(struct xhci_hcd *, struct dbc_request *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgtty.c (ffffffe0006a12a6)
Location: drivers/usb/host/xhci-dbgtty.c:135
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device
```
**Symbols:**

```
ffffffe0006a12a6-ffffffe0006a135e: xhci_dbc_alloc_requests (STB_LOCAL)
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
int xhci_dbc_alloc_requests(struct dbc_ep *dep, struct list_head *head, void (*fn)(struct xhci_hcd *, struct dbc_request *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgtty.c (ffffffff817ca5a0)
Location: drivers/usb/host/xhci-dbgtty.c:135
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device
```
**Symbols:**

```
ffffffff817ca5a0-ffffffff817ca64c: xhci_dbc_alloc_requests (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int xhci_dbc_alloc_requests(struct dbc_ep *dep, struct list_head *head, void (*fn)(struct xhci_hcd *, struct dbc_request *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgtty.c (ffffffff81841ed0)
Location: drivers/usb/host/xhci-dbgtty.c:135
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device
```
**Symbols:**

```
ffffffff81841ed0-ffffffff81841f7c: xhci_dbc_alloc_requests (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int xhci_dbc_alloc_requests(struct dbc_ep *dep, struct list_head *head, void (*fn)(struct xhci_hcd *, struct dbc_request *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgtty.c (ffffffff8185c750)
Location: drivers/usb/host/xhci-dbgtty.c:135
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device
```
**Symbols:**

```
ffffffff8185c750-ffffffff8185c7fc: xhci_dbc_alloc_requests (STB_LOCAL)
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
<b>Param removed. </b>
<code>struct dbc_ep *dep</code>
</li>
<li>
<b>Param reordered. </b>
<code>dep, head, fn</code> ➡️ <code>dbc, direction, head, fn</code>
</li>
<li>
<b>Param type changed. </b>
<code>void (*fn)(struct xhci_hcd *, struct dbc_request *)</code> ➡️ <code>void (*fn)(struct xhci_dbc *, struct dbc_request *)</code>
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
