# Function: <code>dump_cpu_task</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void dump_cpu_task(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b0cc0)
Location: kernel/sched/core.c:8608
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_dump_cpu_stacks
  - kernel/rcu/tree.c:synchronize_sched_expedited
```
**Symbols:**

```
ffffffff810b0cc0-ffffffff810b0cfa: dump_cpu_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void dump_cpu_task(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b37b0)
Location: kernel/sched/core.c:8666
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_dump_cpu_stacks
```
**Symbols:**

```
ffffffff810b37b0-ffffffff810b37ea: dump_cpu_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void dump_cpu_task(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b9df0)
Location: kernel/sched/core.c:8819
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_exp_wait_wake
  - kernel/rcu/tree.c:rcu_dump_cpu_stacks
```
**Symbols:**

```
ffffffff810b9df0-ffffffff810b9e2a: dump_cpu_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void dump_cpu_task(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b4640)
Location: kernel/sched/core.c:6673
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_exp_wait_wake
```
**Symbols:**

```
ffffffff810b4640-ffffffff810b467a: dump_cpu_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void dump_cpu_task(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810bb910)
Location: kernel/sched/core.c:6912
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_exp_wait_wake
```
**Symbols:**

```
ffffffff810bb910-ffffffff810bb94a: dump_cpu_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void dump_cpu_task(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810c2fed)
Location: kernel/sched/core.c:7036
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_exp_wait_wake
```
**Symbols:**

```
ffffffff810c2fed-ffffffff810c3027: dump_cpu_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void dump_cpu_task(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810cc29f)
Location: kernel/sched/core.c:7027
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_exp_wait_wake
```
**Symbols:**

```
ffffffff810cc29f-ffffffff810cc2d9: dump_cpu_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void dump_cpu_task(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d46e0)
Location: kernel/sched/core.c:7509
Inline: False
Direct callers:
  - kernel/rcu/tree.c:synchronize_sched_expedited_wait
```
**Symbols:**

```
ffffffff810d46e0-ffffffff810d471a: dump_cpu_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void dump_cpu_task(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810dec77)
Location: kernel/sched/core.c:7921
Inline: False
Direct callers:
  - kernel/rcu/tree.c:synchronize_sched_expedited_wait
```
**Symbols:**

```
ffffffff810dec77-ffffffff810decb1: dump_cpu_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void dump_cpu_task(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810e6ef8)
Location: kernel/sched/core.c:8165
Inline: False
Direct callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
```
**Symbols:**

```
ffffffff810e6ef8-ffffffff810e6f32: dump_cpu_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void dump_cpu_task(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81bdc73b)
Location: kernel/sched/core.c:9130
Inline: False
Direct callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
```
**Symbols:**

```
ffffffff81bdc73b-ffffffff81bdc775: dump_cpu_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void dump_cpu_task(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81bce8b6)
Location: kernel/sched/core.c:9506
Inline: False
Direct callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:rcu_check_gp_kthread_starvation
  - kernel/rcu/tree.c:rcu_dump_cpu_stacks
```
**Symbols:**

```
ffffffff81bce8b6-ffffffff81bce8f0: dump_cpu_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void dump_cpu_task(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81ca60ea)
Location: kernel/sched/core.c:10825
Inline: False
Direct callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:rcu_check_gp_kthread_starvation
  - kernel/rcu/tree.c:rcu_dump_cpu_stacks
```
**Symbols:**

```
ffffffff81ca60ea-ffffffff81ca6140: dump_cpu_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void dump_cpu_task(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81e55a46)
Location: kernel/sched/core.c:11158
Inline: False
Direct callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:print_cpu_stall
  - kernel/rcu/tree.c:rcu_check_gp_kthread_starvation
  - kernel/rcu/tree.c:rcu_dump_cpu_stacks
```
**Symbols:**

```
ffffffff81e55a46-ffffffff81e55aa6: dump_cpu_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void dump_cpu_task(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff811424e0)
Location: kernel/sched/core.c:11305
Inline: False
Direct callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:rcu_check_gp_kthread_starvation
  - kernel/rcu/tree.c:rcu_dump_cpu_stacks
```
**Symbols:**

```
ffffffff811424e0-ffffffff81142567: dump_cpu_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void dump_cpu_task(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff8114e1f0)
Location: kernel/sched/core.c:11465
Inline: False
Direct callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:rcu_check_gp_kthread_starvation
  - kernel/rcu/tree.c:rcu_dump_cpu_stacks
```
**Symbols:**

```
ffffffff8114e1f0-ffffffff8114e27a: dump_cpu_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void dump_cpu_task(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff8115a030)
Location: kernel/sched/core.c:11467
Inline: False
Direct callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:rcu_check_gp_kthread_starvation
  - kernel/rcu/tree.c:rcu_dump_cpu_stacks
```
**Symbols:**

```
ffffffff8115a030-ffffffff8115a0ba: dump_cpu_task (STB_GLOBAL)
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
void dump_cpu_task(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffff80001013e6a4)
Location: kernel/sched/core.c:7921
Inline: False
Direct callers:
  - kernel/rcu/tree.c:synchronize_sched_expedited_wait
  - kernel/rcu/tree.c:rcu_dump_cpu_stacks
```
**Symbols:**

```
ffff80001013e6a4-ffff80001013e6f8: dump_cpu_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void dump_cpu_task(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (c038e68c)
Location: kernel/sched/core.c:7921
Inline: False
Direct callers:
  - kernel/rcu/tree.c:synchronize_sched_expedited_wait
```
**Symbols:**

```
c038e68c-c038e6e4: dump_cpu_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void dump_cpu_task(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (c00000000018d830)
Location: kernel/sched/core.c:7921
Inline: False
Direct callers:
  - kernel/rcu/tree.c:synchronize_sched_expedited_wait
```
**Symbols:**

```
c00000000018d830-c00000000018d89c: dump_cpu_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void dump_cpu_task(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffe0000ecf80)
Location: kernel/sched/core.c:7921
Inline: False
Direct callers:
  - kernel/rcu/tree.c:synchronize_sched_expedited_wait
  - kernel/rcu/tree.c:rcu_dump_cpu_stacks
```
**Symbols:**

```
ffffffe0000ecf80-ffffffe0000ecfda: dump_cpu_task (STB_GLOBAL)
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
void dump_cpu_task(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d8e67)
Location: kernel/sched/core.c:7921
Inline: False
Direct callers:
  - kernel/rcu/tree.c:synchronize_sched_expedited_wait
```
**Symbols:**

```
ffffffff810d8e67-ffffffff810d8ea1: dump_cpu_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void dump_cpu_task(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810c7872)
Location: kernel/sched/core.c:7921
Inline: False
Direct callers:
  - kernel/rcu/tree.c:synchronize_sched_expedited_wait
```
**Symbols:**

```
ffffffff810c7872-ffffffff810c78ac: dump_cpu_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void dump_cpu_task(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d51a7)
Location: kernel/sched/core.c:7921
Inline: False
Direct callers:
  - kernel/rcu/tree.c:synchronize_sched_expedited_wait
```
**Symbols:**

```
ffffffff810d51a7-ffffffff810d51e1: dump_cpu_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void dump_cpu_task(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810e0a60)
Location: kernel/sched/core.c:7921
Inline: False
Direct callers:
  - kernel/rcu/tree.c:synchronize_sched_expedited_wait
```
**Symbols:**

```
ffffffff810e0a60-ffffffff810e0a9a: dump_cpu_task (STB_GLOBAL)
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
