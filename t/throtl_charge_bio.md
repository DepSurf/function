# Function: <code>throtl_charge_bio</code>

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
In block/blk-throttle.c (ffffffff813db465)
Location: block/blk-throttle.c:816
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:blk_throtl_bio
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
In block/blk-throttle.c (ffffffff81421a58)
Location: block/blk-throttle.c:812
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:tg_dispatch_one_bio
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
In block/blk-throttle.c (ffffffff8143cc11)
Location: block/blk-throttle.c:812
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:tg_dispatch_one_bio
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void throtl_charge_bio(struct throtl_grp *tg, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff814483d0)
Location: block/blk-throttle.c:1043
Inline: False
Direct callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:tg_dispatch_one_bio
```
**Symbols:**

```
ffffffff814483d0-ffffffff81448426: throtl_charge_bio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void throtl_charge_bio(struct throtl_grp *tg, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff81474f60)
Location: block/blk-throttle.c:1041
Inline: False
Direct callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:tg_dispatch_one_bio
```
**Symbols:**

```
ffffffff81474f60-ffffffff81474fb6: throtl_charge_bio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void throtl_charge_bio(struct throtl_grp *tg, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff814a9450)
Location: block/blk-throttle.c:1039
Inline: False
Direct callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:tg_dispatch_one_bio
```
**Symbols:**

```
ffffffff814a9450-ffffffff814a94a3: throtl_charge_bio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void throtl_charge_bio(struct throtl_grp *tg, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff814c3860)
Location: block/blk-throttle.c:1025
Inline: False
Direct callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:tg_dispatch_one_bio
```
**Symbols:**

```
ffffffff814c3860-ffffffff814c38b3: throtl_charge_bio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void throtl_charge_bio(struct throtl_grp *tg, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff814f1df0)
Location: block/blk-throttle.c:1022
Inline: False
Direct callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:tg_dispatch_one_bio
```
**Symbols:**

```
ffffffff814f1df0-ffffffff814f1e43: throtl_charge_bio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void throtl_charge_bio(struct throtl_grp *tg, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff8150b360)
Location: block/blk-throttle.c:1024
Inline: False
Direct callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:tg_dispatch_one_bio
```
**Symbols:**

```
ffffffff8150b360-ffffffff8150b3b3: throtl_charge_bio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void throtl_charge_bio(struct throtl_grp *tg, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff8156c4c0)
Location: block/blk-throttle.c:1042
Inline: False
Direct callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:tg_dispatch_one_bio
```
**Symbols:**

```
ffffffff8156c4c0-ffffffff8156c513: throtl_charge_bio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void throtl_charge_bio(struct throtl_grp *tg, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff81587290)
Location: block/blk-throttle.c:1052
Inline: False
Direct callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:tg_dispatch_one_bio
```
**Symbols:**

```
ffffffff81587290-ffffffff815872e1: throtl_charge_bio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void throtl_charge_bio(struct throtl_grp *tg, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff8158e0e0)
Location: block/blk-throttle.c:1052
Inline: False
Direct callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:tg_dispatch_one_bio
```
**Symbols:**

```
ffffffff8158e0e0-ffffffff8158e131: throtl_charge_bio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void throtl_charge_bio(struct throtl_grp *tg, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff815f3f70)
Location: block/blk-throttle.c:1063
Inline: False
Direct callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:tg_dispatch_one_bio
```
**Symbols:**

```
ffffffff815f3f70-ffffffff815f3fd7: throtl_charge_bio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void throtl_charge_bio(struct throtl_grp *tg, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff816a5910)
Location: block/blk-throttle.c:918
Inline: False
Direct callers:
  - block/blk-throttle.c:__blk_throtl_bio
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:tg_dispatch_one_bio
```
**Symbols:**

```
ffffffff816a5910-ffffffff816a5989: throtl_charge_bio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void throtl_charge_bio(struct throtl_grp *tg, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff817694fa)
Location: block/blk-throttle.c:956
Inline: True
Inline callers:
  - block/blk-throttle.c:__blk_throtl_bio
Direct callers:
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:tg_dispatch_one_bio
```
**Symbols:**

```
ffffffff817647d0-ffffffff81764838: throtl_charge_bio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void throtl_charge_bio(struct throtl_grp *tg, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff817a86c2)
Location: block/blk-throttle.c:955
Inline: True
Inline callers:
  - block/blk-throttle.c:__blk_throtl_bio
Direct callers:
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:tg_dispatch_one_bio
```
**Symbols:**

```
ffffffff817a38c0-ffffffff817a391b: throtl_charge_bio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void throtl_charge_bio(struct throtl_grp *tg, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff817ec42f)
Location: block/blk-throttle.c:961
Inline: True
Inline callers:
  - block/blk-throttle.c:__blk_throtl_bio
Direct callers:
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:tg_dispatch_one_bio
```
**Symbols:**

```
ffffffff817e7410-ffffffff817e746b: throtl_charge_bio (STB_LOCAL)
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
void throtl_charge_bio(struct throtl_grp *tg, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffff80001060f148)
Location: block/blk-throttle.c:1024
Inline: False
Direct callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:tg_dispatch_one_bio
```
**Symbols:**

```
ffff80001060f148-ffff80001060f1dc: throtl_charge_bio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void throtl_charge_bio(struct throtl_grp *tg, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (c07b95b0)
Location: block/blk-throttle.c:1024
Inline: False
Direct callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:tg_dispatch_one_bio
```
**Symbols:**

```
c07b95b0-c07b9644: throtl_charge_bio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void throtl_charge_bio(struct throtl_grp *tg, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (c0000000007ac410)
Location: block/blk-throttle.c:1024
Inline: False
Direct callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:tg_dispatch_one_bio
```
**Symbols:**

```
c0000000007ac410-c0000000007ac498: throtl_charge_bio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void throtl_charge_bio(struct throtl_grp *tg, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffe000447078)
Location: block/blk-throttle.c:1024
Inline: False
Direct callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:tg_dispatch_one_bio
```
**Symbols:**

```
ffffffe000447078-ffffffe0004470fe: throtl_charge_bio (STB_LOCAL)
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
void throtl_charge_bio(struct throtl_grp *tg, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff81503940)
Location: block/blk-throttle.c:1024
Inline: False
Direct callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:tg_dispatch_one_bio
```
**Symbols:**

```
ffffffff81503940-ffffffff81503993: throtl_charge_bio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void throtl_charge_bio(struct throtl_grp *tg, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff814f3e00)
Location: block/blk-throttle.c:1024
Inline: False
Direct callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:tg_dispatch_one_bio
```
**Symbols:**

```
ffffffff814f3e00-ffffffff814f3e53: throtl_charge_bio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void throtl_charge_bio(struct throtl_grp *tg, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff814ff9d0)
Location: block/blk-throttle.c:1024
Inline: False
Direct callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:tg_dispatch_one_bio
```
**Symbols:**

```
ffffffff814ff9d0-ffffffff814ffa23: throtl_charge_bio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void throtl_charge_bio(struct throtl_grp *tg, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff81518ba0)
Location: block/blk-throttle.c:1024
Inline: False
Direct callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:tg_dispatch_one_bio
```
**Symbols:**

```
ffffffff81518ba0-ffffffff81518bf3: throtl_charge_bio (STB_LOCAL)
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
