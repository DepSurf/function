# Function: <code>interval_iter_next</code>

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
struct memtype *interval_iter_next(struct memtype *node, u64 start, u64 last);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/memtype_interval.c (ffffffff81090bb0)
Location: arch/x86/mm/pat/memtype_interval.c:46
Inline: False
Direct callers:
  - arch/x86/mm/pat/memtype_interval.c:memtype_copy_nth_element
  - arch/x86/mm/pat/memtype_interval.c:memtype_check_conflict
  - arch/x86/mm/pat/memtype_interval.c:memtype_match
```
**Symbols:**

```
ffffffff81090bb0-ffffffff81090c10: interval_iter_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct memtype *interval_iter_next(struct memtype *node, u64 start, u64 last);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/memtype_interval.c (ffffffff81090570)
Location: arch/x86/mm/pat/memtype_interval.c:46
Inline: False
Direct callers:
  - arch/x86/mm/pat/memtype_interval.c:memtype_copy_nth_element
  - arch/x86/mm/pat/memtype_interval.c:memtype_check_conflict
  - arch/x86/mm/pat/memtype_interval.c:memtype_match
```
**Symbols:**

```
ffffffff81090570-ffffffff810905d0: interval_iter_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct memtype *interval_iter_next(struct memtype *node, u64 start, u64 last);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/memtype_interval.c (ffffffff810910e0)
Location: arch/x86/mm/pat/memtype_interval.c:46
Inline: False
Direct callers:
  - arch/x86/mm/pat/memtype_interval.c:memtype_copy_nth_element
  - arch/x86/mm/pat/memtype_interval.c:memtype_check_insert
  - arch/x86/mm/pat/memtype_interval.c:memtype_match
```
**Symbols:**

```
ffffffff810910e0-ffffffff8109113a: interval_iter_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct memtype *interval_iter_next(struct memtype *node, u64 start, u64 last);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/memtype_interval.c (ffffffff810a0c60)
Location: arch/x86/mm/pat/memtype_interval.c:46
Inline: False
Direct callers:
  - arch/x86/mm/pat/memtype_interval.c:memtype_copy_nth_element
  - arch/x86/mm/pat/memtype_interval.c:memtype_check_insert
  - arch/x86/mm/pat/memtype_interval.c:memtype_match
```
**Symbols:**

```
ffffffff810a0c60-ffffffff810a0cba: interval_iter_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct memtype *interval_iter_next(struct memtype *node, u64 start, u64 last);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/memtype_interval.c (ffffffff810b4c90)
Location: arch/x86/mm/pat/memtype_interval.c:46
Inline: False
Direct callers:
  - arch/x86/mm/pat/memtype_interval.c:memtype_copy_nth_element
  - arch/x86/mm/pat/memtype_interval.c:memtype_check_insert
  - arch/x86/mm/pat/memtype_interval.c:memtype_match
```
**Symbols:**

```
ffffffff810b4c90-ffffffff810b4d1e: interval_iter_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct memtype *interval_iter_next(struct memtype *node, u64 start, u64 last);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/memtype_interval.c (ffffffff810cfab0)
Location: arch/x86/mm/pat/memtype_interval.c:46
Inline: False
Direct callers:
  - arch/x86/mm/pat/memtype_interval.c:memtype_copy_nth_element
  - arch/x86/mm/pat/memtype_interval.c:memtype_check_insert
  - arch/x86/mm/pat/memtype_interval.c:memtype_check_insert
  - arch/x86/mm/pat/memtype_interval.c:memtype_match
```
**Symbols:**

```
ffffffff810cfab0-ffffffff810cfb3e: interval_iter_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct memtype *interval_iter_next(struct memtype *node, u64 start, u64 last);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/memtype_interval.c (ffffffff810d30f0)
Location: arch/x86/mm/pat/memtype_interval.c:46
Inline: False
Direct callers:
  - arch/x86/mm/pat/memtype_interval.c:memtype_copy_nth_element
  - arch/x86/mm/pat/memtype_interval.c:memtype_check_insert
  - arch/x86/mm/pat/memtype_interval.c:memtype_check_insert
  - arch/x86/mm/pat/memtype_interval.c:memtype_match
```
**Symbols:**

```
ffffffff810d30f0-ffffffff810d317e: interval_iter_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct memtype *interval_iter_next(struct memtype *node, u64 start, u64 last);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/memtype_interval.c (ffffffff810db880)
Location: arch/x86/mm/pat/memtype_interval.c:46
Inline: False
Direct callers:
  - arch/x86/mm/pat/memtype_interval.c:memtype_copy_nth_element
  - arch/x86/mm/pat/memtype_interval.c:memtype_check_insert
  - arch/x86/mm/pat/memtype_interval.c:memtype_check_insert
  - arch/x86/mm/pat/memtype_interval.c:memtype_match
```
**Symbols:**

```
ffffffff810db880-ffffffff810db90e: interval_iter_next (STB_LOCAL)
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
