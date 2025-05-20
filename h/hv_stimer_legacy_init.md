# Function: <code>hv_stimer_legacy_init</code>

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
<summary>In <code>5.8</code>: ✅</summary>

```c
void hv_stimer_legacy_init(unsigned int cpu, int sint);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clocksource/hyperv_timer.c (ffffffff819c2f20)
Location: drivers/clocksource/hyperv_timer.c:226
Inline: False
```
**Symbols:**

```
ffffffff819c2f20-ffffffff819c2f40: hv_stimer_legacy_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void hv_stimer_legacy_init(unsigned int cpu, int sint);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clocksource/hyperv_timer.c (ffffffff819c3310)
Location: drivers/clocksource/hyperv_timer.c:226
Inline: False
```
**Symbols:**

```
ffffffff819c3310-ffffffff819c3330: hv_stimer_legacy_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void hv_stimer_legacy_init(unsigned int cpu, int sint);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clocksource/hyperv_timer.c (ffffffff819a7780)
Location: drivers/clocksource/hyperv_timer.c:295
Inline: False
```
**Symbols:**

```
ffffffff819a7780-ffffffff819a77a0: hv_stimer_legacy_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void hv_stimer_legacy_init(unsigned int cpu, int sint);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/clocksource/hyperv_timer.c (0)
Location: drivers/clocksource/hyperv_timer.c:295
Inline: False
```
**Symbols:**

```
ffffffff81d30cc7-ffffffff81d30cdc: hv_stimer_legacy_init.cold (STB_LOCAL)
ffffffff81a54cd0-ffffffff81a54d10: hv_stimer_legacy_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void hv_stimer_legacy_init(unsigned int cpu, int sint);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/clocksource/hyperv_timer.c (0)
Location: drivers/clocksource/hyperv_timer.c:295
Inline: False
```
**Symbols:**

```
ffffffff81efd104-ffffffff81efd119: hv_stimer_legacy_init.cold (STB_LOCAL)
ffffffff81bc42e0-ffffffff81bc432a: hv_stimer_legacy_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void hv_stimer_legacy_init(unsigned int cpu, int sint);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/clocksource/hyperv_timer.c (0)
Location: drivers/clocksource/hyperv_timer.c:296
Inline: False
```
**Symbols:**

```
ffffffff820a9f9a-ffffffff820a9faf: hv_stimer_legacy_init.cold (STB_LOCAL)
ffffffff81d69a60-ffffffff81d69aaa: hv_stimer_legacy_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void hv_stimer_legacy_init(unsigned int cpu, int sint);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/clocksource/hyperv_timer.c (0)
Location: drivers/clocksource/hyperv_timer.c:307
Inline: False
```
**Symbols:**

```
ffffffff8212b478-ffffffff8212b48d: hv_stimer_legacy_init.cold (STB_LOCAL)
ffffffff81dd5160-ffffffff81dd51aa: hv_stimer_legacy_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void hv_stimer_legacy_init(unsigned int cpu, int sint);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/clocksource/hyperv_timer.c (0)
Location: drivers/clocksource/hyperv_timer.c:307
Inline: False
```
**Symbols:**

```
ffffffff8220d175-ffffffff8220d18a: hv_stimer_legacy_init.cold (STB_LOCAL)
ffffffff81e8d2b0-ffffffff81e8d2fa: hv_stimer_legacy_init (STB_GLOBAL)
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
