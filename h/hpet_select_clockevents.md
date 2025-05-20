# Function: <code>hpet_select_clockevents</code>

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
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff828b812e)
Location: arch/x86/kernel/hpet.c:593
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_late_init
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
In arch/x86/kernel/hpet.c (ffffffff828be62c)
Location: arch/x86/kernel/hpet.c:593
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_late_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void hpet_select_clockevents();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff82ce2690)
Location: arch/x86/kernel/hpet.c:593
Inline: False
Direct callers:
  - arch/x86/kernel/hpet.c:hpet_late_init
```
**Symbols:**

```
ffffffff82ce2690-ffffffff82ce27a1: hpet_select_clockevents (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void hpet_select_clockevents();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff82fcf8b4)
Location: arch/x86/kernel/hpet.c:703
Inline: False
Direct callers:
  - arch/x86/kernel/hpet.c:hpet_late_init
```
**Symbols:**

```
ffffffff82fcf8b4-ffffffff82fcfa3e: hpet_select_clockevents (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void hpet_select_clockevents();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff831da2be)
Location: arch/x86/kernel/hpet.c:703
Inline: False
Direct callers:
  - arch/x86/kernel/hpet.c:hpet_late_init
```
**Symbols:**

```
ffffffff831da2be-ffffffff831da534: hpet_select_clockevents (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void hpet_select_clockevents();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff832bd38f)
Location: arch/x86/kernel/hpet.c:704
Inline: False
Direct callers:
  - arch/x86/kernel/hpet.c:hpet_late_init
```
**Symbols:**

```
ffffffff832bd38f-ffffffff832bd631: hpet_select_clockevents (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void hpet_select_clockevents();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff8346ed69)
Location: arch/x86/kernel/hpet.c:704
Inline: False
Direct callers:
  - arch/x86/kernel/hpet.c:hpet_late_init
```
**Symbols:**

```
ffffffff8346ed69-ffffffff8346f025: hpet_select_clockevents (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void hpet_select_clockevents();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff83e95340)
Location: arch/x86/kernel/hpet.c:704
Inline: False
Direct callers:
  - arch/x86/kernel/hpet.c:hpet_late_init
```
**Symbols:**

```
ffffffff83e95340-ffffffff83e9568a: hpet_select_clockevents (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void hpet_select_clockevents();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff836b8ea0)
Location: arch/x86/kernel/hpet.c:704
Inline: False
Direct callers:
  - arch/x86/kernel/hpet.c:hpet_late_init
```
**Symbols:**

```
ffffffff836b8ea0-ffffffff836b91f1: hpet_select_clockevents (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void hpet_select_clockevents();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff838e9750)
Location: arch/x86/kernel/hpet.c:704
Inline: False
Direct callers:
  - arch/x86/kernel/hpet.c:hpet_late_init
```
**Symbols:**

```
ffffffff838e9750-ffffffff838e9ad0: hpet_select_clockevents (STB_LOCAL)
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
In arch/x86/kernel/hpet.c (ffffffff828a9602)
Location: arch/x86/kernel/hpet.c:593
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_late_init
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
In arch/x86/kernel/hpet.c (ffffffff828a16ae)
Location: arch/x86/kernel/hpet.c:593
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_late_init
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
In arch/x86/kernel/hpet.c (ffffffff828bc501)
Location: arch/x86/kernel/hpet.c:593
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_late_init
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
In arch/x86/kernel/hpet.c (ffffffff828bf659)
Location: arch/x86/kernel/hpet.c:593
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_late_init
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
