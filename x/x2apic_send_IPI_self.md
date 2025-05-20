# Function: <code>x2apic_send_IPI_self</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate ⚠️</summary>

```c
void x2apic_send_IPI_self(int vector);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff81059680)
Location: arch/x86/include/asm/x2apic.h:44
Inline: False
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff81059b00)
Location: arch/x86/include/asm/x2apic.h:44
Inline: False
```
**Symbols:**

```
ffffffff81059680-ffffffff8105969f: x2apic_send_IPI_self (STB_LOCAL)
ffffffff81059b00-ffffffff81059b1f: x2apic_send_IPI_self (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate ⚠️</summary>

```c
void x2apic_send_IPI_self(int vector);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff810598d0)
Location: arch/x86/include/asm/x2apic.h:44
Inline: False
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff81059da0)
Location: arch/x86/include/asm/x2apic.h:44
Inline: False
```
**Symbols:**

```
ffffffff810598d0-ffffffff810598ef: x2apic_send_IPI_self (STB_LOCAL)
ffffffff81059da0-ffffffff81059dbf: x2apic_send_IPI_self (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate ⚠️</summary>

```c
void x2apic_send_IPI_self(int vector);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8105c680)
Location: arch/x86/include/asm/x2apic.h:44
Inline: False
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8105cb60)
Location: arch/x86/include/asm/x2apic.h:44
Inline: False
```
**Symbols:**

```
ffffffff8105c680-ffffffff8105c69f: x2apic_send_IPI_self (STB_LOCAL)
ffffffff8105cb60-ffffffff8105cb7f: x2apic_send_IPI_self (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate ⚠️</summary>

```c
void x2apic_send_IPI_self(int vector);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8105bdb0)
Location: arch/x86/include/asm/x2apic.h:44
Inline: False
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8105c2a0)
Location: arch/x86/include/asm/x2apic.h:44
Inline: False
```
**Symbols:**

```
ffffffff8105bdb0-ffffffff8105bdcf: x2apic_send_IPI_self (STB_LOCAL)
ffffffff8105c2a0-ffffffff8105c2bf: x2apic_send_IPI_self (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void x2apic_send_IPI_self(int vector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8105fe40)
Location: arch/x86/kernel/apic/x2apic_phys.c:135
Inline: False
```
**Symbols:**

```
ffffffff8105fe40-ffffffff8105fe62: x2apic_send_IPI_self (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void x2apic_send_IPI_self(int vector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff81062f30)
Location: arch/x86/kernel/apic/x2apic_phys.c:135
Inline: False
```
**Symbols:**

```
ffffffff81062f30-ffffffff81062f52: x2apic_send_IPI_self (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void x2apic_send_IPI_self(int vector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff81068c30)
Location: arch/x86/kernel/apic/x2apic_phys.c:135
Inline: False
```
**Symbols:**

```
ffffffff81068c30-ffffffff81068c52: x2apic_send_IPI_self (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void x2apic_send_IPI_self(int vector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8106c440)
Location: arch/x86/kernel/apic/x2apic_phys.c:135
Inline: False
```
**Symbols:**

```
ffffffff8106c440-ffffffff8106c462: x2apic_send_IPI_self (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void x2apic_send_IPI_self(int vector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8106db40)
Location: arch/x86/kernel/apic/x2apic_phys.c:138
Inline: False
```
**Symbols:**

```
ffffffff8106db40-ffffffff8106db62: x2apic_send_IPI_self (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void x2apic_send_IPI_self(int vector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff81075000)
Location: arch/x86/kernel/apic/x2apic_phys.c:138
Inline: False
```
**Symbols:**

```
ffffffff81075000-ffffffff81075022: x2apic_send_IPI_self (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void x2apic_send_IPI_self(int vector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff81075630)
Location: arch/x86/kernel/apic/x2apic_phys.c:150
Inline: False
```
**Symbols:**

```
ffffffff81075630-ffffffff81075652: x2apic_send_IPI_self (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void x2apic_send_IPI_self(int vector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff810760d0)
Location: arch/x86/kernel/apic/x2apic_phys.c:150
Inline: False
```
**Symbols:**

```
ffffffff810760d0-ffffffff810760f2: x2apic_send_IPI_self (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void x2apic_send_IPI_self(int vector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff810836b0)
Location: arch/x86/kernel/apic/x2apic_phys.c:150
Inline: False
```
**Symbols:**

```
ffffffff810836b0-ffffffff810836d2: x2apic_send_IPI_self (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void x2apic_send_IPI_self(int vector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff810935e0)
Location: arch/x86/kernel/apic/x2apic_phys.c:150
Inline: False
```
**Symbols:**

```
ffffffff810935e0-ffffffff8109360c: x2apic_send_IPI_self (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void x2apic_send_IPI_self(int vector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff810a8bd0)
Location: arch/x86/kernel/apic/x2apic_phys.c:150
Inline: False
```
**Symbols:**

```
ffffffff810a8bd0-ffffffff810a8bfc: x2apic_send_IPI_self (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void x2apic_send_IPI_self(int vector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff810abe00)
Location: arch/x86/kernel/apic/x2apic_phys.c:153
Inline: False
```
**Symbols:**

```
ffffffff810abe00-ffffffff810abe2c: x2apic_send_IPI_self (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void x2apic_send_IPI_self(int vector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff810b2b70)
Location: arch/x86/kernel/apic/x2apic_phys.c:105
Inline: False
```
**Symbols:**

```
ffffffff810b2b70-ffffffff810b2b8f: x2apic_send_IPI_self (STB_GLOBAL)
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
void x2apic_send_IPI_self(int vector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8106cae0)
Location: arch/x86/kernel/apic/x2apic_phys.c:138
Inline: False
```
**Symbols:**

```
ffffffff8106cae0-ffffffff8106cb02: x2apic_send_IPI_self (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void x2apic_send_IPI_self(int vector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8105cdf0)
Location: arch/x86/kernel/apic/x2apic_phys.c:138
Inline: False
```
**Symbols:**

```
ffffffff8105cdf0-ffffffff8105ce12: x2apic_send_IPI_self (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void x2apic_send_IPI_self(int vector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8106cf90)
Location: arch/x86/kernel/apic/x2apic_phys.c:138
Inline: False
```
**Symbols:**

```
ffffffff8106cf90-ffffffff8106cfb2: x2apic_send_IPI_self (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void x2apic_send_IPI_self(int vector);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8106f210)
Location: arch/x86/kernel/apic/x2apic_phys.c:138
Inline: False
```
**Symbols:**

```
ffffffff8106f210-ffffffff8106f232: x2apic_send_IPI_self (STB_GLOBAL)
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
