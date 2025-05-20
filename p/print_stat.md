# Function: <code>print_stat</code>

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
<details>
<summary>In <code>4.10</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-sysfs.c (ffffffff8141a12b)
Location: block/blk-sysfs.c:500
Inline: True
Inline callers:
  - block/blk-sysfs.c:queue_stats_show
  - block/blk-sysfs.c:queue_stats_show
```
```
In block/blk-mq-sysfs.c (ffffffff81426fd7)
Location: block/blk-mq-sysfs.c:280
Inline: True
Inline callers:
  - block/blk-mq-sysfs.c:blk_mq_hw_sysfs_stat_show
  - block/blk-mq-sysfs.c:blk_mq_hw_sysfs_stat_show
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void print_stat(struct seq_file *m, struct blk_rq_stat *stat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff814598d0)
Location: block/blk-mq-debugfs.c:130
Inline: False
Direct callers:
  - block/blk-mq-debugfs.c:queue_poll_stat_show
  - block/blk-mq-debugfs.c:queue_poll_stat_show
```
**Symbols:**

```
ffffffff814598d0-ffffffff81459907: print_stat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void print_stat(struct seq_file *m, struct blk_rq_stat *stat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff81485650)
Location: block/blk-mq-debugfs.c:128
Inline: False
Direct callers:
  - block/blk-mq-debugfs.c:queue_poll_stat_show
  - block/blk-mq-debugfs.c:queue_poll_stat_show
```
**Symbols:**

```
ffffffff81485650-ffffffff81485687: print_stat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void print_stat(struct seq_file *m, struct blk_rq_stat *stat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff814ba3b0)
Location: block/blk-mq-debugfs.c:27
Inline: False
Direct callers:
  - block/blk-mq-debugfs.c:queue_poll_stat_show
  - block/blk-mq-debugfs.c:queue_poll_stat_show
```
**Symbols:**

```
ffffffff814ba3b0-ffffffff814ba3e7: print_stat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void print_stat(struct seq_file *m, struct blk_rq_stat *stat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff814ce510)
Location: block/blk-mq-debugfs.c:28
Inline: False
Direct callers:
  - block/blk-mq-debugfs.c:queue_poll_stat_show
  - block/blk-mq-debugfs.c:queue_poll_stat_show
```
**Symbols:**

```
ffffffff814ce510-ffffffff814ce547: print_stat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void print_stat(struct seq_file *m, struct blk_rq_stat *stat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff814fcdd0)
Location: block/blk-mq-debugfs.c:17
Inline: False
Direct callers:
  - block/blk-mq-debugfs.c:queue_poll_stat_show
  - block/blk-mq-debugfs.c:queue_poll_stat_show
```
**Symbols:**

```
ffffffff814fcdd0-ffffffff814fce07: print_stat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void print_stat(struct seq_file *m, struct blk_rq_stat *stat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff8151ad20)
Location: block/blk-mq-debugfs.c:17
Inline: False
Direct callers:
  - block/blk-mq-debugfs.c:queue_poll_stat_show
  - block/blk-mq-debugfs.c:queue_poll_stat_show
```
**Symbols:**

```
ffffffff8151ad20-ffffffff8151ad57: print_stat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff8157be2f)
Location: block/blk-mq-debugfs.c:17
Inline: True
Inline callers:
  - block/blk-mq-debugfs.c:queue_poll_stat_show
  - block/blk-mq-debugfs.c:queue_poll_stat_show
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff81598eef)
Location: block/blk-mq-debugfs.c:17
Inline: True
Inline callers:
  - block/blk-mq-debugfs.c:queue_poll_stat_show
  - block/blk-mq-debugfs.c:queue_poll_stat_show
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff8159fcef)
Location: block/blk-mq-debugfs.c:17
Inline: True
Inline callers:
  - block/blk-mq-debugfs.c:queue_poll_stat_show
  - block/blk-mq-debugfs.c:queue_poll_stat_show
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff816084e7)
Location: block/blk-mq-debugfs.c:17
Inline: True
Inline callers:
  - block/blk-mq-debugfs.c:queue_poll_stat_show
  - block/blk-mq-debugfs.c:queue_poll_stat_show
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff816bbfa8)
Location: block/blk-mq-debugfs.c:18
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff8177c928)
Location: block/blk-mq-debugfs.c:18
Inline: True
```
</details>
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
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void print_stat(struct seq_file *m, struct blk_rq_stat *stat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffff800010622de8)
Location: block/blk-mq-debugfs.c:17
Inline: False
Direct callers:
  - block/blk-mq-debugfs.c:queue_poll_stat_show
  - block/blk-mq-debugfs.c:queue_poll_stat_show
```
**Symbols:**

```
ffff800010622de8-ffff800010622e4c: print_stat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void print_stat(struct seq_file *m, struct blk_rq_stat *stat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (c07ca8c8)
Location: block/blk-mq-debugfs.c:17
Inline: False
Direct callers:
  - block/blk-mq-debugfs.c:queue_poll_stat_show
  - block/blk-mq-debugfs.c:queue_poll_stat_show
```
**Symbols:**

```
c07ca8c8-c07ca930: print_stat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void print_stat(struct seq_file *m, struct blk_rq_stat *stat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (c0000000007c2f80)
Location: block/blk-mq-debugfs.c:17
Inline: False
Direct callers:
  - block/blk-mq-debugfs.c:queue_poll_stat_show
  - block/blk-mq-debugfs.c:queue_poll_stat_show
```
**Symbols:**

```
c0000000007c2f80-c0000000007c3000: print_stat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void print_stat(struct seq_file *m, struct blk_rq_stat *stat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffe000454c58)
Location: block/blk-mq-debugfs.c:17
Inline: False
Direct callers:
  - block/blk-mq-debugfs.c:queue_poll_stat_show
  - block/blk-mq-debugfs.c:queue_poll_stat_show
```
**Symbols:**

```
ffffffe000454c58-ffffffe000454cb8: print_stat (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void print_stat(struct seq_file *m, struct blk_rq_stat *stat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff81513300)
Location: block/blk-mq-debugfs.c:17
Inline: False
Direct callers:
  - block/blk-mq-debugfs.c:queue_poll_stat_show
  - block/blk-mq-debugfs.c:queue_poll_stat_show
```
**Symbols:**

```
ffffffff81513300-ffffffff81513337: print_stat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void print_stat(struct seq_file *m, struct blk_rq_stat *stat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff81503610)
Location: block/blk-mq-debugfs.c:17
Inline: False
Direct callers:
  - block/blk-mq-debugfs.c:queue_poll_stat_show
  - block/blk-mq-debugfs.c:queue_poll_stat_show
```
**Symbols:**

```
ffffffff81503610-ffffffff81503647: print_stat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void print_stat(struct seq_file *m, struct blk_rq_stat *stat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff8150f390)
Location: block/blk-mq-debugfs.c:17
Inline: False
Direct callers:
  - block/blk-mq-debugfs.c:queue_poll_stat_show
  - block/blk-mq-debugfs.c:queue_poll_stat_show
```
**Symbols:**

```
ffffffff8150f390-ffffffff8150f3c7: print_stat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void print_stat(struct seq_file *m, struct blk_rq_stat *stat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff81528bb0)
Location: block/blk-mq-debugfs.c:17
Inline: False
Direct callers:
  - block/blk-mq-debugfs.c:queue_poll_stat_show
  - block/blk-mq-debugfs.c:queue_poll_stat_show
```
**Symbols:**

```
ffffffff81528bb0-ffffffff81528be7: print_stat (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
