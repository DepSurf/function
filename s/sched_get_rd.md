# Function: <code>sched_get_rd</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void sched_get_rd(struct root_domain *rd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff810d4280)
Location: kernel/sched/topology.c:262
Inline: False
Direct callers:
  - kernel/sched/rt.c:pull_rt_task
```
**Symbols:**

```
ffffffff810d4280-ffffffff810d428e: sched_get_rd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void sched_get_rd(struct root_domain *rd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff810dbe90)
Location: kernel/sched/topology.c:254
Inline: False
Direct callers:
  - kernel/sched/rt.c:pull_rt_task
```
**Symbols:**

```
ffffffff810dbe90-ffffffff810dbe9e: sched_get_rd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void sched_get_rd(struct root_domain *rd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff810e5ac0)
Location: kernel/sched/topology.c:448
Inline: False
Direct callers:
  - kernel/sched/rt.c:pull_rt_task
```
**Symbols:**

```
ffffffff810e5ac0-ffffffff810e5ace: sched_get_rd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void sched_get_rd(struct root_domain *rd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff810ec710)
Location: kernel/sched/topology.c:477
Inline: False
Direct callers:
  - kernel/sched/rt.c:pull_rt_task
```
**Symbols:**

```
ffffffff810ec710-ffffffff810ec71e: sched_get_rd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void sched_get_rd(struct root_domain *rd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff810f81b0)
Location: kernel/sched/topology.c:477
Inline: False
Direct callers:
  - kernel/sched/rt.c:pull_rt_task
```
**Symbols:**

```
ffffffff810f81b0-ffffffff810f81be: sched_get_rd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void sched_get_rd(struct root_domain *rd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff811021c0)
Location: kernel/sched/topology.c:475
Inline: False
Direct callers:
  - kernel/sched/rt.c:tell_cpu_to_push
```
**Symbols:**

```
ffffffff811021c0-ffffffff811021ce: sched_get_rd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void sched_get_rd(struct root_domain *rd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff81100dd0)
Location: kernel/sched/topology.c:502
Inline: False
Direct callers:
  - kernel/sched/rt.c:tell_cpu_to_push
```
**Symbols:**

```
ffffffff81100dd0-ffffffff81100dde: sched_get_rd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void sched_get_rd(struct root_domain *rd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff81103190)
Location: kernel/sched/topology.c:502
Inline: False
Direct callers:
  - kernel/sched/rt.c:pull_rt_task
```
**Symbols:**

```
ffffffff81103190-ffffffff8110319e: sched_get_rd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void sched_get_rd(struct root_domain *rd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff8111ff70)
Location: kernel/sched/topology.c:502
Inline: False
Direct callers:
  - kernel/sched/rt.c:pull_rt_task
```
**Symbols:**

```
ffffffff8111ff70-ffffffff8111ff7e: sched_get_rd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void sched_get_rd(struct root_domain *rd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8114a090)
Location: kernel/sched/topology.c:522
Inline: False
Direct callers:
  - kernel/sched/build_policy.c:pull_rt_task
```
**Symbols:**

```
ffffffff8114a090-ffffffff8114a0a4: sched_get_rd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void sched_get_rd(struct root_domain *rd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff811789f0)
Location: kernel/sched/topology.c:522
Inline: False
Direct callers:
  - kernel/sched/build_policy.c:pull_rt_task
```
**Symbols:**

```
ffffffff811789f0-ffffffff81178a04: sched_get_rd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void sched_get_rd(struct root_domain *rd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff81189690)
Location: kernel/sched/topology.c:524
Inline: False
Direct callers:
  - kernel/sched/build_policy.c:pull_rt_task
```
**Symbols:**

```
ffffffff81189690-ffffffff811896a4: sched_get_rd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void sched_get_rd(struct root_domain *rd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff81197f90)
Location: kernel/sched/topology.c:526
Inline: False
Direct callers:
  - kernel/sched/build_policy.c:pull_rt_task
```
**Symbols:**

```
ffffffff81197f90-ffffffff81197fa4: sched_get_rd (STB_GLOBAL)
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
void sched_get_rd(struct root_domain *rd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffff80001015c6d0)
Location: kernel/sched/topology.c:477
Inline: False
Direct callers:
  - kernel/sched/rt.c:pull_rt_task
```
**Symbols:**

```
ffff80001015c6d0-ffff80001015c714: sched_get_rd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void sched_get_rd(struct root_domain *rd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (c03a9148)
Location: kernel/sched/topology.c:477
Inline: False
Direct callers:
  - kernel/sched/rt.c:pull_rt_task
```
**Symbols:**

```
c03a9148-c03a9178: sched_get_rd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void sched_get_rd(struct root_domain *rd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (c0000000001b0f30)
Location: kernel/sched/topology.c:477
Inline: False
Direct callers:
  - kernel/sched/rt.c:pull_rt_task
```
**Symbols:**

```
c0000000001b0f30-c0000000001b0f4c: sched_get_rd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void sched_get_rd(struct root_domain *rd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffe0001018fc)
Location: kernel/sched/topology.c:477
Inline: False
Direct callers:
  - kernel/sched/rt.c:pull_rt_task
```
**Symbols:**

```
ffffffe0001018fc-ffffffe000101922: sched_get_rd (STB_GLOBAL)
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
void sched_get_rd(struct root_domain *rd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff810f15b0)
Location: kernel/sched/topology.c:477
Inline: False
Direct callers:
  - kernel/sched/rt.c:pull_rt_task
```
**Symbols:**

```
ffffffff810f15b0-ffffffff810f15be: sched_get_rd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void sched_get_rd(struct root_domain *rd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff810e1620)
Location: kernel/sched/topology.c:477
Inline: False
Direct callers:
  - kernel/sched/rt.c:pull_rt_task
```
**Symbols:**

```
ffffffff810e1620-ffffffff810e162e: sched_get_rd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void sched_get_rd(struct root_domain *rd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff810ee6e0)
Location: kernel/sched/topology.c:477
Inline: False
Direct callers:
  - kernel/sched/rt.c:pull_rt_task
```
**Symbols:**

```
ffffffff810ee6e0-ffffffff810ee6ee: sched_get_rd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void sched_get_rd(struct root_domain *rd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff810f9720)
Location: kernel/sched/topology.c:477
Inline: False
Direct callers:
  - kernel/sched/rt.c:pull_rt_task
```
**Symbols:**

```
ffffffff810f9720-ffffffff810f972e: sched_get_rd (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
