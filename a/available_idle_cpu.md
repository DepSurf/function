# Function: <code>available_idle_cpu</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int available_idle_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810c14c0)
Location: kernel/sched/core.c:4041
Inline: False
Direct callers:
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:__update_idle_core
```
**Symbols:**

```
ffffffff810c14c0-ffffffff810c1513: available_idle_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int available_idle_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810ca7f0)
Location: kernel/sched/core.c:4026
Inline: False
Direct callers:
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:__update_idle_core
```
**Symbols:**

```
ffffffff810ca7f0-ffffffff810ca843: available_idle_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int available_idle_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d24a0)
Location: kernel/sched/core.c:4445
Inline: False
Direct callers:
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:__update_idle_core
  - kernel/sched/fair.c:find_idlest_cpu
```
**Symbols:**

```
ffffffff810d24a0-ffffffff810d24f2: available_idle_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int available_idle_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810dc910)
Location: kernel/sched/core.c:4647
Inline: False
Direct callers:
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:__update_idle_core
  - kernel/sched/fair.c:find_idlest_cpu
```
**Symbols:**

```
ffffffff810dc910-ffffffff810dc962: available_idle_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int available_idle_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810e5490)
Location: kernel/sched/core.c:4880
Inline: False
Direct callers:
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:select_idle_capacity
  - kernel/sched/fair.c:select_idle_cpu
  - kernel/sched/fair.c:select_idle_smt
  - kernel/sched/fair.c:select_idle_core
  - kernel/sched/fair.c:__update_idle_core
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/fair.c:wake_affine
  - kernel/sched/fair.c:wake_affine
```
**Symbols:**

```
ffffffff810e5490-ffffffff810e54e5: available_idle_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int available_idle_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810e2f40)
Location: kernel/sched/core.c:5653
Inline: False
Direct callers:
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:select_idle_capacity
  - kernel/sched/fair.c:select_idle_cpu
  - kernel/sched/fair.c:select_idle_smt
  - kernel/sched/fair.c:select_idle_core
  - kernel/sched/fair.c:__update_idle_core
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/fair.c:wake_affine
  - kernel/sched/fair.c:wake_affine
  - kernel/sched/fair.c:wake_affine
```
**Symbols:**

```
ffffffff810e2f40-ffffffff810e2f95: available_idle_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int available_idle_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810e4e10)
Location: kernel/sched/core.c:5868
Inline: False
Direct callers:
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:select_idle_cpu
  - kernel/sched/fair.c:select_idle_core
  - kernel/sched/fair.c:select_idle_core
  - kernel/sched/fair.c:__update_idle_core
  - kernel/sched/fair.c:find_idlest_cpu
  - kernel/sched/fair.c:wake_affine
  - kernel/sched/fair.c:wake_affine
  - kernel/sched/fair.c:wake_affine
```
**Symbols:**

```
ffffffff810e4e10-ffffffff810e4e65: available_idle_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int available_idle_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810fbd10)
Location: kernel/sched/core.c:7031
Inline: False
Direct callers:
  - kernel/sched/fair.c:find_idlest_group
  - kernel/sched/fair.c:task_hot
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:select_idle_cpu
  - kernel/sched/fair.c:select_idle_core
  - kernel/sched/fair.c:select_idle_core
  - kernel/sched/fair.c:__update_idle_core
  - kernel/sched/fair.c:find_idlest_group_cpu
  - kernel/sched/fair.c:find_idlest_group_cpu
  - kernel/sched/fair.c:wake_affine
  - kernel/sched/fair.c:wake_affine
  - kernel/sched/fair.c:wake_affine
```
**Symbols:**

```
ffffffff810fbd10-ffffffff810fbd84: available_idle_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int available_idle_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff811181b0)
Location: kernel/sched/core.c:7123
Inline: False
Direct callers:
  - kernel/sched/fair.c:find_idlest_group
  - kernel/sched/fair.c:task_hot
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:select_idle_cpu
  - kernel/sched/fair.c:select_idle_core
  - kernel/sched/fair.c:select_idle_core
  - kernel/sched/fair.c:__update_idle_core
  - kernel/sched/fair.c:find_idlest_group_cpu
  - kernel/sched/fair.c:find_idlest_group_cpu
  - kernel/sched/fair.c:wake_affine
  - kernel/sched/fair.c:wake_affine
  - kernel/sched/fair.c:wake_affine
```
**Symbols:**

```
ffffffff811181b0-ffffffff8111823b: available_idle_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int available_idle_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff8113f820)
Location: kernel/sched/core.c:7264
Inline: False
Direct callers:
  - kernel/sched/fair.c:find_idlest_group
  - kernel/sched/fair.c:task_hot
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:select_idle_capacity
  - kernel/sched/fair.c:select_idle_cpu
  - kernel/sched/fair.c:select_idle_core
  - kernel/sched/fair.c:__update_idle_core
  - kernel/sched/fair.c:find_idlest_group_cpu
  - kernel/sched/fair.c:find_idlest_group_cpu
  - kernel/sched/fair.c:wake_affine
  - kernel/sched/fair.c:wake_affine
  - kernel/sched/fair.c:wake_affine
```
**Symbols:**

```
ffffffff8113f820-ffffffff8113f8b1: available_idle_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int available_idle_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff8114bd70)
Location: kernel/sched/core.c:7365
Inline: False
Direct callers:
  - kernel/sched/fair.c:find_idlest_group
  - kernel/sched/fair.c:task_hot
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:select_idle_capacity
  - kernel/sched/fair.c:select_idle_cpu
  - kernel/sched/fair.c:select_idle_core
  - kernel/sched/fair.c:__update_idle_core
  - kernel/sched/fair.c:find_idlest_group_cpu
  - kernel/sched/fair.c:find_idlest_group_cpu
  - kernel/sched/fair.c:wake_affine
  - kernel/sched/fair.c:wake_affine
  - kernel/sched/fair.c:wake_affine
```
**Symbols:**

```
ffffffff8114bd70-ffffffff8114be01: available_idle_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int available_idle_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81157b20)
Location: kernel/sched/core.c:7415
Inline: False
Direct callers:
  - kernel/sched/fair.c:find_idlest_group
  - kernel/sched/fair.c:task_hot
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:select_idle_capacity
  - kernel/sched/fair.c:select_idle_cpu
  - kernel/sched/fair.c:select_idle_cpu
  - kernel/sched/fair.c:select_idle_core
  - kernel/sched/fair.c:__update_idle_core
  - kernel/sched/fair.c:find_idlest_group_cpu
  - kernel/sched/fair.c:find_idlest_group_cpu
  - kernel/sched/fair.c:wake_affine
  - kernel/sched/fair.c:wake_affine
  - kernel/sched/fair.c:wake_affine
```
**Symbols:**

```
ffffffff81157b20-ffffffff81157bb1: available_idle_cpu (STB_GLOBAL)
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
int available_idle_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffff80001013c470)
Location: kernel/sched/core.c:4647
Inline: False
Direct callers:
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:__update_idle_core
  - kernel/sched/fair.c:find_idlest_cpu
```
**Symbols:**

```
ffff80001013c470-ffff80001013c4e4: available_idle_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int available_idle_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (c038c190)
Location: kernel/sched/core.c:4647
Inline: False
Direct callers:
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:find_idlest_cpu
```
**Symbols:**

```
c038c190-c038c1f0: available_idle_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int available_idle_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (c00000000018aa80)
Location: kernel/sched/core.c:4647
Inline: False
Direct callers:
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:__update_idle_core
  - kernel/sched/fair.c:find_idlest_cpu
```
**Symbols:**

```
c00000000018aa80-c00000000018ab34: available_idle_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int available_idle_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffe0000eb7fa)
Location: kernel/sched/core.c:4647
Inline: False
Direct callers:
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:find_idlest_cpu
```
**Symbols:**

```
ffffffe0000eb7fa-ffffffe0000eb85c: available_idle_cpu (STB_GLOBAL)
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
int available_idle_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d6b20)
Location: kernel/sched/core.c:4647
Inline: False
Direct callers:
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:__update_idle_core
  - kernel/sched/fair.c:find_idlest_cpu
```
**Symbols:**

```
ffffffff810d6b20-ffffffff810d6b72: available_idle_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int available_idle_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810c5410)
Location: kernel/sched/core.c:4647
Inline: False
Direct callers:
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:__update_idle_core
  - kernel/sched/fair.c:find_idlest_cpu
```
**Symbols:**

```
ffffffff810c5410-ffffffff810c5462: available_idle_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int available_idle_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d3760)
Location: kernel/sched/core.c:4647
Inline: False
Direct callers:
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:__update_idle_core
  - kernel/sched/fair.c:find_idlest_cpu
```
**Symbols:**

```
ffffffff810d3760-ffffffff810d37b2: available_idle_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int available_idle_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810de6e0)
Location: kernel/sched/core.c:4647
Inline: False
Direct callers:
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:__update_idle_core
  - kernel/sched/fair.c:find_idlest_cpu
```
**Symbols:**

```
ffffffff810de6e0-ffffffff810de732: available_idle_cpu (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
