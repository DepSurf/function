# Function: <code>mc146818_does_rtc_work</code>

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
bool mc146818_does_rtc_work();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/rtc-mc146818-lib.c (ffffffff81b2b2f0)
Location: drivers/rtc/rtc-mc146818-lib.c:85
Inline: False
Direct callers:
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
```
**Symbols:**

```
ffffffff81b2b2f0-ffffffff81b2b30c: mc146818_does_rtc_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool mc146818_does_rtc_work();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/rtc-mc146818-lib.c (ffffffff81cbf0b0)
Location: drivers/rtc/rtc-mc146818-lib.c:85
Inline: False
Direct callers:
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
```
**Symbols:**

```
ffffffff81cbf0b0-ffffffff81cbf0cc: mc146818_does_rtc_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool mc146818_does_rtc_work();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/rtc-mc146818-lib.c (ffffffff81d26a10)
Location: drivers/rtc/rtc-mc146818-lib.c:85
Inline: False
Direct callers:
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
```
**Symbols:**

```
ffffffff81d26a10-ffffffff81d26a2c: mc146818_does_rtc_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool mc146818_does_rtc_work();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/rtc-mc146818-lib.c (ffffffff81ddc7f0)
Location: drivers/rtc/rtc-mc146818-lib.c:94
Inline: False
Direct callers:
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
```
**Symbols:**

```
ffffffff81ddc7f0-ffffffff81ddc813: mc146818_does_rtc_work (STB_GLOBAL)
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
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
