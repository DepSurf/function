# Function: <code>blk_throtl_update_limit_valid</code>

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
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-throttle.c (ffffffff8144a7d0)
Location: block/blk-throttle.c:575
Inline: True
Direct callers:
  - block/blk-throttle.c:tg_set_limit
  - block/blk-throttle.c:tg_set_limit
  - block/blk-throttle.c:tg_set_limit
  - block/blk-throttle.c:throtl_pd_offline
```
**Symbols:**

```
ffffffff8144a7d0-ffffffff8144a8d9: blk_throtl_update_limit_valid.isra.17 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-throttle.c (ffffffff81475ed0)
Location: block/blk-throttle.c:573
Inline: True
Direct callers:
  - block/blk-throttle.c:tg_set_limit
  - block/blk-throttle.c:tg_set_limit
  - block/blk-throttle.c:tg_set_limit
  - block/blk-throttle.c:throtl_pd_offline
```
**Symbols:**

```
ffffffff81475ed0-ffffffff81475fd9: blk_throtl_update_limit_valid.isra.17 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-throttle.c (ffffffff814aa2a0)
Location: block/blk-throttle.c:571
Inline: True
Direct callers:
  - block/blk-throttle.c:tg_set_limit
  - block/blk-throttle.c:tg_set_limit
  - block/blk-throttle.c:tg_set_limit
  - block/blk-throttle.c:throtl_pd_offline
```
**Symbols:**

```
ffffffff814aa2a0-ffffffff814aa39c: blk_throtl_update_limit_valid.isra.24 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-throttle.c (ffffffff814c4910)
Location: block/blk-throttle.c:570
Inline: True
Direct callers:
  - block/blk-throttle.c:tg_set_limit
  - block/blk-throttle.c:tg_set_limit
  - block/blk-throttle.c:tg_set_limit
  - block/blk-throttle.c:throtl_pd_offline
```
**Symbols:**

```
ffffffff814c4910-ffffffff814c49fe: blk_throtl_update_limit_valid.isra.21 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-throttle.c (ffffffff814f30c0)
Location: block/blk-throttle.c:570
Inline: True
Direct callers:
  - block/blk-throttle.c:tg_set_limit
  - block/blk-throttle.c:tg_set_limit
  - block/blk-throttle.c:tg_set_limit
  - block/blk-throttle.c:throtl_pd_offline
```
**Symbols:**

```
ffffffff814f30c0-ffffffff814f31ab: blk_throtl_update_limit_valid.isra.0 (STB_LOCAL)
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
In block/blk-throttle.c (ffffffff8150c660)
Location: block/blk-throttle.c:572
Inline: True
Direct callers:
  - block/blk-throttle.c:tg_set_limit
  - block/blk-throttle.c:tg_set_limit
  - block/blk-throttle.c:tg_set_limit
  - block/blk-throttle.c:throtl_pd_offline
```
**Symbols:**

```
ffffffff8150c660-ffffffff8150c74b: blk_throtl_update_limit_valid.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void blk_throtl_update_limit_valid(struct throtl_data *td);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff8156d8b0)
Location: block/blk-throttle.c:588
Inline: False
Direct callers:
  - block/blk-throttle.c:tg_set_limit
  - block/blk-throttle.c:tg_set_limit
  - block/blk-throttle.c:tg_set_limit
  - block/blk-throttle.c:throtl_pd_offline
```
**Symbols:**

```
ffffffff8156d8b0-ffffffff8156d99b: blk_throtl_update_limit_valid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (0)
Location: block/blk-throttle.c:612
Inline: True
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
Location: block/blk-throttle.c:612
Inline: True
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
Location: block/blk-throttle.c:615
Inline: True
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
Location: block/blk-throttle.c:475
Inline: True
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
Location: block/blk-throttle.c:469
Inline: True
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
Location: block/blk-throttle.c:468
Inline: True
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
Location: block/blk-throttle.c:468
Inline: True
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-throttle.c (ffff8000106101c8)
Location: block/blk-throttle.c:572
Inline: True
Direct callers:
  - block/blk-throttle.c:tg_set_limit
  - block/blk-throttle.c:tg_set_limit
  - block/blk-throttle.c:tg_set_limit
  - block/blk-throttle.c:throtl_pd_offline
```
**Symbols:**

```
ffff8000106101c8-ffff8000106102d8: blk_throtl_update_limit_valid.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void blk_throtl_update_limit_valid(struct throtl_data *td);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (c07bab1c)
Location: block/blk-throttle.c:572
Inline: False
Direct callers:
  - block/blk-throttle.c:tg_set_limit
  - block/blk-throttle.c:tg_set_limit
  - block/blk-throttle.c:tg_set_limit
  - block/blk-throttle.c:throtl_pd_offline
```
**Symbols:**

```
c07bab1c-c07bac14: blk_throtl_update_limit_valid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-throttle.c (c0000000007adb30)
Location: block/blk-throttle.c:572
Inline: True
Direct callers:
  - block/blk-throttle.c:tg_set_limit
  - block/blk-throttle.c:tg_set_limit
  - block/blk-throttle.c:tg_set_limit
  - block/blk-throttle.c:throtl_pd_offline
```
**Symbols:**

```
c0000000007adb30-c0000000007adc98: blk_throtl_update_limit_valid.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-throttle.c (ffffffe00044808c)
Location: block/blk-throttle.c:572
Inline: True
Direct callers:
  - block/blk-throttle.c:tg_set_limit
  - block/blk-throttle.c:tg_set_limit
  - block/blk-throttle.c:tg_set_limit
  - block/blk-throttle.c:throtl_pd_offline
```
**Symbols:**

```
ffffffe00044808c-ffffffe00044815c: blk_throtl_update_limit_valid.isra.0 (STB_LOCAL)
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
In block/blk-throttle.c (ffffffff81504c40)
Location: block/blk-throttle.c:572
Inline: True
Direct callers:
  - block/blk-throttle.c:tg_set_limit
  - block/blk-throttle.c:tg_set_limit
  - block/blk-throttle.c:tg_set_limit
  - block/blk-throttle.c:throtl_pd_offline
```
**Symbols:**

```
ffffffff81504c40-ffffffff81504d2b: blk_throtl_update_limit_valid.isra.0 (STB_LOCAL)
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
In block/blk-throttle.c (ffffffff814f5100)
Location: block/blk-throttle.c:572
Inline: True
Direct callers:
  - block/blk-throttle.c:tg_set_limit
  - block/blk-throttle.c:tg_set_limit
  - block/blk-throttle.c:tg_set_limit
  - block/blk-throttle.c:throtl_pd_offline
```
**Symbols:**

```
ffffffff814f5100-ffffffff814f51eb: blk_throtl_update_limit_valid.isra.0 (STB_LOCAL)
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
In block/blk-throttle.c (ffffffff81500cd0)
Location: block/blk-throttle.c:572
Inline: True
Direct callers:
  - block/blk-throttle.c:tg_set_limit
  - block/blk-throttle.c:tg_set_limit
  - block/blk-throttle.c:tg_set_limit
  - block/blk-throttle.c:throtl_pd_offline
```
**Symbols:**

```
ffffffff81500cd0-ffffffff81500dbb: blk_throtl_update_limit_valid.isra.0 (STB_LOCAL)
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
In block/blk-throttle.c (ffffffff81519a40)
Location: block/blk-throttle.c:572
Inline: True
Direct callers:
  - block/blk-throttle.c:tg_set_limit
  - block/blk-throttle.c:tg_set_limit
  - block/blk-throttle.c:tg_set_limit
  - block/blk-throttle.c:throtl_pd_offline
```
**Symbols:**

```
ffffffff81519a40-ffffffff81519b3f: blk_throtl_update_limit_valid.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
<b>Arch</b>
<ul>
</ul>
