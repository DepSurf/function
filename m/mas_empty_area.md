# Function: <code>mas_empty_area</code>

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
int mas_empty_area(struct ma_state *mas, long unsigned int min, long unsigned int max, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/maple_tree.c (ffffffff8202a0c0)
Location: lib/maple_tree.c:5233
Inline: False
Direct callers:
  - mm/mmap.c:vm_unmapped_area
```
**Symbols:**

```
ffffffff8202a0c0-ffffffff8202a53b: mas_empty_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int mas_empty_area(struct ma_state *mas, long unsigned int min, long unsigned int max, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/maple_tree.c (ffffffff820adbd0)
Location: lib/maple_tree.c:5123
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
  - kernel/irq/irqdesc.c:__irq_alloc_descs
  - mm/mmap.c:vm_unmapped_area
  - lib/maple_tree.c:mtree_alloc_range
```
**Symbols:**

```
ffffffff820adbd0-ffffffff820ae2cb: mas_empty_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int mas_empty_area(struct ma_state *mas, long unsigned int min, long unsigned int max, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/maple_tree.c (ffffffff82188e20)
Location: lib/maple_tree.c:4996
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:__irq_alloc_descs
  - kernel/irq/irqdesc.c:__irq_alloc_descs
  - mm/mmap.c:vm_unmapped_area
  - lib/maple_tree.c:mtree_alloc_range
```
**Symbols:**

```
ffffffff82188e20-ffffffff821894c8: mas_empty_area (STB_GLOBAL)
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
