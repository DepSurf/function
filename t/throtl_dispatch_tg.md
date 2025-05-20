# Function: <code>throtl_dispatch_tg</code>

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
In block/blk-throttle.c (ffffffff813db7fe)
Location: block/blk-throttle.c:943
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_pending_timer_fn
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
In block/blk-throttle.c (ffffffff8142131e)
Location: block/blk-throttle.c:939
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_pending_timer_fn
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
In block/blk-throttle.c (ffffffff8143c70c)
Location: block/blk-throttle.c:939
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_pending_timer_fn
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff8144b090)
Location: block/blk-throttle.c:1175
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_select_dispatch
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
In block/blk-throttle.c (ffffffff814778c0)
Location: block/blk-throttle.c:1173
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_select_dispatch
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
In block/blk-throttle.c (0)
Location: block/blk-throttle.c:1171
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_select_dispatch
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
In block/blk-throttle.c (0)
Location: block/blk-throttle.c:1157
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_select_dispatch
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
In block/blk-throttle.c (ffffffff814f4b5b)
Location: block/blk-throttle.c:1154
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_select_dispatch
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
In block/blk-throttle.c (ffffffff8150e16c)
Location: block/blk-throttle.c:1156
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_select_dispatch
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int throtl_dispatch_tg(struct throtl_grp *tg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff8156e3c0)
Location: block/blk-throttle.c:1174
Inline: False
Direct callers:
  - block/blk-throttle.c:throtl_select_dispatch
```
**Symbols:**

```
ffffffff8156e3c0-ffffffff8156e49d: throtl_dispatch_tg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int throtl_dispatch_tg(struct throtl_grp *tg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff81589920)
Location: block/blk-throttle.c:1184
Inline: False
Direct callers:
  - block/blk-throttle.c:throtl_select_dispatch
```
**Symbols:**

```
ffffffff81589920-ffffffff81589a10: throtl_dispatch_tg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (0)
Location: block/blk-throttle.c:1184
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_select_dispatch
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (0)
Location: block/blk-throttle.c:1195
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_select_dispatch
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (0)
Location: block/blk-throttle.c:1053
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_select_dispatch
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (0)
Location: block/blk-throttle.c:1083
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_pending_timer_fn
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (0)
Location: block/blk-throttle.c:1082
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_pending_timer_fn
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (0)
Location: block/blk-throttle.c:1088
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_pending_timer_fn
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
In block/blk-throttle.c (0)
Location: block/blk-throttle.c:1156
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_select_dispatch
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
In block/blk-throttle.c (0)
Location: block/blk-throttle.c:1156
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_select_dispatch
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
In block/blk-throttle.c (c0000000007afef0)
Location: block/blk-throttle.c:1156
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_select_dispatch
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
In block/blk-throttle.c (ffffffe000449572)
Location: block/blk-throttle.c:1156
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_select_dispatch
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
In block/blk-throttle.c (ffffffff8150674c)
Location: block/blk-throttle.c:1156
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_select_dispatch
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
In block/blk-throttle.c (ffffffff814f6c0c)
Location: block/blk-throttle.c:1156
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_select_dispatch
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
In block/blk-throttle.c (ffffffff815027dc)
Location: block/blk-throttle.c:1156
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_select_dispatch
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
In block/blk-throttle.c (ffffffff8151bbec)
Location: block/blk-throttle.c:1156
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_select_dispatch
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
