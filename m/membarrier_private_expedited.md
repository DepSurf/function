# Function: <code>membarrier_private_expedited</code>

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
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/membarrier.c (ffffffff810dbe72)
Location: kernel/sched/membarrier.c:38
Inline: True
Inline callers:
  - kernel/sched/membarrier.c:SyS_membarrier
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int membarrier_private_expedited(int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/membarrier.c (ffffffff810e42b0)
Location: kernel/sched/membarrier.c:110
Inline: True
Direct callers:
  - kernel/sched/membarrier.c:__ia32_sys_membarrier
  - kernel/sched/membarrier.c:__ia32_sys_membarrier
  - kernel/sched/membarrier.c:__x64_sys_membarrier
  - kernel/sched/membarrier.c:__x64_sys_membarrier
```
**Symbols:**

```
ffffffff810e42b0-ffffffff810e4443: membarrier_private_expedited (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int membarrier_private_expedited(int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/membarrier.c (ffffffff810ee8f0)
Location: kernel/sched/membarrier.c:110
Inline: True
Direct callers:
  - kernel/sched/membarrier.c:__ia32_sys_membarrier
  - kernel/sched/membarrier.c:__ia32_sys_membarrier
  - kernel/sched/membarrier.c:__x64_sys_membarrier
  - kernel/sched/membarrier.c:__x64_sys_membarrier
```
**Symbols:**

```
ffffffff810ee8f0-ffffffff810eea83: membarrier_private_expedited (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int membarrier_private_expedited(int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/membarrier.c (ffffffff810f5730)
Location: kernel/sched/membarrier.c:101
Inline: True
Direct callers:
  - kernel/sched/membarrier.c:__ia32_sys_membarrier
  - kernel/sched/membarrier.c:__ia32_sys_membarrier
  - kernel/sched/membarrier.c:__x64_sys_membarrier
  - kernel/sched/membarrier.c:__x64_sys_membarrier
```
**Symbols:**

```
ffffffff810f5730-ffffffff810f58ab: membarrier_private_expedited (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int membarrier_private_expedited(int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/membarrier.c (ffffffff811013f0)
Location: kernel/sched/membarrier.c:132
Inline: False
Direct callers:
  - kernel/sched/membarrier.c:__ia32_sys_membarrier
  - kernel/sched/membarrier.c:__ia32_sys_membarrier
  - kernel/sched/membarrier.c:__x64_sys_membarrier
  - kernel/sched/membarrier.c:__x64_sys_membarrier
```
**Symbols:**

```
ffffffff811013f0-ffffffff81101525: membarrier_private_expedited (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int membarrier_private_expedited(int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/membarrier.c (ffffffff8110bc20)
Location: kernel/sched/membarrier.c:132
Inline: False
Direct callers:
  - kernel/sched/membarrier.c:__ia32_sys_membarrier
  - kernel/sched/membarrier.c:__ia32_sys_membarrier
  - kernel/sched/membarrier.c:__x64_sys_membarrier
  - kernel/sched/membarrier.c:__x64_sys_membarrier
```
**Symbols:**

```
ffffffff8110bc20-ffffffff8110bd5c: membarrier_private_expedited (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int membarrier_private_expedited(int flags, int cpu_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/membarrier.c (ffffffff81108da0)
Location: kernel/sched/membarrier.c:309
Inline: False
Direct callers:
  - kernel/sched/membarrier.c:__ia32_sys_membarrier
  - kernel/sched/membarrier.c:__ia32_sys_membarrier
  - kernel/sched/membarrier.c:__ia32_sys_membarrier
  - kernel/sched/membarrier.c:__x64_sys_membarrier
  - kernel/sched/membarrier.c:__x64_sys_membarrier
  - kernel/sched/membarrier.c:__x64_sys_membarrier
```
**Symbols:**

```
ffffffff81108da0-ffffffff81108fbe: membarrier_private_expedited (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int membarrier_private_expedited(int flags, int cpu_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/membarrier.c (ffffffff8110ad30)
Location: kernel/sched/membarrier.c:309
Inline: False
Direct callers:
  - kernel/sched/membarrier.c:__ia32_sys_membarrier
  - kernel/sched/membarrier.c:__ia32_sys_membarrier
  - kernel/sched/membarrier.c:__ia32_sys_membarrier
  - kernel/sched/membarrier.c:__x64_sys_membarrier
  - kernel/sched/membarrier.c:__x64_sys_membarrier
  - kernel/sched/membarrier.c:__x64_sys_membarrier
```
**Symbols:**

```
ffffffff8110ad30-ffffffff8110af50: membarrier_private_expedited (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int membarrier_private_expedited(int flags, int cpu_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/membarrier.c (ffffffff81129540)
Location: kernel/sched/membarrier.c:310
Inline: False
Direct callers:
  - kernel/sched/membarrier.c:__ia32_sys_membarrier
  - kernel/sched/membarrier.c:__ia32_sys_membarrier
  - kernel/sched/membarrier.c:__ia32_sys_membarrier
  - kernel/sched/membarrier.c:__x64_sys_membarrier
  - kernel/sched/membarrier.c:__x64_sys_membarrier
  - kernel/sched/membarrier.c:__x64_sys_membarrier
```
**Symbols:**

```
ffffffff81129540-ffffffff811297af: membarrier_private_expedited (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int membarrier_private_expedited(int flags, int cpu_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff811417e0)
Location: kernel/sched/membarrier.c:309
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:__ia32_sys_membarrier
  - kernel/sched/build_utility.c:__ia32_sys_membarrier
  - kernel/sched/build_utility.c:__ia32_sys_membarrier
  - kernel/sched/build_utility.c:__x64_sys_membarrier
  - kernel/sched/build_utility.c:__x64_sys_membarrier
  - kernel/sched/build_utility.c:__x64_sys_membarrier
```
**Symbols:**

```
ffffffff811417e0-ffffffff81141a72: membarrier_private_expedited (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int membarrier_private_expedited(int flags, int cpu_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8116e1d0)
Location: kernel/sched/membarrier.c:309
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:__ia32_sys_membarrier
  - kernel/sched/build_utility.c:__ia32_sys_membarrier
  - kernel/sched/build_utility.c:__ia32_sys_membarrier
  - kernel/sched/build_utility.c:__x64_sys_membarrier
  - kernel/sched/build_utility.c:__x64_sys_membarrier
  - kernel/sched/build_utility.c:__x64_sys_membarrier
```
**Symbols:**

```
ffffffff8116e1d0-ffffffff8116e472: membarrier_private_expedited (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int membarrier_private_expedited(int flags, int cpu_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8117e7f0)
Location: kernel/sched/membarrier.c:310
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:__ia32_sys_membarrier
  - kernel/sched/build_utility.c:__ia32_sys_membarrier
  - kernel/sched/build_utility.c:__ia32_sys_membarrier
  - kernel/sched/build_utility.c:__x64_sys_membarrier
  - kernel/sched/build_utility.c:__x64_sys_membarrier
  - kernel/sched/build_utility.c:__x64_sys_membarrier
```
**Symbols:**

```
ffffffff8117e7f0-ffffffff8117ea98: membarrier_private_expedited (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int membarrier_private_expedited(int flags, int cpu_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8118c730)
Location: kernel/sched/membarrier.c:314
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:__do_sys_membarrier
  - kernel/sched/build_utility.c:__do_sys_membarrier
  - kernel/sched/build_utility.c:__do_sys_membarrier
```
**Symbols:**

```
ffffffff8118c730-ffffffff8118c9f5: membarrier_private_expedited (STB_LOCAL)
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
int membarrier_private_expedited(int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/membarrier.c (ffff800010165e78)
Location: kernel/sched/membarrier.c:132
Inline: False
Direct callers:
  - kernel/sched/membarrier.c:__arm64_sys_membarrier
  - kernel/sched/membarrier.c:__arm64_sys_membarrier
```
**Symbols:**

```
ffff800010165e78-ffff800010166018: membarrier_private_expedited (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int membarrier_private_expedited(int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/membarrier.c (c03b2470)
Location: kernel/sched/membarrier.c:132
Inline: False
Direct callers:
  - kernel/sched/membarrier.c:__se_sys_membarrier
  - kernel/sched/membarrier.c:__se_sys_membarrier
```
**Symbols:**

```
c03b2470-c03b25f8: membarrier_private_expedited (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int membarrier_private_expedited(int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/membarrier.c (c0000000001bd1f0)
Location: kernel/sched/membarrier.c:132
Inline: False
Direct callers:
  - kernel/sched/membarrier.c:__se_sys_membarrier
  - kernel/sched/membarrier.c:__se_sys_membarrier
```
**Symbols:**

```
c0000000001bd1f0-c0000000001bd3e8: membarrier_private_expedited (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int membarrier_private_expedited(int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/membarrier.c (ffffffe000108248)
Location: kernel/sched/membarrier.c:132
Inline: False
Direct callers:
  - kernel/sched/membarrier.c:__se_sys_membarrier
  - kernel/sched/membarrier.c:__se_sys_membarrier
```
**Symbols:**

```
ffffffe000108248-ffffffe000108364: membarrier_private_expedited (STB_LOCAL)
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
int membarrier_private_expedited(int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/membarrier.c (ffffffff810fa700)
Location: kernel/sched/membarrier.c:132
Inline: False
Direct callers:
  - kernel/sched/membarrier.c:__ia32_sys_membarrier
  - kernel/sched/membarrier.c:__ia32_sys_membarrier
  - kernel/sched/membarrier.c:__x64_sys_membarrier
  - kernel/sched/membarrier.c:__x64_sys_membarrier
```
**Symbols:**

```
ffffffff810fa700-ffffffff810fa835: membarrier_private_expedited (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int membarrier_private_expedited(int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/membarrier.c (ffffffff810ea8e0)
Location: kernel/sched/membarrier.c:132
Inline: False
Direct callers:
  - kernel/sched/membarrier.c:__ia32_sys_membarrier
  - kernel/sched/membarrier.c:__ia32_sys_membarrier
  - kernel/sched/membarrier.c:__x64_sys_membarrier
  - kernel/sched/membarrier.c:__x64_sys_membarrier
```
**Symbols:**

```
ffffffff810ea8e0-ffffffff810eaa15: membarrier_private_expedited (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int membarrier_private_expedited(int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/membarrier.c (ffffffff810f78c0)
Location: kernel/sched/membarrier.c:132
Inline: False
Direct callers:
  - kernel/sched/membarrier.c:__ia32_sys_membarrier
  - kernel/sched/membarrier.c:__ia32_sys_membarrier
  - kernel/sched/membarrier.c:__x64_sys_membarrier
  - kernel/sched/membarrier.c:__x64_sys_membarrier
```
**Symbols:**

```
ffffffff810f78c0-ffffffff810f79f5: membarrier_private_expedited (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int membarrier_private_expedited(int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/membarrier.c (ffffffff811029c0)
Location: kernel/sched/membarrier.c:132
Inline: False
Direct callers:
  - kernel/sched/membarrier.c:__ia32_sys_membarrier
  - kernel/sched/membarrier.c:__ia32_sys_membarrier
  - kernel/sched/membarrier.c:__x64_sys_membarrier
  - kernel/sched/membarrier.c:__x64_sys_membarrier
```
**Symbols:**

```
ffffffff811029c0-ffffffff81102b1e: membarrier_private_expedited (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int cpu_id</code>
</li>
</ul>
</details>
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
