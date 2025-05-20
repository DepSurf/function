# Function: <code>sys_sched_yield</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long int sys_sched_yield();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810ae1b0)
Location: kernel/sched/core.c:4594
Inline: False
Direct callers:
  - kernel/sched/core.c:yield
```
**Symbols:**

```
ffffffff810ae1b0-ffffffff810ae206: sys_sched_yield (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long int sys_sched_yield();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b0bd0)
Location: kernel/sched/core.c:4845
Inline: False
Direct callers:
  - kernel/sched/core.c:yield
```
**Symbols:**

```
ffffffff810b0bd0-ffffffff810b0c2d: sys_sched_yield (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long int sys_sched_yield();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b6e30)
Location: kernel/sched/core.c:4882
Inline: False
Direct callers:
  - kernel/sched/core.c:yield
```
**Symbols:**

```
ffffffff810b6e30-ffffffff810b6e8d: sys_sched_yield (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long int sys_sched_yield();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b3080)
Location: kernel/sched/core.c:4779
Inline: False
Direct callers:
  - kernel/sched/core.c:yield
```
**Symbols:**

```
ffffffff810b3080-ffffffff810b30e7: sys_sched_yield (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long int sys_sched_yield();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810ba480)
Location: kernel/sched/core.c:4823
Inline: False
Direct callers:
  - kernel/sched/core.c:yield
```
**Symbols:**

```
ffffffff810ba480-ffffffff810ba4ed: sys_sched_yield (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long int sys_sched_yield();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (c038cdb0)
Location: kernel/sched/core.c:5608
Inline: False
```
**Symbols:**

```
c038cdb0-c038cdd0: sys_sched_yield (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int sys_sched_yield();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (c000000000185510)
Location: kernel/sched/core.c:5608
Inline: False
```
**Symbols:**

```
c000000000185510-c000000000185544: sys_sched_yield (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long int sys_sched_yield();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffe0000ec0c0)
Location: kernel/sched/core.c:5608
Inline: False
```
**Symbols:**

```
ffffffe0000ec0c0-ffffffe0000ec0e4: sys_sched_yield (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
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
</ul>
<b>Arch</b>
<ul>
</ul>
