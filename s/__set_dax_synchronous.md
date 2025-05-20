# Function: <code>__set_dax_synchronous</code>

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
void __set_dax_synchronous(struct dax_device *dax_dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff8173f032)
Location: drivers/dax/super.c:384
Inline: True
Inline callers:
  - drivers/dax/super.c:alloc_dax
Direct callers:
  - drivers/md/dm-table.c:dm_table_set_restrictions
```
**Symbols:**

```
ffffffff8173eb50-ffffffff8173eb63: __set_dax_synchronous (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void __set_dax_synchronous(struct dax_device *dax_dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff81763212)
Location: drivers/dax/super.c:384
Inline: True
Inline callers:
  - drivers/dax/super.c:alloc_dax
Direct callers:
  - drivers/md/dm-table.c:dm_table_set_restrictions
```
**Symbols:**

```
ffffffff81762d30-ffffffff81762d43: __set_dax_synchronous (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void __set_dax_synchronous(struct dax_device *dax_dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff8182307b)
Location: drivers/dax/super.c:405
Inline: True
Inline callers:
  - drivers/dax/super.c:alloc_dax
Direct callers:
  - drivers/md/dm-table.c:dm_table_set_restrictions
```
**Symbols:**

```
ffffffff81822e70-ffffffff81822e83: __set_dax_synchronous (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void __set_dax_synchronous(struct dax_device *dax_dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff81831dbb)
Location: drivers/dax/super.c:413
Inline: True
Inline callers:
  - drivers/dax/super.c:alloc_dax
Direct callers:
  - drivers/md/dm-table.c:dm_table_set_restrictions
```
**Symbols:**

```
ffffffff81831bb0-ffffffff81831bc3: __set_dax_synchronous (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void __set_dax_synchronous(struct dax_device *dax_dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff81814feb)
Location: drivers/dax/super.c:413
Inline: True
Inline callers:
  - drivers/dax/super.c:alloc_dax
Direct callers:
  - drivers/md/dm-table.c:dm_table_set_restrictions
```
**Symbols:**

```
ffffffff81814de0-ffffffff81814df3: __set_dax_synchronous (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void __set_dax_synchronous(struct dax_device *dax_dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff8189f75b)
Location: drivers/dax/super.c:405
Inline: True
Inline callers:
  - drivers/dax/super.c:alloc_dax
Direct callers:
  - drivers/md/dm-table.c:dm_table_set_restrictions
```
**Symbols:**

```
ffffffff8189f530-ffffffff8189f543: __set_dax_synchronous (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void __set_dax_synchronous(struct dax_device *dax_dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffff800010963ad0)
Location: drivers/dax/super.c:384
Inline: True
Inline callers:
  - drivers/dax/super.c:alloc_dax
Direct callers:
  - drivers/md/dm-table.c:dm_table_set_restrictions
```
**Symbols:**

```
ffff8000109636b0-ffff8000109636fc: __set_dax_synchronous (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void __set_dax_synchronous(struct dax_device *dax_dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (c0a39c90)
Location: drivers/dax/super.c:384
Inline: True
Inline callers:
  - drivers/dax/super.c:alloc_dax
Direct callers:
  - drivers/md/dm-table.c:dm_table_set_restrictions
```
**Symbols:**

```
c0a39a28-c0a39a50: __set_dax_synchronous (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void __set_dax_synchronous(struct dax_device *dax_dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (c000000000a18ed0)
Location: drivers/dax/super.c:384
Inline: True
Inline callers:
  - drivers/dax/super.c:alloc_dax
Direct callers:
  - drivers/md/dm-table.c:dm_table_set_restrictions
```
**Symbols:**

```
c000000000a18af0-c000000000a18b14: __set_dax_synchronous (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void __set_dax_synchronous(struct dax_device *dax_dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffe0005d05b8)
Location: drivers/dax/super.c:384
Inline: True
Inline callers:
  - drivers/dax/super.c:alloc_dax
Direct callers:
  - drivers/md/dm-table.c:dm_table_set_restrictions
```
**Symbols:**

```
ffffffe0005d0072-ffffffe0005d009c: __set_dax_synchronous (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void __set_dax_synchronous(struct dax_device *dax_dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff81717902)
Location: drivers/dax/super.c:384
Inline: True
Inline callers:
  - drivers/dax/super.c:alloc_dax
Direct callers:
  - drivers/md/dm-table.c:dm_table_set_restrictions
```
**Symbols:**

```
ffffffff81717420-ffffffff81717433: __set_dax_synchronous (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void __set_dax_synchronous(struct dax_device *dax_dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff816efe32)
Location: drivers/dax/super.c:384
Inline: True
Inline callers:
  - drivers/dax/super.c:alloc_dax
Direct callers:
  - drivers/md/dm-table.c:dm_table_set_restrictions
```
**Symbols:**

```
ffffffff816ef950-ffffffff816ef963: __set_dax_synchronous (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void __set_dax_synchronous(struct dax_device *dax_dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff817566d2)
Location: drivers/dax/super.c:384
Inline: True
Inline callers:
  - drivers/dax/super.c:alloc_dax
Direct callers:
  - drivers/md/dm-table.c:dm_table_set_restrictions
```
**Symbols:**

```
ffffffff817561f0-ffffffff81756203: __set_dax_synchronous (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void __set_dax_synchronous(struct dax_device *dax_dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff81771929)
Location: drivers/dax/super.c:384
Inline: True
Inline callers:
  - drivers/dax/super.c:alloc_dax
Direct callers:
  - drivers/md/dm-table.c:dm_table_set_restrictions
```
**Symbols:**

```
ffffffff81771660-ffffffff81771673: __set_dax_synchronous (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
