# Function: <code>xhci_dbc_free_requests</code>

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
void xhci_dbc_free_requests(struct dbc_ep *dep, struct list_head *head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgtty.c (ffffffff817743d0)
Location: drivers/usb/host/xhci-dbgtty.c:158
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device
```
**Symbols:**

```
ffffffff817743d0-ffffffff81774446: xhci_dbc_free_requests (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void xhci_dbc_free_requests(struct dbc_ep *dep, struct list_head *head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgtty.c (ffffffff817b4de0)
Location: drivers/usb/host/xhci-dbgtty.c:161
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device
```
**Symbols:**

```
ffffffff817b4de0-ffffffff817b4e55: xhci_dbc_free_requests (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void xhci_dbc_free_requests(struct dbc_ep *dep, struct list_head *head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgtty.c (ffffffff817db330)
Location: drivers/usb/host/xhci-dbgtty.c:161
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device
```
**Symbols:**

```
ffffffff817db330-ffffffff817db3a5: xhci_dbc_free_requests (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void xhci_dbc_free_requests(struct dbc_ep *dep, struct list_head *head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgtty.c (ffffffff8181bd40)
Location: drivers/usb/host/xhci-dbgtty.c:161
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device
```
**Symbols:**

```
ffffffff8181bd40-ffffffff8181bdb5: xhci_dbc_free_requests (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void xhci_dbc_free_requests(struct dbc_ep *dep, struct list_head *head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgtty.c (ffffffff8184d100)
Location: drivers/usb/host/xhci-dbgtty.c:161
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device
```
**Symbols:**

```
ffffffff8184d100-ffffffff8184d175: xhci_dbc_free_requests (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void xhci_dbc_free_requests(struct dbc_ep *dep, struct list_head *head);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgtty.c (ffffffff819203d2)
Location: drivers/usb/host/xhci-dbgtty.c:161
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device
Direct callers:
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device
```
**Symbols:**

```
ffffffff8191f8f0-ffffffff8191f965: xhci_dbc_free_requests (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void xhci_dbc_free_requests(struct list_head *head);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgtty.c (ffffffff8192779b)
Location: drivers/usb/host/xhci-dbgtty.c:170
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device
Direct callers:
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device
```
**Symbols:**

```
ffffffff81926c70-ffffffff81926cdd: xhci_dbc_free_requests (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void xhci_dbc_free_requests(struct list_head *head);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgtty.c (ffffffff8190ad6b)
Location: drivers/usb/host/xhci-dbgtty.c:170
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device
Direct callers:
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device
```
**Symbols:**

```
ffffffff8190a350-ffffffff8190a3bd: xhci_dbc_free_requests (STB_LOCAL)
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
In drivers/usb/host/xhci-dbgtty.c (ffffffff819ab427)
Location: drivers/usb/host/xhci-dbgtty.c:170
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgtty.c (ffffffff81b09763)
Location: drivers/usb/host/xhci-dbgtty.c:170
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device
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
In drivers/usb/host/xhci-dbgtty.c (ffffffff81c99533)
Location: drivers/usb/host/xhci-dbgtty.c:170
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device
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
In drivers/usb/host/xhci-dbgtty.c (ffffffff81d008e3)
Location: drivers/usb/host/xhci-dbgtty.c:170
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device
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
In drivers/usb/host/xhci-dbgtty.c (ffffffff81db63e3)
Location: drivers/usb/host/xhci-dbgtty.c:170
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device
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
void xhci_dbc_free_requests(struct dbc_ep *dep, struct list_head *head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgtty.c (ffff800010a8c358)
Location: drivers/usb/host/xhci-dbgtty.c:161
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device
```
**Symbols:**

```
ffff800010a8c358-ffff800010a8c3e4: xhci_dbc_free_requests (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void xhci_dbc_free_requests(struct dbc_ep *dep, struct list_head *head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgtty.c (c0b5f5b0)
Location: drivers/usb/host/xhci-dbgtty.c:161
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device
```
**Symbols:**

```
c0b5f5b0-c0b5f624: xhci_dbc_free_requests (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void xhci_dbc_free_requests(struct dbc_ep *dep, struct list_head *head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgtty.c (c000000000b68b10)
Location: drivers/usb/host/xhci-dbgtty.c:161
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device
```
**Symbols:**

```
c000000000b68b10-c000000000b68bec: xhci_dbc_free_requests (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void xhci_dbc_free_requests(struct dbc_ep *dep, struct list_head *head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgtty.c (ffffffe0006a135e)
Location: drivers/usb/host/xhci-dbgtty.c:161
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device
```
**Symbols:**

```
ffffffe0006a135e-ffffffe0006a13d6: xhci_dbc_free_requests (STB_LOCAL)
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
void xhci_dbc_free_requests(struct dbc_ep *dep, struct list_head *head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgtty.c (ffffffff817ca650)
Location: drivers/usb/host/xhci-dbgtty.c:161
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device
```
**Symbols:**

```
ffffffff817ca650-ffffffff817ca6c5: xhci_dbc_free_requests (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void xhci_dbc_free_requests(struct dbc_ep *dep, struct list_head *head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgtty.c (ffffffff81841f80)
Location: drivers/usb/host/xhci-dbgtty.c:161
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device
```
**Symbols:**

```
ffffffff81841f80-ffffffff81841ff5: xhci_dbc_free_requests (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void xhci_dbc_free_requests(struct dbc_ep *dep, struct list_head *head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgtty.c (ffffffff8185c800)
Location: drivers/usb/host/xhci-dbgtty.c:161
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_register_device
```
**Symbols:**

```
ffffffff8185c800-ffffffff8185c875: xhci_dbc_free_requests (STB_LOCAL)
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
<code>dep, head</code> ➡️ <code>head</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
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
