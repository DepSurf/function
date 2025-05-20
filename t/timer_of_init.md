# Function: <code>timer_of_init</code>

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
<summary>In <code>arm64</code>: ✅</summary>

```c
int timer_of_init(struct device_node *np, struct timer_of *to);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clocksource/timer-of.c (ffff8000114a7cb0)
Location: drivers/clocksource/timer-of.c:168
Inline: False
Direct callers:
  - drivers/clocksource/timer-mediatek.c:mtk_gpt_init
  - drivers/clocksource/timer-mediatek.c:mtk_syst_init
  - drivers/clocksource/timer-sprd.c:sprd_suspend_timer_init
  - drivers/clocksource/timer-sprd.c:sprd_timer_init
  - drivers/clocksource/timer-imx-sysctr.c:sysctr_timer_init
```
**Symbols:**

```
ffff8000114a7cb0-ffff8000114a7f80: timer_of_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int timer_of_init(struct device_node *np, struct timer_of *to);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clocksource/timer-of.c (c15aa274)
Location: drivers/clocksource/timer-of.c:168
Inline: False
Direct callers:
  - drivers/clocksource/timer-tegra.c:tegra20_init_rtc
  - drivers/clocksource/timer-tegra.c:tegra_init_timer
  - drivers/clocksource/timer-mediatek.c:mtk_gpt_init
  - drivers/clocksource/timer-mediatek.c:mtk_syst_init
  - drivers/clocksource/timer-milbeaut.c:mlb_timer_init
  - drivers/clocksource/timer-npcm7xx.c:npcm7xx_timer_init
  - drivers/clocksource/timer-rda.c:rda_timer_init
  - drivers/clocksource/timer-imx-tpm.c:tpm_timer_init
```
**Symbols:**

```
c15aa274-c15aa568: timer_of_init (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int timer_of_init(struct device_node *np, struct timer_of *to);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clocksource/timer-of.c (ffffffe00003a15c)
Location: drivers/clocksource/timer-of.c:168
Inline: False
```
**Symbols:**

```
ffffffe00003a15c-ffffffe00003a3fe: timer_of_init (STB_GLOBAL)
```
</details>
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
<b>Arch</b>
<ul>
</ul>
