# Function: <code>x2apic_phys_pkg_id</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate ⚠️</summary>

```c
int x2apic_phys_pkg_id(int initial_apicid, int index_msb);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff81059660)
Location: arch/x86/include/asm/x2apic.h:39
Inline: False
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff81059ae0)
Location: arch/x86/include/asm/x2apic.h:39
Inline: False
```
**Symbols:**

```
ffffffff81059660-ffffffff81059671: x2apic_phys_pkg_id (STB_LOCAL)
ffffffff81059ae0-ffffffff81059af1: x2apic_phys_pkg_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate ⚠️</summary>

```c
int x2apic_phys_pkg_id(int initial_apicid, int index_msb);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff810598b0)
Location: arch/x86/include/asm/x2apic.h:39
Inline: False
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff81059d80)
Location: arch/x86/include/asm/x2apic.h:39
Inline: False
```
**Symbols:**

```
ffffffff810598b0-ffffffff810598c1: x2apic_phys_pkg_id (STB_LOCAL)
ffffffff81059d80-ffffffff81059d91: x2apic_phys_pkg_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate ⚠️</summary>

```c
int x2apic_phys_pkg_id(int initial_apicid, int index_msb);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8105c660)
Location: arch/x86/include/asm/x2apic.h:39
Inline: False
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8105cb40)
Location: arch/x86/include/asm/x2apic.h:39
Inline: False
```
**Symbols:**

```
ffffffff8105c660-ffffffff8105c671: x2apic_phys_pkg_id (STB_LOCAL)
ffffffff8105cb40-ffffffff8105cb51: x2apic_phys_pkg_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate ⚠️</summary>

```c
int x2apic_phys_pkg_id(int initial_apicid, int index_msb);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8105bd90)
Location: arch/x86/include/asm/x2apic.h:39
Inline: False
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8105c280)
Location: arch/x86/include/asm/x2apic.h:39
Inline: False
```
**Symbols:**

```
ffffffff8105bd90-ffffffff8105bda1: x2apic_phys_pkg_id (STB_LOCAL)
ffffffff8105c280-ffffffff8105c291: x2apic_phys_pkg_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int x2apic_phys_pkg_id(int initial_apicid, int index_msb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8105fe20)
Location: arch/x86/kernel/apic/x2apic_phys.c:130
Inline: False
```
**Symbols:**

```
ffffffff8105fe20-ffffffff8105fe31: x2apic_phys_pkg_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int x2apic_phys_pkg_id(int initial_apicid, int index_msb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff81062f10)
Location: arch/x86/kernel/apic/x2apic_phys.c:130
Inline: False
```
**Symbols:**

```
ffffffff81062f10-ffffffff81062f21: x2apic_phys_pkg_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int x2apic_phys_pkg_id(int initial_apicid, int index_msb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff81068c10)
Location: arch/x86/kernel/apic/x2apic_phys.c:130
Inline: False
```
**Symbols:**

```
ffffffff81068c10-ffffffff81068c21: x2apic_phys_pkg_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int x2apic_phys_pkg_id(int initial_apicid, int index_msb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8106c420)
Location: arch/x86/kernel/apic/x2apic_phys.c:130
Inline: False
```
**Symbols:**

```
ffffffff8106c420-ffffffff8106c431: x2apic_phys_pkg_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int x2apic_phys_pkg_id(int initial_apicid, int index_msb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8106db20)
Location: arch/x86/kernel/apic/x2apic_phys.c:133
Inline: False
```
**Symbols:**

```
ffffffff8106db20-ffffffff8106db31: x2apic_phys_pkg_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int x2apic_phys_pkg_id(int initial_apicid, int index_msb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff81074fe0)
Location: arch/x86/kernel/apic/x2apic_phys.c:133
Inline: False
```
**Symbols:**

```
ffffffff81074fe0-ffffffff81074ff1: x2apic_phys_pkg_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int x2apic_phys_pkg_id(int initial_apicid, int index_msb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff81075610)
Location: arch/x86/kernel/apic/x2apic_phys.c:145
Inline: False
```
**Symbols:**

```
ffffffff81075610-ffffffff81075621: x2apic_phys_pkg_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int x2apic_phys_pkg_id(int initial_apicid, int index_msb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff810760b0)
Location: arch/x86/kernel/apic/x2apic_phys.c:145
Inline: False
```
**Symbols:**

```
ffffffff810760b0-ffffffff810760c1: x2apic_phys_pkg_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int x2apic_phys_pkg_id(int initial_apicid, int index_msb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (0)
Location: arch/x86/kernel/apic/x2apic_phys.c:145
Inline: False
```
**Symbols:**

```
ffffffff81c9e747-ffffffff81c9e76e: x2apic_phys_pkg_id.cold (STB_LOCAL)
ffffffff810836e0-ffffffff810836f5: x2apic_phys_pkg_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int x2apic_phys_pkg_id(int initial_apicid, int index_msb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (0)
Location: arch/x86/kernel/apic/x2apic_phys.c:145
Inline: False
```
**Symbols:**

```
ffffffff81e4db8d-ffffffff81e4dbc0: x2apic_phys_pkg_id.cold (STB_LOCAL)
ffffffff81093610-ffffffff81093631: x2apic_phys_pkg_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int x2apic_phys_pkg_id(int initial_apicid, int index_msb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (0)
Location: arch/x86/kernel/apic/x2apic_phys.c:145
Inline: False
```
**Symbols:**

```
ffffffff82054011-ffffffff82054044: x2apic_phys_pkg_id.cold (STB_LOCAL)
ffffffff810a8c10-ffffffff810a8c31: x2apic_phys_pkg_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int x2apic_phys_pkg_id(int initial_apicid, int index_msb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (0)
Location: arch/x86/kernel/apic/x2apic_phys.c:148
Inline: False
```
**Symbols:**

```
ffffffff820d258f-ffffffff820d25c2: x2apic_phys_pkg_id.cold (STB_LOCAL)
ffffffff810abe40-ffffffff810abe61: x2apic_phys_pkg_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
u32 x2apic_phys_pkg_id(u32 initial_apicid, int index_msb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (0)
Location: arch/x86/kernel/apic/x2apic_phys.c:137
Inline: False
```
**Symbols:**

```
ffffffff821ad2c0-ffffffff821ad2f2: x2apic_phys_pkg_id.cold (STB_LOCAL)
ffffffff810b2ba0-ffffffff810b2bc1: x2apic_phys_pkg_id (STB_GLOBAL)
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
int x2apic_phys_pkg_id(int initial_apicid, int index_msb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8106cac0)
Location: arch/x86/kernel/apic/x2apic_phys.c:133
Inline: False
```
**Symbols:**

```
ffffffff8106cac0-ffffffff8106cad1: x2apic_phys_pkg_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int x2apic_phys_pkg_id(int initial_apicid, int index_msb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8105cdd0)
Location: arch/x86/kernel/apic/x2apic_phys.c:133
Inline: False
```
**Symbols:**

```
ffffffff8105cdd0-ffffffff8105cde1: x2apic_phys_pkg_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int x2apic_phys_pkg_id(int initial_apicid, int index_msb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8106cf70)
Location: arch/x86/kernel/apic/x2apic_phys.c:133
Inline: False
```
**Symbols:**

```
ffffffff8106cf70-ffffffff8106cf81: x2apic_phys_pkg_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int x2apic_phys_pkg_id(int initial_apicid, int index_msb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8106f1f0)
Location: arch/x86/kernel/apic/x2apic_phys.c:133
Inline: False
```
**Symbols:**

```
ffffffff8106f1f0-ffffffff8106f201: x2apic_phys_pkg_id (STB_GLOBAL)
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
