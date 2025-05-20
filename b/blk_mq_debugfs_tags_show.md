# Function: <code>blk_mq_debugfs_tags_show</code>

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
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_debugfs_tags_show(struct seq_file *m, struct blk_mq_tags *tags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff81459f90)
Location: block/blk-mq-debugfs.c:439
Inline: True
Direct callers:
  - block/blk-mq-debugfs.c:hctx_sched_tags_show
  - block/blk-mq-debugfs.c:hctx_tags_show
```
**Symbols:**

```
ffffffff81459f90-ffffffff8145a016: blk_mq_debugfs_tags_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_debugfs_tags_show(struct seq_file *m, struct blk_mq_tags *tags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff81485d10)
Location: block/blk-mq-debugfs.c:436
Inline: True
Direct callers:
  - block/blk-mq-debugfs.c:hctx_sched_tags_show
  - block/blk-mq-debugfs.c:hctx_tags_show
```
**Symbols:**

```
ffffffff81485d10-ffffffff81485d96: blk_mq_debugfs_tags_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_debugfs_tags_show(struct seq_file *m, struct blk_mq_tags *tags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff814bac20)
Location: block/blk-mq-debugfs.c:466
Inline: True
Direct callers:
  - block/blk-mq-debugfs.c:hctx_sched_tags_show
  - block/blk-mq-debugfs.c:hctx_tags_show
```
**Symbols:**

```
ffffffff814bac20-ffffffff814bacab: blk_mq_debugfs_tags_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_debugfs_tags_show(struct seq_file *m, struct blk_mq_tags *tags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff814cedd0)
Location: block/blk-mq-debugfs.c:474
Inline: True
Direct callers:
  - block/blk-mq-debugfs.c:hctx_sched_tags_show
  - block/blk-mq-debugfs.c:hctx_tags_show
```
**Symbols:**

```
ffffffff814cedd0-ffffffff814cee5b: blk_mq_debugfs_tags_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_debugfs_tags_show(struct seq_file *m, struct blk_mq_tags *tags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff814fd680)
Location: block/blk-mq-debugfs.c:443
Inline: True
Direct callers:
  - block/blk-mq-debugfs.c:hctx_sched_tags_show
  - block/blk-mq-debugfs.c:hctx_tags_show
```
**Symbols:**

```
ffffffff814fd680-ffffffff814fd70b: blk_mq_debugfs_tags_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_debugfs_tags_show(struct seq_file *m, struct blk_mq_tags *tags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff8151b5d0)
Location: block/blk-mq-debugfs.c:443
Inline: True
Direct callers:
  - block/blk-mq-debugfs.c:hctx_sched_tags_show
  - block/blk-mq-debugfs.c:hctx_tags_show
```
**Symbols:**

```
ffffffff8151b5d0-ffffffff8151b65b: blk_mq_debugfs_tags_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void blk_mq_debugfs_tags_show(struct seq_file *m, struct blk_mq_tags *tags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff8157b7d0)
Location: block/blk-mq-debugfs.c:447
Inline: False
Direct callers:
  - block/blk-mq-debugfs.c:hctx_sched_tags_show
  - block/blk-mq-debugfs.c:hctx_tags_show
```
**Symbols:**

```
ffffffff8157b7d0-ffffffff8157b85b: blk_mq_debugfs_tags_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void blk_mq_debugfs_tags_show(struct seq_file *m, struct blk_mq_tags *tags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff81598890)
Location: block/blk-mq-debugfs.c:448
Inline: False
Direct callers:
  - block/blk-mq-debugfs.c:hctx_sched_tags_show
  - block/blk-mq-debugfs.c:hctx_tags_show
```
**Symbols:**

```
ffffffff81598890-ffffffff8159891b: blk_mq_debugfs_tags_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void blk_mq_debugfs_tags_show(struct seq_file *m, struct blk_mq_tags *tags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff8159f6a0)
Location: block/blk-mq-debugfs.c:446
Inline: False
Direct callers:
  - block/blk-mq-debugfs.c:hctx_sched_tags_show
  - block/blk-mq-debugfs.c:hctx_tags_show
```
**Symbols:**

```
ffffffff8159f6a0-ffffffff8159f72b: blk_mq_debugfs_tags_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void blk_mq_debugfs_tags_show(struct seq_file *m, struct blk_mq_tags *tags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff81607e50)
Location: block/blk-mq-debugfs.c:447
Inline: False
Direct callers:
  - block/blk-mq-debugfs.c:hctx_sched_tags_show
  - block/blk-mq-debugfs.c:hctx_tags_show
```
**Symbols:**

```
ffffffff81607e50-ffffffff81607edb: blk_mq_debugfs_tags_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void blk_mq_debugfs_tags_show(struct seq_file *m, struct blk_mq_tags *tags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff816bb840)
Location: block/blk-mq-debugfs.c:424
Inline: False
Direct callers:
  - block/blk-mq-debugfs.c:hctx_sched_tags_show
  - block/blk-mq-debugfs.c:hctx_tags_show
```
**Symbols:**

```
ffffffff816bb840-ffffffff816bb8e3: blk_mq_debugfs_tags_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void blk_mq_debugfs_tags_show(struct seq_file *m, struct blk_mq_tags *tags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff8177c0e0)
Location: block/blk-mq-debugfs.c:424
Inline: False
Direct callers:
  - block/blk-mq-debugfs.c:hctx_sched_tags_show
  - block/blk-mq-debugfs.c:hctx_tags_show
```
**Symbols:**

```
ffffffff8177c0e0-ffffffff8177c183: blk_mq_debugfs_tags_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void blk_mq_debugfs_tags_show(struct seq_file *m, struct blk_mq_tags *tags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff817bbbf0)
Location: block/blk-mq-debugfs.c:398
Inline: False
Direct callers:
  - block/blk-mq-debugfs.c:hctx_sched_tags_show
  - block/blk-mq-debugfs.c:hctx_tags_show
```
**Symbols:**

```
ffffffff817bbbf0-ffffffff817bbc93: blk_mq_debugfs_tags_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void blk_mq_debugfs_tags_show(struct seq_file *m, struct blk_mq_tags *tags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff818002b0)
Location: block/blk-mq-debugfs.c:397
Inline: False
Direct callers:
  - block/blk-mq-debugfs.c:hctx_sched_tags_show
  - block/blk-mq-debugfs.c:hctx_tags_show
```
**Symbols:**

```
ffffffff818002b0-ffffffff81800353: blk_mq_debugfs_tags_show (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_debugfs_tags_show(struct seq_file *m, struct blk_mq_tags *tags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffff800010623670)
Location: block/blk-mq-debugfs.c:443
Inline: True
Direct callers:
  - block/blk-mq-debugfs.c:hctx_sched_tags_show
  - block/blk-mq-debugfs.c:hctx_tags_show
```
**Symbols:**

```
ffff800010623670-ffff800010623720: blk_mq_debugfs_tags_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_debugfs_tags_show(struct seq_file *m, struct blk_mq_tags *tags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (c07cb2e4)
Location: block/blk-mq-debugfs.c:443
Inline: True
Direct callers:
  - block/blk-mq-debugfs.c:hctx_sched_tags_show
  - block/blk-mq-debugfs.c:hctx_tags_show
```
**Symbols:**

```
c07cb2e4-c07cb380: blk_mq_debugfs_tags_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_debugfs_tags_show(struct seq_file *m, struct blk_mq_tags *tags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (c0000000007c43e0)
Location: block/blk-mq-debugfs.c:443
Inline: True
Direct callers:
  - block/blk-mq-debugfs.c:hctx_sched_tags_show
  - block/blk-mq-debugfs.c:hctx_tags_show
```
**Symbols:**

```
c0000000007c43e0-c0000000007c44dc: blk_mq_debugfs_tags_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_debugfs_tags_show(struct seq_file *m, struct blk_mq_tags *tags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffe0004556f0)
Location: block/blk-mq-debugfs.c:443
Inline: True
Direct callers:
  - block/blk-mq-debugfs.c:hctx_sched_tags_show
  - block/blk-mq-debugfs.c:hctx_tags_show
```
**Symbols:**

```
ffffffe0004556f0-ffffffe0004557ac: blk_mq_debugfs_tags_show (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_debugfs_tags_show(struct seq_file *m, struct blk_mq_tags *tags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff81513bb0)
Location: block/blk-mq-debugfs.c:443
Inline: True
Direct callers:
  - block/blk-mq-debugfs.c:hctx_sched_tags_show
  - block/blk-mq-debugfs.c:hctx_tags_show
```
**Symbols:**

```
ffffffff81513bb0-ffffffff81513c3b: blk_mq_debugfs_tags_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_debugfs_tags_show(struct seq_file *m, struct blk_mq_tags *tags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff81503ec0)
Location: block/blk-mq-debugfs.c:443
Inline: True
Direct callers:
  - block/blk-mq-debugfs.c:hctx_sched_tags_show
  - block/blk-mq-debugfs.c:hctx_tags_show
```
**Symbols:**

```
ffffffff81503ec0-ffffffff81503f4b: blk_mq_debugfs_tags_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_debugfs_tags_show(struct seq_file *m, struct blk_mq_tags *tags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff8150fc40)
Location: block/blk-mq-debugfs.c:443
Inline: True
Direct callers:
  - block/blk-mq-debugfs.c:hctx_sched_tags_show
  - block/blk-mq-debugfs.c:hctx_tags_show
```
**Symbols:**

```
ffffffff8150fc40-ffffffff8150fccb: blk_mq_debugfs_tags_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_debugfs_tags_show(struct seq_file *m, struct blk_mq_tags *tags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff81529460)
Location: block/blk-mq-debugfs.c:443
Inline: True
Direct callers:
  - block/blk-mq-debugfs.c:hctx_sched_tags_show
  - block/blk-mq-debugfs.c:hctx_tags_show
```
**Symbols:**

```
ffffffff81529460-ffffffff815294eb: blk_mq_debugfs_tags_show (STB_LOCAL)
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
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
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
