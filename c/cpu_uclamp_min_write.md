# Function: <code>cpu_uclamp_min_write</code>

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
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
ssize_t cpu_uclamp_min_write(struct kernfs_open_file *of, char *buf, size_t nbytes, loff_t off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d56c0)
Location: kernel/sched/core.c:7311
Inline: False
```
**Symbols:**

```
ffffffff810d56c0-ffffffff810d56d2: cpu_uclamp_min_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
ssize_t cpu_uclamp_min_write(struct kernfs_open_file *of, char *buf, size_t nbytes, loff_t off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810dfc70)
Location: kernel/sched/core.c:7547
Inline: False
```
**Symbols:**

```
ffffffff810dfc70-ffffffff810dfc82: cpu_uclamp_min_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
ssize_t cpu_uclamp_min_write(struct kernfs_open_file *of, char *buf, size_t nbytes, loff_t off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810dcf60)
Location: kernel/sched/core.c:8512
Inline: False
```
**Symbols:**

```
ffffffff810dcf60-ffffffff810dcf72: cpu_uclamp_min_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
ssize_t cpu_uclamp_min_write(struct kernfs_open_file *of, char *buf, size_t nbytes, loff_t off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810deb30)
Location: kernel/sched/core.c:8888
Inline: False
```
**Symbols:**

```
ffffffff810deb30-ffffffff810deb42: cpu_uclamp_min_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
ssize_t cpu_uclamp_min_write(struct kernfs_open_file *of, char *buf, size_t nbytes, loff_t off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810f3a60)
Location: kernel/sched/core.c:10126
Inline: False
```
**Symbols:**

```
ffffffff810f3a60-ffffffff810f3a72: cpu_uclamp_min_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
ssize_t cpu_uclamp_min_write(struct kernfs_open_file *of, char *buf, size_t nbytes, loff_t off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff8110fad0)
Location: kernel/sched/core.c:10449
Inline: False
```
**Symbols:**

```
ffffffff8110fad0-ffffffff8110faee: cpu_uclamp_min_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ssize_t cpu_uclamp_min_write(struct kernfs_open_file *of, char *buf, size_t nbytes, loff_t off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81136960)
Location: kernel/sched/core.c:10595
Inline: False
```
**Symbols:**

```
ffffffff81136960-ffffffff8113697e: cpu_uclamp_min_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ssize_t cpu_uclamp_min_write(struct kernfs_open_file *of, char *buf, size_t nbytes, loff_t off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff811459a0)
Location: kernel/sched/core.c:10755
Inline: False
```
**Symbols:**

```
ffffffff811459a0-ffffffff811459be: cpu_uclamp_min_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ssize_t cpu_uclamp_min_write(struct kernfs_open_file *of, char *buf, size_t nbytes, loff_t off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81150ec0)
Location: kernel/sched/core.c:10712
Inline: False
```
**Symbols:**

```
ffffffff81150ec0-ffffffff81150ede: cpu_uclamp_min_write (STB_LOCAL)
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
ssize_t cpu_uclamp_min_write(struct kernfs_open_file *of, char *buf, size_t nbytes, loff_t off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffff8000101361d8)
Location: kernel/sched/core.c:7311
Inline: False
```
**Symbols:**

```
ffff8000101361d8-ffff800010136220: cpu_uclamp_min_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
ssize_t cpu_uclamp_min_write(struct kernfs_open_file *of, char *buf, size_t nbytes, loff_t off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (c038512c)
Location: kernel/sched/core.c:7311
Inline: False
```
**Symbols:**

```
c038512c-c038514c: cpu_uclamp_min_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
ssize_t cpu_uclamp_min_write(struct kernfs_open_file *of, char *buf, size_t nbytes, loff_t off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (c000000000181310)
Location: kernel/sched/core.c:7311
Inline: False
```
**Symbols:**

```
c000000000181310-c000000000181328: cpu_uclamp_min_write (STB_LOCAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
ssize_t cpu_uclamp_min_write(struct kernfs_open_file *of, char *buf, size_t nbytes, loff_t off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810cf9c0)
Location: kernel/sched/core.c:7311
Inline: False
```
**Symbols:**

```
ffffffff810cf9c0-ffffffff810cf9d2: cpu_uclamp_min_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
ssize_t cpu_uclamp_min_write(struct kernfs_open_file *of, char *buf, size_t nbytes, loff_t off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810be280)
Location: kernel/sched/core.c:7311
Inline: False
```
**Symbols:**

```
ffffffff810be280-ffffffff810be292: cpu_uclamp_min_write (STB_LOCAL)
```
</details>
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
ssize_t cpu_uclamp_min_write(struct kernfs_open_file *of, char *buf, size_t nbytes, loff_t off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d7520)
Location: kernel/sched/core.c:7311
Inline: False
```
**Symbols:**

```
ffffffff810d7520-ffffffff810d7532: cpu_uclamp_min_write (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
