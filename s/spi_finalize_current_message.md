# Function: <code>spi_finalize_current_message</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void spi_finalize_current_message(struct spi_master *master);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff815e7170)
Location: drivers/spi/spi.c:1244
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:__spi_pump_messages
```
**Symbols:**

```
ffffffff815e7170-ffffffff815e73b0: spi_finalize_current_message (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void spi_finalize_current_message(struct spi_master *master);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff81645aa0)
Location: drivers/spi/spi.c:1300
Inline: False
Direct callers:
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:spi_transfer_one_message
```
**Symbols:**

```
ffffffff81645aa0-ffffffff81645cd9: spi_finalize_current_message (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void spi_finalize_current_message(struct spi_master *master);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff816768a0)
Location: drivers/spi/spi.c:1325
Inline: False
Direct callers:
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:spi_transfer_one_message
```
**Symbols:**

```
ffffffff816768a0-ffffffff81676ad9: spi_finalize_current_message (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void spi_finalize_current_message(struct spi_controller *ctlr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff8168afa0)
Location: drivers/spi/spi.c:1350
Inline: False
Direct callers:
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:spi_transfer_one_message
```
**Symbols:**

```
ffffffff8168afa0-ffffffff8168b1cc: spi_finalize_current_message (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void spi_finalize_current_message(struct spi_controller *ctlr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff816f4910)
Location: drivers/spi/spi.c:1354
Inline: False
Direct callers:
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:spi_transfer_one_message
```
**Symbols:**

```
ffffffff816f4910-ffffffff816f4b48: spi_finalize_current_message (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void spi_finalize_current_message(struct spi_controller *ctlr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff817329d0)
Location: drivers/spi/spi.c:1352
Inline: False
Direct callers:
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:spi_transfer_one_message
```
**Symbols:**

```
ffffffff817329d0-ffffffff81732c19: spi_finalize_current_message (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void spi_finalize_current_message(struct spi_controller *ctlr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff817553f0)
Location: drivers/spi/spi.c:1412
Inline: False
Direct callers:
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:spi_transfer_one_message
```
**Symbols:**

```
ffffffff817553f0-ffffffff81755639: spi_finalize_current_message (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void spi_finalize_current_message(struct spi_controller *ctlr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (0)
Location: drivers/spi/spi.c:1503
Inline: False
Direct callers:
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:spi_transfer_one_message
```
**Symbols:**

```
ffffffff81792a49-ffffffff81792a5f: spi_finalize_current_message.cold (STB_LOCAL)
ffffffff817914f0-ffffffff81791728: spi_finalize_current_message (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void spi_finalize_current_message(struct spi_controller *ctlr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (0)
Location: drivers/spi/spi.c:1505
Inline: False
Direct callers:
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:spi_transfer_one_message
```
**Symbols:**

```
ffffffff817b65ab-ffffffff817b65c1: spi_finalize_current_message.cold (STB_LOCAL)
ffffffff817b50f0-ffffffff817b5328: spi_finalize_current_message (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void spi_finalize_current_message(struct spi_controller *ctlr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (0)
Location: drivers/spi/spi.c:1671
Inline: False
Direct callers:
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:spi_transfer_one_message
```
**Symbols:**

```
ffffffff8187d481-ffffffff8187d497: spi_finalize_current_message.cold (STB_LOCAL)
ffffffff8187bf80-ffffffff8187c27b: spi_finalize_current_message (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void spi_finalize_current_message(struct spi_controller *ctlr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (0)
Location: drivers/spi/spi.c:1713
Inline: False
Direct callers:
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:spi_transfer_one_message
```
**Symbols:**

```
ffffffff81c18cb8-ffffffff81c18cce: spi_finalize_current_message.cold (STB_LOCAL)
ffffffff81888f50-ffffffff81889183: spi_finalize_current_message (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void spi_finalize_current_message(struct spi_controller *ctlr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (0)
Location: drivers/spi/spi.c:1725
Inline: False
Direct callers:
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:spi_transfer_one_message
```
**Symbols:**

```
ffffffff81c0a9b1-ffffffff81c0a9c7: spi_finalize_current_message.cold (STB_LOCAL)
ffffffff8186aa30-ffffffff8186ac63: spi_finalize_current_message (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void spi_finalize_current_message(struct spi_controller *ctlr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (0)
Location: drivers/spi/spi.c:1804
Inline: False
Direct callers:
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:spi_transfer_one_message
```
**Symbols:**

```
ffffffff81d0fa33-ffffffff81d0fac9: spi_finalize_current_message.cold (STB_LOCAL)
ffffffff818fae70-ffffffff818fb0c1: spi_finalize_current_message (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void spi_finalize_current_message(struct spi_controller *ctlr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (0)
Location: drivers/spi/spi.c:1846
Inline: False
Direct callers:
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:spi_transfer_one_message
```
**Symbols:**

```
ffffffff81eda7be-ffffffff81eda846: spi_finalize_current_message.cold (STB_LOCAL)
ffffffff81a4cb00-ffffffff81a4cde3: spi_finalize_current_message (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void spi_finalize_current_message(struct spi_controller *ctlr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (0)
Location: drivers/spi/spi.c:2009
Inline: False
Direct callers:
  - drivers/spi/spi.c:__spi_pump_transfer_message
  - drivers/spi/spi.c:spi_transfer_one_message
```
**Symbols:**

```
ffffffff8209d0c0-ffffffff8209d13e: spi_finalize_current_message.cold (STB_LOCAL)
ffffffff81bd4d70-ffffffff81bd5046: spi_finalize_current_message (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void spi_finalize_current_message(struct spi_controller *ctlr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (0)
Location: drivers/spi/spi.c:2016
Inline: False
Direct callers:
  - drivers/spi/spi.c:__spi_pump_transfer_message
  - drivers/spi/spi.c:spi_transfer_one_message
```
**Symbols:**

```
ffffffff8211df7b-ffffffff8211dfe4: spi_finalize_current_message.cold (STB_LOCAL)
ffffffff81c2bbf0-ffffffff81c2beb4: spi_finalize_current_message (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void spi_finalize_current_message(struct spi_controller *ctlr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (0)
Location: drivers/spi/spi.c:2093
Inline: False
Direct callers:
  - drivers/spi/spi.c:__spi_pump_transfer_message
  - drivers/spi/spi.c:spi_transfer_one_message
```
**Symbols:**

```
ffffffff821ff519-ffffffff821ff582: spi_finalize_current_message.cold (STB_LOCAL)
ffffffff81cde510-ffffffff81cde7d4: spi_finalize_current_message (STB_GLOBAL)
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
void spi_finalize_current_message(struct spi_controller *ctlr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffff8000109c8818)
Location: drivers/spi/spi.c:1505
Inline: False
Direct callers:
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/spi/spi-fsl-spi.c:fsl_spi_do_one_msg
```
**Symbols:**

```
ffff8000109c8818-ffff8000109c8b18: spi_finalize_current_message (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void spi_finalize_current_message(struct spi_controller *ctlr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (c0ab2450)
Location: drivers/spi/spi.c:1505
Inline: False
Direct callers:
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/spi/spi-fsl-spi.c:fsl_spi_do_one_msg
```
**Symbols:**

```
c0ab2450-c0ab2684: spi_finalize_current_message (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void spi_finalize_current_message(struct spi_controller *ctlr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (c000000000a8a220)
Location: drivers/spi/spi.c:1505
Inline: False
Direct callers:
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/spi/spi-fsl-spi.c:fsl_spi_do_one_msg
```
**Symbols:**

```
c000000000a8a220-c000000000a8a514: spi_finalize_current_message (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void spi_finalize_current_message(struct spi_controller *ctlr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffe000618c5c)
Location: drivers/spi/spi.c:1505
Inline: False
Direct callers:
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:spi_transfer_one_message
  - drivers/spi/spi-fsl-spi.c:fsl_spi_do_one_msg
```
**Symbols:**

```
ffffffe000618c5c-ffffffe000618e32: spi_finalize_current_message (STB_GLOBAL)
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
void spi_finalize_current_message(struct spi_controller *ctlr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (0)
Location: drivers/spi/spi.c:1505
Inline: False
Direct callers:
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:spi_transfer_one_message
```
**Symbols:**

```
ffffffff8177b08b-ffffffff8177b0a1: spi_finalize_current_message.cold (STB_LOCAL)
ffffffff81779bd0-ffffffff81779e08: spi_finalize_current_message (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void spi_finalize_current_message(struct spi_controller *ctlr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (0)
Location: drivers/spi/spi.c:1505
Inline: False
Direct callers:
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:spi_transfer_one_message
```
**Symbols:**

```
ffffffff8175ae3b-ffffffff8175ae51: spi_finalize_current_message.cold (STB_LOCAL)
ffffffff81759980-ffffffff81759bb8: spi_finalize_current_message (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void spi_finalize_current_message(struct spi_controller *ctlr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (0)
Location: drivers/spi/spi.c:1505
Inline: False
Direct callers:
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:spi_transfer_one_message
```
**Symbols:**

```
ffffffff817ab42b-ffffffff817ab441: spi_finalize_current_message.cold (STB_LOCAL)
ffffffff817a9f70-ffffffff817aa1a8: spi_finalize_current_message (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void spi_finalize_current_message(struct spi_controller *ctlr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (0)
Location: drivers/spi/spi.c:1505
Inline: False
Direct callers:
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:__spi_pump_messages
  - drivers/spi/spi.c:spi_transfer_one_message
```
**Symbols:**

```
ffffffff817c53bb-ffffffff817c53d1: spi_finalize_current_message.cold (STB_LOCAL)
ffffffff817c3e00-ffffffff817c404d: spi_finalize_current_message (STB_GLOBAL)
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
