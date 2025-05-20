# Function: <code>__clear_bit_unlock</code>

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
In mm/slub.c (ffffffff811e9d24)
Location: arch/x86/include/asm/bitops.h:154
Inline: True
Inline callers:
  - mm/slub.c:free_debug_processing
  - mm/slub.c:free_debug_processing
  - mm/slub.c:validate_store
  - mm/slub.c:validate_store
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:__kmem_cache_create
```
```
In fs/dcache.c (ffffffff812234b0)
Location: arch/x86/include/asm/bitops.h:154
Inline: True
Inline callers:
  - fs/dcache.c:__d_drop
  - fs/dcache.c:__d_obtain_alias
```
```
In fs/mbcache.c (ffffffff8126c960)
Location: arch/x86/include/asm/bitops.h:154
Inline: True
Inline callers:
  - fs/mbcache.c:__mb_cache_entry_find
  - fs/mbcache.c:__mb_cache_entry_find
  - fs/mbcache.c:mb_cache_destroy
  - fs/mbcache.c:mb_cache_destroy
  - fs/mbcache.c:mb_cache_entry_find_first
  - fs/mbcache.c:mb_cache_entry_free
  - fs/mbcache.c:mb_cache_entry_free
  - fs/mbcache.c:mb_cache_entry_insert
  - fs/mbcache.c:mb_cache_entry_insert
  - fs/mbcache.c:mb_cache_entry_insert
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:mb_cache_shrink_scan
  - fs/mbcache.c:mb_cache_shrink_scan
  - fs/mbcache.c:mb_cache_shrink_scan
  - fs/mbcache.c:mb_cache_shrink_scan
  - fs/mbcache.c:mb_cache_entry_alloc
  - fs/mbcache.c:mb_cache_entry_alloc
  - fs/mbcache.c:mb_cache_entry_alloc
  - fs/mbcache.c:mb_cache_entry_alloc
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_shrink
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
In mm/slub.c (ffffffff8120c6ea)
Location: arch/x86/include/asm/bitops.h:154
Inline: True
Inline callers:
  - mm/slub.c:validate_store
  - mm/slub.c:validate_store
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:free_debug_processing
```
```
In fs/dcache.c (ffffffff8124bbc2)
Location: arch/x86/include/asm/bitops.h:154
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_obtain_alias
  - fs/dcache.c:__d_drop
```
```
In fs/mbcache.c (ffffffff81298abd)
Location: arch/x86/include/asm/bitops.h:154
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete_block
  - fs/mbcache.c:mb_cache_entry_delete_block
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:__entry_find
  - fs/mbcache.c:mb_cache_entry_create
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
In mm/slub.c (ffffffff8121e74a)
Location: arch/x86/include/asm/bitops.h:167
Inline: True
Inline callers:
  - mm/slub.c:validate_store
  - mm/slub.c:validate_store
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:free_debug_processing
```
```
In fs/dcache.c (ffffffff8125eba2)
Location: arch/x86/include/asm/bitops.h:167
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_obtain_alias
  - fs/dcache.c:__d_drop
```
```
In fs/mbcache.c (ffffffff812ad53b)
Location: arch/x86/include/asm/bitops.h:167
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete_block
  - fs/mbcache.c:mb_cache_entry_delete_block
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:__entry_find
  - fs/mbcache.c:mb_cache_entry_create
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
In mm/slub.c (ffffffff8122a2e4)
Location: arch/x86/include/asm/bitops.h:167
Inline: True
Inline callers:
  - mm/slub.c:validate_store
  - mm/slub.c:validate_store
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:free_debug_processing
```
```
In fs/dcache.c (ffffffff8126c572)
Location: arch/x86/include/asm/bitops.h:167
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_drop
```
```
In fs/mbcache.c (ffffffff812ba9db)
Location: arch/x86/include/asm/bitops.h:167
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:__entry_find
  - fs/mbcache.c:mb_cache_entry_create
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
In mm/slub.c (ffffffff81245494)
Location: arch/x86/include/asm/bitops.h:168
Inline: True
Inline callers:
  - mm/slub.c:validate_store
  - mm/slub.c:validate_store
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:free_debug_processing
```
```
In fs/dcache.c (ffffffff8128e702)
Location: arch/x86/include/asm/bitops.h:168
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_rehash
  - fs/dcache.c:___d_drop
```
```
In fs/mbcache.c (ffffffff812de2bb)
Location: arch/x86/include/asm/bitops.h:168
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:__entry_find
  - fs/mbcache.c:mb_cache_entry_create
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
In mm/slub.c (ffffffff81269593)
Location: arch/x86/include/asm/bitops.h:168
Inline: True
Inline callers:
  - mm/slub.c:validate_store
  - mm/slub.c:validate_store
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:__slab_free
  - mm/slub.c:__slab_free
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:free_debug_processing
```
```
In fs/dcache.c (ffffffff812b4993)
Location: arch/x86/include/asm/bitops.h:168
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_rehash
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:___d_drop
```
```
In fs/mbcache.c (ffffffff8130a4fc)
Location: arch/x86/include/asm/bitops.h:168
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:__entry_find
  - fs/mbcache.c:mb_cache_entry_create
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
In mm/slub.c (ffffffff8127c66b)
Location: arch/x86/include/asm/bitops.h:168
Inline: True
Inline callers:
  - mm/slub.c:validate_store
  - mm/slub.c:validate_store
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:__slab_free
  - mm/slub.c:__slab_free
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:free_debug_processing
```
```
In fs/dcache.c (ffffffff812c9c13)
Location: arch/x86/include/asm/bitops.h:168
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_rehash
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:___d_drop
```
```
In fs/mbcache.c (ffffffff8131fcdc)
Location: arch/x86/include/asm/bitops.h:168
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:__entry_find
  - fs/mbcache.c:mb_cache_entry_create
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
In mm/slub.c (ffffffff8129823e)
Location: include/asm-generic/bitops-instrumented.h:97
Inline: True
Inline callers:
  - mm/slub.c:validate_store
  - mm/slub.c:validate_store
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:__slab_free
  - mm/slub.c:__slab_free
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:free_debug_processing
```
```
In fs/dcache.c (ffffffff812e6620)
Location: include/asm-generic/bitops-instrumented.h:97
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_rehash
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:___d_drop
```
```
In fs/mbcache.c (ffffffff8134754f)
Location: include/asm-generic/bitops-instrumented.h:97
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:__entry_find
  - fs/mbcache.c:mb_cache_entry_create
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
In mm/slub.c (ffffffff812a809e)
Location: include/asm-generic/bitops-instrumented.h:97
Inline: True
Inline callers:
  - mm/slub.c:validate_store
  - mm/slub.c:validate_store
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:__slab_free
  - mm/slub.c:__slab_free
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:free_debug_processing
```
```
In fs/dcache.c (ffffffff812f8180)
Location: include/asm-generic/bitops-instrumented.h:97
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_rehash
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:___d_drop
```
```
In fs/mbcache.c (ffffffff8135f6bf)
Location: include/asm-generic/bitops-instrumented.h:97
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:__entry_find
  - fs/mbcache.c:mb_cache_entry_create
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
In mm/slub.c (ffffffff812dd301)
Location: include/asm-generic/bitops/instrumented-lock.h:38
Inline: True
Inline callers:
  - mm/slub.c:validate_slab
  - mm/slub.c:__slab_free
  - mm/slub.c:__slab_free
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:unfreeze_partials
  - mm/slub.c:unfreeze_partials
  - mm/slub.c:deactivate_slab
  - mm/slub.c:deactivate_slab
  - mm/slub.c:deactivate_slab
  - mm/slub.c:deactivate_slab
  - mm/slub.c:free_debug_processing
```
```
In fs/dcache.c (ffffffff81330ee0)
Location: include/asm-generic/bitops/instrumented-lock.h:38
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_rehash
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:___d_drop
```
```
In fs/mbcache.c (ffffffff813a529b)
Location: include/asm-generic/bitops/instrumented-lock.h:38
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:mb_cache_entry_create
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
In mm/slub.c (ffffffff812e60d1)
Location: include/asm-generic/bitops/instrumented-lock.h:38
Inline: True
Inline callers:
  - mm/slub.c:validate_slab
  - mm/slub.c:__slab_free
  - mm/slub.c:__slab_free
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:unfreeze_partials
  - mm/slub.c:unfreeze_partials
  - mm/slub.c:deactivate_slab
  - mm/slub.c:deactivate_slab
  - mm/slub.c:deactivate_slab
  - mm/slub.c:deactivate_slab
  - mm/slub.c:free_debug_processing
```
```
In fs/dcache.c (ffffffff8133c870)
Location: include/asm-generic/bitops/instrumented-lock.h:38
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_rehash
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:___d_drop
```
```
In fs/mbcache.c (ffffffff813b5ffb)
Location: include/asm-generic/bitops/instrumented-lock.h:38
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:mb_cache_entry_create
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
In mm/slub.c (ffffffff812ed861)
Location: include/asm-generic/bitops/instrumented-lock.h:38
Inline: True
Inline callers:
  - mm/slub.c:validate_slab
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:__slab_free
  - mm/slub.c:__slab_free
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:unfreeze_partials
  - mm/slub.c:unfreeze_partials
  - mm/slub.c:deactivate_slab
  - mm/slub.c:deactivate_slab
  - mm/slub.c:free_debug_processing
```
```
In fs/dcache.c (ffffffff81342cf5)
Location: include/asm-generic/bitops/instrumented-lock.h:38
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_rehash
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:___d_drop
```
```
In fs/mbcache.c (ffffffff813bd14b)
Location: include/asm-generic/bitops/instrumented-lock.h:38
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:mb_cache_entry_create
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
In mm/slub.c (ffffffff81335bd8)
Location: include/asm-generic/bitops/instrumented-lock.h:38
Inline: True
Inline callers:
  - mm/slub.c:validate_slab
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:__slab_free
  - mm/slub.c:__slab_free
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:__unfreeze_partials
  - mm/slub.c:__unfreeze_partials
  - mm/slub.c:deactivate_slab
  - mm/slub.c:deactivate_slab
  - mm/slub.c:free_debug_processing
```
```
In fs/dcache.c (ffffffff81390735)
Location: include/asm-generic/bitops/instrumented-lock.h:38
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_rehash
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:___d_drop
```
```
In fs/mbcache.c (ffffffff8140ceef)
Location: include/asm-generic/bitops/instrumented-lock.h:38
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:mb_cache_entry_create
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
In mm/slub.c (ffffffff813a738f)
Location: include/asm-generic/bitops/instrumented-lock.h:39
Inline: True
Inline callers:
  - mm/slub.c:validate_slab
  - mm/slub.c:free_partial
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:__unfreeze_partials
  - mm/slub.c:__unfreeze_partials
  - mm/slub.c:free_debug_processing
```
```
In fs/dcache.c (ffffffff814131ec)
Location: include/asm-generic/bitops/instrumented-lock.h:39
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_rehash
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:___d_drop
```
```
In fs/mbcache.c (ffffffff81481d4b)
Location: include/asm-generic/bitops/instrumented-lock.h:39
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete_or_get
  - fs/mbcache.c:mb_cache_entry_delete_or_get
  - fs/mbcache.c:mb_cache_entry_delete_or_get
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:mb_cache_entry_create
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
In mm/slub.c (ffffffff81429fa8)
Location: include/asm-generic/bitops/instrumented-lock.h:39
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:__unfreeze_partials
  - mm/slub.c:__unfreeze_partials
```
```
In fs/dcache.c (ffffffff8149e498)
Location: include/asm-generic/bitops/instrumented-lock.h:39
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_unhash
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_rehash
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:___d_drop
```
```
In fs/mbcache.c (ffffffff81514fa4)
Location: include/asm-generic/bitops/instrumented-lock.h:39
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:__entry_find
  - fs/mbcache.c:__mb_cache_entry_free
  - fs/mbcache.c:mb_cache_entry_create
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
In mm/slub.c (ffffffff8145f449)
Location: include/asm-generic/bitops/instrumented-lock.h:39
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
  - mm/slub.c:__unfreeze_partials
```
```
In fs/dcache.c (ffffffff814d37b8)
Location: include/asm-generic/bitops/instrumented-lock.h:39
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_unhash
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_rehash
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:___d_drop
```
```
In fs/mbcache.c (ffffffff8154c9a4)
Location: include/asm-generic/bitops/instrumented-lock.h:39
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:__entry_find
  - fs/mbcache.c:__mb_cache_entry_free
  - fs/mbcache.c:mb_cache_entry_create
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
In fs/dcache.c (ffffffff81505f38)
Location: include/asm-generic/bitops/instrumented-lock.h:39
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_unhash
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_rehash
  - fs/dcache.c:__d_obtain_alias
  - fs/dcache.c:___d_drop
```
```
In fs/mbcache.c (ffffffff815827d4)
Location: include/asm-generic/bitops/instrumented-lock.h:39
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:__entry_find
  - fs/mbcache.c:__mb_cache_entry_free
  - fs/mbcache.c:mb_cache_entry_create
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
In mm/slub.c (ffff800010349594)
Location: include/asm-generic/bitops/lock.h:57
Inline: True
Inline callers:
  - mm/slub.c:validate_slab_slab
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:__slab_free
  - mm/slub.c:__slab_free
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:free_debug_processing
```
```
In fs/dcache.c (ffff8000103a571c)
Location: include/asm-generic/bitops/lock.h:57
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_rehash
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:___d_drop
```
```
In fs/mbcache.c (ffff800010425338)
Location: include/asm-generic/bitops/lock.h:57
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:__entry_find
  - fs/mbcache.c:mb_cache_entry_create
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
In mm/slub.c (c054d59c)
Location: include/asm-generic/bitops/lock.h:57
Inline: True
Inline callers:
  - mm/slub.c:validate_slab_slab
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:__slab_free
  - mm/slub.c:__slab_free
  - mm/slub.c:unfreeze_partials
  - mm/slub.c:unfreeze_partials
  - mm/slub.c:deactivate_slab
  - mm/slub.c:deactivate_slab
  - mm/slub.c:deactivate_slab
  - mm/slub.c:deactivate_slab
  - mm/slub.c:free_debug_processing
```
```
In fs/dcache.c (c0588f30)
Location: include/asm-generic/bitops/lock.h:57
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_rehash
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:___d_drop
```
```
In fs/mbcache.c (c05edee0)
Location: include/asm-generic/bitops/lock.h:57
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:__entry_find
  - fs/mbcache.c:mb_cache_entry_create
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
In arch/powerpc/kvm/book3s_64_vio_hv.c (c000000000118f00)
Location: arch/powerpc/include/asm/bitops.h:196
Inline: True
Inline callers:
  - arch/powerpc/kvm/book3s_64_vio_hv.c:kvmppc_rm_h_put_tce_indirect
```
```
In arch/powerpc/kvm/book3s_hv_rm_mmu.c (c00000000011fbb0)
Location: arch/powerpc/include/asm/bitops.h:196
Inline: True
Inline callers:
  - arch/powerpc/kvm/book3s_hv_rm_mmu.c:kvmppc_h_clear_ref
  - arch/powerpc/kvm/book3s_hv_rm_mmu.c:kvmppc_do_h_enter
  - arch/powerpc/kvm/book3s_hv_rm_mmu.c:remove_revmap_chain
  - arch/powerpc/kvm/book3s_hv_rm_mmu.c:kvmppc_add_revmap_chain
```
```
In mm/slub.c (c000000000428560)
Location: arch/powerpc/include/asm/bitops.h:196
Inline: True
Inline callers:
  - mm/slub.c:validate_store
  - mm/slub.c:validate_store
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:__slab_free
  - mm/slub.c:__slab_free
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:free_debug_processing
```
```
In fs/dcache.c (c0000000004a1198)
Location: arch/powerpc/include/asm/bitops.h:196
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_rehash
  - fs/dcache.c:___d_drop
```
```
In fs/mbcache.c (c0000000005345b8)
Location: arch/powerpc/include/asm/bitops.h:196
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:__entry_find
  - fs/mbcache.c:mb_cache_entry_create
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
In mm/slub.c (ffffffe00023b14c)
Location: arch/riscv/include/asm/bitops.h:189
Inline: True
Inline callers:
  - mm/slub.c:validate_slab_slab
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:__slab_free
  - mm/slub.c:__slab_free
  - mm/slub.c:free_debug_processing
```
```
In fs/dcache.c (ffffffe00026c2c8)
Location: arch/riscv/include/asm/bitops.h:189
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_rehash
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:___d_drop
```
```
In fs/mbcache.c (ffffffe0002c44b0)
Location: arch/riscv/include/asm/bitops.h:189
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:__entry_find
  - fs/mbcache.c:mb_cache_entry_create
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
In mm/slub.c (ffffffff812a067e)
Location: include/asm-generic/bitops-instrumented.h:97
Inline: True
Inline callers:
  - mm/slub.c:validate_store
  - mm/slub.c:validate_store
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:__slab_free
  - mm/slub.c:__slab_free
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:free_debug_processing
```
```
In fs/dcache.c (ffffffff812f0760)
Location: include/asm-generic/bitops-instrumented.h:97
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_rehash
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:___d_drop
```
```
In fs/mbcache.c (ffffffff81357c9f)
Location: include/asm-generic/bitops-instrumented.h:97
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:__entry_find
  - fs/mbcache.c:mb_cache_entry_create
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
In mm/slub.c (ffffffff8129218e)
Location: include/asm-generic/bitops-instrumented.h:97
Inline: True
Inline callers:
  - mm/slub.c:validate_store
  - mm/slub.c:validate_store
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:__slab_free
  - mm/slub.c:__slab_free
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:free_debug_processing
```
```
In fs/dcache.c (ffffffff812e1390)
Location: include/asm-generic/bitops-instrumented.h:97
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_rehash
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:___d_drop
```
```
In fs/mbcache.c (ffffffff8134894f)
Location: include/asm-generic/bitops-instrumented.h:97
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:__entry_find
  - fs/mbcache.c:mb_cache_entry_create
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
In mm/slub.c (ffffffff8129e48e)
Location: include/asm-generic/bitops-instrumented.h:97
Inline: True
Inline callers:
  - mm/slub.c:validate_store
  - mm/slub.c:validate_store
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:__slab_free
  - mm/slub.c:__slab_free
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:free_debug_processing
```
```
In fs/dcache.c (ffffffff812ee570)
Location: include/asm-generic/bitops-instrumented.h:97
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_rehash
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:___d_drop
```
```
In fs/mbcache.c (ffffffff8135576f)
Location: include/asm-generic/bitops-instrumented.h:97
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:__entry_find
  - fs/mbcache.c:mb_cache_entry_create
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
In mm/slub.c (ffffffff812ae24b)
Location: include/asm-generic/bitops-instrumented.h:97
Inline: True
Inline callers:
  - mm/slub.c:validate_slab_slab
  - mm/slub.c:__kmem_cache_shutdown
  - mm/slub.c:__slab_free
  - mm/slub.c:__slab_free
  - mm/slub.c:___slab_alloc
  - mm/slub.c:___slab_alloc
  - mm/slub.c:free_debug_processing
```
```
In fs/dcache.c (ffffffff81300537)
Location: include/asm-generic/bitops-instrumented.h:97
Inline: True
Inline callers:
  - fs/dcache.c:__d_lookup_done
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:d_alloc_parallel
  - fs/dcache.c:__d_rehash
  - fs/dcache.c:__d_instantiate_anon
  - fs/dcache.c:___d_drop
```
```
In fs/mbcache.c (ffffffff81368d70)
Location: include/asm-generic/bitops-instrumented.h:97
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_shrink
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_delete
  - fs/mbcache.c:mb_cache_entry_get
  - fs/mbcache.c:__entry_find
  - fs/mbcache.c:mb_cache_entry_create
  - fs/mbcache.c:mb_cache_entry_create
```
</details>
</li>
</ul>

## Differences
