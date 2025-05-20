# Function: <code>__folio_clear_slab</code>

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
In mm/slub.c (ffffffff813a8075)
Location: include/linux/page-flags.h:506
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
```
```
In mm/kfence/core.c (ffffffff8349276a)
Location: include/linux/page-flags.h:506
Inline: True
Inline callers:
  - mm/kfence/core.c:kfence_init
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
In mm/slub.c (ffffffff814256e1)
Location: include/linux/page-flags.h:485
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
```
```
In mm/kfence/core.c (ffffffff83ec6403)
Location: include/linux/page-flags.h:485
Inline: True
Inline callers:
  - mm/kfence/core.c:kfence_init
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
In mm/slub.c (ffffffff8145a97b)
Location: include/linux/page-flags.h:479
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
```
```
In mm/kfence/core.c (ffffffff81464782)
Location: include/linux/page-flags.h:479
Inline: True
Inline callers:
  - mm/kfence/core.c:kfence_init_pool
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
In mm/slub.c (ffffffff81459714)
Location: include/linux/page-flags.h:481
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
```
```
In mm/kfence/core.c (ffffffff81493f32)
Location: include/linux/page-flags.h:481
Inline: True
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
