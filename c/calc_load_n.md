# Function: <code>calc_load_n</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/loadavg.c (ffffffff810b0f8d)
Location: kernel/sched/loadavg.c:290
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/loadavg.c:calc_global_load
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long unsigned int calc_load_n(long unsigned int load, long unsigned int exp, long unsigned int active, unsigned int n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/loadavg.c (ffffffff810b37f0)
Location: kernel/sched/loadavg.c:293
Inline: False
Direct callers:
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/loadavg.c:calc_global_load
```
**Symbols:**

```
ffffffff810b37f0-ffffffff810b385a: calc_load_n (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long unsigned int calc_load_n(long unsigned int load, long unsigned int exp, long unsigned int active, unsigned int n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/loadavg.c (ffffffff810b9e30)
Location: kernel/sched/loadavg.c:293
Inline: False
Direct callers:
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/loadavg.c:calc_global_load
```
**Symbols:**

```
ffffffff810b9e30-ffffffff810b9e9a: calc_load_n (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long unsigned int calc_load_n(long unsigned int load, long unsigned int exp, long unsigned int active, unsigned int n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/loadavg.c (ffffffff810b4690)
Location: kernel/sched/loadavg.c:294
Inline: False
Direct callers:
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/loadavg.c:calc_global_load
```
**Symbols:**

```
ffffffff810b4690-ffffffff810b46fa: calc_load_n (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long unsigned int calc_load_n(long unsigned int load, long unsigned int exp, long unsigned int active, unsigned int n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/loadavg.c (ffffffff810bb960)
Location: kernel/sched/loadavg.c:295
Inline: False
Direct callers:
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/loadavg.c:calc_global_load
```
**Symbols:**

```
ffffffff810bb960-ffffffff810bb9ca: calc_load_n (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long unsigned int calc_load_n(long unsigned int load, long unsigned int exp, long unsigned int active, unsigned int n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/loadavg.c (ffffffff810c3030)
Location: kernel/sched/loadavg.c:291
Inline: False
Direct callers:
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/loadavg.c:calc_global_load
```
**Symbols:**

```
ffffffff810c3030-ffffffff810c309a: calc_load_n (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long unsigned int calc_load_n(long unsigned int load, long unsigned int exp, long unsigned int active, unsigned int n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/loadavg.c (ffffffff810cc360)
Location: kernel/sched/loadavg.c:157
Inline: False
Direct callers:
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/psi.c:update_stats
  - kernel/sched/psi.c:update_stats
  - kernel/sched/psi.c:update_stats
```
**Symbols:**

```
ffffffff810cc360-ffffffff810cc3ca: calc_load_n (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long unsigned int calc_load_n(long unsigned int load, long unsigned int exp, long unsigned int active, unsigned int n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/loadavg.c (ffffffff810d47a0)
Location: kernel/sched/loadavg.c:157
Inline: False
Direct callers:
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/psi.c:update_averages
  - kernel/sched/psi.c:update_averages
  - kernel/sched/psi.c:update_averages
```
**Symbols:**

```
ffffffff810d47a0-ffffffff810d480a: calc_load_n (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long unsigned int calc_load_n(long unsigned int load, long unsigned int exp, long unsigned int active, unsigned int n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/loadavg.c (ffffffff810deda0)
Location: kernel/sched/loadavg.c:157
Inline: False
Direct callers:
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/psi.c:update_averages
  - kernel/sched/psi.c:update_averages
  - kernel/sched/psi.c:update_averages
```
**Symbols:**

```
ffffffff810deda0-ffffffff810dee0a: calc_load_n (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long unsigned int calc_load_n(long unsigned int load, long unsigned int exp, long unsigned int active, unsigned int n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/loadavg.c (ffffffff810e6fc0)
Location: kernel/sched/loadavg.c:157
Inline: False
Direct callers:
  - kernel/sched/loadavg.c:calc_global_nohz
  - kernel/sched/loadavg.c:calc_global_nohz
  - kernel/sched/loadavg.c:calc_global_nohz
  - kernel/sched/psi.c:update_averages
  - kernel/sched/psi.c:update_averages
  - kernel/sched/psi.c:update_averages
```
**Symbols:**

```
ffffffff810e6fc0-ffffffff810e702a: calc_load_n (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long unsigned int calc_load_n(long unsigned int load, long unsigned int exp, long unsigned int active, unsigned int n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/loadavg.c (ffffffff810e4c00)
Location: kernel/sched/loadavg.c:157
Inline: False
Direct callers:
  - kernel/sched/loadavg.c:calc_global_nohz
  - kernel/sched/loadavg.c:calc_global_nohz
  - kernel/sched/loadavg.c:calc_global_nohz
  - kernel/sched/psi.c:update_averages
  - kernel/sched/psi.c:update_averages
  - kernel/sched/psi.c:update_averages
```
**Symbols:**

```
ffffffff810e4c00-ffffffff810e4c6a: calc_load_n (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long unsigned int calc_load_n(long unsigned int load, long unsigned int exp, long unsigned int active, unsigned int n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/loadavg.c (ffffffff810e6bc0)
Location: kernel/sched/loadavg.c:157
Inline: False
Direct callers:
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/psi.c:update_averages
  - kernel/sched/psi.c:update_averages
  - kernel/sched/psi.c:update_averages
```
**Symbols:**

```
ffffffff810e6bc0-ffffffff810e6c2a: calc_load_n (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long unsigned int calc_load_n(long unsigned int load, long unsigned int exp, long unsigned int active, unsigned int n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/loadavg.c (ffffffff810fe190)
Location: kernel/sched/loadavg.c:157
Inline: False
Direct callers:
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/psi.c:update_averages
  - kernel/sched/psi.c:update_averages
  - kernel/sched/psi.c:update_averages
```
**Symbols:**

```
ffffffff810fe190-ffffffff810fe1fa: calc_load_n (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long unsigned int calc_load_n(long unsigned int load, long unsigned int exp, long unsigned int active, unsigned int n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff811482c0)
Location: kernel/sched/loadavg.c:156
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:update_averages
  - kernel/sched/build_utility.c:update_averages
  - kernel/sched/build_utility.c:update_averages
  - kernel/sched/build_utility.c:calc_global_load
  - kernel/sched/build_utility.c:calc_global_load
  - kernel/sched/build_utility.c:calc_global_load
```
**Symbols:**

```
ffffffff811482c0-ffffffff81148336: calc_load_n (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long unsigned int calc_load_n(long unsigned int load, long unsigned int exp, long unsigned int active, unsigned int n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff81176a80)
Location: kernel/sched/loadavg.c:156
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:update_averages
  - kernel/sched/build_utility.c:update_averages
  - kernel/sched/build_utility.c:update_averages
  - kernel/sched/build_utility.c:calc_global_load
  - kernel/sched/build_utility.c:calc_global_load
  - kernel/sched/build_utility.c:calc_global_load
```
**Symbols:**

```
ffffffff81176a80-ffffffff81176af6: calc_load_n (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long unsigned int calc_load_n(long unsigned int load, long unsigned int exp, long unsigned int active, unsigned int n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff811876c0)
Location: kernel/sched/loadavg.c:156
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:update_averages
  - kernel/sched/build_utility.c:update_averages
  - kernel/sched/build_utility.c:update_averages
  - kernel/sched/build_utility.c:calc_global_load
  - kernel/sched/build_utility.c:calc_global_load
  - kernel/sched/build_utility.c:calc_global_load
```
**Symbols:**

```
ffffffff811876c0-ffffffff81187736: calc_load_n (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long unsigned int calc_load_n(long unsigned int load, long unsigned int exp, long unsigned int active, unsigned int n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff81195e80)
Location: kernel/sched/loadavg.c:156
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:update_averages
  - kernel/sched/build_utility.c:update_averages
  - kernel/sched/build_utility.c:update_averages
  - kernel/sched/build_utility.c:calc_global_load
  - kernel/sched/build_utility.c:calc_global_load
  - kernel/sched/build_utility.c:calc_global_load
```
**Symbols:**

```
ffffffff81195e80-ffffffff81195ef6: calc_load_n (STB_GLOBAL)
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
long unsigned int calc_load_n(long unsigned int load, long unsigned int exp, long unsigned int active, unsigned int n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/loadavg.c (ffff80001013e860)
Location: kernel/sched/loadavg.c:157
Inline: False
Direct callers:
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/psi.c:update_averages
  - kernel/sched/psi.c:update_averages
  - kernel/sched/psi.c:update_averages
```
**Symbols:**

```
ffff80001013e860-ffff80001013e8f4: calc_load_n (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long unsigned int calc_load_n(long unsigned int load, long unsigned int exp, long unsigned int active, unsigned int n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/loadavg.c (c038e800)
Location: kernel/sched/loadavg.c:157
Inline: False
Direct callers:
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/psi.c:update_averages
  - kernel/sched/psi.c:update_averages
  - kernel/sched/psi.c:update_averages
```
**Symbols:**

```
c038e800-c038e868: calc_load_n (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long unsigned int calc_load_n(long unsigned int load, long unsigned int exp, long unsigned int active, unsigned int n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/loadavg.c (c00000000018d9d0)
Location: kernel/sched/loadavg.c:157
Inline: False
Direct callers:
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/psi.c:update_averages
  - kernel/sched/psi.c:update_averages
  - kernel/sched/psi.c:update_averages
```
**Symbols:**

```
c00000000018d9d0-c00000000018da4c: calc_load_n (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long unsigned int calc_load_n(long unsigned int load, long unsigned int exp, long unsigned int active, unsigned int n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/loadavg.c (ffffffe0000ed088)
Location: kernel/sched/loadavg.c:157
Inline: False
Direct callers:
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/psi.c:update_averages
  - kernel/sched/psi.c:update_averages
  - kernel/sched/psi.c:update_averages
```
**Symbols:**

```
ffffffe0000ed088-ffffffe0000ed10e: calc_load_n (STB_GLOBAL)
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
long unsigned int calc_load_n(long unsigned int load, long unsigned int exp, long unsigned int active, unsigned int n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/loadavg.c (ffffffff810d8f90)
Location: kernel/sched/loadavg.c:157
Inline: False
Direct callers:
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/psi.c:update_averages
  - kernel/sched/psi.c:update_averages
  - kernel/sched/psi.c:update_averages
```
**Symbols:**

```
ffffffff810d8f90-ffffffff810d8ffa: calc_load_n (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long unsigned int calc_load_n(long unsigned int load, long unsigned int exp, long unsigned int active, unsigned int n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/loadavg.c (ffffffff810c7990)
Location: kernel/sched/loadavg.c:157
Inline: False
Direct callers:
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/psi.c:update_averages
  - kernel/sched/psi.c:update_averages
  - kernel/sched/psi.c:update_averages
```
**Symbols:**

```
ffffffff810c7990-ffffffff810c79fa: calc_load_n (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long unsigned int calc_load_n(long unsigned int load, long unsigned int exp, long unsigned int active, unsigned int n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/loadavg.c (ffffffff810d52d0)
Location: kernel/sched/loadavg.c:157
Inline: False
Direct callers:
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/psi.c:update_averages
  - kernel/sched/psi.c:update_averages
  - kernel/sched/psi.c:update_averages
```
**Symbols:**

```
ffffffff810d52d0-ffffffff810d533a: calc_load_n (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long unsigned int calc_load_n(long unsigned int load, long unsigned int exp, long unsigned int active, unsigned int n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/loadavg.c (ffffffff810e0b80)
Location: kernel/sched/loadavg.c:157
Inline: False
Direct callers:
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/loadavg.c:calc_global_load
  - kernel/sched/psi.c:update_averages
  - kernel/sched/psi.c:update_averages
  - kernel/sched/psi.c:update_averages
```
**Symbols:**

```
ffffffff810e0b80-ffffffff810e0bea: calc_load_n (STB_GLOBAL)
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
