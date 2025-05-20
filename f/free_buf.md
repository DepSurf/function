# Function: <code>free_buf</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void free_buf(struct port_buffer *buf, bool can_sleep);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff815169d0)
Location: drivers/char/virtio_console.c:365
Inline: True
Direct callers:
  - drivers/char/virtio_console.c:reclaim_dma_bufs
  - drivers/char/virtio_console.c:discard_port_data
  - drivers/char/virtio_console.c:port_fops_splice_write
  - drivers/char/virtio_console.c:remove_port_data
  - drivers/char/virtio_console.c:remove_port_data
  - drivers/char/virtio_console.c:fill_queue
  - drivers/char/virtio_console.c:add_port
  - drivers/char/virtio_console.c:control_work_handler
```
**Symbols:**

```
ffffffff815169d0-ffffffff81516b23: free_buf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void free_buf(struct port_buffer *buf, bool can_sleep);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff81569620)
Location: drivers/char/virtio_console.c:371
Inline: True
Direct callers:
  - drivers/char/virtio_console.c:control_work_handler
  - drivers/char/virtio_console.c:remove_port_data
  - drivers/char/virtio_console.c:remove_port_data
  - drivers/char/virtio_console.c:add_port
  - drivers/char/virtio_console.c:fill_queue
  - drivers/char/virtio_console.c:port_fops_splice_write
  - drivers/char/virtio_console.c:discard_port_data
  - drivers/char/virtio_console.c:reclaim_dma_bufs
```
**Symbols:**

```
ffffffff81569620-ffffffff815697c1: free_buf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void free_buf(struct port_buffer *buf, bool can_sleep);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff81595d60)
Location: drivers/char/virtio_console.c:370
Inline: True
Direct callers:
  - drivers/char/virtio_console.c:control_work_handler
  - drivers/char/virtio_console.c:remove_port_data
  - drivers/char/virtio_console.c:remove_port_data
  - drivers/char/virtio_console.c:add_port
  - drivers/char/virtio_console.c:fill_queue
  - drivers/char/virtio_console.c:port_fops_splice_write
  - drivers/char/virtio_console.c:discard_port_data
  - drivers/char/virtio_console.c:reclaim_dma_bufs
```
**Symbols:**

```
ffffffff81595d60-ffffffff81595f01: free_buf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void free_buf(struct port_buffer *buf, bool can_sleep);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff815a9b80)
Location: drivers/char/virtio_console.c:370
Inline: True
Direct callers:
  - drivers/char/virtio_console.c:control_work_handler
  - drivers/char/virtio_console.c:remove_port_data
  - drivers/char/virtio_console.c:remove_port_data
  - drivers/char/virtio_console.c:add_port
  - drivers/char/virtio_console.c:fill_queue
  - drivers/char/virtio_console.c:port_fops_splice_write
  - drivers/char/virtio_console.c:discard_port_data
  - drivers/char/virtio_console.c:reclaim_dma_bufs
```
**Symbols:**

```
ffffffff815a9b80-ffffffff815a9cad: free_buf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void free_buf(struct port_buffer *buf, bool can_sleep);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff816104a0)
Location: drivers/char/virtio_console.c:370
Inline: True
Direct callers:
  - drivers/char/virtio_console.c:control_work_handler
  - drivers/char/virtio_console.c:remove_port_data
  - drivers/char/virtio_console.c:remove_port_data
  - drivers/char/virtio_console.c:add_port
  - drivers/char/virtio_console.c:fill_queue
  - drivers/char/virtio_console.c:port_fops_splice_write
  - drivers/char/virtio_console.c:discard_port_data
  - drivers/char/virtio_console.c:reclaim_dma_bufs
```
**Symbols:**

```
ffffffff816104a0-ffffffff81610610: free_buf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void free_buf(struct port_buffer *buf, bool can_sleep);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff81649f80)
Location: drivers/char/virtio_console.c:370
Inline: True
Direct callers:
  - drivers/char/virtio_console.c:remove_vqs
  - drivers/char/virtio_console.c:flush_bufs
  - drivers/char/virtio_console.c:control_work_handler
  - drivers/char/virtio_console.c:fill_queue
  - drivers/char/virtio_console.c:port_fops_splice_write
  - drivers/char/virtio_console.c:discard_port_data
  - drivers/char/virtio_console.c:reclaim_dma_bufs
```
**Symbols:**

```
ffffffff81649f80-ffffffff8164a0f5: free_buf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void free_buf(struct port_buffer *buf, bool can_sleep);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff816681c0)
Location: drivers/char/virtio_console.c:370
Inline: True
Direct callers:
  - drivers/char/virtio_console.c:remove_vqs
  - drivers/char/virtio_console.c:flush_bufs
  - drivers/char/virtio_console.c:control_work_handler
  - drivers/char/virtio_console.c:fill_queue
  - drivers/char/virtio_console.c:port_fops_splice_write
  - drivers/char/virtio_console.c:discard_port_data
  - drivers/char/virtio_console.c:reclaim_dma_bufs
```
**Symbols:**

```
ffffffff816681c0-ffffffff816682ea: free_buf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void free_buf(struct port_buffer *buf, bool can_sleep);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff8169dc40)
Location: drivers/char/virtio_console.c:357
Inline: True
Direct callers:
  - drivers/char/virtio_console.c:remove_vqs
  - drivers/char/virtio_console.c:flush_bufs
  - drivers/char/virtio_console.c:control_work_handler
  - drivers/char/virtio_console.c:fill_queue
  - drivers/char/virtio_console.c:port_fops_splice_write
  - drivers/char/virtio_console.c:discard_port_data
  - drivers/char/virtio_console.c:reclaim_dma_bufs
```
**Symbols:**

```
ffffffff8169dc40-ffffffff8169dd66: free_buf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void free_buf(struct port_buffer *buf, bool can_sleep);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff816c09b0)
Location: drivers/char/virtio_console.c:357
Inline: True
Direct callers:
  - drivers/char/virtio_console.c:remove_vqs
  - drivers/char/virtio_console.c:flush_bufs
  - drivers/char/virtio_console.c:control_work_handler
  - drivers/char/virtio_console.c:fill_queue
  - drivers/char/virtio_console.c:port_fops_splice_write
  - drivers/char/virtio_console.c:discard_port_data
  - drivers/char/virtio_console.c:reclaim_dma_bufs
```
**Symbols:**

```
ffffffff816c09b0-ffffffff816c0ad6: free_buf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void free_buf(struct port_buffer *buf, bool can_sleep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff81774430)
Location: drivers/char/virtio_console.c:357
Inline: False
Direct callers:
  - drivers/char/virtio_console.c:remove_vqs
  - drivers/char/virtio_console.c:remove_vqs
  - drivers/char/virtio_console.c:in_intr
  - drivers/char/virtio_console.c:out_intr
  - drivers/char/virtio_console.c:control_work_handler
  - drivers/char/virtio_console.c:remove_port_data
  - drivers/char/virtio_console.c:fill_queue
  - drivers/char/virtio_console.c:port_fops_open
  - drivers/char/virtio_console.c:port_fops_release
  - drivers/char/virtio_console.c:port_fops_poll
  - drivers/char/virtio_console.c:port_fops_splice_write
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:__send_to_port
  - drivers/char/virtio_console.c:discard_port_data
  - drivers/char/virtio_console.c:reclaim_dma_bufs
```
**Symbols:**

```
ffffffff81774430-ffffffff81774559: free_buf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void free_buf(struct port_buffer *buf, bool can_sleep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff8178f190)
Location: drivers/char/virtio_console.c:357
Inline: False
Direct callers:
  - drivers/char/virtio_console.c:remove_vqs
  - drivers/char/virtio_console.c:remove_vqs
  - drivers/char/virtio_console.c:in_intr
  - drivers/char/virtio_console.c:out_intr
  - drivers/char/virtio_console.c:control_work_handler
  - drivers/char/virtio_console.c:remove_port_data
  - drivers/char/virtio_console.c:fill_queue
  - drivers/char/virtio_console.c:port_fops_open
  - drivers/char/virtio_console.c:port_fops_release
  - drivers/char/virtio_console.c:port_fops_poll
  - drivers/char/virtio_console.c:port_fops_splice_write
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:__send_to_port
  - drivers/char/virtio_console.c:discard_port_data
  - drivers/char/virtio_console.c:reclaim_dma_bufs
```
**Symbols:**

```
ffffffff8178f190-ffffffff8178f2b6: free_buf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void free_buf(struct port_buffer *buf, bool can_sleep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff81771f80)
Location: drivers/char/virtio_console.c:357
Inline: False
Direct callers:
  - drivers/char/virtio_console.c:remove_vqs
  - drivers/char/virtio_console.c:remove_vqs
  - drivers/char/virtio_console.c:in_intr
  - drivers/char/virtio_console.c:out_intr
  - drivers/char/virtio_console.c:control_work_handler
  - drivers/char/virtio_console.c:remove_port_data
  - drivers/char/virtio_console.c:fill_queue
  - drivers/char/virtio_console.c:port_fops_open
  - drivers/char/virtio_console.c:port_fops_release
  - drivers/char/virtio_console.c:port_fops_poll
  - drivers/char/virtio_console.c:port_fops_splice_write
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:__send_to_port
  - drivers/char/virtio_console.c:discard_port_data
  - drivers/char/virtio_console.c:reclaim_dma_bufs
```
**Symbols:**

```
ffffffff81771f80-ffffffff817720a3: free_buf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void free_buf(struct port_buffer *buf, bool can_sleep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff817f7d20)
Location: drivers/char/virtio_console.c:357
Inline: False
Direct callers:
  - drivers/char/virtio_console.c:remove_vqs
  - drivers/char/virtio_console.c:remove_vqs
  - drivers/char/virtio_console.c:in_intr
  - drivers/char/virtio_console.c:out_intr
  - drivers/char/virtio_console.c:control_work_handler
  - drivers/char/virtio_console.c:remove_port_data
  - drivers/char/virtio_console.c:fill_queue
  - drivers/char/virtio_console.c:port_fops_open
  - drivers/char/virtio_console.c:port_fops_release
  - drivers/char/virtio_console.c:port_fops_splice_write
  - drivers/char/virtio_console.c:__send_to_port
  - drivers/char/virtio_console.c:discard_port_data
  - drivers/char/virtio_console.c:reclaim_dma_bufs
```
**Symbols:**

```
ffffffff817f7d20-ffffffff817f7e40: free_buf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void free_buf(struct port_buffer *buf, bool can_sleep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff81936a90)
Location: drivers/char/virtio_console.c:358
Inline: False
Direct callers:
  - drivers/char/virtio_console.c:virtcons_freeze
  - drivers/char/virtio_console.c:remove_vqs
  - drivers/char/virtio_console.c:remove_vqs
  - drivers/char/virtio_console.c:in_intr
  - drivers/char/virtio_console.c:control_work_handler
  - drivers/char/virtio_console.c:unplug_port
  - drivers/char/virtio_console.c:fill_queue
  - drivers/char/virtio_console.c:port_fops_open
  - drivers/char/virtio_console.c:port_fops_release
  - drivers/char/virtio_console.c:port_fops_splice_write
  - drivers/char/virtio_console.c:port_fops_write
  - drivers/char/virtio_console.c:__send_to_port
  - drivers/char/virtio_console.c:reclaim_dma_bufs
```
**Symbols:**

```
ffffffff81936a90-ffffffff81936c1c: free_buf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void free_buf(struct port_buffer *buf, bool can_sleep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff81a96930)
Location: drivers/char/virtio_console.c:350
Inline: False
Direct callers:
  - drivers/char/virtio_console.c:virtcons_freeze
  - drivers/char/virtio_console.c:remove_vqs
  - drivers/char/virtio_console.c:remove_vqs
  - drivers/char/virtio_console.c:in_intr
  - drivers/char/virtio_console.c:control_work_handler
  - drivers/char/virtio_console.c:unplug_port
  - drivers/char/virtio_console.c:fill_queue
  - drivers/char/virtio_console.c:port_fops_open
  - drivers/char/virtio_console.c:port_fops_release
  - drivers/char/virtio_console.c:port_fops_splice_write
  - drivers/char/virtio_console.c:port_fops_write
  - drivers/char/virtio_console.c:__send_to_port
  - drivers/char/virtio_console.c:reclaim_dma_bufs
```
**Symbols:**

```
ffffffff81a96930-ffffffff81a96abc: free_buf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void free_buf(struct port_buffer *buf, bool can_sleep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff81ae2140)
Location: drivers/char/virtio_console.c:351
Inline: False
Direct callers:
  - drivers/char/virtio_console.c:virtcons_freeze
  - drivers/char/virtio_console.c:remove_vqs
  - drivers/char/virtio_console.c:remove_vqs
  - drivers/char/virtio_console.c:in_intr
  - drivers/char/virtio_console.c:control_work_handler
  - drivers/char/virtio_console.c:unplug_port
  - drivers/char/virtio_console.c:fill_queue
  - drivers/char/virtio_console.c:port_fops_open
  - drivers/char/virtio_console.c:port_fops_release
  - drivers/char/virtio_console.c:port_fops_splice_write
  - drivers/char/virtio_console.c:port_fops_write
  - drivers/char/virtio_console.c:__send_to_port
  - drivers/char/virtio_console.c:reclaim_dma_bufs
```
**Symbols:**

```
ffffffff81ae2140-ffffffff81ae22c6: free_buf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void free_buf(struct port_buffer *buf, bool can_sleep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff81b35530)
Location: drivers/char/virtio_console.c:348
Inline: False
Direct callers:
  - drivers/char/virtio_console.c:virtcons_freeze
  - drivers/char/virtio_console.c:remove_vqs
  - drivers/char/virtio_console.c:remove_vqs
  - drivers/char/virtio_console.c:in_intr
  - drivers/char/virtio_console.c:control_work_handler
  - drivers/char/virtio_console.c:unplug_port
  - drivers/char/virtio_console.c:fill_queue
  - drivers/char/virtio_console.c:port_fops_open
  - drivers/char/virtio_console.c:port_fops_release
  - drivers/char/virtio_console.c:port_fops_splice_write
  - drivers/char/virtio_console.c:port_fops_write
  - drivers/char/virtio_console.c:__send_to_port
  - drivers/char/virtio_console.c:reclaim_dma_bufs
```
**Symbols:**

```
ffffffff81b35530-ffffffff81b356b3: free_buf (STB_LOCAL)
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
void free_buf(struct port_buffer *buf, bool can_sleep);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (ffff8000108b37d8)
Location: drivers/char/virtio_console.c:357
Inline: True
Direct callers:
  - drivers/char/virtio_console.c:remove_vqs
  - drivers/char/virtio_console.c:flush_bufs
  - drivers/char/virtio_console.c:control_work_handler
  - drivers/char/virtio_console.c:fill_queue
  - drivers/char/virtio_console.c:port_fops_splice_write
  - drivers/char/virtio_console.c:discard_port_data
  - drivers/char/virtio_console.c:reclaim_dma_bufs
```
**Symbols:**

```
ffff8000108b37d8-ffff8000108b3980: free_buf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void free_buf(struct port_buffer *buf, bool can_sleep);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (c09ad62c)
Location: drivers/char/virtio_console.c:357
Inline: True
Direct callers:
  - drivers/char/virtio_console.c:remove_vqs
  - drivers/char/virtio_console.c:flush_bufs
  - drivers/char/virtio_console.c:control_work_handler
  - drivers/char/virtio_console.c:fill_queue
  - drivers/char/virtio_console.c:port_fops_splice_write
  - drivers/char/virtio_console.c:discard_port_data
  - drivers/char/virtio_console.c:reclaim_dma_bufs
```
**Symbols:**

```
c09ad62c-c09ad760: free_buf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void free_buf(struct port_buffer *buf, bool can_sleep);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (c00000000094bc20)
Location: drivers/char/virtio_console.c:357
Inline: True
Direct callers:
  - drivers/char/virtio_console.c:remove_vqs
  - drivers/char/virtio_console.c:flush_bufs
  - drivers/char/virtio_console.c:control_work_handler
  - drivers/char/virtio_console.c:fill_queue
  - drivers/char/virtio_console.c:port_fops_splice_write
  - drivers/char/virtio_console.c:discard_port_data
  - drivers/char/virtio_console.c:reclaim_dma_bufs
```
**Symbols:**

```
c00000000094bc20-c00000000094be00: free_buf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/virtio_console.c (ffffffe000564f3e)
Location: drivers/char/virtio_console.c:357
Inline: True
Direct callers:
  - drivers/char/virtio_console.c:virtcons_remove
  - drivers/char/virtio_console.c:control_work_handler
  - drivers/char/virtio_console.c:fill_queue
  - drivers/char/virtio_console.c:port_fops_splice_write
  - drivers/char/virtio_console.c:discard_port_data
  - drivers/char/virtio_console.c:reclaim_dma_bufs
```
**Symbols:**

```
ffffffe000564f3e-ffffffe000564fe2: free_buf.isra.0 (STB_LOCAL)
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
void free_buf(struct port_buffer *buf, bool can_sleep);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff81686400)
Location: drivers/char/virtio_console.c:357
Inline: True
Direct callers:
  - drivers/char/virtio_console.c:remove_vqs
  - drivers/char/virtio_console.c:flush_bufs
  - drivers/char/virtio_console.c:control_work_handler
  - drivers/char/virtio_console.c:fill_queue
  - drivers/char/virtio_console.c:port_fops_splice_write
  - drivers/char/virtio_console.c:discard_port_data
  - drivers/char/virtio_console.c:reclaim_dma_bufs
```
**Symbols:**

```
ffffffff81686400-ffffffff81686526: free_buf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff81664360)
Location: drivers/char/virtio_console.c:357
Inline: True
Direct callers:
  - drivers/char/virtio_console.c:remove_vqs
  - drivers/char/virtio_console.c:flush_bufs
  - drivers/char/virtio_console.c:control_work_handler
  - drivers/char/virtio_console.c:fill_queue
  - drivers/char/virtio_console.c:port_fops_splice_write
  - drivers/char/virtio_console.c:discard_port_data
  - drivers/char/virtio_console.c:reclaim_dma_bufs
```
**Symbols:**

```
ffffffff81664360-ffffffff81664414: free_buf.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff816b4ab0)
Location: drivers/char/virtio_console.c:357
Inline: True
Direct callers:
  - drivers/char/virtio_console.c:remove_vqs
  - drivers/char/virtio_console.c:flush_bufs
  - drivers/char/virtio_console.c:control_work_handler
  - drivers/char/virtio_console.c:fill_queue
  - drivers/char/virtio_console.c:port_fops_splice_write
  - drivers/char/virtio_console.c:discard_port_data
  - drivers/char/virtio_console.c:reclaim_dma_bufs
```
**Symbols:**

```
ffffffff816b4ab0-ffffffff816b4b64: free_buf.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void free_buf(struct port_buffer *buf, bool can_sleep);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff816ced50)
Location: drivers/char/virtio_console.c:357
Inline: True
Direct callers:
  - drivers/char/virtio_console.c:remove_vqs
  - drivers/char/virtio_console.c:flush_bufs
  - drivers/char/virtio_console.c:control_work_handler
  - drivers/char/virtio_console.c:fill_queue
  - drivers/char/virtio_console.c:port_fops_splice_write
  - drivers/char/virtio_console.c:discard_port_data
  - drivers/char/virtio_console.c:reclaim_dma_bufs
```
**Symbols:**

```
ffffffff816ced50-ffffffff816cee76: free_buf (STB_LOCAL)
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
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
