# Function: <code>trace_percpu_create_chunk</code>

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
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void trace_percpu_create_chunk(void *base_addr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff811e38be)
Location: include/trace/events/percpu.h:89
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_create_chunk
Direct callers:
  - mm/percpu.c:pcpu_setup_first_chunk
```
**Symbols:**

```
ffffffff811e2f90-ffffffff811e2fde: trace_percpu_create_chunk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void trace_percpu_create_chunk(void *base_addr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff811f93c1)
Location: include/trace/events/percpu.h:90
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_create_chunk
Direct callers:
  - mm/percpu.c:pcpu_setup_first_chunk
```
**Symbols:**

```
ffffffff811f8ad0-ffffffff811f8b23: trace_percpu_create_chunk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void trace_percpu_create_chunk(void *base_addr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff8121af94)
Location: include/trace/events/percpu.h:90
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_create_chunk
Direct callers:
  - mm/percpu.c:pcpu_setup_first_chunk
```
**Symbols:**

```
ffffffff81219da0-ffffffff81219df3: trace_percpu_create_chunk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void trace_percpu_create_chunk(void *base_addr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff8122df48)
Location: include/trace/events/percpu.h:90
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_create_chunk
Direct callers:
  - mm/percpu.c:pcpu_setup_first_chunk
```
**Symbols:**

```
ffffffff8122d480-ffffffff8122d4d3: trace_percpu_create_chunk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void trace_percpu_create_chunk(void *base_addr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff8123dcb5)
Location: include/trace/events/percpu.h:90
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_create_chunk
Direct callers:
  - mm/percpu.c:pcpu_setup_first_chunk
```
**Symbols:**

```
ffffffff8123d1b0-ffffffff8123d200: trace_percpu_create_chunk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void trace_percpu_create_chunk(void *base_addr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff8124c105)
Location: include/trace/events/percpu.h:90
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_create_chunk
Direct callers:
  - mm/percpu.c:pcpu_setup_first_chunk
```
**Symbols:**

```
ffffffff8124b600-ffffffff8124b650: trace_percpu_create_chunk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff8127a1db)
Location: include/trace/events/percpu.h:90
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff81284ad8)
Location: include/trace/events/percpu.h:90
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void trace_percpu_create_chunk(void *base_addr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff8128942e)
Location: include/trace/events/percpu.h:90
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_create_chunk
Direct callers:
  - mm/percpu.c:pcpu_setup_first_chunk
```
**Symbols:**

```
ffffffff81289070-ffffffff812890ac: trace_percpu_create_chunk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void trace_percpu_create_chunk(void *base_addr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff812c8d38)
Location: include/trace/events/percpu.h:90
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_create_chunk
Direct callers:
  - mm/percpu.c:pcpu_setup_first_chunk
```
**Symbols:**

```
ffffffff812c8af0-ffffffff812c8b29: trace_percpu_create_chunk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void trace_percpu_create_chunk(void *base_addr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff813269a9)
Location: include/trace/events/percpu.h:101
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_create_chunk
Direct callers:
  - mm/percpu.c:pcpu_setup_first_chunk
```
**Symbols:**

```
ffffffff813268d0-ffffffff81326947: trace_percpu_create_chunk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff8139b409)
Location: include/trace/events/percpu.h:101
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff813cee89)
Location: include/trace/events/percpu.h:101
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
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
In mm/percpu.c (ffffffff813f99e9)
Location: include/trace/events/percpu.h:101
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
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
In mm/percpu.c (ffff8000102e29b0)
Location: include/trace/events/percpu.h:90
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
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
In mm/percpu.c (c0506c8c)
Location: include/trace/events/percpu.h:90
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void trace_percpu_create_chunk(void *base_addr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/percpu.c (c0000000003a2b04)
Location: include/trace/events/percpu.h:90
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_create_chunk
Direct callers:
  - mm/percpu.c:pcpu_setup_first_chunk
```
**Symbols:**

```
c0000000003a10f0-c0000000003a119c: trace_percpu_create_chunk (STB_LOCAL)
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
In mm/percpu.c (ffffffe0001f9586)
Location: include/trace/events/percpu.h:90
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
  - mm/percpu.c:pcpu_setup_first_chunk
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void trace_percpu_create_chunk(void *base_addr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff81244755)
Location: include/trace/events/percpu.h:90
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_create_chunk
Direct callers:
  - mm/percpu.c:pcpu_setup_first_chunk
```
**Symbols:**

```
ffffffff81243c50-ffffffff81243ca0: trace_percpu_create_chunk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void trace_percpu_create_chunk(void *base_addr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff81237725)
Location: include/trace/events/percpu.h:90
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_create_chunk
Direct callers:
  - mm/percpu.c:pcpu_setup_first_chunk
```
**Symbols:**

```
ffffffff81236c20-ffffffff81236c70: trace_percpu_create_chunk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void trace_percpu_create_chunk(void *base_addr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff812424f5)
Location: include/trace/events/percpu.h:90
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_create_chunk
Direct callers:
  - mm/percpu.c:pcpu_setup_first_chunk
```
**Symbols:**

```
ffffffff812419f0-ffffffff81241a40: trace_percpu_create_chunk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void trace_percpu_create_chunk(void *base_addr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff81251ca5)
Location: include/trace/events/percpu.h:90
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_create_chunk
  - mm/percpu.c:pcpu_create_chunk
Direct callers:
  - mm/percpu.c:pcpu_setup_first_chunk
```
**Symbols:**

```
ffffffff81251170-ffffffff812511d7: trace_percpu_create_chunk (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
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
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
