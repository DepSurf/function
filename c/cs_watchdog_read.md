# Function: <code>cs_watchdog_read</code>

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
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
bool cs_watchdog_read(struct clocksource *cs, u64 *csnow, u64 *wdnow);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/clocksource.c (0)
Location: kernel/time/clocksource.c:197
Inline: False
Direct callers:
  - kernel/time/clocksource.c:clocksource_watchdog
```
**Symbols:**

```
ffffffff81148b10-ffffffff81148be8: cs_watchdog_read (STB_LOCAL)
ffffffff81bd576c-ffffffff81bd57bc: cs_watchdog_read.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
enum wd_read_status cs_watchdog_read(struct clocksource *cs, u64 *csnow, u64 *wdnow);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/clocksource.c (0)
Location: kernel/time/clocksource.c:214
Inline: False
Direct callers:
  - kernel/time/clocksource.c:clocksource_watchdog
```
**Symbols:**

```
ffffffff8116c6f0-ffffffff8116c862: cs_watchdog_read (STB_LOCAL)
ffffffff81cb14dd-ffffffff81cb15bf: cs_watchdog_read.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
enum wd_read_status cs_watchdog_read(struct clocksource *cs, u64 *csnow, u64 *wdnow);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/clocksource.c (0)
Location: kernel/time/clocksource.c:220
Inline: False
Direct callers:
  - kernel/time/clocksource.c:clocksource_watchdog
```
**Symbols:**

```
ffffffff811a06d0-ffffffff811a0822: cs_watchdog_read (STB_LOCAL)
ffffffff81e62a74-ffffffff81e62bad: cs_watchdog_read.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
enum wd_read_status cs_watchdog_read(struct clocksource *cs, u64 *csnow, u64 *wdnow);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/clocksource.c (0)
Location: kernel/time/clocksource.c:220
Inline: False
Direct callers:
  - kernel/time/clocksource.c:clocksource_watchdog
```
**Symbols:**

```
ffffffff811df530-ffffffff811df74b: cs_watchdog_read (STB_LOCAL)
ffffffff8205b85f-ffffffff8205b8f9: cs_watchdog_read.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
enum wd_read_status cs_watchdog_read(struct clocksource *cs, u64 *csnow, u64 *wdnow);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/clocksource.c (0)
Location: kernel/time/clocksource.c:223
Inline: False
Direct callers:
  - kernel/time/clocksource.c:clocksource_watchdog
```
**Symbols:**

```
ffffffff811f3a10-ffffffff811f3c0b: cs_watchdog_read (STB_LOCAL)
ffffffff820da0ea-ffffffff820da10b: cs_watchdog_read.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
enum wd_read_status cs_watchdog_read(struct clocksource *cs, u64 *csnow, u64 *wdnow);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/clocksource.c (0)
Location: kernel/time/clocksource.c:225
Inline: False
Direct callers:
  - kernel/time/clocksource.c:clocksource_watchdog
```
**Symbols:**

```
ffffffff81209b50-ffffffff81209d4b: cs_watchdog_read (STB_LOCAL)
ffffffff821b59e9-ffffffff821b5a0a: cs_watchdog_read.cold (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>bool</code> ➡️ <code>enum wd_read_status</code>
</li>
</ul>
</details>
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
