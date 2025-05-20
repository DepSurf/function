# Function: <code>genradix_root_to_depth</code>

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
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
unsigned int genradix_root_to_depth(struct genradix_root *r);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/generic-radix-tree.c (ffffffff8150e69c)
Location: lib/generic-radix-tree.c:39
Inline: True
Inline callers:
  - lib/generic-radix-tree.c:__genradix_free
  - lib/generic-radix-tree.c:__genradix_iter_peek
  - lib/generic-radix-tree.c:__genradix_ptr_alloc
  - lib/generic-radix-tree.c:__genradix_ptr
```
**Symbols:**

```
ffffffff8150e8d0-ffffffff8150e8d6: genradix_root_to_depth (STB_GLOBAL)
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
In lib/generic-radix-tree.c (ffffffff8152c7dc)
Location: lib/generic-radix-tree.c:40
Inline: True
Inline callers:
  - lib/generic-radix-tree.c:__genradix_free
  - lib/generic-radix-tree.c:__genradix_iter_peek
  - lib/generic-radix-tree.c:__genradix_ptr_alloc
  - lib/generic-radix-tree.c:__genradix_ptr
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
In lib/generic-radix-tree.c (ffffffff8159040c)
Location: lib/generic-radix-tree.c:40
Inline: True
Inline callers:
  - lib/generic-radix-tree.c:__genradix_free
  - lib/generic-radix-tree.c:__genradix_iter_peek
  - lib/generic-radix-tree.c:__genradix_ptr_alloc
  - lib/generic-radix-tree.c:__genradix_ptr
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
In lib/generic-radix-tree.c (ffffffff815acf7c)
Location: lib/generic-radix-tree.c:40
Inline: True
Inline callers:
  - lib/generic-radix-tree.c:__genradix_free
  - lib/generic-radix-tree.c:__genradix_iter_peek
  - lib/generic-radix-tree.c:__genradix_ptr_alloc
  - lib/generic-radix-tree.c:__genradix_ptr
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
In lib/generic-radix-tree.c (ffffffff815b7bf1)
Location: lib/generic-radix-tree.c:40
Inline: True
Inline callers:
  - lib/generic-radix-tree.c:__genradix_free
  - lib/generic-radix-tree.c:__genradix_iter_peek
  - lib/generic-radix-tree.c:__genradix_ptr_alloc
  - lib/generic-radix-tree.c:__genradix_ptr
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
In lib/generic-radix-tree.c (ffffffff8161e301)
Location: lib/generic-radix-tree.c:40
Inline: True
Inline callers:
  - lib/generic-radix-tree.c:__genradix_free
  - lib/generic-radix-tree.c:__genradix_iter_peek
  - lib/generic-radix-tree.c:__genradix_ptr_alloc
  - lib/generic-radix-tree.c:__genradix_ptr
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
In lib/generic-radix-tree.c (ffffffff816ebf71)
Location: lib/generic-radix-tree.c:40
Inline: True
Inline callers:
  - lib/generic-radix-tree.c:__genradix_free
  - lib/generic-radix-tree.c:__genradix_iter_peek
  - lib/generic-radix-tree.c:__genradix_ptr_alloc
  - lib/generic-radix-tree.c:__genradix_ptr
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
In lib/generic-radix-tree.c (ffffffff817dc711)
Location: lib/generic-radix-tree.c:40
Inline: True
Inline callers:
  - lib/generic-radix-tree.c:__genradix_free
  - lib/generic-radix-tree.c:__genradix_iter_peek
  - lib/generic-radix-tree.c:__genradix_ptr_alloc
  - lib/generic-radix-tree.c:__genradix_ptr
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
In lib/generic-radix-tree.c (ffffffff8181be23)
Location: lib/generic-radix-tree.c:40
Inline: True
Inline callers:
  - lib/generic-radix-tree.c:__genradix_free
  - lib/generic-radix-tree.c:__genradix_iter_peek
  - lib/generic-radix-tree.c:__genradix_ptr_alloc
  - lib/generic-radix-tree.c:__genradix_ptr
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
In lib/generic-radix-tree.c (ffffffff818613a3)
Location: lib/generic-radix-tree.c:41
Inline: True
Inline callers:
  - lib/generic-radix-tree.c:__genradix_free
  - lib/generic-radix-tree.c:__genradix_iter_peek_prev
  - lib/generic-radix-tree.c:__genradix_iter_peek
  - lib/generic-radix-tree.c:__genradix_ptr_alloc
  - lib/generic-radix-tree.c:__genradix_ptr
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
In lib/generic-radix-tree.c (ffff800010638548)
Location: lib/generic-radix-tree.c:40
Inline: True
Inline callers:
  - lib/generic-radix-tree.c:__genradix_free
  - lib/generic-radix-tree.c:__genradix_iter_peek
  - lib/generic-radix-tree.c:__genradix_ptr_alloc
  - lib/generic-radix-tree.c:__genradix_ptr
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/generic-radix-tree.c (c07dde84)
Location: lib/generic-radix-tree.c:40
Inline: True
Inline callers:
  - lib/generic-radix-tree.c:__genradix_free
  - lib/generic-radix-tree.c:__genradix_iter_peek
  - lib/generic-radix-tree.c:__genradix_ptr_alloc
  - lib/generic-radix-tree.c:__genradix_ptr
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/generic-radix-tree.c (c0000000007dece0)
Location: lib/generic-radix-tree.c:40
Inline: True
Inline callers:
  - lib/generic-radix-tree.c:__genradix_free
  - lib/generic-radix-tree.c:__genradix_iter_peek
  - lib/generic-radix-tree.c:__genradix_ptr_alloc
  - lib/generic-radix-tree.c:__genradix_ptr
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/generic-radix-tree.c (ffffffe00046526a)
Location: lib/generic-radix-tree.c:40
Inline: True
Inline callers:
  - lib/generic-radix-tree.c:__genradix_free
  - lib/generic-radix-tree.c:__genradix_iter_peek
  - lib/generic-radix-tree.c:__genradix_ptr_alloc
  - lib/generic-radix-tree.c:__genradix_ptr
```
</details>
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
In lib/generic-radix-tree.c (ffffffff81524dbc)
Location: lib/generic-radix-tree.c:40
Inline: True
Inline callers:
  - lib/generic-radix-tree.c:__genradix_free
  - lib/generic-radix-tree.c:__genradix_iter_peek
  - lib/generic-radix-tree.c:__genradix_ptr_alloc
  - lib/generic-radix-tree.c:__genradix_ptr
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
In lib/generic-radix-tree.c (ffffffff8151509c)
Location: lib/generic-radix-tree.c:40
Inline: True
Inline callers:
  - lib/generic-radix-tree.c:__genradix_free
  - lib/generic-radix-tree.c:__genradix_iter_peek
  - lib/generic-radix-tree.c:__genradix_ptr_alloc
  - lib/generic-radix-tree.c:__genradix_ptr
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
In lib/generic-radix-tree.c (ffffffff81520e4c)
Location: lib/generic-radix-tree.c:40
Inline: True
Inline callers:
  - lib/generic-radix-tree.c:__genradix_free
  - lib/generic-radix-tree.c:__genradix_iter_peek
  - lib/generic-radix-tree.c:__genradix_ptr_alloc
  - lib/generic-radix-tree.c:__genradix_ptr
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
In lib/generic-radix-tree.c (ffffffff8153a7cc)
Location: lib/generic-radix-tree.c:40
Inline: True
Inline callers:
  - lib/generic-radix-tree.c:__genradix_free
  - lib/generic-radix-tree.c:__genradix_iter_peek
  - lib/generic-radix-tree.c:__genradix_ptr_alloc
  - lib/generic-radix-tree.c:__genradix_ptr
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
