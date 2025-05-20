# Function: <code>dm_table_get_type</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
unsigned int dm_table_get_type(struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff816a61d0)
Location: drivers/md/dm-table.c:913
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_complete
Direct callers:
  - drivers/md/dm.c:dm_mq_queue_rq
  - drivers/md/dm.c:dm_swap_table
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-ioctl.c:table_load
```
**Symbols:**

```
ffffffff816a61d0-ffffffff816a61de: dm_table_get_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
unsigned int dm_table_get_type(struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff817067f1)
Location: drivers/md/dm-table.c:986
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_bio_based
Direct callers:
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-ioctl.c:table_load
```
**Symbols:**

```
ffffffff817062e0-ffffffff817062ee: dm_table_get_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
unsigned int dm_table_get_type(struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff81738679)
Location: drivers/md/dm-table.c:987
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_bio_based
Direct callers:
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-ioctl.c:table_load
```
**Symbols:**

```
ffffffff81738150-ffffffff8173815e: dm_table_get_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
enum dm_queue_mode dm_table_get_type(struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff81751ba2)
Location: drivers/md/dm-table.c:1027
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_bio_based
Direct callers:
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-ioctl.c:table_load
```
**Symbols:**

```
ffffffff817516b0-ffffffff817516be: dm_table_get_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
enum dm_queue_mode dm_table_get_type(struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff817c3db0)
Location: drivers/md/dm-table.c:1029
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_bio_based
Direct callers:
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-ioctl.c:table_load
```
**Symbols:**

```
ffffffff817c38a0-ffffffff817c38ae: dm_table_get_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
enum dm_queue_mode dm_table_get_type(struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff8180c6f9)
Location: drivers/md/dm-table.c:1064
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_bio_based
Direct callers:
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-ioctl.c:table_load
```
**Symbols:**

```
ffffffff8180c340-ffffffff8180c34e: dm_table_get_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
enum dm_queue_mode dm_table_get_type(struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff81838672)
Location: drivers/md/dm-table.c:1049
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_bio_based
Direct callers:
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-ioctl.c:table_load
```
**Symbols:**

```
ffffffff81838300-ffffffff8183830e: dm_table_get_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
enum dm_queue_mode dm_table_get_type(struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff8187b249)
Location: drivers/md/dm-table.c:1062
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_bio_based
Direct callers:
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-ioctl.c:dm_early_create
```
**Symbols:**

```
ffffffff8187aee0-ffffffff8187aeee: dm_table_get_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
enum dm_queue_mode dm_table_get_type(struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff818ad039)
Location: drivers/md/dm-table.c:1060
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_bio_based
Direct callers:
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-ioctl.c:dm_early_create
```
**Symbols:**

```
ffffffff818accd0-ffffffff818accde: dm_table_get_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
enum dm_queue_mode dm_table_get_type(struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff8197d5ac)
Location: drivers/md/dm-table.c:1036
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_bio_based
Direct callers:
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-ioctl.c:dm_early_create
```
**Symbols:**

```
ffffffff8197d3e0-ffffffff8197d3ee: dm_table_get_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
enum dm_queue_mode dm_table_get_type(struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff81981b2c)
Location: drivers/md/dm-table.c:981
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_bio_based
Direct callers:
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-ioctl.c:dm_early_create
```
**Symbols:**

```
ffffffff81981960-ffffffff8198196e: dm_table_get_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
enum dm_queue_mode dm_table_get_type(struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff81965dbe)
Location: drivers/md/dm-table.c:967
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_bio_based
Direct callers:
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-ioctl.c:dm_early_create
```
**Symbols:**

```
ffffffff81965ba0-ffffffff81965bae: dm_table_get_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
enum dm_queue_mode dm_table_get_type(struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff81a0dd6a)
Location: drivers/md/dm-table.c:962
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_bio_based
Direct callers:
  - drivers/md/dm.c:dm_setup_md_queue
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-ioctl.c:table_load
```
**Symbols:**

```
ffffffff81a0db30-ffffffff81a0db3e: dm_table_get_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
enum dm_queue_mode dm_table_get_type(struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff81b76469)
Location: drivers/md/dm-table.c:964
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_bio_based
Direct callers:
  - drivers/md/dm.c:dm_setup_md_queue
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-ioctl.c:table_load
```
**Symbols:**

```
ffffffff81b76240-ffffffff81b76254: dm_table_get_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
enum dm_queue_mode dm_table_get_type(struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff81d12565)
Location: drivers/md/dm-table.c:959
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_alloc_md_mempools
  - drivers/md/dm-table.c:dm_table_bio_based
Direct callers:
  - drivers/md/dm.c:dm_setup_md_queue
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-ioctl.c:table_load
```
**Symbols:**

```
ffffffff81d135f0-ffffffff81d13604: dm_table_get_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
enum dm_queue_mode dm_table_get_type(struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff81d7b925)
Location: drivers/md/dm-table.c:953
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_alloc_md_mempools
  - drivers/md/dm-table.c:dm_table_bio_based
Direct callers:
  - drivers/md/dm.c:dm_setup_md_queue
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-ioctl.c:table_load
```
**Symbols:**

```
ffffffff81d7c750-ffffffff81d7c764: dm_table_get_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
enum dm_queue_mode dm_table_get_type(struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff81e328a5)
Location: drivers/md/dm-table.c:975
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_alloc_md_mempools
  - drivers/md/dm-table.c:dm_table_bio_based
Direct callers:
  - drivers/md/dm.c:dm_setup_md_queue
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-ioctl.c:table_load
```
**Symbols:**

```
ffffffff81e33c30-ffffffff81e33c44: dm_table_get_type (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
enum dm_queue_mode dm_table_get_type(struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffff800010b03ad8)
Location: drivers/md/dm-table.c:1060
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_bio_based
Direct callers:
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-ioctl.c:dm_early_create
```
**Symbols:**

```
ffff800010b03708-ffff800010b03730: dm_table_get_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
enum dm_queue_mode dm_table_get_type(struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (c0be2b88)
Location: drivers/md/dm-table.c:1060
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_bio_based
Direct callers:
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-ioctl.c:dm_early_create
```
**Symbols:**

```
c0be27d8-c0be27f4: dm_table_get_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
enum dm_queue_mode dm_table_get_type(struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (c000000000bf32d8)
Location: drivers/md/dm-table.c:1060
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_bio_based
Direct callers:
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-ioctl.c:dm_early_create
```
**Symbols:**

```
c000000000bf2d50-c000000000bf2d60: dm_table_get_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
enum dm_queue_mode dm_table_get_type(struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffe0006f301e)
Location: drivers/md/dm-table.c:1060
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_bio_based
Direct callers:
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-ioctl.c:dm_early_create
```
**Symbols:**

```
ffffffe0006f2c42-ffffffe0006f2c64: dm_table_get_type (STB_GLOBAL)
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
enum dm_queue_mode dm_table_get_type(struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff81852eb9)
Location: drivers/md/dm-table.c:1060
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_bio_based
Direct callers:
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-ioctl.c:dm_early_create
```
**Symbols:**

```
ffffffff81852b50-ffffffff81852b5e: dm_table_get_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
enum dm_queue_mode dm_table_get_type(struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff8181a4c9)
Location: drivers/md/dm-table.c:1060
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_bio_based
Direct callers:
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-ioctl.c:dm_early_create
```
**Symbols:**

```
ffffffff8181a160-ffffffff8181a16e: dm_table_get_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
enum dm_queue_mode dm_table_get_type(struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff818a24e9)
Location: drivers/md/dm-table.c:1060
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_bio_based
Direct callers:
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-ioctl.c:dm_early_create
```
**Symbols:**

```
ffffffff818a2180-ffffffff818a218e: dm_table_get_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
enum dm_queue_mode dm_table_get_type(struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff818be729)
Location: drivers/md/dm-table.c:1060
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_bio_based
Direct callers:
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-ioctl.c:dm_early_create
```
**Symbols:**

```
ffffffff818be3c0-ffffffff818be3ce: dm_table_get_type (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>unsigned int</code> ➡️ <code>enum dm_queue_mode</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
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
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
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
