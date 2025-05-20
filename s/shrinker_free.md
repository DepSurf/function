# Function: <code>shrinker_free</code>

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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
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
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void shrinker_free(struct shrinker *shrinker);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shrinker.c (ffffffff813e3db0)
Location: mm/shrinker.c:767
Inline: False
Direct callers:
  - mm/workingset.c:workingset_init
  - mm/zswap.c:zswap_pool_destroy
  - mm/zswap.c:zswap_pool_create
  - mm/huge_memory.c:hugepage_init
  - mm/huge_memory.c:hugepage_init
  - mm/huge_memory.c:hugepage_init
  - mm/zsmalloc.c:zs_destroy_pool
  - fs/super.c:sget
  - fs/super.c:sget
  - fs/super.c:sget
  - fs/super.c:sget_fc
  - fs/super.c:sget_fc
  - fs/super.c:sget_fc
  - fs/super.c:deactivate_locked_super
  - fs/super.c:alloc_super
  - fs/mbcache.c:mb_cache_destroy
  - fs/ext4/extents_status.c:ext4_es_unregister_shrinker
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
```
**Symbols:**

```
ffffffff813e3db0-ffffffff813e3ea7: shrinker_free (STB_GLOBAL)
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
