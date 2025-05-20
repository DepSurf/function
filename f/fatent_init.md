# Function: <code>fatent_init</code>

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
In fs/fat/cache.c (ffffffff812f56e5)
Location: fs/fat/fat.h:321
Inline: True
Inline callers:
  - fs/fat/cache.c:fat_get_cluster
```
```
In fs/fat/fatent.c (ffffffff812f9a2f)
Location: fs/fat/fat.h:321
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/fatent.c:fat_count_free_clusters
```
```
In fs/fat/file.c (ffffffff812fa949)
Location: fs/fat/fat.h:321
Inline: True
Inline callers:
  - fs/fat/file.c:fat_truncate_blocks
```
```
In fs/fat/misc.c (ffffffff812fe3f6)
Location: fs/fat/fat.h:321
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_chain_add
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
In fs/fat/cache.c (ffffffff81329104)
Location: fs/fat/fat.h:324
Inline: True
Inline callers:
  - fs/fat/cache.c:fat_get_cluster
```
```
In fs/fat/fatent.c (ffffffff8132e00c)
Location: fs/fat/fat.h:324
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_count_free_clusters
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
```
```
In fs/fat/file.c (ffffffff8132e6eb)
Location: fs/fat/fat.h:324
Inline: True
Inline callers:
  - fs/fat/file.c:fat_truncate_blocks
```
```
In fs/fat/misc.c (ffffffff813323f1)
Location: fs/fat/fat.h:324
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_chain_add
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
In fs/fat/cache.c (ffffffff8133ee44)
Location: fs/fat/fat.h:324
Inline: True
Inline callers:
  - fs/fat/cache.c:fat_get_cluster
```
```
In fs/fat/fatent.c (ffffffff81343d4c)
Location: fs/fat/fat.h:324
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_count_free_clusters
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
```
```
In fs/fat/file.c (ffffffff8134446f)
Location: fs/fat/fat.h:324
Inline: True
Inline callers:
  - fs/fat/file.c:fat_truncate_blocks
```
```
In fs/fat/misc.c (ffffffff81348191)
Location: fs/fat/fat.h:324
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_chain_add
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
In fs/fat/cache.c (ffffffff81353a0c)
Location: fs/fat/fat.h:324
Inline: True
Inline callers:
  - fs/fat/cache.c:fat_get_cluster
```
```
In fs/fat/fatent.c (ffffffff8135880c)
Location: fs/fat/fat.h:324
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_count_free_clusters
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
```
```
In fs/fat/file.c (ffffffff81358f36)
Location: fs/fat/fat.h:324
Inline: True
Inline callers:
  - fs/fat/file.c:fat_truncate_blocks
```
```
In fs/fat/misc.c (ffffffff8135cba1)
Location: fs/fat/fat.h:324
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
In fs/fat/cache.c (ffffffff8137862c)
Location: fs/fat/fat.h:325
Inline: True
Inline callers:
  - fs/fat/cache.c:fat_get_cluster
```
```
In fs/fat/fatent.c (ffffffff8137d4fc)
Location: fs/fat/fat.h:325
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_count_free_clusters
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
```
```
In fs/fat/file.c (ffffffff8137dc46)
Location: fs/fat/fat.h:325
Inline: True
Inline callers:
  - fs/fat/file.c:fat_truncate_blocks
```
```
In fs/fat/misc.c (ffffffff813818a1)
Location: fs/fat/fat.h:325
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_chain_add
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
In fs/fat/cache.c (ffffffff813a70d8)
Location: fs/fat/fat.h:325
Inline: True
Inline callers:
  - fs/fat/cache.c:fat_get_cluster
```
```
In fs/fat/fatent.c (ffffffff813abf8b)
Location: fs/fat/fat.h:325
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_count_free_clusters
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
```
```
In fs/fat/file.c (ffffffff813ac6aa)
Location: fs/fat/fat.h:325
Inline: True
Inline callers:
  - fs/fat/file.c:fat_truncate_blocks
```
```
In fs/fat/misc.c (ffffffff813b045a)
Location: fs/fat/fat.h:325
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_chain_add
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
In fs/fat/cache.c (ffffffff813bfec8)
Location: fs/fat/fat.h:353
Inline: True
Inline callers:
  - fs/fat/cache.c:fat_get_cluster
```
```
In fs/fat/fatent.c (ffffffff813c505a)
Location: fs/fat/fat.h:353
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_count_free_clusters
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
```
```
In fs/fat/file.c (ffffffff813c5940)
Location: fs/fat/fat.h:353
Inline: True
Inline callers:
  - fs/fat/file.c:fat_truncate_blocks
```
```
In fs/fat/misc.c (ffffffff813c9aba)
Location: fs/fat/fat.h:353
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
In fs/fat/cache.c (ffffffff813ea6d9)
Location: fs/fat/fat.h:353
Inline: True
Inline callers:
  - fs/fat/cache.c:fat_get_cluster
```
```
In fs/fat/fatent.c (ffffffff813ef9ae)
Location: fs/fat/fat.h:353
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_count_free_clusters
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
```
```
In fs/fat/file.c (ffffffff813f048e)
Location: fs/fat/fat.h:353
Inline: True
Inline callers:
  - fs/fat/file.c:fat_truncate_blocks
```
```
In fs/fat/misc.c (ffffffff813f464a)
Location: fs/fat/fat.h:353
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
In fs/fat/cache.c (ffffffff81404779)
Location: fs/fat/fat.h:353
Inline: True
Inline callers:
  - fs/fat/cache.c:fat_get_cluster
```
```
In fs/fat/fatent.c (ffffffff81409a1e)
Location: fs/fat/fat.h:353
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_count_free_clusters
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
```
```
In fs/fat/file.c (ffffffff8140a36e)
Location: fs/fat/fat.h:353
Inline: True
Inline callers:
  - fs/fat/file.c:fat_truncate_blocks
```
```
In fs/fat/misc.c (ffffffff8140e51a)
Location: fs/fat/fat.h:353
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_chain_add
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
In fs/fat/cache.c (ffffffff81452621)
Location: fs/fat/fat.h:353
Inline: True
Inline callers:
  - fs/fat/cache.c:fat_get_cluster
```
```
In fs/fat/fatent.c (ffffffff814575ee)
Location: fs/fat/fat.h:353
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_count_free_clusters
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
```
```
In fs/fat/file.c (ffffffff81458015)
Location: fs/fat/fat.h:353
Inline: True
```
```
In fs/fat/misc.c (ffffffff8145c2fa)
Location: fs/fat/fat.h:353
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_chain_add
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
In fs/fat/cache.c (ffffffff8146eb01)
Location: fs/fat/fat.h:353
Inline: True
Inline callers:
  - fs/fat/cache.c:fat_get_cluster
```
```
In fs/fat/fatent.c (ffffffff814739ae)
Location: fs/fat/fat.h:353
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_count_free_clusters
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
```
```
In fs/fat/file.c (ffffffff81474352)
Location: fs/fat/fat.h:353
Inline: True
```
```
In fs/fat/misc.c (ffffffff814781fa)
Location: fs/fat/fat.h:353
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_chain_add
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
In fs/fat/cache.c (ffffffff814740d6)
Location: fs/fat/fat.h:353
Inline: True
Inline callers:
  - fs/fat/cache.c:fat_get_cluster
```
```
In fs/fat/fatent.c (ffffffff814793fa)
Location: fs/fat/fat.h:353
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_count_free_clusters
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
```
```
In fs/fat/file.c (ffffffff81479cc2)
Location: fs/fat/fat.h:353
Inline: True
```
```
In fs/fat/misc.c (ffffffff8147dc8a)
Location: fs/fat/fat.h:353
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_chain_add
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
In fs/fat/cache.c (ffffffff814cad8f)
Location: fs/fat/fat.h:353
Inline: True
Inline callers:
  - fs/fat/cache.c:fat_get_cluster
```
```
In fs/fat/fatent.c (ffffffff814d0937)
Location: fs/fat/fat.h:353
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_count_free_clusters
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
```
```
In fs/fat/file.c (ffffffff814d12c8)
Location: fs/fat/fat.h:353
Inline: True
```
```
In fs/fat/misc.c (ffffffff814d5519)
Location: fs/fat/fat.h:353
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_chain_add
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fat/cache.c (ffffffff81556e2c)
Location: fs/fat/fat.h:354
Inline: True
Inline callers:
  - fs/fat/cache.c:fat_get_cluster
```
```
In fs/fat/fatent.c (ffffffff8155d48e)
Location: fs/fat/fat.h:354
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_count_free_clusters
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
```
```
In fs/fat/file.c (ffffffff8155df10)
Location: fs/fat/fat.h:354
Inline: True
```
```
In fs/fat/misc.c (ffffffff815625a4)
Location: fs/fat/fat.h:354
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_chain_add
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
In fs/fat/cache.c (ffffffff815f89ca)
Location: fs/fat/fat.h:354
Inline: True
Inline callers:
  - fs/fat/cache.c:fat_get_cluster
```
```
In fs/fat/fatent.c (ffffffff815ff4de)
Location: fs/fat/fat.h:354
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_count_free_clusters
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
```
```
In fs/fat/file.c (ffffffff815fffc0)
Location: fs/fat/fat.h:354
Inline: True
```
```
In fs/fat/misc.c (ffffffff81604f5a)
Location: fs/fat/fat.h:354
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
In fs/fat/cache.c (ffffffff8163094a)
Location: fs/fat/fat.h:354
Inline: True
Inline callers:
  - fs/fat/cache.c:fat_get_cluster
```
```
In fs/fat/fatent.c (ffffffff816374be)
Location: fs/fat/fat.h:354
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_count_free_clusters
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
```
```
In fs/fat/file.c (ffffffff81637fa0)
Location: fs/fat/fat.h:354
Inline: True
```
```
In fs/fat/misc.c (ffffffff8163ce6a)
Location: fs/fat/fat.h:354
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
In fs/fat/cache.c (ffffffff81669dfa)
Location: fs/fat/fat.h:354
Inline: True
Inline callers:
  - fs/fat/cache.c:fat_get_cluster
```
```
In fs/fat/fatent.c (ffffffff816709ae)
Location: fs/fat/fat.h:354
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_count_free_clusters
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
```
```
In fs/fat/file.c (ffffffff81671490)
Location: fs/fat/fat.h:354
Inline: True
```
```
In fs/fat/misc.c (ffffffff816763da)
Location: fs/fat/fat.h:354
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
In fs/fat/cache.c (ffff8000104e3358)
Location: fs/fat/fat.h:353
Inline: True
Inline callers:
  - fs/fat/cache.c:fat_get_cluster
```
```
In fs/fat/fatent.c (ffff8000104e9ef8)
Location: fs/fat/fat.h:353
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_count_free_clusters
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
```
```
In fs/fat/file.c (ffff8000104ea7e4)
Location: fs/fat/fat.h:353
Inline: True
Inline callers:
  - fs/fat/file.c:fat_truncate_blocks
```
```
In fs/fat/misc.c (ffff8000104ef0e4)
Location: fs/fat/fat.h:353
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
In fs/fat/cache.c (c06a24a0)
Location: fs/fat/fat.h:353
Inline: True
Inline callers:
  - fs/fat/cache.c:fat_get_cluster
```
```
In fs/fat/fatent.c (c06a7d8c)
Location: fs/fat/fat.h:353
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_count_free_clusters
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
```
```
In fs/fat/file.c (c06a8778)
Location: fs/fat/fat.h:353
Inline: True
Inline callers:
  - fs/fat/file.c:fat_truncate_blocks
```
```
In fs/fat/misc.c (c06acc3c)
Location: fs/fat/fat.h:353
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
In fs/fat/cache.c (c000000000620524)
Location: fs/fat/fat.h:353
Inline: True
Inline callers:
  - fs/fat/cache.c:fat_get_cluster
```
```
In fs/fat/fatent.c (c000000000627dac)
Location: fs/fat/fat.h:353
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_count_free_clusters
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
```
```
In fs/fat/file.c (c000000000628964)
Location: fs/fat/fat.h:353
Inline: True
Inline callers:
  - fs/fat/file.c:fat_truncate_blocks
```
```
In fs/fat/misc.c (c00000000062e314)
Location: fs/fat/fat.h:353
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
In fs/fat/cache.c (ffffffe000356b50)
Location: fs/fat/fat.h:353
Inline: True
Inline callers:
  - fs/fat/cache.c:fat_get_cluster
```
```
In fs/fat/fatent.c (ffffffe00035ae90)
Location: fs/fat/fat.h:353
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_count_free_clusters
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
```
```
In fs/fat/file.c (ffffffe00035b5c2)
Location: fs/fat/fat.h:353
Inline: True
Inline callers:
  - fs/fat/file.c:fat_truncate_blocks
```
```
In fs/fat/misc.c (ffffffe00035f144)
Location: fs/fat/fat.h:353
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
In fs/fat/cache.c (ffffffff813fcd59)
Location: fs/fat/fat.h:353
Inline: True
Inline callers:
  - fs/fat/cache.c:fat_get_cluster
```
```
In fs/fat/fatent.c (ffffffff81401ffe)
Location: fs/fat/fat.h:353
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_count_free_clusters
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
```
```
In fs/fat/file.c (ffffffff8140294e)
Location: fs/fat/fat.h:353
Inline: True
Inline callers:
  - fs/fat/file.c:fat_truncate_blocks
```
```
In fs/fat/misc.c (ffffffff81406afa)
Location: fs/fat/fat.h:353
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
In fs/fat/cache.c (ffffffff813ed7d9)
Location: fs/fat/fat.h:353
Inline: True
Inline callers:
  - fs/fat/cache.c:fat_get_cluster
```
```
In fs/fat/fatent.c (ffffffff813f2a7e)
Location: fs/fat/fat.h:353
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_count_free_clusters
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
```
```
In fs/fat/file.c (ffffffff813f33ce)
Location: fs/fat/fat.h:353
Inline: True
Inline callers:
  - fs/fat/file.c:fat_truncate_blocks
```
```
In fs/fat/misc.c (ffffffff813f757a)
Location: fs/fat/fat.h:353
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
In fs/fat/cache.c (ffffffff813fa0d9)
Location: fs/fat/fat.h:353
Inline: True
Inline callers:
  - fs/fat/cache.c:fat_get_cluster
```
```
In fs/fat/fatent.c (ffffffff813ff37e)
Location: fs/fat/fat.h:353
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_count_free_clusters
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
```
```
In fs/fat/file.c (ffffffff813ffcce)
Location: fs/fat/fat.h:353
Inline: True
Inline callers:
  - fs/fat/file.c:fat_truncate_blocks
```
```
In fs/fat/misc.c (ffffffff81403e7a)
Location: fs/fat/fat.h:353
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
In fs/fat/cache.c (ffffffff8140fd1e)
Location: fs/fat/fat.h:353
Inline: True
Inline callers:
  - fs/fat/cache.c:fat_get_cluster
```
```
In fs/fat/fatent.c (ffffffff81414fae)
Location: fs/fat/fat.h:353
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_count_free_clusters
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
```
```
In fs/fat/file.c (ffffffff814158fe)
Location: fs/fat/fat.h:353
Inline: True
Inline callers:
  - fs/fat/file.c:fat_truncate_blocks
```
```
In fs/fat/misc.c (ffffffff81419aea)
Location: fs/fat/fat.h:353
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_chain_add
```
</details>
</li>
</ul>

## Differences
