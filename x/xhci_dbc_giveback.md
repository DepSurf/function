# Function: <code>xhci_dbc_giveback</code>

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
void xhci_dbc_giveback(struct dbc_request *req, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (ffffffff817733c0)
Location: drivers/usb/host/xhci-dbgcap.c:133
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_handle_events
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_flush_endpoint_requests
```
**Symbols:**

```
ffffffff817733c0-ffffffff817734e3: xhci_dbc_giveback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void xhci_dbc_giveback(struct dbc_request *req, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (ffffffff817b39e0)
Location: drivers/usb/host/xhci-dbgcap.c:134
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_handle_events
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_flush_endpoint_requests
```
**Symbols:**

```
ffffffff817b39e0-ffffffff817b3b0e: xhci_dbc_giveback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void xhci_dbc_giveback(struct dbc_request *req, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (ffffffff817d9f00)
Location: drivers/usb/host/xhci-dbgcap.c:134
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_handle_events
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_flush_endpoint_requests
```
**Symbols:**

```
ffffffff817d9f00-ffffffff817da042: xhci_dbc_giveback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void xhci_dbc_giveback(struct dbc_request *req, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (ffffffff8181a8a0)
Location: drivers/usb/host/xhci-dbgcap.c:134
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_flush_endpoint_requests
```
**Symbols:**

```
ffffffff8181a8a0-ffffffff8181a9d6: xhci_dbc_giveback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void xhci_dbc_giveback(struct dbc_request *req, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (ffffffff8184bf20)
Location: drivers/usb/host/xhci-dbgcap.c:133
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_flush_endpoint_requests
```
**Symbols:**

```
ffffffff8184bf20-ffffffff8184c056: xhci_dbc_giveback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void xhci_dbc_giveback(struct dbc_request *req, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (ffffffff8191e790)
Location: drivers/usb/host/xhci-dbgcap.c:133
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_handle_xfer_event
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_flush_endpoint_requests
```
**Symbols:**

```
ffffffff8191e790-ffffffff8191e8bd: xhci_dbc_giveback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void xhci_dbc_giveback(struct dbc_request *req, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (ffffffff81926290)
Location: drivers/usb/host/xhci-dbgcap.c:134
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_handle_xfer_event
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_flush_endpoint_requests
```
**Symbols:**

```
ffffffff81926290-ffffffff81926358: xhci_dbc_giveback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void xhci_dbc_giveback(struct dbc_request *req, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (ffffffff81909960)
Location: drivers/usb/host/xhci-dbgcap.c:134
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_handle_xfer_event
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_flush_endpoint_requests
```
**Symbols:**

```
ffffffff81909960-ffffffff81909a28: xhci_dbc_giveback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void xhci_dbc_giveback(struct dbc_request *req, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (ffffffff819aa1d0)
Location: drivers/usb/host/xhci-dbgcap.c:134
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_handle_xfer_event
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_flush_endpoint_requests
```
**Symbols:**

```
ffffffff819aa1d0-ffffffff819aa295: xhci_dbc_giveback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void xhci_dbc_giveback(struct dbc_request *req, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (ffffffff81b07e40)
Location: drivers/usb/host/xhci-dbgcap.c:134
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_handle_xfer_event
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_flush_endpoint_requests
```
**Symbols:**

```
ffffffff81b07e40-ffffffff81b07f2c: xhci_dbc_giveback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void xhci_dbc_giveback(struct dbc_request *req, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (ffffffff81c977a0)
Location: drivers/usb/host/xhci-dbgcap.c:134
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_handle_xfer_event
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_flush_endpoint_requests
```
**Symbols:**

```
ffffffff81c977a0-ffffffff81c9788c: xhci_dbc_giveback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void xhci_dbc_giveback(struct dbc_request *req, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (ffffffff81cfead0)
Location: drivers/usb/host/xhci-dbgcap.c:134
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_handle_xfer_event
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_flush_endpoint_requests
```
**Symbols:**

```
ffffffff81cfead0-ffffffff81cfebbc: xhci_dbc_giveback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void xhci_dbc_giveback(struct dbc_request *req, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (ffffffff81db3bd0)
Location: drivers/usb/host/xhci-dbgcap.c:149
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_handle_xfer_event
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_flush_endpoint_requests
```
**Symbols:**

```
ffffffff81db3bd0-ffffffff81db3cbc: xhci_dbc_giveback (STB_LOCAL)
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
void xhci_dbc_giveback(struct dbc_request *req, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (ffff800010a8a648)
Location: drivers/usb/host/xhci-dbgcap.c:133
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_flush_endpoint_requests
```
**Symbols:**

```
ffff800010a8a648-ffff800010a8a7d0: xhci_dbc_giveback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void xhci_dbc_giveback(struct dbc_request *req, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (c0b5e0c0)
Location: drivers/usb/host/xhci-dbgcap.c:133
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_flush_endpoint_requests
```
**Symbols:**

```
c0b5e0c0-c0b5e224: xhci_dbc_giveback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void xhci_dbc_giveback(struct dbc_request *req, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (c000000000b660a0)
Location: drivers/usb/host/xhci-dbgcap.c:133
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_flush_endpoint_requests
```
**Symbols:**

```
c000000000b660a0-c000000000b66284: xhci_dbc_giveback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void xhci_dbc_giveback(struct dbc_request *req, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (ffffffe00069f690)
Location: drivers/usb/host/xhci-dbgcap.c:133
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_flush_endpoint_requests
```
**Symbols:**

```
ffffffe00069f690-ffffffe00069f7d4: xhci_dbc_giveback (STB_LOCAL)
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
void xhci_dbc_giveback(struct dbc_request *req, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (ffffffff817c9470)
Location: drivers/usb/host/xhci-dbgcap.c:133
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_flush_endpoint_requests
```
**Symbols:**

```
ffffffff817c9470-ffffffff817c95a6: xhci_dbc_giveback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void xhci_dbc_giveback(struct dbc_request *req, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (ffffffff81840da0)
Location: drivers/usb/host/xhci-dbgcap.c:133
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_flush_endpoint_requests
```
**Symbols:**

```
ffffffff81840da0-ffffffff81840ed6: xhci_dbc_giveback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void xhci_dbc_giveback(struct dbc_request *req, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (ffffffff8185b290)
Location: drivers/usb/host/xhci-dbgcap.c:133
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_do_handle_events
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_flush_endpoint_requests
```
**Symbols:**

```
ffffffff8185b290-ffffffff8185b3dd: xhci_dbc_giveback (STB_LOCAL)
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
