# Function: <code>kfence_guarded_alloc</code>

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
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void *kfence_guarded_alloc(struct kmem_cache *cache, size_t size, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/kfence/core.c (ffffffff8133be70)
Location: mm/kfence/core.c:261
Inline: False
Direct callers:
  - mm/kfence/core.c:__kfence_alloc
```
**Symbols:**

```
ffffffff8133be70-ffffffff8133c18e: kfence_guarded_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void *kfence_guarded_alloc(struct kmem_cache *cache, size_t size, gfp_t gfp, long unsigned int *stack_entries, size_t num_stack_entries, u32 alloc_stack_hash);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/kfence/core.c (ffffffff813aeac0)
Location: mm/kfence/core.c:355
Inline: False
Direct callers:
  - mm/kfence/core.c:__kfence_alloc
```
**Symbols:**

```
ffffffff813aeac0-ffffffff813aeead: kfence_guarded_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void *kfence_guarded_alloc(struct kmem_cache *cache, size_t size, gfp_t gfp, long unsigned int *stack_entries, size_t num_stack_entries, u32 alloc_stack_hash);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/kfence/core.c (ffffffff8142f010)
Location: mm/kfence/core.c:354
Inline: False
Direct callers:
  - mm/kfence/core.c:__kfence_alloc
```
**Symbols:**

```
ffffffff8142f010-ffffffff8142f3fb: kfence_guarded_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void *kfence_guarded_alloc(struct kmem_cache *cache, size_t size, gfp_t gfp, long unsigned int *stack_entries, size_t num_stack_entries, u32 alloc_stack_hash);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/kfence/core.c (ffffffff81464d20)
Location: mm/kfence/core.c:382
Inline: False
Direct callers:
  - mm/kfence/core.c:__kfence_alloc
```
**Symbols:**

```
ffffffff81464d20-ffffffff81465132: kfence_guarded_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void *kfence_guarded_alloc(struct kmem_cache *cache, size_t size, gfp_t gfp, long unsigned int *stack_entries, size_t num_stack_entries, u32 alloc_stack_hash);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/kfence/core.c (ffffffff81493970)
Location: mm/kfence/core.c:390
Inline: False
Direct callers:
  - mm/kfence/core.c:__kfence_alloc
```
**Symbols:**

```
ffffffff81493970-ffffffff81493d9e: kfence_guarded_alloc (STB_LOCAL)
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
<li>
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>long unsigned int *stack_entries</code>
</li>
<li>
<b>Param added. </b>
<code>size_t num_stack_entries</code>
</li>
<li>
<b>Param added. </b>
<code>u32 alloc_stack_hash</code>
</li>
</ul>
</details>
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
