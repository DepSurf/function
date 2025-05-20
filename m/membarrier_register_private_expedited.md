# Function: <code>membarrier_register_private_expedited</code>

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
In kernel/sched/membarrier.c (ffffffff810dbdfd)
Location: kernel/sched/membarrier.c:108
Inline: True
Inline callers:
  - kernel/sched/membarrier.c:SyS_membarrier
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int membarrier_register_private_expedited(int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/membarrier.c (ffffffff810e40f0)
Location: kernel/sched/membarrier.c:221
Inline: False
Direct callers:
  - kernel/sched/membarrier.c:__ia32_sys_membarrier
  - kernel/sched/membarrier.c:__ia32_sys_membarrier
  - kernel/sched/membarrier.c:__x64_sys_membarrier
  - kernel/sched/membarrier.c:__x64_sys_membarrier
```
**Symbols:**

```
ffffffff810e40f0-ffffffff810e4167: membarrier_register_private_expedited (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int membarrier_register_private_expedited(int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/membarrier.c (ffffffff810ee870)
Location: kernel/sched/membarrier.c:221
Inline: False
Direct callers:
  - kernel/sched/membarrier.c:__ia32_sys_membarrier
  - kernel/sched/membarrier.c:__ia32_sys_membarrier
  - kernel/sched/membarrier.c:__x64_sys_membarrier
  - kernel/sched/membarrier.c:__x64_sys_membarrier
```
**Symbols:**

```
ffffffff810ee870-ffffffff810ee8e7: membarrier_register_private_expedited (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int membarrier_register_private_expedited(int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/membarrier.c (ffffffff810f5690)
Location: kernel/sched/membarrier.c:212
Inline: False
Direct callers:
  - kernel/sched/membarrier.c:__ia32_sys_membarrier
  - kernel/sched/membarrier.c:__ia32_sys_membarrier
  - kernel/sched/membarrier.c:__x64_sys_membarrier
  - kernel/sched/membarrier.c:__x64_sys_membarrier
```
**Symbols:**

```
ffffffff810f5690-ffffffff810f570a: membarrier_register_private_expedited (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int membarrier_register_private_expedited(int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/membarrier.c (ffffffff811016b0)
Location: kernel/sched/membarrier.c:278
Inline: False
Direct callers:
  - kernel/sched/membarrier.c:__ia32_sys_membarrier
  - kernel/sched/membarrier.c:__ia32_sys_membarrier
  - kernel/sched/membarrier.c:__x64_sys_membarrier
  - kernel/sched/membarrier.c:__x64_sys_membarrier
```
**Symbols:**

```
ffffffff811016b0-ffffffff81101717: membarrier_register_private_expedited (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int membarrier_register_private_expedited(int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/membarrier.c (ffffffff8110bee0)
Location: kernel/sched/membarrier.c:278
Inline: False
Direct callers:
  - kernel/sched/membarrier.c:__ia32_sys_membarrier
  - kernel/sched/membarrier.c:__ia32_sys_membarrier
  - kernel/sched/membarrier.c:__x64_sys_membarrier
  - kernel/sched/membarrier.c:__x64_sys_membarrier
```
**Symbols:**

```
ffffffff8110bee0-ffffffff8110bf70: membarrier_register_private_expedited (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int membarrier_register_private_expedited(int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/membarrier.c (ffffffff81109000)
Location: kernel/sched/membarrier.c:501
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
ffffffff81109000-ffffffff811090c2: membarrier_register_private_expedited (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int membarrier_register_private_expedited(int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/membarrier.c (ffffffff8110ac90)
Location: kernel/sched/membarrier.c:501
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
ffffffff8110ac90-ffffffff8110ad28: membarrier_register_private_expedited (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int membarrier_register_private_expedited(int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/membarrier.c (ffffffff811294a0)
Location: kernel/sched/membarrier.c:502
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
ffffffff811294a0-ffffffff81129538: membarrier_register_private_expedited (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int membarrier_register_private_expedited(int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8113def0)
Location: kernel/sched/membarrier.c:501
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
ffffffff8113def0-ffffffff8113df75: membarrier_register_private_expedited (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int membarrier_register_private_expedited(int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8116de20)
Location: kernel/sched/membarrier.c:501
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
ffffffff8116de20-ffffffff8116dea5: membarrier_register_private_expedited (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int membarrier_register_private_expedited(int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8117e3f0)
Location: kernel/sched/membarrier.c:502
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
ffffffff8117e3f0-ffffffff8117e47a: membarrier_register_private_expedited (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int membarrier_register_private_expedited(int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8118bf30)
Location: kernel/sched/membarrier.c:508
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:__do_sys_membarrier
  - kernel/sched/build_utility.c:__do_sys_membarrier
  - kernel/sched/build_utility.c:__do_sys_membarrier
```
**Symbols:**

```
ffffffff8118bf30-ffffffff8118bfba: membarrier_register_private_expedited (STB_LOCAL)
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
int membarrier_register_private_expedited(int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/membarrier.c (ffff800010166068)
Location: kernel/sched/membarrier.c:278
Inline: False
Direct callers:
  - kernel/sched/membarrier.c:__arm64_sys_membarrier
  - kernel/sched/membarrier.c:__arm64_sys_membarrier
```
**Symbols:**

```
ffff800010166068-ffff800010166130: membarrier_register_private_expedited (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int membarrier_register_private_expedited(int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/membarrier.c (c03b23c4)
Location: kernel/sched/membarrier.c:278
Inline: False
Direct callers:
  - kernel/sched/membarrier.c:__se_sys_membarrier
  - kernel/sched/membarrier.c:__se_sys_membarrier
```
**Symbols:**

```
c03b23c4-c03b2470: membarrier_register_private_expedited (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int membarrier_register_private_expedited(int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/membarrier.c (c0000000001bd620)
Location: kernel/sched/membarrier.c:278
Inline: False
Direct callers:
  - kernel/sched/membarrier.c:__se_sys_membarrier
  - kernel/sched/membarrier.c:__se_sys_membarrier
```
**Symbols:**

```
c0000000001bd620-c0000000001bd6f8: membarrier_register_private_expedited (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int membarrier_register_private_expedited(int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/membarrier.c (ffffffe0001084e6)
Location: kernel/sched/membarrier.c:278
Inline: False
Direct callers:
  - kernel/sched/membarrier.c:__se_sys_membarrier
  - kernel/sched/membarrier.c:__se_sys_membarrier
```
**Symbols:**

```
ffffffe0001084e6-ffffffe00010854e: membarrier_register_private_expedited (STB_LOCAL)
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
int membarrier_register_private_expedited(int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/membarrier.c (ffffffff810fa9c0)
Location: kernel/sched/membarrier.c:278
Inline: False
Direct callers:
  - kernel/sched/membarrier.c:__ia32_sys_membarrier
  - kernel/sched/membarrier.c:__ia32_sys_membarrier
  - kernel/sched/membarrier.c:__x64_sys_membarrier
  - kernel/sched/membarrier.c:__x64_sys_membarrier
```
**Symbols:**

```
ffffffff810fa9c0-ffffffff810faa27: membarrier_register_private_expedited (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int membarrier_register_private_expedited(int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/membarrier.c (ffffffff810eaba0)
Location: kernel/sched/membarrier.c:278
Inline: False
Direct callers:
  - kernel/sched/membarrier.c:__ia32_sys_membarrier
  - kernel/sched/membarrier.c:__ia32_sys_membarrier
  - kernel/sched/membarrier.c:__x64_sys_membarrier
  - kernel/sched/membarrier.c:__x64_sys_membarrier
```
**Symbols:**

```
ffffffff810eaba0-ffffffff810eac07: membarrier_register_private_expedited (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int membarrier_register_private_expedited(int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/membarrier.c (ffffffff810f7b80)
Location: kernel/sched/membarrier.c:278
Inline: False
Direct callers:
  - kernel/sched/membarrier.c:__ia32_sys_membarrier
  - kernel/sched/membarrier.c:__ia32_sys_membarrier
  - kernel/sched/membarrier.c:__x64_sys_membarrier
  - kernel/sched/membarrier.c:__x64_sys_membarrier
```
**Symbols:**

```
ffffffff810f7b80-ffffffff810f7be7: membarrier_register_private_expedited (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int membarrier_register_private_expedited(int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/membarrier.c (ffffffff81102cc0)
Location: kernel/sched/membarrier.c:278
Inline: False
Direct callers:
  - kernel/sched/membarrier.c:__ia32_sys_membarrier
  - kernel/sched/membarrier.c:__ia32_sys_membarrier
  - kernel/sched/membarrier.c:__x64_sys_membarrier
  - kernel/sched/membarrier.c:__x64_sys_membarrier
```
**Symbols:**

```
ffffffff81102cc0-ffffffff81102d27: membarrier_register_private_expedited (STB_LOCAL)
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
