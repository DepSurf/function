# Function: <code>ahash_restore_req</code>

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
In crypto/ahash.c (ffffffff813a2bea)
Location: crypto/ahash.c:286
Inline: True
Inline callers:
  - crypto/ahash.c:ahash_def_finup_finish2
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
In crypto/ahash.c (ffffffff813ded9a)
Location: crypto/ahash.c:269
Inline: True
Inline callers:
  - crypto/ahash.c:ahash_def_finup_finish2
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
In crypto/ahash.c (ffffffff813f732a)
Location: crypto/ahash.c:269
Inline: True
Inline callers:
  - crypto/ahash.c:ahash_def_finup_finish2
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void ahash_restore_req(struct ahash_request *req, int err);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/ahash.c (ffffffff81403810)
Location: crypto/ahash.c:273
Inline: False
Direct callers:
  - crypto/ahash.c:ahash_def_finup_finish1
  - crypto/ahash.c:ahash_def_finup_done2
  - crypto/ahash.c:crypto_ahash_op
  - crypto/ahash.c:ahash_op_unaligned_done
```
**Symbols:**

```
ffffffff81403810-ffffffff81403877: ahash_restore_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void ahash_restore_req(struct ahash_request *req, int err);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/ahash.c (ffffffff8142bf70)
Location: crypto/ahash.c:281
Inline: False
Direct callers:
  - crypto/ahash.c:ahash_def_finup_finish1
  - crypto/ahash.c:ahash_def_finup_done2
  - crypto/ahash.c:crypto_ahash_op
  - crypto/ahash.c:ahash_op_unaligned_done
```
**Symbols:**

```
ffffffff8142bf70-ffffffff8142bfd7: ahash_restore_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void ahash_restore_req(struct ahash_request *req, int err);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/ahash.c (ffffffff8145ec60)
Location: crypto/ahash.c:281
Inline: False
Direct callers:
  - crypto/ahash.c:ahash_def_finup_finish1
  - crypto/ahash.c:ahash_def_finup_done2
  - crypto/ahash.c:crypto_ahash_op
  - crypto/ahash.c:ahash_op_unaligned_done
```
**Symbols:**

```
ffffffff8145ec60-ffffffff8145ecc7: ahash_restore_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void ahash_restore_req(struct ahash_request *req, int err);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/ahash.c (ffffffff8147c5d0)
Location: crypto/ahash.c:292
Inline: False
Direct callers:
  - crypto/ahash.c:ahash_def_finup_finish1
  - crypto/ahash.c:ahash_def_finup_done2
  - crypto/ahash.c:crypto_ahash_op
  - crypto/ahash.c:ahash_op_unaligned_done
```
**Symbols:**

```
ffffffff8147c5d0-ffffffff8147c637: ahash_restore_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void ahash_restore_req(struct ahash_request *req, int err);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/ahash.c (ffffffff814aa740)
Location: crypto/ahash.c:287
Inline: False
Direct callers:
  - crypto/ahash.c:ahash_def_finup_finish1
  - crypto/ahash.c:ahash_def_finup_done2
  - crypto/ahash.c:crypto_ahash_op
  - crypto/ahash.c:ahash_op_unaligned_done
```
**Symbols:**

```
ffffffff814aa740-ffffffff814aa7a7: ahash_restore_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void ahash_restore_req(struct ahash_request *req, int err);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/ahash.c (ffffffff814c5400)
Location: crypto/ahash.c:287
Inline: False
Direct callers:
  - crypto/ahash.c:ahash_def_finup_finish1
  - crypto/ahash.c:ahash_def_finup_done2
  - crypto/ahash.c:crypto_ahash_op
  - crypto/ahash.c:ahash_op_unaligned_done
```
**Symbols:**

```
ffffffff814c5400-ffffffff814c5467: ahash_restore_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void ahash_restore_req(struct ahash_request *req, int err);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/ahash.c (ffffffff815244f0)
Location: crypto/ahash.c:289
Inline: False
Direct callers:
  - crypto/ahash.c:ahash_def_finup
  - crypto/ahash.c:ahash_def_finup_done1
  - crypto/ahash.c:ahash_def_finup_done2
  - crypto/ahash.c:crypto_ahash_op
  - crypto/ahash.c:ahash_op_unaligned_done
```
**Symbols:**

```
ffffffff815244f0-ffffffff81524557: ahash_restore_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void ahash_restore_req(struct ahash_request *req, int err);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/ahash.c (ffffffff815413c0)
Location: crypto/ahash.c:256
Inline: False
Direct callers:
  - crypto/ahash.c:ahash_def_finup
  - crypto/ahash.c:ahash_def_finup_done1
  - crypto/ahash.c:ahash_def_finup_done2
  - crypto/ahash.c:crypto_ahash_op
  - crypto/ahash.c:ahash_op_unaligned_done
```
**Symbols:**

```
ffffffff815413c0-ffffffff81541427: ahash_restore_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void ahash_restore_req(struct ahash_request *req, int err);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/ahash.c (ffffffff815499f0)
Location: crypto/ahash.c:256
Inline: False
Direct callers:
  - crypto/ahash.c:ahash_def_finup
  - crypto/ahash.c:ahash_def_finup_done1
  - crypto/ahash.c:ahash_def_finup_done2
  - crypto/ahash.c:crypto_ahash_op
  - crypto/ahash.c:ahash_op_unaligned_done
```
**Symbols:**

```
ffffffff815499f0-ffffffff81549a57: ahash_restore_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void ahash_restore_req(struct ahash_request *req, int err);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/ahash.c (ffffffff815aa1d0)
Location: crypto/ahash.c:256
Inline: False
Direct callers:
  - crypto/ahash.c:ahash_def_finup
  - crypto/ahash.c:ahash_def_finup_done1
  - crypto/ahash.c:ahash_def_finup_done2
  - crypto/ahash.c:crypto_ahash_op
  - crypto/ahash.c:ahash_op_unaligned_done
```
**Symbols:**

```
ffffffff815aa1d0-ffffffff815aa237: ahash_restore_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void ahash_restore_req(struct ahash_request *req, int err);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/ahash.c (ffffffff81651610)
Location: crypto/ahash.c:256
Inline: False
Direct callers:
  - crypto/ahash.c:ahash_def_finup
  - crypto/ahash.c:ahash_def_finup_done1
  - crypto/ahash.c:ahash_def_finup_done2
  - crypto/ahash.c:crypto_ahash_op
  - crypto/ahash.c:ahash_op_unaligned_done
```
**Symbols:**

```
ffffffff81651610-ffffffff81651685: ahash_restore_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void ahash_restore_req(struct ahash_request *req, int err);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/ahash.c (ffffffff8170b2e0)
Location: crypto/ahash.c:256
Inline: False
Direct callers:
  - crypto/ahash.c:ahash_def_finup
  - crypto/ahash.c:ahash_def_finup_done1
  - crypto/ahash.c:ahash_def_finup_done2
  - crypto/ahash.c:crypto_ahash_op
  - crypto/ahash.c:ahash_op_unaligned_done
```
**Symbols:**

```
ffffffff8170b2e0-ffffffff8170b355: ahash_restore_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void ahash_restore_req(struct ahash_request *req, int err);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/ahash.c (ffffffff81744970)
Location: crypto/ahash.c:239
Inline: False
Direct callers:
  - crypto/ahash.c:ahash_def_finup
  - crypto/ahash.c:ahash_def_finup_done1
  - crypto/ahash.c:ahash_def_finup_done1
  - crypto/ahash.c:crypto_ahash_op
  - crypto/ahash.c:ahash_op_unaligned_done
```
**Symbols:**

```
ffffffff81744970-ffffffff817449c1: ahash_restore_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void ahash_restore_req(struct ahash_request *req, int err);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/ahash.c (ffffffff81786f20)
Location: crypto/ahash.c:331
Inline: False
Direct callers:
  - crypto/ahash.c:ahash_def_finup_finish1
```
**Symbols:**

```
ffffffff81786f20-ffffffff81786f71: ahash_restore_req (STB_LOCAL)
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
void ahash_restore_req(struct ahash_request *req, int err);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/ahash.c (ffff8000105c0038)
Location: crypto/ahash.c:287
Inline: False
Direct callers:
  - crypto/ahash.c:ahash_def_finup_finish1
  - crypto/ahash.c:ahash_def_finup_done2
  - crypto/ahash.c:crypto_ahash_op
  - crypto/ahash.c:ahash_op_unaligned_done
```
**Symbols:**

```
ffff8000105c0038-ffff8000105c00ac: ahash_restore_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void ahash_restore_req(struct ahash_request *req, int err);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/ahash.c (c076dc00)
Location: crypto/ahash.c:287
Inline: False
Direct callers:
  - crypto/ahash.c:ahash_def_finup_finish1
  - crypto/ahash.c:ahash_def_finup_done2
  - crypto/ahash.c:crypto_ahash_op
  - crypto/ahash.c:ahash_op_unaligned_done
```
**Symbols:**

```
c076dc00-c076dc6c: ahash_restore_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void ahash_restore_req(struct ahash_request *req, int err);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/ahash.c (c000000000747fe0)
Location: crypto/ahash.c:287
Inline: False
Direct callers:
  - crypto/ahash.c:ahash_def_finup_finish1
  - crypto/ahash.c:ahash_def_finup_done2
  - crypto/ahash.c:crypto_ahash_op
  - crypto/ahash.c:ahash_op_unaligned_done
```
**Symbols:**

```
c000000000747fe0-c00000000074807c: ahash_restore_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void ahash_restore_req(struct ahash_request *req, int err);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/ahash.c (ffffffe000405048)
Location: crypto/ahash.c:287
Inline: False
Direct callers:
  - crypto/ahash.c:ahash_def_finup_finish1
  - crypto/ahash.c:ahash_def_finup_done2
  - crypto/ahash.c:crypto_ahash_op
  - crypto/ahash.c:ahash_op_unaligned_done
```
**Symbols:**

```
ffffffe000405048-ffffffe0004050b8: ahash_restore_req (STB_LOCAL)
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
void ahash_restore_req(struct ahash_request *req, int err);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/ahash.c (ffffffff814bd9e0)
Location: crypto/ahash.c:287
Inline: False
Direct callers:
  - crypto/ahash.c:ahash_def_finup_finish1
  - crypto/ahash.c:ahash_def_finup_done2
  - crypto/ahash.c:crypto_ahash_op
  - crypto/ahash.c:ahash_op_unaligned_done
```
**Symbols:**

```
ffffffff814bd9e0-ffffffff814bda47: ahash_restore_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void ahash_restore_req(struct ahash_request *req, int err);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/ahash.c (ffffffff814ae400)
Location: crypto/ahash.c:287
Inline: False
Direct callers:
  - crypto/ahash.c:ahash_def_finup_finish1
  - crypto/ahash.c:ahash_def_finup_done2
  - crypto/ahash.c:crypto_ahash_op
  - crypto/ahash.c:ahash_op_unaligned_done
```
**Symbols:**

```
ffffffff814ae400-ffffffff814ae467: ahash_restore_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void ahash_restore_req(struct ahash_request *req, int err);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/ahash.c (ffffffff814b9a70)
Location: crypto/ahash.c:287
Inline: False
Direct callers:
  - crypto/ahash.c:ahash_def_finup_finish1
  - crypto/ahash.c:ahash_def_finup_done2
  - crypto/ahash.c:crypto_ahash_op
  - crypto/ahash.c:ahash_op_unaligned_done
```
**Symbols:**

```
ffffffff814b9a70-ffffffff814b9ad7: ahash_restore_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void ahash_restore_req(struct ahash_request *req, int err);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/ahash.c (ffffffff814d2520)
Location: crypto/ahash.c:287
Inline: False
Direct callers:
  - crypto/ahash.c:ahash_def_finup_finish1
  - crypto/ahash.c:ahash_def_finup_done2
  - crypto/ahash.c:crypto_ahash_op
  - crypto/ahash.c:ahash_op_unaligned_done
```
**Symbols:**

```
ffffffff814d2520-ffffffff814d2587: ahash_restore_req (STB_LOCAL)
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
