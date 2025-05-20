# Function: <code>default_check_apicid_used</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate ⚠️</summary>

```c
long unsigned int default_check_apicid_used(physid_mask_t *map, int apicid);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/apic.c (ffffffff81025ab0)
Location: arch/x86/include/asm/apic.h:588
Inline: False
```
```
In arch/x86/kernel/apic/apic_noop.c (ffffffff81054990)
Location: arch/x86/include/asm/apic.h:588
Inline: False
```
**Symbols:**

```
ffffffff81025ab0-ffffffff81025ac1: default_check_apicid_used (STB_LOCAL)
ffffffff81054990-ffffffff810549a1: default_check_apicid_used (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate ⚠️</summary>

```c
long unsigned int default_check_apicid_used(physid_mask_t *map, int apicid);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/apic.c (ffffffff81024eb0)
Location: arch/x86/include/asm/apic.h:595
Inline: False
```
```
In arch/x86/kernel/apic/apic_noop.c (ffffffff81054b10)
Location: arch/x86/include/asm/apic.h:595
Inline: False
```
**Symbols:**

```
ffffffff81024eb0-ffffffff81024ec2: default_check_apicid_used (STB_LOCAL)
ffffffff81054b10-ffffffff81054b22: default_check_apicid_used (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate ⚠️</summary>

```c
long unsigned int default_check_apicid_used(physid_mask_t *map, int apicid);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/apic.c (ffffffff810255d0)
Location: arch/x86/include/asm/apic.h:595
Inline: False
```
```
In arch/x86/kernel/apic/apic_noop.c (ffffffff810578f0)
Location: arch/x86/include/asm/apic.h:595
Inline: False
```
**Symbols:**

```
ffffffff810255d0-ffffffff810255e2: default_check_apicid_used (STB_LOCAL)
ffffffff810578f0-ffffffff81057902: default_check_apicid_used (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate ⚠️</summary>

```c
long unsigned int default_check_apicid_used(physid_mask_t *map, int apicid);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/apic.c (ffffffff8101bf80)
Location: arch/x86/include/asm/apic.h:575
Inline: False
```
```
In arch/x86/kernel/apic/apic_noop.c (ffffffff810570b0)
Location: arch/x86/include/asm/apic.h:575
Inline: False
```
**Symbols:**

```
ffffffff8101bf80-ffffffff8101bf92: default_check_apicid_used (STB_LOCAL)
ffffffff810570b0-ffffffff810570c2: default_check_apicid_used (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool default_check_apicid_used(physid_mask_t *map, int apicid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic_common.c (ffffffff8105ac70)
Location: arch/x86/kernel/apic/apic_common.c:19
Inline: False
```
**Symbols:**

```
ffffffff8105ac70-ffffffff8105ac85: default_check_apicid_used (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool default_check_apicid_used(physid_mask_t *map, int apicid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic_common.c (ffffffff8105dc70)
Location: arch/x86/kernel/apic/apic_common.c:19
Inline: False
```
**Symbols:**

```
ffffffff8105dc70-ffffffff8105dc85: default_check_apicid_used (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool default_check_apicid_used(physid_mask_t *map, int apicid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic_common.c (ffffffff81063900)
Location: arch/x86/kernel/apic/apic_common.c:19
Inline: False
```
**Symbols:**

```
ffffffff81063900-ffffffff81063915: default_check_apicid_used (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool default_check_apicid_used(physid_mask_t *map, int apicid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic_common.c (ffffffff81066fc0)
Location: arch/x86/kernel/apic/apic_common.c:19
Inline: False
```
**Symbols:**

```
ffffffff81066fc0-ffffffff81066fd5: default_check_apicid_used (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool default_check_apicid_used(physid_mask_t *map, int apicid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic_common.c (ffffffff81067630)
Location: arch/x86/kernel/apic/apic_common.c:19
Inline: False
```
**Symbols:**

```
ffffffff81067630-ffffffff81067645: default_check_apicid_used (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool default_check_apicid_used(physid_mask_t *map, int apicid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic_common.c (ffffffff8106e380)
Location: arch/x86/kernel/apic/apic_common.c:19
Inline: False
```
**Symbols:**

```
ffffffff8106e380-ffffffff8106e395: default_check_apicid_used (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool default_check_apicid_used(physid_mask_t *map, int apicid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic_common.c (ffffffff8106f800)
Location: arch/x86/kernel/apic/apic_common.c:19
Inline: False
```
**Symbols:**

```
ffffffff8106f800-ffffffff8106f815: default_check_apicid_used (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool default_check_apicid_used(physid_mask_t *map, int apicid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic_common.c (ffffffff81070330)
Location: arch/x86/kernel/apic/apic_common.c:19
Inline: False
```
**Symbols:**

```
ffffffff81070330-ffffffff81070345: default_check_apicid_used (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool default_check_apicid_used(physid_mask_t *map, int apicid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic_common.c (ffffffff8107bed0)
Location: arch/x86/kernel/apic/apic_common.c:19
Inline: False
```
**Symbols:**

```
ffffffff8107bed0-ffffffff8107bee5: default_check_apicid_used (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool default_check_apicid_used(physid_mask_t *map, int apicid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic_common.c (ffffffff8108b150)
Location: arch/x86/kernel/apic/apic_common.c:19
Inline: False
```
**Symbols:**

```
ffffffff8108b150-ffffffff8108b16d: default_check_apicid_used (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool default_check_apicid_used(physid_mask_t *map, int apicid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic_common.c (ffffffff8109f380)
Location: arch/x86/kernel/apic/apic_common.c:19
Inline: False
```
**Symbols:**

```
ffffffff8109f380-ffffffff8109f39d: default_check_apicid_used (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool default_check_apicid_used(physid_mask_t *map, int apicid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic_common.c (ffffffff810a2310)
Location: arch/x86/kernel/apic/apic_common.c:19
Inline: False
```
**Symbols:**

```
ffffffff810a2310-ffffffff810a232d: default_check_apicid_used (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool default_check_apicid_used(physid_mask_t *map, u32 apicid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic_common.c (ffffffff810a9080)
Location: arch/x86/kernel/apic/apic_common.c:21
Inline: False
```
**Symbols:**

```
ffffffff810a9080-ffffffff810a909c: default_check_apicid_used (STB_GLOBAL)
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
bool default_check_apicid_used(physid_mask_t *map, int apicid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic_common.c (ffffffff81067120)
Location: arch/x86/kernel/apic/apic_common.c:19
Inline: False
```
**Symbols:**

```
ffffffff81067120-ffffffff81067135: default_check_apicid_used (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool default_check_apicid_used(physid_mask_t *map, int apicid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic_common.c (ffffffff810574e0)
Location: arch/x86/kernel/apic/apic_common.c:19
Inline: False
```
**Symbols:**

```
ffffffff810574e0-ffffffff810574f5: default_check_apicid_used (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool default_check_apicid_used(physid_mask_t *map, int apicid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic_common.c (ffffffff810675d0)
Location: arch/x86/kernel/apic/apic_common.c:19
Inline: False
```
**Symbols:**

```
ffffffff810675d0-ffffffff810675e5: default_check_apicid_used (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool default_check_apicid_used(physid_mask_t *map, int apicid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic_common.c (ffffffff81068bb0)
Location: arch/x86/kernel/apic/apic_common.c:19
Inline: False
```
**Symbols:**

```
ffffffff81068bb0-ffffffff81068bc5: default_check_apicid_used (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>long unsigned int</code> ➡️ <code>bool</code>
</li>
</ul>
</details>
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
<b>Param type changed. </b>
<code>int apicid</code> ➡️ <code>u32 apicid</code>
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
