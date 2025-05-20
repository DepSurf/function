# Function: <code>_register_divider</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct clk *_register_divider(struct device *dev, const char *name, const char *parent_name, long unsigned int flags, void *reg, u8 shift, u8 width, u8 clk_divider_flags, const struct clk_div_table *table, spinlock_t *lock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-divider.c (ffffffff816e9760)
Location: drivers/clk/clk-divider.c:425
Inline: False
Direct callers:
  - drivers/clk/clk-divider.c:clk_register_divider
  - drivers/clk/clk-divider.c:clk_register_divider_table
```
**Symbols:**

```
ffffffff816e9760-ffffffff816e98bc: _register_divider (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct clk_hw *_register_divider(struct device *dev, const char *name, const char *parent_name, long unsigned int flags, void *reg, u8 shift, u8 width, u8 clk_divider_flags, const struct clk_div_table *table, spinlock_t *lock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-divider.c (ffffffff8174dc90)
Location: drivers/clk/clk-divider.c:429
Inline: False
Direct callers:
  - drivers/clk/clk-divider.c:clk_hw_register_divider_table
  - drivers/clk/clk-divider.c:clk_register_divider_table
  - drivers/clk/clk-divider.c:clk_hw_register_divider
  - drivers/clk/clk-divider.c:clk_register_divider
```
**Symbols:**

```
ffffffff8174dc90-ffffffff8174ddf5: _register_divider (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct clk_hw *_register_divider(struct device *dev, const char *name, const char *parent_name, long unsigned int flags, void *reg, u8 shift, u8 width, u8 clk_divider_flags, const struct clk_div_table *table, spinlock_t *lock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-divider.c (ffffffff81536500)
Location: drivers/clk/clk-divider.c:429
Inline: False
Direct callers:
  - drivers/clk/clk-divider.c:clk_hw_register_divider_table
  - drivers/clk/clk-divider.c:clk_register_divider_table
  - drivers/clk/clk-divider.c:clk_hw_register_divider
  - drivers/clk/clk-divider.c:clk_register_divider
```
**Symbols:**

```
ffffffff81536500-ffffffff81536665: _register_divider (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct clk_hw *_register_divider(struct device *dev, const char *name, const char *parent_name, long unsigned int flags, void *reg, u8 shift, u8 width, u8 clk_divider_flags, const struct clk_div_table *table, spinlock_t *lock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-divider.c (ffffffff81549890)
Location: drivers/clk/clk-divider.c:430
Inline: False
Direct callers:
  - drivers/clk/clk-divider.c:clk_hw_register_divider_table
  - drivers/clk/clk-divider.c:clk_register_divider_table
  - drivers/clk/clk-divider.c:clk_hw_register_divider
  - drivers/clk/clk-divider.c:clk_register_divider
```
**Symbols:**

```
ffffffff81549890-ffffffff815499f0: _register_divider (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct clk_hw *_register_divider(struct device *dev, const char *name, const char *parent_name, long unsigned int flags, void *reg, u8 shift, u8 width, u8 clk_divider_flags, const struct clk_div_table *table, spinlock_t *lock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-divider.c (ffffffff815ace10)
Location: drivers/clk/clk-divider.c:431
Inline: False
Direct callers:
  - drivers/clk/clk-divider.c:clk_hw_register_divider_table
  - drivers/clk/clk-divider.c:clk_register_divider_table
  - drivers/clk/clk-divider.c:clk_hw_register_divider
  - drivers/clk/clk-divider.c:clk_register_divider
```
**Symbols:**

```
ffffffff815ace10-ffffffff815acf70: _register_divider (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
struct clk_hw *_register_divider(struct device *dev, const char *name, const char *parent_name, long unsigned int flags, void *reg, u8 shift, u8 width, u8 clk_divider_flags, const struct clk_div_table *table, spinlock_t *lock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/clk/clk-divider.c (0)
Location: drivers/clk/clk-divider.c:453
Inline: False
Direct callers:
  - drivers/clk/clk-divider.c:clk_hw_register_divider_table
  - drivers/clk/clk-divider.c:clk_register_divider_table
  - drivers/clk/clk-divider.c:clk_hw_register_divider
  - drivers/clk/clk-divider.c:clk_register_divider
```
**Symbols:**

```
ffffffff815e4fa0-ffffffff815e50e9: _register_divider (STB_LOCAL)
ffffffff815e51c4-ffffffff815e51dc: _register_divider.cold.5 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
struct clk_hw *_register_divider(struct device *dev, const char *name, const char *parent_name, long unsigned int flags, void *reg, u8 shift, u8 width, u8 clk_divider_flags, const struct clk_div_table *table, spinlock_t *lock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/clk/clk-divider.c (0)
Location: drivers/clk/clk-divider.c:450
Inline: False
Direct callers:
  - drivers/clk/clk-divider.c:clk_hw_register_divider_table
  - drivers/clk/clk-divider.c:clk_register_divider_table
  - drivers/clk/clk-divider.c:clk_hw_register_divider
  - drivers/clk/clk-divider.c:clk_register_divider
```
**Symbols:**

```
ffffffff815febd0-ffffffff815fed19: _register_divider (STB_LOCAL)
ffffffff815ff5b7-ffffffff815ff5cf: _register_divider.cold.4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
struct clk_hw *_register_divider(struct device *dev, const char *name, const char *parent_name, long unsigned int flags, void *reg, u8 shift, u8 width, u8 clk_divider_flags, const struct clk_div_table *table, spinlock_t *lock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/clk/clk-divider.c (0)
Location: drivers/clk/clk-divider.c:466
Inline: False
Direct callers:
  - drivers/clk/clk-divider.c:clk_hw_register_divider_table
  - drivers/clk/clk-divider.c:clk_register_divider_table
  - drivers/clk/clk-divider.c:clk_hw_register_divider
  - drivers/clk/clk-divider.c:clk_register_divider
```
**Symbols:**

```
ffffffff816312c0-ffffffff8163140a: _register_divider (STB_LOCAL)
ffffffff81631cee-ffffffff81631d06: _register_divider.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
struct clk_hw *_register_divider(struct device *dev, const char *name, const char *parent_name, long unsigned int flags, void *reg, u8 shift, u8 width, u8 clk_divider_flags, const struct clk_div_table *table, spinlock_t *lock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/clk/clk-divider.c (0)
Location: drivers/clk/clk-divider.c:466
Inline: False
Direct callers:
  - drivers/clk/clk-divider.c:clk_hw_register_divider_table
  - drivers/clk/clk-divider.c:clk_register_divider_table
  - drivers/clk/clk-divider.c:clk_hw_register_divider
  - drivers/clk/clk-divider.c:clk_register_divider
```
**Symbols:**

```
ffffffff81652ff0-ffffffff8165313a: _register_divider (STB_LOCAL)
ffffffff81653a1e-ffffffff81653a36: _register_divider.cold (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
struct clk_hw *_register_divider(struct device *dev, const char *name, const char *parent_name, long unsigned int flags, void *reg, u8 shift, u8 width, u8 clk_divider_flags, const struct clk_div_table *table, spinlock_t *lock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-divider.c (ffff8000107c3930)
Location: drivers/clk/clk-divider.c:466
Inline: False
Direct callers:
  - drivers/clk/clk-divider.c:clk_hw_register_divider_table
  - drivers/clk/clk-divider.c:clk_register_divider_table
  - drivers/clk/clk-divider.c:clk_hw_register_divider
  - drivers/clk/clk-divider.c:clk_register_divider
```
**Symbols:**

```
ffff8000107c3930-ffff8000107c3a84: _register_divider (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Collision, Selective Inline ⚠️</summary>

```c
struct clk_hw *_register_divider(struct device *dev, const char *name, const char *parent_name, long unsigned int flags, void *reg, u8 shift, u8 width, u8 clk_divider_flags, const struct clk_div_table *table, spinlock_t *lock);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-divider.c (c08ef120)
Location: drivers/clk/clk-divider.c:466
Inline: False
Direct callers:
  - drivers/clk/clk-divider.c:clk_hw_register_divider_table
  - drivers/clk/clk-divider.c:clk_register_divider_table
  - drivers/clk/clk-divider.c:clk_hw_register_divider
  - drivers/clk/clk-divider.c:clk_register_divider
```
```
In drivers/clk/ti/divider.c (c158b93c)
Location: drivers/clk/ti/divider.c:313
Inline: True
Inline callers:
  - drivers/clk/ti/divider.c:of_ti_divider_clk_setup
```
**Symbols:**

```
c08ef120-c08ef280: _register_divider (STB_LOCAL)
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
struct clk_hw *_register_divider(struct device *dev, const char *name, const char *parent_name, long unsigned int flags, void *reg, u8 shift, u8 width, u8 clk_divider_flags, const struct clk_div_table *table, spinlock_t *lock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-divider.c (ffffffe0005111f8)
Location: drivers/clk/clk-divider.c:466
Inline: False
Direct callers:
  - drivers/clk/clk-divider.c:clk_hw_register_divider_table
  - drivers/clk/clk-divider.c:clk_register_divider_table
  - drivers/clk/clk-divider.c:clk_hw_register_divider
  - drivers/clk/clk-divider.c:clk_register_divider
```
**Symbols:**

```
ffffffe0005111f8-ffffffe00051130c: _register_divider (STB_LOCAL)
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
struct clk_hw *_register_divider(struct device *dev, const char *name, const char *parent_name, long unsigned int flags, void *reg, u8 shift, u8 width, u8 clk_divider_flags, const struct clk_div_table *table, spinlock_t *lock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/clk/clk-divider.c (0)
Location: drivers/clk/clk-divider.c:466
Inline: False
Direct callers:
  - drivers/clk/clk-divider.c:clk_hw_register_divider_table
  - drivers/clk/clk-divider.c:clk_register_divider_table
  - drivers/clk/clk-divider.c:clk_hw_register_divider
  - drivers/clk/clk-divider.c:clk_register_divider
```
**Symbols:**

```
ffffffff81619050-ffffffff8161919a: _register_divider (STB_LOCAL)
ffffffff81619a7e-ffffffff81619a96: _register_divider.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
struct clk_hw *_register_divider(struct device *dev, const char *name, const char *parent_name, long unsigned int flags, void *reg, u8 shift, u8 width, u8 clk_divider_flags, const struct clk_div_table *table, spinlock_t *lock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/clk/clk-divider.c (0)
Location: drivers/clk/clk-divider.c:466
Inline: False
Direct callers:
  - drivers/clk/clk-divider.c:clk_hw_register_divider_table
  - drivers/clk/clk-divider.c:clk_register_divider_table
  - drivers/clk/clk-divider.c:clk_hw_register_divider
  - drivers/clk/clk-divider.c:clk_register_divider
```
**Symbols:**

```
ffffffff8160d580-ffffffff8160d6ca: _register_divider (STB_LOCAL)
ffffffff8160dfae-ffffffff8160dfc6: _register_divider.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
struct clk_hw *_register_divider(struct device *dev, const char *name, const char *parent_name, long unsigned int flags, void *reg, u8 shift, u8 width, u8 clk_divider_flags, const struct clk_div_table *table, spinlock_t *lock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/clk/clk-divider.c (0)
Location: drivers/clk/clk-divider.c:466
Inline: False
Direct callers:
  - drivers/clk/clk-divider.c:clk_hw_register_divider_table
  - drivers/clk/clk-divider.c:clk_register_divider_table
  - drivers/clk/clk-divider.c:clk_hw_register_divider
  - drivers/clk/clk-divider.c:clk_register_divider
```
**Symbols:**

```
ffffffff81646e30-ffffffff81646f7a: _register_divider (STB_LOCAL)
ffffffff8164785e-ffffffff81647876: _register_divider.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
struct clk_hw *_register_divider(struct device *dev, const char *name, const char *parent_name, long unsigned int flags, void *reg, u8 shift, u8 width, u8 clk_divider_flags, const struct clk_div_table *table, spinlock_t *lock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/clk/clk-divider.c (0)
Location: drivers/clk/clk-divider.c:466
Inline: False
Direct callers:
  - drivers/clk/clk-divider.c:clk_hw_register_divider_table
  - drivers/clk/clk-divider.c:clk_register_divider_table
  - drivers/clk/clk-divider.c:clk_hw_register_divider
  - drivers/clk/clk-divider.c:clk_register_divider
```
**Symbols:**

```
ffffffff816613c0-ffffffff8166150a: _register_divider (STB_LOCAL)
ffffffff81661dee-ffffffff81661e06: _register_divider.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>struct clk *</code> ➡️ <code>struct clk_hw *</code>
</li>
</ul>
</details>
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
