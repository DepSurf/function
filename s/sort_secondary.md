# Function: <code>sort_secondary</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/tracing_map.c (ffffffff81160b56)
Location: kernel/trace/tracing_map.c:920
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_sort_entries
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
In kernel/trace/tracing_map.c (ffffffff8116b5b6)
Location: kernel/trace/tracing_map.c:920
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_sort_entries
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
In kernel/trace/tracing_map.c (ffffffff8116e594)
Location: kernel/trace/tracing_map.c:923
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_sort_entries
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
In kernel/trace/tracing_map.c (ffffffff8117b680)
Location: kernel/trace/tracing_map.c:924
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_sort_entries
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
In kernel/trace/tracing_map.c (ffffffff8118a90d)
Location: kernel/trace/tracing_map.c:995
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_sort_entries
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
In kernel/trace/tracing_map.c (ffffffff8119826d)
Location: kernel/trace/tracing_map.c:986
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_sort_entries
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
In kernel/trace/tracing_map.c (ffffffff811a5de6)
Location: kernel/trace/tracing_map.c:986
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_sort_entries
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
In kernel/trace/tracing_map.c (ffffffff811b1616)
Location: kernel/trace/tracing_map.c:986
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_sort_entries
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void sort_secondary(struct tracing_map *map, const struct tracing_map_sort_entry **entries, unsigned int n_entries, struct tracing_map_sort_key *primary_key, struct tracing_map_sort_key *secondary_key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/tracing_map.c (ffffffff811c8ad0)
Location: kernel/trace/tracing_map.c:986
Inline: False
Direct callers:
  - kernel/trace/tracing_map.c:tracing_map_sort_entries
```
**Symbols:**

```
ffffffff811c8ad0-ffffffff811c8c3c: sort_secondary (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void sort_secondary(struct tracing_map *map, const struct tracing_map_sort_entry **entries, unsigned int n_entries, struct tracing_map_sort_key *primary_key, struct tracing_map_sort_key *secondary_key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/tracing_map.c (ffffffff811c6190)
Location: kernel/trace/tracing_map.c:986
Inline: False
Direct callers:
  - kernel/trace/tracing_map.c:tracing_map_sort_entries
```
**Symbols:**

```
ffffffff811c6190-ffffffff811c62fc: sort_secondary (STB_LOCAL)
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
In kernel/trace/tracing_map.c (ffffffff811c80a8)
Location: kernel/trace/tracing_map.c:986
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_sort_entries
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
In kernel/trace/tracing_map.c (ffffffff811f3a7d)
Location: kernel/trace/tracing_map.c:998
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_sort_entries
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
In kernel/trace/tracing_map.c (ffffffff8122d16b)
Location: kernel/trace/tracing_map.c:998
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_sort_entries
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
In kernel/trace/tracing_map.c (ffffffff81278e15)
Location: kernel/trace/tracing_map.c:997
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_sort_entries
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
In kernel/trace/tracing_map.c (ffffffff81290855)
Location: kernel/trace/tracing_map.c:997
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_sort_entries
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
In kernel/trace/tracing_map.c (ffffffff812abe7a)
Location: kernel/trace/tracing_map.c:1002
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_sort_entries
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
In kernel/trace/tracing_map.c (ffff80001022f288)
Location: kernel/trace/tracing_map.c:986
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_sort_entries
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
In kernel/trace/tracing_map.c (c0000000002b8b90)
Location: kernel/trace/tracing_map.c:986
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_sort_entries
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
In kernel/trace/tracing_map.c (ffffffff811a9c36)
Location: kernel/trace/tracing_map.c:986
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_sort_entries
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
In kernel/trace/tracing_map.c (ffffffff8119cbb6)
Location: kernel/trace/tracing_map.c:986
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_sort_entries
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
In kernel/trace/tracing_map.c (ffffffff811a7a06)
Location: kernel/trace/tracing_map.c:986
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_sort_entries
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
In kernel/trace/tracing_map.c (ffffffff811b57a6)
Location: kernel/trace/tracing_map.c:986
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_sort_entries
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
</ul>
