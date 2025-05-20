# Function: <code>set_dax_synchronous</code>

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
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff8173f032)
Location: include/linux/dax.h:55
Inline: True
Inline callers:
  - drivers/dax/super.c:alloc_dax
```
```
In drivers/md/dm-table.c (ffffffff8187c16e)
Location: include/linux/dax.h:55
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_set_restrictions
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
In drivers/dax/super.c (ffffffff81763212)
Location: include/linux/dax.h:55
Inline: True
Inline callers:
  - drivers/dax/super.c:alloc_dax
```
```
In drivers/md/dm-table.c (ffffffff818adf4e)
Location: include/linux/dax.h:55
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_set_restrictions
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff8182307b)
Location: include/linux/dax.h:57
Inline: True
Inline callers:
  - drivers/dax/super.c:alloc_dax
```
```
In drivers/md/dm-table.c (ffffffff8197e1aa)
Location: include/linux/dax.h:57
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_set_restrictions
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff81831dbb)
Location: include/linux/dax.h:57
Inline: True
Inline callers:
  - drivers/dax/super.c:alloc_dax
```
```
In drivers/md/dm-table.c (ffffffff819826c2)
Location: include/linux/dax.h:57
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_set_restrictions
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff81814feb)
Location: include/linux/dax.h:57
Inline: True
Inline callers:
  - drivers/dax/super.c:alloc_dax
```
```
In drivers/md/dm-table.c (ffffffff81966ad1)
Location: include/linux/dax.h:57
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_set_restrictions
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff8189f75b)
Location: include/linux/dax.h:56
Inline: True
Inline callers:
  - drivers/dax/super.c:alloc_dax
```
```
In drivers/md/dm-table.c (ffffffff81a0ecea)
Location: include/linux/dax.h:56
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_set_restrictions
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void set_dax_synchronous(struct dax_device *dax_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff819e8dd0)
Location: drivers/dax/super.c:244
Inline: False
Direct callers:
  - drivers/dax/bus.c:devm_create_dev_dax
  - drivers/md/dm-table.c:dm_table_set_restrictions
```
**Symbols:**

```
ffffffff819e8dd0-ffffffff819e8de9: set_dax_synchronous (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void set_dax_synchronous(struct dax_device *dax_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff81b65170)
Location: drivers/dax/super.c:289
Inline: False
Direct callers:
  - drivers/dax/bus.c:devm_create_dev_dax
  - drivers/md/dm-table.c:dm_table_set_restrictions
```
**Symbols:**

```
ffffffff81b65170-ffffffff81b65189: set_dax_synchronous (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void set_dax_synchronous(struct dax_device *dax_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff81bb8770)
Location: drivers/dax/super.c:292
Inline: False
Direct callers:
  - drivers/dax/bus.c:devm_create_dev_dax
  - drivers/md/dm-table.c:dm_table_set_restrictions
```
**Symbols:**

```
ffffffff81bb8770-ffffffff81bb8789: set_dax_synchronous (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void set_dax_synchronous(struct dax_device *dax_dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff81c0cdd0)
Location: drivers/dax/super.c:292
Inline: False
Direct callers:
  - drivers/dax/bus.c:devm_create_dev_dax
  - drivers/md/dm-table.c:dm_table_set_restrictions
```
**Symbols:**

```
ffffffff81c0cdd0-ffffffff81c0cde9: set_dax_synchronous (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffff800010963ad0)
Location: include/linux/dax.h:55
Inline: True
Inline callers:
  - drivers/dax/super.c:alloc_dax
```
```
In drivers/md/dm-table.c (ffff800010b04a0c)
Location: include/linux/dax.h:55
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_set_restrictions
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (c0a39c90)
Location: include/linux/dax.h:55
Inline: True
Inline callers:
  - drivers/dax/super.c:alloc_dax
```
```
In drivers/md/dm-table.c (c0be3a04)
Location: include/linux/dax.h:55
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_set_restrictions
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (c000000000a18ed0)
Location: include/linux/dax.h:55
Inline: True
Inline callers:
  - drivers/dax/super.c:alloc_dax
```
```
In drivers/md/dm-table.c (c000000000bf4580)
Location: include/linux/dax.h:55
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_set_restrictions
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffe0005d05b8)
Location: include/linux/dax.h:55
Inline: True
Inline callers:
  - drivers/dax/super.c:alloc_dax
```
```
In drivers/md/dm-table.c (ffffffe0006f3b9a)
Location: include/linux/dax.h:55
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_set_restrictions
```
</details>
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
In drivers/dax/super.c (ffffffff81717902)
Location: include/linux/dax.h:55
Inline: True
Inline callers:
  - drivers/dax/super.c:alloc_dax
```
```
In drivers/md/dm-table.c (ffffffff81853dce)
Location: include/linux/dax.h:55
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_set_restrictions
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
In drivers/dax/super.c (ffffffff816efe32)
Location: include/linux/dax.h:55
Inline: True
Inline callers:
  - drivers/dax/super.c:alloc_dax
```
```
In drivers/md/dm-table.c (ffffffff8181b3de)
Location: include/linux/dax.h:55
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_set_restrictions
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
In drivers/dax/super.c (ffffffff817566d2)
Location: include/linux/dax.h:55
Inline: True
Inline callers:
  - drivers/dax/super.c:alloc_dax
```
```
In drivers/md/dm-table.c (ffffffff818a33fe)
Location: include/linux/dax.h:55
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_set_restrictions
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
In drivers/dax/super.c (ffffffff81771929)
Location: include/linux/dax.h:55
Inline: True
Inline callers:
  - drivers/dax/super.c:alloc_dax
```
```
In drivers/md/dm-table.c (ffffffff818bf63e)
Location: include/linux/dax.h:55
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_set_restrictions
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
