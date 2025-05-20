# Function: <code>unregister_shrinker</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void unregister_shrinker(struct shrinker *shrinker);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff811a0120)
Location: mm/vmscan.c:255
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_destroy_pool
  - fs/super.c:deactivate_locked_super
  - fs/mbcache.c:exit_mbcache
  - fs/ext4/extents_status.c:ext4_es_unregister_shrinker
```
**Symbols:**

```
ffffffff811a0120-ffffffff811a017c: unregister_shrinker (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void unregister_shrinker(struct shrinker *shrinker);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff811b6860)
Location: mm/vmscan.c:269
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_destroy_pool
  - fs/super.c:deactivate_locked_super
  - fs/mbcache.c:mb_cache_destroy
  - fs/ext4/extents_status.c:ext4_es_unregister_shrinker
```
**Symbols:**

```
ffffffff811b6860-ffffffff811b68bc: unregister_shrinker (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void unregister_shrinker(struct shrinker *shrinker);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff811c6d40)
Location: mm/vmscan.c:296
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_destroy_pool
  - fs/super.c:deactivate_locked_super
  - fs/mbcache.c:mb_cache_destroy
  - fs/ext4/extents_status.c:ext4_es_unregister_shrinker
```
**Symbols:**

```
ffffffff811c6d40-ffffffff811c6d9c: unregister_shrinker (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void unregister_shrinker(struct shrinker *shrinker);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff811cf450)
Location: mm/vmscan.c:297
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_destroy_pool
  - fs/super.c:deactivate_locked_super
  - fs/mbcache.c:mb_cache_destroy
  - fs/ext4/extents_status.c:ext4_es_unregister_shrinker
```
**Symbols:**

```
ffffffff811cf450-ffffffff811cf4a8: unregister_shrinker (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void unregister_shrinker(struct shrinker *shrinker);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff811e4a30)
Location: mm/vmscan.c:298
Inline: True
Direct callers:
  - mm/zsmalloc.c:zs_destroy_pool
  - fs/super.c:deactivate_locked_super
  - fs/mbcache.c:mb_cache_destroy
  - fs/ext4/extents_status.c:ext4_es_unregister_shrinker
```
**Symbols:**

```
ffffffff811e4a30-ffffffff811e4a99: unregister_shrinker (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void unregister_shrinker(struct shrinker *shrinker);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff812061d0)
Location: mm/vmscan.c:346
Inline: True
Direct callers:
  - mm/huge_memory.c:hugepage_init
  - mm/huge_memory.c:hugepage_init
  - mm/zsmalloc.c:zs_destroy_pool
  - fs/super.c:deactivate_locked_super
  - fs/mbcache.c:mb_cache_destroy
  - fs/ext4/extents_status.c:ext4_es_unregister_shrinker
```
**Symbols:**

```
ffffffff812061d0-ffffffff81206238: unregister_shrinker (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void unregister_shrinker(struct shrinker *shrinker);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81218e90)
Location: mm/vmscan.c:436
Inline: False
Direct callers:
  - mm/huge_memory.c:hugepage_init
  - mm/huge_memory.c:hugepage_init
  - mm/zsmalloc.c:zs_destroy_pool
  - fs/super.c:deactivate_locked_super
  - fs/mbcache.c:mb_cache_destroy
  - fs/ext4/extents_status.c:ext4_es_unregister_shrinker
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
```
**Symbols:**

```
ffffffff81218e90-ffffffff81218f08: unregister_shrinker (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void unregister_shrinker(struct shrinker *shrinker);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff812288a0)
Location: mm/vmscan.c:448
Inline: False
Direct callers:
  - mm/huge_memory.c:hugepage_init
  - mm/huge_memory.c:hugepage_init
  - mm/zsmalloc.c:zs_destroy_pool
  - fs/super.c:deactivate_locked_super
  - fs/mbcache.c:mb_cache_destroy
  - fs/ext4/extents_status.c:ext4_es_unregister_shrinker
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
```
**Symbols:**

```
ffffffff812288a0-ffffffff81228916: unregister_shrinker (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void unregister_shrinker(struct shrinker *shrinker);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81236740)
Location: mm/vmscan.c:446
Inline: False
Direct callers:
  - mm/huge_memory.c:hugepage_init
  - mm/huge_memory.c:hugepage_init
  - mm/zsmalloc.c:zs_destroy_pool
  - fs/super.c:deactivate_locked_super
  - fs/mbcache.c:mb_cache_destroy
  - fs/ext4/extents_status.c:ext4_es_unregister_shrinker
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
```
**Symbols:**

```
ffffffff81236740-ffffffff812367b6: unregister_shrinker (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void unregister_shrinker(struct shrinker *shrinker);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81263a90)
Location: mm/vmscan.c:403
Inline: False
Direct callers:
  - mm/huge_memory.c:hugepage_init
  - mm/huge_memory.c:hugepage_init
  - mm/zsmalloc.c:zs_destroy_pool
  - fs/super.c:deactivate_locked_super
  - fs/mbcache.c:mb_cache_destroy
  - fs/ext4/extents_status.c:ext4_es_unregister_shrinker
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
```
**Symbols:**

```
ffffffff81263a90-ffffffff81263b09: unregister_shrinker (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void unregister_shrinker(struct shrinker *shrinker);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff8126e420)
Location: mm/vmscan.c:396
Inline: False
Direct callers:
  - mm/huge_memory.c:hugepage_init
  - mm/huge_memory.c:hugepage_init
  - mm/zsmalloc.c:zs_destroy_pool
  - fs/super.c:deactivate_locked_super
  - fs/mbcache.c:mb_cache_destroy
  - fs/ext4/extents_status.c:ext4_es_unregister_shrinker
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
```
**Symbols:**

```
ffffffff8126e420-ffffffff8126e499: unregister_shrinker (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void unregister_shrinker(struct shrinker *shrinker);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81273100)
Location: mm/vmscan.c:627
Inline: True
Direct callers:
  - mm/huge_memory.c:hugepage_init
  - mm/huge_memory.c:hugepage_init
  - mm/zsmalloc.c:zs_destroy_pool
  - fs/super.c:deactivate_locked_super
  - fs/mbcache.c:mb_cache_destroy
  - fs/ext4/extents_status.c:ext4_es_unregister_shrinker
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
```
**Symbols:**

```
ffffffff81273100-ffffffff8127318f: unregister_shrinker (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void unregister_shrinker(struct shrinker *shrinker);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff812b0490)
Location: mm/vmscan.c:673
Inline: True
Direct callers:
  - mm/huge_memory.c:hugepage_init
  - mm/huge_memory.c:hugepage_init
  - mm/zsmalloc.c:zs_destroy_pool
  - fs/super.c:deactivate_locked_super
  - fs/mbcache.c:mb_cache_destroy
  - fs/ext4/extents_status.c:ext4_es_unregister_shrinker
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
```
**Symbols:**

```
ffffffff812b0490-ffffffff812b051f: unregister_shrinker (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void unregister_shrinker(struct shrinker *shrinker);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff8130bd50)
Location: mm/vmscan.c:670
Inline: True
Direct callers:
  - mm/huge_memory.c:hugepage_init
  - mm/huge_memory.c:hugepage_init
  - mm/zsmalloc.c:zs_destroy_pool
  - fs/super.c:deactivate_locked_super
  - fs/mbcache.c:mb_cache_destroy
  - fs/ext4/extents_status.c:ext4_es_unregister_shrinker
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
```
**Symbols:**

```
ffffffff8130bd50-ffffffff8130bdf7: unregister_shrinker (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void unregister_shrinker(struct shrinker *shrinker);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81377f50)
Location: mm/vmscan.c:742
Inline: True
Direct callers:
  - mm/huge_memory.c:hugepage_init
  - mm/huge_memory.c:hugepage_init
  - mm/zsmalloc.c:zs_destroy_pool
  - fs/super.c:deactivate_locked_super
  - fs/mbcache.c:mb_cache_destroy
  - fs/ext4/extents_status.c:ext4_es_unregister_shrinker
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
```
**Symbols:**

```
ffffffff81377f50-ffffffff81377ffe: unregister_shrinker (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void unregister_shrinker(struct shrinker *shrinker);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff813aa100)
Location: mm/vmscan.c:794
Inline: True
Direct callers:
  - mm/huge_memory.c:hugepage_init
  - mm/huge_memory.c:hugepage_init
  - mm/zsmalloc.c:zs_destroy_pool
  - fs/super.c:deactivate_locked_super
  - fs/mbcache.c:mb_cache_destroy
  - fs/ext4/extents_status.c:ext4_es_unregister_shrinker
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
```
**Symbols:**

```
ffffffff813aa100-ffffffff813aa1a7: unregister_shrinker (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void unregister_shrinker(struct shrinker *shrinker);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffff8000102c6358)
Location: mm/vmscan.c:446
Inline: False
Direct callers:
  - mm/huge_memory.c:hugepage_init
  - mm/huge_memory.c:hugepage_init
  - mm/zsmalloc.c:zs_destroy_pool
  - fs/super.c:deactivate_locked_super
  - fs/mbcache.c:mb_cache_destroy
  - fs/ext4/extents_status.c:ext4_es_unregister_shrinker
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
```
**Symbols:**

```
ffff8000102c6358-ffff8000102c63dc: unregister_shrinker (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void unregister_shrinker(struct shrinker *shrinker);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (c04f1494)
Location: mm/vmscan.c:446
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_destroy_pool
  - fs/super.c:deactivate_locked_super
  - fs/mbcache.c:mb_cache_destroy
  - fs/ext4/extents_status.c:ext4_es_unregister_shrinker
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
```
**Symbols:**

```
c04f1494-c04f1514: unregister_shrinker (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void unregister_shrinker(struct shrinker *shrinker);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (c000000000382600)
Location: mm/vmscan.c:446
Inline: False
Direct callers:
  - mm/huge_memory.c:hugepage_init
  - mm/huge_memory.c:hugepage_init
  - mm/zsmalloc.c:zs_destroy_pool
  - fs/super.c:deactivate_locked_super
  - fs/mbcache.c:mb_cache_destroy
  - fs/ext4/extents_status.c:ext4_es_unregister_shrinker
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
```
**Symbols:**

```
c000000000382600-c0000000003826dc: unregister_shrinker (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void unregister_shrinker(struct shrinker *shrinker);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffe0001e6ca6)
Location: mm/vmscan.c:446
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_destroy_pool
  - fs/super.c:deactivate_locked_super
  - fs/mbcache.c:mb_cache_destroy
  - fs/ext4/extents_status.c:ext4_es_unregister_shrinker
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
```
**Symbols:**

```
ffffffe0001e6ca6-ffffffe0001e6d1e: unregister_shrinker (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void unregister_shrinker(struct shrinker *shrinker);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff8122ed90)
Location: mm/vmscan.c:446
Inline: False
Direct callers:
  - mm/huge_memory.c:hugepage_init
  - mm/huge_memory.c:hugepage_init
  - mm/zsmalloc.c:zs_destroy_pool
  - fs/super.c:deactivate_locked_super
  - fs/mbcache.c:mb_cache_destroy
  - fs/ext4/extents_status.c:ext4_es_unregister_shrinker
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
```
**Symbols:**

```
ffffffff8122ed90-ffffffff8122ee06: unregister_shrinker (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void unregister_shrinker(struct shrinker *shrinker);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81221e50)
Location: mm/vmscan.c:446
Inline: False
Direct callers:
  - mm/huge_memory.c:hugepage_init
  - mm/huge_memory.c:hugepage_init
  - mm/zsmalloc.c:zs_destroy_pool
  - fs/super.c:deactivate_locked_super
  - fs/mbcache.c:mb_cache_destroy
  - fs/ext4/extents_status.c:ext4_es_unregister_shrinker
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
```
**Symbols:**

```
ffffffff81221e50-ffffffff81221ec6: unregister_shrinker (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void unregister_shrinker(struct shrinker *shrinker);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff8122cb30)
Location: mm/vmscan.c:446
Inline: False
Direct callers:
  - mm/huge_memory.c:hugepage_init
  - mm/huge_memory.c:hugepage_init
  - mm/zsmalloc.c:zs_destroy_pool
  - fs/super.c:deactivate_locked_super
  - fs/mbcache.c:mb_cache_destroy
  - fs/ext4/extents_status.c:ext4_es_unregister_shrinker
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
```
**Symbols:**

```
ffffffff8122cb30-ffffffff8122cba6: unregister_shrinker (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void unregister_shrinker(struct shrinker *shrinker);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff8123bf60)
Location: mm/vmscan.c:446
Inline: False
Direct callers:
  - mm/huge_memory.c:hugepage_init
  - mm/huge_memory.c:hugepage_init
  - mm/zsmalloc.c:zs_destroy_pool
  - fs/super.c:deactivate_locked_super
  - fs/mbcache.c:mb_cache_destroy
  - fs/ext4/extents_status.c:ext4_es_unregister_shrinker
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
```
**Symbols:**

```
ffffffff8123bf60-ffffffff8123bfd6: unregister_shrinker (STB_GLOBAL)
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
No changes between <code>4.10</code> and <code>4.13</code> ✅
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
