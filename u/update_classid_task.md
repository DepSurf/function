# Function: <code>update_classid_task</code>

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
void update_classid_task(struct task_struct *p, u32 classid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/netclassid_cgroup.c (ffffffff81976ed0)
Location: net/core/netclassid_cgroup.c:87
Inline: False
Direct callers:
  - net/core/netclassid_cgroup.c:write_classid
  - net/core/netclassid_cgroup.c:cgrp_attach
```
**Symbols:**

```
ffffffff81976ed0-ffffffff81976f60: update_classid_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void update_classid_task(struct task_struct *p, u32 classid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/netclassid_cgroup.c (ffffffff81a4bc80)
Location: net/core/netclassid_cgroup.c:87
Inline: False
Direct callers:
  - net/core/netclassid_cgroup.c:write_classid
  - net/core/netclassid_cgroup.c:cgrp_attach
```
**Symbols:**

```
ffffffff81a4bc80-ffffffff81a4bd10: update_classid_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void update_classid_task(struct task_struct *p, u32 classid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/netclassid_cgroup.c (ffffffff81a518a0)
Location: net/core/netclassid_cgroup.c:86
Inline: False
Direct callers:
  - net/core/netclassid_cgroup.c:write_classid
  - net/core/netclassid_cgroup.c:cgrp_attach
```
**Symbols:**

```
ffffffff81a518a0-ffffffff81a51930: update_classid_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/netclassid_cgroup.c (ffffffff81a3724a)
Location: net/core/netclassid_cgroup.c:86
Inline: True
Inline callers:
  - net/core/netclassid_cgroup.c:write_classid
  - net/core/netclassid_cgroup.c:cgrp_attach
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void update_classid_task(struct task_struct *p, u32 classid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/netclassid_cgroup.c (ffffffff81aecd50)
Location: net/core/netclassid_cgroup.c:83
Inline: False
Direct callers:
  - net/core/netclassid_cgroup.c:write_classid
  - net/core/netclassid_cgroup.c:cgrp_attach
```
**Symbols:**

```
ffffffff81aecd50-ffffffff81aecde0: update_classid_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/netclassid_cgroup.c (ffffffff81c6f96e)
Location: net/core/netclassid_cgroup.c:83
Inline: True
Inline callers:
  - net/core/netclassid_cgroup.c:write_classid
  - net/core/netclassid_cgroup.c:cgrp_attach
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/netclassid_cgroup.c (ffffffff81e2782e)
Location: net/core/netclassid_cgroup.c:83
Inline: True
Inline callers:
  - net/core/netclassid_cgroup.c:write_classid
  - net/core/netclassid_cgroup.c:cgrp_attach
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/netclassid_cgroup.c (ffffffff81e9ce3e)
Location: net/core/netclassid_cgroup.c:83
Inline: True
Inline callers:
  - net/core/netclassid_cgroup.c:write_classid
  - net/core/netclassid_cgroup.c:cgrp_attach
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void update_classid_task(struct task_struct *p, u32 classid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/netclassid_cgroup.c (ffffffff81f5f530)
Location: net/core/netclassid_cgroup.c:83
Inline: False
Direct callers:
  - net/core/netclassid_cgroup.c:write_classid
  - net/core/netclassid_cgroup.c:cgrp_attach
```
**Symbols:**

```
ffffffff81f5f530-ffffffff81f5f5d4: update_classid_task (STB_LOCAL)
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
void update_classid_task(struct task_struct *p, u32 classid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/netclassid_cgroup.c (ffff800010c1d780)
Location: net/core/netclassid_cgroup.c:87
Inline: False
Direct callers:
  - net/core/netclassid_cgroup.c:write_classid
  - net/core/netclassid_cgroup.c:cgrp_attach
```
**Symbols:**

```
ffff800010c1d780-ffff800010c1d874: update_classid_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void update_classid_task(struct task_struct *p, u32 classid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/netclassid_cgroup.c (c0d35370)
Location: net/core/netclassid_cgroup.c:87
Inline: False
Direct callers:
  - net/core/netclassid_cgroup.c:write_classid
  - net/core/netclassid_cgroup.c:cgrp_attach
```
**Symbols:**

```
c0d35370-c0d35424: update_classid_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void update_classid_task(struct task_struct *p, u32 classid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/netclassid_cgroup.c (c000000000d0ea70)
Location: net/core/netclassid_cgroup.c:87
Inline: False
Direct callers:
  - net/core/netclassid_cgroup.c:write_classid
  - net/core/netclassid_cgroup.c:cgrp_attach
```
**Symbols:**

```
c000000000d0ea70-c000000000d0eb94: update_classid_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void update_classid_task(struct task_struct *p, u32 classid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/netclassid_cgroup.c (ffffffe00079734e)
Location: net/core/netclassid_cgroup.c:87
Inline: False
Direct callers:
  - net/core/netclassid_cgroup.c:write_classid
  - net/core/netclassid_cgroup.c:cgrp_attach
```
**Symbols:**

```
ffffffe00079734e-ffffffe000797408: update_classid_task (STB_LOCAL)
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
void update_classid_task(struct task_struct *p, u32 classid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/netclassid_cgroup.c (ffffffff81916d40)
Location: net/core/netclassid_cgroup.c:87
Inline: False
Direct callers:
  - net/core/netclassid_cgroup.c:write_classid
  - net/core/netclassid_cgroup.c:cgrp_attach
```
**Symbols:**

```
ffffffff81916d40-ffffffff81916dd0: update_classid_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void update_classid_task(struct task_struct *p, u32 classid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/netclassid_cgroup.c (ffffffff818d0af0)
Location: net/core/netclassid_cgroup.c:87
Inline: False
Direct callers:
  - net/core/netclassid_cgroup.c:write_classid
  - net/core/netclassid_cgroup.c:cgrp_attach
```
**Symbols:**

```
ffffffff818d0af0-ffffffff818d0b80: update_classid_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void update_classid_task(struct task_struct *p, u32 classid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/netclassid_cgroup.c (ffffffff81967ed0)
Location: net/core/netclassid_cgroup.c:87
Inline: False
Direct callers:
  - net/core/netclassid_cgroup.c:write_classid
  - net/core/netclassid_cgroup.c:cgrp_attach
```
**Symbols:**

```
ffffffff81967ed0-ffffffff81967f60: update_classid_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void update_classid_task(struct task_struct *p, u32 classid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/netclassid_cgroup.c (ffffffff8198a050)
Location: net/core/netclassid_cgroup.c:87
Inline: False
Direct callers:
  - net/core/netclassid_cgroup.c:write_classid
  - net/core/netclassid_cgroup.c:cgrp_attach
```
**Symbols:**

```
ffffffff8198a050-ffffffff8198a0d9: update_classid_task (STB_LOCAL)
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
