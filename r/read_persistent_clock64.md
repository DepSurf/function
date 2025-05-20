# Function: <code>read_persistent_clock64</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void read_persistent_clock64(struct timespec *ts64);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff810f5bf0)
Location: kernel/time/timekeeping.c:1428
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_init
```
**Symbols:**

```
ffffffff810f5bf0-ffffffff810f5c43: read_persistent_clock64 (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void read_persistent_clock64(struct timespec *ts64);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff810fce10)
Location: kernel/time/timekeeping.c:1433
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timekeeping.c:timekeeping_init
```
**Symbols:**

```
ffffffff810fce10-ffffffff810fce63: read_persistent_clock64 (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void read_persistent_clock64(struct timespec *ts64);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff810ffc30)
Location: kernel/time/timekeeping.c:1462
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timekeeping.c:timekeeping_init
```
**Symbols:**

```
ffffffff810ffc30-ffffffff810ffc83: read_persistent_clock64 (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void read_persistent_clock64(struct timespec *ts64);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff81101e10)
Location: kernel/time/timekeeping.c:1454
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timekeeping.c:timekeeping_init
```
**Symbols:**

```
ffffffff81101e10-ffffffff81101e63: read_persistent_clock64 (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void read_persistent_clock64(struct timespec *ts64);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff8110cd70)
Location: kernel/time/timekeeping.c:1489
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timekeeping.c:timekeeping_init
```
**Symbols:**

```
ffffffff8110cd70-ffffffff8110cdc3: read_persistent_clock64 (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void read_persistent_clock64(struct timespec64 *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/rtc.c (ffffffff81038f60)
Location: arch/x86/kernel/rtc.c:154
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timekeeping.c:timekeeping_init
```
**Symbols:**

```
ffffffff81038f60-ffffffff81038f77: read_persistent_clock64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void read_persistent_clock64(struct timespec64 *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/rtc.c (ffffffff8103a170)
Location: arch/x86/kernel/rtc.c:154
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timekeeping.c:read_persistent_wall_and_boot_offset
```
**Symbols:**

```
ffffffff8103a170-ffffffff8103a187: read_persistent_clock64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void read_persistent_clock64(struct timespec64 *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/rtc.c (ffffffff8103c750)
Location: arch/x86/kernel/rtc.c:154
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timekeeping.c:read_persistent_wall_and_boot_offset
```
**Symbols:**

```
ffffffff8103c750-ffffffff8103c767: read_persistent_clock64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void read_persistent_clock64(struct timespec64 *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/rtc.c (ffffffff8103cf10)
Location: arch/x86/kernel/rtc.c:154
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timekeeping.c:read_persistent_wall_and_boot_offset
```
**Symbols:**

```
ffffffff8103cf10-ffffffff8103cf27: read_persistent_clock64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void read_persistent_clock64(struct timespec64 *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/rtc.c (ffffffff8103fd90)
Location: arch/x86/kernel/rtc.c:154
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timekeeping.c:read_persistent_wall_and_boot_offset
```
**Symbols:**

```
ffffffff8103fd90-ffffffff8103fda7: read_persistent_clock64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void read_persistent_clock64(struct timespec64 *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/rtc.c (ffffffff8103fc10)
Location: arch/x86/kernel/rtc.c:154
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timekeeping.c:read_persistent_wall_and_boot_offset
```
**Symbols:**

```
ffffffff8103fc10-ffffffff8103fc27: read_persistent_clock64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void read_persistent_clock64(struct timespec64 *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/rtc.c (ffffffff810415b0)
Location: arch/x86/kernel/rtc.c:154
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timekeeping.c:read_persistent_wall_and_boot_offset
```
**Symbols:**

```
ffffffff810415b0-ffffffff810415c7: read_persistent_clock64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void read_persistent_clock64(struct timespec64 *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/rtc.c (ffffffff81047840)
Location: arch/x86/kernel/rtc.c:154
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timekeeping.c:read_persistent_wall_and_boot_offset
```
**Symbols:**

```
ffffffff81047840-ffffffff81047857: read_persistent_clock64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void read_persistent_clock64(struct timespec64 *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/rtc.c (ffffffff81050730)
Location: arch/x86/kernel/rtc.c:154
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timekeeping.c:read_persistent_wall_and_boot_offset
```
**Symbols:**

```
ffffffff81050730-ffffffff8105074f: read_persistent_clock64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void read_persistent_clock64(struct timespec64 *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/rtc.c (ffffffff8105db10)
Location: arch/x86/kernel/rtc.c:109
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timekeeping.c:read_persistent_wall_and_boot_offset
```
**Symbols:**

```
ffffffff8105db10-ffffffff8105db2f: read_persistent_clock64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void read_persistent_clock64(struct timespec64 *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/rtc.c (ffffffff8105f160)
Location: arch/x86/kernel/rtc.c:109
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timekeeping.c:read_persistent_wall_and_boot_offset
```
**Symbols:**

```
ffffffff8105f160-ffffffff8105f17f: read_persistent_clock64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void read_persistent_clock64(struct timespec64 *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/rtc.c (ffffffff81066210)
Location: arch/x86/kernel/rtc.c:109
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timekeeping.c:read_persistent_wall_and_boot_offset
```
**Symbols:**

```
ffffffff81066210-ffffffff8106622f: read_persistent_clock64 (STB_GLOBAL)
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
void read_persistent_clock64(struct timespec64 *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffff8000101a4e98)
Location: kernel/time/timekeeping.c:1485
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timekeeping.c:read_persistent_wall_and_boot_offset
```
**Symbols:**

```
ffff8000101a4e98-ffff8000101a4ec0: read_persistent_clock64 (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void read_persistent_clock64(struct timespec64 *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm/kernel/time.c (c030f1c0)
Location: arch/arm/kernel/time.c:84
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timekeeping.c:read_persistent_wall_and_boot_offset
```
**Symbols:**

```
c030f1c0-c030f1e8: read_persistent_clock64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void read_persistent_clock64(struct timespec64 *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/powerpc/kernel/time.c (c00000000002bfc0)
Location: arch/powerpc/kernel/time.c:862
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timekeeping.c:read_persistent_wall_and_boot_offset
```
**Symbols:**

```
c00000000002bfc0-c00000000002c100: read_persistent_clock64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void read_persistent_clock64(struct timespec64 *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffe00013144c)
Location: kernel/time/timekeeping.c:1485
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timekeeping.c:read_persistent_wall_and_boot_offset
```
**Symbols:**

```
ffffffe00013144c-ffffffe000131474: read_persistent_clock64 (STB_WEAK)
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
void read_persistent_clock64(struct timespec64 *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/rtc.c (ffffffff8103d090)
Location: arch/x86/kernel/rtc.c:154
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timekeeping.c:read_persistent_wall_and_boot_offset
```
**Symbols:**

```
ffffffff8103d090-ffffffff8103d0a7: read_persistent_clock64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void read_persistent_clock64(struct timespec64 *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/rtc.c (ffffffff8102c720)
Location: arch/x86/kernel/rtc.c:154
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timekeeping.c:read_persistent_wall_and_boot_offset
```
**Symbols:**

```
ffffffff8102c720-ffffffff8102c737: read_persistent_clock64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void read_persistent_clock64(struct timespec64 *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/rtc.c (ffffffff8103ced0)
Location: arch/x86/kernel/rtc.c:154
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timekeeping.c:read_persistent_wall_and_boot_offset
```
**Symbols:**

```
ffffffff8103ced0-ffffffff8103cee7: read_persistent_clock64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void read_persistent_clock64(struct timespec64 *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/rtc.c (ffffffff8103df60)
Location: arch/x86/kernel/rtc.c:154
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_resume
  - kernel/time/timekeeping.c:read_persistent_wall_and_boot_offset
```
**Symbols:**

```
ffffffff8103df60-ffffffff8103df77: read_persistent_clock64 (STB_GLOBAL)
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
<b>Param added. </b>
<code>struct timespec64 *ts</code>
</li>
<li>
<b>Param removed. </b>
<code>struct timespec *ts64</code>
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
