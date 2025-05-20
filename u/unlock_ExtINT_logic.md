# Function: <code>unlock_ExtINT_logic</code>

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
In arch/x86/kernel/apic/io_apic.c (ffffffff81f72c14)
Location: arch/x86/kernel/apic/io_apic.c:1960
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
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
In arch/x86/kernel/apic/io_apic.c (ffffffff81f9b43c)
Location: arch/x86/kernel/apic/io_apic.c:1961
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
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
In arch/x86/kernel/apic/io_apic.c (ffffffff81fd6985)
Location: arch/x86/kernel/apic/io_apic.c:1960
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
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
In arch/x86/kernel/apic/io_apic.c (ffffffff820b76e5)
Location: arch/x86/kernel/apic/io_apic.c:1940
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
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
In arch/x86/kernel/apic/io_apic.c (ffffffff826be092)
Location: arch/x86/kernel/apic/io_apic.c:1993
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
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
In arch/x86/kernel/apic/io_apic.c (ffffffff826e7e4b)
Location: arch/x86/kernel/apic/io_apic.c:1986
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
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
In arch/x86/kernel/apic/io_apic.c (ffffffff8289e994)
Location: arch/x86/kernel/apic/io_apic.c:1986
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
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
In arch/x86/kernel/apic/io_apic.c (ffffffff828b687c)
Location: arch/x86/kernel/apic/io_apic.c:2035
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
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
In arch/x86/kernel/apic/io_apic.c (ffffffff828b9d3f)
Location: arch/x86/kernel/apic/io_apic.c:2038
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void unlock_ExtINT_logic();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff82cdeba6)
Location: arch/x86/kernel/apic/io_apic.c:2025
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
```
**Symbols:**

```
ffffffff82cdeba6-ffffffff82cded30: unlock_ExtINT_logic (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void unlock_ExtINT_logic();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff82fcaf49)
Location: arch/x86/kernel/apic/io_apic.c:2073
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
```
**Symbols:**

```
ffffffff82fcaf49-ffffffff82fcb0da: unlock_ExtINT_logic (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void unlock_ExtINT_logic();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff831d57e0)
Location: arch/x86/kernel/apic/io_apic.c:2075
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
```
**Symbols:**

```
ffffffff831d57e0-ffffffff831d5971: unlock_ExtINT_logic (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void unlock_ExtINT_logic();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff832b8415)
Location: arch/x86/kernel/apic/io_apic.c:2075
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
```
**Symbols:**

```
ffffffff832b8415-ffffffff832b85a6: unlock_ExtINT_logic (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void unlock_ExtINT_logic();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff8346a148)
Location: arch/x86/kernel/apic/io_apic.c:2076
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
```
**Symbols:**

```
ffffffff8346a148-ffffffff8346a2e9: unlock_ExtINT_logic (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void unlock_ExtINT_logic();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff83e8f020)
Location: arch/x86/kernel/apic/io_apic.c:2076
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
```
**Symbols:**

```
ffffffff83e8f020-ffffffff83e8f21f: unlock_ExtINT_logic (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void unlock_ExtINT_logic();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff836b28c0)
Location: arch/x86/kernel/apic/io_apic.c:2077
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
```
**Symbols:**

```
ffffffff836b28c0-ffffffff836b2abf: unlock_ExtINT_logic (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void unlock_ExtINT_logic();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/io_apic.c (ffffffff838e31a0)
Location: arch/x86/kernel/apic/io_apic.c:2073
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
```
**Symbols:**

```
ffffffff838e31a0-ffffffff838e33b6: unlock_ExtINT_logic (STB_LOCAL)
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
In arch/x86/kernel/apic/io_apic.c (ffffffff828a7d57)
Location: arch/x86/kernel/apic/io_apic.c:2044
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
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
In arch/x86/kernel/apic/io_apic.c (ffffffff8289fe15)
Location: arch/x86/kernel/apic/io_apic.c:2038
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
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
In arch/x86/kernel/apic/io_apic.c (ffffffff828bac56)
Location: arch/x86/kernel/apic/io_apic.c:2038
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
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
In arch/x86/kernel/apic/io_apic.c (ffffffff828bad6c)
Location: arch/x86/kernel/apic/io_apic.c:2038
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
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
