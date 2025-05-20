# Function: <code>trace_array_get_by_name</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct trace_array *trace_array_get_by_name(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811bf130)
Location: kernel/trace/trace.c:8707
Inline: False
Direct callers:
  - kernel/trace/trace_boot.c:trace_boot_init_instances
```
**Symbols:**

```
ffffffff811bf130-ffffffff811bf1cd: trace_array_get_by_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct trace_array *trace_array_get_by_name(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811bcd60)
Location: kernel/trace/trace.c:8797
Inline: False
Direct callers:
  - kernel/trace/trace_boot.c:trace_boot_init_instances
```
**Symbols:**

```
ffffffff811bcd60-ffffffff811bcdfd: trace_array_get_by_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct trace_array *trace_array_get_by_name(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811bc860)
Location: kernel/trace/trace.c:9135
Inline: False
Direct callers:
  - kernel/trace/trace_boot.c:trace_boot_init
```
**Symbols:**

```
ffffffff811bc860-ffffffff811bc8fd: trace_array_get_by_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct trace_array *trace_array_get_by_name(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811e7300)
Location: kernel/trace/trace.c:9299
Inline: False
Direct callers:
  - kernel/trace/trace_boot.c:trace_boot_init
```
**Symbols:**

```
ffffffff811e7300-ffffffff811e739d: trace_array_get_by_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct trace_array *trace_array_get_by_name(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8121f280)
Location: kernel/trace/trace.c:9332
Inline: False
Direct callers:
  - kernel/trace/trace_boot.c:trace_boot_init
```
**Symbols:**

```
ffffffff8121f280-ffffffff8121f31e: trace_array_get_by_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct trace_array *trace_array_get_by_name(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81269cc0)
Location: kernel/trace/trace.c:9423
Inline: False
Direct callers:
  - kernel/trace/trace_boot.c:trace_boot_init
```
**Symbols:**

```
ffffffff81269cc0-ffffffff81269d5e: trace_array_get_by_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct trace_array *trace_array_get_by_name(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81280e40)
Location: kernel/trace/trace.c:9586
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_init
  - kernel/trace/trace_boot.c:trace_boot_init
```
**Symbols:**

```
ffffffff81280e40-ffffffff81280ede: trace_array_get_by_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct trace_array *trace_array_get_by_name(const char *name, const char *systems);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8129b0a0)
Location: kernel/trace/trace.c:9782
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_init
  - kernel/trace/trace_boot.c:trace_boot_init
```
**Symbols:**

```
ffffffff8129b0a0-ffffffff8129b148: trace_array_get_by_name (STB_GLOBAL)
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const char *systems</code>
</li>
</ul>
</details>
</li>
</ul>
