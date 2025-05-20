# Function: <code>mmc_put_card</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void mmc_put_card(struct mmc_card *card);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff816be010)
Location: drivers/mmc/core/core.c:1022
Inline: False
Direct callers:
  - drivers/mmc/core/debugfs.c:mmc_ext_csd_open
  - drivers/mmc/core/debugfs.c:mmc_dbg_card_status_get
```
**Symbols:**

```
ffffffff816be010-ffffffff816be044: mmc_put_card (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void mmc_put_card(struct mmc_card *card);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff8171fc20)
Location: drivers/mmc/core/core.c:1023
Inline: False
Direct callers:
  - drivers/mmc/core/debugfs.c:mmc_ext_csd_open
  - drivers/mmc/core/debugfs.c:mmc_dbg_card_status_get
```
**Symbols:**

```
ffffffff8171fc20-ffffffff8171fc54: mmc_put_card (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void mmc_put_card(struct mmc_card *card);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff817524a0)
Location: drivers/mmc/core/core.c:1095
Inline: False
Direct callers:
  - drivers/mmc/core/debugfs.c:mmc_ext_csd_open
  - drivers/mmc/core/debugfs.c:mmc_dbg_card_status_get
```
**Symbols:**

```
ffffffff817524a0-ffffffff817524d4: mmc_put_card (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void mmc_put_card(struct mmc_card *card);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81770cb0)
Location: drivers/mmc/core/core.c:927
Inline: False
Direct callers:
  - drivers/mmc/core/debugfs.c:mmc_ext_csd_open
  - drivers/mmc/core/debugfs.c:mmc_dbg_card_status_get
```
**Symbols:**

```
ffffffff81770cb0-ffffffff81770ce4: mmc_put_card (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void mmc_put_card(struct mmc_card *card, struct mmc_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff817e6a00)
Location: drivers/mmc/core/core.c:1111
Inline: False
```
**Symbols:**

```
ffffffff817e6a00-ffffffff817e6a44: mmc_put_card (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void mmc_put_card(struct mmc_card *card, struct mmc_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff8182fd50)
Location: drivers/mmc/core/core.c:910
Inline: False
```
**Symbols:**

```
ffffffff8182fd50-ffffffff8182fd94: mmc_put_card (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void mmc_put_card(struct mmc_card *card, struct mmc_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff8185bfd0)
Location: drivers/mmc/core/core.c:913
Inline: False
```
**Symbols:**

```
ffffffff8185bfd0-ffffffff8185c012: mmc_put_card (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void mmc_put_card(struct mmc_card *card, struct mmc_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/core.c (0)
Location: drivers/mmc/core/core.c:884
Inline: False
```
**Symbols:**

```
ffffffff818a3cfd-ffffffff818a3d10: mmc_put_card.cold (STB_LOCAL)
ffffffff8189fe90-ffffffff8189fedc: mmc_put_card (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void mmc_put_card(struct mmc_card *card, struct mmc_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff818d2400)
Location: drivers/mmc/core/core.c:884
Inline: False
```
**Symbols:**

```
ffffffff818d2400-ffffffff818d2442: mmc_put_card (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void mmc_put_card(struct mmc_card *card, struct mmc_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff819a4b40)
Location: drivers/mmc/core/core.c:867
Inline: False
```
**Symbols:**

```
ffffffff819a4b40-ffffffff819a4b85: mmc_put_card (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void mmc_put_card(struct mmc_card *card, struct mmc_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff819a7be0)
Location: drivers/mmc/core/core.c:867
Inline: False
```
**Symbols:**

```
ffffffff819a7be0-ffffffff819a7c25: mmc_put_card (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void mmc_put_card(struct mmc_card *card, struct mmc_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff8198c8e0)
Location: drivers/mmc/core/core.c:868
Inline: False
```
**Symbols:**

```
ffffffff8198c8e0-ffffffff8198c925: mmc_put_card (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void mmc_put_card(struct mmc_card *card, struct mmc_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81a37f40)
Location: drivers/mmc/core/core.c:868
Inline: False
```
**Symbols:**

```
ffffffff81a37f40-ffffffff81a37f85: mmc_put_card (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void mmc_put_card(struct mmc_card *card, struct mmc_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81ba4b30)
Location: drivers/mmc/core/core.c:868
Inline: False
```
**Symbols:**

```
ffffffff81ba4b30-ffffffff81ba4b7f: mmc_put_card (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void mmc_put_card(struct mmc_card *card, struct mmc_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81d46d80)
Location: drivers/mmc/core/core.c:867
Inline: False
```
**Symbols:**

```
ffffffff81d46d80-ffffffff81d46dcf: mmc_put_card (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void mmc_put_card(struct mmc_card *card, struct mmc_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81db1570)
Location: drivers/mmc/core/core.c:867
Inline: False
```
**Symbols:**

```
ffffffff81db1570-ffffffff81db15bf: mmc_put_card (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void mmc_put_card(struct mmc_card *card, struct mmc_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81e69900)
Location: drivers/mmc/core/core.c:872
Inline: False
```
**Symbols:**

```
ffffffff81e69900-ffffffff81e6994f: mmc_put_card (STB_GLOBAL)
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
void mmc_put_card(struct mmc_card *card, struct mmc_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffff800010b2d938)
Location: drivers/mmc/core/core.c:884
Inline: False
Direct callers:
  - drivers/mmc/core/block.c:mmc_blk_mq_post_req
  - drivers/mmc/core/block.c:mmc_blk_cqe_complete_rq
  - drivers/mmc/core/queue.c:mmc_mq_queue_rq
  - drivers/mmc/core/queue.c:mmc_mq_recovery_handler
```
**Symbols:**

```
ffff800010b2d938-ffff800010b2d990: mmc_put_card (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void mmc_put_card(struct mmc_card *card, struct mmc_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (c0c06d2c)
Location: drivers/mmc/core/core.c:884
Inline: False
Direct callers:
  - drivers/mmc/core/block.c:mmc_blk_mq_post_req
  - drivers/mmc/core/block.c:mmc_blk_cqe_complete_rq
  - drivers/mmc/core/queue.c:mmc_mq_queue_rq
  - drivers/mmc/core/queue.c:mmc_mq_recovery_handler
```
**Symbols:**

```
c0c06d2c-c0c06da0: mmc_put_card (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void mmc_put_card(struct mmc_card *card, struct mmc_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (c000000000c23f90)
Location: drivers/mmc/core/core.c:884
Inline: False
```
**Symbols:**

```
c000000000c23f90-c000000000c24008: mmc_put_card (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void mmc_put_card(struct mmc_card *card, struct mmc_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffe000705784)
Location: drivers/mmc/core/core.c:884
Inline: False
Direct callers:
  - drivers/mmc/core/block.c:mmc_blk_mq_post_req
  - drivers/mmc/core/block.c:mmc_blk_cqe_complete_rq
  - drivers/mmc/core/queue.c:mmc_mq_queue_rq
  - drivers/mmc/core/queue.c:mmc_mq_recovery_handler
```
**Symbols:**

```
ffffffe000705784-ffffffe0007057dc: mmc_put_card (STB_GLOBAL)
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
void mmc_put_card(struct mmc_card *card, struct mmc_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81875dc0)
Location: drivers/mmc/core/core.c:884
Inline: False
```
**Symbols:**

```
ffffffff81875dc0-ffffffff81875e02: mmc_put_card (STB_GLOBAL)
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
void mmc_put_card(struct mmc_card *card, struct mmc_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff818c7260)
Location: drivers/mmc/core/core.c:884
Inline: False
```
**Symbols:**

```
ffffffff818c7260-ffffffff818c72a2: mmc_put_card (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void mmc_put_card(struct mmc_card *card, struct mmc_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff818e3d10)
Location: drivers/mmc/core/core.c:884
Inline: False
```
**Symbols:**

```
ffffffff818e3d10-ffffffff818e3d52: mmc_put_card (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct mmc_ctx *ctx</code>
</li>
</ul>
</details>
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
