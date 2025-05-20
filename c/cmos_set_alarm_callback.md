# Function: <code>cmos_set_alarm_callback</code>

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
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void cmos_set_alarm_callback(unsigned char seconds, void *param_in);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/rtc/rtc-cmos.c (0)
Location: drivers/rtc/rtc-cmos.c:482
Inline: False
```
**Symbols:**

```
ffffffff81b2c420-ffffffff81b2c504: cmos_set_alarm_callback (STB_LOCAL)
ffffffff81ef10a3-ffffffff81ef10b8: cmos_set_alarm_callback.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void cmos_set_alarm_callback(unsigned char seconds, void *param_in);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/rtc/rtc-cmos.c (0)
Location: drivers/rtc/rtc-cmos.c:482
Inline: False
```
**Symbols:**

```
ffffffff81cc01e0-ffffffff81cc02c4: cmos_set_alarm_callback (STB_LOCAL)
ffffffff820a748e-ffffffff820a74a3: cmos_set_alarm_callback.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void cmos_set_alarm_callback(unsigned char seconds, void *param_in);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/rtc/rtc-cmos.c (0)
Location: drivers/rtc/rtc-cmos.c:482
Inline: False
```
**Symbols:**

```
ffffffff81d27b40-ffffffff81d27c24: cmos_set_alarm_callback (STB_LOCAL)
ffffffff82128891-ffffffff821288a6: cmos_set_alarm_callback.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void cmos_set_alarm_callback(unsigned char seconds, void *param_in);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/rtc/rtc-cmos.c (0)
Location: drivers/rtc/rtc-cmos.c:482
Inline: False
```
**Symbols:**

```
ffffffff81ddd960-ffffffff81ddda44: cmos_set_alarm_callback (STB_LOCAL)
ffffffff8220a223-ffffffff8220a238: cmos_set_alarm_callback.cold (STB_LOCAL)
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
