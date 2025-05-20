# Function: <code>throtl_trim_slice</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void throtl_trim_slice(struct throtl_grp *tg, bool rw);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-throttle.c (ffffffff813d9a70)
Location: block/blk-throttle.c:610
Inline: True
Direct callers:
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:blk_throtl_bio
```
**Symbols:**

```
ffffffff813d9a70-ffffffff813d9a76: throtl_trim_slice.part.13 (STB_LOCAL)
ffffffff813db040-ffffffff813db3ed: throtl_trim_slice (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void throtl_trim_slice(struct throtl_grp *tg, bool rw);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-throttle.c (ffffffff8141f8b0)
Location: block/blk-throttle.c:604
Inline: True
Direct callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:tg_dispatch_one_bio
```
**Symbols:**

```
ffffffff8141f8b0-ffffffff8141f8b6: throtl_trim_slice.part.11 (STB_LOCAL)
ffffffff81420c90-ffffffff81420fdc: throtl_trim_slice (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

```c
void throtl_trim_slice(struct throtl_grp *tg, bool rw);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-throttle.c (ffffffff8143b6e0)
Location: block/blk-throttle.c:604
Inline: True
Direct callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:tg_dispatch_one_bio
```
**Symbols:**

```
ffffffff8143b6e0-ffffffff8143b6e6: throtl_trim_slice.part.17 (STB_LOCAL)
ffffffff8143b6f0-ffffffff8143b9d3: throtl_trim_slice (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void throtl_trim_slice(struct throtl_grp *tg, bool rw);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-throttle.c (ffffffff81449a00)
Location: block/blk-throttle.c:830
Inline: True
Direct callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:tg_dispatch_one_bio
```
**Symbols:**

```
ffffffff81449a00-ffffffff81449a06: throtl_trim_slice.part.22 (STB_LOCAL)
ffffffff81449a10-ffffffff81449d1b: throtl_trim_slice (STB_LOCAL)
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
In block/blk-throttle.c (ffffffff81478036)
Location: block/blk-throttle.c:828
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:tg_dispatch_one_bio
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff814ac9b3)
Location: block/blk-throttle.c:826
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:tg_dispatch_one_bio
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff814c6d62)
Location: block/blk-throttle.c:817
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:tg_dispatch_one_bio
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff814f55b6)
Location: block/blk-throttle.c:817
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:tg_dispatch_one_bio
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff8150ec84)
Location: block/blk-throttle.c:819
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:tg_dispatch_one_bio
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void throtl_trim_slice(struct throtl_grp *tg, bool rw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff8156df80)
Location: block/blk-throttle.c:837
Inline: False
Direct callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:tg_dispatch_one_bio
```
**Symbols:**

```
ffffffff8156df80-ffffffff8156e1f5: throtl_trim_slice (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void throtl_trim_slice(struct throtl_grp *tg, bool rw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff815894b0)
Location: block/blk-throttle.c:834
Inline: False
Direct callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:tg_dispatch_one_bio
```
**Symbols:**

```
ffffffff815894b0-ffffffff81589747: throtl_trim_slice (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void throtl_trim_slice(struct throtl_grp *tg, bool rw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff8158feb0)
Location: block/blk-throttle.c:834
Inline: False
Direct callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:tg_dispatch_one_bio
```
**Symbols:**

```
ffffffff8158feb0-ffffffff8159014d: throtl_trim_slice (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void throtl_trim_slice(struct throtl_grp *tg, bool rw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff815f6860)
Location: block/blk-throttle.c:842
Inline: False
Direct callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:tg_dispatch_one_bio
```
**Symbols:**

```
ffffffff815f6860-ffffffff815f6f1a: throtl_trim_slice (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void throtl_trim_slice(struct throtl_grp *tg, bool rw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff816a7f30)
Location: block/blk-throttle.c:698
Inline: False
Direct callers:
  - block/blk-throttle.c:__blk_throtl_bio
  - block/blk-throttle.c:tg_dispatch_one_bio
```
**Symbols:**

```
ffffffff816a7f30-ffffffff816a8627: throtl_trim_slice (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void throtl_trim_slice(struct throtl_grp *tg, bool rw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff81766930)
Location: block/blk-throttle.c:702
Inline: False
Direct callers:
  - block/blk-throttle.c:__blk_throtl_bio
  - block/blk-throttle.c:tg_dispatch_one_bio
```
**Symbols:**

```
ffffffff81766930-ffffffff81767027: throtl_trim_slice (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void throtl_trim_slice(struct throtl_grp *tg, bool rw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff817a5a10)
Location: block/blk-throttle.c:701
Inline: False
Direct callers:
  - block/blk-throttle.c:__blk_throtl_bio
  - block/blk-throttle.c:tg_dispatch_one_bio
```
**Symbols:**

```
ffffffff817a5a10-ffffffff817a60ed: throtl_trim_slice (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void throtl_trim_slice(struct throtl_grp *tg, bool rw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff817e95c0)
Location: block/blk-throttle.c:736
Inline: False
Direct callers:
  - block/blk-throttle.c:__blk_throtl_bio
  - block/blk-throttle.c:tg_dispatch_one_bio
```
**Symbols:**

```
ffffffff817e95c0-ffffffff817e9e23: throtl_trim_slice (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffff8000106128fc)
Location: block/blk-throttle.c:819
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:tg_dispatch_one_bio
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (c07bd294)
Location: block/blk-throttle.c:819
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:tg_dispatch_one_bio
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (c0000000007b0d8c)
Location: block/blk-throttle.c:819
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:tg_dispatch_one_bio
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffe000449d0e)
Location: block/blk-throttle.c:819
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:tg_dispatch_one_bio
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff81507264)
Location: block/blk-throttle.c:819
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:tg_dispatch_one_bio
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff814f7724)
Location: block/blk-throttle.c:819
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:tg_dispatch_one_bio
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff815032f4)
Location: block/blk-throttle.c:819
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:tg_dispatch_one_bio
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff8151c783)
Location: block/blk-throttle.c:819
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:tg_dispatch_one_bio
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
