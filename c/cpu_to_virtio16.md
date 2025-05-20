# Function: <code>cpu_to_virtio16</code>

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
Location: include/linux/virtio_config.h:220
Inline: True
```
```
In drivers/virtio/virtio_balloon.c (0)
Location: include/linux/virtio_config.h:220
Inline: True
```
```
In drivers/char/virtio_console.c (0)
Location: include/linux/virtio_config.h:220
Inline: True
```
```
In drivers/net/virtio_net.c (0)
Location: include/linux/virtio_config.h:220
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
Location: include/linux/virtio_config.h:233
Inline: True
```
```
In drivers/virtio/virtio_balloon.c (0)
Location: include/linux/virtio_config.h:233
Inline: True
```
```
In drivers/char/virtio_console.c (0)
Location: include/linux/virtio_config.h:233
Inline: True
```
```
In drivers/net/virtio_net.c (0)
Location: include/linux/virtio_config.h:233
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
Location: include/linux/virtio_config.h:233
Inline: True
```
```
In drivers/virtio/virtio_balloon.c (0)
Location: include/linux/virtio_config.h:233
Inline: True
```
```
In drivers/char/virtio_console.c (0)
Location: include/linux/virtio_config.h:233
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
Location: include/linux/virtio_config.h:258
Inline: True
```
```
In drivers/virtio/virtio_balloon.c (0)
Location: include/linux/virtio_config.h:258
Inline: True
```
```
In drivers/char/virtio_console.c (0)
Location: include/linux/virtio_config.h:258
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
Location: include/linux/virtio_config.h:259
Inline: True
```
```
In drivers/virtio/virtio_balloon.c (0)
Location: include/linux/virtio_config.h:259
Inline: True
```
```
In drivers/char/virtio_console.c (0)
Location: include/linux/virtio_config.h:259
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
Location: include/linux/virtio_config.h:259
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_delayed
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_delayed
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_prepare
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_prepare
  - drivers/virtio/virtio_ring.c:virtqueue_disable_cb
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx
  - drivers/virtio/virtio_ring.c:detach_buf
  - drivers/virtio/virtio_ring.c:detach_buf
  - drivers/virtio/virtio_ring.c:detach_buf
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
```
```
In drivers/virtio/virtio_balloon.c (ffffffff815f0319)
Location: include/linux/virtio_config.h:259
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
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
In drivers/char/virtio_console.c (ffffffff8164acf3)
Location: include/linux/virtio_config.h:259
Inline: True
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
Location: include/linux/virtio_config.h:265
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:virtqueue_detach_unused_buf
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_delayed
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_delayed
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_prepare
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_prepare
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_kick_prepare
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
```
```
In drivers/virtio/virtio_balloon.c (ffffffff8160a8f9)
Location: include/linux/virtio_config.h:265
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
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
In drivers/char/virtio_console.c (ffffffff81668ad3)
Location: include/linux/virtio_config.h:265
Inline: True
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
Location: include/linux/virtio_config.h:265
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:virtqueue_detach_unused_buf
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_delayed
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_delayed
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_prepare
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_prepare
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_kick_prepare
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
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:detach_buf_split
  - drivers/virtio/virtio_ring.c:detach_buf_split
  - drivers/virtio/virtio_ring.c:detach_buf_split
```
```
In drivers/virtio/virtio_balloon.c (ffffffff8163e6f9)
Location: include/linux/virtio_config.h:265
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
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
In drivers/char/virtio_console.c (ffffffff8169e42d)
Location: include/linux/virtio_config.h:265
Inline: True
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
Location: include/linux/virtio_config.h:265
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:virtqueue_detach_unused_buf
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_delayed
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_delayed
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_prepare
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_prepare
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_kick_prepare
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
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:detach_buf_split
  - drivers/virtio/virtio_ring.c:detach_buf_split
  - drivers/virtio/virtio_ring.c:detach_buf_split
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81660c69)
Location: include/linux/virtio_config.h:265
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
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
In drivers/char/virtio_console.c (ffffffff816c145d)
Location: include/linux/virtio_config.h:265
Inline: True
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
Location: include/linux/virtio_config.h:265
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:virtqueue_detach_unused_buf
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_delayed
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_delayed
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_prepare
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_prepare
  - drivers/virtio/virtio_ring.c:virtqueue_kick_prepare
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx_split
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
```
```
In drivers/virtio/virtio_balloon.c (ffffffff8170fff8)
Location: include/linux/virtio_config.h:265
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
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
In drivers/char/virtio_console.c (ffffffff81775b9d)
Location: include/linux/virtio_config.h:265
Inline: True
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
Location: include/linux/virtio_config.h:283
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
  - drivers/virtio/virtio_ring.c:virtqueue_kick_prepare
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx_split
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx_split
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
```
```
In drivers/virtio/virtio_balloon.c (ffffffff8172cce8)
Location: include/linux/virtio_config.h:283
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
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
In drivers/char/virtio_console.c (ffffffff817908cd)
Location: include/linux/virtio_config.h:283
Inline: True
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
Location: include/linux/virtio_config.h:283
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
  - drivers/virtio/virtio_ring.c:virtqueue_kick_prepare
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx_split
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx_split
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
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81710899)
Location: include/linux/virtio_config.h:283
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
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
In drivers/char/virtio_console.c (ffffffff81773a2f)
Location: include/linux/virtio_config.h:283
Inline: True
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
Location: include/linux/virtio_config.h:284
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:virtqueue_detach_unused_buf
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_delayed
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_delayed
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_delayed
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_prepare
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_prepare
  - drivers/virtio/virtio_ring.c:virtqueue_kick_prepare
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
```
```
In drivers/virtio/virtio_balloon.c (ffffffff8178d289)
Location: include/linux/virtio_config.h:284
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
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
In drivers/char/virtio_console.c (ffffffff817f986f)
Location: include/linux/virtio_config.h:284
Inline: True
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
Location: include/linux/virtio_config.h:331
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:virtqueue_detach_unused_buf
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_delayed
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_delayed
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_delayed
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_prepare
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_prepare
  - drivers/virtio/virtio_ring.c:virtqueue_kick_prepare
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
```
```
In drivers/virtio/virtio_balloon.c (ffffffff818c545b)
Location: include/linux/virtio_config.h:331
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
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
In drivers/char/virtio_console.c (ffffffff819367ff)
Location: include/linux/virtio_config.h:331
Inline: True
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
Location: include/linux/virtio_config.h:345
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_resize
  - drivers/virtio/virtio_ring.c:virtqueue_resize
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:virtqueue_detach_unused_buf
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_delayed
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_delayed
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_delayed
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_prepare
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_prepare
  - drivers/virtio/virtio_ring.c:virtqueue_kick_prepare
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
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81a15d4b)
Location: include/linux/virtio_config.h:345
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
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
In drivers/char/virtio_console.c (ffffffff81a9665f)
Location: include/linux/virtio_config.h:345
Inline: True
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
Location: include/linux/virtio_config.h:347
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_resize
  - drivers/virtio/virtio_ring.c:virtqueue_resize
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:virtqueue_detach_unused_buf
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_delayed
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_delayed
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_delayed
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_prepare
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_prepare
  - drivers/virtio/virtio_ring.c:virtqueue_disable_cb
  - drivers/virtio/virtio_ring.c:virtqueue_kick_prepare
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
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81a5edfb)
Location: include/linux/virtio_config.h:347
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
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
In drivers/char/virtio_console.c (ffffffff81ae1e6f)
Location: include/linux/virtio_config.h:347
Inline: True
```
```
In drivers/net/virtio_net.c (ffffffff81c4d67c)
Location: include/linux/virtio_config.h:347
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:virtnet_vlan_rx_kill_vid
  - drivers/net/virtio_net.c:virtnet_vlan_rx_add_vid
  - drivers/net/virtio_net.c:_virtnet_set_queues
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
Location: include/linux/virtio_config.h:351
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:virtqueue_detach_unused_buf
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_delayed
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_delayed
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_delayed
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_prepare
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_prepare
  - drivers/virtio/virtio_ring.c:virtqueue_disable_cb
  - drivers/virtio/virtio_ring.c:virtqueue_kick_prepare
  - drivers/virtio/virtio_ring.c:virtqueue_reinit_split
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
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81ab155b)
Location: include/linux/virtio_config.h:351
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
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
In drivers/char/virtio_console.c (ffffffff81b3525f)
Location: include/linux/virtio_config.h:351
Inline: True
```
```
In drivers/net/virtio_net.c (ffffffff81d02c1c)
Location: include/linux/virtio_config.h:351
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:virtnet_vlan_rx_kill_vid
  - drivers/net/virtio_net.c:virtnet_vlan_rx_add_vid
  - drivers/net/virtio_net.c:_virtnet_set_queues
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
Location: include/linux/virtio_config.h:265
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:virtqueue_detach_unused_buf
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_delayed
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_delayed
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_prepare
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_prepare
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_kick_prepare
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
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:detach_buf_split
  - drivers/virtio/virtio_ring.c:detach_buf_split
  - drivers/virtio/virtio_ring.c:detach_buf_split
```
```
In drivers/virtio/virtio_balloon.c (ffff8000108299ac)
Location: include/linux/virtio_config.h:265
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
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
In drivers/char/virtio_console.c (ffff8000108b2f0c)
Location: include/linux/virtio_config.h:265
Inline: True
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
Location: include/linux/virtio_config.h:265
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:virtqueue_detach_unused_buf
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_delayed
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_delayed
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_prepare
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_prepare
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_kick_prepare
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
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:detach_buf_split
  - drivers/virtio/virtio_ring.c:detach_buf_split
  - drivers/virtio/virtio_ring.c:detach_buf_split
```
```
In drivers/virtio/virtio_balloon.c (c0947b9c)
Location: include/linux/virtio_config.h:265
Inline: True
Inline callers:
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
In drivers/char/virtio_console.c (c09ae4e4)
Location: include/linux/virtio_config.h:265
Inline: True
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
Location: include/linux/virtio_config.h:265
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:virtqueue_detach_unused_buf
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_delayed
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_delayed
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_prepare
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_prepare
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_kick_prepare
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
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:detach_buf_split
  - drivers/virtio/virtio_ring.c:detach_buf_split
  - drivers/virtio/virtio_ring.c:detach_buf_split
```
```
In drivers/virtio/virtio_balloon.c (c0000000008d7a98)
Location: include/linux/virtio_config.h:265
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
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
In drivers/char/virtio_console.c (c00000000094c810)
Location: include/linux/virtio_config.h:265
Inline: True
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
Location: include/linux/virtio_config.h:265
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:virtqueue_detach_unused_buf
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_delayed
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_delayed
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_prepare
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_prepare
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_kick_prepare
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
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:detach_buf_split
  - drivers/virtio/virtio_ring.c:detach_buf_split
  - drivers/virtio/virtio_ring.c:detach_buf_split
```
```
In drivers/virtio/virtio_balloon.c (ffffffe000520656)
Location: include/linux/virtio_config.h:265
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
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
In drivers/char/virtio_console.c (ffffffe00056605a)
Location: include/linux/virtio_config.h:265
Inline: True
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
Location: include/linux/virtio_config.h:265
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:virtqueue_detach_unused_buf
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_delayed
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_delayed
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_prepare
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_prepare
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_kick_prepare
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
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:detach_buf_split
  - drivers/virtio/virtio_ring.c:detach_buf_split
  - drivers/virtio/virtio_ring.c:detach_buf_split
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81626ad9)
Location: include/linux/virtio_config.h:265
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
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
In drivers/char/virtio_console.c (ffffffff81686ead)
Location: include/linux/virtio_config.h:265
Inline: True
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
Location: include/linux/virtio_config.h:265
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:virtqueue_detach_unused_buf
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_delayed
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_delayed
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_prepare
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_prepare
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_kick_prepare
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
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:detach_buf_split
  - drivers/virtio/virtio_ring.c:detach_buf_split
  - drivers/virtio/virtio_ring.c:detach_buf_split
```
```
In drivers/virtio/virtio_balloon.c (ffffffff8161b159)
Location: include/linux/virtio_config.h:265
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
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
In drivers/char/virtio_console.c (ffffffff81664aad)
Location: include/linux/virtio_config.h:265
Inline: True
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
Location: include/linux/virtio_config.h:265
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:virtqueue_detach_unused_buf
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_delayed
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_delayed
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_prepare
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_prepare
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_kick_prepare
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
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:detach_buf_split
  - drivers/virtio/virtio_ring.c:detach_buf_split
  - drivers/virtio/virtio_ring.c:detach_buf_split
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81654aa9)
Location: include/linux/virtio_config.h:265
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
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
In drivers/char/virtio_console.c (ffffffff816b51fd)
Location: include/linux/virtio_config.h:265
Inline: True
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
Location: include/linux/virtio_config.h:265
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
  - drivers/virtio/virtio_ring.c:virtqueue_detach_unused_buf
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_delayed
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_delayed
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_prepare
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_prepare
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_kick_prepare
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
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:detach_buf_split
  - drivers/virtio/virtio_ring.c:detach_buf_split
  - drivers/virtio/virtio_ring.c:detach_buf_split
```
```
In drivers/virtio/virtio_balloon.c (ffffffff8166f479)
Location: include/linux/virtio_config.h:265
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
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
In drivers/char/virtio_console.c (ffffffff816cf9fd)
Location: include/linux/virtio_config.h:265
Inline: True
```
</details>
</li>
</ul>

## Differences
