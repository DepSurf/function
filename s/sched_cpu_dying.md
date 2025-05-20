# Function: <code>sched_cpu_dying</code>

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
int sched_cpu_dying(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b2b80)
Location: kernel/sched/core.c:7299
Inline: False
```
**Symbols:**

```
ffffffff810b2b80-ffffffff810b2df1: sched_cpu_dying (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int sched_cpu_dying(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b9160)
Location: kernel/sched/core.c:7420
Inline: False
```
**Symbols:**

```
ffffffff810b9160-ffffffff810b93ce: sched_cpu_dying (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int sched_cpu_dying(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b3c40)
Location: kernel/sched/core.c:5642
Inline: False
```
**Symbols:**

```
ffffffff810b3c40-ffffffff810b3fa0: sched_cpu_dying (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int sched_cpu_dying(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810baee0)
Location: kernel/sched/core.c:5721
Inline: False
```
**Symbols:**

```
ffffffff810baee0-ffffffff810bb24f: sched_cpu_dying (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int sched_cpu_dying(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810c23c0)
Location: kernel/sched/core.c:5860
Inline: False
```
**Symbols:**

```
ffffffff810c23c0-ffffffff810c270f: sched_cpu_dying (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int sched_cpu_dying(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810cb6b0)
Location: kernel/sched/core.c:5838
Inline: False
```
**Symbols:**

```
ffffffff810cb6b0-ffffffff810cba03: sched_cpu_dying (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int sched_cpu_dying(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (0)
Location: kernel/sched/core.c:6290
Inline: False
```
**Symbols:**

```
ffffffff810d46a8-ffffffff810d46c5: sched_cpu_dying.cold (STB_LOCAL)
ffffffff810d36c0-ffffffff810d3a75: sched_cpu_dying (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int sched_cpu_dying(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810ddc30)
Location: kernel/sched/core.c:6477
Inline: False
```
**Symbols:**

```
ffffffff810ddc30-ffffffff810ddf55: sched_cpu_dying (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int sched_cpu_dying(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810e63f0)
Location: kernel/sched/core.c:6712
Inline: False
```
**Symbols:**

```
ffffffff810e63f0-ffffffff810e650b: sched_cpu_dying (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int sched_cpu_dying(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (0)
Location: kernel/sched/core.c:7629
Inline: False
```
**Symbols:**

```
ffffffff81bdc66e-ffffffff81bdc73b: sched_cpu_dying.cold (STB_LOCAL)
ffffffff810e4310-ffffffff810e4409: sched_cpu_dying (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int sched_cpu_dying(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (0)
Location: kernel/sched/core.c:8004
Inline: False
```
**Symbols:**

```
ffffffff81bce7f1-ffffffff81bce8b6: sched_cpu_dying.cold (STB_LOCAL)
ffffffff810e62e0-ffffffff810e63c0: sched_cpu_dying (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int sched_cpu_dying(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (0)
Location: kernel/sched/core.c:9204
Inline: False
```
**Symbols:**

```
ffffffff81ca6000-ffffffff81ca60ea: sched_cpu_dying.cold (STB_LOCAL)
ffffffff810fd790-ffffffff810fd900: sched_cpu_dying (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int sched_cpu_dying(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (0)
Location: kernel/sched/core.c:9497
Inline: False
```
**Symbols:**

```
ffffffff81e55958-ffffffff81e55a46: sched_cpu_dying.cold (STB_LOCAL)
ffffffff8111a1b0-ffffffff8111a31d: sched_cpu_dying (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int sched_cpu_dying(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (0)
Location: kernel/sched/core.c:9687
Inline: False
```
**Symbols:**

```
ffffffff82056cf6-ffffffff82056d0b: sched_cpu_dying.cold (STB_LOCAL)
ffffffff81141910-ffffffff81141b6b: sched_cpu_dying (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int sched_cpu_dying(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (0)
Location: kernel/sched/core.c:9831
Inline: False
```
**Symbols:**

```
ffffffff820d52af-ffffffff820d52c4: sched_cpu_dying.cold (STB_LOCAL)
ffffffff8114d5c0-ffffffff8114d835: sched_cpu_dying (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int sched_cpu_dying(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (0)
Location: kernel/sched/core.c:9820
Inline: False
```
**Symbols:**

```
ffffffff821b0227-ffffffff821b023c: sched_cpu_dying.cold (STB_LOCAL)
ffffffff81159370-ffffffff8115964d: sched_cpu_dying (STB_GLOBAL)
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
int sched_cpu_dying(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffff80001013d518)
Location: kernel/sched/core.c:6477
Inline: False
```
**Symbols:**

```
ffff80001013d518-ffff80001013d97c: sched_cpu_dying (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int sched_cpu_dying(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (c038d55c)
Location: kernel/sched/core.c:6477
Inline: False
```
**Symbols:**

```
c038d55c-c038d958: sched_cpu_dying (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int sched_cpu_dying(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (c00000000018c350)
Location: kernel/sched/core.c:6477
Inline: False
```
**Symbols:**

```
c00000000018c350-c00000000018c8e4: sched_cpu_dying (STB_GLOBAL)
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
int sched_cpu_dying(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d7e20)
Location: kernel/sched/core.c:6477
Inline: False
```
**Symbols:**

```
ffffffff810d7e20-ffffffff810d8145: sched_cpu_dying (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int sched_cpu_dying(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810c67f0)
Location: kernel/sched/core.c:6477
Inline: False
```
**Symbols:**

```
ffffffff810c67f0-ffffffff810c6b53: sched_cpu_dying (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int sched_cpu_dying(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d4610)
Location: kernel/sched/core.c:6477
Inline: False
```
**Symbols:**

```
ffffffff810d4610-ffffffff810d4935: sched_cpu_dying (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int sched_cpu_dying(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810dfa20)
Location: kernel/sched/core.c:6477
Inline: False
```
**Symbols:**

```
ffffffff810dfa20-ffffffff810dfd2f: sched_cpu_dying (STB_GLOBAL)
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
