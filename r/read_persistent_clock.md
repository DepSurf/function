# Function: <code>read_persistent_clock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void read_persistent_clock(struct timespec *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/rtc.c (ffffffff81038c70)
Location: arch/x86/kernel/rtc.c:144
Inline: False
```
**Symbols:**

```
ffffffff81038c70-ffffffff81038c81: read_persistent_clock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void read_persistent_clock(struct timespec *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/rtc.c (ffffffff81037ce0)
Location: arch/x86/kernel/rtc.c:144
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:read_persistent_clock64
```
**Symbols:**

```
ffffffff81037ce0-ffffffff81037cf1: read_persistent_clock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void read_persistent_clock(struct timespec *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/rtc.c (ffffffff81037ac0)
Location: arch/x86/kernel/rtc.c:153
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:read_persistent_clock64
```
**Symbols:**

```
ffffffff81037ac0-ffffffff81037ad1: read_persistent_clock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void read_persistent_clock(struct timespec *ts);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/rtc.c (ffffffff81035b30)
Location: arch/x86/kernel/rtc.c:153
Inline: True
Direct callers:
  - kernel/time/timekeeping.c:read_persistent_clock64
```
**Symbols:**

```
ffffffff81035b30-ffffffff81035b41: read_persistent_clock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void read_persistent_clock(struct timespec *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/rtc.c (ffffffff81037e50)
Location: arch/x86/kernel/rtc.c:154
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:read_persistent_clock64
```
**Symbols:**

```
ffffffff81037e50-ffffffff81037e67: read_persistent_clock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void read_persistent_clock(struct timespec *ts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff811188e0)
Location: kernel/time/timekeeping.c:1484
Inline: False
Direct callers:
  - kernel/time/timekeeping.c:read_persistent_clock64
```
**Symbols:**

```
ffffffff811188e0-ffffffff811188fa: read_persistent_clock (STB_WEAK)
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
