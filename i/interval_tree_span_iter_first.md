# Function: <code>interval_tree_span_iter_first</code>

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
<summary>In <code>6.2</code>: ✅</summary>

```c
void interval_tree_span_iter_first(struct interval_tree_span_iter *iter, struct rb_root_cached *itree, long unsigned int first_index, long unsigned int last_index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/interval_tree.c (ffffffff817e9290)
Location: lib/interval_tree.c:43
Inline: False
Direct callers:
  - lib/interval_tree.c:interval_tree_span_iter_advance
```
**Symbols:**

```
ffffffff817e9290-ffffffff817e9386: interval_tree_span_iter_first (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void interval_tree_span_iter_first(struct interval_tree_span_iter *iter, struct rb_root_cached *itree, long unsigned int first_index, long unsigned int last_index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/interval_tree.c (ffffffff81829250)
Location: lib/interval_tree.c:43
Inline: False
Direct callers:
  - lib/interval_tree.c:interval_tree_span_iter_advance
```
**Symbols:**

```
ffffffff81829250-ffffffff81829346: interval_tree_span_iter_first (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void interval_tree_span_iter_first(struct interval_tree_span_iter *iter, struct rb_root_cached *itree, long unsigned int first_index, long unsigned int last_index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/interval_tree.c (ffffffff8187ac60)
Location: lib/interval_tree.c:43
Inline: False
Direct callers:
  - lib/interval_tree.c:interval_tree_span_iter_advance
```
**Symbols:**

```
ffffffff8187ac60-ffffffff8187ad56: interval_tree_span_iter_first (STB_GLOBAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
