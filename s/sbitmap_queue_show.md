# Function: <code>sbitmap_queue_show</code>

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
<summary>In <code>4.13</code>: ✅</summary>

```c
void sbitmap_queue_show(struct sbitmap_queue *sbq, struct seq_file *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (ffffffff8148b980)
Location: lib/sbitmap.c:500
Inline: False
```
**Symbols:**

```
ffffffff8148b980-ffffffff8148bad8: sbitmap_queue_show (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void sbitmap_queue_show(struct sbitmap_queue *sbq, struct seq_file *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (ffffffff814c7aa0)
Location: lib/sbitmap.c:500
Inline: False
```
**Symbols:**

```
ffffffff814c7aa0-ffffffff814c7bdf: sbitmap_queue_show (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void sbitmap_queue_show(struct sbitmap_queue *sbq, struct seq_file *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (ffffffff814f87e0)
Location: lib/sbitmap.c:548
Inline: False
```
**Symbols:**

```
ffffffff814f87e0-ffffffff814f8932: sbitmap_queue_show (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void sbitmap_queue_show(struct sbitmap_queue *sbq, struct seq_file *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (ffffffff8150ca00)
Location: lib/sbitmap.c:631
Inline: False
```
**Symbols:**

```
ffffffff8150ca00-ffffffff8150cb65: sbitmap_queue_show (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void sbitmap_queue_show(struct sbitmap_queue *sbq, struct seq_file *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (ffffffff8153b180)
Location: lib/sbitmap.c:627
Inline: False
```
**Symbols:**

```
ffffffff8153b180-ffffffff8153b2dd: sbitmap_queue_show (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void sbitmap_queue_show(struct sbitmap_queue *sbq, struct seq_file *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (ffffffff8155bfa0)
Location: lib/sbitmap.c:627
Inline: False
```
**Symbols:**

```
ffffffff8155bfa0-ffffffff8155c0fd: sbitmap_queue_show (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void sbitmap_queue_show(struct sbitmap_queue *sbq, struct seq_file *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (ffffffff815e5a20)
Location: lib/sbitmap.c:610
Inline: False
Direct callers:
  - block/blk-mq-debugfs.c:blk_mq_debugfs_tags_show
  - block/blk-mq-debugfs.c:blk_mq_debugfs_tags_show
```
**Symbols:**

```
ffffffff815e5a20-ffffffff815e5b7d: sbitmap_queue_show (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void sbitmap_queue_show(struct sbitmap_queue *sbq, struct seq_file *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (ffffffff81609de0)
Location: lib/sbitmap.c:605
Inline: False
Direct callers:
  - block/blk-mq-debugfs.c:blk_mq_debugfs_tags_show
  - block/blk-mq-debugfs.c:blk_mq_debugfs_tags_show
```
**Symbols:**

```
ffffffff81609de0-ffffffff81609f3d: sbitmap_queue_show (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void sbitmap_queue_show(struct sbitmap_queue *sbq, struct seq_file *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (ffffffff815edb40)
Location: lib/sbitmap.c:631
Inline: False
Direct callers:
  - block/blk-mq-debugfs.c:blk_mq_debugfs_tags_show
  - block/blk-mq-debugfs.c:blk_mq_debugfs_tags_show
```
**Symbols:**

```
ffffffff815edb40-ffffffff815edc9d: sbitmap_queue_show (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void sbitmap_queue_show(struct sbitmap_queue *sbq, struct seq_file *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/sbitmap.c (0)
Location: lib/sbitmap.c:631
Inline: False
Direct callers:
  - block/blk-mq-debugfs.c:blk_mq_debugfs_tags_show
  - block/blk-mq-debugfs.c:blk_mq_debugfs_tags_show
```
**Symbols:**

```
ffffffff81cdf07f-ffffffff81cdf09a: sbitmap_queue_show.cold (STB_LOCAL)
ffffffff8165abf0-ffffffff8165ad87: sbitmap_queue_show (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void sbitmap_queue_show(struct sbitmap_queue *sbq, struct seq_file *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/sbitmap.c (0)
Location: lib/sbitmap.c:740
Inline: False
Direct callers:
  - block/blk-mq-debugfs.c:blk_mq_debugfs_tags_show
  - block/blk-mq-debugfs.c:blk_mq_debugfs_tags_show
```
**Symbols:**

```
ffffffff81ea5468-ffffffff81ea5483: sbitmap_queue_show.cold (STB_LOCAL)
ffffffff81773000-ffffffff817731a6: sbitmap_queue_show (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void sbitmap_queue_show(struct sbitmap_queue *sbq, struct seq_file *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/sbitmap.c (0)
Location: lib/sbitmap.c:700
Inline: False
Direct callers:
  - block/blk-mq-debugfs.c:blk_mq_debugfs_tags_show
  - block/blk-mq-debugfs.c:blk_mq_debugfs_tags_show
```
**Symbols:**

```
ffffffff8208d86c-ffffffff8208d887: sbitmap_queue_show.cold (STB_LOCAL)
ffffffff818a3450-ffffffff818a35fb: sbitmap_queue_show (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void sbitmap_queue_show(struct sbitmap_queue *sbq, struct seq_file *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/sbitmap.c (0)
Location: lib/sbitmap.c:692
Inline: False
Direct callers:
  - block/blk-mq-debugfs.c:blk_mq_debugfs_tags_show
  - block/blk-mq-debugfs.c:blk_mq_debugfs_tags_show
```
**Symbols:**

```
ffffffff8210db32-ffffffff8210db4d: sbitmap_queue_show.cold (STB_LOCAL)
ffffffff818e57a0-ffffffff818e594b: sbitmap_queue_show (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void sbitmap_queue_show(struct sbitmap_queue *sbq, struct seq_file *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/sbitmap.c (0)
Location: lib/sbitmap.c:687
Inline: False
Direct callers:
  - block/blk-mq-debugfs.c:blk_mq_debugfs_tags_show
  - block/blk-mq-debugfs.c:blk_mq_debugfs_tags_show
```
**Symbols:**

```
ffffffff821eb76f-ffffffff821eb78a: sbitmap_queue_show.cold (STB_LOCAL)
ffffffff8192c7a0-ffffffff8192c94b: sbitmap_queue_show (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void sbitmap_queue_show(struct sbitmap_queue *sbq, struct seq_file *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (ffff800010669768)
Location: lib/sbitmap.c:627
Inline: False
```
**Symbols:**

```
ffff800010669768-ffff80001066991c: sbitmap_queue_show (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void sbitmap_queue_show(struct sbitmap_queue *sbq, struct seq_file *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (c0812554)
Location: lib/sbitmap.c:627
Inline: False
```
**Symbols:**

```
c0812554-c0812714: sbitmap_queue_show (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void sbitmap_queue_show(struct sbitmap_queue *sbq, struct seq_file *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (c00000000081f280)
Location: lib/sbitmap.c:627
Inline: False
```
**Symbols:**

```
c00000000081f280-c00000000081f4d4: sbitmap_queue_show (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void sbitmap_queue_show(struct sbitmap_queue *sbq, struct seq_file *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (ffffffe000494ad4)
Location: lib/sbitmap.c:627
Inline: False
```
**Symbols:**

```
ffffffe000494ad4-ffffffe000494c9c: sbitmap_queue_show (STB_GLOBAL)
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
void sbitmap_queue_show(struct sbitmap_queue *sbq, struct seq_file *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (ffffffff81554590)
Location: lib/sbitmap.c:627
Inline: False
```
**Symbols:**

```
ffffffff81554590-ffffffff815546ed: sbitmap_queue_show (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void sbitmap_queue_show(struct sbitmap_queue *sbq, struct seq_file *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (ffffffff81544810)
Location: lib/sbitmap.c:627
Inline: False
```
**Symbols:**

```
ffffffff81544810-ffffffff8154496d: sbitmap_queue_show (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void sbitmap_queue_show(struct sbitmap_queue *sbq, struct seq_file *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (ffffffff815502d0)
Location: lib/sbitmap.c:627
Inline: False
```
**Symbols:**

```
ffffffff815502d0-ffffffff8155042d: sbitmap_queue_show (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void sbitmap_queue_show(struct sbitmap_queue *sbq, struct seq_file *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (ffffffff8156a110)
Location: lib/sbitmap.c:627
Inline: False
```
**Symbols:**

```
ffffffff8156a110-ffffffff8156a26d: sbitmap_queue_show (STB_GLOBAL)
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
