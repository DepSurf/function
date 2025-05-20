# Function: <code>__zswap_param_set</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int __zswap_param_set(const char *val, const struct kernel_param *kp, char *type, char *compressor);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zswap.c (ffffffff811d82c0)
Location: mm/zswap.c:692
Inline: False
Direct callers:
  - mm/zswap.c:zswap_compressor_param_set
  - mm/zswap.c:zswap_zpool_param_set
```
**Symbols:**

```
ffffffff811d82c0-ffffffff811d85be: __zswap_param_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int __zswap_param_set(const char *val, const struct kernel_param *kp, char *type, char *compressor);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zswap.c (ffffffff811f6410)
Location: mm/zswap.c:702
Inline: False
Direct callers:
  - mm/zswap.c:zswap_zpool_param_set
  - mm/zswap.c:zswap_compressor_param_set
```
**Symbols:**

```
ffffffff811f6410-ffffffff811f66f4: __zswap_param_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __zswap_param_set(const char *val, const struct kernel_param *kp, char *type, char *compressor);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zswap.c (ffffffff81206da0)
Location: mm/zswap.c:629
Inline: False
Direct callers:
  - mm/zswap.c:zswap_zpool_param_set
  - mm/zswap.c:zswap_compressor_param_set
```
**Symbols:**

```
ffffffff81206da0-ffffffff812070a7: __zswap_param_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __zswap_param_set(const char *val, const struct kernel_param *kp, char *type, char *compressor);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zswap.c (ffffffff81212f70)
Location: mm/zswap.c:660
Inline: False
Direct callers:
  - mm/zswap.c:zswap_zpool_param_set
  - mm/zswap.c:zswap_compressor_param_set
```
**Symbols:**

```
ffffffff81212f70-ffffffff812132f1: __zswap_param_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __zswap_param_set(const char *val, const struct kernel_param *kp, char *type, char *compressor);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zswap.c (ffffffff8122dab0)
Location: mm/zswap.c:660
Inline: False
Direct callers:
  - mm/zswap.c:zswap_zpool_param_set
  - mm/zswap.c:zswap_compressor_param_set
```
**Symbols:**

```
ffffffff8122dab0-ffffffff8122de77: __zswap_param_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int __zswap_param_set(const char *val, const struct kernel_param *kp, char *type, char *compressor);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/zswap.c (0)
Location: mm/zswap.c:675
Inline: False
Direct callers:
  - mm/zswap.c:zswap_zpool_param_set
  - mm/zswap.c:zswap_compressor_param_set
```
**Symbols:**

```
ffffffff8124fee0-ffffffff8125021c: __zswap_param_set (STB_LOCAL)
ffffffff81250cc3-ffffffff81250d0b: __zswap_param_set.cold.18 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int __zswap_param_set(const char *val, const struct kernel_param *kp, char *type, char *compressor);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/zswap.c (0)
Location: mm/zswap.c:675
Inline: False
Direct callers:
  - mm/zswap.c:zswap_zpool_param_set
  - mm/zswap.c:zswap_compressor_param_set
```
**Symbols:**

```
ffffffff812643b0-ffffffff812646ec: __zswap_param_set (STB_LOCAL)
ffffffff8126519f-ffffffff812651e7: __zswap_param_set.cold.17 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int __zswap_param_set(const char *val, const struct kernel_param *kp, char *type, char *compressor);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/zswap.c (0)
Location: mm/zswap.c:666
Inline: False
Direct callers:
  - mm/zswap.c:zswap_zpool_param_set
  - mm/zswap.c:zswap_compressor_param_set
```
**Symbols:**

```
ffffffff8127f310-ffffffff8127f662: __zswap_param_set (STB_LOCAL)
ffffffff81280144-ffffffff812801bb: __zswap_param_set.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int __zswap_param_set(const char *val, const struct kernel_param *kp, char *type, char *compressor);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/zswap.c (0)
Location: mm/zswap.c:666
Inline: False
Direct callers:
  - mm/zswap.c:zswap_zpool_param_set
  - mm/zswap.c:zswap_compressor_param_set
```
**Symbols:**

```
ffffffff8128ed70-ffffffff8128f0d6: __zswap_param_set (STB_LOCAL)
ffffffff8128fba0-ffffffff8128fbeb: __zswap_param_set.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int __zswap_param_set(const char *val, const struct kernel_param *kp, char *type, char *compressor);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/zswap.c (0)
Location: mm/zswap.c:697
Inline: False
Direct callers:
  - mm/zswap.c:zswap_zpool_param_set
  - mm/zswap.c:zswap_compressor_param_set
```
**Symbols:**

```
ffffffff812c1ab0-ffffffff812c1d81: __zswap_param_set (STB_LOCAL)
ffffffff812c2800-ffffffff812c284b: __zswap_param_set.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int __zswap_param_set(const char *val, const struct kernel_param *kp, char *type, char *compressor);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/zswap.c (0)
Location: mm/zswap.c:753
Inline: False
Direct callers:
  - mm/zswap.c:zswap_zpool_param_set
  - mm/zswap.c:zswap_compressor_param_set
```
**Symbols:**

```
ffffffff812cd690-ffffffff812cd961: __zswap_param_set (STB_LOCAL)
ffffffff81be88d3-ffffffff81be891e: __zswap_param_set.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int __zswap_param_set(const char *val, const struct kernel_param *kp, char *type, char *compressor);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/zswap.c (0)
Location: mm/zswap.c:753
Inline: False
Direct callers:
  - mm/zswap.c:zswap_zpool_param_set
  - mm/zswap.c:zswap_compressor_param_set
```
**Symbols:**

```
ffffffff812d4120-ffffffff812d449c: __zswap_param_set (STB_LOCAL)
ffffffff81bda8ca-ffffffff81bda915: __zswap_param_set.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int __zswap_param_set(const char *val, const struct kernel_param *kp, char *type, char *compressor);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/zswap.c (0)
Location: mm/zswap.c:753
Inline: False
Direct callers:
  - mm/zswap.c:zswap_zpool_param_set
  - mm/zswap.c:zswap_compressor_param_set
```
**Symbols:**

```
ffffffff81319e00-ffffffff8131a1bb: __zswap_param_set (STB_LOCAL)
ffffffff81cbef67-ffffffff81cbf015: __zswap_param_set.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int __zswap_param_set(const char *val, const struct kernel_param *kp, char *type, char *compressor);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/zswap.c (0)
Location: mm/zswap.c:768
Inline: False
Direct callers:
  - mm/zswap.c:zswap_zpool_param_set
  - mm/zswap.c:zswap_compressor_param_set
```
**Symbols:**

```
ffffffff81384e30-ffffffff813851fb: __zswap_param_set (STB_LOCAL)
ffffffff81e7115a-ffffffff81e711f1: __zswap_param_set.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int __zswap_param_set(const char *val, const struct kernel_param *kp, char *type, char *compressor);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/zswap.c (0)
Location: mm/zswap.c:768
Inline: False
Direct callers:
  - mm/zswap.c:zswap_zpool_param_set
  - mm/zswap.c:zswap_compressor_param_set
```
**Symbols:**

```
ffffffff81402b10-ffffffff81402f28: __zswap_param_set (STB_LOCAL)
ffffffff82065ead-ffffffff82065f00: __zswap_param_set.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int __zswap_param_set(const char *val, const struct kernel_param *kp, char *type, char *compressor);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/zswap.c (0)
Location: mm/zswap.c:874
Inline: False
Direct callers:
  - mm/zswap.c:zswap_zpool_param_set
  - mm/zswap.c:zswap_compressor_param_set
```
**Symbols:**

```
ffffffff81436020-ffffffff8143649f: __zswap_param_set (STB_LOCAL)
ffffffff820e5666-ffffffff820e56be: __zswap_param_set.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int __zswap_param_set(const char *val, const struct kernel_param *kp, char *type, char *compressor);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/zswap.c (0)
Location: mm/zswap.c:1216
Inline: False
Direct callers:
  - mm/zswap.c:zswap_zpool_param_set
  - mm/zswap.c:zswap_compressor_param_set
```
**Symbols:**

```
ffffffff8146fa50-ffffffff8146ff06: __zswap_param_set (STB_LOCAL)
ffffffff821c283a-ffffffff821c2892: __zswap_param_set.cold (STB_LOCAL)
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
int __zswap_param_set(const char *val, const struct kernel_param *kp, char *type, char *compressor);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zswap.c (ffff80001032ba80)
Location: mm/zswap.c:666
Inline: False
Direct callers:
  - mm/zswap.c:zswap_zpool_param_set
  - mm/zswap.c:zswap_compressor_param_set
```
**Symbols:**

```
ffff80001032ba80-ffff80001032be40: __zswap_param_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __zswap_param_set(const char *val, const struct kernel_param *kp, char *type, char *compressor);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zswap.c (c0541b24)
Location: mm/zswap.c:666
Inline: False
Direct callers:
  - mm/zswap.c:zswap_zpool_param_set
  - mm/zswap.c:zswap_compressor_param_set
```
**Symbols:**

```
c0541b24-c0541ec8: __zswap_param_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __zswap_param_set(const char *val, const struct kernel_param *kp, char *type, char *compressor);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zswap.c (c000000000403470)
Location: mm/zswap.c:666
Inline: False
Direct callers:
  - mm/zswap.c:zswap_zpool_param_set
  - mm/zswap.c:zswap_compressor_param_set
```
**Symbols:**

```
c000000000403470-c000000000403db0: __zswap_param_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __zswap_param_set(const char *val, const struct kernel_param *kp, char *type, char *compressor);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zswap.c (ffffffe00022a67e)
Location: mm/zswap.c:666
Inline: False
Direct callers:
  - mm/zswap.c:zswap_zpool_param_set
  - mm/zswap.c:zswap_compressor_param_set
```
**Symbols:**

```
ffffffe00022a67e-ffffffe00022a9d8: __zswap_param_set (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int __zswap_param_set(const char *val, const struct kernel_param *kp, char *type, char *compressor);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/zswap.c (0)
Location: mm/zswap.c:666
Inline: False
Direct callers:
  - mm/zswap.c:zswap_zpool_param_set
  - mm/zswap.c:zswap_compressor_param_set
```
**Symbols:**

```
ffffffff81287350-ffffffff812876b6: __zswap_param_set (STB_LOCAL)
ffffffff81288180-ffffffff812881cb: __zswap_param_set.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int __zswap_param_set(const char *val, const struct kernel_param *kp, char *type, char *compressor);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/zswap.c (0)
Location: mm/zswap.c:666
Inline: False
Direct callers:
  - mm/zswap.c:zswap_zpool_param_set
  - mm/zswap.c:zswap_compressor_param_set
```
**Symbols:**

```
ffffffff812791b0-ffffffff81279516: __zswap_param_set (STB_LOCAL)
ffffffff81279fe0-ffffffff8127a02b: __zswap_param_set.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int __zswap_param_set(const char *val, const struct kernel_param *kp, char *type, char *compressor);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/zswap.c (0)
Location: mm/zswap.c:666
Inline: False
Direct callers:
  - mm/zswap.c:zswap_zpool_param_set
  - mm/zswap.c:zswap_compressor_param_set
```
**Symbols:**

```
ffffffff81285160-ffffffff812854c6: __zswap_param_set (STB_LOCAL)
ffffffff81285f90-ffffffff81285fdb: __zswap_param_set.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int __zswap_param_set(const char *val, const struct kernel_param *kp, char *type, char *compressor);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/zswap.c (0)
Location: mm/zswap.c:666
Inline: False
Direct callers:
  - mm/zswap.c:zswap_zpool_param_set
  - mm/zswap.c:zswap_compressor_param_set
```
**Symbols:**

```
ffffffff812952c0-ffffffff812955f9: __zswap_param_set (STB_LOCAL)
ffffffff81295d79-ffffffff81295dc1: __zswap_param_set.cold (STB_LOCAL)
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
