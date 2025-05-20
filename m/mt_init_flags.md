# Function: <code>mt_init_flags</code>

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
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810e5bc7)
Location: include/linux/maple_tree.h:574
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
```
```
In mm/mmap.c (ffffffff813c952d)
Location: include/linux/maple_tree.h:574
Inline: True
Inline callers:
  - mm/mmap.c:do_mas_align_munmap
```
```
In lib/maple_tree.c (ffffffff82027cb9)
Location: include/linux/maple_tree.h:574
Inline: True
Inline callers:
  - lib/maple_tree.c:mt_destroy_walk
  - lib/maple_tree.c:mt_free_walk
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
In kernel/fork.c (ffffffff810f130a)
Location: include/linux/maple_tree.h:583
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
```
```
In mm/mmap.c (ffffffff813fd941)
Location: include/linux/maple_tree.h:583
Inline: True
Inline callers:
  - mm/mmap.c:do_vmi_align_munmap
```
```
In drivers/base/regmap/regcache-maple.c (ffffffff81b726f0)
Location: include/linux/maple_tree.h:583
Inline: True
Inline callers:
  - drivers/base/regmap/regcache-maple.c:regcache_maple_init
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
In kernel/fork.c (ffffffff810fa6da)
Location: include/linux/maple_tree.h:765
Inline: True
Inline callers:
  - kernel/fork.c:mm_init
```
```
In mm/mmap.c (ffffffff81427add)
Location: include/linux/maple_tree.h:765
Inline: True
Inline callers:
  - mm/mmap.c:do_vmi_align_munmap
```
```
In drivers/base/regmap/regcache-maple.c (ffffffff81bc5eff)
Location: include/linux/maple_tree.h:765
Inline: True
Inline callers:
  - drivers/base/regmap/regcache-maple.c:regcache_maple_init
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
