# Function: <code>init_tg_rt_entry</code>

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
void init_tg_rt_entry(struct task_group *tg, struct rt_rq *rt_rq, struct sched_rt_entity *rt_se, int cpu, struct sched_rt_entity *parent);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810f022c)
Location: kernel/sched/rt.c:156
Inline: True
Inline callers:
  - kernel/sched/rt.c:alloc_rt_sched_group
Direct callers:
  - kernel/sched/core.c:sched_init
```
**Symbols:**

```
ffffffff810effe0-ffffffff810f005d: init_tg_rt_entry (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void init_tg_rt_entry(struct task_group *tg, struct rt_rq *rt_rq, struct sched_rt_entity *rt_se, int cpu, struct sched_rt_entity *parent);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffff800010151788)
Location: kernel/sched/rt.c:156
Inline: True
Inline callers:
  - kernel/sched/rt.c:alloc_rt_sched_group
Direct callers:
  - kernel/sched/core.c:sched_init
```
**Symbols:**

```
ffff8000101515c8-ffff80001015166c: init_tg_rt_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void init_tg_rt_entry(struct task_group *tg, struct rt_rq *rt_rq, struct sched_rt_entity *rt_se, int cpu, struct sched_rt_entity *parent);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (c039ea84)
Location: kernel/sched/rt.c:156
Inline: True
Inline callers:
  - kernel/sched/rt.c:alloc_rt_sched_group
Direct callers:
  - kernel/sched/core.c:sched_init
```
**Symbols:**

```
c039e8a8-c039e92c: init_tg_rt_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void init_tg_rt_entry(struct task_group *tg, struct rt_rq *rt_rq, struct sched_rt_entity *rt_se, int cpu, struct sched_rt_entity *parent);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (c0000000001a5068)
Location: kernel/sched/rt.c:156
Inline: True
Inline callers:
  - kernel/sched/rt.c:alloc_rt_sched_group
Direct callers:
  - kernel/sched/core.c:sched_init
```
**Symbols:**

```
c0000000001a4e70-c0000000001a4ef4: init_tg_rt_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void init_tg_rt_entry(struct task_group *tg, struct rt_rq *rt_rq, struct sched_rt_entity *rt_se, int cpu, struct sched_rt_entity *parent);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffe0000f99c6)
Location: kernel/sched/rt.c:156
Inline: True
Inline callers:
  - kernel/sched/rt.c:alloc_rt_sched_group
Direct callers:
  - kernel/sched/core.c:sched_init
```
**Symbols:**

```
ffffffe0000f9898-ffffffe0000f9930: init_tg_rt_entry (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void init_tg_rt_entry(struct task_group *tg, struct rt_rq *rt_rq, struct sched_rt_entity *rt_se, int cpu, struct sched_rt_entity *parent);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810d95ec)
Location: kernel/sched/rt.c:156
Inline: True
Inline callers:
  - kernel/sched/rt.c:alloc_rt_sched_group
Direct callers:
  - kernel/sched/core.c:sched_init
```
**Symbols:**

```
ffffffff810d93a0-ffffffff810d941d: init_tg_rt_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void init_tg_rt_entry(struct task_group *tg, struct rt_rq *rt_rq, struct sched_rt_entity *rt_se, int cpu, struct sched_rt_entity *parent);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810e675c)
Location: kernel/sched/rt.c:156
Inline: True
Inline callers:
  - kernel/sched/rt.c:alloc_rt_sched_group
Direct callers:
  - kernel/sched/core.c:sched_init
```
**Symbols:**

```
ffffffff810e6510-ffffffff810e658d: init_tg_rt_entry (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
</ul>
