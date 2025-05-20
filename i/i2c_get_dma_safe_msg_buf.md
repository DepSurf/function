# Function: <code>i2c_get_dma_safe_msg_buf</code>

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
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
u8 *i2c_get_dma_safe_msg_buf(struct i2c_msg *msg, unsigned int threshold);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff817d4730)
Location: drivers/i2c/i2c-core-base.c:2265
Inline: True
```
**Symbols:**

```
ffffffff817d4730-ffffffff817d47aa: i2c_get_dma_safe_msg_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
u8 *i2c_get_dma_safe_msg_buf(struct i2c_msg *msg, unsigned int threshold);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff817fb860)
Location: drivers/i2c/i2c-core-base.c:2266
Inline: False
```
**Symbols:**

```
ffffffff817fb860-ffffffff817fb909: i2c_get_dma_safe_msg_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
u8 *i2c_get_dma_safe_msg_buf(struct i2c_msg *msg, unsigned int threshold);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff8183bf10)
Location: drivers/i2c/i2c-core-base.c:2359
Inline: False
```
**Symbols:**

```
ffffffff8183bf10-ffffffff8183bfb1: i2c_get_dma_safe_msg_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
u8 *i2c_get_dma_safe_msg_buf(struct i2c_msg *msg, unsigned int threshold);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff8186d8b0)
Location: drivers/i2c/i2c-core-base.c:2364
Inline: False
```
**Symbols:**

```
ffffffff8186d8b0-ffffffff8186d951: i2c_get_dma_safe_msg_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
u8 *i2c_get_dma_safe_msg_buf(struct i2c_msg *msg, unsigned int threshold);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff81940c80)
Location: drivers/i2c/i2c-core-base.c:2293
Inline: False
```
**Symbols:**

```
ffffffff81940c80-ffffffff81940d2c: i2c_get_dma_safe_msg_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
u8 *i2c_get_dma_safe_msg_buf(struct i2c_msg *msg, unsigned int threshold);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff81947050)
Location: drivers/i2c/i2c-core-base.c:2423
Inline: False
```
**Symbols:**

```
ffffffff81947050-ffffffff819470fc: i2c_get_dma_safe_msg_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
u8 *i2c_get_dma_safe_msg_buf(struct i2c_msg *msg, unsigned int threshold);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff8192a960)
Location: drivers/i2c/i2c-core-base.c:2483
Inline: False
```
**Symbols:**

```
ffffffff8192a960-ffffffff8192aa0c: i2c_get_dma_safe_msg_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
u8 *i2c_get_dma_safe_msg_buf(struct i2c_msg *msg, unsigned int threshold);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff819cdb10)
Location: drivers/i2c/i2c-core-base.c:2484
Inline: False
```
**Symbols:**

```
ffffffff819cdb10-ffffffff819cdbb6: i2c_get_dma_safe_msg_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
u8 *i2c_get_dma_safe_msg_buf(struct i2c_msg *msg, unsigned int threshold);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff81b2fbd0)
Location: drivers/i2c/i2c-core-base.c:2488
Inline: False
```
**Symbols:**

```
ffffffff81b2fbd0-ffffffff81b2fcb3: i2c_get_dma_safe_msg_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
u8 *i2c_get_dma_safe_msg_buf(struct i2c_msg *msg, unsigned int threshold);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff81cc4150)
Location: drivers/i2c/i2c-core-base.c:2496
Inline: False
```
**Symbols:**

```
ffffffff81cc4150-ffffffff81cc422a: i2c_get_dma_safe_msg_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
u8 *i2c_get_dma_safe_msg_buf(struct i2c_msg *msg, unsigned int threshold);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff81d2bbc0)
Location: drivers/i2c/i2c-core-base.c:2609
Inline: False
```
**Symbols:**

```
ffffffff81d2bbc0-ffffffff81d2bca1: i2c_get_dma_safe_msg_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
u8 *i2c_get_dma_safe_msg_buf(struct i2c_msg *msg, unsigned int threshold);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff81de1a80)
Location: drivers/i2c/i2c-core-base.c:2627
Inline: False
```
**Symbols:**

```
ffffffff81de1a80-ffffffff81de1b61: i2c_get_dma_safe_msg_buf (STB_GLOBAL)
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
u8 *i2c_get_dma_safe_msg_buf(struct i2c_msg *msg, unsigned int threshold);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffff800010ab0168)
Location: drivers/i2c/i2c-core-base.c:2364
Inline: False
```
**Symbols:**

```
ffff800010ab0168-ffff800010ab0250: i2c_get_dma_safe_msg_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
u8 *i2c_get_dma_safe_msg_buf(struct i2c_msg *msg, unsigned int threshold);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (c0b92b44)
Location: drivers/i2c/i2c-core-base.c:2364
Inline: True
```
**Symbols:**

```
c0b92b44-c0b92c2c: i2c_get_dma_safe_msg_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
u8 *i2c_get_dma_safe_msg_buf(struct i2c_msg *msg, unsigned int threshold);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (c000000000b94950)
Location: drivers/i2c/i2c-core-base.c:2364
Inline: False
```
**Symbols:**

```
c000000000b94950-c000000000b94a78: i2c_get_dma_safe_msg_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
u8 *i2c_get_dma_safe_msg_buf(struct i2c_msg *msg, unsigned int threshold);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffe0006b9492)
Location: drivers/i2c/i2c-core-base.c:2364
Inline: True
```
**Symbols:**

```
ffffffe0006b9492-ffffffe0006b958a: i2c_get_dma_safe_msg_buf (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
u8 *i2c_get_dma_safe_msg_buf(struct i2c_msg *msg, unsigned int threshold);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff81861a40)
Location: drivers/i2c/i2c-core-base.c:2364
Inline: False
Direct callers:
  - drivers/i2c/busses/i2c-amd-mp2-plat.c:i2c_amd_xfer
```
**Symbols:**

```
ffffffff81861a40-ffffffff81861ae1: i2c_get_dma_safe_msg_buf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
u8 *i2c_get_dma_safe_msg_buf(struct i2c_msg *msg, unsigned int threshold);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff8187cc50)
Location: drivers/i2c/i2c-core-base.c:2364
Inline: False
```
**Symbols:**

```
ffffffff8187cc50-ffffffff8187ccf1: i2c_get_dma_safe_msg_buf (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
