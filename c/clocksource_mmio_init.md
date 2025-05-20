# Function: <code>clocksource_mmio_init</code>

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
int clocksource_mmio_init(void *base, const char *name, long unsigned int hz, int rating, unsigned int bits, u64 (*read)(struct clocksource *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clocksource/mmio.c (ffff8000114a81d4)
Location: drivers/clocksource/mmio.c:49
Inline: False
Direct callers:
  - drivers/clocksource/timer-rockchip.c:rk_timer_init
  - drivers/clocksource/timer-mediatek.c:mtk_gpt_init
  - drivers/clocksource/timer-owl.c:owl_timer_init
  - drivers/clocksource/timer-sp804.c:__sp804_clocksource_and_sched_clock_init
```
**Symbols:**

```
ffff8000114a81d4-ffff8000114a828c: clocksource_mmio_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int clocksource_mmio_init(void *base, const char *name, long unsigned int hz, int rating, unsigned int bits, u64 (*read)(struct clocksource *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clocksource/mmio.c (c15aaaf0)
Location: drivers/clocksource/mmio.c:49
Inline: False
Direct callers:
  - arch/arm/plat-omap/counter_32k.c:omap_init_clocksource_32k
  - drivers/clocksource/renesas-ostm.c:ostm_init
  - drivers/clocksource/timer-rockchip.c:rk_timer_init
  - drivers/clocksource/timer-armada-370-xp.c:armada_370_xp_timer_common_init
  - drivers/clocksource/timer-orion.c:orion_timer_init
  - drivers/clocksource/timer-meson6.c:meson6_timer_init
  - drivers/clocksource/timer-tegra.c:tegra_init_timer
  - drivers/clocksource/timer-mediatek.c:mtk_gpt_init
  - drivers/clocksource/timer-owl.c:owl_timer_init
  - drivers/clocksource/timer-milbeaut.c:mlb_timer_init
  - drivers/clocksource/timer-npcm7xx.c:npcm7xx_timer_init
  - drivers/clocksource/timer-sp804.c:__sp804_clocksource_and_sched_clock_init
  - drivers/clocksource/timer-imx-gpt.c:_mxc_timer_init
  - drivers/clocksource/timer-imx-tpm.c:tpm_timer_init
```
**Symbols:**

```
c15aaaf0-c15aaba8: clocksource_mmio_init (STB_GLOBAL)
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
<b>Arch</b>
<ul>
</ul>
