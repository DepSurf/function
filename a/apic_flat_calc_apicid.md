# Function: <code>apic_flat_calc_apicid</code>

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
u32 apic_flat_calc_apicid(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic_common.c (ffffffff8105ac50)
Location: arch/x86/kernel/apic/apic_common.c:14
Inline: False
```
**Symbols:**

```
ffffffff8105ac50-ffffffff8105ac64: apic_flat_calc_apicid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
u32 apic_flat_calc_apicid(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic_common.c (ffffffff8105dc50)
Location: arch/x86/kernel/apic/apic_common.c:14
Inline: False
```
**Symbols:**

```
ffffffff8105dc50-ffffffff8105dc64: apic_flat_calc_apicid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
u32 apic_flat_calc_apicid(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic_common.c (ffffffff810638e0)
Location: arch/x86/kernel/apic/apic_common.c:14
Inline: False
```
**Symbols:**

```
ffffffff810638e0-ffffffff810638f4: apic_flat_calc_apicid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
u32 apic_flat_calc_apicid(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic_common.c (ffffffff81066fa0)
Location: arch/x86/kernel/apic/apic_common.c:14
Inline: False
```
**Symbols:**

```
ffffffff81066fa0-ffffffff81066fb4: apic_flat_calc_apicid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
u32 apic_flat_calc_apicid(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic_common.c (ffffffff81067610)
Location: arch/x86/kernel/apic/apic_common.c:14
Inline: False
```
**Symbols:**

```
ffffffff81067610-ffffffff81067624: apic_flat_calc_apicid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
u32 apic_flat_calc_apicid(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic_common.c (ffffffff8106e360)
Location: arch/x86/kernel/apic/apic_common.c:14
Inline: False
```
**Symbols:**

```
ffffffff8106e360-ffffffff8106e374: apic_flat_calc_apicid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
u32 apic_flat_calc_apicid(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic_common.c (ffffffff8106f7e0)
Location: arch/x86/kernel/apic/apic_common.c:14
Inline: False
```
**Symbols:**

```
ffffffff8106f7e0-ffffffff8106f7f4: apic_flat_calc_apicid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
u32 apic_flat_calc_apicid(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic_common.c (ffffffff81070310)
Location: arch/x86/kernel/apic/apic_common.c:14
Inline: False
```
**Symbols:**

```
ffffffff81070310-ffffffff81070324: apic_flat_calc_apicid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
u32 apic_flat_calc_apicid(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/apic_common.c (0)
Location: arch/x86/kernel/apic/apic_common.c:14
Inline: False
```
**Symbols:**

```
ffffffff81c9dcd9-ffffffff81c9dd00: apic_flat_calc_apicid.cold (STB_LOCAL)
ffffffff8107beb0-ffffffff8107bec8: apic_flat_calc_apicid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
u32 apic_flat_calc_apicid(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/apic_common.c (0)
Location: arch/x86/kernel/apic/apic_common.c:14
Inline: False
```
**Symbols:**

```
ffffffff81e4d15a-ffffffff81e4d18d: apic_flat_calc_apicid.cold (STB_LOCAL)
ffffffff8108b120-ffffffff8108b144: apic_flat_calc_apicid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
u32 apic_flat_calc_apicid(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/apic_common.c (0)
Location: arch/x86/kernel/apic/apic_common.c:14
Inline: False
```
**Symbols:**

```
ffffffff82053cb8-ffffffff82053ceb: apic_flat_calc_apicid.cold (STB_LOCAL)
ffffffff8109f340-ffffffff8109f364: apic_flat_calc_apicid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
u32 apic_flat_calc_apicid(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/apic_common.c (0)
Location: arch/x86/kernel/apic/apic_common.c:14
Inline: False
```
**Symbols:**

```
ffffffff820d22af-ffffffff820d22e2: apic_flat_calc_apicid.cold (STB_LOCAL)
ffffffff810a22d0-ffffffff810a22f4: apic_flat_calc_apicid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
u32 apic_flat_calc_apicid(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/apic_common.c (0)
Location: arch/x86/kernel/apic/apic_common.c:16
Inline: False
```
**Symbols:**

```
ffffffff821acf34-ffffffff821acf67: apic_flat_calc_apicid.cold (STB_LOCAL)
ffffffff810a9040-ffffffff810a9064: apic_flat_calc_apicid (STB_GLOBAL)
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
u32 apic_flat_calc_apicid(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic_common.c (ffffffff81067100)
Location: arch/x86/kernel/apic/apic_common.c:14
Inline: False
```
**Symbols:**

```
ffffffff81067100-ffffffff81067114: apic_flat_calc_apicid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
u32 apic_flat_calc_apicid(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic_common.c (ffffffff810574c0)
Location: arch/x86/kernel/apic/apic_common.c:14
Inline: False
```
**Symbols:**

```
ffffffff810574c0-ffffffff810574d4: apic_flat_calc_apicid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
u32 apic_flat_calc_apicid(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic_common.c (ffffffff810675b0)
Location: arch/x86/kernel/apic/apic_common.c:14
Inline: False
```
**Symbols:**

```
ffffffff810675b0-ffffffff810675c4: apic_flat_calc_apicid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
u32 apic_flat_calc_apicid(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic_common.c (ffffffff81068b90)
Location: arch/x86/kernel/apic/apic_common.c:14
Inline: False
```
**Symbols:**

```
ffffffff81068b90-ffffffff81068ba4: apic_flat_calc_apicid (STB_GLOBAL)
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
