# Function: <code>__blk_crypto_init_request</code>

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
<summary>In <code>5.8</code>: ✅</summary>

```c
blk_status_t __blk_crypto_init_request(struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-crypto.c (ffffffff81581af0)
Location: block/blk-crypto.c:208
Inline: False
Direct callers:
  - block/blk-core.c:blk_insert_cloned_request
  - block/blk-mq.c:blk_mq_make_request
```
**Symbols:**

```
ffffffff81581af0-ffffffff81581b1b: __blk_crypto_init_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
blk_status_t __blk_crypto_init_request(struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-crypto.c (ffffffff8159eae0)
Location: block/blk-crypto.c:219
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_submit_bio
```
**Symbols:**

```
ffffffff8159eae0-ffffffff8159eb0b: __blk_crypto_init_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
blk_status_t __blk_crypto_init_request(struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-crypto.c (ffffffff815a58b0)
Location: block/blk-crypto.c:219
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_submit_bio
```
**Symbols:**

```
ffffffff815a58b0-ffffffff815a58db: __blk_crypto_init_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
blk_status_t __blk_crypto_init_request(struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-crypto.c (ffffffff8160e380)
Location: block/blk-crypto.c:219
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_submit_bio
```
**Symbols:**

```
ffffffff8160e380-ffffffff8160e3ab: __blk_crypto_init_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
blk_status_t __blk_crypto_init_request(struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-crypto.c (ffffffff816c1a10)
Location: block/blk-crypto.c:221
Inline: False
Direct callers:
  - block/blk-mq.c:blk_insert_cloned_request
  - block/blk-mq.c:blk_mq_submit_bio
```
**Symbols:**

```
ffffffff816c1a10-ffffffff816c1a45: __blk_crypto_init_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
blk_status_t __blk_crypto_init_request(struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-crypto.c (ffffffff81782be0)
Location: block/blk-crypto.c:227
Inline: False
Direct callers:
  - block/blk-mq.c:blk_insert_cloned_request
  - block/blk-mq.c:blk_mq_submit_bio
```
**Symbols:**

```
ffffffff81782be0-ffffffff81782c15: __blk_crypto_init_request (STB_GLOBAL)
```
</details>
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
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
</ul>
