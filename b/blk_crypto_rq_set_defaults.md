# Function: <code>blk_crypto_rq_set_defaults</code>

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
In block/blk-core.c (ffffffff8154279f)
Location: block/blk-crypto-internal.h:52
Inline: True
Inline callers:
  - block/blk-core.c:blk_rq_init
```
```
In block/blk-mq.c (ffffffff8154e479)
Location: block/blk-crypto-internal.h:52
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_rq_ctx_init
```
```
In block/blk-crypto.c (ffffffff81581b4c)
Location: block/blk-crypto-internal.h:52
Inline: True
Inline callers:
  - block/blk-crypto.c:__blk_crypto_free_request
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
In block/blk-core.c (ffffffff8155ee4f)
Location: block/blk-crypto-internal.h:52
Inline: True
Inline callers:
  - block/blk-core.c:blk_rq_init
```
```
In block/blk-mq.c (ffffffff8156a897)
Location: block/blk-crypto-internal.h:52
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_rq_ctx_init
```
```
In block/blk-crypto.c (ffffffff8159eb3c)
Location: block/blk-crypto-internal.h:52
Inline: True
Inline callers:
  - block/blk-crypto.c:__blk_crypto_free_request
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
In block/blk-core.c (ffffffff8156769f)
Location: block/blk-crypto-internal.h:52
Inline: True
Inline callers:
  - block/blk-core.c:blk_rq_init
```
```
In block/blk-mq.c (ffffffff815727df)
Location: block/blk-crypto-internal.h:52
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_rq_ctx_init
```
```
In block/blk-crypto.c (ffffffff815a590c)
Location: block/blk-crypto-internal.h:52
Inline: True
Inline callers:
  - block/blk-crypto.c:__blk_crypto_free_request
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
In block/blk-core.c (ffffffff815cbdb5)
Location: block/blk-crypto-internal.h:52
Inline: True
Inline callers:
  - block/blk-core.c:blk_rq_init
```
```
In block/blk-mq.c (ffffffff815d6e0f)
Location: block/blk-crypto-internal.h:52
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_rq_ctx_init
```
```
In block/blk-crypto.c (ffffffff8160e3dc)
Location: block/blk-crypto-internal.h:52
Inline: True
Inline callers:
  - block/blk-crypto.c:__blk_crypto_free_request
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
In block/blk-mq.c (ffffffff81682b15)
Location: block/blk-crypto-internal.h:57
Inline: True
Inline callers:
  - block/blk-mq.c:blk_rq_init
```
```
In block/blk-crypto.c (ffffffff816c1a7c)
Location: block/blk-crypto-internal.h:57
Inline: True
Inline callers:
  - block/blk-crypto.c:__blk_crypto_free_request
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
In block/blk-mq.c (ffffffff81740185)
Location: block/blk-crypto-internal.h:57
Inline: True
Inline callers:
  - block/blk-mq.c:blk_rq_init
```
```
In block/blk-crypto.c (ffffffff81782c5c)
Location: block/blk-crypto-internal.h:57
Inline: True
Inline callers:
  - block/blk-crypto.c:__blk_crypto_free_request
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
In block/blk-mq.c (ffffffff8177c675)
Location: block/blk-crypto-internal.h:57
Inline: True
Inline callers:
  - block/blk-mq.c:blk_rq_init
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
In block/blk-mq.c (ffffffff817bea05)
Location: block/blk-crypto-internal.h:57
Inline: True
Inline callers:
  - block/blk-mq.c:blk_rq_init
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
