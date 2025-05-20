# Function: <code>padata_alloc_pd</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct parallel_data *padata_alloc_pd(struct padata_instance *pinst, const struct cpumask *pcpumask, const struct cpumask *cbcpumask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/padata.c (ffffffff8118a260)
Location: kernel/padata.c:408
Inline: False
Direct callers:
  - kernel/padata.c:__padata_set_cpumasks
  - kernel/padata.c:padata_alloc
```
**Symbols:**

```
ffffffff8118a260-ffffffff8118a471: padata_alloc_pd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct parallel_data *padata_alloc_pd(struct padata_instance *pinst, const struct cpumask *pcpumask, const struct cpumask *cbcpumask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/padata.c (ffffffff8119c920)
Location: kernel/padata.c:408
Inline: False
Direct callers:
  - kernel/padata.c:padata_alloc
  - kernel/padata.c:padata_cpu_callback
  - kernel/padata.c:padata_set_cpumask
  - kernel/padata.c:padata_set_cpumask
```
**Symbols:**

```
ffffffff8119c920-ffffffff8119cb42: padata_alloc_pd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct parallel_data *padata_alloc_pd(struct padata_instance *pinst, const struct cpumask *pcpumask, const struct cpumask *cbcpumask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/padata.c (ffffffff811abe50)
Location: kernel/padata.c:405
Inline: False
Direct callers:
  - kernel/padata.c:padata_alloc
  - kernel/padata.c:padata_cpu_online
  - kernel/padata.c:padata_set_cpumask
```
**Symbols:**

```
ffffffff811abe50-ffffffff811ac096: padata_alloc_pd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct parallel_data *padata_alloc_pd(struct padata_instance *pinst, const struct cpumask *pcpumask, const struct cpumask *cbcpumask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/padata.c (ffffffff811b32b0)
Location: kernel/padata.c:401
Inline: False
Direct callers:
  - kernel/padata.c:padata_alloc_possible
  - kernel/padata.c:padata_cpu_online
  - kernel/padata.c:padata_set_cpumask
```
**Symbols:**

```
ffffffff811b32b0-ffffffff811b3506: padata_alloc_pd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct parallel_data *padata_alloc_pd(struct padata_instance *pinst, const struct cpumask *pcpumask, const struct cpumask *cbcpumask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/padata.c (ffffffff811c6f00)
Location: kernel/padata.c:466
Inline: False
Direct callers:
  - kernel/padata.c:padata_alloc_possible
  - kernel/padata.c:padata_cpu_online
  - kernel/padata.c:padata_set_cpumask
```
**Symbols:**

```
ffffffff811c6f00-ffffffff811c7172: padata_alloc_pd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct parallel_data *padata_alloc_pd(struct padata_instance *pinst, const struct cpumask *pcpumask, const struct cpumask *cbcpumask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/padata.c (ffffffff811e7150)
Location: kernel/padata.c:467
Inline: False
Direct callers:
  - kernel/padata.c:padata_alloc_possible
  - kernel/padata.c:padata_cpu_online
  - kernel/padata.c:padata_set_cpumask
```
**Symbols:**

```
ffffffff811e7150-ffffffff811e73c9: padata_alloc_pd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct parallel_data *padata_alloc_pd(struct padata_instance *pinst, const struct cpumask *pcpumask, const struct cpumask *cbcpumask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/padata.c (ffffffff811f7ea0)
Location: kernel/padata.c:467
Inline: False
Direct callers:
  - kernel/padata.c:padata_alloc_possible
  - kernel/padata.c:padata_cpu_online
  - kernel/padata.c:padata_set_cpumask
```
**Symbols:**

```
ffffffff811f7ea0-ffffffff811f8119: padata_alloc_pd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct parallel_data *padata_alloc_pd(struct padata_instance *pinst, const struct cpumask *pcpumask, const struct cpumask *cbcpumask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/padata.c (ffffffff8120fd30)
Location: kernel/padata.c:479
Inline: False
Direct callers:
  - kernel/padata.c:padata_cpu_online
  - kernel/padata.c:__padata_remove_cpu
  - kernel/padata.c:padata_set_cpumask
```
**Symbols:**

```
ffffffff8120fd30-ffffffff8120ffa9: padata_alloc_pd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct parallel_data *padata_alloc_pd(struct padata_shell *ps);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/padata.c (ffffffff8121d760)
Location: kernel/padata.c:429
Inline: False
Direct callers:
  - kernel/padata.c:padata_alloc_shell
  - kernel/padata.c:padata_replace
```
**Symbols:**

```
ffffffff8121d760-ffffffff8121d9b9: padata_alloc_pd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct parallel_data *padata_alloc_pd(struct padata_shell *ps);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/padata.c (ffffffff812498b0)
Location: kernel/padata.c:594
Inline: False
Direct callers:
  - kernel/padata.c:padata_alloc_shell
  - kernel/padata.c:padata_replace
```
**Symbols:**

```
ffffffff812498b0-ffffffff81249acb: padata_alloc_pd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct parallel_data *padata_alloc_pd(struct padata_shell *ps);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/padata.c (ffffffff81253aa0)
Location: kernel/padata.c:566
Inline: False
Direct callers:
  - kernel/padata.c:padata_alloc_shell
  - kernel/padata.c:padata_replace
```
**Symbols:**

```
ffffffff81253aa0-ffffffff81253ca3: padata_alloc_pd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct parallel_data *padata_alloc_pd(struct padata_shell *ps);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/padata.c (ffffffff81258130)
Location: kernel/padata.c:566
Inline: False
Direct callers:
  - kernel/padata.c:padata_alloc_shell
  - kernel/padata.c:padata_replace
```
**Symbols:**

```
ffffffff81258130-ffffffff8125833c: padata_alloc_pd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct parallel_data *padata_alloc_pd(struct padata_shell *ps);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/padata.c (ffffffff81293ca0)
Location: kernel/padata.c:553
Inline: False
Direct callers:
  - kernel/padata.c:padata_alloc_shell
  - kernel/padata.c:padata_replace
```
**Symbols:**

```
ffffffff81293ca0-ffffffff81293f1a: padata_alloc_pd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct parallel_data *padata_alloc_pd(struct padata_shell *ps);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/padata.c (ffffffff812e9ce0)
Location: kernel/padata.c:553
Inline: False
Direct callers:
  - kernel/padata.c:padata_alloc_shell
  - kernel/padata.c:padata_replace
```
**Symbols:**

```
ffffffff812e9ce0-ffffffff812e9f4f: padata_alloc_pd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct parallel_data *padata_alloc_pd(struct padata_shell *ps);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/padata.c (ffffffff81353c30)
Location: kernel/padata.c:566
Inline: False
Direct callers:
  - kernel/padata.c:padata_alloc_shell
  - kernel/padata.c:padata_replace
```
**Symbols:**

```
ffffffff81353c30-ffffffff81353eaa: padata_alloc_pd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct parallel_data *padata_alloc_pd(struct padata_shell *ps);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/padata.c (ffffffff81384e30)
Location: kernel/padata.c:566
Inline: False
Direct callers:
  - kernel/padata.c:padata_alloc_shell
  - kernel/padata.c:padata_replace
```
**Symbols:**

```
ffffffff81384e30-ffffffff813850aa: padata_alloc_pd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct parallel_data *padata_alloc_pd(struct padata_shell *ps);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/padata.c (ffffffff813ae170)
Location: kernel/padata.c:566
Inline: False
Direct callers:
  - kernel/padata.c:padata_alloc_shell
  - kernel/padata.c:padata_replace
```
**Symbols:**

```
ffffffff813ae170-ffffffff813ae419: padata_alloc_pd (STB_LOCAL)
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
struct parallel_data *padata_alloc_pd(struct padata_shell *ps);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/padata.c (ffff8000102a8f20)
Location: kernel/padata.c:429
Inline: False
Direct callers:
  - kernel/padata.c:padata_alloc_shell
  - kernel/padata.c:padata_replace
```
**Symbols:**

```
ffff8000102a8f20-ffff8000102a9118: padata_alloc_pd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct parallel_data *padata_alloc_pd(struct padata_shell *ps);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/padata.c (c04d8304)
Location: kernel/padata.c:429
Inline: False
Direct callers:
  - kernel/padata.c:padata_alloc_shell
  - kernel/padata.c:padata_replace
```
**Symbols:**

```
c04d8304-c04d84e4: padata_alloc_pd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct parallel_data *padata_alloc_pd(struct padata_shell *ps);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/padata.c (c00000000035d2d0)
Location: kernel/padata.c:429
Inline: False
Direct callers:
  - kernel/padata.c:padata_alloc_shell
  - kernel/padata.c:padata_replace
```
**Symbols:**

```
c00000000035d2d0-c00000000035d58c: padata_alloc_pd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct parallel_data *padata_alloc_pd(struct padata_shell *ps);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/padata.c (ffffffe0001d23d4)
Location: kernel/padata.c:429
Inline: False
Direct callers:
  - kernel/padata.c:padata_alloc_shell
  - kernel/padata.c:padata_set_cpumask
```
**Symbols:**

```
ffffffe0001d23d4-ffffffe0001d25fe: padata_alloc_pd (STB_LOCAL)
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
struct parallel_data *padata_alloc_pd(struct padata_shell *ps);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/padata.c (ffffffff81215db0)
Location: kernel/padata.c:429
Inline: False
Direct callers:
  - kernel/padata.c:padata_alloc_shell
  - kernel/padata.c:padata_replace
```
**Symbols:**

```
ffffffff81215db0-ffffffff81216009: padata_alloc_pd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct parallel_data *padata_alloc_pd(struct padata_shell *ps);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/padata.c (ffffffff81208b10)
Location: kernel/padata.c:429
Inline: False
Direct callers:
  - kernel/padata.c:padata_alloc_shell
  - kernel/padata.c:padata_replace
```
**Symbols:**

```
ffffffff81208b10-ffffffff81208d69: padata_alloc_pd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct parallel_data *padata_alloc_pd(struct padata_shell *ps);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/padata.c (ffffffff81213b50)
Location: kernel/padata.c:429
Inline: False
Direct callers:
  - kernel/padata.c:padata_alloc_shell
  - kernel/padata.c:padata_replace
```
**Symbols:**

```
ffffffff81213b50-ffffffff81213da9: padata_alloc_pd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct parallel_data *padata_alloc_pd(struct padata_shell *ps);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/padata.c (ffffffff81222d90)
Location: kernel/padata.c:429
Inline: False
Direct callers:
  - kernel/padata.c:padata_alloc_shell
  - kernel/padata.c:padata_replace
```
**Symbols:**

```
ffffffff81222d90-ffffffff81222fe9: padata_alloc_pd (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.3</code> and <code>5.4</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct padata_shell *ps</code>
</li>
<li>
<b>Param removed. </b>
<code>struct padata_instance *pinst</code>
</li>
<li>
<b>Param removed. </b>
<code>const struct cpumask *pcpumask</code>
</li>
<li>
<b>Param removed. </b>
<code>const struct cpumask *cbcpumask</code>
</li>
</ul>
</details>
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
