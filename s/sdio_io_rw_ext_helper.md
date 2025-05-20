# Function: <code>sdio_io_rw_ext_helper</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int sdio_io_rw_ext_helper(struct sdio_func *func, int write, unsigned int addr, int incr_addr, u8 *buf, unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_io.c (ffffffff816cbbd0)
Location: drivers/mmc/core/sdio_io.c:303
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_io.c:sdio_readw
  - drivers/mmc/core/sdio_io.c:sdio_readw
  - drivers/mmc/core/sdio_io.c:sdio_readl
  - drivers/mmc/core/sdio_io.c:sdio_readl
  - drivers/mmc/core/sdio_io.c:sdio_writew
  - drivers/mmc/core/sdio_io.c:sdio_writel
  - drivers/mmc/core/sdio_io.c:sdio_readsb
  - drivers/mmc/core/sdio_io.c:sdio_writesb
```
**Symbols:**

```
ffffffff816cbbd0-ffffffff816cbdc8: sdio_io_rw_ext_helper (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int sdio_io_rw_ext_helper(struct sdio_func *func, int write, unsigned int addr, int incr_addr, u8 *buf, unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_io.c (ffffffff8172eb40)
Location: drivers/mmc/core/sdio_io.c:303
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_io.c:sdio_writel
  - drivers/mmc/core/sdio_io.c:sdio_readl
  - drivers/mmc/core/sdio_io.c:sdio_readl
  - drivers/mmc/core/sdio_io.c:sdio_writew
  - drivers/mmc/core/sdio_io.c:sdio_readw
  - drivers/mmc/core/sdio_io.c:sdio_readw
  - drivers/mmc/core/sdio_io.c:sdio_writesb
  - drivers/mmc/core/sdio_io.c:sdio_readsb
```
**Symbols:**

```
ffffffff8172eb40-ffffffff8172ed1c: sdio_io_rw_ext_helper (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int sdio_io_rw_ext_helper(struct sdio_func *func, int write, unsigned int addr, int incr_addr, u8 *buf, unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_io.c (ffffffff81761d50)
Location: drivers/mmc/core/sdio_io.c:303
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_io.c:sdio_writel
  - drivers/mmc/core/sdio_io.c:sdio_readl
  - drivers/mmc/core/sdio_io.c:sdio_readl
  - drivers/mmc/core/sdio_io.c:sdio_writew
  - drivers/mmc/core/sdio_io.c:sdio_readw
  - drivers/mmc/core/sdio_io.c:sdio_readw
  - drivers/mmc/core/sdio_io.c:sdio_writesb
  - drivers/mmc/core/sdio_io.c:sdio_readsb
```
**Symbols:**

```
ffffffff81761d50-ffffffff81761f52: sdio_io_rw_ext_helper (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int sdio_io_rw_ext_helper(struct sdio_func *func, int write, unsigned int addr, int incr_addr, u8 *buf, unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_io.c (ffffffff817803c0)
Location: drivers/mmc/core/sdio_io.c:305
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_io.c:sdio_writel
  - drivers/mmc/core/sdio_io.c:sdio_readl
  - drivers/mmc/core/sdio_io.c:sdio_writew
  - drivers/mmc/core/sdio_io.c:sdio_readw
  - drivers/mmc/core/sdio_io.c:sdio_writesb
  - drivers/mmc/core/sdio_io.c:sdio_readsb
```
**Symbols:**

```
ffffffff817803c0-ffffffff817805b8: sdio_io_rw_ext_helper (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int sdio_io_rw_ext_helper(struct sdio_func *func, int write, unsigned int addr, int incr_addr, u8 *buf, unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_io.c (ffffffff817f6980)
Location: drivers/mmc/core/sdio_io.c:305
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_io.c:sdio_writel
  - drivers/mmc/core/sdio_io.c:sdio_readl
  - drivers/mmc/core/sdio_io.c:sdio_writew
  - drivers/mmc/core/sdio_io.c:sdio_readw
  - drivers/mmc/core/sdio_io.c:sdio_writesb
  - drivers/mmc/core/sdio_io.c:sdio_readsb
```
**Symbols:**

```
ffffffff817f6980-ffffffff817f6b78: sdio_io_rw_ext_helper (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int sdio_io_rw_ext_helper(struct sdio_func *func, int write, unsigned int addr, int incr_addr, u8 *buf, unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_io.c (ffffffff8183ffa0)
Location: drivers/mmc/core/sdio_io.c:305
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_io.c:sdio_writel
  - drivers/mmc/core/sdio_io.c:sdio_readl
  - drivers/mmc/core/sdio_io.c:sdio_writew
  - drivers/mmc/core/sdio_io.c:sdio_readw
  - drivers/mmc/core/sdio_io.c:sdio_writesb
  - drivers/mmc/core/sdio_io.c:sdio_readsb
```
**Symbols:**

```
ffffffff8183ffa0-ffffffff8184019c: sdio_io_rw_ext_helper (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int sdio_io_rw_ext_helper(struct sdio_func *func, int write, unsigned int addr, int incr_addr, u8 *buf, unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_io.c (ffffffff8186bf50)
Location: drivers/mmc/core/sdio_io.c:305
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_io.c:sdio_writel
  - drivers/mmc/core/sdio_io.c:sdio_readl
  - drivers/mmc/core/sdio_io.c:sdio_writew
  - drivers/mmc/core/sdio_io.c:sdio_readw
  - drivers/mmc/core/sdio_io.c:sdio_writesb
  - drivers/mmc/core/sdio_io.c:sdio_readsb
```
**Symbols:**

```
ffffffff8186bf50-ffffffff8186c14c: sdio_io_rw_ext_helper (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int sdio_io_rw_ext_helper(struct sdio_func *func, int write, unsigned int addr, int incr_addr, u8 *buf, unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_io.c (ffffffff818afd80)
Location: drivers/mmc/core/sdio_io.c:315
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_io.c:sdio_writel
  - drivers/mmc/core/sdio_io.c:sdio_readl
  - drivers/mmc/core/sdio_io.c:sdio_writew
  - drivers/mmc/core/sdio_io.c:sdio_readw
  - drivers/mmc/core/sdio_io.c:sdio_writesb
  - drivers/mmc/core/sdio_io.c:sdio_readsb
```
**Symbols:**

```
ffffffff818afd80-ffffffff818affba: sdio_io_rw_ext_helper (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int sdio_io_rw_ext_helper(struct sdio_func *func, int write, unsigned int addr, int incr_addr, u8 *buf, unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_io.c (ffffffff818e2230)
Location: drivers/mmc/core/sdio_io.c:315
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_io.c:sdio_writel
  - drivers/mmc/core/sdio_io.c:sdio_readl
  - drivers/mmc/core/sdio_io.c:sdio_writew
  - drivers/mmc/core/sdio_io.c:sdio_readw
  - drivers/mmc/core/sdio_io.c:sdio_writesb
  - drivers/mmc/core/sdio_io.c:sdio_readsb
```
**Symbols:**

```
ffffffff818e2230-ffffffff818e246a: sdio_io_rw_ext_helper (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int sdio_io_rw_ext_helper(struct sdio_func *func, int write, unsigned int addr, int incr_addr, u8 *buf, unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_io.c (ffffffff819b52e0)
Location: drivers/mmc/core/sdio_io.c:315
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_io.c:sdio_writel
  - drivers/mmc/core/sdio_io.c:sdio_readl
  - drivers/mmc/core/sdio_io.c:sdio_writew
  - drivers/mmc/core/sdio_io.c:sdio_readw
  - drivers/mmc/core/sdio_io.c:sdio_writesb
  - drivers/mmc/core/sdio_io.c:sdio_readsb
```
**Symbols:**

```
ffffffff819b52e0-ffffffff819b551a: sdio_io_rw_ext_helper (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int sdio_io_rw_ext_helper(struct sdio_func *func, int write, unsigned int addr, int incr_addr, u8 *buf, unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_io.c (ffffffff819b78a0)
Location: drivers/mmc/core/sdio_io.c:315
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_io.c:sdio_writel
  - drivers/mmc/core/sdio_io.c:sdio_readl
  - drivers/mmc/core/sdio_io.c:sdio_writew
  - drivers/mmc/core/sdio_io.c:sdio_readw
  - drivers/mmc/core/sdio_io.c:sdio_writesb
  - drivers/mmc/core/sdio_io.c:sdio_readsb
```
**Symbols:**

```
ffffffff819b78a0-ffffffff819b7ada: sdio_io_rw_ext_helper (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int sdio_io_rw_ext_helper(struct sdio_func *func, int write, unsigned int addr, int incr_addr, u8 *buf, unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_io.c (ffffffff8199c040)
Location: drivers/mmc/core/sdio_io.c:315
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_io.c:sdio_writel
  - drivers/mmc/core/sdio_io.c:sdio_readl
  - drivers/mmc/core/sdio_io.c:sdio_writew
  - drivers/mmc/core/sdio_io.c:sdio_readw
  - drivers/mmc/core/sdio_io.c:sdio_writesb
  - drivers/mmc/core/sdio_io.c:sdio_readsb
```
**Symbols:**

```
ffffffff8199c040-ffffffff8199c26b: sdio_io_rw_ext_helper (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int sdio_io_rw_ext_helper(struct sdio_func *func, int write, unsigned int addr, int incr_addr, u8 *buf, unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_io.c (ffffffff81a48a20)
Location: drivers/mmc/core/sdio_io.c:315
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_io.c:sdio_writel
  - drivers/mmc/core/sdio_io.c:sdio_readl
  - drivers/mmc/core/sdio_io.c:sdio_writew
  - drivers/mmc/core/sdio_io.c:sdio_readw
  - drivers/mmc/core/sdio_io.c:sdio_writesb
  - drivers/mmc/core/sdio_io.c:sdio_readsb
```
**Symbols:**

```
ffffffff81a48a20-ffffffff81a48c4b: sdio_io_rw_ext_helper (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int sdio_io_rw_ext_helper(struct sdio_func *func, int write, unsigned int addr, int incr_addr, u8 *buf, unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_io.c (ffffffff81bb6bc0)
Location: drivers/mmc/core/sdio_io.c:315
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_io.c:sdio_writel
  - drivers/mmc/core/sdio_io.c:sdio_readl
  - drivers/mmc/core/sdio_io.c:sdio_writew
  - drivers/mmc/core/sdio_io.c:sdio_readw
  - drivers/mmc/core/sdio_io.c:sdio_writesb
  - drivers/mmc/core/sdio_io.c:sdio_readsb
```
**Symbols:**

```
ffffffff81bb6bc0-ffffffff81bb6e15: sdio_io_rw_ext_helper (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int sdio_io_rw_ext_helper(struct sdio_func *func, int write, unsigned int addr, int incr_addr, u8 *buf, unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_io.c (ffffffff81d5b690)
Location: drivers/mmc/core/sdio_io.c:315
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_io.c:sdio_writel
  - drivers/mmc/core/sdio_io.c:sdio_readl
  - drivers/mmc/core/sdio_io.c:sdio_writew
  - drivers/mmc/core/sdio_io.c:sdio_readw
  - drivers/mmc/core/sdio_io.c:sdio_writesb
  - drivers/mmc/core/sdio_io.c:sdio_readsb
```
**Symbols:**

```
ffffffff81d5b690-ffffffff81d5b8e5: sdio_io_rw_ext_helper (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int sdio_io_rw_ext_helper(struct sdio_func *func, int write, unsigned int addr, int incr_addr, u8 *buf, unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_io.c (ffffffff81dc6110)
Location: drivers/mmc/core/sdio_io.c:315
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_io.c:sdio_writel
  - drivers/mmc/core/sdio_io.c:sdio_readl
  - drivers/mmc/core/sdio_io.c:sdio_writew
  - drivers/mmc/core/sdio_io.c:sdio_readw
  - drivers/mmc/core/sdio_io.c:sdio_writesb
  - drivers/mmc/core/sdio_io.c:sdio_readsb
```
**Symbols:**

```
ffffffff81dc6110-ffffffff81dc6365: sdio_io_rw_ext_helper (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int sdio_io_rw_ext_helper(struct sdio_func *func, int write, unsigned int addr, int incr_addr, u8 *buf, unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_io.c (ffffffff81e7ea50)
Location: drivers/mmc/core/sdio_io.c:315
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_io.c:sdio_writel
  - drivers/mmc/core/sdio_io.c:sdio_readl
  - drivers/mmc/core/sdio_io.c:sdio_writew
  - drivers/mmc/core/sdio_io.c:sdio_readw
  - drivers/mmc/core/sdio_io.c:sdio_writesb
  - drivers/mmc/core/sdio_io.c:sdio_readsb
```
**Symbols:**

```
ffffffff81e7ea50-ffffffff81e7eca5: sdio_io_rw_ext_helper (STB_LOCAL)
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
int sdio_io_rw_ext_helper(struct sdio_func *func, int write, unsigned int addr, int incr_addr, u8 *buf, unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_io.c (ffff800010b3c918)
Location: drivers/mmc/core/sdio_io.c:315
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_io.c:sdio_writel
  - drivers/mmc/core/sdio_io.c:sdio_readl
  - drivers/mmc/core/sdio_io.c:sdio_writew
  - drivers/mmc/core/sdio_io.c:sdio_readw
  - drivers/mmc/core/sdio_io.c:sdio_writesb
  - drivers/mmc/core/sdio_io.c:sdio_readsb
```
**Symbols:**

```
ffff800010b3c918-ffff800010b3cb44: sdio_io_rw_ext_helper (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int sdio_io_rw_ext_helper(struct sdio_func *func, int write, unsigned int addr, int incr_addr, u8 *buf, unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_io.c (c0c16fe0)
Location: drivers/mmc/core/sdio_io.c:315
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_io.c:sdio_writel
  - drivers/mmc/core/sdio_io.c:sdio_readl
  - drivers/mmc/core/sdio_io.c:sdio_writew
  - drivers/mmc/core/sdio_io.c:sdio_readw
  - drivers/mmc/core/sdio_io.c:sdio_writesb
  - drivers/mmc/core/sdio_io.c:sdio_readsb
```
**Symbols:**

```
c0c16fe0-c0c17200: sdio_io_rw_ext_helper (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int sdio_io_rw_ext_helper(struct sdio_func *func, int write, unsigned int addr, int incr_addr, u8 *buf, unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_io.c (c000000000c399e0)
Location: drivers/mmc/core/sdio_io.c:315
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_io.c:sdio_writel
  - drivers/mmc/core/sdio_io.c:sdio_readl
  - drivers/mmc/core/sdio_io.c:sdio_writew
  - drivers/mmc/core/sdio_io.c:sdio_readw
  - drivers/mmc/core/sdio_io.c:sdio_writesb
  - drivers/mmc/core/sdio_io.c:sdio_readsb
```
**Symbols:**

```
c000000000c399e0-c000000000c39d0c: sdio_io_rw_ext_helper (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int sdio_io_rw_ext_helper(struct sdio_func *func, int write, unsigned int addr, int incr_addr, u8 *buf, unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_io.c (ffffffe000713cb2)
Location: drivers/mmc/core/sdio_io.c:315
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_io.c:sdio_writel
  - drivers/mmc/core/sdio_io.c:sdio_readl
  - drivers/mmc/core/sdio_io.c:sdio_writew
  - drivers/mmc/core/sdio_io.c:sdio_readw
  - drivers/mmc/core/sdio_io.c:sdio_writesb
  - drivers/mmc/core/sdio_io.c:sdio_readsb
```
**Symbols:**

```
ffffffe000713cb2-ffffffe000713e92: sdio_io_rw_ext_helper (STB_LOCAL)
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
int sdio_io_rw_ext_helper(struct sdio_func *func, int write, unsigned int addr, int incr_addr, u8 *buf, unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_io.c (ffffffff81885bf0)
Location: drivers/mmc/core/sdio_io.c:315
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_io.c:sdio_writel
  - drivers/mmc/core/sdio_io.c:sdio_readl
  - drivers/mmc/core/sdio_io.c:sdio_writew
  - drivers/mmc/core/sdio_io.c:sdio_readw
  - drivers/mmc/core/sdio_io.c:sdio_writesb
  - drivers/mmc/core/sdio_io.c:sdio_readsb
```
**Symbols:**

```
ffffffff81885bf0-ffffffff81885e2a: sdio_io_rw_ext_helper (STB_LOCAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int sdio_io_rw_ext_helper(struct sdio_func *func, int write, unsigned int addr, int incr_addr, u8 *buf, unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_io.c (ffffffff818d7090)
Location: drivers/mmc/core/sdio_io.c:315
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_io.c:sdio_writel
  - drivers/mmc/core/sdio_io.c:sdio_readl
  - drivers/mmc/core/sdio_io.c:sdio_writew
  - drivers/mmc/core/sdio_io.c:sdio_readw
  - drivers/mmc/core/sdio_io.c:sdio_writesb
  - drivers/mmc/core/sdio_io.c:sdio_readsb
```
**Symbols:**

```
ffffffff818d7090-ffffffff818d72ca: sdio_io_rw_ext_helper (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int sdio_io_rw_ext_helper(struct sdio_func *func, int write, unsigned int addr, int incr_addr, u8 *buf, unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_io.c (ffffffff818f3bb0)
Location: drivers/mmc/core/sdio_io.c:315
Inline: False
Direct callers:
  - drivers/mmc/core/sdio_io.c:sdio_writel
  - drivers/mmc/core/sdio_io.c:sdio_readl
  - drivers/mmc/core/sdio_io.c:sdio_writew
  - drivers/mmc/core/sdio_io.c:sdio_readw
  - drivers/mmc/core/sdio_io.c:sdio_writesb
  - drivers/mmc/core/sdio_io.c:sdio_readsb
```
**Symbols:**

```
ffffffff818f3bb0-ffffffff818f3dea: sdio_io_rw_ext_helper (STB_LOCAL)
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
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
