# Function: <code>ptp_clock_adjtime</code>

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
int ptp_clock_adjtime(struct posix_clock *pc, struct timex *tx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ptp/ptp_clock.c (ffffffff817dec50)
Location: drivers/ptp/ptp_clock.c:124
Inline: False
```
**Symbols:**

```
ffffffff817dec50-ffffffff817ded5a: ptp_clock_adjtime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ptp_clock_adjtime(struct posix_clock *pc, struct timex *tx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ptp/ptp_clock.c (ffffffff8180a090)
Location: drivers/ptp/ptp_clock.c:127
Inline: False
```
**Symbols:**

```
ffffffff8180a090-ffffffff8180a19a: ptp_clock_adjtime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ptp_clock_adjtime(struct posix_clock *pc, struct __kernel_timex *tx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ptp/ptp_clock.c (ffffffff8184be10)
Location: drivers/ptp/ptp_clock.c:115
Inline: False
```
**Symbols:**

```
ffffffff8184be10-ffffffff8184bf10: ptp_clock_adjtime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ptp_clock_adjtime(struct posix_clock *pc, struct __kernel_timex *tx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ptp/ptp_clock.c (ffffffff8187d640)
Location: drivers/ptp/ptp_clock.c:115
Inline: False
```
**Symbols:**

```
ffffffff8187d640-ffffffff8187d740: ptp_clock_adjtime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ptp_clock_adjtime(struct posix_clock *pc, struct __kernel_timex *tx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ptp/ptp_clock.c (ffffffff8194ba70)
Location: drivers/ptp/ptp_clock.c:115
Inline: False
```
**Symbols:**

```
ffffffff8194ba70-ffffffff8194bb98: ptp_clock_adjtime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ptp_clock_adjtime(struct posix_clock *pc, struct __kernel_timex *tx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ptp/ptp_clock.c (ffffffff81951480)
Location: drivers/ptp/ptp_clock.c:115
Inline: False
```
**Symbols:**

```
ffffffff81951480-ffffffff819515a8: ptp_clock_adjtime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ptp_clock_adjtime(struct posix_clock *pc, struct __kernel_timex *tx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ptp/ptp_clock.c (ffffffff81935300)
Location: drivers/ptp/ptp_clock.c:115
Inline: False
```
**Symbols:**

```
ffffffff81935300-ffffffff81935430: ptp_clock_adjtime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int ptp_clock_adjtime(struct posix_clock *pc, struct __kernel_timex *tx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ptp/ptp_clock.c (0)
Location: drivers/ptp/ptp_clock.c:100
Inline: False
```
**Symbols:**

```
ffffffff819d8920-ffffffff819d8af4: ptp_clock_adjtime (STB_LOCAL)
ffffffff81d26060-ffffffff81d26075: ptp_clock_adjtime.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int ptp_clock_adjtime(struct posix_clock *pc, struct __kernel_timex *tx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ptp/ptp_clock.c (0)
Location: drivers/ptp/ptp_clock.c:100
Inline: False
```
**Symbols:**

```
ffffffff81b3be20-ffffffff81b3c02a: ptp_clock_adjtime (STB_LOCAL)
ffffffff81ef1e93-ffffffff81ef1ebd: ptp_clock_adjtime.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int ptp_clock_adjtime(struct posix_clock *pc, struct __kernel_timex *tx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ptp/ptp_clock.c (0)
Location: drivers/ptp/ptp_clock.c:100
Inline: False
```
**Symbols:**

```
ffffffff81cd1d70-ffffffff81cd1f59: ptp_clock_adjtime (STB_LOCAL)
ffffffff820a775b-ffffffff820a7785: ptp_clock_adjtime.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int ptp_clock_adjtime(struct posix_clock *pc, struct __kernel_timex *tx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ptp/ptp_clock.c (0)
Location: drivers/ptp/ptp_clock.c:100
Inline: False
```
**Symbols:**

```
ffffffff81d397b0-ffffffff81d399d2: ptp_clock_adjtime (STB_LOCAL)
ffffffff82128b56-ffffffff82128b80: ptp_clock_adjtime.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int ptp_clock_adjtime(struct posix_clock *pc, struct __kernel_timex *tx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ptp/ptp_clock.c (0)
Location: drivers/ptp/ptp_clock.c:102
Inline: False
```
**Symbols:**

```
ffffffff81defb70-ffffffff81defd92: ptp_clock_adjtime (STB_LOCAL)
ffffffff8220a4e8-ffffffff8220a512: ptp_clock_adjtime.cold (STB_LOCAL)
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
int ptp_clock_adjtime(struct posix_clock *pc, struct __kernel_timex *tx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ptp/ptp_clock.c (ffff800010ac6ed8)
Location: drivers/ptp/ptp_clock.c:115
Inline: False
```
**Symbols:**

```
ffff800010ac6ed8-ffff800010ac7000: ptp_clock_adjtime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ptp_clock_adjtime(struct posix_clock *pc, struct __kernel_timex *tx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ptp/ptp_clock.c (c0ba6948)
Location: drivers/ptp/ptp_clock.c:115
Inline: False
```
**Symbols:**

```
c0ba6948-c0ba6a80: ptp_clock_adjtime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ptp_clock_adjtime(struct posix_clock *pc, struct __kernel_timex *tx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ptp/ptp_clock.c (c000000000ba85d0)
Location: drivers/ptp/ptp_clock.c:115
Inline: False
```
**Symbols:**

```
c000000000ba85d0-c000000000ba877c: ptp_clock_adjtime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ptp_clock_adjtime(struct posix_clock *pc, struct __kernel_timex *tx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ptp/ptp_clock.c (ffffffe0006c5948)
Location: drivers/ptp/ptp_clock.c:115
Inline: False
```
**Symbols:**

```
ffffffe0006c5948-ffffffe0006c5a2c: ptp_clock_adjtime (STB_LOCAL)
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
int ptp_clock_adjtime(struct posix_clock *pc, struct __kernel_timex *tx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ptp/ptp_clock.c (ffffffff81825bb0)
Location: drivers/ptp/ptp_clock.c:115
Inline: False
```
**Symbols:**

```
ffffffff81825bb0-ffffffff81825cb0: ptp_clock_adjtime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ptp_clock_adjtime(struct posix_clock *pc, struct __kernel_timex *tx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ptp/ptp_clock.c (ffffffff817ed240)
Location: drivers/ptp/ptp_clock.c:115
Inline: False
```
**Symbols:**

```
ffffffff817ed240-ffffffff817ed340: ptp_clock_adjtime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ptp_clock_adjtime(struct posix_clock *pc, struct __kernel_timex *tx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ptp/ptp_clock.c (ffffffff81872af0)
Location: drivers/ptp/ptp_clock.c:115
Inline: False
```
**Symbols:**

```
ffffffff81872af0-ffffffff81872bf0: ptp_clock_adjtime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ptp_clock_adjtime(struct posix_clock *pc, struct __kernel_timex *tx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ptp/ptp_clock.c (ffffffff8188e4a0)
Location: drivers/ptp/ptp_clock.c:115
Inline: False
```
**Symbols:**

```
ffffffff8188e4a0-ffffffff8188e5a0: ptp_clock_adjtime (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct timex *tx</code> ➡️ <code>struct __kernel_timex *tx</code>
</li>
</ul>
</details>
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
