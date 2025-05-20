# Function: <code>set_track_prepare</code>

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
depot_stack_handle_t set_track_prepare();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff813a3e50)
Location: mm/slub.c:730
Inline: False
Direct callers:
  - mm/slub.c:free_debug_processing
  - mm/slub.c:alloc_debug_processing
```
**Symbols:**

```
ffffffff813a3e50-ffffffff813a3ec9: set_track_prepare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
depot_stack_handle_t set_track_prepare();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81423eb0)
Location: mm/slub.c:745
Inline: False
Direct callers:
  - mm/slub.c:free_to_partial_list
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
```
**Symbols:**

```
ffffffff81423eb0-ffffffff81423f29: set_track_prepare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
depot_stack_handle_t set_track_prepare();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81459150)
Location: mm/slub.c:766
Inline: False
Direct callers:
  - mm/slub.c:free_to_partial_list
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
```
**Symbols:**

```
ffffffff81459150-ffffffff814591c9: set_track_prepare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
depot_stack_handle_t set_track_prepare();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81454110)
Location: mm/slub.c:879
Inline: False
Direct callers:
  - mm/slub.c:free_to_partial_list
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
```
**Symbols:**

```
ffffffff81454110-ffffffff81454189: set_track_prepare (STB_LOCAL)
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
