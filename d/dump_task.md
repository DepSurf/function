# Function: <code>dump_task</code>

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
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int dump_task(struct task_struct *p, void *arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff8121bcb0)
Location: mm/oom_kill.c:380
Inline: True
Direct callers:
  - mm/oom_kill.c:dump_header
```
**Symbols:**

```
ffffffff8121bcb0-ffffffff8121bdde: dump_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int dump_task(struct task_struct *p, void *arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff81229640)
Location: mm/oom_kill.c:380
Inline: True
Direct callers:
  - mm/oom_kill.c:dump_header
```
**Symbols:**

```
ffffffff81229640-ffffffff8122976e: dump_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int dump_task(struct task_struct *p, void *arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/oom_kill.c (ffffffff81256260)
Location: mm/oom_kill.c:381
Inline: True
Direct callers:
  - mm/oom_kill.c:dump_header
```
**Symbols:**

```
ffffffff81256260-ffffffff812563c0: dump_task.part.0 (STB_LOCAL)
ffffffff812563c0-ffffffff81256408: dump_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int dump_task(struct task_struct *p, void *arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/oom_kill.c (ffffffff81260f30)
Location: mm/oom_kill.c:383
Inline: True
Direct callers:
  - mm/oom_kill.c:dump_header
```
**Symbols:**

```
ffffffff81260f30-ffffffff8126103b: dump_task.part.0 (STB_LOCAL)
ffffffff81261040-ffffffff81261088: dump_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int dump_task(struct task_struct *p, void *arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff81265a90)
Location: mm/oom_kill.c:383
Inline: True
Direct callers:
  - mm/oom_kill.c:dump_header
```
**Symbols:**

```
ffffffff81265a90-ffffffff81265bd0: dump_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int dump_task(struct task_struct *p, void *arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff812a22c0)
Location: mm/oom_kill.c:384
Inline: True
Direct callers:
  - mm/oom_kill.c:dump_header
```
**Symbols:**

```
ffffffff812a22c0-ffffffff812a2400: dump_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int dump_task(struct task_struct *p, void *arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff812f9d10)
Location: mm/oom_kill.c:381
Inline: True
Direct callers:
  - mm/oom_kill.c:dump_header
```
**Symbols:**

```
ffffffff812f9d10-ffffffff812f9ef9: dump_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int dump_task(struct task_struct *p, void *arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff81363eb0)
Location: mm/oom_kill.c:381
Inline: True
Direct callers:
  - mm/oom_kill.c:dump_header
```
**Symbols:**

```
ffffffff81363eb0-ffffffff813640a5: dump_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int dump_task(struct task_struct *p, void *arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff81396380)
Location: mm/oom_kill.c:381
Inline: True
Direct callers:
  - mm/oom_kill.c:dump_header
```
**Symbols:**

```
ffffffff81396380-ffffffff81396578: dump_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int dump_task(struct task_struct *p, void *arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff813c0410)
Location: mm/oom_kill.c:381
Inline: True
Direct callers:
  - mm/oom_kill.c:dump_header
```
**Symbols:**

```
ffffffff813c0410-ffffffff813c0656: dump_task (STB_LOCAL)
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
int dump_task(struct task_struct *p, void *arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffff8000102b73a0)
Location: mm/oom_kill.c:380
Inline: True
Direct callers:
  - mm/oom_kill.c:dump_header
```
**Symbols:**

```
ffff8000102b73a0-ffff8000102b74bc: dump_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
int dump_task(struct task_struct *p, void *arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/oom_kill.c (c04e56ac)
Location: mm/oom_kill.c:380
Inline: True
Inline callers:
  - mm/oom_kill.c:dump_header
Direct callers:
  - mm/oom_kill.c:dump_header
```
**Symbols:**

```
c04e4088-c04e4160: dump_task.part.0 (STB_LOCAL)
c04e4160-c04e4198: dump_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int dump_task(struct task_struct *p, void *arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (c00000000036efc0)
Location: mm/oom_kill.c:380
Inline: True
Direct callers:
  - mm/oom_kill.c:dump_header
```
**Symbols:**

```
c00000000036efc0-c00000000036f10c: dump_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
int dump_task(struct task_struct *p, void *arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/oom_kill.c (ffffffe0001dcad4)
Location: mm/oom_kill.c:380
Inline: True
Inline callers:
  - mm/oom_kill.c:dump_header
Direct callers:
  - mm/oom_kill.c:dump_header
```
**Symbols:**

```
ffffffe0001db6ea-ffffffe0001db7aa: dump_task.part.0 (STB_LOCAL)
ffffffe0001db7aa-ffffffe0001db7ea: dump_task (STB_LOCAL)
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
int dump_task(struct task_struct *p, void *arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff81221c90)
Location: mm/oom_kill.c:380
Inline: True
Direct callers:
  - mm/oom_kill.c:dump_header
```
**Symbols:**

```
ffffffff81221c90-ffffffff81221dbe: dump_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int dump_task(struct task_struct *p, void *arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff81214e40)
Location: mm/oom_kill.c:380
Inline: True
Direct callers:
  - mm/oom_kill.c:dump_header
```
**Symbols:**

```
ffffffff81214e40-ffffffff81214f6e: dump_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int dump_task(struct task_struct *p, void *arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff8121fa30)
Location: mm/oom_kill.c:380
Inline: True
Direct callers:
  - mm/oom_kill.c:dump_header
```
**Symbols:**

```
ffffffff8121fa30-ffffffff8121fb5e: dump_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int dump_task(struct task_struct *p, void *arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff8122eae0)
Location: mm/oom_kill.c:380
Inline: True
Direct callers:
  - mm/oom_kill.c:dump_header
```
**Symbols:**

```
ffffffff8122eae0-ffffffff8122ec1e: dump_task (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
