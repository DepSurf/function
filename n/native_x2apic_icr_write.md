# Function: <code>native_x2apic_icr_write</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_x2apic_icr_write(u32 low, u32 id);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff810595a0)
Location: arch/x86/include/asm/apic.h:218
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff81059a30)
Location: arch/x86/include/asm/apic.h:218
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_mask
```
**Symbols:**

```
ffffffff810595a0-ffffffff810595c4: native_x2apic_icr_write (STB_LOCAL)
ffffffff81059a30-ffffffff81059a54: native_x2apic_icr_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_x2apic_icr_write(u32 low, u32 id);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff81059810)
Location: arch/x86/include/asm/apic.h:225
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff81059d33)
Location: arch/x86/include/asm/apic.h:225
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_dest
```
**Symbols:**

```
ffffffff81059810-ffffffff81059834: native_x2apic_icr_write (STB_LOCAL)
ffffffff81059cb0-ffffffff81059cd4: native_x2apic_icr_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_x2apic_icr_write(u32 low, u32 id);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8105c5c0)
Location: arch/x86/include/asm/apic.h:224
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8105caf3)
Location: arch/x86/include/asm/apic.h:224
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_dest
```
**Symbols:**

```
ffffffff8105c5c0-ffffffff8105c5e4: native_x2apic_icr_write (STB_LOCAL)
ffffffff8105ca70-ffffffff8105ca94: native_x2apic_icr_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_x2apic_icr_write(u32 low, u32 id);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8105bcf0)
Location: arch/x86/include/asm/apic.h:223
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8105c233)
Location: arch/x86/include/asm/apic.h:223
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:__x2apic_send_IPI_dest
```
**Symbols:**

```
ffffffff8105bcf0-ffffffff8105bd14: native_x2apic_icr_write (STB_LOCAL)
ffffffff8105c1b0-ffffffff8105c1d4: native_x2apic_icr_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_x2apic_icr_write(u32 low, u32 id);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff81060085)
Location: arch/x86/include/asm/apic.h:239
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff810606c0)
Location: arch/x86/include/asm/apic.h:239
Inline: False
```
**Symbols:**

```
ffffffff81060150-ffffffff81060174: native_x2apic_icr_write (STB_LOCAL)
ffffffff810606c0-ffffffff810606e4: native_x2apic_icr_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_x2apic_icr_write(u32 low, u32 id);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8106306f)
Location: arch/x86/include/asm/apic.h:240
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff81063790)
Location: arch/x86/include/asm/apic.h:240
Inline: False
```
**Symbols:**

```
ffffffff810631c0-ffffffff810631e4: native_x2apic_icr_write (STB_LOCAL)
ffffffff81063790-ffffffff810637b4: native_x2apic_icr_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_x2apic_icr_write(u32 low, u32 id);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff81068e4f)
Location: arch/x86/include/asm/apic.h:240
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff81069490)
Location: arch/x86/include/asm/apic.h:240
Inline: False
```
**Symbols:**

```
ffffffff81068f10-ffffffff81068f34: native_x2apic_icr_write (STB_LOCAL)
ffffffff81069490-ffffffff810694b4: native_x2apic_icr_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_x2apic_icr_write(u32 low, u32 id);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8106c66f)
Location: arch/x86/include/asm/apic.h:242
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8106cce0)
Location: arch/x86/include/asm/apic.h:242
Inline: False
```
**Symbols:**

```
ffffffff8106c740-ffffffff8106c764: native_x2apic_icr_write (STB_LOCAL)
ffffffff8106cce0-ffffffff8106cd04: native_x2apic_icr_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_x2apic_icr_write(u32 low, u32 id);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff8106d5d0)
Location: arch/x86/include/asm/apic.h:247
Inline: False
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8106de50)
Location: arch/x86/include/asm/apic.h:247
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_all
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_allbutself
  - arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8106e440)
Location: arch/x86/include/asm/apic.h:247
Inline: False
```
**Symbols:**

```
ffffffff8106d5d0-ffffffff8106d5f4: native_x2apic_icr_write (STB_LOCAL)
ffffffff8106de00-ffffffff8106de24: native_x2apic_icr_write (STB_LOCAL)
ffffffff8106e440-ffffffff8106e464: native_x2apic_icr_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_x2apic_icr_write(u32 low, u32 id);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff81074700)
Location: arch/x86/include/asm/apic.h:247
Inline: False
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff81075300)
Location: arch/x86/include/asm/apic.h:247
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_all
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_allbutself
  - arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff81075920)
Location: arch/x86/include/asm/apic.h:247
Inline: False
```
**Symbols:**

```
ffffffff81074700-ffffffff81074724: native_x2apic_icr_write (STB_LOCAL)
ffffffff81075280-ffffffff810752a4: native_x2apic_icr_write (STB_LOCAL)
ffffffff81075920-ffffffff81075944: native_x2apic_icr_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_x2apic_icr_write(u32 low, u32 id);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff81075180)
Location: arch/x86/include/asm/apic.h:237
Inline: False
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff81075963)
Location: arch/x86/include/asm/apic.h:237
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_all
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_allbutself
  - arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff81075f60)
Location: arch/x86/include/asm/apic.h:237
Inline: False
```
**Symbols:**

```
ffffffff81075180-ffffffff810751a4: native_x2apic_icr_write (STB_LOCAL)
ffffffff810758b0-ffffffff810758d4: native_x2apic_icr_write (STB_LOCAL)
ffffffff81075f60-ffffffff81075f84: native_x2apic_icr_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_x2apic_icr_write(u32 low, u32 id);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff81075c20)
Location: arch/x86/include/asm/apic.h:238
Inline: False
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff81076403)
Location: arch/x86/include/asm/apic.h:238
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_all
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_allbutself
  - arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff810769f0)
Location: arch/x86/include/asm/apic.h:238
Inline: False
```
**Symbols:**

```
ffffffff81075c20-ffffffff81075c44: native_x2apic_icr_write (STB_LOCAL)
ffffffff81076240-ffffffff81076264: native_x2apic_icr_write (STB_LOCAL)
ffffffff810769f0-ffffffff81076a14: native_x2apic_icr_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_x2apic_icr_write(u32 low, u32 id);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff810831a0)
Location: arch/x86/include/asm/apic.h:238
Inline: False
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff81083a53)
Location: arch/x86/include/asm/apic.h:238
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_all
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_allbutself
  - arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff810841c0)
Location: arch/x86/include/asm/apic.h:238
Inline: False
```
**Symbols:**

```
ffffffff810831a0-ffffffff810831c4: native_x2apic_icr_write (STB_LOCAL)
ffffffff81083840-ffffffff81083864: native_x2apic_icr_write (STB_LOCAL)
ffffffff810841c0-ffffffff810841e4: native_x2apic_icr_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_x2apic_icr_write(u32 low, u32 id);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff81093020)
Location: arch/x86/include/asm/apic.h:238
Inline: False
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff81093a33)
Location: arch/x86/include/asm/apic.h:238
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_all
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_allbutself
  - arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff81094290)
Location: arch/x86/include/asm/apic.h:238
Inline: False
```
**Symbols:**

```
ffffffff81093020-ffffffff8109305d: native_x2apic_icr_write (STB_LOCAL)
ffffffff810937f0-ffffffff8109382d: native_x2apic_icr_write (STB_LOCAL)
ffffffff81094290-ffffffff810942cd: native_x2apic_icr_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_x2apic_icr_write(u32 low, u32 id);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff810a8380)
Location: arch/x86/include/asm/apic.h:236
Inline: False
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff810a9163)
Location: arch/x86/include/asm/apic.h:236
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_all
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_allbutself
  - arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff810a9b10)
Location: arch/x86/include/asm/apic.h:236
Inline: False
```
**Symbols:**

```
ffffffff810a8380-ffffffff810a83bd: native_x2apic_icr_write (STB_LOCAL)
ffffffff810a8e60-ffffffff810a8e9d: native_x2apic_icr_write (STB_LOCAL)
ffffffff810a9b10-ffffffff810a9b4d: native_x2apic_icr_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_x2apic_icr_write(u32 low, u32 id);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff810ab5f0)
Location: arch/x86/include/asm/apic.h:238
Inline: False
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff810ac323)
Location: arch/x86/include/asm/apic.h:238
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_all
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_allbutself
  - arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff810acb60)
Location: arch/x86/include/asm/apic.h:238
Inline: False
```
**Symbols:**

```
ffffffff810ab5f0-ffffffff810ab62d: native_x2apic_icr_write (STB_LOCAL)
ffffffff810ac080-ffffffff810ac0bd: native_x2apic_icr_write (STB_LOCAL)
ffffffff810acb60-ffffffff810acb9d: native_x2apic_icr_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_x2apic_icr_write(u32 low, u32 id);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff810b2460)
Location: arch/x86/include/asm/apic.h:214
Inline: False
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff810b2ee3)
Location: arch/x86/include/asm/apic.h:214
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_all
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_allbutself
  - arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff810b3b80)
Location: arch/x86/include/asm/apic.h:214
Inline: False
```
**Symbols:**

```
ffffffff810b2460-ffffffff810b249d: native_x2apic_icr_write (STB_LOCAL)
ffffffff810b2e10-ffffffff810b2e4d: native_x2apic_icr_write (STB_LOCAL)
ffffffff810b3b80-ffffffff810b3bbd: native_x2apic_icr_write (STB_LOCAL)
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
void native_x2apic_icr_write(u32 low, u32 id);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8106cdf0)
Location: arch/x86/include/asm/apic.h:247
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_all
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_allbutself
  - arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8106d3e0)
Location: arch/x86/include/asm/apic.h:247
Inline: False
```
**Symbols:**

```
ffffffff8106cda0-ffffffff8106cdc4: native_x2apic_icr_write (STB_LOCAL)
ffffffff8106d3e0-ffffffff8106d404: native_x2apic_icr_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_x2apic_icr_write(u32 low, u32 id);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8105d10a)
Location: arch/x86/include/asm/apic.h:247
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_all
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_allbutself
  - arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8105d7d0)
Location: arch/x86/include/asm/apic.h:247
Inline: False
```
**Symbols:**

```
ffffffff8105d170-ffffffff8105d1a2: native_x2apic_icr_write (STB_LOCAL)
ffffffff8105d7d0-ffffffff8105d802: native_x2apic_icr_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_x2apic_icr_write(u32 low, u32 id);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8106d2a0)
Location: arch/x86/include/asm/apic.h:247
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_all
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_allbutself
  - arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8106d890)
Location: arch/x86/include/asm/apic.h:247
Inline: False
```
**Symbols:**

```
ffffffff8106d250-ffffffff8106d274: native_x2apic_icr_write (STB_LOCAL)
ffffffff8106d890-ffffffff8106d8b4: native_x2apic_icr_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_x2apic_icr_write(u32 low, u32 id);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff8106eca0)
Location: arch/x86/include/asm/apic.h:247
Inline: False
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8106f520)
Location: arch/x86/include/asm/apic.h:247
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_all
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_allbutself
  - arch/x86/kernel/apic/x2apic_phys.c:__x2apic_send_IPI_mask
  - arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8106fb10)
Location: arch/x86/include/asm/apic.h:247
Inline: False
```
**Symbols:**

```
ffffffff8106eca0-ffffffff8106ecc4: native_x2apic_icr_write (STB_LOCAL)
ffffffff8106f4d0-ffffffff8106f4f4: native_x2apic_icr_write (STB_LOCAL)
ffffffff8106fb10-ffffffff8106fb34: native_x2apic_icr_write (STB_LOCAL)
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
