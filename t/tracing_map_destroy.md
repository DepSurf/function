# Function: <code>tracing_map_destroy</code>

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
void tracing_map_destroy(struct tracing_map *map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/tracing_map.c (ffffffff81160600)
Location: kernel/trace/tracing_map.c:534
Inline: False
Direct callers:
  - kernel/trace/tracing_map.c:tracing_map_create
  - kernel/trace/trace_events_hist.c:destroy_hist_data
```
**Symbols:**

```
ffffffff81160600-ffffffff8116062f: tracing_map_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void tracing_map_destroy(struct tracing_map *map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/tracing_map.c (ffffffff8116b060)
Location: kernel/trace/tracing_map.c:534
Inline: False
Direct callers:
  - kernel/trace/tracing_map.c:tracing_map_create
  - kernel/trace/trace_events_hist.c:destroy_hist_data
```
**Symbols:**

```
ffffffff8116b060-ffffffff8116b08f: tracing_map_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void tracing_map_destroy(struct tracing_map *map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/tracing_map.c (ffffffff8116e000)
Location: kernel/trace/tracing_map.c:537
Inline: False
Direct callers:
  - kernel/trace/tracing_map.c:tracing_map_create
  - kernel/trace/trace_events_hist.c:destroy_hist_data
```
**Symbols:**

```
ffffffff8116e000-ffffffff8116e037: tracing_map_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void tracing_map_destroy(struct tracing_map *map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/tracing_map.c (ffffffff8117b0e0)
Location: kernel/trace/tracing_map.c:538
Inline: False
Direct callers:
  - kernel/trace/tracing_map.c:tracing_map_create
  - kernel/trace/trace_events_hist.c:destroy_hist_data
```
**Symbols:**

```
ffffffff8117b0e0-ffffffff8117b117: tracing_map_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void tracing_map_destroy(struct tracing_map *map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/tracing_map.c (ffffffff8118a270)
Location: kernel/trace/tracing_map.c:677
Inline: False
Direct callers:
  - kernel/trace/tracing_map.c:tracing_map_create
```
**Symbols:**

```
ffffffff8118a270-ffffffff8118a2a6: tracing_map_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void tracing_map_destroy(struct tracing_map *map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/tracing_map.c (ffffffff81197bd0)
Location: kernel/trace/tracing_map.c:668
Inline: False
Direct callers:
  - kernel/trace/tracing_map.c:tracing_map_create
```
**Symbols:**

```
ffffffff81197bd0-ffffffff81197c06: tracing_map_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void tracing_map_destroy(struct tracing_map *map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/tracing_map.c (ffffffff811a57b0)
Location: kernel/trace/tracing_map.c:668
Inline: False
Direct callers:
  - kernel/trace/tracing_map.c:tracing_map_create
```
**Symbols:**

```
ffffffff811a57b0-ffffffff811a57eb: tracing_map_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void tracing_map_destroy(struct tracing_map *map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/tracing_map.c (ffffffff811b0fe0)
Location: kernel/trace/tracing_map.c:668
Inline: False
Direct callers:
  - kernel/trace/tracing_map.c:tracing_map_create
```
**Symbols:**

```
ffffffff811b0fe0-ffffffff811b101b: tracing_map_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void tracing_map_destroy(struct tracing_map *map);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/tracing_map.c (ffffffff811c9736)
Location: kernel/trace/tracing_map.c:668
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_create
Direct callers:
  - kernel/trace/trace_events_hist.c:destroy_hist_data
```
**Symbols:**

```
ffffffff811c9560-ffffffff811c9593: tracing_map_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void tracing_map_destroy(struct tracing_map *map);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/tracing_map.c (ffffffff811c6df6)
Location: kernel/trace/tracing_map.c:668
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_create
Direct callers:
  - kernel/trace/trace_events_hist.c:destroy_hist_data
```
**Symbols:**

```
ffffffff811c6c20-ffffffff811c6c53: tracing_map_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void tracing_map_destroy(struct tracing_map *map);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/tracing_map.c (ffffffff811c7de6)
Location: kernel/trace/tracing_map.c:668
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_create
Direct callers:
  - kernel/trace/trace_events_hist.c:destroy_hist_data
```
**Symbols:**

```
ffffffff811c7c10-ffffffff811c7c43: tracing_map_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void tracing_map_destroy(struct tracing_map *map);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/tracing_map.c (ffffffff811f3736)
Location: kernel/trace/tracing_map.c:671
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_create
Direct callers:
  - kernel/trace/trace_events_hist.c:destroy_hist_data
```
**Symbols:**

```
ffffffff811f3530-ffffffff811f3563: tracing_map_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void tracing_map_destroy(struct tracing_map *map);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/tracing_map.c (ffffffff8122ce35)
Location: kernel/trace/tracing_map.c:671
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_create
Direct callers:
  - kernel/trace/trace_events_hist.c:destroy_hist_data
```
**Symbols:**

```
ffffffff8122cc20-ffffffff8122cc5d: tracing_map_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void tracing_map_destroy(struct tracing_map *map);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/tracing_map.c (ffffffff81278a95)
Location: kernel/trace/tracing_map.c:671
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_create
Direct callers:
  - kernel/trace/trace_events_hist.c:destroy_hist_data
```
**Symbols:**

```
ffffffff81278860-ffffffff8127889d: tracing_map_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void tracing_map_destroy(struct tracing_map *map);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/tracing_map.c (ffffffff812904d5)
Location: kernel/trace/tracing_map.c:671
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_create
Direct callers:
  - kernel/trace/trace_events_hist.c:destroy_hist_data
```
**Symbols:**

```
ffffffff812902a0-ffffffff812902dd: tracing_map_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void tracing_map_destroy(struct tracing_map *map);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/tracing_map.c (ffffffff812abac4)
Location: kernel/trace/tracing_map.c:676
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_create
Direct callers:
  - kernel/trace/trace_events_hist.c:destroy_hist_data
```
**Symbols:**

```
ffffffff812ab860-ffffffff812ab89d: tracing_map_destroy (STB_GLOBAL)
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
void tracing_map_destroy(struct tracing_map *map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/tracing_map.c (ffff80001022ec28)
Location: kernel/trace/tracing_map.c:668
Inline: False
Direct callers:
  - kernel/trace/tracing_map.c:tracing_map_create
```
**Symbols:**

```
ffff80001022ec28-ffff80001022ec70: tracing_map_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void tracing_map_destroy(struct tracing_map *map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/tracing_map.c (c0000000002b82b0)
Location: kernel/trace/tracing_map.c:668
Inline: False
Direct callers:
  - kernel/trace/tracing_map.c:tracing_map_create
```
**Symbols:**

```
c0000000002b82b0-c0000000002b8310: tracing_map_destroy (STB_GLOBAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
void tracing_map_destroy(struct tracing_map *map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/tracing_map.c (ffffffff811a9600)
Location: kernel/trace/tracing_map.c:668
Inline: False
Direct callers:
  - kernel/trace/tracing_map.c:tracing_map_create
```
**Symbols:**

```
ffffffff811a9600-ffffffff811a963b: tracing_map_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void tracing_map_destroy(struct tracing_map *map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/tracing_map.c (ffffffff8119c580)
Location: kernel/trace/tracing_map.c:668
Inline: False
Direct callers:
  - kernel/trace/tracing_map.c:tracing_map_create
```
**Symbols:**

```
ffffffff8119c580-ffffffff8119c5bb: tracing_map_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void tracing_map_destroy(struct tracing_map *map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/tracing_map.c (ffffffff811a73d0)
Location: kernel/trace/tracing_map.c:668
Inline: False
Direct callers:
  - kernel/trace/tracing_map.c:tracing_map_create
```
**Symbols:**

```
ffffffff811a73d0-ffffffff811a740b: tracing_map_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void tracing_map_destroy(struct tracing_map *map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/tracing_map.c (ffffffff811b5170)
Location: kernel/trace/tracing_map.c:668
Inline: False
Direct callers:
  - kernel/trace/tracing_map.c:tracing_map_create
```
**Symbols:**

```
ffffffff811b5170-ffffffff811b51ab: tracing_map_destroy (STB_GLOBAL)
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
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
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
