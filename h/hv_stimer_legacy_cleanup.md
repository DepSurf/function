# Function: <code>hv_stimer_legacy_cleanup</code>

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
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void hv_stimer_legacy_cleanup(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clocksource/hyperv_timer.c (ffffffff819c333b)
Location: drivers/clocksource/hyperv_timer.c:249
Inline: True
Inline callers:
  - drivers/clocksource/hyperv_timer.c:hv_stimer_global_cleanup
```
**Symbols:**

```
ffffffff819c32f0-ffffffff819c330a: hv_stimer_legacy_cleanup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void hv_stimer_legacy_cleanup(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clocksource/hyperv_timer.c (ffffffff819c372b)
Location: drivers/clocksource/hyperv_timer.c:249
Inline: True
Inline callers:
  - drivers/clocksource/hyperv_timer.c:hv_stimer_global_cleanup
```
**Symbols:**

```
ffffffff819c36e0-ffffffff819c36fa: hv_stimer_legacy_cleanup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void hv_stimer_legacy_cleanup(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clocksource/hyperv_timer.c (ffffffff819a7c7b)
Location: drivers/clocksource/hyperv_timer.c:318
Inline: True
Inline callers:
  - drivers/clocksource/hyperv_timer.c:hv_stimer_global_cleanup
```
**Symbols:**

```
ffffffff819a7a40-ffffffff819a7a5a: hv_stimer_legacy_cleanup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void hv_stimer_legacy_cleanup(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/clocksource/hyperv_timer.c (ffffffff81a5522c)
Location: drivers/clocksource/hyperv_timer.c:318
Inline: True
Inline callers:
  - drivers/clocksource/hyperv_timer.c:hv_stimer_global_cleanup
```
**Symbols:**

```
ffffffff81d30d19-ffffffff81d30d2d: hv_stimer_legacy_cleanup.cold (STB_LOCAL)
ffffffff81a54f20-ffffffff81a54f51: hv_stimer_legacy_cleanup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void hv_stimer_legacy_cleanup(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/clocksource/hyperv_timer.c (ffffffff81bc4989)
Location: drivers/clocksource/hyperv_timer.c:318
Inline: True
Inline callers:
  - drivers/clocksource/hyperv_timer.c:hv_stimer_global_cleanup
```
**Symbols:**

```
ffffffff81efd156-ffffffff81efd16b: hv_stimer_legacy_cleanup.cold (STB_LOCAL)
ffffffff81bc46f0-ffffffff81bc472c: hv_stimer_legacy_cleanup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
void hv_stimer_legacy_cleanup(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/clocksource/hyperv_timer.c (ffffffff81d6a202)
Location: drivers/clocksource/hyperv_timer.c:319
Inline: True
Inline callers:
  - drivers/clocksource/hyperv_timer.c:hv_stimer_global_cleanup
```
**Symbols:**

```
ffffffff820a9fec-ffffffff820aa001: hv_stimer_legacy_cleanup.cold (STB_LOCAL)
ffffffff81d69f30-ffffffff81d69f6c: hv_stimer_legacy_cleanup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
void hv_stimer_legacy_cleanup(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/clocksource/hyperv_timer.c (ffffffff81dd55c2)
Location: drivers/clocksource/hyperv_timer.c:330
Inline: True
Inline callers:
  - drivers/clocksource/hyperv_timer.c:hv_stimer_global_cleanup
```
**Symbols:**

```
ffffffff8212b4ca-ffffffff8212b4df: hv_stimer_legacy_cleanup.cold (STB_LOCAL)
ffffffff81dd5360-ffffffff81dd539c: hv_stimer_legacy_cleanup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void hv_stimer_legacy_cleanup(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/clocksource/hyperv_timer.c (ffffffff81e8d712)
Location: drivers/clocksource/hyperv_timer.c:330
Inline: True
Inline callers:
  - drivers/clocksource/hyperv_timer.c:hv_stimer_global_cleanup
```
**Symbols:**

```
ffffffff8220d1c7-ffffffff8220d1dc: hv_stimer_legacy_cleanup.cold (STB_LOCAL)
ffffffff81e8d4b0-ffffffff81e8d4ec: hv_stimer_legacy_cleanup (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
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
<b>Regular</b>
<ul>
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
