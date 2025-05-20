# Function: <code>t_mod_start</code>

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
void *t_mod_start(struct seq_file *m, loff_t *pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81155b30)
Location: kernel/trace/ftrace.c:3298
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:t_start
  - kernel/trace/ftrace.c:t_next
  - kernel/trace/ftrace.c:t_next
```
**Symbols:**

```
ffffffff81155b30-ffffffff81155c75: t_mod_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void *t_mod_start(struct seq_file *m, loff_t *pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811624e0)
Location: kernel/trace/ftrace.c:3266
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:t_start
  - kernel/trace/ftrace.c:t_next
  - kernel/trace/ftrace.c:t_next
```
**Symbols:**

```
ffffffff811624e0-ffffffff81162625: t_mod_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void *t_mod_start(struct seq_file *m, loff_t *pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811713c0)
Location: kernel/trace/ftrace.c:3255
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:t_start
  - kernel/trace/ftrace.c:t_next
  - kernel/trace/ftrace.c:t_next
```
**Symbols:**

```
ffffffff811713c0-ffffffff81171505: t_mod_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void *t_mod_start(struct seq_file *m, loff_t *pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8117ee70)
Location: kernel/trace/ftrace.c:3214
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:t_start
  - kernel/trace/ftrace.c:t_next
  - kernel/trace/ftrace.c:t_next
```
**Symbols:**

```
ffffffff8117ee70-ffffffff8117efb5: t_mod_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void *t_mod_start(struct seq_file *m, loff_t *pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8118bd30)
Location: kernel/trace/ftrace.c:3220
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:t_start
  - kernel/trace/ftrace.c:t_next
  - kernel/trace/ftrace.c:t_next
```
**Symbols:**

```
ffffffff8118bd30-ffffffff8118be86: t_mod_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void *t_mod_start(struct seq_file *m, loff_t *pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81197b60)
Location: kernel/trace/ftrace.c:3221
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:t_start
  - kernel/trace/ftrace.c:t_next
  - kernel/trace/ftrace.c:t_next
```
**Symbols:**

```
ffffffff81197b60-ffffffff81197cb6: t_mod_start (STB_LOCAL)
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
In kernel/trace/ftrace.c (ffffffff811ad860)
Location: kernel/trace/ftrace.c:3340
Inline: True
Direct callers:
  - kernel/trace/ftrace.c:t_start
  - kernel/trace/ftrace.c:t_next
  - kernel/trace/ftrace.c:t_next
```
**Symbols:**

```
ffffffff811ad860-ffffffff811ad9aa: t_mod_start.isra.0 (STB_LOCAL)
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
In kernel/trace/ftrace.c (ffffffff811ab170)
Location: kernel/trace/ftrace.c:3418
Inline: True
Direct callers:
  - kernel/trace/ftrace.c:t_start
  - kernel/trace/ftrace.c:t_next
  - kernel/trace/ftrace.c:t_next
```
**Symbols:**

```
ffffffff811ab170-ffffffff811ab2ba: t_mod_start.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void *t_mod_start(struct seq_file *m, loff_t *pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811abe10)
Location: kernel/trace/ftrace.c:3418
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:t_start
  - kernel/trace/ftrace.c:t_next
  - kernel/trace/ftrace.c:t_next
```
**Symbols:**

```
ffffffff811abe10-ffffffff811abf70: t_mod_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void *t_mod_start(struct seq_file *m, loff_t *pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811d5a70)
Location: kernel/trace/ftrace.c:3419
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:t_start
  - kernel/trace/ftrace.c:t_next
  - kernel/trace/ftrace.c:t_next
```
**Symbols:**

```
ffffffff811d5a70-ffffffff811d5bd0: t_mod_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void *t_mod_start(struct seq_file *m, loff_t *pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8120ac90)
Location: kernel/trace/ftrace.c:3431
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:t_start
  - kernel/trace/ftrace.c:t_next
  - kernel/trace/ftrace.c:t_next
```
**Symbols:**

```
ffffffff8120ac90-ffffffff8120ade2: t_mod_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void *t_mod_start(struct seq_file *m, loff_t *pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81253270)
Location: kernel/trace/ftrace.c:3451
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:t_start
  - kernel/trace/ftrace.c:t_next
  - kernel/trace/ftrace.c:t_next
```
**Symbols:**

```
ffffffff81253270-ffffffff812533c2: t_mod_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void *t_mod_start(struct seq_file *m, loff_t *pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8126a630)
Location: kernel/trace/ftrace.c:3540
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:t_start
  - kernel/trace/ftrace.c:t_next
  - kernel/trace/ftrace.c:t_next
```
**Symbols:**

```
ffffffff8126a630-ffffffff8126a782: t_mod_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void *t_mod_start(struct seq_file *m, loff_t *pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff812847e0)
Location: kernel/trace/ftrace.c:3506
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:t_start
  - kernel/trace/ftrace.c:t_next
  - kernel/trace/ftrace.c:t_next
```
**Symbols:**

```
ffffffff812847e0-ffffffff81284932: t_mod_start (STB_LOCAL)
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
void *t_mod_start(struct seq_file *m, loff_t *pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffff8000102101f0)
Location: kernel/trace/ftrace.c:3221
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:t_start
  - kernel/trace/ftrace.c:t_next
  - kernel/trace/ftrace.c:t_next
```
**Symbols:**

```
ffff8000102101f0-ffff800010210364: t_mod_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void *t_mod_start(struct seq_file *m, loff_t *pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (c044e628)
Location: kernel/trace/ftrace.c:3221
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:t_start
  - kernel/trace/ftrace.c:t_next
  - kernel/trace/ftrace.c:t_next
```
**Symbols:**

```
c044e628-c044e7ac: t_mod_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void *t_mod_start(struct seq_file *m, loff_t *pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (c00000000028dcd0)
Location: kernel/trace/ftrace.c:3221
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:t_start
  - kernel/trace/ftrace.c:t_next
  - kernel/trace/ftrace.c:t_next
```
**Symbols:**

```
c00000000028dcd0-c00000000028dec8: t_mod_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void *t_mod_start(struct seq_file *m, loff_t *pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffe00016feec)
Location: kernel/trace/ftrace.c:3221
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:t_start
  - kernel/trace/ftrace.c:t_next
  - kernel/trace/ftrace.c:t_next
```
**Symbols:**

```
ffffffe00016feec-ffffffe00016ffe8: t_mod_start (STB_LOCAL)
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
void *t_mod_start(struct seq_file *m, loff_t *pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81190180)
Location: kernel/trace/ftrace.c:3221
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:t_start
  - kernel/trace/ftrace.c:t_next
  - kernel/trace/ftrace.c:t_next
```
**Symbols:**

```
ffffffff81190180-ffffffff811902d6: t_mod_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void *t_mod_start(struct seq_file *m, loff_t *pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811833c0)
Location: kernel/trace/ftrace.c:3221
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:t_start
  - kernel/trace/ftrace.c:t_next
  - kernel/trace/ftrace.c:t_next
```
**Symbols:**

```
ffffffff811833c0-ffffffff81183516: t_mod_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void *t_mod_start(struct seq_file *m, loff_t *pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8118df50)
Location: kernel/trace/ftrace.c:3221
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:t_start
  - kernel/trace/ftrace.c:t_next
  - kernel/trace/ftrace.c:t_next
```
**Symbols:**

```
ffffffff8118df50-ffffffff8118e0a6: t_mod_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void *t_mod_start(struct seq_file *m, loff_t *pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8119bae0)
Location: kernel/trace/ftrace.c:3221
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:t_start
  - kernel/trace/ftrace.c:t_next
  - kernel/trace/ftrace.c:t_next
```
**Symbols:**

```
ffffffff8119bae0-ffffffff8119bc36: t_mod_start (STB_LOCAL)
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
