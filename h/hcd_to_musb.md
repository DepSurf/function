# Function: <code>hcd_to_musb</code>

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
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct musb *hcd_to_musb(struct usb_hcd *hcd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/musb/musb_host.c (c0b6a6e0)
Location: drivers/usb/musb/musb_host.c:73
Inline: True
Inline callers:
  - drivers/usb/musb/musb_host.c:musb_bus_resume
  - drivers/usb/musb/musb_host.c:musb_bus_suspend
  - drivers/usb/musb/musb_host.c:musb_h_stop
  - drivers/usb/musb/musb_host.c:musb_h_start
  - drivers/usb/musb/musb_host.c:musb_h_get_frame_number
  - drivers/usb/musb/musb_host.c:musb_h_disable
  - drivers/usb/musb/musb_host.c:musb_urb_dequeue
  - drivers/usb/musb/musb_host.c:musb_urb_enqueue
Direct callers:
  - drivers/usb/musb/musb_virthub.c:musb_hub_control
  - drivers/usb/musb/musb_virthub.c:musb_hub_status_data
```
**Symbols:**

```
c0b6c090-c0b6c0ac: hcd_to_musb (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
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
<b>Arch</b>
<ul>
</ul>
