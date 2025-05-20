# Function: <code>apic_default_calc_apicid</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
u32 apic_default_calc_apicid(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic_common.c (ffffffff8105ac30)
Location: arch/x86/kernel/apic/apic_common.c:9
Inline: False
```
**Symbols:**

```
ffffffff8105ac30-ffffffff8105ac50: apic_default_calc_apicid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
u32 apic_default_calc_apicid(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic_common.c (ffffffff8105dc30)
Location: arch/x86/kernel/apic/apic_common.c:9
Inline: False
```
**Symbols:**

```
ffffffff8105dc30-ffffffff8105dc50: apic_default_calc_apicid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
u32 apic_default_calc_apicid(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic_common.c (ffffffff810638c0)
Location: arch/x86/kernel/apic/apic_common.c:9
Inline: False
```
**Symbols:**

```
ffffffff810638c0-ffffffff810638e0: apic_default_calc_apicid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
u32 apic_default_calc_apicid(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic_common.c (ffffffff81066f80)
Location: arch/x86/kernel/apic/apic_common.c:9
Inline: False
```
**Symbols:**

```
ffffffff81066f80-ffffffff81066fa0: apic_default_calc_apicid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
u32 apic_default_calc_apicid(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic_common.c (ffffffff810675f0)
Location: arch/x86/kernel/apic/apic_common.c:9
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:apic_uv_calc_apicid
```
**Symbols:**

```
ffffffff810675f0-ffffffff81067610: apic_default_calc_apicid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
u32 apic_default_calc_apicid(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic_common.c (ffffffff8106e340)
Location: arch/x86/kernel/apic/apic_common.c:9
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:apic_uv_calc_apicid
```
**Symbols:**

```
ffffffff8106e340-ffffffff8106e360: apic_default_calc_apicid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
u32 apic_default_calc_apicid(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic_common.c (ffffffff8106f7c0)
Location: arch/x86/kernel/apic/apic_common.c:9
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:apic_uv_calc_apicid
```
**Symbols:**

```
ffffffff8106f7c0-ffffffff8106f7e0: apic_default_calc_apicid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
u32 apic_default_calc_apicid(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic_common.c (ffffffff810702f0)
Location: arch/x86/kernel/apic/apic_common.c:9
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:apic_uv_calc_apicid
```
**Symbols:**

```
ffffffff810702f0-ffffffff81070310: apic_default_calc_apicid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
u32 apic_default_calc_apicid(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic_common.c (ffffffff8107be70)
Location: arch/x86/kernel/apic/apic_common.c:9
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:apic_uv_calc_apicid
```
**Symbols:**

```
ffffffff8107be70-ffffffff8107beb0: apic_default_calc_apicid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
u32 apic_default_calc_apicid(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic_common.c (ffffffff8108b0d0)
Location: arch/x86/kernel/apic/apic_common.c:9
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:apic_uv_calc_apicid
```
**Symbols:**

```
ffffffff8108b0d0-ffffffff8108b118: apic_default_calc_apicid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
u32 apic_default_calc_apicid(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic_common.c (ffffffff8109f2e0)
Location: arch/x86/kernel/apic/apic_common.c:9
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:apic_uv_calc_apicid
```
**Symbols:**

```
ffffffff8109f2e0-ffffffff8109f328: apic_default_calc_apicid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
u32 apic_default_calc_apicid(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic_common.c (ffffffff810a2270)
Location: arch/x86/kernel/apic/apic_common.c:9
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:apic_uv_calc_apicid
```
**Symbols:**

```
ffffffff810a2270-ffffffff810a22b8: apic_default_calc_apicid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
u32 apic_default_calc_apicid(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic_common.c (ffffffff810a8fe0)
Location: arch/x86/kernel/apic/apic_common.c:11
Inline: False
```
**Symbols:**

```
ffffffff810a8fe0-ffffffff810a9027: apic_default_calc_apicid (STB_GLOBAL)
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
u32 apic_default_calc_apicid(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic_common.c (ffffffff810670e0)
Location: arch/x86/kernel/apic/apic_common.c:9
Inline: False
```
**Symbols:**

```
ffffffff810670e0-ffffffff81067100: apic_default_calc_apicid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
u32 apic_default_calc_apicid(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic_common.c (ffffffff810574a0)
Location: arch/x86/kernel/apic/apic_common.c:9
Inline: False
```
**Symbols:**

```
ffffffff810574a0-ffffffff810574c0: apic_default_calc_apicid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
u32 apic_default_calc_apicid(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic_common.c (ffffffff81067590)
Location: arch/x86/kernel/apic/apic_common.c:9
Inline: False
```
**Symbols:**

```
ffffffff81067590-ffffffff810675b0: apic_default_calc_apicid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
u32 apic_default_calc_apicid(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic_common.c (ffffffff81068b70)
Location: arch/x86/kernel/apic/apic_common.c:9
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:apic_uv_calc_apicid
```
**Symbols:**

```
ffffffff81068b70-ffffffff81068b90: apic_default_calc_apicid (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
