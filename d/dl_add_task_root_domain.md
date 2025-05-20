# Function: <code>dl_add_task_root_domain</code>

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
<summary>In <code>5.4</code>: ✅</summary>

```c
void dl_add_task_root_domain(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810f45d0)
Location: kernel/sched/deadline.c:2294
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:update_tasks_root_domain
```
**Symbols:**

```
ffffffff810f45d0-ffffffff810f46eb: dl_add_task_root_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void dl_add_task_root_domain(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810fddc0)
Location: kernel/sched/deadline.c:2293
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:update_tasks_root_domain
```
**Symbols:**

```
ffffffff810fddc0-ffffffff810fdedb: dl_add_task_root_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void dl_add_task_root_domain(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810fc390)
Location: kernel/sched/deadline.c:2406
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:update_tasks_root_domain
```
**Symbols:**

```
ffffffff810fc390-ffffffff810fc4ab: dl_add_task_root_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void dl_add_task_root_domain(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810fe6a0)
Location: kernel/sched/deadline.c:2385
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:update_tasks_root_domain
```
**Symbols:**

```
ffffffff810fe6a0-ffffffff810fe7e2: dl_add_task_root_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void dl_add_task_root_domain(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff81119fc0)
Location: kernel/sched/deadline.c:2397
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:update_tasks_root_domain
```
**Symbols:**

```
ffffffff81119fc0-ffffffff8111a131: dl_add_task_root_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void dl_add_task_root_domain(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff81139cf0)
Location: kernel/sched/deadline.c:2550
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:update_tasks_root_domain
```
**Symbols:**

```
ffffffff81139cf0-ffffffff81139e74: dl_add_task_root_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void dl_add_task_root_domain(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff81164550)
Location: kernel/sched/deadline.c:2550
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:update_tasks_root_domain
```
**Symbols:**

```
ffffffff81164550-ffffffff811646e7: dl_add_task_root_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void dl_add_task_root_domain(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff81174cf0)
Location: kernel/sched/deadline.c:2542
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:dl_update_tasks_root_domain
```
**Symbols:**

```
ffffffff81174cf0-ffffffff81174e87: dl_add_task_root_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void dl_add_task_root_domain(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff81182ff0)
Location: kernel/sched/deadline.c:2639
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:dl_update_tasks_root_domain
```
**Symbols:**

```
ffffffff81182ff0-ffffffff81183187: dl_add_task_root_domain (STB_GLOBAL)
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
void dl_add_task_root_domain(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffff800010156a60)
Location: kernel/sched/deadline.c:2294
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:update_tasks_root_domain
```
**Symbols:**

```
ffff800010156a60-ffff800010156c0c: dl_add_task_root_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void dl_add_task_root_domain(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (c03a4718)
Location: kernel/sched/deadline.c:2294
Inline: False
```
**Symbols:**

```
c03a4718-c03a48bc: dl_add_task_root_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void dl_add_task_root_domain(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (c0000000001ab490)
Location: kernel/sched/deadline.c:2294
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:update_tasks_root_domain
```
**Symbols:**

```
c0000000001ab490-c0000000001ab6b0: dl_add_task_root_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void dl_add_task_root_domain(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffe0000fda6e)
Location: kernel/sched/deadline.c:2294
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:update_tasks_root_domain
```
**Symbols:**

```
ffffffe0000fda6e-ffffffe0000fdbf6: dl_add_task_root_domain (STB_GLOBAL)
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
void dl_add_task_root_domain(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810ed9d0)
Location: kernel/sched/deadline.c:2294
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:update_tasks_root_domain
```
**Symbols:**

```
ffffffff810ed9d0-ffffffff810edaeb: dl_add_task_root_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void dl_add_task_root_domain(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810dda60)
Location: kernel/sched/deadline.c:2294
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:update_tasks_root_domain
```
**Symbols:**

```
ffffffff810dda60-ffffffff810ddb7b: dl_add_task_root_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void dl_add_task_root_domain(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810eab00)
Location: kernel/sched/deadline.c:2294
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:update_tasks_root_domain
```
**Symbols:**

```
ffffffff810eab00-ffffffff810eac1b: dl_add_task_root_domain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void dl_add_task_root_domain(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810f5ab0)
Location: kernel/sched/deadline.c:2294
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:update_tasks_root_domain
```
**Symbols:**

```
ffffffff810f5ab0-ffffffff810f5bc4: dl_add_task_root_domain (STB_GLOBAL)
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
