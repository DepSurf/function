# Function: <code>blk_mq_all_tag_busy_iter</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void blk_mq_all_tag_busy_iter(struct blk_mq_tags *tags, busy_tag_iter_fn *fn, void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff813c6e30)
Location: block/blk-mq-tag.c:467
Inline: False
```
**Symbols:**

```
ffffffff813c6e30-ffffffff813c6e84: blk_mq_all_tag_busy_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff8140b06a)
Location: block/blk-mq-tag.c:467
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_tagset_busy_iter
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff81425c55)
Location: block/blk-mq-tag.c:284
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_tagset_busy_iter
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff81433800)
Location: block/blk-mq-tag.c:271
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_tagset_busy_iter
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff8145f428)
Location: block/blk-mq-tag.c:281
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_tagset_busy_iter
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff81492cf8)
Location: block/blk-mq-tag.c:297
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_tagset_busy_iter
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff814acc10)
Location: block/blk-mq-tag.c:334
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_tagset_busy_iter
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff814daf25)
Location: block/blk-mq-tag.c:327
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_tagset_busy_iter
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff814f42e5)
Location: block/blk-mq-tag.c:328
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_tagset_busy_iter
```
</details>
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
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffff8000105f3f48)
Location: block/blk-mq-tag.c:328
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_tagset_busy_iter
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (c079fc40)
Location: block/blk-mq-tag.c:328
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_tagset_busy_iter
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (c00000000078b65c)
Location: block/blk-mq-tag.c:328
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_tagset_busy_iter
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffe0004320fa)
Location: block/blk-mq-tag.c:328
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_tagset_busy_iter
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff814ec8c5)
Location: block/blk-mq-tag.c:328
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_tagset_busy_iter
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff814dce15)
Location: block/blk-mq-tag.c:328
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_tagset_busy_iter
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff814e8955)
Location: block/blk-mq-tag.c:328
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_tagset_busy_iter
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff815018f5)
Location: block/blk-mq-tag.c:328
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_tagset_busy_iter
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
