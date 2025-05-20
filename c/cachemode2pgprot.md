# Function: <code>cachemode2pgprot</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81f7790e)
Location: arch/x86/include/asm/pgtable_types.h:351
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:__init_extra_mapping
```
```
In arch/x86/mm/pageattr.c (ffffffff8106e84f)
Location: arch/x86/include/asm/pgtable_types.h:351
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:_set_memory_array
  - arch/x86/mm/pageattr.c:_set_pages_array
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81fa0043)
Location: arch/x86/include/asm/pgtable_types.h:389
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:__init_extra_mapping
```
```
In arch/x86/mm/pageattr.c (ffffffff8106e956)
Location: arch/x86/include/asm/pgtable_types.h:389
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:_set_pages_array
  - arch/x86/mm/pageattr.c:_set_pages_array
  - arch/x86/mm/pageattr.c:_set_memory_wt
  - arch/x86/mm/pageattr.c:_set_memory_wc
  - arch/x86/mm/pageattr.c:_set_memory_wc
  - arch/x86/mm/pageattr.c:_set_memory_array
  - arch/x86/mm/pageattr.c:_set_memory_array
  - arch/x86/mm/pageattr.c:_set_memory_uc
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81fdb5ad)
Location: arch/x86/include/asm/pgtable_types.h:389
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:__init_extra_mapping
```
```
In arch/x86/mm/pageattr.c (ffffffff810725f5)
Location: arch/x86/include/asm/pgtable_types.h:389
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:_set_pages_array
  - arch/x86/mm/pageattr.c:_set_pages_array
  - arch/x86/mm/pageattr.c:_set_memory_wt
  - arch/x86/mm/pageattr.c:_set_memory_wc
  - arch/x86/mm/pageattr.c:_set_memory_wc
  - arch/x86/mm/pageattr.c:_set_memory_array
  - arch/x86/mm/pageattr.c:_set_memory_array
  - arch/x86/mm/pageattr.c:_set_memory_uc
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff820bc5cb)
Location: arch/x86/include/asm/pgtable_types.h:426
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:__init_extra_mapping
```
```
In arch/x86/mm/pageattr.c (ffffffff81071bd1)
Location: arch/x86/include/asm/pgtable_types.h:426
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:_set_pages_array
  - arch/x86/mm/pageattr.c:_set_pages_array
  - arch/x86/mm/pageattr.c:_set_memory_wt
  - arch/x86/mm/pageattr.c:_set_memory_wc
  - arch/x86/mm/pageattr.c:_set_memory_wc
  - arch/x86/mm/pageattr.c:_set_memory_array
  - arch/x86/mm/pageattr.c:_set_memory_array
  - arch/x86/mm/pageattr.c:_set_memory_uc
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff826c3005)
Location: arch/x86/include/asm/pgtable_types.h:451
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:__init_extra_mapping
```
```
In arch/x86/mm/pageattr.c (ffffffff81077271)
Location: arch/x86/include/asm/pgtable_types.h:451
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:_set_pages_array
  - arch/x86/mm/pageattr.c:_set_pages_array
  - arch/x86/mm/pageattr.c:_set_memory_wt
  - arch/x86/mm/pageattr.c:_set_memory_wc
  - arch/x86/mm/pageattr.c:_set_memory_wc
  - arch/x86/mm/pageattr.c:_set_memory_array
  - arch/x86/mm/pageattr.c:_set_memory_array
  - arch/x86/mm/pageattr.c:_set_memory_uc
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff826ed271)
Location: arch/x86/include/asm/pgtable_types.h:450
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:__init_extra_mapping
```
```
In arch/x86/mm/pageattr.c (ffffffff81079cda)
Location: arch/x86/include/asm/pgtable_types.h:450
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:_set_pages_array
  - arch/x86/mm/pageattr.c:_set_pages_array
  - arch/x86/mm/pageattr.c:_set_memory_wt
  - arch/x86/mm/pageattr.c:_set_memory_wc
  - arch/x86/mm/pageattr.c:_set_memory_wc
  - arch/x86/mm/pageattr.c:_set_memory_array
  - arch/x86/mm/pageattr.c:_set_memory_array
  - arch/x86/mm/pageattr.c:_set_memory_uc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff828a3e03)
Location: arch/x86/include/asm/pgtable_types.h:474
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:__init_extra_mapping
```
```
In arch/x86/mm/pageattr.c (ffffffff810804ea)
Location: arch/x86/include/asm/pgtable_types.h:474
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:_set_pages_array
  - arch/x86/mm/pageattr.c:_set_pages_array
  - arch/x86/mm/pageattr.c:_set_memory_wt
  - arch/x86/mm/pageattr.c:_set_memory_wc
  - arch/x86/mm/pageattr.c:_set_memory_wc
  - arch/x86/mm/pageattr.c:_set_memory_array
  - arch/x86/mm/pageattr.c:_set_memory_array
  - arch/x86/mm/pageattr.c:_set_memory_uc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff828bc2aa)
Location: arch/x86/include/asm/pgtable_types.h:473
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:__init_extra_mapping
```
```
In arch/x86/mm/pageattr.c (ffffffff81083faa)
Location: arch/x86/include/asm/pgtable_types.h:473
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:_set_pages_array
  - arch/x86/mm/pageattr.c:_set_pages_array
  - arch/x86/mm/pageattr.c:_set_memory_wt
  - arch/x86/mm/pageattr.c:_set_memory_wc
  - arch/x86/mm/pageattr.c:_set_memory_wc
  - arch/x86/mm/pageattr.c:_set_memory_array
  - arch/x86/mm/pageattr.c:_set_memory_array
  - arch/x86/mm/pageattr.c:_set_memory_uc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff828c2751)
Location: arch/x86/include/asm/pgtable_types.h:473
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:__init_extra_mapping
```
```
In arch/x86/mm/pageattr.c (ffffffff81084cea)
Location: arch/x86/include/asm/pgtable_types.h:473
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:_set_pages_array
  - arch/x86/mm/pageattr.c:_set_pages_array
  - arch/x86/mm/pageattr.c:_set_memory_wt
  - arch/x86/mm/pageattr.c:_set_memory_wc
  - arch/x86/mm/pageattr.c:_set_memory_wc
  - arch/x86/mm/pageattr.c:_set_memory_uc
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
In arch/x86/mm/pat/set_memory.c (ffffffff8108e8b1)
Location: arch/x86/mm/pat/set_memory.c:72
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:_set_pages_array
  - arch/x86/mm/pat/set_memory.c:_set_pages_array
  - arch/x86/mm/pat/set_memory.c:_set_memory_wt
  - arch/x86/mm/pat/set_memory.c:_set_memory_wc
  - arch/x86/mm/pat/set_memory.c:_set_memory_wc
  - arch/x86/mm/pat/set_memory.c:set_memory_uc
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
In arch/x86/mm/pat/set_memory.c (ffffffff8108e681)
Location: arch/x86/mm/pat/set_memory.c:72
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:_set_pages_array
  - arch/x86/mm/pat/set_memory.c:_set_pages_array
  - arch/x86/mm/pat/set_memory.c:_set_memory_wt
  - arch/x86/mm/pat/set_memory.c:_set_memory_wc
  - arch/x86/mm/pat/set_memory.c:_set_memory_wc
  - arch/x86/mm/pat/set_memory.c:set_memory_uc
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
In arch/x86/mm/pat/set_memory.c (ffffffff8108f231)
Location: arch/x86/mm/pat/set_memory.c:74
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:_set_pages_array
  - arch/x86/mm/pat/set_memory.c:_set_pages_array
  - arch/x86/mm/pat/set_memory.c:_set_memory_wt
  - arch/x86/mm/pat/set_memory.c:_set_memory_wc
  - arch/x86/mm/pat/set_memory.c:_set_memory_wc
  - arch/x86/mm/pat/set_memory.c:set_memory_uc
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
In arch/x86/mm/pat/set_memory.c (ffffffff8109ece1)
Location: arch/x86/mm/pat/set_memory.c:74
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:_set_pages_array
  - arch/x86/mm/pat/set_memory.c:_set_pages_array
  - arch/x86/mm/pat/set_memory.c:_set_memory_wt
  - arch/x86/mm/pat/set_memory.c:_set_memory_wc
  - arch/x86/mm/pat/set_memory.c:_set_memory_wc
  - arch/x86/mm/pat/set_memory.c:set_memory_uc
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
In arch/x86/mm/pat/set_memory.c (ffffffff810b271f)
Location: arch/x86/mm/pat/set_memory.c:77
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:_set_pages_array
  - arch/x86/mm/pat/set_memory.c:_set_pages_array
  - arch/x86/mm/pat/set_memory.c:_set_memory_wt
  - arch/x86/mm/pat/set_memory.c:_set_memory_wc
  - arch/x86/mm/pat/set_memory.c:_set_memory_wc
  - arch/x86/mm/pat/set_memory.c:set_memory_uc
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
In arch/x86/mm/pat/set_memory.c (ffffffff810cd05f)
Location: arch/x86/mm/pat/set_memory.c:78
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:_set_pages_array
  - arch/x86/mm/pat/set_memory.c:_set_pages_array
  - arch/x86/mm/pat/set_memory.c:_set_memory_wt
  - arch/x86/mm/pat/set_memory.c:_set_memory_wc
  - arch/x86/mm/pat/set_memory.c:_set_memory_wc
  - arch/x86/mm/pat/set_memory.c:set_memory_uc
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
In arch/x86/mm/pat/set_memory.c (ffffffff810d068f)
Location: arch/x86/mm/pat/set_memory.c:79
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:_set_pages_array
  - arch/x86/mm/pat/set_memory.c:_set_pages_array
  - arch/x86/mm/pat/set_memory.c:_set_memory_wt
  - arch/x86/mm/pat/set_memory.c:_set_memory_wc
  - arch/x86/mm/pat/set_memory.c:_set_memory_wc
  - arch/x86/mm/pat/set_memory.c:set_memory_uc
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
In arch/x86/mm/pat/set_memory.c (ffffffff810d8d6f)
Location: arch/x86/mm/pat/set_memory.c:79
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:_set_pages_array
  - arch/x86/mm/pat/set_memory.c:_set_pages_array
  - arch/x86/mm/pat/set_memory.c:_set_memory_wt
  - arch/x86/mm/pat/set_memory.c:_set_memory_wc
  - arch/x86/mm/pat/set_memory.c:_set_memory_wc
  - arch/x86/mm/pat/set_memory.c:set_memory_uc
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
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff828ad727)
Location: arch/x86/include/asm/pgtable_types.h:473
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:__init_extra_mapping
```
```
In arch/x86/mm/pageattr.c (ffffffff81083cea)
Location: arch/x86/include/asm/pgtable_types.h:473
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:_set_pages_array
  - arch/x86/mm/pageattr.c:_set_pages_array
  - arch/x86/mm/pageattr.c:_set_memory_wt
  - arch/x86/mm/pageattr.c:_set_memory_wc
  - arch/x86/mm/pageattr.c:_set_memory_wc
  - arch/x86/mm/pageattr.c:_set_memory_uc
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff828a59e8)
Location: arch/x86/include/asm/pgtable_types.h:473
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:__init_extra_mapping
```
```
In arch/x86/mm/pageattr.c (ffffffff8107293a)
Location: arch/x86/include/asm/pgtable_types.h:473
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:_set_pages_array
  - arch/x86/mm/pageattr.c:_set_pages_array
  - arch/x86/mm/pageattr.c:_set_memory_wt
  - arch/x86/mm/pageattr.c:_set_memory_wc
  - arch/x86/mm/pageattr.c:_set_memory_wc
  - arch/x86/mm/pageattr.c:_set_memory_uc
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff828c0626)
Location: arch/x86/include/asm/pgtable_types.h:473
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:__init_extra_mapping
```
```
In arch/x86/mm/pageattr.c (ffffffff81083c9a)
Location: arch/x86/include/asm/pgtable_types.h:473
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:_set_pages_array
  - arch/x86/mm/pageattr.c:_set_pages_array
  - arch/x86/mm/pageattr.c:_set_memory_wt
  - arch/x86/mm/pageattr.c:_set_memory_wc
  - arch/x86/mm/pageattr.c:_set_memory_wc
  - arch/x86/mm/pageattr.c:_set_memory_uc
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff828c3771)
Location: arch/x86/include/asm/pgtable_types.h:473
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:__init_extra_mapping
```
```
In arch/x86/mm/pageattr.c (ffffffff81085dda)
Location: arch/x86/include/asm/pgtable_types.h:473
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:_set_pages_array
  - arch/x86/mm/pageattr.c:_set_pages_array
  - arch/x86/mm/pageattr.c:_set_memory_wt
  - arch/x86/mm/pageattr.c:_set_memory_wc
  - arch/x86/mm/pageattr.c:_set_memory_wc
  - arch/x86/mm/pageattr.c:_set_memory_uc
```
</details>
</li>
</ul>

## Differences
