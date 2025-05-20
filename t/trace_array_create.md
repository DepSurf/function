# Function: <code>trace_array_create</code>

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
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
struct trace_array *trace_array_create(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (0)
Location: kernel/trace/trace.c:8319
Inline: False
Direct callers:
  - kernel/trace/trace.c:instance_mkdir
```
**Symbols:**

```
ffffffff811a1bcf-ffffffff811a1bdb: trace_array_create.cold (STB_LOCAL)
ffffffff811a1290-ffffffff811a151f: trace_array_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
struct trace_array *trace_array_create(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (0)
Location: kernel/trace/trace.c:8370
Inline: False
Direct callers:
  - kernel/trace/trace.c:instance_mkdir
```
**Symbols:**

```
ffffffff811ad5a5-ffffffff811ad5b1: trace_array_create.cold (STB_LOCAL)
ffffffff811accd0-ffffffff811acf61: trace_array_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
struct trace_array *trace_array_create(const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (0)
Location: kernel/trace/trace.c:8602
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_array_get_by_name
  - kernel/trace/trace.c:instance_mkdir
```
**Symbols:**

```
ffffffff811bee80-ffffffff811bf128: trace_array_create (STB_LOCAL)
ffffffff811c54cf-ffffffff811c54db: trace_array_create.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
struct trace_array *trace_array_create(const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (0)
Location: kernel/trace/trace.c:8694
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_array_get_by_name
  - kernel/trace/trace.c:instance_mkdir
```
**Symbols:**

```
ffffffff811bcb00-ffffffff811bcd5d: trace_array_create (STB_LOCAL)
ffffffff81be580b-ffffffff81be5817: trace_array_create.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
struct trace_array *trace_array_create(const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (0)
Location: kernel/trace/trace.c:9032
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_array_get_by_name
  - kernel/trace/trace.c:instance_mkdir
```
**Symbols:**

```
ffffffff811bc600-ffffffff811bc85d: trace_array_create (STB_LOCAL)
ffffffff81bd76b9-ffffffff81bd76c5: trace_array_create.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct trace_array *trace_array_create(const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (0)
Location: kernel/trace/trace.c:9196
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_array_get_by_name
  - kernel/trace/trace.c:instance_mkdir
```
**Symbols:**

```
ffffffff811e7060-ffffffff811e72f2: trace_array_create (STB_LOCAL)
ffffffff81cb51f1-ffffffff81cb51fd: trace_array_create.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct trace_array *trace_array_create(const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (0)
Location: kernel/trace/trace.c:9229
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_array_get_by_name
  - kernel/trace/trace.c:instance_mkdir
```
**Symbols:**

```
ffffffff8121efe0-ffffffff8121f27d: trace_array_create (STB_LOCAL)
ffffffff81e662a2-ffffffff81e662ae: trace_array_create.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct trace_array *trace_array_create(const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81269a10)
Location: kernel/trace/trace.c:9320
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_array_get_by_name
  - kernel/trace/trace.c:instance_mkdir
```
**Symbols:**

```
ffffffff81269a10-ffffffff81269ca9: trace_array_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct trace_array *trace_array_create(const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81280ba0)
Location: kernel/trace/trace.c:9479
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_array_get_by_name
  - kernel/trace/trace.c:instance_mkdir
```
**Symbols:**

```
ffffffff81280ba0-ffffffff81280e30: trace_array_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8129b1b3)
Location: kernel/trace/trace.c:9738
Inline: True
Inline callers:
  - kernel/trace/trace.c:instance_mkdir
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
struct trace_array *trace_array_create(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffff800010229d00)
Location: kernel/trace/trace.c:8370
Inline: False
Direct callers:
  - kernel/trace/trace.c:instance_mkdir
```
**Symbols:**

```
ffff800010229d00-ffff800010229f30: trace_array_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct trace_array *trace_array_create(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (c04673a0)
Location: kernel/trace/trace.c:8370
Inline: False
Direct callers:
  - kernel/trace/trace.c:instance_mkdir
```
**Symbols:**

```
c04673a0-c04675b4: trace_array_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct trace_array *trace_array_create(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (c0000000002b1530)
Location: kernel/trace/trace.c:8370
Inline: False
Direct callers:
  - kernel/trace/trace.c:instance_mkdir
```
**Symbols:**

```
c0000000002b1530-c0000000002b19f8: trace_array_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct trace_array *trace_array_create(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffe000184394)
Location: kernel/trace/trace.c:8370
Inline: False
Direct callers:
  - kernel/trace/trace.c:instance_mkdir
```
**Symbols:**

```
ffffffe000184394-ffffffe0001845ba: trace_array_create (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
struct trace_array *trace_array_create(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (0)
Location: kernel/trace/trace.c:8370
Inline: False
Direct callers:
  - kernel/trace/trace.c:instance_mkdir
```
**Symbols:**

```
ffffffff811a5bc5-ffffffff811a5bd1: trace_array_create.cold (STB_LOCAL)
ffffffff811a52f0-ffffffff811a5581: trace_array_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
struct trace_array *trace_array_create(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (0)
Location: kernel/trace/trace.c:8370
Inline: False
Direct callers:
  - kernel/trace/trace.c:instance_mkdir
```
**Symbols:**

```
ffffffff81198b55-ffffffff81198b61: trace_array_create.cold (STB_LOCAL)
ffffffff811982a0-ffffffff81198531: trace_array_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
struct trace_array *trace_array_create(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (0)
Location: kernel/trace/trace.c:8370
Inline: False
Direct callers:
  - kernel/trace/trace.c:instance_mkdir
```
**Symbols:**

```
ffffffff811a3995-ffffffff811a39a1: trace_array_create.cold (STB_LOCAL)
ffffffff811a30c0-ffffffff811a3351: trace_array_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
struct trace_array *trace_array_create(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (0)
Location: kernel/trace/trace.c:8370
Inline: False
Direct callers:
  - kernel/trace/trace.c:instance_mkdir
```
**Symbols:**

```
ffffffff811b1725-ffffffff811b1731: trace_array_create.cold (STB_LOCAL)
ffffffff811b0e50-ffffffff811b10e1: trace_array_create (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
