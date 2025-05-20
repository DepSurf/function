# Function: <code>perf_trace_ext4_lazy_itable_init</code>

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
void perf_trace_ext4_lazy_itable_init(void *__data, struct super_block *sb, ext4_group_t group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81438ce0)
Location: include/trace/events/ext4.h:2786
Inline: False
```
**Symbols:**

```
ffffffff81438ce0-ffffffff81438dbe: perf_trace_ext4_lazy_itable_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void perf_trace_ext4_lazy_itable_init(void *__data, struct super_block *sb, ext4_group_t group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff8143ee90)
Location: include/trace/events/ext4.h:2610
Inline: False
```
**Symbols:**

```
ffffffff8143ee90-ffffffff8143ef6e: perf_trace_ext4_lazy_itable_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void perf_trace_ext4_lazy_itable_init(void *__data, struct super_block *sb, ext4_group_t group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81492b20)
Location: include/trace/events/ext4.h:2610
Inline: False
```
**Symbols:**

```
ffffffff81492b20-ffffffff81492bfe: perf_trace_ext4_lazy_itable_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void perf_trace_ext4_lazy_itable_init(void *__data, struct super_block *sb, ext4_group_t group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff815179f0)
Location: include/trace/events/ext4.h:2616
Inline: False
```
**Symbols:**

```
ffffffff815179f0-ffffffff81517af1: perf_trace_ext4_lazy_itable_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void perf_trace_ext4_lazy_itable_init(void *__data, struct super_block *sb, ext4_group_t group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff815b3560)
Location: include/trace/events/ext4.h:2653
Inline: False
```
**Symbols:**

```
ffffffff815b3560-ffffffff815b365e: perf_trace_ext4_lazy_itable_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void perf_trace_ext4_lazy_itable_init(void *__data, struct super_block *sb, ext4_group_t group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff815ea2c0)
Location: include/trace/events/ext4.h:2660
Inline: False
```
**Symbols:**

```
ffffffff815ea2c0-ffffffff815ea3be: perf_trace_ext4_lazy_itable_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void perf_trace_ext4_lazy_itable_init(void *__data, struct super_block *sb, ext4_group_t group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81622cb0)
Location: include/trace/events/ext4.h:2657
Inline: False
```
**Symbols:**

```
ffffffff81622cb0-ffffffff81622dae: perf_trace_ext4_lazy_itable_init (STB_LOCAL)
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
