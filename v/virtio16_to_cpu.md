# Function: <code>virtio16_to_cpu</code>

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
Location: include/linux/virtio_config.h:215
Inline: True
```
```
In drivers/char/virtio_console.c (0)
Location: include/linux/virtio_config.h:215
Inline: True
```
```
In drivers/block/virtio_blk.c (0)
Location: include/linux/virtio_config.h:215
Inline: True
```
```
In drivers/net/virtio_net.c (0)
Location: include/linux/virtio_config.h:215
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
Location: include/linux/virtio_config.h:228
Inline: True
```
```
In drivers/char/virtio_console.c (0)
Location: include/linux/virtio_config.h:228
Inline: True
```
```
In drivers/block/virtio_blk.c (0)
Location: include/linux/virtio_config.h:228
Inline: True
```
```
In drivers/net/virtio_net.c (0)
Location: include/linux/virtio_config.h:228
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
Location: include/linux/virtio_config.h:228
Inline: True
```
```
In drivers/char/virtio_console.c (0)
Location: include/linux/virtio_config.h:228
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
Location: include/linux/virtio_config.h:253
Inline: True
```
```
In drivers/char/virtio_console.c (0)
Location: include/linux/virtio_config.h:253
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
Location: include/linux/virtio_config.h:254
Inline: True
```
```
In drivers/char/virtio_console.c (0)
Location: include/linux/virtio_config.h:254
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
In drivers/virtio/virtio_ring.c (ffffffff815eabf8)
Location: include/linux/virtio_config.h:254
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_delayed
  - drivers/virtio/virtio_ring.c:virtqueue_poll
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx
  - drivers/virtio/virtio_ring.c:detach_buf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_sgs
  - drivers/virtio/virtio_ring.c:virtqueue_add_sgs
  - drivers/virtio/virtio_ring.c:virtqueue_add_sgs
  - drivers/virtio/virtio_ring.c:virtqueue_add_sgs
```
```
In drivers/char/virtio_console.c (ffffffff8164aa95)
Location: include/linux/virtio_config.h:254
Inline: True
Inline callers:
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
In drivers/virtio/virtio_ring.c (ffffffff81605340)
Location: include/linux/virtio_config.h:260
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_delayed
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_kick_prepare
  - drivers/virtio/virtio_ring.c:virtqueue_add
  - drivers/virtio/virtio_ring.c:virtqueue_add
  - drivers/virtio/virtio_ring.c:virtqueue_add
  - drivers/virtio/virtio_ring.c:virtqueue_add
  - drivers/virtio/virtio_ring.c:detach_buf_split
```
```
In drivers/char/virtio_console.c (ffffffff81668d55)
Location: include/linux/virtio_config.h:260
Inline: True
Inline callers:
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
In drivers/virtio/virtio_ring.c (ffffffff816384bb)
Location: include/linux/virtio_config.h:260
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_delayed
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_kick_prepare
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:detach_buf_split
```
```
In drivers/char/virtio_console.c (ffffffff8169e6a3)
Location: include/linux/virtio_config.h:260
Inline: True
Inline callers:
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
In drivers/virtio/virtio_ring.c (ffffffff8165a2a5)
Location: include/linux/virtio_config.h:260
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_delayed
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_kick_prepare
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:detach_buf_split
```
```
In drivers/char/virtio_console.c (ffffffff816c1753)
Location: include/linux/virtio_config.h:260
Inline: True
Inline callers:
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
In drivers/virtio/virtio_ring.c (ffffffff8170a01d)
Location: include/linux/virtio_config.h:260
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_delayed
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb
  - drivers/virtio/virtio_ring.c:virtqueue_kick_prepare
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx_split
  - drivers/virtio/virtio_ring.c:detach_buf_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
```
```
In drivers/char/virtio_console.c (ffffffff81774fd1)
Location: include/linux/virtio_config.h:260
Inline: True
Inline callers:
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
In drivers/virtio/virtio_ring.c (ffffffff8172721d)
Location: include/linux/virtio_config.h:278
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_delayed
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb
  - drivers/virtio/virtio_ring.c:virtqueue_kick_prepare
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx_split
  - drivers/virtio/virtio_ring.c:detach_buf_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
```
```
In drivers/char/virtio_console.c (ffffffff8178fd1c)
Location: include/linux/virtio_config.h:278
Inline: True
Inline callers:
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
In drivers/virtio/virtio_ring.c (ffffffff8170b1ed)
Location: include/linux/virtio_config.h:278
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_delayed
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb
  - drivers/virtio/virtio_ring.c:virtqueue_kick_prepare
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx_split
  - drivers/virtio/virtio_ring.c:detach_buf_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
```
```
In drivers/char/virtio_console.c (ffffffff8177289c)
Location: include/linux/virtio_config.h:278
Inline: True
Inline callers:
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
In drivers/virtio/virtio_ring.c (ffffffff81786b34)
Location: include/linux/virtio_config.h:279
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_delayed
  - drivers/virtio/virtio_ring.c:virtqueue_poll
  - drivers/virtio/virtio_ring.c:virtqueue_kick_prepare
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
```
```
In drivers/char/virtio_console.c (ffffffff817f87ac)
Location: include/linux/virtio_config.h:279
Inline: True
Inline callers:
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
In drivers/virtio/virtio_ring.c (ffffffff818bdb42)
Location: include/linux/virtio_config.h:326
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_delayed
  - drivers/virtio/virtio_ring.c:virtqueue_poll
  - drivers/virtio/virtio_ring.c:virtqueue_kick_prepare
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
```
```
In drivers/char/virtio_console.c (ffffffff819369c2)
Location: include/linux/virtio_config.h:326
Inline: True
Inline callers:
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
In drivers/virtio/virtio_ring.c (ffffffff81a0ceae)
Location: include/linux/virtio_config.h:340
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_delayed
  - drivers/virtio/virtio_ring.c:virtqueue_poll
  - drivers/virtio/virtio_ring.c:virtqueue_kick_prepare
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
```
```
In drivers/char/virtio_console.c (ffffffff81a96852)
Location: include/linux/virtio_config.h:340
Inline: True
Inline callers:
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
In drivers/virtio/virtio_ring.c (ffffffff81a55b32)
Location: include/linux/virtio_config.h:342
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_delayed
  - drivers/virtio/virtio_ring.c:virtqueue_poll
  - drivers/virtio/virtio_ring.c:virtqueue_kick_prepare
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
```
```
In drivers/char/virtio_console.c (ffffffff81ae2062)
Location: include/linux/virtio_config.h:342
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:config_work_handler
  - drivers/char/virtio_console.c:config_work_handler
```
```
In drivers/block/virtio_blk.c (ffffffff81b8135e)
Location: include/linux/virtio_config.h:342
Inline: True
Inline callers:
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:init_vq
  - drivers/block/virtio_blk.c:virtblk_getgeo
```
```
In drivers/scsi/virtio_scsi.c (ffffffff81be3437)
Location: include/linux/virtio_config.h:342
Inline: True
Inline callers:
  - drivers/scsi/virtio_scsi.c:virtscsi_probe
```
```
In drivers/net/virtio_net.c (ffffffff81c5175e)
Location: include/linux/virtio_config.h:342
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_validate
  - drivers/net/virtio_net.c:virtnet_config_changed_work
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
In drivers/virtio/virtio_ring.c (ffffffff81aa6ba2)
Location: include/linux/virtio_config.h:346
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_delayed
  - drivers/virtio/virtio_ring.c:virtqueue_poll
  - drivers/virtio/virtio_ring.c:virtqueue_kick_prepare
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
```
```
In drivers/char/virtio_console.c (ffffffff81b35452)
Location: include/linux/virtio_config.h:346
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:config_work_handler
  - drivers/char/virtio_console.c:config_work_handler
```
```
In drivers/block/virtio_blk.c (ffffffff81bd521c)
Location: include/linux/virtio_config.h:346
Inline: True
Inline callers:
  - drivers/block/virtio_blk.c:virtblk_probe
  - drivers/block/virtio_blk.c:init_vq
  - drivers/block/virtio_blk.c:virtblk_getgeo
```
```
In drivers/scsi/virtio_scsi.c (ffffffff81c38897)
Location: include/linux/virtio_config.h:346
Inline: True
Inline callers:
  - drivers/scsi/virtio_scsi.c:virtscsi_probe
```
```
In drivers/net/virtio_net.c (ffffffff81d079f0)
Location: include/linux/virtio_config.h:346
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_probe
  - drivers/net/virtio_net.c:virtnet_validate
  - drivers/net/virtio_net.c:virtnet_config_changed_work
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
In drivers/virtio/virtio_ring.c (ffff800010822514)
Location: include/linux/virtio_config.h:260
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_delayed
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_kick_prepare
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:detach_buf_split
```
```
In drivers/char/virtio_console.c (ffff8000108b3780)
Location: include/linux/virtio_config.h:260
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:config_work_handler
  - drivers/char/virtio_console.c:config_work_handler
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
In drivers/virtio/virtio_ring.c (c093feac)
Location: include/linux/virtio_config.h:260
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_delayed
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_kick_prepare
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:detach_buf_split
```
```
In drivers/char/virtio_console.c (c09aee34)
Location: include/linux/virtio_config.h:260
Inline: True
Inline callers:
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
In drivers/virtio/virtio_ring.c (c0000000008cca9c)
Location: include/linux/virtio_config.h:260
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_delayed
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_kick_prepare
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:detach_buf_split
```
```
In drivers/char/virtio_console.c (c00000000094cc64)
Location: include/linux/virtio_config.h:260
Inline: True
Inline callers:
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
In drivers/virtio/virtio_ring.c (ffffffe000518e80)
Location: include/linux/virtio_config.h:260
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_delayed
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_kick_prepare
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:detach_buf_split
```
```
In drivers/char/virtio_console.c (ffffffe0005656ca)
Location: include/linux/virtio_config.h:260
Inline: True
Inline callers:
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
In drivers/virtio/virtio_ring.c (ffffffff81620145)
Location: include/linux/virtio_config.h:260
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_delayed
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_kick_prepare
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:detach_buf_split
```
```
In drivers/char/virtio_console.c (ffffffff816871a3)
Location: include/linux/virtio_config.h:260
Inline: True
Inline callers:
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
In drivers/virtio/virtio_ring.c (ffffffff81614795)
Location: include/linux/virtio_config.h:260
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_delayed
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_kick_prepare
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:detach_buf_split
```
```
In drivers/char/virtio_console.c (ffffffff81664d93)
Location: include/linux/virtio_config.h:260
Inline: True
Inline callers:
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
In drivers/virtio/virtio_ring.c (ffffffff8164e0e5)
Location: include/linux/virtio_config.h:260
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_delayed
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_kick_prepare
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:detach_buf_split
```
```
In drivers/char/virtio_console.c (ffffffff816b54e3)
Location: include/linux/virtio_config.h:260
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:config_work_handler
  - drivers/char/virtio_console.c:config_work_handler
```
```
In drivers/scsi/virtio_scsi.c (ffffffff81772ed8)
Location: include/linux/virtio_config.h:260
Inline: True
Inline callers:
  - drivers/scsi/virtio_scsi.c:virtscsi_probe
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
In drivers/virtio/virtio_ring.c (ffffffff81668775)
Location: include/linux/virtio_config.h:260
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_delayed
  - drivers/virtio/virtio_ring.c:virtqueue_get_buf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_kick_prepare
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:detach_buf_split
```
```
In drivers/char/virtio_console.c (ffffffff816cff92)
Location: include/linux/virtio_config.h:260
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:config_work_handler
  - drivers/char/virtio_console.c:config_work_handler
```
</details>
</li>
</ul>

## Differences
