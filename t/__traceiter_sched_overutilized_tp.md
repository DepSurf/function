# Function: <code>__traceiter_sched_overutilized_tp</code>

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
int __traceiter_sched_overutilized_tp(void *__data, struct root_domain *rd, bool overutilized);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d69e0)
Location: include/trace/events/sched.h:721
Inline: False
```
**Symbols:**

```
ffffffff810d69e0-ffffffff810d6a28: __traceiter_sched_overutilized_tp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __traceiter_sched_overutilized_tp(void *__data, struct root_domain *rd, bool overutilized);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d86b0)
Location: include/trace/events/sched.h:721
Inline: False
```
**Symbols:**

```
ffffffff810d86b0-ffffffff810d86f6: __traceiter_sched_overutilized_tp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __traceiter_sched_overutilized_tp(void *__data, struct root_domain *rd, bool overutilized);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810ebf40)
Location: include/trace/events/sched.h:719
Inline: False
```
**Symbols:**

```
ffffffff810ebf40-ffffffff810ebf86: __traceiter_sched_overutilized_tp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __traceiter_sched_overutilized_tp(void *__data, struct root_domain *rd, bool overutilized);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81107090)
Location: include/trace/events/sched.h:722
Inline: False
```
**Symbols:**

```
ffffffff81107090-ffffffff811070e0: __traceiter_sched_overutilized_tp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __traceiter_sched_overutilized_tp(void *__data, struct root_domain *rd, bool overutilized);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff8112cf80)
Location: include/trace/events/sched.h:722
Inline: False
```
**Symbols:**

```
ffffffff8112cf80-ffffffff8112cfd0: __traceiter_sched_overutilized_tp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __traceiter_sched_overutilized_tp(void *__data, struct root_domain *rd, bool overutilized);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff8113a1e0)
Location: include/trace/events/sched.h:722
Inline: False
```
**Symbols:**

```
ffffffff8113a1e0-ffffffff8113a230: __traceiter_sched_overutilized_tp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __traceiter_sched_overutilized_tp(void *__data, struct root_domain *rd, bool overutilized);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81145040)
Location: include/trace/events/sched.h:771
Inline: False
```
**Symbols:**

```
ffffffff81145040-ffffffff81145090: __traceiter_sched_overutilized_tp (STB_GLOBAL)
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
