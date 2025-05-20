# Function: <code>uv_phys_pkg_id</code>

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
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int uv_phys_pkg_id(int initial_apicid, int index_msb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff8106d290)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:627
Inline: False
```
**Symbols:**

```
ffffffff8106d290-ffffffff8106d2c5: uv_phys_pkg_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int uv_phys_pkg_id(int initial_apicid, int index_msb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff81074410)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:661
Inline: False
```
**Symbols:**

```
ffffffff81074410-ffffffff81074448: uv_phys_pkg_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int uv_phys_pkg_id(int initial_apicid, int index_msb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff81074f90)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:812
Inline: False
```
**Symbols:**

```
ffffffff81074f90-ffffffff81074fbb: uv_phys_pkg_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int uv_phys_pkg_id(int initial_apicid, int index_msb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff81075a30)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:808
Inline: False
```
**Symbols:**

```
ffffffff81075a30-ffffffff81075a5b: uv_phys_pkg_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int uv_phys_pkg_id(int initial_apicid, int index_msb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (0)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:808
Inline: False
```
**Symbols:**

```
ffffffff81082ff0-ffffffff81083028: uv_phys_pkg_id (STB_LOCAL)
ffffffff81c9e56f-ffffffff81c9e58e: uv_phys_pkg_id.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int uv_phys_pkg_id(int initial_apicid, int index_msb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (0)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:814
Inline: False
```
**Symbols:**

```
ffffffff81092dd0-ffffffff81092e14: uv_phys_pkg_id (STB_LOCAL)
ffffffff81e4d9c4-ffffffff81e4d9e3: uv_phys_pkg_id.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int uv_phys_pkg_id(int initial_apicid, int index_msb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (0)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:814
Inline: False
```
**Symbols:**

```
ffffffff810a7ff0-ffffffff810a8034: uv_phys_pkg_id (STB_LOCAL)
ffffffff82053e54-ffffffff82053e73: uv_phys_pkg_id.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int uv_phys_pkg_id(int initial_apicid, int index_msb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (0)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:815
Inline: False
```
**Symbols:**

```
ffffffff810ab260-ffffffff810ab2a4: uv_phys_pkg_id (STB_LOCAL)
ffffffff820d2476-ffffffff820d2495: uv_phys_pkg_id.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
u32 uv_phys_pkg_id(u32 initial_apicid, int index_msb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (0)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:792
Inline: False
```
**Symbols:**

```
ffffffff810b2110-ffffffff810b2150: uv_phys_pkg_id (STB_LOCAL)
ffffffff821ad1a7-ffffffff821ad1c6: uv_phys_pkg_id.cold (STB_LOCAL)
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int uv_phys_pkg_id(int initial_apicid, int index_msb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff8106e9c0)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:627
Inline: False
```
**Symbols:**

```
ffffffff8106e9c0-ffffffff8106e9ef: uv_phys_pkg_id (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<code>int initial_apicid</code> ➡️ <code>u32 initial_apicid</code>
</li>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>u32</code>
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
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
