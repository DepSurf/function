# Function: <code>sched_cpu_starting</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int sched_cpu_starting(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b2b20)
Location: kernel/sched/core.c:7291
Inline: False
```
**Symbols:**

```
ffffffff810b2b20-ffffffff810b2b74: sched_cpu_starting (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int sched_cpu_starting(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b9100)
Location: kernel/sched/core.c:7412
Inline: False
```
**Symbols:**

```
ffffffff810b9100-ffffffff810b9154: sched_cpu_starting (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int sched_cpu_starting(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b3be0)
Location: kernel/sched/core.c:5634
Inline: False
```
**Symbols:**

```
ffffffff810b3be0-ffffffff810b3c34: sched_cpu_starting (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int sched_cpu_starting(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810bae80)
Location: kernel/sched/core.c:5713
Inline: False
```
**Symbols:**

```
ffffffff810bae80-ffffffff810baed4: sched_cpu_starting (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int sched_cpu_starting(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810c2360)
Location: kernel/sched/core.c:5851
Inline: False
```
**Symbols:**

```
ffffffff810c2360-ffffffff810c23b4: sched_cpu_starting (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int sched_cpu_starting(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810cb670)
Location: kernel/sched/core.c:5830
Inline: False
```
**Symbols:**

```
ffffffff810cb670-ffffffff810cb6a2: sched_cpu_starting (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int sched_cpu_starting(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff828c4bcf)
Location: kernel/sched/core.c:6282
Inline: True
Inline callers:
  - kernel/sched/core.c:migration_init
```
**Symbols:**

```
ffffffff810d3680-ffffffff810d36b2: sched_cpu_starting (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int sched_cpu_starting(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff828cd1a6)
Location: kernel/sched/core.c:6469
Inline: True
Inline callers:
  - kernel/sched/core.c:migration_init
```
**Symbols:**

```
ffffffff810ddbf0-ffffffff810ddc22: sched_cpu_starting (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int sched_cpu_starting(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff82cee539)
Location: kernel/sched/core.c:6704
Inline: True
Inline callers:
  - kernel/sched/core.c:migration_init
```
**Symbols:**

```
ffffffff810e63b0-ffffffff810e63e2: sched_cpu_starting (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int sched_cpu_starting(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff82fdacd2)
Location: kernel/sched/core.c:7567
Inline: True
Inline callers:
  - kernel/sched/core.c:migration_init
```
**Symbols:**

```
ffffffff810e4240-ffffffff810e4272: sched_cpu_starting (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int sched_cpu_starting(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff831e5661)
Location: kernel/sched/core.c:7942
Inline: True
Inline callers:
  - kernel/sched/core.c:migration_init
```
**Symbols:**

```
ffffffff810e6210-ffffffff810e6242: sched_cpu_starting (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int sched_cpu_starting(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff832c956a)
Location: kernel/sched/core.c:9141
Inline: True
Inline callers:
  - kernel/sched/core.c:migration_init
```
**Symbols:**

```
ffffffff810fd6c0-ffffffff810fd71f: sched_cpu_starting (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int sched_cpu_starting(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff8347c738)
Location: kernel/sched/core.c:9434
Inline: True
Inline callers:
  - kernel/sched/core.c:migration_init
```
**Symbols:**

```
ffffffff8111a0d0-ffffffff8111a139: sched_cpu_starting (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int sched_cpu_starting(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff83ea7bcd)
Location: kernel/sched/core.c:9624
Inline: True
Inline callers:
  - kernel/sched/core.c:migration_init
```
**Symbols:**

```
ffffffff81141810-ffffffff81141879: sched_cpu_starting (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int sched_cpu_starting(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff836cc53d)
Location: kernel/sched/core.c:9768
Inline: True
Inline callers:
  - kernel/sched/core.c:migration_init
```
**Symbols:**

```
ffffffff8114d4c0-ffffffff8114d529: sched_cpu_starting (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int sched_cpu_starting(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81159180)
Location: kernel/sched/core.c:9757
Inline: False
Direct callers:
  - kernel/sched/core.c:migration_init
```
**Symbols:**

```
ffffffff81159180-ffffffff811592d7: sched_cpu_starting (STB_GLOBAL)
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
int sched_cpu_starting(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffff800011444a6c)
Location: kernel/sched/core.c:6469
Inline: True
Inline callers:
  - kernel/sched/core.c:migration_init
```
**Symbols:**

```
ffff80001013d4c8-ffff80001013d518: sched_cpu_starting (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int sched_cpu_starting(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (c151eae8)
Location: kernel/sched/core.c:6469
Inline: True
Inline callers:
  - kernel/sched/core.c:migration_init
```
**Symbols:**

```
c038d514-c038d55c: sched_cpu_starting (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int sched_cpu_starting(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (c0000000013691f8)
Location: kernel/sched/core.c:6469
Inline: True
Inline callers:
  - kernel/sched/core.c:migration_init
```
**Symbols:**

```
c00000000018c2e0-c00000000018c344: sched_cpu_starting (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int sched_cpu_starting(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffe000006900)
Location: kernel/sched/core.c:6469
Inline: True
Inline callers:
  - kernel/sched/core.c:migration_init
```
**Symbols:**

```
ffffffe0000ec84c-ffffffe0000ec8a0: sched_cpu_starting (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int sched_cpu_starting(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff828b5f99)
Location: kernel/sched/core.c:6469
Inline: True
Inline callers:
  - kernel/sched/core.c:migration_init
```
**Symbols:**

```
ffffffff810d7de0-ffffffff810d7e12: sched_cpu_starting (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int sched_cpu_starting(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810c6700)
Location: kernel/sched/core.c:6469
Inline: False
Direct callers:
  - kernel/sched/core.c:migration_init
```
**Symbols:**

```
ffffffff810c6700-ffffffff810c67eb: sched_cpu_starting (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int sched_cpu_starting(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff828c8e98)
Location: kernel/sched/core.c:6469
Inline: True
Inline callers:
  - kernel/sched/core.c:migration_init
```
**Symbols:**

```
ffffffff810d45d0-ffffffff810d4602: sched_cpu_starting (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int sched_cpu_starting(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff828ce1ef)
Location: kernel/sched/core.c:6469
Inline: True
Inline callers:
  - kernel/sched/core.c:migration_init
```
**Symbols:**

```
ffffffff810df9e0-ffffffff810dfa12: sched_cpu_starting (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
