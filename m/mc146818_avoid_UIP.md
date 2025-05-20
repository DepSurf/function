# Function: <code>mc146818_avoid_UIP</code>

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
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool mc146818_avoid_UIP(void (*callback)(unsigned char, void *), void *param);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/rtc-mc146818-lib.c (ffffffff81b2b200)
Location: drivers/rtc/rtc-mc146818-lib.c:17
Inline: False
Direct callers:
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_does_rtc_work
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
```
**Symbols:**

```
ffffffff81b2b200-ffffffff81b2b2ec: mc146818_avoid_UIP (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool mc146818_avoid_UIP(void (*callback)(unsigned char, void *), void *param);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/rtc-mc146818-lib.c (ffffffff81cbefc0)
Location: drivers/rtc/rtc-mc146818-lib.c:17
Inline: False
Direct callers:
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_does_rtc_work
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
```
**Symbols:**

```
ffffffff81cbefc0-ffffffff81cbf09b: mc146818_avoid_UIP (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool mc146818_avoid_UIP(void (*callback)(unsigned char, void *), void *param);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/rtc-mc146818-lib.c (ffffffff81d26920)
Location: drivers/rtc/rtc-mc146818-lib.c:17
Inline: False
Direct callers:
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_does_rtc_work
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
```
**Symbols:**

```
ffffffff81d26920-ffffffff81d269fb: mc146818_avoid_UIP (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool mc146818_avoid_UIP(void (*callback)(unsigned char, void *), int timeout, void *param);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/rtc-mc146818-lib.c (ffffffff81ddc690)
Location: drivers/rtc/rtc-mc146818-lib.c:21
Inline: False
Direct callers:
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_get_time
  - drivers/rtc/rtc-mc146818-lib.c:mc146818_does_rtc_work
  - drivers/rtc/rtc-cmos.c:cmos_set_alarm
  - drivers/rtc/rtc-cmos.c:cmos_read_alarm
```
**Symbols:**

```
ffffffff81ddc690-ffffffff81ddc7df: mc146818_avoid_UIP (STB_GLOBAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int timeout</code>
</li>
<li>
<b>Param reordered. </b>
<code>callback, param</code> ➡️ <code>callback, timeout, param</code>
</li>
</ul>
</details>
</li>
</ul>
