# Function: <code>spi_new_device</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct spi_device *spi_new_device(struct spi_master *master, struct spi_board_info *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff815e8c80)
Location: drivers/spi/spi.c:570
Inline: False
```
**Symbols:**

```
ffffffff815e8c80-ffffffff815e8d58: spi_new_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct spi_device *spi_new_device(struct spi_master *master, struct spi_board_info *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff816471f0)
Location: drivers/spi/spi.c:573
Inline: False
```
**Symbols:**

```
ffffffff816471f0-ffffffff816472ba: spi_new_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct spi_device *spi_new_device(struct spi_master *master, struct spi_board_info *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff816782e0)
Location: drivers/spi/spi.c:574
Inline: False
```
**Symbols:**

```
ffffffff816782e0-ffffffff816783aa: spi_new_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct spi_device *spi_new_device(struct spi_controller *ctlr, struct spi_board_info *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff8168c9e0)
Location: drivers/spi/spi.c:575
Inline: False
```
**Symbols:**

```
ffffffff8168c9e0-ffffffff8168cae2: spi_new_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct spi_device *spi_new_device(struct spi_controller *ctlr, struct spi_board_info *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff816f6390)
Location: drivers/spi/spi.c:579
Inline: False
```
**Symbols:**

```
ffffffff816f6390-ffffffff816f6492: spi_new_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct spi_device *spi_new_device(struct spi_controller *ctlr, struct spi_board_info *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff81731790)
Location: drivers/spi/spi.c:583
Inline: False
```
**Symbols:**

```
ffffffff81731790-ffffffff81731881: spi_new_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct spi_device *spi_new_device(struct spi_controller *ctlr, struct spi_board_info *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff81754180)
Location: drivers/spi/spi.c:623
Inline: False
```
**Symbols:**

```
ffffffff81754180-ffffffff81754271: spi_new_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
struct spi_device *spi_new_device(struct spi_controller *ctlr, struct spi_board_info *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (0)
Location: drivers/spi/spi.c:629
Inline: False
```
**Symbols:**

```
ffffffff81792869-ffffffff81792895: spi_new_device.cold (STB_LOCAL)
ffffffff8178f930-ffffffff8178fa24: spi_new_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
struct spi_device *spi_new_device(struct spi_controller *ctlr, struct spi_board_info *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (0)
Location: drivers/spi/spi.c:630
Inline: False
```
**Symbols:**

```
ffffffff817b640b-ffffffff817b6424: spi_new_device.cold (STB_LOCAL)
ffffffff817b3510-ffffffff817b360b: spi_new_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
struct spi_device *spi_new_device(struct spi_controller *ctlr, struct spi_board_info *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (0)
Location: drivers/spi/spi.c:642
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_register_controller
  - drivers/spi/spi.c:spi_register_board_info
```
**Symbols:**

```
ffffffff8187d34c-ffffffff8187d365: spi_new_device.cold (STB_LOCAL)
ffffffff8187ad50-ffffffff8187ae4b: spi_new_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
struct spi_device *spi_new_device(struct spi_controller *ctlr, struct spi_board_info *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (0)
Location: drivers/spi/spi.c:651
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_register_controller
  - drivers/spi/spi.c:spi_register_board_info
```
**Symbols:**

```
ffffffff81c18dcc-ffffffff81c18dfd: spi_new_device.cold (STB_LOCAL)
ffffffff81889a40-ffffffff81889b78: spi_new_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
struct spi_device *spi_new_device(struct spi_controller *ctlr, struct spi_board_info *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (0)
Location: drivers/spi/spi.c:655
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_register_controller
  - drivers/spi/spi.c:spi_register_board_info
```
**Symbols:**

```
ffffffff81c0ab5d-ffffffff81c0ab8e: spi_new_device.cold (STB_LOCAL)
ffffffff8186c350-ffffffff8186c481: spi_new_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct spi_device *spi_new_device(struct spi_controller *ctlr, struct spi_board_info *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (0)
Location: drivers/spi/spi.c:714
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_register_controller
  - drivers/spi/spi.c:spi_register_board_info
```
**Symbols:**

```
ffffffff81d0fc97-ffffffff81d0fcc8: spi_new_device.cold (STB_LOCAL)
ffffffff818fc230-ffffffff818fc361: spi_new_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct spi_device *spi_new_device(struct spi_controller *ctlr, struct spi_board_info *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (0)
Location: drivers/spi/spi.c:682
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_register_controller
  - drivers/spi/spi.c:spi_register_board_info
```
**Symbols:**

```
ffffffff81eda9c2-ffffffff81eda9f3: spi_new_device.cold (STB_LOCAL)
ffffffff81a4d8e0-ffffffff81a4da1d: spi_new_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct spi_device *spi_new_device(struct spi_controller *ctlr, struct spi_board_info *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff81bd7dd0)
Location: drivers/spi/spi.c:744
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_register_controller
  - drivers/spi/spi.c:spi_register_board_info
```
**Symbols:**

```
ffffffff81bd7dd0-ffffffff81bd7f26: spi_new_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct spi_device *spi_new_device(struct spi_controller *ctlr, struct spi_board_info *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff81c2e800)
Location: drivers/spi/spi.c:745
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_register_controller
  - drivers/spi/spi.c:spi_register_board_info
```
**Symbols:**

```
ffffffff81c2e800-ffffffff81c2e956: spi_new_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct spi_device *spi_new_device(struct spi_controller *ctlr, struct spi_board_info *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff81ce1500)
Location: drivers/spi/spi.c:762
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_register_controller
  - drivers/spi/spi.c:spi_register_board_info
```
**Symbols:**

```
ffffffff81ce1500-ffffffff81ce16c8: spi_new_device (STB_GLOBAL)
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
struct spi_device *spi_new_device(struct spi_controller *ctlr, struct spi_board_info *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffff8000109c2b58)
Location: drivers/spi/spi.c:630
Inline: False
```
**Symbols:**

```
ffff8000109c2b58-ffff8000109c2c64: spi_new_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct spi_device *spi_new_device(struct spi_controller *ctlr, struct spi_board_info *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (c0aafd40)
Location: drivers/spi/spi.c:630
Inline: False
```
**Symbols:**

```
c0aafd40-c0aafe54: spi_new_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct spi_device *spi_new_device(struct spi_controller *ctlr, struct spi_board_info *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (c000000000a87830)
Location: drivers/spi/spi.c:630
Inline: False
```
**Symbols:**

```
c000000000a87830-c000000000a87998: spi_new_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct spi_device *spi_new_device(struct spi_controller *ctlr, struct spi_board_info *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffe000617902)
Location: drivers/spi/spi.c:630
Inline: False
```
**Symbols:**

```
ffffffe000617902-ffffffe0006179f8: spi_new_device (STB_GLOBAL)
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
struct spi_device *spi_new_device(struct spi_controller *ctlr, struct spi_board_info *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (0)
Location: drivers/spi/spi.c:630
Inline: False
```
**Symbols:**

```
ffffffff8177aeeb-ffffffff8177af04: spi_new_device.cold (STB_LOCAL)
ffffffff81777ff0-ffffffff817780eb: spi_new_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
struct spi_device *spi_new_device(struct spi_controller *ctlr, struct spi_board_info *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (0)
Location: drivers/spi/spi.c:630
Inline: False
```
**Symbols:**

```
ffffffff8175ac9b-ffffffff8175acb4: spi_new_device.cold (STB_LOCAL)
ffffffff81757da0-ffffffff81757e9b: spi_new_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
struct spi_device *spi_new_device(struct spi_controller *ctlr, struct spi_board_info *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (0)
Location: drivers/spi/spi.c:630
Inline: False
```
**Symbols:**

```
ffffffff817ab28b-ffffffff817ab2a4: spi_new_device.cold (STB_LOCAL)
ffffffff817a8390-ffffffff817a848b: spi_new_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
struct spi_device *spi_new_device(struct spi_controller *ctlr, struct spi_board_info *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (0)
Location: drivers/spi/spi.c:630
Inline: False
```
**Symbols:**

```
ffffffff817c521b-ffffffff817c5234: spi_new_device.cold (STB_LOCAL)
ffffffff817c2220-ffffffff817c231b: spi_new_device (STB_GLOBAL)
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
<b>Param added. </b>
<code>struct spi_controller *ctlr</code>
</li>
<li>
<b>Param removed. </b>
<code>struct spi_master *master</code>
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
