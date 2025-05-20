# Function: <code>sched_put_rd</code>

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
void sched_put_rd(struct root_domain *rd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff810d4290)
Location: kernel/sched/topology.c:267
Inline: False
Direct callers:
  - kernel/sched/rt.c:rto_push_irq_work_func
```
**Symbols:**

```
ffffffff810d4290-ffffffff810d42b2: sched_put_rd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void sched_put_rd(struct root_domain *rd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff810dbea0)
Location: kernel/sched/topology.c:259
Inline: False
Direct callers:
  - kernel/sched/rt.c:rto_push_irq_work_func
```
**Symbols:**

```
ffffffff810dbea0-ffffffff810dbec2: sched_put_rd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void sched_put_rd(struct root_domain *rd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff810e5ad0)
Location: kernel/sched/topology.c:453
Inline: False
Direct callers:
  - kernel/sched/rt.c:rto_push_irq_work_func
```
**Symbols:**

```
ffffffff810e5ad0-ffffffff810e5af2: sched_put_rd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void sched_put_rd(struct root_domain *rd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff810ec720)
Location: kernel/sched/topology.c:482
Inline: False
Direct callers:
  - kernel/sched/rt.c:rto_push_irq_work_func
```
**Symbols:**

```
ffffffff810ec720-ffffffff810ec741: sched_put_rd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void sched_put_rd(struct root_domain *rd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff810f81c0)
Location: kernel/sched/topology.c:482
Inline: False
Direct callers:
  - kernel/sched/rt.c:rto_push_irq_work_func
```
**Symbols:**

```
ffffffff810f81c0-ffffffff810f81e1: sched_put_rd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void sched_put_rd(struct root_domain *rd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff811021d0)
Location: kernel/sched/topology.c:480
Inline: False
Direct callers:
  - kernel/sched/rt.c:rto_push_irq_work_func
```
**Symbols:**

```
ffffffff811021d0-ffffffff811021f1: sched_put_rd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void sched_put_rd(struct root_domain *rd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff81100de0)
Location: kernel/sched/topology.c:507
Inline: False
Direct callers:
  - kernel/sched/rt.c:rto_push_irq_work_func
```
**Symbols:**

```
ffffffff81100de0-ffffffff81100e01: sched_put_rd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void sched_put_rd(struct root_domain *rd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff811031a0)
Location: kernel/sched/topology.c:507
Inline: False
Direct callers:
  - kernel/sched/rt.c:rto_push_irq_work_func
```
**Symbols:**

```
ffffffff811031a0-ffffffff811031c1: sched_put_rd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void sched_put_rd(struct root_domain *rd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff8111ff80)
Location: kernel/sched/topology.c:507
Inline: False
Direct callers:
  - kernel/sched/rt.c:rto_push_irq_work_func
```
**Symbols:**

```
ffffffff8111ff80-ffffffff8111ffa1: sched_put_rd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void sched_put_rd(struct root_domain *rd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8114a0b0)
Location: kernel/sched/topology.c:527
Inline: False
Direct callers:
  - kernel/sched/build_policy.c:rto_push_irq_work_func
```
**Symbols:**

```
ffffffff8114a0b0-ffffffff8114a0e1: sched_put_rd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void sched_put_rd(struct root_domain *rd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff81178a20)
Location: kernel/sched/topology.c:527
Inline: False
Direct callers:
  - kernel/sched/build_policy.c:rto_push_irq_work_func
```
**Symbols:**

```
ffffffff81178a20-ffffffff81178a51: sched_put_rd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void sched_put_rd(struct root_domain *rd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff811896c0)
Location: kernel/sched/topology.c:529
Inline: False
Direct callers:
  - kernel/sched/build_policy.c:rto_push_irq_work_func
```
**Symbols:**

```
ffffffff811896c0-ffffffff811896f1: sched_put_rd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void sched_put_rd(struct root_domain *rd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff81197fc0)
Location: kernel/sched/topology.c:531
Inline: False
Direct callers:
  - kernel/sched/build_policy.c:rto_push_irq_work_func
```
**Symbols:**

```
ffffffff81197fc0-ffffffff81197ff1: sched_put_rd (STB_GLOBAL)
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
void sched_put_rd(struct root_domain *rd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffff80001015c718)
Location: kernel/sched/topology.c:482
Inline: False
Direct callers:
  - kernel/sched/rt.c:rto_push_irq_work_func
```
**Symbols:**

```
ffff80001015c718-ffff80001015c774: sched_put_rd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void sched_put_rd(struct root_domain *rd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (c03a9178)
Location: kernel/sched/topology.c:482
Inline: False
Direct callers:
  - kernel/sched/rt.c:rto_push_irq_work_func
```
**Symbols:**

```
c03a9178-c03a91c8: sched_put_rd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void sched_put_rd(struct root_domain *rd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (c0000000001b0f50)
Location: kernel/sched/topology.c:482
Inline: False
Direct callers:
  - kernel/sched/rt.c:rto_push_irq_work_func
```
**Symbols:**

```
c0000000001b0f50-c0000000001b0fb4: sched_put_rd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void sched_put_rd(struct root_domain *rd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffe000101922)
Location: kernel/sched/topology.c:482
Inline: False
Direct callers:
  - kernel/sched/rt.c:rto_push_irq_work_func
```
**Symbols:**

```
ffffffe000101922-ffffffe00010196e: sched_put_rd (STB_GLOBAL)
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
void sched_put_rd(struct root_domain *rd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff810f15c0)
Location: kernel/sched/topology.c:482
Inline: False
Direct callers:
  - kernel/sched/rt.c:rto_push_irq_work_func
```
**Symbols:**

```
ffffffff810f15c0-ffffffff810f15e1: sched_put_rd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void sched_put_rd(struct root_domain *rd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff810e1630)
Location: kernel/sched/topology.c:482
Inline: False
Direct callers:
  - kernel/sched/rt.c:rto_push_irq_work_func
```
**Symbols:**

```
ffffffff810e1630-ffffffff810e1651: sched_put_rd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void sched_put_rd(struct root_domain *rd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff810ee6f0)
Location: kernel/sched/topology.c:482
Inline: False
Direct callers:
  - kernel/sched/rt.c:rto_push_irq_work_func
```
**Symbols:**

```
ffffffff810ee6f0-ffffffff810ee711: sched_put_rd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void sched_put_rd(struct root_domain *rd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff810f9730)
Location: kernel/sched/topology.c:482
Inline: False
Direct callers:
  - kernel/sched/rt.c:rto_push_irq_work_func
```
**Symbols:**

```
ffffffff810f9730-ffffffff810f9751: sched_put_rd (STB_GLOBAL)
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
