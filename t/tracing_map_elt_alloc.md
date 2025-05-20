# Function: <code>tracing_map_elt_alloc</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct tracing_map_elt *tracing_map_elt_alloc(struct tracing_map *map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/tracing_map.c (ffffffff8115fc40)
Location: kernel/trace/tracing_map.c:310
Inline: False
Direct callers:
  - kernel/trace/tracing_map.c:tracing_map_sort_entries
  - kernel/trace/tracing_map.c:tracing_map_init
```
**Symbols:**

```
ffffffff8115fc40-ffffffff8115fd54: tracing_map_elt_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct tracing_map_elt *tracing_map_elt_alloc(struct tracing_map *map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/tracing_map.c (ffffffff8116a6a0)
Location: kernel/trace/tracing_map.c:310
Inline: False
Direct callers:
  - kernel/trace/tracing_map.c:tracing_map_sort_entries
  - kernel/trace/tracing_map.c:tracing_map_init
```
**Symbols:**

```
ffffffff8116a6a0-ffffffff8116a7b4: tracing_map_elt_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct tracing_map_elt *tracing_map_elt_alloc(struct tracing_map *map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/tracing_map.c (ffffffff8116d6a0)
Location: kernel/trace/tracing_map.c:313
Inline: False
Direct callers:
  - kernel/trace/tracing_map.c:tracing_map_sort_entries
  - kernel/trace/tracing_map.c:tracing_map_init
```
**Symbols:**

```
ffffffff8116d6a0-ffffffff8116d7a9: tracing_map_elt_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct tracing_map_elt *tracing_map_elt_alloc(struct tracing_map *map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/tracing_map.c (ffffffff8117a750)
Location: kernel/trace/tracing_map.c:313
Inline: False
Direct callers:
  - kernel/trace/tracing_map.c:tracing_map_sort_entries
  - kernel/trace/tracing_map.c:tracing_map_init
```
**Symbols:**

```
ffffffff8117a750-ffffffff8117a862: tracing_map_elt_alloc (STB_LOCAL)
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
In kernel/trace/tracing_map.c (ffffffff8118a4a0)
Location: kernel/trace/tracing_map.c:409
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_init
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
In kernel/trace/tracing_map.c (ffffffff81197e00)
Location: kernel/trace/tracing_map.c:400
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_init
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
In kernel/trace/tracing_map.c (ffffffff811a59cf)
Location: kernel/trace/tracing_map.c:400
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_init
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
In kernel/trace/tracing_map.c (ffffffff811b11ff)
Location: kernel/trace/tracing_map.c:400
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct tracing_map_elt *tracing_map_elt_alloc(struct tracing_map *map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/tracing_map.c (ffffffff811c9160)
Location: kernel/trace/tracing_map.c:400
Inline: False
Direct callers:
  - kernel/trace/tracing_map.c:tracing_map_alloc_elts
```
**Symbols:**

```
ffffffff811c9160-ffffffff811c92b1: tracing_map_elt_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct tracing_map_elt *tracing_map_elt_alloc(struct tracing_map *map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/tracing_map.c (ffffffff811c6820)
Location: kernel/trace/tracing_map.c:400
Inline: False
Direct callers:
  - kernel/trace/tracing_map.c:tracing_map_alloc_elts
```
**Symbols:**

```
ffffffff811c6820-ffffffff811c697b: tracing_map_elt_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/tracing_map.c (ffffffff811c7899)
Location: kernel/trace/tracing_map.c:400
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_alloc_elts
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/tracing_map.c (ffffffff811f3051)
Location: kernel/trace/tracing_map.c:403
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_alloc_elts
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct tracing_map_elt *tracing_map_elt_alloc(struct tracing_map *map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/tracing_map.c (ffffffff8122c5a0)
Location: kernel/trace/tracing_map.c:403
Inline: False
Direct callers:
  - kernel/trace/tracing_map.c:tracing_map_alloc_elts
```
**Symbols:**

```
ffffffff8122c5a0-ffffffff8122c755: tracing_map_elt_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct tracing_map_elt *tracing_map_elt_alloc(struct tracing_map *map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/tracing_map.c (ffffffff812780f0)
Location: kernel/trace/tracing_map.c:403
Inline: False
Direct callers:
  - kernel/trace/tracing_map.c:tracing_map_alloc_elts
```
**Symbols:**

```
ffffffff812780f0-ffffffff812782a5: tracing_map_elt_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct tracing_map_elt *tracing_map_elt_alloc(struct tracing_map *map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/tracing_map.c (ffffffff8128fb30)
Location: kernel/trace/tracing_map.c:403
Inline: False
Direct callers:
  - kernel/trace/tracing_map.c:tracing_map_alloc_elts
```
**Symbols:**

```
ffffffff8128fb30-ffffffff8128fcde: tracing_map_elt_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct tracing_map_elt *tracing_map_elt_alloc(struct tracing_map *map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/tracing_map.c (ffffffff812ab0c0)
Location: kernel/trace/tracing_map.c:403
Inline: False
Direct callers:
  - kernel/trace/tracing_map.c:tracing_map_alloc_elts
```
**Symbols:**

```
ffffffff812ab0c0-ffffffff812ab29d: tracing_map_elt_alloc (STB_LOCAL)
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
In kernel/trace/tracing_map.c (ffff80001022ee64)
Location: kernel/trace/tracing_map.c:400
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_init
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/tracing_map.c (c0000000002b85b0)
Location: kernel/trace/tracing_map.c:400
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_init
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
In kernel/trace/tracing_map.c (ffffffff811a981f)
Location: kernel/trace/tracing_map.c:400
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_init
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
In kernel/trace/tracing_map.c (ffffffff8119c79f)
Location: kernel/trace/tracing_map.c:400
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_init
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
In kernel/trace/tracing_map.c (ffffffff811a75ef)
Location: kernel/trace/tracing_map.c:400
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_init
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
In kernel/trace/tracing_map.c (ffffffff811b538f)
Location: kernel/trace/tracing_map.c:400
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_init
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
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
