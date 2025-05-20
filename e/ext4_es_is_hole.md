# Function: <code>ext4_es_is_hole</code>

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
In fs/ext4/inode.c (ffffffff81296ead)
Location: fs/ext4/extents_status.h:123
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_get_block_prep
```
```
In fs/ext4/extents_status.c (0)
Location: fs/ext4/extents_status.h:123
Inline: True
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
In fs/ext4/inode.c (ffffffff812c44d0)
Location: fs/ext4/extents_status.h:123
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_get_block_prep
```
```
In fs/ext4/extents_status.c (0)
Location: fs/ext4/extents_status.h:123
Inline: True
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
In fs/ext4/inode.c (ffffffff812d9b80)
Location: fs/ext4/extents_status.h:123
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_get_block_prep
```
```
In fs/ext4/extents_status.c (0)
Location: fs/ext4/extents_status.h:123
Inline: True
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
In fs/ext4/extents_status.c (0)
Location: fs/ext4/extents_status.h:123
Inline: True
```
```
In fs/ext4/inode.c (ffffffff812fda9d)
Location: fs/ext4/extents_status.h:123
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_get_block_prep
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
In fs/ext4/extents_status.c (0)
Location: fs/ext4/extents_status.h:124
Inline: True
```
```
In fs/ext4/inode.c (ffffffff81322279)
Location: fs/ext4/extents_status.h:124
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_get_block_prep
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
In fs/ext4/extents_status.c (ffffffff81341fdc)
Location: fs/ext4/extents_status.h:124
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_can_be_merged
```
```
In fs/ext4/inode.c (ffffffff81351369)
Location: fs/ext4/extents_status.h:124
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_get_block_prep
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
In fs/ext4/extents_status.c (ffffffff8135982c)
Location: fs/ext4/extents_status.h:176
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_can_be_merged
```
```
In fs/ext4/inode.c (ffffffff8136a209)
Location: fs/ext4/extents_status.h:176
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_get_block_prep
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
In fs/ext4/extents_status.c (ffffffff81382809)
Location: fs/ext4/extents_status.h:176
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_can_be_merged
```
```
In fs/ext4/inode.c (ffffffff8139365e)
Location: fs/ext4/extents_status.h:176
Inline: True
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
In fs/ext4/extents.c (ffffffff813917b5)
Location: fs/ext4/extents_status.h:177
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_fill_es_cache_info
```
```
In fs/ext4/extents_status.c (ffffffff8139ad79)
Location: fs/ext4/extents_status.h:177
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_can_be_merged
```
```
In fs/ext4/inode.c (ffffffff813ac010)
Location: fs/ext4/extents_status.h:177
Inline: True
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
In fs/ext4/extents.c (ffffffff813dd295)
Location: fs/ext4/extents_status.h:177
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_fill_es_cache_info
```
```
In fs/ext4/extents_status.c (ffffffff813e627e)
Location: fs/ext4/extents_status.h:177
Inline: True
```
```
In fs/ext4/inode.c (ffffffff813f83fd)
Location: fs/ext4/extents_status.h:177
Inline: True
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
In fs/ext4/extents.c (ffffffff813eeb85)
Location: fs/ext4/extents_status.h:177
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_fill_es_cache_info
```
```
In fs/ext4/extents_status.c (ffffffff813f85de)
Location: fs/ext4/extents_status.h:177
Inline: True
```
```
In fs/ext4/inode.c (ffffffff8140a0a0)
Location: fs/ext4/extents_status.h:177
Inline: True
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
In fs/ext4/extents.c (ffffffff813fd48f)
Location: fs/ext4/extents_status.h:177
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_get_es_cache
```
```
In fs/ext4/extents_status.c (ffffffff813fea55)
Location: fs/ext4/extents_status.h:177
Inline: True
```
```
In fs/ext4/inode.c (ffffffff814101d0)
Location: fs/ext4/extents_status.h:177
Inline: True
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
In fs/ext4/extents.c (ffffffff814473f8)
Location: fs/ext4/extents_status.h:177
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_fill_es_cache_info
```
```
In fs/ext4/extents_status.c (ffffffff81451278)
Location: fs/ext4/extents_status.h:177
Inline: True
```
```
In fs/ext4/inode.c (ffffffff814657d0)
Location: fs/ext4/extents_status.h:177
Inline: True
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
In fs/ext4/extents.c (ffffffff814c3a82)
Location: fs/ext4/extents_status.h:177
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_fill_es_cache_info
```
```
In fs/ext4/extents_status.c (ffffffff814ce431)
Location: fs/ext4/extents_status.h:177
Inline: True
```
```
In fs/ext4/inode.c (ffffffff814e517b)
Location: fs/ext4/extents_status.h:177
Inline: True
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
In fs/ext4/extents.c (ffffffff8155bdc2)
Location: fs/ext4/extents_status.h:177
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_fill_es_cache_info
```
```
In fs/ext4/extents_status.c (ffffffff81566bf0)
Location: fs/ext4/extents_status.h:177
Inline: True
```
```
In fs/ext4/inode.c (ffffffff8157e7fc)
Location: fs/ext4/extents_status.h:177
Inline: True
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
In fs/ext4/extents.c (ffffffff81593bd8)
Location: fs/ext4/extents_status.h:177
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_fill_es_cache_info
```
```
In fs/ext4/extents_status.c (ffffffff8159e8a1)
Location: fs/ext4/extents_status.h:177
Inline: True
```
```
In fs/ext4/inode.c (ffffffff815b25ea)
Location: fs/ext4/extents_status.h:177
Inline: True
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
In fs/ext4/extents.c (ffffffff815cc8c8)
Location: fs/ext4/extents_status.h:177
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_fill_es_cache_info
```
```
In fs/ext4/extents_status.c (ffffffff815d7411)
Location: fs/ext4/extents_status.h:177
Inline: True
```
```
In fs/ext4/inode.c (ffffffff815ed0ed)
Location: fs/ext4/extents_status.h:177
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_map_blocks
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
In fs/ext4/extents.c (ffff800010464350)
Location: fs/ext4/extents_status.h:177
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_fill_es_cache_info
```
```
In fs/ext4/extents_status.c (ffff80001046d7d0)
Location: fs/ext4/extents_status.h:177
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_can_be_merged
```
```
In fs/ext4/inode.c (ffff80001047eb30)
Location: fs/ext4/extents_status.h:177
Inline: True
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
In fs/ext4/extents.c (c06253a4)
Location: fs/ext4/extents_status.h:177
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_fill_es_cache_info
```
```
In fs/ext4/extents_status.c (c062ef4c)
Location: fs/ext4/extents_status.h:177
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_can_be_merged
```
```
In fs/ext4/inode.c (c063f960)
Location: fs/ext4/extents_status.h:177
Inline: True
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
In fs/ext4/extents.c (c0000000005825ac)
Location: fs/ext4/extents_status.h:177
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_fill_es_cache_info
```
```
In fs/ext4/extents_status.c (c00000000058d6b4)
Location: fs/ext4/extents_status.h:177
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_can_be_merged
```
```
In fs/ext4/inode.c (c0000000005a2414)
Location: fs/ext4/extents_status.h:177
Inline: True
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
In fs/ext4/extents.c (ffffffe0002f3238)
Location: fs/ext4/extents_status.h:177
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_fill_es_cache_info
```
```
In fs/ext4/extents_status.c (ffffffe0002faa8c)
Location: fs/ext4/extents_status.h:177
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_can_be_merged
```
```
In fs/ext4/inode.c (ffffffe000309572)
Location: fs/ext4/extents_status.h:177
Inline: True
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
In fs/ext4/extents.c (ffffffff81389d95)
Location: fs/ext4/extents_status.h:177
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_fill_es_cache_info
```
```
In fs/ext4/extents_status.c (ffffffff81393359)
Location: fs/ext4/extents_status.h:177
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_can_be_merged
```
```
In fs/ext4/inode.c (ffffffff813a45f0)
Location: fs/ext4/extents_status.h:177
Inline: True
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
In fs/ext4/extents.c (ffffffff8137a825)
Location: fs/ext4/extents_status.h:177
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_fill_es_cache_info
```
```
In fs/ext4/extents_status.c (ffffffff81383de9)
Location: fs/ext4/extents_status.h:177
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_can_be_merged
```
```
In fs/ext4/inode.c (ffffffff81395080)
Location: fs/ext4/extents_status.h:177
Inline: True
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
In fs/ext4/extents.c (ffffffff813876f5)
Location: fs/ext4/extents_status.h:177
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_fill_es_cache_info
```
```
In fs/ext4/extents_status.c (ffffffff81390cb9)
Location: fs/ext4/extents_status.h:177
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_can_be_merged
```
```
In fs/ext4/inode.c (ffffffff813a1e50)
Location: fs/ext4/extents_status.h:177
Inline: True
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
In fs/ext4/extents.c (ffffffff8139b3d5)
Location: fs/ext4/extents_status.h:177
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_fill_es_cache_info
```
```
In fs/ext4/extents_status.c (ffffffff813a4b49)
Location: fs/ext4/extents_status.h:177
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_can_be_merged
```
```
In fs/ext4/inode.c (ffffffff813b52d0)
Location: fs/ext4/extents_status.h:177
Inline: True
```
</details>
</li>
</ul>

## Differences
