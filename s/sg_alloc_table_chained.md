# Function: <code>sg_alloc_table_chained</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int sg_alloc_table_chained(struct sg_table *table, int nents, struct scatterlist *first_chunk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/sg_pool.c (ffffffff81461e10)
Location: lib/sg_pool.c:98
Inline: True
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_init_io
```
**Symbols:**

```
ffffffff81461e10-ffffffff81461eb4: sg_alloc_table_chained (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int sg_alloc_table_chained(struct sg_table *table, int nents, struct scatterlist *first_chunk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/sg_pool.c (ffffffff81480950)
Location: lib/sg_pool.c:98
Inline: True
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_init_io
```
**Symbols:**

```
ffffffff81480950-ffffffff814809f4: sg_alloc_table_chained (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int sg_alloc_table_chained(struct sg_table *table, int nents, struct scatterlist *first_chunk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/sg_pool.c (ffffffff81489b10)
Location: lib/sg_pool.c:98
Inline: True
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_init_io
```
**Symbols:**

```
ffffffff81489b10-ffffffff81489bbc: sg_alloc_table_chained (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int sg_alloc_table_chained(struct sg_table *table, int nents, struct scatterlist *first_chunk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/sg_pool.c (ffffffff814c5c60)
Location: lib/sg_pool.c:98
Inline: True
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_init_io
```
**Symbols:**

```
ffffffff814c5c60-ffffffff814c5d0c: sg_alloc_table_chained (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int sg_alloc_table_chained(struct sg_table *table, int nents, struct scatterlist *first_chunk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/sg_pool.c (ffffffff814f6b90)
Location: lib/sg_pool.c:98
Inline: True
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_init_io
```
**Symbols:**

```
ffffffff814f6b90-ffffffff814f6c3c: sg_alloc_table_chained (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int sg_alloc_table_chained(struct sg_table *table, int nents, struct scatterlist *first_chunk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/sg_pool.c (ffffffff8150afd0)
Location: lib/sg_pool.c:98
Inline: True
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_init_io
```
**Symbols:**

```
ffffffff8150afd0-ffffffff8150b07c: sg_alloc_table_chained (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int sg_alloc_table_chained(struct sg_table *table, int nents, struct scatterlist *first_chunk, unsigned int nents_first_chunk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/sg_pool.c (ffffffff815396e0)
Location: lib/sg_pool.c:111
Inline: True
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_init_io
  - drivers/scsi/scsi_lib.c:scsi_init_io
```
**Symbols:**

```
ffffffff815396e0-ffffffff81539776: sg_alloc_table_chained (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int sg_alloc_table_chained(struct sg_table *table, int nents, struct scatterlist *first_chunk, unsigned int nents_first_chunk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/sg_pool.c (ffffffff8155a500)
Location: lib/sg_pool.c:111
Inline: True
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_init_io
  - drivers/scsi/scsi_lib.c:scsi_init_io
```
**Symbols:**

```
ffffffff8155a500-ffffffff8155a596: sg_alloc_table_chained (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int sg_alloc_table_chained(struct sg_table *table, int nents, struct scatterlist *first_chunk, unsigned int nents_first_chunk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sg_pool.c (ffffffff815e3dc0)
Location: lib/sg_pool.c:111
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_init_io
  - drivers/scsi/scsi_lib.c:scsi_init_io
```
**Symbols:**

```
ffffffff815e3dc0-ffffffff815e3e56: sg_alloc_table_chained (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int sg_alloc_table_chained(struct sg_table *table, int nents, struct scatterlist *first_chunk, unsigned int nents_first_chunk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sg_pool.c (ffffffff816082f0)
Location: lib/sg_pool.c:111
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_alloc_sgtables
  - drivers/scsi/scsi_lib.c:scsi_alloc_sgtables
```
**Symbols:**

```
ffffffff816082f0-ffffffff81608386: sg_alloc_table_chained (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int sg_alloc_table_chained(struct sg_table *table, int nents, struct scatterlist *first_chunk, unsigned int nents_first_chunk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sg_pool.c (ffffffff815eaf50)
Location: lib/sg_pool.c:111
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_alloc_sgtables
  - drivers/scsi/scsi_lib.c:scsi_alloc_sgtables
```
**Symbols:**

```
ffffffff815eaf50-ffffffff815eafe6: sg_alloc_table_chained (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int sg_alloc_table_chained(struct sg_table *table, int nents, struct scatterlist *first_chunk, unsigned int nents_first_chunk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sg_pool.c (ffffffff81657520)
Location: lib/sg_pool.c:112
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_alloc_sgtables
  - drivers/scsi/scsi_lib.c:scsi_alloc_sgtables
```
**Symbols:**

```
ffffffff81657520-ffffffff816575b9: sg_alloc_table_chained (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int sg_alloc_table_chained(struct sg_table *table, int nents, struct scatterlist *first_chunk, unsigned int nents_first_chunk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sg_pool.c (ffffffff8176ee00)
Location: lib/sg_pool.c:112
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_alloc_sgtables
  - drivers/scsi/scsi_lib.c:scsi_alloc_sgtables
```
**Symbols:**

```
ffffffff8176ee00-ffffffff8176eeb4: sg_alloc_table_chained (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int sg_alloc_table_chained(struct sg_table *table, int nents, struct scatterlist *first_chunk, unsigned int nents_first_chunk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sg_pool.c (ffffffff8189e760)
Location: lib/sg_pool.c:112
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_alloc_sgtables
  - drivers/scsi/scsi_lib.c:scsi_alloc_sgtables
```
**Symbols:**

```
ffffffff8189e760-ffffffff8189e814: sg_alloc_table_chained (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int sg_alloc_table_chained(struct sg_table *table, int nents, struct scatterlist *first_chunk, unsigned int nents_first_chunk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sg_pool.c (ffffffff818e0d30)
Location: lib/sg_pool.c:112
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_alloc_sgtables
  - drivers/scsi/scsi_lib.c:scsi_alloc_sgtables
```
**Symbols:**

```
ffffffff818e0d30-ffffffff818e0de4: sg_alloc_table_chained (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int sg_alloc_table_chained(struct sg_table *table, int nents, struct scatterlist *first_chunk, unsigned int nents_first_chunk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sg_pool.c (ffffffff819278a0)
Location: lib/sg_pool.c:112
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_alloc_sgtables
  - drivers/scsi/scsi_lib.c:scsi_alloc_sgtables
```
**Symbols:**

```
ffffffff819278a0-ffffffff81927954: sg_alloc_table_chained (STB_GLOBAL)
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
int sg_alloc_table_chained(struct sg_table *table, int nents, struct scatterlist *first_chunk, unsigned int nents_first_chunk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/sg_pool.c (ffff8000106677d0)
Location: lib/sg_pool.c:111
Inline: True
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_init_io
  - drivers/scsi/scsi_lib.c:scsi_init_io
```
**Symbols:**

```
ffff8000106677d0-ffff800010667898: sg_alloc_table_chained (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int sg_alloc_table_chained(struct sg_table *table, int nents, struct scatterlist *first_chunk, unsigned int nents_first_chunk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/sg_pool.c (c080ff64)
Location: lib/sg_pool.c:111
Inline: True
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_init_io
  - drivers/scsi/scsi_lib.c:scsi_init_io
```
**Symbols:**

```
c080ff64-c0810028: sg_alloc_table_chained (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int sg_alloc_table_chained(struct sg_table *table, int nents, struct scatterlist *first_chunk, unsigned int nents_first_chunk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sg_pool.c (c00000000081cb80)
Location: lib/sg_pool.c:111
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_init_io
  - drivers/scsi/scsi_lib.c:scsi_init_io
```
**Symbols:**

```
c00000000081cb80-c00000000081cc9c: sg_alloc_table_chained (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int sg_alloc_table_chained(struct sg_table *table, int nents, struct scatterlist *first_chunk, unsigned int nents_first_chunk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/sg_pool.c (ffffffe000492e18)
Location: lib/sg_pool.c:111
Inline: True
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_init_io
  - drivers/scsi/scsi_lib.c:scsi_init_io
```
**Symbols:**

```
ffffffe000492e18-ffffffe000492eb4: sg_alloc_table_chained (STB_GLOBAL)
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
int sg_alloc_table_chained(struct sg_table *table, int nents, struct scatterlist *first_chunk, unsigned int nents_first_chunk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/sg_pool.c (ffffffff81552ae0)
Location: lib/sg_pool.c:111
Inline: True
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_init_io
  - drivers/scsi/scsi_lib.c:scsi_init_io
```
**Symbols:**

```
ffffffff81552ae0-ffffffff81552b76: sg_alloc_table_chained (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int sg_alloc_table_chained(struct sg_table *table, int nents, struct scatterlist *first_chunk, unsigned int nents_first_chunk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/sg_pool.c (ffffffff81542dc0)
Location: lib/sg_pool.c:111
Inline: True
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_init_io
  - drivers/scsi/scsi_lib.c:scsi_init_io
```
**Symbols:**

```
ffffffff81542dc0-ffffffff81542e56: sg_alloc_table_chained (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int sg_alloc_table_chained(struct sg_table *table, int nents, struct scatterlist *first_chunk, unsigned int nents_first_chunk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/sg_pool.c (ffffffff8154e820)
Location: lib/sg_pool.c:111
Inline: True
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_init_io
  - drivers/scsi/scsi_lib.c:scsi_init_io
```
**Symbols:**

```
ffffffff8154e820-ffffffff8154e8b6: sg_alloc_table_chained (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int sg_alloc_table_chained(struct sg_table *table, int nents, struct scatterlist *first_chunk, unsigned int nents_first_chunk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/sg_pool.c (ffffffff81568670)
Location: lib/sg_pool.c:111
Inline: True
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_init_io
  - drivers/scsi/scsi_lib.c:scsi_init_io
```
**Symbols:**

```
ffffffff81568670-ffffffff81568706: sg_alloc_table_chained (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
