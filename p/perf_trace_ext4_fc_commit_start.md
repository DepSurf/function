# Function: <code>perf_trace_ext4_fc_commit_start</code>

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
void perf_trace_ext4_fc_commit_start(void *__data, struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81438fb0)
Location: include/trace/events/ext4.h:2853
Inline: False
```
**Symbols:**

```
ffffffff81438fb0-ffffffff81439083: perf_trace_ext4_fc_commit_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void perf_trace_ext4_fc_commit_start(void *__data, struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff8143f160)
Location: include/trace/events/ext4.h:2677
Inline: False
```
**Symbols:**

```
ffffffff8143f160-ffffffff8143f233: perf_trace_ext4_fc_commit_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void perf_trace_ext4_fc_commit_start(void *__data, struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81492df0)
Location: include/trace/events/ext4.h:2677
Inline: False
```
**Symbols:**

```
ffffffff81492df0-ffffffff81492ec3: perf_trace_ext4_fc_commit_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void perf_trace_ext4_fc_commit_start(void *__data, struct super_block *sb, tid_t commit_tid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81517d40)
Location: include/trace/events/ext4.h:2683
Inline: False
```
**Symbols:**

```
ffffffff81517d40-ffffffff81517e41: perf_trace_ext4_fc_commit_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void perf_trace_ext4_fc_commit_start(void *__data, struct super_block *sb, tid_t commit_tid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff815b38c0)
Location: include/trace/events/ext4.h:2720
Inline: False
```
**Symbols:**

```
ffffffff815b38c0-ffffffff815b39be: perf_trace_ext4_fc_commit_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void perf_trace_ext4_fc_commit_start(void *__data, struct super_block *sb, tid_t commit_tid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff815ea620)
Location: include/trace/events/ext4.h:2727
Inline: False
```
**Symbols:**

```
ffffffff815ea620-ffffffff815ea71e: perf_trace_ext4_fc_commit_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void perf_trace_ext4_fc_commit_start(void *__data, struct super_block *sb, tid_t commit_tid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81623010)
Location: include/trace/events/ext4.h:2724
Inline: False
```
**Symbols:**

```
ffffffff81623010-ffffffff8162310e: perf_trace_ext4_fc_commit_start (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>tid_t commit_tid</code>
</li>
</ul>
</details>
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
