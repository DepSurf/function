# Function: <code>mtree_range_walk</code>

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
In <code>5.19</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/maple_tree.c (ffffffff82030a67)
Location: lib/maple_tree.c:2895
Inline: True
Inline callers:
  - lib/maple_tree.c:mt_find
  - lib/maple_tree.c:mas_erase
  - lib/maple_tree.c:mas_destroy
  - lib/maple_tree.c:mas_prev_entry
  - lib/maple_tree.c:mas_prev_entry
  - lib/maple_tree.c:mas_next_entry
  - lib/maple_tree.c:mas_next_entry
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void *mtree_range_walk(struct ma_state *mas);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/maple_tree.c (ffffffff820a7cc0)
Location: lib/maple_tree.c:2932
Inline: False
Direct callers:
  - lib/maple_tree.c:mt_find
  - lib/maple_tree.c:mas_erase
  - lib/maple_tree.c:mas_destroy
  - lib/maple_tree.c:mas_walk
  - lib/maple_tree.c:mas_next_slot
  - lib/maple_tree.c:mas_next_slot
  - lib/maple_tree.c:mas_next_slot
  - lib/maple_tree.c:mas_next_slot
  - lib/maple_tree.c:mas_prev_slot
  - lib/maple_tree.c:mas_prev_slot
  - lib/maple_tree.c:mas_prev_slot
  - lib/maple_tree.c:mas_prev_slot
```
**Symbols:**

```
ffffffff820a7cc0-ffffffff820a7eed: mtree_range_walk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void *mtree_range_walk(struct ma_state *mas);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/maple_tree.c (ffffffff8218dc59)
Location: lib/maple_tree.c:2753
Inline: True
Inline callers:
  - lib/maple_tree.c:mt_find
  - lib/maple_tree.c:mas_erase
  - lib/maple_tree.c:mas_destroy
  - lib/maple_tree.c:mas_walk
  - lib/maple_tree.c:mas_next_slot
  - lib/maple_tree.c:mas_prev_slot
Direct callers:
  - lib/maple_tree.c:mas_next_slot
  - lib/maple_tree.c:mas_next_slot
  - lib/maple_tree.c:mas_prev_slot
  - lib/maple_tree.c:mas_prev_slot
```
**Symbols:**

```
ffffffff8217e0e0-ffffffff8217e3a2: mtree_range_walk (STB_LOCAL)
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
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
