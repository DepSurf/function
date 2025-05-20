# Function: <code>clk_hw_register_fractional_divider</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct clk_hw *clk_hw_register_fractional_divider(struct device *dev, const char *name, const char *parent_name, long unsigned int flags, void *reg, u8 mshift, u8 mwidth, u8 nshift, u8 nwidth, u8 clk_divider_flags, spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-fractional-divider.c (ffffffff8174f690)
Location: drivers/clk/clk-fractional-divider.c:119
Inline: False
Direct callers:
  - drivers/clk/clk-fractional-divider.c:clk_register_fractional_divider
```
**Symbols:**

```
ffffffff8174f690-ffffffff8174f7f3: clk_hw_register_fractional_divider (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct clk_hw *clk_hw_register_fractional_divider(struct device *dev, const char *name, const char *parent_name, long unsigned int flags, void *reg, u8 mshift, u8 mwidth, u8 nshift, u8 nwidth, u8 clk_divider_flags, spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-fractional-divider.c (ffffffff81537f00)
Location: drivers/clk/clk-fractional-divider.c:119
Inline: False
Direct callers:
  - drivers/clk/clk-fractional-divider.c:clk_register_fractional_divider
```
**Symbols:**

```
ffffffff81537f00-ffffffff81538063: clk_hw_register_fractional_divider (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct clk_hw *clk_hw_register_fractional_divider(struct device *dev, const char *name, const char *parent_name, long unsigned int flags, void *reg, u8 mshift, u8 mwidth, u8 nshift, u8 nwidth, u8 clk_divider_flags, spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-fractional-divider.c (ffffffff8154b1b0)
Location: drivers/clk/clk-fractional-divider.c:119
Inline: False
Direct callers:
  - drivers/clk/clk-fractional-divider.c:clk_register_fractional_divider
```
**Symbols:**

```
ffffffff8154b1b0-ffffffff8154b317: clk_hw_register_fractional_divider (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct clk_hw *clk_hw_register_fractional_divider(struct device *dev, const char *name, const char *parent_name, long unsigned int flags, void *reg, u8 mshift, u8 mwidth, u8 nshift, u8 nwidth, u8 clk_divider_flags, spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-fractional-divider.c (ffffffff815ae7e0)
Location: drivers/clk/clk-fractional-divider.c:131
Inline: False
Direct callers:
  - drivers/clk/clk-fractional-divider.c:clk_register_fractional_divider
```
**Symbols:**

```
ffffffff815ae7e0-ffffffff815ae947: clk_hw_register_fractional_divider (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct clk_hw *clk_hw_register_fractional_divider(struct device *dev, const char *name, const char *parent_name, long unsigned int flags, void *reg, u8 mshift, u8 mwidth, u8 nshift, u8 nwidth, u8 clk_divider_flags, spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-fractional-divider.c (ffffffff815e6a40)
Location: drivers/clk/clk-fractional-divider.c:131
Inline: False
Direct callers:
  - drivers/clk/clk-fractional-divider.c:clk_register_fractional_divider
```
**Symbols:**

```
ffffffff815e6a40-ffffffff815e6ba5: clk_hw_register_fractional_divider (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct clk_hw *clk_hw_register_fractional_divider(struct device *dev, const char *name, const char *parent_name, long unsigned int flags, void *reg, u8 mshift, u8 mwidth, u8 nshift, u8 nwidth, u8 clk_divider_flags, spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-fractional-divider.c (ffffffff81600d90)
Location: drivers/clk/clk-fractional-divider.c:138
Inline: False
Direct callers:
  - drivers/clk/clk-fractional-divider.c:clk_register_fractional_divider
```
**Symbols:**

```
ffffffff81600d90-ffffffff81600ef5: clk_hw_register_fractional_divider (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct clk_hw *clk_hw_register_fractional_divider(struct device *dev, const char *name, const char *parent_name, long unsigned int flags, void *reg, u8 mshift, u8 mwidth, u8 nshift, u8 nwidth, u8 clk_divider_flags, spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-fractional-divider.c (ffffffff81633680)
Location: drivers/clk/clk-fractional-divider.c:155
Inline: False
Direct callers:
  - drivers/clk/clk-fractional-divider.c:clk_register_fractional_divider
```
**Symbols:**

```
ffffffff81633680-ffffffff816337e7: clk_hw_register_fractional_divider (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct clk_hw *clk_hw_register_fractional_divider(struct device *dev, const char *name, const char *parent_name, long unsigned int flags, void *reg, u8 mshift, u8 mwidth, u8 nshift, u8 nwidth, u8 clk_divider_flags, spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-fractional-divider.c (ffffffff816553b0)
Location: drivers/clk/clk-fractional-divider.c:155
Inline: False
Direct callers:
  - drivers/clk/clk-fractional-divider.c:clk_register_fractional_divider
```
**Symbols:**

```
ffffffff816553b0-ffffffff81655517: clk_hw_register_fractional_divider (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct clk_hw *clk_hw_register_fractional_divider(struct device *dev, const char *name, const char *parent_name, long unsigned int flags, void *reg, u8 mshift, u8 mwidth, u8 nshift, u8 nwidth, u8 clk_divider_flags, spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-fractional-divider.c (ffffffff81705666)
Location: drivers/clk/clk-fractional-divider.c:155
Inline: True
Inline callers:
  - drivers/clk/clk-fractional-divider.c:clk_register_fractional_divider
```
**Symbols:**

```
ffffffff817051d0-ffffffff8170533a: clk_hw_register_fractional_divider (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct clk_hw *clk_hw_register_fractional_divider(struct device *dev, const char *name, const char *parent_name, long unsigned int flags, void *reg, u8 mshift, u8 mwidth, u8 nshift, u8 nwidth, u8 clk_divider_flags, spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-fractional-divider.c (ffffffff81722956)
Location: drivers/clk/clk-fractional-divider.c:155
Inline: True
Inline callers:
  - drivers/clk/clk-fractional-divider.c:clk_register_fractional_divider
```
**Symbols:**

```
ffffffff817224c0-ffffffff8172262a: clk_hw_register_fractional_divider (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct clk_hw *clk_hw_register_fractional_divider(struct device *dev, const char *name, const char *parent_name, long unsigned int flags, void *reg, u8 mshift, u8 mwidth, u8 nshift, u8 nwidth, u8 clk_divider_flags, spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-fractional-divider.c (ffffffff817038d0)
Location: drivers/clk/clk-fractional-divider.c:155
Inline: False
Direct callers:
  - drivers/clk/clk-fractional-divider.c:clk_register_fractional_divider
```
**Symbols:**

```
ffffffff817038d0-ffffffff81703a37: clk_hw_register_fractional_divider (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct clk_hw *clk_hw_register_fractional_divider(struct device *dev, const char *name, const char *parent_name, long unsigned int flags, void *reg, u8 mshift, u8 mwidth, u8 nshift, u8 nwidth, u8 clk_divider_flags, spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/clk/clk-fractional-divider.c (0)
Location: drivers/clk/clk-fractional-divider.c:193
Inline: False
Direct callers:
  - drivers/clk/clk-fractional-divider.c:clk_register_fractional_divider
```
**Symbols:**

```
ffffffff81cf3a3e-ffffffff81cf3ad8: clk_hw_register_fractional_divider.cold (STB_LOCAL)
ffffffff8177e5d0-ffffffff8177e76d: clk_hw_register_fractional_divider (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct clk_hw *clk_hw_register_fractional_divider(struct device *dev, const char *name, const char *parent_name, long unsigned int flags, void *reg, u8 mshift, u8 mwidth, u8 nshift, u8 nwidth, u8 clk_divider_flags, spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/clk/clk-fractional-divider.c (0)
Location: drivers/clk/clk-fractional-divider.c:193
Inline: False
Direct callers:
  - drivers/clk/clk-fractional-divider.c:clk_register_fractional_divider
```
**Symbols:**

```
ffffffff81ebbcc7-ffffffff81ebbd88: clk_hw_register_fractional_divider.cold (STB_LOCAL)
ffffffff818b53f0-ffffffff818b55c8: clk_hw_register_fractional_divider (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct clk_hw *clk_hw_register_fractional_divider(struct device *dev, const char *name, const char *parent_name, long unsigned int flags, void *reg, u8 mshift, u8 mwidth, u8 nshift, u8 nwidth, u8 clk_divider_flags, spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/clk/clk-fractional-divider.c (0)
Location: drivers/clk/clk-fractional-divider.c:240
Inline: False
Direct callers:
  - drivers/clk/clk-fractional-divider.c:clk_register_fractional_divider
```
**Symbols:**

```
ffffffff8209357d-ffffffff8209363e: clk_hw_register_fractional_divider.cold (STB_LOCAL)
ffffffff81a02280-ffffffff81a02458: clk_hw_register_fractional_divider (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct clk_hw *clk_hw_register_fractional_divider(struct device *dev, const char *name, const char *parent_name, long unsigned int flags, void *reg, u8 mshift, u8 mwidth, u8 nshift, u8 nwidth, u8 clk_divider_flags, spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-fractional-divider.c (ffffffff81a4b5f2)
Location: drivers/clk/clk-fractional-divider.c:248
Inline: True
Inline callers:
  - drivers/clk/clk-fractional-divider.c:clk_register_fractional_divider
```
**Symbols:**

```
ffffffff81a4afa0-ffffffff81a4b0e7: clk_hw_register_fractional_divider (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct clk_hw *clk_hw_register_fractional_divider(struct device *dev, const char *name, const char *parent_name, long unsigned int flags, void *reg, u8 mshift, u8 mwidth, u8 nshift, u8 nwidth, u8 clk_divider_flags, spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-fractional-divider.c (ffffffff81a973d0)
Location: drivers/clk/clk-fractional-divider.c:261
Inline: True
Inline callers:
  - drivers/clk/clk-fractional-divider.c:clk_register_fractional_divider
```
**Symbols:**

```
ffffffff81a96d10-ffffffff81a96e79: clk_hw_register_fractional_divider (STB_GLOBAL)
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
struct clk_hw *clk_hw_register_fractional_divider(struct device *dev, const char *name, const char *parent_name, long unsigned int flags, void *reg, u8 mshift, u8 mwidth, u8 nshift, u8 nwidth, u8 clk_divider_flags, spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-fractional-divider.c (ffff8000107c6d50)
Location: drivers/clk/clk-fractional-divider.c:155
Inline: False
Direct callers:
  - drivers/clk/clk-fractional-divider.c:clk_register_fractional_divider
```
**Symbols:**

```
ffff8000107c6d50-ffff8000107c6eb8: clk_hw_register_fractional_divider (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct clk_hw *clk_hw_register_fractional_divider(struct device *dev, const char *name, const char *parent_name, long unsigned int flags, void *reg, u8 mshift, u8 mwidth, u8 nshift, u8 nwidth, u8 clk_divider_flags, spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-fractional-divider.c (c08f1eec)
Location: drivers/clk/clk-fractional-divider.c:155
Inline: False
Direct callers:
  - drivers/clk/clk-fractional-divider.c:clk_register_fractional_divider
```
**Symbols:**

```
c08f1eec-c08f2050: clk_hw_register_fractional_divider (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct clk_hw *clk_hw_register_fractional_divider(struct device *dev, const char *name, const char *parent_name, long unsigned int flags, void *reg, u8 mshift, u8 mwidth, u8 nshift, u8 nwidth, u8 clk_divider_flags, spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-fractional-divider.c (ffffffe000513d2c)
Location: drivers/clk/clk-fractional-divider.c:155
Inline: False
Direct callers:
  - drivers/clk/clk-fractional-divider.c:clk_register_fractional_divider
```
**Symbols:**

```
ffffffe000513d2c-ffffffe000513e42: clk_hw_register_fractional_divider (STB_GLOBAL)
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
struct clk_hw *clk_hw_register_fractional_divider(struct device *dev, const char *name, const char *parent_name, long unsigned int flags, void *reg, u8 mshift, u8 mwidth, u8 nshift, u8 nwidth, u8 clk_divider_flags, spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-fractional-divider.c (ffffffff8161b410)
Location: drivers/clk/clk-fractional-divider.c:155
Inline: False
Direct callers:
  - drivers/clk/clk-fractional-divider.c:clk_register_fractional_divider
```
**Symbols:**

```
ffffffff8161b410-ffffffff8161b577: clk_hw_register_fractional_divider (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct clk_hw *clk_hw_register_fractional_divider(struct device *dev, const char *name, const char *parent_name, long unsigned int flags, void *reg, u8 mshift, u8 mwidth, u8 nshift, u8 nwidth, u8 clk_divider_flags, spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-fractional-divider.c (ffffffff8160f940)
Location: drivers/clk/clk-fractional-divider.c:155
Inline: False
Direct callers:
  - drivers/clk/clk-fractional-divider.c:clk_register_fractional_divider
```
**Symbols:**

```
ffffffff8160f940-ffffffff8160faa7: clk_hw_register_fractional_divider (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct clk_hw *clk_hw_register_fractional_divider(struct device *dev, const char *name, const char *parent_name, long unsigned int flags, void *reg, u8 mshift, u8 mwidth, u8 nshift, u8 nwidth, u8 clk_divider_flags, spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-fractional-divider.c (ffffffff816491f0)
Location: drivers/clk/clk-fractional-divider.c:155
Inline: False
Direct callers:
  - drivers/clk/clk-fractional-divider.c:clk_register_fractional_divider
```
**Symbols:**

```
ffffffff816491f0-ffffffff81649357: clk_hw_register_fractional_divider (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct clk_hw *clk_hw_register_fractional_divider(struct device *dev, const char *name, const char *parent_name, long unsigned int flags, void *reg, u8 mshift, u8 mwidth, u8 nshift, u8 nwidth, u8 clk_divider_flags, spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-fractional-divider.c (ffffffff81663780)
Location: drivers/clk/clk-fractional-divider.c:155
Inline: False
Direct callers:
  - drivers/clk/clk-fractional-divider.c:clk_register_fractional_divider
```
**Symbols:**

```
ffffffff81663780-ffffffff816638e7: clk_hw_register_fractional_divider (STB_GLOBAL)
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
