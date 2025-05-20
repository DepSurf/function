# Function: <code>throtl_qnode_add_bio</code>

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
In block/blk-throttle.c (ffffffff813d9b45)
Location: block/blk-throttle.c:250
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_add_bio_tg
  - block/blk-throttle.c:tg_dispatch_one_bio
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void throtl_qnode_add_bio(struct bio *bio, struct throtl_qnode *qn, struct list_head *queued);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff8141f100)
Location: block/blk-throttle.c:244
Inline: False
Direct callers:
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:throtl_add_bio_tg
```
**Symbols:**

```
ffffffff8141f100-ffffffff8141f189: throtl_qnode_add_bio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void throtl_qnode_add_bio(struct bio *bio, struct throtl_qnode *qn, struct list_head *queued);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff8143a6c0)
Location: block/blk-throttle.c:244
Inline: False
Direct callers:
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:throtl_add_bio_tg
```
**Symbols:**

```
ffffffff8143a6c0-ffffffff8143a749: throtl_qnode_add_bio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void throtl_qnode_add_bio(struct bio *bio, struct throtl_qnode *qn, struct list_head *queued);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff81448360)
Location: block/blk-throttle.c:410
Inline: False
Direct callers:
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:throtl_add_bio_tg
```
**Symbols:**

```
ffffffff81448360-ffffffff814483c7: throtl_qnode_add_bio (STB_LOCAL)
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
In block/blk-throttle.c (ffffffff814774eb)
Location: block/blk-throttle.c:409
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:throtl_add_bio_tg
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void throtl_qnode_add_bio(struct bio *bio, struct throtl_qnode *qn, struct list_head *queued);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff814a9290)
Location: block/blk-throttle.c:407
Inline: False
Direct callers:
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:throtl_add_bio_tg
```
**Symbols:**

```
ffffffff814a9290-ffffffff814a9302: throtl_qnode_add_bio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void throtl_qnode_add_bio(struct bio *bio, struct throtl_qnode *qn, struct list_head *queued);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff814c4600)
Location: block/blk-throttle.c:406
Inline: False
Direct callers:
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:throtl_add_bio_tg
```
**Symbols:**

```
ffffffff814c4600-ffffffff814c466e: throtl_qnode_add_bio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void throtl_qnode_add_bio(struct bio *bio, struct throtl_qnode *qn, struct list_head *queued);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff814f2dd0)
Location: block/blk-throttle.c:406
Inline: False
Direct callers:
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:throtl_add_bio_tg
```
**Symbols:**

```
ffffffff814f2dd0-ffffffff814f2e35: throtl_qnode_add_bio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void throtl_qnode_add_bio(struct bio *bio, struct throtl_qnode *qn, struct list_head *queued);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff8150c370)
Location: block/blk-throttle.c:406
Inline: False
Direct callers:
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:throtl_add_bio_tg
```
**Symbols:**

```
ffffffff8150c370-ffffffff8150c3d5: throtl_qnode_add_bio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void throtl_qnode_add_bio(struct bio *bio, struct throtl_qnode *qn, struct list_head *queued);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff8156d9ce)
Location: block/blk-throttle.c:410
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_add_bio_tg
Direct callers:
  - block/blk-throttle.c:tg_dispatch_one_bio
```
**Symbols:**

```
ffffffff8156d7e0-ffffffff8156d845: throtl_qnode_add_bio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void throtl_qnode_add_bio(struct bio *bio, struct throtl_qnode *qn, struct list_head *queued);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff81587ee2)
Location: block/blk-throttle.c:410
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_add_bio_tg
Direct callers:
  - block/blk-throttle.c:tg_dispatch_one_bio
```
**Symbols:**

```
ffffffff81587e30-ffffffff81587ea6: throtl_qnode_add_bio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void throtl_qnode_add_bio(struct bio *bio, struct throtl_qnode *qn, struct list_head *queued);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff8158ed32)
Location: block/blk-throttle.c:410
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_add_bio_tg
Direct callers:
  - block/blk-throttle.c:tg_dispatch_one_bio
```
**Symbols:**

```
ffffffff8158ec80-ffffffff8158ecf6: throtl_qnode_add_bio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void throtl_qnode_add_bio(struct bio *bio, struct throtl_qnode *qn, struct list_head *queued);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff815f4d92)
Location: block/blk-throttle.c:413
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_add_bio_tg
Direct callers:
  - block/blk-throttle.c:tg_dispatch_one_bio
```
**Symbols:**

```
ffffffff815f4ce0-ffffffff815f4d56: throtl_qnode_add_bio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void throtl_qnode_add_bio(struct bio *bio, struct throtl_qnode *qn, struct list_head *queued);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff816a696e)
Location: block/blk-throttle.c:261
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_add_bio_tg
Direct callers:
  - block/blk-throttle.c:tg_dispatch_one_bio
```
**Symbols:**

```
ffffffff816a6890-ffffffff816a6927: throtl_qnode_add_bio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void throtl_qnode_add_bio(struct bio *bio, struct throtl_qnode *qn, struct list_head *queued);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff817658c0)
Location: block/blk-throttle.c:261
Inline: False
Direct callers:
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:throtl_add_bio_tg
```
**Symbols:**

```
ffffffff817658c0-ffffffff81765957: throtl_qnode_add_bio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void throtl_qnode_add_bio(struct bio *bio, struct throtl_qnode *qn, struct list_head *queued);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff817a4980)
Location: block/blk-throttle.c:261
Inline: False
Direct callers:
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:throtl_add_bio_tg
```
**Symbols:**

```
ffffffff817a4980-ffffffff817a4a17: throtl_qnode_add_bio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void throtl_qnode_add_bio(struct bio *bio, struct throtl_qnode *qn, struct list_head *queued);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff817e8550)
Location: block/blk-throttle.c:261
Inline: False
Direct callers:
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:throtl_add_bio_tg
```
**Symbols:**

```
ffffffff817e8550-ffffffff817e85e7: throtl_qnode_add_bio (STB_LOCAL)
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
void throtl_qnode_add_bio(struct bio *bio, struct throtl_qnode *qn, struct list_head *queued);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffff800010610598)
Location: block/blk-throttle.c:406
Inline: False
Direct callers:
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:throtl_add_bio_tg
```
**Symbols:**

```
ffff800010610598-ffff800010610674: throtl_qnode_add_bio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void throtl_qnode_add_bio(struct bio *bio, struct throtl_qnode *qn, struct list_head *queued);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (c07ba7dc)
Location: block/blk-throttle.c:406
Inline: False
Direct callers:
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:throtl_add_bio_tg
```
**Symbols:**

```
c07ba7dc-c07ba880: throtl_qnode_add_bio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void throtl_qnode_add_bio(struct bio *bio, struct throtl_qnode *qn, struct list_head *queued);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (c0000000007ad660)
Location: block/blk-throttle.c:406
Inline: False
Direct callers:
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:throtl_add_bio_tg
```
**Symbols:**

```
c0000000007ad660-c0000000007ad74c: throtl_qnode_add_bio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void throtl_qnode_add_bio(struct bio *bio, struct throtl_qnode *qn, struct list_head *queued);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffe000447dbe)
Location: block/blk-throttle.c:406
Inline: False
Direct callers:
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:throtl_add_bio_tg
```
**Symbols:**

```
ffffffe000447dbe-ffffffe000447e6c: throtl_qnode_add_bio (STB_LOCAL)
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
void throtl_qnode_add_bio(struct bio *bio, struct throtl_qnode *qn, struct list_head *queued);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff81504950)
Location: block/blk-throttle.c:406
Inline: False
Direct callers:
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:throtl_add_bio_tg
```
**Symbols:**

```
ffffffff81504950-ffffffff815049b5: throtl_qnode_add_bio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void throtl_qnode_add_bio(struct bio *bio, struct throtl_qnode *qn, struct list_head *queued);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff814f4e10)
Location: block/blk-throttle.c:406
Inline: False
Direct callers:
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:throtl_add_bio_tg
```
**Symbols:**

```
ffffffff814f4e10-ffffffff814f4e75: throtl_qnode_add_bio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void throtl_qnode_add_bio(struct bio *bio, struct throtl_qnode *qn, struct list_head *queued);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff815009e0)
Location: block/blk-throttle.c:406
Inline: False
Direct callers:
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:throtl_add_bio_tg
```
**Symbols:**

```
ffffffff815009e0-ffffffff81500a45: throtl_qnode_add_bio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void throtl_qnode_add_bio(struct bio *bio, struct throtl_qnode *qn, struct list_head *queued);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff81519940)
Location: block/blk-throttle.c:406
Inline: False
Direct callers:
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:throtl_add_bio_tg
```
**Symbols:**

```
ffffffff81519940-ffffffff815199b9: throtl_qnode_add_bio (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
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
