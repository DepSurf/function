# Function: <code>cgroup_procs_next</code>

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
void *cgroup_procs_next(struct seq_file *s, void *v, loff_t *pos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8112811c)
Location: kernel/cgroup/cgroup.c:3841
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_procs_start
```
**Symbols:**

```
ffffffff81128010-ffffffff8112803e: cgroup_procs_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void *cgroup_procs_next(struct seq_file *s, void *v, loff_t *pos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81134540)
Location: kernel/cgroup/cgroup.c:4259
Inline: True
```
**Symbols:**

```
ffffffff81134540-ffffffff81134558: cgroup_procs_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void *cgroup_procs_next(struct seq_file *s, void *v, loff_t *pos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81142c60)
Location: kernel/cgroup/cgroup.c:4296
Inline: True
```
**Symbols:**

```
ffffffff81142c60-ffffffff81142c78: cgroup_procs_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void *cgroup_procs_next(struct seq_file *s, void *v, loff_t *pos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8114e790)
Location: kernel/cgroup/cgroup.c:4365
Inline: True
```
**Symbols:**

```
ffffffff8114e790-ffffffff8114e7a8: cgroup_procs_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void *cgroup_procs_next(struct seq_file *s, void *v, loff_t *pos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8115a2f0)
Location: kernel/cgroup/cgroup.c:4655
Inline: True
```
**Symbols:**

```
ffffffff8115a2f0-ffffffff8115a308: cgroup_procs_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void *cgroup_procs_next(struct seq_file *s, void *v, loff_t *pos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81165f90)
Location: kernel/cgroup/cgroup.c:4666
Inline: True
```
**Symbols:**

```
ffffffff81165f90-ffffffff81165fb1: cgroup_procs_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void *cgroup_procs_next(struct seq_file *s, void *v, loff_t *pos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8117729d)
Location: kernel/cgroup/cgroup.c:4600
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:__cgroup_procs_start
```
**Symbols:**

```
ffffffff81177100-ffffffff81177121: cgroup_procs_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void *cgroup_procs_next(struct seq_file *s, void *v, loff_t *pos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81173f7e)
Location: kernel/cgroup/cgroup.c:4601
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:__cgroup_procs_start
```
**Symbols:**

```
ffffffff81173de0-ffffffff81173e01: cgroup_procs_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void *cgroup_procs_next(struct seq_file *s, void *v, loff_t *pos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81174b51)
Location: kernel/cgroup/cgroup.c:4614
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:__cgroup_procs_start
```
**Symbols:**

```
ffffffff811749b0-ffffffff811749d1: cgroup_procs_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void *cgroup_procs_next(struct seq_file *s, void *v, loff_t *pos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8119bdf1)
Location: kernel/cgroup/cgroup.c:4789
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:__cgroup_procs_start
```
**Symbols:**

```
ffffffff8119ba80-ffffffff8119baa5: cgroup_procs_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void *cgroup_procs_next(struct seq_file *s, void *v, loff_t *pos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811cc085)
Location: kernel/cgroup/cgroup.c:4800
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:__cgroup_procs_start
```
**Symbols:**

```
ffffffff811cbcd0-ffffffff811cbcfd: cgroup_procs_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void *cgroup_procs_next(struct seq_file *s, void *v, loff_t *pos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8120f584)
Location: kernel/cgroup/cgroup.c:4997
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:__cgroup_procs_start
```
**Symbols:**

```
ffffffff8120f190-ffffffff8120f1bd: cgroup_procs_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void *cgroup_procs_next(struct seq_file *s, void *v, loff_t *pos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81224f94)
Location: kernel/cgroup/cgroup.c:4974
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:__cgroup_procs_start
```
**Symbols:**

```
ffffffff81224ba0-ffffffff81224bcd: cgroup_procs_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void *cgroup_procs_next(struct seq_file *s, void *v, loff_t *pos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8123cc84)
Location: kernel/cgroup/cgroup.c:5010
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:__cgroup_procs_start
```
**Symbols:**

```
ffffffff8123c890-ffffffff8123c8bd: cgroup_procs_next (STB_LOCAL)
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
void *cgroup_procs_next(struct seq_file *s, void *v, loff_t *pos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffff8000101d7b80)
Location: kernel/cgroup/cgroup.c:4666
Inline: True
```
**Symbols:**

```
ffff8000101d7b80-ffff8000101d7bc4: cgroup_procs_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void *cgroup_procs_next(struct seq_file *s, void *v, loff_t *pos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (c041a9ec)
Location: kernel/cgroup/cgroup.c:4666
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:__cgroup_procs_start
```
**Symbols:**

```
c041a848-c041a88c: cgroup_procs_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void *cgroup_procs_next(struct seq_file *s, void *v, loff_t *pos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (c000000000244960)
Location: kernel/cgroup/cgroup.c:4666
Inline: True
```
**Symbols:**

```
c000000000244960-c000000000244990: cgroup_procs_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void *cgroup_procs_next(struct seq_file *s, void *v, loff_t *pos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffe000150c24)
Location: kernel/cgroup/cgroup.c:4666
Inline: True
```
**Symbols:**

```
ffffffe000150c24-ffffffe000150c60: cgroup_procs_next (STB_LOCAL)
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
void *cgroup_procs_next(struct seq_file *s, void *v, loff_t *pos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8115e5b0)
Location: kernel/cgroup/cgroup.c:4666
Inline: True
```
**Symbols:**

```
ffffffff8115e5b0-ffffffff8115e5d1: cgroup_procs_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void *cgroup_procs_next(struct seq_file *s, void *v, loff_t *pos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81151860)
Location: kernel/cgroup/cgroup.c:4666
Inline: True
```
**Symbols:**

```
ffffffff81151860-ffffffff81151881: cgroup_procs_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void *cgroup_procs_next(struct seq_file *s, void *v, loff_t *pos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8115c380)
Location: kernel/cgroup/cgroup.c:4666
Inline: True
```
**Symbols:**

```
ffffffff8115c380-ffffffff8115c3a1: cgroup_procs_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void *cgroup_procs_next(struct seq_file *s, void *v, loff_t *pos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811694a0)
Location: kernel/cgroup/cgroup.c:4666
Inline: True
```
**Symbols:**

```
ffffffff811694a0-ffffffff811694c1: cgroup_procs_next (STB_LOCAL)
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
