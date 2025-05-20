# Function: <code>sched_cpu_deactivate</code>

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
int sched_cpu_deactivate(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b29a0)
Location: kernel/sched/core.c:7251
Inline: False
```
**Symbols:**

```
ffffffff810b29a0-ffffffff810b2b1b: sched_cpu_deactivate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int sched_cpu_deactivate(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b8f90)
Location: kernel/sched/core.c:7372
Inline: False
```
**Symbols:**

```
ffffffff810b8f90-ffffffff810b9100: sched_cpu_deactivate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int sched_cpu_deactivate(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b3b10)
Location: kernel/sched/core.c:5600
Inline: False
```
**Symbols:**

```
ffffffff810b3b10-ffffffff810b3bdb: sched_cpu_deactivate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int sched_cpu_deactivate(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810badb0)
Location: kernel/sched/core.c:5679
Inline: False
```
**Symbols:**

```
ffffffff810badb0-ffffffff810bae7b: sched_cpu_deactivate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int sched_cpu_deactivate(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810c2290)
Location: kernel/sched/core.c:5817
Inline: False
```
**Symbols:**

```
ffffffff810c2290-ffffffff810c235b: sched_cpu_deactivate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int sched_cpu_deactivate(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810cb5c0)
Location: kernel/sched/core.c:5788
Inline: False
```
**Symbols:**

```
ffffffff810cb5c0-ffffffff810cb66c: sched_cpu_deactivate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int sched_cpu_deactivate(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d35d0)
Location: kernel/sched/core.c:6240
Inline: False
```
**Symbols:**

```
ffffffff810d35d0-ffffffff810d367d: sched_cpu_deactivate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int sched_cpu_deactivate(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810ddb40)
Location: kernel/sched/core.c:6427
Inline: False
```
**Symbols:**

```
ffffffff810ddb40-ffffffff810ddbed: sched_cpu_deactivate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int sched_cpu_deactivate(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810e6300)
Location: kernel/sched/core.c:6662
Inline: False
```
**Symbols:**

```
ffffffff810e6300-ffffffff810e63b0: sched_cpu_deactivate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int sched_cpu_deactivate(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810e40b0)
Location: kernel/sched/core.c:7502
Inline: False
```
**Symbols:**

```
ffffffff810e40b0-ffffffff810e4238: sched_cpu_deactivate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int sched_cpu_deactivate(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810e6080)
Location: kernel/sched/core.c:7871
Inline: False
```
**Symbols:**

```
ffffffff810e6080-ffffffff810e6210: sched_cpu_deactivate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int sched_cpu_deactivate(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (0)
Location: kernel/sched/core.c:9068
Inline: False
```
**Symbols:**

```
ffffffff81ca5fbd-ffffffff81ca6000: sched_cpu_deactivate.cold (STB_LOCAL)
ffffffff810fd280-ffffffff810fd6bd: sched_cpu_deactivate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int sched_cpu_deactivate(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (0)
Location: kernel/sched/core.c:9359
Inline: False
```
**Symbols:**

```
ffffffff81e55919-ffffffff81e55958: sched_cpu_deactivate.cold (STB_LOCAL)
ffffffff81119c50-ffffffff8111a0ca: sched_cpu_deactivate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int sched_cpu_deactivate(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (0)
Location: kernel/sched/core.c:9549
Inline: False
```
**Symbols:**

```
ffffffff82056cb9-ffffffff82056cf6: sched_cpu_deactivate.cold (STB_LOCAL)
ffffffff811415b0-ffffffff811417f8: sched_cpu_deactivate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int sched_cpu_deactivate(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (0)
Location: kernel/sched/core.c:9694
Inline: False
```
**Symbols:**

```
ffffffff820d5272-ffffffff820d52af: sched_cpu_deactivate.cold (STB_LOCAL)
ffffffff8114d250-ffffffff8114d4af: sched_cpu_deactivate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int sched_cpu_deactivate(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (0)
Location: kernel/sched/core.c:9683
Inline: False
```
**Symbols:**

```
ffffffff821b01ea-ffffffff821b0227: sched_cpu_deactivate.cold (STB_LOCAL)
ffffffff81158f10-ffffffff8115916f: sched_cpu_deactivate (STB_GLOBAL)
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
int sched_cpu_deactivate(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffff80001013d398)
Location: kernel/sched/core.c:6427
Inline: False
```
**Symbols:**

```
ffff80001013d398-ffff80001013d4c4: sched_cpu_deactivate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int sched_cpu_deactivate(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (c038d464)
Location: kernel/sched/core.c:6427
Inline: False
```
**Symbols:**

```
c038d464-c038d514: sched_cpu_deactivate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int sched_cpu_deactivate(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (c00000000018c120)
Location: kernel/sched/core.c:6427
Inline: False
```
**Symbols:**

```
c00000000018c120-c00000000018c2d8: sched_cpu_deactivate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int sched_cpu_deactivate(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffe0000ec770)
Location: kernel/sched/core.c:6427
Inline: False
```
**Symbols:**

```
ffffffe0000ec770-ffffffe0000ec84c: sched_cpu_deactivate (STB_GLOBAL)
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
int sched_cpu_deactivate(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d7d30)
Location: kernel/sched/core.c:6427
Inline: False
```
**Symbols:**

```
ffffffff810d7d30-ffffffff810d7ddd: sched_cpu_deactivate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int sched_cpu_deactivate(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810c6650)
Location: kernel/sched/core.c:6427
Inline: False
```
**Symbols:**

```
ffffffff810c6650-ffffffff810c66fd: sched_cpu_deactivate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int sched_cpu_deactivate(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d4520)
Location: kernel/sched/core.c:6427
Inline: False
```
**Symbols:**

```
ffffffff810d4520-ffffffff810d45cd: sched_cpu_deactivate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int sched_cpu_deactivate(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810df930)
Location: kernel/sched/core.c:6427
Inline: False
```
**Symbols:**

```
ffffffff810df930-ffffffff810df9dd: sched_cpu_deactivate (STB_GLOBAL)
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
