# Function: <code>__put_unaligned_cpu16</code>

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
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
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
In <code>arm64</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/zstd/huf_decompress.c (0)
Location: include/linux/unaligned/packed_struct.h:28
Inline: True
```
```
In drivers/net/slip/slhc.c (c0ae129c)
Location: include/linux/unaligned/packed_struct.h:28
Inline: True
```
```
In drivers/usb/host/xhci-hub.c (c0b57ea0)
Location: include/linux/unaligned/packed_struct.h:28
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
```
```
In net/core/netpoll.c (c0d2947c)
Location: include/linux/unaligned/packed_struct.h:28
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
```
</details>
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/zstd/huf_decompress.c (0)
Location: include/linux/unaligned/packed_struct.h:28
Inline: True
```
```
In drivers/net/slip/slhc.c (ffffffe0006303e8)
Location: include/linux/unaligned/packed_struct.h:28
Inline: True
```
```
In drivers/usb/host/xhci-hub.c (ffffffe00069a974)
Location: include/linux/unaligned/packed_struct.h:28
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
  - drivers/usb/host/xhci-hub.c:xhci_hub_control
```
```
In net/core/netpoll.c (ffffffe00078d918)
Location: include/linux/unaligned/packed_struct.h:28
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
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
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
