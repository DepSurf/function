# Function: <code>wakeup_secondary_cpu_via_init</code>

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
In arch/x86/kernel/smpboot.c (ffffffff81051ffb)
Location: arch/x86/kernel/smpboot.c:691
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
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
In arch/x86/kernel/smpboot.c (ffffffff81052117)
Location: arch/x86/kernel/smpboot.c:710
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
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
In arch/x86/kernel/smpboot.c (ffffffff81054a24)
Location: arch/x86/kernel/smpboot.c:734
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
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
In arch/x86/kernel/smpboot.c (ffffffff8105436e)
Location: arch/x86/kernel/smpboot.c:737
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
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
In arch/x86/kernel/smpboot.c (ffffffff81058160)
Location: arch/x86/kernel/smpboot.c:674
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
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
In arch/x86/kernel/smpboot.c (ffffffff8105ae3a)
Location: arch/x86/kernel/smpboot.c:727
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
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
In arch/x86/kernel/smpboot.c (ffffffff81060aba)
Location: arch/x86/kernel/smpboot.c:728
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int wakeup_secondary_cpu_via_init(int phys_apicid, long unsigned int start_eip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/smpboot.c (0)
Location: arch/x86/kernel/smpboot.c:780
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:do_boot_cpu
```
**Symbols:**

```
ffffffff81063030-ffffffff8106335b: wakeup_secondary_cpu_via_init (STB_LOCAL)
ffffffff81064979-ffffffff810649b1: wakeup_secondary_cpu_via_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int wakeup_secondary_cpu_via_init(int phys_apicid, long unsigned int start_eip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/smpboot.c (0)
Location: arch/x86/kernel/smpboot.c:780
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:do_boot_cpu
```
**Symbols:**

```
ffffffff810636e0-ffffffff81063a0b: wakeup_secondary_cpu_via_init (STB_LOCAL)
ffffffff81064ff9-ffffffff81065031: wakeup_secondary_cpu_via_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int wakeup_secondary_cpu_via_init(int phys_apicid, long unsigned int start_eip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/smpboot.c (0)
Location: arch/x86/kernel/smpboot.c:793
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:do_boot_cpu
```
**Symbols:**

```
ffffffff81069a10-ffffffff81069d3b: wakeup_secondary_cpu_via_init (STB_LOCAL)
ffffffff8106b94c-ffffffff8106b984: wakeup_secondary_cpu_via_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int wakeup_secondary_cpu_via_init(int phys_apicid, long unsigned int start_eip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/smpboot.c (0)
Location: arch/x86/kernel/smpboot.c:789
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:do_boot_cpu
```
**Symbols:**

```
ffffffff8106b6e0-ffffffff8106ba0b: wakeup_secondary_cpu_via_init (STB_LOCAL)
ffffffff81bd68a1-ffffffff81bd68d9: wakeup_secondary_cpu_via_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int wakeup_secondary_cpu_via_init(int phys_apicid, long unsigned int start_eip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/smpboot.c (0)
Location: arch/x86/kernel/smpboot.c:790
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:do_boot_cpu
```
**Symbols:**

```
ffffffff8106c0c0-ffffffff8106c3eb: wakeup_secondary_cpu_via_init (STB_LOCAL)
ffffffff81bc8a7b-ffffffff81bc8ab3: wakeup_secondary_cpu_via_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int wakeup_secondary_cpu_via_init(int phys_apicid, long unsigned int start_eip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/smpboot.c (0)
Location: arch/x86/kernel/smpboot.c:792
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:do_boot_cpu
```
**Symbols:**

```
ffffffff81076cd0-ffffffff81076ffb: wakeup_secondary_cpu_via_init (STB_LOCAL)
ffffffff81c9d372-ffffffff81c9d3aa: wakeup_secondary_cpu_via_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int wakeup_secondary_cpu_via_init(int phys_apicid, long unsigned int start_eip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/smpboot.c (0)
Location: arch/x86/kernel/smpboot.c:835
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:do_boot_cpu
```
**Symbols:**

```
ffffffff81085b70-ffffffff81085e91: wakeup_secondary_cpu_via_init (STB_LOCAL)
ffffffff81e4c7fe-ffffffff81e4c823: wakeup_secondary_cpu_via_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int wakeup_secondary_cpu_via_init(int phys_apicid, long unsigned int start_eip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff81098e10)
Location: arch/x86/kernel/smpboot.c:833
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:do_boot_cpu
```
**Symbols:**

```
ffffffff81098e10-ffffffff81099164: wakeup_secondary_cpu_via_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int wakeup_secondary_cpu_via_init(int phys_apicid, long unsigned int start_eip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff8109c180)
Location: arch/x86/kernel/smpboot.c:883
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:do_boot_cpu
```
**Symbols:**

```
ffffffff8109c180-ffffffff8109c3ed: wakeup_secondary_cpu_via_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int wakeup_secondary_cpu_via_init(u32 phys_apicid, long unsigned int start_eip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff810a36b0)
Location: arch/x86/kernel/smpboot.c:849
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:do_boot_cpu
```
**Symbols:**

```
ffffffff810a36b0-ffffffff810a3981: wakeup_secondary_cpu_via_init (STB_LOCAL)
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
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int wakeup_secondary_cpu_via_init(int phys_apicid, long unsigned int start_eip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/smpboot.c (0)
Location: arch/x86/kernel/smpboot.c:780
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:do_boot_cpu
```
**Symbols:**

```
ffffffff810631d0-ffffffff810634fb: wakeup_secondary_cpu_via_init (STB_LOCAL)
ffffffff81064ae9-ffffffff81064b21: wakeup_secondary_cpu_via_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int wakeup_secondary_cpu_via_init(int phys_apicid, long unsigned int start_eip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/smpboot.c (0)
Location: arch/x86/kernel/smpboot.c:780
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:do_boot_cpu
```
**Symbols:**

```
ffffffff810534e0-ffffffff8105380b: wakeup_secondary_cpu_via_init (STB_LOCAL)
ffffffff81054dbe-ffffffff81054df6: wakeup_secondary_cpu_via_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int wakeup_secondary_cpu_via_init(int phys_apicid, long unsigned int start_eip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/smpboot.c (0)
Location: arch/x86/kernel/smpboot.c:780
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:do_boot_cpu
```
**Symbols:**

```
ffffffff81063680-ffffffff810639ab: wakeup_secondary_cpu_via_init (STB_LOCAL)
ffffffff81064f99-ffffffff81064fd1: wakeup_secondary_cpu_via_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int wakeup_secondary_cpu_via_init(int phys_apicid, long unsigned int start_eip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/smpboot.c (0)
Location: arch/x86/kernel/smpboot.c:780
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:do_boot_cpu
```
**Symbols:**

```
ffffffff81064c40-ffffffff81064f6b: wakeup_secondary_cpu_via_init (STB_LOCAL)
ffffffff81066579-ffffffff810665b1: wakeup_secondary_cpu_via_init.cold (STB_LOCAL)
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int phys_apicid</code> ➡️ <code>u32 phys_apicid</code>
</li>
</ul>
</details>
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
