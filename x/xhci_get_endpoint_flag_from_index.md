# Function: <code>xhci_get_endpoint_flag_from_index</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
unsigned int xhci_get_endpoint_flag_from_index(unsigned int ep_index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff8164ea80)
Location: drivers/usb/host/xhci.c:1178
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring
```
**Symbols:**

```
ffffffff8164ea80-ffffffff8164ea95: xhci_get_endpoint_flag_from_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
unsigned int xhci_get_endpoint_flag_from_index(unsigned int ep_index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff816b273c)
Location: drivers/usb/host/xhci.c:1185
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring
```
**Symbols:**

```
ffffffff816af3d0-ffffffff816af3e5: xhci_get_endpoint_flag_from_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
unsigned int xhci_get_endpoint_flag_from_index(unsigned int ep_index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff816e08ec)
Location: drivers/usb/host/xhci.c:1188
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring
```
**Symbols:**

```
ffffffff816dd570-ffffffff816dd585: xhci_get_endpoint_flag_from_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff816f459a)
Location: drivers/usb/host/xhci.c:1154
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff8176085a)
Location: drivers/usb/host/xhci.c:1160
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring
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
In drivers/usb/host/xhci.c (ffffffff817a125f)
Location: drivers/usb/host/xhci.c:1268
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring
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
In drivers/usb/host/xhci.c (ffffffff817c751f)
Location: drivers/usb/host/xhci.c:1285
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring
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
In drivers/usb/host/xhci.c (ffffffff818068b0)
Location: drivers/usb/host/xhci.c:1307
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring
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
In drivers/usb/host/xhci.c (ffffffff81837760)
Location: drivers/usb/host/xhci.c:1316
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring
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
In drivers/usb/host/xhci.c (ffffffff81903f84)
Location: drivers/usb/host/xhci.c:1318
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_setup_input_ctx_for_quirk
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
In drivers/usb/host/xhci.c (ffffffff8190c5e4)
Location: drivers/usb/host/xhci.c:1455
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_setup_input_ctx_for_quirk
```
</details>
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
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
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffff800010a757c8)
Location: drivers/usb/host/xhci.c:1316
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring
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
In drivers/usb/host/xhci.c (c0b49298)
Location: drivers/usb/host/xhci.c:1316
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring
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
In drivers/usb/host/xhci.c (c000000000b4bb14)
Location: drivers/usb/host/xhci.c:1316
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring
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
In drivers/usb/host/xhci.c (ffffffe00068d83a)
Location: drivers/usb/host/xhci.c:1316
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff817efb10)
Location: drivers/usb/host/xhci.c:1316
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff817b4c20)
Location: drivers/usb/host/xhci.c:1316
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring
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
In drivers/usb/host/xhci.c (ffffffff8182c5e0)
Location: drivers/usb/host/xhci.c:1316
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring
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
In drivers/usb/host/xhci.c (ffffffff818465d0)
Location: drivers/usb/host/xhci.c:1316
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
</ul>
