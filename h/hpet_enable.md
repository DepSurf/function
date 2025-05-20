# Function: <code>hpet_enable</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int hpet_enable();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff81f73f59)
Location: arch/x86/kernel/hpet.c:817
Inline: True
Direct callers:
  - arch/x86/kernel/time.c:hpet_time_init
```
**Symbols:**

```
ffffffff81f73f59-ffffffff81f741fe: hpet_enable.part.13 (STB_LOCAL)
ffffffff81f741fe-ffffffff81f7421e: hpet_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int hpet_enable();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff81f9c792)
Location: arch/x86/kernel/hpet.c:811
Inline: True
Direct callers:
  - arch/x86/kernel/time.c:hpet_time_init
```
**Symbols:**

```
ffffffff81f9c792-ffffffff81f9ca58: hpet_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int hpet_enable();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff81fd7cdd)
Location: arch/x86/kernel/hpet.c:906
Inline: True
Direct callers:
  - arch/x86/kernel/time.c:hpet_time_init
```
**Symbols:**

```
ffffffff81fd7cdd-ffffffff81fd7fa3: hpet_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int hpet_enable();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff820b8b16)
Location: arch/x86/kernel/hpet.c:901
Inline: True
Direct callers:
  - arch/x86/kernel/time.c:hpet_time_init
```
**Symbols:**

```
ffffffff820b8b16-ffffffff820b8de0: hpet_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int hpet_enable();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff826bf360)
Location: arch/x86/kernel/hpet.c:901
Inline: True
Direct callers:
  - arch/x86/kernel/time.c:hpet_time_init
```
**Symbols:**

```
ffffffff826bf360-ffffffff826bf62a: hpet_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int hpet_enable();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff826e913f)
Location: arch/x86/kernel/hpet.c:902
Inline: False
Direct callers:
  - arch/x86/kernel/time.c:hpet_time_init
  - arch/x86/kernel/hpet.c:hpet_late_init
```
**Symbols:**

```
ffffffff826e913f-ffffffff826e9405: hpet_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int hpet_enable();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff8289fcfb)
Location: arch/x86/kernel/hpet.c:898
Inline: False
Direct callers:
  - arch/x86/kernel/time.c:hpet_time_init
  - arch/x86/kernel/hpet.c:hpet_late_init
```
**Symbols:**

```
ffffffff8289fcfb-ffffffff8289ffc1: hpet_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int hpet_enable();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff828b7d13)
Location: arch/x86/kernel/hpet.c:812
Inline: False
Direct callers:
  - arch/x86/kernel/time.c:hpet_time_init
  - arch/x86/kernel/hpet.c:hpet_late_init
```
**Symbols:**

```
ffffffff828b7d13-ffffffff828b80b2: hpet_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int hpet_enable();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff828be211)
Location: arch/x86/kernel/hpet.c:812
Inline: False
Direct callers:
  - arch/x86/kernel/time.c:hpet_time_init
  - arch/x86/kernel/hpet.c:hpet_late_init
```
**Symbols:**

```
ffffffff828be211-ffffffff828be5b0: hpet_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int hpet_enable();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff82ce27a1)
Location: arch/x86/kernel/hpet.c:812
Inline: False
Direct callers:
  - arch/x86/kernel/time.c:hpet_time_init
  - arch/x86/kernel/hpet.c:hpet_late_init
```
**Symbols:**

```
ffffffff82ce27a1-ffffffff82ce2a59: hpet_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int hpet_enable();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff82fcfa3e)
Location: arch/x86/kernel/hpet.c:922
Inline: False
Direct callers:
  - arch/x86/kernel/time.c:hpet_time_init
  - arch/x86/kernel/hpet.c:hpet_late_init
```
**Symbols:**

```
ffffffff82fcfa3e-ffffffff82fcfcf6: hpet_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int hpet_enable();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff831da534)
Location: arch/x86/kernel/hpet.c:922
Inline: False
Direct callers:
  - arch/x86/kernel/time.c:hpet_time_init
  - arch/x86/kernel/hpet.c:hpet_late_init
```
**Symbols:**

```
ffffffff831da534-ffffffff831da8e2: hpet_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int hpet_enable();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff832bd631)
Location: arch/x86/kernel/hpet.c:1000
Inline: False
Direct callers:
  - arch/x86/kernel/time.c:hpet_time_init
  - arch/x86/kernel/hpet.c:hpet_late_init
```
**Symbols:**

```
ffffffff832bd631-ffffffff832bdb02: hpet_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int hpet_enable();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff8346f025)
Location: arch/x86/kernel/hpet.c:1000
Inline: False
Direct callers:
  - arch/x86/kernel/time.c:hpet_time_init
  - arch/x86/kernel/hpet.c:hpet_late_init
```
**Symbols:**

```
ffffffff8346f025-ffffffff8346f503: hpet_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int hpet_enable();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff83e956a0)
Location: arch/x86/kernel/hpet.c:1000
Inline: False
Direct callers:
  - arch/x86/kernel/time.c:hpet_time_init
  - arch/x86/kernel/hpet.c:hpet_late_init
```
**Symbols:**

```
ffffffff83e956a0-ffffffff83e95b32: hpet_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int hpet_enable();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff836b9210)
Location: arch/x86/kernel/hpet.c:1000
Inline: False
Direct callers:
  - arch/x86/kernel/time.c:hpet_time_init
  - arch/x86/kernel/hpet.c:hpet_late_init
```
**Symbols:**

```
ffffffff836b9210-ffffffff836b96b3: hpet_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int hpet_enable();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff838e9ae0)
Location: arch/x86/kernel/hpet.c:1000
Inline: False
Direct callers:
  - arch/x86/kernel/time.c:hpet_time_init
  - arch/x86/kernel/hpet.c:hpet_late_init
```
**Symbols:**

```
ffffffff838e9ae0-ffffffff838e9fe9: hpet_enable (STB_GLOBAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
int hpet_enable();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff828a91e7)
Location: arch/x86/kernel/hpet.c:812
Inline: False
Direct callers:
  - arch/x86/kernel/time.c:hpet_time_init
  - arch/x86/kernel/hpet.c:hpet_late_init
```
**Symbols:**

```
ffffffff828a91e7-ffffffff828a9586: hpet_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int hpet_enable();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff828a1293)
Location: arch/x86/kernel/hpet.c:812
Inline: False
Direct callers:
  - arch/x86/kernel/time.c:hpet_time_init
  - arch/x86/kernel/hpet.c:hpet_late_init
```
**Symbols:**

```
ffffffff828a1293-ffffffff828a1632: hpet_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int hpet_enable();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff828bc0e6)
Location: arch/x86/kernel/hpet.c:812
Inline: False
Direct callers:
  - arch/x86/kernel/time.c:hpet_time_init
  - arch/x86/kernel/hpet.c:hpet_late_init
```
**Symbols:**

```
ffffffff828bc0e6-ffffffff828bc485: hpet_enable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int hpet_enable();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/hpet.c (ffffffff828bf23e)
Location: arch/x86/kernel/hpet.c:812
Inline: False
Direct callers:
  - arch/x86/kernel/time.c:hpet_time_init
  - arch/x86/kernel/hpet.c:hpet_late_init
```
**Symbols:**

```
ffffffff828bf23e-ffffffff828bf5dd: hpet_enable (STB_GLOBAL)
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
No changes between <code>4.15</code> and <code>4.18</code> ✅
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
