# Function: <code>tg_may_dispatch</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
bool tg_may_dispatch(struct throtl_grp *tg, struct bio *bio, long unsigned int *wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff813da3c0)
Location: block/blk-throttle.c:764
Inline: False
Direct callers:
  - block/blk-throttle.c:tg_update_disptime
  - block/blk-throttle.c:tg_update_disptime
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:blk_throtl_bio
```
**Symbols:**

```
ffffffff813da3c0-ffffffff813da69a: tg_may_dispatch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
bool tg_may_dispatch(struct throtl_grp *tg, struct bio *bio, long unsigned int *wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff81420020)
Location: block/blk-throttle.c:758
Inline: False
Direct callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:tg_update_disptime
  - block/blk-throttle.c:tg_update_disptime
```
**Symbols:**

```
ffffffff81420020-ffffffff81420313: tg_may_dispatch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool tg_may_dispatch(struct throtl_grp *tg, struct bio *bio, long unsigned int *wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff8143b3e0)
Location: block/blk-throttle.c:758
Inline: False
Direct callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:tg_update_disptime
  - block/blk-throttle.c:tg_update_disptime
```
**Symbols:**

```
ffffffff8143b3e0-ffffffff8143b6de: tg_may_dispatch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool tg_may_dispatch(struct throtl_grp *tg, struct bio *bio, long unsigned int *wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff81449480)
Location: block/blk-throttle.c:986
Inline: False
Direct callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:throtl_select_dispatch
  - block/blk-throttle.c:throtl_select_dispatch
  - block/blk-throttle.c:tg_update_disptime
  - block/blk-throttle.c:tg_update_disptime
```
**Symbols:**

```
ffffffff81449480-ffffffff81449818: tg_may_dispatch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool tg_may_dispatch(struct throtl_grp *tg, struct bio *bio, long unsigned int *wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff81476100)
Location: block/blk-throttle.c:984
Inline: False
Direct callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:throtl_select_dispatch
  - block/blk-throttle.c:throtl_select_dispatch
  - block/blk-throttle.c:tg_update_disptime
  - block/blk-throttle.c:tg_update_disptime
```
**Symbols:**

```
ffffffff81476100-ffffffff81476670: tg_may_dispatch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool tg_may_dispatch(struct throtl_grp *tg, struct bio *bio, long unsigned int *wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff814aa6d0)
Location: block/blk-throttle.c:982
Inline: False
Direct callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:throtl_select_dispatch
  - block/blk-throttle.c:throtl_select_dispatch
  - block/blk-throttle.c:tg_update_disptime
  - block/blk-throttle.c:tg_update_disptime
```
**Symbols:**

```
ffffffff814aa6d0-ffffffff814aac29: tg_may_dispatch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool tg_may_dispatch(struct throtl_grp *tg, struct bio *bio, long unsigned int *wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff814c4b10)
Location: block/blk-throttle.c:968
Inline: False
Direct callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:throtl_select_dispatch
  - block/blk-throttle.c:throtl_select_dispatch
  - block/blk-throttle.c:tg_update_disptime
  - block/blk-throttle.c:tg_update_disptime
```
**Symbols:**

```
ffffffff814c4b10-ffffffff814c5022: tg_may_dispatch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool tg_may_dispatch(struct throtl_grp *tg, struct bio *bio, long unsigned int *wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff814f32c0)
Location: block/blk-throttle.c:965
Inline: False
Direct callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:throtl_select_dispatch
  - block/blk-throttle.c:throtl_select_dispatch
  - block/blk-throttle.c:tg_update_disptime
  - block/blk-throttle.c:tg_update_disptime
```
**Symbols:**

```
ffffffff814f32c0-ffffffff814f3841: tg_may_dispatch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool tg_may_dispatch(struct throtl_grp *tg, struct bio *bio, long unsigned int *wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff8150c850)
Location: block/blk-throttle.c:967
Inline: False
Direct callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:throtl_select_dispatch
  - block/blk-throttle.c:throtl_select_dispatch
  - block/blk-throttle.c:tg_update_disptime
  - block/blk-throttle.c:tg_update_disptime
```
**Symbols:**

```
ffffffff8150c850-ffffffff8150ced2: tg_may_dispatch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool tg_may_dispatch(struct throtl_grp *tg, struct bio *bio, long unsigned int *wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff8156dc50)
Location: block/blk-throttle.c:985
Inline: False
Direct callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:throtl_dispatch_tg
  - block/blk-throttle.c:throtl_dispatch_tg
  - block/blk-throttle.c:tg_update_disptime
  - block/blk-throttle.c:tg_update_disptime
```
**Symbols:**

```
ffffffff8156dc50-ffffffff8156df79: tg_may_dispatch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool tg_may_dispatch(struct throtl_grp *tg, struct bio *bio, long unsigned int *wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff815887f0)
Location: block/blk-throttle.c:994
Inline: False
Direct callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:throtl_dispatch_tg
  - block/blk-throttle.c:throtl_dispatch_tg
  - block/blk-throttle.c:tg_update_disptime
  - block/blk-throttle.c:tg_update_disptime
```
**Symbols:**

```
ffffffff815887f0-ffffffff81588acc: tg_may_dispatch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool tg_may_dispatch(struct throtl_grp *tg, struct bio *bio, long unsigned int *wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff8158f440)
Location: block/blk-throttle.c:994
Inline: False
Direct callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:throtl_select_dispatch
  - block/blk-throttle.c:throtl_select_dispatch
  - block/blk-throttle.c:tg_update_disptime
  - block/blk-throttle.c:tg_update_disptime
```
**Symbols:**

```
ffffffff8158f440-ffffffff8158f71b: tg_may_dispatch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool tg_may_dispatch(struct throtl_grp *tg, struct bio *bio, long unsigned int *wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff815f5860)
Location: block/blk-throttle.c:1002
Inline: False
Direct callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:throtl_select_dispatch
  - block/blk-throttle.c:throtl_select_dispatch
  - block/blk-throttle.c:tg_update_disptime
  - block/blk-throttle.c:tg_update_disptime
```
**Symbols:**

```
ffffffff815f5860-ffffffff815f5bb7: tg_may_dispatch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool tg_may_dispatch(struct throtl_grp *tg, struct bio *bio, long unsigned int *wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff816a89c0)
Location: block/blk-throttle.c:859
Inline: False
Direct callers:
  - block/blk-throttle.c:__blk_throtl_bio
  - block/blk-throttle.c:throtl_select_dispatch
  - block/blk-throttle.c:throtl_select_dispatch
  - block/blk-throttle.c:tg_update_disptime
  - block/blk-throttle.c:tg_update_disptime
```
**Symbols:**

```
ffffffff816a89c0-ffffffff816a8fe1: tg_may_dispatch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool tg_may_dispatch(struct throtl_grp *tg, struct bio *bio, long unsigned int *wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff81767630)
Location: block/blk-throttle.c:896
Inline: False
Direct callers:
  - block/blk-throttle.c:__blk_throtl_bio
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:tg_update_disptime
  - block/blk-throttle.c:tg_update_disptime
```
**Symbols:**

```
ffffffff81767630-ffffffff81767ca3: tg_may_dispatch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool tg_may_dispatch(struct throtl_grp *tg, struct bio *bio, long unsigned int *wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff817a67c0)
Location: block/blk-throttle.c:895
Inline: False
Direct callers:
  - block/blk-throttle.c:__blk_throtl_bio
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:tg_update_disptime
  - block/blk-throttle.c:tg_update_disptime
```
**Symbols:**

```
ffffffff817a67c0-ffffffff817a6e37: tg_may_dispatch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool tg_may_dispatch(struct throtl_grp *tg, struct bio *bio, long unsigned int *wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff817ea500)
Location: block/blk-throttle.c:901
Inline: False
Direct callers:
  - block/blk-throttle.c:__blk_throtl_bio
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:tg_update_disptime
  - block/blk-throttle.c:tg_update_disptime
```
**Symbols:**

```
ffffffff817ea500-ffffffff817eabbf: tg_may_dispatch (STB_LOCAL)
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
bool tg_may_dispatch(struct throtl_grp *tg, struct bio *bio, long unsigned int *wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffff800010610730)
Location: block/blk-throttle.c:967
Inline: False
Direct callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:throtl_select_dispatch
  - block/blk-throttle.c:throtl_select_dispatch
  - block/blk-throttle.c:tg_update_disptime
  - block/blk-throttle.c:tg_update_disptime
```
**Symbols:**

```
ffff800010610730-ffff800010610d14: tg_may_dispatch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool tg_may_dispatch(struct throtl_grp *tg, struct bio *bio, long unsigned int *wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (c07bac14)
Location: block/blk-throttle.c:967
Inline: False
Direct callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:throtl_select_dispatch
  - block/blk-throttle.c:throtl_select_dispatch
  - block/blk-throttle.c:tg_update_disptime
  - block/blk-throttle.c:tg_update_disptime
```
**Symbols:**

```
c07bac14-c07bb2dc: tg_may_dispatch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool tg_may_dispatch(struct throtl_grp *tg, struct bio *bio, long unsigned int *wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (c0000000007adfd0)
Location: block/blk-throttle.c:967
Inline: False
Direct callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:throtl_select_dispatch
  - block/blk-throttle.c:throtl_select_dispatch
  - block/blk-throttle.c:tg_update_disptime
  - block/blk-throttle.c:tg_update_disptime
```
**Symbols:**

```
c0000000007adfd0-c0000000007ae700: tg_may_dispatch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool tg_may_dispatch(struct throtl_grp *tg, struct bio *bio, long unsigned int *wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffe000448276)
Location: block/blk-throttle.c:967
Inline: False
Direct callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:throtl_select_dispatch
  - block/blk-throttle.c:throtl_select_dispatch
  - block/blk-throttle.c:tg_update_disptime
  - block/blk-throttle.c:tg_update_disptime
```
**Symbols:**

```
ffffffe000448276-ffffffe00044871e: tg_may_dispatch (STB_LOCAL)
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
bool tg_may_dispatch(struct throtl_grp *tg, struct bio *bio, long unsigned int *wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff81504e30)
Location: block/blk-throttle.c:967
Inline: False
Direct callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:throtl_select_dispatch
  - block/blk-throttle.c:throtl_select_dispatch
  - block/blk-throttle.c:tg_update_disptime
  - block/blk-throttle.c:tg_update_disptime
```
**Symbols:**

```
ffffffff81504e30-ffffffff815054b2: tg_may_dispatch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool tg_may_dispatch(struct throtl_grp *tg, struct bio *bio, long unsigned int *wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff814f52f0)
Location: block/blk-throttle.c:967
Inline: False
Direct callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:throtl_select_dispatch
  - block/blk-throttle.c:throtl_select_dispatch
  - block/blk-throttle.c:tg_update_disptime
  - block/blk-throttle.c:tg_update_disptime
```
**Symbols:**

```
ffffffff814f52f0-ffffffff814f5972: tg_may_dispatch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool tg_may_dispatch(struct throtl_grp *tg, struct bio *bio, long unsigned int *wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff81500ec0)
Location: block/blk-throttle.c:967
Inline: False
Direct callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:throtl_select_dispatch
  - block/blk-throttle.c:throtl_select_dispatch
  - block/blk-throttle.c:tg_update_disptime
  - block/blk-throttle.c:tg_update_disptime
```
**Symbols:**

```
ffffffff81500ec0-ffffffff81501542: tg_may_dispatch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool tg_may_dispatch(struct throtl_grp *tg, struct bio *bio, long unsigned int *wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff8151a140)
Location: block/blk-throttle.c:967
Inline: False
Direct callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:throtl_select_dispatch
  - block/blk-throttle.c:throtl_select_dispatch
  - block/blk-throttle.c:tg_update_disptime
  - block/blk-throttle.c:tg_update_disptime
```
**Symbols:**

```
ffffffff8151a140-ffffffff8151a7f9: tg_may_dispatch (STB_LOCAL)
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
No changes between <code>4.10</code> and <code>4.13</code> ✅
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
