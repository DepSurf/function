# Function: <code>update_tasks_root_domain</code>

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
void update_tasks_root_domain(struct cpuset *cs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff8116b8c0)
Location: kernel/cgroup/cpuset.c:910
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
**Symbols:**

```
ffffffff8116b8c0-ffffffff8116b92a: update_tasks_root_domain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void update_tasks_root_domain(struct cpuset *cs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff8117d4f0)
Location: kernel/cgroup/cpuset.c:914
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:rebuild_root_domains
```
**Symbols:**

```
ffffffff8117d4f0-ffffffff8117d54e: update_tasks_root_domain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void update_tasks_root_domain(struct cpuset *cs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff8117a340)
Location: kernel/cgroup/cpuset.c:914
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:rebuild_root_domains
```
**Symbols:**

```
ffffffff8117a340-ffffffff8117a39e: update_tasks_root_domain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void update_tasks_root_domain(struct cpuset *cs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff8117aec0)
Location: kernel/cgroup/cpuset.c:914
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
**Symbols:**

```
ffffffff8117aec0-ffffffff8117af1e: update_tasks_root_domain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void update_tasks_root_domain(struct cpuset *cs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff811a2a30)
Location: kernel/cgroup/cpuset.c:942
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
**Symbols:**

```
ffffffff811a2a30-ffffffff811a2a8e: update_tasks_root_domain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void update_tasks_root_domain(struct cpuset *cs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff811d3520)
Location: kernel/cgroup/cpuset.c:982
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
**Symbols:**

```
ffffffff811d3520-ffffffff811d35a6: update_tasks_root_domain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void update_tasks_root_domain(struct cpuset *cs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff81217460)
Location: kernel/cgroup/cpuset.c:1069
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
**Symbols:**

```
ffffffff81217460-ffffffff812174e6: update_tasks_root_domain (STB_LOCAL)
```
</details>
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
<summary>In <code>arm64</code>: ✅</summary>

```c
void update_tasks_root_domain(struct cpuset *cs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffff8000101dfda0)
Location: kernel/cgroup/cpuset.c:910
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
**Symbols:**

```
ffff8000101dfda0-ffff8000101dfe18: update_tasks_root_domain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (c0422acc)
Location: kernel/cgroup/cpuset.c:910
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void update_tasks_root_domain(struct cpuset *cs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (c00000000024e5c0)
Location: kernel/cgroup/cpuset.c:910
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
**Symbols:**

```
c00000000024e5c0-c00000000024e654: update_tasks_root_domain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void update_tasks_root_domain(struct cpuset *cs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffe000156ca2)
Location: kernel/cgroup/cpuset.c:910
Inline: False
```
**Symbols:**

```
ffffffe000156ca2-ffffffe000156cf6: update_tasks_root_domain (STB_LOCAL)
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
void update_tasks_root_domain(struct cpuset *cs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff81163ee0)
Location: kernel/cgroup/cpuset.c:910
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
**Symbols:**

```
ffffffff81163ee0-ffffffff81163f4a: update_tasks_root_domain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void update_tasks_root_domain(struct cpuset *cs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff81157130)
Location: kernel/cgroup/cpuset.c:910
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
**Symbols:**

```
ffffffff81157130-ffffffff8115719a: update_tasks_root_domain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void update_tasks_root_domain(struct cpuset *cs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff81161cb0)
Location: kernel/cgroup/cpuset.c:910
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
**Symbols:**

```
ffffffff81161cb0-ffffffff81161d1a: update_tasks_root_domain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void update_tasks_root_domain(struct cpuset *cs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff8116f140)
Location: kernel/cgroup/cpuset.c:910
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
```
**Symbols:**

```
ffffffff8116f140-ffffffff8116f1aa: update_tasks_root_domain (STB_LOCAL)
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
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
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
