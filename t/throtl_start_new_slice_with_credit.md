# Function: <code>throtl_start_new_slice_with_credit</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void throtl_start_new_slice_with_credit(struct throtl_grp *tg, bool rw, long unsigned int start);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff813da790)
Location: block/blk-throttle.c:550
Inline: False
Direct callers:
  - block/blk-throttle.c:tg_dispatch_one_bio
```
**Symbols:**

```
ffffffff813da790-ffffffff813da9ae: throtl_start_new_slice_with_credit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void throtl_start_new_slice_with_credit(struct throtl_grp *tg, bool rw, long unsigned int start);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff81420410)
Location: block/blk-throttle.c:544
Inline: False
Direct callers:
  - block/blk-throttle.c:tg_dispatch_one_bio
```
**Symbols:**

```
ffffffff81420410-ffffffff814205c6: throtl_start_new_slice_with_credit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void throtl_start_new_slice_with_credit(struct throtl_grp *tg, bool rw, long unsigned int start);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff8143ae70)
Location: block/blk-throttle.c:544
Inline: False
Direct callers:
  - block/blk-throttle.c:tg_dispatch_one_bio
```
**Symbols:**

```
ffffffff8143ae70-ffffffff8143afde: throtl_start_new_slice_with_credit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void throtl_start_new_slice_with_credit(struct throtl_grp *tg, bool rw, long unsigned int start);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff81448e10)
Location: block/blk-throttle.c:770
Inline: False
Direct callers:
  - block/blk-throttle.c:tg_dispatch_one_bio
```
**Symbols:**

```
ffffffff81448e10-ffffffff81448f8e: throtl_start_new_slice_with_credit (STB_LOCAL)
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
In block/blk-throttle.c (ffffffff81477542)
Location: block/blk-throttle.c:768
Inline: True
Inline callers:
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
In block/blk-throttle.c (ffffffff814abb05)
Location: block/blk-throttle.c:766
Inline: True
Inline callers:
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
In block/blk-throttle.c (ffffffff814c5ef5)
Location: block/blk-throttle.c:757
Inline: True
Inline callers:
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
In block/blk-throttle.c (ffffffff814f4734)
Location: block/blk-throttle.c:757
Inline: True
Inline callers:
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
In block/blk-throttle.c (ffffffff8150dcc4)
Location: block/blk-throttle.c:759
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_dispatch_one_bio
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void throtl_start_new_slice_with_credit(struct throtl_grp *tg, bool rw, long unsigned int start);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff8156c650)
Location: block/blk-throttle.c:777
Inline: False
Direct callers:
  - block/blk-throttle.c:tg_dispatch_one_bio
```
**Symbols:**

```
ffffffff8156c650-ffffffff8156c774: throtl_start_new_slice_with_credit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void throtl_start_new_slice_with_credit(struct throtl_grp *tg, bool rw, long unsigned int start);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff81588ad0)
Location: block/blk-throttle.c:774
Inline: False
Direct callers:
  - block/blk-throttle.c:tg_dispatch_one_bio
```
**Symbols:**

```
ffffffff81588ad0-ffffffff81588c10: throtl_start_new_slice_with_credit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void throtl_start_new_slice_with_credit(struct throtl_grp *tg, bool rw, long unsigned int start);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff8158f720)
Location: block/blk-throttle.c:774
Inline: False
Direct callers:
  - block/blk-throttle.c:tg_dispatch_one_bio
```
**Symbols:**

```
ffffffff8158f720-ffffffff8158f860: throtl_start_new_slice_with_credit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void throtl_start_new_slice_with_credit(struct throtl_grp *tg, bool rw, long unsigned int start);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff815f5d10)
Location: block/blk-throttle.c:777
Inline: False
Direct callers:
  - block/blk-throttle.c:tg_dispatch_one_bio
```
**Symbols:**

```
ffffffff815f5d10-ffffffff815f5ffd: throtl_start_new_slice_with_credit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void throtl_start_new_slice_with_credit(struct throtl_grp *tg, bool rw, long unsigned int start);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff816a6f40)
Location: block/blk-throttle.c:637
Inline: False
Direct callers:
  - block/blk-throttle.c:tg_dispatch_one_bio
```
**Symbols:**

```
ffffffff816a6f40-ffffffff816a721f: throtl_start_new_slice_with_credit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void throtl_start_new_slice_with_credit(struct throtl_grp *tg, bool rw, long unsigned int start);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff81765fc0)
Location: block/blk-throttle.c:634
Inline: False
Direct callers:
  - block/blk-throttle.c:tg_dispatch_one_bio
```
**Symbols:**

```
ffffffff81765fc0-ffffffff81766315: throtl_start_new_slice_with_credit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void throtl_start_new_slice_with_credit(struct throtl_grp *tg, bool rw, long unsigned int start);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff817a5090)
Location: block/blk-throttle.c:633
Inline: False
Direct callers:
  - block/blk-throttle.c:tg_dispatch_one_bio
```
**Symbols:**

```
ffffffff817a5090-ffffffff817a53e5: throtl_start_new_slice_with_credit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void throtl_start_new_slice_with_credit(struct throtl_grp *tg, bool rw, long unsigned int start);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff817e8c60)
Location: block/blk-throttle.c:633
Inline: False
Direct callers:
  - block/blk-throttle.c:tg_dispatch_one_bio
```
**Symbols:**

```
ffffffff817e8c60-ffffffff817e8fb5: throtl_start_new_slice_with_credit (STB_LOCAL)
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
In block/blk-throttle.c (ffff80001061194c)
Location: block/blk-throttle.c:759
Inline: True
Inline callers:
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
In block/blk-throttle.c (c07bc08c)
Location: block/blk-throttle.c:759
Inline: True
Inline callers:
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
In block/blk-throttle.c (c0000000007af96c)
Location: block/blk-throttle.c:759
Inline: True
Inline callers:
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
In block/blk-throttle.c (ffffffe000449224)
Location: block/blk-throttle.c:759
Inline: True
Inline callers:
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
In block/blk-throttle.c (ffffffff815062a4)
Location: block/blk-throttle.c:759
Inline: True
Inline callers:
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
In block/blk-throttle.c (ffffffff814f6764)
Location: block/blk-throttle.c:759
Inline: True
Inline callers:
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
In block/blk-throttle.c (ffffffff81502334)
Location: block/blk-throttle.c:759
Inline: True
Inline callers:
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
In block/blk-throttle.c (ffffffff8151b65c)
Location: block/blk-throttle.c:759
Inline: True
Inline callers:
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
