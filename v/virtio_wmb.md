# Function: <code>virtio_wmb</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff814bfa0a)
Location: include/linux/virtio_ring.h:42
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_add_sgs
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff815104cd)
Location: include/linux/virtio_ring.h:40
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_sgs
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff8153c62d)
Location: include/linux/virtio_ring.h:40
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_sgs
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff81550307)
Location: include/linux/virtio_ring.h:40
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_sgs
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff815b3afe)
Location: include/linux/virtio_ring.h:41
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_sgs
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff815ec1ee)
Location: include/linux/virtio_ring.h:41
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_sgs
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff816052a2)
Location: include/linux/virtio_ring.h:41
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_delayed
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_prepare
  - drivers/virtio/virtio_ring.c:virtqueue_add
  - drivers/virtio/virtio_ring.c:virtqueue_add
  - drivers/virtio/virtio_ring.c:virtqueue_add
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff81638436)
Location: include/linux/virtio_ring.h:41
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_delayed
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_prepare
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_indirect_packed
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff8165a21e)
Location: include/linux/virtio_ring.h:41
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_delayed
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_prepare
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff81709f7f)
Location: include/linux/virtio_ring.h:41
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_delayed
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_prepare
  - drivers/virtio/virtio_ring.c:virtqueue_add_packed
  - drivers/virtio/virtio_ring.c:virtqueue_add_indirect_packed
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff8172717f)
Location: include/linux/virtio_ring.h:41
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_delayed
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_prepare
  - drivers/virtio/virtio_ring.c:virtqueue_add_packed
  - drivers/virtio/virtio_ring.c:virtqueue_add_indirect_packed
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff8170b169)
Location: include/linux/virtio_ring.h:41
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_delayed
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_prepare
  - drivers/virtio/virtio_ring.c:virtqueue_add_packed
  - drivers/virtio/virtio_ring.c:virtqueue_add_indirect_packed
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff817869aa)
Location: include/linux/virtio_ring.h:41
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_prepare
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_delayed_packed
  - drivers/virtio/virtio_ring.c:virtqueue_add_packed
  - drivers/virtio/virtio_ring.c:virtqueue_add_indirect_packed
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff818bda6d)
Location: include/linux/virtio_ring.h:41
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_delayed
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_prepare
  - drivers/virtio/virtio_ring.c:virtqueue_add_packed
  - drivers/virtio/virtio_ring.c:virtqueue_add_indirect_packed
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff81a0cdcd)
Location: include/linux/virtio_ring.h:41
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_delayed
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_prepare
  - drivers/virtio/virtio_ring.c:virtqueue_add_packed
  - drivers/virtio/virtio_ring.c:virtqueue_add_indirect_packed
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff81a55a5d)
Location: include/linux/virtio_ring.h:41
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_delayed
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_prepare
  - drivers/virtio/virtio_ring.c:virtqueue_add_packed
  - drivers/virtio/virtio_ring.c:virtqueue_add_indirect_packed
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff81aa6acd)
Location: include/linux/virtio_ring.h:41
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_delayed
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_prepare
  - drivers/virtio/virtio_ring.c:virtqueue_add_packed
  - drivers/virtio/virtio_ring.c:virtqueue_add_indirect_packed
  - drivers/virtio/virtio_ring.c:virtqueue_add_split
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffff800010822450)
Location: include/linux/virtio_ring.h:41
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_delayed
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_prepare
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_indirect_packed
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (c093fdc8)
Location: include/linux/virtio_ring.h:41
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_delayed
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_prepare
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (c0000000008cc9c8)
Location: include/linux/virtio_ring.h:41
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_delayed
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_prepare
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffe000518dc6)
Location: include/linux/virtio_ring.h:41
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_delayed
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_prepare
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff816200be)
Location: include/linux/virtio_ring.h:41
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_delayed
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_prepare
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff8161470e)
Location: include/linux/virtio_ring.h:41
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_delayed
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_prepare
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff8164e05e)
Location: include/linux/virtio_ring.h:41
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_delayed
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_prepare
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff816686ee)
Location: include/linux/virtio_ring.h:41
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_delayed
  - drivers/virtio/virtio_ring.c:virtqueue_enable_cb_prepare
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf_ctx
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_inbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
  - drivers/virtio/virtio_ring.c:virtqueue_add_outbuf
```
</details>
</li>
</ul>

## Differences
