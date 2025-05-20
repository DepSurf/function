# Function: <code>cpumask_any_and_distribute</code>

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
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int cpumask_any_and_distribute(const struct cpumask *src1p, const struct cpumask *src2p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cpumask.c (ffffffff815e7f00)
Location: lib/cpumask.c:246
Inline: False
Direct callers:
  - kernel/sched/core.c:__set_cpus_allowed_ptr
```
**Symbols:**

```
ffffffff815e7f00-ffffffff815e7f58: cpumask_any_and_distribute (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int cpumask_any_and_distribute(const struct cpumask *src1p, const struct cpumask *src2p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cpumask.c (ffffffff8160d060)
Location: lib/cpumask.c:246
Inline: False
Direct callers:
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/rt.c:find_lowest_rq
  - kernel/sched/deadline.c:find_later_rq
```
**Symbols:**

```
ffffffff8160d060-ffffffff8160d0bc: cpumask_any_and_distribute (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int cpumask_any_and_distribute(const struct cpumask *src1p, const struct cpumask *src2p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cpumask.c (ffffffff815f0850)
Location: lib/cpumask.c:246
Inline: False
Direct callers:
  - kernel/sched/core.c:__set_cpus_allowed_ptr
  - kernel/sched/rt.c:find_lowest_rq
  - kernel/sched/deadline.c:find_later_rq
```
**Symbols:**

```
ffffffff815f0850-ffffffff815f08c4: cpumask_any_and_distribute (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int cpumask_any_and_distribute(const struct cpumask *src1p, const struct cpumask *src2p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cpumask.c (ffffffff8165d930)
Location: lib/cpumask.c:246
Inline: False
Direct callers:
  - kernel/sched/core.c:__set_cpus_allowed_ptr_locked
  - kernel/sched/rt.c:find_lowest_rq
  - kernel/sched/deadline.c:find_later_rq
```
**Symbols:**

```
ffffffff8165d930-ffffffff8165d9a4: cpumask_any_and_distribute (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int cpumask_any_and_distribute(const struct cpumask *src1p, const struct cpumask *src2p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cpumask.c (ffffffff81776d30)
Location: lib/cpumask.c:246
Inline: False
Direct callers:
  - kernel/sched/core.c:__set_cpus_allowed_ptr_locked
  - kernel/sched/build_policy.c:find_later_rq
  - kernel/sched/build_policy.c:find_lowest_rq
```
**Symbols:**

```
ffffffff81776d30-ffffffff81776db1: cpumask_any_and_distribute (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
unsigned int cpumask_any_and_distribute(const struct cpumask *src1p, const struct cpumask *src2p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cpumask.c (ffffffff8201f7b0)
Location: lib/cpumask.c:161
Inline: False
Direct callers:
  - kernel/sched/core.c:__set_cpus_allowed_ptr_locked
  - kernel/sched/build_policy.c:find_later_rq
  - kernel/sched/build_policy.c:find_lowest_rq
```
**Symbols:**

```
ffffffff8201f7b0-ffffffff8201f826: cpumask_any_and_distribute (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
unsigned int cpumask_any_and_distribute(const struct cpumask *src1p, const struct cpumask *src2p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cpumask.c (ffffffff8209f7c0)
Location: lib/cpumask.c:170
Inline: False
Direct callers:
  - kernel/sched/core.c:__set_cpus_allowed_ptr_locked
  - kernel/sched/build_policy.c:find_later_rq
  - kernel/sched/build_policy.c:find_lowest_rq
  - kernel/bpf/cpumask.c:bpf_cpumask_any_and_distribute
```
**Symbols:**

```
ffffffff8209f7c0-ffffffff8209f836: cpumask_any_and_distribute (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
unsigned int cpumask_any_and_distribute(const struct cpumask *src1p, const struct cpumask *src2p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/cpumask.c (ffffffff82177820)
Location: lib/cpumask.c:169
Inline: False
Direct callers:
  - kernel/sched/core.c:__set_cpus_allowed_ptr_locked
  - kernel/sched/build_policy.c:find_later_rq
  - kernel/sched/build_policy.c:find_lowest_rq
  - kernel/bpf/cpumask.c:bpf_cpumask_any_and_distribute
```
**Symbols:**

```
ffffffff82177820-ffffffff82177896: cpumask_any_and_distribute (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>unsigned int</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
