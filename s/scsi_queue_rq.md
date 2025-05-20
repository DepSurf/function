# Function: <code>scsi_queue_rq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int scsi_queue_rq(struct blk_mq_hw_ctx *hctx, const struct blk_mq_queue_data *bd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff815af780)
Location: drivers/scsi/scsi_lib.c:1963
Inline: False
```
**Symbols:**

```
ffffffff815af780-ffffffff815aff08: scsi_queue_rq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int scsi_queue_rq(struct blk_mq_hw_ctx *hctx, const struct blk_mq_queue_data *bd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81607990)
Location: drivers/scsi/scsi_lib.c:1879
Inline: False
```
**Symbols:**

```
ffffffff81607990-ffffffff81608122: scsi_queue_rq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int scsi_queue_rq(struct blk_mq_hw_ctx *hctx, const struct blk_mq_queue_data *bd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff816372a0)
Location: drivers/scsi/scsi_lib.c:1889
Inline: False
```
**Symbols:**

```
ffffffff816372a0-ffffffff81637a27: scsi_queue_rq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
blk_status_t scsi_queue_rq(struct blk_mq_hw_ctx *hctx, const struct blk_mq_queue_data *bd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff8164ce00)
Location: drivers/scsi/scsi_lib.c:1913
Inline: False
```
**Symbols:**

```
ffffffff8164ce00-ffffffff8164d477: scsi_queue_rq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
blk_status_t scsi_queue_rq(struct blk_mq_hw_ctx *hctx, const struct blk_mq_queue_data *bd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff816b61b0)
Location: drivers/scsi/scsi_lib.c:1994
Inline: False
```
**Symbols:**

```
ffffffff816b61b0-ffffffff816b674e: scsi_queue_rq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
blk_status_t scsi_queue_rq(struct blk_mq_hw_ctx *hctx, const struct blk_mq_queue_data *bd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff816f2460)
Location: drivers/scsi/scsi_lib.c:2030
Inline: False
```
**Symbols:**

```
ffffffff816f2460-ffffffff816f2a08: scsi_queue_rq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
blk_status_t scsi_queue_rq(struct blk_mq_hw_ctx *hctx, const struct blk_mq_queue_data *bd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81714fe0)
Location: drivers/scsi/scsi_lib.c:1689
Inline: False
```
**Symbols:**

```
ffffffff81714fe0-ffffffff817159bb: scsi_queue_rq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
blk_status_t scsi_queue_rq(struct blk_mq_hw_ctx *hctx, const struct blk_mq_queue_data *bd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_lib.c (0)
Location: drivers/scsi/scsi_lib.c:1632
Inline: False
```
**Symbols:**

```
ffffffff817507c0-ffffffff81751169: scsi_queue_rq (STB_LOCAL)
ffffffff817515d8-ffffffff81751612: scsi_queue_rq.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
blk_status_t scsi_queue_rq(struct blk_mq_hw_ctx *hctx, const struct blk_mq_queue_data *bd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_lib.c (0)
Location: drivers/scsi/scsi_lib.c:1644
Inline: False
```
**Symbols:**

```
ffffffff817749e0-ffffffff817753e0: scsi_queue_rq (STB_LOCAL)
ffffffff81775849-ffffffff81775893: scsi_queue_rq.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
blk_status_t scsi_queue_rq(struct blk_mq_hw_ctx *hctx, const struct blk_mq_queue_data *bd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_lib.c (0)
Location: drivers/scsi/scsi_lib.c:1627
Inline: False
```
**Symbols:**

```
ffffffff81837db0-ffffffff81838306: scsi_queue_rq (STB_LOCAL)
ffffffff81838784-ffffffff818387ab: scsi_queue_rq.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
blk_status_t scsi_queue_rq(struct blk_mq_hw_ctx *hctx, const struct blk_mq_queue_data *bd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_lib.c (0)
Location: drivers/scsi/scsi_lib.c:1644
Inline: False
```
**Symbols:**

```
ffffffff81848730-ffffffff81848c37: scsi_queue_rq (STB_LOCAL)
ffffffff81c1692d-ffffffff81c16954: scsi_queue_rq.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
blk_status_t scsi_queue_rq(struct blk_mq_hw_ctx *hctx, const struct blk_mq_queue_data *bd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_lib.c (0)
Location: drivers/scsi/scsi_lib.c:1637
Inline: False
```
**Symbols:**

```
ffffffff8182ba50-ffffffff8182c064: scsi_queue_rq (STB_LOCAL)
ffffffff81c08608-ffffffff81c0862f: scsi_queue_rq.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
blk_status_t scsi_queue_rq(struct blk_mq_hw_ctx *hctx, const struct blk_mq_queue_data *bd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_lib.c (0)
Location: drivers/scsi/scsi_lib.c:1639
Inline: False
```
**Symbols:**

```
ffffffff818b75e0-ffffffff818b7c61: scsi_queue_rq (STB_LOCAL)
ffffffff81d0c5fc-ffffffff81d0c6e5: scsi_queue_rq.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
blk_status_t scsi_queue_rq(struct blk_mq_hw_ctx *hctx, const struct blk_mq_queue_data *bd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_lib.c (0)
Location: drivers/scsi/scsi_lib.c:1697
Inline: False
```
**Symbols:**

```
ffffffff81a02cd0-ffffffff81a032eb: scsi_queue_rq (STB_LOCAL)
ffffffff81ed5540-ffffffff81ed5605: scsi_queue_rq.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
blk_status_t scsi_queue_rq(struct blk_mq_hw_ctx *hctx, const struct blk_mq_queue_data *bd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_lib.c (0)
Location: drivers/scsi/scsi_lib.c:1704
Inline: False
```
**Symbols:**

```
ffffffff81b816d0-ffffffff81b81d45: scsi_queue_rq (STB_LOCAL)
ffffffff8209bb6b-ffffffff8209bc09: scsi_queue_rq.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
blk_status_t scsi_queue_rq(struct blk_mq_hw_ctx *hctx, const struct blk_mq_queue_data *bd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_lib.c (0)
Location: drivers/scsi/scsi_lib.c:1709
Inline: False
```
**Symbols:**

```
ffffffff81bd53d0-ffffffff81bd5a43: scsi_queue_rq (STB_LOCAL)
ffffffff8211ca02-ffffffff8211caa0: scsi_queue_rq.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
blk_status_t scsi_queue_rq(struct blk_mq_hw_ctx *hctx, const struct blk_mq_queue_data *bd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_lib.c (0)
Location: drivers/scsi/scsi_lib.c:1706
Inline: False
```
**Symbols:**

```
ffffffff81c2a030-ffffffff81c2a693: scsi_queue_rq (STB_LOCAL)
ffffffff821fa8b2-ffffffff821fa950: scsi_queue_rq.cold (STB_LOCAL)
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
blk_status_t scsi_queue_rq(struct blk_mq_hw_ctx *hctx, const struct blk_mq_queue_data *bd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffff800010978a98)
Location: drivers/scsi/scsi_lib.c:1644
Inline: False
```
**Symbols:**

```
ffff800010978a98-ffff8000109795ec: scsi_queue_rq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
blk_status_t scsi_queue_rq(struct blk_mq_hw_ctx *hctx, const struct blk_mq_queue_data *bd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (c0a4c940)
Location: drivers/scsi/scsi_lib.c:1644
Inline: False
```
**Symbols:**

```
c0a4c940-c0a4d3b0: scsi_queue_rq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
blk_status_t scsi_queue_rq(struct blk_mq_hw_ctx *hctx, const struct blk_mq_queue_data *bd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (c000000000a33180)
Location: drivers/scsi/scsi_lib.c:1644
Inline: False
```
**Symbols:**

```
c000000000a33180-c000000000a33ea8: scsi_queue_rq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
blk_status_t scsi_queue_rq(struct blk_mq_hw_ctx *hctx, const struct blk_mq_queue_data *bd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffe0005e03d2)
Location: drivers/scsi/scsi_lib.c:1644
Inline: False
```
**Symbols:**

```
ffffffe0005e03d2-ffffffe0005e0cf2: scsi_queue_rq (STB_LOCAL)
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
blk_status_t scsi_queue_rq(struct blk_mq_hw_ctx *hctx, const struct blk_mq_queue_data *bd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_lib.c (0)
Location: drivers/scsi/scsi_lib.c:1644
Inline: False
```
**Symbols:**

```
ffffffff817290d0-ffffffff81729ad0: scsi_queue_rq (STB_LOCAL)
ffffffff81729f39-ffffffff81729f83: scsi_queue_rq.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
blk_status_t scsi_queue_rq(struct blk_mq_hw_ctx *hctx, const struct blk_mq_queue_data *bd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_lib.c (0)
Location: drivers/scsi/scsi_lib.c:1644
Inline: False
```
**Symbols:**

```
ffffffff81702500-ffffffff81702ee2: scsi_queue_rq (STB_LOCAL)
ffffffff81703359-ffffffff817033a3: scsi_queue_rq.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
blk_status_t scsi_queue_rq(struct blk_mq_hw_ctx *hctx, const struct blk_mq_queue_data *bd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_lib.c (0)
Location: drivers/scsi/scsi_lib.c:1644
Inline: False
```
**Symbols:**

```
ffffffff81767ea0-ffffffff817688a0: scsi_queue_rq (STB_LOCAL)
ffffffff81768d09-ffffffff81768d53: scsi_queue_rq.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
blk_status_t scsi_queue_rq(struct blk_mq_hw_ctx *hctx, const struct blk_mq_queue_data *bd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_lib.c (0)
Location: drivers/scsi/scsi_lib.c:1644
Inline: False
```
**Symbols:**

```
ffffffff817835e0-ffffffff81784018: scsi_queue_rq (STB_LOCAL)
ffffffff81784489-ffffffff817844c9: scsi_queue_rq.cold (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>blk_status_t</code>
</li>
</ul>
</details>
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
