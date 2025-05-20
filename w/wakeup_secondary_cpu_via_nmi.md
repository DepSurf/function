# Function: <code>wakeup_secondary_cpu_via_nmi</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int wakeup_secondary_cpu_via_nmi(int apicid, long unsigned int start_eip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff810518b0)
Location: arch/x86/kernel/smpboot.c:657
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
```
**Symbols:**

```
ffffffff810518b0-ffffffff81051997: wakeup_secondary_cpu_via_nmi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int wakeup_secondary_cpu_via_nmi(int apicid, long unsigned int start_eip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff81051a50)
Location: arch/x86/kernel/smpboot.c:676
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
```
**Symbols:**

```
ffffffff81051a50-ffffffff81051b2c: wakeup_secondary_cpu_via_nmi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int wakeup_secondary_cpu_via_nmi(int apicid, long unsigned int start_eip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff810543a0)
Location: arch/x86/kernel/smpboot.c:700
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
```
**Symbols:**

```
ffffffff810543a0-ffffffff8105447c: wakeup_secondary_cpu_via_nmi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int wakeup_secondary_cpu_via_nmi(int apicid, long unsigned int start_eip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff81053cf0)
Location: arch/x86/kernel/smpboot.c:703
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
```
**Symbols:**

```
ffffffff81053cf0-ffffffff81053dca: wakeup_secondary_cpu_via_nmi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int wakeup_secondary_cpu_via_nmi(int apicid, long unsigned int start_eip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff81057a90)
Location: arch/x86/kernel/smpboot.c:640
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
```
**Symbols:**

```
ffffffff81057a90-ffffffff81057b7c: wakeup_secondary_cpu_via_nmi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int wakeup_secondary_cpu_via_nmi(int apicid, long unsigned int start_eip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/smpboot.c (0)
Location: arch/x86/kernel/smpboot.c:693
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
```
**Symbols:**

```
ffffffff8105b7bf-ffffffff8105b7e3: wakeup_secondary_cpu_via_nmi.cold.9 (STB_LOCAL)
ffffffff8105a7f0-ffffffff8105a8c6: wakeup_secondary_cpu_via_nmi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int wakeup_secondary_cpu_via_nmi(int apicid, long unsigned int start_eip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/smpboot.c (0)
Location: arch/x86/kernel/smpboot.c:694
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
```
**Symbols:**

```
ffffffff81061449-ffffffff8106146d: wakeup_secondary_cpu_via_nmi.cold.11 (STB_LOCAL)
ffffffff81060470-ffffffff81060546: wakeup_secondary_cpu_via_nmi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int wakeup_secondary_cpu_via_nmi(int apicid, long unsigned int start_eip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/smpboot.c (0)
Location: arch/x86/kernel/smpboot.c:746
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:do_boot_cpu
```
**Symbols:**

```
ffffffff81064b34-ffffffff81064b58: wakeup_secondary_cpu_via_nmi.cold (STB_LOCAL)
ffffffff81063d50-ffffffff81063e26: wakeup_secondary_cpu_via_nmi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int wakeup_secondary_cpu_via_nmi(int apicid, long unsigned int start_eip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/smpboot.c (0)
Location: arch/x86/kernel/smpboot.c:746
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:do_boot_cpu
```
**Symbols:**

```
ffffffff810651b4-ffffffff810651d8: wakeup_secondary_cpu_via_nmi.cold (STB_LOCAL)
ffffffff81064400-ffffffff810644d6: wakeup_secondary_cpu_via_nmi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int wakeup_secondary_cpu_via_nmi(int apicid, long unsigned int start_eip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/smpboot.c (0)
Location: arch/x86/kernel/smpboot.c:759
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:do_boot_cpu
```
**Symbols:**

```
ffffffff8106bb05-ffffffff8106bb29: wakeup_secondary_cpu_via_nmi.cold (STB_LOCAL)
ffffffff8106ae60-ffffffff8106af36: wakeup_secondary_cpu_via_nmi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int wakeup_secondary_cpu_via_nmi(int apicid, long unsigned int start_eip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/smpboot.c (0)
Location: arch/x86/kernel/smpboot.c:754
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:do_boot_cpu
```
**Symbols:**

```
ffffffff81bd6a72-ffffffff81bd6a96: wakeup_secondary_cpu_via_nmi.cold (STB_LOCAL)
ffffffff8106cad0-ffffffff8106cbaf: wakeup_secondary_cpu_via_nmi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int wakeup_secondary_cpu_via_nmi(int apicid, long unsigned int start_eip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/smpboot.c (0)
Location: arch/x86/kernel/smpboot.c:755
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:do_boot_cpu
```
**Symbols:**

```
ffffffff81bc8c4c-ffffffff81bc8c70: wakeup_secondary_cpu_via_nmi.cold (STB_LOCAL)
ffffffff8106d570-ffffffff8106d64a: wakeup_secondary_cpu_via_nmi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int wakeup_secondary_cpu_via_nmi(int apicid, long unsigned int start_eip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/smpboot.c (0)
Location: arch/x86/kernel/smpboot.c:757
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:do_boot_cpu
```
**Symbols:**

```
ffffffff81c9d5c2-ffffffff81c9d601: wakeup_secondary_cpu_via_nmi.cold (STB_LOCAL)
ffffffff81078cb0-ffffffff81078d96: wakeup_secondary_cpu_via_nmi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int wakeup_secondary_cpu_via_nmi(int apicid, long unsigned int start_eip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/smpboot.c (0)
Location: arch/x86/kernel/smpboot.c:800
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:do_boot_cpu
```
**Symbols:**

```
ffffffff81e4ca5f-ffffffff81e4ca9e: wakeup_secondary_cpu_via_nmi.cold (STB_LOCAL)
ffffffff81087a90-ffffffff81087b7e: wakeup_secondary_cpu_via_nmi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int wakeup_secondary_cpu_via_nmi(int apicid, long unsigned int start_eip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/smpboot.c (0)
Location: arch/x86/kernel/smpboot.c:798
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:do_boot_cpu
```
**Symbols:**

```
ffffffff82053b94-ffffffff82053baf: wakeup_secondary_cpu_via_nmi.cold (STB_LOCAL)
ffffffff8109b3e0-ffffffff8109b4f9: wakeup_secondary_cpu_via_nmi (STB_GLOBAL)
```
</details>
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
int wakeup_secondary_cpu_via_nmi(int apicid, long unsigned int start_eip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/smpboot.c (0)
Location: arch/x86/kernel/smpboot.c:746
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:do_boot_cpu
```
**Symbols:**

```
ffffffff81064ca4-ffffffff81064cc8: wakeup_secondary_cpu_via_nmi.cold (STB_LOCAL)
ffffffff81063ef0-ffffffff81063fc6: wakeup_secondary_cpu_via_nmi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int wakeup_secondary_cpu_via_nmi(int apicid, long unsigned int start_eip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/smpboot.c (0)
Location: arch/x86/kernel/smpboot.c:746
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:do_boot_cpu
```
**Symbols:**

```
ffffffff81054f79-ffffffff81054f9d: wakeup_secondary_cpu_via_nmi.cold (STB_LOCAL)
ffffffff810541f0-ffffffff810542c6: wakeup_secondary_cpu_via_nmi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int wakeup_secondary_cpu_via_nmi(int apicid, long unsigned int start_eip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/smpboot.c (0)
Location: arch/x86/kernel/smpboot.c:746
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:do_boot_cpu
```
**Symbols:**

```
ffffffff81065154-ffffffff81065178: wakeup_secondary_cpu_via_nmi.cold (STB_LOCAL)
ffffffff810643a0-ffffffff81064476: wakeup_secondary_cpu_via_nmi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int wakeup_secondary_cpu_via_nmi(int apicid, long unsigned int start_eip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/smpboot.c (0)
Location: arch/x86/kernel/smpboot.c:746
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:do_boot_cpu
```
**Symbols:**

```
ffffffff81066734-ffffffff81066758: wakeup_secondary_cpu_via_nmi.cold (STB_LOCAL)
ffffffff81065960-ffffffff81065a36: wakeup_secondary_cpu_via_nmi (STB_GLOBAL)
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
