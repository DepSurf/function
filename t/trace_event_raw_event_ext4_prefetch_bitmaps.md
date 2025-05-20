# Function: <code>trace_event_raw_event_ext4_prefetch_bitmaps</code>

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
void trace_event_raw_event_ext4_prefetch_bitmaps(void *__data, struct super_block *sb, ext4_group_t group, ext4_group_t next, unsigned int prefetch_ios);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81440180)
Location: include/trace/events/ext4.h:2761
Inline: False
```
**Symbols:**

```
ffffffff81440180-ffffffff81440241: trace_event_raw_event_ext4_prefetch_bitmaps (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void trace_event_raw_event_ext4_prefetch_bitmaps(void *__data, struct super_block *sb, ext4_group_t group, ext4_group_t next, unsigned int prefetch_ios);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81445a40)
Location: include/trace/events/ext4.h:2585
Inline: False
```
**Symbols:**

```
ffffffff81445a40-ffffffff81445b0e: trace_event_raw_event_ext4_prefetch_bitmaps (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void trace_event_raw_event_ext4_prefetch_bitmaps(void *__data, struct super_block *sb, ext4_group_t group, ext4_group_t next, unsigned int prefetch_ios);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff814998d0)
Location: include/trace/events/ext4.h:2585
Inline: False
```
**Symbols:**

```
ffffffff814998d0-ffffffff8149999e: trace_event_raw_event_ext4_prefetch_bitmaps (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void trace_event_raw_event_ext4_prefetch_bitmaps(void *__data, struct super_block *sb, ext4_group_t group, ext4_group_t next, unsigned int prefetch_ios);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff8151cd20)
Location: include/trace/events/ext4.h:2591
Inline: False
```
**Symbols:**

```
ffffffff8151cd20-ffffffff8151cde2: trace_event_raw_event_ext4_prefetch_bitmaps (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void trace_event_raw_event_ext4_prefetch_bitmaps(void *__data, struct super_block *sb, ext4_group_t group, ext4_group_t next, unsigned int prefetch_ios);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff815b8f10)
Location: include/trace/events/ext4.h:2628
Inline: False
```
**Symbols:**

```
ffffffff815b8f10-ffffffff815b8fd2: trace_event_raw_event_ext4_prefetch_bitmaps (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void trace_event_raw_event_ext4_prefetch_bitmaps(void *__data, struct super_block *sb, ext4_group_t group, ext4_group_t next, unsigned int prefetch_ios);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff815efc60)
Location: include/trace/events/ext4.h:2635
Inline: False
```
**Symbols:**

```
ffffffff815efc60-ffffffff815efd22: trace_event_raw_event_ext4_prefetch_bitmaps (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void trace_event_raw_event_ext4_prefetch_bitmaps(void *__data, struct super_block *sb, ext4_group_t group, ext4_group_t next, unsigned int prefetch_ios);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81628640)
Location: include/trace/events/ext4.h:2632
Inline: False
```
**Symbols:**

```
ffffffff81628640-ffffffff81628702: trace_event_raw_event_ext4_prefetch_bitmaps (STB_LOCAL)
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
