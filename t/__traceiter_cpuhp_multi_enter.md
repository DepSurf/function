# Function: <code>__traceiter_cpuhp_multi_enter</code>

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
int __traceiter_cpuhp_multi_enter(void *__data, unsigned int cpu, int target, int idx, int (*fun)(unsigned int, struct hlist_node *), struct hlist_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810a42b0)
Location: include/trace/events/cpuhp.h:37
Inline: False
```
**Symbols:**

```
ffffffff810a42b0-ffffffff810a431b: __traceiter_cpuhp_multi_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __traceiter_cpuhp_multi_enter(void *__data, unsigned int cpu, int target, int idx, int (*fun)(unsigned int, struct hlist_node *), struct hlist_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810a4f00)
Location: include/trace/events/cpuhp.h:37
Inline: False
```
**Symbols:**

```
ffffffff810a4f00-ffffffff810a4f69: __traceiter_cpuhp_multi_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __traceiter_cpuhp_multi_enter(void *__data, unsigned int cpu, int target, int idx, int (*fun)(unsigned int, struct hlist_node *), struct hlist_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810b6740)
Location: include/trace/events/cpuhp.h:37
Inline: False
```
**Symbols:**

```
ffffffff810b6740-ffffffff810b67a9: __traceiter_cpuhp_multi_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __traceiter_cpuhp_multi_enter(void *__data, unsigned int cpu, int target, int idx, int (*fun)(unsigned int, struct hlist_node *), struct hlist_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810ccc80)
Location: include/trace/events/cpuhp.h:37
Inline: False
```
**Symbols:**

```
ffffffff810ccc80-ffffffff810cccff: __traceiter_cpuhp_multi_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __traceiter_cpuhp_multi_enter(void *__data, unsigned int cpu, int target, int idx, int (*fun)(unsigned int, struct hlist_node *), struct hlist_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810eac30)
Location: include/trace/events/cpuhp.h:37
Inline: False
```
**Symbols:**

```
ffffffff810eac30-ffffffff810eacaf: __traceiter_cpuhp_multi_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __traceiter_cpuhp_multi_enter(void *__data, unsigned int cpu, int target, int idx, int (*fun)(unsigned int, struct hlist_node *), struct hlist_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810f6830)
Location: include/trace/events/cpuhp.h:37
Inline: False
```
**Symbols:**

```
ffffffff810f6830-ffffffff810f68af: __traceiter_cpuhp_multi_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __traceiter_cpuhp_multi_enter(void *__data, unsigned int cpu, int target, int idx, int (*fun)(unsigned int, struct hlist_node *), struct hlist_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810ffbe0)
Location: include/trace/events/cpuhp.h:37
Inline: False
```
**Symbols:**

```
ffffffff810ffbe0-ffffffff810ffc5f: __traceiter_cpuhp_multi_enter (STB_GLOBAL)
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
