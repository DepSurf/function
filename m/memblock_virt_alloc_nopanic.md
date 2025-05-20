# Function: <code>memblock_virt_alloc_nopanic</code>

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
In kernel/printk/printk.c (ffffffff81f7edf2)
Location: include/linux/bootmem.h:170
Inline: True
Inline callers:
  - kernel/printk/printk.c:setup_log_buf
```
```
In mm/page_alloc.c (ffffffff81f87294)
Location: include/linux/bootmem.h:170
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_large_system_hash
```
```
In mm/percpu.c (ffffffff81f887cc)
Location: include/linux/bootmem.h:170
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_alloc_alloc_info
  - mm/percpu.c:pcpu_embed_first_chunk
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
In kernel/printk/printk.c (ffffffff81fa7d87)
Location: include/linux/bootmem.h:174
Inline: True
Inline callers:
  - kernel/printk/printk.c:setup_log_buf
```
```
In mm/page_alloc.c (ffffffff81fb129c)
Location: include/linux/bootmem.h:174
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_large_system_hash
```
```
In mm/percpu.c (ffffffff81fb2e14)
Location: include/linux/bootmem.h:174
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_embed_first_chunk
  - mm/percpu.c:pcpu_alloc_alloc_info
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
In kernel/printk/printk.c (ffffffff81fe3aed)
Location: include/linux/bootmem.h:179
Inline: True
Inline callers:
  - kernel/printk/printk.c:setup_log_buf
```
```
In mm/page_alloc.c (ffffffff81fedb6a)
Location: include/linux/bootmem.h:179
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_large_system_hash
```
```
In mm/percpu.c (ffffffff81fef7e0)
Location: include/linux/bootmem.h:179
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_embed_first_chunk
  - mm/percpu.c:pcpu_alloc_alloc_info
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
In kernel/printk/printk.c (ffffffff820c4572)
Location: include/linux/bootmem.h:179
Inline: True
Inline callers:
  - kernel/printk/printk.c:setup_log_buf
```
```
In mm/page_alloc.c (ffffffff820cf7c3)
Location: include/linux/bootmem.h:179
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_large_system_hash
```
```
In mm/percpu.c (ffffffff820d1bcb)
Location: include/linux/bootmem.h:179
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_embed_first_chunk
  - mm/percpu.c:pcpu_alloc_alloc_info
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
In kernel/printk/printk.c (ffffffff826cc813)
Location: include/linux/bootmem.h:191
Inline: True
Inline callers:
  - kernel/printk/printk.c:setup_log_buf
```
```
In mm/page_alloc.c (ffffffff826d81e8)
Location: include/linux/bootmem.h:191
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_large_system_hash
```
```
In mm/percpu.c (ffffffff826da6ec)
Location: include/linux/bootmem.h:191
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_embed_first_chunk
  - mm/percpu.c:pcpu_alloc_alloc_info
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
In kernel/printk/printk.c (ffffffff826f69ac)
Location: include/linux/bootmem.h:191
Inline: True
Inline callers:
  - kernel/printk/printk.c:setup_log_buf
```
```
In mm/page_alloc.c (ffffffff827026a0)
Location: include/linux/bootmem.h:191
Inline: True
Inline callers:
  - mm/page_alloc.c:alloc_large_system_hash
```
```
In mm/percpu.c (ffffffff82704c18)
Location: include/linux/bootmem.h:191
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_embed_first_chunk
  - mm/percpu.c:pcpu_alloc_alloc_info
```
</details>
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
