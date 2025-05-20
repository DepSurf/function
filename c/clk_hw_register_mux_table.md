# Function: <code>clk_hw_register_mux_table</code>

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
struct clk_hw *clk_hw_register_mux_table(struct device *dev, const char *name, const const char * *parent_names, u8 num_parents, long unsigned int flags, void *reg, u8 shift, u32 mask, u8 clk_mux_flags, u32 *table, spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-mux.c (ffffffff8174ea30)
Location: drivers/clk/clk-mux.c:116
Inline: False
Direct callers:
  - drivers/clk/clk-mux.c:clk_hw_register_mux
  - drivers/clk/clk-mux.c:clk_register_mux
```
**Symbols:**

```
ffffffff8174ea30-ffffffff8174eb9e: clk_hw_register_mux_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct clk_hw *clk_hw_register_mux_table(struct device *dev, const char *name, const const char * *parent_names, u8 num_parents, long unsigned int flags, void *reg, u8 shift, u32 mask, u8 clk_mux_flags, u32 *table, spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-mux.c (ffffffff815372a0)
Location: drivers/clk/clk-mux.c:116
Inline: False
Direct callers:
  - drivers/clk/clk-mux.c:clk_hw_register_mux
  - drivers/clk/clk-mux.c:clk_register_mux
```
**Symbols:**

```
ffffffff815372a0-ffffffff8153740e: clk_hw_register_mux_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct clk_hw *clk_hw_register_mux_table(struct device *dev, const char *name, const const char * *parent_names, u8 num_parents, long unsigned int flags, void *reg, u8 shift, u32 mask, u8 clk_mux_flags, u32 *table, spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-mux.c (ffffffff8154a5d0)
Location: drivers/clk/clk-mux.c:116
Inline: False
Direct callers:
  - drivers/clk/clk-mux.c:clk_hw_register_mux
  - drivers/clk/clk-mux.c:clk_register_mux
```
**Symbols:**

```
ffffffff8154a5d0-ffffffff8154a73f: clk_hw_register_mux_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct clk_hw *clk_hw_register_mux_table(struct device *dev, const char *name, const const char * *parent_names, u8 num_parents, long unsigned int flags, void *reg, u8 shift, u32 mask, u8 clk_mux_flags, u32 *table, spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-mux.c (ffffffff815adb50)
Location: drivers/clk/clk-mux.c:116
Inline: False
Direct callers:
  - drivers/clk/clk-mux.c:clk_hw_register_mux
  - drivers/clk/clk-mux.c:clk_register_mux
```
**Symbols:**

```
ffffffff815adb50-ffffffff815adcad: clk_hw_register_mux_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
struct clk_hw *clk_hw_register_mux_table(struct device *dev, const char *name, const const char * *parent_names, u8 num_parents, long unsigned int flags, void *reg, u8 shift, u32 mask, u8 clk_mux_flags, u32 *table, spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/clk/clk-mux.c (0)
Location: drivers/clk/clk-mux.c:135
Inline: False
Direct callers:
  - drivers/clk/clk-mux.c:clk_hw_register_mux
  - drivers/clk/clk-mux.c:clk_register_mux
```
**Symbols:**

```
ffffffff815e5fb6-ffffffff815e5fce: clk_hw_register_mux_table.cold.1 (STB_LOCAL)
ffffffff815e5da0-ffffffff815e5ee6: clk_hw_register_mux_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
struct clk_hw *clk_hw_register_mux_table(struct device *dev, const char *name, const const char * *parent_names, u8 num_parents, long unsigned int flags, void *reg, u8 shift, u32 mask, u8 clk_mux_flags, u32 *table, spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/clk/clk-mux.c (0)
Location: drivers/clk/clk-mux.c:132
Inline: False
Direct callers:
  - drivers/clk/clk-mux.c:clk_hw_register_mux
  - drivers/clk/clk-mux.c:clk_register_mux
```
**Symbols:**

```
ffffffff816003ad-ffffffff816003c5: clk_hw_register_mux_table.cold.0 (STB_LOCAL)
ffffffff81600130-ffffffff81600276: clk_hw_register_mux_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
struct clk_hw *clk_hw_register_mux_table(struct device *dev, const char *name, const const char * *parent_names, u8 num_parents, long unsigned int flags, void *reg, u8 shift, u32 mask, u8 clk_mux_flags, u32 *table, spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/clk/clk-mux.c (0)
Location: drivers/clk/clk-mux.c:148
Inline: False
Direct callers:
  - drivers/clk/clk-mux.c:clk_hw_register_mux
  - drivers/clk/clk-mux.c:clk_register_mux
```
**Symbols:**

```
ffffffff81632c6f-ffffffff81632c87: clk_hw_register_mux_table.cold (STB_LOCAL)
ffffffff816329e0-ffffffff81632b33: clk_hw_register_mux_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
struct clk_hw *clk_hw_register_mux_table(struct device *dev, const char *name, const const char * *parent_names, u8 num_parents, long unsigned int flags, void *reg, u8 shift, u32 mask, u8 clk_mux_flags, u32 *table, spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/clk/clk-mux.c (0)
Location: drivers/clk/clk-mux.c:148
Inline: False
Direct callers:
  - drivers/clk/clk-mux.c:clk_hw_register_mux
  - drivers/clk/clk-mux.c:clk_register_mux
```
**Symbols:**

```
ffffffff8165499f-ffffffff816549b7: clk_hw_register_mux_table.cold (STB_LOCAL)
ffffffff81654710-ffffffff81654863: clk_hw_register_mux_table (STB_GLOBAL)
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
struct clk_hw *clk_hw_register_mux_table(struct device *dev, const char *name, const const char * *parent_names, u8 num_parents, long unsigned int flags, void *reg, u8 shift, u32 mask, u8 clk_mux_flags, u32 *table, spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-mux.c (ffff8000107c5e18)
Location: drivers/clk/clk-mux.c:148
Inline: False
Direct callers:
  - drivers/clk/clk-mux.c:clk_hw_register_mux
  - drivers/clk/clk-mux.c:clk_register_mux
```
**Symbols:**

```
ffff8000107c5e18-ffff8000107c5f90: clk_hw_register_mux_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct clk_hw *clk_hw_register_mux_table(struct device *dev, const char *name, const const char * *parent_names, u8 num_parents, long unsigned int flags, void *reg, u8 shift, u32 mask, u8 clk_mux_flags, u32 *table, spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-mux.c (c08f1254)
Location: drivers/clk/clk-mux.c:148
Inline: False
Direct callers:
  - drivers/clk/clk-mux.c:clk_hw_register_mux
  - drivers/clk/clk-mux.c:clk_register_mux
  - drivers/clk/clk-npcm7xx.c:npcm7xx_clk_init
  - drivers/net/ethernet/ti/cpts.c:cpts_create
```
**Symbols:**

```
c08f1254-c08f13c4: clk_hw_register_mux_table (STB_GLOBAL)
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
struct clk_hw *clk_hw_register_mux_table(struct device *dev, const char *name, const const char * *parent_names, u8 num_parents, long unsigned int flags, void *reg, u8 shift, u32 mask, u8 clk_mux_flags, u32 *table, spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-mux.c (ffffffe00051337c)
Location: drivers/clk/clk-mux.c:148
Inline: False
Direct callers:
  - drivers/clk/clk-mux.c:clk_hw_register_mux
  - drivers/clk/clk-mux.c:clk_register_mux
```
**Symbols:**

```
ffffffe00051337c-ffffffe000513528: clk_hw_register_mux_table (STB_GLOBAL)
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
struct clk_hw *clk_hw_register_mux_table(struct device *dev, const char *name, const const char * *parent_names, u8 num_parents, long unsigned int flags, void *reg, u8 shift, u32 mask, u8 clk_mux_flags, u32 *table, spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/clk/clk-mux.c (0)
Location: drivers/clk/clk-mux.c:148
Inline: False
Direct callers:
  - drivers/clk/clk-mux.c:clk_hw_register_mux
  - drivers/clk/clk-mux.c:clk_register_mux
```
**Symbols:**

```
ffffffff8161a9ff-ffffffff8161aa17: clk_hw_register_mux_table.cold (STB_LOCAL)
ffffffff8161a770-ffffffff8161a8c3: clk_hw_register_mux_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
struct clk_hw *clk_hw_register_mux_table(struct device *dev, const char *name, const const char * *parent_names, u8 num_parents, long unsigned int flags, void *reg, u8 shift, u32 mask, u8 clk_mux_flags, u32 *table, spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/clk/clk-mux.c (0)
Location: drivers/clk/clk-mux.c:148
Inline: False
Direct callers:
  - drivers/clk/clk-mux.c:clk_hw_register_mux
  - drivers/clk/clk-mux.c:clk_register_mux
```
**Symbols:**

```
ffffffff8160ef2f-ffffffff8160ef47: clk_hw_register_mux_table.cold (STB_LOCAL)
ffffffff8160eca0-ffffffff8160edf3: clk_hw_register_mux_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
struct clk_hw *clk_hw_register_mux_table(struct device *dev, const char *name, const const char * *parent_names, u8 num_parents, long unsigned int flags, void *reg, u8 shift, u32 mask, u8 clk_mux_flags, u32 *table, spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/clk/clk-mux.c (0)
Location: drivers/clk/clk-mux.c:148
Inline: False
Direct callers:
  - drivers/clk/clk-mux.c:clk_hw_register_mux
  - drivers/clk/clk-mux.c:clk_register_mux
```
**Symbols:**

```
ffffffff816487df-ffffffff816487f7: clk_hw_register_mux_table.cold (STB_LOCAL)
ffffffff81648550-ffffffff816486a3: clk_hw_register_mux_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
struct clk_hw *clk_hw_register_mux_table(struct device *dev, const char *name, const const char * *parent_names, u8 num_parents, long unsigned int flags, void *reg, u8 shift, u32 mask, u8 clk_mux_flags, u32 *table, spinlock_t *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/clk/clk-mux.c (0)
Location: drivers/clk/clk-mux.c:148
Inline: False
Direct callers:
  - drivers/clk/clk-mux.c:clk_hw_register_mux
  - drivers/clk/clk-mux.c:clk_register_mux
```
**Symbols:**

```
ffffffff81662d6f-ffffffff81662d87: clk_hw_register_mux_table.cold (STB_LOCAL)
ffffffff81662ae0-ffffffff81662c33: clk_hw_register_mux_table (STB_GLOBAL)
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
