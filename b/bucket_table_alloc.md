# Function: <code>bucket_table_alloc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct bucket_table *bucket_table_alloc(struct rhashtable *ht, size_t nbuckets, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffff814000c0)
Location: lib/rhashtable.c:111
Inline: False
Direct callers:
  - lib/rhashtable.c:rhashtable_init
  - lib/rhashtable.c:rhashtable_insert_rehash
  - lib/rhashtable.c:rht_deferred_worker
  - lib/rhashtable.c:rht_deferred_worker
```
**Symbols:**

```
ffffffff814000c0-ffffffff8140024d: bucket_table_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct bucket_table *bucket_table_alloc(struct rhashtable *ht, size_t nbuckets, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffff81447840)
Location: lib/rhashtable.c:115
Inline: False
Direct callers:
  - lib/rhashtable.c:rhashtable_init
  - lib/rhashtable.c:rhashtable_insert_rehash
  - lib/rhashtable.c:rht_deferred_worker
  - lib/rhashtable.c:rht_deferred_worker
```
**Symbols:**

```
ffffffff81447840-ffffffff81447a2a: bucket_table_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct bucket_table *bucket_table_alloc(struct rhashtable *ht, size_t nbuckets, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffff81466370)
Location: lib/rhashtable.c:115
Inline: False
Direct callers:
  - lib/rhashtable.c:rhashtable_init
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rht_deferred_worker
  - lib/rhashtable.c:rht_deferred_worker
```
**Symbols:**

```
ffffffff81466370-ffffffff81466455: bucket_table_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct bucket_table *bucket_table_alloc(struct rhashtable *ht, size_t nbuckets, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffff8146b750)
Location: lib/rhashtable.c:205
Inline: False
Direct callers:
  - lib/rhashtable.c:rhashtable_init
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_alloc
```
**Symbols:**

```
ffffffff8146b750-ffffffff8146b8f6: bucket_table_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct bucket_table *bucket_table_alloc(struct rhashtable *ht, size_t nbuckets, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffff81497a40)
Location: lib/rhashtable.c:205
Inline: False
Direct callers:
  - lib/rhashtable.c:rhashtable_init
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_alloc
```
**Symbols:**

```
ffffffff81497a40-ffffffff81497be6: bucket_table_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct bucket_table *bucket_table_alloc(struct rhashtable *ht, size_t nbuckets, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffff814cc9a0)
Location: lib/rhashtable.c:169
Inline: False
Direct callers:
  - lib/rhashtable.c:rhashtable_init
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_alloc
```
**Symbols:**

```
ffffffff814cc9a0-ffffffff814ccb39: bucket_table_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/rhashtable.c (ffffffff814e0f90)
Location: lib/rhashtable.c:167
Inline: True
Direct callers:
  - lib/rhashtable.c:rhashtable_init
  - lib/rhashtable.c:rhashtable_init
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_alloc
```
**Symbols:**

```
ffffffff814e0f90-ffffffff814e110d: bucket_table_alloc.isra.21 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/rhashtable.c (ffffffff8150ce10)
Location: lib/rhashtable.c:166
Inline: True
Direct callers:
  - lib/rhashtable.c:rhashtable_init
  - lib/rhashtable.c:rhashtable_init
  - lib/rhashtable.c:rhashtable_insert_slow
```
**Symbols:**

```
ffffffff8150ce10-ffffffff8150cef8: bucket_table_alloc.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/rhashtable.c (ffffffff8152ac60)
Location: lib/rhashtable.c:166
Inline: True
Direct callers:
  - lib/rhashtable.c:rhashtable_init
  - lib/rhashtable.c:rhashtable_init
  - lib/rhashtable.c:rhashtable_insert_slow
```
**Symbols:**

```
ffffffff8152ac60-ffffffff8152ad48: bucket_table_alloc.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/rhashtable.c (ffffffff8158e270)
Location: lib/rhashtable.c:175
Inline: True
Direct callers:
  - lib/rhashtable.c:rhashtable_init
  - lib/rhashtable.c:rhashtable_init
  - lib/rhashtable.c:rhashtable_insert_rehash
  - lib/rhashtable.c:rht_deferred_worker
  - lib/rhashtable.c:rhashtable_shrink
```
**Symbols:**

```
ffffffff8158e270-ffffffff8158e358: bucket_table_alloc.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/rhashtable.c (ffffffff815aad70)
Location: lib/rhashtable.c:175
Inline: True
Direct callers:
  - lib/rhashtable.c:rhashtable_init
  - lib/rhashtable.c:rhashtable_init
  - lib/rhashtable.c:rhashtable_insert_rehash
  - lib/rhashtable.c:rht_deferred_worker
  - lib/rhashtable.c:rht_deferred_worker
```
**Symbols:**

```
ffffffff815aad70-ffffffff815aaec9: bucket_table_alloc.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/rhashtable.c (ffffffff815b5880)
Location: lib/rhashtable.c:175
Inline: True
Direct callers:
  - lib/rhashtable.c:rhashtable_init
  - lib/rhashtable.c:rhashtable_init
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rht_deferred_worker
  - lib/rhashtable.c:rht_deferred_worker
  - lib/rhashtable.c:rht_deferred_worker
```
**Symbols:**

```
ffffffff815b5880-ffffffff815b59d9: bucket_table_alloc.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/rhashtable.c (ffffffff8161bd10)
Location: lib/rhashtable.c:175
Inline: True
Direct callers:
  - lib/rhashtable.c:rhashtable_init
  - lib/rhashtable.c:rhashtable_init
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rht_deferred_worker
  - lib/rhashtable.c:rht_deferred_worker
  - lib/rhashtable.c:rht_deferred_worker
```
**Symbols:**

```
ffffffff8161bd10-ffffffff8161be69: bucket_table_alloc.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/rhashtable.c (ffffffff816e9700)
Location: lib/rhashtable.c:175
Inline: True
Direct callers:
  - lib/rhashtable.c:rhashtable_init
  - lib/rhashtable.c:rhashtable_init
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rht_deferred_worker
  - lib/rhashtable.c:rht_deferred_worker
  - lib/rhashtable.c:rht_deferred_worker
```
**Symbols:**

```
ffffffff816e9700-ffffffff816e9850: bucket_table_alloc.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/rhashtable.c (ffffffff817d9890)
Location: lib/rhashtable.c:175
Inline: True
Direct callers:
  - lib/rhashtable.c:rhashtable_init
  - lib/rhashtable.c:rhashtable_init
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rht_deferred_worker
  - lib/rhashtable.c:rht_deferred_worker
  - lib/rhashtable.c:rht_deferred_worker
```
**Symbols:**

```
ffffffff817d9890-ffffffff817d99e0: bucket_table_alloc.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/rhashtable.c (ffffffff81818c10)
Location: lib/rhashtable.c:175
Inline: True
Direct callers:
  - lib/rhashtable.c:rhashtable_init
  - lib/rhashtable.c:rhashtable_init
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rht_deferred_worker
  - lib/rhashtable.c:rht_deferred_worker
  - lib/rhashtable.c:rht_deferred_worker
```
**Symbols:**

```
ffffffff81818c10-ffffffff81818d53: bucket_table_alloc.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/rhashtable.c (ffffffff8185df40)
Location: lib/rhashtable.c:175
Inline: True
Direct callers:
  - lib/rhashtable.c:rhashtable_init
  - lib/rhashtable.c:rhashtable_init
  - lib/rhashtable.c:rhashtable_try_insert
  - lib/rhashtable.c:rht_deferred_worker
  - lib/rhashtable.c:rht_deferred_worker
  - lib/rhashtable.c:rht_deferred_worker
```
**Symbols:**

```
ffffffff8185df40-ffffffff8185e0a4: bucket_table_alloc.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/rhashtable.c (ffff800010635db0)
Location: lib/rhashtable.c:166
Inline: True
Direct callers:
  - lib/rhashtable.c:rhashtable_init
  - lib/rhashtable.c:rhashtable_init
  - lib/rhashtable.c:rhashtable_insert_slow
```
**Symbols:**

```
ffff800010635db0-ffff800010635e98: bucket_table_alloc.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct bucket_table *bucket_table_alloc(struct rhashtable *ht, size_t nbuckets, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (c07dbc9c)
Location: lib/rhashtable.c:166
Inline: False
Direct callers:
  - lib/rhashtable.c:rhashtable_init
  - lib/rhashtable.c:rhashtable_init
  - lib/rhashtable.c:rhashtable_insert_slow
  - lib/rhashtable.c:rhashtable_rehash_alloc
```
**Symbols:**

```
c07dbc9c-c07dbdf4: bucket_table_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/rhashtable.c (c0000000007dc300)
Location: lib/rhashtable.c:166
Inline: True
Direct callers:
  - lib/rhashtable.c:rhashtable_init
  - lib/rhashtable.c:rhashtable_init
  - lib/rhashtable.c:rhashtable_insert_slow
```
**Symbols:**

```
c0000000007dc300-c0000000007dc428: bucket_table_alloc.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/rhashtable.c (ffffffe000463b3e)
Location: lib/rhashtable.c:166
Inline: True
Direct callers:
  - lib/rhashtable.c:rhashtable_init
  - lib/rhashtable.c:rhashtable_init
  - lib/rhashtable.c:rhashtable_insert_slow
```
**Symbols:**

```
ffffffe000463b3e-ffffffe000463c08: bucket_table_alloc.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/rhashtable.c (ffffffff81523240)
Location: lib/rhashtable.c:166
Inline: True
Direct callers:
  - lib/rhashtable.c:rhashtable_init
  - lib/rhashtable.c:rhashtable_init
  - lib/rhashtable.c:rhashtable_insert_slow
```
**Symbols:**

```
ffffffff81523240-ffffffff81523328: bucket_table_alloc.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/rhashtable.c (ffffffff81513520)
Location: lib/rhashtable.c:166
Inline: True
Direct callers:
  - lib/rhashtable.c:rhashtable_init
  - lib/rhashtable.c:rhashtable_init
  - lib/rhashtable.c:rhashtable_insert_slow
```
**Symbols:**

```
ffffffff81513520-ffffffff81513608: bucket_table_alloc.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/rhashtable.c (ffffffff8151f2d0)
Location: lib/rhashtable.c:166
Inline: True
Direct callers:
  - lib/rhashtable.c:rhashtable_init
  - lib/rhashtable.c:rhashtable_init
  - lib/rhashtable.c:rhashtable_insert_slow
```
**Symbols:**

```
ffffffff8151f2d0-ffffffff8151f3b8: bucket_table_alloc.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/rhashtable.c (ffffffff81538cf0)
Location: lib/rhashtable.c:166
Inline: True
Direct callers:
  - lib/rhashtable.c:rhashtable_init
  - lib/rhashtable.c:rhashtable_init
  - lib/rhashtable.c:rhashtable_insert_slow
```
**Symbols:**

```
ffffffff81538cf0-ffffffff81538dd8: bucket_table_alloc.isra.0 (STB_LOCAL)
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
</ul>
<b>Arch</b>
<ul>
</ul>
