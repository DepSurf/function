# Function: <code>clk_register_mux_table</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct clk *clk_register_mux_table(struct device *dev, const char *name, const const char * *parent_names, u8 num_parents, long unsigned int flags, void *reg, u8 shift, u32 mask, u8 clk_mux_flags, u32 *table, spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-mux.c (ffffffff816ea2c0)
Location: drivers/clk/clk-mux.c:119
Inline: False
Direct callers:
  - drivers/clk/clk-mux.c:clk_register_mux
```
**Symbols:**

```
ffffffff816ea2c0-ffffffff816ea440: clk_register_mux_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct clk *clk_register_mux_table(struct device *dev, const char *name, const const char * *parent_names, u8 num_parents, long unsigned int flags, void *reg, u8 shift, u32 mask, u8 clk_mux_flags, u32 *table, spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-mux.c (ffffffff8174ec51)
Location: drivers/clk/clk-mux.c:172
Inline: True
Inline callers:
  - drivers/clk/clk-mux.c:clk_register_mux
```
**Symbols:**

```
ffffffff8174ebf0-ffffffff8174ec3b: clk_register_mux_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct clk *clk_register_mux_table(struct device *dev, const char *name, const const char * *parent_names, u8 num_parents, long unsigned int flags, void *reg, u8 shift, u32 mask, u8 clk_mux_flags, u32 *table, spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-mux.c (ffffffff815374c1)
Location: drivers/clk/clk-mux.c:172
Inline: True
Inline callers:
  - drivers/clk/clk-mux.c:clk_register_mux
```
**Symbols:**

```
ffffffff81537460-ffffffff815374ab: clk_register_mux_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct clk *clk_register_mux_table(struct device *dev, const char *name, const const char * *parent_names, u8 num_parents, long unsigned int flags, void *reg, u8 shift, u32 mask, u8 clk_mux_flags, u32 *table, spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-mux.c (ffffffff8154a7d5)
Location: drivers/clk/clk-mux.c:172
Inline: True
Inline callers:
  - drivers/clk/clk-mux.c:clk_register_mux
```
**Symbols:**

```
ffffffff8154a780-ffffffff8154a7b7: clk_register_mux_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct clk *clk_register_mux_table(struct device *dev, const char *name, const const char * *parent_names, u8 num_parents, long unsigned int flags, void *reg, u8 shift, u32 mask, u8 clk_mux_flags, u32 *table, spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-mux.c (ffffffff815add45)
Location: drivers/clk/clk-mux.c:170
Inline: True
Inline callers:
  - drivers/clk/clk-mux.c:clk_register_mux
```
**Symbols:**

```
ffffffff815adcf0-ffffffff815add27: clk_register_mux_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct clk *clk_register_mux_table(struct device *dev, const char *name, const const char * *parent_names, u8 num_parents, long unsigned int flags, void *reg, u8 shift, u32 mask, u8 clk_mux_flags, u32 *table, spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-mux.c (ffffffff815e5f75)
Location: drivers/clk/clk-mux.c:189
Inline: True
Inline callers:
  - drivers/clk/clk-mux.c:clk_register_mux
```
**Symbols:**

```
ffffffff815e5f30-ffffffff815e5f67: clk_register_mux_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct clk *clk_register_mux_table(struct device *dev, const char *name, const const char * *parent_names, u8 num_parents, long unsigned int flags, void *reg, u8 shift, u32 mask, u8 clk_mux_flags, u32 *table, spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-mux.c (ffffffff81600305)
Location: drivers/clk/clk-mux.c:186
Inline: True
Inline callers:
  - drivers/clk/clk-mux.c:clk_register_mux
```
**Symbols:**

```
ffffffff816002c0-ffffffff816002f7: clk_register_mux_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct clk *clk_register_mux_table(struct device *dev, const char *name, const const char * *parent_names, u8 num_parents, long unsigned int flags, void *reg, u8 shift, u32 mask, u8 clk_mux_flags, u32 *table, spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-mux.c (ffffffff81632bc5)
Location: drivers/clk/clk-mux.c:202
Inline: True
Inline callers:
  - drivers/clk/clk-mux.c:clk_register_mux
```
**Symbols:**

```
ffffffff81632b80-ffffffff81632bb7: clk_register_mux_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct clk *clk_register_mux_table(struct device *dev, const char *name, const const char * *parent_names, u8 num_parents, long unsigned int flags, void *reg, u8 shift, u32 mask, u8 clk_mux_flags, u32 *table, spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-mux.c (ffffffff816548f5)
Location: drivers/clk/clk-mux.c:202
Inline: True
Inline callers:
  - drivers/clk/clk-mux.c:clk_register_mux
```
**Symbols:**

```
ffffffff816548b0-ffffffff816548e7: clk_register_mux_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct clk *clk_register_mux_table(struct device *dev, const char *name, const const char * *parent_names, u8 num_parents, long unsigned int flags, void *reg, u8 shift, u32 mask, u8 clk_mux_flags, u32 *table, spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-mux.c (ffffffff817046a0)
Location: drivers/clk/clk-mux.c:209
Inline: False
```
**Symbols:**

```
ffffffff817046a0-ffffffff817046e8: clk_register_mux_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct clk *clk_register_mux_table(struct device *dev, const char *name, const const char * *parent_names, u8 num_parents, long unsigned int flags, void *reg, u8 shift, u32 mask, u8 clk_mux_flags, u32 *table, spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-mux.c (ffffffff817218e0)
Location: drivers/clk/clk-mux.c:209
Inline: False
```
**Symbols:**

```
ffffffff817218e0-ffffffff81721928: clk_register_mux_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct clk *clk_register_mux_table(struct device *dev, const char *name, const const char * *parent_names, u8 num_parents, long unsigned int flags, void *reg, u8 shift, u32 mask, u8 clk_mux_flags, u32 *table, spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-mux.c (ffffffff81702c10)
Location: drivers/clk/clk-mux.c:244
Inline: False
```
**Symbols:**

```
ffffffff81702c10-ffffffff81702c58: clk_register_mux_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct clk *clk_register_mux_table(struct device *dev, const char *name, const const char * *parent_names, u8 num_parents, long unsigned int flags, void *reg, u8 shift, u32 mask, u8 clk_mux_flags, u32 *table, spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-mux.c (ffffffff8177d8a0)
Location: drivers/clk/clk-mux.c:244
Inline: False
```
**Symbols:**

```
ffffffff8177d8a0-ffffffff8177d8e8: clk_register_mux_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct clk *clk_register_mux_table(struct device *dev, const char *name, const const char * *parent_names, u8 num_parents, long unsigned int flags, void *reg, u8 shift, u32 mask, u8 clk_mux_flags, const u32 *table, spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-mux.c (ffffffff818b44f0)
Location: drivers/clk/clk-mux.c:244
Inline: False
```
**Symbols:**

```
ffffffff818b44f0-ffffffff818b454a: clk_register_mux_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct clk *clk_register_mux_table(struct device *dev, const char *name, const const char * *parent_names, u8 num_parents, long unsigned int flags, void *reg, u8 shift, u32 mask, u8 clk_mux_flags, const u32 *table, spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-mux.c (ffffffff81a010b0)
Location: drivers/clk/clk-mux.c:244
Inline: False
```
**Symbols:**

```
ffffffff81a010b0-ffffffff81a0110a: clk_register_mux_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct clk *clk_register_mux_table(struct device *dev, const char *name, const const char * *parent_names, u8 num_parents, long unsigned int flags, void *reg, u8 shift, u32 mask, u8 clk_mux_flags, const u32 *table, spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-mux.c (ffffffff81a49db0)
Location: drivers/clk/clk-mux.c:244
Inline: False
```
**Symbols:**

```
ffffffff81a49db0-ffffffff81a49e0a: clk_register_mux_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct clk *clk_register_mux_table(struct device *dev, const char *name, const const char * *parent_names, u8 num_parents, long unsigned int flags, void *reg, u8 shift, u32 mask, u8 clk_mux_flags, const u32 *table, spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-mux.c (ffffffff81a95900)
Location: drivers/clk/clk-mux.c:244
Inline: False
```
**Symbols:**

```
ffffffff81a95900-ffffffff81a9595a: clk_register_mux_table (STB_GLOBAL)
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
struct clk *clk_register_mux_table(struct device *dev, const char *name, const const char * *parent_names, u8 num_parents, long unsigned int flags, void *reg, u8 shift, u32 mask, u8 clk_mux_flags, u32 *table, spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-mux.c (ffff8000107c608c)
Location: drivers/clk/clk-mux.c:202
Inline: True
Inline callers:
  - drivers/clk/clk-mux.c:clk_register_mux
Direct callers:
  - drivers/clk/hisilicon/clk.c:hisi_clk_register_mux
```
**Symbols:**

```
ffff8000107c5f90-ffff8000107c6040: clk_register_mux_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct clk *clk_register_mux_table(struct device *dev, const char *name, const const char * *parent_names, u8 num_parents, long unsigned int flags, void *reg, u8 shift, u32 mask, u8 clk_mux_flags, u32 *table, spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-mux.c (c08f14a0)
Location: drivers/clk/clk-mux.c:202
Inline: True
Inline callers:
  - drivers/clk/clk-mux.c:clk_register_mux
Direct callers:
  - drivers/clk/hisilicon/clk.c:hisi_clk_register_mux
```
**Symbols:**

```
c08f1428-c08f1488: clk_register_mux_table (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct clk *clk_register_mux_table(struct device *dev, const char *name, const const char * *parent_names, u8 num_parents, long unsigned int flags, void *reg, u8 shift, u32 mask, u8 clk_mux_flags, u32 *table, spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-mux.c (ffffffe000513646)
Location: drivers/clk/clk-mux.c:202
Inline: True
Inline callers:
  - drivers/clk/clk-mux.c:clk_register_mux
```
**Symbols:**

```
ffffffe00051359c-ffffffe000513614: clk_register_mux_table (STB_GLOBAL)
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
struct clk *clk_register_mux_table(struct device *dev, const char *name, const const char * *parent_names, u8 num_parents, long unsigned int flags, void *reg, u8 shift, u32 mask, u8 clk_mux_flags, u32 *table, spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-mux.c (ffffffff8161a955)
Location: drivers/clk/clk-mux.c:202
Inline: True
Inline callers:
  - drivers/clk/clk-mux.c:clk_register_mux
```
**Symbols:**

```
ffffffff8161a910-ffffffff8161a947: clk_register_mux_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct clk *clk_register_mux_table(struct device *dev, const char *name, const const char * *parent_names, u8 num_parents, long unsigned int flags, void *reg, u8 shift, u32 mask, u8 clk_mux_flags, u32 *table, spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-mux.c (ffffffff8160ee85)
Location: drivers/clk/clk-mux.c:202
Inline: True
Inline callers:
  - drivers/clk/clk-mux.c:clk_register_mux
```
**Symbols:**

```
ffffffff8160ee40-ffffffff8160ee77: clk_register_mux_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct clk *clk_register_mux_table(struct device *dev, const char *name, const const char * *parent_names, u8 num_parents, long unsigned int flags, void *reg, u8 shift, u32 mask, u8 clk_mux_flags, u32 *table, spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-mux.c (ffffffff81648735)
Location: drivers/clk/clk-mux.c:202
Inline: True
Inline callers:
  - drivers/clk/clk-mux.c:clk_register_mux
```
**Symbols:**

```
ffffffff816486f0-ffffffff81648727: clk_register_mux_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct clk *clk_register_mux_table(struct device *dev, const char *name, const const char * *parent_names, u8 num_parents, long unsigned int flags, void *reg, u8 shift, u32 mask, u8 clk_mux_flags, u32 *table, spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-mux.c (ffffffff81662cc5)
Location: drivers/clk/clk-mux.c:202
Inline: True
Inline callers:
  - drivers/clk/clk-mux.c:clk_register_mux
```
**Symbols:**

```
ffffffff81662c80-ffffffff81662cb7: clk_register_mux_table (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>u32 *table</code> ➡️ <code>const u32 *table</code>
</li>
</ul>
</details>
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
