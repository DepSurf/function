# Function: <code>interval_subtree_search</code>

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
struct memtype *interval_subtree_search(struct memtype *node, u64 start, u64 last);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/memtype_interval.c (ffffffff81090b50)
Location: arch/x86/mm/pat/memtype_interval.c:46
Inline: False
Direct callers:
  - arch/x86/mm/pat/memtype_interval.c:memtype_copy_nth_element
  - arch/x86/mm/pat/memtype_interval.c:memtype_lookup
  - arch/x86/mm/pat/memtype_interval.c:memtype_check_conflict
  - arch/x86/mm/pat/memtype_interval.c:memtype_match
  - arch/x86/mm/pat/memtype_interval.c:interval_iter_next
```
**Symbols:**

```
ffffffff81090b50-ffffffff81090ba1: interval_subtree_search (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct memtype *interval_subtree_search(struct memtype *node, u64 start, u64 last);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/memtype_interval.c (ffffffff81090510)
Location: arch/x86/mm/pat/memtype_interval.c:46
Inline: False
Direct callers:
  - arch/x86/mm/pat/memtype_interval.c:memtype_copy_nth_element
  - arch/x86/mm/pat/memtype_interval.c:memtype_lookup
  - arch/x86/mm/pat/memtype_interval.c:memtype_check_conflict
  - arch/x86/mm/pat/memtype_interval.c:memtype_match
  - arch/x86/mm/pat/memtype_interval.c:interval_iter_next
```
**Symbols:**

```
ffffffff81090510-ffffffff81090561: interval_subtree_search (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct memtype *interval_subtree_search(struct memtype *node, u64 start, u64 last);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/memtype_interval.c (ffffffff81091080)
Location: arch/x86/mm/pat/memtype_interval.c:46
Inline: False
Direct callers:
  - arch/x86/mm/pat/memtype_interval.c:memtype_copy_nth_element
  - arch/x86/mm/pat/memtype_interval.c:memtype_lookup
  - arch/x86/mm/pat/memtype_interval.c:memtype_check_insert
  - arch/x86/mm/pat/memtype_interval.c:memtype_match
  - arch/x86/mm/pat/memtype_interval.c:interval_iter_next
```
**Symbols:**

```
ffffffff81091080-ffffffff810910d1: interval_subtree_search (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct memtype *interval_subtree_search(struct memtype *node, u64 start, u64 last);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/memtype_interval.c (ffffffff810a0c00)
Location: arch/x86/mm/pat/memtype_interval.c:46
Inline: False
Direct callers:
  - arch/x86/mm/pat/memtype_interval.c:memtype_copy_nth_element
  - arch/x86/mm/pat/memtype_interval.c:memtype_lookup
  - arch/x86/mm/pat/memtype_interval.c:memtype_check_insert
  - arch/x86/mm/pat/memtype_interval.c:memtype_match
  - arch/x86/mm/pat/memtype_interval.c:interval_iter_next
```
**Symbols:**

```
ffffffff810a0c00-ffffffff810a0c51: interval_subtree_search (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct memtype *interval_subtree_search(struct memtype *node, u64 start, u64 last);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/memtype_interval.c (ffffffff810b4c20)
Location: arch/x86/mm/pat/memtype_interval.c:46
Inline: False
Direct callers:
  - arch/x86/mm/pat/memtype_interval.c:memtype_copy_nth_element
  - arch/x86/mm/pat/memtype_interval.c:memtype_lookup
  - arch/x86/mm/pat/memtype_interval.c:memtype_check_insert
  - arch/x86/mm/pat/memtype_interval.c:memtype_match
  - arch/x86/mm/pat/memtype_interval.c:interval_iter_next
```
**Symbols:**

```
ffffffff810b4c20-ffffffff810b4c85: interval_subtree_search (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct memtype *interval_subtree_search(struct memtype *node, u64 start, u64 last);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/memtype_interval.c (ffffffff810cfa30)
Location: arch/x86/mm/pat/memtype_interval.c:46
Inline: False
Direct callers:
  - arch/x86/mm/pat/memtype_interval.c:memtype_copy_nth_element
  - arch/x86/mm/pat/memtype_interval.c:memtype_lookup
  - arch/x86/mm/pat/memtype_interval.c:memtype_check_insert
  - arch/x86/mm/pat/memtype_interval.c:memtype_match
  - arch/x86/mm/pat/memtype_interval.c:interval_iter_next
```
**Symbols:**

```
ffffffff810cfa30-ffffffff810cfa95: interval_subtree_search (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct memtype *interval_subtree_search(struct memtype *node, u64 start, u64 last);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/memtype_interval.c (ffffffff810d3070)
Location: arch/x86/mm/pat/memtype_interval.c:46
Inline: False
Direct callers:
  - arch/x86/mm/pat/memtype_interval.c:memtype_copy_nth_element
  - arch/x86/mm/pat/memtype_interval.c:memtype_lookup
  - arch/x86/mm/pat/memtype_interval.c:memtype_check_insert
  - arch/x86/mm/pat/memtype_interval.c:memtype_match
  - arch/x86/mm/pat/memtype_interval.c:interval_iter_next
```
**Symbols:**

```
ffffffff810d3070-ffffffff810d30d5: interval_subtree_search (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct memtype *interval_subtree_search(struct memtype *node, u64 start, u64 last);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/memtype_interval.c (ffffffff810db800)
Location: arch/x86/mm/pat/memtype_interval.c:46
Inline: False
Direct callers:
  - arch/x86/mm/pat/memtype_interval.c:memtype_copy_nth_element
  - arch/x86/mm/pat/memtype_interval.c:memtype_lookup
  - arch/x86/mm/pat/memtype_interval.c:memtype_check_insert
  - arch/x86/mm/pat/memtype_interval.c:memtype_match
  - arch/x86/mm/pat/memtype_interval.c:interval_iter_next
```
**Symbols:**

```
ffffffff810db800-ffffffff810db865: interval_subtree_search (STB_LOCAL)
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
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
