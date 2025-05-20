# Function: <code>x2apic_get_apic_id</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate ⚠️</summary>

```c
unsigned int x2apic_get_apic_id(long unsigned int id);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff81059640)
Location: arch/x86/include/asm/x2apic.h:29
Inline: False
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff81059ac0)
Location: arch/x86/include/asm/x2apic.h:29
Inline: False
```
**Symbols:**

```
ffffffff81059640-ffffffff8105964d: x2apic_get_apic_id (STB_LOCAL)
ffffffff81059ac0-ffffffff81059acd: x2apic_get_apic_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate ⚠️</summary>

```c
unsigned int x2apic_get_apic_id(long unsigned int id);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff81059890)
Location: arch/x86/include/asm/x2apic.h:29
Inline: False
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff81059d60)
Location: arch/x86/include/asm/x2apic.h:29
Inline: False
```
**Symbols:**

```
ffffffff81059890-ffffffff8105989d: x2apic_get_apic_id (STB_LOCAL)
ffffffff81059d60-ffffffff81059d6d: x2apic_get_apic_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate ⚠️</summary>

```c
unsigned int x2apic_get_apic_id(long unsigned int id);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8105c640)
Location: arch/x86/include/asm/x2apic.h:29
Inline: False
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8105cb20)
Location: arch/x86/include/asm/x2apic.h:29
Inline: False
```
**Symbols:**

```
ffffffff8105c640-ffffffff8105c64d: x2apic_get_apic_id (STB_LOCAL)
ffffffff8105cb20-ffffffff8105cb2d: x2apic_get_apic_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate ⚠️</summary>

```c
unsigned int x2apic_get_apic_id(long unsigned int id);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8105bd70)
Location: arch/x86/include/asm/x2apic.h:29
Inline: False
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8105c260)
Location: arch/x86/include/asm/x2apic.h:29
Inline: False
```
**Symbols:**

```
ffffffff8105bd70-ffffffff8105bd7d: x2apic_get_apic_id (STB_LOCAL)
ffffffff8105c260-ffffffff8105c26d: x2apic_get_apic_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
unsigned int x2apic_get_apic_id(long unsigned int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8105fe00)
Location: arch/x86/kernel/apic/x2apic_phys.c:120
Inline: False
```
**Symbols:**

```
ffffffff8105fe00-ffffffff8105fe0d: x2apic_get_apic_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
unsigned int x2apic_get_apic_id(long unsigned int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff81062ef0)
Location: arch/x86/kernel/apic/x2apic_phys.c:120
Inline: False
```
**Symbols:**

```
ffffffff81062ef0-ffffffff81062efd: x2apic_get_apic_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
unsigned int x2apic_get_apic_id(long unsigned int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff81068bf0)
Location: arch/x86/kernel/apic/x2apic_phys.c:120
Inline: False
```
**Symbols:**

```
ffffffff81068bf0-ffffffff81068bfd: x2apic_get_apic_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
unsigned int x2apic_get_apic_id(long unsigned int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8106c400)
Location: arch/x86/kernel/apic/x2apic_phys.c:120
Inline: False
```
**Symbols:**

```
ffffffff8106c400-ffffffff8106c40e: x2apic_get_apic_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Collision, Selective Inline ⚠️</summary>

```c
unsigned int x2apic_get_apic_id(long unsigned int x);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff8106d2b1)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:606
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_phys_pkg_id
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8106db00)
Location: arch/x86/kernel/apic/x2apic_phys.c:123
Inline: False
```
**Symbols:**

```
ffffffff8106d260-ffffffff8106d274: x2apic_get_apic_id (STB_LOCAL)
ffffffff8106db00-ffffffff8106db0e: x2apic_get_apic_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Collision, Selective Inline ⚠️</summary>

```c
unsigned int x2apic_get_apic_id(long unsigned int x);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff81074431)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:640
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_phys_pkg_id
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff81074fc0)
Location: arch/x86/kernel/apic/x2apic_phys.c:123
Inline: False
```
**Symbols:**

```
ffffffff810743e0-ffffffff810743f4: x2apic_get_apic_id (STB_LOCAL)
ffffffff81074fc0-ffffffff81074fce: x2apic_get_apic_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision, Selective Inline ⚠️</summary>

```c
unsigned int x2apic_get_apic_id(long unsigned int id);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff81074f70)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:797
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff810755f0)
Location: arch/x86/kernel/apic/x2apic_phys.c:135
Inline: False
```
**Symbols:**

```
ffffffff81074f70-ffffffff81074f7e: x2apic_get_apic_id (STB_LOCAL)
ffffffff810755f0-ffffffff810755fe: x2apic_get_apic_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision, Selective Inline ⚠️</summary>

```c
unsigned int x2apic_get_apic_id(long unsigned int id);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff81075a10)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:793
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff81076090)
Location: arch/x86/kernel/apic/x2apic_phys.c:135
Inline: False
```
**Symbols:**

```
ffffffff81075a10-ffffffff81075a1d: x2apic_get_apic_id (STB_LOCAL)
ffffffff81076090-ffffffff8107609d: x2apic_get_apic_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision, Selective Inline ⚠️</summary>

```c
unsigned int x2apic_get_apic_id(long unsigned int id);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff81082ee0)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:793
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff81083690)
Location: arch/x86/kernel/apic/x2apic_phys.c:135
Inline: False
```
**Symbols:**

```
ffffffff81082ee0-ffffffff81082eed: x2apic_get_apic_id (STB_LOCAL)
ffffffff81083690-ffffffff8108369d: x2apic_get_apic_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision, Selective Inline ⚠️</summary>

```c
unsigned int x2apic_get_apic_id(long unsigned int id);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff81092c90)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:799
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff810935a0)
Location: arch/x86/kernel/apic/x2apic_phys.c:135
Inline: False
```
**Symbols:**

```
ffffffff81092c90-ffffffff81092ca3: x2apic_get_apic_id (STB_LOCAL)
ffffffff810935a0-ffffffff810935b3: x2apic_get_apic_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision, Selective Inline ⚠️</summary>

```c
unsigned int x2apic_get_apic_id(long unsigned int id);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff810a7ed0)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:799
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff810a8b70)
Location: arch/x86/kernel/apic/x2apic_phys.c:135
Inline: False
```
**Symbols:**

```
ffffffff810a7ed0-ffffffff810a7ee3: x2apic_get_apic_id (STB_LOCAL)
ffffffff810a8b70-ffffffff810a8b83: x2apic_get_apic_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision, Selective Inline ⚠️</summary>

```c
unsigned int x2apic_get_apic_id(long unsigned int id);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff810ab140)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:800
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff810abda0)
Location: arch/x86/kernel/apic/x2apic_phys.c:138
Inline: False
```
**Symbols:**

```
ffffffff810ab140-ffffffff810ab153: x2apic_get_apic_id (STB_LOCAL)
ffffffff810abda0-ffffffff810abdb3: x2apic_get_apic_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
u32 x2apic_get_apic_id(u32 id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff810b2b40)
Location: arch/x86/kernel/apic/x2apic_phys.c:127
Inline: True
Direct callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_phys_pkg_id
```
**Symbols:**

```
ffffffff810b2b40-ffffffff810b2b53: x2apic_get_apic_id (STB_GLOBAL)
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
unsigned int x2apic_get_apic_id(long unsigned int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8106caa0)
Location: arch/x86/kernel/apic/x2apic_phys.c:123
Inline: False
```
**Symbols:**

```
ffffffff8106caa0-ffffffff8106caae: x2apic_get_apic_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
unsigned int x2apic_get_apic_id(long unsigned int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8105cdb0)
Location: arch/x86/kernel/apic/x2apic_phys.c:123
Inline: False
```
**Symbols:**

```
ffffffff8105cdb0-ffffffff8105cdbe: x2apic_get_apic_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
unsigned int x2apic_get_apic_id(long unsigned int id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8106cf50)
Location: arch/x86/kernel/apic/x2apic_phys.c:123
Inline: False
```
**Symbols:**

```
ffffffff8106cf50-ffffffff8106cf5e: x2apic_get_apic_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Collision ⚠️</summary>

```c
unsigned int x2apic_get_apic_id(long unsigned int x);
```

**Collision:** Static-Global Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff8106e980)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:606
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_phys_pkg_id
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8106f1d0)
Location: arch/x86/kernel/apic/x2apic_phys.c:123
Inline: False
```
**Symbols:**

```
ffffffff8106e980-ffffffff8106e9bb: x2apic_get_apic_id (STB_LOCAL)
ffffffff8106f1d0-ffffffff8106f1de: x2apic_get_apic_id (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.3</code> and <code>5.4</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>long unsigned int x</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int id</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>long unsigned int id</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int x</code>
</li>
</ul>
</details>
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
<code>long unsigned int id</code> ➡️ <code>u32 id</code>
</li>
<li>
<b>Return type changed. </b>
<code>unsigned int</code> ➡️ <code>u32</code>
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
<details>
<summary>Changed between <code>generic</code> and <code>aws</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>long unsigned int id</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int x</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>generic</code> and <code>azure</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>long unsigned int id</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int x</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>generic</code> and <code>gcp</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>long unsigned int id</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int x</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
