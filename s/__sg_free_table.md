# Function: <code>__sg_free_table</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void __sg_free_table(struct sg_table *table, unsigned int max_ents, bool skip_first_chunk, sg_free_fn *free_fn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff813f9e00)
Location: lib/scatterlist.c:205
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_free_table
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_mq_free_sgtables
  - drivers/scsi/scsi_lib.c:scsi_mq_free_sgtables
  - drivers/scsi/scsi_lib.c:scsi_mq_free_sgtables
  - drivers/scsi/scsi_lib.c:scsi_release_buffers
  - drivers/scsi/scsi_lib.c:scsi_release_buffers
  - drivers/scsi/scsi_lib.c:scsi_end_request
```
**Symbols:**

```
ffffffff813f9e00-ffffffff813f9e8c: __sg_free_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void __sg_free_table(struct sg_table *table, unsigned int max_ents, bool skip_first_chunk, sg_free_fn *free_fn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff8144110a)
Location: lib/scatterlist.c:205
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_free_table
```
**Symbols:**

```
ffffffff81440e50-ffffffff81440eda: __sg_free_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void __sg_free_table(struct sg_table *table, unsigned int max_ents, bool skip_first_chunk, sg_free_fn *free_fn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff8145e2aa)
Location: lib/scatterlist.c:205
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_free_table
```
**Symbols:**

```
ffffffff8145e070-ffffffff8145e0fa: __sg_free_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void __sg_free_table(struct sg_table *table, unsigned int max_ents, bool skip_first_chunk, sg_free_fn *free_fn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff8146351a)
Location: lib/scatterlist.c:205
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_free_table
```
**Symbols:**

```
ffffffff81463370-ffffffff814633f7: __sg_free_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void __sg_free_table(struct sg_table *table, unsigned int max_ents, bool skip_first_chunk, sg_free_fn *free_fn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff8148f42a)
Location: lib/scatterlist.c:205
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_free_table
```
**Symbols:**

```
ffffffff8148f280-ffffffff8148f309: __sg_free_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __sg_free_table(struct sg_table *table, unsigned int max_ents, bool skip_first_chunk, sg_free_fn *free_fn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff814c3e50)
Location: lib/scatterlist.c:193
Inline: False
Direct callers:
  - lib/scatterlist.c:sg_free_table
```
**Symbols:**

```
ffffffff814c3e50-ffffffff814c3edf: __sg_free_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __sg_free_table(struct sg_table *table, unsigned int max_ents, bool skip_first_chunk, sg_free_fn *free_fn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff814d8540)
Location: lib/scatterlist.c:193
Inline: False
Direct callers:
  - lib/scatterlist.c:sg_free_table
```
**Symbols:**

```
ffffffff814d8540-ffffffff814d85cf: __sg_free_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __sg_free_table(struct sg_table *table, unsigned int max_ents, unsigned int nents_first_chunk, sg_free_fn *free_fn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff81504350)
Location: lib/scatterlist.c:192
Inline: False
Direct callers:
  - lib/scatterlist.c:sg_free_table
```
**Symbols:**

```
ffffffff81504350-ffffffff815043da: __sg_free_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __sg_free_table(struct sg_table *table, unsigned int max_ents, unsigned int nents_first_chunk, sg_free_fn *free_fn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff81522360)
Location: lib/scatterlist.c:192
Inline: False
Direct callers:
  - lib/scatterlist.c:sg_free_table
```
**Symbols:**

```
ffffffff81522360-ffffffff815223ea: __sg_free_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void __sg_free_table(struct sg_table *table, unsigned int max_ents, unsigned int nents_first_chunk, sg_free_fn *free_fn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff8158649c)
Location: lib/scatterlist.c:192
Inline: True
Inline callers:
  - lib/scatterlist.c:__sg_alloc_table_from_pages
  - lib/scatterlist.c:sg_free_table
Direct callers:
  - lib/sg_pool.c:sg_alloc_table_chained
```
**Symbols:**

```
ffffffff815856c0-ffffffff8158574a: __sg_free_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void __sg_free_table(struct sg_table *table, unsigned int max_ents, unsigned int nents_first_chunk, sg_free_fn *free_fn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff815a2ed0)
Location: lib/scatterlist.c:192
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_free_table
Direct callers:
  - lib/sg_pool.c:sg_alloc_table_chained
```
**Symbols:**

```
ffffffff815a27c0-ffffffff815a284a: __sg_free_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void __sg_free_table(struct sg_table *table, unsigned int max_ents, unsigned int nents_first_chunk, sg_free_fn *free_fn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff815a9e00)
Location: lib/scatterlist.c:192
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_free_table
Direct callers:
  - lib/sg_pool.c:sg_alloc_table_chained
```
**Symbols:**

```
ffffffff815a96f0-ffffffff815a977a: __sg_free_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void __sg_free_table(struct sg_table *table, unsigned int max_ents, unsigned int nents_first_chunk, sg_free_fn *free_fn, unsigned int num_ents);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff81613789)
Location: lib/scatterlist.c:193
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_alloc_table_from_pages_segment
  - lib/scatterlist.c:sg_alloc_table
Direct callers:
  - lib/sg_pool.c:sg_alloc_table_chained
```
**Symbols:**

```
ffffffff81612870-ffffffff816128f2: __sg_free_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void __sg_free_table(struct sg_table *table, unsigned int max_ents, unsigned int nents_first_chunk, sg_free_fn *free_fn, unsigned int num_ents);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff816e000d)
Location: lib/scatterlist.c:193
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_alloc_table_from_pages_segment
  - lib/scatterlist.c:sg_alloc_table
Direct callers:
  - lib/sg_pool.c:sg_alloc_table_chained
```
**Symbols:**

```
ffffffff816deef0-ffffffff816def88: __sg_free_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void __sg_free_table(struct sg_table *table, unsigned int max_ents, unsigned int nents_first_chunk, sg_free_fn *free_fn, unsigned int num_ents);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff817d04da)
Location: lib/scatterlist.c:193
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_alloc_table
  - lib/scatterlist.c:sg_free_append_table
Direct callers:
  - lib/sg_pool.c:sg_alloc_table_chained
```
**Symbols:**

```
ffffffff817cf0c0-ffffffff817cf158: __sg_free_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void __sg_free_table(struct sg_table *table, unsigned int max_ents, unsigned int nents_first_chunk, sg_free_fn *free_fn, unsigned int num_ents);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff8180f12a)
Location: lib/scatterlist.c:195
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_alloc_table
  - lib/scatterlist.c:sg_free_append_table
Direct callers:
  - lib/sg_pool.c:sg_alloc_table_chained
```
**Symbols:**

```
ffffffff8180d570-ffffffff8180d60d: __sg_free_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void __sg_free_table(struct sg_table *table, unsigned int max_ents, unsigned int nents_first_chunk, sg_free_fn *free_fn, unsigned int num_ents);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff81854daa)
Location: lib/scatterlist.c:195
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_alloc_table
  - lib/scatterlist.c:sg_free_append_table
Direct callers:
  - lib/sg_pool.c:sg_alloc_table_chained
```
**Symbols:**

```
ffffffff81853220-ffffffff818532bd: __sg_free_table (STB_GLOBAL)
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
void __sg_free_table(struct sg_table *table, unsigned int max_ents, unsigned int nents_first_chunk, sg_free_fn *free_fn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffff80001062bf48)
Location: lib/scatterlist.c:192
Inline: False
Direct callers:
  - lib/scatterlist.c:sg_free_table
```
**Symbols:**

```
ffff80001062bf48-ffff80001062bfec: __sg_free_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __sg_free_table(struct sg_table *table, unsigned int max_ents, unsigned int nents_first_chunk, sg_free_fn *free_fn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (c07d29ac)
Location: lib/scatterlist.c:192
Inline: False
Direct callers:
  - lib/scatterlist.c:sg_free_table
```
**Symbols:**

```
c07d29ac-c07d2a5c: __sg_free_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __sg_free_table(struct sg_table *table, unsigned int max_ents, unsigned int nents_first_chunk, sg_free_fn *free_fn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (c0000000007ce6f0)
Location: lib/scatterlist.c:192
Inline: False
Direct callers:
  - lib/scatterlist.c:sg_free_table
  - lib/sg_pool.c:sg_alloc_table_chained
```
**Symbols:**

```
c0000000007ce6f0-c0000000007ce818: __sg_free_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __sg_free_table(struct sg_table *table, unsigned int max_ents, unsigned int nents_first_chunk, sg_free_fn *free_fn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffe00045c160)
Location: lib/scatterlist.c:192
Inline: False
Direct callers:
  - lib/scatterlist.c:sg_free_table
```
**Symbols:**

```
ffffffe00045c160-ffffffe00045c1ec: __sg_free_table (STB_GLOBAL)
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
void __sg_free_table(struct sg_table *table, unsigned int max_ents, unsigned int nents_first_chunk, sg_free_fn *free_fn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff8151a940)
Location: lib/scatterlist.c:192
Inline: False
Direct callers:
  - lib/scatterlist.c:sg_free_table
```
**Symbols:**

```
ffffffff8151a940-ffffffff8151a9ca: __sg_free_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __sg_free_table(struct sg_table *table, unsigned int max_ents, unsigned int nents_first_chunk, sg_free_fn *free_fn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff8150ac30)
Location: lib/scatterlist.c:192
Inline: False
Direct callers:
  - lib/scatterlist.c:sg_free_table
```
**Symbols:**

```
ffffffff8150ac30-ffffffff8150acba: __sg_free_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __sg_free_table(struct sg_table *table, unsigned int max_ents, unsigned int nents_first_chunk, sg_free_fn *free_fn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff815169d0)
Location: lib/scatterlist.c:192
Inline: False
Direct callers:
  - lib/scatterlist.c:sg_free_table
```
**Symbols:**

```
ffffffff815169d0-ffffffff81516a5a: __sg_free_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __sg_free_table(struct sg_table *table, unsigned int max_ents, unsigned int nents_first_chunk, sg_free_fn *free_fn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff81530160)
Location: lib/scatterlist.c:192
Inline: False
Direct callers:
  - lib/scatterlist.c:sg_free_table
```
**Symbols:**

```
ffffffff81530160-ffffffff815301ea: __sg_free_table (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int nents_first_chunk</code>
</li>
<li>
<b>Param removed. </b>
<code>bool skip_first_chunk</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int num_ents</code>
</li>
</ul>
</details>
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
