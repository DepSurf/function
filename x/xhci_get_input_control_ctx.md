# Function: <code>xhci_get_input_control_ctx</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct xhci_input_control_ctx *xhci_get_input_control_ctx(struct xhci_container_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff81653d30)
Location: drivers/usb/host/xhci-mem.c:538
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_reserve_bandwidth
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_change_max_exit_latency
  - drivers/usb/host/xhci.c:xhci_update_hub_device
  - drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-dbg.c:xhci_dbg_ctx
```
**Symbols:**

```
ffffffff81653d30-ffffffff81653d46: xhci_get_input_control_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct xhci_input_control_ctx *xhci_get_input_control_ctx(struct xhci_container_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff816b47c0)
Location: drivers/usb/host/xhci-mem.c:550
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_update_hub_device
  - drivers/usb/host/xhci.c:xhci_change_max_exit_latency
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_reserve_bandwidth
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-dbg.c:xhci_dbg_ctx
```
**Symbols:**

```
ffffffff816b47c0-ffffffff816b47d6: xhci_get_input_control_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct xhci_input_control_ctx *xhci_get_input_control_ctx(struct xhci_container_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff816e2970)
Location: drivers/usb/host/xhci-mem.c:550
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_update_hub_device
  - drivers/usb/host/xhci.c:xhci_change_max_exit_latency
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_reserve_bandwidth
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-dbg.c:xhci_dbg_ctx
```
**Symbols:**

```
ffffffff816e2970-ffffffff816e2986: xhci_get_input_control_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct xhci_input_control_ctx *xhci_get_input_control_ctx(struct xhci_container_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff816f6a70)
Location: drivers/usb/host/xhci-mem.c:504
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_update_hub_device
  - drivers/usb/host/xhci.c:xhci_change_max_exit_latency
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_reserve_bandwidth
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
```
**Symbols:**

```
ffffffff816f6a70-ffffffff816f6a88: xhci_get_input_control_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct xhci_input_control_ctx *xhci_get_input_control_ctx(struct xhci_container_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff817634e0)
Location: drivers/usb/host/xhci-mem.c:491
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_update_hub_device
  - drivers/usb/host/xhci.c:xhci_change_max_exit_latency
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_reserve_bandwidth
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
```
**Symbols:**

```
ffffffff817634e0-ffffffff817634f8: xhci_get_input_control_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct xhci_input_control_ctx *xhci_get_input_control_ctx(struct xhci_container_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff817a3730)
Location: drivers/usb/host/xhci-mem.c:495
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_update_hub_device
  - drivers/usb/host/xhci.c:xhci_change_max_exit_latency
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
  - drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_reserve_bandwidth
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
```
**Symbols:**

```
ffffffff817a3730-ffffffff817a3746: xhci_get_input_control_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct xhci_input_control_ctx *xhci_get_input_control_ctx(struct xhci_container_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff817c9a50)
Location: drivers/usb/host/xhci-mem.c:495
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_update_hub_device
  - drivers/usb/host/xhci.c:xhci_change_max_exit_latency
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
  - drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_reserve_bandwidth
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
```
**Symbols:**

```
ffffffff817c9a50-ffffffff817c9a66: xhci_get_input_control_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct xhci_input_control_ctx *xhci_get_input_control_ctx(struct xhci_container_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff81809e70)
Location: drivers/usb/host/xhci-mem.c:495
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_update_hub_device
  - drivers/usb/host/xhci.c:xhci_change_max_exit_latency
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
  - drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_reserve_bandwidth
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
```
**Symbols:**

```
ffffffff81809e70-ffffffff81809e86: xhci_get_input_control_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct xhci_input_control_ctx *xhci_get_input_control_ctx(struct xhci_container_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff8183adf0)
Location: drivers/usb/host/xhci-mem.c:495
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_update_hub_device
  - drivers/usb/host/xhci.c:xhci_change_max_exit_latency
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
  - drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_reserve_bandwidth
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
```
**Symbols:**

```
ffffffff8183adf0-ffffffff8183ae06: xhci_get_input_control_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct xhci_input_control_ctx *xhci_get_input_control_ctx(struct xhci_container_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff8190d840)
Location: drivers/usb/host/xhci-mem.c:495
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_update_hub_device
  - drivers/usb/host/xhci.c:xhci_change_max_exit_latency
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
  - drivers/usb/host/xhci.c:xhci_setup_input_ctx_for_quirk
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_reserve_bandwidth
  - drivers/usb/host/xhci.c:xhci_zero_in_ctx
  - drivers/usb/host/xhci.c:xhci_check_maxpacket
```
**Symbols:**

```
ffffffff8190d840-ffffffff8190d856: xhci_get_input_control_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct xhci_input_control_ctx *xhci_get_input_control_ctx(struct xhci_container_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff819153e0)
Location: drivers/usb/host/xhci-mem.c:504
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_update_hub_device
  - drivers/usb/host/xhci.c:xhci_change_max_exit_latency
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
  - drivers/usb/host/xhci.c:xhci_setup_input_ctx_for_quirk
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_reserve_bandwidth
  - drivers/usb/host/xhci.c:xhci_zero_in_ctx
  - drivers/usb/host/xhci.c:xhci_check_maxpacket
```
**Symbols:**

```
ffffffff819153e0-ffffffff819153f6: xhci_get_input_control_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct xhci_input_control_ctx *xhci_get_input_control_ctx(struct xhci_container_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff818f88f0)
Location: drivers/usb/host/xhci-mem.c:504
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_update_hub_device
  - drivers/usb/host/xhci.c:xhci_change_max_exit_latency
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_reserve_bandwidth
  - drivers/usb/host/xhci.c:xhci_zero_in_ctx
  - drivers/usb/host/xhci.c:xhci_check_maxpacket
```
**Symbols:**

```
ffffffff818f88f0-ffffffff818f8906: xhci_get_input_control_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct xhci_input_control_ctx *xhci_get_input_control_ctx(struct xhci_container_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff81997050)
Location: drivers/usb/host/xhci-mem.c:504
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_update_hub_device
  - drivers/usb/host/xhci.c:xhci_change_max_exit_latency
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_reserve_bandwidth
  - drivers/usb/host/xhci.c:xhci_zero_in_ctx
  - drivers/usb/host/xhci.c:xhci_check_maxpacket
```
**Symbols:**

```
ffffffff81997050-ffffffff81997066: xhci_get_input_control_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct xhci_input_control_ctx *xhci_get_input_control_ctx(struct xhci_container_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff81af3f10)
Location: drivers/usb/host/xhci-mem.c:503
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_update_hub_device
  - drivers/usb/host/xhci.c:xhci_change_max_exit_latency
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_reserve_bandwidth
  - drivers/usb/host/xhci.c:xhci_zero_in_ctx
  - drivers/usb/host/xhci.c:xhci_check_maxpacket
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
```
**Symbols:**

```
ffffffff81af3f10-ffffffff81af3f2c: xhci_get_input_control_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct xhci_input_control_ctx *xhci_get_input_control_ctx(struct xhci_container_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff81c81520)
Location: drivers/usb/host/xhci-mem.c:503
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_update_hub_device
  - drivers/usb/host/xhci.c:xhci_change_max_exit_latency
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_reserve_bandwidth
  - drivers/usb/host/xhci.c:xhci_zero_in_ctx
  - drivers/usb/host/xhci.c:xhci_check_maxpacket
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
```
**Symbols:**

```
ffffffff81c81520-ffffffff81c8153c: xhci_get_input_control_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct xhci_input_control_ctx *xhci_get_input_control_ctx(struct xhci_container_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff81ce8230)
Location: drivers/usb/host/xhci-mem.c:495
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_update_hub_device
  - drivers/usb/host/xhci.c:xhci_change_max_exit_latency
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_reserve_bandwidth
  - drivers/usb/host/xhci.c:xhci_zero_in_ctx
  - drivers/usb/host/xhci.c:xhci_check_maxpacket
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
```
**Symbols:**

```
ffffffff81ce8230-ffffffff81ce824c: xhci_get_input_control_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct xhci_input_control_ctx *xhci_get_input_control_ctx(struct xhci_container_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff81d9da40)
Location: drivers/usb/host/xhci-mem.c:506
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_update_hub_device
  - drivers/usb/host/xhci.c:xhci_change_max_exit_latency
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_reserve_bandwidth
  - drivers/usb/host/xhci.c:xhci_zero_in_ctx
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
```
**Symbols:**

```
ffffffff81d9da40-ffffffff81d9da5c: xhci_get_input_control_ctx (STB_GLOBAL)
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
struct xhci_input_control_ctx *xhci_get_input_control_ctx(struct xhci_container_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffff800010a78930)
Location: drivers/usb/host/xhci-mem.c:495
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_update_hub_device
  - drivers/usb/host/xhci.c:xhci_change_max_exit_latency
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
  - drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_reserve_bandwidth
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
```
**Symbols:**

```
ffff800010a78930-ffff800010a78974: xhci_get_input_control_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct xhci_input_control_ctx *xhci_get_input_control_ctx(struct xhci_container_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (c0b4c528)
Location: drivers/usb/host/xhci-mem.c:495
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_update_hub_device
  - drivers/usb/host/xhci.c:xhci_change_max_exit_latency
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
  - drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_reserve_bandwidth
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
```
**Symbols:**

```
c0b4c528-c0b4c550: xhci_get_input_control_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct xhci_input_control_ctx *xhci_get_input_control_ctx(struct xhci_container_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (c000000000b4fdb0)
Location: drivers/usb/host/xhci-mem.c:495
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_update_hub_device
  - drivers/usb/host/xhci.c:xhci_change_max_exit_latency
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
  - drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_reserve_bandwidth
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
```
**Symbols:**

```
c000000000b4fdb0-c000000000b4fdd8: xhci_get_input_control_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct xhci_input_control_ctx *xhci_get_input_control_ctx(struct xhci_container_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffe0006903d0)
Location: drivers/usb/host/xhci-mem.c:495
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_update_hub_device
  - drivers/usb/host/xhci.c:xhci_change_max_exit_latency
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
  - drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_reserve_bandwidth
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
```
**Symbols:**

```
ffffffe0006903d0-ffffffe0006903fc: xhci_get_input_control_ctx (STB_GLOBAL)
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
struct xhci_input_control_ctx *xhci_get_input_control_ctx(struct xhci_container_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff817f31a0)
Location: drivers/usb/host/xhci-mem.c:495
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_update_hub_device
  - drivers/usb/host/xhci.c:xhci_change_max_exit_latency
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
  - drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_reserve_bandwidth
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
```
**Symbols:**

```
ffffffff817f31a0-ffffffff817f31b6: xhci_get_input_control_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct xhci_input_control_ctx *xhci_get_input_control_ctx(struct xhci_container_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff817b8340)
Location: drivers/usb/host/xhci-mem.c:495
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_update_hub_device
  - drivers/usb/host/xhci.c:xhci_change_max_exit_latency
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
  - drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_reserve_bandwidth
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
```
**Symbols:**

```
ffffffff817b8340-ffffffff817b8356: xhci_get_input_control_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct xhci_input_control_ctx *xhci_get_input_control_ctx(struct xhci_container_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff8182fc70)
Location: drivers/usb/host/xhci-mem.c:495
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_update_hub_device
  - drivers/usb/host/xhci.c:xhci_change_max_exit_latency
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
  - drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_reserve_bandwidth
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
```
**Symbols:**

```
ffffffff8182fc70-ffffffff8182fc86: xhci_get_input_control_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct xhci_input_control_ctx *xhci_get_input_control_ctx(struct xhci_container_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff81849e10)
Location: drivers/usb/host/xhci-mem.c:495
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_update_hub_device
  - drivers/usb/host/xhci.c:xhci_change_max_exit_latency
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_free_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
  - drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_reserve_bandwidth
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
```
**Symbols:**

```
ffffffff81849e10-ffffffff81849e26: xhci_get_input_control_ctx (STB_GLOBAL)
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
