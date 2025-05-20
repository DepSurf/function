# Function: <code>xhci_dbc_queue_trb</code>

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
In drivers/usb/host/xhci-dbgcap.c (ffffffff81773df2)
Location: drivers/usb/host/xhci-dbgcap.c:217
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
In drivers/usb/host/xhci-dbgcap.c (ffffffff817b4441)
Location: drivers/usb/host/xhci-dbgcap.c:218
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
In drivers/usb/host/xhci-dbgcap.c (ffffffff817da985)
Location: drivers/usb/host/xhci-dbgcap.c:218
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
In drivers/usb/host/xhci-dbgcap.c (ffffffff8181b0c3)
Location: drivers/usb/host/xhci-dbgcap.c:218
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue
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
In drivers/usb/host/xhci-dbgcap.c (ffffffff8184bdc1)
Location: drivers/usb/host/xhci-dbgcap.c:217
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void xhci_dbc_queue_trb(struct xhci_ring *ring, u32 field1, u32 field2, u32 field3, u32 field4);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (ffffffff8191e8c0)
Location: drivers/usb/host/xhci-dbgcap.c:217
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_queue_bulk_tx
```
**Symbols:**

```
ffffffff8191e8c0-ffffffff8191e96e: xhci_dbc_queue_trb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void xhci_dbc_queue_trb(struct xhci_ring *ring, u32 field1, u32 field2, u32 field3, u32 field4);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (ffffffff81925f30)
Location: drivers/usb/host/xhci-dbgcap.c:223
Inline: False
Direct callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_queue_bulk_tx
```
**Symbols:**

```
ffffffff81925f30-ffffffff81925fc1: xhci_dbc_queue_trb (STB_LOCAL)
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
In drivers/usb/host/xhci-dbgcap.c (ffffffff819096b8)
Location: drivers/usb/host/xhci-dbgcap.c:223
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_queue_bulk_tx
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
In drivers/usb/host/xhci-dbgcap.c (ffffffff819a9f38)
Location: drivers/usb/host/xhci-dbgcap.c:223
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_queue_bulk_tx
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
In drivers/usb/host/xhci-dbgcap.c (ffffffff81b0845c)
Location: drivers/usb/host/xhci-dbgcap.c:223
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_queue_bulk_tx
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
In drivers/usb/host/xhci-dbgcap.c (ffffffff81c979bc)
Location: drivers/usb/host/xhci-dbgcap.c:223
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_queue_bulk_tx
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
In drivers/usb/host/xhci-dbgcap.c (ffffffff81cfecec)
Location: drivers/usb/host/xhci-dbgcap.c:223
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_queue_bulk_tx
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
In drivers/usb/host/xhci-dbgcap.c (ffffffff81db3dec)
Location: drivers/usb/host/xhci-dbgcap.c:238
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_dbc_queue_bulk_tx
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
In drivers/usb/host/xhci-dbgcap.c (ffff800010a8ba3c)
Location: drivers/usb/host/xhci-dbgcap.c:217
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_queue
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
In drivers/usb/host/xhci-dbgcap.c (c0b5deac)
Location: drivers/usb/host/xhci-dbgcap.c:217
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue
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
In drivers/usb/host/xhci-dbgcap.c (c000000000b679d4)
Location: drivers/usb/host/xhci-dbgcap.c:217
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
In drivers/usb/host/xhci-dbgcap.c (ffffffe0006a0794)
Location: drivers/usb/host/xhci-dbgcap.c:217
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
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbgcap.c (ffffffff817c9311)
Location: drivers/usb/host/xhci-dbgcap.c:217
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue
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
In drivers/usb/host/xhci-dbgcap.c (ffffffff81840c41)
Location: drivers/usb/host/xhci-dbgcap.c:217
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue
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
In drivers/usb/host/xhci-dbgcap.c (ffffffff8185b111)
Location: drivers/usb/host/xhci-dbgcap.c:217
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:dbc_ep_do_queue
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
