# Function: <code>blk_mq_get_tags</code>

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
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long unsigned int blk_mq_get_tags(struct blk_mq_alloc_data *data, int nr_tags, unsigned int *offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff8168c8b0)
Location: block/blk-mq-tag.c:115
Inline: False
Direct callers:
  - block/blk-mq.c:__blk_mq_alloc_requests_batch
```
**Symbols:**

```
ffffffff8168c8b0-ffffffff8168c935: blk_mq_get_tags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long unsigned int blk_mq_get_tags(struct blk_mq_alloc_data *data, int nr_tags, unsigned int *offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff8174b090)
Location: block/blk-mq-tag.c:111
Inline: False
Direct callers:
  - block/blk-mq.c:__blk_mq_alloc_requests_batch
```
**Symbols:**

```
ffffffff8174b090-ffffffff8174b115: blk_mq_get_tags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long unsigned int blk_mq_get_tags(struct blk_mq_alloc_data *data, int nr_tags, unsigned int *offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff817877b0)
Location: block/blk-mq-tag.c:118
Inline: False
Direct callers:
  - block/blk-mq.c:__blk_mq_alloc_requests
```
**Symbols:**

```
ffffffff817877b0-ffffffff81787835: blk_mq_get_tags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long unsigned int blk_mq_get_tags(struct blk_mq_alloc_data *data, int nr_tags, unsigned int *offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff817c9e80)
Location: block/blk-mq-tag.c:118
Inline: False
Direct callers:
  - block/blk-mq.c:__blk_mq_alloc_requests_batch
```
**Symbols:**

```
ffffffff817c9e80-ffffffff817c9f05: blk_mq_get_tags (STB_GLOBAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
