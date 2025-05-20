# Function: <code>wq_worker_comm</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void wq_worker_comm(char *buf, size_t size, struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810af2b0)
Location: kernel/workqueue.c:4606
Inline: False
Direct callers:
  - fs/proc/array.c:proc_task_name
```
**Symbols:**

```
ffffffff810af2b0-ffffffff810af373: wq_worker_comm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void wq_worker_comm(char *buf, size_t size, struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810b8420)
Location: kernel/workqueue.c:4629
Inline: False
Direct callers:
  - fs/proc/array.c:proc_task_name
```
**Symbols:**

```
ffffffff810b8420-ffffffff810b84e3: wq_worker_comm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void wq_worker_comm(char *buf, size_t size, struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810bdf20)
Location: kernel/workqueue.c:4774
Inline: False
Direct callers:
  - fs/proc/array.c:proc_task_name
```
**Symbols:**

```
ffffffff810bdf20-ffffffff810bdfe8: wq_worker_comm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void wq_worker_comm(char *buf, size_t size, struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810c44c0)
Location: kernel/workqueue.c:4808
Inline: False
Direct callers:
  - fs/proc/array.c:proc_task_name
```
**Symbols:**

```
ffffffff810c44c0-ffffffff810c4588: wq_worker_comm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void wq_worker_comm(char *buf, size_t size, struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810cc180)
Location: kernel/workqueue.c:4831
Inline: False
Direct callers:
  - fs/proc/array.c:proc_task_name
```
**Symbols:**

```
ffffffff810cc180-ffffffff810cc248: wq_worker_comm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void wq_worker_comm(char *buf, size_t size, struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (0)
Location: kernel/workqueue.c:4844
Inline: False
Direct callers:
  - fs/proc/array.c:proc_task_name
```
**Symbols:**

```
ffffffff81bdc124-ffffffff81bdc130: wq_worker_comm.cold (STB_LOCAL)
ffffffff810c72c0-ffffffff810c73b5: wq_worker_comm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void wq_worker_comm(char *buf, size_t size, struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (0)
Location: kernel/workqueue.c:4851
Inline: False
Direct callers:
  - fs/proc/array.c:proc_task_name
```
**Symbols:**

```
ffffffff81bce249-ffffffff81bce255: wq_worker_comm.cold (STB_LOCAL)
ffffffff810c8a50-ffffffff810c8b44: wq_worker_comm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void wq_worker_comm(char *buf, size_t size, struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (0)
Location: kernel/workqueue.c:4904
Inline: False
Direct callers:
  - fs/proc/array.c:proc_task_name
```
**Symbols:**

```
ffffffff81ca5467-ffffffff81ca5473: wq_worker_comm.cold (STB_LOCAL)
ffffffff810db620-ffffffff810db714: wq_worker_comm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void wq_worker_comm(char *buf, size_t size, struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (0)
Location: kernel/workqueue.c:4906
Inline: False
Direct callers:
  - fs/proc/array.c:proc_task_name
```
**Symbols:**

```
ffffffff81e54d3b-ffffffff81e54d47: wq_worker_comm.cold (STB_LOCAL)
ffffffff810f4ef0-ffffffff810f4fe9: wq_worker_comm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void wq_worker_comm(char *buf, size_t size, struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff811173d0)
Location: kernel/workqueue.c:4915
Inline: False
Direct callers:
  - fs/proc/array.c:proc_task_name
```
**Symbols:**

```
ffffffff811173d0-ffffffff811174d5: wq_worker_comm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void wq_worker_comm(char *buf, size_t size, struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff81124410)
Location: kernel/workqueue.c:5313
Inline: False
Direct callers:
  - fs/proc/array.c:proc_task_name
```
**Symbols:**

```
ffffffff81124410-ffffffff8112451b: wq_worker_comm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void wq_worker_comm(char *buf, size_t size, struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff8112eb10)
Location: kernel/workqueue.c:5336
Inline: False
Direct callers:
  - fs/proc/array.c:proc_task_name
```
**Symbols:**

```
ffffffff8112eb10-ffffffff8112ec1b: wq_worker_comm (STB_GLOBAL)
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
void wq_worker_comm(char *buf, size_t size, struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffff8000101227a8)
Location: kernel/workqueue.c:4808
Inline: False
Direct callers:
  - fs/proc/array.c:proc_task_name
```
**Symbols:**

```
ffff8000101227a8-ffff8000101228cc: wq_worker_comm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void wq_worker_comm(char *buf, size_t size, struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (c0376128)
Location: kernel/workqueue.c:4808
Inline: False
Direct callers:
  - fs/proc/array.c:proc_task_name
```
**Symbols:**

```
c0376128-c03761f8: wq_worker_comm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void wq_worker_comm(char *buf, size_t size, struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (c00000000016c300)
Location: kernel/workqueue.c:4808
Inline: False
Direct callers:
  - fs/proc/array.c:proc_task_name
```
**Symbols:**

```
c00000000016c300-c00000000016c490: wq_worker_comm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void wq_worker_comm(char *buf, size_t size, struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffe0000db16c)
Location: kernel/workqueue.c:4808
Inline: False
Direct callers:
  - fs/proc/array.c:proc_task_name
```
**Symbols:**

```
ffffffe0000db16c-ffffffe0000db280: wq_worker_comm (STB_GLOBAL)
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
void wq_worker_comm(char *buf, size_t size, struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810be830)
Location: kernel/workqueue.c:4808
Inline: False
Direct callers:
  - fs/proc/array.c:proc_task_name
```
**Symbols:**

```
ffffffff810be830-ffffffff810be8f8: wq_worker_comm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void wq_worker_comm(char *buf, size_t size, struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810ad060)
Location: kernel/workqueue.c:4808
Inline: False
Direct callers:
  - fs/proc/array.c:proc_task_name
```
**Symbols:**

```
ffffffff810ad060-ffffffff810ad122: wq_worker_comm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void wq_worker_comm(char *buf, size_t size, struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810bdd90)
Location: kernel/workqueue.c:4808
Inline: False
Direct callers:
  - fs/proc/array.c:proc_task_name
```
**Symbols:**

```
ffffffff810bdd90-ffffffff810bde58: wq_worker_comm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void wq_worker_comm(char *buf, size_t size, struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810c6110)
Location: kernel/workqueue.c:4808
Inline: False
Direct callers:
  - fs/proc/array.c:proc_task_name
```
**Symbols:**

```
ffffffff810c6110-ffffffff810c61cf: wq_worker_comm (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
