# Function: <code>psi_write</code>

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
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/psi.c (ffffffff810f7420)
Location: kernel/sched/psi.c:1190
Inline: True
Direct callers:
  - kernel/sched/psi.c:psi_cpu_write
  - kernel/sched/psi.c:psi_memory_write
  - kernel/sched/psi.c:psi_io_write
```
**Symbols:**

```
ffffffff810f7420-ffffffff810f7517: psi_write.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/psi.c (ffffffff811031b0)
Location: kernel/sched/psi.c:1191
Inline: True
Direct callers:
  - kernel/sched/psi.c:psi_cpu_write
  - kernel/sched/psi.c:psi_memory_write
  - kernel/sched/psi.c:psi_io_write
```
**Symbols:**

```
ffffffff811031b0-ffffffff811032b8: psi_write.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
ssize_t psi_write(struct file *file, const char *user_buf, size_t nbytes, enum psi_res res);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (ffffffff8110ddd0)
Location: kernel/sched/psi.c:1240
Inline: True
Direct callers:
  - kernel/sched/psi.c:psi_cpu_write
  - kernel/sched/psi.c:psi_memory_write
  - kernel/sched/psi.c:psi_io_write
```
**Symbols:**

```
ffffffff8110ddd0-ffffffff8110dee1: psi_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
ssize_t psi_write(struct file *file, const char *user_buf, size_t nbytes, enum psi_res res);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (ffffffff8110b120)
Location: kernel/sched/psi.c:1252
Inline: True
Direct callers:
  - kernel/sched/psi.c:psi_cpu_write
  - kernel/sched/psi.c:psi_memory_write
  - kernel/sched/psi.c:psi_io_write
```
**Symbols:**

```
ffffffff8110b120-ffffffff8110b231: psi_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
ssize_t psi_write(struct file *file, const char *user_buf, size_t nbytes, enum psi_res res);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (ffffffff8110cea0)
Location: kernel/sched/psi.c:1284
Inline: True
Direct callers:
  - kernel/sched/psi.c:psi_cpu_write
  - kernel/sched/psi.c:psi_memory_write
  - kernel/sched/psi.c:psi_io_write
```
**Symbols:**

```
ffffffff8110cea0-ffffffff8110cfb0: psi_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
ssize_t psi_write(struct file *file, const char *user_buf, size_t nbytes, enum psi_res res);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (ffffffff8112b410)
Location: kernel/sched/psi.c:1282
Inline: True
Direct callers:
  - kernel/sched/psi.c:psi_cpu_write
  - kernel/sched/psi.c:psi_memory_write
  - kernel/sched/psi.c:psi_io_write
```
**Symbols:**

```
ffffffff8112b410-ffffffff8112b567: psi_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
ssize_t psi_write(struct file *file, const char *user_buf, size_t nbytes, enum psi_res res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8114ca20)
Location: kernel/sched/psi.c:1285
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:psi_cpu_write
  - kernel/sched/build_utility.c:psi_memory_write
  - kernel/sched/build_utility.c:psi_io_write
```
**Symbols:**

```
ffffffff8114ca20-ffffffff8114cb9e: psi_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ssize_t psi_write(struct file *file, const char *user_buf, size_t nbytes, enum psi_res res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8117b770)
Location: kernel/sched/psi.c:1461
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:psi_cpu_write
  - kernel/sched/build_utility.c:psi_memory_write
  - kernel/sched/build_utility.c:psi_io_write
```
**Symbols:**

```
ffffffff8117b770-ffffffff8117b8eb: psi_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ssize_t psi_write(struct file *file, const char *user_buf, size_t nbytes, enum psi_res res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8118c380)
Location: kernel/sched/psi.c:1520
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:psi_cpu_write
  - kernel/sched/build_utility.c:psi_memory_write
  - kernel/sched/build_utility.c:psi_io_write
```
**Symbols:**

```
ffffffff8118c380-ffffffff8118c504: psi_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ssize_t psi_write(struct file *file, const char *user_buf, size_t nbytes, enum psi_res res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8119ad10)
Location: kernel/sched/psi.c:1512
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:psi_cpu_write
  - kernel/sched/build_utility.c:psi_memory_write
  - kernel/sched/build_utility.c:psi_io_write
```
**Symbols:**

```
ffffffff8119ad10-ffffffff8119ae94: psi_write (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/psi.c (ffff800010168090)
Location: kernel/sched/psi.c:1191
Inline: True
Direct callers:
  - kernel/sched/psi.c:psi_cpu_write
  - kernel/sched/psi.c:psi_memory_write
  - kernel/sched/psi.c:psi_io_write
```
**Symbols:**

```
ffff800010168090-ffff8000101682bc: psi_write.isra.0.part.0 (STB_LOCAL)
ffff8000101682c0-ffff800010168324: psi_write.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/psi.c (c03b4a54)
Location: kernel/sched/psi.c:1191
Inline: True
```
**Symbols:**

```
c03b4a54-c03b4ba0: psi_write.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
ssize_t psi_write(struct file *file, const char *user_buf, size_t nbytes, enum psi_res res);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (c0000000001c0010)
Location: kernel/sched/psi.c:1191
Inline: True
Direct callers:
  - kernel/sched/psi.c:psi_cpu_write
  - kernel/sched/psi.c:psi_memory_write
  - kernel/sched/psi.c:psi_io_write
```
**Symbols:**

```
c0000000001c0010-c0000000001c018c: psi_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/psi.c (ffffffe00010a1cc)
Location: kernel/sched/psi.c:1191
Inline: True
```
**Symbols:**

```
ffffffe00010a1cc-ffffffe00010a29c: psi_write.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/psi.c (ffffffff810fc4c0)
Location: kernel/sched/psi.c:1191
Inline: True
Direct callers:
  - kernel/sched/psi.c:psi_cpu_write
  - kernel/sched/psi.c:psi_memory_write
  - kernel/sched/psi.c:psi_io_write
```
**Symbols:**

```
ffffffff810fc4c0-ffffffff810fc5c8: psi_write.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/psi.c (ffffffff810ec6d0)
Location: kernel/sched/psi.c:1191
Inline: True
Direct callers:
  - kernel/sched/psi.c:psi_cpu_write
  - kernel/sched/psi.c:psi_memory_write
  - kernel/sched/psi.c:psi_io_write
```
**Symbols:**

```
ffffffff810ec6d0-ffffffff810ec7d8: psi_write.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/psi.c (ffffffff810f9680)
Location: kernel/sched/psi.c:1191
Inline: True
Direct callers:
  - kernel/sched/psi.c:psi_cpu_write
  - kernel/sched/psi.c:psi_memory_write
  - kernel/sched/psi.c:psi_io_write
```
**Symbols:**

```
ffffffff810f9680-ffffffff810f9788: psi_write.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/psi.c (ffffffff811047c0)
Location: kernel/sched/psi.c:1191
Inline: True
Direct callers:
  - kernel/sched/psi.c:psi_cpu_write
  - kernel/sched/psi.c:psi_memory_write
  - kernel/sched/psi.c:psi_io_write
```
**Symbols:**

```
ffffffff811047c0-ffffffff811048c8: psi_write.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
