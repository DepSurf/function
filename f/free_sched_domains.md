# Function: <code>free_sched_domains</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void free_sched_domains(cpumask_var_t *doms, unsigned int ndoms);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810afc90)
Location: kernel/sched/core.c:7074
Inline: True
Inline callers:
  - kernel/sched/core.c:partition_sched_domains
```
**Symbols:**

```
ffffffff810afc90-ffffffff810afca0: free_sched_domains (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void free_sched_domains(cpumask_var_t *doms, unsigned int ndoms);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b2729)
Location: kernel/sched/core.c:7009
Inline: True
Inline callers:
  - kernel/sched/core.c:partition_sched_domains
```
**Symbols:**

```
ffffffff810b2490-ffffffff810b24a0: free_sched_domains (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void free_sched_domains(cpumask_var_t *doms, unsigned int ndoms);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b89d0)
Location: kernel/sched/core.c:7130
Inline: False
Direct callers:
  - kernel/sched/core.c:partition_sched_domains
  - kernel/sched/core.c:alloc_sched_domains
```
**Symbols:**

```
ffffffff810b89d0-ffffffff810b8a10: free_sched_domains (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void free_sched_domains(cpumask_var_t *doms, unsigned int ndoms);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff810cd330)
Location: kernel/sched/topology.c:1754
Inline: False
Direct callers:
  - kernel/sched/topology.c:partition_sched_domains
  - kernel/sched/topology.c:alloc_sched_domains
```
**Symbols:**

```
ffffffff810cd330-ffffffff810cd370: free_sched_domains (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void free_sched_domains(cpumask_var_t *doms, unsigned int ndoms);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff810d4b40)
Location: kernel/sched/topology.c:1769
Inline: False
Direct callers:
  - kernel/sched/topology.c:partition_sched_domains
  - kernel/sched/topology.c:alloc_sched_domains
```
**Symbols:**

```
ffffffff810d4b40-ffffffff810d4b80: free_sched_domains (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void free_sched_domains(cpumask_var_t *doms, unsigned int ndoms);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff810dc720)
Location: kernel/sched/topology.c:1765
Inline: False
Direct callers:
  - kernel/sched/topology.c:partition_sched_domains
  - kernel/sched/topology.c:alloc_sched_domains
```
**Symbols:**

```
ffffffff810dc720-ffffffff810dc760: free_sched_domains (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void free_sched_domains(cpumask_var_t *doms, unsigned int ndoms);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff810e6380)
Location: kernel/sched/topology.c:2040
Inline: False
Direct callers:
  - kernel/sched/topology.c:partition_sched_domains
  - kernel/sched/topology.c:alloc_sched_domains
```
**Symbols:**

```
ffffffff810e6380-ffffffff810e63c0: free_sched_domains (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void free_sched_domains(cpumask_var_t *doms, unsigned int ndoms);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff810ecfa0)
Location: kernel/sched/topology.c:2065
Inline: False
Direct callers:
  - kernel/sched/topology.c:partition_sched_domains
  - kernel/sched/topology.c:alloc_sched_domains
```
**Symbols:**

```
ffffffff810ecfa0-ffffffff810ecfe0: free_sched_domains (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void free_sched_domains(cpumask_var_t *doms, unsigned int ndoms);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff810f8ad0)
Location: kernel/sched/topology.c:2128
Inline: False
Direct callers:
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:alloc_sched_domains
```
**Symbols:**

```
ffffffff810f8ad0-ffffffff810f8b10: free_sched_domains (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void free_sched_domains(cpumask_var_t *doms, unsigned int ndoms);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff81102dfa)
Location: kernel/sched/topology.c:2113
Inline: True
Inline callers:
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:alloc_sched_domains
```
**Symbols:**

```
ffffffff81102a10-ffffffff81102a50: free_sched_domains (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void free_sched_domains(cpumask_var_t *doms, unsigned int ndoms);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff81101a1a)
Location: kernel/sched/topology.c:2171
Inline: True
Inline callers:
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:alloc_sched_domains
```
**Symbols:**

```
ffffffff81101630-ffffffff81101670: free_sched_domains (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void free_sched_domains(cpumask_var_t *doms, unsigned int ndoms);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff81103d8d)
Location: kernel/sched/topology.c:2199
Inline: True
Inline callers:
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:alloc_sched_domains
```
**Symbols:**

```
ffffffff811039c0-ffffffff81103a00: free_sched_domains (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void free_sched_domains(cpumask_var_t *doms, unsigned int ndoms);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff81120de3)
Location: kernel/sched/topology.c:2328
Inline: True
Inline callers:
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:alloc_sched_domains
```
**Symbols:**

```
ffffffff811209e0-ffffffff81120a20: free_sched_domains (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void free_sched_domains(cpumask_var_t *doms, unsigned int ndoms);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8114b2b5)
Location: kernel/sched/topology.c:2435
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:partition_sched_domains_locked
  - kernel/sched/build_utility.c:alloc_sched_domains
```
**Symbols:**

```
ffffffff8114adb0-ffffffff8114adf6: free_sched_domains (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void free_sched_domains(cpumask_var_t *doms, unsigned int ndoms);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff81179cd9)
Location: kernel/sched/topology.c:2442
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:partition_sched_domains_locked
  - kernel/sched/build_utility.c:alloc_sched_domains
```
**Symbols:**

```
ffffffff811797a0-ffffffff811797e6: free_sched_domains (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void free_sched_domains(cpumask_var_t *doms, unsigned int ndoms);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8118a802)
Location: kernel/sched/topology.c:2542
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:partition_sched_domains_locked
  - kernel/sched/build_utility.c:alloc_sched_domains
```
**Symbols:**

```
ffffffff8118a390-ffffffff8118a3d6: free_sched_domains (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void free_sched_domains(cpumask_var_t *doms, unsigned int ndoms);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff81199118)
Location: kernel/sched/topology.c:2587
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:partition_sched_domains_locked
  - kernel/sched/build_utility.c:alloc_sched_domains
```
**Symbols:**

```
ffffffff81198c90-ffffffff81198cd6: free_sched_domains (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void free_sched_domains(cpumask_var_t *doms, unsigned int ndoms);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffff80001015d4cc)
Location: kernel/sched/topology.c:2128
Inline: True
Inline callers:
  - kernel/sched/topology.c:partition_sched_domains_locked
```
**Symbols:**

```
ffff80001015d1d0-ffff80001015d1fc: free_sched_domains (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void free_sched_domains(cpumask_var_t *doms, unsigned int ndoms);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (c03a9638)
Location: kernel/sched/topology.c:2128
Inline: True
Inline callers:
  - kernel/sched/topology.c:partition_sched_domains_locked
```
**Symbols:**

```
c03a92dc-c03a92f8: free_sched_domains (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void free_sched_domains(cpumask_var_t *doms, unsigned int ndoms);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (c0000000001b2110)
Location: kernel/sched/topology.c:2128
Inline: True
Inline callers:
  - kernel/sched/topology.c:partition_sched_domains_locked
```
**Symbols:**

```
c0000000001b1d00-c0000000001b1d34: free_sched_domains (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void free_sched_domains(cpumask_var_t *doms, unsigned int ndoms);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffe000101da0)
Location: kernel/sched/topology.c:2128
Inline: True
Inline callers:
  - kernel/sched/topology.c:partition_sched_domains_locked
```
**Symbols:**

```
ffffffe000101a66-ffffffe000101a90: free_sched_domains (STB_GLOBAL)
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
void free_sched_domains(cpumask_var_t *doms, unsigned int ndoms);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff810f1ed0)
Location: kernel/sched/topology.c:2128
Inline: False
Direct callers:
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:alloc_sched_domains
```
**Symbols:**

```
ffffffff810f1ed0-ffffffff810f1f10: free_sched_domains (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void free_sched_domains(cpumask_var_t *doms, unsigned int ndoms);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff810e1f40)
Location: kernel/sched/topology.c:2128
Inline: False
Direct callers:
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:alloc_sched_domains
```
**Symbols:**

```
ffffffff810e1f40-ffffffff810e1f80: free_sched_domains (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void free_sched_domains(cpumask_var_t *doms, unsigned int ndoms);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff810ef000)
Location: kernel/sched/topology.c:2128
Inline: False
Direct callers:
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:alloc_sched_domains
```
**Symbols:**

```
ffffffff810ef000-ffffffff810ef040: free_sched_domains (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void free_sched_domains(cpumask_var_t *doms, unsigned int ndoms);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/topology.c (ffffffff810fa040)
Location: kernel/sched/topology.c:2128
Inline: False
Direct callers:
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:alloc_sched_domains
```
**Symbols:**

```
ffffffff810fa040-ffffffff810fa080: free_sched_domains (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
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
