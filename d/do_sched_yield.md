# Function: <code>do_sched_yield</code>

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
In <code>4.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void do_sched_yield();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810bebf0)
Location: kernel/sched/core.c:4958
Inline: False
Direct callers:
  - kernel/sched/core.c:yield
  - kernel/sched/core.c:__x64_sys_sched_yield
```
**Symbols:**

```
ffffffff810bebf0-ffffffff810bec58: do_sched_yield (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void do_sched_yield();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810c7e90)
Location: kernel/sched/core.c:4943
Inline: False
Direct callers:
  - kernel/sched/core.c:yield
  - kernel/sched/core.c:__x64_sys_sched_yield
```
**Symbols:**

```
ffffffff810c7e90-ffffffff810c7ef8: do_sched_yield (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void do_sched_yield();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810ceea0)
Location: kernel/sched/core.c:5396
Inline: False
Direct callers:
  - kernel/sched/core.c:yield
  - kernel/sched/core.c:__x64_sys_sched_yield
```
**Symbols:**

```
ffffffff810ceea0-ffffffff810cef0e: do_sched_yield (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void do_sched_yield();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d8c60)
Location: kernel/sched/core.c:5587
Inline: False
Direct callers:
  - kernel/sched/core.c:yield
  - kernel/sched/core.c:__x64_sys_sched_yield
```
**Symbols:**

```
ffffffff810d8c60-ffffffff810d8cce: do_sched_yield (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void do_sched_yield();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810e1af0)
Location: kernel/sched/core.c:5820
Inline: False
Direct callers:
  - kernel/sched/core.c:yield
  - kernel/sched/core.c:__do_sys_sched_yield
```
**Symbols:**

```
ffffffff810e1af0-ffffffff810e1b60: do_sched_yield (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void do_sched_yield();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810dee90)
Location: kernel/sched/core.c:6636
Inline: False
Direct callers:
  - kernel/sched/core.c:yield
  - kernel/sched/core.c:__do_sys_sched_yield
```
**Symbols:**

```
ffffffff810dee90-ffffffff810def3f: do_sched_yield (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void do_sched_yield();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810e0a80)
Location: kernel/sched/core.c:6937
Inline: False
Direct callers:
  - kernel/sched/core.c:yield
  - kernel/sched/core.c:__do_sys_sched_yield
```
**Symbols:**

```
ffffffff810e0a80-ffffffff810e0b2f: do_sched_yield (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void do_sched_yield();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (0)
Location: kernel/sched/core.c:8130
Inline: False
Direct callers:
  - kernel/sched/core.c:yield
  - kernel/sched/core.c:__do_sys_sched_yield
```
**Symbols:**

```
ffffffff810f6b80-ffffffff810f6c39: do_sched_yield (STB_LOCAL)
ffffffff81ca5d4d-ffffffff81ca5d61: do_sched_yield.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void do_sched_yield();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (0)
Location: kernel/sched/core.c:8238
Inline: False
Direct callers:
  - kernel/sched/core.c:yield
  - kernel/sched/core.c:__do_sys_sched_yield
```
**Symbols:**

```
ffffffff811130d0-ffffffff8111319c: do_sched_yield (STB_LOCAL)
ffffffff81e55689-ffffffff81e5569e: do_sched_yield.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void do_sched_yield();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (0)
Location: kernel/sched/core.c:8422
Inline: False
Direct callers:
  - kernel/sched/core.c:yield
  - kernel/sched/core.c:__do_sys_sched_yield
```
**Symbols:**

```
ffffffff8113a1d0-ffffffff8113a2a0: do_sched_yield (STB_LOCAL)
ffffffff82056afb-ffffffff82056b10: do_sched_yield.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void do_sched_yield();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (0)
Location: kernel/sched/core.c:8531
Inline: False
Direct callers:
  - kernel/sched/core.c:yield
  - kernel/sched/core.c:__do_sys_sched_yield
```
**Symbols:**

```
ffffffff81149450-ffffffff81149538: do_sched_yield (STB_LOCAL)
ffffffff820d51cb-ffffffff820d51e0: do_sched_yield.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void do_sched_yield();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (0)
Location: kernel/sched/core.c:8535
Inline: False
Direct callers:
  - kernel/sched/core.c:yield
  - kernel/sched/core.c:__do_sys_sched_yield
```
**Symbols:**

```
ffffffff81154e50-ffffffff81154f38: do_sched_yield (STB_LOCAL)
ffffffff821b0119-ffffffff821b012e: do_sched_yield.cold (STB_LOCAL)
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
void do_sched_yield();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffff800010138e98)
Location: kernel/sched/core.c:5587
Inline: False
Direct callers:
  - kernel/sched/core.c:yield
  - kernel/sched/core.c:__arm64_sys_sched_yield
```
**Symbols:**

```
ffff800010138e98-ffff800010138f18: do_sched_yield (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void do_sched_yield();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (c03881f4)
Location: kernel/sched/core.c:5587
Inline: False
Direct callers:
  - kernel/sched/core.c:yield
  - kernel/sched/core.c:sys_sched_yield
```
**Symbols:**

```
c03881f4-c038828c: do_sched_yield (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void do_sched_yield();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (c0000000001853d0)
Location: kernel/sched/core.c:5587
Inline: False
Direct callers:
  - kernel/sched/core.c:yield
  - kernel/sched/core.c:sys_sched_yield
```
**Symbols:**

```
c0000000001853d0-c000000000185508: do_sched_yield (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void do_sched_yield();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffe0000e8bdc)
Location: kernel/sched/core.c:5587
Inline: False
Direct callers:
  - kernel/sched/core.c:yield
  - kernel/sched/core.c:sys_sched_yield
```
**Symbols:**

```
ffffffe0000e8bdc-ffffffe0000e8c98: do_sched_yield (STB_LOCAL)
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
void do_sched_yield();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d3130)
Location: kernel/sched/core.c:5587
Inline: False
Direct callers:
  - kernel/sched/core.c:yield
  - kernel/sched/core.c:__x64_sys_sched_yield
```
**Symbols:**

```
ffffffff810d3130-ffffffff810d319e: do_sched_yield (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void do_sched_yield();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810c1760)
Location: kernel/sched/core.c:5587
Inline: False
Direct callers:
  - kernel/sched/core.c:yield
  - kernel/sched/core.c:__x64_sys_sched_yield
```
**Symbols:**

```
ffffffff810c1760-ffffffff810c17c8: do_sched_yield (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void do_sched_yield();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d0810)
Location: kernel/sched/core.c:5587
Inline: False
Direct callers:
  - kernel/sched/core.c:yield
  - kernel/sched/core.c:__x64_sys_sched_yield
```
**Symbols:**

```
ffffffff810d0810-ffffffff810d087e: do_sched_yield (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void do_sched_yield();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810da880)
Location: kernel/sched/core.c:5587
Inline: False
Direct callers:
  - kernel/sched/core.c:yield
  - kernel/sched/core.c:__x64_sys_sched_yield
```
**Symbols:**

```
ffffffff810da880-ffffffff810da8fa: do_sched_yield (STB_LOCAL)
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
