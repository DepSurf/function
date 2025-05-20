# Function: <code>shrinker_alloc</code>

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
struct shrinker *shrinker_alloc(unsigned int flags, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shrinker.c (ffffffff813e42b0)
Location: mm/shrinker.c:676
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_init_nohz
  - kernel/rcu/tree.c:kfree_rcu_batch_init
  - mm/workingset.c:workingset_init
  - mm/zswap.c:zswap_pool_create
  - mm/huge_memory.c:hugepage_init
  - mm/huge_memory.c:hugepage_init
  - mm/zsmalloc.c:zs_create_pool
  - fs/super.c:alloc_super
  - fs/mbcache.c:mb_cache_create
  - fs/quota/dquot.c:dquot_init
  - fs/ext4/extents_status.c:ext4_es_register_shrinker
  - fs/jbd2/journal.c:journal_init_common
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_probe_backend_init
```
**Symbols:**

```
ffffffff813e42b0-ffffffff813e451b: shrinker_alloc (STB_GLOBAL)
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
