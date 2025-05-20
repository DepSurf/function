# Function: <code>__blk_mq_all_tag_iter</code>

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
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void __blk_mq_all_tag_iter(struct blk_mq_tags *tags, busy_tag_iter_fn *fn, void *priv, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff815548d0)
Location: block/blk-mq-tag.c:353
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_all_tag_iter
Direct callers:
  - block/blk-mq-tag.c:blk_mq_tagset_wait_completed_request
```
**Symbols:**

```
ffffffff815548d0-ffffffff81554b00: __blk_mq_all_tag_iter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void __blk_mq_all_tag_iter(struct blk_mq_tags *tags, busy_tag_iter_fn *fn, void *priv, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff81571000)
Location: block/blk-mq-tag.c:313
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_all_tag_iter
Direct callers:
  - block/blk-mq-tag.c:blk_mq_tagset_wait_completed_request
```
**Symbols:**

```
ffffffff81571000-ffffffff8157124f: __blk_mq_all_tag_iter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void __blk_mq_all_tag_iter(struct blk_mq_tags *tags, busy_tag_iter_fn *fn, void *priv, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff81579060)
Location: block/blk-mq-tag.c:336
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_all_tag_iter
Direct callers:
  - block/blk-mq-tag.c:blk_mq_tagset_wait_completed_request
```
**Symbols:**

```
ffffffff81579060-ffffffff8157927f: __blk_mq_all_tag_iter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff815de308)
Location: block/blk-mq-tag.c:337
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_tagset_busy_iter
  - block/blk-mq-tag.c:blk_mq_all_tag_iter
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff8168c349)
Location: block/blk-mq-tag.c:393
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_tagset_busy_iter
  - block/blk-mq-tag.c:blk_mq_all_tag_iter
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff8174aae9)
Location: block/blk-mq-tag.c:387
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_tagset_busy_iter
  - block/blk-mq-tag.c:blk_mq_all_tag_iter
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff817871d0)
Location: block/blk-mq-tag.c:394
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_tagset_busy_iter
  - block/blk-mq-tag.c:blk_mq_all_tag_iter
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff817c98b0)
Location: block/blk-mq-tag.c:394
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_tagset_busy_iter
  - block/blk-mq-tag.c:blk_mq_all_tag_iter
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
</ul>
