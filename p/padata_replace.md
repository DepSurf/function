# Function: <code>padata_replace</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void padata_replace(struct padata_instance *pinst, struct parallel_data *pd_new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/padata.c (ffffffff81189f60)
Location: kernel/padata.c:503
Inline: False
Direct callers:
  - kernel/padata.c:__padata_set_cpumasks
```
**Symbols:**

```
ffffffff81189f60-ffffffff8118a08d: padata_replace (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void padata_replace(struct padata_instance *pinst, struct parallel_data *pd_new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/padata.c (ffffffff8119c660)
Location: kernel/padata.c:503
Inline: False
Direct callers:
  - kernel/padata.c:padata_cpu_callback
  - kernel/padata.c:padata_set_cpumask
  - kernel/padata.c:padata_set_cpumask
```
**Symbols:**

```
ffffffff8119c660-ffffffff8119c78d: padata_replace (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void padata_replace(struct padata_instance *pinst, struct parallel_data *pd_new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/padata.c (ffffffff811ac480)
Location: kernel/padata.c:500
Inline: False
Direct callers:
  - kernel/padata.c:padata_cpu_online
  - kernel/padata.c:padata_set_cpumask
```
**Symbols:**

```
ffffffff811ac480-ffffffff811ac566: padata_replace (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void padata_replace(struct padata_instance *pinst, struct parallel_data *pd_new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/padata.c (ffffffff811b39d0)
Location: kernel/padata.c:496
Inline: False
Direct callers:
  - kernel/padata.c:padata_cpu_online
  - kernel/padata.c:padata_set_cpumask
```
**Symbols:**

```
ffffffff811b39d0-ffffffff811b3ab6: padata_replace (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void padata_replace(struct padata_instance *pinst, struct parallel_data *pd_new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/padata.c (ffffffff811c7660)
Location: kernel/padata.c:561
Inline: False
Direct callers:
  - kernel/padata.c:padata_cpu_online
  - kernel/padata.c:padata_set_cpumask
```
**Symbols:**

```
ffffffff811c7660-ffffffff811c7746: padata_replace (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void padata_replace(struct padata_instance *pinst, struct parallel_data *pd_new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/padata.c (ffffffff811e78b0)
Location: kernel/padata.c:562
Inline: False
Direct callers:
  - kernel/padata.c:padata_cpu_online
  - kernel/padata.c:padata_set_cpumask
```
**Symbols:**

```
ffffffff811e78b0-ffffffff811e7995: padata_replace (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void padata_replace(struct padata_instance *pinst, struct parallel_data *pd_new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/padata.c (ffffffff811f8800)
Location: kernel/padata.c:562
Inline: False
Direct callers:
  - kernel/padata.c:padata_cpu_online
  - kernel/padata.c:padata_set_cpumask
```
**Symbols:**

```
ffffffff811f8800-ffffffff811f88e5: padata_replace (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void padata_replace(struct padata_instance *pinst, struct parallel_data *pd_new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/padata.c (ffffffff812102a0)
Location: kernel/padata.c:574
Inline: False
Direct callers:
  - kernel/padata.c:padata_cpu_online
  - kernel/padata.c:__padata_remove_cpu
  - kernel/padata.c:padata_set_cpumask
```
**Symbols:**

```
ffffffff812102a0-ffffffff81210386: padata_replace (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int padata_replace(struct padata_instance *pinst);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/padata.c (ffffffff8121da70)
Location: kernel/padata.c:515
Inline: False
Direct callers:
  - kernel/padata.c:padata_cpu_online
  - kernel/padata.c:padata_set_cpumask
```
**Symbols:**

```
ffffffff8121da70-ffffffff8121dbe1: padata_replace (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int padata_replace(struct padata_instance *pinst);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/padata.c (ffffffff81249ad0)
Location: kernel/padata.c:679
Inline: False
Direct callers:
  - kernel/padata.c:padata_cpu_dead
  - kernel/padata.c:padata_cpu_online
  - kernel/padata.c:__padata_set_cpumasks
```
**Symbols:**

```
ffffffff81249ad0-ffffffff81249bd5: padata_replace (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int padata_replace(struct padata_instance *pinst);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/padata.c (ffffffff81253d60)
Location: kernel/padata.c:654
Inline: False
Direct callers:
  - kernel/padata.c:padata_cpu_dead
  - kernel/padata.c:padata_cpu_online
  - kernel/padata.c:__padata_set_cpumasks
```
**Symbols:**

```
ffffffff81253d60-ffffffff81253e31: padata_replace (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int padata_replace(struct padata_instance *pinst);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/padata.c (ffffffff812583f0)
Location: kernel/padata.c:654
Inline: False
Direct callers:
  - kernel/padata.c:padata_cpu_dead
  - kernel/padata.c:padata_cpu_online
  - kernel/padata.c:padata_set_cpumask
```
**Symbols:**

```
ffffffff812583f0-ffffffff812584c1: padata_replace (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int padata_replace(struct padata_instance *pinst);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/padata.c (ffffffff81293fd0)
Location: kernel/padata.c:641
Inline: False
Direct callers:
  - kernel/padata.c:padata_cpu_dead
  - kernel/padata.c:padata_cpu_online
  - kernel/padata.c:padata_set_cpumask
```
**Symbols:**

```
ffffffff81293fd0-ffffffff812940e1: padata_replace (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int padata_replace(struct padata_instance *pinst);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/padata.c (ffffffff812ea000)
Location: kernel/padata.c:641
Inline: False
Direct callers:
  - kernel/padata.c:padata_cpu_dead
  - kernel/padata.c:padata_cpu_online
  - kernel/padata.c:padata_set_cpumask
```
**Symbols:**

```
ffffffff812ea000-ffffffff812ea11f: padata_replace (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int padata_replace(struct padata_instance *pinst);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/padata.c (ffffffff81353ec0)
Location: kernel/padata.c:654
Inline: False
Direct callers:
  - kernel/padata.c:padata_cpu_dead
  - kernel/padata.c:padata_cpu_online
  - kernel/padata.c:padata_set_cpumask
```
**Symbols:**

```
ffffffff81353ec0-ffffffff81353fdf: padata_replace (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int padata_replace(struct padata_instance *pinst);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/padata.c (ffffffff813850c0)
Location: kernel/padata.c:654
Inline: False
Direct callers:
  - kernel/padata.c:padata_cpu_dead
  - kernel/padata.c:padata_cpu_online
  - kernel/padata.c:padata_set_cpumask
```
**Symbols:**

```
ffffffff813850c0-ffffffff813851df: padata_replace (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int padata_replace(struct padata_instance *pinst);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/padata.c (ffffffff813ae430)
Location: kernel/padata.c:654
Inline: False
Direct callers:
  - kernel/padata.c:padata_cpu_dead
  - kernel/padata.c:padata_cpu_online
  - kernel/padata.c:padata_set_cpumask
```
**Symbols:**

```
ffffffff813ae430-ffffffff813ae54f: padata_replace (STB_LOCAL)
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
int padata_replace(struct padata_instance *pinst);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/padata.c (ffff8000102a91c8)
Location: kernel/padata.c:515
Inline: False
Direct callers:
  - kernel/padata.c:padata_cpu_online
  - kernel/padata.c:padata_set_cpumask
  - kernel/padata.c:padata_set_cpumask
```
**Symbols:**

```
ffff8000102a91c8-ffff8000102a93e0: padata_replace (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int padata_replace(struct padata_instance *pinst);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/padata.c (c04d8588)
Location: kernel/padata.c:515
Inline: False
Direct callers:
  - kernel/padata.c:padata_cpu_online
  - kernel/padata.c:padata_set_cpumask
  - kernel/padata.c:padata_set_cpumask
```
**Symbols:**

```
c04d8588-c04d86dc: padata_replace (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int padata_replace(struct padata_instance *pinst);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/padata.c (c00000000035d590)
Location: kernel/padata.c:515
Inline: False
Direct callers:
  - kernel/padata.c:padata_cpu_online
  - kernel/padata.c:padata_set_cpumask
  - kernel/padata.c:padata_set_cpumask
```
**Symbols:**

```
c00000000035d590-c00000000035d7d4: padata_replace (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/padata.c (ffffffe0001d27e6)
Location: kernel/padata.c:515
Inline: True
Inline callers:
  - kernel/padata.c:padata_set_cpumask
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
int padata_replace(struct padata_instance *pinst);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/padata.c (ffffffff812160c0)
Location: kernel/padata.c:515
Inline: False
Direct callers:
  - kernel/padata.c:padata_cpu_online
  - kernel/padata.c:padata_set_cpumask
```
**Symbols:**

```
ffffffff812160c0-ffffffff81216231: padata_replace (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int padata_replace(struct padata_instance *pinst);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/padata.c (ffffffff81208e20)
Location: kernel/padata.c:515
Inline: False
Direct callers:
  - kernel/padata.c:padata_cpu_online
  - kernel/padata.c:padata_set_cpumask
```
**Symbols:**

```
ffffffff81208e20-ffffffff81208f91: padata_replace (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int padata_replace(struct padata_instance *pinst);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/padata.c (ffffffff81213e60)
Location: kernel/padata.c:515
Inline: False
Direct callers:
  - kernel/padata.c:padata_cpu_online
  - kernel/padata.c:padata_set_cpumask
```
**Symbols:**

```
ffffffff81213e60-ffffffff81213fd1: padata_replace (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int padata_replace(struct padata_instance *pinst);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/padata.c (ffffffff812230a0)
Location: kernel/padata.c:515
Inline: False
Direct callers:
  - kernel/padata.c:padata_cpu_online
  - kernel/padata.c:padata_set_cpumask
```
**Symbols:**

```
ffffffff812230a0-ffffffff81223211: padata_replace (STB_LOCAL)
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
<b>Param removed. </b>
<code>struct parallel_data *pd_new</code>
</li>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>int</code>
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
