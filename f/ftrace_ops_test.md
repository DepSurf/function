# Function: <code>ftrace_ops_test</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81140a40)
Location: kernel/trace/ftrace.c:1512
Inline: True
Direct callers:
  - kernel/trace/ftrace.c:ftrace_ops_control_func
  - kernel/trace/ftrace.c:ftrace_ops_list_func
```
**Symbols:**

```
ffffffff81140a40-ffffffff81140a9d: ftrace_ops_test.isra.9 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81149130)
Location: kernel/trace/ftrace.c:1481
Inline: True
Direct callers:
  - kernel/trace/ftrace.c:ftrace_ops_list_func
```
**Symbols:**

```
ffffffff81149130-ffffffff8114918d: ftrace_ops_test.isra.11 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81152fe0)
Location: kernel/trace/ftrace.c:1487
Inline: True
Direct callers:
  - kernel/trace/ftrace.c:ftrace_ops_list_func
```
**Symbols:**

```
ffffffff81152fe0-ffffffff8115303d: ftrace_ops_test.isra.13 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81155970)
Location: kernel/trace/ftrace.c:1572
Inline: True
Direct callers:
  - kernel/trace/ftrace.c:ftrace_graph_entry_test
  - kernel/trace/ftrace.c:ftrace_ops_list_func
```
**Symbols:**

```
ffffffff81155970-ffffffff811559ac: ftrace_ops_test.isra.23 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81162310)
Location: kernel/trace/ftrace.c:1548
Inline: True
Direct callers:
  - kernel/trace/ftrace.c:ftrace_graph_entry_test
  - kernel/trace/ftrace.c:ftrace_ops_list_func
```
**Symbols:**

```
ffffffff81162310-ffffffff8116234c: ftrace_ops_test.isra.27 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811711f0)
Location: kernel/trace/ftrace.c:1537
Inline: True
Direct callers:
  - kernel/trace/ftrace.c:ftrace_ops_list_func
```
**Symbols:**

```
ffffffff811711f0-ffffffff8117122b: ftrace_ops_test.isra.29 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ftrace_ops_test(struct ftrace_ops *ops, long unsigned int ip, void *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811803a0)
Location: kernel/trace/ftrace.c:1486
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_ops_list_func
```
**Symbols:**

```
ffffffff811803a0-ffffffff811803e1: ftrace_ops_test (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ftrace_ops_test(struct ftrace_ops *ops, long unsigned int ip, void *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8118d570)
Location: kernel/trace/ftrace.c:1483
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_ops_list_func
```
**Symbols:**

```
ffffffff8118d570-ffffffff8118d5b1: ftrace_ops_test (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ftrace_ops_test(struct ftrace_ops *ops, long unsigned int ip, void *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81199180)
Location: kernel/trace/ftrace.c:1484
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_ops_list_func
```
**Symbols:**

```
ffffffff81199180-ffffffff811991c1: ftrace_ops_test (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int ftrace_ops_test(struct ftrace_ops *ops, long unsigned int ip, void *regs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811ae354)
Location: kernel/trace/ftrace.c:1477
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_ops_list_func
```
**Symbols:**

```
ffffffff811af520-ffffffff811af561: ftrace_ops_test (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int ftrace_ops_test(struct ftrace_ops *ops, long unsigned int ip, void *regs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811abc83)
Location: kernel/trace/ftrace.c:1476
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_ops_list_func
```
**Symbols:**

```
ffffffff811aced0-ffffffff811acf11: ftrace_ops_test (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int ftrace_ops_test(struct ftrace_ops *ops, long unsigned int ip, void *regs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811ac580)
Location: kernel/trace/ftrace.c:1476
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_ops_list_func
```
**Symbols:**

```
ffffffff811ad970-ffffffff811ad9b1: ftrace_ops_test (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int ftrace_ops_test(struct ftrace_ops *ops, long unsigned int ip, void *regs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811d61fb)
Location: kernel/trace/ftrace.c:1477
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_ops_list_func
```
**Symbols:**

```
ffffffff811d76d0-ffffffff811d7733: ftrace_ops_test (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int ftrace_ops_test(struct ftrace_ops *ops, long unsigned int ip, void *regs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8120b51a)
Location: kernel/trace/ftrace.c:1471
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:arch_ftrace_ops_list_func
  - kernel/trace/ftrace.c:__ftrace_hash_rec_update
```
**Symbols:**

```
ffffffff8120cbd0-ffffffff8120cc54: ftrace_ops_test (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int ftrace_ops_test(struct ftrace_ops *ops, long unsigned int ip, void *regs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81253f3a)
Location: kernel/trace/ftrace.c:1477
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:arch_ftrace_ops_list_func
  - kernel/trace/ftrace.c:__ftrace_hash_rec_update
```
**Symbols:**

```
ffffffff812556f0-ffffffff81255774: ftrace_ops_test (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int ftrace_ops_test(struct ftrace_ops *ops, long unsigned int ip, void *regs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8126b52c)
Location: kernel/trace/ftrace.c:1508
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:arch_ftrace_ops_list_func
  - kernel/trace/ftrace.c:__ftrace_hash_rec_update
```
**Symbols:**

```
ffffffff8126ca70-ffffffff8126caf4: ftrace_ops_test (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int ftrace_ops_test(struct ftrace_ops *ops, long unsigned int ip, void *regs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff812859dc)
Location: kernel/trace/ftrace.c:1507
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:arch_ftrace_ops_list_func
  - kernel/trace/ftrace.c:__ftrace_hash_rec_update
```
**Symbols:**

```
ffffffff81287060-ffffffff812870e4: ftrace_ops_test (STB_GLOBAL)
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
int ftrace_ops_test(struct ftrace_ops *ops, long unsigned int ip, void *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffff800010211ce0)
Location: kernel/trace/ftrace.c:1484
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_ops_no_ops
```
**Symbols:**

```
ffff800010211ce0-ffff800010211d4c: ftrace_ops_test (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ftrace_ops_test(struct ftrace_ops *ops, long unsigned int ip, void *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (c045077c)
Location: kernel/trace/ftrace.c:1484
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_ops_list_func
```
**Symbols:**

```
c045077c-c0450810: ftrace_ops_test (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ftrace_ops_test(struct ftrace_ops *ops, long unsigned int ip, void *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (c0000000002919a0)
Location: kernel/trace/ftrace.c:1484
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_ops_list_func
```
**Symbols:**

```
c0000000002919a0-c000000000291a44: ftrace_ops_test (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ftrace_ops_test(struct ftrace_ops *ops, long unsigned int ip, void *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffe0001720b6)
Location: kernel/trace/ftrace.c:1484
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_ops_list_func
```
**Symbols:**

```
ffffffe0001720b6-ffffffe0001720fe: ftrace_ops_test (STB_GLOBAL)
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
int ftrace_ops_test(struct ftrace_ops *ops, long unsigned int ip, void *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811917a0)
Location: kernel/trace/ftrace.c:1484
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_ops_list_func
```
**Symbols:**

```
ffffffff811917a0-ffffffff811917e1: ftrace_ops_test (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ftrace_ops_test(struct ftrace_ops *ops, long unsigned int ip, void *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811848b0)
Location: kernel/trace/ftrace.c:1484
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_ops_list_func
```
**Symbols:**

```
ffffffff811848b0-ffffffff811848f1: ftrace_ops_test (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ftrace_ops_test(struct ftrace_ops *ops, long unsigned int ip, void *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8118f570)
Location: kernel/trace/ftrace.c:1484
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_ops_list_func
```
**Symbols:**

```
ffffffff8118f570-ffffffff8118f5b1: ftrace_ops_test (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ftrace_ops_test(struct ftrace_ops *ops, long unsigned int ip, void *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8119d120)
Location: kernel/trace/ftrace.c:1484
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_ops_list_func
```
**Symbols:**

```
ffffffff8119d120-ffffffff8119d161: ftrace_ops_test (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
