# Function: <code>announce_cpu</code>

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
In arch/x86/kernel/smpboot.c (ffffffff81051bbf)
Location: arch/x86/kernel/smpboot.c:820
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
In arch/x86/kernel/smpboot.c (ffffffff81051d51)
Location: arch/x86/kernel/smpboot.c:832
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
In arch/x86/kernel/smpboot.c (ffffffff8105464e)
Location: arch/x86/kernel/smpboot.c:848
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
In arch/x86/kernel/smpboot.c (ffffffff81053fa1)
Location: arch/x86/kernel/smpboot.c:851
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
In arch/x86/kernel/smpboot.c (ffffffff81057d50)
Location: arch/x86/kernel/smpboot.c:788
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
In arch/x86/kernel/smpboot.c (ffffffff8105aa72)
Location: arch/x86/kernel/smpboot.c:841
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
In arch/x86/kernel/smpboot.c (ffffffff810606f2)
Location: arch/x86/kernel/smpboot.c:842
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:native_cpu_up
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
In arch/x86/kernel/smpboot.c (ffffffff81063eac)
Location: arch/x86/kernel/smpboot.c:894
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:do_boot_cpu
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
In arch/x86/kernel/smpboot.c (ffffffff81064551)
Location: arch/x86/kernel/smpboot.c:894
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:do_boot_cpu
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void announce_cpu(int cpu, int apicid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/smpboot.c (0)
Location: arch/x86/kernel/smpboot.c:907
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:do_boot_cpu
```
**Symbols:**

```
ffffffff810698c0-ffffffff81069a0c: announce_cpu (STB_LOCAL)
ffffffff8106b8ef-ffffffff8106b94c: announce_cpu.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void announce_cpu(int cpu, int apicid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/smpboot.c (0)
Location: arch/x86/kernel/smpboot.c:903
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:do_boot_cpu
```
**Symbols:**

```
ffffffff8106b590-ffffffff8106b6dc: announce_cpu (STB_LOCAL)
ffffffff81bd6844-ffffffff81bd68a1: announce_cpu.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void announce_cpu(int cpu, int apicid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/smpboot.c (0)
Location: arch/x86/kernel/smpboot.c:904
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:do_boot_cpu
```
**Symbols:**

```
ffffffff8106bf70-ffffffff8106c0bc: announce_cpu (STB_LOCAL)
ffffffff81bc8a1e-ffffffff81bc8a7b: announce_cpu.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void announce_cpu(int cpu, int apicid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/smpboot.c (0)
Location: arch/x86/kernel/smpboot.c:906
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:do_boot_cpu
```
**Symbols:**

```
ffffffff81076b50-ffffffff81076cc6: announce_cpu (STB_LOCAL)
ffffffff81c9d315-ffffffff81c9d372: announce_cpu.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void announce_cpu(int cpu, int apicid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/smpboot.c (0)
Location: arch/x86/kernel/smpboot.c:949
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:do_boot_cpu
```
**Symbols:**

```
ffffffff810859f0-ffffffff81085b67: announce_cpu (STB_LOCAL)
ffffffff81e4c71c-ffffffff81e4c7fe: announce_cpu.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void announce_cpu(int cpu, int apicid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff81098bd0)
Location: arch/x86/kernel/smpboot.c:947
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:do_boot_cpu
```
**Symbols:**

```
ffffffff81098bd0-ffffffff81098df6: announce_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void announce_cpu(int cpu, int apicid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff8109bea0)
Location: arch/x86/kernel/smpboot.c:966
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:do_boot_cpu
```
**Symbols:**

```
ffffffff8109bea0-ffffffff8109c09b: announce_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void announce_cpu(int cpu, int apicid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff810a34a0)
Location: arch/x86/kernel/smpboot.c:932
Inline: False
Direct callers:
  - arch/x86/kernel/smpboot.c:do_boot_cpu
```
**Symbols:**

```
ffffffff810a34a0-ffffffff810a369b: announce_cpu (STB_LOCAL)
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
In arch/x86/kernel/smpboot.c (ffffffff81064041)
Location: arch/x86/kernel/smpboot.c:894
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:do_boot_cpu
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
In arch/x86/kernel/smpboot.c (ffffffff81054341)
Location: arch/x86/kernel/smpboot.c:894
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:do_boot_cpu
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
In arch/x86/kernel/smpboot.c (ffffffff810644f1)
Location: arch/x86/kernel/smpboot.c:894
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:do_boot_cpu
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
In arch/x86/kernel/smpboot.c (ffffffff81065ab1)
Location: arch/x86/kernel/smpboot.c:894
Inline: True
Inline callers:
  - arch/x86/kernel/smpboot.c:do_boot_cpu
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
