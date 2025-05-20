# Function: <code>native_apic_mem_write</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_apic_mem_write(u32 reg, u32 v);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/ipi.c (ffffffff81054bd6)
Location: arch/x86/include/asm/apic.h:89
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_sequence_phys
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_sequence_phys
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_allbutself_phys
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_allbutself_phys
```
```
In arch/x86/kernel/apic/apic_numachip.c (ffffffff81058fa0)
Location: arch/x86/include/asm/apic.h:89
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_numachip.c:numachip_send_IPI_one
  - arch/x86/kernel/apic/apic_numachip.c:numachip_send_IPI_one
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff8105a240)
Location: arch/x86/include/asm/apic.h:89
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_flat_64.c:flat_send_IPI_mask_allbutself
  - arch/x86/kernel/apic/apic_flat_64.c:flat_send_IPI_mask_allbutself
  - arch/x86/kernel/apic/apic_flat_64.c:flat_send_IPI_allbutself
  - arch/x86/kernel/apic/apic_flat_64.c:flat_send_IPI_allbutself
```
```
In arch/x86/kernel/apic/probe_64.c (ffffffff8105a905)
Location: arch/x86/include/asm/apic.h:89
Inline: True
Inline callers:
  - arch/x86/kernel/apic/probe_64.c:apic_send_IPI_self
```
**Symbols:**

```
ffffffff81058fa0-ffffffff81058fae: native_apic_mem_write (STB_LOCAL)
ffffffff8105a240-ffffffff8105a24e: native_apic_mem_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_apic_mem_write(u32 reg, u32 v);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/ipi.c (ffffffff81054d35)
Location: arch/x86/include/asm/apic.h:94
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field
  - arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field
  - arch/x86/kernel/apic/ipi.c:__default_send_IPI_shortcut
```
```
In arch/x86/kernel/apic/apic_numachip.c (ffffffff81059300)
Location: arch/x86/include/asm/apic.h:94
Inline: False
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff8105a490)
Location: arch/x86/include/asm/apic.h:94
Inline: False
```
**Symbols:**

```
ffffffff81059300-ffffffff8105930e: native_apic_mem_write (STB_LOCAL)
ffffffff8105a490-ffffffff8105a49e: native_apic_mem_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_apic_mem_write(u32 reg, u32 v);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/ipi.c (ffffffff81057af5)
Location: arch/x86/include/asm/apic.h:93
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field
  - arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field
  - arch/x86/kernel/apic/ipi.c:__default_send_IPI_shortcut
```
```
In arch/x86/kernel/apic/apic_numachip.c (ffffffff8105c090)
Location: arch/x86/include/asm/apic.h:93
Inline: False
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff8105d2a0)
Location: arch/x86/include/asm/apic.h:93
Inline: False
```
**Symbols:**

```
ffffffff8105c090-ffffffff8105c09e: native_apic_mem_write (STB_LOCAL)
ffffffff8105d2a0-ffffffff8105d2ae: native_apic_mem_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_apic_mem_write(u32 reg, u32 v);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/ipi.c (ffffffff81057275)
Location: arch/x86/include/asm/apic.h:92
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field
  - arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field
  - arch/x86/kernel/apic/ipi.c:__default_send_IPI_shortcut
```
```
In arch/x86/kernel/apic/apic_numachip.c (ffffffff8105b790)
Location: arch/x86/include/asm/apic.h:92
Inline: False
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff8105c9c0)
Location: arch/x86/include/asm/apic.h:92
Inline: False
```
**Symbols:**

```
ffffffff8105b790-ffffffff8105b79e: native_apic_mem_write (STB_LOCAL)
ffffffff8105c9c0-ffffffff8105c9ce: native_apic_mem_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_apic_mem_write(u32 reg, u32 v);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/ipi.c (ffffffff8105af05)
Location: arch/x86/include/asm/apic.h:101
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field
  - arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field
  - arch/x86/kernel/apic/ipi.c:__default_send_IPI_shortcut
```
```
In arch/x86/kernel/apic/apic_numachip.c (ffffffff8105f890)
Location: arch/x86/include/asm/apic.h:101
Inline: False
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff81060730)
Location: arch/x86/include/asm/apic.h:101
Inline: False
```
**Symbols:**

```
ffffffff8105f890-ffffffff8105f89e: native_apic_mem_write (STB_LOCAL)
ffffffff81060730-ffffffff8106073e: native_apic_mem_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_apic_mem_write(u32 reg, u32 v);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_apic.c (ffffffff8102bbcd)
Location: arch/x86/include/asm/apic.h:102
Inline: True
```
```
In arch/x86/kernel/apic/ipi.c (ffffffff8105df05)
Location: arch/x86/include/asm/apic.h:102
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field
  - arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field
  - arch/x86/kernel/apic/ipi.c:__default_send_IPI_shortcut
```
```
In arch/x86/kernel/apic/apic_numachip.c (ffffffff810629a0)
Location: arch/x86/include/asm/apic.h:102
Inline: False
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff81063820)
Location: arch/x86/include/asm/apic.h:102
Inline: False
```
**Symbols:**

```
ffffffff810629a0-ffffffff810629ae: native_apic_mem_write (STB_LOCAL)
ffffffff81063820-ffffffff8106382e: native_apic_mem_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_apic_mem_write(u32 reg, u32 v);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_apic.c (ffffffff8102cb9d)
Location: arch/x86/include/asm/apic.h:102
Inline: True
```
```
In arch/x86/kernel/apic/ipi.c (ffffffff81063b95)
Location: arch/x86/include/asm/apic.h:102
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field
  - arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field
  - arch/x86/kernel/apic/ipi.c:__default_send_IPI_shortcut
```
```
In arch/x86/kernel/apic/apic_numachip.c (ffffffff810686a0)
Location: arch/x86/include/asm/apic.h:102
Inline: False
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff81069520)
Location: arch/x86/include/asm/apic.h:102
Inline: False
```
**Symbols:**

```
ffffffff810686a0-ffffffff810686ae: native_apic_mem_write (STB_LOCAL)
ffffffff81069520-ffffffff8106952e: native_apic_mem_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_apic_mem_write(u32 reg, u32 v);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_apic.c (ffffffff8102e91d)
Location: arch/x86/include/asm/apic.h:103
Inline: True
```
```
In arch/x86/kernel/apic/ipi.c (ffffffff81067258)
Location: arch/x86/include/asm/apic.h:103
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field
  - arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field
  - arch/x86/kernel/apic/ipi.c:__default_send_IPI_shortcut
```
```
In arch/x86/kernel/apic/apic_numachip.c (ffffffff8106bea0)
Location: arch/x86/include/asm/apic.h:103
Inline: False
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff8106cd20)
Location: arch/x86/include/asm/apic.h:103
Inline: False
```
**Symbols:**

```
ffffffff8106bea0-ffffffff8106bea9: native_apic_mem_write (STB_LOCAL)
ffffffff8106cd20-ffffffff8106cd29: native_apic_mem_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_apic_mem_write(u32 reg, u32 v);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_apic.c (ffffffff8102f22d)
Location: arch/x86/include/asm/apic.h:103
Inline: True
```
```
In arch/x86/kernel/apic/ipi.c (ffffffff81067d64)
Location: arch/x86/include/asm/apic.h:103
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_self
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_all
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_allbutself
  - arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field
  - arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field
```
```
In arch/x86/kernel/apic/apic_numachip.c (ffffffff8106ca50)
Location: arch/x86/include/asm/apic.h:103
Inline: False
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff8106e480)
Location: arch/x86/include/asm/apic.h:103
Inline: False
```
**Symbols:**

```
ffffffff8106ca50-ffffffff8106ca59: native_apic_mem_write (STB_LOCAL)
ffffffff8106e480-ffffffff8106e489: native_apic_mem_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_apic_mem_write(u32 reg, u32 v);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_apic.c (ffffffff81031d7d)
Location: arch/x86/include/asm/apic.h:103
Inline: True
```
```
In arch/x86/kernel/apic/ipi.c (ffffffff8106eab4)
Location: arch/x86/include/asm/apic.h:103
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_self
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_all
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_allbutself
  - arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field
  - arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field
```
```
In arch/x86/kernel/apic/apic_numachip.c (ffffffff81073db0)
Location: arch/x86/include/asm/apic.h:103
Inline: False
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff81075980)
Location: arch/x86/include/asm/apic.h:103
Inline: False
```
**Symbols:**

```
ffffffff81073db0-ffffffff81073db9: native_apic_mem_write (STB_LOCAL)
ffffffff81075980-ffffffff81075989: native_apic_mem_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_apic_mem_write(u32 reg, u32 v);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_apic.c (ffffffff81032a5d)
Location: arch/x86/include/asm/apic.h:103
Inline: True
```
```
In arch/x86/kernel/apic/ipi.c (ffffffff8106ff34)
Location: arch/x86/include/asm/apic.h:103
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_self
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_all
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_allbutself
  - arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field
  - arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field
```
```
In arch/x86/kernel/apic/apic_numachip.c (ffffffff81074910)
Location: arch/x86/include/asm/apic.h:103
Inline: False
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff81075fb0)
Location: arch/x86/include/asm/apic.h:103
Inline: False
```
**Symbols:**

```
ffffffff81074910-ffffffff81074919: native_apic_mem_write (STB_LOCAL)
ffffffff81075fb0-ffffffff81075fb9: native_apic_mem_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_apic_mem_write(u32 reg, u32 v);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_apic.c (ffffffff81033ebd)
Location: arch/x86/include/asm/apic.h:103
Inline: True
```
```
In arch/x86/kernel/apic/ipi.c (ffffffff81070a84)
Location: arch/x86/include/asm/apic.h:103
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_self
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_all
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_allbutself
  - arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field
  - arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field
```
```
In arch/x86/kernel/apic/apic_numachip.c (ffffffff810753c0)
Location: arch/x86/include/asm/apic.h:103
Inline: False
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff81076a40)
Location: arch/x86/include/asm/apic.h:103
Inline: False
```
**Symbols:**

```
ffffffff810753c0-ffffffff810753c9: native_apic_mem_write (STB_LOCAL)
ffffffff81076a40-ffffffff81076a49: native_apic_mem_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_apic_mem_write(u32 reg, u32 v);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_apic.c (ffffffff81038bad)
Location: arch/x86/include/asm/apic.h:103
Inline: True
```
```
In arch/x86/kernel/apic/ipi.c (ffffffff8107c704)
Location: arch/x86/include/asm/apic.h:103
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_self
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_all
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_allbutself
  - arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field
  - arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field
```
```
In arch/x86/kernel/apic/apic_numachip.c (ffffffff810828b0)
Location: arch/x86/include/asm/apic.h:103
Inline: False
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff81084210)
Location: arch/x86/include/asm/apic.h:103
Inline: False
```
**Symbols:**

```
ffffffff810828b0-ffffffff810828b9: native_apic_mem_write (STB_LOCAL)
ffffffff81084210-ffffffff81084219: native_apic_mem_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_apic_mem_write(u32 reg, u32 v);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_apic.c (ffffffff8103f91f)
Location: arch/x86/include/asm/apic.h:103
Inline: True
```
```
In arch/x86/kernel/apic/ipi.c (ffffffff8108bac4)
Location: arch/x86/include/asm/apic.h:103
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_self
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_all
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_allbutself
  - arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field
  - arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field
```
```
In arch/x86/kernel/apic/apic_numachip.c (ffffffff810924d0)
Location: arch/x86/include/asm/apic.h:103
Inline: False
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff81094300)
Location: arch/x86/include/asm/apic.h:103
Inline: False
```
**Symbols:**

```
ffffffff810924d0-ffffffff810924e1: native_apic_mem_write (STB_LOCAL)
ffffffff81094300-ffffffff81094311: native_apic_mem_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_apic_mem_write(u32 reg, u32 v);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_apic.c (ffffffff8104916f)
Location: arch/x86/include/asm/apic.h:101
Inline: True
```
```
In arch/x86/kernel/apic/ipi.c (ffffffff8109ff44)
Location: arch/x86/include/asm/apic.h:101
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_self
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_all
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_allbutself
  - arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field
  - arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field
```
```
In arch/x86/kernel/apic/apic_numachip.c (ffffffff810a74f0)
Location: arch/x86/include/asm/apic.h:101
Inline: False
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff810a9ba0)
Location: arch/x86/include/asm/apic.h:101
Inline: False
```
**Symbols:**

```
ffffffff810a74f0-ffffffff810a7501: native_apic_mem_write (STB_LOCAL)
ffffffff810a9ba0-ffffffff810a9bb1: native_apic_mem_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_apic_mem_write(u32 reg, u32 v);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_apic.c (ffffffff81049379)
Location: arch/x86/include/asm/apic.h:103
Inline: True
```
```
In arch/x86/kernel/apic/ipi.c (ffffffff810a2ec4)
Location: arch/x86/include/asm/apic.h:103
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_self
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_all
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_allbutself
  - arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field
  - arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field
```
```
In arch/x86/kernel/apic/apic_numachip.c (ffffffff810aa750)
Location: arch/x86/include/asm/apic.h:103
Inline: False
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff810acf60)
Location: arch/x86/include/asm/apic.h:103
Inline: False
```
**Symbols:**

```
ffffffff810aa750-ffffffff810aa761: native_apic_mem_write (STB_LOCAL)
ffffffff810acf60-ffffffff810acf71: native_apic_mem_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_apic_mem_write(u32 reg, u32 v);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_apic.c (ffffffff810507d9)
Location: arch/x86/include/asm/apic.h:88
Inline: True
```
```
In arch/x86/kernel/apic/ipi.c (ffffffff810a9de5)
Location: arch/x86/include/asm/apic.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_self
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_all
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_allbutself
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_allbutself_phys
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_allbutself_phys
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_sequence_phys
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_sequence_phys
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_single_phys
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_single_phys
```
```
In arch/x86/kernel/apic/apic_numachip.c (ffffffff810b1820)
Location: arch/x86/include/asm/apic.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_numachip.c:native_apic_mem_eoi
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff810b3c60)
Location: arch/x86/include/asm/apic.h:88
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_flat_64.c:native_apic_mem_eoi
```
**Symbols:**

```
ffffffff810b17d0-ffffffff810b17e1: native_apic_mem_write (STB_LOCAL)
ffffffff810b3c10-ffffffff810b3c21: native_apic_mem_write (STB_LOCAL)
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
void native_apic_mem_write(u32 reg, u32 v);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_apic.c (ffffffff8102f38d)
Location: arch/x86/include/asm/apic.h:103
Inline: True
```
```
In arch/x86/kernel/apic/ipi.c (ffffffff81067854)
Location: arch/x86/include/asm/apic.h:103
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_self
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_all
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_allbutself
  - arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field
  - arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field
```
```
In arch/x86/kernel/apic/apic_numachip.c (ffffffff8106c540)
Location: arch/x86/include/asm/apic.h:103
Inline: False
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff8106d420)
Location: arch/x86/include/asm/apic.h:103
Inline: False
```
**Symbols:**

```
ffffffff8106c540-ffffffff8106c549: native_apic_mem_write (STB_LOCAL)
ffffffff8106d420-ffffffff8106d429: native_apic_mem_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_apic_mem_write(u32 reg, u32 v);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_apic.c (ffffffff8101f2fd)
Location: arch/x86/include/asm/apic.h:103
Inline: True
```
```
In arch/x86/kernel/apic/ipi.c (ffffffff81057bc4)
Location: arch/x86/include/asm/apic.h:103
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_self
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_all
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_allbutself
  - arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field
  - arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field
```
```
In arch/x86/kernel/apic/apic_numachip.c (ffffffff8105c860)
Location: arch/x86/include/asm/apic.h:103
Inline: False
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff8105d860)
Location: arch/x86/include/asm/apic.h:103
Inline: False
```
**Symbols:**

```
ffffffff8105c860-ffffffff8105c869: native_apic_mem_write (STB_LOCAL)
ffffffff8105d860-ffffffff8105d869: native_apic_mem_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_apic_mem_write(u32 reg, u32 v);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_apic.c (ffffffff8102f1ed)
Location: arch/x86/include/asm/apic.h:103
Inline: True
```
```
In arch/x86/kernel/apic/ipi.c (ffffffff81067d04)
Location: arch/x86/include/asm/apic.h:103
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_self
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_all
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_allbutself
  - arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field
  - arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field
```
```
In arch/x86/kernel/apic/apic_numachip.c (ffffffff8106c9f0)
Location: arch/x86/include/asm/apic.h:103
Inline: False
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff8106d8d0)
Location: arch/x86/include/asm/apic.h:103
Inline: False
```
**Symbols:**

```
ffffffff8106c9f0-ffffffff8106c9f9: native_apic_mem_write (STB_LOCAL)
ffffffff8106d8d0-ffffffff8106d8d9: native_apic_mem_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void native_apic_mem_write(u32 reg, u32 v);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_apic.c (ffffffff8103002d)
Location: arch/x86/include/asm/apic.h:103
Inline: True
```
```
In arch/x86/kernel/apic/ipi.c (ffffffff810692e4)
Location: arch/x86/include/asm/apic.h:103
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_self
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_all
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_allbutself
  - arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field
  - arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field
```
```
In arch/x86/kernel/apic/apic_numachip.c (ffffffff8106e0f0)
Location: arch/x86/include/asm/apic.h:103
Inline: False
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff8106fb50)
Location: arch/x86/include/asm/apic.h:103
Inline: False
```
**Symbols:**

```
ffffffff8106e0f0-ffffffff8106e0f9: native_apic_mem_write (STB_LOCAL)
ffffffff8106fb50-ffffffff8106fb59: native_apic_mem_write (STB_LOCAL)
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
