# Function: <code>mas_store_gfp</code>

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
int mas_store_gfp(struct ma_state *mas, void *entry, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/maple_tree.c (ffffffff82037bb0)
Location: lib/maple_tree.c:5676
Inline: False
Direct callers:
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:do_mas_align_munmap
  - mm/mmap.c:do_mas_align_munmap
```
**Symbols:**

```
ffffffff82037bb0-ffffffff82037cb6: mas_store_gfp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int mas_store_gfp(struct ma_state *mas, void *entry, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/maple_tree.c (ffffffff820b6c20)
Location: lib/maple_tree.c:5507
Inline: False
Direct callers:
  - kernel/irq/irqdesc.c:early_irq_init
  - kernel/irq/irqdesc.c:alloc_descs
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:do_vmi_align_munmap
  - mm/mmap.c:do_vmi_align_munmap
  - drivers/base/regmap/regcache-maple.c:regcache_maple_insert_block
  - drivers/base/regmap/regcache-maple.c:regcache_maple_drop
  - drivers/base/regmap/regcache-maple.c:regcache_maple_drop
  - drivers/base/regmap/regcache-maple.c:regcache_maple_drop
  - drivers/base/regmap/regcache-maple.c:regcache_maple_write
```
**Symbols:**

```
ffffffff820b6c20-ffffffff820b6d26: mas_store_gfp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int mas_store_gfp(struct ma_state *mas, void *entry, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/maple_tree.c (ffffffff821900d0)
Location: lib/maple_tree.c:5407
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
  - kernel/irq/irqdesc.c:early_irq_init
  - kernel/irq/irqdesc.c:alloc_descs
  - mm/mmap.c:do_brk_flags
  - mm/mmap.c:do_vmi_align_munmap
  - mm/mmap.c:do_vmi_align_munmap
  - drivers/base/regmap/regcache-maple.c:regcache_maple_insert_block
  - drivers/base/regmap/regcache-maple.c:regcache_maple_drop
  - drivers/base/regmap/regcache-maple.c:regcache_maple_drop
  - drivers/base/regmap/regcache-maple.c:regcache_maple_write
```
**Symbols:**

```
ffffffff821900d0-ffffffff821901e6: mas_store_gfp (STB_GLOBAL)
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
