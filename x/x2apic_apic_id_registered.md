# Function: <code>x2apic_apic_id_registered</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate ⚠️</summary>

```c
int x2apic_apic_id_registered();
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff81059630)
Location: arch/x86/include/asm/x2apic.h:17
Inline: False
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff81059ab0)
Location: arch/x86/include/asm/x2apic.h:17
Inline: False
```
**Symbols:**

```
ffffffff81059630-ffffffff81059640: x2apic_apic_id_registered (STB_LOCAL)
ffffffff81059ab0-ffffffff81059ac0: x2apic_apic_id_registered (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate ⚠️</summary>

```c
int x2apic_apic_id_registered();
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff81059880)
Location: arch/x86/include/asm/x2apic.h:17
Inline: False
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff81059d10)
Location: arch/x86/include/asm/x2apic.h:17
Inline: False
```
**Symbols:**

```
ffffffff81059880-ffffffff81059890: x2apic_apic_id_registered (STB_LOCAL)
ffffffff81059d10-ffffffff81059d20: x2apic_apic_id_registered (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate ⚠️</summary>

```c
int x2apic_apic_id_registered();
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8105c630)
Location: arch/x86/include/asm/x2apic.h:17
Inline: False
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8105cad0)
Location: arch/x86/include/asm/x2apic.h:17
Inline: False
```
**Symbols:**

```
ffffffff8105c630-ffffffff8105c640: x2apic_apic_id_registered (STB_LOCAL)
ffffffff8105cad0-ffffffff8105cae0: x2apic_apic_id_registered (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate ⚠️</summary>

```c
int x2apic_apic_id_registered();
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8105bd60)
Location: arch/x86/include/asm/x2apic.h:17
Inline: False
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8105c210)
Location: arch/x86/include/asm/x2apic.h:17
Inline: False
```
**Symbols:**

```
ffffffff8105bd60-ffffffff8105bd70: x2apic_apic_id_registered (STB_LOCAL)
ffffffff8105c210-ffffffff8105c220: x2apic_apic_id_registered (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int x2apic_apic_id_registered();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8105fdf0)
Location: arch/x86/kernel/apic/x2apic_phys.c:109
Inline: False
```
**Symbols:**

```
ffffffff8105fdf0-ffffffff8105fe00: x2apic_apic_id_registered (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int x2apic_apic_id_registered();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff81062ee0)
Location: arch/x86/kernel/apic/x2apic_phys.c:109
Inline: False
```
**Symbols:**

```
ffffffff81062ee0-ffffffff81062ef0: x2apic_apic_id_registered (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int x2apic_apic_id_registered();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff81068be0)
Location: arch/x86/kernel/apic/x2apic_phys.c:109
Inline: False
```
**Symbols:**

```
ffffffff81068be0-ffffffff81068bf0: x2apic_apic_id_registered (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int x2apic_apic_id_registered();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8106c3f0)
Location: arch/x86/kernel/apic/x2apic_phys.c:109
Inline: False
```
**Symbols:**

```
ffffffff8106c3f0-ffffffff8106c400: x2apic_apic_id_registered (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int x2apic_apic_id_registered();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8106daf0)
Location: arch/x86/kernel/apic/x2apic_phys.c:104
Inline: False
```
**Symbols:**

```
ffffffff8106daf0-ffffffff8106db00: x2apic_apic_id_registered (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int x2apic_apic_id_registered();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff81074fb0)
Location: arch/x86/kernel/apic/x2apic_phys.c:104
Inline: False
```
**Symbols:**

```
ffffffff81074fb0-ffffffff81074fc0: x2apic_apic_id_registered (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int x2apic_apic_id_registered();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff810755e0)
Location: arch/x86/kernel/apic/x2apic_phys.c:115
Inline: False
```
**Symbols:**

```
ffffffff810755e0-ffffffff810755f0: x2apic_apic_id_registered (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int x2apic_apic_id_registered();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff81076080)
Location: arch/x86/kernel/apic/x2apic_phys.c:115
Inline: False
```
**Symbols:**

```
ffffffff81076080-ffffffff81076090: x2apic_apic_id_registered (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int x2apic_apic_id_registered();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff81083680)
Location: arch/x86/kernel/apic/x2apic_phys.c:115
Inline: False
```
**Symbols:**

```
ffffffff81083680-ffffffff81083690: x2apic_apic_id_registered (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int x2apic_apic_id_registered();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff81093580)
Location: arch/x86/kernel/apic/x2apic_phys.c:115
Inline: False
```
**Symbols:**

```
ffffffff81093580-ffffffff81093594: x2apic_apic_id_registered (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int x2apic_apic_id_registered();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff810a8b40)
Location: arch/x86/kernel/apic/x2apic_phys.c:115
Inline: False
```
**Symbols:**

```
ffffffff810a8b40-ffffffff810a8b54: x2apic_apic_id_registered (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int x2apic_apic_id_registered();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff810abd70)
Location: arch/x86/kernel/apic/x2apic_phys.c:118
Inline: False
```
**Symbols:**

```
ffffffff810abd70-ffffffff810abd84: x2apic_apic_id_registered (STB_GLOBAL)
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
int x2apic_apic_id_registered();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8106ca90)
Location: arch/x86/kernel/apic/x2apic_phys.c:104
Inline: False
```
**Symbols:**

```
ffffffff8106ca90-ffffffff8106caa0: x2apic_apic_id_registered (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int x2apic_apic_id_registered();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8105cda0)
Location: arch/x86/kernel/apic/x2apic_phys.c:104
Inline: False
```
**Symbols:**

```
ffffffff8105cda0-ffffffff8105cdb0: x2apic_apic_id_registered (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int x2apic_apic_id_registered();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8106cf40)
Location: arch/x86/kernel/apic/x2apic_phys.c:104
Inline: False
```
**Symbols:**

```
ffffffff8106cf40-ffffffff8106cf50: x2apic_apic_id_registered (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int x2apic_apic_id_registered();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8106f1c0)
Location: arch/x86/kernel/apic/x2apic_phys.c:104
Inline: False
```
**Symbols:**

```
ffffffff8106f1c0-ffffffff8106f1d0: x2apic_apic_id_registered (STB_GLOBAL)
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
