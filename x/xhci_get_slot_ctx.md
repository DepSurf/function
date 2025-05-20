# Function: <code>xhci_get_slot_ctx</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
struct xhci_slot_ctx *xhci_get_slot_ctx(struct xhci_hcd *xhci, struct xhci_container_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff81653d50)
Location: drivers/usb/host/xhci-mem.c:547
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_setup_addressable_virt_dev
  - drivers/usb/host/xhci-mem.c:xhci_slot_copy
  - drivers/usb/host/xhci-mem.c:xhci_slot_copy
Direct callers:
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_change_max_exit_latency
  - drivers/usb/host/xhci.c:xhci_update_hub_device
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-dbg.c:xhci_get_slot_state
  - drivers/usb/host/xhci-dbg.c:xhci_dbg_ctx
```
**Symbols:**

```
ffffffff81653d50-ffffffff81653d7e: xhci_get_slot_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct xhci_slot_ctx *xhci_get_slot_ctx(struct xhci_hcd *xhci, struct xhci_container_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff816b56d5)
Location: drivers/usb/host/xhci-mem.c:559
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_slot_copy
  - drivers/usb/host/xhci-mem.c:xhci_slot_copy
  - drivers/usb/host/xhci-mem.c:xhci_setup_addressable_virt_dev
Direct callers:
  - drivers/usb/host/xhci.c:xhci_update_hub_device
  - drivers/usb/host/xhci.c:xhci_change_max_exit_latency
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-dbg.c:xhci_dbg_ctx
  - drivers/usb/host/xhci-dbg.c:xhci_get_slot_state
```
**Symbols:**

```
ffffffff816b47e0-ffffffff816b480e: xhci_get_slot_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct xhci_slot_ctx *xhci_get_slot_ctx(struct xhci_hcd *xhci, struct xhci_container_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff816e3885)
Location: drivers/usb/host/xhci-mem.c:559
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_slot_copy
  - drivers/usb/host/xhci-mem.c:xhci_slot_copy
  - drivers/usb/host/xhci-mem.c:xhci_setup_addressable_virt_dev
Direct callers:
  - drivers/usb/host/xhci.c:xhci_update_hub_device
  - drivers/usb/host/xhci.c:xhci_change_max_exit_latency
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-dbg.c:xhci_dbg_ctx
  - drivers/usb/host/xhci-dbg.c:xhci_get_slot_state
```
**Symbols:**

```
ffffffff816e2990-ffffffff816e29be: xhci_get_slot_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct xhci_slot_ctx *xhci_get_slot_ctx(struct xhci_hcd *xhci, struct xhci_container_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff816f78c5)
Location: drivers/usb/host/xhci-mem.c:513
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_slot_copy
  - drivers/usb/host/xhci-mem.c:xhci_slot_copy
  - drivers/usb/host/xhci-mem.c:xhci_setup_addressable_virt_dev
Direct callers:
  - drivers/usb/host/xhci.c:xhci_update_hub_device
  - drivers/usb/host/xhci.c:xhci_change_max_exit_latency
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_free_dev
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-dbg.c:xhci_get_slot_state
```
**Symbols:**

```
ffffffff816f6a90-ffffffff816f6ab9: xhci_get_slot_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct xhci_slot_ctx *xhci_get_slot_ctx(struct xhci_hcd *xhci, struct xhci_container_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff81764605)
Location: drivers/usb/host/xhci-mem.c:500
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_slot_copy
  - drivers/usb/host/xhci-mem.c:xhci_slot_copy
  - drivers/usb/host/xhci-mem.c:xhci_setup_addressable_virt_dev
Direct callers:
  - drivers/usb/host/xhci.c:xhci_update_hub_device
  - drivers/usb/host/xhci.c:xhci_change_max_exit_latency
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_free_dev
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-dbg.c:xhci_get_slot_state
  - drivers/usb/host/xhci-debugfs.c:xhci_slot_context_show
```
**Symbols:**

```
ffffffff81763500-ffffffff81763529: xhci_get_slot_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct xhci_slot_ctx *xhci_get_slot_ctx(struct xhci_hcd *xhci, struct xhci_container_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff817a4895)
Location: drivers/usb/host/xhci-mem.c:504
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_slot_copy
  - drivers/usb/host/xhci-mem.c:xhci_slot_copy
  - drivers/usb/host/xhci-mem.c:xhci_setup_addressable_virt_dev
Direct callers:
  - drivers/usb/host/xhci.c:xhci_update_hub_device
  - drivers/usb/host/xhci.c:xhci_change_max_exit_latency
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_free_dev
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-dbg.c:xhci_get_slot_state
  - drivers/usb/host/xhci-debugfs.c:xhci_slot_context_show
```
**Symbols:**

```
ffffffff817a3750-ffffffff817a3779: xhci_get_slot_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct xhci_slot_ctx *xhci_get_slot_ctx(struct xhci_hcd *xhci, struct xhci_container_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff817cac25)
Location: drivers/usb/host/xhci-mem.c:504
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_slot_copy
  - drivers/usb/host/xhci-mem.c:xhci_slot_copy
  - drivers/usb/host/xhci-mem.c:xhci_setup_addressable_virt_dev
Direct callers:
  - drivers/usb/host/xhci.c:xhci_update_hub_device
  - drivers/usb/host/xhci.c:xhci_change_max_exit_latency
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_free_dev
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-dbg.c:xhci_get_slot_state
  - drivers/usb/host/xhci-debugfs.c:xhci_slot_context_show
```
**Symbols:**

```
ffffffff817c9a70-ffffffff817c9a99: xhci_get_slot_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct xhci_slot_ctx *xhci_get_slot_ctx(struct xhci_hcd *xhci, struct xhci_container_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff8180b015)
Location: drivers/usb/host/xhci-mem.c:504
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_slot_copy
  - drivers/usb/host/xhci-mem.c:xhci_slot_copy
  - drivers/usb/host/xhci-mem.c:xhci_setup_addressable_virt_dev
Direct callers:
  - drivers/usb/host/xhci.c:xhci_update_hub_device
  - drivers/usb/host/xhci.c:xhci_change_max_exit_latency
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_free_dev
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-dbg.c:xhci_get_slot_state
  - drivers/usb/host/xhci-debugfs.c:xhci_slot_context_show
```
**Symbols:**

```
ffffffff81809e90-ffffffff81809eb9: xhci_get_slot_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct xhci_slot_ctx *xhci_get_slot_ctx(struct xhci_hcd *xhci, struct xhci_container_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff8183bfd5)
Location: drivers/usb/host/xhci-mem.c:504
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_slot_copy
  - drivers/usb/host/xhci-mem.c:xhci_slot_copy
  - drivers/usb/host/xhci-mem.c:xhci_setup_addressable_virt_dev
Direct callers:
  - drivers/usb/host/xhci.c:xhci_update_hub_device
  - drivers/usb/host/xhci.c:xhci_change_max_exit_latency
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_free_dev
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-dbg.c:xhci_get_slot_state
  - drivers/usb/host/xhci-debugfs.c:xhci_slot_context_show
```
**Symbols:**

```
ffffffff8183ae10-ffffffff8183ae39: xhci_get_slot_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct xhci_slot_ctx *xhci_get_slot_ctx(struct xhci_hcd *xhci, struct xhci_container_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff8190eda5)
Location: drivers/usb/host/xhci-mem.c:504
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_slot_copy
  - drivers/usb/host/xhci-mem.c:xhci_slot_copy
  - drivers/usb/host/xhci-mem.c:xhci_setup_addressable_virt_dev
Direct callers:
  - drivers/usb/host/xhci.c:xhci_update_hub_device
  - drivers/usb/host/xhci.c:xhci_change_max_exit_latency
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_free_dev
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_zero_in_ctx
  - drivers/usb/host/xhci-ring.c:xhci_handle_cmd_addr_dev
  - drivers/usb/host/xhci-ring.c:xhci_handle_cmd_disable_slot
  - drivers/usb/host/xhci-dbg.c:xhci_get_slot_state
  - drivers/usb/host/xhci-debugfs.c:xhci_slot_context_show
```
**Symbols:**

```
ffffffff8190d860-ffffffff8190d889: xhci_get_slot_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct xhci_slot_ctx *xhci_get_slot_ctx(struct xhci_hcd *xhci, struct xhci_container_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff81916905)
Location: drivers/usb/host/xhci-mem.c:513
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_slot_copy
  - drivers/usb/host/xhci-mem.c:xhci_slot_copy
  - drivers/usb/host/xhci-mem.c:xhci_setup_addressable_virt_dev
Direct callers:
  - drivers/usb/host/xhci.c:xhci_update_hub_device
  - drivers/usb/host/xhci.c:xhci_change_max_exit_latency
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_free_dev
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_zero_in_ctx
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_handle_cmd_disable_slot
  - drivers/usb/host/xhci-dbg.c:xhci_get_slot_state
  - drivers/usb/host/xhci-debugfs.c:xhci_slot_context_show
```
**Symbols:**

```
ffffffff81915400-ffffffff81915429: xhci_get_slot_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct xhci_slot_ctx *xhci_get_slot_ctx(struct xhci_hcd *xhci, struct xhci_container_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff818f9d85)
Location: drivers/usb/host/xhci-mem.c:513
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_slot_copy
  - drivers/usb/host/xhci-mem.c:xhci_slot_copy
  - drivers/usb/host/xhci-mem.c:xhci_setup_addressable_virt_dev
Direct callers:
  - drivers/usb/host/xhci.c:xhci_update_hub_device
  - drivers/usb/host/xhci.c:xhci_change_max_exit_latency
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_free_dev
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_zero_in_ctx
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-dbg.c:xhci_get_slot_state
  - drivers/usb/host/xhci-debugfs.c:xhci_slot_context_show
```
**Symbols:**

```
ffffffff818f8910-ffffffff818f8939: xhci_get_slot_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct xhci_slot_ctx *xhci_get_slot_ctx(struct xhci_hcd *xhci, struct xhci_container_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff81998a15)
Location: drivers/usb/host/xhci-mem.c:513
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_slot_copy
  - drivers/usb/host/xhci-mem.c:xhci_slot_copy
  - drivers/usb/host/xhci-mem.c:xhci_setup_addressable_virt_dev
Direct callers:
  - drivers/usb/host/xhci.c:xhci_update_hub_device
  - drivers/usb/host/xhci.c:xhci_change_max_exit_latency
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_free_dev
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_zero_in_ctx
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-dbg.c:xhci_get_slot_state
  - drivers/usb/host/xhci-debugfs.c:xhci_slot_context_show
```
**Symbols:**

```
ffffffff81997070-ffffffff81997099: xhci_get_slot_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct xhci_slot_ctx *xhci_get_slot_ctx(struct xhci_hcd *xhci, struct xhci_container_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff81af59f5)
Location: drivers/usb/host/xhci-mem.c:512
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_slot_copy
  - drivers/usb/host/xhci-mem.c:xhci_slot_copy
  - drivers/usb/host/xhci-mem.c:xhci_setup_addressable_virt_dev
Direct callers:
  - drivers/usb/host/xhci.c:xhci_update_hub_device
  - drivers/usb/host/xhci.c:xhci_change_max_exit_latency
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_free_dev
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_zero_in_ctx
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-dbg.c:xhci_get_slot_state
  - drivers/usb/host/xhci-debugfs.c:xhci_slot_context_show
```
**Symbols:**

```
ffffffff81af3f30-ffffffff81af3f63: xhci_get_slot_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct xhci_slot_ctx *xhci_get_slot_ctx(struct xhci_hcd *xhci, struct xhci_container_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff81c832b5)
Location: drivers/usb/host/xhci-mem.c:512
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_slot_copy
  - drivers/usb/host/xhci-mem.c:xhci_slot_copy
  - drivers/usb/host/xhci-mem.c:xhci_setup_addressable_virt_dev
Direct callers:
  - drivers/usb/host/xhci.c:xhci_update_hub_device
  - drivers/usb/host/xhci.c:xhci_change_max_exit_latency
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_free_dev
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_zero_in_ctx
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-dbg.c:xhci_get_slot_state
  - drivers/usb/host/xhci-debugfs.c:xhci_slot_context_show
```
**Symbols:**

```
ffffffff81c81550-ffffffff81c81583: xhci_get_slot_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct xhci_slot_ctx *xhci_get_slot_ctx(struct xhci_hcd *xhci, struct xhci_container_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff81ce9ff5)
Location: drivers/usb/host/xhci-mem.c:504
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_slot_copy
  - drivers/usb/host/xhci-mem.c:xhci_slot_copy
  - drivers/usb/host/xhci-mem.c:xhci_setup_addressable_virt_dev
Direct callers:
  - drivers/usb/host/xhci.c:xhci_update_hub_device
  - drivers/usb/host/xhci.c:xhci_change_max_exit_latency
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_free_dev
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_zero_in_ctx
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-dbg.c:xhci_get_slot_state
  - drivers/usb/host/xhci-debugfs.c:xhci_slot_context_show
```
**Symbols:**

```
ffffffff81ce8260-ffffffff81ce8293: xhci_get_slot_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct xhci_slot_ctx *xhci_get_slot_ctx(struct xhci_hcd *xhci, struct xhci_container_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff81d9f825)
Location: drivers/usb/host/xhci-mem.c:515
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_slot_copy
  - drivers/usb/host/xhci-mem.c:xhci_slot_copy
  - drivers/usb/host/xhci-mem.c:xhci_setup_addressable_virt_dev
Direct callers:
  - drivers/usb/host/xhci.c:xhci_update_hub_device
  - drivers/usb/host/xhci.c:xhci_change_max_exit_latency
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_free_dev
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci.c:xhci_zero_in_ctx
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-dbg.c:xhci_get_slot_state
  - drivers/usb/host/xhci-debugfs.c:xhci_slot_context_show
```
**Symbols:**

```
ffffffff81d9da70-ffffffff81d9daa3: xhci_get_slot_ctx (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
struct xhci_slot_ctx *xhci_get_slot_ctx(struct xhci_hcd *xhci, struct xhci_container_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffff800010a79d84)
Location: drivers/usb/host/xhci-mem.c:504
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_slot_copy
  - drivers/usb/host/xhci-mem.c:xhci_slot_copy
  - drivers/usb/host/xhci-mem.c:xhci_setup_addressable_virt_dev
Direct callers:
  - drivers/usb/host/xhci.c:xhci_update_hub_device
  - drivers/usb/host/xhci.c:xhci_change_max_exit_latency
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_free_dev
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-dbg.c:xhci_get_slot_state
  - drivers/usb/host/xhci-mtk-sch.c:xhci_mtk_drop_ep_quirk
  - drivers/usb/host/xhci-mtk-sch.c:xhci_mtk_add_ep_quirk
  - drivers/usb/host/xhci-debugfs.c:xhci_slot_context_show
```
**Symbols:**

```
ffff800010a78978-ffff800010a789c8: xhci_get_slot_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct xhci_slot_ctx *xhci_get_slot_ctx(struct xhci_hcd *xhci, struct xhci_container_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (c0b4d76c)
Location: drivers/usb/host/xhci-mem.c:504
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_slot_copy
  - drivers/usb/host/xhci-mem.c:xhci_slot_copy
  - drivers/usb/host/xhci-mem.c:xhci_setup_addressable_virt_dev
Direct callers:
  - drivers/usb/host/xhci.c:xhci_update_hub_device
  - drivers/usb/host/xhci.c:xhci_change_max_exit_latency
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_free_dev
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_handle_cmd_set_deq
  - drivers/usb/host/xhci-dbg.c:xhci_get_slot_state
  - drivers/usb/host/xhci-mtk-sch.c:xhci_mtk_drop_ep_quirk
  - drivers/usb/host/xhci-mtk-sch.c:xhci_mtk_add_ep_quirk
  - drivers/usb/host/xhci-debugfs.c:xhci_slot_context_show
```
**Symbols:**

```
c0b4c550-c0b4c590: xhci_get_slot_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct xhci_slot_ctx *xhci_get_slot_ctx(struct xhci_hcd *xhci, struct xhci_container_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (c000000000b514b8)
Location: drivers/usb/host/xhci-mem.c:504
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_slot_copy
  - drivers/usb/host/xhci-mem.c:xhci_slot_copy
  - drivers/usb/host/xhci-mem.c:xhci_setup_addressable_virt_dev
Direct callers:
  - drivers/usb/host/xhci.c:xhci_update_hub_device
  - drivers/usb/host/xhci.c:xhci_change_max_exit_latency
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_free_dev
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-dbg.c:xhci_get_slot_state
  - drivers/usb/host/xhci-debugfs.c:xhci_slot_context_show
```
**Symbols:**

```
c000000000b4fde0-c000000000b4fe2c: xhci_get_slot_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct xhci_slot_ctx *xhci_get_slot_ctx(struct xhci_hcd *xhci, struct xhci_container_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffe000691546)
Location: drivers/usb/host/xhci-mem.c:504
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_slot_copy
  - drivers/usb/host/xhci-mem.c:xhci_slot_copy
  - drivers/usb/host/xhci-mem.c:xhci_setup_addressable_virt_dev
Direct callers:
  - drivers/usb/host/xhci.c:xhci_update_hub_device
  - drivers/usb/host/xhci.c:xhci_change_max_exit_latency
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_free_dev
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-dbg.c:xhci_get_slot_state
  - drivers/usb/host/xhci-debugfs.c:xhci_slot_context_show
```
**Symbols:**

```
ffffffe0006903fc-ffffffe000690440: xhci_get_slot_ctx (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
struct xhci_slot_ctx *xhci_get_slot_ctx(struct xhci_hcd *xhci, struct xhci_container_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff817f4385)
Location: drivers/usb/host/xhci-mem.c:504
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_slot_copy
  - drivers/usb/host/xhci-mem.c:xhci_slot_copy
  - drivers/usb/host/xhci-mem.c:xhci_setup_addressable_virt_dev
Direct callers:
  - drivers/usb/host/xhci.c:xhci_update_hub_device
  - drivers/usb/host/xhci.c:xhci_change_max_exit_latency
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_free_dev
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-dbg.c:xhci_get_slot_state
  - drivers/usb/host/xhci-debugfs.c:xhci_slot_context_show
```
**Symbols:**

```
ffffffff817f31c0-ffffffff817f31e9: xhci_get_slot_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct xhci_slot_ctx *xhci_get_slot_ctx(struct xhci_hcd *xhci, struct xhci_container_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff817b9525)
Location: drivers/usb/host/xhci-mem.c:504
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_slot_copy
  - drivers/usb/host/xhci-mem.c:xhci_slot_copy
  - drivers/usb/host/xhci-mem.c:xhci_setup_addressable_virt_dev
Direct callers:
  - drivers/usb/host/xhci.c:xhci_update_hub_device
  - drivers/usb/host/xhci.c:xhci_change_max_exit_latency
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_free_dev
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-dbg.c:xhci_get_slot_state
  - drivers/usb/host/xhci-debugfs.c:xhci_slot_context_show
```
**Symbols:**

```
ffffffff817b8360-ffffffff817b8389: xhci_get_slot_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct xhci_slot_ctx *xhci_get_slot_ctx(struct xhci_hcd *xhci, struct xhci_container_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff81830e55)
Location: drivers/usb/host/xhci-mem.c:504
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_slot_copy
  - drivers/usb/host/xhci-mem.c:xhci_slot_copy
  - drivers/usb/host/xhci-mem.c:xhci_setup_addressable_virt_dev
Direct callers:
  - drivers/usb/host/xhci.c:xhci_update_hub_device
  - drivers/usb/host/xhci.c:xhci_change_max_exit_latency
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_free_dev
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-dbg.c:xhci_get_slot_state
  - drivers/usb/host/xhci-debugfs.c:xhci_slot_context_show
```
**Symbols:**

```
ffffffff8182fc90-ffffffff8182fcb9: xhci_get_slot_ctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct xhci_slot_ctx *xhci_get_slot_ctx(struct xhci_hcd *xhci, struct xhci_container_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff8184b025)
Location: drivers/usb/host/xhci-mem.c:504
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_slot_copy
  - drivers/usb/host/xhci-mem.c:xhci_slot_copy
  - drivers/usb/host/xhci-mem.c:xhci_setup_addressable_virt_dev
Direct callers:
  - drivers/usb/host/xhci.c:xhci_update_hub_device
  - drivers/usb/host/xhci.c:xhci_change_max_exit_latency
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_setup_device
  - drivers/usb/host/xhci.c:xhci_alloc_dev
  - drivers/usb/host/xhci.c:xhci_free_dev
  - drivers/usb/host/xhci.c:xhci_configure_endpoint
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-dbg.c:xhci_get_slot_state
  - drivers/usb/host/xhci-debugfs.c:xhci_slot_context_show
```
**Symbols:**

```
ffffffff81849e30-ffffffff81849e59: xhci_get_slot_ctx (STB_GLOBAL)
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
