# Function: <code>depot_alloc_stack</code>

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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct stack_record *depot_alloc_stack(long unsigned int *entries, int size, u32 hash, void **prealloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/stackdepot.c (0)
Location: lib/stackdepot.c:109
Inline: False
Direct callers:
  - lib/stackdepot.c:__stack_depot_save
```
**Symbols:**

```
ffffffff8176f4d0-ffffffff8176f69d: depot_alloc_stack (STB_LOCAL)
ffffffff81ea49b8-ffffffff81ea49cc: depot_alloc_stack.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct stack_record *depot_alloc_stack(long unsigned int *entries, int size, u32 hash, void **prealloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/stackdepot.c (0)
Location: lib/stackdepot.c:120
Inline: False
Direct callers:
  - lib/stackdepot.c:__stack_depot_save
```
**Symbols:**

```
ffffffff8189efc0-ffffffff8189f188: depot_alloc_stack (STB_LOCAL)
ffffffff8208d539-ffffffff8208d54d: depot_alloc_stack.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct stack_record *depot_alloc_stack(long unsigned int *entries, int size, u32 hash, void **prealloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/stackdepot.c (0)
Location: lib/stackdepot.c:260
Inline: False
Direct callers:
  - lib/stackdepot.c:__stack_depot_save
```
**Symbols:**

```
ffffffff818e15a0-ffffffff818e1781: depot_alloc_stack (STB_LOCAL)
ffffffff8210d8d7-ffffffff8210d8eb: depot_alloc_stack.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct stack_record *depot_alloc_stack(long unsigned int *entries, unsigned int nr_entries, u32 hash, depot_flags_t flags, void **prealloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/stackdepot.c (0)
Location: lib/stackdepot.c:423
Inline: False
Direct callers:
  - lib/stackdepot.c:stack_depot_save_flags
```
**Symbols:**

```
ffffffff81928170-ffffffff819284ae: depot_alloc_stack (STB_LOCAL)
ffffffff821eb4c8-ffffffff821eb4dc: depot_alloc_stack.cold (STB_LOCAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int nr_entries</code>
</li>
<li>
<b>Param added. </b>
<code>depot_flags_t flags</code>
</li>
<li>
<b>Param removed. </b>
<code>int size</code>
</li>
<li>
<b>Param reordered. </b>
<code>entries, size, hash, prealloc</code> ➡️ <code>entries, nr_entries, hash, flags, prealloc</code>
</li>
</ul>
</details>
</li>
</ul>
