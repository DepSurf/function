# Function: <code>trace_iterator_reset</code>

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
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811a1c9b)
Location: kernel/trace/trace.h:1974
Inline: True
```
```
In kernel/trace/trace_kdb.c (ffffffff811c9228)
Location: kernel/trace/trace.h:1974
Inline: True
Inline callers:
  - kernel/trace/trace_kdb.c:kdb_ftdump
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811ad694)
Location: kernel/trace/trace.h:1994
Inline: True
```
```
In kernel/trace/trace_kdb.c (ffffffff811d4f18)
Location: kernel/trace/trace.h:1994
Inline: True
Inline callers:
  - kernel/trace/trace_kdb.c:kdb_ftdump
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811c56da)
Location: kernel/trace/trace.h:2072
Inline: True
```
```
In kernel/trace/trace_kdb.c (ffffffff811f14c5)
Location: kernel/trace/trace.h:2072
Inline: True
Inline callers:
  - kernel/trace/trace_kdb.c:ftrace_dump_buf
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81be59f7)
Location: kernel/trace/trace.h:1929
Inline: True
```
```
In kernel/trace/trace_kdb.c (ffffffff811efef5)
Location: kernel/trace/trace.h:1929
Inline: True
Inline callers:
  - kernel/trace/trace_kdb.c:ftrace_dump_buf
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81bd7891)
Location: kernel/trace/trace.h:1898
Inline: True
```
```
In kernel/trace/trace_kdb.c (ffffffff811f0e25)
Location: kernel/trace/trace.h:1898
Inline: True
Inline callers:
  - kernel/trace/trace_kdb.c:ftrace_dump_buf
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81cb57be)
Location: kernel/trace/trace.h:1921
Inline: True
```
```
In kernel/trace/trace_kdb.c (ffffffff81221ec5)
Location: kernel/trace/trace.h:1921
Inline: True
Inline callers:
  - kernel/trace/trace_kdb.c:ftrace_dump_buf
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81224ca3)
Location: kernel/trace/trace.h:1964
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_read_pipe
```
```
In kernel/trace/trace_kdb.c (ffffffff81261bd7)
Location: kernel/trace/trace.h:1964
Inline: True
Inline callers:
  - kernel/trace/trace_kdb.c:ftrace_dump_buf
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8126fe03)
Location: kernel/trace/trace.h:1950
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_read_pipe
```
```
In kernel/trace/trace_kdb.c (ffffffff812b32c9)
Location: kernel/trace/trace.h:1950
Inline: True
Inline callers:
  - kernel/trace/trace_kdb.c:ftrace_dump_buf
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81287061)
Location: kernel/trace/trace.h:1983
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_read_pipe
```
```
In kernel/trace/trace_kdb.c (ffffffff812d5b99)
Location: kernel/trace/trace.h:1983
Inline: True
Inline callers:
  - kernel/trace/trace_kdb.c:ftrace_dump_buf
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff812a212b)
Location: kernel/trace/trace.h:2004
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_read_pipe
```
```
In kernel/trace/trace_kdb.c (ffffffff812f36a9)
Location: kernel/trace/trace.h:2004
Inline: True
Inline callers:
  - kernel/trace/trace_kdb.c:ftrace_dump_buf
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffff80001022a3b4)
Location: kernel/trace/trace.h:1994
Inline: True
```
```
In kernel/trace/trace_kdb.c (ffff800010255040)
Location: kernel/trace/trace.h:1994
Inline: True
Inline callers:
  - kernel/trace/trace_kdb.c:kdb_ftdump
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (c0467a70)
Location: kernel/trace/trace.h:1994
Inline: True
```
```
In kernel/trace/trace_kdb.c (c04882c0)
Location: kernel/trace/trace.h:1994
Inline: True
Inline callers:
  - kernel/trace/trace_kdb.c:kdb_ftdump
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (c0000000002b2014)
Location: kernel/trace/trace.h:1994
Inline: True
```
```
In kernel/trace/trace_kdb.c (c0000000002f4ca0)
Location: kernel/trace/trace.h:1994
Inline: True
Inline callers:
  - kernel/trace/trace_kdb.c:kdb_ftdump
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffe000184916)
Location: kernel/trace/trace.h:1994
Inline: True
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811a5cb4)
Location: kernel/trace/trace.h:1994
Inline: True
```
```
In kernel/trace/trace_kdb.c (ffffffff811cd538)
Location: kernel/trace/trace.h:1994
Inline: True
Inline callers:
  - kernel/trace/trace_kdb.c:kdb_ftdump
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81198c3f)
Location: kernel/trace/trace.h:1994
Inline: True
```
```
In kernel/trace/trace_kdb.c (ffffffff811c0308)
Location: kernel/trace/trace.h:1994
Inline: True
Inline callers:
  - kernel/trace/trace_kdb.c:kdb_ftdump
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811a3a84)
Location: kernel/trace/trace.h:1994
Inline: True
```
```
In kernel/trace/trace_kdb.c (ffffffff811cb308)
Location: kernel/trace/trace.h:1994
Inline: True
Inline callers:
  - kernel/trace/trace_kdb.c:kdb_ftdump
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811b1814)
Location: kernel/trace/trace.h:1994
Inline: True
```
```
In kernel/trace/trace_kdb.c (ffffffff811d9568)
Location: kernel/trace/trace.h:1994
Inline: True
Inline callers:
  - kernel/trace/trace_kdb.c:kdb_ftdump
```
</details>
</li>
</ul>

## Differences
