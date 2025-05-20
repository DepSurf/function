# Function: <code>__bpf_trace_ext4_read_block_bitmap_load</code>

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
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __bpf_trace_ext4_read_block_bitmap_load(void *__data, struct super_block *sb, long unsigned int group, bool prefetch);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff8143cc70)
Location: include/trace/events/ext4.h:1338
Inline: False
```
**Symbols:**

```
ffffffff8143cc70-ffffffff8143cc7e: __bpf_trace_ext4_read_block_bitmap_load (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __bpf_trace_ext4_read_block_bitmap_load(void *__data, struct super_block *sb, long unsigned int group, bool prefetch);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81442b30)
Location: include/trace/events/ext4.h:1338
Inline: False
```
**Symbols:**

```
ffffffff81442b30-ffffffff81442b3e: __bpf_trace_ext4_read_block_bitmap_load (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __bpf_trace_ext4_read_block_bitmap_load(void *__data, struct super_block *sb, long unsigned int group, bool prefetch);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff814967d0)
Location: include/trace/events/ext4.h:1338
Inline: False
```
**Symbols:**

```
ffffffff814967d0-ffffffff814967de: __bpf_trace_ext4_read_block_bitmap_load (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __bpf_trace_ext4_read_block_bitmap_load(void *__data, struct super_block *sb, long unsigned int group, bool prefetch);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81521290)
Location: include/trace/events/ext4.h:1344
Inline: False
```
**Symbols:**

```
ffffffff81521290-ffffffff815212aa: __bpf_trace_ext4_read_block_bitmap_load (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __bpf_trace_ext4_read_block_bitmap_load(void *__data, struct super_block *sb, long unsigned int group, bool prefetch);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff815bdcc0)
Location: include/trace/events/ext4.h:1346
Inline: False
```
**Symbols:**

```
ffffffff815bdcc0-ffffffff815bdcda: __bpf_trace_ext4_read_block_bitmap_load (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __bpf_trace_ext4_read_block_bitmap_load(void *__data, struct super_block *sb, long unsigned int group, bool prefetch);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff815f4a40)
Location: include/trace/events/ext4.h:1353
Inline: False
```
**Symbols:**

```
ffffffff815f4a40-ffffffff815f4a5a: __bpf_trace_ext4_read_block_bitmap_load (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __bpf_trace_ext4_read_block_bitmap_load(void *__data, struct super_block *sb, long unsigned int group, bool prefetch);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff8162d3f0)
Location: include/trace/events/ext4.h:1350
Inline: False
```
**Symbols:**

```
ffffffff8162d3f0-ffffffff8162d40a: __bpf_trace_ext4_read_block_bitmap_load (STB_LOCAL)
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
<b>Regular</b>
<ul>
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
