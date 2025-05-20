# Function: <code>tasklet_schedule</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff8112f98c)
Location: include/linux/interrupt.h:533
Inline: True
```
```
In drivers/tty/vt/keyboard.c (ffffffff814f2420)
Location: include/linux/interrupt.h:533
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:setledstate
  - drivers/tty/vt/keyboard.c:vt_kbd_con_start
  - drivers/tty/vt/keyboard.c:vt_kbd_con_stop
  - drivers/tty/vt/keyboard.c:vt_do_kdskled
Direct callers:
  - drivers/tty/vt/keyboard.c:kbd_init
```
```
In drivers/tty/vt/vt.c (ffffffff814f83e0)
Location: include/linux/interrupt.h:533
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:redraw_screen
```
```
In drivers/usb/core/hcd.c (ffffffff8160cf9a)
Location: include/linux/interrupt.h:533
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
```
```
In net/core/flow.c (ffffffff81734408)
Location: include/linux/interrupt.h:533
Inline: True
Inline callers:
  - net/core/flow.c:flow_cache_flush_per_cpu
```
```
In net/ipv4/tcp_output.c (ffffffff81774a88)
Location: include/linux/interrupt.h:533
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_wfree
```
**Symbols:**

```
ffffffff814f2420-ffffffff814f243e: tasklet_schedule.constprop.20 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff81137c7d)
Location: include/linux/interrupt.h:552
Inline: True
```
```
In drivers/tty/vt/keyboard.c (ffffffff81546277)
Location: include/linux/interrupt.h:552
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:vt_do_kdskled
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:vt_kbd_con_stop
  - drivers/tty/vt/keyboard.c:vt_kbd_con_start
  - drivers/tty/vt/keyboard.c:setledstate
Direct callers:
  - drivers/tty/vt/keyboard.c:kbd_init
```
```
In drivers/tty/vt/vt.c (ffffffff81548a85)
Location: include/linux/interrupt.h:552
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:redraw_screen
```
```
In drivers/usb/core/hcd.c (ffffffff8166cb1f)
Location: include/linux/interrupt.h:552
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
```
```
In net/core/flow.c (ffffffff817a04d8)
Location: include/linux/interrupt.h:552
Inline: True
Inline callers:
  - net/core/flow.c:flow_cache_flush_per_cpu
```
```
In net/ipv4/tcp_output.c (ffffffff817e1a08)
Location: include/linux/interrupt.h:552
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_wfree
```
**Symbols:**

```
ffffffff81543030-ffffffff8154304e: tasklet_schedule.constprop.22 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff81141a0d)
Location: include/linux/interrupt.h:572
Inline: True
```
```
In drivers/tty/vt/keyboard.c (ffffffff815728c7)
Location: include/linux/interrupt.h:572
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:vt_do_kdskled
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:vt_kbd_con_stop
  - drivers/tty/vt/keyboard.c:vt_kbd_con_start
  - drivers/tty/vt/keyboard.c:setledstate
Direct callers:
  - drivers/tty/vt/keyboard.c:kbd_init
```
```
In drivers/tty/vt/vt.c (ffffffff815754e5)
Location: include/linux/interrupt.h:572
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:redraw_screen
```
```
In drivers/usb/core/hcd.c (ffffffff8169a81f)
Location: include/linux/interrupt.h:572
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
```
```
In net/core/flow.c (ffffffff817ceea8)
Location: include/linux/interrupt.h:572
Inline: True
Inline callers:
  - net/core/flow.c:flow_cache_flush_per_cpu
```
```
In net/ipv4/tcp_output.c (ffffffff81811f20)
Location: include/linux/interrupt.h:572
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_wfree
```
**Symbols:**

```
ffffffff8156f670-ffffffff8156f68e: tasklet_schedule.constprop.22 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff8114324d)
Location: include/linux/interrupt.h:581
Inline: True
```
```
In drivers/tty/vt/keyboard.c (ffffffff8158697a)
Location: include/linux/interrupt.h:581
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:vt_do_kdskled
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:vt_kbd_con_stop
  - drivers/tty/vt/keyboard.c:vt_kbd_con_start
  - drivers/tty/vt/keyboard.c:setledstate
Direct callers:
  - drivers/tty/vt/keyboard.c:kbd_init
```
```
In drivers/tty/vt/vt.c (ffffffff81589399)
Location: include/linux/interrupt.h:581
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:redraw_screen
```
```
In drivers/usb/core/hcd.c (ffffffff816afa7e)
Location: include/linux/interrupt.h:581
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
```
```
In net/core/flow.c (ffffffff817ee228)
Location: include/linux/interrupt.h:581
Inline: True
Inline callers:
  - net/core/flow.c:flow_cache_flush_per_cpu
```
```
In net/ipv4/tcp_output.c (ffffffff81832ada)
Location: include/linux/interrupt.h:581
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_pace_kick
  - net/ipv4/tcp_output.c:tcp_wfree
```
**Symbols:**

```
ffffffff81583bf0-ffffffff81583c0f: tasklet_schedule.constprop.20 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff8114ff01)
Location: include/linux/interrupt.h:583
Inline: True
```
```
In drivers/tty/vt/keyboard.c (ffffffff815eb47a)
Location: include/linux/interrupt.h:583
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:vt_do_kdskled
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:vt_kbd_con_stop
  - drivers/tty/vt/keyboard.c:vt_kbd_con_start
  - drivers/tty/vt/keyboard.c:setledstate
Direct callers:
  - drivers/tty/vt/keyboard.c:kbd_init
```
```
In drivers/tty/vt/vt.c (ffffffff815edec9)
Location: include/linux/interrupt.h:583
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:redraw_screen
```
```
In drivers/usb/core/hcd.c (ffffffff8171b0ee)
Location: include/linux/interrupt.h:583
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
```
```
In drivers/usb/host/xhci-dbgtty.c (ffffffff817749c1)
Location: include/linux/interrupt.h:583
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
  - drivers/usb/host/xhci-dbgtty.c:dbc_tty_unthrottle
  - drivers/usb/host/xhci-dbgtty.c:dbc_read_complete
```
```
In net/ipv4/tcp_output.c (ffffffff818b1f0f)
Location: include/linux/interrupt.h:583
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_pace_kick
  - net/ipv4/tcp_output.c:tcp_wfree
```
```
In net/xfrm/xfrm_input.c (ffffffff818feed5)
Location: include/linux/interrupt.h:583
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_queue
```
**Symbols:**

```
ffffffff815e86f0-ffffffff815e870f: tasklet_schedule.constprop.20 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff8115e980)
Location: include/linux/interrupt.h:588
Inline: True
```
```
In drivers/tty/vt/keyboard.c (ffffffff816246a9)
Location: include/linux/interrupt.h:588
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:vt_do_kdskled
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:vt_kbd_con_stop
  - drivers/tty/vt/keyboard.c:vt_kbd_con_start
  - drivers/tty/vt/keyboard.c:setledstate
Direct callers:
  - drivers/tty/vt/keyboard.c:kbd_init
```
```
In drivers/tty/vt/vt.c (ffffffff816273b1)
Location: include/linux/interrupt.h:588
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:redraw_screen
```
```
In drivers/usb/core/hcd.c (ffffffff81759ee2)
Location: include/linux/interrupt.h:588
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
```
```
In drivers/usb/host/xhci-dbgtty.c (ffffffff817b5111)
Location: include/linux/interrupt.h:588
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
  - drivers/usb/host/xhci-dbgtty.c:dbc_tty_unthrottle
  - drivers/usb/host/xhci-dbgtty.c:dbc_read_complete
```
```
In net/ipv4/tcp_output.c (ffffffff81907131)
Location: include/linux/interrupt.h:588
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_wfree
```
```
In net/xfrm/xfrm_input.c (ffffffff81955992)
Location: include/linux/interrupt.h:588
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_queue
```
**Symbols:**

```
ffffffff81621960-ffffffff81621980: tasklet_schedule.constprop.23 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff8116b610)
Location: include/linux/interrupt.h:604
Inline: True
```
```
In drivers/tty/vt/keyboard.c (ffffffff81641b99)
Location: include/linux/interrupt.h:604
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:vt_do_kdskled
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:vt_kbd_con_stop
  - drivers/tty/vt/keyboard.c:vt_kbd_con_start
  - drivers/tty/vt/keyboard.c:setledstate
Direct callers:
  - drivers/tty/vt/keyboard.c:kbd_init
```
```
In drivers/tty/vt/vt.c (ffffffff81644f20)
Location: include/linux/interrupt.h:604
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:redraw_screen
```
```
In drivers/usb/core/hcd.c (ffffffff8177e462)
Location: include/linux/interrupt.h:604
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
```
```
In drivers/usb/host/xhci-dbgtty.c (ffffffff817db661)
Location: include/linux/interrupt.h:604
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
  - drivers/usb/host/xhci-dbgtty.c:dbc_tty_unthrottle
  - drivers/usb/host/xhci-dbgtty.c:dbc_read_complete
```
```
In net/ipv4/tcp_output.c (ffffffff81934d21)
Location: include/linux/interrupt.h:604
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_wfree
```
```
In net/xfrm/xfrm_input.c (ffffffff8198a472)
Location: include/linux/interrupt.h:604
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_queue
```
**Symbols:**

```
ffffffff8163ee40-ffffffff8163ee60: tasklet_schedule.constprop.23 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff811783dc)
Location: include/linux/interrupt.h:633
Inline: True
```
```
In drivers/tty/vt/keyboard.c (ffffffff816760f8)
Location: include/linux/interrupt.h:633
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:vt_do_kdskled
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:vt_kbd_con_stop
  - drivers/tty/vt/keyboard.c:vt_kbd_con_start
  - drivers/tty/vt/keyboard.c:setledstate
Direct callers:
  - drivers/tty/vt/keyboard.c:kbd_init
```
```
In drivers/tty/vt/vt.c (ffffffff81679521)
Location: include/linux/interrupt.h:633
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:redraw_screen
```
```
In drivers/usb/core/hcd.c (ffffffff817bc9e2)
Location: include/linux/interrupt.h:633
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
```
```
In drivers/usb/host/xhci-dbgtty.c (ffffffff8181c075)
Location: include/linux/interrupt.h:633
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
  - drivers/usb/host/xhci-dbgtty.c:dbc_tty_unthrottle
  - drivers/usb/host/xhci-dbgtty.c:dbc_read_complete
```
```
In net/ipv4/tcp_output.c (ffffffff81998af0)
Location: include/linux/interrupt.h:633
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_wfree
```
```
In net/xfrm/xfrm_input.c (ffffffff819f47c6)
Location: include/linux/interrupt.h:633
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_queue
```
**Symbols:**

```
ffffffff81673380-ffffffff8167339f: tasklet_schedule.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff8118425c)
Location: include/linux/interrupt.h:638
Inline: True
```
```
In drivers/tty/vt/keyboard.c (ffffffff81698898)
Location: include/linux/interrupt.h:638
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:vt_do_kdskled
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:vt_kbd_con_stop
  - drivers/tty/vt/keyboard.c:vt_kbd_con_start
  - drivers/tty/vt/keyboard.c:setledstate
Direct callers:
  - drivers/tty/vt/keyboard.c:kbd_init
```
```
In drivers/tty/vt/vt.c (ffffffff8169bd01)
Location: include/linux/interrupt.h:638
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:redraw_screen
```
```
In drivers/usb/core/hcd.c (ffffffff817ed202)
Location: include/linux/interrupt.h:638
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
```
```
In drivers/usb/host/xhci-dbgtty.c (ffffffff8184d435)
Location: include/linux/interrupt.h:638
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
  - drivers/usb/host/xhci-dbgtty.c:dbc_tty_unthrottle
  - drivers/usb/host/xhci-dbgtty.c:dbc_read_complete
```
```
In net/ipv4/tcp_output.c (ffffffff819cf60f)
Location: include/linux/interrupt.h:638
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_wfree
```
```
In net/xfrm/xfrm_input.c (ffffffff81a2b476)
Location: include/linux/interrupt.h:638
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_queue
```
**Symbols:**

```
ffffffff81695ae0-ffffffff81695aff: tasklet_schedule.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/irq/resend.c (ffffffff811261c9)
Location: include/linux/interrupt.h:652
Inline: True
Inline callers:
  - kernel/irq/resend.c:check_irq_resend
```
```
In kernel/debug/debug_core.c (ffffffff811982dc)
Location: include/linux/interrupt.h:652
Inline: True
```
```
In drivers/tty/vt/keyboard.c (ffffffff8174ac08)
Location: include/linux/interrupt.h:652
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:vt_do_kdskled
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:vt_kbd_con_stop
  - drivers/tty/vt/keyboard.c:vt_kbd_con_start
  - drivers/tty/vt/keyboard.c:vt_set_led_state
Direct callers:
  - drivers/tty/vt/keyboard.c:kbd_init
```
```
In drivers/tty/vt/vt.c (ffffffff8174eecf)
Location: include/linux/interrupt.h:652
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:redraw_screen
```
```
In drivers/usb/core/hcd.c (ffffffff818bca22)
Location: include/linux/interrupt.h:652
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
```
```
In drivers/usb/host/xhci-dbgtty.c (ffffffff8191fed5)
Location: include/linux/interrupt.h:652
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
  - drivers/usb/host/xhci-dbgtty.c:dbc_tty_unthrottle
  - drivers/usb/host/xhci-dbgtty.c:dbc_read_complete
```
```
In net/ipv4/tcp_output.c (ffffffff81abb862)
Location: include/linux/interrupt.h:652
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_wfree
```
```
In net/xfrm/xfrm_input.c (ffffffff81b1d945)
Location: include/linux/interrupt.h:652
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_queue
```
**Symbols:**

```
ffffffff81748340-ffffffff8174835f: tasklet_schedule.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/irq/resend.c (ffffffff81121db9)
Location: include/linux/interrupt.h:690
Inline: True
Inline callers:
  - kernel/irq/resend.c:check_irq_resend
```
```
In kernel/debug/debug_core.c (ffffffff811956bc)
Location: include/linux/interrupt.h:690
Inline: True
```
```
In drivers/tty/vt/keyboard.c (ffffffff81766378)
Location: include/linux/interrupt.h:690
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:vt_do_kdskled
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:vt_kbd_con_stop
  - drivers/tty/vt/keyboard.c:vt_kbd_con_start
  - drivers/tty/vt/keyboard.c:vt_set_led_state
Direct callers:
  - drivers/tty/vt/keyboard.c:kbd_init
```
```
In drivers/tty/vt/vt.c (ffffffff8176a851)
Location: include/linux/interrupt.h:690
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:redraw_screen
```
```
In drivers/usb/core/hcd.c (ffffffff818c9732)
Location: include/linux/interrupt.h:690
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
```
```
In drivers/usb/host/xhci-dbgtty.c (ffffffff819275d8)
Location: include/linux/interrupt.h:690
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
  - drivers/usb/host/xhci-dbgtty.c:dbc_tty_unthrottle
  - drivers/usb/host/xhci-dbgtty.c:dbc_read_complete
```
```
In net/ipv4/tcp_output.c (ffffffff81ac7442)
Location: include/linux/interrupt.h:690
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_wfree
```
```
In net/xfrm/xfrm_input.c (ffffffff81b2c215)
Location: include/linux/interrupt.h:690
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_queue
```
**Symbols:**

```
ffffffff817640d0-ffffffff817640ef: tasklet_schedule.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/irq/resend.c (ffffffff81122139)
Location: include/linux/interrupt.h:680
Inline: True
Inline callers:
  - kernel/irq/resend.c:check_irq_resend
```
```
In drivers/tty/vt/keyboard.c (ffffffff81749fc6)
Location: include/linux/interrupt.h:680
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:vt_do_kdskled
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:vt_kbd_con_stop
  - drivers/tty/vt/keyboard.c:vt_kbd_con_start
  - drivers/tty/vt/keyboard.c:vt_set_led_state
  - drivers/tty/vt/keyboard.c:vt_set_leds_compute_shiftstate
Direct callers:
  - drivers/tty/vt/keyboard.c:kbd_init
```
```
In drivers/usb/core/hcd.c (ffffffff818ad062)
Location: include/linux/interrupt.h:680
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
```
```
In drivers/usb/host/xhci-dbgtty.c (ffffffff8190ac98)
Location: include/linux/interrupt.h:680
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
  - drivers/usb/host/xhci-dbgtty.c:dbc_tty_unthrottle
  - drivers/usb/host/xhci-dbgtty.c:dbc_read_complete
```
```
In net/ipv4/tcp_output.c (ffffffff81ab2465)
Location: include/linux/interrupt.h:680
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_wfree
```
```
In net/xfrm/xfrm_input.c (ffffffff81b19e75)
Location: include/linux/interrupt.h:680
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_queue
```
**Symbols:**

```
ffffffff817479a0-ffffffff817479bf: tasklet_schedule.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/irq/resend.c (ffffffff811426e9)
Location: include/linux/interrupt.h:654
Inline: True
Inline callers:
  - kernel/irq/resend.c:check_irq_resend
```
```
In drivers/tty/vt/keyboard.c (ffffffff817cb621)
Location: include/linux/interrupt.h:654
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:vt_do_kdskled
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:vt_kbd_con_stop
  - drivers/tty/vt/keyboard.c:vt_kbd_con_start
  - drivers/tty/vt/keyboard.c:vt_set_led_state
  - drivers/tty/vt/keyboard.c:vt_set_leds_compute_shiftstate
Direct callers:
  - drivers/tty/vt/keyboard.c:kbd_init
```
```
In drivers/usb/core/hcd.c (ffffffff819420ff)
Location: include/linux/interrupt.h:654
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
```
```
In drivers/usb/host/xhci-dbgtty.c (ffffffff819ab348)
Location: include/linux/interrupt.h:654
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
  - drivers/usb/host/xhci-dbgtty.c:dbc_tty_unthrottle
  - drivers/usb/host/xhci-dbgtty.c:dbc_read_complete
```
```
In net/ipv4/tcp_output.c (ffffffff81b6f2e5)
Location: include/linux/interrupt.h:654
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_wfree
```
```
In net/xfrm/xfrm_input.c (ffffffff81bde49a)
Location: include/linux/interrupt.h:654
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_queue
```
**Symbols:**

```
ffffffff817c8ab0-ffffffff817c8acf: tasklet_schedule.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/irq/resend.c (ffffffff8116623c)
Location: include/linux/interrupt.h:705
Inline: True
Inline callers:
  - kernel/irq/resend.c:check_irq_resend
```
```
In drivers/tty/vt/keyboard.c (ffffffff81908e55)
Location: include/linux/interrupt.h:705
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:vt_do_kdskled
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:vt_kbd_con_stop
  - drivers/tty/vt/keyboard.c:vt_kbd_con_start
  - drivers/tty/vt/keyboard.c:vt_set_led_state
  - drivers/tty/vt/keyboard.c:vt_set_leds_compute_shiftstate
Direct callers:
  - drivers/tty/vt/keyboard.c:kbd_init
```
```
In drivers/usb/core/hcd.c (ffffffff81a99fd1)
Location: include/linux/interrupt.h:705
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
  - drivers/usb/core/hcd.c:usb_giveback_urb_bh
```
```
In drivers/usb/host/xhci-dbgtty.c (ffffffff81b090f8)
Location: include/linux/interrupt.h:705
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
  - drivers/usb/host/xhci-dbgtty.c:dbc_tty_unthrottle
  - drivers/usb/host/xhci-dbgtty.c:dbc_read_complete
```
```
In net/ipv4/tcp_output.c (ffffffff81cfe96a)
Location: include/linux/interrupt.h:705
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_wfree
```
```
In net/xfrm/xfrm_input.c (ffffffff81d752b4)
Location: include/linux/interrupt.h:705
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_queue
```
**Symbols:**

```
ffffffff81905e00-ffffffff81905e2b: tasklet_schedule.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/resend.c (ffffffff8119a3ac)
Location: include/linux/interrupt.h:705
Inline: True
Inline callers:
  - kernel/irq/resend.c:check_irq_resend
```
```
In drivers/dma/hsu/hsu.c (ffffffff81a07876)
Location: include/linux/interrupt.h:705
Inline: True
Inline callers:
  - drivers/dma/hsu/hsu.c:hsu_dma_do_irq
```
```
In drivers/tty/vt/keyboard.c (ffffffff81a63445)
Location: include/linux/interrupt.h:705
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:vt_do_kdskled
  - drivers/tty/vt/keyboard.c:kbd_init
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:vt_kbd_con_stop
  - drivers/tty/vt/keyboard.c:vt_kbd_con_start
  - drivers/tty/vt/keyboard.c:vt_set_led_state
  - drivers/tty/vt/keyboard.c:vt_set_leds_compute_shiftstate
```
```
In drivers/usb/core/hcd.c (ffffffff81c1e531)
Location: include/linux/interrupt.h:705
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
  - drivers/usb/core/hcd.c:usb_giveback_urb_bh
```
```
In drivers/usb/host/xhci-dbgtty.c (ffffffff81c98dec)
Location: include/linux/interrupt.h:705
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
  - drivers/usb/host/xhci-dbgtty.c:dbc_tty_unthrottle
  - drivers/usb/host/xhci-dbgtty.c:dbc_read_complete
```
```
In net/ipv4/tcp_output.c (ffffffff81ec387c)
Location: include/linux/interrupt.h:705
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_wfree
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/resend.c (ffffffff811ac0d0)
Location: include/linux/interrupt.h:705
Inline: True
Inline callers:
  - kernel/irq/resend.c:check_irq_resend
```
```
In drivers/dma/hsu/hsu.c (ffffffff81a50706)
Location: include/linux/interrupt.h:705
Inline: True
Inline callers:
  - drivers/dma/hsu/hsu.c:hsu_dma_do_irq
```
```
In drivers/tty/vt/keyboard.c (ffffffff81aadb05)
Location: include/linux/interrupt.h:705
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:vt_do_kdskled
  - drivers/tty/vt/keyboard.c:kbd_init
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:vt_kbd_con_stop
  - drivers/tty/vt/keyboard.c:vt_kbd_con_start
  - drivers/tty/vt/keyboard.c:vt_set_led_state
  - drivers/tty/vt/keyboard.c:vt_set_leds_compute_shiftstate
```
```
In drivers/usb/core/hcd.c (ffffffff81c85436)
Location: include/linux/interrupt.h:705
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
  - drivers/usb/core/hcd.c:usb_giveback_urb_bh
```
```
In drivers/usb/host/xhci-dbgtty.c (ffffffff81d00187)
Location: include/linux/interrupt.h:705
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
  - drivers/usb/host/xhci-dbgtty.c:dbc_tty_unthrottle
  - drivers/usb/host/xhci-dbgtty.c:dbc_read_complete
```
```
In net/ipv4/tcp_output.c (ffffffff81f21abc)
Location: include/linux/interrupt.h:705
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_wfree
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/resend.c (ffffffff811bbcd0)
Location: include/linux/interrupt.h:709
Inline: True
Inline callers:
  - kernel/irq/resend.c:check_irq_resend
```
```
In drivers/dma/hsu/hsu.c (ffffffff81a9c3d6)
Location: include/linux/interrupt.h:709
Inline: True
Inline callers:
  - drivers/dma/hsu/hsu.c:hsu_dma_do_irq
```
```
In drivers/tty/vt/keyboard.c (ffffffff81b00735)
Location: include/linux/interrupt.h:709
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:vt_do_kdskled
  - drivers/tty/vt/keyboard.c:kbd_init
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:vt_kbd_con_stop
  - drivers/tty/vt/keyboard.c:vt_kbd_con_start
  - drivers/tty/vt/keyboard.c:vt_set_led_state
  - drivers/tty/vt/keyboard.c:vt_set_leds_compute_shiftstate
```
```
In drivers/usb/core/hcd.c (ffffffff81d39e36)
Location: include/linux/interrupt.h:709
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
  - drivers/usb/core/hcd.c:usb_giveback_urb_bh
```
```
In drivers/usb/host/xhci-dbgtty.c (ffffffff81db5c20)
Location: include/linux/interrupt.h:709
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
  - drivers/usb/host/xhci-dbgtty.c:dbc_tty_unthrottle
  - drivers/usb/host/xhci-dbgtty.c:dbc_read_complete
```
```
In net/ipv4/tcp_output.c (ffffffff81fe5a4c)
Location: include/linux/interrupt.h:709
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_wfree
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/irq/resend.c (ffff80001017d630)
Location: include/linux/interrupt.h:638
Inline: True
Inline callers:
  - kernel/irq/resend.c:check_irq_resend
```
```
In kernel/debug/debug_core.c (ffff8000101f9b4c)
Location: include/linux/interrupt.h:638
Inline: True
```
```
In drivers/dma/amba-pl08x.c (ffff800010802178)
Location: include/linux/interrupt.h:638
Inline: True
Inline callers:
  - drivers/dma/amba-pl08x.c:pl08x_irq
  - drivers/dma/amba-pl08x.c:pl08x_irq
```
```
In drivers/dma/bcm2835-dma.c (ffff8000108052c0)
Location: include/linux/interrupt.h:638
Inline: True
Inline callers:
  - drivers/dma/bcm2835-dma.c:bcm2835_dma_callback
  - drivers/dma/bcm2835-dma.c:bcm2835_dma_callback
```
```
In drivers/dma/mv_xor.c (ffff800010806534)
Location: include/linux/interrupt.h:638
Inline: True
Inline callers:
  - drivers/dma/mv_xor.c:mv_xor_interrupt_handler
  - drivers/dma/mv_xor.c:mv_xor_prep_dma_xor
  - drivers/dma/mv_xor.c:mv_chan_slot_cleanup
```
```
In drivers/dma/mv_xor_v2.c (ffff800010808884)
Location: include/linux/interrupt.h:638
Inline: True
Inline callers:
  - drivers/dma/mv_xor_v2.c:mv_xor_v2_prep_sw_desc
  - drivers/dma/mv_xor_v2.c:mv_xor_v2_interrupt_handler
```
```
In drivers/dma/mxs-dma.c (ffff80001080a138)
Location: include/linux/interrupt.h:638
Inline: True
Inline callers:
  - drivers/dma/mxs-dma.c:mxs_dma_int_handler
```
```
In drivers/dma/ipu/ipu_idmac.c (ffff80001080cffc)
Location: include/linux/interrupt.h:638
Inline: True
Inline callers:
  - drivers/dma/ipu/ipu_idmac.c:idmac_free_chan_resources
  - drivers/dma/ipu/ipu_idmac.c:idmac_prep_slave_sg
```
```
In drivers/tty/vt/keyboard.c (ffff80001086e8c8)
Location: include/linux/interrupt.h:638
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:vt_do_kdskled
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:vt_kbd_con_stop
  - drivers/tty/vt/keyboard.c:vt_kbd_con_start
  - drivers/tty/vt/keyboard.c:setledstate
Direct callers:
  - drivers/tty/vt/keyboard.c:kbd_init
```
```
In drivers/tty/vt/vt.c (ffff8000108732fc)
Location: include/linux/interrupt.h:638
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:redraw_screen
```
```
In drivers/net/ethernet/smsc/smc91x.c (ffff8000109fc9c8)
Location: include/linux/interrupt.h:638
Inline: True
Inline callers:
  - drivers/net/ethernet/smsc/smc91x.c:smc_hardware_send_pkt
```
```
In drivers/usb/core/hcd.c (ffff800010a1cc90)
Location: include/linux/interrupt.h:638
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
```
```
In drivers/usb/host/xhci-dbgtty.c (ffff800010a8c880)
Location: include/linux/interrupt.h:638
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
  - drivers/usb/host/xhci-dbgtty.c:dbc_tty_unthrottle
  - drivers/usb/host/xhci-dbgtty.c:dbc_read_complete
```
```
In net/ipv4/tcp_output.c (ffff800010c82a64)
Location: include/linux/interrupt.h:638
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_wfree
```
```
In net/xfrm/xfrm_input.c (ffff800010cea02c)
Location: include/linux/interrupt.h:638
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_queue
```
**Symbols:**

```
ffff80001086a6b0-ffff80001086a730: tasklet_schedule.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/irq/resend.c (c03cdf7c)
Location: include/linux/interrupt.h:638
Inline: True
Inline callers:
  - kernel/irq/resend.c:check_irq_resend
```
```
In kernel/debug/debug_core.c (c0439d1c)
Location: include/linux/interrupt.h:638
Inline: True
```
```
In drivers/dma/amba-pl08x.c (c0922988)
Location: include/linux/interrupt.h:638
Inline: True
Inline callers:
  - drivers/dma/amba-pl08x.c:pl08x_irq
  - drivers/dma/amba-pl08x.c:pl08x_irq
```
```
In drivers/dma/mv_xor.c (c0924c3c)
Location: include/linux/interrupt.h:638
Inline: True
Inline callers:
  - drivers/dma/mv_xor.c:mv_xor_interrupt_handler
  - drivers/dma/mv_xor.c:mv_xor_prep_dma_xor
  - drivers/dma/mv_xor.c:mv_chan_slot_cleanup
```
```
In drivers/dma/mxs-dma.c (c0926b58)
Location: include/linux/interrupt.h:638
Inline: True
Inline callers:
  - drivers/dma/mxs-dma.c:mxs_dma_int_handler
```
```
In drivers/dma/ipu/ipu_idmac.c (c0929718)
Location: include/linux/interrupt.h:638
Inline: True
Inline callers:
  - drivers/dma/ipu/ipu_idmac.c:idmac_free_chan_resources
  - drivers/dma/ipu/ipu_idmac.c:idmac_prep_slave_sg
```
```
In drivers/dma/tegra20-apb-dma.c (c092a3cc)
Location: include/linux/interrupt.h:638
Inline: True
Inline callers:
  - drivers/dma/tegra20-apb-dma.c:tegra_dma_isr
```
```
In drivers/dma/ti/edma.c (c092f858)
Location: include/linux/interrupt.h:638
Inline: True
Inline callers:
  - drivers/dma/ti/edma.c:dma_irq_handler
  - drivers/dma/ti/edma.c:dma_irq_handler
```
```
In drivers/dma/ti/omap-dma.c (c09323fc)
Location: include/linux/interrupt.h:638
Inline: True
Inline callers:
  - drivers/dma/ti/omap-dma.c:omap_dma_callback
  - drivers/dma/ti/omap-dma.c:omap_dma_callback
```
```
In drivers/tty/vt/keyboard.c (c09727f8)
Location: include/linux/interrupt.h:638
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:vt_do_kdskled
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:vt_kbd_con_stop
  - drivers/tty/vt/keyboard.c:vt_kbd_con_start
  - drivers/tty/vt/keyboard.c:setledstate
Direct callers:
  - drivers/tty/vt/keyboard.c:kbd_init
```
```
In drivers/tty/vt/vt.c (c09760c8)
Location: include/linux/interrupt.h:638
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:redraw_screen
```
```
In drivers/usb/core/hcd.c (c0af4118)
Location: include/linux/interrupt.h:638
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
```
```
In drivers/usb/host/xhci-dbgtty.c (c0b5f4a4)
Location: include/linux/interrupt.h:638
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
  - drivers/usb/host/xhci-dbgtty.c:dbc_tty_unthrottle
  - drivers/usb/host/xhci-dbgtty.c:dbc_read_complete
```
```
In sound/core/timer.c (c0c8dc08)
Location: include/linux/interrupt.h:638
Inline: True
```
```
In net/ipv4/tcp_output.c (c0d91448)
Location: include/linux/interrupt.h:638
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_wfree
```
```
In net/xfrm/xfrm_input.c (c0df1ecc)
Location: include/linux/interrupt.h:638
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_queue
```
**Symbols:**

```
c096f3e0-c096f414: tasklet_schedule.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/irq/resend.c (c0000000001d820c)
Location: include/linux/interrupt.h:638
Inline: True
Inline callers:
  - kernel/irq/resend.c:check_irq_resend
```
```
In kernel/debug/debug_core.c (c0000000002713a0)
Location: include/linux/interrupt.h:638
Inline: True
```
```
In drivers/tty/vt/keyboard.c (c00000000090ee40)
Location: include/linux/interrupt.h:638
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:vt_do_kdskled
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:vt_kbd_con_stop
  - drivers/tty/vt/keyboard.c:vt_kbd_con_start
  - drivers/tty/vt/keyboard.c:setledstate
Direct callers:
  - drivers/tty/vt/keyboard.c:kbd_init
```
```
In drivers/tty/vt/vt.c (c000000000913e88)
Location: include/linux/interrupt.h:638
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:redraw_screen
```
```
In drivers/usb/core/hcd.c (c000000000ad60f0)
Location: include/linux/interrupt.h:638
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
```
```
In drivers/usb/host/xhci-dbgtty.c (c000000000b68fd0)
Location: include/linux/interrupt.h:638
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
  - drivers/usb/host/xhci-dbgtty.c:dbc_tty_unthrottle
  - drivers/usb/host/xhci-dbgtty.c:dbc_read_complete
```
```
In net/ipv4/tcp_output.c (c000000000d8d410)
Location: include/linux/interrupt.h:638
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_wfree
```
```
In net/xfrm/xfrm_input.c (c000000000e0d880)
Location: include/linux/interrupt.h:638
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_queue
```
**Symbols:**

```
c00000000090a570-c00000000090a5d0: tasklet_schedule.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/keyboard.c (ffffffe00054199a)
Location: include/linux/interrupt.h:638
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:vt_do_kdskled
  - drivers/tty/vt/keyboard.c:kbd_init
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:vt_kbd_con_stop
  - drivers/tty/vt/keyboard.c:vt_kbd_con_start
  - drivers/tty/vt/keyboard.c:setledstate
```
```
In drivers/tty/vt/vt.c (ffffffe000544e36)
Location: include/linux/interrupt.h:638
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:redraw_screen
```
```
In drivers/usb/core/hcd.c (ffffffe0006409ce)
Location: include/linux/interrupt.h:638
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
```
```
In drivers/usb/host/xhci-dbgtty.c (ffffffe0006a164c)
Location: include/linux/interrupt.h:638
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
  - drivers/usb/host/xhci-dbgtty.c:dbc_tty_unthrottle
  - drivers/usb/host/xhci-dbgtty.c:dbc_read_complete
```
```
In net/ipv4/tcp_output.c (ffffffe0007e3f9e)
Location: include/linux/interrupt.h:638
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_wfree
```
```
In net/xfrm/xfrm_input.c (ffffffe000837be4)
Location: include/linux/interrupt.h:638
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_queue
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff8117c87c)
Location: include/linux/interrupt.h:638
Inline: True
```
```
In drivers/tty/vt/keyboard.c (ffffffff8165e2f8)
Location: include/linux/interrupt.h:638
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:vt_do_kdskled
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:vt_kbd_con_stop
  - drivers/tty/vt/keyboard.c:vt_kbd_con_start
  - drivers/tty/vt/keyboard.c:setledstate
Direct callers:
  - drivers/tty/vt/keyboard.c:kbd_init
```
```
In drivers/tty/vt/vt.c (ffffffff81661761)
Location: include/linux/interrupt.h:638
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:redraw_screen
```
```
In drivers/usb/core/hcd.c (ffffffff817a55e2)
Location: include/linux/interrupt.h:638
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
```
```
In net/ipv4/tcp_output.c (ffffffff8196f47f)
Location: include/linux/interrupt.h:638
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_wfree
```
```
In net/xfrm/xfrm_input.c (ffffffff819cab06)
Location: include/linux/interrupt.h:638
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_queue
```
**Symbols:**

```
ffffffff8165b540-ffffffff8165b55f: tasklet_schedule.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff8116fa5c)
Location: include/linux/interrupt.h:638
Inline: True
```
```
In drivers/tty/vt/keyboard.c (ffffffff8163e678)
Location: include/linux/interrupt.h:638
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:vt_do_kdskled
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:vt_kbd_con_stop
  - drivers/tty/vt/keyboard.c:vt_kbd_con_start
  - drivers/tty/vt/keyboard.c:setledstate
Direct callers:
  - drivers/tty/vt/keyboard.c:kbd_init
```
```
In drivers/tty/vt/vt.c (ffffffff81641ae1)
Location: include/linux/interrupt.h:638
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:redraw_screen
```
```
In drivers/usb/core/hcd.c (ffffffff817970a2)
Location: include/linux/interrupt.h:638
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
```
```
In drivers/usb/host/xhci-dbgtty.c (ffffffff817ca985)
Location: include/linux/interrupt.h:638
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
  - drivers/usb/host/xhci-dbgtty.c:dbc_tty_unthrottle
  - drivers/usb/host/xhci-dbgtty.c:dbc_read_complete
```
```
In drivers/hv/vmbus_drv.c (ffffffff8184eb59)
Location: include/linux/interrupt.h:638
Inline: True
Inline callers:
  - drivers/hv/vmbus_drv.c:vmbus_isr
  - drivers/hv/vmbus_drv.c:vmbus_isr
```
```
In drivers/hv/connection.c (ffffffff8185001f)
Location: include/linux/interrupt.h:638
Inline: True
Inline callers:
  - drivers/hv/connection.c:vmbus_on_event
```
```
In net/ipv4/tcp_output.c (ffffffff81928f4f)
Location: include/linux/interrupt.h:638
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_wfree
```
```
In net/xfrm/xfrm_input.c (ffffffff819878f6)
Location: include/linux/interrupt.h:638
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_queue
```
**Symbols:**

```
ffffffff8163b8c0-ffffffff8163b8df: tasklet_schedule.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff8117a64c)
Location: include/linux/interrupt.h:638
Inline: True
```
```
In drivers/tty/vt/keyboard.c (ffffffff8168c6d8)
Location: include/linux/interrupt.h:638
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:vt_do_kdskled
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:vt_kbd_con_stop
  - drivers/tty/vt/keyboard.c:vt_kbd_con_start
  - drivers/tty/vt/keyboard.c:setledstate
Direct callers:
  - drivers/tty/vt/keyboard.c:kbd_init
```
```
In drivers/tty/vt/vt.c (ffffffff8168fb41)
Location: include/linux/interrupt.h:638
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:redraw_screen
```
```
In drivers/usb/core/hcd.c (ffffffff817e2082)
Location: include/linux/interrupt.h:638
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
```
```
In drivers/usb/host/xhci-dbgtty.c (ffffffff818422b5)
Location: include/linux/interrupt.h:638
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
  - drivers/usb/host/xhci-dbgtty.c:dbc_tty_unthrottle
  - drivers/usb/host/xhci-dbgtty.c:dbc_read_complete
```
```
In net/ipv4/tcp_output.c (ffffffff819d9c4f)
Location: include/linux/interrupt.h:638
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_wfree
```
```
In net/xfrm/xfrm_input.c (ffffffff81a35586)
Location: include/linux/interrupt.h:638
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_queue
```
**Symbols:**

```
ffffffff81689920-ffffffff8168993f: tasklet_schedule.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff8118805c)
Location: include/linux/interrupt.h:638
Inline: True
```
```
In drivers/tty/vt/keyboard.c (ffffffff816a6cd8)
Location: include/linux/interrupt.h:638
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:vt_do_kdskled
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:vt_kbd_con_stop
  - drivers/tty/vt/keyboard.c:vt_kbd_con_start
  - drivers/tty/vt/keyboard.c:setledstate
Direct callers:
  - drivers/tty/vt/keyboard.c:kbd_init
```
```
In drivers/tty/vt/vt.c (ffffffff816aa141)
Location: include/linux/interrupt.h:638
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:redraw_screen
```
```
In drivers/usb/core/hcd.c (ffffffff817fc4aa)
Location: include/linux/interrupt.h:638
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
```
```
In drivers/usb/host/xhci-dbgtty.c (ffffffff8185c6e5)
Location: include/linux/interrupt.h:638
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
  - drivers/usb/host/xhci-dbgtty.c:dbc_tty_unthrottle
  - drivers/usb/host/xhci-dbgtty.c:dbc_read_complete
```
```
In net/ipv4/tcp_output.c (ffffffff819e38af)
Location: include/linux/interrupt.h:638
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_wfree
```
```
In net/xfrm/xfrm_input.c (ffffffff81a40ee6)
Location: include/linux/interrupt.h:638
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_trans_queue
```
**Symbols:**

```
ffffffff816a3f80-ffffffff816a3f9f: tasklet_schedule.constprop.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
