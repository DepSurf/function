# Function: <code>virtio_has_feature</code>

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
Location: include/linux/virtio_config.h:143
Inline: True
```
```
In drivers/virtio/virtio_ring.c (0)
Location: include/linux/virtio_config.h:143
Inline: True
```
```
In drivers/virtio/virtio_balloon.c (ffffffff814c397d)
Location: include/linux/virtio_config.h:143
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:fill_balloon
  - drivers/virtio/virtio_balloon.c:leak_balloon
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:virtballoon_oom_notify
```
```
In drivers/char/virtio_console.c (ffffffff8151714f)
Location: include/linux/virtio_config.h:143
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
```
```
In drivers/block/virtio_blk.c (ffffffff8157187f)
Location: include/linux/virtio_config.h:143
Inline: True
Inline callers:
  - drivers/block/virtio_blk.c:virtblk_ioctl
  - drivers/block/virtio_blk.c:virtblk_get_cache_mode
  - drivers/block/virtio_blk.c:virtblk_get_cache_mode
  - drivers/block/virtio_blk.c:virtblk_getgeo
  - drivers/block/virtio_blk.c:init_vq
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:virtblk_probe
```
```
In drivers/net/virtio_net.c (ffffffff815f1a75)
Location: include/linux/virtio_config.h:143
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:virtnet_send_command
  - drivers/net/virtio_net.c:virtnet_set_mac_address
  - drivers/net/virtio_net.c:virtnet_set_mac_address
  - drivers/net/virtio_net.c:virtnet_set_queues
  - drivers/net/virtio_net.c:virtnet_set_rx_mode
  - drivers/net/virtio_net.c:virtnet_config_changed_work
  - drivers/net/virtio_net.c:virtnet_find_vqs
  - drivers/net/virtio_net.c:virtnet_find_vqs
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
In drivers/virtio/virtio.c (0)
Location: include/linux/virtio_config.h:143
Inline: True
```
```
In drivers/virtio/virtio_ring.c (ffffffff8150f723)
Location: include/linux/virtio_config.h:143
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81514036)
Location: include/linux/virtio_config.h:143
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:virtballoon_oom_notify
  - drivers/virtio/virtio_balloon.c:leak_balloon
```
```
In drivers/char/virtio_console.c (ffffffff8156b73a)
Location: include/linux/virtio_config.h:143
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
```
```
In drivers/block/virtio_blk.c (ffffffff815c7dec)
Location: include/linux/virtio_config.h:143
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
  - drivers/block/virtio_blk.c:virtblk_get_cache_mode
  - drivers/block/virtio_blk.c:virtblk_get_cache_mode
  - drivers/block/virtio_blk.c:init_vq
  - drivers/block/virtio_blk.c:virtblk_getgeo
  - drivers/block/virtio_blk.c:virtblk_ioctl
```
```
In drivers/net/virtio_net.c (ffffffff81653f31)
Location: include/linux/virtio_config.h:143
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
  - drivers/net/virtio_net.c:virtnet_find_vqs
  - drivers/net/virtio_net.c:virtnet_find_vqs
  - drivers/net/virtio_net.c:virtnet_config_changed_work
  - drivers/net/virtio_net.c:virtnet_set_rx_mode
  - drivers/net/virtio_net.c:virtnet_set_queues
  - drivers/net/virtio_net.c:virtnet_set_mac_address
  - drivers/net/virtio_net.c:virtnet_set_mac_address
  - drivers/net/virtio_net.c:virtnet_send_command
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
In drivers/virtio/virtio.c (0)
Location: include/linux/virtio_config.h:143
Inline: True
```
```
In drivers/virtio/virtio_ring.c (ffffffff8153b8c3)
Location: include/linux/virtio_config.h:143
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81540b06)
Location: include/linux/virtio_config.h:143
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:virtballoon_oom_notify
  - drivers/virtio/virtio_balloon.c:leak_balloon
```
```
In drivers/char/virtio_console.c (ffffffff81597eaa)
Location: include/linux/virtio_config.h:143
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
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
In drivers/virtio/virtio.c (0)
Location: include/linux/virtio_config.h:148
Inline: True
```
```
In drivers/virtio/virtio_ring.c (ffffffff8154f201)
Location: include/linux/virtio_config.h:148
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81554406)
Location: include/linux/virtio_config.h:148
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:virtballoon_oom_notify
  - drivers/virtio/virtio_balloon.c:leak_balloon
```
```
In drivers/char/virtio_console.c (ffffffff815abf87)
Location: include/linux/virtio_config.h:148
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
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
In drivers/virtio/virtio.c (0)
Location: include/linux/virtio_config.h:149
Inline: True
```
```
In drivers/virtio/virtio_ring.c (ffffffff815b29c1)
Location: include/linux/virtio_config.h:149
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
```
```
In drivers/virtio/virtio_balloon.c (ffffffff815b7e86)
Location: include/linux/virtio_config.h:149
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:virtballoon_oom_notify
  - drivers/virtio/virtio_balloon.c:leak_balloon
```
```
In drivers/char/virtio_console.c (ffffffff81612933)
Location: include/linux/virtio_config.h:149
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
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
In drivers/virtio/virtio.c (ffffffff815ea062)
Location: include/linux/virtio_config.h:149
Inline: True
```
```
In drivers/virtio/virtio_ring.c (ffffffff815eadf5)
Location: include/linux/virtio_config.h:149
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
In drivers/virtio/virtio_balloon.c (ffffffff815f09ac)
Location: include/linux/virtio_config.h:149
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
In drivers/char/virtio_console.c (ffffffff8164c99a)
Location: include/linux/virtio_config.h:149
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:config_work_handler
  - drivers/char/virtio_console.c:config_work_handler
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
In drivers/virtio/virtio.c (ffffffff81604572)
Location: include/linux/virtio_config.h:155
Inline: True
```
```
In drivers/virtio/virtio_ring.c (ffffffff81605d75)
Location: include/linux/virtio_config.h:155
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
In drivers/virtio/virtio_balloon.c (ffffffff8160b68c)
Location: include/linux/virtio_config.h:155
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
In drivers/char/virtio_console.c (ffffffff8166a86a)
Location: include/linux/virtio_config.h:155
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:config_work_handler
  - drivers/char/virtio_console.c:config_work_handler
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
In drivers/virtio/virtio.c (ffffffff81636f64)
Location: include/linux/virtio_config.h:155
Inline: True
```
```
In drivers/virtio/virtio_ring.c (ffffffff81637ef5)
Location: include/linux/virtio_config.h:155
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
In drivers/virtio/virtio_balloon.c (ffffffff8163f580)
Location: include/linux/virtio_config.h:155
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
In drivers/char/virtio_console.c (ffffffff816a068b)
Location: include/linux/virtio_config.h:155
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:config_work_handler
  - drivers/char/virtio_console.c:config_work_handler
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
In drivers/virtio/virtio.c (ffffffff81658cc4)
Location: include/linux/virtio_config.h:155
Inline: True
```
```
In drivers/virtio/virtio_ring.c (ffffffff81659ce5)
Location: include/linux/virtio_config.h:155
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
In drivers/virtio/virtio_balloon.c (ffffffff816619a0)
Location: include/linux/virtio_config.h:155
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
In drivers/char/virtio_console.c (ffffffff816c3442)
Location: include/linux/virtio_config.h:155
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:config_work_handler
  - drivers/char/virtio_console.c:config_work_handler
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
In drivers/virtio/virtio.c (ffffffff81709518)
Location: include/linux/virtio_config.h:155
Inline: True
```
```
In drivers/virtio/virtio_ring.c (ffffffff8170b295)
Location: include/linux/virtio_config.h:155
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
In drivers/virtio/virtio_balloon.c (ffffffff8171053a)
Location: include/linux/virtio_config.h:155
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
In drivers/char/virtio_console.c (ffffffff81776e8e)
Location: include/linux/virtio_config.h:155
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:config_work_handler
  - drivers/char/virtio_console.c:config_work_handler
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
In drivers/virtio/virtio.c (ffffffff817264c8)
Location: include/linux/virtio_config.h:164
Inline: True
```
```
In drivers/virtio/virtio_ring.c (ffffffff817280f5)
Location: include/linux/virtio_config.h:164
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
In drivers/virtio/virtio_balloon.c (ffffffff8172d104)
Location: include/linux/virtio_config.h:164
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
In drivers/char/virtio_console.c (ffffffff81791c03)
Location: include/linux/virtio_config.h:164
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:config_work_handler
  - drivers/char/virtio_console.c:config_work_handler
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
In drivers/virtio/virtio.c (ffffffff8170a271)
Location: include/linux/virtio_config.h:164
Inline: True
```
```
In drivers/virtio/virtio_ring.c (ffffffff8170c625)
Location: include/linux/virtio_config.h:164
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
In drivers/virtio/virtio_balloon.c (ffffffff81710564)
Location: include/linux/virtio_config.h:164
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
In drivers/char/virtio_console.c (ffffffff817746f0)
Location: include/linux/virtio_config.h:164
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:config_work_handler
  - drivers/char/virtio_console.c:config_work_handler
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
Location: include/linux/virtio_config.h:165
Inline: True
Inline callers:
  - drivers/virtio/virtio.c:virtio_features_ok
  - drivers/virtio/virtio.c:virtio_features_ok
  - drivers/virtio/virtio.c:virtio_features_ok
```
```
In drivers/virtio/virtio_ring.c (ffffffff81788a15)
Location: include/linux/virtio_config.h:165
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
In drivers/virtio/virtio_balloon.c (ffffffff8178cf3e)
Location: include/linux/virtio_config.h:165
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
In drivers/char/virtio_console.c (ffffffff817faaf0)
Location: include/linux/virtio_config.h:165
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:config_work_handler
  - drivers/char/virtio_console.c:config_work_handler
```
```
In drivers/iommu/virtio-iommu.c (ffffffff8182f621)
Location: include/linux/virtio_config.h:165
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
Location: include/linux/virtio_config.h:171
Inline: True
Inline callers:
  - drivers/virtio/virtio.c:virtio_features_ok
  - drivers/virtio/virtio.c:virtio_features_ok
  - drivers/virtio/virtio.c:virtio_features_ok
```
```
In drivers/virtio/virtio_ring.c (ffffffff818bf048)
Location: include/linux/virtio_config.h:171
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
In drivers/virtio/virtio_balloon.c (ffffffff818c503e)
Location: include/linux/virtio_config.h:171
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
In drivers/char/virtio_console.c (ffffffff81939aa2)
Location: include/linux/virtio_config.h:171
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:config_work_handler
  - drivers/char/virtio_console.c:config_work_handler
```
```
In drivers/iommu/virtio-iommu.c (ffffffff81970825)
Location: include/linux/virtio_config.h:171
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
Location: include/linux/virtio_config.h:185
Inline: True
Inline callers:
  - drivers/virtio/virtio.c:virtio_features_ok
  - drivers/virtio/virtio.c:virtio_features_ok
  - drivers/virtio/virtio.c:virtio_features_ok
```
```
In drivers/virtio/virtio_ring.c (ffffffff81a0e733)
Location: include/linux/virtio_config.h:185
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
In drivers/virtio/virtio_pci_modern.c (ffffffff81a135a6)
Location: include/linux/virtio_config.h:185
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_modern.c:vp_modern_disable_vq_and_reset
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81a158de)
Location: include/linux/virtio_config.h:185
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
In drivers/char/virtio_console.c (ffffffff81a99bdd)
Location: include/linux/virtio_config.h:185
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:config_work_handler
  - drivers/char/virtio_console.c:config_work_handler
```
```
In drivers/iommu/virtio-iommu.c (ffffffff81adb645)
Location: include/linux/virtio_config.h:185
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
Location: include/linux/virtio_config.h:187
Inline: True
Inline callers:
  - drivers/virtio/virtio.c:virtio_features_ok
  - drivers/virtio/virtio.c:virtio_features_ok
  - drivers/virtio/virtio.c:virtio_features_ok
```
```
In drivers/virtio/virtio_ring.c (ffffffff81a57683)
Location: include/linux/virtio_config.h:187
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
In drivers/virtio/virtio_pci_modern.c (ffffffff81a5c604)
Location: include/linux/virtio_config.h:187
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_modern.c:vp_modern_disable_vq_and_reset
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81a5ec7a)
Location: include/linux/virtio_config.h:187
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
In drivers/char/virtio_console.c (ffffffff81ae544d)
Location: include/linux/virtio_config.h:187
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:config_work_handler
  - drivers/char/virtio_console.c:config_work_handler
```
```
In drivers/iommu/virtio-iommu.c (ffffffff81b29905)
Location: include/linux/virtio_config.h:187
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
Location: include/linux/virtio_config.h:187
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
In drivers/scsi/virtio_scsi.c (ffffffff81be32e9)
Location: include/linux/virtio_config.h:187
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
In drivers/net/virtio_net.c (ffffffff81c52255)
Location: include/linux/virtio_config.h:187
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
Location: include/linux/virtio_config.h:191
Inline: True
Inline callers:
  - drivers/virtio/virtio.c:virtio_features_ok
  - drivers/virtio/virtio.c:virtio_features_ok
  - drivers/virtio/virtio.c:virtio_features_ok
```
```
In drivers/virtio/virtio_ring.c (ffffffff81aa8eb3)
Location: include/linux/virtio_config.h:191
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
In drivers/virtio/virtio_pci_modern.c (ffffffff81aad935)
Location: include/linux/virtio_config.h:191
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_modern.c:vp_modern_create_avq
  - drivers/virtio/virtio_pci_modern.c:del_vq
  - drivers/virtio/virtio_pci_modern.c:setup_vq
  - drivers/virtio/virtio_pci_modern.c:vp_modern_disable_vq_and_reset
  - drivers/virtio/virtio_pci_modern.c:vp_reset
  - drivers/virtio/virtio_pci_modern.c:vp_set_status
  - drivers/virtio/virtio_pci_modern.c:vp_modern_admin_cmd_exec
```
```
In drivers/virtio/virtio_pci_admin_legacy_io.c (ffffffff81ab00d5)
Location: include/linux/virtio_config.h:191
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_admin_legacy_io.c:virtio_pci_admin_has_legacy_io
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81ab13da)
Location: include/linux/virtio_config.h:191
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
In drivers/char/virtio_console.c (ffffffff81b38846)
Location: include/linux/virtio_config.h:191
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:config_work_handler
  - drivers/char/virtio_console.c:config_work_handler
```
```
In drivers/iommu/virtio-iommu.c (ffffffff81b808f5)
Location: include/linux/virtio_config.h:191
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
Location: include/linux/virtio_config.h:191
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
In drivers/scsi/virtio_scsi.c (ffffffff81c38749)
Location: include/linux/virtio_config.h:191
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
In drivers/net/virtio_net.c (ffffffff81d08628)
Location: include/linux/virtio_config.h:191
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
In drivers/virtio/virtio.c (ffff800010821194)
Location: include/linux/virtio_config.h:155
Inline: True
```
```
In drivers/virtio/virtio_ring.c (ffff800010823630)
Location: include/linux/virtio_config.h:155
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
In drivers/virtio/virtio_balloon.c (ffff80001082abec)
Location: include/linux/virtio_config.h:155
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
In drivers/char/virtio_console.c (ffff8000108b5850)
Location: include/linux/virtio_config.h:155
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:config_work_handler
  - drivers/char/virtio_console.c:config_work_handler
```
```
In drivers/iommu/virtio-iommu.c (ffff8000108dbfe4)
Location: include/linux/virtio_config.h:155
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
In drivers/virtio/virtio.c (c093efa0)
Location: include/linux/virtio_config.h:155
Inline: True
```
```
In drivers/virtio/virtio_ring.c (c09411a8)
Location: include/linux/virtio_config.h:155
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
In drivers/virtio/virtio_balloon.c (c0948b3c)
Location: include/linux/virtio_config.h:155
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
In drivers/char/virtio_console.c (c09b04a0)
Location: include/linux/virtio_config.h:155
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:config_work_handler
  - drivers/char/virtio_console.c:config_work_handler
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
In drivers/virtio/virtio.c (c0000000008cac90)
Location: include/linux/virtio_config.h:155
Inline: True
```
```
In drivers/virtio/virtio_ring.c (c0000000008cc120)
Location: include/linux/virtio_config.h:155
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
In drivers/virtio/virtio_balloon.c (c0000000008d7ec4)
Location: include/linux/virtio_config.h:155
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
In drivers/char/virtio_console.c (c00000000094ff70)
Location: include/linux/virtio_config.h:155
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:config_work_handler
  - drivers/char/virtio_console.c:config_work_handler
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
In drivers/virtio/virtio.c (ffffffe0005181b2)
Location: include/linux/virtio_config.h:155
Inline: True
```
```
In drivers/virtio/virtio_ring.c (ffffffe000519e50)
Location: include/linux/virtio_config.h:155
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
In drivers/virtio/virtio_balloon.c (ffffffe000520ddc)
Location: include/linux/virtio_config.h:155
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
In drivers/char/virtio_console.c (ffffffe000566c48)
Location: include/linux/virtio_config.h:155
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:config_work_handler
  - drivers/char/virtio_console.c:config_work_handler
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
In drivers/virtio/virtio.c (ffffffff8161eb64)
Location: include/linux/virtio_config.h:155
Inline: True
```
```
In drivers/virtio/virtio_ring.c (ffffffff8161fb85)
Location: include/linux/virtio_config.h:155
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
In drivers/virtio/virtio_balloon.c (ffffffff81627810)
Location: include/linux/virtio_config.h:155
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
In drivers/char/virtio_console.c (ffffffff81688e92)
Location: include/linux/virtio_config.h:155
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:config_work_handler
  - drivers/char/virtio_console.c:config_work_handler
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
In drivers/virtio/virtio.c (ffffffff81613254)
Location: include/linux/virtio_config.h:155
Inline: True
```
```
In drivers/virtio/virtio_ring.c (ffffffff81614115)
Location: include/linux/virtio_config.h:155
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
In drivers/virtio/virtio_balloon.c (ffffffff8161be90)
Location: include/linux/virtio_config.h:155
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
In drivers/char/virtio_console.c (ffffffff816667e1)
Location: include/linux/virtio_config.h:155
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:config_work_handler
  - drivers/char/virtio_console.c:config_work_handler
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
In drivers/virtio/virtio.c (ffffffff8164cb04)
Location: include/linux/virtio_config.h:155
Inline: True
```
```
In drivers/virtio/virtio_ring.c (ffffffff8164db25)
Location: include/linux/virtio_config.h:155
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
In drivers/virtio/virtio_balloon.c (ffffffff816557e0)
Location: include/linux/virtio_config.h:155
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
In drivers/char/virtio_console.c (ffffffff816b6fb1)
Location: include/linux/virtio_config.h:155
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:config_work_handler
  - drivers/char/virtio_console.c:config_work_handler
```
```
In drivers/scsi/virtio_scsi.c (ffffffff81772ddc)
Location: include/linux/virtio_config.h:155
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
In drivers/virtio/virtio.c (ffffffff816671d2)
Location: include/linux/virtio_config.h:155
Inline: True
```
```
In drivers/virtio/virtio_ring.c (ffffffff816681b5)
Location: include/linux/virtio_config.h:155
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
In drivers/virtio/virtio_balloon.c (ffffffff816703af)
Location: include/linux/virtio_config.h:155
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
In drivers/char/virtio_console.c (ffffffff816d1705)
Location: include/linux/virtio_config.h:155
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:config_work_handler
  - drivers/char/virtio_console.c:config_work_handler
```
</details>
</li>
</ul>

## Differences
