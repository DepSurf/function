# Function: <code>timer_of_rate</code>

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
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
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
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/clocksource/timer-mediatek.c (0)
Location: drivers/clocksource/timer-of.h:59
Inline: True
```
```
In drivers/clocksource/timer-sprd.c (0)
Location: drivers/clocksource/timer-of.h:59
Inline: True
```
```
In drivers/clocksource/timer-imx-sysctr.c (0)
Location: drivers/clocksource/timer-of.h:59
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/clocksource/timer-tegra.c (c15abc94)
Location: drivers/clocksource/timer-of.h:59
Inline: True
Inline callers:
  - drivers/clocksource/timer-tegra.c:tegra_init_timer
  - drivers/clocksource/timer-tegra.c:tegra_init_timer
  - drivers/clocksource/timer-tegra.c:tegra_timer_setup
```
```
In drivers/clocksource/timer-mediatek.c (c15ac7d0)
Location: drivers/clocksource/timer-of.h:59
Inline: True
Inline callers:
  - drivers/clocksource/timer-mediatek.c:mtk_gpt_init
  - drivers/clocksource/timer-mediatek.c:mtk_gpt_init
  - drivers/clocksource/timer-mediatek.c:mtk_gpt_init
  - drivers/clocksource/timer-mediatek.c:mtk_syst_init
```
```
In drivers/clocksource/timer-milbeaut.c (c15acb64)
Location: drivers/clocksource/timer-of.h:59
Inline: True
Inline callers:
  - drivers/clocksource/timer-milbeaut.c:mlb_timer_init
  - drivers/clocksource/timer-milbeaut.c:mlb_timer_init
```
```
In drivers/clocksource/timer-npcm7xx.c (c15acc6c)
Location: drivers/clocksource/timer-of.h:59
Inline: True
Inline callers:
  - drivers/clocksource/timer-npcm7xx.c:npcm7xx_timer_init
  - drivers/clocksource/timer-npcm7xx.c:npcm7xx_timer_init
```
```
In drivers/clocksource/timer-imx-tpm.c (c15ae71c)
Location: drivers/clocksource/timer-of.h:59
Inline: True
Inline callers:
  - drivers/clocksource/timer-imx-tpm.c:tpm_timer_init
  - drivers/clocksource/timer-imx-tpm.c:tpm_timer_init
  - drivers/clocksource/timer-imx-tpm.c:tpm_timer_init
  - drivers/clocksource/timer-imx-tpm.c:tpm_timer_init
```
</details>
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
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
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
