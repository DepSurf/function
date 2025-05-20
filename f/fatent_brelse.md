# Function: <code>fatent_brelse</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void fatent_brelse(struct fat_entry *fatent);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fat/cache.c (ffffffff812f5780)
Location: fs/fat/fat.h:336
Inline: True
Inline callers:
  - fs/fat/cache.c:fat_get_cluster
```
```
In fs/fat/fatent.c (ffffffff812f9220)
Location: fs/fat/fat.h:336
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_ent_read
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/fatent.c:fat_count_free_clusters
  - fs/fat/fatent.c:fat_count_free_clusters
Direct callers:
  - fs/fat/fatent.c:fat_ent_read
```
```
In fs/fat/file.c (ffffffff812fa9b6)
Location: fs/fat/fat.h:336
Inline: True
Inline callers:
  - fs/fat/file.c:fat_truncate_blocks
  - fs/fat/file.c:fat_truncate_blocks
```
```
In fs/fat/misc.c (ffffffff812fe44e)
Location: fs/fat/fat.h:336
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_chain_add
```
**Symbols:**

```
ffffffff812f9220-ffffffff812f927b: fatent_brelse (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void fatent_brelse(struct fat_entry *fatent);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fat/cache.c (ffffffff81329199)
Location: fs/fat/fat.h:339
Inline: True
Inline callers:
  - fs/fat/cache.c:fat_get_cluster
```
```
In fs/fat/fatent.c (ffffffff8132e083)
Location: fs/fat/fat.h:339
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_count_free_clusters
  - fs/fat/fatent.c:fat_count_free_clusters
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/fatent.c:fat_ent_read
Direct callers:
  - fs/fat/fatent.c:fat_ent_read
```
```
In fs/fat/file.c (ffffffff8132e758)
Location: fs/fat/fat.h:339
Inline: True
Inline callers:
  - fs/fat/file.c:fat_truncate_blocks
  - fs/fat/file.c:fat_truncate_blocks
```
```
In fs/fat/misc.c (ffffffff81332449)
Location: fs/fat/fat.h:339
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_chain_add
```
**Symbols:**

```
ffffffff8132ce40-ffffffff8132ce9b: fatent_brelse (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void fatent_brelse(struct fat_entry *fatent);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fat/cache.c (ffffffff8133eed9)
Location: fs/fat/fat.h:339
Inline: True
Inline callers:
  - fs/fat/cache.c:fat_get_cluster
```
```
In fs/fat/fatent.c (ffffffff81343dc3)
Location: fs/fat/fat.h:339
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_count_free_clusters
  - fs/fat/fatent.c:fat_count_free_clusters
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/fatent.c:fat_ent_read
Direct callers:
  - fs/fat/fatent.c:fat_ent_read
```
```
In fs/fat/file.c (ffffffff813444dc)
Location: fs/fat/fat.h:339
Inline: True
Inline callers:
  - fs/fat/file.c:fat_truncate_blocks
  - fs/fat/file.c:fat_truncate_blocks
```
```
In fs/fat/misc.c (ffffffff813481e9)
Location: fs/fat/fat.h:339
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_chain_add
```
**Symbols:**

```
ffffffff81342b80-ffffffff81342bdb: fatent_brelse (STB_LOCAL)
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
In fs/fat/cache.c (ffffffff81353aa1)
Location: fs/fat/fat.h:339
Inline: True
Inline callers:
  - fs/fat/cache.c:fat_get_cluster
```
```
In fs/fat/fatent.c (ffffffff81358891)
Location: fs/fat/fat.h:339
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_count_free_clusters
  - fs/fat/fatent.c:fat_count_free_clusters
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/fatent.c:fat_ent_read
  - fs/fat/fatent.c:fat_ent_read
```
```
In fs/fat/file.c (ffffffff81358f9c)
Location: fs/fat/fat.h:339
Inline: True
Inline callers:
  - fs/fat/file.c:fat_truncate_blocks
  - fs/fat/file.c:fat_truncate_blocks
```
```
In fs/fat/misc.c (ffffffff8135cbf9)
Location: fs/fat/fat.h:339
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_chain_add
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
In fs/fat/cache.c (ffffffff813786c1)
Location: fs/fat/fat.h:340
Inline: True
Inline callers:
  - fs/fat/cache.c:fat_get_cluster
```
```
In fs/fat/fatent.c (ffffffff8137d581)
Location: fs/fat/fat.h:340
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_count_free_clusters
  - fs/fat/fatent.c:fat_count_free_clusters
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/fatent.c:fat_ent_read
  - fs/fat/fatent.c:fat_ent_read
```
```
In fs/fat/file.c (ffffffff8137dcac)
Location: fs/fat/fat.h:340
Inline: True
Inline callers:
  - fs/fat/file.c:fat_truncate_blocks
  - fs/fat/file.c:fat_truncate_blocks
```
```
In fs/fat/misc.c (ffffffff813818f9)
Location: fs/fat/fat.h:340
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_chain_add
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void fatent_brelse(struct fat_entry *fatent);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fat/cache.c (ffffffff813a716d)
Location: fs/fat/fat.h:340
Inline: True
Inline callers:
  - fs/fat/cache.c:fat_get_cluster
```
```
In fs/fat/fatent.c (ffffffff813abfbe)
Location: fs/fat/fat.h:340
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_count_free_clusters
  - fs/fat/fatent.c:fat_count_free_clusters
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/fatent.c:fat_ent_read
Direct callers:
  - fs/fat/fatent.c:fat_ent_read
```
```
In fs/fat/file.c (ffffffff813ac70b)
Location: fs/fat/fat.h:340
Inline: True
Inline callers:
  - fs/fat/file.c:fat_truncate_blocks
  - fs/fat/file.c:fat_truncate_blocks
```
```
In fs/fat/misc.c (ffffffff813b04b9)
Location: fs/fat/fat.h:340
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_chain_add
```
**Symbols:**

```
ffffffff813aad60-ffffffff813aadbb: fatent_brelse (STB_LOCAL)
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
In fs/fat/cache.c (ffffffff813bff5d)
Location: fs/fat/fat.h:368
Inline: True
Inline callers:
  - fs/fat/cache.c:fat_get_cluster
```
```
In fs/fat/fatent.c (ffffffff813c50e8)
Location: fs/fat/fat.h:368
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_count_free_clusters
  - fs/fat/fatent.c:fat_count_free_clusters
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/fatent.c:fat_ent_read
  - fs/fat/fatent.c:fat_ent_read
```
```
In fs/fat/file.c (ffffffff813c5999)
Location: fs/fat/fat.h:368
Inline: True
Inline callers:
  - fs/fat/file.c:fat_truncate_blocks
  - fs/fat/file.c:fat_truncate_blocks
```
```
In fs/fat/misc.c (ffffffff813c9b19)
Location: fs/fat/fat.h:368
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_chain_add
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
In fs/fat/cache.c (ffffffff813ea764)
Location: fs/fat/fat.h:368
Inline: True
Inline callers:
  - fs/fat/cache.c:fat_get_cluster
```
```
In fs/fat/fatent.c (ffffffff813efab2)
Location: fs/fat/fat.h:368
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_count_free_clusters
  - fs/fat/fatent.c:fat_count_free_clusters
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/fatent.c:fat_ent_read
  - fs/fat/fatent.c:fat_ent_read
```
```
In fs/fat/file.c (ffffffff813f04e7)
Location: fs/fat/fat.h:368
Inline: True
Inline callers:
  - fs/fat/file.c:fat_truncate_blocks
  - fs/fat/file.c:fat_truncate_blocks
```
```
In fs/fat/misc.c (ffffffff813f46a9)
Location: fs/fat/fat.h:368
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_chain_add
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
In fs/fat/cache.c (ffffffff81404804)
Location: fs/fat/fat.h:368
Inline: True
Inline callers:
  - fs/fat/cache.c:fat_get_cluster
```
```
In fs/fat/fatent.c (ffffffff81409b22)
Location: fs/fat/fat.h:368
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_count_free_clusters
  - fs/fat/fatent.c:fat_count_free_clusters
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/fatent.c:fat_ent_read
  - fs/fat/fatent.c:fat_ent_read
```
```
In fs/fat/file.c (ffffffff8140a3c7)
Location: fs/fat/fat.h:368
Inline: True
Inline callers:
  - fs/fat/file.c:fat_truncate_blocks
  - fs/fat/file.c:fat_truncate_blocks
```
```
In fs/fat/misc.c (ffffffff8140e579)
Location: fs/fat/fat.h:368
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_chain_add
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void fatent_brelse(struct fat_entry *fatent);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fat/cache.c (ffffffff814526a3)
Location: fs/fat/fat.h:368
Inline: True
Inline callers:
  - fs/fat/cache.c:fat_get_cluster
```
```
In fs/fat/fatent.c (ffffffff814576fa)
Location: fs/fat/fat.h:368
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_count_free_clusters
  - fs/fat/fatent.c:fat_count_free_clusters
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/fatent.c:fat_ent_read
Direct callers:
  - fs/fat/fatent.c:fat_ent_read
```
```
In fs/fat/file.c (ffffffff8145806a)
Location: fs/fat/fat.h:368
Inline: True
```
```
In fs/fat/misc.c (ffffffff8145c359)
Location: fs/fat/fat.h:368
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_chain_add
```
**Symbols:**

```
ffffffff81455fa0-ffffffff81455ffe: fatent_brelse (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void fatent_brelse(struct fat_entry *fatent);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fat/cache.c (ffffffff8146eb83)
Location: fs/fat/fat.h:368
Inline: True
Inline callers:
  - fs/fat/cache.c:fat_get_cluster
```
```
In fs/fat/fatent.c (ffffffff81473aba)
Location: fs/fat/fat.h:368
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_count_free_clusters
  - fs/fat/fatent.c:fat_count_free_clusters
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/fatent.c:fat_ent_read
Direct callers:
  - fs/fat/fatent.c:fat_ent_read
```
```
In fs/fat/file.c (ffffffff814743a7)
Location: fs/fat/fat.h:368
Inline: True
```
```
In fs/fat/misc.c (ffffffff81478259)
Location: fs/fat/fat.h:368
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_chain_add
```
**Symbols:**

```
ffffffff81472360-ffffffff814723be: fatent_brelse (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void fatent_brelse(struct fat_entry *fatent);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fat/cache.c (ffffffff81474161)
Location: fs/fat/fat.h:368
Inline: True
Inline callers:
  - fs/fat/cache.c:fat_get_cluster
```
```
In fs/fat/fatent.c (ffffffff81479506)
Location: fs/fat/fat.h:368
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_count_free_clusters
  - fs/fat/fatent.c:fat_count_free_clusters
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/fatent.c:fat_ent_read
Direct callers:
  - fs/fat/fatent.c:fat_ent_read
```
```
In fs/fat/file.c (ffffffff81479d17)
Location: fs/fat/fat.h:368
Inline: True
```
```
In fs/fat/misc.c (ffffffff8147dce5)
Location: fs/fat/fat.h:368
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_chain_add
```
**Symbols:**

```
ffffffff81477d70-ffffffff81477dce: fatent_brelse (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void fatent_brelse(struct fat_entry *fatent);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fat/cache.c (ffffffff814cae05)
Location: fs/fat/fat.h:368
Inline: True
Inline callers:
  - fs/fat/cache.c:fat_get_cluster
```
```
In fs/fat/fatent.c (ffffffff814d09fe)
Location: fs/fat/fat.h:368
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_count_free_clusters
  - fs/fat/fatent.c:fat_count_free_clusters
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/fatent.c:fat_ent_read
Direct callers:
  - fs/fat/fatent.c:fat_ent_read
```
```
In fs/fat/file.c (ffffffff814d1321)
Location: fs/fat/fat.h:368
Inline: True
```
```
In fs/fat/misc.c (ffffffff814d5574)
Location: fs/fat/fat.h:368
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_chain_add
```
**Symbols:**

```
ffffffff814cefc0-ffffffff814cf03b: fatent_brelse (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void fatent_brelse(struct fat_entry *fatent);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fat/cache.c (ffffffff81556eac)
Location: fs/fat/fat.h:369
Inline: True
Inline callers:
  - fs/fat/cache.c:fat_get_cluster
```
```
In fs/fat/fatent.c (ffffffff8155d570)
Location: fs/fat/fat.h:369
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_count_free_clusters
  - fs/fat/fatent.c:fat_count_free_clusters
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/fatent.c:fat_ent_read
Direct callers:
  - fs/fat/fatent.c:fat_ent_read
```
```
In fs/fat/file.c (ffffffff8155df64)
Location: fs/fat/fat.h:369
Inline: True
```
```
In fs/fat/misc.c (ffffffff815625cf)
Location: fs/fat/fat.h:369
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_chain_add
```
**Symbols:**

```
ffffffff8155b9c0-ffffffff8155ba45: fatent_brelse (STB_LOCAL)
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
In fs/fat/cache.c (ffffffff815f8aac)
Location: fs/fat/fat.h:369
Inline: True
Inline callers:
  - fs/fat/cache.c:fat_get_cluster
```
```
In fs/fat/fatent.c (ffffffff815ff5c0)
Location: fs/fat/fat.h:369
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_count_free_clusters
  - fs/fat/fatent.c:fat_count_free_clusters
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/fatent.c:fat_ent_read
  - fs/fat/fatent.c:fat_ent_read
```
```
In fs/fat/file.c (ffffffff81600014)
Location: fs/fat/fat.h:369
Inline: True
```
```
In fs/fat/misc.c (ffffffff81604f91)
Location: fs/fat/fat.h:369
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_chain_add
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
In fs/fat/cache.c (ffffffff81630a2c)
Location: fs/fat/fat.h:369
Inline: True
Inline callers:
  - fs/fat/cache.c:fat_get_cluster
```
```
In fs/fat/fatent.c (ffffffff816375a0)
Location: fs/fat/fat.h:369
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_count_free_clusters
  - fs/fat/fatent.c:fat_count_free_clusters
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/fatent.c:fat_ent_read
  - fs/fat/fatent.c:fat_ent_read
```
```
In fs/fat/file.c (ffffffff81637ff4)
Location: fs/fat/fat.h:369
Inline: True
```
```
In fs/fat/misc.c (ffffffff8163cea1)
Location: fs/fat/fat.h:369
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_chain_add
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
In fs/fat/cache.c (ffffffff81669edc)
Location: fs/fat/fat.h:369
Inline: True
Inline callers:
  - fs/fat/cache.c:fat_get_cluster
```
```
In fs/fat/fatent.c (ffffffff81670a90)
Location: fs/fat/fat.h:369
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_count_free_clusters
  - fs/fat/fatent.c:fat_count_free_clusters
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/fatent.c:fat_ent_read
  - fs/fat/fatent.c:fat_ent_read
```
```
In fs/fat/file.c (ffffffff816714e4)
Location: fs/fat/fat.h:369
Inline: True
```
```
In fs/fat/misc.c (ffffffff81676411)
Location: fs/fat/fat.h:369
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_chain_add
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
In fs/fat/cache.c (ffff8000104e33f4)
Location: fs/fat/fat.h:368
Inline: True
Inline callers:
  - fs/fat/cache.c:fat_get_cluster
```
```
In fs/fat/fatent.c (ffff8000104e9fa4)
Location: fs/fat/fat.h:368
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_count_free_clusters
  - fs/fat/fatent.c:fat_count_free_clusters
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/fatent.c:fat_ent_read
  - fs/fat/fatent.c:fat_ent_read
```
```
In fs/fat/file.c (ffff8000104ea820)
Location: fs/fat/fat.h:368
Inline: True
Inline callers:
  - fs/fat/file.c:fat_truncate_blocks
  - fs/fat/file.c:fat_truncate_blocks
```
```
In fs/fat/misc.c (ffff8000104ef134)
Location: fs/fat/fat.h:368
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_chain_add
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
In fs/fat/cache.c (c06a2558)
Location: fs/fat/fat.h:368
Inline: True
Inline callers:
  - fs/fat/cache.c:fat_get_cluster
```
```
In fs/fat/fatent.c (c06a7dfc)
Location: fs/fat/fat.h:368
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_count_free_clusters
  - fs/fat/fatent.c:fat_count_free_clusters
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/fatent.c:fat_ent_read
  - fs/fat/fatent.c:fat_ent_read
```
```
In fs/fat/file.c (c06a87b8)
Location: fs/fat/fat.h:368
Inline: True
Inline callers:
  - fs/fat/file.c:fat_truncate_blocks
  - fs/fat/file.c:fat_truncate_blocks
```
```
In fs/fat/misc.c (c06acc98)
Location: fs/fat/fat.h:368
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_chain_add
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
In fs/fat/cache.c (c0000000006205d8)
Location: fs/fat/fat.h:368
Inline: True
Inline callers:
  - fs/fat/cache.c:fat_get_cluster
```
```
In fs/fat/fatent.c (c000000000627e5c)
Location: fs/fat/fat.h:368
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_count_free_clusters
  - fs/fat/fatent.c:fat_count_free_clusters
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/fatent.c:fat_ent_read
  - fs/fat/fatent.c:fat_ent_read
```
```
In fs/fat/file.c (c0000000006289b8)
Location: fs/fat/fat.h:368
Inline: True
Inline callers:
  - fs/fat/file.c:fat_truncate_blocks
  - fs/fat/file.c:fat_truncate_blocks
```
```
In fs/fat/misc.c (c00000000062e390)
Location: fs/fat/fat.h:368
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_chain_add
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
In fs/fat/cache.c (ffffffe000356bd0)
Location: fs/fat/fat.h:368
Inline: True
Inline callers:
  - fs/fat/cache.c:fat_get_cluster
```
```
In fs/fat/fatent.c (ffffffe00035aecc)
Location: fs/fat/fat.h:368
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_count_free_clusters
  - fs/fat/fatent.c:fat_count_free_clusters
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/fatent.c:fat_ent_read
  - fs/fat/fatent.c:fat_ent_read
```
```
In fs/fat/file.c (ffffffe00035b5f8)
Location: fs/fat/fat.h:368
Inline: True
Inline callers:
  - fs/fat/file.c:fat_truncate_blocks
  - fs/fat/file.c:fat_truncate_blocks
```
```
In fs/fat/misc.c (ffffffe00035f18c)
Location: fs/fat/fat.h:368
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_chain_add
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
In fs/fat/cache.c (ffffffff813fcde4)
Location: fs/fat/fat.h:368
Inline: True
Inline callers:
  - fs/fat/cache.c:fat_get_cluster
```
```
In fs/fat/fatent.c (ffffffff81402102)
Location: fs/fat/fat.h:368
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_count_free_clusters
  - fs/fat/fatent.c:fat_count_free_clusters
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/fatent.c:fat_ent_read
  - fs/fat/fatent.c:fat_ent_read
```
```
In fs/fat/file.c (ffffffff814029a7)
Location: fs/fat/fat.h:368
Inline: True
Inline callers:
  - fs/fat/file.c:fat_truncate_blocks
  - fs/fat/file.c:fat_truncate_blocks
```
```
In fs/fat/misc.c (ffffffff81406b59)
Location: fs/fat/fat.h:368
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_chain_add
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
In fs/fat/cache.c (ffffffff813ed864)
Location: fs/fat/fat.h:368
Inline: True
Inline callers:
  - fs/fat/cache.c:fat_get_cluster
```
```
In fs/fat/fatent.c (ffffffff813f2b82)
Location: fs/fat/fat.h:368
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_count_free_clusters
  - fs/fat/fatent.c:fat_count_free_clusters
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/fatent.c:fat_ent_read
  - fs/fat/fatent.c:fat_ent_read
```
```
In fs/fat/file.c (ffffffff813f3427)
Location: fs/fat/fat.h:368
Inline: True
Inline callers:
  - fs/fat/file.c:fat_truncate_blocks
  - fs/fat/file.c:fat_truncate_blocks
```
```
In fs/fat/misc.c (ffffffff813f75d9)
Location: fs/fat/fat.h:368
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_chain_add
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
In fs/fat/cache.c (ffffffff813fa164)
Location: fs/fat/fat.h:368
Inline: True
Inline callers:
  - fs/fat/cache.c:fat_get_cluster
```
```
In fs/fat/fatent.c (ffffffff813ff482)
Location: fs/fat/fat.h:368
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_count_free_clusters
  - fs/fat/fatent.c:fat_count_free_clusters
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/fatent.c:fat_ent_read
  - fs/fat/fatent.c:fat_ent_read
```
```
In fs/fat/file.c (ffffffff813ffd27)
Location: fs/fat/fat.h:368
Inline: True
Inline callers:
  - fs/fat/file.c:fat_truncate_blocks
  - fs/fat/file.c:fat_truncate_blocks
```
```
In fs/fat/misc.c (ffffffff81403ed9)
Location: fs/fat/fat.h:368
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_chain_add
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
In fs/fat/cache.c (ffffffff8140fd9f)
Location: fs/fat/fat.h:368
Inline: True
Inline callers:
  - fs/fat/cache.c:fat_get_cluster
```
```
In fs/fat/fatent.c (ffffffff814150b2)
Location: fs/fat/fat.h:368
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_count_free_clusters
  - fs/fat/fatent.c:fat_count_free_clusters
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/fatent.c:fat_ent_read
  - fs/fat/fatent.c:fat_ent_read
```
```
In fs/fat/file.c (ffffffff81415957)
Location: fs/fat/fat.h:368
Inline: True
Inline callers:
  - fs/fat/file.c:fat_truncate_blocks
  - fs/fat/file.c:fat_truncate_blocks
```
```
In fs/fat/misc.c (ffffffff81419b49)
Location: fs/fat/fat.h:368
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_chain_add
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
</ul>
