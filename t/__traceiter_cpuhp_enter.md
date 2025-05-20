# Function: <code>__traceiter_cpuhp_enter</code>

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
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __traceiter_cpuhp_enter(void *__data, unsigned int cpu, int target, int idx, int (*fun)(unsigned int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810a4250)
Location: include/trace/events/cpuhp.h:10
Inline: False
```
**Symbols:**

```
ffffffff810a4250-ffffffff810a42ab: __traceiter_cpuhp_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __traceiter_cpuhp_enter(void *__data, unsigned int cpu, int target, int idx, int (*fun)(unsigned int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810a4ea0)
Location: include/trace/events/cpuhp.h:10
Inline: False
```
**Symbols:**

```
ffffffff810a4ea0-ffffffff810a4ef9: __traceiter_cpuhp_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __traceiter_cpuhp_enter(void *__data, unsigned int cpu, int target, int idx, int (*fun)(unsigned int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810b66e0)
Location: include/trace/events/cpuhp.h:10
Inline: False
```
**Symbols:**

```
ffffffff810b66e0-ffffffff810b6739: __traceiter_cpuhp_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __traceiter_cpuhp_enter(void *__data, unsigned int cpu, int target, int idx, int (*fun)(unsigned int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810ccc10)
Location: include/trace/events/cpuhp.h:10
Inline: False
```
**Symbols:**

```
ffffffff810ccc10-ffffffff810ccc78: __traceiter_cpuhp_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __traceiter_cpuhp_enter(void *__data, unsigned int cpu, int target, int idx, int (*fun)(unsigned int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810eabb0)
Location: include/trace/events/cpuhp.h:10
Inline: False
```
**Symbols:**

```
ffffffff810eabb0-ffffffff810eac18: __traceiter_cpuhp_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __traceiter_cpuhp_enter(void *__data, unsigned int cpu, int target, int idx, int (*fun)(unsigned int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810f6790)
Location: include/trace/events/cpuhp.h:10
Inline: False
```
**Symbols:**

```
ffffffff810f6790-ffffffff810f67f8: __traceiter_cpuhp_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __traceiter_cpuhp_enter(void *__data, unsigned int cpu, int target, int idx, int (*fun)(unsigned int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810ffb40)
Location: include/trace/events/cpuhp.h:10
Inline: False
```
**Symbols:**

```
ffffffff810ffb40-ffffffff810ffba8: __traceiter_cpuhp_enter (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
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
