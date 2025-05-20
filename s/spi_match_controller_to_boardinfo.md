# Function: <code>spi_match_controller_to_boardinfo</code>

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
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void spi_match_controller_to_boardinfo(struct spi_controller *ctlr, struct spi_board_info *bi);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff8168caf0)
Location: drivers/spi/spi.c:650
Inline: True
Direct callers:
  - drivers/spi/spi.c:spi_register_controller
  - drivers/spi/spi.c:spi_register_board_info
```
**Symbols:**

```
ffffffff8168caf0-ffffffff8168cb36: spi_match_controller_to_boardinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void spi_match_controller_to_boardinfo(struct spi_controller *ctlr, struct spi_board_info *bi);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff816f64a0)
Location: drivers/spi/spi.c:654
Inline: True
Direct callers:
  - drivers/spi/spi.c:spi_register_controller
  - drivers/spi/spi.c:spi_register_board_info
```
**Symbols:**

```
ffffffff816f64a0-ffffffff816f64e6: spi_match_controller_to_boardinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void spi_match_controller_to_boardinfo(struct spi_controller *ctlr, struct spi_board_info *bi);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff81731890)
Location: drivers/spi/spi.c:658
Inline: True
Direct callers:
  - drivers/spi/spi.c:spi_register_controller
  - drivers/spi/spi.c:spi_register_board_info
```
**Symbols:**

```
ffffffff81731890-ffffffff817318d5: spi_match_controller_to_boardinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void spi_match_controller_to_boardinfo(struct spi_controller *ctlr, struct spi_board_info *bi);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff81754280)
Location: drivers/spi/spi.c:698
Inline: True
Direct callers:
  - drivers/spi/spi.c:spi_register_controller
  - drivers/spi/spi.c:spi_register_board_info
```
**Symbols:**

```
ffffffff81754280-ffffffff817542c5: spi_match_controller_to_boardinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void spi_match_controller_to_boardinfo(struct spi_controller *ctlr, struct spi_board_info *bi);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (ffffffff81792895)
Location: drivers/spi/spi.c:704
Inline: True
Direct callers:
  - drivers/spi/spi.c:spi_register_controller
  - drivers/spi/spi.c:spi_register_board_info
```
**Symbols:**

```
ffffffff8178fa30-ffffffff8178fa65: spi_match_controller_to_boardinfo (STB_LOCAL)
ffffffff81792895-ffffffff817928ad: spi_match_controller_to_boardinfo.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void spi_match_controller_to_boardinfo(struct spi_controller *ctlr, struct spi_board_info *bi);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (ffffffff817b6424)
Location: drivers/spi/spi.c:705
Inline: True
Direct callers:
  - drivers/spi/spi.c:spi_register_controller
  - drivers/spi/spi.c:spi_register_board_info
```
**Symbols:**

```
ffffffff817b3610-ffffffff817b3645: spi_match_controller_to_boardinfo (STB_LOCAL)
ffffffff817b6424-ffffffff817b643c: spi_match_controller_to_boardinfo.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff8187b107)
Location: drivers/spi/spi.c:717
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_register_controller
  - drivers/spi/spi.c:spi_register_controller
  - drivers/spi/spi.c:spi_register_board_info
  - drivers/spi/spi.c:spi_register_board_info
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff81889db2)
Location: drivers/spi/spi.c:726
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_register_controller
  - drivers/spi/spi.c:spi_register_controller
  - drivers/spi/spi.c:spi_register_board_info
  - drivers/spi/spi.c:spi_register_board_info
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff8186c7b6)
Location: drivers/spi/spi.c:730
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_register_controller
  - drivers/spi/spi.c:spi_register_controller
  - drivers/spi/spi.c:spi_register_board_info
  - drivers/spi/spi.c:spi_register_board_info
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff818fc658)
Location: drivers/spi/spi.c:789
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_register_controller
  - drivers/spi/spi.c:spi_register_controller
  - drivers/spi/spi.c:spi_register_board_info
  - drivers/spi/spi.c:spi_register_board_info
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff81a4dceb)
Location: drivers/spi/spi.c:758
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_register_controller
  - drivers/spi/spi.c:spi_register_controller
  - drivers/spi/spi.c:spi_register_board_info
  - drivers/spi/spi.c:spi_register_board_info
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff81bd818d)
Location: drivers/spi/spi.c:820
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_register_controller
  - drivers/spi/spi.c:spi_register_controller
  - drivers/spi/spi.c:spi_register_board_info
  - drivers/spi/spi.c:spi_register_board_info
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff81c2eb86)
Location: drivers/spi/spi.c:821
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_register_controller
  - drivers/spi/spi.c:spi_register_controller
  - drivers/spi/spi.c:spi_register_board_info
  - drivers/spi/spi.c:spi_register_board_info
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffff81ce192e)
Location: drivers/spi/spi.c:860
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_register_controller
  - drivers/spi/spi.c:spi_register_controller
  - drivers/spi/spi.c:spi_register_board_info
  - drivers/spi/spi.c:spi_register_board_info
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
void spi_match_controller_to_boardinfo(struct spi_controller *ctlr, struct spi_board_info *bi);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffff8000109c3b98)
Location: drivers/spi/spi.c:705
Inline: True
Direct callers:
  - drivers/spi/spi.c:spi_register_controller
  - drivers/spi/spi.c:spi_register_board_info
```
**Symbols:**

```
ffff8000109c3b98-ffff8000109c3bf8: spi_match_controller_to_boardinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void spi_match_controller_to_boardinfo(struct spi_controller *ctlr, struct spi_board_info *bi);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (c0ab0688)
Location: drivers/spi/spi.c:705
Inline: True
Direct callers:
  - drivers/spi/spi.c:spi_register_controller
  - drivers/spi/spi.c:spi_register_board_info
```
**Symbols:**

```
c0ab0688-c0ab06dc: spi_match_controller_to_boardinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void spi_match_controller_to_boardinfo(struct spi_controller *ctlr, struct spi_board_info *bi);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (c000000000a879a0)
Location: drivers/spi/spi.c:705
Inline: True
Direct callers:
  - drivers/spi/spi.c:spi_register_controller
  - drivers/spi/spi.c:spi_register_board_info
```
**Symbols:**

```
c000000000a879a0-c000000000a87a1c: spi_match_controller_to_boardinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void spi_match_controller_to_boardinfo(struct spi_controller *ctlr, struct spi_board_info *bi);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (ffffffe0006179f8)
Location: drivers/spi/spi.c:705
Inline: True
Direct callers:
  - drivers/spi/spi.c:spi_register_controller
  - drivers/spi/spi.c:spi_register_board_info
```
**Symbols:**

```
ffffffe0006179f8-ffffffe000617a50: spi_match_controller_to_boardinfo (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
void spi_match_controller_to_boardinfo(struct spi_controller *ctlr, struct spi_board_info *bi);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (ffffffff8177af04)
Location: drivers/spi/spi.c:705
Inline: True
Direct callers:
  - drivers/spi/spi.c:spi_register_controller
  - drivers/spi/spi.c:spi_register_board_info
```
**Symbols:**

```
ffffffff817780f0-ffffffff81778125: spi_match_controller_to_boardinfo (STB_LOCAL)
ffffffff8177af04-ffffffff8177af1c: spi_match_controller_to_boardinfo.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
void spi_match_controller_to_boardinfo(struct spi_controller *ctlr, struct spi_board_info *bi);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (ffffffff8175acb4)
Location: drivers/spi/spi.c:705
Inline: True
Direct callers:
  - drivers/spi/spi.c:spi_register_controller
  - drivers/spi/spi.c:spi_register_board_info
```
**Symbols:**

```
ffffffff81757ea0-ffffffff81757ed5: spi_match_controller_to_boardinfo (STB_LOCAL)
ffffffff8175acb4-ffffffff8175accc: spi_match_controller_to_boardinfo.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
void spi_match_controller_to_boardinfo(struct spi_controller *ctlr, struct spi_board_info *bi);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (ffffffff817ab2a4)
Location: drivers/spi/spi.c:705
Inline: True
Direct callers:
  - drivers/spi/spi.c:spi_register_controller
  - drivers/spi/spi.c:spi_register_board_info
```
**Symbols:**

```
ffffffff817a8490-ffffffff817a84c5: spi_match_controller_to_boardinfo (STB_LOCAL)
ffffffff817ab2a4-ffffffff817ab2bc: spi_match_controller_to_boardinfo.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void spi_match_controller_to_boardinfo(struct spi_controller *ctlr, struct spi_board_info *bi);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/spi/spi.c (ffffffff817c5234)
Location: drivers/spi/spi.c:705
Inline: True
Direct callers:
  - drivers/spi/spi.c:spi_register_controller
  - drivers/spi/spi.c:spi_register_board_info
```
**Symbols:**

```
ffffffff817c2320-ffffffff817c2355: spi_match_controller_to_boardinfo (STB_LOCAL)
ffffffff817c5234-ffffffff817c524c: spi_match_controller_to_boardinfo.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
