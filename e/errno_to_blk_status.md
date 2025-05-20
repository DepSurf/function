# Function: <code>errno_to_blk_status</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
blk_status_t errno_to_blk_status(int errno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8141fad0)
Location: block/blk-core.c:155
Inline: False
Direct callers:
  - drivers/md/dm.c:__split_and_process_bio
```
**Symbols:**

```
ffffffff8141fad0-ffffffff8141fb0f: errno_to_blk_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
blk_status_t errno_to_blk_status(int errno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8144a600)
Location: block/blk-core.c:155
Inline: False
Direct callers:
  - drivers/md/dm.c:__split_and_process_bio
```
**Symbols:**

```
ffffffff8144a600-ffffffff8144a63f: errno_to_blk_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
blk_status_t errno_to_blk_status(int errno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8147d830)
Location: block/blk-core.c:228
Inline: False
Direct callers:
  - drivers/md/dm.c:__process_bio
  - drivers/md/dm.c:__split_and_process_bio
```
**Symbols:**

```
ffffffff8147d830-ffffffff8147d86f: errno_to_blk_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
blk_status_t errno_to_blk_status(int errno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8149af60)
Location: block/blk-core.c:146
Inline: False
Direct callers:
  - drivers/md/dm.c:__process_bio
  - drivers/md/dm.c:__split_and_process_bio
```
**Symbols:**

```
ffffffff8149af60-ffffffff8149af9f: errno_to_blk_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
blk_status_t errno_to_blk_status(int errno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814c90c0)
Location: block/blk-core.c:184
Inline: False
Direct callers:
  - drivers/md/dm.c:__process_bio
  - drivers/md/dm.c:__split_and_process_bio
```
**Symbols:**

```
ffffffff814c90c0-ffffffff814c90f1: errno_to_blk_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
blk_status_t errno_to_blk_status(int errno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814e22b0)
Location: block/blk-core.c:187
Inline: False
Direct callers:
  - drivers/md/dm.c:__process_bio
  - drivers/md/dm.c:__split_and_process_bio
```
**Symbols:**

```
ffffffff814e22b0-ffffffff814e22e1: errno_to_blk_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
blk_status_t errno_to_blk_status(int errno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81540f70)
Location: block/blk-core.c:195
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_submit_ioend
  - block/keyslot-manager.c:blk_ksm_get_slot_for_key
  - drivers/block/loop.c:lo_complete_rq
  - drivers/md/dm.c:__process_bio
  - drivers/md/dm.c:__split_and_process_bio
```
**Symbols:**

```
ffffffff81540f70-ffffffff81540fa1: errno_to_blk_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
blk_status_t errno_to_blk_status(int errno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8155dc00)
Location: block/blk-core.c:198
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_submit_ioend
  - block/keyslot-manager.c:blk_ksm_get_slot_for_key
  - drivers/block/loop.c:lo_complete_rq
  - drivers/md/dm.c:__split_and_process_bio
```
**Symbols:**

```
ffffffff8155dc00-ffffffff8155dc33: errno_to_blk_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
blk_status_t errno_to_blk_status(int errno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81566460)
Location: block/blk-core.c:199
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_submit_ioend
  - block/keyslot-manager.c:blk_ksm_get_slot_for_key
  - drivers/block/loop.c:lo_complete_rq
  - drivers/md/dm.c:__split_and_process_bio
```
**Symbols:**

```
ffffffff81566460-ffffffff81566493: errno_to_blk_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
blk_status_t errno_to_blk_status(int errno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff815ca860)
Location: block/blk-core.c:194
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_submit_ioend
  - block/keyslot-manager.c:blk_ksm_get_slot_for_key
  - drivers/block/loop.c:lo_complete_rq
  - drivers/md/dm.c:__split_and_process_bio
```
**Symbols:**

```
ffffffff815ca860-ffffffff815ca8bd: errno_to_blk_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
blk_status_t errno_to_blk_status(int errno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81675df0)
Location: block/blk-core.c:179
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_submit_ioend
  - block/blk-crypto-profile.c:blk_crypto_get_keyslot
  - drivers/block/loop.c:lo_complete_rq
```
**Symbols:**

```
ffffffff81675df0-ffffffff81675e61: errno_to_blk_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
blk_status_t errno_to_blk_status(int errno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81731dd0)
Location: block/blk-core.c:177
Inline: False
Direct callers:
  - fs/crypto/bio.c:fscrypt_decrypt_bio
  - fs/iomap/buffered-io.c:iomap_submit_ioend
  - block/blk-crypto-profile.c:blk_crypto_get_keyslot
  - drivers/block/loop.c:lo_complete_rq
```
**Symbols:**

```
ffffffff81731dd0-ffffffff81731e41: errno_to_blk_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
blk_status_t errno_to_blk_status(int errno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8176e160)
Location: block/blk-core.c:180
Inline: False
Direct callers:
  - fs/crypto/bio.c:fscrypt_decrypt_bio
  - fs/iomap/buffered-io.c:iomap_submit_ioend
  - block/blk-crypto-profile.c:blk_crypto_get_keyslot
  - drivers/block/loop.c:lo_complete_rq
```
**Symbols:**

```
ffffffff8176e160-ffffffff8176e1d1: errno_to_blk_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
blk_status_t errno_to_blk_status(int errno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff817b0380)
Location: block/blk-core.c:181
Inline: False
Direct callers:
  - fs/crypto/bio.c:fscrypt_decrypt_bio
  - fs/iomap/buffered-io.c:iomap_submit_ioend
  - block/blk-crypto-profile.c:blk_crypto_get_keyslot
  - drivers/block/loop.c:lo_complete_rq
```
**Symbols:**

```
ffffffff817b0380-ffffffff817b03f1: errno_to_blk_status (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
blk_status_t errno_to_blk_status(int errno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffff8000105df5b0)
Location: block/blk-core.c:187
Inline: False
Direct callers:
  - drivers/md/dm.c:__process_bio
  - drivers/md/dm.c:__split_and_process_bio
```
**Symbols:**

```
ffff8000105df5b0-ffff8000105df61c: errno_to_blk_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
blk_status_t errno_to_blk_status(int errno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (c078c3ac)
Location: block/blk-core.c:187
Inline: False
Direct callers:
  - drivers/md/dm.c:__process_bio
  - drivers/md/dm.c:__split_and_process_bio
```
**Symbols:**

```
c078c3ac-c078c3fc: errno_to_blk_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
blk_status_t errno_to_blk_status(int errno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (c0000000007717d0)
Location: block/blk-core.c:187
Inline: False
Direct callers:
  - drivers/md/dm.c:__process_bio
  - drivers/md/dm.c:__split_and_process_bio
```
**Symbols:**

```
c0000000007717d0-c000000000771828: errno_to_blk_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
blk_status_t errno_to_blk_status(int errno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffe000422008)
Location: block/blk-core.c:187
Inline: False
Direct callers:
  - drivers/md/dm.c:__process_bio
  - drivers/md/dm.c:__split_and_process_bio
```
**Symbols:**

```
ffffffe000422008-ffffffe000422058: errno_to_blk_status (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
blk_status_t errno_to_blk_status(int errno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814da890)
Location: block/blk-core.c:187
Inline: False
Direct callers:
  - drivers/md/dm.c:__process_bio
  - drivers/md/dm.c:__split_and_process_bio
```
**Symbols:**

```
ffffffff814da890-ffffffff814da8c1: errno_to_blk_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
blk_status_t errno_to_blk_status(int errno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814cb240)
Location: block/blk-core.c:187
Inline: False
Direct callers:
  - drivers/nvdimm/pmem.c:pmem_make_request
  - drivers/nvdimm/btt.c:btt_make_request
  - drivers/md/dm.c:__process_bio
  - drivers/md/dm.c:__split_and_process_bio
```
**Symbols:**

```
ffffffff814cb240-ffffffff814cb271: errno_to_blk_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
blk_status_t errno_to_blk_status(int errno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814d6920)
Location: block/blk-core.c:187
Inline: False
Direct callers:
  - drivers/md/dm.c:__process_bio
  - drivers/md/dm.c:__split_and_process_bio
```
**Symbols:**

```
ffffffff814d6920-ffffffff814d6951: errno_to_blk_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
blk_status_t errno_to_blk_status(int errno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814ef530)
Location: block/blk-core.c:187
Inline: False
Direct callers:
  - drivers/md/dm.c:__process_bio
  - drivers/md/dm.c:__split_and_process_bio
```
**Symbols:**

```
ffffffff814ef530-ffffffff814ef561: errno_to_blk_status (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
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
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
