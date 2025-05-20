# Function: <code>native_apic_msr_write</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_apic_msr_write(u32 reg, u32 v);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff81059710)
Location: arch/x86/include/asm/apic.h:181
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff81059ec0)
Location: arch/x86/include/asm/apic.h:181
Inline: True
```
**Symbols:**

```
ffffffff81059710-ffffffff8105973f: native_apic_msr_write (STB_LOCAL)
ffffffff81059ec0-ffffffff81059eef: native_apic_msr_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_apic_msr_write(u32 reg, u32 v);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff81059970)
Location: arch/x86/include/asm/apic.h:188
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8105a1b0)
Location: arch/x86/include/asm/apic.h:188
Inline: True
```
**Symbols:**

```
ffffffff81059970-ffffffff810599a0: native_apic_msr_write (STB_LOCAL)
ffffffff8105a1b0-ffffffff8105a1e0: native_apic_msr_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_apic_msr_write(u32 reg, u32 v);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8105c720)
Location: arch/x86/include/asm/apic.h:187
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8105cf00)
Location: arch/x86/include/asm/apic.h:187
Inline: True
```
**Symbols:**

```
ffffffff8105c720-ffffffff8105c750: native_apic_msr_write (STB_LOCAL)
ffffffff8105cf00-ffffffff8105cf30: native_apic_msr_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_apic_msr_write(u32 reg, u32 v);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8105be50)
Location: arch/x86/include/asm/apic.h:186
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8105c390)
Location: arch/x86/include/asm/apic.h:186
Inline: True
```
**Symbols:**

```
ffffffff8105be50-ffffffff8105be81: native_apic_msr_write (STB_LOCAL)
ffffffff8105c390-ffffffff8105c3c1: native_apic_msr_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_apic_msr_write(u32 reg, u32 v);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8105fe70)
Location: arch/x86/include/asm/apic.h:202
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff81060500)
Location: arch/x86/include/asm/apic.h:202
Inline: True
```
**Symbols:**

```
ffffffff8105fe70-ffffffff8105fea1: native_apic_msr_write (STB_LOCAL)
ffffffff81060500-ffffffff81060531: native_apic_msr_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_apic_msr_write(u32 reg, u32 v);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff81062f60)
Location: arch/x86/include/asm/apic.h:203
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff810635f0)
Location: arch/x86/include/asm/apic.h:203
Inline: True
```
**Symbols:**

```
ffffffff81062f60-ffffffff81062f90: native_apic_msr_write (STB_LOCAL)
ffffffff810635f0-ffffffff81063620: native_apic_msr_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_apic_msr_write(u32 reg, u32 v);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff81068c60)
Location: arch/x86/include/asm/apic.h:203
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff810692f0)
Location: arch/x86/include/asm/apic.h:203
Inline: True
```
**Symbols:**

```
ffffffff81068c60-ffffffff81068c90: native_apic_msr_write (STB_LOCAL)
ffffffff810692f0-ffffffff81069320: native_apic_msr_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_apic_msr_write(u32 reg, u32 v);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8106c470)
Location: arch/x86/include/asm/apic.h:205
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8106cb40)
Location: arch/x86/include/asm/apic.h:205
Inline: True
```
**Symbols:**

```
ffffffff8106c470-ffffffff8106c4a0: native_apic_msr_write (STB_LOCAL)
ffffffff8106cb40-ffffffff8106cb70: native_apic_msr_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_apic_msr_write(u32 reg, u32 v);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff8106d520)
Location: arch/x86/include/asm/apic.h:210
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8106db70)
Location: arch/x86/include/asm/apic.h:210
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8106e2a0)
Location: arch/x86/include/asm/apic.h:210
Inline: True
```
**Symbols:**

```
ffffffff8106d520-ffffffff8106d550: native_apic_msr_write (STB_LOCAL)
ffffffff8106db70-ffffffff8106dba0: native_apic_msr_write (STB_LOCAL)
ffffffff8106e2a0-ffffffff8106e2d0: native_apic_msr_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_apic_msr_write(u32 reg, u32 v);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff81074690)
Location: arch/x86/include/asm/apic.h:210
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff81075030)
Location: arch/x86/include/asm/apic.h:210
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff810755e0)
Location: arch/x86/include/asm/apic.h:210
Inline: True
```
**Symbols:**

```
ffffffff81074690-ffffffff810746c0: native_apic_msr_write (STB_LOCAL)
ffffffff81075030-ffffffff81075060: native_apic_msr_write (STB_LOCAL)
ffffffff810755e0-ffffffff81075610: native_apic_msr_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_apic_msr_write(u32 reg, u32 v);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff81075110)
Location: arch/x86/include/asm/apic.h:200
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff81075660)
Location: arch/x86/include/asm/apic.h:200
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff81075c20)
Location: arch/x86/include/asm/apic.h:200
Inline: True
```
**Symbols:**

```
ffffffff81075110-ffffffff81075140: native_apic_msr_write (STB_LOCAL)
ffffffff81075660-ffffffff81075690: native_apic_msr_write (STB_LOCAL)
ffffffff81075c20-ffffffff81075c50: native_apic_msr_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_apic_msr_write(u32 reg, u32 v);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff81075bb0)
Location: arch/x86/include/asm/apic.h:201
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff81076100)
Location: arch/x86/include/asm/apic.h:201
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff810766d0)
Location: arch/x86/include/asm/apic.h:201
Inline: True
```
**Symbols:**

```
ffffffff81075bb0-ffffffff81075be0: native_apic_msr_write (STB_LOCAL)
ffffffff81076100-ffffffff81076130: native_apic_msr_write (STB_LOCAL)
ffffffff810766d0-ffffffff81076700: native_apic_msr_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_apic_msr_write(u32 reg, u32 v);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff81083130)
Location: arch/x86/include/asm/apic.h:201
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff81083700)
Location: arch/x86/include/asm/apic.h:201
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff81083dd0)
Location: arch/x86/include/asm/apic.h:201
Inline: True
```
**Symbols:**

```
ffffffff81083130-ffffffff81083160: native_apic_msr_write (STB_LOCAL)
ffffffff81083700-ffffffff81083730: native_apic_msr_write (STB_LOCAL)
ffffffff81083dd0-ffffffff81083e00: native_apic_msr_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_apic_msr_write(u32 reg, u32 v);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff81092f60)
Location: arch/x86/include/asm/apic.h:201
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff81093640)
Location: arch/x86/include/asm/apic.h:201
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff81093e20)
Location: arch/x86/include/asm/apic.h:201
Inline: True
```
**Symbols:**

```
ffffffff81092f60-ffffffff81092fc3: native_apic_msr_write (STB_LOCAL)
ffffffff81093640-ffffffff810936a3: native_apic_msr_write (STB_LOCAL)
ffffffff81093e20-ffffffff81093e83: native_apic_msr_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_apic_msr_write(u32 reg, u32 v);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff810a8230)
Location: arch/x86/include/asm/apic.h:199
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff810a8c50)
Location: arch/x86/include/asm/apic.h:199
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff810a94c0)
Location: arch/x86/include/asm/apic.h:199
Inline: True
```
**Symbols:**

```
ffffffff810a8230-ffffffff810a8293: native_apic_msr_write (STB_LOCAL)
ffffffff810a8c50-ffffffff810a8cb3: native_apic_msr_write (STB_LOCAL)
ffffffff810a94c0-ffffffff810a9523: native_apic_msr_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_apic_msr_write(u32 reg, u32 v);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff810ab4a0)
Location: arch/x86/include/asm/apic.h:201
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff810abe80)
Location: arch/x86/include/asm/apic.h:201
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff810ac720)
Location: arch/x86/include/asm/apic.h:201
Inline: True
```
**Symbols:**

```
ffffffff810ab4a0-ffffffff810ab503: native_apic_msr_write (STB_LOCAL)
ffffffff810abe80-ffffffff810abee3: native_apic_msr_write (STB_LOCAL)
ffffffff810ac720-ffffffff810ac783: native_apic_msr_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_apic_msr_write(u32 reg, u32 v);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff810b2310)
Location: arch/x86/include/asm/apic.h:189
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff810b2be0)
Location: arch/x86/include/asm/apic.h:189
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff810b33a0)
Location: arch/x86/include/asm/apic.h:189
Inline: True
```
**Symbols:**

```
ffffffff810b2310-ffffffff810b2373: native_apic_msr_write (STB_LOCAL)
ffffffff810b2be0-ffffffff810b2c43: native_apic_msr_write (STB_LOCAL)
ffffffff810b33a0-ffffffff810b3403: native_apic_msr_write (STB_LOCAL)
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
<summary>In <code>aws</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_apic_msr_write(u32 reg, u32 v);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8106cb10)
Location: arch/x86/include/asm/apic.h:210
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8106d240)
Location: arch/x86/include/asm/apic.h:210
Inline: True
```
**Symbols:**

```
ffffffff8106cb10-ffffffff8106cb40: native_apic_msr_write (STB_LOCAL)
ffffffff8106d240-ffffffff8106d270: native_apic_msr_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_apic_msr_write(u32 reg, u32 v);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8105ce70)
Location: arch/x86/include/asm/apic.h:210
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8105d670)
Location: arch/x86/include/asm/apic.h:210
Inline: True
```
**Symbols:**

```
ffffffff8105ce70-ffffffff8105ceac: native_apic_msr_write (STB_LOCAL)
ffffffff8105d670-ffffffff8105d6ac: native_apic_msr_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_apic_msr_write(u32 reg, u32 v);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8106cfc0)
Location: arch/x86/include/asm/apic.h:210
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8106d6f0)
Location: arch/x86/include/asm/apic.h:210
Inline: True
```
**Symbols:**

```
ffffffff8106cfc0-ffffffff8106cff0: native_apic_msr_write (STB_LOCAL)
ffffffff8106d6f0-ffffffff8106d720: native_apic_msr_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_apic_msr_write(u32 reg, u32 v);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff8106ebf0)
Location: arch/x86/include/asm/apic.h:210
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8106f240)
Location: arch/x86/include/asm/apic.h:210
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8106f970)
Location: arch/x86/include/asm/apic.h:210
Inline: True
```
**Symbols:**

```
ffffffff8106ebf0-ffffffff8106ec20: native_apic_msr_write (STB_LOCAL)
ffffffff8106f240-ffffffff8106f270: native_apic_msr_write (STB_LOCAL)
ffffffff8106f970-ffffffff8106f9a0: native_apic_msr_write (STB_LOCAL)
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
