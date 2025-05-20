# Function: <code>hv_ce_shutdown</code>

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
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int hv_ce_shutdown(struct clock_event_device *evt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clocksource/hyperv_timer.c (ffffffff818bc760)
Location: drivers/clocksource/hyperv_timer.c:64
Inline: False
```
**Symbols:**

```
ffffffff818bc760-ffffffff818bc795: hv_ce_shutdown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int hv_ce_shutdown(struct clock_event_device *evt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clocksource/hyperv_timer.c (ffffffff818ef230)
Location: drivers/clocksource/hyperv_timer.c:65
Inline: False
```
**Symbols:**

```
ffffffff818ef230-ffffffff818ef265: hv_ce_shutdown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int hv_ce_shutdown(struct clock_event_device *evt);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clocksource/hyperv_timer.c (ffffffff819c32b8)
Location: drivers/clocksource/hyperv_timer.c:75
Inline: True
Inline callers:
  - drivers/clocksource/hyperv_timer.c:hv_stimer_cleanup
```
**Symbols:**

```
ffffffff819c3190-ffffffff819c31c8: hv_ce_shutdown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int hv_ce_shutdown(struct clock_event_device *evt);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clocksource/hyperv_timer.c (ffffffff819c36a8)
Location: drivers/clocksource/hyperv_timer.c:75
Inline: True
Inline callers:
  - drivers/clocksource/hyperv_timer.c:hv_stimer_cleanup
```
**Symbols:**

```
ffffffff819c3580-ffffffff819c35b8: hv_ce_shutdown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int hv_ce_shutdown(struct clock_event_device *evt);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clocksource/hyperv_timer.c (ffffffff819a79eb)
Location: drivers/clocksource/hyperv_timer.c:87
Inline: True
Inline callers:
  - drivers/clocksource/hyperv_timer.c:hv_stimer_cleanup
  - drivers/clocksource/hyperv_timer.c:hv_stimer_cleanup
```
**Symbols:**

```
ffffffff819a78b0-ffffffff819a7908: hv_ce_shutdown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int hv_ce_shutdown(struct clock_event_device *evt);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/clocksource/hyperv_timer.c (ffffffff81a54e75)
Location: drivers/clocksource/hyperv_timer.c:87
Inline: True
Direct callers:
  - drivers/clocksource/hyperv_timer.c:hv_stimer_cleanup
```
**Symbols:**

```
ffffffff81a54e30-ffffffff81a54e94: hv_ce_shutdown (STB_LOCAL)
ffffffff81d30cf0-ffffffff81d30d04: hv_ce_shutdown.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
int hv_ce_shutdown(struct clock_event_device *evt);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/clocksource/hyperv_timer.c (ffffffff81bc4603)
Location: drivers/clocksource/hyperv_timer.c:87
Inline: True
Direct callers:
  - drivers/clocksource/hyperv_timer.c:hv_stimer_cleanup
```
**Symbols:**

```
ffffffff81bc45c0-ffffffff81bc4652: hv_ce_shutdown (STB_LOCAL)
ffffffff81efd12d-ffffffff81efd141: hv_ce_shutdown.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
int hv_ce_shutdown(struct clock_event_device *evt);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/clocksource/hyperv_timer.c (ffffffff81d69e23)
Location: drivers/clocksource/hyperv_timer.c:88
Inline: True
Direct callers:
  - drivers/clocksource/hyperv_timer.c:hv_stimer_cleanup
```
**Symbols:**

```
ffffffff81d69de0-ffffffff81d69e72: hv_ce_shutdown (STB_LOCAL)
ffffffff820a9fc3-ffffffff820a9fd7: hv_ce_shutdown.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
int hv_ce_shutdown(struct clock_event_device *evt);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/clocksource/hyperv_timer.c (ffffffff81dd5277)
Location: drivers/clocksource/hyperv_timer.c:88
Inline: True
Direct callers:
  - drivers/clocksource/hyperv_timer.c:hv_stimer_cleanup
```
**Symbols:**

```
ffffffff81dd5240-ffffffff81dd52a6: hv_ce_shutdown (STB_LOCAL)
ffffffff8212b4a1-ffffffff8212b4b5: hv_ce_shutdown.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int hv_ce_shutdown(struct clock_event_device *evt);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/clocksource/hyperv_timer.c (ffffffff81e8d3c7)
Location: drivers/clocksource/hyperv_timer.c:88
Inline: True
Direct callers:
  - drivers/clocksource/hyperv_timer.c:hv_stimer_cleanup
```
**Symbols:**

```
ffffffff81e8d390-ffffffff81e8d3f6: hv_ce_shutdown (STB_LOCAL)
ffffffff8220d19e-ffffffff8220d1b2: hv_ce_shutdown.cold (STB_LOCAL)
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
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int hv_ce_shutdown(struct clock_event_device *evt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clocksource/hyperv_timer.c (ffffffff81890600)
Location: drivers/clocksource/hyperv_timer.c:65
Inline: False
```
**Symbols:**

```
ffffffff81890600-ffffffff81890635: hv_ce_shutdown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int hv_ce_shutdown(struct clock_event_device *evt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clocksource/hyperv_timer.c (ffffffff81849b60)
Location: drivers/clocksource/hyperv_timer.c:65
Inline: False
```
**Symbols:**

```
ffffffff81849b60-ffffffff81849baf: hv_ce_shutdown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int hv_ce_shutdown(struct clock_event_device *evt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clocksource/hyperv_timer.c (ffffffff818e4060)
Location: drivers/clocksource/hyperv_timer.c:65
Inline: False
```
**Symbols:**

```
ffffffff818e4060-ffffffff818e4095: hv_ce_shutdown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int hv_ce_shutdown(struct clock_event_device *evt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clocksource/hyperv_timer.c (ffffffff81900cc0)
Location: drivers/clocksource/hyperv_timer.c:65
Inline: False
```
**Symbols:**

```
ffffffff81900cc0-ffffffff81900cf5: hv_ce_shutdown (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
