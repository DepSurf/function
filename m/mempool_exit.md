# Function: <code>mempool_exit</code>

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
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void mempool_exit(mempool_t *pool);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mempool.c (ffffffff811f0f80)
Location: mm/mempool.c:151
Inline: True
Direct callers:
  - mm/mempool.c:mempool_destroy
  - block/bio.c:bioset_exit
  - block/bio.c:bioset_exit
  - block/bio-integrity.c:bioset_integrity_free
  - block/bio-integrity.c:bioset_integrity_free
  - drivers/md/dm-io.c:dm_io_client_destroy
  - drivers/md/dm-io.c:dm_io_client_create
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_destroy
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_create
```
**Symbols:**

```
ffffffff811f0f80-ffffffff811f0fe7: mempool_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void mempool_exit(mempool_t *pool);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mempool.c (ffffffff81202de0)
Location: mm/mempool.c:151
Inline: True
Direct callers:
  - mm/mempool.c:mempool_destroy
  - block/bio.c:bioset_exit
  - block/bio.c:bioset_exit
  - block/bio-integrity.c:bioset_integrity_free
  - block/bio-integrity.c:bioset_integrity_free
  - drivers/md/dm-io.c:dm_io_client_destroy
  - drivers/md/dm-io.c:dm_io_client_create
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_destroy
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_create
```
**Symbols:**

```
ffffffff81202de0-ffffffff81202e47: mempool_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void mempool_exit(mempool_t *pool);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mempool.c (ffffffff8121a1e0)
Location: mm/mempool.c:151
Inline: True
Direct callers:
  - mm/mempool.c:mempool_destroy
  - block/bio.c:bioset_exit
  - block/bio.c:bioset_exit
  - block/bio-integrity.c:bioset_integrity_free
  - block/bio-integrity.c:bioset_integrity_free
  - drivers/md/dm-io.c:dm_io_client_destroy
  - drivers/md/dm-io.c:dm_io_client_create
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_destroy
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_create
```
**Symbols:**

```
ffffffff8121a1e0-ffffffff8121a236: mempool_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void mempool_exit(mempool_t *pool);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mempool.c (ffffffff81227b50)
Location: mm/mempool.c:151
Inline: True
Direct callers:
  - mm/mempool.c:mempool_destroy
  - block/bio.c:bioset_exit
  - block/bio.c:bioset_exit
  - block/bio-integrity.c:bioset_integrity_free
  - block/bio-integrity.c:bioset_integrity_free
  - drivers/md/dm-io.c:dm_io_client_destroy
  - drivers/md/dm-io.c:dm_io_client_create
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_destroy
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_create
```
**Symbols:**

```
ffffffff81227b50-ffffffff81227ba6: mempool_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void mempool_exit(mempool_t *pool);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempool.c (ffffffff812544c0)
Location: mm/mempool.c:151
Inline: False
Direct callers:
  - mm/mempool.c:mempool_destroy
  - block/bio.c:bioset_init
  - block/bio.c:bioset_init
  - block/bio-integrity.c:bioset_integrity_free
  - block/bio-integrity.c:bioset_integrity_free
  - drivers/md/md.c:md_free
  - drivers/md/dm-io.c:dm_io_client_destroy
  - drivers/md/dm-io.c:dm_io_client_create
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_destroy
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_create
```
**Symbols:**

```
ffffffff812544c0-ffffffff81254516: mempool_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void mempool_exit(mempool_t *pool);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempool.c (ffffffff8125f0b0)
Location: mm/mempool.c:149
Inline: False
Direct callers:
  - mm/mempool.c:mempool_destroy
  - block/bio.c:bioset_init
  - block/bio.c:bioset_init
  - block/bio-integrity.c:bioset_integrity_free
  - block/bio-integrity.c:bioset_integrity_free
  - drivers/md/md.c:md_free
  - drivers/md/dm-io.c:dm_io_client_destroy
  - drivers/md/dm-io.c:dm_io_client_create
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_destroy
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_create
```
**Symbols:**

```
ffffffff8125f0b0-ffffffff8125f128: mempool_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void mempool_exit(mempool_t *pool);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempool.c (ffffffff81263c20)
Location: mm/mempool.c:149
Inline: False
Direct callers:
  - mm/mempool.c:mempool_destroy
  - block/bio.c:bioset_exit
  - block/bio.c:bioset_exit
  - block/bio-integrity.c:bioset_integrity_free
  - block/bio-integrity.c:bioset_integrity_free
  - drivers/md/dm-io.c:dm_io_client_destroy
  - drivers/md/dm-io.c:dm_io_client_create
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_destroy
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_create
```
**Symbols:**

```
ffffffff81263c20-ffffffff81263c98: mempool_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void mempool_exit(mempool_t *pool);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempool.c (ffffffff812a0200)
Location: mm/mempool.c:151
Inline: False
Direct callers:
  - mm/mempool.c:mempool_destroy
  - block/bio.c:bioset_exit
  - block/bio.c:bioset_exit
  - block/bio-integrity.c:bioset_integrity_free
  - block/bio-integrity.c:bioset_integrity_free
  - drivers/md/dm-io.c:dm_io_client_destroy
  - drivers/md/dm-io.c:dm_io_client_create
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_destroy
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_create
```
**Symbols:**

```
ffffffff812a0200-ffffffff812a0278: mempool_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void mempool_exit(mempool_t *pool);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempool.c (ffffffff812f77e0)
Location: mm/mempool.c:150
Inline: False
Direct callers:
  - mm/mempool.c:mempool_init_node
  - mm/mempool.c:mempool_destroy
  - fs/notify/fanotify/fanotify.c:fanotify_free_group_priv
  - block/bio.c:bioset_exit
  - block/bio.c:bioset_exit
  - block/bio-integrity.c:bioset_integrity_free
  - block/bio-integrity.c:bioset_integrity_free
  - block/bio-integrity.c:bioset_integrity_create
  - drivers/md/dm-io.c:dm_io_client_destroy
  - drivers/md/dm-io.c:dm_io_client_create
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_destroy
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_create
```
**Symbols:**

```
ffffffff812f77e0-ffffffff812f7866: mempool_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void mempool_exit(mempool_t *pool);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempool.c (ffffffff81361140)
Location: mm/mempool.c:156
Inline: False
Direct callers:
  - mm/mempool.c:mempool_init_node
  - mm/mempool.c:mempool_destroy
  - fs/notify/fanotify/fanotify.c:fanotify_free_group_priv
  - block/bio.c:bioset_exit
  - block/bio.c:bioset_exit
  - block/bio-integrity.c:bioset_integrity_free
  - block/bio-integrity.c:bioset_integrity_free
  - block/bio-integrity.c:bioset_integrity_create
  - drivers/md/dm-io.c:dm_io_client_destroy
  - drivers/md/dm-io.c:dm_io_client_create
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_destroy
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_create
```
**Symbols:**

```
ffffffff81361140-ffffffff813611db: mempool_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void mempool_exit(mempool_t *pool);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempool.c (ffffffff81393500)
Location: mm/mempool.c:156
Inline: False
Direct callers:
  - mm/mempool.c:mempool_init_node
  - mm/mempool.c:mempool_destroy
  - fs/notify/fanotify/fanotify.c:fanotify_free_group_priv
  - block/bio.c:bioset_exit
  - block/bio.c:bioset_exit
  - block/bio-integrity.c:bioset_integrity_free
  - block/bio-integrity.c:bioset_integrity_free
  - block/bio-integrity.c:bioset_integrity_create
  - drivers/md/dm-io.c:dm_io_client_destroy
  - drivers/md/dm-io.c:dm_io_client_create
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_destroy
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_create
```
**Symbols:**

```
ffffffff81393500-ffffffff8139359b: mempool_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void mempool_exit(mempool_t *pool);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempool.c (ffffffff813bd1b0)
Location: mm/mempool.c:166
Inline: False
Direct callers:
  - mm/mempool.c:mempool_init_node
  - mm/mempool.c:mempool_destroy
  - fs/notify/fanotify/fanotify.c:fanotify_free_group_priv
  - block/bio.c:bioset_exit
  - block/bio.c:bioset_exit
  - block/bio-integrity.c:bioset_integrity_free
  - block/bio-integrity.c:bioset_integrity_free
  - block/bio-integrity.c:bioset_integrity_create
  - drivers/md/dm-io.c:dm_io_client_destroy
  - drivers/md/dm-io.c:dm_io_client_create
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_destroy
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_create
```
**Symbols:**

```
ffffffff813bd1b0-ffffffff813bd24b: mempool_exit (STB_GLOBAL)
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
void mempool_exit(mempool_t *pool);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mempool.c (ffff8000102b5070)
Location: mm/mempool.c:151
Inline: True
Direct callers:
  - mm/mempool.c:mempool_destroy
  - block/bio.c:bioset_exit
  - block/bio.c:bioset_exit
  - block/bio-integrity.c:bioset_integrity_free
  - block/bio-integrity.c:bioset_integrity_free
  - drivers/md/dm-io.c:dm_io_client_destroy
  - drivers/md/dm-io.c:dm_io_client_create
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_destroy
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_create
```
**Symbols:**

```
ffff8000102b5070-ffff8000102b50d8: mempool_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void mempool_exit(mempool_t *pool);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mempool.c (c04e2450)
Location: mm/mempool.c:151
Inline: True
Direct callers:
  - mm/mempool.c:mempool_destroy
  - block/bio.c:bioset_exit
  - block/bio.c:bioset_exit
  - block/bio-integrity.c:bioset_integrity_free
  - block/bio-integrity.c:bioset_integrity_free
  - drivers/md/dm-io.c:dm_io_client_destroy
  - drivers/md/dm-io.c:dm_io_client_create
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_destroy
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_create
```
**Symbols:**

```
c04e2450-c04e24c0: mempool_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void mempool_exit(mempool_t *pool);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempool.c (c00000000036c140)
Location: mm/mempool.c:151
Inline: False
Direct callers:
  - mm/mempool.c:mempool_destroy
  - block/bio.c:bioset_exit
  - block/bio.c:bioset_exit
  - block/bio-integrity.c:bioset_integrity_free
  - block/bio-integrity.c:bioset_integrity_free
  - drivers/md/dm-io.c:dm_io_client_destroy
  - drivers/md/dm-io.c:dm_io_client_create
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_destroy
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_create
```
**Symbols:**

```
c00000000036c140-c00000000036c1d0: mempool_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void mempool_exit(mempool_t *pool);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mempool.c (ffffffe0001da0f6)
Location: mm/mempool.c:151
Inline: True
Direct callers:
  - mm/mempool.c:mempool_destroy
  - block/bio.c:bioset_exit
  - block/bio.c:bioset_exit
  - block/bio-integrity.c:bioset_integrity_free
  - block/bio-integrity.c:bioset_integrity_free
  - drivers/md/dm-io.c:dm_io_client_destroy
  - drivers/md/dm-io.c:dm_io_client_create
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_destroy
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_create
```
**Symbols:**

```
ffffffe0001da0f6-ffffffe0001da152: mempool_exit (STB_GLOBAL)
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
void mempool_exit(mempool_t *pool);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mempool.c (ffffffff812201a0)
Location: mm/mempool.c:151
Inline: True
Direct callers:
  - mm/mempool.c:mempool_destroy
  - block/bio.c:bioset_exit
  - block/bio.c:bioset_exit
  - block/bio-integrity.c:bioset_integrity_free
  - block/bio-integrity.c:bioset_integrity_free
  - drivers/md/dm-io.c:dm_io_client_destroy
  - drivers/md/dm-io.c:dm_io_client_create
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_destroy
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_create
```
**Symbols:**

```
ffffffff812201a0-ffffffff812201f6: mempool_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void mempool_exit(mempool_t *pool);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mempool.c (ffffffff81213350)
Location: mm/mempool.c:151
Inline: True
Direct callers:
  - mm/mempool.c:mempool_destroy
  - block/bio.c:bioset_exit
  - block/bio.c:bioset_exit
  - block/bio-integrity.c:bioset_integrity_free
  - block/bio-integrity.c:bioset_integrity_free
  - drivers/md/dm-io.c:dm_io_client_destroy
  - drivers/md/dm-io.c:dm_io_client_create
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_destroy
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_create
```
**Symbols:**

```
ffffffff81213350-ffffffff812133a6: mempool_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void mempool_exit(mempool_t *pool);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mempool.c (ffffffff8121df40)
Location: mm/mempool.c:151
Inline: True
Direct callers:
  - mm/mempool.c:mempool_destroy
  - block/bio.c:bioset_exit
  - block/bio.c:bioset_exit
  - block/bio-integrity.c:bioset_integrity_free
  - block/bio-integrity.c:bioset_integrity_free
  - drivers/md/dm-io.c:dm_io_client_destroy
  - drivers/md/dm-io.c:dm_io_client_create
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_destroy
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_create
```
**Symbols:**

```
ffffffff8121df40-ffffffff8121df96: mempool_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void mempool_exit(mempool_t *pool);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mempool.c (ffffffff8122cfb0)
Location: mm/mempool.c:151
Inline: True
Direct callers:
  - mm/mempool.c:mempool_destroy
  - block/bio.c:bioset_exit
  - block/bio.c:bioset_exit
  - block/bio-integrity.c:bioset_integrity_free
  - block/bio-integrity.c:bioset_integrity_free
  - drivers/md/dm-io.c:dm_io_client_destroy
  - drivers/md/dm-io.c:dm_io_client_create
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_destroy
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_create
```
**Symbols:**

```
ffffffff8122cfb0-ffffffff8122d006: mempool_exit (STB_GLOBAL)
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
