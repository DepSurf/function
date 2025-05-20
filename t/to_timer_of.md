# Function: <code>to_timer_of</code>

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
In drivers/clocksource/timer-mediatek.c (ffff800010b66690)
Location: drivers/clocksource/timer-of.h:44
Inline: True
Inline callers:
  - drivers/clocksource/timer-mediatek.c:mtk_gpt_interrupt
  - drivers/clocksource/timer-mediatek.c:mtk_gpt_clkevt_next_event
  - drivers/clocksource/timer-mediatek.c:mtk_gpt_clkevt_set_periodic
  - drivers/clocksource/timer-mediatek.c:mtk_gpt_clkevt_shutdown
  - drivers/clocksource/timer-mediatek.c:mtk_syst_clkevt_next_event
  - drivers/clocksource/timer-mediatek.c:mtk_syst_handler
```
```
In drivers/clocksource/timer-sprd.c (ffff800010b66c28)
Location: drivers/clocksource/timer-of.h:44
Inline: True
Inline callers:
  - drivers/clocksource/timer-sprd.c:sprd_timer_interrupt
  - drivers/clocksource/timer-sprd.c:sprd_timer_shutdown
  - drivers/clocksource/timer-sprd.c:sprd_timer_set_periodic
  - drivers/clocksource/timer-sprd.c:sprd_timer_set_next_event
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
In drivers/clocksource/timer-tegra.c (c0c49acc)
Location: drivers/clocksource/timer-of.h:44
Inline: True
Inline callers:
  - drivers/clocksource/timer-tegra.c:tegra_timer_suspend
  - drivers/clocksource/timer-tegra.c:tegra_timer_isr
  - drivers/clocksource/timer-tegra.c:tegra_timer_set_periodic
  - drivers/clocksource/timer-tegra.c:tegra_timer_set_periodic
  - drivers/clocksource/timer-tegra.c:tegra_timer_shutdown
  - drivers/clocksource/timer-tegra.c:tegra_timer_set_next_event
```
```
In drivers/clocksource/timer-mediatek.c (c0c4a6d4)
Location: drivers/clocksource/timer-of.h:44
Inline: True
Inline callers:
  - drivers/clocksource/timer-mediatek.c:mtk_gpt_interrupt
  - drivers/clocksource/timer-mediatek.c:mtk_gpt_clkevt_next_event
  - drivers/clocksource/timer-mediatek.c:mtk_gpt_clkevt_set_periodic
  - drivers/clocksource/timer-mediatek.c:mtk_gpt_clkevt_shutdown
  - drivers/clocksource/timer-mediatek.c:mtk_syst_clkevt_next_event
  - drivers/clocksource/timer-mediatek.c:mtk_syst_handler
```
```
In drivers/clocksource/timer-milbeaut.c (c0c4ac48)
Location: drivers/clocksource/timer-of.h:44
Inline: True
Inline callers:
  - drivers/clocksource/timer-milbeaut.c:mlb_clkevt_next_event
  - drivers/clocksource/timer-milbeaut.c:mlb_set_state_shutdown
  - drivers/clocksource/timer-milbeaut.c:mlb_set_state_oneshot
  - drivers/clocksource/timer-milbeaut.c:mlb_set_state_periodic
  - drivers/clocksource/timer-milbeaut.c:mlb_timer_interrupt
```
```
In drivers/clocksource/timer-npcm7xx.c (c0c4aca8)
Location: drivers/clocksource/timer-of.h:44
Inline: True
Inline callers:
  - drivers/clocksource/timer-npcm7xx.c:npcm7xx_timer0_interrupt
  - drivers/clocksource/timer-npcm7xx.c:npcm7xx_clockevent_set_next_event
  - drivers/clocksource/timer-npcm7xx.c:npcm7xx_timer_periodic
  - drivers/clocksource/timer-npcm7xx.c:npcm7xx_timer_oneshot
  - drivers/clocksource/timer-npcm7xx.c:npcm7xx_timer_shutdown
  - drivers/clocksource/timer-npcm7xx.c:npcm7xx_timer_resume
```
```
In drivers/clocksource/timer-rda.c (c0c4af54)
Location: drivers/clocksource/timer-of.h:44
Inline: True
Inline callers:
  - drivers/clocksource/timer-rda.c:rda_ostimer_interrupt
  - drivers/clocksource/timer-rda.c:rda_ostimer_set_next_event
  - drivers/clocksource/timer-rda.c:rda_ostimer_set_state_periodic
  - drivers/clocksource/timer-rda.c:rda_ostimer_set_state_shutdown
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
