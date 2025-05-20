# Function: <code>init_amd_k8</code>

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
In arch/x86/kernel/cpu/amd.c (ffffffff81042d0b)
Location: arch/x86/kernel/cpu/amd.c:586
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
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
In arch/x86/kernel/cpu/amd.c (ffffffff81042f3f)
Location: arch/x86/kernel/cpu/amd.c:598
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
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
In arch/x86/kernel/cpu/amd.c (ffffffff81042a7d)
Location: arch/x86/kernel/cpu/amd.c:617
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
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
In arch/x86/kernel/cpu/amd.c (ffffffff81040b67)
Location: arch/x86/kernel/cpu/amd.c:617
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
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
In arch/x86/kernel/cpu/amd.c (ffffffff81043b66)
Location: arch/x86/kernel/cpu/amd.c:652
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
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
In arch/x86/kernel/cpu/amd.c (ffffffff8104613c)
Location: arch/x86/kernel/cpu/amd.c:711
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
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
In arch/x86/kernel/cpu/amd.c (ffffffff81047c31)
Location: arch/x86/kernel/cpu/amd.c:718
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
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
In arch/x86/kernel/cpu/amd.c (ffffffff8104a8e1)
Location: arch/x86/kernel/cpu/amd.c:722
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
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
In arch/x86/kernel/cpu/amd.c (ffffffff8104b2e4)
Location: arch/x86/kernel/cpu/amd.c:724
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void init_amd_k8(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/amd.c (ffffffff8104ee20)
Location: arch/x86/kernel/cpu/amd.c:750
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
```
**Symbols:**

```
ffffffff8104ee20-ffffffff8104f002: init_amd_k8 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void init_amd_k8(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/amd.c (ffffffff8104e0e0)
Location: arch/x86/kernel/cpu/amd.c:724
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
```
**Symbols:**

```
ffffffff8104e0e0-ffffffff8104e2c2: init_amd_k8 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void init_amd_k8(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/amd.c (ffffffff8104fb80)
Location: arch/x86/kernel/cpu/amd.c:719
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
```
**Symbols:**

```
ffffffff8104fb80-ffffffff8104fd62: init_amd_k8 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void init_amd_k8(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/amd.c (0)
Location: arch/x86/kernel/cpu/amd.c:723
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
```
**Symbols:**

```
ffffffff81057e20-ffffffff81058026: init_amd_k8 (STB_LOCAL)
ffffffff81c9b20e-ffffffff81c9b238: init_amd_k8.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void init_amd_k8(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/amd.c (0)
Location: arch/x86/kernel/cpu/amd.c:699
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
```
**Symbols:**

```
ffffffff81064330-ffffffff81064552: init_amd_k8 (STB_LOCAL)
ffffffff81e4a749-ffffffff81e4a773: init_amd_k8.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void init_amd_k8(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/amd.c (0)
Location: arch/x86/kernel/cpu/amd.c:699
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
```
**Symbols:**

```
ffffffff81073550-ffffffff81073772: init_amd_k8 (STB_LOCAL)
ffffffff82052bbf-ffffffff82052be9: init_amd_k8.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void init_amd_k8(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/amd.c (0)
Location: arch/x86/kernel/cpu/amd.c:771
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
```
**Symbols:**

```
ffffffff810751d0-ffffffff810753f2: init_amd_k8 (STB_LOCAL)
ffffffff820d108c-ffffffff820d10b6: init_amd_k8.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void init_amd_k8(struct cpuinfo_x86 *c);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/amd.c (0)
Location: arch/x86/kernel/cpu/amd.c:746
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
```
**Symbols:**

```
ffffffff8107c830-ffffffff8107ca84: init_amd_k8 (STB_LOCAL)
ffffffff821abbbd-ffffffff821abbe7: init_amd_k8.cold (STB_LOCAL)
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
In arch/x86/kernel/cpu/amd.c (ffffffff8104b454)
Location: arch/x86/kernel/cpu/amd.c:724
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
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
In arch/x86/kernel/cpu/amd.c (ffffffff8103a8c4)
Location: arch/x86/kernel/cpu/amd.c:724
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
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
In arch/x86/kernel/cpu/amd.c (ffffffff8104b294)
Location: arch/x86/kernel/cpu/amd.c:724
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
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
In arch/x86/kernel/cpu/amd.c (ffffffff8104c6a4)
Location: arch/x86/kernel/cpu/amd.c:724
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/amd.c:init_amd
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
