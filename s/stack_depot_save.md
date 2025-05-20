# Function: <code>stack_depot_save</code>

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
<summary>In <code>5.19</code>: ✅</summary>

```c
depot_stack_handle_t stack_depot_save(long unsigned int *entries, unsigned int nr_entries, gfp_t alloc_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/stackdepot.c (ffffffff8176fa30)
Location: lib/stackdepot.c:471
Inline: False
Direct callers:
  - mm/slub.c:set_track_prepare
```
**Symbols:**

```
ffffffff8176fa30-ffffffff8176fa4c: stack_depot_save (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
depot_stack_handle_t stack_depot_save(long unsigned int *entries, unsigned int nr_entries, gfp_t alloc_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/stackdepot.c (ffffffff8189f560)
Location: lib/stackdepot.c:529
Inline: False
Direct callers:
  - mm/slub.c:set_track_prepare
```
**Symbols:**

```
ffffffff8189f560-ffffffff8189f584: stack_depot_save (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
depot_stack_handle_t stack_depot_save(long unsigned int *entries, unsigned int nr_entries, gfp_t alloc_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/stackdepot.c (ffffffff818e1b30)
Location: lib/stackdepot.c:452
Inline: False
Direct callers:
  - mm/slub.c:set_track_prepare
```
**Symbols:**

```
ffffffff818e1b30-ffffffff818e1b4c: stack_depot_save (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
depot_stack_handle_t stack_depot_save(long unsigned int *entries, unsigned int nr_entries, gfp_t alloc_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/stackdepot.c (ffffffff81928c80)
Location: lib/stackdepot.c:722
Inline: False
Direct callers:
  - mm/slub.c:set_track_prepare
```
**Symbols:**

```
ffffffff81928c80-ffffffff81928c9c: stack_depot_save (STB_GLOBAL)
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
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
