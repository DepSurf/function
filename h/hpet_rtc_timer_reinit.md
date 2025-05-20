# Function: <code>hpet_rtc_timer_reinit</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff810626b6)
Location: arch/x86/kernel/hpet.c:1207
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_rtc_interrupt
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff810624f2)
Location: arch/x86/kernel/hpet.c:1204
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_rtc_interrupt
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff81065562)
Location: arch/x86/kernel/hpet.c:1299
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_rtc_interrupt
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff81064499)
Location: arch/x86/kernel/hpet.c:1294
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_rtc_interrupt
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff81068619)
Location: arch/x86/kernel/hpet.c:1294
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_rtc_interrupt
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff8106b169)
Location: arch/x86/kernel/hpet.c:1294
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_rtc_interrupt
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff81070ef9)
Location: arch/x86/kernel/hpet.c:1290
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_rtc_interrupt
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff81074e7a)
Location: arch/x86/kernel/hpet.c:1208
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_rtc_interrupt
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff81075e4a)
Location: arch/x86/kernel/hpet.c:1208
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_rtc_interrupt
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void hpet_rtc_timer_reinit();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/hpet.c (0)
Location: arch/x86/kernel/hpet.c:1208
Inline: False
Direct callers:
  - arch/x86/kernel/hpet.c:hpet_rtc_interrupt
```
**Symbols:**

```
ffffffff8107cd40-ffffffff8107ce19: hpet_rtc_timer_reinit (STB_LOCAL)
ffffffff8107da90-ffffffff8107daa4: hpet_rtc_timer_reinit.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void hpet_rtc_timer_reinit();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/hpet.c (0)
Location: arch/x86/kernel/hpet.c:1318
Inline: False
Direct callers:
  - arch/x86/kernel/hpet.c:hpet_rtc_interrupt
```
**Symbols:**

```
ffffffff8107cc70-ffffffff8107cd40: hpet_rtc_timer_reinit (STB_LOCAL)
ffffffff81bd7e2d-ffffffff81bd7e41: hpet_rtc_timer_reinit.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (0)
Location: arch/x86/kernel/hpet.c:1318
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_rtc_interrupt
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (0)
Location: arch/x86/kernel/hpet.c:1399
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_rtc_interrupt
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff8109d0f0)
Location: arch/x86/kernel/hpet.c:1399
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_rtc_interrupt
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff810b4190)
Location: arch/x86/kernel/hpet.c:1399
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_rtc_interrupt
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff810b7290)
Location: arch/x86/kernel/hpet.c:1401
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_rtc_interrupt
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff810be6d0)
Location: arch/x86/kernel/hpet.c:1401
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_rtc_interrupt
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
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff81074e4a)
Location: arch/x86/kernel/hpet.c:1208
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_rtc_interrupt
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff81064e7a)
Location: arch/x86/kernel/hpet.c:1208
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_rtc_interrupt
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff81074dfa)
Location: arch/x86/kernel/hpet.c:1208
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_rtc_interrupt
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff81076e5a)
Location: arch/x86/kernel/hpet.c:1208
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_rtc_interrupt
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
