# Function: <code>ptp_clock_settime</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int ptp_clock_settime(struct posix_clock *pc, const struct timespec64 *tp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ptp/ptp_clock.c (ffffffff817dec10)
Location: drivers/ptp/ptp_clock.c:108
Inline: False
```
**Symbols:**

```
ffffffff817dec10-ffffffff817dec2b: ptp_clock_settime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ptp_clock_settime(struct posix_clock *pc, const struct timespec64 *tp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ptp/ptp_clock.c (ffffffff8180a040)
Location: drivers/ptp/ptp_clock.c:108
Inline: False
```
**Symbols:**

```
ffffffff8180a040-ffffffff8180a05b: ptp_clock_settime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ptp_clock_settime(struct posix_clock *pc, const struct timespec64 *tp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ptp/ptp_clock.c (ffffffff8184bd30)
Location: drivers/ptp/ptp_clock.c:96
Inline: False
```
**Symbols:**

```
ffffffff8184bd30-ffffffff8184bd4b: ptp_clock_settime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ptp_clock_settime(struct posix_clock *pc, const struct timespec64 *tp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ptp/ptp_clock.c (ffffffff8187d540)
Location: drivers/ptp/ptp_clock.c:96
Inline: False
```
**Symbols:**

```
ffffffff8187d540-ffffffff8187d55b: ptp_clock_settime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ptp_clock_settime(struct posix_clock *pc, const struct timespec64 *tp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ptp/ptp_clock.c (ffffffff8194b910)
Location: drivers/ptp/ptp_clock.c:96
Inline: False
```
**Symbols:**

```
ffffffff8194b910-ffffffff8194b92b: ptp_clock_settime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ptp_clock_settime(struct posix_clock *pc, const struct timespec64 *tp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ptp/ptp_clock.c (ffffffff81951320)
Location: drivers/ptp/ptp_clock.c:96
Inline: False
```
**Symbols:**

```
ffffffff81951320-ffffffff8195133b: ptp_clock_settime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ptp_clock_settime(struct posix_clock *pc, const struct timespec64 *tp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ptp/ptp_clock.c (ffffffff819351a0)
Location: drivers/ptp/ptp_clock.c:96
Inline: False
```
**Symbols:**

```
ffffffff819351a0-ffffffff819351bb: ptp_clock_settime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int ptp_clock_settime(struct posix_clock *pc, const struct timespec64 *tp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ptp/ptp_clock.c (0)
Location: drivers/ptp/ptp_clock.c:76
Inline: False
```
**Symbols:**

```
ffffffff819d9010-ffffffff819d909a: ptp_clock_settime (STB_LOCAL)
ffffffff81d260bb-ffffffff81d260d0: ptp_clock_settime.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int ptp_clock_settime(struct posix_clock *pc, const struct timespec64 *tp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ptp/ptp_clock.c (0)
Location: drivers/ptp/ptp_clock.c:76
Inline: False
```
**Symbols:**

```
ffffffff81b3c660-ffffffff81b3c70c: ptp_clock_settime (STB_LOCAL)
ffffffff81ef1f18-ffffffff81ef1f42: ptp_clock_settime.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int ptp_clock_settime(struct posix_clock *pc, const struct timespec64 *tp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ptp/ptp_clock.c (0)
Location: drivers/ptp/ptp_clock.c:76
Inline: False
```
**Symbols:**

```
ffffffff81cd2600-ffffffff81cd26a9: ptp_clock_settime (STB_LOCAL)
ffffffff820a77ae-ffffffff820a77d8: ptp_clock_settime.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int ptp_clock_settime(struct posix_clock *pc, const struct timespec64 *tp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ptp/ptp_clock.c (0)
Location: drivers/ptp/ptp_clock.c:76
Inline: False
```
**Symbols:**

```
ffffffff81d3a080-ffffffff81d3a12c: ptp_clock_settime (STB_LOCAL)
ffffffff82128ba9-ffffffff82128bd3: ptp_clock_settime.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int ptp_clock_settime(struct posix_clock *pc, const struct timespec64 *tp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ptp/ptp_clock.c (0)
Location: drivers/ptp/ptp_clock.c:78
Inline: False
```
**Symbols:**

```
ffffffff81df0630-ffffffff81df06dc: ptp_clock_settime (STB_LOCAL)
ffffffff8220a53b-ffffffff8220a565: ptp_clock_settime.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int ptp_clock_settime(struct posix_clock *pc, const struct timespec64 *tp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ptp/ptp_clock.c (ffff800010ac6d78)
Location: drivers/ptp/ptp_clock.c:96
Inline: False
```
**Symbols:**

```
ffff800010ac6d78-ffff800010ac6db0: ptp_clock_settime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ptp_clock_settime(struct posix_clock *pc, const struct timespec64 *tp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ptp/ptp_clock.c (c0ba683c)
Location: drivers/ptp/ptp_clock.c:96
Inline: False
```
**Symbols:**

```
c0ba683c-c0ba6860: ptp_clock_settime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ptp_clock_settime(struct posix_clock *pc, const struct timespec64 *tp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ptp/ptp_clock.c (c000000000ba8400)
Location: drivers/ptp/ptp_clock.c:96
Inline: False
```
**Symbols:**

```
c000000000ba8400-c000000000ba8444: ptp_clock_settime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ptp_clock_settime(struct posix_clock *pc, const struct timespec64 *tp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ptp/ptp_clock.c (ffffffe0006c5810)
Location: drivers/ptp/ptp_clock.c:96
Inline: False
```
**Symbols:**

```
ffffffe0006c5810-ffffffe0006c5840: ptp_clock_settime (STB_LOCAL)
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
int ptp_clock_settime(struct posix_clock *pc, const struct timespec64 *tp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ptp/ptp_clock.c (ffffffff81825ab0)
Location: drivers/ptp/ptp_clock.c:96
Inline: False
```
**Symbols:**

```
ffffffff81825ab0-ffffffff81825acb: ptp_clock_settime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ptp_clock_settime(struct posix_clock *pc, const struct timespec64 *tp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ptp/ptp_clock.c (ffffffff817ed140)
Location: drivers/ptp/ptp_clock.c:96
Inline: False
```
**Symbols:**

```
ffffffff817ed140-ffffffff817ed15b: ptp_clock_settime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ptp_clock_settime(struct posix_clock *pc, const struct timespec64 *tp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ptp/ptp_clock.c (ffffffff818729f0)
Location: drivers/ptp/ptp_clock.c:96
Inline: False
```
**Symbols:**

```
ffffffff818729f0-ffffffff81872a0b: ptp_clock_settime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ptp_clock_settime(struct posix_clock *pc, const struct timespec64 *tp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ptp/ptp_clock.c (ffffffff8188e3a0)
Location: drivers/ptp/ptp_clock.c:96
Inline: False
```
**Symbols:**

```
ffffffff8188e3a0-ffffffff8188e3bb: ptp_clock_settime (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
