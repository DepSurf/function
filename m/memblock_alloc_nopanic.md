# Function: <code>memblock_alloc_nopanic</code>

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
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff828ad8e4)
Location: include/linux/memblock.h:365
Inline: True
Inline callers:
  - kernel/printk/printk.c:setup_log_buf
```
```
In mm/page_alloc.c (ffffffff828b9dc9)
Location: include/linux/memblock.h:365
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_large_system_hash
```
```
In mm/percpu.c (ffffffff828bc35f)
Location: include/linux/memblock.h:365
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_embed_first_chunk
  - mm/percpu.c:pcpu_alloc_alloc_info
```
```
In drivers/usb/early/xhci-dbc.c (ffffffff828ea6a6)
Location: include/linux/memblock.h:365
Inline: True
Inline callers:
  - drivers/usb/early/xhci-dbc.c:xdbc_get_page
```
```
In drivers/firmware/memmap.c (ffffffff828f19f2)
Location: include/linux/memblock.h:365
Inline: True
Inline callers:
  - drivers/firmware/memmap.c:firmware_map_add_early
```
</details>
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
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
