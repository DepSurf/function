# Function: <code>musb_g_giveback</code>

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
<summary>In <code>armhf</code>: ✅</summary>

```c
void musb_g_giveback(struct musb_ep *ep, struct usb_request *request, int status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/musb/musb_gadget.c (c0b6fb08)
Location: drivers/usb/musb/musb_gadget.c:122
Inline: False
Direct callers:
  - drivers/usb/musb/musb_gadget_ep0.c:musb_g_ep0_queue
  - drivers/usb/musb/musb_gadget_ep0.c:musb_g_ep0_irq
  - drivers/usb/musb/musb_gadget_ep0.c:musb_g_ep0_irq
  - drivers/usb/musb/musb_gadget_ep0.c:musb_g_ep0_irq
  - drivers/usb/musb/musb_gadget_ep0.c:ep0_txstate
  - drivers/usb/musb/musb_gadget.c:musb_gadget_dequeue
  - drivers/usb/musb/musb_gadget.c:musb_gadget_disable
  - drivers/usb/musb/musb_gadget.c:rxstate
  - drivers/usb/musb/musb_gadget.c:musb_g_tx
```
**Symbols:**

```
c0b6fb08-c0b6fc10: musb_g_giveback (STB_GLOBAL)
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
