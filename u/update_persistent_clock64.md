# Function: <code>update_persistent_clock64</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int update_persistent_clock64(struct timespec now64);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/ntp.c (ffffffff810f7180)
Location: kernel/time/ntp.c:495
Inline: False
```
**Symbols:**

```
ffffffff810f7180-ffffffff810f7190: update_persistent_clock64 (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int update_persistent_clock64(struct timespec now64);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/ntp.c (ffffffff810fe2c0)
Location: kernel/time/ntp.c:501
Inline: False
```
**Symbols:**

```
ffffffff810fe2c0-ffffffff810fe2d0: update_persistent_clock64 (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int update_persistent_clock64(struct timespec now64);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/ntp.c (ffffffff811010b0)
Location: kernel/time/ntp.c:501
Inline: False
```
**Symbols:**

```
ffffffff811010b0-ffffffff811010c0: update_persistent_clock64 (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int update_persistent_clock64(struct timespec now64);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/ntp.c (ffffffff81103210)
Location: kernel/time/ntp.c:501
Inline: False
```
**Symbols:**

```
ffffffff81103210-ffffffff81103224: update_persistent_clock64 (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int update_persistent_clock64(struct timespec now64);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/ntp.c (ffffffff8110e3a0)
Location: kernel/time/ntp.c:563
Inline: False
```
**Symbols:**

```
ffffffff8110e3a0-ffffffff8110e3b4: update_persistent_clock64 (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int update_persistent_clock64(struct timespec64 now);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/rtc.c (ffffffff81038f30)
Location: arch/x86/kernel/rtc.c:148
Inline: False
```
**Symbols:**

```
ffffffff81038f30-ffffffff81038f57: update_persistent_clock64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int update_persistent_clock64(struct timespec64 now);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/rtc.c (ffffffff8103a140)
Location: arch/x86/kernel/rtc.c:148
Inline: False
```
**Symbols:**

```
ffffffff8103a140-ffffffff8103a167: update_persistent_clock64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int update_persistent_clock64(struct timespec64 now);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/rtc.c (ffffffff8103c720)
Location: arch/x86/kernel/rtc.c:148
Inline: False
```
**Symbols:**

```
ffffffff8103c720-ffffffff8103c747: update_persistent_clock64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int update_persistent_clock64(struct timespec64 now);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/rtc.c (ffffffff8103cee0)
Location: arch/x86/kernel/rtc.c:148
Inline: False
```
**Symbols:**

```
ffffffff8103cee0-ffffffff8103cf07: update_persistent_clock64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int update_persistent_clock64(struct timespec64 now);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/rtc.c (ffffffff8103fd60)
Location: arch/x86/kernel/rtc.c:148
Inline: False
Direct callers:
  - kernel/time/ntp.c:sync_cmos_clock
```
**Symbols:**

```
ffffffff8103fd60-ffffffff8103fd87: update_persistent_clock64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int update_persistent_clock64(struct timespec64 now);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/rtc.c (ffffffff8103fbe0)
Location: arch/x86/kernel/rtc.c:148
Inline: False
Direct callers:
  - kernel/time/ntp.c:sync_hw_clock
```
**Symbols:**

```
ffffffff8103fbe0-ffffffff8103fc07: update_persistent_clock64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int update_persistent_clock64(struct timespec64 now);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/rtc.c (ffffffff81041580)
Location: arch/x86/kernel/rtc.c:148
Inline: False
Direct callers:
  - kernel/time/ntp.c:sync_hw_clock
```
**Symbols:**

```
ffffffff81041580-ffffffff810415a7: update_persistent_clock64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int update_persistent_clock64(struct timespec64 now);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/rtc.c (ffffffff81047810)
Location: arch/x86/kernel/rtc.c:148
Inline: False
Direct callers:
  - kernel/time/ntp.c:sync_hw_clock
```
**Symbols:**

```
ffffffff81047810-ffffffff81047837: update_persistent_clock64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int update_persistent_clock64(struct timespec64 now);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/rtc.c (ffffffff81050700)
Location: arch/x86/kernel/rtc.c:148
Inline: False
Direct callers:
  - kernel/time/ntp.c:sync_hw_clock
```
**Symbols:**

```
ffffffff81050700-ffffffff8105072f: update_persistent_clock64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int update_persistent_clock64(struct timespec64 now);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/rtc.c (ffffffff8105dad0)
Location: arch/x86/kernel/rtc.c:103
Inline: False
Direct callers:
  - kernel/time/ntp.c:sync_hw_clock
```
**Symbols:**

```
ffffffff8105dad0-ffffffff8105daff: update_persistent_clock64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int update_persistent_clock64(struct timespec64 now);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/rtc.c (ffffffff8105f120)
Location: arch/x86/kernel/rtc.c:103
Inline: False
Direct callers:
  - kernel/time/ntp.c:sync_hw_clock
```
**Symbols:**

```
ffffffff8105f120-ffffffff8105f14f: update_persistent_clock64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int update_persistent_clock64(struct timespec64 now);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/rtc.c (ffffffff810661d0)
Location: arch/x86/kernel/rtc.c:103
Inline: False
Direct callers:
  - kernel/time/ntp.c:sync_hw_clock
```
**Symbols:**

```
ffffffff810661d0-ffffffff810661ff: update_persistent_clock64 (STB_GLOBAL)
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
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int update_persistent_clock64(struct timespec64 now);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/powerpc/kernel/time.c (c00000000002bf00)
Location: arch/powerpc/kernel/time.c:823
Inline: False
```
**Symbols:**

```
c00000000002bf00-c00000000002bfb4: update_persistent_clock64 (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int update_persistent_clock64(struct timespec64 now);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/rtc.c (ffffffff8103d060)
Location: arch/x86/kernel/rtc.c:148
Inline: False
```
**Symbols:**

```
ffffffff8103d060-ffffffff8103d087: update_persistent_clock64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int update_persistent_clock64(struct timespec64 now);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/rtc.c (ffffffff8102c6f0)
Location: arch/x86/kernel/rtc.c:148
Inline: False
```
**Symbols:**

```
ffffffff8102c6f0-ffffffff8102c717: update_persistent_clock64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int update_persistent_clock64(struct timespec64 now);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/rtc.c (ffffffff8103cea0)
Location: arch/x86/kernel/rtc.c:148
Inline: False
```
**Symbols:**

```
ffffffff8103cea0-ffffffff8103cec7: update_persistent_clock64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int update_persistent_clock64(struct timespec64 now);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/rtc.c (ffffffff8103df30)
Location: arch/x86/kernel/rtc.c:148
Inline: False
```
**Symbols:**

```
ffffffff8103df30-ffffffff8103df57: update_persistent_clock64 (STB_GLOBAL)
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
<code>struct timespec64 now</code>
</li>
<li>
<b>Param removed. </b>
<code>struct timespec now64</code>
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
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
