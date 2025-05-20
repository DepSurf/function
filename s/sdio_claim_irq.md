# Function: <code>sdio_claim_irq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int sdio_claim_irq(struct sdio_func *func, sdio_irq_handler_t *handler);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_irq.c (ffffffff816cc760)
Location: drivers/mmc/core/sdio_irq.c:259
Inline: False
```
**Symbols:**

```
ffffffff816cc760-ffffffff816cc998: sdio_claim_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int sdio_claim_irq(struct sdio_func *func, sdio_irq_handler_t *handler);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_irq.c (ffffffff8172f6a0)
Location: drivers/mmc/core/sdio_irq.c:259
Inline: False
```
**Symbols:**

```
ffffffff8172f6a0-ffffffff8172f8c5: sdio_claim_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int sdio_claim_irq(struct sdio_func *func, sdio_irq_handler_t *handler);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_irq.c (ffffffff81762690)
Location: drivers/mmc/core/sdio_irq.c:261
Inline: False
```
**Symbols:**

```
ffffffff81762690-ffffffff817628b5: sdio_claim_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int sdio_claim_irq(struct sdio_func *func, sdio_irq_handler_t *handler);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_irq.c (ffffffff81780e40)
Location: drivers/mmc/core/sdio_irq.c:282
Inline: True
```
**Symbols:**

```
ffffffff81780e40-ffffffff81781071: sdio_claim_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int sdio_claim_irq(struct sdio_func *func, sdio_irq_handler_t *handler);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_irq.c (ffffffff817f7410)
Location: drivers/mmc/core/sdio_irq.c:283
Inline: True
```
**Symbols:**

```
ffffffff817f7410-ffffffff817f7647: sdio_claim_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int sdio_claim_irq(struct sdio_func *func, sdio_irq_handler_t *handler);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_irq.c (ffffffff818408f0)
Location: drivers/mmc/core/sdio_irq.c:283
Inline: False
```
**Symbols:**

```
ffffffff818408f0-ffffffff81840b30: sdio_claim_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int sdio_claim_irq(struct sdio_func *func, sdio_irq_handler_t *handler);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_irq.c (ffffffff8186c8a0)
Location: drivers/mmc/core/sdio_irq.c:283
Inline: False
```
**Symbols:**

```
ffffffff8186c8a0-ffffffff8186cae0: sdio_claim_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int sdio_claim_irq(struct sdio_func *func, sdio_irq_handler_t *handler);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/sdio_irq.c (0)
Location: drivers/mmc/core/sdio_irq.c:282
Inline: False
```
**Symbols:**

```
ffffffff818b0b63-ffffffff818b0b76: sdio_claim_irq.cold (STB_LOCAL)
ffffffff818b0710-ffffffff818b093e: sdio_claim_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int sdio_claim_irq(struct sdio_func *func, sdio_irq_handler_t *handler);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_irq.c (ffffffff818e2bb0)
Location: drivers/mmc/core/sdio_irq.c:299
Inline: False
```
**Symbols:**

```
ffffffff818e2bb0-ffffffff818e2de5: sdio_claim_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int sdio_claim_irq(struct sdio_func *func, sdio_irq_handler_t *handler);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_irq.c (ffffffff819b5f30)
Location: drivers/mmc/core/sdio_irq.c:300
Inline: False
```
**Symbols:**

```
ffffffff819b5f30-ffffffff819b607b: sdio_claim_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int sdio_claim_irq(struct sdio_func *func, sdio_irq_handler_t *handler);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_irq.c (ffffffff819b84b0)
Location: drivers/mmc/core/sdio_irq.c:299
Inline: False
```
**Symbols:**

```
ffffffff819b84b0-ffffffff819b85fb: sdio_claim_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int sdio_claim_irq(struct sdio_func *func, sdio_irq_handler_t *handler);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_irq.c (ffffffff8199caf0)
Location: drivers/mmc/core/sdio_irq.c:299
Inline: False
```
**Symbols:**

```
ffffffff8199caf0-ffffffff8199cd25: sdio_claim_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int sdio_claim_irq(struct sdio_func *func, sdio_irq_handler_t *handler);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/sdio_irq.c (0)
Location: drivers/mmc/core/sdio_irq.c:299
Inline: False
```
**Symbols:**

```
ffffffff81d2e82d-ffffffff81d2e84b: sdio_claim_irq.cold (STB_LOCAL)
ffffffff81a494e0-ffffffff81a4971b: sdio_claim_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int sdio_claim_irq(struct sdio_func *func, sdio_irq_handler_t *handler);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/sdio_irq.c (0)
Location: drivers/mmc/core/sdio_irq.c:299
Inline: False
```
**Symbols:**

```
ffffffff81efac9e-ffffffff81efacbc: sdio_claim_irq.cold (STB_LOCAL)
ffffffff81bb77e0-ffffffff81bb7a28: sdio_claim_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int sdio_claim_irq(struct sdio_func *func, sdio_irq_handler_t *handler);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/sdio_irq.c (0)
Location: drivers/mmc/core/sdio_irq.c:299
Inline: False
```
**Symbols:**

```
ffffffff820a9ba4-ffffffff820a9bc2: sdio_claim_irq.cold (STB_LOCAL)
ffffffff81d5c3a0-ffffffff81d5c5e9: sdio_claim_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int sdio_claim_irq(struct sdio_func *func, sdio_irq_handler_t *handler);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/sdio_irq.c (0)
Location: drivers/mmc/core/sdio_irq.c:299
Inline: False
```
**Symbols:**

```
ffffffff8212af7d-ffffffff8212af9b: sdio_claim_irq.cold (STB_LOCAL)
ffffffff81dc6e10-ffffffff81dc704d: sdio_claim_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int sdio_claim_irq(struct sdio_func *func, sdio_irq_handler_t *handler);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/sdio_irq.c (0)
Location: drivers/mmc/core/sdio_irq.c:299
Inline: False
```
**Symbols:**

```
ffffffff8220cd3a-ffffffff8220cd58: sdio_claim_irq.cold (STB_LOCAL)
ffffffff81e7f750-ffffffff81e7f98d: sdio_claim_irq (STB_GLOBAL)
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
int sdio_claim_irq(struct sdio_func *func, sdio_irq_handler_t *handler);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_irq.c (ffff800010b3d468)
Location: drivers/mmc/core/sdio_irq.c:299
Inline: False
```
**Symbols:**

```
ffff800010b3d468-ffff800010b3d67c: sdio_claim_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int sdio_claim_irq(struct sdio_func *func, sdio_irq_handler_t *handler);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_irq.c (c0c17a58)
Location: drivers/mmc/core/sdio_irq.c:299
Inline: False
```
**Symbols:**

```
c0c17a58-c0c17c88: sdio_claim_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int sdio_claim_irq(struct sdio_func *func, sdio_irq_handler_t *handler);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_irq.c (c000000000c3a870)
Location: drivers/mmc/core/sdio_irq.c:299
Inline: False
```
**Symbols:**

```
c000000000c3a870-c000000000c3ab50: sdio_claim_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int sdio_claim_irq(struct sdio_func *func, sdio_irq_handler_t *handler);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_irq.c (ffffffe0007145fa)
Location: drivers/mmc/core/sdio_irq.c:299
Inline: False
```
**Symbols:**

```
ffffffe0007145fa-ffffffe0007147a2: sdio_claim_irq (STB_GLOBAL)
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
int sdio_claim_irq(struct sdio_func *func, sdio_irq_handler_t *handler);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_irq.c (ffffffff81886570)
Location: drivers/mmc/core/sdio_irq.c:299
Inline: False
```
**Symbols:**

```
ffffffff81886570-ffffffff818867a5: sdio_claim_irq (STB_GLOBAL)
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
int sdio_claim_irq(struct sdio_func *func, sdio_irq_handler_t *handler);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_irq.c (ffffffff818d7a10)
Location: drivers/mmc/core/sdio_irq.c:299
Inline: False
```
**Symbols:**

```
ffffffff818d7a10-ffffffff818d7c45: sdio_claim_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int sdio_claim_irq(struct sdio_func *func, sdio_irq_handler_t *handler);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio_irq.c (ffffffff818f4530)
Location: drivers/mmc/core/sdio_irq.c:299
Inline: False
```
**Symbols:**

```
ffffffff818f4530-ffffffff818f4765: sdio_claim_irq (STB_GLOBAL)
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
