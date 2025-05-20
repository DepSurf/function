# Function: <code>hv_stimer_cleanup</code>

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
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void hv_stimer_cleanup(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clocksource/hyperv_timer.c (ffffffff818bc930)
Location: drivers/clocksource/hyperv_timer.c:135
Inline: True
```
**Symbols:**

```
ffffffff818bc930-ffffffff818bc95e: hv_stimer_cleanup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void hv_stimer_cleanup(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clocksource/hyperv_timer.c (ffffffff818ef430)
Location: drivers/clocksource/hyperv_timer.c:136
Inline: True
```
**Symbols:**

```
ffffffff818ef430-ffffffff818ef45e: hv_stimer_cleanup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int hv_stimer_cleanup(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clocksource/hyperv_timer.c (ffffffff819c3280)
Location: drivers/clocksource/hyperv_timer.c:141
Inline: False
Direct callers:
  - drivers/clocksource/hyperv_timer.c:hv_stimer_global_cleanup
```
**Symbols:**

```
ffffffff819c3280-ffffffff819c32e9: hv_stimer_cleanup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int hv_stimer_cleanup(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clocksource/hyperv_timer.c (ffffffff819c3670)
Location: drivers/clocksource/hyperv_timer.c:141
Inline: False
Direct callers:
  - drivers/clocksource/hyperv_timer.c:hv_stimer_global_cleanup
```
**Symbols:**

```
ffffffff819c3670-ffffffff819c36d9: hv_stimer_cleanup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int hv_stimer_cleanup(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clocksource/hyperv_timer.c (ffffffff819a79c0)
Location: drivers/clocksource/hyperv_timer.c:154
Inline: False
Direct callers:
  - drivers/clocksource/hyperv_timer.c:hv_stimer_global_cleanup
```
**Symbols:**

```
ffffffff819a79c0-ffffffff819a7a3e: hv_stimer_cleanup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int hv_stimer_cleanup(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/clocksource/hyperv_timer.c (0)
Location: drivers/clocksource/hyperv_timer.c:154
Inline: False
Direct callers:
  - drivers/clocksource/hyperv_timer.c:hv_stimer_global_cleanup
```
**Symbols:**

```
ffffffff81d30d04-ffffffff81d30d19: hv_stimer_cleanup.cold (STB_LOCAL)
ffffffff81a54ea0-ffffffff81a54f1e: hv_stimer_cleanup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int hv_stimer_cleanup(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/clocksource/hyperv_timer.c (0)
Location: drivers/clocksource/hyperv_timer.c:154
Inline: False
Direct callers:
  - drivers/clocksource/hyperv_timer.c:hv_stimer_global_cleanup
```
**Symbols:**

```
ffffffff81efd141-ffffffff81efd156: hv_stimer_cleanup.cold (STB_LOCAL)
ffffffff81bc4660-ffffffff81bc46ee: hv_stimer_cleanup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int hv_stimer_cleanup(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/clocksource/hyperv_timer.c (0)
Location: drivers/clocksource/hyperv_timer.c:155
Inline: False
Direct callers:
  - drivers/clocksource/hyperv_timer.c:hv_stimer_global_cleanup
```
**Symbols:**

```
ffffffff820a9fd7-ffffffff820a9fec: hv_stimer_cleanup.cold (STB_LOCAL)
ffffffff81d69e90-ffffffff81d69f1e: hv_stimer_cleanup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int hv_stimer_cleanup(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/clocksource/hyperv_timer.c (0)
Location: drivers/clocksource/hyperv_timer.c:155
Inline: False
Direct callers:
  - drivers/clocksource/hyperv_timer.c:hv_stimer_global_cleanup
```
**Symbols:**

```
ffffffff8212b4b5-ffffffff8212b4ca: hv_stimer_cleanup.cold (STB_LOCAL)
ffffffff81dd52c0-ffffffff81dd534e: hv_stimer_cleanup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int hv_stimer_cleanup(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/clocksource/hyperv_timer.c (0)
Location: drivers/clocksource/hyperv_timer.c:155
Inline: False
Direct callers:
  - drivers/clocksource/hyperv_timer.c:hv_stimer_global_cleanup
```
**Symbols:**

```
ffffffff8220d1b2-ffffffff8220d1c7: hv_stimer_cleanup.cold (STB_LOCAL)
ffffffff81e8d410-ffffffff81e8d49e: hv_stimer_cleanup (STB_GLOBAL)
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
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void hv_stimer_cleanup(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clocksource/hyperv_timer.c (ffffffff81890800)
Location: drivers/clocksource/hyperv_timer.c:136
Inline: True
```
**Symbols:**

```
ffffffff81890800-ffffffff8189082e: hv_stimer_cleanup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void hv_stimer_cleanup(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clocksource/hyperv_timer.c (ffffffff81849bb0)
Location: drivers/clocksource/hyperv_timer.c:136
Inline: True
Direct callers:
  - drivers/hv/vmbus_drv.c:hv_crash_handler
  - drivers/hv/hv.c:hv_synic_cleanup
```
**Symbols:**

```
ffffffff81849bb0-ffffffff81849bde: hv_stimer_cleanup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void hv_stimer_cleanup(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clocksource/hyperv_timer.c (ffffffff818e4260)
Location: drivers/clocksource/hyperv_timer.c:136
Inline: True
```
**Symbols:**

```
ffffffff818e4260-ffffffff818e428e: hv_stimer_cleanup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void hv_stimer_cleanup(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clocksource/hyperv_timer.c (ffffffff81900ec0)
Location: drivers/clocksource/hyperv_timer.c:136
Inline: True
```
**Symbols:**

```
ffffffff81900ec0-ffffffff81900eee: hv_stimer_cleanup (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>int</code>
</li>
</ul>
</details>
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
