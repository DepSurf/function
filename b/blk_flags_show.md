# Function: <code>blk_flags_show</code>

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
int blk_flags_show(struct seq_file *m, const long unsigned int flags, const const char * *flag_name, int flag_name_count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff814596a0)
Location: block/blk-mq-debugfs.c:27
Inline: False
Direct callers:
  - block/blk-mq-debugfs.c:__blk_mq_debugfs_rq_show
  - block/blk-mq-debugfs.c:__blk_mq_debugfs_rq_show
  - block/blk-mq-debugfs.c:__blk_mq_debugfs_rq_show
  - block/blk-mq-debugfs.c:hctx_flags_show
  - block/blk-mq-debugfs.c:hctx_state_show
  - block/blk-mq-debugfs.c:queue_state_show
```
**Symbols:**

```
ffffffff814596a0-ffffffff81459742: blk_flags_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int blk_flags_show(struct seq_file *m, const long unsigned int flags, const const char * *flag_name, int flag_name_count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff81485410)
Location: block/blk-mq-debugfs.c:27
Inline: False
Direct callers:
  - block/blk-mq-debugfs.c:__blk_mq_debugfs_rq_show
  - block/blk-mq-debugfs.c:__blk_mq_debugfs_rq_show
  - block/blk-mq-debugfs.c:__blk_mq_debugfs_rq_show
  - block/blk-mq-debugfs.c:hctx_flags_show
  - block/blk-mq-debugfs.c:hctx_state_show
  - block/blk-mq-debugfs.c:queue_state_show
```
**Symbols:**

```
ffffffff81485410-ffffffff814854b2: blk_flags_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int blk_flags_show(struct seq_file *m, const long unsigned int flags, const const char * *flag_name, int flag_name_count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff814ba2c0)
Location: block/blk-mq-debugfs.c:85
Inline: False
Direct callers:
  - block/blk-mq-debugfs.c:__blk_mq_debugfs_rq_show
  - block/blk-mq-debugfs.c:__blk_mq_debugfs_rq_show
  - block/blk-mq-debugfs.c:hctx_flags_show
  - block/blk-mq-debugfs.c:hctx_state_show
  - block/blk-mq-debugfs.c:queue_state_show
```
**Symbols:**

```
ffffffff814ba2c0-ffffffff814ba363: blk_flags_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int blk_flags_show(struct seq_file *m, const long unsigned int flags, const const char * *flag_name, int flag_name_count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff814ce420)
Location: block/blk-mq-debugfs.c:86
Inline: False
Direct callers:
  - block/blk-mq-debugfs.c:__blk_mq_debugfs_rq_show
  - block/blk-mq-debugfs.c:__blk_mq_debugfs_rq_show
  - block/blk-mq-debugfs.c:hctx_flags_show
  - block/blk-mq-debugfs.c:hctx_state_show
  - block/blk-mq-debugfs.c:queue_state_show
```
**Symbols:**

```
ffffffff814ce420-ffffffff814ce4c3: blk_flags_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int blk_flags_show(struct seq_file *m, const long unsigned int flags, const const char * *flag_name, int flag_name_count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff814fcce0)
Location: block/blk-mq-debugfs.c:75
Inline: False
Direct callers:
  - block/blk-mq-debugfs.c:__blk_mq_debugfs_rq_show
  - block/blk-mq-debugfs.c:__blk_mq_debugfs_rq_show
  - block/blk-mq-debugfs.c:hctx_flags_show
  - block/blk-mq-debugfs.c:hctx_state_show
  - block/blk-mq-debugfs.c:queue_state_show
```
**Symbols:**

```
ffffffff814fcce0-ffffffff814fcd82: blk_flags_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int blk_flags_show(struct seq_file *m, const long unsigned int flags, const const char * *flag_name, int flag_name_count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff8151ac30)
Location: block/blk-mq-debugfs.c:75
Inline: False
Direct callers:
  - block/blk-mq-debugfs.c:__blk_mq_debugfs_rq_show
  - block/blk-mq-debugfs.c:__blk_mq_debugfs_rq_show
  - block/blk-mq-debugfs.c:hctx_flags_show
  - block/blk-mq-debugfs.c:hctx_state_show
  - block/blk-mq-debugfs.c:queue_state_show
```
**Symbols:**

```
ffffffff8151ac30-ffffffff8151acd2: blk_flags_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff8157b9e0)
Location: block/blk-mq-debugfs.c:75
Inline: True
Direct callers:
  - block/blk-mq-debugfs.c:__blk_mq_debugfs_rq_show
  - block/blk-mq-debugfs.c:__blk_mq_debugfs_rq_show
  - block/blk-mq-debugfs.c:hctx_flags_show
  - block/blk-mq-debugfs.c:hctx_state_show
  - block/blk-mq-debugfs.c:queue_state_show
```
**Symbols:**

```
ffffffff8157b9e0-ffffffff8157ba8d: blk_flags_show.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff81598aa0)
Location: block/blk-mq-debugfs.c:75
Inline: True
Direct callers:
  - block/blk-mq-debugfs.c:__blk_mq_debugfs_rq_show
  - block/blk-mq-debugfs.c:__blk_mq_debugfs_rq_show
  - block/blk-mq-debugfs.c:hctx_flags_show
  - block/blk-mq-debugfs.c:hctx_state_show
  - block/blk-mq-debugfs.c:queue_state_show
```
**Symbols:**

```
ffffffff81598aa0-ffffffff81598b4d: blk_flags_show.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff8159f8b0)
Location: block/blk-mq-debugfs.c:75
Inline: True
Direct callers:
  - block/blk-mq-debugfs.c:__blk_mq_debugfs_rq_show
  - block/blk-mq-debugfs.c:__blk_mq_debugfs_rq_show
  - block/blk-mq-debugfs.c:hctx_flags_show
  - block/blk-mq-debugfs.c:hctx_state_show
  - block/blk-mq-debugfs.c:queue_state_show
```
**Symbols:**

```
ffffffff8159f8b0-ffffffff8159f95d: blk_flags_show.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff81608060)
Location: block/blk-mq-debugfs.c:75
Inline: True
Direct callers:
  - block/blk-mq-debugfs.c:__blk_mq_debugfs_rq_show
  - block/blk-mq-debugfs.c:__blk_mq_debugfs_rq_show
  - block/blk-mq-debugfs.c:hctx_flags_show
  - block/blk-mq-debugfs.c:hctx_state_show
  - block/blk-mq-debugfs.c:queue_state_show
```
**Symbols:**

```
ffffffff81608060-ffffffff8160810d: blk_flags_show.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff816bba40)
Location: block/blk-mq-debugfs.c:79
Inline: True
Direct callers:
  - block/blk-mq-debugfs.c:__blk_mq_debugfs_rq_show
  - block/blk-mq-debugfs.c:__blk_mq_debugfs_rq_show
  - block/blk-mq-debugfs.c:hctx_flags_show
  - block/blk-mq-debugfs.c:hctx_state_show
  - block/blk-mq-debugfs.c:queue_state_show
```
**Symbols:**

```
ffffffff816bba40-ffffffff816bbb17: blk_flags_show.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff8177c320)
Location: block/blk-mq-debugfs.c:79
Inline: True
Direct callers:
  - block/blk-mq-debugfs.c:__blk_mq_debugfs_rq_show
  - block/blk-mq-debugfs.c:__blk_mq_debugfs_rq_show
  - block/blk-mq-debugfs.c:hctx_flags_show
  - block/blk-mq-debugfs.c:hctx_state_show
  - block/blk-mq-debugfs.c:queue_state_show
```
**Symbols:**

```
ffffffff8177c320-ffffffff8177c3f7: blk_flags_show.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff817bbe30)
Location: block/blk-mq-debugfs.c:52
Inline: True
Direct callers:
  - block/blk-mq-debugfs.c:__blk_mq_debugfs_rq_show
  - block/blk-mq-debugfs.c:__blk_mq_debugfs_rq_show
  - block/blk-mq-debugfs.c:hctx_flags_show
  - block/blk-mq-debugfs.c:hctx_state_show
  - block/blk-mq-debugfs.c:queue_state_show
```
**Symbols:**

```
ffffffff817bbe30-ffffffff817bbefb: blk_flags_show.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff818004f0)
Location: block/blk-mq-debugfs.c:52
Inline: True
Direct callers:
  - block/blk-mq-debugfs.c:__blk_mq_debugfs_rq_show
  - block/blk-mq-debugfs.c:__blk_mq_debugfs_rq_show
  - block/blk-mq-debugfs.c:hctx_flags_show
  - block/blk-mq-debugfs.c:hctx_state_show
  - block/blk-mq-debugfs.c:queue_state_show
```
**Symbols:**

```
ffffffff818004f0-ffffffff818005bb: blk_flags_show.isra.0 (STB_LOCAL)
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
int blk_flags_show(struct seq_file *m, const long unsigned int flags, const const char * *flag_name, int flag_name_count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffff800010622cb8)
Location: block/blk-mq-debugfs.c:75
Inline: False
Direct callers:
  - block/blk-mq-debugfs.c:__blk_mq_debugfs_rq_show
  - block/blk-mq-debugfs.c:__blk_mq_debugfs_rq_show
  - block/blk-mq-debugfs.c:hctx_flags_show
  - block/blk-mq-debugfs.c:hctx_state_show
  - block/blk-mq-debugfs.c:queue_state_show
```
**Symbols:**

```
ffff800010622cb8-ffff800010622d90: blk_flags_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int blk_flags_show(struct seq_file *m, const long unsigned int flags, const const char * *flag_name, int flag_name_count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (c07ca784)
Location: block/blk-mq-debugfs.c:75
Inline: False
Direct callers:
  - block/blk-mq-debugfs.c:__blk_mq_debugfs_rq_show
  - block/blk-mq-debugfs.c:__blk_mq_debugfs_rq_show
  - block/blk-mq-debugfs.c:hctx_flags_show
  - block/blk-mq-debugfs.c:hctx_state_show
  - block/blk-mq-debugfs.c:queue_state_show
```
**Symbols:**

```
c07ca784-c07ca880: blk_flags_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int blk_flags_show(struct seq_file *m, const long unsigned int flags, const const char * *flag_name, int flag_name_count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (c0000000007c2dd0)
Location: block/blk-mq-debugfs.c:75
Inline: False
Direct callers:
  - block/blk-mq-debugfs.c:__blk_mq_debugfs_rq_show
  - block/blk-mq-debugfs.c:__blk_mq_debugfs_rq_show
  - block/blk-mq-debugfs.c:hctx_flags_show
  - block/blk-mq-debugfs.c:hctx_state_show
  - block/blk-mq-debugfs.c:queue_state_show
```
**Symbols:**

```
c0000000007c2dd0-c0000000007c2f08: blk_flags_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int blk_flags_show(struct seq_file *m, const long unsigned int flags, const const char * *flag_name, int flag_name_count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffe000454b54)
Location: block/blk-mq-debugfs.c:75
Inline: False
Direct callers:
  - block/blk-mq-debugfs.c:__blk_mq_debugfs_rq_show
  - block/blk-mq-debugfs.c:__blk_mq_debugfs_rq_show
  - block/blk-mq-debugfs.c:hctx_flags_show
  - block/blk-mq-debugfs.c:hctx_state_show
  - block/blk-mq-debugfs.c:queue_state_show
```
**Symbols:**

```
ffffffe000454b54-ffffffe000454c06: blk_flags_show (STB_LOCAL)
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
int blk_flags_show(struct seq_file *m, const long unsigned int flags, const const char * *flag_name, int flag_name_count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff81513210)
Location: block/blk-mq-debugfs.c:75
Inline: False
Direct callers:
  - block/blk-mq-debugfs.c:__blk_mq_debugfs_rq_show
  - block/blk-mq-debugfs.c:__blk_mq_debugfs_rq_show
  - block/blk-mq-debugfs.c:hctx_flags_show
  - block/blk-mq-debugfs.c:hctx_state_show
  - block/blk-mq-debugfs.c:queue_state_show
```
**Symbols:**

```
ffffffff81513210-ffffffff815132b2: blk_flags_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int blk_flags_show(struct seq_file *m, const long unsigned int flags, const const char * *flag_name, int flag_name_count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff81503520)
Location: block/blk-mq-debugfs.c:75
Inline: False
Direct callers:
  - block/blk-mq-debugfs.c:__blk_mq_debugfs_rq_show
  - block/blk-mq-debugfs.c:__blk_mq_debugfs_rq_show
  - block/blk-mq-debugfs.c:hctx_flags_show
  - block/blk-mq-debugfs.c:hctx_state_show
  - block/blk-mq-debugfs.c:queue_state_show
```
**Symbols:**

```
ffffffff81503520-ffffffff815035c2: blk_flags_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int blk_flags_show(struct seq_file *m, const long unsigned int flags, const const char * *flag_name, int flag_name_count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff8150f2a0)
Location: block/blk-mq-debugfs.c:75
Inline: False
Direct callers:
  - block/blk-mq-debugfs.c:__blk_mq_debugfs_rq_show
  - block/blk-mq-debugfs.c:__blk_mq_debugfs_rq_show
  - block/blk-mq-debugfs.c:hctx_flags_show
  - block/blk-mq-debugfs.c:hctx_state_show
  - block/blk-mq-debugfs.c:queue_state_show
```
**Symbols:**

```
ffffffff8150f2a0-ffffffff8150f342: blk_flags_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int blk_flags_show(struct seq_file *m, const long unsigned int flags, const const char * *flag_name, int flag_name_count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff81528ac0)
Location: block/blk-mq-debugfs.c:75
Inline: False
Direct callers:
  - block/blk-mq-debugfs.c:__blk_mq_debugfs_rq_show
  - block/blk-mq-debugfs.c:__blk_mq_debugfs_rq_show
  - block/blk-mq-debugfs.c:hctx_flags_show
  - block/blk-mq-debugfs.c:hctx_state_show
  - block/blk-mq-debugfs.c:queue_state_show
```
**Symbols:**

```
ffffffff81528ac0-ffffffff81528b62: blk_flags_show (STB_LOCAL)
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
