# Function: <code>find_patch</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct ucode_patch *find_patch(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff8104e060)
Location: arch/x86/kernel/cpu/microcode/amd.c:541
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/amd.c:collect_cpu_info_amd
  - arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_amd
```
**Symbols:**

```
ffffffff8104e060-ffffffff8104e0de: find_patch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct ucode_patch *find_patch(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff8104e1f0)
Location: arch/x86/kernel/cpu/microcode/amd.c:553
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:collect_cpu_info_amd
```
**Symbols:**

```
ffffffff8104e1f0-ffffffff8104e26e: find_patch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Collision ⚠️</summary>

```c
struct microcode_intel *find_patch(struct ucode_cpu_info *uci);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff8104fb50)
Location: arch/x86/kernel/cpu/microcode/intel.c:697
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:reload_ucode_intel
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81050870)
Location: arch/x86/kernel/cpu/microcode/amd.c:568
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:collect_cpu_info_amd
```
**Symbols:**

```
ffffffff8104fb50-ffffffff8104fbc3: find_patch (STB_LOCAL)
ffffffff81050870-ffffffff810508ee: find_patch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Collision ⚠️</summary>

```c
struct microcode_intel *find_patch(struct ucode_cpu_info *uci);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff8104faa0)
Location: arch/x86/kernel/cpu/microcode/intel.c:717
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:reload_ucode_intel
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81050780)
Location: arch/x86/kernel/cpu/microcode/amd.c:428
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:collect_cpu_info_amd
```
**Symbols:**

```
ffffffff8104faa0-ffffffff8104fb15: find_patch (STB_LOCAL)
ffffffff81050780-ffffffff810507e5: find_patch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Collision ⚠️</summary>

```c
struct microcode_intel *find_patch(struct ucode_cpu_info *uci);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81053580)
Location: arch/x86/kernel/cpu/microcode/intel.c:726
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:reload_ucode_intel
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81054390)
Location: arch/x86/kernel/cpu/microcode/amd.c:431
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:collect_cpu_info_amd
```
**Symbols:**

```
ffffffff81053580-ffffffff810535f5: find_patch (STB_LOCAL)
ffffffff81054390-ffffffff810543f5: find_patch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Collision ⚠️</summary>

```c
struct microcode_intel *find_patch(struct ucode_cpu_info *uci);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81056220)
Location: arch/x86/kernel/cpu/microcode/intel.c:727
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:reload_ucode_intel
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81057160)
Location: arch/x86/kernel/cpu/microcode/amd.c:431
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_amd
```
**Symbols:**

```
ffffffff81056220-ffffffff81056295: find_patch (STB_LOCAL)
ffffffff81057160-ffffffff810571c5: find_patch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Collision ⚠️</summary>

```c
struct microcode_intel *find_patch(struct ucode_cpu_info *uci);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff810538b0)
Location: arch/x86/kernel/cpu/microcode/intel.c:727
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:reload_ucode_intel
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81054710)
Location: arch/x86/kernel/cpu/microcode/amd.c:638
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_amd
```
**Symbols:**

```
ffffffff810538b0-ffffffff81053925: find_patch (STB_LOCAL)
ffffffff81054710-ffffffff8105478f: find_patch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Collision ⚠️</summary>

```c
struct microcode_intel *find_patch(struct ucode_cpu_info *uci);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81056a50)
Location: arch/x86/kernel/cpu/microcode/intel.c:724
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:reload_ucode_intel
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81057960)
Location: arch/x86/kernel/cpu/microcode/amd.c:636
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_amd
```
**Symbols:**

```
ffffffff81056a50-ffffffff81056abd: find_patch (STB_LOCAL)
ffffffff81057960-ffffffff810579d5: find_patch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Collision ⚠️</summary>

```c
struct microcode_intel *find_patch(struct ucode_cpu_info *uci);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81057300)
Location: arch/x86/kernel/cpu/microcode/intel.c:724
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:reload_ucode_intel
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81058230)
Location: arch/x86/kernel/cpu/microcode/amd.c:636
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_amd
```
**Symbols:**

```
ffffffff81057300-ffffffff8105736d: find_patch (STB_LOCAL)
ffffffff81058230-ffffffff810582a5: find_patch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Collision ⚠️</summary>

```c
struct microcode_intel *find_patch(struct ucode_cpu_info *uci);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff8105c5b0)
Location: arch/x86/kernel/cpu/microcode/intel.c:724
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:reload_ucode_intel
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff8105dbf0)
Location: arch/x86/kernel/cpu/microcode/amd.c:636
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:collect_cpu_info_amd
```
**Symbols:**

```
ffffffff8105c5b0-ffffffff8105c625: find_patch (STB_LOCAL)
ffffffff8105dbf0-ffffffff8105dc63: find_patch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision ⚠️</summary>

```c
struct microcode_intel *find_patch(struct ucode_cpu_info *uci);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff8105ae20)
Location: arch/x86/kernel/cpu/microcode/intel.c:681
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:reload_ucode_intel
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff8105c290)
Location: arch/x86/kernel/cpu/microcode/amd.c:635
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:collect_cpu_info_amd
```
**Symbols:**

```
ffffffff8105ae20-ffffffff8105ae95: find_patch (STB_LOCAL)
ffffffff8105c290-ffffffff8105c303: find_patch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision ⚠️</summary>

```c
struct microcode_intel *find_patch(struct ucode_cpu_info *uci);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff8105b7d0)
Location: arch/x86/kernel/cpu/microcode/intel.c:681
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:reload_ucode_intel
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff8105cba0)
Location: arch/x86/kernel/cpu/microcode/amd.c:635
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:collect_cpu_info_amd
```
**Symbols:**

```
ffffffff8105b7d0-ffffffff8105b845: find_patch (STB_LOCAL)
ffffffff8105cba0-ffffffff8105cc13: find_patch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision ⚠️</summary>

```c
struct microcode_intel *find_patch(struct ucode_cpu_info *uci);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81064de0)
Location: arch/x86/kernel/cpu/microcode/intel.c:681
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:reload_ucode_intel
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81066240)
Location: arch/x86/kernel/cpu/microcode/amd.c:635
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:collect_cpu_info_amd
```
**Symbols:**

```
ffffffff81064de0-ffffffff81064e55: find_patch (STB_LOCAL)
ffffffff81066240-ffffffff810662b3: find_patch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision ⚠️</summary>

```c
struct microcode_intel *find_patch(struct ucode_cpu_info *uci);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81071800)
Location: arch/x86/kernel/cpu/microcode/intel.c:643
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:reload_ucode_intel
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81072fa0)
Location: arch/x86/kernel/cpu/microcode/amd.c:641
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/amd.c:load_microcode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:collect_cpu_info_amd
```
**Symbols:**

```
ffffffff81071800-ffffffff8107188b: find_patch (STB_LOCAL)
ffffffff81072fa0-ffffffff81073024: find_patch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision ⚠️</summary>

```c
struct microcode_intel *find_patch(struct ucode_cpu_info *uci);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff810812c0)
Location: arch/x86/kernel/cpu/microcode/intel.c:511
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:reload_ucode_intel
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81082fe0)
Location: arch/x86/kernel/cpu/microcode/amd.c:652
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/amd.c:load_microcode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:collect_cpu_info_amd
```
**Symbols:**

```
ffffffff810812c0-ffffffff81081341: find_patch (STB_LOCAL)
ffffffff81082fe0-ffffffff81083064: find_patch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision ⚠️</summary>

```c
struct microcode_intel *find_patch(struct ucode_cpu_info *uci);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81083740)
Location: arch/x86/kernel/cpu/microcode/intel.c:503
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:reload_ucode_intel
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81084e20)
Location: arch/x86/kernel/cpu/microcode/amd.c:645
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/amd.c:load_microcode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:collect_cpu_info_amd
```
**Symbols:**

```
ffffffff81083740-ffffffff810837c1: find_patch (STB_LOCAL)
ffffffff81084e20-ffffffff81084ea4: find_patch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct ucode_patch *find_patch(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff8108c0b0)
Location: arch/x86/kernel/cpu/microcode/amd.c:595
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:collect_cpu_info_amd
  - arch/x86/kernel/cpu/microcode/amd.c:reload_ucode_amd
```
**Symbols:**

```
ffffffff8108c0b0-ffffffff8108c134: find_patch (STB_LOCAL)
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
<summary>In <code>aws</code>: Collision ⚠️</summary>

```c
struct microcode_intel *find_patch(struct ucode_cpu_info *uci);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81056e80)
Location: arch/x86/kernel/cpu/microcode/intel.c:724
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:reload_ucode_intel
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81057db0)
Location: arch/x86/kernel/cpu/microcode/amd.c:636
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_amd
```
**Symbols:**

```
ffffffff81056e80-ffffffff81056eed: find_patch (STB_LOCAL)
ffffffff81057db0-ffffffff81057e25: find_patch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Collision ⚠️</summary>

```c
struct microcode_intel *find_patch(struct ucode_cpu_info *uci);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81047070)
Location: arch/x86/kernel/cpu/microcode/intel.c:724
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:reload_ucode_intel
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81047fa0)
Location: arch/x86/kernel/cpu/microcode/amd.c:636
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_amd
```
**Symbols:**

```
ffffffff81047070-ffffffff810470dd: find_patch (STB_LOCAL)
ffffffff81047fa0-ffffffff81048015: find_patch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Collision ⚠️</summary>

```c
struct microcode_intel *find_patch(struct ucode_cpu_info *uci);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff810572b0)
Location: arch/x86/kernel/cpu/microcode/intel.c:724
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:reload_ucode_intel
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff810581e0)
Location: arch/x86/kernel/cpu/microcode/amd.c:636
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_amd
```
**Symbols:**

```
ffffffff810572b0-ffffffff8105731d: find_patch (STB_LOCAL)
ffffffff810581e0-ffffffff81058255: find_patch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Collision ⚠️</summary>

```c
struct microcode_intel *find_patch(struct ucode_cpu_info *uci);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/intel.c (ffffffff81058750)
Location: arch/x86/kernel/cpu/microcode/intel.c:724
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/intel.c:apply_microcode_intel
  - arch/x86/kernel/cpu/microcode/intel.c:reload_ucode_intel
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81059680)
Location: arch/x86/kernel/cpu/microcode/amd.c:636
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_amd
```
**Symbols:**

```
ffffffff81058750-ffffffff810587bd: find_patch (STB_LOCAL)
ffffffff81059680-ffffffff810596f5: find_patch (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.8</code> and <code>4.10</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct ucode_cpu_info *uci</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned int cpu</code>
</li>
<li>
<b>Return type changed. </b>
<code>struct ucode_patch *</code> ➡️ <code>struct microcode_intel *</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int cpu</code>
</li>
<li>
<b>Param removed. </b>
<code>struct ucode_cpu_info *uci</code>
</li>
<li>
<b>Return type changed. </b>
<code>struct microcode_intel *</code> ➡️ <code>struct ucode_patch *</code>
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
