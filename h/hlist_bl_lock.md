# Function: <code>hlist_bl_lock</code>

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
In fs/dcache.c (ffffffff81223480)
Location: include/linux/list_bl.h:119
Inline: True
Inline callers:
  - fs/dcache.c:__d_drop
  - fs/dcache.c:__d_obtain_alias
```
```
In fs/mbcache.c (ffffffff8126cbdc)
Location: include/linux/list_bl.h:119
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_destroy
  - fs/mbcache.c:mb_cache_destroy
  - fs/mbcache.c:mb_cache_entry_find_next
  - fs/mbcache.c:mb_cache_entry_find_first
  - fs/mbcache.c:mb_cache_entry_free
  - fs/mbcache.c:mb_cache_entry_free
  - fs/mbcache.c:mb_cache_entry_insert
  - fs/mbcache.c:mb_cache_entry_insert
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:mb_cache_shrink_scan
  - fs/mbcache.c:mb_cache_shrink_scan
  - fs/mbcache.c:mb_cache_entry_alloc
  - fs/mbcache.c:mb_cache_entry_alloc
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_shrink
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
In fs/dcache.c (ffffffff8124bb63)
Location: include/linux/list_bl.h:119
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_obtain_alias
  - fs/dcache.c:__d_drop
```
```
In fs/mbcache.c (ffffffff81298a78)
Location: include/linux/list_bl.h:119
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete_block
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:__entry_find
  - fs/mbcache.c:mb_cache_entry_create
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
In fs/dcache.c (ffffffff8125eb43)
Location: include/linux/list_bl.h:119
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_obtain_alias
  - fs/dcache.c:__d_drop
```
```
In fs/mbcache.c (ffffffff812ad4f6)
Location: include/linux/list_bl.h:119
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete_block
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:__entry_find
  - fs/mbcache.c:mb_cache_entry_create
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
In fs/dcache.c (ffffffff8126c513)
Location: include/linux/list_bl.h:119
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_drop
```
```
In fs/mbcache.c (ffffffff812ba99e)
Location: include/linux/list_bl.h:119
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:__entry_find
  - fs/mbcache.c:mb_cache_entry_create
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
In fs/dcache.c (ffffffff8128e6a3)
Location: include/linux/list_bl.h:120
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_rehash
  - fs/dcache.c:___d_drop
```
```
In fs/mbcache.c (ffffffff812de27e)
Location: include/linux/list_bl.h:120
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:__entry_find
  - fs/mbcache.c:mb_cache_entry_create
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
In fs/dcache.c (ffffffff812b4915)
Location: include/linux/list_bl.h:120
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_rehash
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:___d_drop
```
```
In fs/mbcache.c (ffffffff8130a4be)
Location: include/linux/list_bl.h:120
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:__entry_find
  - fs/mbcache.c:mb_cache_entry_create
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
In fs/dcache.c (ffffffff812c9b95)
Location: include/linux/list_bl.h:120
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_rehash
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:___d_drop
```
```
In fs/mbcache.c (ffffffff8131fc9e)
Location: include/linux/list_bl.h:120
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:__entry_find
  - fs/mbcache.c:mb_cache_entry_create
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
In fs/dcache.c (ffffffff812e65a5)
Location: include/linux/list_bl.h:146
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_rehash
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:___d_drop
```
```
In fs/mbcache.c (ffffffff8134750d)
Location: include/linux/list_bl.h:146
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:__entry_find
  - fs/mbcache.c:mb_cache_entry_create
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
In fs/dcache.c (ffffffff812f8105)
Location: include/linux/list_bl.h:146
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_rehash
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:___d_drop
```
```
In fs/mbcache.c (ffffffff8135f67d)
Location: include/linux/list_bl.h:146
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:__entry_find
  - fs/mbcache.c:mb_cache_entry_create
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
In fs/dcache.c (ffffffff81330e65)
Location: include/linux/list_bl.h:146
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_rehash
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:___d_drop
```
```
In fs/mbcache.c (ffffffff813a5259)
Location: include/linux/list_bl.h:146
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:mb_cache_entry_create
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
In fs/dcache.c (ffffffff8133c816)
Location: include/linux/list_bl.h:146
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_rehash
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:___d_drop
```
```
In fs/mbcache.c (ffffffff813b5fb9)
Location: include/linux/list_bl.h:146
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:mb_cache_entry_create
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
In fs/dcache.c (ffffffff81342c9b)
Location: include/linux/list_bl.h:146
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_rehash
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:___d_drop
```
```
In fs/mbcache.c (ffffffff813bd109)
Location: include/linux/list_bl.h:146
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:mb_cache_entry_create
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
In fs/dcache.c (ffffffff813906db)
Location: include/linux/list_bl.h:146
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_rehash
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:___d_drop
```
```
In fs/mbcache.c (ffffffff8140cea7)
Location: include/linux/list_bl.h:146
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:mb_cache_entry_create
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
In fs/dcache.c (ffffffff81413192)
Location: include/linux/list_bl.h:146
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_rehash
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:___d_drop
```
```
In fs/mbcache.c (ffffffff81481cf2)
Location: include/linux/list_bl.h:146
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete_or_get
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:mb_cache_entry_create
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
In fs/dcache.c (ffffffff8149e44c)
Location: include/linux/list_bl.h:146
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_unhash
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_rehash
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:___d_drop
```
```
In fs/mbcache.c (ffffffff81514f5b)
Location: include/linux/list_bl.h:146
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:__entry_find
  - fs/mbcache.c:__mb_cache_entry_free
  - fs/mbcache.c:mb_cache_entry_create
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
In fs/dcache.c (ffffffff814d376c)
Location: include/linux/list_bl.h:146
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_unhash
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_rehash
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:___d_drop
```
```
In fs/mbcache.c (ffffffff8154c95b)
Location: include/linux/list_bl.h:146
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:__entry_find
  - fs/mbcache.c:__mb_cache_entry_free
  - fs/mbcache.c:mb_cache_entry_create
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
In fs/dcache.c (ffffffff81505eec)
Location: include/linux/list_bl.h:146
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_unhash
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_rehash
  - fs/dcache.c:__d_obtain_alias
  - fs/dcache.c:___d_drop
```
```
In fs/mbcache.c (ffffffff8158278b)
Location: include/linux/list_bl.h:146
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:__entry_find
  - fs/mbcache.c:__mb_cache_entry_free
  - fs/mbcache.c:mb_cache_entry_create
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
In fs/dcache.c (ffff8000103a56bc)
Location: include/linux/list_bl.h:146
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_rehash
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:___d_drop
```
```
In fs/mbcache.c (ffff8000104252d8)
Location: include/linux/list_bl.h:146
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:__entry_find
  - fs/mbcache.c:mb_cache_entry_create
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
In fs/dcache.c (c0588eb8)
Location: include/linux/list_bl.h:146
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_rehash
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:___d_drop
```
```
In fs/mbcache.c (c05ede60)
Location: include/linux/list_bl.h:146
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:__entry_find
  - fs/mbcache.c:mb_cache_entry_create
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
In fs/dcache.c (c0000000004a1128)
Location: include/linux/list_bl.h:146
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_rehash
  - fs/dcache.c:___d_drop
```
```
In fs/mbcache.c (c000000000534554)
Location: include/linux/list_bl.h:146
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:__entry_find
  - fs/mbcache.c:mb_cache_entry_create
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
In fs/dcache.c (ffffffe00026c288)
Location: include/linux/list_bl.h:146
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_rehash
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:___d_drop
```
```
In fs/mbcache.c (ffffffe0002c43e4)
Location: include/linux/list_bl.h:146
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:__entry_find
  - fs/mbcache.c:mb_cache_entry_create
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
In fs/dcache.c (ffffffff812f06e5)
Location: include/linux/list_bl.h:146
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_rehash
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:___d_drop
```
```
In fs/mbcache.c (ffffffff81357c5d)
Location: include/linux/list_bl.h:146
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:__entry_find
  - fs/mbcache.c:mb_cache_entry_create
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
In fs/dcache.c (ffffffff812e1315)
Location: include/linux/list_bl.h:146
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_rehash
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:___d_drop
```
```
In fs/mbcache.c (ffffffff8134890d)
Location: include/linux/list_bl.h:146
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:__entry_find
  - fs/mbcache.c:mb_cache_entry_create
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
In fs/dcache.c (ffffffff812ee4f5)
Location: include/linux/list_bl.h:146
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_rehash
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:___d_drop
```
```
In fs/mbcache.c (ffffffff8135572d)
Location: include/linux/list_bl.h:146
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:__entry_find
  - fs/mbcache.c:mb_cache_entry_create
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
In fs/dcache.c (ffffffff813004b5)
Location: include/linux/list_bl.h:146
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_rehash
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:___d_drop
```
```
In fs/mbcache.c (ffffffff81368d21)
Location: include/linux/list_bl.h:146
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:__entry_find
  - fs/mbcache.c:mb_cache_entry_create
```
</details>
</li>
</ul>

## Differences
