# Function: <code>xhci_alloc_command</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct xhci_command *xhci_alloc_command(struct xhci_hcd *xhci, bool allocate_in_ctx, bool allocate_completion, gfp_t mem_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff81654d50)
Location: drivers/usb/host/xhci-mem.c:1724
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_free_dev
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_update_hub_device
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:finish_td
```
**Symbols:**

```
ffffffff81654d50-ffffffff81654e83: xhci_alloc_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct xhci_command *xhci_alloc_command(struct xhci_hcd *xhci, bool allocate_in_ctx, bool allocate_completion, gfp_t mem_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff816b5740)
Location: drivers/usb/host/xhci-mem.c:1740
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_update_hub_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_free_dev
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
  - drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
```
**Symbols:**

```
ffffffff816b5740-ffffffff816b5873: xhci_alloc_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct xhci_command *xhci_alloc_command(struct xhci_hcd *xhci, bool allocate_in_ctx, bool allocate_completion, gfp_t mem_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff816e38f0)
Location: drivers/usb/host/xhci-mem.c:1773
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_update_hub_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_free_dev
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
  - drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
```
**Symbols:**

```
ffffffff816e38f0-ffffffff816e3a23: xhci_alloc_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct xhci_command *xhci_alloc_command(struct xhci_hcd *xhci, bool allocate_in_ctx, bool allocate_completion, gfp_t mem_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff816f7920)
Location: drivers/usb/host/xhci-mem.c:1715
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_update_hub_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_disable_slot
  - drivers/usb/host/xhci.c:xhci_free_dev
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
  - drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
```
**Symbols:**

```
ffffffff816f7920-ffffffff816f7a46: xhci_alloc_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct xhci_command *xhci_alloc_command(struct xhci_hcd *xhci, bool allocate_in_ctx, bool allocate_completion, gfp_t mem_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff81764660)
Location: drivers/usb/host/xhci-mem.c:1717
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_update_hub_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_disable_slot
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci-mem.c:xhci_mem_init
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
  - drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
```
**Symbols:**

```
ffffffff81764660-ffffffff8176477a: xhci_alloc_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct xhci_command *xhci_alloc_command(struct xhci_hcd *xhci, bool allocate_completion, gfp_t mem_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff817a48f0)
Location: drivers/usb/host/xhci-mem.c:1732
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_disable_slot
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci-mem.c:xhci_alloc_command_with_ctx
  - drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
```
**Symbols:**

```
ffffffff817a48f0-ffffffff817a49e0: xhci_alloc_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct xhci_command *xhci_alloc_command(struct xhci_hcd *xhci, bool allocate_completion, gfp_t mem_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff817cac80)
Location: drivers/usb/host/xhci-mem.c:1732
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_disable_slot
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci-mem.c:xhci_alloc_command_with_ctx
  - drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
```
**Symbols:**

```
ffffffff817cac80-ffffffff817cada7: xhci_alloc_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct xhci_command *xhci_alloc_command(struct xhci_hcd *xhci, bool allocate_completion, gfp_t mem_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff8180b070)
Location: drivers/usb/host/xhci-mem.c:1732
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_disable_slot
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci-mem.c:xhci_alloc_command_with_ctx
  - drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
```
**Symbols:**

```
ffffffff8180b070-ffffffff8180b159: xhci_alloc_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct xhci_command *xhci_alloc_command(struct xhci_hcd *xhci, bool allocate_completion, gfp_t mem_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff8183c030)
Location: drivers/usb/host/xhci-mem.c:1738
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_disable_slot
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci-mem.c:xhci_alloc_command_with_ctx
  - drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
```
**Symbols:**

```
ffffffff8183c030-ffffffff8183c119: xhci_alloc_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct xhci_command *xhci_alloc_command(struct xhci_hcd *xhci, bool allocate_completion, gfp_t mem_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff8190ee00)
Location: drivers/usb/host/xhci-mem.c:1738
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_disable_slot
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_check_maxpacket
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci-mem.c:xhci_alloc_command_with_ctx
  - drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:xhci_cleanup_halted_endpoint
  - drivers/usb/host/xhci-ring.c:xhci_handle_cmd_reset_ep
```
**Symbols:**

```
ffffffff8190ee00-ffffffff8190eee9: xhci_alloc_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct xhci_command *xhci_alloc_command(struct xhci_hcd *xhci, bool allocate_completion, gfp_t mem_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff81916960)
Location: drivers/usb/host/xhci-mem.c:1746
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_disable_slot
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_check_maxpacket
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci-mem.c:xhci_alloc_command_with_ctx
  - drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:xhci_cleanup_halted_endpoint
  - drivers/usb/host/xhci-ring.c:xhci_handle_cmd_reset_ep
```
**Symbols:**

```
ffffffff81916960-ffffffff81916a49: xhci_alloc_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct xhci_command *xhci_alloc_command(struct xhci_hcd *xhci, bool allocate_completion, gfp_t mem_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff818f9de0)
Location: drivers/usb/host/xhci-mem.c:1733
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_disable_slot
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_check_maxpacket
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci-mem.c:xhci_alloc_command_with_ctx
```
**Symbols:**

```
ffffffff818f9de0-ffffffff818f9ec9: xhci_alloc_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct xhci_command *xhci_alloc_command(struct xhci_hcd *xhci, bool allocate_completion, gfp_t mem_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff81998a70)
Location: drivers/usb/host/xhci-mem.c:1733
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_disable_slot
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_check_maxpacket
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci-mem.c:xhci_alloc_command_with_ctx
  - drivers/usb/host/xhci-ring.c:xhci_move_dequeue_past_td
```
**Symbols:**

```
ffffffff81998a70-ffffffff81998be8: xhci_alloc_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct xhci_command *xhci_alloc_command(struct xhci_hcd *xhci, bool allocate_completion, gfp_t mem_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff81af5a60)
Location: drivers/usb/host/xhci-mem.c:1724
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_disable_slot
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_check_maxpacket
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci-mem.c:xhci_alloc_command_with_ctx
  - drivers/usb/host/xhci-ring.c:xhci_move_dequeue_past_td
```
**Symbols:**

```
ffffffff81af5a60-ffffffff81af5bee: xhci_alloc_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct xhci_command *xhci_alloc_command(struct xhci_hcd *xhci, bool allocate_completion, gfp_t mem_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff81c83330)
Location: drivers/usb/host/xhci-mem.c:1733
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_disable_slot
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_check_maxpacket
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci-mem.c:xhci_alloc_command_with_ctx
  - drivers/usb/host/xhci-ring.c:xhci_handle_halted_endpoint
  - drivers/usb/host/xhci-ring.c:xhci_move_dequeue_past_td
```
**Symbols:**

```
ffffffff81c83330-ffffffff81c834e4: xhci_alloc_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct xhci_command *xhci_alloc_command(struct xhci_hcd *xhci, bool allocate_completion, gfp_t mem_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff81cea070)
Location: drivers/usb/host/xhci-mem.c:1713
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_disable_slot
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_check_maxpacket
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci-mem.c:xhci_alloc_command_with_ctx
  - drivers/usb/host/xhci-ring.c:xhci_handle_halted_endpoint
  - drivers/usb/host/xhci-ring.c:xhci_move_dequeue_past_td
```
**Symbols:**

```
ffffffff81cea070-ffffffff81cea224: xhci_alloc_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct xhci_command *xhci_alloc_command(struct xhci_hcd *xhci, bool allocate_completion, gfp_t mem_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff81d9f8a0)
Location: drivers/usb/host/xhci-mem.c:1721
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_disable_slot
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci-mem.c:xhci_alloc_command_with_ctx
  - drivers/usb/host/xhci-ring.c:xhci_handle_halted_endpoint
  - drivers/usb/host/xhci-ring.c:xhci_move_dequeue_past_td
```
**Symbols:**

```
ffffffff81d9f8a0-ffffffff81d9fa93: xhci_alloc_command (STB_GLOBAL)
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
struct xhci_command *xhci_alloc_command(struct xhci_hcd *xhci, bool allocate_completion, gfp_t mem_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffff800010a79e08)
Location: drivers/usb/host/xhci-mem.c:1738
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_disable_slot
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci-mem.c:xhci_alloc_command_with_ctx
  - drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
```
**Symbols:**

```
ffff800010a79e08-ffff800010a79ee4: xhci_alloc_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct xhci_command *xhci_alloc_command(struct xhci_hcd *xhci, bool allocate_completion, gfp_t mem_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (c0b4d7d8)
Location: drivers/usb/host/xhci-mem.c:1738
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_disable_slot
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci-mem.c:xhci_alloc_command_with_ctx
  - drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
```
**Symbols:**

```
c0b4d7d8-c0b4d894: xhci_alloc_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct xhci_command *xhci_alloc_command(struct xhci_hcd *xhci, bool allocate_completion, gfp_t mem_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (c000000000b51550)
Location: drivers/usb/host/xhci-mem.c:1738
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_disable_slot
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci-mem.c:xhci_alloc_command_with_ctx
  - drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
```
**Symbols:**

```
c000000000b51550-c000000000b51674: xhci_alloc_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct xhci_command *xhci_alloc_command(struct xhci_hcd *xhci, bool allocate_completion, gfp_t mem_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffe0006915a4)
Location: drivers/usb/host/xhci-mem.c:1738
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_disable_slot
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci-mem.c:xhci_alloc_command_with_ctx
  - drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
```
**Symbols:**

```
ffffffe0006915a4-ffffffe00069165c: xhci_alloc_command (STB_GLOBAL)
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
struct xhci_command *xhci_alloc_command(struct xhci_hcd *xhci, bool allocate_completion, gfp_t mem_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff817f43e0)
Location: drivers/usb/host/xhci-mem.c:1738
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_disable_slot
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci-mem.c:xhci_alloc_command_with_ctx
  - drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
```
**Symbols:**

```
ffffffff817f43e0-ffffffff817f44c9: xhci_alloc_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct xhci_command *xhci_alloc_command(struct xhci_hcd *xhci, bool allocate_completion, gfp_t mem_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff817b9580)
Location: drivers/usb/host/xhci-mem.c:1738
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_disable_slot
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci-mem.c:xhci_alloc_command_with_ctx
  - drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
```
**Symbols:**

```
ffffffff817b9580-ffffffff817b9669: xhci_alloc_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct xhci_command *xhci_alloc_command(struct xhci_hcd *xhci, bool allocate_completion, gfp_t mem_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff81830eb0)
Location: drivers/usb/host/xhci-mem.c:1738
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_disable_slot
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci-mem.c:xhci_alloc_command_with_ctx
  - drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
```
**Symbols:**

```
ffffffff81830eb0-ffffffff81830f99: xhci_alloc_command (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct xhci_command *xhci_alloc_command(struct xhci_hcd *xhci, bool allocate_completion, gfp_t mem_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff8184b080)
Location: drivers/usb/host/xhci-mem.c:1738
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_disable_slot
  - drivers/usb/host/xhci.c:xhci_endpoint_reset
  - drivers/usb/host/xhci.c:xhci_urb_dequeue
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci.c:xhci_run
  - drivers/usb/host/xhci-mem.c:xhci_alloc_command_with_ctx
  - drivers/usb/host/xhci-ring.c:xhci_queue_new_dequeue_state
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
```
**Symbols:**

```
ffffffff8184b080-ffffffff8184b169: xhci_alloc_command (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>bool allocate_in_ctx</code>
</li>
<li>
<b>Param reordered. </b>
<code>xhci, allocate_in_ctx, allocate_completion, mem_flags</code> ➡️ <code>xhci, allocate_completion, mem_flags</code>
</li>
</ul>
</details>
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
