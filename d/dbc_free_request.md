# Function: <code>dbc_free_request</code>

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
void dbc_free_request(struct dbc_ep *dep, struct dbc_request *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (ffffffff81773bf0)
Location: drivers/usb/host/xhci-dbgcap.c:209
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_free_requests
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_alloc_requests
```
**Symbols:**

```
ffffffff81773bf0-ffffffff81773c58: dbc_free_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void dbc_free_request(struct dbc_ep *dep, struct dbc_request *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (ffffffff817b4240)
Location: drivers/usb/host/xhci-dbgcap.c:210
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_free_requests
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_alloc_requests
```
**Symbols:**

```
ffffffff817b4240-ffffffff817b42a8: dbc_free_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void dbc_free_request(struct dbc_ep *dep, struct dbc_request *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (ffffffff817da7b0)
Location: drivers/usb/host/xhci-dbgcap.c:210
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_free_requests
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_alloc_requests
```
**Symbols:**

```
ffffffff817da7b0-ffffffff817da818: dbc_free_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void dbc_free_request(struct dbc_ep *dep, struct dbc_request *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (ffffffff8181aee0)
Location: drivers/usb/host/xhci-dbgcap.c:210
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_free_requests
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_alloc_requests
```
**Symbols:**

```
ffffffff8181aee0-ffffffff8181af48: dbc_free_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void dbc_free_request(struct dbc_ep *dep, struct dbc_request *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (ffffffff8184c560)
Location: drivers/usb/host/xhci-dbgcap.c:209
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_free_requests
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_alloc_requests
```
**Symbols:**

```
ffffffff8184c560-ffffffff8184c5c8: dbc_free_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void dbc_free_request(struct dbc_ep *dep, struct dbc_request *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (ffffffff8191f0f0)
Location: drivers/usb/host/xhci-dbgcap.c:209
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_alloc_requests
```
**Symbols:**

```
ffffffff8191f0f0-ffffffff8191f158: dbc_free_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void dbc_free_request(struct dbc_request *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (ffffffff81926880)
Location: drivers/usb/host/xhci-dbgcap.c:215
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_alloc_requests
```
**Symbols:**

```
ffffffff81926880-ffffffff819268da: dbc_free_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void dbc_free_request(struct dbc_request *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (ffffffff81909f60)
Location: drivers/usb/host/xhci-dbgcap.c:215
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_alloc_requests
```
**Symbols:**

```
ffffffff81909f60-ffffffff81909fba: dbc_free_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void dbc_free_request(struct dbc_request *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (ffffffff819aa820)
Location: drivers/usb/host/xhci-dbgcap.c:215
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_alloc_requests
```
**Symbols:**

```
ffffffff819aa820-ffffffff819aa877: dbc_free_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void dbc_free_request(struct dbc_request *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (ffffffff81b088b0)
Location: drivers/usb/host/xhci-dbgcap.c:215
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_alloc_requests
```
**Symbols:**

```
ffffffff81b088b0-ffffffff81b08919: dbc_free_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void dbc_free_request(struct dbc_request *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (ffffffff81c984a0)
Location: drivers/usb/host/xhci-dbgcap.c:215
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_alloc_requests
```
**Symbols:**

```
ffffffff81c984a0-ffffffff81c98509: dbc_free_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void dbc_free_request(struct dbc_request *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (ffffffff81cff810)
Location: drivers/usb/host/xhci-dbgcap.c:215
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_alloc_requests
```
**Symbols:**

```
ffffffff81cff810-ffffffff81cff879: dbc_free_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void dbc_free_request(struct dbc_request *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (ffffffff81db5290)
Location: drivers/usb/host/xhci-dbgcap.c:230
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_alloc_requests
```
**Symbols:**

```
ffffffff81db5290-ffffffff81db52f9: dbc_free_request (STB_GLOBAL)
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
void dbc_free_request(struct dbc_ep *dep, struct dbc_request *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (ffff800010a8b838)
Location: drivers/usb/host/xhci-dbgcap.c:209
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_free_requests
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_alloc_requests
```
**Symbols:**

```
ffff800010a8b838-ffff800010a8b8e0: dbc_free_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void dbc_free_request(struct dbc_ep *dep, struct dbc_request *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (c0b5e9c0)
Location: drivers/usb/host/xhci-dbgcap.c:209
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_free_requests
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_alloc_requests
```
**Symbols:**

```
c0b5e9c0-c0b5ea60: dbc_free_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void dbc_free_request(struct dbc_ep *dep, struct dbc_request *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (c000000000b67770)
Location: drivers/usb/host/xhci-dbgcap.c:209
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_free_requests
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_alloc_requests
```
**Symbols:**

```
c000000000b67770-c000000000b67838: dbc_free_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void dbc_free_request(struct dbc_ep *dep, struct dbc_request *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (ffffffe0006a0608)
Location: drivers/usb/host/xhci-dbgcap.c:209
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_free_requests
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_alloc_requests
```
**Symbols:**

```
ffffffe0006a0608-ffffffe0006a068c: dbc_free_request (STB_GLOBAL)
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
void dbc_free_request(struct dbc_ep *dep, struct dbc_request *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (ffffffff817c9ab0)
Location: drivers/usb/host/xhci-dbgcap.c:209
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_free_requests
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_alloc_requests
```
**Symbols:**

```
ffffffff817c9ab0-ffffffff817c9b18: dbc_free_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void dbc_free_request(struct dbc_ep *dep, struct dbc_request *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (ffffffff818413e0)
Location: drivers/usb/host/xhci-dbgcap.c:209
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_free_requests
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_alloc_requests
```
**Symbols:**

```
ffffffff818413e0-ffffffff81841448: dbc_free_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void dbc_free_request(struct dbc_ep *dep, struct dbc_request *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (ffffffff8185b920)
Location: drivers/usb/host/xhci-dbgcap.c:209
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_free_requests
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_alloc_requests
```
**Symbols:**

```
ffffffff8185b920-ffffffff8185b992: dbc_free_request (STB_GLOBAL)
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
