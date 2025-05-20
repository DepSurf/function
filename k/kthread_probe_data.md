# Function: <code>kthread_probe_data</code>

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
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void *kthread_probe_data(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810a9b20)
Location: kernel/kthread.c:158
Inline: False
Direct callers:
  - kernel/workqueue.c:print_worker_info
```
**Symbols:**

```
ffffffff810a9b20-ffffffff810a9b99: kthread_probe_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void *kthread_probe_data(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810a6770)
Location: kernel/kthread.c:161
Inline: False
Direct callers:
  - kernel/workqueue.c:print_worker_info
```
**Symbols:**

```
ffffffff810a6770-ffffffff810a67d1: kthread_probe_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void *kthread_probe_data(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810acee0)
Location: kernel/kthread.c:169
Inline: False
Direct callers:
  - kernel/workqueue.c:print_worker_info
```
**Symbols:**

```
ffffffff810acee0-ffffffff810acf41: kthread_probe_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void *kthread_probe_data(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810b3c50)
Location: kernel/kthread.c:168
Inline: False
Direct callers:
  - kernel/workqueue.c:print_worker_info
```
**Symbols:**

```
ffffffff810b3c50-ffffffff810b3cb1: kthread_probe_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void *kthread_probe_data(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810bcda0)
Location: kernel/kthread.c:168
Inline: False
Direct callers:
  - kernel/workqueue.c:print_worker_info
```
**Symbols:**

```
ffffffff810bcda0-ffffffff810bce01: kthread_probe_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void *kthread_probe_data(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/kthread.c (0)
Location: kernel/kthread.c:177
Inline: False
Direct callers:
  - kernel/workqueue.c:print_worker_info
```
**Symbols:**

```
ffffffff810c33b5-ffffffff810c33c8: kthread_probe_data.cold (STB_LOCAL)
ffffffff810c2c70-ffffffff810c2cda: kthread_probe_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void *kthread_probe_data(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810c9240)
Location: kernel/kthread.c:177
Inline: False
Direct callers:
  - kernel/workqueue.c:print_worker_info
```
**Symbols:**

```
ffffffff810c9240-ffffffff810c92a1: kthread_probe_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void *kthread_probe_data(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810d1630)
Location: kernel/kthread.c:199
Inline: False
Direct callers:
  - kernel/workqueue.c:print_worker_info
```
**Symbols:**

```
ffffffff810d1630-ffffffff810d1691: kthread_probe_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void *kthread_probe_data(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810cc060)
Location: kernel/kthread.c:200
Inline: False
Direct callers:
  - kernel/workqueue.c:print_worker_info
```
**Symbols:**

```
ffffffff810cc060-ffffffff810cc0c1: kthread_probe_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void *kthread_probe_data(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810cdb40)
Location: kernel/kthread.c:226
Inline: False
Direct callers:
  - kernel/workqueue.c:print_worker_info
```
**Symbols:**

```
ffffffff810cdb40-ffffffff810cdba4: kthread_probe_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void *kthread_probe_data(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810e0d20)
Location: kernel/kthread.c:226
Inline: False
Direct callers:
  - kernel/workqueue.c:print_worker_info
```
**Symbols:**

```
ffffffff810e0d20-ffffffff810e0d84: kthread_probe_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void *kthread_probe_data(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810fb020)
Location: kernel/kthread.c:247
Inline: False
Direct callers:
  - kernel/workqueue.c:print_worker_info
```
**Symbols:**

```
ffffffff810fb020-ffffffff810fb08e: kthread_probe_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void *kthread_probe_data(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff8111ded0)
Location: kernel/kthread.c:247
Inline: False
Direct callers:
  - kernel/workqueue.c:print_worker_info
```
**Symbols:**

```
ffffffff8111ded0-ffffffff8111df3e: kthread_probe_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void *kthread_probe_data(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff8112b120)
Location: kernel/kthread.c:258
Inline: False
Direct callers:
  - kernel/workqueue.c:print_worker_info
```
**Symbols:**

```
ffffffff8112b120-ffffffff8112b18e: kthread_probe_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void *kthread_probe_data(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff81135870)
Location: kernel/kthread.c:257
Inline: False
Direct callers:
  - kernel/workqueue.c:print_worker_info
```
**Symbols:**

```
ffffffff81135870-ffffffff811358de: kthread_probe_data (STB_GLOBAL)
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
void *kthread_probe_data(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffff800010128e90)
Location: kernel/kthread.c:177
Inline: False
Direct callers:
  - kernel/workqueue.c:print_worker_info
```
**Symbols:**

```
ffff800010128e90-ffff800010128f08: kthread_probe_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void *kthread_probe_data(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (c037b42c)
Location: kernel/kthread.c:177
Inline: False
Direct callers:
  - kernel/workqueue.c:print_worker_info
```
**Symbols:**

```
c037b42c-c037b4c4: kthread_probe_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void *kthread_probe_data(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (c000000000173680)
Location: kernel/kthread.c:177
Inline: False
Direct callers:
  - kernel/workqueue.c:print_worker_info
```
**Symbols:**

```
c000000000173680-c000000000173708: kthread_probe_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void *kthread_probe_data(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffe0000dfdaa)
Location: kernel/kthread.c:177
Inline: False
Direct callers:
  - kernel/workqueue.c:print_worker_info
```
**Symbols:**

```
ffffffe0000dfdaa-ffffffe0000dfdf4: kthread_probe_data (STB_GLOBAL)
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
void *kthread_probe_data(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810c35c0)
Location: kernel/kthread.c:177
Inline: False
Direct callers:
  - kernel/workqueue.c:print_worker_info
```
**Symbols:**

```
ffffffff810c35c0-ffffffff810c3621: kthread_probe_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void *kthread_probe_data(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810b1df0)
Location: kernel/kthread.c:177
Inline: False
Direct callers:
  - kernel/workqueue.c:print_worker_info
```
**Symbols:**

```
ffffffff810b1df0-ffffffff810b1e51: kthread_probe_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void *kthread_probe_data(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810c2b10)
Location: kernel/kthread.c:177
Inline: False
Direct callers:
  - kernel/workqueue.c:print_worker_info
```
**Symbols:**

```
ffffffff810c2b10-ffffffff810c2b71: kthread_probe_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void *kthread_probe_data(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810caf50)
Location: kernel/kthread.c:177
Inline: False
Direct callers:
  - kernel/workqueue.c:print_worker_info
```
**Symbols:**

```
ffffffff810caf50-ffffffff810cafb1: kthread_probe_data (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
