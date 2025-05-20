# Function: <code>bt_tags_for_each</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void bt_tags_for_each(struct blk_mq_tags *tags, struct blk_mq_bitmap_tags *bt, unsigned int off, busy_tag_iter_fn *fn, void *data, bool reserved);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff813c6d50)
Location: block/blk-mq-tag.c:444
Inline: False
Direct callers:
  - block/blk-mq-tag.c:blk_mq_all_tag_busy_iter
  - block/blk-mq-tag.c:blk_mq_all_tag_busy_iter
```
**Symbols:**

```
ffffffff813c6d50-ffffffff813c6e26: bt_tags_for_each (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void bt_tags_for_each(struct blk_mq_tags *tags, struct blk_mq_bitmap_tags *bt, unsigned int off, busy_tag_iter_fn *fn, void *data, bool reserved);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff8140af50)
Location: block/blk-mq-tag.c:444
Inline: False
Direct callers:
  - block/blk-mq-tag.c:blk_mq_tagset_busy_iter
  - block/blk-mq-tag.c:blk_mq_tagset_busy_iter
```
**Symbols:**

```
ffffffff8140af50-ffffffff8140b026: bt_tags_for_each (STB_LOCAL)
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
In block/blk-mq-tag.c (ffffffff81425c60)
Location: block/blk-mq-tag.c:270
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_tagset_busy_iter
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
In block/blk-mq-tag.c (ffffffff81433812)
Location: block/blk-mq-tag.c:257
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_tagset_busy_iter
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
In block/blk-mq-tag.c (ffffffff8145f43d)
Location: block/blk-mq-tag.c:267
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_tagset_busy_iter
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
In block/blk-mq-tag.c (ffffffff81492d0d)
Location: block/blk-mq-tag.c:283
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_tagset_busy_iter
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
In block/blk-mq-tag.c (ffffffff814acc23)
Location: block/blk-mq-tag.c:310
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_tagset_busy_iter
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
In block/blk-mq-tag.c (ffffffff814daf3a)
Location: block/blk-mq-tag.c:303
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_tagset_busy_iter
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
In block/blk-mq-tag.c (ffffffff814f42fa)
Location: block/blk-mq-tag.c:304
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_tagset_busy_iter
  - block/blk-mq-tag.c:blk_mq_tagset_busy_iter
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff81555198)
Location: block/blk-mq-tag.c:339
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_all_tag_iter
  - block/blk-mq-tag.c:blk_mq_all_tag_iter
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff8157184f)
Location: block/blk-mq-tag.c:299
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_all_tag_iter
  - block/blk-mq-tag.c:blk_mq_all_tag_iter
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff8157987d)
Location: block/blk-mq-tag.c:322
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_all_tag_iter
  - block/blk-mq-tag.c:blk_mq_all_tag_iter
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
In block/blk-mq-tag.c (ffffffff815de457)
Location: block/blk-mq-tag.c:323
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_tagset_busy_iter
  - block/blk-mq-tag.c:blk_mq_tagset_busy_iter
  - block/blk-mq-tag.c:blk_mq_all_tag_iter
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
In block/blk-mq-tag.c (ffffffff8168c35c)
Location: block/blk-mq-tag.c:379
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_tagset_busy_iter
  - block/blk-mq-tag.c:blk_mq_tagset_busy_iter
  - block/blk-mq-tag.c:blk_mq_all_tag_iter
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
In block/blk-mq-tag.c (ffffffff8174aafc)
Location: block/blk-mq-tag.c:373
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_tagset_busy_iter
  - block/blk-mq-tag.c:blk_mq_tagset_busy_iter
  - block/blk-mq-tag.c:blk_mq_all_tag_iter
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
In block/blk-mq-tag.c (ffffffff817871e3)
Location: block/blk-mq-tag.c:380
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_tagset_busy_iter
  - block/blk-mq-tag.c:blk_mq_tagset_busy_iter
  - block/blk-mq-tag.c:blk_mq_all_tag_iter
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
In block/blk-mq-tag.c (ffffffff817c98c3)
Location: block/blk-mq-tag.c:380
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_tagset_busy_iter
  - block/blk-mq-tag.c:blk_mq_tagset_busy_iter
  - block/blk-mq-tag.c:blk_mq_all_tag_iter
  - block/blk-mq-tag.c:blk_mq_all_tag_iter
```
</details>
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
In block/blk-mq-tag.c (ffff8000105f3f54)
Location: block/blk-mq-tag.c:304
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_tagset_busy_iter
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
In block/blk-mq-tag.c (c079fc50)
Location: block/blk-mq-tag.c:304
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_tagset_busy_iter
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
In block/blk-mq-tag.c (c00000000078b714)
Location: block/blk-mq-tag.c:304
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_tagset_busy_iter
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
In block/blk-mq-tag.c (ffffffe000432104)
Location: block/blk-mq-tag.c:304
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_tagset_busy_iter
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
In block/blk-mq-tag.c (ffffffff814ec8da)
Location: block/blk-mq-tag.c:304
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_tagset_busy_iter
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
In block/blk-mq-tag.c (ffffffff814dce2a)
Location: block/blk-mq-tag.c:304
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_tagset_busy_iter
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
In block/blk-mq-tag.c (ffffffff814e896a)
Location: block/blk-mq-tag.c:304
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_tagset_busy_iter
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
In block/blk-mq-tag.c (ffffffff8150190a)
Location: block/blk-mq-tag.c:304
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_tagset_busy_iter
  - block/blk-mq-tag.c:blk_mq_tagset_busy_iter
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
</ul>
