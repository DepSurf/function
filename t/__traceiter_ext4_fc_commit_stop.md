# Function: <code>__traceiter_ext4_fc_commit_stop</code>

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
int __traceiter_ext4_fc_commit_stop(void *__data, struct super_block *sb, int nblks, int reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff814334e0)
Location: include/trace/events/ext4.h:2870
Inline: False
```
**Symbols:**

```
ffffffff814334e0-ffffffff81433531: __traceiter_ext4_fc_commit_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __traceiter_ext4_fc_commit_stop(void *__data, struct super_block *sb, int nblks, int reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81439d00)
Location: include/trace/events/ext4.h:2694
Inline: False
```
**Symbols:**

```
ffffffff81439d00-ffffffff81439d4f: __traceiter_ext4_fc_commit_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __traceiter_ext4_fc_commit_stop(void *__data, struct super_block *sb, int nblks, int reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff8148d980)
Location: include/trace/events/ext4.h:2694
Inline: False
```
**Symbols:**

```
ffffffff8148d980-ffffffff8148d9cf: __traceiter_ext4_fc_commit_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __traceiter_ext4_fc_commit_stop(void *__data, struct super_block *sb, int nblks, int reason, tid_t commit_tid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81511c10)
Location: include/trace/events/ext4.h:2702
Inline: False
```
**Symbols:**

```
ffffffff81511c10-ffffffff81511c78: __traceiter_ext4_fc_commit_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __traceiter_ext4_fc_commit_stop(void *__data, struct super_block *sb, int nblks, int reason, tid_t commit_tid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff815ad1f0)
Location: include/trace/events/ext4.h:2739
Inline: False
```
**Symbols:**

```
ffffffff815ad1f0-ffffffff815ad258: __traceiter_ext4_fc_commit_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __traceiter_ext4_fc_commit_stop(void *__data, struct super_block *sb, int nblks, int reason, tid_t commit_tid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff815e3ef0)
Location: include/trace/events/ext4.h:2746
Inline: False
```
**Symbols:**

```
ffffffff815e3ef0-ffffffff815e3f58: __traceiter_ext4_fc_commit_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __traceiter_ext4_fc_commit_stop(void *__data, struct super_block *sb, int nblks, int reason, tid_t commit_tid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff8161c8f0)
Location: include/trace/events/ext4.h:2743
Inline: False
```
**Symbols:**

```
ffffffff8161c8f0-ffffffff8161c958: __traceiter_ext4_fc_commit_stop (STB_GLOBAL)
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
