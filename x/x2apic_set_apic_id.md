# Function: <code>x2apic_set_apic_id</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate ⚠️</summary>

```c
long unsigned int x2apic_set_apic_id(unsigned int id);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff81059650)
Location: arch/x86/include/asm/x2apic.h:34
Inline: False
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff81059ad0)
Location: arch/x86/include/asm/x2apic.h:34
Inline: False
```
**Symbols:**

```
ffffffff81059650-ffffffff8105965d: x2apic_set_apic_id (STB_LOCAL)
ffffffff81059ad0-ffffffff81059add: x2apic_set_apic_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate ⚠️</summary>

```c
long unsigned int x2apic_set_apic_id(unsigned int id);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff810598a0)
Location: arch/x86/include/asm/x2apic.h:34
Inline: False
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff81059d70)
Location: arch/x86/include/asm/x2apic.h:34
Inline: False
```
**Symbols:**

```
ffffffff810598a0-ffffffff810598ad: x2apic_set_apic_id (STB_LOCAL)
ffffffff81059d70-ffffffff81059d7d: x2apic_set_apic_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate ⚠️</summary>

```c
long unsigned int x2apic_set_apic_id(unsigned int id);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8105c650)
Location: arch/x86/include/asm/x2apic.h:34
Inline: False
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8105cb30)
Location: arch/x86/include/asm/x2apic.h:34
Inline: False
```
**Symbols:**

```
ffffffff8105c650-ffffffff8105c65d: x2apic_set_apic_id (STB_LOCAL)
ffffffff8105cb30-ffffffff8105cb3d: x2apic_set_apic_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate ⚠️</summary>

```c
long unsigned int x2apic_set_apic_id(unsigned int id);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8105bd80)
Location: arch/x86/include/asm/x2apic.h:34
Inline: False
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8105c270)
Location: arch/x86/include/asm/x2apic.h:34
Inline: False
```
**Symbols:**

```
ffffffff8105bd80-ffffffff8105bd8d: x2apic_set_apic_id (STB_LOCAL)
ffffffff8105c270-ffffffff8105c27d: x2apic_set_apic_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
u32 x2apic_set_apic_id(unsigned int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8105fe10)
Location: arch/x86/kernel/apic/x2apic_phys.c:125
Inline: False
```
**Symbols:**

```
ffffffff8105fe10-ffffffff8105fe1d: x2apic_set_apic_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
u32 x2apic_set_apic_id(unsigned int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff81062f00)
Location: arch/x86/kernel/apic/x2apic_phys.c:125
Inline: False
```
**Symbols:**

```
ffffffff81062f00-ffffffff81062f0d: x2apic_set_apic_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
u32 x2apic_set_apic_id(unsigned int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff81068c00)
Location: arch/x86/kernel/apic/x2apic_phys.c:125
Inline: False
```
**Symbols:**

```
ffffffff81068c00-ffffffff81068c0d: x2apic_set_apic_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
u32 x2apic_set_apic_id(unsigned int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8106c410)
Location: arch/x86/kernel/apic/x2apic_phys.c:125
Inline: False
```
**Symbols:**

```
ffffffff8106c410-ffffffff8106c41d: x2apic_set_apic_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
u32 x2apic_set_apic_id(unsigned int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8106db10)
Location: arch/x86/kernel/apic/x2apic_phys.c:128
Inline: False
```
**Symbols:**

```
ffffffff8106db10-ffffffff8106db1d: x2apic_set_apic_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
u32 x2apic_set_apic_id(unsigned int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff81074fd0)
Location: arch/x86/kernel/apic/x2apic_phys.c:128
Inline: False
```
**Symbols:**

```
ffffffff81074fd0-ffffffff81074fdd: x2apic_set_apic_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
u32 x2apic_set_apic_id(unsigned int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff81075600)
Location: arch/x86/kernel/apic/x2apic_phys.c:140
Inline: False
```
**Symbols:**

```
ffffffff81075600-ffffffff8107560d: x2apic_set_apic_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
u32 x2apic_set_apic_id(unsigned int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff810760a0)
Location: arch/x86/kernel/apic/x2apic_phys.c:140
Inline: False
```
**Symbols:**

```
ffffffff810760a0-ffffffff810760ad: x2apic_set_apic_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
u32 x2apic_set_apic_id(unsigned int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff810836a0)
Location: arch/x86/kernel/apic/x2apic_phys.c:140
Inline: False
```
**Symbols:**

```
ffffffff810836a0-ffffffff810836ad: x2apic_set_apic_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
u32 x2apic_set_apic_id(unsigned int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff810935c0)
Location: arch/x86/kernel/apic/x2apic_phys.c:140
Inline: False
```
**Symbols:**

```
ffffffff810935c0-ffffffff810935d3: x2apic_set_apic_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
u32 x2apic_set_apic_id(unsigned int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff810a8ba0)
Location: arch/x86/kernel/apic/x2apic_phys.c:140
Inline: False
```
**Symbols:**

```
ffffffff810a8ba0-ffffffff810a8bb3: x2apic_set_apic_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
u32 x2apic_set_apic_id(unsigned int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff810abdd0)
Location: arch/x86/kernel/apic/x2apic_phys.c:143
Inline: False
```
**Symbols:**

```
ffffffff810abdd0-ffffffff810abde3: x2apic_set_apic_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
u32 x2apic_set_apic_id(u32 id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (0)
Location: arch/x86/kernel/apic/x2apic_phys.c:132
Inline: False
```
**Symbols:**

```
ffffffff810b2d20-ffffffff810b2d33: x2apic_set_apic_id (STB_GLOBAL)
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
u32 x2apic_set_apic_id(unsigned int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8106cab0)
Location: arch/x86/kernel/apic/x2apic_phys.c:128
Inline: False
```
**Symbols:**

```
ffffffff8106cab0-ffffffff8106cabd: x2apic_set_apic_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
u32 x2apic_set_apic_id(unsigned int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8105cdc0)
Location: arch/x86/kernel/apic/x2apic_phys.c:128
Inline: False
```
**Symbols:**

```
ffffffff8105cdc0-ffffffff8105cdcd: x2apic_set_apic_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
u32 x2apic_set_apic_id(unsigned int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8106cf60)
Location: arch/x86/kernel/apic/x2apic_phys.c:128
Inline: False
```
**Symbols:**

```
ffffffff8106cf60-ffffffff8106cf6d: x2apic_set_apic_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
u32 x2apic_set_apic_id(unsigned int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8106f1e0)
Location: arch/x86/kernel/apic/x2apic_phys.c:128
Inline: False
```
**Symbols:**

```
ffffffff8106f1e0-ffffffff8106f1ed: x2apic_set_apic_id (STB_GLOBAL)
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
<code>long unsigned int</code> ➡️ <code>u32</code>
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
<code>unsigned int id</code> ➡️ <code>u32 id</code>
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
