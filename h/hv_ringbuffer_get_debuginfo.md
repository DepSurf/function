# Function: <code>hv_ringbuffer_get_debuginfo</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int hv_ringbuffer_get_debuginfo(struct hv_ring_buffer_info *ring_info, struct hv_ring_buffer_debug_info *debug_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hv/ring_buffer.c (ffffffff81853730)
Location: drivers/hv/ring_buffer.c:156
Inline: False
Direct callers:
  - drivers/hv/vmbus_drv.c:in_write_bytes_avail_show
  - drivers/hv/vmbus_drv.c:in_read_bytes_avail_show
  - drivers/hv/vmbus_drv.c:in_write_index_show
  - drivers/hv/vmbus_drv.c:in_read_index_show
  - drivers/hv/vmbus_drv.c:in_intr_mask_show
  - drivers/hv/vmbus_drv.c:out_write_bytes_avail_show
  - drivers/hv/vmbus_drv.c:out_read_bytes_avail_show
  - drivers/hv/vmbus_drv.c:out_write_index_show
  - drivers/hv/vmbus_drv.c:out_read_index_show
  - drivers/hv/vmbus_drv.c:out_intr_mask_show
```
**Symbols:**

```
ffffffff81853730-ffffffff818537bb: hv_ringbuffer_get_debuginfo (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Flavor</b>
<ul>
</ul>
