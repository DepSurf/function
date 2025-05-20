# Function: <code>anon_vma_trylock_read</code>

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
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff8135ba2b)
Location: include/linux/rmap.h:134
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_anon
```
```
In mm/ksm.c (ffffffff813a3521)
Location: include/linux/rmap.h:134
Inline: True
Inline callers:
  - mm/ksm.c:rmap_walk_ksm
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff813d66da)
Location: include/linux/rmap.h:134
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_anon
```
```
In mm/ksm.c (ffffffff81423281)
Location: include/linux/rmap.h:134
Inline: True
Inline callers:
  - mm/ksm.c:rmap_walk_ksm
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff8140b65d)
Location: include/linux/rmap.h:134
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_anon
```
```
In mm/ksm.c (ffffffff81458310)
Location: include/linux/rmap.h:134
Inline: True
Inline callers:
  - mm/ksm.c:rmap_walk_ksm
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff81437f56)
Location: include/linux/rmap.h:139
Inline: True
Inline callers:
  - mm/rmap.c:rmap_walk_anon
```
```
In mm/ksm.c (ffffffff81492a80)
Location: include/linux/rmap.h:139
Inline: True
Inline callers:
  - mm/ksm.c:rmap_walk_ksm
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
