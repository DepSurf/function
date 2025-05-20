# Function: <code>bt_alloc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int bt_alloc(struct blk_mq_bitmap_tags *bt, unsigned int depth, int node, bool reserved);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff813c7350)
Location: block/blk-mq-tag.c:537
Inline: False
Direct callers:
  - block/blk-mq-tag.c:blk_mq_init_tags
  - block/blk-mq-tag.c:blk_mq_init_tags
```
**Symbols:**

```
ffffffff813c7350-ffffffff813c748d: bt_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-mq-tag.c (ffffffff8140b580)
Location: block/blk-mq-tag.c:574
Inline: True
Direct callers:
  - block/blk-mq-tag.c:blk_mq_init_tags
  - block/blk-mq-tag.c:blk_mq_init_tags
```
**Symbols:**

```
ffffffff8140b580-ffffffff8140b6b6: bt_alloc.constprop.11 (STB_LOCAL)
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
In block/blk-mq-tag.c (ffffffff814261b6)
Location: block/blk-mq-tag.c:359
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_init_tags
  - block/blk-mq-tag.c:blk_mq_init_tags
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
In block/blk-mq-tag.c (ffffffff81433f12)
Location: block/blk-mq-tag.c:344
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_init_tags
  - block/blk-mq-tag.c:blk_mq_init_tags
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
In block/blk-mq-tag.c (ffffffff8145fc42)
Location: block/blk-mq-tag.c:354
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_init_tags
  - block/blk-mq-tag.c:blk_mq_init_tags
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
In block/blk-mq-tag.c (ffffffff81493535)
Location: block/blk-mq-tag.c:341
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_init_tags
  - block/blk-mq-tag.c:blk_mq_init_tags
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
In block/blk-mq-tag.c (ffffffff814ad565)
Location: block/blk-mq-tag.c:411
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_init_tags
  - block/blk-mq-tag.c:blk_mq_init_tags
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
In block/blk-mq-tag.c (ffffffff814db7e2)
Location: block/blk-mq-tag.c:404
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_init_tags
  - block/blk-mq-tag.c:blk_mq_init_tags
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
In block/blk-mq-tag.c (ffffffff814f4c12)
Location: block/blk-mq-tag.c:436
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_init_tags
  - block/blk-mq-tag.c:blk_mq_init_tags
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
In block/blk-mq-tag.c (ffffffff815555e6)
Location: block/blk-mq-tag.c:483
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_init_tags
  - block/blk-mq-tag.c:blk_mq_init_tags
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
In block/blk-mq-tag.c (ffffffff81571e36)
Location: block/blk-mq-tag.c:441
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_init_tags
  - block/blk-mq-tag.c:blk_mq_init_tags
  - block/blk-mq-tag.c:blk_mq_init_shared_sbitmap
  - block/blk-mq-tag.c:blk_mq_init_shared_sbitmap
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
In block/blk-mq-tag.c (ffffffff81579e50)
Location: block/blk-mq-tag.c:467
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_init_tags
  - block/blk-mq-tag.c:blk_mq_init_tags
  - block/blk-mq-tag.c:blk_mq_init_shared_sbitmap
  - block/blk-mq-tag.c:blk_mq_init_shared_sbitmap
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
In block/blk-mq-tag.c (ffffffff815defc4)
Location: block/blk-mq-tag.c:468
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_init_bitmaps
  - block/blk-mq-tag.c:blk_mq_init_bitmaps
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
In block/blk-mq-tag.c (ffffffff8168d737)
Location: block/blk-mq-tag.c:539
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_init_bitmaps
  - block/blk-mq-tag.c:blk_mq_init_bitmaps
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
In block/blk-mq-tag.c (ffffffff8174bf37)
Location: block/blk-mq-tag.c:532
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_init_bitmaps
  - block/blk-mq-tag.c:blk_mq_init_bitmaps
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
In block/blk-mq-tag.c (ffffffff81788657)
Location: block/blk-mq-tag.c:539
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_init_bitmaps
  - block/blk-mq-tag.c:blk_mq_init_bitmaps
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
In block/blk-mq-tag.c (ffffffff817cad27)
Location: block/blk-mq-tag.c:539
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_init_bitmaps
  - block/blk-mq-tag.c:blk_mq_init_bitmaps
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
In block/blk-mq-tag.c (ffff8000105f4a54)
Location: block/blk-mq-tag.c:436
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_init_tags
  - block/blk-mq-tag.c:blk_mq_init_tags
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
In block/blk-mq-tag.c (c07a06ac)
Location: block/blk-mq-tag.c:436
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_init_tags
  - block/blk-mq-tag.c:blk_mq_init_tags
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
In block/blk-mq-tag.c (c00000000078c448)
Location: block/blk-mq-tag.c:436
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_init_tags
  - block/blk-mq-tag.c:blk_mq_init_tags
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
In block/blk-mq-tag.c (ffffffe000432952)
Location: block/blk-mq-tag.c:436
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_init_tags
  - block/blk-mq-tag.c:blk_mq_init_tags
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
In block/blk-mq-tag.c (ffffffff814ed1f2)
Location: block/blk-mq-tag.c:436
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_init_tags
  - block/blk-mq-tag.c:blk_mq_init_tags
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
In block/blk-mq-tag.c (ffffffff814dd742)
Location: block/blk-mq-tag.c:436
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_init_tags
  - block/blk-mq-tag.c:blk_mq_init_tags
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
In block/blk-mq-tag.c (ffffffff814e9282)
Location: block/blk-mq-tag.c:436
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_init_tags
  - block/blk-mq-tag.c:blk_mq_init_tags
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
In block/blk-mq-tag.c (ffffffff81502242)
Location: block/blk-mq-tag.c:436
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_init_tags
  - block/blk-mq-tag.c:blk_mq_init_tags
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
