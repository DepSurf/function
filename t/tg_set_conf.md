# Function: <code>tg_set_conf</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
ssize_t tg_set_conf(struct kernfs_open_file *of, char *buf, size_t nbytes, loff_t off, bool is_u64);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-throttle.c (ffffffff813dac90)
Location: block/blk-throttle.c:1185
Inline: False
Direct callers:
  - block/blk-throttle.c:tg_set_conf_uint
  - block/blk-throttle.c:tg_set_conf_u64
```
**Symbols:**

```
ffffffff813dac90-ffffffff813dad94: tg_set_conf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-throttle.c (ffffffff81420b50)
Location: block/blk-throttle.c:1181
Inline: True
Direct callers:
  - block/blk-throttle.c:tg_set_conf_uint
  - block/blk-throttle.c:tg_set_conf_u64
```
**Symbols:**

```
ffffffff81420b50-ffffffff81420c50: tg_set_conf.constprop.15 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-throttle.c (ffffffff8143c110)
Location: block/blk-throttle.c:1181
Inline: True
Direct callers:
  - block/blk-throttle.c:tg_set_conf_uint
  - block/blk-throttle.c:tg_set_conf_u64
```
**Symbols:**

```
ffffffff8143c110-ffffffff8143c210: tg_set_conf.constprop.21 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-throttle.c (ffffffff8144a440)
Location: block/blk-throttle.c:1440
Inline: True
Direct callers:
  - block/blk-throttle.c:tg_set_conf_uint
  - block/blk-throttle.c:tg_set_conf_u64
```
**Symbols:**

```
ffffffff8144a440-ffffffff8144a541: tg_set_conf.constprop.27 (STB_LOCAL)
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
In block/blk-throttle.c (ffffffff81477180)
Location: block/blk-throttle.c:1438
Inline: True
Direct callers:
  - block/blk-throttle.c:tg_set_conf_uint
  - block/blk-throttle.c:tg_set_conf_u64
```
**Symbols:**

```
ffffffff81477180-ffffffff81477281: tg_set_conf.constprop.25 (STB_LOCAL)
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
In block/blk-throttle.c (ffffffff814ab8b0)
Location: block/blk-throttle.c:1437
Inline: True
Direct callers:
  - block/blk-throttle.c:tg_set_conf_uint
  - block/blk-throttle.c:tg_set_conf_u64
```
**Symbols:**

```
ffffffff814ab8b0-ffffffff814ab9b5: tg_set_conf.constprop.31 (STB_LOCAL)
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
In block/blk-throttle.c (ffffffff814c5ca0)
Location: block/blk-throttle.c:1423
Inline: True
Direct callers:
  - block/blk-throttle.c:tg_set_conf_uint
  - block/blk-throttle.c:tg_set_conf_u64
```
**Symbols:**

```
ffffffff814c5ca0-ffffffff814c5da1: tg_set_conf.constprop.30 (STB_LOCAL)
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
In block/blk-throttle.c (ffffffff814f44e0)
Location: block/blk-throttle.c:1420
Inline: True
Direct callers:
  - block/blk-throttle.c:tg_set_conf_uint
  - block/blk-throttle.c:tg_set_conf_u64
```
**Symbols:**

```
ffffffff814f44e0-ffffffff814f45e5: tg_set_conf.constprop.0 (STB_LOCAL)
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
In block/blk-throttle.c (ffffffff8150da70)
Location: block/blk-throttle.c:1422
Inline: True
Direct callers:
  - block/blk-throttle.c:tg_set_conf_uint
  - block/blk-throttle.c:tg_set_conf_u64
```
**Symbols:**

```
ffffffff8150da70-ffffffff8150db75: tg_set_conf.constprop.0 (STB_LOCAL)
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
In block/blk-throttle.c (ffffffff8156fce0)
Location: block/blk-throttle.c:1440
Inline: True
Direct callers:
  - block/blk-throttle.c:tg_set_conf_uint
  - block/blk-throttle.c:tg_set_conf_u64
```
**Symbols:**

```
ffffffff8156fce0-ffffffff8156fde5: tg_set_conf.constprop.0 (STB_LOCAL)
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
In block/blk-throttle.c (ffffffff8158ab20)
Location: block/blk-throttle.c:1454
Inline: True
Direct callers:
  - block/blk-throttle.c:tg_set_conf_uint
  - block/blk-throttle.c:tg_set_conf_u64
```
**Symbols:**

```
ffffffff8158ab20-ffffffff8158ac25: tg_set_conf.constprop.0 (STB_LOCAL)
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
In block/blk-throttle.c (ffffffff81591600)
Location: block/blk-throttle.c:1454
Inline: True
Direct callers:
  - block/blk-throttle.c:tg_set_conf_uint
  - block/blk-throttle.c:tg_set_conf_u64
```
**Symbols:**

```
ffffffff81591600-ffffffff81591705: tg_set_conf.constprop.0 (STB_LOCAL)
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
In block/blk-throttle.c (ffffffff815f8770)
Location: block/blk-throttle.c:1465
Inline: True
Direct callers:
  - block/blk-throttle.c:tg_set_conf_uint
  - block/blk-throttle.c:tg_set_conf_u64
```
**Symbols:**

```
ffffffff815f8770-ffffffff815f889c: tg_set_conf.constprop.0 (STB_LOCAL)
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
In block/blk-throttle.c (ffffffff816a9e80)
Location: block/blk-throttle.c:1333
Inline: True
Direct callers:
  - block/blk-throttle.c:tg_set_conf_uint
  - block/blk-throttle.c:tg_set_conf_u64
```
**Symbols:**

```
ffffffff816a9e80-ffffffff816a9fd8: tg_set_conf.constprop.0 (STB_LOCAL)
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
In block/blk-throttle.c (ffffffff817690e0)
Location: block/blk-throttle.c:1363
Inline: True
Direct callers:
  - block/blk-throttle.c:tg_set_conf_uint
  - block/blk-throttle.c:tg_set_conf_u64
```
**Symbols:**

```
ffffffff817690e0-ffffffff81769232: tg_set_conf.constprop.0 (STB_LOCAL)
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
In block/blk-throttle.c (ffffffff817a8270)
Location: block/blk-throttle.c:1362
Inline: True
Direct callers:
  - block/blk-throttle.c:tg_set_conf_uint
  - block/blk-throttle.c:tg_set_conf_u64
```
**Symbols:**

```
ffffffff817a8270-ffffffff817a83e6: tg_set_conf.isra.0 (STB_LOCAL)
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
In block/blk-throttle.c (ffffffff817ebff0)
Location: block/blk-throttle.c:1370
Inline: True
Direct callers:
  - block/blk-throttle.c:tg_set_conf_uint
  - block/blk-throttle.c:tg_set_conf_u64
```
**Symbols:**

```
ffffffff817ebff0-ffffffff817ec166: tg_set_conf.isra.0 (STB_LOCAL)
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
In block/blk-throttle.c (ffff800010611288)
Location: block/blk-throttle.c:1422
Inline: True
Direct callers:
  - block/blk-throttle.c:tg_set_conf_uint
  - block/blk-throttle.c:tg_set_conf_u64
```
**Symbols:**

```
ffff800010611288-ffff80001061139c: tg_set_conf.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-throttle.c (c07bbe1c)
Location: block/blk-throttle.c:1422
Inline: True
Direct callers:
  - block/blk-throttle.c:tg_set_conf_uint
  - block/blk-throttle.c:tg_set_conf_u64
```
**Symbols:**

```
c07bbe1c-c07bbf38: tg_set_conf.constprop.0 (STB_LOCAL)
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
In block/blk-throttle.c (c0000000007aee50)
Location: block/blk-throttle.c:1422
Inline: True
Direct callers:
  - block/blk-throttle.c:tg_set_conf_uint
  - block/blk-throttle.c:tg_set_conf_u64
```
**Symbols:**

```
c0000000007aee50-c0000000007aefc8: tg_set_conf.isra.0 (STB_LOCAL)
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
In block/blk-throttle.c (ffffffe000448bde)
Location: block/blk-throttle.c:1422
Inline: True
Direct callers:
  - block/blk-throttle.c:tg_set_conf_uint
  - block/blk-throttle.c:tg_set_conf_u64
```
**Symbols:**

```
ffffffe000448bde-ffffffe000448cd0: tg_set_conf.isra.0 (STB_LOCAL)
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
In block/blk-throttle.c (ffffffff81506050)
Location: block/blk-throttle.c:1422
Inline: True
Direct callers:
  - block/blk-throttle.c:tg_set_conf_uint
  - block/blk-throttle.c:tg_set_conf_u64
```
**Symbols:**

```
ffffffff81506050-ffffffff81506155: tg_set_conf.constprop.0 (STB_LOCAL)
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
In block/blk-throttle.c (ffffffff814f6510)
Location: block/blk-throttle.c:1422
Inline: True
Direct callers:
  - block/blk-throttle.c:tg_set_conf_uint
  - block/blk-throttle.c:tg_set_conf_u64
```
**Symbols:**

```
ffffffff814f6510-ffffffff814f6615: tg_set_conf.constprop.0 (STB_LOCAL)
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
In block/blk-throttle.c (ffffffff815020e0)
Location: block/blk-throttle.c:1422
Inline: True
Direct callers:
  - block/blk-throttle.c:tg_set_conf_uint
  - block/blk-throttle.c:tg_set_conf_u64
```
**Symbols:**

```
ffffffff815020e0-ffffffff815021e5: tg_set_conf.constprop.0 (STB_LOCAL)
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
In block/blk-throttle.c (ffffffff8151b400)
Location: block/blk-throttle.c:1422
Inline: True
Direct callers:
  - block/blk-throttle.c:tg_set_conf_uint
  - block/blk-throttle.c:tg_set_conf_u64
```
**Symbols:**

```
ffffffff8151b400-ffffffff8151b505: tg_set_conf.constprop.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
