# Function: <code>jailhouse_cpuid_base</code>

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
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
uint32_t jailhouse_cpuid_base();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/jailhouse.c (ffffffff8106e840)
Location: arch/x86/kernel/jailhouse.c:26
Inline: True
Direct callers:
  - arch/x86/kernel/jailhouse.c:jailhouse_paravirt
  - arch/x86/kernel/jailhouse.c:jailhouse_detect
```
**Symbols:**

```
ffffffff8106e840-ffffffff8106e90c: jailhouse_cpuid_base (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
uint32_t jailhouse_cpuid_base();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/jailhouse.c (ffffffff81074860)
Location: arch/x86/kernel/jailhouse.c:27
Inline: True
Direct callers:
  - arch/x86/kernel/jailhouse.c:jailhouse_paravirt
  - arch/x86/kernel/jailhouse.c:jailhouse_detect
```
**Symbols:**

```
ffffffff81074860-ffffffff8107492c: jailhouse_cpuid_base (STB_LOCAL)
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
In arch/x86/kernel/jailhouse.c (ffffffff81078498)
Location: arch/x86/kernel/jailhouse.c:27
Inline: True
Inline callers:
  - arch/x86/kernel/jailhouse.c:jailhouse_paravirt
  - arch/x86/kernel/jailhouse.c:jailhouse_paravirt
  - arch/x86/kernel/jailhouse.c:jailhouse_detect
  - arch/x86/kernel/jailhouse.c:jailhouse_detect
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
In arch/x86/kernel/jailhouse.c (ffffffff810794e8)
Location: arch/x86/kernel/jailhouse.c:27
Inline: True
Inline callers:
  - arch/x86/kernel/jailhouse.c:jailhouse_paravirt
  - arch/x86/kernel/jailhouse.c:jailhouse_paravirt
  - arch/x86/kernel/jailhouse.c:jailhouse_detect
  - arch/x86/kernel/jailhouse.c:jailhouse_detect
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
uint32_t jailhouse_cpuid_base();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/jailhouse.c (ffffffff81080855)
Location: arch/x86/kernel/jailhouse.c:43
Inline: True
Inline callers:
  - arch/x86/kernel/jailhouse.c:jailhouse_paravirt
Direct callers:
  - arch/x86/kernel/jailhouse.c:jailhouse_paravirt
  - arch/x86/kernel/jailhouse.c:jailhouse_detect
```
**Symbols:**

```
ffffffff81080770-ffffffff8108081b: jailhouse_cpuid_base.part.0 (STB_LOCAL)
ffffffff81080820-ffffffff8108084c: jailhouse_cpuid_base (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
uint32_t jailhouse_cpuid_base();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/jailhouse.c (ffffffff81080465)
Location: arch/x86/kernel/jailhouse.c:45
Inline: True
Inline callers:
  - arch/x86/kernel/jailhouse.c:jailhouse_paravirt
Direct callers:
  - arch/x86/kernel/jailhouse.c:jailhouse_paravirt
  - arch/x86/kernel/jailhouse.c:jailhouse_detect
```
**Symbols:**

```
ffffffff81080380-ffffffff81080426: jailhouse_cpuid_base.part.0 (STB_LOCAL)
ffffffff81080430-ffffffff8108045c: jailhouse_cpuid_base (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
uint32_t jailhouse_cpuid_base();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/jailhouse.c (ffffffff81081305)
Location: arch/x86/kernel/jailhouse.c:45
Inline: True
Inline callers:
  - arch/x86/kernel/jailhouse.c:jailhouse_paravirt
Direct callers:
  - arch/x86/kernel/jailhouse.c:jailhouse_paravirt
  - arch/x86/kernel/jailhouse.c:jailhouse_detect
```
**Symbols:**

```
ffffffff81081220-ffffffff810812c6: jailhouse_cpuid_base.part.0 (STB_LOCAL)
ffffffff810812d0-ffffffff810812fc: jailhouse_cpuid_base (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
uint32_t jailhouse_cpuid_base();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/jailhouse.c (ffffffff810902b5)
Location: arch/x86/kernel/jailhouse.c:45
Inline: True
Inline callers:
  - arch/x86/kernel/jailhouse.c:jailhouse_paravirt
Direct callers:
  - arch/x86/kernel/jailhouse.c:jailhouse_paravirt
  - arch/x86/kernel/jailhouse.c:jailhouse_detect
```
**Symbols:**

```
ffffffff810901d0-ffffffff81090276: jailhouse_cpuid_base.part.0 (STB_LOCAL)
ffffffff81090280-ffffffff810902ac: jailhouse_cpuid_base (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
uint32_t jailhouse_cpuid_base();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/jailhouse.c (ffffffff810a1245)
Location: arch/x86/kernel/jailhouse.c:45
Inline: True
Inline callers:
  - arch/x86/kernel/jailhouse.c:jailhouse_paravirt
Direct callers:
  - arch/x86/kernel/jailhouse.c:jailhouse_paravirt
  - arch/x86/kernel/jailhouse.c:jailhouse_detect
```
**Symbols:**

```
ffffffff810a10d0-ffffffff810a119c: jailhouse_cpuid_base.part.0 (STB_LOCAL)
ffffffff81e4eae5-ffffffff81e4eb1a: jailhouse_cpuid_base (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/jailhouse.c (ffffffff810b91d5)
Location: arch/x86/kernel/jailhouse.c:45
Inline: True
Inline callers:
  - arch/x86/kernel/jailhouse.c:jailhouse_paravirt
  - arch/x86/kernel/jailhouse.c:jailhouse_detect
Direct callers:
  - arch/x86/kernel/jailhouse.c:jailhouse_paravirt
  - arch/x86/kernel/jailhouse.c:jailhouse_detect
```
**Symbols:**

```
ffffffff810b8fe0-ffffffff810b90ac: jailhouse_cpuid_base.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/jailhouse.c (ffffffff810bc3a5)
Location: arch/x86/kernel/jailhouse.c:45
Inline: True
Inline callers:
  - arch/x86/kernel/jailhouse.c:jailhouse_paravirt
  - arch/x86/kernel/jailhouse.c:jailhouse_detect
Direct callers:
  - arch/x86/kernel/jailhouse.c:jailhouse_paravirt
  - arch/x86/kernel/jailhouse.c:jailhouse_detect
```
**Symbols:**

```
ffffffff810bc1b0-ffffffff810bc27c: jailhouse_cpuid_base.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/jailhouse.c (ffffffff810c3525)
Location: arch/x86/kernel/jailhouse.c:45
Inline: True
Inline callers:
  - arch/x86/kernel/jailhouse.c:jailhouse_paravirt
  - arch/x86/kernel/jailhouse.c:jailhouse_detect
Direct callers:
  - arch/x86/kernel/jailhouse.c:jailhouse_paravirt
  - arch/x86/kernel/jailhouse.c:jailhouse_detect
```
**Symbols:**

```
ffffffff810c3330-ffffffff810c33fc: jailhouse_cpuid_base.part.0 (STB_LOCAL)
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
In arch/x86/kernel/jailhouse.c (ffffffff810784e8)
Location: arch/x86/kernel/jailhouse.c:27
Inline: True
Inline callers:
  - arch/x86/kernel/jailhouse.c:jailhouse_paravirt
  - arch/x86/kernel/jailhouse.c:jailhouse_paravirt
  - arch/x86/kernel/jailhouse.c:jailhouse_detect
  - arch/x86/kernel/jailhouse.c:jailhouse_detect
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/jailhouse.c (ffffffff81067d55)
Location: arch/x86/kernel/jailhouse.c:27
Inline: True
Inline callers:
  - arch/x86/kernel/jailhouse.c:jailhouse_paravirt
  - arch/x86/kernel/jailhouse.c:jailhouse_detect
Direct callers:
  - arch/x86/kernel/jailhouse.c:jailhouse_paravirt
  - arch/x86/kernel/jailhouse.c:jailhouse_detect
```
**Symbols:**

```
ffffffff81067cc0-ffffffff81067d44: jailhouse_cpuid_base.part.0 (STB_LOCAL)
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
In arch/x86/kernel/jailhouse.c (ffffffff81078498)
Location: arch/x86/kernel/jailhouse.c:27
Inline: True
Inline callers:
  - arch/x86/kernel/jailhouse.c:jailhouse_paravirt
  - arch/x86/kernel/jailhouse.c:jailhouse_paravirt
  - arch/x86/kernel/jailhouse.c:jailhouse_detect
  - arch/x86/kernel/jailhouse.c:jailhouse_detect
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
In arch/x86/kernel/jailhouse.c (ffffffff8107a598)
Location: arch/x86/kernel/jailhouse.c:27
Inline: True
Inline callers:
  - arch/x86/kernel/jailhouse.c:jailhouse_paravirt
  - arch/x86/kernel/jailhouse.c:jailhouse_paravirt
  - arch/x86/kernel/jailhouse.c:jailhouse_detect
  - arch/x86/kernel/jailhouse.c:jailhouse_detect
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
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
</ul>
