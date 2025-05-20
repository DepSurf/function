# Function: <code>virtio_is_little_endian</code>

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
In drivers/virtio/virtio_ring.c (0)
Location: include/linux/virtio_config.h:208
Inline: True
```
```
In drivers/virtio/virtio_balloon.c (0)
Location: include/linux/virtio_config.h:208
Inline: True
```
```
In drivers/char/virtio_console.c (0)
Location: include/linux/virtio_config.h:208
Inline: True
```
```
In drivers/block/virtio_blk.c (0)
Location: include/linux/virtio_config.h:208
Inline: True
```
```
In drivers/net/virtio_net.c (0)
Location: include/linux/virtio_config.h:208
Inline: True
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
In drivers/virtio/virtio_ring.c (0)
Location: include/linux/virtio_config.h:221
Inline: True
```
```
In drivers/virtio/virtio_balloon.c (0)
Location: include/linux/virtio_config.h:221
Inline: True
```
```
In drivers/char/virtio_console.c (0)
Location: include/linux/virtio_config.h:221
Inline: True
```
```
In drivers/block/virtio_blk.c (0)
Location: include/linux/virtio_config.h:221
Inline: True
```
```
In drivers/net/virtio_net.c (0)
Location: include/linux/virtio_config.h:221
Inline: True
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
In drivers/virtio/virtio_ring.c (0)
Location: include/linux/virtio_config.h:221
Inline: True
```
```
In drivers/virtio/virtio_balloon.c (0)
Location: include/linux/virtio_config.h:221
Inline: True
```
```
In drivers/char/virtio_console.c (0)
Location: include/linux/virtio_config.h:221
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
In drivers/virtio/virtio_ring.c (0)
Location: include/linux/virtio_config.h:246
Inline: True
```
```
In drivers/virtio/virtio_balloon.c (0)
Location: include/linux/virtio_config.h:246
Inline: True
```
```
In drivers/char/virtio_console.c (0)
Location: include/linux/virtio_config.h:246
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
In drivers/virtio/virtio_ring.c (0)
Location: include/linux/virtio_config.h:247
Inline: True
```
```
In drivers/virtio/virtio_balloon.c (0)
Location: include/linux/virtio_config.h:247
Inline: True
```
```
In drivers/char/virtio_console.c (0)
Location: include/linux/virtio_config.h:247
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
In drivers/virtio/virtio_ring.c (ffffffff815eae3d)
Location: include/linux/virtio_config.h:247
Inline: True
Inline callers:
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
Location: include/linux/virtio_config.h:247
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_restore
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
```
```
In drivers/char/virtio_console.c (ffffffff8164c9e0)
Location: include/linux/virtio_config.h:247
Inline: True
Inline callers:
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
In drivers/virtio/virtio_ring.c (ffffffff81605ce9)
Location: include/linux/virtio_config.h:253
Inline: True
Inline callers:
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
Location: include/linux/virtio_config.h:253
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_restore
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:report_free_page_func
  - drivers/virtio/virtio_balloon.c:report_free_page_func
  - drivers/virtio/virtio_balloon.c:report_free_page_func
  - drivers/virtio/virtio_balloon.c:virtio_balloon_cmd_id_received
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
```
```
In drivers/char/virtio_console.c (ffffffff8166a8b0)
Location: include/linux/virtio_config.h:253
Inline: True
Inline callers:
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
In drivers/virtio/virtio_ring.c (ffffffff81637e81)
Location: include/linux/virtio_config.h:253
Inline: True
Inline callers:
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
Location: include/linux/virtio_config.h:253
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_restore
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:report_free_page_func
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtio_balloon_cmd_id_received
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
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
In drivers/char/virtio_console.c (ffffffff816a06d8)
Location: include/linux/virtio_config.h:253
Inline: True
Inline callers:
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
In drivers/virtio/virtio_ring.c (ffffffff81659c71)
Location: include/linux/virtio_config.h:253
Inline: True
Inline callers:
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
Location: include/linux/virtio_config.h:253
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_restore
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:report_free_page_func
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtio_balloon_cmd_id_received
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
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
In drivers/char/virtio_console.c (ffffffff816c348f)
Location: include/linux/virtio_config.h:253
Inline: True
Inline callers:
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
In drivers/virtio/virtio_ring.c (ffffffff8170b222)
Location: include/linux/virtio_config.h:253
Inline: True
Inline callers:
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
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81710bbd)
Location: include/linux/virtio_config.h:253
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_restore
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:report_free_page_func
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtio_balloon_cmd_id_received
  - drivers/virtio/virtio_balloon.c:update_balloon_size_func
  - drivers/virtio/virtio_balloon.c:update_balloon_size
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
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
  - drivers/virtio/virtio_balloon.c:fill_balloon
```
```
In drivers/char/virtio_console.c (ffffffff81776edb)
Location: include/linux/virtio_config.h:253
Inline: True
Inline callers:
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
In drivers/virtio/virtio_ring.c (ffffffff8172804d)
Location: include/linux/virtio_config.h:271
Inline: True
Inline callers:
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
```
```
In drivers/virtio/virtio_balloon.c (ffffffff8172df8e)
Location: include/linux/virtio_config.h:271
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:report_free_page_func
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
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
  - drivers/virtio/virtio_balloon.c:fill_balloon
```
```
In drivers/char/virtio_console.c (ffffffff81791c03)
Location: include/linux/virtio_config.h:271
Inline: True
Inline callers:
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
In drivers/virtio/virtio_ring.c (ffffffff8170c582)
Location: include/linux/virtio_config.h:271
Inline: True
Inline callers:
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
```
```
In drivers/virtio/virtio_balloon.c (ffffffff8171145e)
Location: include/linux/virtio_config.h:271
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:report_free_page_func
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
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
  - drivers/virtio/virtio_balloon.c:fill_balloon
```
```
In drivers/char/virtio_console.c (ffffffff817746f0)
Location: include/linux/virtio_config.h:271
Inline: True
Inline callers:
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
In drivers/virtio/virtio_ring.c (ffffffff817889ea)
Location: include/linux/virtio_config.h:272
Inline: True
Inline callers:
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
In drivers/virtio/virtio_balloon.c (ffffffff8178dec1)
Location: include/linux/virtio_config.h:272
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:report_free_page_func
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
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
  - drivers/virtio/virtio_balloon.c:fill_balloon
```
```
In drivers/char/virtio_console.c (ffffffff817faaf0)
Location: include/linux/virtio_config.h:272
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:config_work_handler
  - drivers/char/virtio_console.c:config_work_handler
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
In drivers/virtio/virtio_ring.c (ffffffff818bf005)
Location: include/linux/virtio_config.h:319
Inline: True
Inline callers:
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
In drivers/virtio/virtio_balloon.c (ffffffff818c5e06)
Location: include/linux/virtio_config.h:319
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:report_free_page_func
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
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
  - drivers/virtio/virtio_balloon.c:fill_balloon
```
```
In drivers/char/virtio_console.c (ffffffff81939aa2)
Location: include/linux/virtio_config.h:319
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:config_work_handler
  - drivers/char/virtio_console.c:config_work_handler
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
In drivers/virtio/virtio_ring.c (ffffffff81a0f026)
Location: include/linux/virtio_config.h:333
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_resize
  - drivers/virtio/virtio_ring.c:virtqueue_resize
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
In drivers/virtio/virtio_balloon.c (ffffffff81a16728)
Location: include/linux/virtio_config.h:333
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:report_free_page_func
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
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
  - drivers/virtio/virtio_balloon.c:fill_balloon
```
```
In drivers/char/virtio_console.c (ffffffff81a99bdd)
Location: include/linux/virtio_config.h:333
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:config_work_handler
  - drivers/char/virtio_console.c:config_work_handler
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
In drivers/virtio/virtio_ring.c (ffffffff81a580ea)
Location: include/linux/virtio_config.h:335
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_resize
  - drivers/virtio/virtio_ring.c:virtqueue_resize
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
In drivers/virtio/virtio_balloon.c (ffffffff81a5f7c8)
Location: include/linux/virtio_config.h:335
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:report_free_page_func
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
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
  - drivers/virtio/virtio_balloon.c:fill_balloon
```
```
In drivers/char/virtio_console.c (ffffffff81ae544d)
Location: include/linux/virtio_config.h:335
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:config_work_handler
  - drivers/char/virtio_console.c:config_work_handler
```
```
In drivers/block/virtio_blk.c (ffffffff81b80ca3)
Location: include/linux/virtio_config.h:335
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
  - drivers/block/virtio_blk.c:virtblk_poll
  - drivers/block/virtio_blk.c:init_vq
  - drivers/block/virtio_blk.c:virtblk_update_capacity
  - drivers/block/virtio_blk.c:virtblk_getgeo
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
In drivers/scsi/virtio_scsi.c (ffffffff81be33e4)
Location: include/linux/virtio_config.h:335
Inline: True
Inline callers:
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
In drivers/net/virtio_net.c (ffffffff81c5175e)
Location: include/linux/virtio_config.h:335
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_validate
  - drivers/net/virtio_net.c:virtnet_config_changed_work
  - drivers/net/virtio_net.c:virtnet_vlan_rx_kill_vid
  - drivers/net/virtio_net.c:virtnet_vlan_rx_add_vid
  - drivers/net/virtio_net.c:virtnet_set_rx_mode
  - drivers/net/virtio_net.c:virtnet_set_rx_mode
  - drivers/net/virtio_net.c:_virtnet_set_queues
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
In drivers/virtio/virtio_ring.c (ffffffff81aa8e33)
Location: include/linux/virtio_config.h:339
Inline: True
Inline callers:
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
In drivers/virtio/virtio_balloon.c (ffffffff81ab1fb2)
Location: include/linux/virtio_config.h:339
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:report_free_page_func
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
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
  - drivers/virtio/virtio_balloon.c:fill_balloon
```
```
In drivers/char/virtio_console.c (ffffffff81b38846)
Location: include/linux/virtio_config.h:339
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:config_work_handler
  - drivers/char/virtio_console.c:config_work_handler
```
```
In drivers/block/virtio_blk.c (ffffffff81bd4b02)
Location: include/linux/virtio_config.h:339
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
  - drivers/block/virtio_blk.c:virtblk_poll
  - drivers/block/virtio_blk.c:init_vq
  - drivers/block/virtio_blk.c:virtblk_update_capacity
  - drivers/block/virtio_blk.c:virtblk_getgeo
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
In drivers/scsi/virtio_scsi.c (ffffffff81c38844)
Location: include/linux/virtio_config.h:339
Inline: True
Inline callers:
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
In drivers/net/virtio_net.c (ffffffff81d079f0)
Location: include/linux/virtio_config.h:339
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_validate
  - drivers/net/virtio_net.c:virtnet_config_changed_work
  - drivers/net/virtio_net.c:virtnet_vlan_rx_kill_vid
  - drivers/net/virtio_net.c:virtnet_vlan_rx_add_vid
  - drivers/net/virtio_net.c:virtnet_set_rx_mode
  - drivers/net/virtio_net.c:virtnet_set_rx_mode
  - drivers/net/virtio_net.c:_virtnet_set_queues
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
In drivers/virtio/virtio_ring.c (ffff800010823558)
Location: include/linux/virtio_config.h:253
Inline: True
Inline callers:
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
Location: include/linux/virtio_config.h:253
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_restore
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:report_free_page_func
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtio_balloon_cmd_id_received
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
```
```
In drivers/char/virtio_console.c (ffff8000108b588c)
Location: include/linux/virtio_config.h:253
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:config_work_handler
  - drivers/char/virtio_console.c:config_work_handler
```
```
In drivers/iommu/virtio-iommu.c (ffff8000108dc3a0)
Location: include/linux/virtio_config.h:253
Inline: True
Inline callers:
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
In drivers/virtio/virtio_ring.c (c0941118)
Location: include/linux/virtio_config.h:253
Inline: True
Inline callers:
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
In drivers/virtio/virtio_balloon.c (c0948b3c)
Location: include/linux/virtio_config.h:253
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_restore
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:report_free_page_func
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtio_balloon_cmd_id_received
  - drivers/virtio/virtio_balloon.c:update_balloon_size
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
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
In drivers/char/virtio_console.c (c09b04e8)
Location: include/linux/virtio_config.h:253
Inline: True
Inline callers:
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
In drivers/virtio/virtio_ring.c (c0000000008cc030)
Location: include/linux/virtio_config.h:253
Inline: True
Inline callers:
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
In drivers/virtio/virtio_balloon.c (c0000000008d7ec4)
Location: include/linux/virtio_config.h:253
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_restore
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:report_free_page_func
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtio_balloon_cmd_id_received
  - drivers/virtio/virtio_balloon.c:update_balloon_size
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:set_page_pfns
```
```
In drivers/char/virtio_console.c (c00000000094ffc8)
Location: include/linux/virtio_config.h:253
Inline: True
Inline callers:
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
In drivers/virtio/virtio_ring.c (ffffffe000519dc4)
Location: include/linux/virtio_config.h:253
Inline: True
Inline callers:
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
In drivers/virtio/virtio_balloon.c (ffffffe000520ac8)
Location: include/linux/virtio_config.h:253
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:report_free_page_func
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtio_balloon_cmd_id_received
  - drivers/virtio/virtio_balloon.c:update_balloon_size
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:set_page_pfns
```
```
In drivers/char/virtio_console.c (ffffffe000566ffc)
Location: include/linux/virtio_config.h:253
Inline: True
Inline callers:
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
In drivers/virtio/virtio_ring.c (ffffffff8161fb11)
Location: include/linux/virtio_config.h:253
Inline: True
Inline callers:
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
Location: include/linux/virtio_config.h:253
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_restore
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:report_free_page_func
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtio_balloon_cmd_id_received
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
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
In drivers/char/virtio_console.c (ffffffff81688edf)
Location: include/linux/virtio_config.h:253
Inline: True
Inline callers:
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
In drivers/virtio/virtio_ring.c (ffffffff816140a4)
Location: include/linux/virtio_config.h:253
Inline: True
Inline callers:
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
In drivers/virtio/virtio_balloon.c (ffffffff8161be90)
Location: include/linux/virtio_config.h:253
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_restore
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:report_free_page_func
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtio_balloon_cmd_id_received
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
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
In drivers/char/virtio_console.c (ffffffff816669a0)
Location: include/linux/virtio_config.h:253
Inline: True
Inline callers:
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
In drivers/virtio/virtio_ring.c (ffffffff8164dab1)
Location: include/linux/virtio_config.h:253
Inline: True
Inline callers:
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
Location: include/linux/virtio_config.h:253
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_restore
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:report_free_page_func
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtio_balloon_cmd_id_received
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
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
In drivers/char/virtio_console.c (ffffffff816b7176)
Location: include/linux/virtio_config.h:253
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:config_work_handler
  - drivers/char/virtio_console.c:config_work_handler
```
```
In drivers/scsi/virtio_scsi.c (ffffffff81772e9a)
Location: include/linux/virtio_config.h:253
Inline: True
Inline callers:
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
In drivers/virtio/virtio_ring.c (ffffffff81668141)
Location: include/linux/virtio_config.h:253
Inline: True
Inline callers:
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
Location: include/linux/virtio_config.h:253
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_restore
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:report_free_page_func
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtio_balloon_cmd_id_received
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
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
In drivers/char/virtio_console.c (ffffffff816d1748)
Location: include/linux/virtio_config.h:253
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:virtcons_probe
  - drivers/char/virtio_console.c:config_work_handler
  - drivers/char/virtio_console.c:config_work_handler
```
</details>
</li>
</ul>

## Differences
