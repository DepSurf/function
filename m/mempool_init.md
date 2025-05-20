# Function: <code>mempool_init</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int mempool_init(mempool_t *pool, int min_nr, mempool_alloc_t *alloc_fn, mempool_free_t *free_fn, void *pool_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempool.c (ffffffff811f1100)
Location: mm/mempool.c:225
Inline: False
Direct callers:
  - block/bio.c:bioset_init
  - block/bio.c:bioset_init
  - block/bounce.c:init_emergency_isa_pool
  - drivers/md/dm-io.c:dm_io_client_create
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_create
```
**Symbols:**

```
ffffffff811f1100-ffffffff811f1118: mempool_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int mempool_init(mempool_t *pool, int min_nr, mempool_alloc_t *alloc_fn, mempool_free_t *free_fn, void *pool_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempool.c (ffffffff81202f60)
Location: mm/mempool.c:226
Inline: False
Direct callers:
  - block/bio.c:bioset_init
  - block/bio.c:bioset_init
  - block/bounce.c:init_emergency_isa_pool
  - drivers/md/dm-io.c:dm_io_client_create
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_create
```
**Symbols:**

```
ffffffff81202f60-ffffffff81202f78: mempool_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int mempool_init(mempool_t *pool, int min_nr, mempool_alloc_t *alloc_fn, mempool_free_t *free_fn, void *pool_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempool.c (ffffffff8121a360)
Location: mm/mempool.c:228
Inline: False
Direct callers:
  - block/bio.c:bioset_init
  - block/bio.c:bioset_init
  - block/bounce.c:init_emergency_isa_pool
  - drivers/md/dm-io.c:dm_io_client_create
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_create
```
**Symbols:**

```
ffffffff8121a360-ffffffff8121a378: mempool_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int mempool_init(mempool_t *pool, int min_nr, mempool_alloc_t *alloc_fn, mempool_free_t *free_fn, void *pool_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempool.c (ffffffff81227cd0)
Location: mm/mempool.c:228
Inline: False
Direct callers:
  - block/bio.c:bioset_init
  - block/bio.c:bioset_init
  - block/bounce.c:init_emergency_isa_pool
  - drivers/md/dm-io.c:dm_io_client_create
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_create
```
**Symbols:**

```
ffffffff81227cd0-ffffffff81227ce8: mempool_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int mempool_init(mempool_t *pool, int min_nr, mempool_alloc_t *alloc_fn, mempool_free_t *free_fn, void *pool_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempool.c (ffffffff81254640)
Location: mm/mempool.c:228
Inline: False
Direct callers:
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
  - block/bio.c:bioset_init
  - block/bio.c:bioset_init
  - block/bounce.c:init_emergency_isa_pool
  - drivers/md/md.c:md_alloc
  - drivers/md/dm-io.c:dm_io_client_create
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_create
```
**Symbols:**

```
ffffffff81254640-ffffffff81254658: mempool_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int mempool_init(mempool_t *pool, int min_nr, mempool_alloc_t *alloc_fn, mempool_free_t *free_fn, void *pool_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempool.c (ffffffff8125f250)
Location: mm/mempool.c:226
Inline: False
Direct callers:
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
  - block/bio.c:bioset_init
  - block/bio.c:bioset_init
  - block/bounce.c:init_emergency_isa_pool
  - drivers/md/md.c:md_alloc
  - drivers/md/dm-io.c:dm_io_client_create
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_create
```
**Symbols:**

```
ffffffff8125f250-ffffffff8125f268: mempool_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int mempool_init(mempool_t *pool, int min_nr, mempool_alloc_t *alloc_fn, mempool_free_t *free_fn, void *pool_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempool.c (ffffffff81263db0)
Location: mm/mempool.c:226
Inline: False
Direct callers:
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
  - block/bio.c:bioset_init
  - block/bio.c:bioset_init
  - drivers/md/dm-io.c:dm_io_client_create
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_create
```
**Symbols:**

```
ffffffff81263db0-ffffffff81263dc8: mempool_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int mempool_init(mempool_t *pool, int min_nr, mempool_alloc_t *alloc_fn, mempool_free_t *free_fn, void *pool_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempool.c (ffffffff812a0390)
Location: mm/mempool.c:228
Inline: False
Direct callers:
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
  - block/bio.c:bioset_init
  - block/bio.c:bioset_init
  - drivers/md/dm-io.c:dm_io_client_create
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_create
```
**Symbols:**

```
ffffffff812a0390-ffffffff812a03a8: mempool_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int mempool_init(mempool_t *pool, int min_nr, mempool_alloc_t *alloc_fn, mempool_free_t *free_fn, void *pool_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempool.c (ffffffff812f79b0)
Location: mm/mempool.c:227
Inline: False
Direct callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_mark
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
  - block/bio.c:bioset_init
  - block/bio.c:bioset_init
  - block/bio-integrity.c:bioset_integrity_create
  - drivers/md/dm-io.c:dm_io_client_create
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_create
```
**Symbols:**

```
ffffffff812f79b0-ffffffff812f79da: mempool_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int mempool_init(mempool_t *pool, int min_nr, mempool_alloc_t *alloc_fn, mempool_free_t *free_fn, void *pool_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempool.c (ffffffff81361340)
Location: mm/mempool.c:233
Inline: False
Direct callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_mark
  - fs/verity/hash_algs.c:fsverity_get_hash_alg
  - block/bio.c:bioset_init
  - block/bio.c:bioset_init
  - block/bio-integrity.c:bioset_integrity_create
  - drivers/md/dm-io.c:dm_io_client_create
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_create
```
**Symbols:**

```
ffffffff81361340-ffffffff8136136a: mempool_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int mempool_init(mempool_t *pool, int min_nr, mempool_alloc_t *alloc_fn, mempool_free_t *free_fn, void *pool_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempool.c (ffffffff81393700)
Location: mm/mempool.c:233
Inline: False
Direct callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_mark
  - block/bio.c:bioset_init
  - block/bio.c:bioset_init
  - block/bio-integrity.c:bioset_integrity_create
  - drivers/md/dm-io.c:dm_io_client_create
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_create
```
**Symbols:**

```
ffffffff81393700-ffffffff8139372a: mempool_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int mempool_init(mempool_t *pool, int min_nr, mempool_alloc_t *alloc_fn, mempool_free_t *free_fn, void *pool_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempool.c (ffffffff813bd3b0)
Location: mm/mempool.c:243
Inline: False
Direct callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_add_mark
  - block/bio.c:bioset_init
  - block/bio.c:bioset_init
  - block/bio-integrity.c:bioset_integrity_create
  - drivers/md/dm-io.c:dm_io_client_create
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_create
```
**Symbols:**

```
ffffffff813bd3b0-ffffffff813bd3da: mempool_init (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int mempool_init(mempool_t *pool, int min_nr, mempool_alloc_t *alloc_fn, mempool_free_t *free_fn, void *pool_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempool.c (ffff8000102b5290)
Location: mm/mempool.c:228
Inline: False
Direct callers:
  - block/bio.c:bioset_init
  - block/bio.c:bioset_init
  - drivers/md/dm-io.c:dm_io_client_create
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_create
```
**Symbols:**

```
ffff8000102b5290-ffff8000102b52f4: mempool_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int mempool_init(mempool_t *pool, int min_nr, mempool_alloc_t *alloc_fn, mempool_free_t *free_fn, void *pool_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempool.c (c04e25e4)
Location: mm/mempool.c:228
Inline: False
Direct callers:
  - block/bio.c:bioset_init
  - block/bio.c:bioset_init
  - block/bounce.c:init_emergency_isa_pool
  - block/bounce.c:init_emergency_pool
  - drivers/md/dm-io.c:dm_io_client_create
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_create
```
**Symbols:**

```
c04e25e4-c04e261c: mempool_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int mempool_init(mempool_t *pool, int min_nr, mempool_alloc_t *alloc_fn, mempool_free_t *free_fn, void *pool_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempool.c (c00000000036c7b0)
Location: mm/mempool.c:228
Inline: False
Direct callers:
  - block/bio.c:bioset_init
  - block/bio.c:bioset_init
  - drivers/md/dm-io.c:dm_io_client_create
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_create
```
**Symbols:**

```
c00000000036c7b0-c00000000036c7cc: mempool_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int mempool_init(mempool_t *pool, int min_nr, mempool_alloc_t *alloc_fn, mempool_free_t *free_fn, void *pool_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempool.c (ffffffe0001da2ee)
Location: mm/mempool.c:228
Inline: False
Direct callers:
  - block/bio.c:bioset_init
  - block/bio.c:bioset_init
  - drivers/md/dm-io.c:dm_io_client_create
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_create
```
**Symbols:**

```
ffffffe0001da2ee-ffffffe0001da340: mempool_init (STB_GLOBAL)
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
int mempool_init(mempool_t *pool, int min_nr, mempool_alloc_t *alloc_fn, mempool_free_t *free_fn, void *pool_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempool.c (ffffffff81220320)
Location: mm/mempool.c:228
Inline: False
Direct callers:
  - block/bio.c:bioset_init
  - block/bio.c:bioset_init
  - block/bounce.c:init_emergency_isa_pool
  - drivers/md/dm-io.c:dm_io_client_create
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_create
```
**Symbols:**

```
ffffffff81220320-ffffffff81220338: mempool_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int mempool_init(mempool_t *pool, int min_nr, mempool_alloc_t *alloc_fn, mempool_free_t *free_fn, void *pool_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempool.c (ffffffff812134d0)
Location: mm/mempool.c:228
Inline: False
Direct callers:
  - block/bio.c:bioset_init
  - block/bio.c:bioset_init
  - block/bounce.c:init_emergency_isa_pool
  - drivers/md/dm-io.c:dm_io_client_create
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_create
```
**Symbols:**

```
ffffffff812134d0-ffffffff812134e8: mempool_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int mempool_init(mempool_t *pool, int min_nr, mempool_alloc_t *alloc_fn, mempool_free_t *free_fn, void *pool_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempool.c (ffffffff8121e0c0)
Location: mm/mempool.c:228
Inline: False
Direct callers:
  - block/bio.c:bioset_init
  - block/bio.c:bioset_init
  - block/bounce.c:init_emergency_isa_pool
  - drivers/md/dm-io.c:dm_io_client_create
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_create
```
**Symbols:**

```
ffffffff8121e0c0-ffffffff8121e0d8: mempool_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int mempool_init(mempool_t *pool, int min_nr, mempool_alloc_t *alloc_fn, mempool_free_t *free_fn, void *pool_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempool.c (ffffffff8122d130)
Location: mm/mempool.c:228
Inline: False
Direct callers:
  - block/bio.c:bioset_init
  - block/bio.c:bioset_init
  - block/bounce.c:init_emergency_isa_pool
  - drivers/md/dm-io.c:dm_io_client_create
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_create
```
**Symbols:**

```
ffffffff8122d130-ffffffff8122d148: mempool_init (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
