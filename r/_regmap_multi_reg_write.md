# Function: <code>_regmap_multi_reg_write</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int _regmap_multi_reg_write(struct regmap *map, const struct reg_sequence *regs, size_t num_regs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff81566d00)
Location: drivers/base/regmap/regmap.c:1959
Inline: True
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_multi_reg_write
  - drivers/base/regmap/regmap.c:regmap_multi_reg_write_bypassed
  - drivers/base/regmap/regmap.c:regmap_register_patch
```
**Symbols:**

```
ffffffff81566d00-ffffffff815670c3: _regmap_multi_reg_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int _regmap_multi_reg_write(struct regmap *map, const struct reg_sequence *regs, size_t num_regs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff815bb710)
Location: drivers/base/regmap/regmap.c:2056
Inline: True
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_register_patch
  - drivers/base/regmap/regmap.c:regmap_multi_reg_write_bypassed
  - drivers/base/regmap/regmap.c:regmap_multi_reg_write
```
**Symbols:**

```
ffffffff815bb710-ffffffff815bbb0d: _regmap_multi_reg_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int _regmap_multi_reg_write(struct regmap *map, const struct reg_sequence *regs, size_t num_regs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff815eab20)
Location: drivers/base/regmap/regmap.c:2102
Inline: True
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_register_patch
  - drivers/base/regmap/regmap.c:regmap_multi_reg_write_bypassed
  - drivers/base/regmap/regmap.c:regmap_multi_reg_write
```
**Symbols:**

```
ffffffff815eab20-ffffffff815eaf1d: _regmap_multi_reg_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int _regmap_multi_reg_write(struct regmap *map, const struct reg_sequence *regs, size_t num_regs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff815ff450)
Location: drivers/base/regmap/regmap.c:2106
Inline: True
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_register_patch
  - drivers/base/regmap/regmap.c:regmap_multi_reg_write_bypassed
  - drivers/base/regmap/regmap.c:regmap_multi_reg_write
```
**Symbols:**

```
ffffffff815ff450-ffffffff815ff85a: _regmap_multi_reg_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int _regmap_multi_reg_write(struct regmap *map, const struct reg_sequence *regs, size_t num_regs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff81667740)
Location: drivers/base/regmap/regmap.c:2185
Inline: True
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_register_patch
  - drivers/base/regmap/regmap.c:regmap_multi_reg_write_bypassed
  - drivers/base/regmap/regmap.c:regmap_multi_reg_write
```
**Symbols:**

```
ffffffff81667740-ffffffff81667b4d: _regmap_multi_reg_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int _regmap_multi_reg_write(struct regmap *map, const struct reg_sequence *regs, size_t num_regs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff816a2ce0)
Location: drivers/base/regmap/regmap.c:2165
Inline: True
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_register_patch
  - drivers/base/regmap/regmap.c:regmap_multi_reg_write_bypassed
  - drivers/base/regmap/regmap.c:regmap_multi_reg_write
```
**Symbols:**

```
ffffffff816a2ce0-ffffffff816a30de: _regmap_multi_reg_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int _regmap_multi_reg_write(struct regmap *map, const struct reg_sequence *regs, size_t num_regs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff816c3700)
Location: drivers/base/regmap/regmap.c:2264
Inline: True
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_register_patch
  - drivers/base/regmap/regmap.c:regmap_multi_reg_write_bypassed
  - drivers/base/regmap/regmap.c:regmap_multi_reg_write
```
**Symbols:**

```
ffffffff816c3700-ffffffff816c3afe: _regmap_multi_reg_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int _regmap_multi_reg_write(struct regmap *map, const struct reg_sequence *regs, size_t num_regs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff816fe63e)
Location: drivers/base/regmap/regmap.c:2261
Inline: True
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_register_patch
  - drivers/base/regmap/regmap.c:regmap_multi_reg_write_bypassed
  - drivers/base/regmap/regmap.c:regmap_multi_reg_write
```
**Symbols:**

```
ffffffff816fe5b0-ffffffff816fe98c: _regmap_multi_reg_write (STB_LOCAL)
ffffffff816ff261-ffffffff816ff294: _regmap_multi_reg_write.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int _regmap_multi_reg_write(struct regmap *map, const struct reg_sequence *regs, size_t num_regs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff81722a5e)
Location: drivers/base/regmap/regmap.c:2268
Inline: True
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_register_patch
  - drivers/base/regmap/regmap.c:regmap_multi_reg_write_bypassed
  - drivers/base/regmap/regmap.c:regmap_multi_reg_write
```
**Symbols:**

```
ffffffff817229d0-ffffffff81722dab: _regmap_multi_reg_write (STB_LOCAL)
ffffffff817235ff-ffffffff8172361f: _regmap_multi_reg_write.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int _regmap_multi_reg_write(struct regmap *map, const struct reg_sequence *regs, size_t num_regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regmap.c (0)
Location: drivers/base/regmap/regmap.c:2263
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_register_patch
  - drivers/base/regmap/regmap.c:regmap_multi_reg_write_bypassed
  - drivers/base/regmap/regmap.c:regmap_multi_reg_write
```
**Symbols:**

```
ffffffff817decf0-ffffffff817def4d: _regmap_multi_reg_write (STB_LOCAL)
ffffffff817df80d-ffffffff817df82d: _regmap_multi_reg_write.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int _regmap_multi_reg_write(struct regmap *map, const struct reg_sequence *regs, size_t num_regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regmap.c (0)
Location: drivers/base/regmap/regmap.c:2416
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_register_patch
  - drivers/base/regmap/regmap.c:regmap_multi_reg_write_bypassed
  - drivers/base/regmap/regmap.c:regmap_multi_reg_write
```
**Symbols:**

```
ffffffff817f3d70-ffffffff817f4017: _regmap_multi_reg_write (STB_LOCAL)
ffffffff81c0f49e-ffffffff81c0f4be: _regmap_multi_reg_write.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int _regmap_multi_reg_write(struct regmap *map, const struct reg_sequence *regs, size_t num_regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regmap.c (0)
Location: drivers/base/regmap/regmap.c:2416
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_register_patch
  - drivers/base/regmap/regmap.c:regmap_multi_reg_write_bypassed
  - drivers/base/regmap/regmap.c:regmap_multi_reg_write
```
**Symbols:**

```
ffffffff817d85e0-ffffffff817d8887: _regmap_multi_reg_write (STB_LOCAL)
ffffffff81c015e8-ffffffff81c01608: _regmap_multi_reg_write.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int _regmap_multi_reg_write(struct regmap *map, const struct reg_sequence *regs, size_t num_regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regmap.c (0)
Location: drivers/base/regmap/regmap.c:2457
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_register_patch
  - drivers/base/regmap/regmap.c:regmap_multi_reg_write_bypassed
  - drivers/base/regmap/regmap.c:regmap_multi_reg_write
```
**Symbols:**

```
ffffffff81863d20-ffffffff81863fc6: _regmap_multi_reg_write (STB_LOCAL)
ffffffff81d04c79-ffffffff81d04cf4: _regmap_multi_reg_write.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int _regmap_multi_reg_write(struct regmap *map, const struct reg_sequence *regs, size_t num_regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regmap.c (0)
Location: drivers/base/regmap/regmap.c:2477
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_register_patch
  - drivers/base/regmap/regmap.c:regmap_multi_reg_write_bypassed
  - drivers/base/regmap/regmap.c:regmap_multi_reg_write
```
**Symbols:**

```
ffffffff819abed0-ffffffff819ac1fe: _regmap_multi_reg_write (STB_LOCAL)
ffffffff81ecd688-ffffffff81ecd723: _regmap_multi_reg_write.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int _regmap_multi_reg_write(struct regmap *map, const struct reg_sequence *regs, size_t num_regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regmap.c (0)
Location: drivers/base/regmap/regmap.c:2608
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_register_patch
  - drivers/base/regmap/regmap.c:regmap_multi_reg_write_bypassed
  - drivers/base/regmap/regmap.c:regmap_multi_reg_write
```
**Symbols:**

```
ffffffff81b1f4a0-ffffffff81b1f7e3: _regmap_multi_reg_write (STB_LOCAL)
ffffffff82099393-ffffffff8209940e: _regmap_multi_reg_write.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int _regmap_multi_reg_write(struct regmap *map, const struct reg_sequence *regs, size_t num_regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regmap.c (0)
Location: drivers/base/regmap/regmap.c:2625
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_register_patch
  - drivers/base/regmap/regmap.c:regmap_multi_reg_write_bypassed
  - drivers/base/regmap/regmap.c:regmap_multi_reg_write
```
**Symbols:**

```
ffffffff81b6e6a0-ffffffff81b6e9e3: _regmap_multi_reg_write (STB_LOCAL)
ffffffff8211a443-ffffffff8211a4a1: _regmap_multi_reg_write.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int _regmap_multi_reg_write(struct regmap *map, const struct reg_sequence *regs, size_t num_regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regmap.c (0)
Location: drivers/base/regmap/regmap.c:2513
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_register_patch
  - drivers/base/regmap/regmap.c:regmap_multi_reg_write_bypassed
  - drivers/base/regmap/regmap.c:regmap_multi_reg_write
```
**Symbols:**

```
ffffffff81bc22a0-ffffffff81bc25e3: _regmap_multi_reg_write (STB_LOCAL)
ffffffff821f82ca-ffffffff821f8328: _regmap_multi_reg_write.cold (STB_LOCAL)
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
int _regmap_multi_reg_write(struct regmap *map, const struct reg_sequence *regs, size_t num_regs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffff800010917340)
Location: drivers/base/regmap/regmap.c:2268
Inline: True
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_register_patch
  - drivers/base/regmap/regmap.c:regmap_multi_reg_write_bypassed
  - drivers/base/regmap/regmap.c:regmap_multi_reg_write
```
**Symbols:**

```
ffff800010917340-ffff80001091777c: _regmap_multi_reg_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int _regmap_multi_reg_write(struct regmap *map, const struct reg_sequence *regs, size_t num_regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (c09fd1ac)
Location: drivers/base/regmap/regmap.c:2268
Inline: False
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_register_patch
  - drivers/base/regmap/regmap.c:regmap_multi_reg_write_bypassed
  - drivers/base/regmap/regmap.c:regmap_multi_reg_write
```
**Symbols:**

```
c09fd1ac-c09fd60c: _regmap_multi_reg_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int _regmap_multi_reg_write(struct regmap *map, const struct reg_sequence *regs, size_t num_regs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (c0000000009ba180)
Location: drivers/base/regmap/regmap.c:2268
Inline: True
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_register_patch
  - drivers/base/regmap/regmap.c:regmap_multi_reg_write_bypassed
  - drivers/base/regmap/regmap.c:regmap_multi_reg_write
```
**Symbols:**

```
c0000000009ba180-c0000000009ba7a8: _regmap_multi_reg_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int _regmap_multi_reg_write(struct regmap *map, const struct reg_sequence *regs, size_t num_regs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffe000597cd0)
Location: drivers/base/regmap/regmap.c:2268
Inline: True
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_register_patch
  - drivers/base/regmap/regmap.c:regmap_multi_reg_write_bypassed
  - drivers/base/regmap/regmap.c:regmap_multi_reg_write
```
**Symbols:**

```
ffffffe000597cd0-ffffffe000597fae: _regmap_multi_reg_write (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
int _regmap_multi_reg_write(struct regmap *map, const struct reg_sequence *regs, size_t num_regs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff816e8d8e)
Location: drivers/base/regmap/regmap.c:2268
Inline: True
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_register_patch
  - drivers/base/regmap/regmap.c:regmap_multi_reg_write_bypassed
  - drivers/base/regmap/regmap.c:regmap_multi_reg_write
```
**Symbols:**

```
ffffffff816e8d00-ffffffff816e90db: _regmap_multi_reg_write (STB_LOCAL)
ffffffff816e992f-ffffffff816e994f: _regmap_multi_reg_write.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
int _regmap_multi_reg_write(struct regmap *map, const struct reg_sequence *regs, size_t num_regs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff816c33ce)
Location: drivers/base/regmap/regmap.c:2268
Inline: True
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_register_patch
  - drivers/base/regmap/regmap.c:regmap_multi_reg_write_bypassed
  - drivers/base/regmap/regmap.c:regmap_multi_reg_write
```
**Symbols:**

```
ffffffff816c3340-ffffffff816c371b: _regmap_multi_reg_write (STB_LOCAL)
ffffffff816c3f6f-ffffffff816c3f8f: _regmap_multi_reg_write.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
int _regmap_multi_reg_write(struct regmap *map, const struct reg_sequence *regs, size_t num_regs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff81715f1e)
Location: drivers/base/regmap/regmap.c:2268
Inline: True
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_register_patch
  - drivers/base/regmap/regmap.c:regmap_multi_reg_write_bypassed
  - drivers/base/regmap/regmap.c:regmap_multi_reg_write
```
**Symbols:**

```
ffffffff81715e90-ffffffff8171626b: _regmap_multi_reg_write (STB_LOCAL)
ffffffff81716abf-ffffffff81716adf: _regmap_multi_reg_write.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
int _regmap_multi_reg_write(struct regmap *map, const struct reg_sequence *regs, size_t num_regs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/regmap/regmap.c (ffffffff817311be)
Location: drivers/base/regmap/regmap.c:2268
Inline: True
Direct callers:
  - drivers/base/regmap/regmap.c:regmap_register_patch
  - drivers/base/regmap/regmap.c:regmap_multi_reg_write_bypassed
  - drivers/base/regmap/regmap.c:regmap_multi_reg_write
```
**Symbols:**

```
ffffffff81731130-ffffffff8173150b: _regmap_multi_reg_write (STB_LOCAL)
ffffffff81731d5f-ffffffff81731d7f: _regmap_multi_reg_write.cold (STB_LOCAL)
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
