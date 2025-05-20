# Function: <code>rt_task_fits_capacity</code>

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
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool rt_task_fits_capacity(struct task_struct *p, int cpu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810f73b0)
Location: kernel/sched/rt.c:457
Inline: True
```
**Symbols:**

```
ffffffff810f73b0-ffffffff810f740a: rt_task_fits_capacity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool rt_task_fits_capacity(struct task_struct *p, int cpu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810f55b0)
Location: kernel/sched/rt.c:458
Inline: True
```
**Symbols:**

```
ffffffff810f55b0-ffffffff810f560a: rt_task_fits_capacity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool rt_task_fits_capacity(struct task_struct *p, int cpu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810f7680)
Location: kernel/sched/rt.c:458
Inline: True
```
**Symbols:**

```
ffffffff810f7680-ffffffff810f76db: rt_task_fits_capacity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
bool rt_task_fits_capacity(struct task_struct *p, int cpu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff81111c50)
Location: kernel/sched/rt.c:469
Inline: True
```
**Symbols:**

```
ffffffff81111c50-ffffffff81111cd0: rt_task_fits_capacity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
bool rt_task_fits_capacity(struct task_struct *p, int cpu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff8112ea60)
Location: kernel/sched/rt.c:505
Inline: True
```
**Symbols:**

```
ffffffff8112ea60-ffffffff8112eaf4: rt_task_fits_capacity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
bool rt_task_fits_capacity(struct task_struct *p, int cpu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff81158860)
Location: kernel/sched/rt.c:505
Inline: True
```
**Symbols:**

```
ffffffff81158860-ffffffff811588f4: rt_task_fits_capacity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
bool rt_task_fits_capacity(struct task_struct *p, int cpu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff81168b40)
Location: kernel/sched/rt.c:505
Inline: True
```
**Symbols:**

```
ffffffff81168b40-ffffffff81168bd4: rt_task_fits_capacity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
bool rt_task_fits_capacity(struct task_struct *p, int cpu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff81175bd0)
Location: kernel/sched/rt.c:461
Inline: True
```
**Symbols:**

```
ffffffff81175bd0-ffffffff81175c1f: rt_task_fits_capacity (STB_LOCAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
