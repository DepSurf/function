# Function: <code>destroy_sort_entry</code>

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
void destroy_sort_entry(struct tracing_map_sort_entry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/tracing_map.c (ffffffff8115fbe0)
Location: kernel/trace/tracing_map.c:771
Inline: False
Direct callers:
  - kernel/trace/tracing_map.c:tracing_map_sort_entries
  - kernel/trace/tracing_map.c:tracing_map_destroy_sort_entries
```
**Symbols:**

```
ffffffff8115fbe0-ffffffff8115fc0a: destroy_sort_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void destroy_sort_entry(struct tracing_map_sort_entry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/tracing_map.c (ffffffff8116a640)
Location: kernel/trace/tracing_map.c:771
Inline: False
Direct callers:
  - kernel/trace/tracing_map.c:tracing_map_sort_entries
  - kernel/trace/tracing_map.c:tracing_map_destroy_sort_entries
```
**Symbols:**

```
ffffffff8116a640-ffffffff8116a66a: destroy_sort_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void destroy_sort_entry(struct tracing_map_sort_entry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/tracing_map.c (ffffffff8116d5e0)
Location: kernel/trace/tracing_map.c:774
Inline: False
Direct callers:
  - kernel/trace/tracing_map.c:tracing_map_sort_entries
  - kernel/trace/tracing_map.c:tracing_map_destroy_sort_entries
```
**Symbols:**

```
ffffffff8116d5e0-ffffffff8116d614: destroy_sort_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void destroy_sort_entry(struct tracing_map_sort_entry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/tracing_map.c (ffffffff8117a690)
Location: kernel/trace/tracing_map.c:775
Inline: False
Direct callers:
  - kernel/trace/tracing_map.c:tracing_map_sort_entries
  - kernel/trace/tracing_map.c:tracing_map_destroy_sort_entries
```
**Symbols:**

```
ffffffff8117a690-ffffffff8117a6c4: destroy_sort_entry (STB_LOCAL)
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
In kernel/trace/tracing_map.c (ffffffff8118a6a3)
Location: kernel/trace/tracing_map.c:914
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_destroy_sort_entries
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
In kernel/trace/tracing_map.c (ffffffff81198003)
Location: kernel/trace/tracing_map.c:905
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_destroy_sort_entries
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
In kernel/trace/tracing_map.c (ffffffff811a5bd3)
Location: kernel/trace/tracing_map.c:905
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_destroy_sort_entries
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
In kernel/trace/tracing_map.c (ffffffff811b1403)
Location: kernel/trace/tracing_map.c:905
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_destroy_sort_entries
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
In kernel/trace/tracing_map.c (ffffffff811c9a69)
Location: kernel/trace/tracing_map.c:905
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_sort_entries
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
In kernel/trace/tracing_map.c (ffffffff811c7129)
Location: kernel/trace/tracing_map.c:905
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_sort_entries
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
In kernel/trace/tracing_map.c (ffffffff811c8224)
Location: kernel/trace/tracing_map.c:905
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
In kernel/trace/tracing_map.c (ffffffff811f37e5)
Location: kernel/trace/tracing_map.c:917
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_destroy_sort_entries
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
In kernel/trace/tracing_map.c (ffffffff8122cee3)
Location: kernel/trace/tracing_map.c:917
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_destroy_sort_entries
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
In kernel/trace/tracing_map.c (ffffffff81278b63)
Location: kernel/trace/tracing_map.c:917
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_destroy_sort_entries
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
In kernel/trace/tracing_map.c (ffffffff812905a3)
Location: kernel/trace/tracing_map.c:917
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_destroy_sort_entries
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
In kernel/trace/tracing_map.c (ffffffff812abb93)
Location: kernel/trace/tracing_map.c:922
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_destroy_sort_entries
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
In kernel/trace/tracing_map.c (ffff80001022f088)
Location: kernel/trace/tracing_map.c:905
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_destroy_sort_entries
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
In kernel/trace/tracing_map.c (c0000000002b88d8)
Location: kernel/trace/tracing_map.c:905
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_destroy_sort_entries
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
In kernel/trace/tracing_map.c (ffffffff811a9a23)
Location: kernel/trace/tracing_map.c:905
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_destroy_sort_entries
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
In kernel/trace/tracing_map.c (ffffffff8119c9a3)
Location: kernel/trace/tracing_map.c:905
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_destroy_sort_entries
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
In kernel/trace/tracing_map.c (ffffffff811a77f3)
Location: kernel/trace/tracing_map.c:905
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_destroy_sort_entries
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
In kernel/trace/tracing_map.c (ffffffff811b5593)
Location: kernel/trace/tracing_map.c:905
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_destroy_sort_entries
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
</ul>
