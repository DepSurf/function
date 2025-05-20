# Function: <code>hctx_may_queue</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff813c6fd9)
Location: block/blk-mq-tag.c:120
Inline: True
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
In block/blk-mq-tag.c (ffffffff8140b1f5)
Location: block/blk-mq-tag.c:120
Inline: True
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
In block/blk-mq-tag.c (ffffffff81425975)
Location: block/blk-mq-tag.c:66
Inline: True
Inline callers:
  - block/blk-mq-tag.c:__bt_get
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
In block/blk-mq-tag.c (ffffffff814336be)
Location: block/blk-mq-tag.c:66
Inline: True
Inline callers:
  - block/blk-mq-tag.c:__blk_mq_get_tag
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
In block/blk-mq-tag.c (ffffffff8145f2ae)
Location: block/blk-mq-tag.c:66
Inline: True
Inline callers:
  - block/blk-mq-tag.c:__blk_mq_get_tag
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
In block/blk-mq-tag.c (ffffffff81492c3e)
Location: block/blk-mq-tag.c:69
Inline: True
Inline callers:
  - block/blk-mq-tag.c:__blk_mq_get_tag
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
In block/blk-mq-tag.c (ffffffff814acb5e)
Location: block/blk-mq-tag.c:69
Inline: True
Inline callers:
  - block/blk-mq-tag.c:__blk_mq_get_tag
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
In block/blk-mq-tag.c (ffffffff814dae6e)
Location: block/blk-mq-tag.c:70
Inline: True
Inline callers:
  - block/blk-mq-tag.c:__blk_mq_get_tag
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
In block/blk-mq-tag.c (ffffffff814f422e)
Location: block/blk-mq-tag.c:71
Inline: True
Inline callers:
  - block/blk-mq-tag.c:__blk_mq_get_tag
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
In block/blk-mq-tag.c (ffffffff81554d0b)
Location: block/blk-mq-tag.c:63
Inline: True
Inline callers:
  - block/blk-mq-tag.c:__blk_mq_get_driver_tag
  - block/blk-mq-tag.c:__blk_mq_get_driver_tag
  - block/blk-mq-tag.c:__blk_mq_get_tag
  - block/blk-mq-tag.c:__blk_mq_get_tag
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
In block/blk-mq.c (ffffffff8156b5f6)
Location: block/blk-mq.h:289
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_get_driver_tag
```
```
In block/blk-mq-tag.c (ffffffff81570f68)
Location: block/blk-mq.h:289
Inline: True
Inline callers:
  - block/blk-mq-tag.c:__blk_mq_get_tag
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
In block/blk-mq.c (ffffffff815732bd)
Location: block/blk-mq.h:307
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_get_driver_tag
```
```
In block/blk-mq-tag.c (ffffffff81578dc8)
Location: block/blk-mq.h:307
Inline: True
Inline callers:
  - block/blk-mq-tag.c:__blk_mq_get_tag
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
In block/blk-mq.c (ffffffff815da21d)
Location: block/blk-mq.h:322
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_get_driver_tag
```
```
In block/blk-mq-tag.c (ffffffff815ddff8)
Location: block/blk-mq.h:322
Inline: True
Inline callers:
  - block/blk-mq-tag.c:__blk_mq_get_tag
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
In block/blk-mq.c (ffffffff81687d05)
Location: block/blk-mq.h:341
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_get_driver_tag
```
```
In block/blk-mq-tag.c (ffffffff8168c076)
Location: block/blk-mq.h:341
Inline: True
Inline callers:
  - block/blk-mq-tag.c:__blk_mq_get_tag
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
In block/blk-mq.c (ffffffff817460ae)
Location: block/blk-mq.h:341
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_get_driver_tag
```
```
In block/blk-mq-tag.c (ffffffff8174a7f6)
Location: block/blk-mq.h:341
Inline: True
Inline callers:
  - block/blk-mq-tag.c:__blk_mq_get_tag
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
In block/blk-mq.c (ffffffff817828ee)
Location: block/blk-mq.h:391
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_get_driver_tag
```
```
In block/blk-mq-tag.c (ffffffff81786ed6)
Location: block/blk-mq.h:391
Inline: True
Inline callers:
  - block/blk-mq-tag.c:__blk_mq_get_tag
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
In block/blk-mq.c (ffffffff817c4c7b)
Location: block/blk-mq.h:414
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_alloc_driver_tag
```
```
In block/blk-mq-tag.c (ffffffff817c95b6)
Location: block/blk-mq.h:414
Inline: True
Inline callers:
  - block/blk-mq-tag.c:__blk_mq_get_tag
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
In block/blk-mq-tag.c (ffff8000105f3e8c)
Location: block/blk-mq-tag.c:71
Inline: True
Inline callers:
  - block/blk-mq-tag.c:__blk_mq_get_tag
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
In block/blk-mq-tag.c (c079fad8)
Location: block/blk-mq-tag.c:71
Inline: True
Inline callers:
  - block/blk-mq-tag.c:__blk_mq_get_tag
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
In block/blk-mq-tag.c (c00000000078b544)
Location: block/blk-mq-tag.c:71
Inline: True
Inline callers:
  - block/blk-mq-tag.c:__blk_mq_get_tag
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
In block/blk-mq-tag.c (ffffffe000432060)
Location: block/blk-mq-tag.c:71
Inline: True
Inline callers:
  - block/blk-mq-tag.c:__blk_mq_get_tag
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
In block/blk-mq-tag.c (ffffffff814ec80e)
Location: block/blk-mq-tag.c:71
Inline: True
Inline callers:
  - block/blk-mq-tag.c:__blk_mq_get_tag
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
In block/blk-mq-tag.c (ffffffff814dcd5e)
Location: block/blk-mq-tag.c:71
Inline: True
Inline callers:
  - block/blk-mq-tag.c:__blk_mq_get_tag
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
In block/blk-mq-tag.c (ffffffff814e889e)
Location: block/blk-mq-tag.c:71
Inline: True
Inline callers:
  - block/blk-mq-tag.c:__blk_mq_get_tag
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
In block/blk-mq-tag.c (ffffffff8150183e)
Location: block/blk-mq-tag.c:71
Inline: True
Inline callers:
  - block/blk-mq-tag.c:__blk_mq_get_tag
```
</details>
</li>
</ul>

## Differences
