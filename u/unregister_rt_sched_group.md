# Function: <code>unregister_rt_sched_group</code>

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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void unregister_rt_sched_group(struct task_group *tg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff81114b70)
Location: kernel/sched/rt.c:262
Inline: True
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_css_free
  - kernel/sched/core.c:sched_unregister_group_rcu
```
**Symbols:**

```
ffffffff81114b70-ffffffff81114b7b: unregister_rt_sched_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void unregister_rt_sched_group(struct task_group *tg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff81133a50)
Location: kernel/sched/rt.c:309
Inline: True
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_css_free
  - kernel/sched/core.c:sched_unregister_group_rcu
```
**Symbols:**

```
ffffffff81133a50-ffffffff81133a5f: unregister_rt_sched_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void unregister_rt_sched_group(struct task_group *tg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff8115ded0)
Location: kernel/sched/rt.c:309
Inline: True
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_css_free
  - kernel/sched/core.c:sched_unregister_group_rcu
```
**Symbols:**

```
ffffffff8115ded0-ffffffff8115dedf: unregister_rt_sched_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void unregister_rt_sched_group(struct task_group *tg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff8116e5b0)
Location: kernel/sched/rt.c:309
Inline: True
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_css_free
  - kernel/sched/core.c:sched_unregister_group_rcu
```
**Symbols:**

```
ffffffff8116e5b0-ffffffff8116e5bf: unregister_rt_sched_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void unregister_rt_sched_group(struct task_group *tg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff8117bb80)
Location: kernel/sched/rt.c:312
Inline: True
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_css_free
  - kernel/sched/core.c:sched_unregister_group_rcu
```
**Symbols:**

```
ffffffff8117bb80-ffffffff8117bb8f: unregister_rt_sched_group (STB_GLOBAL)
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
