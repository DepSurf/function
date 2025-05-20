# Function: <code>__blk_crypto_rq_put_keyslot</code>

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
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void __blk_crypto_rq_put_keyslot(struct request *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-crypto.c (ffffffff817c2e97)
Location: block/blk-crypto.c:235
Inline: True
Inline callers:
  - block/blk-crypto.c:__blk_crypto_free_request
Direct callers:
  - block/blk-merge.c:attempt_merge
  - block/blk-mq.c:blk_mq_end_request_batch
  - block/blk-mq.c:blk_update_request
  - block/blk-mq.c:blk_update_request
  - block/blk-mq.c:blk_update_request
```
**Symbols:**

```
ffffffff817c2e10-ffffffff817c2e40: __blk_crypto_rq_put_keyslot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void __blk_crypto_rq_put_keyslot(struct request *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-crypto.c (ffffffff81807b27)
Location: block/blk-crypto.c:235
Inline: True
Inline callers:
  - block/blk-crypto.c:__blk_crypto_free_request
Direct callers:
  - block/blk-merge.c:attempt_merge
  - block/blk-mq.c:blk_mq_end_request_batch
  - block/blk-mq.c:blk_update_request
  - block/blk-mq.c:blk_update_request
  - block/blk-mq.c:blk_update_request
```
**Symbols:**

```
ffffffff81807aa0-ffffffff81807ad0: __blk_crypto_rq_put_keyslot (STB_GLOBAL)
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
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
