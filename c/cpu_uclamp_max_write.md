# Function: <code>cpu_uclamp_max_write</code>

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
ssize_t cpu_uclamp_max_write(struct kernfs_open_file *of, char *buf, size_t nbytes, loff_t off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d56a0)
Location: kernel/sched/core.c:7318
Inline: False
```
**Symbols:**

```
ffffffff810d56a0-ffffffff810d56b5: cpu_uclamp_max_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
ssize_t cpu_uclamp_max_write(struct kernfs_open_file *of, char *buf, size_t nbytes, loff_t off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810dfc90)
Location: kernel/sched/core.c:7554
Inline: False
```
**Symbols:**

```
ffffffff810dfc90-ffffffff810dfca5: cpu_uclamp_max_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
ssize_t cpu_uclamp_max_write(struct kernfs_open_file *of, char *buf, size_t nbytes, loff_t off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810dcf80)
Location: kernel/sched/core.c:8519
Inline: False
```
**Symbols:**

```
ffffffff810dcf80-ffffffff810dcf95: cpu_uclamp_max_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
ssize_t cpu_uclamp_max_write(struct kernfs_open_file *of, char *buf, size_t nbytes, loff_t off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810deb50)
Location: kernel/sched/core.c:8895
Inline: False
```
**Symbols:**

```
ffffffff810deb50-ffffffff810deb65: cpu_uclamp_max_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
ssize_t cpu_uclamp_max_write(struct kernfs_open_file *of, char *buf, size_t nbytes, loff_t off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810f3a80)
Location: kernel/sched/core.c:10133
Inline: False
```
**Symbols:**

```
ffffffff810f3a80-ffffffff810f3a95: cpu_uclamp_max_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
ssize_t cpu_uclamp_max_write(struct kernfs_open_file *of, char *buf, size_t nbytes, loff_t off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff8110faf0)
Location: kernel/sched/core.c:10456
Inline: False
```
**Symbols:**

```
ffffffff8110faf0-ffffffff8110fb11: cpu_uclamp_max_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ssize_t cpu_uclamp_max_write(struct kernfs_open_file *of, char *buf, size_t nbytes, loff_t off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81136990)
Location: kernel/sched/core.c:10602
Inline: False
```
**Symbols:**

```
ffffffff81136990-ffffffff811369b1: cpu_uclamp_max_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ssize_t cpu_uclamp_max_write(struct kernfs_open_file *of, char *buf, size_t nbytes, loff_t off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff811459d0)
Location: kernel/sched/core.c:10762
Inline: False
```
**Symbols:**

```
ffffffff811459d0-ffffffff811459f1: cpu_uclamp_max_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ssize_t cpu_uclamp_max_write(struct kernfs_open_file *of, char *buf, size_t nbytes, loff_t off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81150ef0)
Location: kernel/sched/core.c:10719
Inline: False
```
**Symbols:**

```
ffffffff81150ef0-ffffffff81150f11: cpu_uclamp_max_write (STB_LOCAL)
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
ssize_t cpu_uclamp_max_write(struct kernfs_open_file *of, char *buf, size_t nbytes, loff_t off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffff800010136190)
Location: kernel/sched/core.c:7318
Inline: False
```
**Symbols:**

```
ffff800010136190-ffff8000101361d8: cpu_uclamp_max_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
ssize_t cpu_uclamp_max_write(struct kernfs_open_file *of, char *buf, size_t nbytes, loff_t off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (c038514c)
Location: kernel/sched/core.c:7318
Inline: False
```
**Symbols:**

```
c038514c-c038516c: cpu_uclamp_max_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
ssize_t cpu_uclamp_max_write(struct kernfs_open_file *of, char *buf, size_t nbytes, loff_t off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (c0000000001812f0)
Location: kernel/sched/core.c:7318
Inline: False
```
**Symbols:**

```
c0000000001812f0-c000000000181308: cpu_uclamp_max_write (STB_LOCAL)
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
ssize_t cpu_uclamp_max_write(struct kernfs_open_file *of, char *buf, size_t nbytes, loff_t off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810cf9a0)
Location: kernel/sched/core.c:7318
Inline: False
```
**Symbols:**

```
ffffffff810cf9a0-ffffffff810cf9b5: cpu_uclamp_max_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
ssize_t cpu_uclamp_max_write(struct kernfs_open_file *of, char *buf, size_t nbytes, loff_t off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810be260)
Location: kernel/sched/core.c:7318
Inline: False
```
**Symbols:**

```
ffffffff810be260-ffffffff810be275: cpu_uclamp_max_write (STB_LOCAL)
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
ssize_t cpu_uclamp_max_write(struct kernfs_open_file *of, char *buf, size_t nbytes, loff_t off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d7500)
Location: kernel/sched/core.c:7318
Inline: False
```
**Symbols:**

```
ffffffff810d7500-ffffffff810d7515: cpu_uclamp_max_write (STB_LOCAL)
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
