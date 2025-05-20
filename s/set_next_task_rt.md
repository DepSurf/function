# Function: <code>set_next_task_rt</code>

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
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void set_next_task_rt(struct rq *rq, struct task_struct *p, bool first);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810ee18c)
Location: kernel/sched/rt.c:1518
Inline: True
Inline callers:
  - kernel/sched/rt.c:pick_next_task_rt
  - kernel/sched/rt.c:pick_next_task_rt
```
**Symbols:**

```
ffffffff810ee2e0-ffffffff810ee425: set_next_task_rt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void set_next_task_rt(struct rq *rq, struct task_struct *p, bool first);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810f7b4c)
Location: kernel/sched/rt.c:1575
Inline: True
Inline callers:
  - kernel/sched/rt.c:pick_next_task_rt
  - kernel/sched/rt.c:pick_next_task_rt
```
**Symbols:**

```
ffffffff810f78c0-ffffffff810f7a05: set_next_task_rt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void set_next_task_rt(struct rq *rq, struct task_struct *p, bool first);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810f5d4c)
Location: kernel/sched/rt.c:1577
Inline: True
Inline callers:
  - kernel/sched/rt.c:pick_next_task_rt
  - kernel/sched/rt.c:pick_next_task_rt
```
**Symbols:**

```
ffffffff810f5a90-ffffffff810f5be9: set_next_task_rt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void set_next_task_rt(struct rq *rq, struct task_struct *p, bool first);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810f80ac)
Location: kernel/sched/rt.c:1577
Inline: True
Inline callers:
  - kernel/sched/rt.c:pick_next_task_rt
  - kernel/sched/rt.c:pick_next_task_rt
```
**Symbols:**

```
ffffffff810f7df0-ffffffff810f7f49: set_next_task_rt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void set_next_task_rt(struct rq *rq, struct task_struct *p, bool first);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/rt.c (ffffffff81113711)
Location: kernel/sched/rt.c:1592
Inline: True
Inline callers:
  - kernel/sched/rt.c:pick_next_task_rt
  - kernel/sched/rt.c:pick_next_task_rt
```
**Symbols:**

```
ffffffff811133c0-ffffffff81113561: set_next_task_rt (STB_LOCAL)
ffffffff81ca6848-ffffffff81ca6872: set_next_task_rt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void set_next_task_rt(struct rq *rq, struct task_struct *p, bool first);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff81138451)
Location: kernel/sched/rt.c:1747
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:pick_next_task_rt
  - kernel/sched/build_policy.c:pick_next_task_rt
```
**Symbols:**

```
ffffffff81138080-ffffffff81138264: set_next_task_rt (STB_LOCAL)
ffffffff81e567b4-ffffffff81e567de: set_next_task_rt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
void set_next_task_rt(struct rq *rq, struct task_struct *p, bool first);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff81162af8)
Location: kernel/sched/rt.c:1743
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:pick_next_task_rt
  - kernel/sched/build_policy.c:pick_next_task_rt
```
**Symbols:**

```
ffffffff81162750-ffffffff81162934: set_next_task_rt (STB_LOCAL)
ffffffff820579d4-ffffffff820579fe: set_next_task_rt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
void set_next_task_rt(struct rq *rq, struct task_struct *p, bool first);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff81173278)
Location: kernel/sched/rt.c:1743
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:pick_next_task_rt
  - kernel/sched/build_policy.c:pick_next_task_rt
```
**Symbols:**

```
ffffffff81172ed0-ffffffff811730b4: set_next_task_rt (STB_LOCAL)
ffffffff820d61fa-ffffffff820d6224: set_next_task_rt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void set_next_task_rt(struct rq *rq, struct task_struct *p, bool first);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff81180b58)
Location: kernel/sched/rt.c:1688
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:pick_next_task_rt
  - kernel/sched/build_policy.c:pick_next_task_rt
```
**Symbols:**

```
ffffffff811807e0-ffffffff81180a18: set_next_task_rt (STB_LOCAL)
ffffffff821b1398-ffffffff821b13c2: set_next_task_rt.cold (STB_LOCAL)
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
void set_next_task_rt(struct rq *rq, struct task_struct *p, bool first);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffff80001014ee40)
Location: kernel/sched/rt.c:1518
Inline: True
Inline callers:
  - kernel/sched/rt.c:pick_next_task_rt
  - kernel/sched/rt.c:pick_next_task_rt
```
**Symbols:**

```
ffff80001014f228-ffff80001014f378: set_next_task_rt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void set_next_task_rt(struct rq *rq, struct task_struct *p, bool first);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (c039d2bc)
Location: kernel/sched/rt.c:1518
Inline: True
Inline callers:
  - kernel/sched/rt.c:pick_next_task_rt
  - kernel/sched/rt.c:pick_next_task_rt
```
**Symbols:**

```
c039d47c-c039d5ec: set_next_task_rt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void set_next_task_rt(struct rq *rq, struct task_struct *p, bool first);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (c0000000001a3268)
Location: kernel/sched/rt.c:1518
Inline: True
Inline callers:
  - kernel/sched/rt.c:pick_next_task_rt
  - kernel/sched/rt.c:pick_next_task_rt
```
**Symbols:**

```
c0000000001a3420-c0000000001a35c4: set_next_task_rt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void set_next_task_rt(struct rq *rq, struct task_struct *p, bool first);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffe0000f7d14)
Location: kernel/sched/rt.c:1518
Inline: True
Inline callers:
  - kernel/sched/rt.c:pick_next_task_rt
  - kernel/sched/rt.c:pick_next_task_rt
```
**Symbols:**

```
ffffffe0000f7e9e-ffffffe0000f7fe2: set_next_task_rt (STB_LOCAL)
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
void set_next_task_rt(struct rq *rq, struct task_struct *p, bool first);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810e7e85)
Location: kernel/sched/rt.c:1518
Inline: True
Inline callers:
  - kernel/sched/rt.c:pick_next_task_rt
  - kernel/sched/rt.c:pick_next_task_rt
```
**Symbols:**

```
ffffffff810e7fd0-ffffffff810e8115: set_next_task_rt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void set_next_task_rt(struct rq *rq, struct task_struct *p, bool first);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810d74dc)
Location: kernel/sched/rt.c:1518
Inline: True
Inline callers:
  - kernel/sched/rt.c:pick_next_task_rt
  - kernel/sched/rt.c:pick_next_task_rt
```
**Symbols:**

```
ffffffff810d7790-ffffffff810d78d5: set_next_task_rt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void set_next_task_rt(struct rq *rq, struct task_struct *p, bool first);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810e46bc)
Location: kernel/sched/rt.c:1518
Inline: True
Inline callers:
  - kernel/sched/rt.c:pick_next_task_rt
  - kernel/sched/rt.c:pick_next_task_rt
```
**Symbols:**

```
ffffffff810e4810-ffffffff810e4955: set_next_task_rt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void set_next_task_rt(struct rq *rq, struct task_struct *p, bool first);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810f0b45)
Location: kernel/sched/rt.c:1518
Inline: True
Inline callers:
  - kernel/sched/rt.c:pick_next_task_rt
  - kernel/sched/rt.c:pick_next_task_rt
```
**Symbols:**

```
ffffffff810f0c90-ffffffff810f0dd5: set_next_task_rt (STB_LOCAL)
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
