# Function: <code>raw_atomic_long_cmpxchg</code>

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
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/ucount.c (ffffffff8113784f)
Location: include/linux/atomic/atomic-long.h:1361
Inline: True
Inline callers:
  - kernel/ucount.c:inc_ucount
```
```
In kernel/printk/printk_ringbuffer.c (ffffffff811a4980)
Location: include/linux/atomic/atomic-long.h:1361
Inline: True
Inline callers:
  - kernel/printk/printk_ringbuffer.c:desc_reserve
```
```
In kernel/events/core.c (ffffffff813750b5)
Location: include/linux/atomic/atomic-long.h:1361
Inline: True
```
```
In fs/nsfs.c (ffffffff81502cee)
Location: include/linux/atomic/atomic-long.h:1361
Inline: True
Inline callers:
  - fs/nsfs.c:__ns_get_path
```
```
In net/xdp/xdp_umem.c (ffffffff8206c654)
Location: include/linux/atomic/atomic-long.h:1361
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_reg
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
In kernel/ucount.c (ffffffff81142a5f)
Location: include/linux/atomic/atomic-long.h:1361
Inline: True
Inline callers:
  - kernel/ucount.c:inc_ucount
```
```
In kernel/printk/printk_ringbuffer.c (ffffffff811b4470)
Location: include/linux/atomic/atomic-long.h:1361
Inline: True
Inline callers:
  - kernel/printk/printk_ringbuffer.c:desc_reserve
```
```
In kernel/events/core.c (ffffffff8139e3e5)
Location: include/linux/atomic/atomic-long.h:1361
Inline: True
```
```
In fs/nsfs.c (ffffffff81537918)
Location: include/linux/atomic/atomic-long.h:1361
Inline: True
Inline callers:
  - fs/nsfs.c:__ns_get_path
```
```
In net/xdp/xdp_umem.c (ffffffff82140452)
Location: include/linux/atomic/atomic-long.h:1361
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_reg
```
</details>
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
