# Function: <code>enqueue_task_rt</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void enqueue_task_rt(struct rq *rq, struct task_struct *p, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810c0740)
Location: kernel/sched/rt.c:1256
Inline: False
```
**Symbols:**

```
ffffffff810c0740-ffffffff810c09d9: enqueue_task_rt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void enqueue_task_rt(struct rq *rq, struct task_struct *p, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810c4150)
Location: kernel/sched/rt.c:1318
Inline: False
```
**Symbols:**

```
ffffffff810c4150-ffffffff810c4470: enqueue_task_rt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void enqueue_task_rt(struct rq *rq, struct task_struct *p, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810ca1b0)
Location: kernel/sched/rt.c:1317
Inline: False
```
**Symbols:**

```
ffffffff810ca1b0-ffffffff810ca4c7: enqueue_task_rt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void enqueue_task_rt(struct rq *rq, struct task_struct *p, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810c3d10)
Location: kernel/sched/rt.c:1329
Inline: False
```
**Symbols:**

```
ffffffff810c3d10-ffffffff810c3fde: enqueue_task_rt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void enqueue_task_rt(struct rq *rq, struct task_struct *p, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810cb4e0)
Location: kernel/sched/rt.c:1319
Inline: False
```
**Symbols:**

```
ffffffff810cb4e0-ffffffff810cb7b7: enqueue_task_rt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void enqueue_task_rt(struct rq *rq, struct task_struct *p, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810d2e20)
Location: kernel/sched/rt.c:1328
Inline: False
```
**Symbols:**

```
ffffffff810d2e20-ffffffff810d30f6: enqueue_task_rt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void enqueue_task_rt(struct rq *rq, struct task_struct *p, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810dd060)
Location: kernel/sched/rt.c:1328
Inline: False
```
**Symbols:**

```
ffffffff810dd060-ffffffff810dd336: enqueue_task_rt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void enqueue_task_rt(struct rq *rq, struct task_struct *p, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/rt.c (0)
Location: kernel/sched/rt.c:1328
Inline: False
```
**Symbols:**

```
ffffffff810e4020-ffffffff810e4302: enqueue_task_rt (STB_LOCAL)
ffffffff810e52f9-ffffffff810e531c: enqueue_task_rt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void enqueue_task_rt(struct rq *rq, struct task_struct *p, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810eebe0)
Location: kernel/sched/rt.c:1329
Inline: False
```
**Symbols:**

```
ffffffff810eebe0-ffffffff810eeca6: enqueue_task_rt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void enqueue_task_rt(struct rq *rq, struct task_struct *p, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810f83e0)
Location: kernel/sched/rt.c:1370
Inline: False
```
**Symbols:**

```
ffffffff810f83e0-ffffffff810f84e1: enqueue_task_rt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void enqueue_task_rt(struct rq *rq, struct task_struct *p, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810f65f0)
Location: kernel/sched/rt.c:1372
Inline: False
```
**Symbols:**

```
ffffffff810f65f0-ffffffff810f66f1: enqueue_task_rt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void enqueue_task_rt(struct rq *rq, struct task_struct *p, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810f8610)
Location: kernel/sched/rt.c:1372
Inline: False
```
**Symbols:**

```
ffffffff810f8610-ffffffff810f8711: enqueue_task_rt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void enqueue_task_rt(struct rq *rq, struct task_struct *p, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff811139a0)
Location: kernel/sched/rt.c:1387
Inline: False
```
**Symbols:**

```
ffffffff811139a0-ffffffff81113cd6: enqueue_task_rt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void enqueue_task_rt(struct rq *rq, struct task_struct *p, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff81131010)
Location: kernel/sched/rt.c:1539
Inline: False
```
**Symbols:**

```
ffffffff81131010-ffffffff81131438: enqueue_task_rt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void enqueue_task_rt(struct rq *rq, struct task_struct *p, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/build_policy.c (0)
Location: kernel/sched/rt.c:1535
Inline: False
```
**Symbols:**

```
ffffffff8115af60-ffffffff8115b417: enqueue_task_rt (STB_LOCAL)
ffffffff820572f0-ffffffff82057315: enqueue_task_rt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void enqueue_task_rt(struct rq *rq, struct task_struct *p, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/build_policy.c (0)
Location: kernel/sched/rt.c:1535
Inline: False
```
**Symbols:**

```
ffffffff8116b170-ffffffff8116b5fe: enqueue_task_rt (STB_LOCAL)
ffffffff820d5b20-ffffffff820d5b3d: enqueue_task_rt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void enqueue_task_rt(struct rq *rq, struct task_struct *p, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/build_policy.c (0)
Location: kernel/sched/rt.c:1480
Inline: False
```
**Symbols:**

```
ffffffff81178b10-ffffffff81178efc: enqueue_task_rt (STB_LOCAL)
ffffffff821b0c6e-ffffffff821b0c8b: enqueue_task_rt.cold (STB_LOCAL)
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
void enqueue_task_rt(struct rq *rq, struct task_struct *p, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffff8000101502e0)
Location: kernel/sched/rt.c:1329
Inline: False
```
**Symbols:**

```
ffff8000101502e0-ffff8000101503a4: enqueue_task_rt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void enqueue_task_rt(struct rq *rq, struct task_struct *p, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (c039d77c)
Location: kernel/sched/rt.c:1329
Inline: False
```
**Symbols:**

```
c039d77c-c039d820: enqueue_task_rt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void enqueue_task_rt(struct rq *rq, struct task_struct *p, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (c0000000001a37f0)
Location: kernel/sched/rt.c:1329
Inline: False
```
**Symbols:**

```
c0000000001a37f0-c0000000001a38e4: enqueue_task_rt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void enqueue_task_rt(struct rq *rq, struct task_struct *p, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffe0000f8a72)
Location: kernel/sched/rt.c:1329
Inline: False
```
**Symbols:**

```
ffffffe0000f8a72-ffffffe0000f8b34: enqueue_task_rt (STB_LOCAL)
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
void enqueue_task_rt(struct rq *rq, struct task_struct *p, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810e8410)
Location: kernel/sched/rt.c:1329
Inline: False
```
**Symbols:**

```
ffffffff810e8410-ffffffff810e86f0: enqueue_task_rt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void enqueue_task_rt(struct rq *rq, struct task_struct *p, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810d7fa0)
Location: kernel/sched/rt.c:1329
Inline: False
```
**Symbols:**

```
ffffffff810d7fa0-ffffffff810d8066: enqueue_task_rt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void enqueue_task_rt(struct rq *rq, struct task_struct *p, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810e5110)
Location: kernel/sched/rt.c:1329
Inline: False
```
**Symbols:**

```
ffffffff810e5110-ffffffff810e51d6: enqueue_task_rt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void enqueue_task_rt(struct rq *rq, struct task_struct *p, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810f1170)
Location: kernel/sched/rt.c:1329
Inline: False
```
**Symbols:**

```
ffffffff810f1170-ffffffff810f144e: enqueue_task_rt (STB_LOCAL)
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
