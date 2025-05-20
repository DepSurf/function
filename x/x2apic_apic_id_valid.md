# Function: <code>x2apic_apic_id_valid</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate ⚠️</summary>

```c
int x2apic_apic_id_valid(int apicid);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff81059620)
Location: arch/x86/include/asm/x2apic.h:12
Inline: False
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff81059aa0)
Location: arch/x86/include/asm/x2apic.h:12
Inline: False
```
**Symbols:**

```
ffffffff81059620-ffffffff81059630: x2apic_apic_id_valid (STB_LOCAL)
ffffffff81059aa0-ffffffff81059ab0: x2apic_apic_id_valid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate ⚠️</summary>

```c
int x2apic_apic_id_valid(int apicid);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff81059870)
Location: arch/x86/include/asm/x2apic.h:12
Inline: False
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff81059d00)
Location: arch/x86/include/asm/x2apic.h:12
Inline: False
```
**Symbols:**

```
ffffffff81059870-ffffffff81059880: x2apic_apic_id_valid (STB_LOCAL)
ffffffff81059d00-ffffffff81059d10: x2apic_apic_id_valid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate ⚠️</summary>

```c
int x2apic_apic_id_valid(int apicid);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8105c620)
Location: arch/x86/include/asm/x2apic.h:12
Inline: False
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8105cac0)
Location: arch/x86/include/asm/x2apic.h:12
Inline: False
```
**Symbols:**

```
ffffffff8105c620-ffffffff8105c630: x2apic_apic_id_valid (STB_LOCAL)
ffffffff8105cac0-ffffffff8105cad0: x2apic_apic_id_valid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate ⚠️</summary>

```c
int x2apic_apic_id_valid(int apicid);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8105bd50)
Location: arch/x86/include/asm/x2apic.h:12
Inline: False
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8105c200)
Location: arch/x86/include/asm/x2apic.h:12
Inline: False
```
**Symbols:**

```
ffffffff8105bd50-ffffffff8105bd60: x2apic_apic_id_valid (STB_LOCAL)
ffffffff8105c200-ffffffff8105c210: x2apic_apic_id_valid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int x2apic_apic_id_valid(int apicid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8105fde0)
Location: arch/x86/kernel/apic/x2apic_phys.c:104
Inline: False
```
**Symbols:**

```
ffffffff8105fde0-ffffffff8105fdf0: x2apic_apic_id_valid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int x2apic_apic_id_valid(u32 apicid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff81062ed0)
Location: arch/x86/kernel/apic/x2apic_phys.c:104
Inline: False
```
**Symbols:**

```
ffffffff81062ed0-ffffffff81062ee0: x2apic_apic_id_valid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int x2apic_apic_id_valid(u32 apicid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff81068bd0)
Location: arch/x86/kernel/apic/x2apic_phys.c:104
Inline: False
```
**Symbols:**

```
ffffffff81068bd0-ffffffff81068be0: x2apic_apic_id_valid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int x2apic_apic_id_valid(u32 apicid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8106c3e0)
Location: arch/x86/kernel/apic/x2apic_phys.c:104
Inline: False
```
**Symbols:**

```
ffffffff8106c3e0-ffffffff8106c3f0: x2apic_apic_id_valid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int x2apic_apic_id_valid(u32 apicid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8106dae0)
Location: arch/x86/kernel/apic/x2apic_phys.c:99
Inline: False
```
**Symbols:**

```
ffffffff8106dae0-ffffffff8106daf0: x2apic_apic_id_valid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int x2apic_apic_id_valid(u32 apicid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff81074fa0)
Location: arch/x86/kernel/apic/x2apic_phys.c:99
Inline: False
```
**Symbols:**

```
ffffffff81074fa0-ffffffff81074fb0: x2apic_apic_id_valid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int x2apic_apic_id_valid(u32 apicid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff810755b0)
Location: arch/x86/kernel/apic/x2apic_phys.c:107
Inline: False
```
**Symbols:**

```
ffffffff810755b0-ffffffff810755d3: x2apic_apic_id_valid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int x2apic_apic_id_valid(u32 apicid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff81076050)
Location: arch/x86/kernel/apic/x2apic_phys.c:107
Inline: False
```
**Symbols:**

```
ffffffff81076050-ffffffff81076073: x2apic_apic_id_valid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int x2apic_apic_id_valid(u32 apicid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff81083650)
Location: arch/x86/kernel/apic/x2apic_phys.c:107
Inline: False
```
**Symbols:**

```
ffffffff81083650-ffffffff81083673: x2apic_apic_id_valid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int x2apic_apic_id_valid(u32 apicid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff81093550)
Location: arch/x86/kernel/apic/x2apic_phys.c:107
Inline: False
```
**Symbols:**

```
ffffffff81093550-ffffffff8109357b: x2apic_apic_id_valid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int x2apic_apic_id_valid(u32 apicid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff810a8b00)
Location: arch/x86/kernel/apic/x2apic_phys.c:107
Inline: False
```
**Symbols:**

```
ffffffff810a8b00-ffffffff810a8b2b: x2apic_apic_id_valid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int x2apic_apic_id_valid(u32 apicid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff810abd30)
Location: arch/x86/kernel/apic/x2apic_phys.c:110
Inline: False
```
**Symbols:**

```
ffffffff810abd30-ffffffff810abd5b: x2apic_apic_id_valid (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
int x2apic_apic_id_valid(u32 apicid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8106ca80)
Location: arch/x86/kernel/apic/x2apic_phys.c:99
Inline: False
```
**Symbols:**

```
ffffffff8106ca80-ffffffff8106ca90: x2apic_apic_id_valid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int x2apic_apic_id_valid(u32 apicid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8105cd90)
Location: arch/x86/kernel/apic/x2apic_phys.c:99
Inline: False
```
**Symbols:**

```
ffffffff8105cd90-ffffffff8105cda0: x2apic_apic_id_valid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int x2apic_apic_id_valid(u32 apicid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8106cf30)
Location: arch/x86/kernel/apic/x2apic_phys.c:99
Inline: False
```
**Symbols:**

```
ffffffff8106cf30-ffffffff8106cf40: x2apic_apic_id_valid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int x2apic_apic_id_valid(u32 apicid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8106f1b0)
Location: arch/x86/kernel/apic/x2apic_phys.c:99
Inline: False
```
**Symbols:**

```
ffffffff8106f1b0-ffffffff8106f1c0: x2apic_apic_id_valid (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int apicid</code> ➡️ <code>u32 apicid</code>
</li>
</ul>
</details>
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
