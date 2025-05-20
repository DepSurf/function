# Function: <code>alarm_clock_get</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int alarm_clock_get(clockid_t which_clock, struct timespec *tp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (ffffffff810fad70)
Location: kernel/time/alarmtimer.c:510
Inline: False
```
**Symbols:**

```
ffffffff810fad70-ffffffff810fadc6: alarm_clock_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int alarm_clock_get(clockid_t which_clock, struct timespec *tp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (ffffffff81102060)
Location: kernel/time/alarmtimer.c:525
Inline: False
```
**Symbols:**

```
ffffffff81102060-ffffffff811020b7: alarm_clock_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int alarm_clock_get(clockid_t which_clock, struct timespec *tp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (ffffffff81104880)
Location: kernel/time/alarmtimer.c:559
Inline: False
```
**Symbols:**

```
ffffffff81104880-ffffffff811048d7: alarm_clock_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int alarm_clock_get(clockid_t which_clock, struct timespec *tp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (ffffffff81106800)
Location: kernel/time/alarmtimer.c:636
Inline: False
```
**Symbols:**

```
ffffffff81106800-ffffffff8110685a: alarm_clock_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int alarm_clock_get(clockid_t which_clock, struct timespec *tp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (ffffffff811118a0)
Location: kernel/time/alarmtimer.c:650
Inline: False
```
**Symbols:**

```
ffffffff811118a0-ffffffff81111900: alarm_clock_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int alarm_clock_get(clockid_t which_clock, struct timespec64 *tp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (ffffffff8111d290)
Location: kernel/time/alarmtimer.c:657
Inline: False
```
**Symbols:**

```
ffffffff8111d290-ffffffff8111d2ec: alarm_clock_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int alarm_clock_get(clockid_t which_clock, struct timespec64 *tp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (ffffffff81128a40)
Location: kernel/time/alarmtimer.c:654
Inline: False
```
**Symbols:**

```
ffffffff81128a40-ffffffff81128a9c: alarm_clock_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int alarm_clock_get(clockid_t which_clock, struct timespec64 *tp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (ffffffff81133490)
Location: kernel/time/alarmtimer.c:653
Inline: False
```
**Symbols:**

```
ffffffff81133490-ffffffff811334ec: alarm_clock_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int alarm_clock_get(clockid_t which_clock, struct timespec64 *tp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (ffffffff8113f3e0)
Location: kernel/time/alarmtimer.c:675
Inline: False
```
**Symbols:**

```
ffffffff8113f3e0-ffffffff8113f43c: alarm_clock_get (STB_LOCAL)
```
</details>
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
int alarm_clock_get(clockid_t which_clock, struct timespec64 *tp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (ffff8000101a9150)
Location: kernel/time/alarmtimer.c:675
Inline: False
```
**Symbols:**

```
ffff8000101a9150-ffff8000101a91d8: alarm_clock_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int alarm_clock_get(clockid_t which_clock, struct timespec64 *tp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (c03f4848)
Location: kernel/time/alarmtimer.c:675
Inline: False
```
**Symbols:**

```
c03f4848-c03f4904: alarm_clock_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int alarm_clock_get(clockid_t which_clock, struct timespec64 *tp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (c00000000020c760)
Location: kernel/time/alarmtimer.c:675
Inline: False
```
**Symbols:**

```
c00000000020c760-c00000000020c814: alarm_clock_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int alarm_clock_get(clockid_t which_clock, struct timespec64 *tp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (ffffffe000134ce4)
Location: kernel/time/alarmtimer.c:675
Inline: False
```
**Symbols:**

```
ffffffe000134ce4-ffffffe000134d5c: alarm_clock_get (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int alarm_clock_get(clockid_t which_clock, struct timespec64 *tp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (ffffffff81137b90)
Location: kernel/time/alarmtimer.c:675
Inline: False
```
**Symbols:**

```
ffffffff81137b90-ffffffff81137bec: alarm_clock_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int alarm_clock_get(clockid_t which_clock, struct timespec64 *tp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (ffffffff8112a5e0)
Location: kernel/time/alarmtimer.c:675
Inline: False
```
**Symbols:**

```
ffffffff8112a5e0-ffffffff8112a63c: alarm_clock_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int alarm_clock_get(clockid_t which_clock, struct timespec64 *tp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (ffffffff811358b0)
Location: kernel/time/alarmtimer.c:675
Inline: False
```
**Symbols:**

```
ffffffff811358b0-ffffffff8113590c: alarm_clock_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int alarm_clock_get(clockid_t which_clock, struct timespec64 *tp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/alarmtimer.c (ffffffff811422e0)
Location: kernel/time/alarmtimer.c:675
Inline: False
```
**Symbols:**

```
ffffffff811422e0-ffffffff8114233c: alarm_clock_get (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct timespec *tp</code> ➡️ <code>struct timespec64 *tp</code>
</li>
</ul>
</details>
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
