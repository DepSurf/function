# Function: <code>sched_debug_header</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void sched_debug_header(struct seq_file *m);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/debug.c (ffffffff810c5460)
Location: kernel/sched/debug.c:347
Inline: False
Direct callers:
  - kernel/sched/debug.c:sched_debug_show
  - kernel/sched/debug.c:sysrq_sched_debug_show
```
**Symbols:**

```
ffffffff810c5460-ffffffff810c59f6: sched_debug_header (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void sched_debug_header(struct seq_file *m);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/debug.c (ffffffff810c93a0)
Location: kernel/sched/debug.c:658
Inline: False
Direct callers:
  - kernel/sched/debug.c:sysrq_sched_debug_show
  - kernel/sched/debug.c:sched_debug_show
```
**Symbols:**

```
ffffffff810c93a0-ffffffff810c993d: sched_debug_header (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void sched_debug_header(struct seq_file *m);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/debug.c (ffffffff810cf3c0)
Location: kernel/sched/debug.c:661
Inline: False
Direct callers:
  - kernel/sched/debug.c:sysrq_sched_debug_show
  - kernel/sched/debug.c:sched_debug_show
```
**Symbols:**

```
ffffffff810cf3c0-ffffffff810cf95d: sched_debug_header (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void sched_debug_header(struct seq_file *m);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/debug.c (ffffffff810ce430)
Location: kernel/sched/debug.c:675
Inline: False
Direct callers:
  - kernel/sched/debug.c:sysrq_sched_debug_show
  - kernel/sched/debug.c:sched_debug_show
```
**Symbols:**

```
ffffffff810ce430-ffffffff810ce9cd: sched_debug_header (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void sched_debug_header(struct seq_file *m);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/debug.c (ffffffff810d5d10)
Location: kernel/sched/debug.c:725
Inline: False
Direct callers:
  - kernel/sched/debug.c:sysrq_sched_debug_show
  - kernel/sched/debug.c:sched_debug_show
```
**Symbols:**

```
ffffffff810d5d10-ffffffff810d62ad: sched_debug_header (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void sched_debug_header(struct seq_file *m);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/debug.c (0)
Location: kernel/sched/debug.c:706
Inline: False
Direct callers:
  - kernel/sched/debug.c:sysrq_sched_debug_show
  - kernel/sched/debug.c:sched_debug_show
```
**Symbols:**

```
ffffffff810dde20-ffffffff810de1a2: sched_debug_header (STB_LOCAL)
ffffffff810e11ff-ffffffff810e141a: sched_debug_header.cold.9 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void sched_debug_header(struct seq_file *m);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/debug.c (0)
Location: kernel/sched/debug.c:705
Inline: False
Direct callers:
  - kernel/sched/debug.c:sysrq_sched_debug_show
  - kernel/sched/debug.c:sched_debug_show
```
**Symbols:**

```
ffffffff810e85a0-ffffffff810e8922: sched_debug_header (STB_LOCAL)
ffffffff810eb94f-ffffffff810ebb6a: sched_debug_header.cold.10 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void sched_debug_header(struct seq_file *m);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/debug.c (0)
Location: kernel/sched/debug.c:685
Inline: False
Direct callers:
  - kernel/sched/debug.c:sysrq_sched_debug_show
  - kernel/sched/debug.c:sched_debug_show
```
**Symbols:**

```
ffffffff810ef390-ffffffff810ef713: sched_debug_header (STB_LOCAL)
ffffffff810f276c-ffffffff810f2994: sched_debug_header.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void sched_debug_header(struct seq_file *m);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/debug.c (0)
Location: kernel/sched/debug.c:685
Inline: False
Direct callers:
  - kernel/sched/debug.c:sysrq_sched_debug_show
  - kernel/sched/debug.c:sched_debug_show
```
**Symbols:**

```
ffffffff810fb1d0-ffffffff810fb553: sched_debug_header (STB_LOCAL)
ffffffff810fe42c-ffffffff810fe654: sched_debug_header.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void sched_debug_header(struct seq_file *m);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/debug.c (0)
Location: kernel/sched/debug.c:682
Inline: False
Direct callers:
  - kernel/sched/debug.c:sysrq_sched_debug_show
  - kernel/sched/debug.c:sched_debug_show
```
**Symbols:**

```
ffffffff81105600-ffffffff81105983: sched_debug_header (STB_LOCAL)
ffffffff81108afc-ffffffff81108d24: sched_debug_header.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void sched_debug_header(struct seq_file *m);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/debug.c (0)
Location: kernel/sched/debug.c:736
Inline: False
Direct callers:
  - kernel/sched/debug.c:sysrq_sched_debug_show
  - kernel/sched/debug.c:sched_debug_show
```
**Symbols:**

```
ffffffff81103cc0-ffffffff81104043: sched_debug_header (STB_LOCAL)
ffffffff81bdcee0-ffffffff81bdd108: sched_debug_header.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void sched_debug_header(struct seq_file *m);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/debug.c (0)
Location: kernel/sched/debug.c:758
Inline: False
Direct callers:
  - kernel/sched/debug.c:sysrq_sched_debug_show
  - kernel/sched/debug.c:sched_debug_show
```
**Symbols:**

```
ffffffff81105e30-ffffffff811061c1: sched_debug_header (STB_LOCAL)
ffffffff81bcf04c-ffffffff81bcf26e: sched_debug_header.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void sched_debug_header(struct seq_file *m);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/debug.c (0)
Location: kernel/sched/debug.c:774
Inline: False
Direct callers:
  - kernel/sched/debug.c:sysrq_sched_debug_show
  - kernel/sched/debug.c:sched_debug_show
```
**Symbols:**

```
ffffffff81124ac0-ffffffff81124e7c: sched_debug_header (STB_LOCAL)
ffffffff81ca7ce8-ffffffff81ca7f23: sched_debug_header.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void sched_debug_header(struct seq_file *m);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/build_utility.c (0)
Location: kernel/sched/debug.c:782
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:sysrq_sched_debug_show
  - kernel/sched/build_utility.c:sched_debug_show
```
**Symbols:**

```
ffffffff81144eb0-ffffffff8114529f: sched_debug_header (STB_LOCAL)
ffffffff81e57f3a-ffffffff81e5818e: sched_debug_header.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void sched_debug_header(struct seq_file *m);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff81171870)
Location: kernel/sched/debug.c:783
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:sysrq_sched_debug_show
  - kernel/sched/build_utility.c:sched_debug_show
```
**Symbols:**

```
ffffffff81171870-ffffffff81171f87: sched_debug_header (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void sched_debug_header(struct seq_file *m);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff81182c70)
Location: kernel/sched/debug.c:829
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:sysrq_sched_debug_show
  - kernel/sched/build_utility.c:sched_debug_show
```
**Symbols:**

```
ffffffff81182c70-ffffffff8118339e: sched_debug_header (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void sched_debug_header(struct seq_file *m);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff81191510)
Location: kernel/sched/debug.c:830
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:sysrq_sched_debug_show
  - kernel/sched/build_utility.c:sched_debug_show
```
**Symbols:**

```
ffffffff81191510-ffffffff81191ae0: sched_debug_header (STB_LOCAL)
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
void sched_debug_header(struct seq_file *m);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/debug.c (ffff800010160e50)
Location: kernel/sched/debug.c:685
Inline: False
Direct callers:
  - kernel/sched/debug.c:sysrq_sched_debug_show
  - kernel/sched/debug.c:sched_debug_show
```
**Symbols:**

```
ffff800010160e50-ffff800010161354: sched_debug_header (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void sched_debug_header(struct seq_file *m);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/debug.c (c03ad524)
Location: kernel/sched/debug.c:685
Inline: False
Direct callers:
  - kernel/sched/debug.c:sysrq_sched_debug_show
  - kernel/sched/debug.c:sched_debug_show
```
**Symbols:**

```
c03ad524-c03adb28: sched_debug_header (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void sched_debug_header(struct seq_file *m);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/debug.c (c0000000001b6010)
Location: kernel/sched/debug.c:685
Inline: False
Direct callers:
  - kernel/sched/debug.c:sysrq_sched_debug_show
  - kernel/sched/debug.c:sched_debug_show
```
**Symbols:**

```
c0000000001b6010-c0000000001b671c: sched_debug_header (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void sched_debug_header(struct seq_file *m);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/debug.c (ffffffe00010456a)
Location: kernel/sched/debug.c:685
Inline: False
Direct callers:
  - kernel/sched/debug.c:sysrq_sched_debug_show
  - kernel/sched/debug.c:sched_debug_show
```
**Symbols:**

```
ffffffe00010456a-ffffffe000104a46: sched_debug_header (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void sched_debug_header(struct seq_file *m);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/debug.c (0)
Location: kernel/sched/debug.c:685
Inline: False
Direct callers:
  - kernel/sched/debug.c:sysrq_sched_debug_show
  - kernel/sched/debug.c:sched_debug_show
```
**Symbols:**

```
ffffffff810f4500-ffffffff810f4883: sched_debug_header (STB_LOCAL)
ffffffff810f774c-ffffffff810f7974: sched_debug_header.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void sched_debug_header(struct seq_file *m);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/debug.c (0)
Location: kernel/sched/debug.c:685
Inline: False
Direct callers:
  - kernel/sched/debug.c:sysrq_sched_debug_show
  - kernel/sched/debug.c:sched_debug_show
```
**Symbols:**

```
ffffffff810e46e0-ffffffff810e4a4f: sched_debug_header (STB_LOCAL)
ffffffff810e791c-ffffffff810e7b44: sched_debug_header.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void sched_debug_header(struct seq_file *m);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/debug.c (0)
Location: kernel/sched/debug.c:685
Inline: False
Direct callers:
  - kernel/sched/debug.c:sysrq_sched_debug_show
  - kernel/sched/debug.c:sched_debug_show
```
**Symbols:**

```
ffffffff810f1700-ffffffff810f1a83: sched_debug_header (STB_LOCAL)
ffffffff810f495c-ffffffff810f4b84: sched_debug_header.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void sched_debug_header(struct seq_file *m);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/debug.c (0)
Location: kernel/sched/debug.c:685
Inline: False
Direct callers:
  - kernel/sched/debug.c:sysrq_sched_debug_show
  - kernel/sched/debug.c:sched_debug_show
```
**Symbols:**

```
ffffffff810fc6f0-ffffffff810fca73: sched_debug_header (STB_LOCAL)
ffffffff810ff95c-ffffffff810ffb84: sched_debug_header.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
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
