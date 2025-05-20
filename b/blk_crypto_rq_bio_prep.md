# Function: <code>blk_crypto_rq_bio_prep</code>

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
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff815432ad)
Location: block/blk-crypto-internal.h:147
Inline: True
Inline callers:
  - block/blk-core.c:blk_rq_prep_clone
```
```
In block/blk-mq.c (ffffffff8155108d)
Location: block/blk-crypto-internal.h:147
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_make_request
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
In block/blk-core.c (ffffffff8155fafb)
Location: block/blk-crypto-internal.h:157
Inline: True
Inline callers:
  - block/blk-core.c:blk_rq_prep_clone
```
```
In block/blk-mq.c (ffffffff8156ef49)
Location: block/blk-crypto-internal.h:157
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_submit_bio
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
In block/blk-core.c (ffffffff815687eb)
Location: block/blk-crypto-internal.h:157
Inline: True
Inline callers:
  - block/blk-core.c:blk_rq_prep_clone
```
```
In block/blk-mq.c (ffffffff81576b29)
Location: block/blk-crypto-internal.h:157
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_submit_bio
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
In block/blk-core.c (ffffffff815ccdcb)
Location: block/blk-crypto-internal.h:157
Inline: True
Inline callers:
  - block/blk-core.c:blk_rq_prep_clone
```
```
In block/blk-mq.c (ffffffff815db7d9)
Location: block/blk-crypto-internal.h:157
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_submit_bio
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
In block/blk-mq.c (ffffffff816846e9)
Location: block/blk-crypto-internal.h:169
Inline: True
Inline callers:
  - block/blk-mq.c:blk_rq_prep_clone
  - block/blk-mq.c:blk_mq_submit_bio
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
In block/blk-mq.c (ffffffff81742099)
Location: block/blk-crypto-internal.h:183
Inline: True
Inline callers:
  - block/blk-mq.c:blk_rq_prep_clone
  - block/blk-mq.c:blk_mq_submit_bio
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
In block/blk-mq.c (ffffffff8177da6d)
Location: block/blk-crypto-internal.h:200
Inline: True
Inline callers:
  - block/blk-mq.c:blk_rq_prep_clone
  - block/blk-mq.c:blk_mq_submit_bio
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
In block/blk-mq.c (ffffffff817bfdfa)
Location: block/blk-crypto-internal.h:200
Inline: True
Inline callers:
  - block/blk-mq.c:blk_rq_prep_clone
  - block/blk-mq.c:blk_mq_submit_bio
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
