# Function: <code>perf_trace_ext4_read_block_bitmap_load</code>

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
void perf_trace_ext4_read_block_bitmap_load(void *__data, struct super_block *sb, long unsigned int group, bool prefetch);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81435c70)
Location: include/trace/events/ext4.h:1338
Inline: False
```
**Symbols:**

```
ffffffff81435c70-ffffffff81435d59: perf_trace_ext4_read_block_bitmap_load (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void perf_trace_ext4_read_block_bitmap_load(void *__data, struct super_block *sb, long unsigned int group, bool prefetch);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff8143c440)
Location: include/trace/events/ext4.h:1338
Inline: False
```
**Symbols:**

```
ffffffff8143c440-ffffffff8143c529: perf_trace_ext4_read_block_bitmap_load (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void perf_trace_ext4_read_block_bitmap_load(void *__data, struct super_block *sb, long unsigned int group, bool prefetch);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff814900c0)
Location: include/trace/events/ext4.h:1338
Inline: False
```
**Symbols:**

```
ffffffff814900c0-ffffffff814901a9: perf_trace_ext4_read_block_bitmap_load (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void perf_trace_ext4_read_block_bitmap_load(void *__data, struct super_block *sb, long unsigned int group, bool prefetch);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff815149d0)
Location: include/trace/events/ext4.h:1344
Inline: False
```
**Symbols:**

```
ffffffff815149d0-ffffffff81514adc: perf_trace_ext4_read_block_bitmap_load (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void perf_trace_ext4_read_block_bitmap_load(void *__data, struct super_block *sb, long unsigned int group, bool prefetch);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff815b01d0)
Location: include/trace/events/ext4.h:1346
Inline: False
```
**Symbols:**

```
ffffffff815b01d0-ffffffff815b02d9: perf_trace_ext4_read_block_bitmap_load (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void perf_trace_ext4_read_block_bitmap_load(void *__data, struct super_block *sb, long unsigned int group, bool prefetch);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff815e6f30)
Location: include/trace/events/ext4.h:1353
Inline: False
```
**Symbols:**

```
ffffffff815e6f30-ffffffff815e7039: perf_trace_ext4_read_block_bitmap_load (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void perf_trace_ext4_read_block_bitmap_load(void *__data, struct super_block *sb, long unsigned int group, bool prefetch);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff8161f920)
Location: include/trace/events/ext4.h:1350
Inline: False
```
**Symbols:**

```
ffffffff8161f920-ffffffff8161fa29: perf_trace_ext4_read_block_bitmap_load (STB_LOCAL)
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
