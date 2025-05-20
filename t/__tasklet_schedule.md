# Function: <code>__tasklet_schedule</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __tasklet_schedule(struct tasklet_struct *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff81085560)
Location: kernel/softirq.c:449
Inline: False
Direct callers:
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:setledstate
  - drivers/tty/vt/keyboard.c:vt_kbd_con_start
  - drivers/tty/vt/keyboard.c:vt_kbd_con_stop
  - drivers/tty/vt/keyboard.c:vt_do_kdskled
  - drivers/tty/vt/vt.c:redraw_screen
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
  - net/core/flow.c:flow_cache_flush_per_cpu
  - net/ipv4/tcp_output.c:tcp_wfree
```
**Symbols:**

```
ffffffff81085560-ffffffff8108561f: __tasklet_schedule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __tasklet_schedule(struct tasklet_struct *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff81088640)
Location: kernel/softirq.c:449
Inline: False
Direct callers:
  - drivers/tty/vt/keyboard.c:vt_do_kdskled
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:vt_kbd_con_stop
  - drivers/tty/vt/keyboard.c:vt_kbd_con_start
  - drivers/tty/vt/keyboard.c:setledstate
  - drivers/tty/vt/vt.c:redraw_screen
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
  - net/core/flow.c:flow_cache_flush_per_cpu
  - net/ipv4/tcp_output.c:tcp_wfree
```
**Symbols:**

```
ffffffff81088640-ffffffff810886f8: __tasklet_schedule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __tasklet_schedule(struct tasklet_struct *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff8108d4c0)
Location: kernel/softirq.c:463
Inline: False
Direct callers:
  - drivers/tty/vt/keyboard.c:vt_do_kdskled
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:vt_kbd_con_stop
  - drivers/tty/vt/keyboard.c:vt_kbd_con_start
  - drivers/tty/vt/keyboard.c:setledstate
  - drivers/tty/vt/vt.c:redraw_screen
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
  - net/core/flow.c:flow_cache_flush_per_cpu
  - net/ipv4/tcp_output.c:tcp_wfree
```
**Symbols:**

```
ffffffff8108d4c0-ffffffff8108d579: __tasklet_schedule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __tasklet_schedule(struct tasklet_struct *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff8108a5e0)
Location: kernel/softirq.c:463
Inline: False
Direct callers:
  - drivers/tty/vt/keyboard.c:vt_do_kdskled
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:vt_kbd_con_stop
  - drivers/tty/vt/keyboard.c:vt_kbd_con_start
  - drivers/tty/vt/keyboard.c:setledstate
  - drivers/tty/vt/vt.c:redraw_screen
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
  - net/core/flow.c:flow_cache_flush_per_cpu
  - net/ipv4/tcp_output.c:tcp_pace_kick
  - net/ipv4/tcp_output.c:tcp_wfree
```
**Symbols:**

```
ffffffff8108a5e0-ffffffff8108a699: __tasklet_schedule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __tasklet_schedule(struct tasklet_struct *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff81091170)
Location: kernel/softirq.c:463
Inline: False
Direct callers:
  - drivers/tty/vt/keyboard.c:vt_do_kdskled
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:vt_kbd_con_stop
  - drivers/tty/vt/keyboard.c:vt_kbd_con_start
  - drivers/tty/vt/keyboard.c:setledstate
  - drivers/tty/vt/vt.c:redraw_screen
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
  - drivers/usb/host/xhci-dbgtty.c:dbc_tty_unthrottle
  - drivers/usb/host/xhci-dbgtty.c:dbc_read_complete
  - net/ipv4/tcp_output.c:tcp_pace_kick
  - net/ipv4/tcp_output.c:tcp_wfree
  - net/xfrm/xfrm_input.c:xfrm_trans_queue
```
**Symbols:**

```
ffffffff81091170-ffffffff8109122c: __tasklet_schedule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __tasklet_schedule(struct tasklet_struct *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff81094cf0)
Location: kernel/softirq.c:486
Inline: False
Direct callers:
  - drivers/tty/vt/keyboard.c:vt_do_kdskled
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:vt_kbd_con_stop
  - drivers/tty/vt/keyboard.c:vt_kbd_con_start
  - drivers/tty/vt/keyboard.c:setledstate
  - drivers/tty/vt/vt.c:redraw_screen
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
  - drivers/usb/host/xhci-dbgtty.c:dbc_tty_unthrottle
  - drivers/usb/host/xhci-dbgtty.c:dbc_read_complete
  - net/ipv4/tcp_output.c:tcp_wfree
  - net/xfrm/xfrm_input.c:xfrm_trans_queue
```
**Symbols:**

```
ffffffff81094cf0-ffffffff81094d0c: __tasklet_schedule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __tasklet_schedule(struct tasklet_struct *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff8109d100)
Location: kernel/softirq.c:487
Inline: False
Direct callers:
  - drivers/tty/vt/keyboard.c:vt_do_kdskled
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:vt_kbd_con_stop
  - drivers/tty/vt/keyboard.c:vt_kbd_con_start
  - drivers/tty/vt/keyboard.c:setledstate
  - drivers/tty/vt/vt.c:redraw_screen
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
  - drivers/usb/host/xhci-dbgtty.c:dbc_tty_unthrottle
  - drivers/usb/host/xhci-dbgtty.c:dbc_read_complete
  - net/ipv4/tcp_output.c:tcp_wfree
  - net/xfrm/xfrm_input.c:xfrm_trans_queue
```
**Symbols:**

```
ffffffff8109d100-ffffffff8109d11c: __tasklet_schedule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __tasklet_schedule(struct tasklet_struct *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff810a17e0)
Location: kernel/softirq.c:487
Inline: False
Direct callers:
  - drivers/tty/vt/keyboard.c:vt_do_kdskled
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:vt_kbd_con_stop
  - drivers/tty/vt/keyboard.c:vt_kbd_con_start
  - drivers/tty/vt/keyboard.c:setledstate
  - drivers/tty/vt/vt.c:redraw_screen
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
  - drivers/usb/host/xhci-dbgtty.c:dbc_tty_unthrottle
  - drivers/usb/host/xhci-dbgtty.c:dbc_read_complete
  - net/ipv4/tcp_output.c:tcp_wfree
  - net/xfrm/xfrm_input.c:xfrm_trans_queue
```
**Symbols:**

```
ffffffff810a17e0-ffffffff810a17fc: __tasklet_schedule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __tasklet_schedule(struct tasklet_struct *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff810a7da0)
Location: kernel/softirq.c:487
Inline: False
Direct callers:
  - drivers/tty/vt/keyboard.c:vt_do_kdskled
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:vt_kbd_con_stop
  - drivers/tty/vt/keyboard.c:vt_kbd_con_start
  - drivers/tty/vt/keyboard.c:setledstate
  - drivers/tty/vt/vt.c:redraw_screen
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
  - drivers/usb/host/xhci-dbgtty.c:dbc_tty_unthrottle
  - drivers/usb/host/xhci-dbgtty.c:dbc_read_complete
  - net/ipv4/tcp_output.c:tcp_wfree
  - net/xfrm/xfrm_input.c:xfrm_trans_queue
```
**Symbols:**

```
ffffffff810a7da0-ffffffff810a7dbc: __tasklet_schedule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __tasklet_schedule(struct tasklet_struct *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff810af3b0)
Location: kernel/softirq.c:514
Inline: False
Direct callers:
  - kernel/irq/resend.c:check_irq_resend
  - drivers/tty/vt/keyboard.c:vt_do_kdskled
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:vt_kbd_con_stop
  - drivers/tty/vt/keyboard.c:vt_kbd_con_start
  - drivers/tty/vt/keyboard.c:vt_set_led_state
  - drivers/tty/vt/vt.c:redraw_screen
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
  - drivers/usb/host/xhci-dbgtty.c:dbc_tty_unthrottle
  - drivers/usb/host/xhci-dbgtty.c:dbc_read_complete
  - net/ipv4/tcp_output.c:tcp_wfree
  - net/xfrm/xfrm_input.c:xfrm_trans_queue
```
**Symbols:**

```
ffffffff810af3b0-ffffffff810af474: __tasklet_schedule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __tasklet_schedule(struct tasklet_struct *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff810aab60)
Location: kernel/softirq.c:518
Inline: False
Direct callers:
  - kernel/irq/resend.c:check_irq_resend
  - drivers/tty/vt/keyboard.c:vt_do_kdskled
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:vt_kbd_con_stop
  - drivers/tty/vt/keyboard.c:vt_kbd_con_start
  - drivers/tty/vt/keyboard.c:vt_set_led_state
  - drivers/tty/vt/vt.c:redraw_screen
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
  - drivers/usb/host/xhci-dbgtty.c:dbc_tty_unthrottle
  - drivers/usb/host/xhci-dbgtty.c:dbc_read_complete
  - net/ipv4/tcp_output.c:tcp_wfree
  - net/xfrm/xfrm_input.c:xfrm_trans_queue
```
**Symbols:**

```
ffffffff810aab60-ffffffff810aac14: __tasklet_schedule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __tasklet_schedule(struct tasklet_struct *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff810abef0)
Location: kernel/softirq.c:735
Inline: False
Direct callers:
  - kernel/irq/resend.c:check_irq_resend
  - drivers/tty/vt/keyboard.c:vt_do_kdskled
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:vt_kbd_con_stop
  - drivers/tty/vt/keyboard.c:vt_kbd_con_start
  - drivers/tty/vt/keyboard.c:vt_set_led_state
  - drivers/tty/vt/keyboard.c:vt_set_leds_compute_shiftstate
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
  - drivers/usb/host/xhci-dbgtty.c:dbc_tty_unthrottle
  - drivers/usb/host/xhci-dbgtty.c:dbc_read_complete
  - net/ipv4/tcp_output.c:tcp_wfree
  - net/xfrm/xfrm_input.c:xfrm_trans_queue
```
**Symbols:**

```
ffffffff810abef0-ffffffff810abfac: __tasklet_schedule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __tasklet_schedule(struct tasklet_struct *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff810bdcb0)
Location: kernel/softirq.c:734
Inline: False
Direct callers:
  - kernel/irq/resend.c:check_irq_resend
  - drivers/tty/vt/keyboard.c:vt_do_kdskled
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:vt_kbd_con_stop
  - drivers/tty/vt/keyboard.c:vt_kbd_con_start
  - drivers/tty/vt/keyboard.c:vt_set_led_state
  - drivers/tty/vt/keyboard.c:vt_set_leds_compute_shiftstate
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
  - drivers/usb/host/xhci-dbgtty.c:dbc_tty_unthrottle
  - drivers/usb/host/xhci-dbgtty.c:dbc_read_complete
  - net/ipv4/tcp_output.c:tcp_wfree
  - net/xfrm/xfrm_input.c:xfrm_trans_queue
```
**Symbols:**

```
ffffffff810bdcb0-ffffffff810bdd33: __tasklet_schedule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __tasklet_schedule(struct tasklet_struct *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff810d4cf0)
Location: kernel/softirq.c:748
Inline: False
Direct callers:
  - kernel/irq/resend.c:check_irq_resend
  - drivers/tty/vt/keyboard.c:vt_do_kdskled
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:vt_kbd_con_stop
  - drivers/tty/vt/keyboard.c:vt_kbd_con_start
  - drivers/tty/vt/keyboard.c:vt_set_led_state
  - drivers/tty/vt/keyboard.c:vt_set_leds_compute_shiftstate
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
  - drivers/usb/core/hcd.c:usb_giveback_urb_bh
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
  - drivers/usb/host/xhci-dbgtty.c:dbc_tty_unthrottle
  - drivers/usb/host/xhci-dbgtty.c:dbc_read_complete
  - net/ipv4/tcp_output.c:tcp_wfree
  - net/xfrm/xfrm_input.c:xfrm_trans_queue
```
**Symbols:**

```
ffffffff810d4cf0-ffffffff810d4d16: __tasklet_schedule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __tasklet_schedule(struct tasklet_struct *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff810f3d20)
Location: kernel/softirq.c:748
Inline: False
Direct callers:
  - kernel/irq/resend.c:check_irq_resend
  - drivers/dma/hsu/hsu.c:hsu_dma_do_irq
  - drivers/tty/vt/keyboard.c:vt_do_kdskled
  - drivers/tty/vt/keyboard.c:kbd_init
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:vt_kbd_con_stop
  - drivers/tty/vt/keyboard.c:vt_kbd_con_start
  - drivers/tty/vt/keyboard.c:vt_set_led_state
  - drivers/tty/vt/keyboard.c:vt_set_leds_compute_shiftstate
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
  - drivers/usb/core/hcd.c:usb_giveback_urb_bh
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
  - drivers/usb/host/xhci-dbgtty.c:dbc_tty_unthrottle
  - drivers/usb/host/xhci-dbgtty.c:dbc_read_complete
  - net/ipv4/tcp_output.c:tcp_wfree
```
**Symbols:**

```
ffffffff810f3d20-ffffffff810f3d46: __tasklet_schedule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __tasklet_schedule(struct tasklet_struct *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff81100150)
Location: kernel/softirq.c:730
Inline: False
Direct callers:
  - kernel/irq/resend.c:check_irq_resend
  - drivers/dma/hsu/hsu.c:hsu_dma_do_irq
  - drivers/tty/vt/keyboard.c:vt_do_kdskled
  - drivers/tty/vt/keyboard.c:kbd_init
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:vt_kbd_con_stop
  - drivers/tty/vt/keyboard.c:vt_kbd_con_start
  - drivers/tty/vt/keyboard.c:vt_set_led_state
  - drivers/tty/vt/keyboard.c:vt_set_leds_compute_shiftstate
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
  - drivers/usb/core/hcd.c:usb_giveback_urb_bh
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
  - drivers/usb/host/xhci-dbgtty.c:dbc_tty_unthrottle
  - drivers/usb/host/xhci-dbgtty.c:dbc_read_complete
  - net/ipv4/tcp_output.c:tcp_wfree
```
**Symbols:**

```
ffffffff81100150-ffffffff81100176: __tasklet_schedule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __tasklet_schedule(struct tasklet_struct *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff81109870)
Location: kernel/softirq.c:730
Inline: False
Direct callers:
  - kernel/irq/resend.c:check_irq_resend
  - drivers/dma/hsu/hsu.c:hsu_dma_do_irq
  - drivers/tty/vt/keyboard.c:vt_do_kdskled
  - drivers/tty/vt/keyboard.c:kbd_init
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:vt_kbd_con_stop
  - drivers/tty/vt/keyboard.c:vt_kbd_con_start
  - drivers/tty/vt/keyboard.c:vt_set_led_state
  - drivers/tty/vt/keyboard.c:vt_set_leds_compute_shiftstate
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
  - drivers/usb/core/hcd.c:usb_giveback_urb_bh
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
  - drivers/usb/host/xhci-dbgtty.c:dbc_tty_unthrottle
  - drivers/usb/host/xhci-dbgtty.c:dbc_read_complete
  - net/ipv4/tcp_output.c:tcp_wfree
```
**Symbols:**

```
ffffffff81109870-ffffffff81109896: __tasklet_schedule (STB_GLOBAL)
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
void __tasklet_schedule(struct tasklet_struct *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffff8000100ff620)
Location: kernel/softirq.c:487
Inline: False
Direct callers:
  - kernel/irq/resend.c:check_irq_resend
  - drivers/dma/amba-pl08x.c:pl08x_irq
  - drivers/dma/amba-pl08x.c:pl08x_irq
  - drivers/dma/bcm2835-dma.c:bcm2835_dma_callback
  - drivers/dma/bcm2835-dma.c:bcm2835_dma_callback
  - drivers/dma/mv_xor.c:mv_xor_interrupt_handler
  - drivers/dma/mv_xor.c:mv_xor_prep_dma_xor
  - drivers/dma/mv_xor.c:mv_chan_slot_cleanup
  - drivers/dma/mv_xor_v2.c:mv_xor_v2_prep_sw_desc
  - drivers/dma/mv_xor_v2.c:mv_xor_v2_interrupt_handler
  - drivers/dma/mxs-dma.c:mxs_dma_int_handler
  - drivers/dma/ipu/ipu_idmac.c:idmac_free_chan_resources
  - drivers/dma/ipu/ipu_idmac.c:idmac_prep_slave_sg
  - drivers/tty/vt/keyboard.c:vt_do_kdskled
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:vt_kbd_con_stop
  - drivers/tty/vt/keyboard.c:vt_kbd_con_start
  - drivers/tty/vt/keyboard.c:setledstate
  - drivers/tty/vt/vt.c:redraw_screen
  - drivers/net/ethernet/smsc/smc91x.c:smc_hardware_send_pkt
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
  - drivers/usb/host/xhci-dbgtty.c:dbc_tty_unthrottle
  - drivers/usb/host/xhci-dbgtty.c:dbc_read_complete
  - net/ipv4/tcp_output.c:tcp_wfree
  - net/xfrm/xfrm_input.c:xfrm_trans_queue
```
**Symbols:**

```
ffff8000100ff620-ffff8000100ff65c: __tasklet_schedule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __tasklet_schedule(struct tasklet_struct *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (c035c250)
Location: kernel/softirq.c:487
Inline: False
Direct callers:
  - kernel/irq/resend.c:check_irq_resend
  - drivers/dma/amba-pl08x.c:pl08x_irq
  - drivers/dma/amba-pl08x.c:pl08x_irq
  - drivers/dma/mv_xor.c:mv_xor_interrupt_handler
  - drivers/dma/mv_xor.c:mv_xor_prep_dma_xor
  - drivers/dma/mv_xor.c:mv_chan_slot_cleanup
  - drivers/dma/mxs-dma.c:mxs_dma_int_handler
  - drivers/dma/ipu/ipu_idmac.c:idmac_free_chan_resources
  - drivers/dma/ipu/ipu_idmac.c:idmac_prep_slave_sg
  - drivers/dma/tegra20-apb-dma.c:tegra_dma_isr
  - drivers/dma/ti/edma.c:dma_irq_handler
  - drivers/dma/ti/edma.c:dma_irq_handler
  - drivers/dma/ti/omap-dma.c:omap_dma_callback
  - drivers/tty/vt/keyboard.c:vt_do_kdskled
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:vt_kbd_con_stop
  - drivers/tty/vt/keyboard.c:vt_kbd_con_start
  - drivers/tty/vt/keyboard.c:setledstate
  - drivers/tty/vt/vt.c:redraw_screen
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
  - drivers/usb/host/xhci-dbgtty.c:dbc_tty_unthrottle
  - drivers/usb/host/xhci-dbgtty.c:dbc_read_complete
  - net/ipv4/tcp_output.c:tcp_wfree
  - net/xfrm/xfrm_input.c:xfrm_trans_queue
```
**Symbols:**

```
c035c250-c035c278: __tasklet_schedule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __tasklet_schedule(struct tasklet_struct *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (c000000000146a00)
Location: kernel/softirq.c:487
Inline: False
Direct callers:
  - kernel/irq/resend.c:check_irq_resend
  - drivers/tty/vt/keyboard.c:vt_do_kdskled
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:vt_kbd_con_stop
  - drivers/tty/vt/keyboard.c:vt_kbd_con_start
  - drivers/tty/vt/keyboard.c:setledstate
  - drivers/tty/vt/vt.c:redraw_screen
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
  - drivers/usb/host/xhci-dbgtty.c:dbc_tty_unthrottle
  - drivers/usb/host/xhci-dbgtty.c:dbc_read_complete
  - net/ipv4/tcp_output.c:tcp_wfree
  - net/xfrm/xfrm_input.c:xfrm_trans_queue
```
**Symbols:**

```
c000000000146a00-c000000000146a20: __tasklet_schedule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __tasklet_schedule(struct tasklet_struct *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffe0000c744e)
Location: kernel/softirq.c:487
Inline: False
Direct callers:
  - drivers/tty/vt/keyboard.c:vt_do_kdskled
  - drivers/tty/vt/keyboard.c:kbd_init
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:vt_kbd_con_stop
  - drivers/tty/vt/keyboard.c:vt_kbd_con_start
  - drivers/tty/vt/keyboard.c:setledstate
  - drivers/tty/vt/vt.c:redraw_screen
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
  - drivers/usb/host/xhci-dbgtty.c:dbc_tty_unthrottle
  - drivers/usb/host/xhci-dbgtty.c:dbc_read_complete
  - net/ipv4/tcp_output.c:tcp_wfree
  - net/xfrm/xfrm_input.c:xfrm_trans_queue
```
**Symbols:**

```
ffffffe0000c744e-ffffffe0000c7482: __tasklet_schedule (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void __tasklet_schedule(struct tasklet_struct *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff810a16c0)
Location: kernel/softirq.c:487
Inline: False
Direct callers:
  - drivers/tty/vt/keyboard.c:vt_do_kdskled
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:vt_kbd_con_stop
  - drivers/tty/vt/keyboard.c:vt_kbd_con_start
  - drivers/tty/vt/keyboard.c:setledstate
  - drivers/tty/vt/vt.c:redraw_screen
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
  - net/ipv4/tcp_output.c:tcp_wfree
  - net/xfrm/xfrm_input.c:xfrm_trans_queue
```
**Symbols:**

```
ffffffff810a16c0-ffffffff810a16dc: __tasklet_schedule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __tasklet_schedule(struct tasklet_struct *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff810900a0)
Location: kernel/softirq.c:487
Inline: False
Direct callers:
  - drivers/tty/vt/keyboard.c:vt_do_kdskled
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:vt_kbd_con_stop
  - drivers/tty/vt/keyboard.c:vt_kbd_con_start
  - drivers/tty/vt/keyboard.c:setledstate
  - drivers/tty/vt/vt.c:redraw_screen
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
  - drivers/usb/host/xhci-dbgtty.c:dbc_tty_unthrottle
  - drivers/usb/host/xhci-dbgtty.c:dbc_read_complete
  - drivers/hv/vmbus_drv.c:vmbus_isr
  - drivers/hv/vmbus_drv.c:vmbus_isr
  - drivers/hv/connection.c:vmbus_on_event
  - net/ipv4/tcp_output.c:tcp_wfree
  - net/xfrm/xfrm_input.c:xfrm_trans_queue
```
**Symbols:**

```
ffffffff810900a0-ffffffff810900bc: __tasklet_schedule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __tasklet_schedule(struct tasklet_struct *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff810a1670)
Location: kernel/softirq.c:487
Inline: False
Direct callers:
  - drivers/tty/vt/keyboard.c:vt_do_kdskled
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:vt_kbd_con_stop
  - drivers/tty/vt/keyboard.c:vt_kbd_con_start
  - drivers/tty/vt/keyboard.c:setledstate
  - drivers/tty/vt/vt.c:redraw_screen
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
  - drivers/usb/host/xhci-dbgtty.c:dbc_tty_unthrottle
  - drivers/usb/host/xhci-dbgtty.c:dbc_read_complete
  - net/ipv4/tcp_output.c:tcp_wfree
  - net/xfrm/xfrm_input.c:xfrm_trans_queue
```
**Symbols:**

```
ffffffff810a1670-ffffffff810a168c: __tasklet_schedule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __tasklet_schedule(struct tasklet_struct *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/softirq.c (ffffffff810a9630)
Location: kernel/softirq.c:487
Inline: False
Direct callers:
  - drivers/tty/vt/keyboard.c:vt_do_kdskled
  - drivers/tty/vt/keyboard.c:kbd_event
  - drivers/tty/vt/keyboard.c:vt_kbd_con_stop
  - drivers/tty/vt/keyboard.c:vt_kbd_con_start
  - drivers/tty/vt/keyboard.c:setledstate
  - drivers/tty/vt/vt.c:redraw_screen
  - drivers/usb/core/hcd.c:usb_hcd_giveback_urb
  - drivers/usb/host/xhci-dbgtty.c:dbc_rx_push
  - drivers/usb/host/xhci-dbgtty.c:dbc_tty_unthrottle
  - drivers/usb/host/xhci-dbgtty.c:dbc_read_complete
  - net/ipv4/tcp_output.c:tcp_wfree
  - net/xfrm/xfrm_input.c:xfrm_trans_queue
```
**Symbols:**

```
ffffffff810a9630-ffffffff810a964c: __tasklet_schedule (STB_GLOBAL)
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
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
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
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
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
