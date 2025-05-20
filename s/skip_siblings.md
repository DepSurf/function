# Function: <code>skip_siblings</code>

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
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff81450589)
Location: lib/radix-tree.c:1470
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_iter_resume
  - lib/radix-tree.c:__radix_tree_next_slot
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
In lib/radix-tree.c (ffffffff818f02dc)
Location: lib/radix-tree.c:1613
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_iter_resume
  - lib/radix-tree.c:__radix_tree_next_slot
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
In lib/radix-tree.c (ffffffff8197672c)
Location: lib/radix-tree.c:1611
Inline: True
Inline callers:
  - lib/radix-tree.c:radix_tree_iter_resume
  - lib/radix-tree.c:__radix_tree_next_slot
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void **skip_siblings(struct radix_tree_node **nodep, void **slot, struct radix_tree_iter *iter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/radix-tree.c (ffffffff819d2e20)
Location: lib/radix-tree.c:1612
Inline: False
Direct callers:
  - lib/radix-tree.c:radix_tree_iter_resume
  - lib/radix-tree.c:__radix_tree_next_slot
```
**Symbols:**

```
ffffffff819d2e20-ffffffff819d2e80: skip_siblings (STB_LOCAL)
```
</details>
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
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
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
</ul>
