# Function: <code>calibrate_APIC_clock</code>

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
In arch/x86/kernel/apic/apic.c (ffffffff81f71395)
Location: arch/x86/kernel/apic/apic.c:677
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock
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
In arch/x86/kernel/apic/apic.c (ffffffff81f99b55)
Location: arch/x86/kernel/apic/apic.c:709
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock
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
In arch/x86/kernel/apic/apic.c (ffffffff81fd5031)
Location: arch/x86/kernel/apic/apic.c:710
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock
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
In arch/x86/kernel/apic/apic.c (ffffffff820b5d24)
Location: arch/x86/kernel/apic/apic.c:789
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock
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
In arch/x86/kernel/apic/apic.c (ffffffff826bc52e)
Location: arch/x86/kernel/apic/apic.c:795
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock
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
In arch/x86/kernel/apic/apic.c (ffffffff826e62dc)
Location: arch/x86/kernel/apic/apic.c:799
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock
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
In arch/x86/kernel/apic/apic.c (ffffffff8289ce1f)
Location: arch/x86/kernel/apic/apic.c:805
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int calibrate_APIC_clock();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff828b4aef)
Location: arch/x86/kernel/apic/apic.c:855
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock
```
**Symbols:**

```
ffffffff828b4aef-ffffffff828b4f68: calibrate_APIC_clock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int calibrate_APIC_clock();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff828b7f48)
Location: arch/x86/kernel/apic/apic.c:864
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock
```
**Symbols:**

```
ffffffff828b7f48-ffffffff828b83c5: calibrate_APIC_clock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int calibrate_APIC_clock();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff82cdd14f)
Location: arch/x86/kernel/apic/apic.c:825
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock
```
**Symbols:**

```
ffffffff82cdd14f-ffffffff82cdd595: calibrate_APIC_clock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int calibrate_APIC_clock();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff82fc94e3)
Location: arch/x86/kernel/apic/apic.c:834
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock
```
**Symbols:**

```
ffffffff82fc94e3-ffffffff82fc9929: calibrate_APIC_clock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int calibrate_APIC_clock();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff831d3d3e)
Location: arch/x86/kernel/apic/apic.c:834
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock
```
**Symbols:**

```
ffffffff831d3d3e-ffffffff831d4184: calibrate_APIC_clock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int calibrate_APIC_clock();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff832b68ca)
Location: arch/x86/kernel/apic/apic.c:831
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock
```
**Symbols:**

```
ffffffff832b68ca-ffffffff832b6d10: calibrate_APIC_clock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int calibrate_APIC_clock();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff834683bf)
Location: arch/x86/kernel/apic/apic.c:840
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock
```
**Symbols:**

```
ffffffff834683bf-ffffffff83468815: calibrate_APIC_clock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int calibrate_APIC_clock();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff83e8c880)
Location: arch/x86/kernel/apic/apic.c:841
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock
```
**Symbols:**

```
ffffffff83e8c880-ffffffff83e8ce01: calibrate_APIC_clock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int calibrate_APIC_clock();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff836b0110)
Location: arch/x86/kernel/apic/apic.c:843
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock
```
**Symbols:**

```
ffffffff836b0110-ffffffff836b0691: calibrate_APIC_clock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int calibrate_APIC_clock();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff838e0700)
Location: arch/x86/kernel/apic/apic.c:810
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock
```
**Symbols:**

```
ffffffff838e0700-ffffffff838e0c8a: calibrate_APIC_clock (STB_LOCAL)
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
int calibrate_APIC_clock();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff828a5f4f)
Location: arch/x86/kernel/apic/apic.c:864
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock
```
**Symbols:**

```
ffffffff828a5f4f-ffffffff828a63cc: calibrate_APIC_clock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int calibrate_APIC_clock();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff8289e091)
Location: arch/x86/kernel/apic/apic.c:864
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock
```
**Symbols:**

```
ffffffff8289e091-ffffffff8289e4ed: calibrate_APIC_clock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int calibrate_APIC_clock();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff828b8e5f)
Location: arch/x86/kernel/apic/apic.c:864
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock
```
**Symbols:**

```
ffffffff828b8e5f-ffffffff828b92dc: calibrate_APIC_clock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int calibrate_APIC_clock();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff828b8f60)
Location: arch/x86/kernel/apic/apic.c:864
Inline: False
Direct callers:
  - arch/x86/kernel/apic/apic.c:setup_boot_APIC_clock
```
**Symbols:**

```
ffffffff828b8f60-ffffffff828b93dd: calibrate_APIC_clock (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
