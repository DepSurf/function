# Function: <code>__virtio_test_bit</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio.c (0)
Location: include/linux/virtio_config.h:92
Inline: True
```
```
In drivers/virtio/virtio_ring.c (0)
Location: include/linux/virtio_config.h:92
Inline: True
```
```
In drivers/virtio/virtio_mmio.c (0)
Location: include/linux/virtio_config.h:92
Inline: True
```
```
In drivers/virtio/virtio_pci_modern.c (0)
Location: include/linux/virtio_config.h:92
Inline: True
```
```
In drivers/virtio/virtio_balloon.c (0)
Location: include/linux/virtio_config.h:92
Inline: True
```
```
In drivers/char/virtio_console.c (0)
Location: include/linux/virtio_config.h:92
Inline: True
```
```
In drivers/block/virtio_blk.c (0)
Location: include/linux/virtio_config.h:92
Inline: True
```
```
In drivers/net/virtio_net.c (ffffffff815f1a7a)
Location: include/linux/virtio_config.h:92
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:virtnet_set_mac_address
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio.c (ffffffff8150ead5)
Location: include/linux/virtio_config.h:92
Inline: True
Inline callers:
  - drivers/virtio/virtio.c:features_show
```
```
In drivers/virtio/virtio_ring.c (ffffffff8150f723)
Location: include/linux/virtio_config.h:92
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
```
```
In drivers/virtio/virtio_mmio.c (0)
Location: include/linux/virtio_config.h:92
Inline: True
```
```
In drivers/virtio/virtio_pci_modern.c (0)
Location: include/linux/virtio_config.h:92
Inline: True
```
```
In drivers/virtio/virtio_balloon.c (0)
Location: include/linux/virtio_config.h:92
Inline: True
```
```
In drivers/char/virtio_console.c (0)
Location: include/linux/virtio_config.h:92
Inline: True
```
```
In drivers/block/virtio_blk.c (ffffffff815c70e0)
Location: include/linux/virtio_config.h:92
Inline: True
Inline callers:
  - drivers/block/virtio_blk.c:virtblk_get_cache_mode
```
```
In drivers/net/virtio_net.c (ffffffff8165395d)
Location: include/linux/virtio_config.h:92
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:virtnet_find_vqs
  - drivers/net/virtio_net.c:virtnet_set_mac_address
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio.c (ffffffff8153ac35)
Location: include/linux/virtio_config.h:92
Inline: True
Inline callers:
  - drivers/virtio/virtio.c:features_show
```
```
In drivers/virtio/virtio_ring.c (ffffffff8153b8c3)
Location: include/linux/virtio_config.h:92
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
```
```
In drivers/virtio/virtio_mmio.c (0)
Location: include/linux/virtio_config.h:92
Inline: True
```
```
In drivers/virtio/virtio_pci_modern.c (0)
Location: include/linux/virtio_config.h:92
Inline: True
```
```
In drivers/virtio/virtio_balloon.c (0)
Location: include/linux/virtio_config.h:92
Inline: True
```
```
In drivers/char/virtio_console.c (0)
Location: include/linux/virtio_config.h:92
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio.c (ffffffff8154e457)
Location: include/linux/virtio_config.h:97
Inline: True
Inline callers:
  - drivers/virtio/virtio.c:features_show
```
```
In drivers/virtio/virtio_ring.c (ffffffff8154f201)
Location: include/linux/virtio_config.h:97
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
```
```
In drivers/virtio/virtio_mmio.c (0)
Location: include/linux/virtio_config.h:97
Inline: True
```
```
In drivers/virtio/virtio_pci_modern.c (0)
Location: include/linux/virtio_config.h:97
Inline: True
```
```
In drivers/virtio/virtio_balloon.c (0)
Location: include/linux/virtio_config.h:97
Inline: True
```
```
In drivers/char/virtio_console.c (0)
Location: include/linux/virtio_config.h:97
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio.c (ffffffff815b1b57)
Location: include/linux/virtio_config.h:98
Inline: True
Inline callers:
  - drivers/virtio/virtio.c:features_show
```
```
In drivers/virtio/virtio_ring.c (ffffffff815b29c1)
Location: include/linux/virtio_config.h:98
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
```
```
In drivers/virtio/virtio_mmio.c (0)
Location: include/linux/virtio_config.h:98
Inline: True
```
```
In drivers/virtio/virtio_pci_modern.c (0)
Location: include/linux/virtio_config.h:98
Inline: True
```
```
In drivers/virtio/virtio_balloon.c (0)
Location: include/linux/virtio_config.h:98
Inline: True
```
```
In drivers/char/virtio_console.c (0)
Location: include/linux/virtio_config.h:98
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio.c (ffffffff815e9fa8)
Location: include/linux/virtio_config.h:98
Inline: True
Inline callers:
  - drivers/virtio/virtio.c:features_show
```
```
In drivers/virtio/virtio_ring.c (ffffffff815eadf5)
Location: include/linux/virtio_config.h:98
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_delayed
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_delayed
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_delayed
  - drivers/virtio/virtio_ring.c:virtqueue_poll
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_prepare
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_prepare
  - drivers/virtio/virtio_ring.c:virtqueue_disable_cb
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx
  - drivers/virtio/virtio_ring.c:detach_buf
  - drivers/virtio/virtio_ring.c:detach_buf
  - drivers/virtio/virtio_ring.c:detach_buf
  - drivers/virtio/virtio_ring.c:detach_buf
  - drivers/virtio/virtio_ring.c:detach_buf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_sgs
  - drivers/virtio/virtio_ring.c:virtqueue_add_sgs
  - drivers/virtio/virtio_ring.c:virtqueue_add_sgs
  - drivers/virtio/virtio_ring.c:virtqueue_add_sgs
  - drivers/virtio/virtio_ring.c:virtqueue_add_sgs
  - drivers/virtio/virtio_ring.c:virtqueue_add_sgs
  - drivers/virtio/virtio_ring.c:virtqueue_add_sgs
  - drivers/virtio/virtio_ring.c:virtqueue_add_sgs
  - drivers/virtio/virtio_ring.c:virtqueue_add_sgs
  - drivers/virtio/virtio_ring.c:virtqueue_add_sgs
  - drivers/virtio/virtio_ring.c:virtqueue_add_sgs
  - drivers/virtio/virtio_ring.c:virtqueue_add_sgs
  - drivers/virtio/virtio_ring.c:virtqueue_add_sgs
  - drivers/virtio/virtio_ring.c:virtqueue_add_sgs
  - drivers/virtio/virtio_ring.c:virtqueue_add_sgs
  - drivers/virtio/virtio_ring.c:virtqueue_add_sgs
```
```
In drivers/virtio/virtio_mmio.c (ffffffff815ec55d)
Location: include/linux/virtio_config.h:98
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:vm_finalize_features
```
```
In drivers/virtio/virtio_pci_modern.c (ffffffff815ed519)
Location: include/linux/virtio_config.h:98
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_modern.c:vp_finalize_features
```
```
In drivers/virtio/virtio_pci_common.c (ffffffff815eea12)
Location: include/linux/virtio_config.h:98
Inline: True
```
```
In drivers/virtio/virtio_balloon.c (ffffffff815f09ac)
Location: include/linux/virtio_config.h:98
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_restore
  - drivers/virtio/virtio_balloon.c:virtballoon_restore
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:virtballoon_oom_notify
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:leak_balloon
```
```
In drivers/char/virtio_console.c (ffffffff8164cb99)
Location: include/linux/virtio_config.h:98
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:virtcons_restore
  - drivers/char/virtio_console.c:virtcons_freeze
  - drivers/char/virtio_console.c:virtcons_freeze
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_remove
  - drivers/char/virtio_console.c:init_vqs
  - drivers/char/virtio_console.c:init_vqs
  - drivers/char/virtio_console.c:init_vqs
  - drivers/char/virtio_console.c:config_work_handler
  - drivers/char/virtio_console.c:config_work_handler
  - drivers/char/virtio_console.c:config_work_handler
  - drivers/char/virtio_console.c:config_intr
  - drivers/char/virtio_console.c:add_port
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio.c (ffffffff816044b8)
Location: include/linux/virtio_config.h:104
Inline: True
Inline callers:
  - drivers/virtio/virtio.c:features_show
```
```
In drivers/virtio/virtio_ring.c (ffffffff81605d75)
Location: include/linux/virtio_config.h:104
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:vring_create_virtqueue
  - drivers/virtio/virtio_ring.c:vring_create_virtqueue
  - drivers/virtio/virtio_ring.c:vring_create_virtqueue
  - drivers/virtio/virtio_ring.c:vring_create_virtqueue
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:virtqueue_detach_unused_buf
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_delayed
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_delayed
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_delayed
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_prepare
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_prepare
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_kick_prepare
  - drivers/virtio/virtio_ring.c:virtqueue_kick_prepare
  - drivers/virtio/virtio_ring.c:virtqueue_add
  - drivers/virtio/virtio_ring.c:virtqueue_add
  - drivers/virtio/virtio_ring.c:virtqueue_add
  - drivers/virtio/virtio_ring.c:virtqueue_add
  - drivers/virtio/virtio_ring.c:virtqueue_add
  - drivers/virtio/virtio_ring.c:virtqueue_add
  - drivers/virtio/virtio_ring.c:virtqueue_add
  - drivers/virtio/virtio_ring.c:virtqueue_add
  - drivers/virtio/virtio_ring.c:virtqueue_add
  - drivers/virtio/virtio_ring.c:virtqueue_add
  - drivers/virtio/virtio_ring.c:virtqueue_add
  - drivers/virtio/virtio_ring.c:virtqueue_add
  - drivers/virtio/virtio_ring.c:virtqueue_add
  - drivers/virtio/virtio_ring.c:virtqueue_add
  - drivers/virtio/virtio_ring.c:virtqueue_add
  - drivers/virtio/virtio_ring.c:virtqueue_add
  - drivers/virtio/virtio_ring.c:virtqueue_add
  - drivers/virtio/virtio_ring.c:detach_buf_split
  - drivers/virtio/virtio_ring.c:detach_buf_split
  - drivers/virtio/virtio_ring.c:detach_buf_split
  - drivers/virtio/virtio_ring.c:detach_buf_split
  - drivers/virtio/virtio_ring.c:detach_buf_split
```
```
In drivers/virtio/virtio_mmio.c (ffffffff8160712d)
Location: include/linux/virtio_config.h:104
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:vm_finalize_features
```
```
In drivers/virtio/virtio_pci_modern.c (ffffffff81607df9)
Location: include/linux/virtio_config.h:104
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_modern.c:vp_finalize_features
```
```
In drivers/virtio/virtio_pci_common.c (ffffffff81609112)
Location: include/linux/virtio_config.h:104
Inline: True
```
```
In drivers/virtio/virtio_balloon.c (ffffffff8160b68c)
Location: include/linux/virtio_config.h:104
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_restore
  - drivers/virtio/virtio_balloon.c:virtballoon_restore
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtio_balloon_shrinker_scan
  - drivers/virtio/virtio_balloon.c:report_free_page_func
  - drivers/virtio/virtio_balloon.c:report_free_page_func
  - drivers/virtio/virtio_balloon.c:report_free_page_func
  - drivers/virtio/virtio_balloon.c:virtio_balloon_cmd_id_received
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:virtballoon_changed
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:leak_balloon
```
```
In drivers/char/virtio_console.c (ffffffff8166a5c9)
Location: include/linux/virtio_config.h:104
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:virtcons_restore
  - drivers/char/virtio_console.c:virtcons_freeze
  - drivers/char/virtio_console.c:virtcons_freeze
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_remove
  - drivers/char/virtio_console.c:init_vqs
  - drivers/char/virtio_console.c:init_vqs
  - drivers/char/virtio_console.c:init_vqs
  - drivers/char/virtio_console.c:config_work_handler
  - drivers/char/virtio_console.c:config_work_handler
  - drivers/char/virtio_console.c:config_work_handler
  - drivers/char/virtio_console.c:config_intr
  - drivers/char/virtio_console.c:add_port
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio.c (ffffffff81636ea8)
Location: include/linux/virtio_config.h:104
Inline: True
Inline callers:
  - drivers/virtio/virtio.c:features_show
```
```
In drivers/virtio/virtio_ring.c (ffffffff81637ef5)
Location: include/linux/virtio_config.h:104
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:vring_create_virtqueue
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:virtqueue_detach_unused_buf
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_delayed
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_delayed
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_delayed
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_prepare
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_prepare
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_kick_prepare
  - drivers/virtio/virtio_ring.c:virtqueue_kick_prepare
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:detach_buf_split
  - drivers/virtio/virtio_ring.c:detach_buf_split
  - drivers/virtio/virtio_ring.c:detach_buf_split
  - drivers/virtio/virtio_ring.c:detach_buf_split
  - drivers/virtio/virtio_ring.c:detach_buf_split
```
```
In drivers/virtio/virtio_mmio.c (ffffffff8163af6d)
Location: include/linux/virtio_config.h:104
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:vm_finalize_features
```
```
In drivers/virtio/virtio_pci_modern.c (ffffffff8163bc59)
Location: include/linux/virtio_config.h:104
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_modern.c:vp_finalize_features
```
```
In drivers/virtio/virtio_pci_common.c (ffffffff8163cf72)
Location: include/linux/virtio_config.h:104
Inline: True
```
```
In drivers/virtio/virtio_balloon.c (ffffffff8163f580)
Location: include/linux/virtio_config.h:104
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_restore
  - drivers/virtio/virtio_balloon.c:virtballoon_restore
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtio_balloon_shrinker_scan
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:report_free_page_func
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtio_balloon_cmd_id_received
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:virtballoon_changed
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:leak_balloon
  - drivers/virtio/virtio_balloon.c:leak_balloon
```
```
In drivers/char/virtio_console.c (ffffffff816a03c9)
Location: include/linux/virtio_config.h:104
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:virtcons_restore
  - drivers/char/virtio_console.c:virtcons_freeze
  - drivers/char/virtio_console.c:virtcons_freeze
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_remove
  - drivers/char/virtio_console.c:init_vqs
  - drivers/char/virtio_console.c:init_vqs
  - drivers/char/virtio_console.c:init_vqs
  - drivers/char/virtio_console.c:config_work_handler
  - drivers/char/virtio_console.c:config_work_handler
  - drivers/char/virtio_console.c:config_work_handler
  - drivers/char/virtio_console.c:config_intr
  - drivers/char/virtio_console.c:add_port
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio.c (ffffffff81658c08)
Location: include/linux/virtio_config.h:104
Inline: True
Inline callers:
  - drivers/virtio/virtio.c:features_show
```
```
In drivers/virtio/virtio_ring.c (ffffffff81659ce5)
Location: include/linux/virtio_config.h:104
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:vring_create_virtqueue
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:virtqueue_detach_unused_buf
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_delayed
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_delayed
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_delayed
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_prepare
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_prepare
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_kick_prepare
  - drivers/virtio/virtio_ring.c:virtqueue_kick_prepare
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:detach_buf_split
  - drivers/virtio/virtio_ring.c:detach_buf_split
  - drivers/virtio/virtio_ring.c:detach_buf_split
  - drivers/virtio/virtio_ring.c:detach_buf_split
  - drivers/virtio/virtio_ring.c:detach_buf_split
```
```
In drivers/virtio/virtio_mmio.c (ffffffff8165d42d)
Location: include/linux/virtio_config.h:104
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:vm_finalize_features
```
```
In drivers/virtio/virtio_pci_modern.c (ffffffff8165e109)
Location: include/linux/virtio_config.h:104
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_modern.c:vp_finalize_features
```
```
In drivers/virtio/virtio_pci_common.c (ffffffff8165f452)
Location: include/linux/virtio_config.h:104
Inline: True
```
```
In drivers/virtio/virtio_balloon.c (ffffffff816619a0)
Location: include/linux/virtio_config.h:104
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_restore
  - drivers/virtio/virtio_balloon.c:virtballoon_restore
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:remove_common
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtio_balloon_shrinker_scan
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:report_free_page_func
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtio_balloon_cmd_id_received
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:virtballoon_changed
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:leak_balloon
  - drivers/virtio/virtio_balloon.c:leak_balloon
```
```
In drivers/char/virtio_console.c (ffffffff816c3179)
Location: include/linux/virtio_config.h:104
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:virtcons_restore
  - drivers/char/virtio_console.c:virtcons_freeze
  - drivers/char/virtio_console.c:virtcons_freeze
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_remove
  - drivers/char/virtio_console.c:init_vqs
  - drivers/char/virtio_console.c:init_vqs
  - drivers/char/virtio_console.c:init_vqs
  - drivers/char/virtio_console.c:config_work_handler
  - drivers/char/virtio_console.c:config_work_handler
  - drivers/char/virtio_console.c:config_work_handler
  - drivers/char/virtio_console.c:config_intr
  - drivers/char/virtio_console.c:add_port
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio.c (ffffffff817092c8)
Location: include/linux/virtio_config.h:104
Inline: True
Inline callers:
  - drivers/virtio/virtio.c:features_show
```
```
In drivers/virtio/virtio_ring.c (ffffffff8170b295)
Location: include/linux/virtio_config.h:104
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:vring_create_virtqueue
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:virtqueue_detach_unused_buf
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_delayed
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_delayed
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_delayed
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_prepare
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_prepare
  - drivers/virtio/virtio_ring.c:virtqueue_kick_prepare
  - drivers/virtio/virtio_ring.c:virtqueue_kick_prepare
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx_split
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx_split
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx_split
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx_split
  - drivers/virtio/virtio_ring.c:detach_buf_split
  - drivers/virtio/virtio_ring.c:detach_buf_split
  - drivers/virtio/virtio_ring.c:detach_buf_split
  - drivers/virtio/virtio_ring.c:detach_buf_split
  - drivers/virtio/virtio_ring.c:detach_buf_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtio_max_dma_size
```
```
In drivers/virtio/virtio_mmio.c (ffffffff8170c550)
Location: include/linux/virtio_config.h:104
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:vm_finalize_features
```
```
In drivers/virtio/virtio_pci_modern.c (ffffffff8170d219)
Location: include/linux/virtio_config.h:104
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_modern.c:vp_finalize_features
```
```
In drivers/virtio/virtio_pci_common.c (ffffffff8170e4b2)
Location: include/linux/virtio_config.h:104
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:virtio_pci_sriov_configure
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81710547)
Location: include/linux/virtio_config.h:104
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_validate
  - drivers/virtio/virtio_balloon.c:virtballoon_restore
  - drivers/virtio/virtio_balloon.c:virtballoon_restore
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:remove_common
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:report_free_page_func
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtio_balloon_cmd_id_received
  - drivers/virtio/virtio_balloon.c:virtio_balloon_cmd_id_received
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:update_balloon_size_func
  - drivers/virtio/virtio_balloon.c:update_balloon_size_func
  - drivers/virtio/virtio_balloon.c:update_balloon_size
  - drivers/virtio/virtio_balloon.c:update_balloon_size
  - drivers/virtio/virtio_balloon.c:virtballoon_changed
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:leak_balloon
  - drivers/virtio/virtio_balloon.c:leak_balloon
  - drivers/virtio/virtio_balloon.c:fill_balloon
  - drivers/virtio/virtio_balloon.c:fill_balloon
```
```
In drivers/char/virtio_console.c (ffffffff81776b65)
Location: include/linux/virtio_config.h:104
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:virtcons_restore
  - drivers/char/virtio_console.c:virtcons_restore
  - drivers/char/virtio_console.c:virtcons_restore
  - drivers/char/virtio_console.c:virtcons_freeze
  - drivers/char/virtio_console.c:virtcons_freeze
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_remove
  - drivers/char/virtio_console.c:init_vqs
  - drivers/char/virtio_console.c:init_vqs
  - drivers/char/virtio_console.c:init_vqs
  - drivers/char/virtio_console.c:config_work_handler
  - drivers/char/virtio_console.c:config_work_handler
  - drivers/char/virtio_console.c:config_work_handler
  - drivers/char/virtio_console.c:config_intr
  - drivers/char/virtio_console.c:init_port_console
  - drivers/char/virtio_console.c:port_fops_open
  - drivers/char/virtio_console.c:port_fops_release
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio.c (ffffffff81726278)
Location: include/linux/virtio_config.h:113
Inline: True
Inline callers:
  - drivers/virtio/virtio.c:features_show
```
```
In drivers/virtio/virtio_ring.c (ffffffff817280f5)
Location: include/linux/virtio_config.h:113
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:vring_create_virtqueue
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:virtqueue_detach_unused_buf
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_delayed
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_delayed
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_delayed
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_delayed
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_prepare
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_prepare
  - drivers/virtio/virtio_ring.c:virtqueue_kick_prepare
  - drivers/virtio/virtio_ring.c:virtqueue_kick_prepare
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx_split
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx_split
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx_split
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx_split
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx_split
  - drivers/virtio/virtio_ring.c:detach_buf_split
  - drivers/virtio/virtio_ring.c:detach_buf_split
  - drivers/virtio/virtio_ring.c:detach_buf_split
  - drivers/virtio/virtio_ring.c:detach_buf_split
  - drivers/virtio/virtio_ring.c:detach_buf_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtio_max_dma_size
```
```
In drivers/virtio/virtio_mmio.c (ffffffff81729370)
Location: include/linux/virtio_config.h:113
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:vm_finalize_features
```
```
In drivers/virtio/virtio_pci_modern.c (ffffffff8172a129)
Location: include/linux/virtio_config.h:113
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_modern.c:vp_finalize_features
```
```
In drivers/virtio/virtio_pci_common.c (ffffffff8172b282)
Location: include/linux/virtio_config.h:113
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:virtio_pci_sriov_configure
```
```
In drivers/virtio/virtio_balloon.c (ffffffff8172d111)
Location: include/linux/virtio_config.h:113
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_validate
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:remove_common
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:report_free_page_func
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:virtballoon_changed
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:leak_balloon
  - drivers/virtio/virtio_balloon.c:leak_balloon
  - drivers/virtio/virtio_balloon.c:fill_balloon
  - drivers/virtio/virtio_balloon.c:fill_balloon
```
```
In drivers/char/virtio_console.c (ffffffff81791895)
Location: include/linux/virtio_config.h:113
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:virtcons_restore
  - drivers/char/virtio_console.c:virtcons_restore
  - drivers/char/virtio_console.c:virtcons_restore
  - drivers/char/virtio_console.c:virtcons_freeze
  - drivers/char/virtio_console.c:virtcons_freeze
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_remove
  - drivers/char/virtio_console.c:init_vqs
  - drivers/char/virtio_console.c:init_vqs
  - drivers/char/virtio_console.c:init_vqs
  - drivers/char/virtio_console.c:config_work_handler
  - drivers/char/virtio_console.c:config_work_handler
  - drivers/char/virtio_console.c:config_work_handler
  - drivers/char/virtio_console.c:config_intr
  - drivers/char/virtio_console.c:init_port_console
  - drivers/char/virtio_console.c:port_fops_open
  - drivers/char/virtio_console.c:port_fops_release
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio.c (ffffffff81709e88)
Location: include/linux/virtio_config.h:113
Inline: True
Inline callers:
  - drivers/virtio/virtio.c:features_show
```
```
In drivers/virtio/virtio_ring.c (ffffffff8170c625)
Location: include/linux/virtio_config.h:113
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:vring_create_virtqueue
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:virtqueue_detach_unused_buf
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_delayed
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_delayed
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_delayed
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_delayed
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_prepare
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_prepare
  - drivers/virtio/virtio_ring.c:virtqueue_kick_prepare
  - drivers/virtio/virtio_ring.c:virtqueue_kick_prepare
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx_split
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx_split
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx_split
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx_split
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx_split
  - drivers/virtio/virtio_ring.c:detach_buf_split
  - drivers/virtio/virtio_ring.c:detach_buf_split
  - drivers/virtio/virtio_ring.c:detach_buf_split
  - drivers/virtio/virtio_ring.c:detach_buf_split
  - drivers/virtio/virtio_ring.c:detach_buf_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtio_max_dma_size
```
```
In drivers/virtio/virtio_mmio.c (ffffffff8170daff)
Location: include/linux/virtio_config.h:113
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:vm_finalize_features
```
```
In drivers/virtio/virtio_pci_modern.c (ffffffff8170e969)
Location: include/linux/virtio_config.h:113
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_modern.c:vp_finalize_features
```
```
In drivers/virtio/virtio_pci_common.c (ffffffff8170f002)
Location: include/linux/virtio_config.h:113
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:virtio_pci_sriov_configure
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81710571)
Location: include/linux/virtio_config.h:113
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_validate
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:remove_common
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:report_free_page_func
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:virtballoon_changed
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:leak_balloon
  - drivers/virtio/virtio_balloon.c:leak_balloon
  - drivers/virtio/virtio_balloon.c:fill_balloon
  - drivers/virtio/virtio_balloon.c:fill_balloon
```
```
In drivers/char/virtio_console.c (ffffffff81773e05)
Location: include/linux/virtio_config.h:113
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:virtcons_restore
  - drivers/char/virtio_console.c:virtcons_freeze
  - drivers/char/virtio_console.c:virtcons_freeze
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_remove
  - drivers/char/virtio_console.c:init_vqs
  - drivers/char/virtio_console.c:init_vqs
  - drivers/char/virtio_console.c:init_vqs
  - drivers/char/virtio_console.c:config_work_handler
  - drivers/char/virtio_console.c:config_work_handler
  - drivers/char/virtio_console.c:config_work_handler
  - drivers/char/virtio_console.c:config_intr
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio.c (ffffffff81785afd)
Location: include/linux/virtio_config.h:114
Inline: True
Inline callers:
  - drivers/virtio/virtio.c:virtio_features_ok
  - drivers/virtio/virtio.c:virtio_features_ok
  - drivers/virtio/virtio.c:virtio_features_ok
  - drivers/virtio/virtio.c:features_show
```
```
In drivers/virtio/virtio_ring.c (ffffffff81788a15)
Location: include/linux/virtio_config.h:114
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:vring_create_virtqueue
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:virtqueue_detach_unused_buf
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_delayed
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_delayed
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_delayed
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_delayed
  - drivers/virtio/virtio_ring.c:virtqueue_poll
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_prepare
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_prepare
  - drivers/virtio/virtio_ring.c:virtqueue_kick_prepare
  - drivers/virtio/virtio_ring.c:virtqueue_kick_prepare
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx_split
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx_split
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx_split
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx_split
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx_split
  - drivers/virtio/virtio_ring.c:detach_buf_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
```
```
In drivers/virtio/virtio_mmio.c (ffffffff8178a35f)
Location: include/linux/virtio_config.h:114
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:vm_finalize_features
```
```
In drivers/virtio/virtio_pci_modern.c (ffffffff8178b299)
Location: include/linux/virtio_config.h:114
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_modern.c:vp_finalize_features
```
```
In drivers/virtio/virtio_pci_common.c (ffffffff8178b932)
Location: include/linux/virtio_config.h:114
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:virtio_pci_sriov_configure
```
```
In drivers/virtio/virtio_balloon.c (ffffffff8178cf4b)
Location: include/linux/virtio_config.h:114
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_validate
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:remove_common
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:report_free_page_func
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:virtballoon_changed
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:leak_balloon
  - drivers/virtio/virtio_balloon.c:leak_balloon
  - drivers/virtio/virtio_balloon.c:fill_balloon
  - drivers/virtio/virtio_balloon.c:fill_balloon
```
```
In drivers/char/virtio_console.c (ffffffff817fa1d9)
Location: include/linux/virtio_config.h:114
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:virtcons_restore
  - drivers/char/virtio_console.c:virtcons_freeze
  - drivers/char/virtio_console.c:virtcons_freeze
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_remove
  - drivers/char/virtio_console.c:init_vqs
  - drivers/char/virtio_console.c:init_vqs
  - drivers/char/virtio_console.c:init_vqs
  - drivers/char/virtio_console.c:config_work_handler
  - drivers/char/virtio_console.c:config_work_handler
  - drivers/char/virtio_console.c:config_work_handler
  - drivers/char/virtio_console.c:config_intr
```
```
In drivers/iommu/virtio-iommu.c (ffffffff8182f626)
Location: include/linux/virtio_config.h:114
Inline: True
Inline callers:
  - drivers/iommu/virtio-iommu.c:viommu_probe
  - drivers/iommu/virtio-iommu.c:viommu_probe
  - drivers/iommu/virtio-iommu.c:viommu_probe
  - drivers/iommu/virtio-iommu.c:viommu_probe
  - drivers/iommu/virtio-iommu.c:viommu_probe
  - drivers/iommu/virtio-iommu.c:viommu_probe
  - drivers/iommu/virtio-iommu.c:viommu_probe
  - drivers/iommu/virtio-iommu.c:viommu_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio.c (ffffffff818bc7f7)
Location: include/linux/virtio_config.h:120
Inline: True
Inline callers:
  - drivers/virtio/virtio.c:virtio_features_ok
  - drivers/virtio/virtio.c:virtio_features_ok
  - drivers/virtio/virtio.c:virtio_features_ok
  - drivers/virtio/virtio.c:features_show
```
```
In drivers/virtio/virtio_ring.c (ffffffff818bf048)
Location: include/linux/virtio_config.h:120
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:vring_create_virtqueue
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:virtqueue_detach_unused_buf
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_delayed
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_delayed
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_delayed
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_delayed
  - drivers/virtio/virtio_ring.c:virtqueue_poll
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_prepare
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_prepare
  - drivers/virtio/virtio_ring.c:virtqueue_kick_prepare
  - drivers/virtio/virtio_ring.c:virtqueue_kick_prepare
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx_split
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx_split
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx_split
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx_split
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx_split
  - drivers/virtio/virtio_ring.c:detach_buf_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
```
```
In drivers/virtio/virtio_mmio.c (ffffffff818c1b29)
Location: include/linux/virtio_config.h:120
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:vm_finalize_features
```
```
In drivers/virtio/virtio_pci_modern.c (ffffffff818c2d49)
Location: include/linux/virtio_config.h:120
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_modern.c:vp_finalize_features
```
```
In drivers/virtio/virtio_pci_common.c (ffffffff818c34c1)
Location: include/linux/virtio_config.h:120
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:virtio_pci_sriov_configure
```
```
In drivers/virtio/virtio_balloon.c (ffffffff818c504b)
Location: include/linux/virtio_config.h:120
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_validate
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:remove_common
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:report_free_page_func
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:virtballoon_changed
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:leak_balloon
  - drivers/virtio/virtio_balloon.c:leak_balloon
  - drivers/virtio/virtio_balloon.c:fill_balloon
  - drivers/virtio/virtio_balloon.c:fill_balloon
```
```
In drivers/char/virtio_console.c (ffffffff81939725)
Location: include/linux/virtio_config.h:120
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:virtcons_restore
  - drivers/char/virtio_console.c:virtcons_freeze
  - drivers/char/virtio_console.c:virtcons_freeze
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_remove
  - drivers/char/virtio_console.c:virtcons_remove
  - drivers/char/virtio_console.c:init_vqs
  - drivers/char/virtio_console.c:init_vqs
  - drivers/char/virtio_console.c:init_vqs
  - drivers/char/virtio_console.c:config_work_handler
  - drivers/char/virtio_console.c:config_work_handler
  - drivers/char/virtio_console.c:config_work_handler
  - drivers/char/virtio_console.c:config_intr
```
```
In drivers/iommu/virtio-iommu.c (ffffffff8197082a)
Location: include/linux/virtio_config.h:120
Inline: True
Inline callers:
  - drivers/iommu/virtio-iommu.c:viommu_probe
  - drivers/iommu/virtio-iommu.c:viommu_probe
  - drivers/iommu/virtio-iommu.c:viommu_probe
  - drivers/iommu/virtio-iommu.c:viommu_probe
  - drivers/iommu/virtio-iommu.c:viommu_probe
  - drivers/iommu/virtio-iommu.c:viommu_probe
  - drivers/iommu/virtio-iommu.c:viommu_probe
  - drivers/iommu/virtio-iommu.c:viommu_probe
  - drivers/iommu/virtio-iommu.c:viommu_attach_dev
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
In drivers/virtio/virtio.c (ffffffff81a0b4d7)
Location: include/linux/virtio_config.h:134
Inline: True
Inline callers:
  - drivers/virtio/virtio.c:virtio_features_ok
  - drivers/virtio/virtio.c:virtio_features_ok
  - drivers/virtio/virtio.c:virtio_features_ok
  - drivers/virtio/virtio.c:features_show
```
```
In drivers/virtio/virtio_ring.c (ffffffff81a0e733)
Location: include/linux/virtio_config.h:134
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:virtqueue_resize
  - drivers/virtio/virtio_ring.c:virtqueue_resize
  - drivers/virtio/virtio_ring.c:vring_create_virtqueue
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:virtqueue_detach_unused_buf
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_delayed
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_delayed
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_delayed
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_delayed
  - drivers/virtio/virtio_ring.c:virtqueue_poll
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_prepare
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_prepare
  - drivers/virtio/virtio_ring.c:virtqueue_kick_prepare
  - drivers/virtio/virtio_ring.c:virtqueue_kick_prepare
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx_split
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx_split
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx_split
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx_split
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx_split
  - drivers/virtio/virtio_ring.c:detach_buf_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
```
```
In drivers/virtio/virtio_mmio.c (ffffffff81a11ab9)
Location: include/linux/virtio_config.h:134
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:vm_finalize_features
```
```
In drivers/virtio/virtio_pci_modern.c (ffffffff81a135a6)
Location: include/linux/virtio_config.h:134
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_modern.c:vp_modern_disable_vq_and_reset
  - drivers/virtio/virtio_pci_modern.c:vp_finalize_features
```
```
In drivers/virtio/virtio_pci_common.c (ffffffff81a13af1)
Location: include/linux/virtio_config.h:134
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:virtio_pci_sriov_configure
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81a158eb)
Location: include/linux/virtio_config.h:134
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_validate
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:remove_common
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:report_free_page_func
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:virtballoon_changed
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:leak_balloon
  - drivers/virtio/virtio_balloon.c:leak_balloon
  - drivers/virtio/virtio_balloon.c:fill_balloon
  - drivers/virtio/virtio_balloon.c:fill_balloon
```
```
In drivers/char/virtio_console.c (ffffffff81a998c5)
Location: include/linux/virtio_config.h:134
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:virtcons_restore
  - drivers/char/virtio_console.c:virtcons_freeze
  - drivers/char/virtio_console.c:virtcons_freeze
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_remove
  - drivers/char/virtio_console.c:virtcons_remove
  - drivers/char/virtio_console.c:init_vqs
  - drivers/char/virtio_console.c:init_vqs
  - drivers/char/virtio_console.c:init_vqs
  - drivers/char/virtio_console.c:config_work_handler
  - drivers/char/virtio_console.c:config_work_handler
  - drivers/char/virtio_console.c:config_work_handler
  - drivers/char/virtio_console.c:config_intr
```
```
In drivers/iommu/virtio-iommu.c (ffffffff81adb64a)
Location: include/linux/virtio_config.h:134
Inline: True
Inline callers:
  - drivers/iommu/virtio-iommu.c:viommu_probe
  - drivers/iommu/virtio-iommu.c:viommu_probe
  - drivers/iommu/virtio-iommu.c:viommu_probe
  - drivers/iommu/virtio-iommu.c:viommu_probe
  - drivers/iommu/virtio-iommu.c:viommu_probe
  - drivers/iommu/virtio-iommu.c:viommu_probe
  - drivers/iommu/virtio-iommu.c:viommu_probe
  - drivers/iommu/virtio-iommu.c:viommu_probe
  - drivers/iommu/virtio-iommu.c:viommu_attach_dev
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
In drivers/virtio/virtio.c (ffffffff81a54367)
Location: include/linux/virtio_config.h:136
Inline: True
Inline callers:
  - drivers/virtio/virtio.c:virtio_features_ok
  - drivers/virtio/virtio.c:virtio_features_ok
  - drivers/virtio/virtio.c:virtio_features_ok
  - drivers/virtio/virtio.c:features_show
```
```
In drivers/virtio/virtio_ring.c (ffffffff81a57683)
Location: include/linux/virtio_config.h:136
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:virtqueue_resize
  - drivers/virtio/virtio_ring.c:virtqueue_resize
  - drivers/virtio/virtio_ring.c:vring_create_virtqueue_dma
  - drivers/virtio/virtio_ring.c:vring_create_virtqueue
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:virtqueue_detach_unused_buf
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_delayed
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_delayed
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_delayed
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_delayed
  - drivers/virtio/virtio_ring.c:virtqueue_poll
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_prepare
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_prepare
  - drivers/virtio/virtio_ring.c:virtqueue_disable_cb
  - drivers/virtio/virtio_ring.c:virtqueue_kick_prepare
  - drivers/virtio/virtio_ring.c:virtqueue_kick_prepare
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx_split
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx_split
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx_split
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx_split
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx_split
  - drivers/virtio/virtio_ring.c:detach_buf_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
```
```
In drivers/virtio/virtio_mmio.c (ffffffff81a5adc5)
Location: include/linux/virtio_config.h:136
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:vm_setup_vq
  - drivers/virtio/virtio_mmio.c:vm_finalize_features
```
```
In drivers/virtio/virtio_pci_modern.c (ffffffff81a5bb02)
Location: include/linux/virtio_config.h:136
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:vp_modern_disable_vq_and_reset
  - drivers/virtio/virtio_pci_modern.c:vp_finalize_features
```
```
In drivers/virtio/virtio_pci_common.c (ffffffff81a5cb52)
Location: include/linux/virtio_config.h:136
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:virtio_pci_sriov_configure
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81a5ec87)
Location: include/linux/virtio_config.h:136
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_validate
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:remove_common
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:report_free_page_func
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:virtballoon_changed
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:leak_balloon
  - drivers/virtio/virtio_balloon.c:leak_balloon
  - drivers/virtio/virtio_balloon.c:fill_balloon
  - drivers/virtio/virtio_balloon.c:fill_balloon
```
```
In drivers/char/virtio_console.c (ffffffff81ae5135)
Location: include/linux/virtio_config.h:136
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:virtcons_restore
  - drivers/char/virtio_console.c:virtcons_freeze
  - drivers/char/virtio_console.c:virtcons_freeze
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_remove
  - drivers/char/virtio_console.c:virtcons_remove
  - drivers/char/virtio_console.c:init_vqs
  - drivers/char/virtio_console.c:init_vqs
  - drivers/char/virtio_console.c:init_vqs
  - drivers/char/virtio_console.c:config_work_handler
  - drivers/char/virtio_console.c:config_work_handler
  - drivers/char/virtio_console.c:config_work_handler
  - drivers/char/virtio_console.c:config_intr
```
```
In drivers/iommu/virtio-iommu.c (ffffffff81b2990a)
Location: include/linux/virtio_config.h:136
Inline: True
Inline callers:
  - drivers/iommu/virtio-iommu.c:viommu_probe
  - drivers/iommu/virtio-iommu.c:viommu_probe
  - drivers/iommu/virtio-iommu.c:viommu_probe
  - drivers/iommu/virtio-iommu.c:viommu_probe
  - drivers/iommu/virtio-iommu.c:viommu_probe
  - drivers/iommu/virtio-iommu.c:viommu_probe
  - drivers/iommu/virtio-iommu.c:viommu_probe
  - drivers/iommu/virtio-iommu.c:viommu_probe
  - drivers/iommu/virtio-iommu.c:viommu_attach_dev
```
```
In drivers/block/virtio_blk.c (ffffffff81b80ca3)
Location: include/linux/virtio_config.h:136
Inline: True
Inline callers:
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_poll
  - drivers/block/virtio_blk.c:virtblk_attrs_are_visible
  - drivers/block/virtio_blk.c:cache_type_store
  - drivers/block/virtio_blk.c:virtblk_get_cache_mode
  - drivers/block/virtio_blk.c:virtblk_get_cache_mode
  - drivers/block/virtio_blk.c:init_vq
  - drivers/block/virtio_blk.c:init_vq
  - drivers/block/virtio_blk.c:virtblk_update_capacity
  - drivers/block/virtio_blk.c:virtblk_getgeo
  - drivers/block/virtio_blk.c:virtblk_getgeo
  - drivers/block/virtio_blk.c:virtblk_probe_zoned_device
  - drivers/block/virtio_blk.c:virtblk_probe_zoned_device
  - drivers/block/virtio_blk.c:virtblk_probe_zoned_device
  - drivers/block/virtio_blk.c:virtblk_probe_zoned_device
  - drivers/block/virtio_blk.c:virtblk_probe_zoned_device
  - drivers/block/virtio_blk.c:virtblk_probe_zoned_device
  - drivers/block/virtio_blk.c:virtblk_report_zones
  - drivers/block/virtio_blk.c:virtblk_report_zones
  - drivers/block/virtio_blk.c:virtblk_report_zones
  - drivers/block/virtio_blk.c:virtblk_report_zones
  - drivers/block/virtio_blk.c:virtblk_parse_zone
  - drivers/block/virtio_blk.c:virtblk_parse_zone
  - drivers/block/virtio_blk.c:virtblk_parse_zone
  - drivers/block/virtio_blk.c:virtblk_add_req
```
```
In drivers/scsi/virtio_scsi.c (ffffffff81be32f6)
Location: include/linux/virtio_config.h:136
Inline: True
Inline callers:
  - drivers/scsi/virtio_scsi.c:virtscsi_restore
  - drivers/scsi/virtio_scsi.c:virtscsi_remove
  - drivers/scsi/virtio_scsi.c:virtscsi_probe
  - drivers/scsi/virtio_scsi.c:virtscsi_probe
  - drivers/scsi/virtio_scsi.c:virtscsi_probe
  - drivers/scsi/virtio_scsi.c:virtscsi_probe
  - drivers/scsi/virtio_scsi.c:virtscsi_probe
  - drivers/scsi/virtio_scsi.c:virtscsi_probe
  - drivers/scsi/virtio_scsi.c:virtscsi_probe
  - drivers/scsi/virtio_scsi.c:virtscsi_probe
  - drivers/scsi/virtio_scsi.c:virtscsi_init
  - drivers/scsi/virtio_scsi.c:virtscsi_init
  - drivers/scsi/virtio_scsi.c:virtscsi_abort
  - drivers/scsi/virtio_scsi.c:virtscsi_device_reset
  - drivers/scsi/virtio_scsi.c:virtscsi_queuecommand
  - drivers/scsi/virtio_scsi.c:virtscsi_queuecommand
  - drivers/scsi/virtio_scsi.c:virtscsi_queuecommand
  - drivers/scsi/virtio_scsi.c:virtscsi_queuecommand
  - drivers/scsi/virtio_scsi.c:virtscsi_queuecommand
  - drivers/scsi/virtio_scsi.c:virtscsi_handle_event
  - drivers/scsi/virtio_scsi.c:virtscsi_handle_event
  - drivers/scsi/virtio_scsi.c:virtscsi_handle_event
  - drivers/scsi/virtio_scsi.c:virtscsi_handle_event
  - drivers/scsi/virtio_scsi.c:virtscsi_handle_event
  - drivers/scsi/virtio_scsi.c:virtscsi_handle_event
  - drivers/scsi/virtio_scsi.c:virtscsi_complete_cmd
  - drivers/scsi/virtio_scsi.c:virtscsi_complete_cmd
  - drivers/scsi/virtio_scsi.c:virtscsi_complete_cmd
```
```
In drivers/net/virtio_net.c (ffffffff81c521f3)
Location: include/linux/virtio_config.h:136
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_validate
  - drivers/net/virtio_net.c:virtnet_validate
  - drivers/net/virtio_net.c:virtnet_validate
  - drivers/net/virtio_net.c:virtnet_validate
  - drivers/net/virtio_net.c:virtnet_validate
  - drivers/net/virtio_net.c:virtnet_validate
  - drivers/net/virtio_net.c:virtnet_validate
  - drivers/net/virtio_net.c:virtnet_validate
  - drivers/net/virtio_net.c:virtnet_validate
  - drivers/net/virtio_net.c:virtnet_validate
  - drivers/net/virtio_net.c:virtnet_validate
  - drivers/net/virtio_net.c:virtnet_validate
  - drivers/net/virtio_net.c:virtnet_validate
  - drivers/net/virtio_net.c:virtnet_find_vqs
  - drivers/net/virtio_net.c:virtnet_find_vqs
  - drivers/net/virtio_net.c:virtnet_config_changed_work
  - drivers/net/virtio_net.c:virtnet_config_changed_work
  - drivers/net/virtio_net.c:virtnet_get_phys_port_name
  - drivers/net/virtio_net.c:virtnet_xdp_set
  - drivers/net/virtio_net.c:virtnet_xdp_set
  - drivers/net/virtio_net.c:virtnet_xdp_set
  - drivers/net/virtio_net.c:virtnet_xdp_set
  - drivers/net/virtio_net.c:virtnet_xdp_set
  - drivers/net/virtio_net.c:virtnet_xdp_set
  - drivers/net/virtio_net.c:virtnet_xdp_set
  - drivers/net/virtio_net.c:virtnet_xdp_set
  - drivers/net/virtio_net.c:virtnet_set_coalesce
  - drivers/net/virtio_net.c:virtnet_vlan_rx_kill_vid
  - drivers/net/virtio_net.c:virtnet_vlan_rx_add_vid
  - drivers/net/virtio_net.c:virtnet_set_rx_mode
  - drivers/net/virtio_net.c:virtnet_set_rx_mode
  - drivers/net/virtio_net.c:virtnet_set_rx_mode
  - drivers/net/virtio_net.c:_virtnet_set_queues
  - drivers/net/virtio_net.c:_virtnet_set_queues
  - drivers/net/virtio_net.c:virtnet_set_mac_address
  - drivers/net/virtio_net.c:virtnet_set_mac_address
  - drivers/net/virtio_net.c:virtnet_set_mac_address
  - drivers/net/virtio_net.c:virtnet_set_mac_address
  - drivers/net/virtio_net.c:virtnet_send_command
  - drivers/net/virtio_net.c:xmit_skb
  - drivers/net/virtio_net.c:receive_buf
  - drivers/net/virtio_net.c:receive_mergeable
  - drivers/net/virtio_net.c:receive_mergeable
  - drivers/net/virtio_net.c:receive_mergeable_xdp
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
In drivers/virtio/virtio.c (ffffffff81aa5007)
Location: include/linux/virtio_config.h:140
Inline: True
Inline callers:
  - drivers/virtio/virtio.c:virtio_features_ok
  - drivers/virtio/virtio.c:virtio_features_ok
  - drivers/virtio/virtio.c:virtio_features_ok
  - drivers/virtio/virtio.c:features_show
```
```
In drivers/virtio/virtio_ring.c (ffffffff81aa8eb3)
Location: include/linux/virtio_config.h:140
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:vring_create_virtqueue_dma
  - drivers/virtio/virtio_ring.c:vring_create_virtqueue
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:virtqueue_detach_unused_buf
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_delayed
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_delayed
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_delayed
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_delayed
  - drivers/virtio/virtio_ring.c:virtqueue_poll
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_prepare
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_prepare
  - drivers/virtio/virtio_ring.c:virtqueue_disable_cb
  - drivers/virtio/virtio_ring.c:virtqueue_kick_prepare
  - drivers/virtio/virtio_ring.c:virtqueue_kick_prepare
  - drivers/virtio/virtio_ring.c:virtqueue_reinit_split
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx_split
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx_split
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx_split
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx_split
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx_split
  - drivers/virtio/virtio_ring.c:detach_buf_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
```
```
In drivers/virtio/virtio_mmio.c (ffffffff81aac205)
Location: include/linux/virtio_config.h:140
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:vm_setup_vq
  - drivers/virtio/virtio_mmio.c:vm_finalize_features
```
```
In drivers/virtio/virtio_pci_modern.c (ffffffff81aad935)
Location: include/linux/virtio_config.h:140
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_modern.c:vp_modern_create_avq
  - drivers/virtio/virtio_pci_modern.c:del_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:vp_modern_disable_vq_and_reset
  - drivers/virtio/virtio_pci_modern.c:vp_reset
  - drivers/virtio/virtio_pci_modern.c:vp_set_status
  - drivers/virtio/virtio_pci_modern.c:vp_finalize_features
  - drivers/virtio/virtio_pci_modern.c:vp_finalize_features
  - drivers/virtio/virtio_pci_modern.c:vp_finalize_features
  - drivers/virtio/virtio_pci_modern.c:vp_finalize_features
  - drivers/virtio/virtio_pci_modern.c:vp_modern_admin_cmd_exec
```
```
In drivers/virtio/virtio_pci_common.c (ffffffff81aae932)
Location: include/linux/virtio_config.h:140
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:virtio_pci_sriov_configure
```
```
In drivers/virtio/virtio_pci_admin_legacy_io.c (ffffffff81ab00d5)
Location: include/linux/virtio_config.h:140
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_admin_legacy_io.c:virtio_pci_admin_has_legacy_io
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81ab13e7)
Location: include/linux/virtio_config.h:140
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_validate
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:remove_common
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:report_free_page_func
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:virtballoon_changed
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:leak_balloon
  - drivers/virtio/virtio_balloon.c:leak_balloon
  - drivers/virtio/virtio_balloon.c:fill_balloon
  - drivers/virtio/virtio_balloon.c:fill_balloon
```
```
In drivers/char/virtio_console.c (ffffffff81b38505)
Location: include/linux/virtio_config.h:140
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:virtcons_restore
  - drivers/char/virtio_console.c:virtcons_freeze
  - drivers/char/virtio_console.c:virtcons_freeze
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_remove
  - drivers/char/virtio_console.c:virtcons_remove
  - drivers/char/virtio_console.c:init_vqs
  - drivers/char/virtio_console.c:init_vqs
  - drivers/char/virtio_console.c:init_vqs
  - drivers/char/virtio_console.c:config_work_handler
  - drivers/char/virtio_console.c:config_work_handler
  - drivers/char/virtio_console.c:config_work_handler
  - drivers/char/virtio_console.c:config_intr
```
```
In drivers/iommu/virtio-iommu.c (ffffffff81b808fa)
Location: include/linux/virtio_config.h:140
Inline: True
Inline callers:
  - drivers/iommu/virtio-iommu.c:viommu_probe
  - drivers/iommu/virtio-iommu.c:viommu_probe
  - drivers/iommu/virtio-iommu.c:viommu_probe
  - drivers/iommu/virtio-iommu.c:viommu_probe
  - drivers/iommu/virtio-iommu.c:viommu_probe
  - drivers/iommu/virtio-iommu.c:viommu_probe
  - drivers/iommu/virtio-iommu.c:viommu_probe
  - drivers/iommu/virtio-iommu.c:viommu_probe
  - drivers/iommu/virtio-iommu.c:viommu_attach_dev
```
```
In drivers/block/virtio_blk.c (ffffffff81bd4b02)
Location: include/linux/virtio_config.h:140
Inline: True
Inline callers:
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_poll
  - drivers/block/virtio_blk.c:virtblk_attrs_are_visible
  - drivers/block/virtio_blk.c:cache_type_store
  - drivers/block/virtio_blk.c:virtblk_get_cache_mode
  - drivers/block/virtio_blk.c:virtblk_get_cache_mode
  - drivers/block/virtio_blk.c:init_vq
  - drivers/block/virtio_blk.c:init_vq
  - drivers/block/virtio_blk.c:virtblk_update_capacity
  - drivers/block/virtio_blk.c:virtblk_getgeo
  - drivers/block/virtio_blk.c:virtblk_getgeo
  - drivers/block/virtio_blk.c:virtblk_probe_zoned_device
  - drivers/block/virtio_blk.c:virtblk_probe_zoned_device
  - drivers/block/virtio_blk.c:virtblk_probe_zoned_device
  - drivers/block/virtio_blk.c:virtblk_probe_zoned_device
  - drivers/block/virtio_blk.c:virtblk_probe_zoned_device
  - drivers/block/virtio_blk.c:virtblk_probe_zoned_device
  - drivers/block/virtio_blk.c:virtblk_report_zones
  - drivers/block/virtio_blk.c:virtblk_report_zones
  - drivers/block/virtio_blk.c:virtblk_report_zones
  - drivers/block/virtio_blk.c:virtblk_report_zones
  - drivers/block/virtio_blk.c:virtblk_parse_zone
  - drivers/block/virtio_blk.c:virtblk_parse_zone
  - drivers/block/virtio_blk.c:virtblk_parse_zone
  - drivers/block/virtio_blk.c:virtblk_add_req
```
```
In drivers/scsi/virtio_scsi.c (ffffffff81c38756)
Location: include/linux/virtio_config.h:140
Inline: True
Inline callers:
  - drivers/scsi/virtio_scsi.c:virtscsi_restore
  - drivers/scsi/virtio_scsi.c:virtscsi_remove
  - drivers/scsi/virtio_scsi.c:virtscsi_probe
  - drivers/scsi/virtio_scsi.c:virtscsi_probe
  - drivers/scsi/virtio_scsi.c:virtscsi_probe
  - drivers/scsi/virtio_scsi.c:virtscsi_probe
  - drivers/scsi/virtio_scsi.c:virtscsi_probe
  - drivers/scsi/virtio_scsi.c:virtscsi_probe
  - drivers/scsi/virtio_scsi.c:virtscsi_probe
  - drivers/scsi/virtio_scsi.c:virtscsi_probe
  - drivers/scsi/virtio_scsi.c:virtscsi_init
  - drivers/scsi/virtio_scsi.c:virtscsi_init
  - drivers/scsi/virtio_scsi.c:virtscsi_abort
  - drivers/scsi/virtio_scsi.c:virtscsi_device_reset
  - drivers/scsi/virtio_scsi.c:virtscsi_queuecommand
  - drivers/scsi/virtio_scsi.c:virtscsi_queuecommand
  - drivers/scsi/virtio_scsi.c:virtscsi_queuecommand
  - drivers/scsi/virtio_scsi.c:virtscsi_queuecommand
  - drivers/scsi/virtio_scsi.c:virtscsi_queuecommand
  - drivers/scsi/virtio_scsi.c:virtscsi_handle_event
  - drivers/scsi/virtio_scsi.c:virtscsi_handle_event
  - drivers/scsi/virtio_scsi.c:virtscsi_handle_event
  - drivers/scsi/virtio_scsi.c:virtscsi_handle_event
  - drivers/scsi/virtio_scsi.c:virtscsi_handle_event
  - drivers/scsi/virtio_scsi.c:virtscsi_handle_event
  - drivers/scsi/virtio_scsi.c:virtscsi_complete_cmd
  - drivers/scsi/virtio_scsi.c:virtscsi_complete_cmd
  - drivers/scsi/virtio_scsi.c:virtscsi_complete_cmd
```
```
In drivers/net/virtio_net.c (ffffffff81d085ca)
Location: include/linux/virtio_config.h:140
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_validate
  - drivers/net/virtio_net.c:virtnet_validate
  - drivers/net/virtio_net.c:virtnet_validate
  - drivers/net/virtio_net.c:virtnet_validate
  - drivers/net/virtio_net.c:virtnet_validate_features
  - drivers/net/virtio_net.c:virtnet_validate_features
  - drivers/net/virtio_net.c:virtnet_validate_features
  - drivers/net/virtio_net.c:virtnet_validate_features
  - drivers/net/virtio_net.c:virtnet_validate_features
  - drivers/net/virtio_net.c:virtnet_validate_features
  - drivers/net/virtio_net.c:virtnet_validate_features
  - drivers/net/virtio_net.c:virtnet_validate_features
  - drivers/net/virtio_net.c:virtnet_validate_features
  - drivers/net/virtio_net.c:virtnet_validate_features
  - drivers/net/virtio_net.c:virtnet_find_vqs
  - drivers/net/virtio_net.c:virtnet_find_vqs
  - drivers/net/virtio_net.c:virtnet_config_changed_work
  - drivers/net/virtio_net.c:virtnet_config_changed_work
  - drivers/net/virtio_net.c:virtnet_get_phys_port_name
  - drivers/net/virtio_net.c:virtnet_xdp_set
  - drivers/net/virtio_net.c:virtnet_xdp_set
  - drivers/net/virtio_net.c:virtnet_xdp_set
  - drivers/net/virtio_net.c:virtnet_xdp_set
  - drivers/net/virtio_net.c:virtnet_xdp_set
  - drivers/net/virtio_net.c:virtnet_xdp_set
  - drivers/net/virtio_net.c:virtnet_xdp_set
  - drivers/net/virtio_net.c:virtnet_xdp_set
  - drivers/net/virtio_net.c:virtnet_get_per_queue_coalesce
  - drivers/net/virtio_net.c:virtnet_set_per_queue_coalesce
  - drivers/net/virtio_net.c:virtnet_set_coalesce
  - drivers/net/virtio_net.c:virtnet_send_rx_notf_coal_cmds
  - drivers/net/virtio_net.c:virtnet_vlan_rx_kill_vid
  - drivers/net/virtio_net.c:virtnet_vlan_rx_add_vid
  - drivers/net/virtio_net.c:virtnet_set_rx_mode
  - drivers/net/virtio_net.c:virtnet_set_rx_mode
  - drivers/net/virtio_net.c:virtnet_set_rx_mode
  - drivers/net/virtio_net.c:_virtnet_set_queues
  - drivers/net/virtio_net.c:_virtnet_set_queues
  - drivers/net/virtio_net.c:virtnet_set_mac_address
  - drivers/net/virtio_net.c:virtnet_set_mac_address
  - drivers/net/virtio_net.c:virtnet_set_mac_address
  - drivers/net/virtio_net.c:virtnet_set_mac_address
  - drivers/net/virtio_net.c:virtnet_send_command
  - drivers/net/virtio_net.c:xmit_skb
  - drivers/net/virtio_net.c:receive_buf
  - drivers/net/virtio_net.c:receive_mergeable
  - drivers/net/virtio_net.c:receive_mergeable
  - drivers/net/virtio_net.c:receive_mergeable_xdp
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio.c (ffff8000108210b0)
Location: include/linux/virtio_config.h:104
Inline: True
Inline callers:
  - drivers/virtio/virtio.c:features_show
```
```
In drivers/virtio/virtio_ring.c (ffff800010823630)
Location: include/linux/virtio_config.h:104
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:vring_create_virtqueue
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:virtqueue_detach_unused_buf
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_delayed
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_delayed
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_delayed
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_prepare
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_prepare
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_kick_prepare
  - drivers/virtio/virtio_ring.c:virtqueue_kick_prepare
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:detach_buf_split
  - drivers/virtio/virtio_ring.c:detach_buf_split
  - drivers/virtio/virtio_ring.c:detach_buf_split
  - drivers/virtio/virtio_ring.c:detach_buf_split
  - drivers/virtio/virtio_ring.c:detach_buf_split
```
```
In drivers/virtio/virtio_mmio.c (ffff800010825cb8)
Location: include/linux/virtio_config.h:104
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:vm_finalize_features
```
```
In drivers/virtio/virtio_pci_modern.c (ffff800010826dac)
Location: include/linux/virtio_config.h:104
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_modern.c:vp_finalize_features
```
```
In drivers/virtio/virtio_pci_common.c (ffff800010828210)
Location: include/linux/virtio_config.h:104
Inline: True
```
```
In drivers/virtio/virtio_balloon.c (ffff80001082abec)
Location: include/linux/virtio_config.h:104
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_restore
  - drivers/virtio/virtio_balloon.c:virtballoon_restore
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:remove_common
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtio_balloon_shrinker_scan
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:report_free_page_func
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtio_balloon_cmd_id_received
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:virtballoon_changed
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:leak_balloon
```
```
In drivers/char/virtio_console.c (ffff8000108b51f8)
Location: include/linux/virtio_config.h:104
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:virtcons_restore
  - drivers/char/virtio_console.c:virtcons_freeze
  - drivers/char/virtio_console.c:virtcons_freeze
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_remove
  - drivers/char/virtio_console.c:init_vqs
  - drivers/char/virtio_console.c:init_vqs
  - drivers/char/virtio_console.c:init_vqs
  - drivers/char/virtio_console.c:config_work_handler
  - drivers/char/virtio_console.c:config_work_handler
  - drivers/char/virtio_console.c:config_work_handler
  - drivers/char/virtio_console.c:config_intr
  - drivers/char/virtio_console.c:add_port
```
```
In drivers/iommu/virtio-iommu.c (ffff8000108dbfe8)
Location: include/linux/virtio_config.h:104
Inline: True
Inline callers:
  - drivers/iommu/virtio-iommu.c:viommu_probe
  - drivers/iommu/virtio-iommu.c:viommu_probe
  - drivers/iommu/virtio-iommu.c:viommu_probe
  - drivers/iommu/virtio-iommu.c:viommu_probe
  - drivers/iommu/virtio-iommu.c:viommu_probe
  - drivers/iommu/virtio-iommu.c:viommu_probe
  - drivers/iommu/virtio-iommu.c:viommu_probe
  - drivers/iommu/virtio-iommu.c:viommu_probe
  - drivers/iommu/virtio-iommu.c:viommu_probe
  - drivers/iommu/virtio-iommu.c:viommu_probe
  - drivers/iommu/virtio-iommu.c:viommu_probe
  - drivers/iommu/virtio-iommu.c:viommu_probe
  - drivers/iommu/virtio-iommu.c:viommu_probe
  - drivers/iommu/virtio-iommu.c:viommu_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio.c (c093eeb4)
Location: include/linux/virtio_config.h:104
Inline: True
Inline callers:
  - drivers/virtio/virtio.c:features_show
```
```
In drivers/virtio/virtio_ring.c (c09411a8)
Location: include/linux/virtio_config.h:104
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:vring_create_virtqueue
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:virtqueue_detach_unused_buf
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_delayed
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_delayed
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_delayed
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_prepare
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_prepare
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_kick_prepare
  - drivers/virtio/virtio_ring.c:virtqueue_kick_prepare
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:detach_buf_split
  - drivers/virtio/virtio_ring.c:detach_buf_split
  - drivers/virtio/virtio_ring.c:detach_buf_split
  - drivers/virtio/virtio_ring.c:detach_buf_split
  - drivers/virtio/virtio_ring.c:detach_buf_split
  - drivers/virtio/virtio_ring.c:virtio_max_dma_size
```
```
In drivers/virtio/virtio_mmio.c (c0944034)
Location: include/linux/virtio_config.h:104
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:vm_finalize_features
```
```
In drivers/virtio/virtio_pci_modern.c (c0944f5c)
Location: include/linux/virtio_config.h:104
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_modern.c:vp_finalize_features
```
```
In drivers/virtio/virtio_pci_common.c (c094623c)
Location: include/linux/virtio_config.h:104
Inline: True
```
```
In drivers/virtio/virtio_balloon.c (c0948b3c)
Location: include/linux/virtio_config.h:104
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_restore
  - drivers/virtio/virtio_balloon.c:virtballoon_restore
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:remove_common
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtio_balloon_shrinker_scan
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:report_free_page_func
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtio_balloon_cmd_id_received
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:update_balloon_size
  - drivers/virtio/virtio_balloon.c:update_balloon_size
  - drivers/virtio/virtio_balloon.c:virtballoon_changed
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:leak_balloon
  - drivers/virtio/virtio_balloon.c:leak_balloon
```
```
In drivers/char/virtio_console.c (c09b01ac)
Location: include/linux/virtio_config.h:104
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:virtcons_restore
  - drivers/char/virtio_console.c:virtcons_freeze
  - drivers/char/virtio_console.c:virtcons_freeze
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_remove
  - drivers/char/virtio_console.c:init_vqs
  - drivers/char/virtio_console.c:init_vqs
  - drivers/char/virtio_console.c:init_vqs
  - drivers/char/virtio_console.c:config_work_handler
  - drivers/char/virtio_console.c:config_work_handler
  - drivers/char/virtio_console.c:config_work_handler
  - drivers/char/virtio_console.c:config_intr
  - drivers/char/virtio_console.c:add_port
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio.c (c0000000008ca754)
Location: include/linux/virtio_config.h:104
Inline: True
Inline callers:
  - drivers/virtio/virtio.c:features_show
```
```
In drivers/virtio/virtio_ring.c (c0000000008cc120)
Location: include/linux/virtio_config.h:104
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:vring_create_virtqueue
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:virtqueue_detach_unused_buf
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_delayed
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_delayed
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_delayed
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_prepare
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_prepare
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_kick_prepare
  - drivers/virtio/virtio_ring.c:virtqueue_kick_prepare
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:detach_buf_split
  - drivers/virtio/virtio_ring.c:detach_buf_split
  - drivers/virtio/virtio_ring.c:detach_buf_split
  - drivers/virtio/virtio_ring.c:detach_buf_split
  - drivers/virtio/virtio_ring.c:detach_buf_split
  - drivers/virtio/virtio_ring.c:virtio_max_dma_size
```
```
In drivers/virtio/virtio_mmio.c (c0000000008d1120)
Location: include/linux/virtio_config.h:104
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:vm_finalize_features
```
```
In drivers/virtio/virtio_pci_modern.c (c0000000008d2b90)
Location: include/linux/virtio_config.h:104
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_modern.c:vp_finalize_features
```
```
In drivers/virtio/virtio_pci_common.c (c0000000008d46a8)
Location: include/linux/virtio_config.h:104
Inline: True
```
```
In drivers/virtio/virtio_balloon.c (c0000000008d7ec4)
Location: include/linux/virtio_config.h:104
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_restore
  - drivers/virtio/virtio_balloon.c:virtballoon_restore
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:remove_common
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtio_balloon_shrinker_scan
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:report_free_page_func
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtio_balloon_cmd_id_received
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:update_balloon_size
  - drivers/virtio/virtio_balloon.c:update_balloon_size
  - drivers/virtio/virtio_balloon.c:virtballoon_changed
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:leak_balloon
  - drivers/virtio/virtio_balloon.c:set_page_pfns
```
```
In drivers/char/virtio_console.c (c00000000094fb90)
Location: include/linux/virtio_config.h:104
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:virtcons_restore
  - drivers/char/virtio_console.c:virtcons_freeze
  - drivers/char/virtio_console.c:virtcons_freeze
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_remove
  - drivers/char/virtio_console.c:init_vqs
  - drivers/char/virtio_console.c:init_vqs
  - drivers/char/virtio_console.c:init_vqs
  - drivers/char/virtio_console.c:config_work_handler
  - drivers/char/virtio_console.c:config_work_handler
  - drivers/char/virtio_console.c:config_work_handler
  - drivers/char/virtio_console.c:config_intr
  - drivers/char/virtio_console.c:add_port
  - drivers/char/virtio_console.c:send_control_msg
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
In drivers/virtio/virtio.c (ffffffe0005180d2)
Location: include/linux/virtio_config.h:104
Inline: True
Inline callers:
  - drivers/virtio/virtio.c:features_show
```
```
In drivers/virtio/virtio_ring.c (ffffffe000519e50)
Location: include/linux/virtio_config.h:104
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:vring_create_virtqueue
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:virtqueue_detach_unused_buf
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_delayed
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_delayed
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_delayed
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_prepare
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_prepare
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_kick_prepare
  - drivers/virtio/virtio_ring.c:virtqueue_kick_prepare
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:detach_buf_split
  - drivers/virtio/virtio_ring.c:detach_buf_split
  - drivers/virtio/virtio_ring.c:detach_buf_split
  - drivers/virtio/virtio_ring.c:detach_buf_split
  - drivers/virtio/virtio_ring.c:detach_buf_split
  - drivers/virtio/virtio_ring.c:virtio_max_dma_size
```
```
In drivers/virtio/virtio_mmio.c (ffffffe00051c3ea)
Location: include/linux/virtio_config.h:104
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:vm_finalize_features
```
```
In drivers/virtio/virtio_pci_modern.c (ffffffe00051d5f6)
Location: include/linux/virtio_config.h:104
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_modern.c:vp_finalize_features
```
```
In drivers/virtio/virtio_pci_common.c (ffffffe00051e820)
Location: include/linux/virtio_config.h:104
Inline: True
```
```
In drivers/virtio/virtio_balloon.c (ffffffe000520dec)
Location: include/linux/virtio_config.h:104
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtio_balloon_shrinker_scan
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:report_free_page_func
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtio_balloon_cmd_id_received
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:update_balloon_size
  - drivers/virtio/virtio_balloon.c:update_balloon_size
  - drivers/virtio/virtio_balloon.c:virtballoon_changed
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:leak_balloon
  - drivers/virtio/virtio_balloon.c:set_page_pfns
```
```
In drivers/char/virtio_console.c (ffffffe000566c56)
Location: include/linux/virtio_config.h:104
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_remove
  - drivers/char/virtio_console.c:config_work_handler
  - drivers/char/virtio_console.c:config_work_handler
  - drivers/char/virtio_console.c:config_work_handler
  - drivers/char/virtio_console.c:config_intr
  - drivers/char/virtio_console.c:add_port
  - drivers/char/virtio_console.c:send_control_msg
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio.c (ffffffff8161eaa8)
Location: include/linux/virtio_config.h:104
Inline: True
Inline callers:
  - drivers/virtio/virtio.c:features_show
```
```
In drivers/virtio/virtio_ring.c (ffffffff8161fb85)
Location: include/linux/virtio_config.h:104
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:vring_create_virtqueue
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:virtqueue_detach_unused_buf
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_delayed
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_delayed
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_delayed
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_prepare
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_prepare
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_kick_prepare
  - drivers/virtio/virtio_ring.c:virtqueue_kick_prepare
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:detach_buf_split
  - drivers/virtio/virtio_ring.c:detach_buf_split
  - drivers/virtio/virtio_ring.c:detach_buf_split
  - drivers/virtio/virtio_ring.c:detach_buf_split
  - drivers/virtio/virtio_ring.c:detach_buf_split
```
```
In drivers/virtio/virtio_mmio.c (ffffffff816232cd)
Location: include/linux/virtio_config.h:104
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:vm_finalize_features
```
```
In drivers/virtio/virtio_pci_modern.c (ffffffff81623fa9)
Location: include/linux/virtio_config.h:104
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_modern.c:vp_finalize_features
```
```
In drivers/virtio/virtio_pci_common.c (ffffffff816252c2)
Location: include/linux/virtio_config.h:104
Inline: True
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81627810)
Location: include/linux/virtio_config.h:104
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_restore
  - drivers/virtio/virtio_balloon.c:virtballoon_restore
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:remove_common
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtio_balloon_shrinker_scan
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:report_free_page_func
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtio_balloon_cmd_id_received
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:virtballoon_changed
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:leak_balloon
  - drivers/virtio/virtio_balloon.c:leak_balloon
```
```
In drivers/char/virtio_console.c (ffffffff81688bc9)
Location: include/linux/virtio_config.h:104
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:virtcons_restore
  - drivers/char/virtio_console.c:virtcons_freeze
  - drivers/char/virtio_console.c:virtcons_freeze
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_remove
  - drivers/char/virtio_console.c:init_vqs
  - drivers/char/virtio_console.c:init_vqs
  - drivers/char/virtio_console.c:init_vqs
  - drivers/char/virtio_console.c:config_work_handler
  - drivers/char/virtio_console.c:config_work_handler
  - drivers/char/virtio_console.c:config_work_handler
  - drivers/char/virtio_console.c:config_intr
  - drivers/char/virtio_console.c:add_port
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio.c (ffffffff81613198)
Location: include/linux/virtio_config.h:104
Inline: True
Inline callers:
  - drivers/virtio/virtio.c:features_show
```
```
In drivers/virtio/virtio_ring.c (ffffffff81614115)
Location: include/linux/virtio_config.h:104
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:vring_create_virtqueue
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:virtqueue_detach_unused_buf
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_delayed
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_delayed
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_delayed
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_prepare
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_prepare
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_kick_prepare
  - drivers/virtio/virtio_ring.c:virtqueue_kick_prepare
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:detach_buf_split
  - drivers/virtio/virtio_ring.c:detach_buf_split
  - drivers/virtio/virtio_ring.c:detach_buf_split
  - drivers/virtio/virtio_ring.c:detach_buf_split
  - drivers/virtio/virtio_ring.c:detach_buf_split
  - drivers/virtio/virtio_ring.c:virtio_max_dma_size
```
```
In drivers/virtio/virtio_mmio.c (ffffffff8161791d)
Location: include/linux/virtio_config.h:104
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:vm_finalize_features
```
```
In drivers/virtio/virtio_pci_modern.c (ffffffff816185f9)
Location: include/linux/virtio_config.h:104
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_modern.c:vp_finalize_features
```
```
In drivers/virtio/virtio_pci_common.c (ffffffff81619942)
Location: include/linux/virtio_config.h:104
Inline: True
```
```
In drivers/virtio/virtio_balloon.c (ffffffff8161be90)
Location: include/linux/virtio_config.h:104
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_restore
  - drivers/virtio/virtio_balloon.c:virtballoon_restore
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:remove_common
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtio_balloon_shrinker_scan
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:report_free_page_func
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtio_balloon_cmd_id_received
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:virtballoon_changed
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:leak_balloon
  - drivers/virtio/virtio_balloon.c:leak_balloon
```
```
In drivers/char/virtio_console.c (ffffffff81666679)
Location: include/linux/virtio_config.h:104
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:virtcons_restore
  - drivers/char/virtio_console.c:virtcons_freeze
  - drivers/char/virtio_console.c:virtcons_freeze
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_remove
  - drivers/char/virtio_console.c:init_vqs
  - drivers/char/virtio_console.c:init_vqs
  - drivers/char/virtio_console.c:init_vqs
  - drivers/char/virtio_console.c:config_work_handler
  - drivers/char/virtio_console.c:config_work_handler
  - drivers/char/virtio_console.c:config_work_handler
  - drivers/char/virtio_console.c:config_intr
  - drivers/char/virtio_console.c:add_port
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio.c (ffffffff8164ca48)
Location: include/linux/virtio_config.h:104
Inline: True
Inline callers:
  - drivers/virtio/virtio.c:features_show
```
```
In drivers/virtio/virtio_ring.c (ffffffff8164db25)
Location: include/linux/virtio_config.h:104
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:vring_create_virtqueue
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:virtqueue_detach_unused_buf
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_delayed
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_delayed
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_delayed
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_prepare
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_prepare
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_kick_prepare
  - drivers/virtio/virtio_ring.c:virtqueue_kick_prepare
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:detach_buf_split
  - drivers/virtio/virtio_ring.c:detach_buf_split
  - drivers/virtio/virtio_ring.c:detach_buf_split
  - drivers/virtio/virtio_ring.c:detach_buf_split
  - drivers/virtio/virtio_ring.c:detach_buf_split
```
```
In drivers/virtio/virtio_mmio.c (ffffffff8165126d)
Location: include/linux/virtio_config.h:104
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:vm_finalize_features
```
```
In drivers/virtio/virtio_pci_modern.c (ffffffff81651f49)
Location: include/linux/virtio_config.h:104
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_modern.c:vp_finalize_features
```
```
In drivers/virtio/virtio_pci_common.c (ffffffff81653292)
Location: include/linux/virtio_config.h:104
Inline: True
```
```
In drivers/virtio/virtio_balloon.c (ffffffff816557e0)
Location: include/linux/virtio_config.h:104
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_restore
  - drivers/virtio/virtio_balloon.c:virtballoon_restore
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:remove_common
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtio_balloon_shrinker_scan
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:report_free_page_func
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtio_balloon_cmd_id_received
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:virtballoon_changed
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:leak_balloon
  - drivers/virtio/virtio_balloon.c:leak_balloon
```
```
In drivers/char/virtio_console.c (ffffffff816b6e49)
Location: include/linux/virtio_config.h:104
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:virtcons_restore
  - drivers/char/virtio_console.c:virtcons_freeze
  - drivers/char/virtio_console.c:virtcons_freeze
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_remove
  - drivers/char/virtio_console.c:init_vqs
  - drivers/char/virtio_console.c:init_vqs
  - drivers/char/virtio_console.c:init_vqs
  - drivers/char/virtio_console.c:config_work_handler
  - drivers/char/virtio_console.c:config_work_handler
  - drivers/char/virtio_console.c:config_work_handler
  - drivers/char/virtio_console.c:config_intr
  - drivers/char/virtio_console.c:add_port
```
```
In drivers/scsi/virtio_scsi.c (ffffffff81772de9)
Location: include/linux/virtio_config.h:104
Inline: True
Inline callers:
  - drivers/scsi/virtio_scsi.c:virtscsi_restore
  - drivers/scsi/virtio_scsi.c:virtscsi_remove
  - drivers/scsi/virtio_scsi.c:virtscsi_probe
  - drivers/scsi/virtio_scsi.c:virtscsi_probe
  - drivers/scsi/virtio_scsi.c:virtscsi_probe
  - drivers/scsi/virtio_scsi.c:virtscsi_probe
  - drivers/scsi/virtio_scsi.c:virtscsi_probe
  - drivers/scsi/virtio_scsi.c:virtscsi_probe
  - drivers/scsi/virtio_scsi.c:virtscsi_probe
  - drivers/scsi/virtio_scsi.c:virtscsi_probe
  - drivers/scsi/virtio_scsi.c:virtscsi_init
  - drivers/scsi/virtio_scsi.c:virtscsi_init
  - drivers/scsi/virtio_scsi.c:virtscsi_abort
  - drivers/scsi/virtio_scsi.c:virtscsi_device_reset
  - drivers/scsi/virtio_scsi.c:virtscsi_queuecommand
  - drivers/scsi/virtio_scsi.c:virtscsi_queuecommand
  - drivers/scsi/virtio_scsi.c:virtscsi_queuecommand
  - drivers/scsi/virtio_scsi.c:virtscsi_queuecommand
  - drivers/scsi/virtio_scsi.c:virtscsi_queuecommand
  - drivers/scsi/virtio_scsi.c:virtscsi_handle_event
  - drivers/scsi/virtio_scsi.c:virtscsi_handle_event
  - drivers/scsi/virtio_scsi.c:virtscsi_handle_event
  - drivers/scsi/virtio_scsi.c:virtscsi_handle_event
  - drivers/scsi/virtio_scsi.c:virtscsi_handle_event
  - drivers/scsi/virtio_scsi.c:virtscsi_handle_event
  - drivers/scsi/virtio_scsi.c:virtscsi_complete_cmd
  - drivers/scsi/virtio_scsi.c:virtscsi_complete_cmd
  - drivers/scsi/virtio_scsi.c:virtscsi_complete_cmd
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio.c (ffffffff81667118)
Location: include/linux/virtio_config.h:104
Inline: True
Inline callers:
  - drivers/virtio/virtio.c:features_show
```
```
In drivers/virtio/virtio_ring.c (ffffffff816681b5)
Location: include/linux/virtio_config.h:104
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:vring_create_virtqueue
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:virtqueue_detach_unused_buf
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_delayed
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_delayed
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_delayed
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_prepare
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_prepare
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_kick_prepare
  - drivers/virtio/virtio_ring.c:virtqueue_kick_prepare
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:detach_buf_split
  - drivers/virtio/virtio_ring.c:detach_buf_split
  - drivers/virtio/virtio_ring.c:detach_buf_split
  - drivers/virtio/virtio_ring.c:detach_buf_split
  - drivers/virtio/virtio_ring.c:detach_buf_split
```
```
In drivers/virtio/virtio_mmio.c (ffffffff8166b8fd)
Location: include/linux/virtio_config.h:104
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:vm_finalize_features
```
```
In drivers/virtio/virtio_pci_modern.c (ffffffff8166c5d9)
Location: include/linux/virtio_config.h:104
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_modern.c:vp_finalize_features
```
```
In drivers/virtio/virtio_pci_common.c (ffffffff8166d922)
Location: include/linux/virtio_config.h:104
Inline: True
```
```
In drivers/virtio/virtio_balloon.c (ffffffff816703af)
Location: include/linux/virtio_config.h:104
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_restore
  - drivers/virtio/virtio_balloon.c:virtballoon_restore
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:remove_common
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtio_balloon_shrinker_scan
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:report_free_page_func
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtio_balloon_cmd_id_received
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:virtballoon_changed
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:leak_balloon
  - drivers/virtio/virtio_balloon.c:leak_balloon
```
```
In drivers/char/virtio_console.c (ffffffff816d1459)
Location: include/linux/virtio_config.h:104
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:virtcons_restore
  - drivers/char/virtio_console.c:virtcons_freeze
  - drivers/char/virtio_console.c:virtcons_freeze
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_remove
  - drivers/char/virtio_console.c:init_vqs
  - drivers/char/virtio_console.c:init_vqs
  - drivers/char/virtio_console.c:init_vqs
  - drivers/char/virtio_console.c:config_work_handler
  - drivers/char/virtio_console.c:config_work_handler
  - drivers/char/virtio_console.c:config_work_handler
  - drivers/char/virtio_console.c:config_intr
  - drivers/char/virtio_console.c:add_port
```
</details>
</li>
</ul>

## Differences
