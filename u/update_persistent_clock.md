# Function: <code>update_persistent_clock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int update_persistent_clock(struct timespec now);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/rtc.c (ffffffff81038c40)
Location: arch/x86/kernel/rtc.c:138
Inline: False
Direct callers:
  - kernel/time/ntp.c:update_persistent_clock64
```
**Symbols:**

```
ffffffff81038c40-ffffffff81038c61: update_persistent_clock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int update_persistent_clock(struct timespec now);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/rtc.c (ffffffff81037cb0)
Location: arch/x86/kernel/rtc.c:138
Inline: False
Direct callers:
  - kernel/time/ntp.c:update_persistent_clock64
```
**Symbols:**

```
ffffffff81037cb0-ffffffff81037cd1: update_persistent_clock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int update_persistent_clock(struct timespec now);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/rtc.c (ffffffff81037a90)
Location: arch/x86/kernel/rtc.c:147
Inline: False
Direct callers:
  - kernel/time/ntp.c:update_persistent_clock64
```
**Symbols:**

```
ffffffff81037a90-ffffffff81037ab1: update_persistent_clock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int update_persistent_clock(struct timespec now);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/rtc.c (ffffffff81035b00)
Location: arch/x86/kernel/rtc.c:147
Inline: False
Direct callers:
  - kernel/time/ntp.c:update_persistent_clock64
```
**Symbols:**

```
ffffffff81035b00-ffffffff81035b29: update_persistent_clock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int update_persistent_clock(struct timespec now);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/rtc.c (ffffffff81037e20)
Location: arch/x86/kernel/rtc.c:148
Inline: False
Direct callers:
  - kernel/time/ntp.c:update_persistent_clock64
```
**Symbols:**

```
ffffffff81037e20-ffffffff81037e4f: update_persistent_clock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int update_persistent_clock(struct timespec now);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/ntp.c (ffffffff81119d50)
Location: kernel/time/ntp.c:558
Inline: False
Direct callers:
  - kernel/time/ntp.c:update_persistent_clock64
```
**Symbols:**

```
ffffffff81119d50-ffffffff81119d60: update_persistent_clock (STB_WEAK)
```
</details>
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
</ul>
