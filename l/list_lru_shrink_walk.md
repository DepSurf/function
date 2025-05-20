# Function: <code>list_lru_shrink_walk</code>

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
In mm/workingset.c (ffffffff811b9d73)
Location: include/linux/list_lru.h:167
Inline: True
Inline callers:
  - mm/workingset.c:scan_shadow_nodes
```
```
In fs/dcache.c (ffffffff812255b0)
Location: include/linux/list_lru.h:167
Inline: True
Inline callers:
  - fs/dcache.c:prune_dcache_sb
```
```
In fs/inode.c (ffffffff81228f60)
Location: include/linux/list_lru.h:167
Inline: True
Inline callers:
  - fs/inode.c:prune_icache_sb
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
In mm/workingset.c (ffffffff811d40e3)
Location: include/linux/list_lru.h:167
Inline: True
Inline callers:
  - mm/workingset.c:scan_shadow_nodes
```
```
In fs/dcache.c (ffffffff8124d6a0)
Location: include/linux/list_lru.h:167
Inline: True
Inline callers:
  - fs/dcache.c:prune_dcache_sb
```
```
In fs/inode.c (ffffffff81251660)
Location: include/linux/list_lru.h:167
Inline: True
Inline callers:
  - fs/inode.c:prune_icache_sb
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
In mm/workingset.c (ffffffff811e40a3)
Location: include/linux/list_lru.h:167
Inline: True
Inline callers:
  - mm/workingset.c:scan_shadow_nodes
```
```
In fs/dcache.c (ffffffff81260770)
Location: include/linux/list_lru.h:167
Inline: True
Inline callers:
  - fs/dcache.c:prune_dcache_sb
```
```
In fs/inode.c (ffffffff81264760)
Location: include/linux/list_lru.h:167
Inline: True
Inline callers:
  - fs/inode.c:prune_icache_sb
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
In mm/workingset.c (ffffffff811ee2b3)
Location: include/linux/list_lru.h:168
Inline: True
Inline callers:
  - mm/workingset.c:scan_shadow_nodes
```
```
In fs/dcache.c (ffffffff8126df40)
Location: include/linux/list_lru.h:168
Inline: True
Inline callers:
  - fs/dcache.c:prune_dcache_sb
```
```
In fs/inode.c (ffffffff81271f90)
Location: include/linux/list_lru.h:168
Inline: True
Inline callers:
  - fs/inode.c:prune_icache_sb
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
In mm/workingset.c (ffffffff81204963)
Location: include/linux/list_lru.h:169
Inline: True
Inline callers:
  - mm/workingset.c:scan_shadow_nodes
```
```
In fs/dcache.c (ffffffff81290860)
Location: include/linux/list_lru.h:169
Inline: True
Inline callers:
  - fs/dcache.c:prune_dcache_sb
```
```
In fs/inode.c (ffffffff812948b0)
Location: include/linux/list_lru.h:169
Inline: True
Inline callers:
  - fs/inode.c:prune_icache_sb
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
In mm/workingset.c (ffffffff81225463)
Location: include/linux/list_lru.h:170
Inline: True
Inline callers:
  - mm/workingset.c:scan_shadow_nodes
```
```
In fs/dcache.c (ffffffff812b701a)
Location: include/linux/list_lru.h:170
Inline: True
Inline callers:
  - fs/dcache.c:prune_dcache_sb
```
```
In fs/inode.c (ffffffff812ba9ea)
Location: include/linux/list_lru.h:170
Inline: True
Inline callers:
  - fs/inode.c:prune_icache_sb
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
In fs/dcache.c (ffffffff812cc1fa)
Location: include/linux/list_lru.h:191
Inline: True
Inline callers:
  - fs/dcache.c:prune_dcache_sb
```
```
In fs/inode.c (ffffffff812cfd2a)
Location: include/linux/list_lru.h:191
Inline: True
Inline callers:
  - fs/inode.c:prune_icache_sb
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
In fs/dcache.c (ffffffff812e8ddc)
Location: include/linux/list_lru.h:192
Inline: True
Inline callers:
  - fs/dcache.c:prune_dcache_sb
```
```
In fs/inode.c (ffffffff812ecc7c)
Location: include/linux/list_lru.h:192
Inline: True
Inline callers:
  - fs/inode.c:prune_icache_sb
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
In fs/dcache.c (ffffffff812fa97c)
Location: include/linux/list_lru.h:192
Inline: True
Inline callers:
  - fs/dcache.c:prune_dcache_sb
```
```
In fs/inode.c (ffffffff812fe80c)
Location: include/linux/list_lru.h:192
Inline: True
Inline callers:
  - fs/inode.c:prune_icache_sb
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
In fs/dcache.c (ffffffff813339dc)
Location: include/linux/list_lru.h:192
Inline: True
Inline callers:
  - fs/dcache.c:prune_dcache_sb
```
```
In fs/inode.c (ffffffff813378ab)
Location: include/linux/list_lru.h:192
Inline: True
Inline callers:
  - fs/inode.c:prune_icache_sb
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
In fs/dcache.c (ffffffff8133f35c)
Location: include/linux/list_lru.h:192
Inline: True
Inline callers:
  - fs/dcache.c:prune_dcache_sb
```
```
In fs/inode.c (ffffffff813431eb)
Location: include/linux/list_lru.h:192
Inline: True
Inline callers:
  - fs/inode.c:prune_icache_sb
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
In fs/dcache.c (ffffffff813457dc)
Location: include/linux/list_lru.h:192
Inline: True
Inline callers:
  - fs/dcache.c:prune_dcache_sb
```
```
In fs/inode.c (ffffffff813494ab)
Location: include/linux/list_lru.h:192
Inline: True
Inline callers:
  - fs/inode.c:prune_icache_sb
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
In fs/dcache.c (ffffffff813933ec)
Location: include/linux/list_lru.h:192
Inline: True
Inline callers:
  - fs/dcache.c:prune_dcache_sb
```
```
In fs/inode.c (ffffffff813971fb)
Location: include/linux/list_lru.h:192
Inline: True
Inline callers:
  - fs/inode.c:prune_icache_sb
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
In fs/dcache.c (ffffffff81414b17)
Location: include/linux/list_lru.h:191
Inline: True
Inline callers:
  - fs/dcache.c:prune_dcache_sb
```
```
In fs/inode.c (ffffffff81419307)
Location: include/linux/list_lru.h:191
Inline: True
Inline callers:
  - fs/inode.c:prune_icache_sb
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
In fs/dcache.c (ffffffff814a0017)
Location: include/linux/list_lru.h:191
Inline: True
Inline callers:
  - fs/dcache.c:prune_dcache_sb
```
```
In fs/inode.c (ffffffff814a4d27)
Location: include/linux/list_lru.h:191
Inline: True
Inline callers:
  - fs/inode.c:prune_icache_sb
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
In fs/dcache.c (ffffffff814d5337)
Location: include/linux/list_lru.h:191
Inline: True
Inline callers:
  - fs/dcache.c:prune_dcache_sb
```
```
In fs/inode.c (ffffffff814d9eb7)
Location: include/linux/list_lru.h:191
Inline: True
Inline callers:
  - fs/inode.c:prune_icache_sb
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
In mm/zswap.c (ffffffff8146f49d)
Location: include/linux/list_lru.h:241
Inline: True
Inline callers:
  - mm/zswap.c:zswap_shrinker_scan
```
```
In fs/dcache.c (ffffffff81507757)
Location: include/linux/list_lru.h:241
Inline: True
Inline callers:
  - fs/dcache.c:prune_dcache_sb
```
```
In fs/inode.c (ffffffff8150c637)
Location: include/linux/list_lru.h:241
Inline: True
Inline callers:
  - fs/inode.c:prune_icache_sb
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
In fs/dcache.c (ffff8000103a9b24)
Location: include/linux/list_lru.h:192
Inline: True
Inline callers:
  - fs/dcache.c:prune_dcache_sb
```
```
In fs/inode.c (ffff8000103af66c)
Location: include/linux/list_lru.h:192
Inline: True
Inline callers:
  - fs/inode.c:prune_icache_sb
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
In fs/dcache.c (c058ac54)
Location: include/linux/list_lru.h:192
Inline: True
Inline callers:
  - fs/dcache.c:prune_dcache_sb
```
```
In fs/inode.c (c058f438)
Location: include/linux/list_lru.h:192
Inline: True
Inline callers:
  - fs/inode.c:prune_icache_sb
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
In fs/dcache.c (c0000000004a4778)
Location: include/linux/list_lru.h:192
Inline: True
Inline callers:
  - fs/dcache.c:prune_dcache_sb
```
```
In fs/inode.c (c0000000004ab198)
Location: include/linux/list_lru.h:192
Inline: True
Inline callers:
  - fs/inode.c:prune_icache_sb
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
In fs/dcache.c (ffffffe00026f96c)
Location: include/linux/list_lru.h:192
Inline: True
Inline callers:
  - fs/dcache.c:prune_dcache_sb
```
```
In fs/inode.c (ffffffe000274112)
Location: include/linux/list_lru.h:192
Inline: True
Inline callers:
  - fs/inode.c:prune_icache_sb
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
In fs/dcache.c (ffffffff812f2f5c)
Location: include/linux/list_lru.h:192
Inline: True
Inline callers:
  - fs/dcache.c:prune_dcache_sb
```
```
In fs/inode.c (ffffffff812f6dec)
Location: include/linux/list_lru.h:192
Inline: True
Inline callers:
  - fs/inode.c:prune_icache_sb
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
In fs/dcache.c (ffffffff812e3b8c)
Location: include/linux/list_lru.h:192
Inline: True
Inline callers:
  - fs/dcache.c:prune_dcache_sb
```
```
In fs/inode.c (ffffffff812e7a0c)
Location: include/linux/list_lru.h:192
Inline: True
Inline callers:
  - fs/inode.c:prune_icache_sb
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
In fs/dcache.c (ffffffff812f0d6c)
Location: include/linux/list_lru.h:192
Inline: True
Inline callers:
  - fs/dcache.c:prune_dcache_sb
```
```
In fs/inode.c (ffffffff812f4bfc)
Location: include/linux/list_lru.h:192
Inline: True
Inline callers:
  - fs/inode.c:prune_icache_sb
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
In fs/dcache.c (ffffffff81301f2c)
Location: include/linux/list_lru.h:192
Inline: True
Inline callers:
  - fs/dcache.c:prune_dcache_sb
```
```
In fs/inode.c (ffffffff81305d8c)
Location: include/linux/list_lru.h:192
Inline: True
Inline callers:
  - fs/inode.c:prune_icache_sb
```
</details>
</li>
</ul>

## Differences
