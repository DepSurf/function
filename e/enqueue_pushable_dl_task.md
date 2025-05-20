# Function: <code>enqueue_pushable_dl_task</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void enqueue_pushable_dl_task(struct rq *rq, struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810c18b0)
Location: kernel/sched/deadline.c:157
Inline: True
Direct callers:
  - kernel/sched/deadline.c:enqueue_task_dl
  - kernel/sched/deadline.c:put_prev_task_dl
```
**Symbols:**

```
ffffffff810c18b0-ffffffff810c1941: enqueue_pushable_dl_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void enqueue_pushable_dl_task(struct rq *rq, struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810c52f0)
Location: kernel/sched/deadline.c:157
Inline: True
Direct callers:
  - kernel/sched/deadline.c:put_prev_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
```
**Symbols:**

```
ffffffff810c52f0-ffffffff810c5393: enqueue_pushable_dl_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void enqueue_pushable_dl_task(struct rq *rq, struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810cb350)
Location: kernel/sched/deadline.c:157
Inline: True
Direct callers:
  - kernel/sched/deadline.c:put_prev_task_dl
  - kernel/sched/deadline.c:enqueue_task_dl
```
**Symbols:**

```
ffffffff810cb350-ffffffff810cb3f3: enqueue_pushable_dl_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void enqueue_pushable_dl_task(struct rq *rq, struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810c5690)
Location: kernel/sched/deadline.c:410
Inline: True
Direct callers:
  - kernel/sched/deadline.c:enqueue_task_dl
```
**Symbols:**

```
ffffffff810c5690-ffffffff810c5733: enqueue_pushable_dl_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void enqueue_pushable_dl_task(struct rq *rq, struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810ccdd0)
Location: kernel/sched/deadline.c:411
Inline: True
Direct callers:
  - kernel/sched/deadline.c:enqueue_task_dl
```
**Symbols:**

```
ffffffff810ccdd0-ffffffff810cce63: enqueue_pushable_dl_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void enqueue_pushable_dl_task(struct rq *rq, struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810d4d10)
Location: kernel/sched/deadline.c:445
Inline: True
Direct callers:
  - kernel/sched/deadline.c:enqueue_task_dl
```
**Symbols:**

```
ffffffff810d4d10-ffffffff810d4db2: enqueue_pushable_dl_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void enqueue_pushable_dl_task(struct rq *rq, struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810de6c0)
Location: kernel/sched/deadline.c:446
Inline: True
Direct callers:
  - kernel/sched/deadline.c:enqueue_task_dl
```
**Symbols:**

```
ffffffff810de6c0-ffffffff810de762: enqueue_pushable_dl_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void enqueue_pushable_dl_task(struct rq *rq, struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810e5740)
Location: kernel/sched/deadline.c:445
Inline: True
Direct callers:
  - kernel/sched/deadline.c:enqueue_task_dl
```
**Symbols:**

```
ffffffff810e5740-ffffffff810e583d: enqueue_pushable_dl_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void enqueue_pushable_dl_task(struct rq *rq, struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810f0b60)
Location: kernel/sched/deadline.c:445
Inline: True
Direct callers:
  - kernel/sched/deadline.c:enqueue_task_dl
```
**Symbols:**

```
ffffffff810f0b60-ffffffff810f0c5d: enqueue_pushable_dl_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void enqueue_pushable_dl_task(struct rq *rq, struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810f9d80)
Location: kernel/sched/deadline.c:447
Inline: False
Direct callers:
  - kernel/sched/deadline.c:enqueue_task_dl
```
**Symbols:**

```
ffffffff810f9d80-ffffffff810f9e79: enqueue_pushable_dl_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void enqueue_pushable_dl_task(struct rq *rq, struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810f8140)
Location: kernel/sched/deadline.c:524
Inline: False
Direct callers:
  - kernel/sched/deadline.c:enqueue_task_dl
```
**Symbols:**

```
ffffffff810f8140-ffffffff810f8239: enqueue_pushable_dl_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void enqueue_pushable_dl_task(struct rq *rq, struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810fa2a0)
Location: kernel/sched/deadline.c:532
Inline: False
Direct callers:
  - kernel/sched/deadline.c:enqueue_task_dl
```
**Symbols:**

```
ffffffff810fa2a0-ffffffff810fa3b0: enqueue_pushable_dl_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void enqueue_pushable_dl_task(struct rq *rq, struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff81115110)
Location: kernel/sched/deadline.c:532
Inline: False
Direct callers:
  - kernel/sched/deadline.c:enqueue_task_dl
```
**Symbols:**

```
ffffffff81115110-ffffffff81115220: enqueue_pushable_dl_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void enqueue_pushable_dl_task(struct rq *rq, struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff8112e4a0)
Location: kernel/sched/deadline.c:604
Inline: False
Direct callers:
  - kernel/sched/build_policy.c:enqueue_task_dl
```
**Symbols:**

```
ffffffff8112e4a0-ffffffff8112e5d6: enqueue_pushable_dl_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void enqueue_pushable_dl_task(struct rq *rq, struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff811583e0)
Location: kernel/sched/deadline.c:606
Inline: False
Direct callers:
  - kernel/sched/build_policy.c:enqueue_task_dl
```
**Symbols:**

```
ffffffff811583e0-ffffffff8115851e: enqueue_pushable_dl_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void enqueue_pushable_dl_task(struct rq *rq, struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff81168510)
Location: kernel/sched/deadline.c:601
Inline: False
Direct callers:
  - kernel/sched/build_policy.c:enqueue_task_dl
```
**Symbols:**

```
ffffffff81168510-ffffffff81168672: enqueue_pushable_dl_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void enqueue_pushable_dl_task(struct rq *rq, struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff811756f0)
Location: kernel/sched/deadline.c:595
Inline: False
Direct callers:
  - kernel/sched/build_policy.c:enqueue_task_dl
```
**Symbols:**

```
ffffffff811756f0-ffffffff81175897: enqueue_pushable_dl_task (STB_LOCAL)
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
void enqueue_pushable_dl_task(struct rq *rq, struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffff800010152868)
Location: kernel/sched/deadline.c:445
Inline: True
Direct callers:
  - kernel/sched/deadline.c:enqueue_task_dl
```
**Symbols:**

```
ffff800010152868-ffff800010152944: enqueue_pushable_dl_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void enqueue_pushable_dl_task(struct rq *rq, struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (c039f460)
Location: kernel/sched/deadline.c:445
Inline: False
Direct callers:
  - kernel/sched/deadline.c:enqueue_task_dl
```
**Symbols:**

```
c039f460-c039f55c: enqueue_pushable_dl_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void enqueue_pushable_dl_task(struct rq *rq, struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (c0000000001a5cc0)
Location: kernel/sched/deadline.c:445
Inline: False
Direct callers:
  - kernel/sched/deadline.c:enqueue_task_dl
```
**Symbols:**

```
c0000000001a5cc0-c0000000001a5de0: enqueue_pushable_dl_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void enqueue_pushable_dl_task(struct rq *rq, struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffe0000fa460)
Location: kernel/sched/deadline.c:445
Inline: True
Direct callers:
  - kernel/sched/deadline.c:enqueue_task_dl
```
**Symbols:**

```
ffffffe0000fa460-ffffffe0000fa518: enqueue_pushable_dl_task (STB_LOCAL)
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
void enqueue_pushable_dl_task(struct rq *rq, struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810e9f60)
Location: kernel/sched/deadline.c:445
Inline: True
Direct callers:
  - kernel/sched/deadline.c:enqueue_task_dl
```
**Symbols:**

```
ffffffff810e9f60-ffffffff810ea05d: enqueue_pushable_dl_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void enqueue_pushable_dl_task(struct rq *rq, struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810d9f20)
Location: kernel/sched/deadline.c:445
Inline: True
Direct callers:
  - kernel/sched/deadline.c:enqueue_task_dl
```
**Symbols:**

```
ffffffff810d9f20-ffffffff810da01d: enqueue_pushable_dl_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void enqueue_pushable_dl_task(struct rq *rq, struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810e7090)
Location: kernel/sched/deadline.c:445
Inline: True
Direct callers:
  - kernel/sched/deadline.c:enqueue_task_dl
```
**Symbols:**

```
ffffffff810e7090-ffffffff810e718d: enqueue_pushable_dl_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void enqueue_pushable_dl_task(struct rq *rq, struct task_struct *p);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810f2050)
Location: kernel/sched/deadline.c:445
Inline: True
Direct callers:
  - kernel/sched/deadline.c:enqueue_task_dl
```
**Symbols:**

```
ffffffff810f2050-ffffffff810f214d: enqueue_pushable_dl_task (STB_LOCAL)
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
