# Function: <code>throtl_can_upgrade</code>

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
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
bool throtl_can_upgrade(struct throtl_data *td, struct throtl_grp *this_tg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff8144a590)
Location: block/blk-throttle.c:1851
Inline: True
Direct callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:throtl_pending_timer_fn
```
**Symbols:**

```
ffffffff8144a590-ffffffff8144a7c9: throtl_can_upgrade (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
bool throtl_can_upgrade(struct throtl_data *td, struct throtl_grp *this_tg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff81475ca0)
Location: block/blk-throttle.c:1849
Inline: True
Direct callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:throtl_pending_timer_fn
```
**Symbols:**

```
ffffffff81475ca0-ffffffff81475ec5: throtl_can_upgrade (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
bool throtl_can_upgrade(struct throtl_data *td, struct throtl_grp *this_tg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff814aa3a0)
Location: block/blk-throttle.c:1858
Inline: True
Direct callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:throtl_pending_timer_fn
```
**Symbols:**

```
ffffffff814aa3a0-ffffffff814aa5b7: throtl_can_upgrade (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
bool throtl_can_upgrade(struct throtl_data *td, struct throtl_grp *this_tg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff814c46f0)
Location: block/blk-throttle.c:1844
Inline: True
Direct callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:throtl_pending_timer_fn
```
**Symbols:**

```
ffffffff814c46f0-ffffffff814c4907: throtl_can_upgrade (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
bool throtl_can_upgrade(struct throtl_data *td, struct throtl_grp *this_tg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff814f2ec0)
Location: block/blk-throttle.c:1841
Inline: True
Direct callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:throtl_pending_timer_fn
```
**Symbols:**

```
ffffffff814f2ec0-ffffffff814f30b6: throtl_can_upgrade (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
bool throtl_can_upgrade(struct throtl_data *td, struct throtl_grp *this_tg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff8150c460)
Location: block/blk-throttle.c:1843
Inline: True
Direct callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:throtl_pending_timer_fn
```
**Symbols:**

```
ffffffff8150c460-ffffffff8150c656: throtl_can_upgrade (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-throttle.c (ffffffff815700c5)
Location: block/blk-throttle.c:1887
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:throtl_pending_timer_fn
Direct callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:throtl_pending_timer_fn
```
**Symbols:**

```
ffffffff8156e9f0-ffffffff8156eb1d: throtl_can_upgrade.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-throttle.c (ffffffff8158aecb)
Location: block/blk-throttle.c:1901
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:throtl_pending_timer_fn
Direct callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:throtl_pending_timer_fn
```
**Symbols:**

```
ffffffff815890c0-ffffffff815891fd: throtl_can_upgrade.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-throttle.c (ffffffff81591bd9)
Location: block/blk-throttle.c:1901
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:throtl_pending_timer_fn
Direct callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:throtl_pending_timer_fn
```
**Symbols:**

```
ffffffff8158fb90-ffffffff8158fd5d: throtl_can_upgrade.part.0 (STB_LOCAL)
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
In block/blk-throttle.c (ffffffff815f8c12)
Location: block/blk-throttle.c:1912
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:throtl_pending_timer_fn
Direct callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:throtl_pending_timer_fn
```
**Symbols:**

```
ffffffff815f6330-ffffffff815f652f: throtl_can_upgrade.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool throtl_can_upgrade(struct throtl_data *td, struct throtl_grp *this_tg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff816a79b0)
Location: block/blk-throttle.c:1813
Inline: False
Direct callers:
  - block/blk-throttle.c:__blk_throtl_bio
  - block/blk-throttle.c:__blk_throtl_bio
  - block/blk-throttle.c:throtl_pending_timer_fn
```
**Symbols:**

```
ffffffff816a79b0-ffffffff816a7bf5: throtl_can_upgrade (STB_LOCAL)
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
Location: block/blk-throttle.c:2154
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
Location: block/blk-throttle.c:2157
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
Location: block/blk-throttle.c:2165
Inline: True
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
bool throtl_can_upgrade(struct throtl_data *td, struct throtl_grp *this_tg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffff80001060ff80)
Location: block/blk-throttle.c:1843
Inline: True
Direct callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:throtl_pending_timer_fn
  - block/blk-throttle.c:throtl_pending_timer_fn
```
**Symbols:**

```
ffff80001060ff80-ffff8000106101c4: throtl_can_upgrade (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
bool throtl_can_upgrade(struct throtl_data *td, struct throtl_grp *this_tg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (c07ba8f8)
Location: block/blk-throttle.c:1843
Inline: True
Direct callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:throtl_pending_timer_fn
```
**Symbols:**

```
c07ba8f8-c07bab1c: throtl_can_upgrade (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
bool throtl_can_upgrade(struct throtl_data *td, struct throtl_grp *this_tg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (c0000000007ad820)
Location: block/blk-throttle.c:1843
Inline: True
Direct callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:throtl_pending_timer_fn
```
**Symbols:**

```
c0000000007ad820-c0000000007adb28: throtl_can_upgrade (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
bool throtl_can_upgrade(struct throtl_data *td, struct throtl_grp *this_tg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffe000447f0c)
Location: block/blk-throttle.c:1843
Inline: True
Direct callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:throtl_pending_timer_fn
```
**Symbols:**

```
ffffffe000447f0c-ffffffe00044808c: throtl_can_upgrade (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
bool throtl_can_upgrade(struct throtl_data *td, struct throtl_grp *this_tg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff81504a40)
Location: block/blk-throttle.c:1843
Inline: True
Direct callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:throtl_pending_timer_fn
```
**Symbols:**

```
ffffffff81504a40-ffffffff81504c36: throtl_can_upgrade (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
bool throtl_can_upgrade(struct throtl_data *td, struct throtl_grp *this_tg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff814f4f00)
Location: block/blk-throttle.c:1843
Inline: True
Direct callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:throtl_pending_timer_fn
```
**Symbols:**

```
ffffffff814f4f00-ffffffff814f50f6: throtl_can_upgrade (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
bool throtl_can_upgrade(struct throtl_data *td, struct throtl_grp *this_tg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff81500ad0)
Location: block/blk-throttle.c:1843
Inline: True
Direct callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:throtl_pending_timer_fn
```
**Symbols:**

```
ffffffff81500ad0-ffffffff81500cc6: throtl_can_upgrade (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
bool throtl_can_upgrade(struct throtl_data *td, struct throtl_grp *this_tg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff81519d30)
Location: block/blk-throttle.c:1843
Inline: True
Direct callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:throtl_pending_timer_fn
```
**Symbols:**

```
ffffffff81519d30-ffffffff81519f35: throtl_can_upgrade (STB_LOCAL)
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
