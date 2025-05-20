# Function: <code>xhci_dbc_free_req</code>

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
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void xhci_dbc_free_req(struct dbc_ep *dep, struct dbc_request *req);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgtty.c (ffffffff81774415)
Location: drivers/usb/host/xhci-dbgtty.c:125
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_free_requests
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_alloc_requests
```
**Symbols:**

```
ffffffff81774c40-ffffffff81774c6a: xhci_dbc_free_req (STB_GLOBAL)
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
In drivers/usb/host/xhci-dbgtty.c (ffffffff817b4e30)
Location: drivers/usb/host/xhci-dbgtty.c:128
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_free_requests
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_alloc_requests
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
In drivers/usb/host/xhci-dbgtty.c (ffffffff817db380)
Location: drivers/usb/host/xhci-dbgtty.c:128
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_free_requests
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_alloc_requests
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
In drivers/usb/host/xhci-dbgtty.c (ffffffff8181bd90)
Location: drivers/usb/host/xhci-dbgtty.c:128
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_free_requests
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_alloc_requests
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgtty.c (ffffffff8184d150)
Location: drivers/usb/host/xhci-dbgtty.c:128
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_free_requests
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
In drivers/usb/host/xhci-dbgtty.c (ffffffff8192040d)
Location: drivers/usb/host/xhci-dbgtty.c:128
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device
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
In drivers/usb/host/xhci-dbgtty.c (ffffffff819277db)
Location: drivers/usb/host/xhci-dbgtty.c:136
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device
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
In drivers/usb/host/xhci-dbgtty.c (ffffffff8190adab)
Location: drivers/usb/host/xhci-dbgtty.c:136
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_unregister_device
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
In drivers/usb/host/xhci-dbgtty.c (ffffffff819ab467)
Location: drivers/usb/host/xhci-dbgtty.c:136
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
In drivers/usb/host/xhci-dbgtty.c (ffffffff81b097a3)
Location: drivers/usb/host/xhci-dbgtty.c:136
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
In drivers/usb/host/xhci-dbgtty.c (ffffffff81c99573)
Location: drivers/usb/host/xhci-dbgtty.c:136
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
In drivers/usb/host/xhci-dbgtty.c (ffffffff81d00923)
Location: drivers/usb/host/xhci-dbgtty.c:136
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
In drivers/usb/host/xhci-dbgtty.c (ffffffff81db6423)
Location: drivers/usb/host/xhci-dbgtty.c:136
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
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgtty.c (ffff800010a8c3b0)
Location: drivers/usb/host/xhci-dbgtty.c:128
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_free_requests
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgtty.c (c0b5f600)
Location: drivers/usb/host/xhci-dbgtty.c:128
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_free_requests
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
In drivers/usb/host/xhci-dbgtty.c (c000000000b68ba0)
Location: drivers/usb/host/xhci-dbgtty.c:128
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_free_requests
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
In drivers/usb/host/xhci-dbgtty.c (ffffffe0006a139a)
Location: drivers/usb/host/xhci-dbgtty.c:128
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_free_requests
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
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgtty.c (ffffffff817ca6a0)
Location: drivers/usb/host/xhci-dbgtty.c:128
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_free_requests
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgtty.c (ffffffff81841fd0)
Location: drivers/usb/host/xhci-dbgtty.c:128
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_free_requests
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgtty.c (ffffffff8185c850)
Location: drivers/usb/host/xhci-dbgtty.c:128
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_free_requests
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
