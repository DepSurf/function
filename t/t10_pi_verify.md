# Function: <code>t10_pi_verify</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int t10_pi_verify(struct blk_integrity_iter *iter, csum_fn *fn, unsigned int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/t10-pi.c (ffffffff813e8830)
Location: block/t10-pi.c:73
Inline: False
Direct callers:
  - block/t10-pi.c:t10_pi_type1_verify_crc
  - block/t10-pi.c:t10_pi_type1_verify_ip
  - block/t10-pi.c:t10_pi_type3_verify_crc
  - block/t10-pi.c:t10_pi_type3_verify_ip
```
**Symbols:**

```
ffffffff813e8830-ffffffff813e8921: t10_pi_verify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int t10_pi_verify(struct blk_integrity_iter *iter, csum_fn *fn, unsigned int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/t10-pi.c (ffffffff8142ebb0)
Location: block/t10-pi.c:73
Inline: False
Direct callers:
  - block/t10-pi.c:t10_pi_type3_verify_ip
  - block/t10-pi.c:t10_pi_type3_verify_crc
  - block/t10-pi.c:t10_pi_type1_verify_ip
  - block/t10-pi.c:t10_pi_type1_verify_crc
```
**Symbols:**

```
ffffffff8142ebb0-ffffffff8142eca1: t10_pi_verify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int t10_pi_verify(struct blk_integrity_iter *iter, csum_fn *fn, unsigned int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/t10-pi.c (ffffffff81448930)
Location: block/t10-pi.c:73
Inline: False
Direct callers:
  - block/t10-pi.c:t10_pi_type3_verify_ip
  - block/t10-pi.c:t10_pi_type3_verify_crc
  - block/t10-pi.c:t10_pi_type1_verify_ip
  - block/t10-pi.c:t10_pi_type1_verify_crc
```
**Symbols:**

```
ffffffff81448930-ffffffff81448a21: t10_pi_verify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
blk_status_t t10_pi_verify(struct blk_integrity_iter *iter, csum_fn *fn, unsigned int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/t10-pi.c (ffffffff81456dd0)
Location: block/t10-pi.c:70
Inline: False
Direct callers:
  - block/t10-pi.c:t10_pi_type3_verify_ip
  - block/t10-pi.c:t10_pi_type3_verify_crc
  - block/t10-pi.c:t10_pi_type1_verify_ip
  - block/t10-pi.c:t10_pi_type1_verify_crc
```
**Symbols:**

```
ffffffff81456dd0-ffffffff81456ebc: t10_pi_verify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
blk_status_t t10_pi_verify(struct blk_integrity_iter *iter, csum_fn *fn, unsigned int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/t10-pi.c (ffffffff81482a20)
Location: block/t10-pi.c:70
Inline: False
Direct callers:
  - block/t10-pi.c:t10_pi_type3_verify_ip
  - block/t10-pi.c:t10_pi_type3_verify_crc
  - block/t10-pi.c:t10_pi_type1_verify_ip
  - block/t10-pi.c:t10_pi_type1_verify_crc
```
**Symbols:**

```
ffffffff81482a20-ffffffff81482b0e: t10_pi_verify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
blk_status_t t10_pi_verify(struct blk_integrity_iter *iter, csum_fn *fn, unsigned int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/t10-pi.c (0)
Location: block/t10-pi.c:70
Inline: False
Direct callers:
  - block/t10-pi.c:t10_pi_type3_verify_ip
  - block/t10-pi.c:t10_pi_type3_verify_crc
  - block/t10-pi.c:t10_pi_type1_verify_ip
  - block/t10-pi.c:t10_pi_type1_verify_crc
```
**Symbols:**

```
ffffffff814b7680-ffffffff814b7733: t10_pi_verify (STB_LOCAL)
ffffffff814b77d0-ffffffff814b7817: t10_pi_verify.cold.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
blk_status_t t10_pi_verify(struct blk_integrity_iter *iter, csum_fn *fn, unsigned int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/t10-pi.c (0)
Location: block/t10-pi.c:70
Inline: False
Direct callers:
  - block/t10-pi.c:t10_pi_type3_verify_ip
  - block/t10-pi.c:t10_pi_type3_verify_crc
  - block/t10-pi.c:t10_pi_type1_verify_ip
  - block/t10-pi.c:t10_pi_type1_verify_crc
```
**Symbols:**

```
ffffffff814cae60-ffffffff814caf13: t10_pi_verify (STB_LOCAL)
ffffffff814cb369-ffffffff814cb3b0: t10_pi_verify.cold.5 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
blk_status_t t10_pi_verify(struct blk_integrity_iter *iter, csum_fn *fn, unsigned int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/t10-pi.c (0)
Location: block/t10-pi.c:53
Inline: False
Direct callers:
  - block/t10-pi.c:t10_pi_type3_verify_ip
  - block/t10-pi.c:t10_pi_type3_verify_crc
  - block/t10-pi.c:t10_pi_type1_verify_ip
  - block/t10-pi.c:t10_pi_type1_verify_crc
```
**Symbols:**

```
ffffffff814f9770-ffffffff814f9832: t10_pi_verify (STB_LOCAL)
ffffffff814f9cd9-ffffffff814f9d23: t10_pi_verify.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/t10-pi.c (ffffffff81517995)
Location: block/t10-pi.c:53
Inline: True
Inline callers:
  - block/t10-pi.c:t10_pi_type3_verify_ip
  - block/t10-pi.c:t10_pi_type3_verify_crc
  - block/t10-pi.c:t10_pi_type1_verify_ip
  - block/t10-pi.c:t10_pi_type1_verify_crc
Direct callers:
  - block/t10-pi.c:t10_pi_type3_verify_ip
  - block/t10-pi.c:t10_pi_type3_verify_crc
  - block/t10-pi.c:t10_pi_type1_verify_ip
  - block/t10-pi.c:t10_pi_type1_verify_crc
```
**Symbols:**

```
ffffffff81517860-ffffffff81517928: t10_pi_verify.part.0 (STB_LOCAL)
ffffffff81517bae-ffffffff81517bf5: t10_pi_verify.part.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
blk_status_t t10_pi_verify(struct blk_integrity_iter *iter, csum_fn *fn, enum t10_dif_type type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/t10-pi.c (ffffffff81577ce5)
Location: block/t10-pi.c:54
Inline: True
Direct callers:
  - block/t10-pi.c:t10_pi_type3_verify_ip
  - block/t10-pi.c:t10_pi_type3_verify_crc
  - block/t10-pi.c:t10_pi_type1_verify_ip
  - block/t10-pi.c:t10_pi_type1_verify_crc
```
**Symbols:**

```
ffffffff81577ce0-ffffffff81577d96: t10_pi_verify (STB_LOCAL)
ffffffff81578416-ffffffff8157845d: t10_pi_verify.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
blk_status_t t10_pi_verify(struct blk_integrity_iter *iter, csum_fn *fn, enum t10_dif_type type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/t10-pi.c (ffffffff815947d5)
Location: block/t10-pi.c:54
Inline: True
Direct callers:
  - block/t10-pi.c:t10_pi_type3_verify_ip
  - block/t10-pi.c:t10_pi_type3_verify_crc
  - block/t10-pi.c:t10_pi_type1_verify_ip
  - block/t10-pi.c:t10_pi_type1_verify_crc
```
**Symbols:**

```
ffffffff815947d0-ffffffff8159487f: t10_pi_verify (STB_LOCAL)
ffffffff81bf3d84-ffffffff81bf3dcb: t10_pi_verify.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
blk_status_t t10_pi_verify(struct blk_integrity_iter *iter, csum_fn *fn, enum t10_dif_type type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/t10-pi.c (ffffffff8159b5b5)
Location: block/t10-pi.c:54
Inline: True
Direct callers:
  - block/t10-pi.c:t10_pi_type3_verify_ip
  - block/t10-pi.c:t10_pi_type3_verify_crc
  - block/t10-pi.c:t10_pi_type1_verify_ip
  - block/t10-pi.c:t10_pi_type1_verify_crc
```
**Symbols:**

```
ffffffff8159b5b0-ffffffff8159b65f: t10_pi_verify (STB_LOCAL)
ffffffff81be5be6-ffffffff81be5c2d: t10_pi_verify.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/t10-pi.c (ffffffff81603f25)
Location: block/t10-pi.c:54
Inline: True
Inline callers:
  - block/t10-pi.c:t10_pi_type3_verify_ip
  - block/t10-pi.c:t10_pi_type3_verify_ip
  - block/t10-pi.c:t10_pi_type3_verify_crc
  - block/t10-pi.c:t10_pi_type3_verify_crc
  - block/t10-pi.c:t10_pi_type1_verify_ip
  - block/t10-pi.c:t10_pi_type1_verify_crc
Direct callers:
  - block/t10-pi.c:t10_pi_type1_verify_ip
  - block/t10-pi.c:t10_pi_type1_verify_crc
```
**Symbols:**

```
ffffffff816039f0-ffffffff81603a9f: t10_pi_verify.part.0 (STB_LOCAL)
ffffffff81cda262-ffffffff81cda2a9: t10_pi_verify.part.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/t10-pi.c (ffffffff816b7585)
Location: block/t10-pi.c:56
Inline: True
Inline callers:
  - block/t10-pi.c:t10_pi_type3_verify_ip
  - block/t10-pi.c:t10_pi_type3_verify_ip
  - block/t10-pi.c:t10_pi_type3_verify_crc
  - block/t10-pi.c:t10_pi_type3_verify_crc
  - block/t10-pi.c:t10_pi_type1_verify_ip
  - block/t10-pi.c:t10_pi_type1_verify_crc
Direct callers:
  - block/t10-pi.c:t10_pi_type1_verify_ip
  - block/t10-pi.c:t10_pi_type1_verify_crc
```
**Symbols:**

```
ffffffff816b68b0-ffffffff816b698c: t10_pi_verify.part.0 (STB_LOCAL)
ffffffff81e8dd36-ffffffff81e8dd75: t10_pi_verify.part.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/t10-pi.c (ffffffff81777605)
Location: block/t10-pi.c:56
Inline: True
Inline callers:
  - block/t10-pi.c:t10_pi_type3_verify_ip
  - block/t10-pi.c:t10_pi_type3_verify_ip
  - block/t10-pi.c:t10_pi_type3_verify_crc
  - block/t10-pi.c:t10_pi_type3_verify_crc
  - block/t10-pi.c:t10_pi_type1_verify_ip
  - block/t10-pi.c:t10_pi_type1_verify_crc
Direct callers:
  - block/t10-pi.c:t10_pi_type1_verify_ip
  - block/t10-pi.c:t10_pi_type1_verify_crc
```
**Symbols:**

```
ffffffff81776800-ffffffff8177691f: t10_pi_verify.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/t10-pi.c (ffffffff817b7285)
Location: block/t10-pi.c:56
Inline: True
Inline callers:
  - block/t10-pi.c:t10_pi_type3_verify_ip
  - block/t10-pi.c:t10_pi_type3_verify_ip
  - block/t10-pi.c:t10_pi_type3_verify_crc
  - block/t10-pi.c:t10_pi_type3_verify_crc
  - block/t10-pi.c:t10_pi_type1_verify_ip
  - block/t10-pi.c:t10_pi_type1_verify_crc
Direct callers:
  - block/t10-pi.c:t10_pi_type1_verify_ip
  - block/t10-pi.c:t10_pi_type1_verify_crc
```
**Symbols:**

```
ffffffff817b63d0-ffffffff817b64ef: t10_pi_verify.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/t10-pi.c (ffffffff817fbc95)
Location: block/t10-pi.c:56
Inline: True
Inline callers:
  - block/t10-pi.c:t10_pi_type3_verify_ip
  - block/t10-pi.c:t10_pi_type3_verify_ip
  - block/t10-pi.c:t10_pi_type3_verify_crc
  - block/t10-pi.c:t10_pi_type3_verify_crc
  - block/t10-pi.c:t10_pi_type1_verify_ip
  - block/t10-pi.c:t10_pi_type1_verify_crc
Direct callers:
  - block/t10-pi.c:t10_pi_type1_verify_ip
  - block/t10-pi.c:t10_pi_type1_verify_crc
```
**Symbols:**

```
ffffffff817fade0-ffffffff817faeff: t10_pi_verify.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
blk_status_t t10_pi_verify(struct blk_integrity_iter *iter, csum_fn *fn, enum t10_dif_type type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/t10-pi.c (ffff80001061ed50)
Location: block/t10-pi.c:53
Inline: True
Direct callers:
  - block/t10-pi.c:t10_pi_type3_verify_ip
  - block/t10-pi.c:t10_pi_type3_verify_crc
  - block/t10-pi.c:t10_pi_type1_verify_ip
  - block/t10-pi.c:t10_pi_type1_verify_crc
```
**Symbols:**

```
ffff80001061ed50-ffff80001061ee88: t10_pi_verify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
blk_status_t t10_pi_verify(struct blk_integrity_iter *iter, csum_fn *fn, enum t10_dif_type type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/t10-pi.c (c07c677c)
Location: block/t10-pi.c:53
Inline: True
Direct callers:
  - block/t10-pi.c:t10_pi_type3_verify_ip
  - block/t10-pi.c:t10_pi_type3_verify_crc
  - block/t10-pi.c:t10_pi_type1_verify_ip
  - block/t10-pi.c:t10_pi_type1_verify_crc
```
**Symbols:**

```
c07c677c-c07c68c0: t10_pi_verify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
blk_status_t t10_pi_verify(struct blk_integrity_iter *iter, csum_fn *fn, enum t10_dif_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/t10-pi.c (c0000000007bddd0)
Location: block/t10-pi.c:53
Inline: False
Direct callers:
  - block/t10-pi.c:t10_pi_type3_verify_ip
  - block/t10-pi.c:t10_pi_type3_verify_crc
  - block/t10-pi.c:t10_pi_type1_verify_ip
  - block/t10-pi.c:t10_pi_type1_verify_crc
```
**Symbols:**

```
c0000000007bddd0-c0000000007bdfd8: t10_pi_verify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
blk_status_t t10_pi_verify(struct blk_integrity_iter *iter, csum_fn *fn, enum t10_dif_type type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/t10-pi.c (ffffffe00045166a)
Location: block/t10-pi.c:53
Inline: True
Direct callers:
  - block/t10-pi.c:t10_pi_type3_verify_ip
  - block/t10-pi.c:t10_pi_type3_verify_crc
  - block/t10-pi.c:t10_pi_type1_verify_ip
  - block/t10-pi.c:t10_pi_type1_verify_crc
```
**Symbols:**

```
ffffffe00045166a-ffffffe0004517a8: t10_pi_verify (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/t10-pi.c (ffffffff8150ff75)
Location: block/t10-pi.c:53
Inline: True
Inline callers:
  - block/t10-pi.c:t10_pi_type3_verify_ip
  - block/t10-pi.c:t10_pi_type3_verify_crc
  - block/t10-pi.c:t10_pi_type1_verify_ip
  - block/t10-pi.c:t10_pi_type1_verify_crc
Direct callers:
  - block/t10-pi.c:t10_pi_type3_verify_ip
  - block/t10-pi.c:t10_pi_type3_verify_crc
  - block/t10-pi.c:t10_pi_type1_verify_ip
  - block/t10-pi.c:t10_pi_type1_verify_crc
```
**Symbols:**

```
ffffffff8150fe40-ffffffff8150ff08: t10_pi_verify.part.0 (STB_LOCAL)
ffffffff8151018e-ffffffff815101d5: t10_pi_verify.part.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/t10-pi.c (ffffffff81500295)
Location: block/t10-pi.c:53
Inline: True
Inline callers:
  - block/t10-pi.c:t10_pi_type3_verify_ip
  - block/t10-pi.c:t10_pi_type3_verify_crc
  - block/t10-pi.c:t10_pi_type1_verify_ip
  - block/t10-pi.c:t10_pi_type1_verify_crc
Direct callers:
  - block/t10-pi.c:t10_pi_type3_verify_ip
  - block/t10-pi.c:t10_pi_type3_verify_crc
  - block/t10-pi.c:t10_pi_type1_verify_ip
  - block/t10-pi.c:t10_pi_type1_verify_crc
```
**Symbols:**

```
ffffffff81500160-ffffffff81500228: t10_pi_verify.part.0 (STB_LOCAL)
ffffffff815004ae-ffffffff815004f5: t10_pi_verify.part.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/t10-pi.c (ffffffff8150c005)
Location: block/t10-pi.c:53
Inline: True
Inline callers:
  - block/t10-pi.c:t10_pi_type3_verify_ip
  - block/t10-pi.c:t10_pi_type3_verify_crc
  - block/t10-pi.c:t10_pi_type1_verify_ip
  - block/t10-pi.c:t10_pi_type1_verify_crc
Direct callers:
  - block/t10-pi.c:t10_pi_type3_verify_ip
  - block/t10-pi.c:t10_pi_type3_verify_crc
  - block/t10-pi.c:t10_pi_type1_verify_ip
  - block/t10-pi.c:t10_pi_type1_verify_crc
```
**Symbols:**

```
ffffffff8150bed0-ffffffff8150bf98: t10_pi_verify.part.0 (STB_LOCAL)
ffffffff8150c21e-ffffffff8150c265: t10_pi_verify.part.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/t10-pi.c (ffffffff815256c5)
Location: block/t10-pi.c:53
Inline: True
Inline callers:
  - block/t10-pi.c:t10_pi_type3_verify_ip
  - block/t10-pi.c:t10_pi_type3_verify_crc
  - block/t10-pi.c:t10_pi_type1_verify_ip
  - block/t10-pi.c:t10_pi_type1_verify_crc
Direct callers:
  - block/t10-pi.c:t10_pi_type3_verify_ip
  - block/t10-pi.c:t10_pi_type3_verify_crc
  - block/t10-pi.c:t10_pi_type1_verify_ip
  - block/t10-pi.c:t10_pi_type1_verify_crc
```
**Symbols:**

```
ffffffff81525590-ffffffff81525658: t10_pi_verify.part.0 (STB_LOCAL)
ffffffff815258fc-ffffffff81525943: t10_pi_verify.part.0.cold (STB_LOCAL)
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
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>blk_status_t</code>
</li>
</ul>
</details>
</li>
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
</ul>
