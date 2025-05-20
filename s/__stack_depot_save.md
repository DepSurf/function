# Function: <code>__stack_depot_save</code>

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
depot_stack_handle_t __stack_depot_save(long unsigned int *entries, unsigned int nr_entries, gfp_t alloc_flags, bool can_alloc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/stackdepot.c (0)
Location: lib/stackdepot.c:364
Inline: False
Direct callers:
  - lib/stackdepot.c:stack_depot_save
```
**Symbols:**

```
ffffffff81ea49cc-ffffffff81ea49e7: __stack_depot_save.cold (STB_LOCAL)
ffffffff8176f6a0-ffffffff8176fa26: __stack_depot_save (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
depot_stack_handle_t __stack_depot_save(long unsigned int *entries, unsigned int nr_entries, unsigned int extra_bits, gfp_t alloc_flags, bool can_alloc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/stackdepot.c (0)
Location: lib/stackdepot.c:419
Inline: False
Direct callers:
  - lib/stackdepot.c:stack_depot_save
```
**Symbols:**

```
ffffffff8208d54d-ffffffff8208d568: __stack_depot_save.cold (STB_LOCAL)
ffffffff8189f1a0-ffffffff8189f54e: __stack_depot_save (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
depot_stack_handle_t __stack_depot_save(long unsigned int *entries, unsigned int nr_entries, gfp_t alloc_flags, bool can_alloc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/stackdepot.c (0)
Location: lib/stackdepot.c:358
Inline: False
Direct callers:
  - lib/stackdepot.c:stack_depot_save
```
**Symbols:**

```
ffffffff8210d8eb-ffffffff8210d906: __stack_depot_save.cold (STB_LOCAL)
ffffffff818e17a0-ffffffff818e1b13: __stack_depot_save (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int extra_bits</code>
</li>
<li>
<b>Param reordered. </b>
<code>entries, nr_entries, alloc_flags, can_alloc</code> ➡️ <code>entries, nr_entries, extra_bits, alloc_flags, can_alloc</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>unsigned int extra_bits</code>
</li>
<li>
<b>Param reordered. </b>
<code>entries, nr_entries, extra_bits, alloc_flags, can_alloc</code> ➡️ <code>entries, nr_entries, alloc_flags, can_alloc</code>
</li>
</ul>
</details>
</li>
</ul>
