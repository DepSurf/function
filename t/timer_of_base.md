# Function: <code>timer_of_base</code>

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
Location: drivers/clocksource/timer-of.h:49
Inline: True
```
```
In drivers/clocksource/timer-sprd.c (0)
Location: drivers/clocksource/timer-of.h:49
Inline: True
```
```
In drivers/clocksource/timer-imx-sysctr.c (0)
Location: drivers/clocksource/timer-of.h:49
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
In drivers/clocksource/timer-tegra.c (c15abb3c)
Location: drivers/clocksource/timer-of.h:49
Inline: True
Inline callers:
  - drivers/clocksource/timer-tegra.c:tegra_init_timer
  - drivers/clocksource/timer-tegra.c:tegra_rtc_read_ms
  - drivers/clocksource/timer-tegra.c:tegra_timer_setup
  - drivers/clocksource/timer-tegra.c:tegra_timer_suspend
  - drivers/clocksource/timer-tegra.c:tegra_timer_isr
  - drivers/clocksource/timer-tegra.c:tegra_timer_set_periodic
  - drivers/clocksource/timer-tegra.c:tegra_timer_shutdown
  - drivers/clocksource/timer-tegra.c:tegra_timer_set_next_event
```
```
In drivers/clocksource/timer-mediatek.c (c15ac790)
Location: drivers/clocksource/timer-of.h:49
Inline: True
Inline callers:
  - drivers/clocksource/timer-mediatek.c:mtk_gpt_init
  - drivers/clocksource/timer-mediatek.c:mtk_gpt_init
  - drivers/clocksource/timer-mediatek.c:mtk_gpt_init
  - drivers/clocksource/timer-mediatek.c:mtk_gpt_init
  - drivers/clocksource/timer-mediatek.c:mtk_gpt_init
  - drivers/clocksource/timer-mediatek.c:mtk_gpt_init
  - drivers/clocksource/timer-mediatek.c:mtk_gpt_init
  - drivers/clocksource/timer-mediatek.c:mtk_gpt_init
  - drivers/clocksource/timer-mediatek.c:mtk_gpt_init
  - drivers/clocksource/timer-mediatek.c:mtk_gpt_init
  - drivers/clocksource/timer-mediatek.c:mtk_gpt_init
  - drivers/clocksource/timer-mediatek.c:mtk_gpt_init
  - drivers/clocksource/timer-mediatek.c:mtk_gpt_interrupt
  - drivers/clocksource/timer-mediatek.c:mtk_gpt_clkevt_next_event
  - drivers/clocksource/timer-mediatek.c:mtk_gpt_clkevt_next_event
  - drivers/clocksource/timer-mediatek.c:mtk_gpt_clkevt_next_event
  - drivers/clocksource/timer-mediatek.c:mtk_gpt_clkevt_next_event
  - drivers/clocksource/timer-mediatek.c:mtk_gpt_clkevt_next_event
  - drivers/clocksource/timer-mediatek.c:mtk_gpt_clkevt_set_periodic
  - drivers/clocksource/timer-mediatek.c:mtk_gpt_clkevt_set_periodic
  - drivers/clocksource/timer-mediatek.c:mtk_gpt_clkevt_set_periodic
  - drivers/clocksource/timer-mediatek.c:mtk_gpt_clkevt_set_periodic
  - drivers/clocksource/timer-mediatek.c:mtk_gpt_clkevt_set_periodic
  - drivers/clocksource/timer-mediatek.c:mtk_gpt_clkevt_shutdown
  - drivers/clocksource/timer-mediatek.c:mtk_gpt_clkevt_shutdown
  - drivers/clocksource/timer-mediatek.c:mtk_syst_clkevt_next_event
  - drivers/clocksource/timer-mediatek.c:mtk_syst_clkevt_next_event
  - drivers/clocksource/timer-mediatek.c:mtk_syst_clkevt_next_event
  - drivers/clocksource/timer-mediatek.c:mtk_syst_handler
```
```
In drivers/clocksource/timer-milbeaut.c (c15acb70)
Location: drivers/clocksource/timer-of.h:49
Inline: True
Inline callers:
  - drivers/clocksource/timer-milbeaut.c:mlb_timer_init
  - drivers/clocksource/timer-milbeaut.c:mlb_timer_init
  - drivers/clocksource/timer-milbeaut.c:mlb_timer_sched_read
  - drivers/clocksource/timer-milbeaut.c:mlb_clkevt_next_event
  - drivers/clocksource/timer-milbeaut.c:mlb_set_state_shutdown
  - drivers/clocksource/timer-milbeaut.c:mlb_set_state_oneshot
  - drivers/clocksource/timer-milbeaut.c:mlb_set_state_periodic
  - drivers/clocksource/timer-milbeaut.c:mlb_timer_interrupt
```
```
In drivers/clocksource/timer-npcm7xx.c (c15acc30)
Location: drivers/clocksource/timer-of.h:49
Inline: True
Inline callers:
  - drivers/clocksource/timer-npcm7xx.c:npcm7xx_timer_init
  - drivers/clocksource/timer-npcm7xx.c:npcm7xx_timer_init
  - drivers/clocksource/timer-npcm7xx.c:npcm7xx_timer_init
  - drivers/clocksource/timer-npcm7xx.c:npcm7xx_timer_init
  - drivers/clocksource/timer-npcm7xx.c:npcm7xx_timer_init
  - drivers/clocksource/timer-npcm7xx.c:npcm7xx_timer_init
  - drivers/clocksource/timer-npcm7xx.c:npcm7xx_timer0_interrupt
  - drivers/clocksource/timer-npcm7xx.c:npcm7xx_clockevent_set_next_event
  - drivers/clocksource/timer-npcm7xx.c:npcm7xx_clockevent_set_next_event
  - drivers/clocksource/timer-npcm7xx.c:npcm7xx_timer_periodic
  - drivers/clocksource/timer-npcm7xx.c:npcm7xx_timer_periodic
  - drivers/clocksource/timer-npcm7xx.c:npcm7xx_timer_oneshot
  - drivers/clocksource/timer-npcm7xx.c:npcm7xx_timer_oneshot
  - drivers/clocksource/timer-npcm7xx.c:npcm7xx_timer_shutdown
  - drivers/clocksource/timer-npcm7xx.c:npcm7xx_timer_shutdown
  - drivers/clocksource/timer-npcm7xx.c:npcm7xx_timer_resume
  - drivers/clocksource/timer-npcm7xx.c:npcm7xx_timer_resume
```
```
In drivers/clocksource/timer-rda.c (c0c4af90)
Location: drivers/clocksource/timer-of.h:49
Inline: True
Inline callers:
  - drivers/clocksource/timer-rda.c:rda_hwtimer_read
  - drivers/clocksource/timer-rda.c:rda_ostimer_interrupt
  - drivers/clocksource/timer-rda.c:rda_ostimer_set_next_event
  - drivers/clocksource/timer-rda.c:rda_ostimer_set_state_periodic
  - drivers/clocksource/timer-rda.c:rda_ostimer_set_state_shutdown
```
```
In drivers/clocksource/timer-imx-tpm.c (c15ae668)
Location: drivers/clocksource/timer-of.h:49
Inline: True
Inline callers:
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
