# Function: <code>preferred_group_nid</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810ba910)
Location: kernel/sched/fair.c:1743
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_fault
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810bde8f)
Location: kernel/sched/fair.c:1856
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_fault
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int preferred_group_nid(struct task_struct *p, int nid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810bd9e0)
Location: kernel/sched/fair.c:1988
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_numa_fault
```
**Symbols:**

```
ffffffff810bd9e0-ffffffff810be00e: preferred_group_nid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int preferred_group_nid(struct task_struct *p, int nid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810b8990)
Location: kernel/sched/fair.c:1984
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_numa_fault
```
**Symbols:**

```
ffffffff810b8990-ffffffff810b8fc4: preferred_group_nid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int preferred_group_nid(struct task_struct *p, int nid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810c07f0)
Location: kernel/sched/fair.c:2036
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_numa_fault
```
**Symbols:**

```
ffffffff810c07f0-ffffffff810c0e24: preferred_group_nid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int preferred_group_nid(struct task_struct *p, int nid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810c5e00)
Location: kernel/sched/fair.c:2064
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_numa_fault
```
**Symbols:**

```
ffffffff810c5e00-ffffffff810c640b: preferred_group_nid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int preferred_group_nid(struct task_struct *p, int nid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810d03d0)
Location: kernel/sched/fair.c:2013
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_numa_fault
```
**Symbols:**

```
ffffffff810d03d0-ffffffff810d09db: preferred_group_nid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int preferred_group_nid(struct task_struct *p, int nid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810d8300)
Location: kernel/sched/fair.c:2082
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_numa_placement
```
**Symbols:**

```
ffffffff810d8300-ffffffff810d8940: preferred_group_nid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int preferred_group_nid(struct task_struct *p, int nid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810e2c00)
Location: kernel/sched/fair.c:2040
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_numa_placement
```
**Symbols:**

```
ffffffff810e2c00-ffffffff810e3240: preferred_group_nid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int preferred_group_nid(struct task_struct *p, int nid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810ec160)
Location: kernel/sched/fair.c:2269
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_numa_placement
```
**Symbols:**

```
ffffffff810ec160-ffffffff810ec7ad: preferred_group_nid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int preferred_group_nid(struct task_struct *p, int nid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810e9c70)
Location: kernel/sched/fair.c:2283
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_numa_placement
```
**Symbols:**

```
ffffffff810e9c70-ffffffff810ea2bd: preferred_group_nid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int preferred_group_nid(struct task_struct *p, int nid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810eb570)
Location: kernel/sched/fair.c:2280
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_numa_placement
```
**Symbols:**

```
ffffffff810eb570-ffffffff810ebba2: preferred_group_nid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int preferred_group_nid(struct task_struct *p, int nid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff811030f0)
Location: kernel/sched/fair.c:2269
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_numa_placement
```
**Symbols:**

```
ffffffff811030f0-ffffffff81103722: preferred_group_nid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int preferred_group_nid(struct task_struct *p, int nid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff8111e7c0)
Location: kernel/sched/fair.c:2274
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_numa_placement
```
**Symbols:**

```
ffffffff8111e7c0-ffffffff8111ee25: preferred_group_nid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int preferred_group_nid(struct task_struct *p, int nid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff81147b80)
Location: kernel/sched/fair.c:2469
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_numa_placement
```
**Symbols:**

```
ffffffff81147b80-ffffffff811481be: preferred_group_nid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int preferred_group_nid(struct task_struct *p, int nid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff81157a20)
Location: kernel/sched/fair.c:2469
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_numa_placement
```
**Symbols:**

```
ffffffff81157a20-ffffffff81158066: preferred_group_nid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int preferred_group_nid(struct task_struct *p, int nid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff81163c70)
Location: kernel/sched/fair.c:2710
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_numa_placement
```
**Symbols:**

```
ffffffff81163c70-ffffffff811642b6: preferred_group_nid (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffff800010147900)
Location: kernel/sched/fair.c:2040
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_placement
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (c000000000193c40)
Location: kernel/sched/fair.c:2040
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_numa_placement
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int preferred_group_nid(struct task_struct *p, int nid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810dcdb0)
Location: kernel/sched/fair.c:2040
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_numa_placement
```
**Symbols:**

```
ffffffff810dcdb0-ffffffff810dd3f0: preferred_group_nid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int preferred_group_nid(struct task_struct *p, int nid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810cbdc0)
Location: kernel/sched/fair.c:2040
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_numa_placement
```
**Symbols:**

```
ffffffff810cbdc0-ffffffff810cc400: preferred_group_nid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int preferred_group_nid(struct task_struct *p, int nid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810d9130)
Location: kernel/sched/fair.c:2040
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_numa_placement
```
**Symbols:**

```
ffffffff810d9130-ffffffff810d9770: preferred_group_nid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int preferred_group_nid(struct task_struct *p, int nid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810e4b60)
Location: kernel/sched/fair.c:2040
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_numa_placement
```
**Symbols:**

```
ffffffff810e4b60-ffffffff810e51a0: preferred_group_nid (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
