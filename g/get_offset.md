# Function: <code>get_offset</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/module.c (ffffffff81107ac0)
Location: kernel/module.c:2194
Inline: True
Direct callers:
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
```
**Symbols:**

```
ffffffff81107ac0-ffffffff81107b0a: get_offset.isra.58 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/module.c (ffffffff8110ee60)
Location: kernel/module.c:2305
Inline: True
Direct callers:
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
```
**Symbols:**

```
ffffffff8110ee60-ffffffff8110eeac: get_offset.isra.62 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/module.c (ffffffff81116780)
Location: kernel/module.c:2317
Inline: True
Direct callers:
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
```
**Symbols:**

```
ffffffff81116780-ffffffff811167cc: get_offset.isra.63 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/module.c (ffffffff81117ce0)
Location: kernel/module.c:2344
Inline: True
Direct callers:
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
```
**Symbols:**

```
ffffffff81117ce0-ffffffff81117d2c: get_offset.isra.59 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/module.c (ffffffff811232c0)
Location: kernel/module.c:2352
Inline: True
Direct callers:
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
```
**Symbols:**

```
ffffffff811232c0-ffffffff8112330c: get_offset.isra.60 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/module.c (ffffffff811317b0)
Location: kernel/module.c:2347
Inline: True
Direct callers:
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
```
**Symbols:**

```
ffffffff811317b0-ffffffff811317f3: get_offset.isra.66 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Collision, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/module.c (ffffffff8113d060)
Location: kernel/module.c:2348
Inline: True
Direct callers:
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
```
```
In lib/xarray.c (ffffffff81a17e70)
Location: lib/xarray.c:136
Inline: True
Inline callers:
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:__xas_next
  - lib/xarray.c:__xas_next
  - lib/xarray.c:__xas_prev
  - lib/xarray.c:__xas_prev
  - lib/xarray.c:xas_create_range
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_load
```
**Symbols:**

```
ffffffff8113d060-ffffffff8113d0a3: get_offset.isra.68 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Collision, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/module.c (ffffffff811487c0)
Location: kernel/module.c:2348
Inline: True
Direct callers:
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
```
```
In lib/xarray.c (ffffffff81a87a39)
Location: lib/xarray.c:141
Inline: True
Inline callers:
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:__xas_next
  - lib/xarray.c:__xas_next
  - lib/xarray.c:__xas_prev
  - lib/xarray.c:__xas_prev
  - lib/xarray.c:xas_create_range
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_load
```
**Symbols:**

```
ffffffff811487c0-ffffffff81148803: get_offset.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Collision, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/module.c (ffffffff81154640)
Location: kernel/module.c:2405
Inline: True
Direct callers:
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
```
```
In lib/xarray.c (ffffffff81abecd9)
Location: lib/xarray.c:142
Inline: True
Inline callers:
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:__xas_next
  - lib/xarray.c:__xas_next
  - lib/xarray.c:__xas_prev
  - lib/xarray.c:__xas_prev
  - lib/xarray.c:xas_create_range
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_load
```
**Symbols:**

```
ffffffff81154640-ffffffff81154683: get_offset.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81165ea3)
Location: kernel/module.c:2399
Inline: True
Inline callers:
  - kernel/module.c:layout_symtab
  - kernel/module.c:layout_symtab
  - kernel/module.c:layout_sections
  - kernel/module.c:layout_sections
```
```
In lib/xarray.c (ffffffff815fb240)
Location: lib/xarray.c:142
Inline: True
Inline callers:
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:__xas_next
  - lib/xarray.c:__xas_next
  - lib/xarray.c:__xas_prev
  - lib/xarray.c:__xas_prev
  - lib/xarray.c:xas_create_range
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_load
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff811625d3)
Location: kernel/module.c:2482
Inline: True
Inline callers:
  - kernel/module.c:layout_symtab
  - kernel/module.c:layout_symtab
  - kernel/module.c:layout_sections
  - kernel/module.c:layout_sections
```
```
In lib/xarray.c (ffffffff8161fda9)
Location: lib/xarray.c:142
Inline: True
Inline callers:
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:__xas_next
  - lib/xarray.c:__xas_next
  - lib/xarray.c:__xas_prev
  - lib/xarray.c:__xas_prev
  - lib/xarray.c:xas_create_range
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_load
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81163092)
Location: kernel/module.c:2397
Inline: True
Inline callers:
  - kernel/module.c:layout_symtab
  - kernel/module.c:layout_symtab
  - kernel/module.c:layout_sections
  - kernel/module.c:layout_sections
```
```
In lib/xarray.c (ffffffff81603529)
Location: lib/xarray.c:142
Inline: True
Inline callers:
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:__xas_next
  - lib/xarray.c:__xas_next
  - lib/xarray.c:__xas_prev
  - lib/xarray.c:__xas_prev
  - lib/xarray.c:xas_create_range
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_load
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff811885d2)
Location: kernel/module.c:2399
Inline: True
Inline callers:
  - kernel/module.c:layout_symtab
  - kernel/module.c:layout_symtab
  - kernel/module.c:layout_sections
  - kernel/module.c:layout_sections
```
```
In lib/xarray.c (ffffffff81671ed5)
Location: lib/xarray.c:142
Inline: True
Inline callers:
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:__xas_next
  - lib/xarray.c:__xas_next
  - lib/xarray.c:__xas_prev
  - lib/xarray.c:__xas_prev
  - lib/xarray.c:xas_create_range
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_load
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
In lib/xarray.c (ffffffff8178c68c)
Location: lib/xarray.c:142
Inline: True
Inline callers:
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:__xas_next
  - lib/xarray.c:__xas_next
  - lib/xarray.c:__xas_prev
  - lib/xarray.c:__xas_prev
  - lib/xarray.c:xas_create_range
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
In lib/xarray.c (ffffffff82049d2c)
Location: lib/xarray.c:142
Inline: True
Inline callers:
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:__xas_next
  - lib/xarray.c:__xas_next
  - lib/xarray.c:__xas_prev
  - lib/xarray.c:__xas_prev
  - lib/xarray.c:xas_create_range
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
In lib/xarray.c (ffffffff820c612c)
Location: lib/xarray.c:144
Inline: True
Inline callers:
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:__xas_next
  - lib/xarray.c:__xas_next
  - lib/xarray.c:__xas_prev
  - lib/xarray.c:__xas_prev
  - lib/xarray.c:xas_create_range
  - lib/xarray.c:xas_descend
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
In lib/xarray.c (ffffffff821a0aac)
Location: lib/xarray.c:144
Inline: True
Inline callers:
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:__xas_next
  - lib/xarray.c:__xas_next
  - lib/xarray.c:__xas_prev
  - lib/xarray.c:__xas_prev
  - lib/xarray.c:xas_create_range
  - lib/xarray.c:xas_descend
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Collision, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/module.c (ffff8000101c3810)
Location: kernel/module.c:2405
Inline: True
Direct callers:
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
```
```
In lib/xarray.c (ffff800010d99cdc)
Location: lib/xarray.c:142
Inline: True
Inline callers:
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:__xas_next
  - lib/xarray.c:__xas_next
  - lib/xarray.c:__xas_prev
  - lib/xarray.c:__xas_prev
  - lib/xarray.c:xas_create_range
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_load
```
**Symbols:**

```
ffff8000101c3810-ffff8000101c3894: get_offset.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Collision, Selective Inline ⚠️</summary>

```c
long int get_offset(struct module *mod, unsigned int *size, Elf32_Shdr *sechdr, unsigned int section);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/module.c (c040aa0c)
Location: kernel/module.c:2405
Inline: False
Direct callers:
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
```
```
In lib/xarray.c (c0e96850)
Location: lib/xarray.c:142
Inline: True
Inline callers:
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:__xas_next
  - lib/xarray.c:__xas_next
  - lib/xarray.c:__xas_prev
  - lib/xarray.c:__xas_prev
  - lib/xarray.c:xas_create_range
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_load
```
**Symbols:**

```
c040aa0c-c040aa64: get_offset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Collision, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/module.c (c000000000229f30)
Location: kernel/module.c:2405
Inline: True
Direct callers:
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
```
```
In lib/xarray.c (c000000000edfd54)
Location: lib/xarray.c:142
Inline: True
Inline callers:
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:__xas_next
  - lib/xarray.c:__xas_next
  - lib/xarray.c:__xas_prev
  - lib/xarray.c:__xas_prev
  - lib/xarray.c:xas_create_range
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_load
```
**Symbols:**

```
c000000000229f30-c000000000229fc8: get_offset.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Collision, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/module.c (ffffffe00014469e)
Location: kernel/module.c:2405
Inline: True
Direct callers:
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
```
```
In lib/xarray.c (ffffffe0008c28ea)
Location: lib/xarray.c:142
Inline: True
Inline callers:
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:__xas_next
  - lib/xarray.c:__xas_next
  - lib/xarray.c:__xas_prev
  - lib/xarray.c:__xas_prev
  - lib/xarray.c:xas_create_range
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_load
```
**Symbols:**

```
ffffffe00014469e-ffffffe00014470c: get_offset.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Collision, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/module.c (ffffffff8114cc60)
Location: kernel/module.c:2405
Inline: True
Direct callers:
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
```
```
In lib/xarray.c (ffffffff81a5db29)
Location: lib/xarray.c:142
Inline: True
Inline callers:
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:__xas_next
  - lib/xarray.c:__xas_next
  - lib/xarray.c:__xas_prev
  - lib/xarray.c:__xas_prev
  - lib/xarray.c:xas_create_range
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_load
```
**Symbols:**

```
ffffffff8114cc60-ffffffff8114cca3: get_offset.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Collision, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/module.c (ffffffff8113ff10)
Location: kernel/module.c:2405
Inline: True
Direct callers:
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
```
```
In lib/xarray.c (ffffffff81a1abf9)
Location: lib/xarray.c:142
Inline: True
Inline callers:
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:__xas_next
  - lib/xarray.c:__xas_next
  - lib/xarray.c:__xas_prev
  - lib/xarray.c:__xas_prev
  - lib/xarray.c:xas_create_range
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_load
```
**Symbols:**

```
ffffffff8113ff10-ffffffff8113ff53: get_offset.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Collision, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/module.c (ffffffff8114ab10)
Location: kernel/module.c:2405
Inline: True
Direct callers:
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
```
```
In lib/xarray.c (ffffffff81ac9f19)
Location: lib/xarray.c:142
Inline: True
Inline callers:
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:__xas_next
  - lib/xarray.c:__xas_next
  - lib/xarray.c:__xas_prev
  - lib/xarray.c:__xas_prev
  - lib/xarray.c:xas_create_range
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_load
```
**Symbols:**

```
ffffffff8114ab10-ffffffff8114ab53: get_offset.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Collision, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/module.c (ffffffff81157800)
Location: kernel/module.c:2405
Inline: True
Direct callers:
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:layout_and_allocate
```
```
In lib/xarray.c (ffffffff81ad649d)
Location: lib/xarray.c:142
Inline: True
Inline callers:
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_find_marked
  - lib/xarray.c:__xas_next
  - lib/xarray.c:__xas_next
  - lib/xarray.c:__xas_prev
  - lib/xarray.c:__xas_prev
  - lib/xarray.c:xas_create_range
  - lib/xarray.c:xas_create
  - lib/xarray.c:xas_load
```
**Symbols:**

```
ffffffff81157800-ffffffff81157843: get_offset.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
