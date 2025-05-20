# Function: <code>tracing_map_array_clear</code>

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
void tracing_map_array_clear(struct tracing_map_array *a);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/tracing_map.c (ffffffff8115fed0)
Location: kernel/trace/tracing_map.c:206
Inline: False
Direct callers:
  - kernel/trace/tracing_map.c:tracing_map_clear
```
**Symbols:**

```
ffffffff8115fed0-ffffffff8115ff2a: tracing_map_array_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void tracing_map_array_clear(struct tracing_map_array *a);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/tracing_map.c (ffffffff8116a930)
Location: kernel/trace/tracing_map.c:206
Inline: False
Direct callers:
  - kernel/trace/tracing_map.c:tracing_map_clear
```
**Symbols:**

```
ffffffff8116a930-ffffffff8116a98a: tracing_map_array_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void tracing_map_array_clear(struct tracing_map_array *a);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/tracing_map.c (ffffffff8116e06b)
Location: kernel/trace/tracing_map.c:206
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_clear
Direct callers:
  - kernel/trace/tracing_map.c:tracing_map_clear
```
**Symbols:**

```
ffffffff8116d650-ffffffff8116d69f: tracing_map_array_clear.part.1 (STB_LOCAL)
ffffffff8116d920-ffffffff8116d934: tracing_map_array_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void tracing_map_array_clear(struct tracing_map_array *a);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/tracing_map.c (ffffffff8117b14b)
Location: kernel/trace/tracing_map.c:206
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_clear
Direct callers:
  - kernel/trace/tracing_map.c:tracing_map_clear
```
**Symbols:**

```
ffffffff8117a700-ffffffff8117a74f: tracing_map_array_clear.part.1 (STB_LOCAL)
ffffffff8117a9e0-ffffffff8117a9f4: tracing_map_array_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
void tracing_map_array_clear(struct tracing_map_array *a);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/tracing_map.c (ffffffff8118a2db)
Location: kernel/trace/tracing_map.c:295
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_clear
Direct callers:
  - kernel/trace/tracing_map.c:tracing_map_clear
```
**Symbols:**

```
ffffffff81189840-ffffffff8118988a: tracing_map_array_clear.part.4 (STB_LOCAL)
ffffffff81189a50-ffffffff81189a63: tracing_map_array_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
void tracing_map_array_clear(struct tracing_map_array *a);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/tracing_map.c (ffffffff81197c3b)
Location: kernel/trace/tracing_map.c:286
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_clear
Direct callers:
  - kernel/trace/tracing_map.c:tracing_map_clear
```
**Symbols:**

```
ffffffff811970f0-ffffffff8119713a: tracing_map_array_clear.part.4 (STB_LOCAL)
ffffffff81197300-ffffffff81197313: tracing_map_array_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void tracing_map_array_clear(struct tracing_map_array *a);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/tracing_map.c (ffffffff811a581b)
Location: kernel/trace/tracing_map.c:286
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_clear
Direct callers:
  - kernel/trace/tracing_map.c:tracing_map_clear
```
**Symbols:**

```
ffffffff811a4f90-ffffffff811a4fda: tracing_map_array_clear.part.0 (STB_LOCAL)
ffffffff811a5550-ffffffff811a5563: tracing_map_array_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void tracing_map_array_clear(struct tracing_map_array *a);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/tracing_map.c (ffffffff811b104b)
Location: kernel/trace/tracing_map.c:286
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_clear
Direct callers:
  - kernel/trace/tracing_map.c:tracing_map_clear
```
**Symbols:**

```
ffffffff811b07c0-ffffffff811b080a: tracing_map_array_clear.part.0 (STB_LOCAL)
ffffffff811b0d80-ffffffff811b0d93: tracing_map_array_clear (STB_GLOBAL)
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
In kernel/trace/tracing_map.c (ffffffff811c95cb)
Location: kernel/trace/tracing_map.c:286
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_clear
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
In kernel/trace/tracing_map.c (ffffffff811c6c8b)
Location: kernel/trace/tracing_map.c:286
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_clear
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
In kernel/trace/tracing_map.c (ffffffff811c7c7b)
Location: kernel/trace/tracing_map.c:286
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_clear
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
In kernel/trace/tracing_map.c (ffffffff811f35a3)
Location: kernel/trace/tracing_map.c:287
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_clear
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/tracing_map.c (ffffffff8122cc93)
Location: kernel/trace/tracing_map.c:287
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_clear
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
In kernel/trace/tracing_map.c (ffffffff812788e3)
Location: kernel/trace/tracing_map.c:287
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_clear
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
In kernel/trace/tracing_map.c (ffffffff81290325)
Location: kernel/trace/tracing_map.c:287
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_clear
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
In kernel/trace/tracing_map.c (ffffffff812ab8e5)
Location: kernel/trace/tracing_map.c:287
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_clear
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void tracing_map_array_clear(struct tracing_map_array *a);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/tracing_map.c (ffff80001022ec94)
Location: kernel/trace/tracing_map.c:286
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_clear
Direct callers:
  - kernel/trace/tracing_map.c:tracing_map_clear
```
**Symbols:**

```
ffff80001022df58-ffff80001022dfa8: tracing_map_array_clear.part.0 (STB_LOCAL)
ffff80001022e658-ffff80001022e678: tracing_map_array_clear (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
void tracing_map_array_clear(struct tracing_map_array *a);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/tracing_map.c (c0000000002b8344)
Location: kernel/trace/tracing_map.c:286
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_clear
Direct callers:
  - kernel/trace/tracing_map.c:tracing_map_clear
```
**Symbols:**

```
c0000000002b7150-c0000000002b71c8: tracing_map_array_clear.part.0 (STB_LOCAL)
c0000000002b7b90-c0000000002b7ba8: tracing_map_array_clear (STB_GLOBAL)
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
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
void tracing_map_array_clear(struct tracing_map_array *a);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/tracing_map.c (ffffffff811a966b)
Location: kernel/trace/tracing_map.c:286
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_clear
Direct callers:
  - kernel/trace/tracing_map.c:tracing_map_clear
```
**Symbols:**

```
ffffffff811a8de0-ffffffff811a8e2a: tracing_map_array_clear.part.0 (STB_LOCAL)
ffffffff811a93a0-ffffffff811a93b3: tracing_map_array_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
void tracing_map_array_clear(struct tracing_map_array *a);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/tracing_map.c (ffffffff8119c5eb)
Location: kernel/trace/tracing_map.c:286
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_clear
Direct callers:
  - kernel/trace/tracing_map.c:tracing_map_clear
```
**Symbols:**

```
ffffffff8119bd60-ffffffff8119bdaa: tracing_map_array_clear.part.0 (STB_LOCAL)
ffffffff8119c320-ffffffff8119c333: tracing_map_array_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
void tracing_map_array_clear(struct tracing_map_array *a);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/tracing_map.c (ffffffff811a743b)
Location: kernel/trace/tracing_map.c:286
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_clear
Direct callers:
  - kernel/trace/tracing_map.c:tracing_map_clear
```
**Symbols:**

```
ffffffff811a6bb0-ffffffff811a6bfa: tracing_map_array_clear.part.0 (STB_LOCAL)
ffffffff811a7170-ffffffff811a7183: tracing_map_array_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void tracing_map_array_clear(struct tracing_map_array *a);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/tracing_map.c (ffffffff811b51db)
Location: kernel/trace/tracing_map.c:286
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_clear
Direct callers:
  - kernel/trace/tracing_map.c:tracing_map_clear
```
**Symbols:**

```
ffffffff811b4950-ffffffff811b499a: tracing_map_array_clear.part.0 (STB_LOCAL)
ffffffff811b4f10-ffffffff811b4f23: tracing_map_array_clear (STB_GLOBAL)
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
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
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
