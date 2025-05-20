# Function: <code>timer_probe</code>

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
void timer_probe();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clocksource/timer-probe.c (ffff8000114a8000)
Location: drivers/clocksource/timer-probe.c:16
Inline: False
Direct callers:
  - arch/arm64/kernel/time.c:time_init
```
**Symbols:**

```
ffff8000114a8000-ffff8000114a811c: timer_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void timer_probe();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clocksource/timer-probe.c (c15aa5f4)
Location: drivers/clocksource/timer-probe.c:16
Inline: False
Direct callers:
  - arch/arm/kernel/time.c:time_init
  - arch/arm/mach-mediatek/mediatek.c:mediatek_timer_init
  - arch/arm/mach-omap2/timer.c:omap5_realtime_timer_init
  - arch/arm/mach-omap2/timer.c:omap4_local_timer_init
  - arch/arm/mach-omap2/timer.c:omap3_gptimer_timer_init
  - arch/arm/mach-omap2/timer.c:omap3_secure_sync32k_timer_init
  - arch/arm/mach-omap2/timer.c:omap_init_time
  - arch/arm/mach-rockchip/rockchip.c:rockchip_timer_init
  - arch/arm/mach-shmobile/setup-rcar-gen2.c:rcar_gen2_timer_init
```
**Symbols:**

```
c15aa5f4-c15aa6f0: timer_probe (STB_GLOBAL)
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
void timer_probe();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clocksource/timer-probe.c (ffffffe00003a488)
Location: drivers/clocksource/timer-probe.c:16
Inline: False
Direct callers:
  - arch/riscv/kernel/time.c:time_init
```
**Symbols:**

```
ffffffe00003a488-ffffffe00003a546: timer_probe (STB_GLOBAL)
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
