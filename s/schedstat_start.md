# Function: <code>schedstat_start</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void *schedstat_start(struct seq_file *file, loff_t *offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/stats.c (ffffffff810c53c0)
Location: kernel/sched/stats.c:83
Inline: False
Direct callers:
  - kernel/sched/stats.c:schedstat_next
```
**Symbols:**

```
ffffffff810c53c0-ffffffff810c542d: schedstat_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void *schedstat_start(struct seq_file *file, loff_t *offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/stats.c (ffffffff810c9060)
Location: kernel/sched/stats.c:83
Inline: False
Direct callers:
  - kernel/sched/stats.c:schedstat_next
```
**Symbols:**

```
ffffffff810c9060-ffffffff810c90cd: schedstat_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void *schedstat_start(struct seq_file *file, loff_t *offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/stats.c (ffffffff810cf070)
Location: kernel/sched/stats.c:83
Inline: False
Direct callers:
  - kernel/sched/stats.c:schedstat_next
```
**Symbols:**

```
ffffffff810cf070-ffffffff810cf0e1: schedstat_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void *schedstat_start(struct seq_file *file, loff_t *offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/stats.c (ffffffff810ce270)
Location: kernel/sched/stats.c:83
Inline: False
Direct callers:
  - kernel/sched/stats.c:schedstat_next
```
**Symbols:**

```
ffffffff810ce270-ffffffff810ce2d9: schedstat_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void *schedstat_start(struct seq_file *file, loff_t *offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/stats.c (ffffffff810d5b50)
Location: kernel/sched/stats.c:84
Inline: False
Direct callers:
  - kernel/sched/stats.c:schedstat_next
```
**Symbols:**

```
ffffffff810d5b50-ffffffff810d5bb8: schedstat_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void *schedstat_start(struct seq_file *file, loff_t *offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/stats.c (ffffffff810ddb00)
Location: kernel/sched/stats.c:83
Inline: False
Direct callers:
  - kernel/sched/stats.c:schedstat_next
```
**Symbols:**

```
ffffffff810ddb00-ffffffff810ddb68: schedstat_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void *schedstat_start(struct seq_file *file, loff_t *offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/stats.c (ffffffff810e8270)
Location: kernel/sched/stats.c:83
Inline: False
Direct callers:
  - kernel/sched/stats.c:schedstat_next
```
**Symbols:**

```
ffffffff810e8270-ffffffff810e82d8: schedstat_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void *schedstat_start(struct seq_file *file, loff_t *offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/stats.c (ffffffff810ef1f0)
Location: kernel/sched/stats.c:83
Inline: False
Direct callers:
  - kernel/sched/stats.c:schedstat_next
```
**Symbols:**

```
ffffffff810ef1f0-ffffffff810ef258: schedstat_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void *schedstat_start(struct seq_file *file, loff_t *offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/stats.c (ffffffff810faea0)
Location: kernel/sched/stats.c:83
Inline: False
Direct callers:
  - kernel/sched/stats.c:schedstat_next
```
**Symbols:**

```
ffffffff810faea0-ffffffff810faf08: schedstat_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void *schedstat_start(struct seq_file *file, loff_t *offset);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/stats.c (ffffffff8110547c)
Location: kernel/sched/stats.c:83
Inline: True
Inline callers:
  - kernel/sched/stats.c:schedstat_next
```
**Symbols:**

```
ffffffff811053f0-ffffffff8110545b: schedstat_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void *schedstat_start(struct seq_file *file, loff_t *offset);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/stats.c (ffffffff81103aec)
Location: kernel/sched/stats.c:83
Inline: True
Inline callers:
  - kernel/sched/stats.c:schedstat_next
```
**Symbols:**

```
ffffffff81103a60-ffffffff81103acb: schedstat_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void *schedstat_start(struct seq_file *file, loff_t *offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/stats.c (ffffffff81105d50)
Location: kernel/sched/stats.c:83
Inline: False
Direct callers:
  - kernel/sched/stats.c:schedstat_next
```
**Symbols:**

```
ffffffff81105d50-ffffffff81105dbb: schedstat_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void *schedstat_start(struct seq_file *file, loff_t *offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/stats.c (ffffffff81123c20)
Location: kernel/sched/stats.c:83
Inline: False
Direct callers:
  - kernel/sched/stats.c:schedstat_next
```
**Symbols:**

```
ffffffff81123c20-ffffffff81123c8b: schedstat_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void *schedstat_start(struct seq_file *file, loff_t *offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (0)
Location: kernel/sched/stats.c:186
Inline: False
```
**Symbols:**

```
ffffffff811425f0-ffffffff811425ff: schedstat_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void *schedstat_start(struct seq_file *file, loff_t *offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (0)
Location: kernel/sched/stats.c:186
Inline: False
```
**Symbols:**

```
ffffffff81170340-ffffffff8117034f: schedstat_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void *schedstat_start(struct seq_file *file, loff_t *offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (0)
Location: kernel/sched/stats.c:186
Inline: False
```
**Symbols:**

```
ffffffff8117fd90-ffffffff8117fd9f: schedstat_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void *schedstat_start(struct seq_file *file, loff_t *offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (0)
Location: kernel/sched/stats.c:186
Inline: False
```
**Symbols:**

```
ffffffff8118d730-ffffffff8118d7b3: schedstat_start (STB_LOCAL)
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
void *schedstat_start(struct seq_file *file, loff_t *offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/stats.c (ffff80001015f970)
Location: kernel/sched/stats.c:83
Inline: False
Direct callers:
  - kernel/sched/stats.c:schedstat_next
```
**Symbols:**

```
ffff80001015f970-ffff80001015f9f4: schedstat_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void *schedstat_start(struct seq_file *file, loff_t *offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/stats.c (c03ac170)
Location: kernel/sched/stats.c:83
Inline: False
Direct callers:
  - kernel/sched/stats.c:schedstat_next
```
**Symbols:**

```
c03ac170-c03ac1fc: schedstat_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void *schedstat_start(struct seq_file *file, loff_t *offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/stats.c (c0000000001b4fa0)
Location: kernel/sched/stats.c:83
Inline: False
Direct callers:
  - kernel/sched/stats.c:schedstat_next
```
**Symbols:**

```
c0000000001b4fa0-c0000000001b5050: schedstat_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void *schedstat_start(struct seq_file *file, loff_t *offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/stats.c (ffffffe000103b1a)
Location: kernel/sched/stats.c:83
Inline: False
Direct callers:
  - kernel/sched/stats.c:schedstat_next
```
**Symbols:**

```
ffffffe000103b1a-ffffffe000103b92: schedstat_start (STB_LOCAL)
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
void *schedstat_start(struct seq_file *file, loff_t *offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/stats.c (ffffffff810f41d0)
Location: kernel/sched/stats.c:83
Inline: False
Direct callers:
  - kernel/sched/stats.c:schedstat_next
```
**Symbols:**

```
ffffffff810f41d0-ffffffff810f4238: schedstat_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void *schedstat_start(struct seq_file *file, loff_t *offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/stats.c (ffffffff810e43b0)
Location: kernel/sched/stats.c:83
Inline: False
Direct callers:
  - kernel/sched/stats.c:schedstat_next
```
**Symbols:**

```
ffffffff810e43b0-ffffffff810e4418: schedstat_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void *schedstat_start(struct seq_file *file, loff_t *offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/stats.c (ffffffff810f13d0)
Location: kernel/sched/stats.c:83
Inline: False
Direct callers:
  - kernel/sched/stats.c:schedstat_next
```
**Symbols:**

```
ffffffff810f13d0-ffffffff810f1438: schedstat_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void *schedstat_start(struct seq_file *file, loff_t *offset);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/stats.c (ffffffff810fc3c0)
Location: kernel/sched/stats.c:83
Inline: False
Direct callers:
  - kernel/sched/stats.c:schedstat_next
```
**Symbols:**

```
ffffffff810fc3c0-ffffffff810fc428: schedstat_start (STB_LOCAL)
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
