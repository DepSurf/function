# Function: <code>oom_evaluate_task</code>

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
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int oom_evaluate_task(struct task_struct *task, void *arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff811b5440)
Location: mm/oom_kill.c:288
Inline: True
```
**Symbols:**

```
ffffffff811b5440-ffffffff811b5524: oom_evaluate_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int oom_evaluate_task(struct task_struct *task, void *arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff811bd150)
Location: mm/oom_kill.c:291
Inline: True
```
**Symbols:**

```
ffffffff811bd150-ffffffff811bd23d: oom_evaluate_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int oom_evaluate_task(struct task_struct *task, void *arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff811d1d60)
Location: mm/oom_kill.c:312
Inline: True
```
**Symbols:**

```
ffffffff811d1d60-ffffffff811d1e4d: oom_evaluate_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int oom_evaluate_task(struct task_struct *task, void *arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff811f2b50)
Location: mm/oom_kill.c:307
Inline: True
```
**Symbols:**

```
ffffffff811f2b50-ffffffff811f2c46: oom_evaluate_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int oom_evaluate_task(struct task_struct *task, void *arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff81204b70)
Location: mm/oom_kill.c:315
Inline: True
```
**Symbols:**

```
ffffffff81204b70-ffffffff81204c66: oom_evaluate_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int oom_evaluate_task(struct task_struct *task, void *arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff8121bf10)
Location: mm/oom_kill.c:309
Inline: True
```
**Symbols:**

```
ffffffff8121bf10-ffffffff8121c02b: oom_evaluate_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int oom_evaluate_task(struct task_struct *task, void *arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff812298a0)
Location: mm/oom_kill.c:309
Inline: True
```
**Symbols:**

```
ffffffff812298a0-ffffffff812299bb: oom_evaluate_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int oom_evaluate_task(struct task_struct *task, void *arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff812565c0)
Location: mm/oom_kill.c:310
Inline: True
```
**Symbols:**

```
ffffffff812565c0-ffffffff8125676d: oom_evaluate_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int oom_evaluate_task(struct task_struct *task, void *arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff812611d0)
Location: mm/oom_kill.c:310
Inline: True
```
**Symbols:**

```
ffffffff812611d0-ffffffff8126138a: oom_evaluate_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int oom_evaluate_task(struct task_struct *task, void *arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff81266250)
Location: mm/oom_kill.c:310
Inline: True
```
**Symbols:**

```
ffffffff81266250-ffffffff812663ef: oom_evaluate_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int oom_evaluate_task(struct task_struct *task, void *arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/oom_kill.c (ffffffff812a2aa8)
Location: mm/oom_kill.c:311
Inline: True
Direct callers:
  - mm/oom_kill.c:out_of_memory
```
**Symbols:**

```
ffffffff812a2a70-ffffffff812a2c2c: oom_evaluate_task (STB_LOCAL)
ffffffff81cba381-ffffffff81cba396: oom_evaluate_task.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int oom_evaluate_task(struct task_struct *task, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/oom_kill.c (0)
Location: mm/oom_kill.c:308
Inline: False
Direct callers:
  - mm/oom_kill.c:out_of_memory
```
**Symbols:**

```
ffffffff812fa860-ffffffff812faa38: oom_evaluate_task (STB_LOCAL)
ffffffff81e6ba8b-ffffffff81e6baa0: oom_evaluate_task.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int oom_evaluate_task(struct task_struct *task, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/oom_kill.c (0)
Location: mm/oom_kill.c:308
Inline: False
Direct callers:
  - mm/oom_kill.c:out_of_memory
```
**Symbols:**

```
ffffffff81365020-ffffffff813651f8: oom_evaluate_task (STB_LOCAL)
ffffffff82062433-ffffffff82062448: oom_evaluate_task.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int oom_evaluate_task(struct task_struct *task, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/oom_kill.c (0)
Location: mm/oom_kill.c:308
Inline: False
Direct callers:
  - mm/oom_kill.c:out_of_memory
```
**Symbols:**

```
ffffffff813974e0-ffffffff813976b8: oom_evaluate_task (STB_LOCAL)
ffffffff820e1c0e-ffffffff820e1c23: oom_evaluate_task.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int oom_evaluate_task(struct task_struct *task, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/oom_kill.c (0)
Location: mm/oom_kill.c:308
Inline: False
Direct callers:
  - mm/oom_kill.c:out_of_memory
```
**Symbols:**

```
ffffffff813c1310-ffffffff813c14e8: oom_evaluate_task (STB_LOCAL)
ffffffff821be633-ffffffff821be648: oom_evaluate_task.cold (STB_LOCAL)
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
int oom_evaluate_task(struct task_struct *task, void *arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffff8000102b75e0)
Location: mm/oom_kill.c:309
Inline: True
```
**Symbols:**

```
ffff8000102b75e0-ffff8000102b7734: oom_evaluate_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int oom_evaluate_task(struct task_struct *task, void *arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (c04e4298)
Location: mm/oom_kill.c:309
Inline: True
```
**Symbols:**

```
c04e4298-c04e4398: oom_evaluate_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int oom_evaluate_task(struct task_struct *task, void *arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (c00000000036f2c0)
Location: mm/oom_kill.c:309
Inline: True
```
**Symbols:**

```
c00000000036f2c0-c00000000036f4ec: oom_evaluate_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int oom_evaluate_task(struct task_struct *task, void *arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffe0001db946)
Location: mm/oom_kill.c:309
Inline: True
```
**Symbols:**

```
ffffffe0001db946-ffffffe0001dba42: oom_evaluate_task (STB_LOCAL)
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
int oom_evaluate_task(struct task_struct *task, void *arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff81221ef0)
Location: mm/oom_kill.c:309
Inline: True
```
**Symbols:**

```
ffffffff81221ef0-ffffffff8122200b: oom_evaluate_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int oom_evaluate_task(struct task_struct *task, void *arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff812150a0)
Location: mm/oom_kill.c:309
Inline: True
```
**Symbols:**

```
ffffffff812150a0-ffffffff812151bb: oom_evaluate_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int oom_evaluate_task(struct task_struct *task, void *arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff8121fc90)
Location: mm/oom_kill.c:309
Inline: True
```
**Symbols:**

```
ffffffff8121fc90-ffffffff8121fdab: oom_evaluate_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int oom_evaluate_task(struct task_struct *task, void *arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff8122ed70)
Location: mm/oom_kill.c:309
Inline: True
```
**Symbols:**

```
ffffffff8122ed70-ffffffff8122ee8b: oom_evaluate_task (STB_LOCAL)
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
