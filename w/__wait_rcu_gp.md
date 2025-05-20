# Function: <code>__wait_rcu_gp</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __wait_rcu_gp(bool checktiny, int n, call_rcu_func_t *crcu_array, struct rcu_synchronize *rs_array);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff810e34a0)
Location: kernel/rcu/update.c:323
Inline: False
```
**Symbols:**

```
ffffffff810e34a0-ffffffff810e3589: __wait_rcu_gp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __wait_rcu_gp(bool checktiny, int n, call_rcu_func_t *crcu_array, struct rcu_synchronize *rs_array);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff810e9230)
Location: kernel/rcu/update.c:342
Inline: False
Direct callers:
  - kernel/rcu/update.c:rcu_barrier_tasks
```
**Symbols:**

```
ffffffff810e9230-ffffffff810e931c: __wait_rcu_gp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __wait_rcu_gp(bool checktiny, int n, call_rcu_func_t *crcu_array, struct rcu_synchronize *rs_array);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff810f0100)
Location: kernel/rcu/update.c:345
Inline: False
Direct callers:
  - kernel/rcu/update.c:rcu_barrier_tasks
```
**Symbols:**

```
ffffffff810f0100-ffffffff810f01ec: __wait_rcu_gp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __wait_rcu_gp(bool checktiny, int n, call_rcu_func_t *crcu_array, struct rcu_synchronize *rs_array);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff810f00a0)
Location: kernel/rcu/update.c:380
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_cpu_deactivate
```
**Symbols:**

```
ffffffff810f00a0-ffffffff810f01f5: __wait_rcu_gp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __wait_rcu_gp(bool checktiny, int n, call_rcu_func_t *crcu_array, struct rcu_synchronize *rs_array);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff810f9d60)
Location: kernel/rcu/update.c:381
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/rcu/update.c:rcu_barrier_tasks
```
**Symbols:**

```
ffffffff810f9d60-ffffffff810f9eb8: __wait_rcu_gp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __wait_rcu_gp(bool checktiny, int n, call_rcu_func_t *crcu_array, struct rcu_synchronize *rs_array);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff811022e0)
Location: kernel/rcu/update.c:333
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/rcu/update.c:rcu_barrier_tasks
```
**Symbols:**

```
ffffffff811022e0-ffffffff81102430: __wait_rcu_gp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __wait_rcu_gp(bool checktiny, int n, call_rcu_func_t *crcu_array, struct rcu_synchronize *rs_array);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff8110dce0)
Location: kernel/rcu/update.c:329
Inline: False
Direct callers:
  - kernel/rcu/update.c:rcu_barrier_tasks
```
**Symbols:**

```
ffffffff8110dce0-ffffffff8110de1a: __wait_rcu_gp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __wait_rcu_gp(bool checktiny, int n, call_rcu_func_t *crcu_array, struct rcu_synchronize *rs_array);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff81117370)
Location: kernel/rcu/update.c:318
Inline: False
Direct callers:
  - kernel/rcu/update.c:rcu_barrier_tasks
  - kernel/rcu/update.c:synchronize_rcu_tasks
  - kernel/rcu/tree.c:synchronize_rcu_expedited
```
**Symbols:**

```
ffffffff81117370-ffffffff811174b8: __wait_rcu_gp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __wait_rcu_gp(bool checktiny, int n, call_rcu_func_t *crcu_array, struct rcu_synchronize *rs_array);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff81123740)
Location: kernel/rcu/update.c:343
Inline: False
Direct callers:
  - kernel/rcu/update.c:rcu_barrier_tasks
  - kernel/rcu/update.c:synchronize_rcu_tasks
  - kernel/rcu/tree.c:synchronize_rcu_expedited
```
**Symbols:**

```
ffffffff81123740-ffffffff81123888: __wait_rcu_gp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __wait_rcu_gp(bool checktiny, int n, call_rcu_func_t *crcu_array, struct rcu_synchronize *rs_array);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff8112fdc0)
Location: kernel/rcu/update.c:380
Inline: False
Direct callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited
```
**Symbols:**

```
ffffffff8112fdc0-ffffffff8112fedd: __wait_rcu_gp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __wait_rcu_gp(bool checktiny, int n, call_rcu_func_t *crcu_array, struct rcu_synchronize *rs_array);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff8112bc20)
Location: kernel/rcu/update.c:369
Inline: False
Direct callers:
  - kernel/rcu/update.c:rcu_barrier_tasks_rude
  - kernel/rcu/tree.c:synchronize_rcu_expedited
```
**Symbols:**

```
ffffffff8112bc20-ffffffff8112bd43: __wait_rcu_gp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __wait_rcu_gp(bool checktiny, int n, call_rcu_func_t *crcu_array, struct rcu_synchronize *rs_array);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff8112c0b0)
Location: kernel/rcu/update.c:371
Inline: False
Direct callers:
  - kernel/rcu/update.c:rcu_barrier_tasks_rude
  - kernel/rcu/tree.c:synchronize_rcu_expedited
```
**Symbols:**

```
ffffffff8112c0b0-ffffffff8112c1d3: __wait_rcu_gp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __wait_rcu_gp(bool checktiny, int n, call_rcu_func_t *crcu_array, struct rcu_synchronize *rs_array);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff8114cc40)
Location: kernel/rcu/update.c:371
Inline: False
Direct callers:
  - kernel/rcu/update.c:rcu_barrier_tasks_rude
  - kernel/rcu/tree.c:synchronize_rcu_expedited
```
**Symbols:**

```
ffffffff8114cc40-ffffffff8114cd63: __wait_rcu_gp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __wait_rcu_gp(bool checktiny, int n, call_rcu_func_t *crcu_array, struct rcu_synchronize *rs_array);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff811729a0)
Location: kernel/rcu/update.c:371
Inline: False
Direct callers:
  - kernel/rcu/update.c:synchronize_rcu_tasks_trace
  - kernel/rcu/update.c:synchronize_rcu_tasks_rude
  - kernel/rcu/update.c:synchronize_rcu_tasks
  - kernel/rcu/tree.c:synchronize_rcu_expedited
```
**Symbols:**

```
ffffffff811729a0-ffffffff81172af5: __wait_rcu_gp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __wait_rcu_gp(bool checktiny, int n, call_rcu_func_t *crcu_array, struct rcu_synchronize *rs_array);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff811a9360)
Location: kernel/rcu/update.c:371
Inline: False
Direct callers:
  - kernel/rcu/update.c:synchronize_rcu_tasks_generic
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:cond_synchronize_rcu_full
  - kernel/rcu/tree.c:synchronize_rcu
  - kernel/rcu/tree.c:kvfree_call_rcu
```
**Symbols:**

```
ffffffff811a9360-ffffffff811a94b5: __wait_rcu_gp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __wait_rcu_gp(bool checktiny, int n, call_rcu_func_t *crcu_array, struct rcu_synchronize *rs_array);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff811bb0b0)
Location: kernel/rcu/update.c:410
Inline: False
Direct callers:
  - kernel/rcu/update.c:synchronize_rcu_tasks_generic
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:synchronize_rcu
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_free
```
**Symbols:**

```
ffffffff811bb0b0-ffffffff811bb233: __wait_rcu_gp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __wait_rcu_gp(bool checktiny, int n, call_rcu_func_t *crcu_array, struct rcu_synchronize *rs_array);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff811cb070)
Location: kernel/rcu/update.c:411
Inline: False
Direct callers:
  - kernel/rcu/update.c:synchronize_rcu_tasks_generic
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:synchronize_rcu
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_free
```
**Symbols:**

```
ffffffff811cb070-ffffffff811cb1f3: __wait_rcu_gp (STB_GLOBAL)
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
void __wait_rcu_gp(bool checktiny, int n, call_rcu_func_t *crcu_array, struct rcu_synchronize *rs_array);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffff800010188858)
Location: kernel/rcu/update.c:343
Inline: False
Direct callers:
  - kernel/rcu/update.c:rcu_barrier_tasks
  - kernel/rcu/tree.c:synchronize_rcu_expedited
```
**Symbols:**

```
ffff800010188858-ffff8000101889e0: __wait_rcu_gp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __wait_rcu_gp(bool checktiny, int n, call_rcu_func_t *crcu_array, struct rcu_synchronize *rs_array);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (c03d71b8)
Location: kernel/rcu/update.c:343
Inline: False
Direct callers:
  - kernel/rcu/update.c:rcu_barrier_tasks
  - kernel/rcu/tree.c:synchronize_rcu_expedited
```
**Symbols:**

```
c03d71b8-c03d7348: __wait_rcu_gp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __wait_rcu_gp(bool checktiny, int n, call_rcu_func_t *crcu_array, struct rcu_synchronize *rs_array);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (c0000000001e2a10)
Location: kernel/rcu/update.c:343
Inline: False
Direct callers:
  - kernel/rcu/update.c:rcu_barrier_tasks
  - kernel/rcu/update.c:synchronize_rcu_tasks
  - kernel/rcu/tree.c:synchronize_rcu_expedited
```
**Symbols:**

```
c0000000001e2a10-c0000000001e2c34: __wait_rcu_gp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __wait_rcu_gp(bool checktiny, int n, call_rcu_func_t *crcu_array, struct rcu_synchronize *rs_array);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffe00011de0a)
Location: kernel/rcu/update.c:343
Inline: False
Direct callers:
  - kernel/rcu/update.c:rcu_barrier_tasks
  - kernel/rcu/tree.c:synchronize_rcu_expedited
```
**Symbols:**

```
ffffffe00011de0a-ffffffe00011df5c: __wait_rcu_gp (STB_GLOBAL)
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
void __wait_rcu_gp(bool checktiny, int n, call_rcu_func_t *crcu_array, struct rcu_synchronize *rs_array);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff8111bd20)
Location: kernel/rcu/update.c:343
Inline: False
Direct callers:
  - kernel/rcu/update.c:rcu_barrier_tasks
  - kernel/rcu/update.c:synchronize_rcu_tasks
  - kernel/rcu/tree.c:synchronize_rcu_expedited
```
**Symbols:**

```
ffffffff8111bd20-ffffffff8111be68: __wait_rcu_gp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __wait_rcu_gp(bool checktiny, int n, call_rcu_func_t *crcu_array, struct rcu_synchronize *rs_array);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff8110cd90)
Location: kernel/rcu/update.c:343
Inline: False
Direct callers:
  - kernel/rcu/update.c:rcu_barrier_tasks
  - kernel/rcu/update.c:synchronize_rcu_tasks
  - kernel/rcu/tree.c:synchronize_rcu_expedited
```
**Symbols:**

```
ffffffff8110cd90-ffffffff8110ced8: __wait_rcu_gp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __wait_rcu_gp(bool checktiny, int n, call_rcu_func_t *crcu_array, struct rcu_synchronize *rs_array);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff81119c10)
Location: kernel/rcu/update.c:343
Inline: False
Direct callers:
  - kernel/rcu/update.c:rcu_barrier_tasks
  - kernel/rcu/update.c:synchronize_rcu_tasks
  - kernel/rcu/tree.c:synchronize_rcu_expedited
```
**Symbols:**

```
ffffffff81119c10-ffffffff81119d58: __wait_rcu_gp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __wait_rcu_gp(bool checktiny, int n, call_rcu_func_t *crcu_array, struct rcu_synchronize *rs_array);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff81125380)
Location: kernel/rcu/update.c:343
Inline: False
Direct callers:
  - kernel/rcu/update.c:rcu_barrier_tasks
  - kernel/rcu/update.c:synchronize_rcu_tasks
  - kernel/rcu/tree.c:synchronize_rcu_expedited
```
**Symbols:**

```
ffffffff81125380-ffffffff811254ba: __wait_rcu_gp (STB_GLOBAL)
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
