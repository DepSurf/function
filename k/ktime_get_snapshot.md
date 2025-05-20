# Function: <code>ktime_get_snapshot</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void ktime_get_snapshot(struct system_time_snapshot *systime_snapshot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff810f48a0)
Location: kernel/time/timekeeping.c:882
Inline: False
```
**Symbols:**

```
ffffffff810f48a0-ffffffff810f49f6: ktime_get_snapshot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void ktime_get_snapshot(struct system_time_snapshot *systime_snapshot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff810fb9c0)
Location: kernel/time/timekeeping.c:887
Inline: False
```
**Symbols:**

```
ffffffff810fb9c0-ffffffff810fbb20: ktime_get_snapshot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void ktime_get_snapshot(struct system_time_snapshot *systime_snapshot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff810fe8c0)
Location: kernel/time/timekeeping.c:916
Inline: False
```
**Symbols:**

```
ffffffff810fe8c0-ffffffff810fea20: ktime_get_snapshot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void ktime_get_snapshot(struct system_time_snapshot *systime_snapshot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff81100b40)
Location: kernel/time/timekeeping.c:948
Inline: False
```
**Symbols:**

```
ffffffff81100b40-ffffffff81100c7c: ktime_get_snapshot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void ktime_get_snapshot(struct system_time_snapshot *systime_snapshot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff8110b940)
Location: kernel/time/timekeeping.c:952
Inline: False
```
**Symbols:**

```
ffffffff8110b940-ffffffff8110ba7f: ktime_get_snapshot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void ktime_get_snapshot(struct system_time_snapshot *systime_snapshot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff81117100)
Location: kernel/time/timekeeping.c:953
Inline: False
```
**Symbols:**

```
ffffffff81117100-ffffffff8111723e: ktime_get_snapshot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void ktime_get_snapshot(struct system_time_snapshot *systime_snapshot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff81122740)
Location: kernel/time/timekeeping.c:960
Inline: False
```
**Symbols:**

```
ffffffff81122740-ffffffff8112287e: ktime_get_snapshot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void ktime_get_snapshot(struct system_time_snapshot *systime_snapshot);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff8112d8a0)
Location: kernel/time/timekeeping.c:967
Inline: True
```
**Symbols:**

```
ffffffff8112d8a0-ffffffff8112d9d8: ktime_get_snapshot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void ktime_get_snapshot(struct system_time_snapshot *systime_snapshot);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff81139850)
Location: kernel/time/timekeeping.c:967
Inline: True
```
**Symbols:**

```
ffffffff81139850-ffffffff81139988: ktime_get_snapshot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void ktime_get_snapshot(struct system_time_snapshot *systime_snapshot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff81149100)
Location: kernel/time/timekeeping.c:967
Inline: False
Direct callers:
  - drivers/ptp/ptp_clock.c:ptp_clock_event
```
**Symbols:**

```
ffffffff81149100-ffffffff81149240: ktime_get_snapshot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void ktime_get_snapshot(struct system_time_snapshot *systime_snapshot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff81145570)
Location: kernel/time/timekeeping.c:1036
Inline: False
Direct callers:
  - drivers/ptp/ptp_clock.c:ptp_clock_event
```
**Symbols:**

```
ffffffff81145570-ffffffff811456b0: ktime_get_snapshot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void ktime_get_snapshot(struct system_time_snapshot *systime_snapshot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff81146470)
Location: kernel/time/timekeeping.c:1036
Inline: False
Direct callers:
  - drivers/ptp/ptp_clock.c:ptp_clock_event
```
**Symbols:**

```
ffffffff81146470-ffffffff811465bd: ktime_get_snapshot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void ktime_get_snapshot(struct system_time_snapshot *systime_snapshot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/timekeeping.c (0)
Location: kernel/time/timekeeping.c:1036
Inline: False
Direct callers:
  - drivers/ptp/ptp_clock.c:ptp_clock_event
```
**Symbols:**

```
ffffffff81cb0cb0-ffffffff81cb0d2e: ktime_get_snapshot.cold (STB_LOCAL)
ffffffff811698a0-ffffffff811699ff: ktime_get_snapshot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void ktime_get_snapshot(struct system_time_snapshot *systime_snapshot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/timekeeping.c (0)
Location: kernel/time/timekeeping.c:1055
Inline: False
Direct callers:
  - drivers/ptp/ptp_clock.c:ptp_clock_event
```
**Symbols:**

```
ffffffff81e62224-ffffffff81e62295: ktime_get_snapshot.cold (STB_LOCAL)
ffffffff8119d480-ffffffff8119d5e1: ktime_get_snapshot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void ktime_get_snapshot(struct system_time_snapshot *systime_snapshot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/timekeeping.c (0)
Location: kernel/time/timekeeping.c:1055
Inline: False
Direct callers:
  - drivers/ptp/ptp_clock.c:ptp_clock_event
```
**Symbols:**

```
ffffffff8205b095-ffffffff8205b106: ktime_get_snapshot.cold (STB_LOCAL)
ffffffff811dc0c0-ffffffff811dc221: ktime_get_snapshot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void ktime_get_snapshot(struct system_time_snapshot *systime_snapshot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/timekeeping.c (0)
Location: kernel/time/timekeeping.c:1055
Inline: False
Direct callers:
  - drivers/ptp/ptp_clock.c:ptp_clock_event
```
**Symbols:**

```
ffffffff820d9929-ffffffff820d999a: ktime_get_snapshot.cold (STB_LOCAL)
ffffffff811f04d0-ffffffff811f0631: ktime_get_snapshot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void ktime_get_snapshot(struct system_time_snapshot *systime_snapshot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/time/timekeeping.c (0)
Location: kernel/time/timekeeping.c:1055
Inline: False
Direct callers:
  - drivers/ptp/ptp_clock.c:ptp_clock_event
```
**Symbols:**

```
ffffffff821b5228-ffffffff821b5299: ktime_get_snapshot.cold (STB_LOCAL)
ffffffff81206610-ffffffff81206771: ktime_get_snapshot (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void ktime_get_snapshot(struct system_time_snapshot *systime_snapshot);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffff8000101a39a0)
Location: kernel/time/timekeeping.c:967
Inline: True
```
**Symbols:**

```
ffff8000101a39a0-ffff8000101a3a84: ktime_get_snapshot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void ktime_get_snapshot(struct system_time_snapshot *systime_snapshot);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (c03ed940)
Location: kernel/time/timekeeping.c:967
Inline: True
```
**Symbols:**

```
c03ed940-c03edbb8: ktime_get_snapshot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void ktime_get_snapshot(struct system_time_snapshot *systime_snapshot);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (c000000000204f60)
Location: kernel/time/timekeeping.c:967
Inline: True
```
**Symbols:**

```
c000000000204f60-c0000000002050b8: ktime_get_snapshot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void ktime_get_snapshot(struct system_time_snapshot *systime_snapshot);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffe000130522)
Location: kernel/time/timekeeping.c:967
Inline: True
```
**Symbols:**

```
ffffffe000130522-ffffffe000130600: ktime_get_snapshot (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void ktime_get_snapshot(struct system_time_snapshot *systime_snapshot);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff81132000)
Location: kernel/time/timekeeping.c:967
Inline: True
```
**Symbols:**

```
ffffffff81132000-ffffffff81132138: ktime_get_snapshot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void ktime_get_snapshot(struct system_time_snapshot *systime_snapshot);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff81124a60)
Location: kernel/time/timekeeping.c:967
Inline: True
```
**Symbols:**

```
ffffffff81124a60-ffffffff81124b98: ktime_get_snapshot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void ktime_get_snapshot(struct system_time_snapshot *systime_snapshot);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff8112fd20)
Location: kernel/time/timekeeping.c:967
Inline: True
```
**Symbols:**

```
ffffffff8112fd20-ffffffff8112fe58: ktime_get_snapshot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void ktime_get_snapshot(struct system_time_snapshot *systime_snapshot);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff8113c740)
Location: kernel/time/timekeeping.c:967
Inline: True
```
**Symbols:**

```
ffffffff8113c740-ffffffff8113c878: ktime_get_snapshot (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
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
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
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
