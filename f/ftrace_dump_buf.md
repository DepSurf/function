# Function: <code>ftrace_dump_buf</code>

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
In kernel/trace/trace_kdb.c (ffffffff8116ca3e)
Location: kernel/trace/trace_kdb.c:19
Inline: True
Inline callers:
  - kernel/trace/trace_kdb.c:kdb_ftdump
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kdb.c (ffffffff81179f0b)
Location: kernel/trace/trace_kdb.c:19
Inline: True
Inline callers:
  - kernel/trace/trace_kdb.c:kdb_ftdump
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kdb.c (ffffffff811859db)
Location: kernel/trace/trace_kdb.c:19
Inline: True
Inline callers:
  - kernel/trace/trace_kdb.c:kdb_ftdump
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kdb.c (ffffffff811886fa)
Location: kernel/trace/trace_kdb.c:19
Inline: True
Inline callers:
  - kernel/trace/trace_kdb.c:kdb_ftdump
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kdb.c (ffffffff8119639a)
Location: kernel/trace/trace_kdb.c:20
Inline: True
Inline callers:
  - kernel/trace/trace_kdb.c:kdb_ftdump
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kdb.c (ffffffff811abba8)
Location: kernel/trace/trace_kdb.c:20
Inline: True
Inline callers:
  - kernel/trace/trace_kdb.c:kdb_ftdump
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kdb.c (ffffffff811ba168)
Location: kernel/trace/trace_kdb.c:20
Inline: True
Inline callers:
  - kernel/trace/trace_kdb.c:kdb_ftdump
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kdb.c (ffffffff811c91f8)
Location: kernel/trace/trace_kdb.c:23
Inline: True
Inline callers:
  - kernel/trace/trace_kdb.c:kdb_ftdump
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kdb.c (ffffffff811d4ee8)
Location: kernel/trace/trace_kdb.c:23
Inline: True
Inline callers:
  - kernel/trace/trace_kdb.c:kdb_ftdump
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void ftrace_dump_buf(int skip_entries, long int cpu_file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kdb.c (ffffffff811f1480)
Location: kernel/trace/trace_kdb.c:23
Inline: False
Direct callers:
  - kernel/trace/trace_kdb.c:kdb_ftdump
```
**Symbols:**

```
ffffffff811f1480-ffffffff811f16b2: ftrace_dump_buf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void ftrace_dump_buf(int skip_entries, long int cpu_file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kdb.c (ffffffff811efeb0)
Location: kernel/trace/trace_kdb.c:23
Inline: False
Direct callers:
  - kernel/trace/trace_kdb.c:kdb_ftdump
```
**Symbols:**

```
ffffffff811efeb0-ffffffff811f00e2: ftrace_dump_buf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void ftrace_dump_buf(int skip_entries, long int cpu_file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kdb.c (ffffffff811f0de0)
Location: kernel/trace/trace_kdb.c:23
Inline: False
Direct callers:
  - kernel/trace/trace_kdb.c:kdb_ftdump
```
**Symbols:**

```
ffffffff811f0de0-ffffffff811f1019: ftrace_dump_buf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void ftrace_dump_buf(int skip_entries, long int cpu_file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kdb.c (ffffffff81221e80)
Location: kernel/trace/trace_kdb.c:23
Inline: False
Direct callers:
  - kernel/trace/trace_kdb.c:kdb_ftdump
```
**Symbols:**

```
ffffffff81221e80-ffffffff812220b9: ftrace_dump_buf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void ftrace_dump_buf(int skip_entries, long int cpu_file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kdb.c (ffffffff81261b90)
Location: kernel/trace/trace_kdb.c:23
Inline: False
Direct callers:
  - kernel/trace/trace_kdb.c:kdb_ftdump
```
**Symbols:**

```
ffffffff81261b90-ffffffff81261ddd: ftrace_dump_buf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void ftrace_dump_buf(int skip_entries, long int cpu_file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kdb.c (ffffffff812b3280)
Location: kernel/trace/trace_kdb.c:23
Inline: False
Direct callers:
  - kernel/trace/trace_kdb.c:kdb_ftdump
```
**Symbols:**

```
ffffffff812b3280-ffffffff812b34df: ftrace_dump_buf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void ftrace_dump_buf(int skip_entries, long int cpu_file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kdb.c (ffffffff812d5b50)
Location: kernel/trace/trace_kdb.c:23
Inline: False
Direct callers:
  - kernel/trace/trace_kdb.c:kdb_ftdump
```
**Symbols:**

```
ffffffff812d5b50-ffffffff812d5daf: ftrace_dump_buf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void ftrace_dump_buf(int skip_entries, long int cpu_file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kdb.c (ffffffff812f3660)
Location: kernel/trace/trace_kdb.c:23
Inline: False
Direct callers:
  - kernel/trace/trace_kdb.c:kdb_ftdump
```
**Symbols:**

```
ffffffff812f3660-ffffffff812f38be: ftrace_dump_buf (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kdb.c (ffff80001025501c)
Location: kernel/trace/trace_kdb.c:23
Inline: True
Inline callers:
  - kernel/trace/trace_kdb.c:kdb_ftdump
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kdb.c (c0488294)
Location: kernel/trace/trace_kdb.c:23
Inline: True
Inline callers:
  - kernel/trace/trace_kdb.c:kdb_ftdump
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kdb.c (c0000000002f4c74)
Location: kernel/trace/trace_kdb.c:23
Inline: True
Inline callers:
  - kernel/trace/trace_kdb.c:kdb_ftdump
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kdb.c (ffffffff811cd508)
Location: kernel/trace/trace_kdb.c:23
Inline: True
Inline callers:
  - kernel/trace/trace_kdb.c:kdb_ftdump
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kdb.c (ffffffff811c02d8)
Location: kernel/trace/trace_kdb.c:23
Inline: True
Inline callers:
  - kernel/trace/trace_kdb.c:kdb_ftdump
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kdb.c (ffffffff811cb2d8)
Location: kernel/trace/trace_kdb.c:23
Inline: True
Inline callers:
  - kernel/trace/trace_kdb.c:kdb_ftdump
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kdb.c (ffffffff811d9538)
Location: kernel/trace/trace_kdb.c:23
Inline: True
Inline callers:
  - kernel/trace/trace_kdb.c:kdb_ftdump
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
