# Function: <code>get_free_elt</code>

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
struct tracing_map_elt *get_free_elt(struct tracing_map *map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/tracing_map.c (ffffffff8115fa90)
Location: kernel/trace/tracing_map.c:347
Inline: False
Direct callers:
  - kernel/trace/tracing_map.c:tracing_map_insert
```
**Symbols:**

```
ffffffff8115fa90-ffffffff8115faee: get_free_elt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct tracing_map_elt *get_free_elt(struct tracing_map *map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/tracing_map.c (ffffffff8116a4f0)
Location: kernel/trace/tracing_map.c:347
Inline: False
Direct callers:
  - kernel/trace/tracing_map.c:tracing_map_insert
```
**Symbols:**

```
ffffffff8116a4f0-ffffffff8116a54e: get_free_elt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct tracing_map_elt *get_free_elt(struct tracing_map *map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/tracing_map.c (ffffffff8116d490)
Location: kernel/trace/tracing_map.c:350
Inline: False
Direct callers:
  - kernel/trace/tracing_map.c:tracing_map_insert
```
**Symbols:**

```
ffffffff8116d490-ffffffff8116d4ea: get_free_elt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct tracing_map_elt *get_free_elt(struct tracing_map *map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/tracing_map.c (ffffffff8117a540)
Location: kernel/trace/tracing_map.c:350
Inline: False
Direct callers:
  - kernel/trace/tracing_map.c:tracing_map_insert
```
**Symbols:**

```
ffffffff8117a540-ffffffff8117a59d: get_free_elt (STB_LOCAL)
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
In kernel/trace/tracing_map.c (ffffffff81189edf)
Location: kernel/trace/tracing_map.c:458
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_insert
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
In kernel/trace/tracing_map.c (ffffffff811977f2)
Location: kernel/trace/tracing_map.c:449
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_insert
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
In kernel/trace/tracing_map.c (ffffffff811a51fe)
Location: kernel/trace/tracing_map.c:449
Inline: True
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
In kernel/trace/tracing_map.c (ffffffff811b0a2e)
Location: kernel/trace/tracing_map.c:449
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct tracing_map_elt *get_free_elt(struct tracing_map *map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/tracing_map.c (ffffffff811c88c0)
Location: kernel/trace/tracing_map.c:449
Inline: False
Direct callers:
  - kernel/trace/tracing_map.c:__tracing_map_insert
```
**Symbols:**

```
ffffffff811c88c0-ffffffff811c8920: get_free_elt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct tracing_map_elt *get_free_elt(struct tracing_map *map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/tracing_map.c (ffffffff811c5fa0)
Location: kernel/trace/tracing_map.c:449
Inline: False
Direct callers:
  - kernel/trace/tracing_map.c:__tracing_map_insert
```
**Symbols:**

```
ffffffff811c5fa0-ffffffff811c6000: get_free_elt (STB_LOCAL)
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
In kernel/trace/tracing_map.c (ffffffff811c7642)
Location: kernel/trace/tracing_map.c:449
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:__tracing_map_insert
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
In kernel/trace/tracing_map.c (ffffffff811f2d73)
Location: kernel/trace/tracing_map.c:452
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:__tracing_map_insert
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
In kernel/trace/tracing_map.c (ffffffff8122c32a)
Location: kernel/trace/tracing_map.c:452
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:__tracing_map_insert
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
In kernel/trace/tracing_map.c (ffffffff81277e5a)
Location: kernel/trace/tracing_map.c:452
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:__tracing_map_insert
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
In kernel/trace/tracing_map.c (ffffffff8128f89a)
Location: kernel/trace/tracing_map.c:452
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:__tracing_map_insert
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
In kernel/trace/tracing_map.c (ffffffff812aadfa)
Location: kernel/trace/tracing_map.c:452
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:__tracing_map_insert
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
In kernel/trace/tracing_map.c (ffff80001022e1dc)
Location: kernel/trace/tracing_map.c:449
Inline: True
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
In kernel/trace/tracing_map.c (c0000000002b7530)
Location: kernel/trace/tracing_map.c:449
Inline: True
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
In kernel/trace/tracing_map.c (ffffffff811a904e)
Location: kernel/trace/tracing_map.c:449
Inline: True
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
In kernel/trace/tracing_map.c (ffffffff8119bfce)
Location: kernel/trace/tracing_map.c:449
Inline: True
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
In kernel/trace/tracing_map.c (ffffffff811a6e1e)
Location: kernel/trace/tracing_map.c:449
Inline: True
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
In kernel/trace/tracing_map.c (ffffffff811b4bbe)
Location: kernel/trace/tracing_map.c:449
Inline: True
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
</ul>
