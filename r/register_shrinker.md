# Function: <code>register_shrinker</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int register_shrinker(struct shrinker *shrinker);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff811a0d60)
Location: mm/vmscan.c:226
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_create_pool
  - fs/super.c:sget_userns
  - fs/mbcache.c:init_mbcache
  - fs/ext4/extents_status.c:ext4_es_register_shrinker
```
**Symbols:**

```
ffffffff811a0d60-ffffffff811a0dfa: register_shrinker (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int register_shrinker(struct shrinker *shrinker);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff811b7180)
Location: mm/vmscan.c:248
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_create_pool
  - fs/super.c:sget_userns
  - fs/mbcache.c:mb_cache_create
  - fs/ext4/extents_status.c:ext4_es_register_shrinker
```
**Symbols:**

```
ffffffff811b7180-ffffffff811b720e: register_shrinker (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int register_shrinker(struct shrinker *shrinker);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff811c76b0)
Location: mm/vmscan.c:275
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_create_pool
  - fs/super.c:sget_userns
  - fs/mbcache.c:mb_cache_create
  - fs/ext4/extents_status.c:ext4_es_register_shrinker
```
**Symbols:**

```
ffffffff811c76b0-ffffffff811c773e: register_shrinker (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int register_shrinker(struct shrinker *shrinker);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff811cfde0)
Location: mm/vmscan.c:276
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_create_pool
  - fs/super.c:sget_userns
  - fs/mbcache.c:mb_cache_create
  - fs/ext4/extents_status.c:ext4_es_register_shrinker
```
**Symbols:**

```
ffffffff811cfde0-ffffffff811cfe6e: register_shrinker (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int register_shrinker(struct shrinker *shrinker);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff811e5290)
Location: mm/vmscan.c:277
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_create_pool
  - fs/super.c:sget_userns
  - fs/mbcache.c:mb_cache_create
  - fs/ext4/extents_status.c:ext4_es_register_shrinker
```
**Symbols:**

```
ffffffff811e5290-ffffffff811e531e: register_shrinker (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int register_shrinker(struct shrinker *shrinker);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff812082d0)
Location: mm/vmscan.c:332
Inline: False
Direct callers:
  - mm/workingset.c:workingset_init
  - mm/huge_memory.c:hugepage_init
  - mm/huge_memory.c:hugepage_init
  - mm/zsmalloc.c:zs_create_pool
  - fs/mbcache.c:mb_cache_create
  - fs/quota/dquot.c:dquot_init
  - fs/ext4/extents_status.c:ext4_es_register_shrinker
```
**Symbols:**

```
ffffffff812082d0-ffffffff812082ff: register_shrinker (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int register_shrinker(struct shrinker *shrinker);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff8121af50)
Location: mm/vmscan.c:422
Inline: False
Direct callers:
  - mm/huge_memory.c:hugepage_init
  - mm/huge_memory.c:hugepage_init
  - mm/zsmalloc.c:zs_create_pool
  - fs/mbcache.c:mb_cache_create
  - fs/quota/dquot.c:dquot_init
  - fs/ext4/extents_status.c:ext4_es_register_shrinker
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
```
**Symbols:**

```
ffffffff8121af50-ffffffff8121af7f: register_shrinker (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int register_shrinker(struct shrinker *shrinker);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff8122abe0)
Location: mm/vmscan.c:434
Inline: False
Direct callers:
  - mm/huge_memory.c:hugepage_init
  - mm/huge_memory.c:hugepage_init
  - mm/zsmalloc.c:zs_create_pool
  - fs/mbcache.c:mb_cache_create
  - fs/quota/dquot.c:dquot_init
  - fs/ext4/extents_status.c:ext4_es_register_shrinker
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
```
**Symbols:**

```
ffffffff8122abe0-ffffffff8122ac0d: register_shrinker (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int register_shrinker(struct shrinker *shrinker);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81238ab0)
Location: mm/vmscan.c:432
Inline: False
Direct callers:
  - mm/huge_memory.c:hugepage_init
  - mm/huge_memory.c:hugepage_init
  - mm/zsmalloc.c:zs_create_pool
  - fs/mbcache.c:mb_cache_create
  - fs/quota/dquot.c:dquot_init
  - fs/ext4/extents_status.c:ext4_es_register_shrinker
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
```
**Symbols:**

```
ffffffff81238ab0-ffffffff81238add: register_shrinker (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int register_shrinker(struct shrinker *shrinker);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff812672f0)
Location: mm/vmscan.c:389
Inline: False
Direct callers:
  - kernel/rcu/tree.c:kfree_rcu_batch_init
  - mm/huge_memory.c:hugepage_init
  - mm/huge_memory.c:hugepage_init
  - mm/zsmalloc.c:zs_create_pool
  - fs/mbcache.c:mb_cache_create
  - fs/quota/dquot.c:dquot_init
  - fs/ext4/extents_status.c:ext4_es_register_shrinker
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_probe_backend_init
```
**Symbols:**

```
ffffffff812672f0-ffffffff81267378: register_shrinker (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int register_shrinker(struct shrinker *shrinker);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81271d40)
Location: mm/vmscan.c:382
Inline: False
Direct callers:
  - kernel/rcu/tree.c:kfree_rcu_batch_init
  - mm/huge_memory.c:hugepage_init
  - mm/huge_memory.c:hugepage_init
  - mm/zsmalloc.c:zs_create_pool
  - fs/mbcache.c:mb_cache_create
  - fs/quota/dquot.c:dquot_init
  - fs/ext4/extents_status.c:ext4_es_register_shrinker
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_probe_backend_init
```
**Symbols:**

```
ffffffff81271d40-ffffffff81271dc8: register_shrinker (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int register_shrinker(struct shrinker *shrinker);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81277070)
Location: mm/vmscan.c:613
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_init
  - mm/huge_memory.c:hugepage_init
  - mm/huge_memory.c:hugepage_init
  - mm/zsmalloc.c:zs_create_pool
  - fs/mbcache.c:mb_cache_create
  - fs/quota/dquot.c:dquot_init
  - fs/ext4/extents_status.c:ext4_es_register_shrinker
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_probe_backend_init
```
**Symbols:**

```
ffffffff81277070-ffffffff812770d0: register_shrinker (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int register_shrinker(struct shrinker *shrinker);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff812b49b0)
Location: mm/vmscan.c:659
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_init
  - mm/huge_memory.c:hugepage_init
  - mm/huge_memory.c:hugepage_init
  - mm/zsmalloc.c:zs_create_pool
  - fs/mbcache.c:mb_cache_create
  - fs/quota/dquot.c:dquot_init
  - fs/ext4/extents_status.c:ext4_es_register_shrinker
  - fs/jbd2/journal.c:journal_init_common
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_probe_backend_init
```
**Symbols:**

```
ffffffff812b49b0-ffffffff812b4a10: register_shrinker (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int register_shrinker(struct shrinker *shrinker);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81310970)
Location: mm/vmscan.c:656
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_init
  - mm/huge_memory.c:hugepage_init
  - mm/huge_memory.c:hugepage_init
  - mm/zsmalloc.c:zs_create_pool
  - fs/mbcache.c:mb_cache_create
  - fs/quota/dquot.c:dquot_init
  - fs/ext4/extents_status.c:ext4_es_register_shrinker
  - fs/jbd2/journal.c:journal_init_common
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_probe_backend_init
```
**Symbols:**

```
ffffffff81310970-ffffffff813109d8: register_shrinker (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int register_shrinker(struct shrinker *shrinker, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff8137e2e0)
Location: mm/vmscan.c:732
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_init
  - mm/huge_memory.c:hugepage_init
  - mm/huge_memory.c:hugepage_init
  - mm/zsmalloc.c:zs_create_pool
  - fs/mbcache.c:mb_cache_create
  - fs/quota/dquot.c:dquot_init
  - fs/ext4/extents_status.c:ext4_es_register_shrinker
  - fs/jbd2/journal.c:journal_init_common
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_probe_backend_init
```
**Symbols:**

```
ffffffff8137e2e0-ffffffff8137e348: register_shrinker (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int register_shrinker(struct shrinker *shrinker, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff813afd10)
Location: mm/vmscan.c:784
Inline: False
Direct callers:
  - kernel/rcu/tree.c:kfree_rcu_batch_init
  - mm/huge_memory.c:hugepage_init
  - mm/huge_memory.c:hugepage_init
  - mm/zsmalloc.c:zs_create_pool
  - fs/mbcache.c:mb_cache_create
  - fs/quota/dquot.c:dquot_init
  - fs/ext4/extents_status.c:ext4_es_register_shrinker
  - fs/jbd2/journal.c:journal_init_common
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_probe_backend_init
```
**Symbols:**

```
ffffffff813afd10-ffffffff813afd78: register_shrinker (STB_GLOBAL)
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
int register_shrinker(struct shrinker *shrinker);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffff8000102c9868)
Location: mm/vmscan.c:432
Inline: False
Direct callers:
  - mm/huge_memory.c:hugepage_init
  - mm/huge_memory.c:hugepage_init
  - mm/zsmalloc.c:zs_create_pool
  - fs/mbcache.c:mb_cache_create
  - fs/quota/dquot.c:dquot_init
  - fs/ext4/extents_status.c:ext4_es_register_shrinker
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
```
**Symbols:**

```
ffff8000102c9868-ffff8000102c98a8: register_shrinker (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int register_shrinker(struct shrinker *shrinker);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (c04f380c)
Location: mm/vmscan.c:432
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_create_pool
  - fs/mbcache.c:mb_cache_create
  - fs/quota/dquot.c:dquot_init
  - fs/ext4/extents_status.c:ext4_es_register_shrinker
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
```
**Symbols:**

```
c04f380c-c04f3840: register_shrinker (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int register_shrinker(struct shrinker *shrinker);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (c000000000385e80)
Location: mm/vmscan.c:432
Inline: False
Direct callers:
  - mm/huge_memory.c:hugepage_init
  - mm/huge_memory.c:hugepage_init
  - mm/zsmalloc.c:zs_create_pool
  - fs/mbcache.c:mb_cache_create
  - fs/quota/dquot.c:dquot_init
  - fs/ext4/extents_status.c:ext4_es_register_shrinker
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
```
**Symbols:**

```
c000000000385e80-c000000000385ed8: register_shrinker (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int register_shrinker(struct shrinker *shrinker);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffe0001e8c4a)
Location: mm/vmscan.c:432
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_create_pool
  - fs/mbcache.c:mb_cache_create
  - fs/quota/dquot.c:dquot_init
  - fs/ext4/extents_status.c:ext4_es_register_shrinker
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
```
**Symbols:**

```
ffffffe0001e8c4a-ffffffe0001e8c88: register_shrinker (STB_GLOBAL)
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
int register_shrinker(struct shrinker *shrinker);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81231100)
Location: mm/vmscan.c:432
Inline: False
Direct callers:
  - mm/huge_memory.c:hugepage_init
  - mm/huge_memory.c:hugepage_init
  - mm/zsmalloc.c:zs_create_pool
  - fs/mbcache.c:mb_cache_create
  - fs/quota/dquot.c:dquot_init
  - fs/ext4/extents_status.c:ext4_es_register_shrinker
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
```
**Symbols:**

```
ffffffff81231100-ffffffff8123112d: register_shrinker (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int register_shrinker(struct shrinker *shrinker);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff812241c0)
Location: mm/vmscan.c:432
Inline: False
Direct callers:
  - mm/huge_memory.c:hugepage_init
  - mm/huge_memory.c:hugepage_init
  - mm/zsmalloc.c:zs_create_pool
  - fs/mbcache.c:mb_cache_create
  - fs/quota/dquot.c:dquot_init
  - fs/ext4/extents_status.c:ext4_es_register_shrinker
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
```
**Symbols:**

```
ffffffff812241c0-ffffffff812241ed: register_shrinker (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int register_shrinker(struct shrinker *shrinker);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff8122eea0)
Location: mm/vmscan.c:432
Inline: False
Direct callers:
  - mm/huge_memory.c:hugepage_init
  - mm/huge_memory.c:hugepage_init
  - mm/zsmalloc.c:zs_create_pool
  - fs/mbcache.c:mb_cache_create
  - fs/quota/dquot.c:dquot_init
  - fs/ext4/extents_status.c:ext4_es_register_shrinker
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
```
**Symbols:**

```
ffffffff8122eea0-ffffffff8122eecd: register_shrinker (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int register_shrinker(struct shrinker *shrinker);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff8123e2b0)
Location: mm/vmscan.c:432
Inline: False
Direct callers:
  - mm/huge_memory.c:hugepage_init
  - mm/huge_memory.c:hugepage_init
  - mm/zsmalloc.c:zs_create_pool
  - fs/mbcache.c:mb_cache_create
  - fs/quota/dquot.c:dquot_init
  - fs/ext4/extents_status.c:ext4_es_register_shrinker
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
```
**Symbols:**

```
ffffffff8123e2b0-ffffffff8123e2dd: register_shrinker (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const char *fmt</code>
</li>
<li>
<b>Param added. </b>
<code>void (anon)</code>
</li>
</ul>
</details>
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
