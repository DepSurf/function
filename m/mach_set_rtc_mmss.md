# Function: <code>mach_set_rtc_mmss</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int mach_set_rtc_mmss(const struct timespec *now);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/rtc.c (ffffffff81038810)
Location: arch/x86/kernel/rtc.c:41
Inline: False
```
**Symbols:**

```
ffffffff81038810-ffffffff81038a98: mach_set_rtc_mmss (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int mach_set_rtc_mmss(const struct timespec *now);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/rtc.c (ffffffff81037a70)
Location: arch/x86/kernel/rtc.c:41
Inline: False
```
**Symbols:**

```
ffffffff81037a70-ffffffff81037b09: mach_set_rtc_mmss (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int mach_set_rtc_mmss(const struct timespec *now);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/rtc.c (ffffffff81037830)
Location: arch/x86/kernel/rtc.c:41
Inline: False
```
**Symbols:**

```
ffffffff81037830-ffffffff810378c9: mach_set_rtc_mmss (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int mach_set_rtc_mmss(const struct timespec *now);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/rtc.c (ffffffff810358e0)
Location: arch/x86/kernel/rtc.c:41
Inline: False
```
**Symbols:**

```
ffffffff810358e0-ffffffff81035979: mach_set_rtc_mmss (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int mach_set_rtc_mmss(const struct timespec *now);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/rtc.c (ffffffff81037c00)
Location: arch/x86/kernel/rtc.c:42
Inline: False
```
**Symbols:**

```
ffffffff81037c00-ffffffff81037c99: mach_set_rtc_mmss (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int mach_set_rtc_mmss(const struct timespec64 *now);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/rtc.c (0)
Location: arch/x86/kernel/rtc.c:42
Inline: False
```
**Symbols:**

```
ffffffff81038f77-ffffffff81038fb1: mach_set_rtc_mmss.cold.0 (STB_LOCAL)
ffffffff81038d30-ffffffff81038d9d: mach_set_rtc_mmss (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int mach_set_rtc_mmss(const struct timespec64 *now);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/rtc.c (0)
Location: arch/x86/kernel/rtc.c:42
Inline: False
```
**Symbols:**

```
ffffffff8103a187-ffffffff8103a1c1: mach_set_rtc_mmss.cold.0 (STB_LOCAL)
ffffffff81039f40-ffffffff81039fad: mach_set_rtc_mmss (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int mach_set_rtc_mmss(const struct timespec64 *now);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/rtc.c (0)
Location: arch/x86/kernel/rtc.c:42
Inline: False
```
**Symbols:**

```
ffffffff8103c767-ffffffff8103c7a2: mach_set_rtc_mmss.cold (STB_LOCAL)
ffffffff8103c500-ffffffff8103c571: mach_set_rtc_mmss (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int mach_set_rtc_mmss(const struct timespec64 *now);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/rtc.c (0)
Location: arch/x86/kernel/rtc.c:42
Inline: False
```
**Symbols:**

```
ffffffff8103cf27-ffffffff8103cf62: mach_set_rtc_mmss.cold (STB_LOCAL)
ffffffff8103ccc0-ffffffff8103cd31: mach_set_rtc_mmss (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int mach_set_rtc_mmss(const struct timespec64 *now);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/rtc.c (0)
Location: arch/x86/kernel/rtc.c:42
Inline: False
```
**Symbols:**

```
ffffffff8103fda7-ffffffff8103fde2: mach_set_rtc_mmss.cold (STB_LOCAL)
ffffffff8103fb50-ffffffff8103fbbf: mach_set_rtc_mmss (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int mach_set_rtc_mmss(const struct timespec64 *now);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/rtc.c (0)
Location: arch/x86/kernel/rtc.c:42
Inline: False
```
**Symbols:**

```
ffffffff81bd4449-ffffffff81bd4484: mach_set_rtc_mmss.cold (STB_LOCAL)
ffffffff8103f9d0-ffffffff8103fa3f: mach_set_rtc_mmss (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int mach_set_rtc_mmss(const struct timespec64 *now);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/rtc.c (0)
Location: arch/x86/kernel/rtc.c:42
Inline: False
```
**Symbols:**

```
ffffffff81bc6968-ffffffff81bc69a3: mach_set_rtc_mmss.cold (STB_LOCAL)
ffffffff81041370-ffffffff810413df: mach_set_rtc_mmss (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int mach_set_rtc_mmss(const struct timespec64 *now);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/rtc.c (0)
Location: arch/x86/kernel/rtc.c:42
Inline: False
```
**Symbols:**

```
ffffffff81c99c6b-ffffffff81c99ca6: mach_set_rtc_mmss.cold (STB_LOCAL)
ffffffff810475f0-ffffffff8104765f: mach_set_rtc_mmss (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int mach_set_rtc_mmss(const struct timespec64 *now);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/rtc.c (0)
Location: arch/x86/kernel/rtc.c:42
Inline: False
```
**Symbols:**

```
ffffffff81e49752-ffffffff81e4978c: mach_set_rtc_mmss.cold (STB_LOCAL)
ffffffff81050490-ffffffff8105052d: mach_set_rtc_mmss (STB_GLOBAL)
```
</details>
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
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int mach_set_rtc_mmss(const struct timespec64 *now);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/rtc.c (0)
Location: arch/x86/kernel/rtc.c:42
Inline: False
```
**Symbols:**

```
ffffffff8103d0a7-ffffffff8103d0e2: mach_set_rtc_mmss.cold (STB_LOCAL)
ffffffff8103ce40-ffffffff8103ceb1: mach_set_rtc_mmss (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int mach_set_rtc_mmss(const struct timespec64 *now);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/rtc.c (0)
Location: arch/x86/kernel/rtc.c:42
Inline: False
```
**Symbols:**

```
ffffffff8102c737-ffffffff8102c772: mach_set_rtc_mmss.cold (STB_LOCAL)
ffffffff8102c4d0-ffffffff8102c541: mach_set_rtc_mmss (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int mach_set_rtc_mmss(const struct timespec64 *now);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/rtc.c (0)
Location: arch/x86/kernel/rtc.c:42
Inline: False
```
**Symbols:**

```
ffffffff8103cee7-ffffffff8103cf22: mach_set_rtc_mmss.cold (STB_LOCAL)
ffffffff8103cc80-ffffffff8103ccf1: mach_set_rtc_mmss (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int mach_set_rtc_mmss(const struct timespec64 *now);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/rtc.c (0)
Location: arch/x86/kernel/rtc.c:42
Inline: False
```
**Symbols:**

```
ffffffff8103df77-ffffffff8103dfb2: mach_set_rtc_mmss.cold (STB_LOCAL)
ffffffff8103dd10-ffffffff8103dd81: mach_set_rtc_mmss (STB_GLOBAL)
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
<code>const struct timespec *now</code> ➡️ <code>const struct timespec64 *now</code>
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
