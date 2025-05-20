# Function: <code>native_apic_mem_read</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Selective Inline ⚠️</summary>

```c
u32 native_apic_mem_read(u32 reg);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/ipi.c (ffffffff81054bb7)
Location: arch/x86/include/asm/apic.h:98
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_sequence_phys
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_allbutself_phys
```
```
In arch/x86/kernel/apic/apic_numachip.c (ffffffff81058fb0)
Location: arch/x86/include/asm/apic.h:98
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_numachip.c:numachip_send_IPI_one
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff8105a250)
Location: arch/x86/include/asm/apic.h:98
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_flat_64.c:flat_send_IPI_mask_allbutself
  - arch/x86/kernel/apic/apic_flat_64.c:flat_send_IPI_allbutself
```
```
In arch/x86/kernel/apic/probe_64.c (ffffffff8105a8d6)
Location: arch/x86/include/asm/apic.h:98
Inline: True
Inline callers:
  - arch/x86/kernel/apic/probe_64.c:apic_send_IPI_self
```
**Symbols:**

```
ffffffff81058fb0-ffffffff81058fbe: native_apic_mem_read (STB_LOCAL)
ffffffff8105a250-ffffffff8105a25e: native_apic_mem_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
u32 native_apic_mem_read(u32 reg);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/ipi.c (ffffffff81054d26)
Location: arch/x86/include/asm/apic.h:103
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field
  - arch/x86/kernel/apic/ipi.c:__default_send_IPI_shortcut
```
```
In arch/x86/kernel/apic/apic_numachip.c (ffffffff81059310)
Location: arch/x86/include/asm/apic.h:103
Inline: False
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff8105a4a0)
Location: arch/x86/include/asm/apic.h:103
Inline: False
```
**Symbols:**

```
ffffffff81059310-ffffffff8105931e: native_apic_mem_read (STB_LOCAL)
ffffffff8105a4a0-ffffffff8105a4ae: native_apic_mem_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Selective Inline ⚠️</summary>

```c
u32 native_apic_mem_read(u32 reg);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/ipi.c (ffffffff81057ae6)
Location: arch/x86/include/asm/apic.h:102
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field
  - arch/x86/kernel/apic/ipi.c:__default_send_IPI_shortcut
```
```
In arch/x86/kernel/apic/apic_numachip.c (ffffffff8105c0a0)
Location: arch/x86/include/asm/apic.h:102
Inline: False
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff8105d2b0)
Location: arch/x86/include/asm/apic.h:102
Inline: False
```
**Symbols:**

```
ffffffff8105c0a0-ffffffff8105c0ae: native_apic_mem_read (STB_LOCAL)
ffffffff8105d2b0-ffffffff8105d2be: native_apic_mem_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
u32 native_apic_mem_read(u32 reg);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/ipi.c (ffffffff81057266)
Location: arch/x86/include/asm/apic.h:101
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field
  - arch/x86/kernel/apic/ipi.c:__default_send_IPI_shortcut
```
```
In arch/x86/kernel/apic/apic_numachip.c (ffffffff8105b7a0)
Location: arch/x86/include/asm/apic.h:101
Inline: False
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff8105c9d0)
Location: arch/x86/include/asm/apic.h:101
Inline: False
```
**Symbols:**

```
ffffffff8105b7a0-ffffffff8105b7ae: native_apic_mem_read (STB_LOCAL)
ffffffff8105c9d0-ffffffff8105c9de: native_apic_mem_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
u32 native_apic_mem_read(u32 reg);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/ipi.c (ffffffff8105aef6)
Location: arch/x86/include/asm/apic.h:110
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field
  - arch/x86/kernel/apic/ipi.c:__default_send_IPI_shortcut
```
```
In arch/x86/kernel/apic/apic_numachip.c (ffffffff8105f8a0)
Location: arch/x86/include/asm/apic.h:110
Inline: False
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff81060740)
Location: arch/x86/include/asm/apic.h:110
Inline: False
```
**Symbols:**

```
ffffffff8105f8a0-ffffffff8105f8ae: native_apic_mem_read (STB_LOCAL)
ffffffff81060740-ffffffff8106074e: native_apic_mem_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Selective Inline ⚠️</summary>

```c
u32 native_apic_mem_read(u32 reg);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_apic.c (ffffffff8102bb85)
Location: arch/x86/include/asm/apic.h:111
Inline: True
```
```
In arch/x86/kernel/apic/ipi.c (ffffffff8105def6)
Location: arch/x86/include/asm/apic.h:111
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field
  - arch/x86/kernel/apic/ipi.c:__default_send_IPI_shortcut
```
```
In arch/x86/kernel/apic/apic_numachip.c (ffffffff810629b0)
Location: arch/x86/include/asm/apic.h:111
Inline: False
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff81063830)
Location: arch/x86/include/asm/apic.h:111
Inline: False
```
**Symbols:**

```
ffffffff810629b0-ffffffff810629b9: native_apic_mem_read (STB_LOCAL)
ffffffff81063830-ffffffff81063839: native_apic_mem_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Selective Inline ⚠️</summary>

```c
u32 native_apic_mem_read(u32 reg);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_apic.c (ffffffff8102cb55)
Location: arch/x86/include/asm/apic.h:111
Inline: True
```
```
In arch/x86/kernel/apic/ipi.c (ffffffff81063b86)
Location: arch/x86/include/asm/apic.h:111
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field
  - arch/x86/kernel/apic/ipi.c:__default_send_IPI_shortcut
```
```
In arch/x86/kernel/apic/apic_numachip.c (ffffffff810686b0)
Location: arch/x86/include/asm/apic.h:111
Inline: False
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff81069530)
Location: arch/x86/include/asm/apic.h:111
Inline: False
```
**Symbols:**

```
ffffffff810686b0-ffffffff810686b9: native_apic_mem_read (STB_LOCAL)
ffffffff81069530-ffffffff81069539: native_apic_mem_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Selective Inline ⚠️</summary>

```c
u32 native_apic_mem_read(u32 reg);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_apic.c (ffffffff8102e8d5)
Location: arch/x86/include/asm/apic.h:112
Inline: True
```
```
In arch/x86/kernel/apic/ipi.c (ffffffff81067249)
Location: arch/x86/include/asm/apic.h:112
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field
  - arch/x86/kernel/apic/ipi.c:__default_send_IPI_shortcut
```
```
In arch/x86/kernel/apic/apic_numachip.c (ffffffff8106beb0)
Location: arch/x86/include/asm/apic.h:112
Inline: False
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff8106cd30)
Location: arch/x86/include/asm/apic.h:112
Inline: False
```
**Symbols:**

```
ffffffff8106beb0-ffffffff8106beb9: native_apic_mem_read (STB_LOCAL)
ffffffff8106cd30-ffffffff8106cd39: native_apic_mem_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Selective Inline ⚠️</summary>

```c
u32 native_apic_mem_read(u32 reg);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_apic.c (ffffffff8102f1e5)
Location: arch/x86/include/asm/apic.h:112
Inline: True
```
```
In arch/x86/kernel/apic/ipi.c (ffffffff81067d52)
Location: arch/x86/include/asm/apic.h:112
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_self
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_all
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_allbutself
  - arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field
```
```
In arch/x86/kernel/apic/apic_numachip.c (ffffffff8106ca60)
Location: arch/x86/include/asm/apic.h:112
Inline: False
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff8106e490)
Location: arch/x86/include/asm/apic.h:112
Inline: False
```
**Symbols:**

```
ffffffff8106ca60-ffffffff8106ca69: native_apic_mem_read (STB_LOCAL)
ffffffff8106e490-ffffffff8106e499: native_apic_mem_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
u32 native_apic_mem_read(u32 reg);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_apic.c (ffffffff81031d35)
Location: arch/x86/include/asm/apic.h:112
Inline: True
```
```
In arch/x86/kernel/apic/ipi.c (ffffffff8106eaa2)
Location: arch/x86/include/asm/apic.h:112
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_self
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_all
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_allbutself
  - arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field
```
```
In arch/x86/kernel/apic/apic_numachip.c (ffffffff81073dc0)
Location: arch/x86/include/asm/apic.h:112
Inline: False
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff81075990)
Location: arch/x86/include/asm/apic.h:112
Inline: False
```
**Symbols:**

```
ffffffff81073dc0-ffffffff81073dc9: native_apic_mem_read (STB_LOCAL)
ffffffff81075990-ffffffff81075999: native_apic_mem_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline ⚠️</summary>

```c
u32 native_apic_mem_read(u32 reg);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_apic.c (ffffffff81032a15)
Location: arch/x86/include/asm/apic.h:112
Inline: True
```
```
In arch/x86/kernel/apic/ipi.c (ffffffff8106ff22)
Location: arch/x86/include/asm/apic.h:112
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_self
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_all
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_allbutself
  - arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field
```
```
In arch/x86/kernel/apic/apic_numachip.c (ffffffff81074920)
Location: arch/x86/include/asm/apic.h:112
Inline: False
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff81075fc0)
Location: arch/x86/include/asm/apic.h:112
Inline: False
```
**Symbols:**

```
ffffffff81074920-ffffffff81074929: native_apic_mem_read (STB_LOCAL)
ffffffff81075fc0-ffffffff81075fc9: native_apic_mem_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
u32 native_apic_mem_read(u32 reg);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_apic.c (ffffffff81033e75)
Location: arch/x86/include/asm/apic.h:112
Inline: True
```
```
In arch/x86/kernel/apic/ipi.c (ffffffff81070a72)
Location: arch/x86/include/asm/apic.h:112
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_self
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_all
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_allbutself
  - arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field
```
```
In arch/x86/kernel/apic/apic_numachip.c (ffffffff810753d0)
Location: arch/x86/include/asm/apic.h:112
Inline: False
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff81076a50)
Location: arch/x86/include/asm/apic.h:112
Inline: False
```
**Symbols:**

```
ffffffff810753d0-ffffffff810753d9: native_apic_mem_read (STB_LOCAL)
ffffffff81076a50-ffffffff81076a59: native_apic_mem_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
u32 native_apic_mem_read(u32 reg);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_apic.c (ffffffff81038b65)
Location: arch/x86/include/asm/apic.h:112
Inline: True
```
```
In arch/x86/kernel/apic/ipi.c (ffffffff8107c6f2)
Location: arch/x86/include/asm/apic.h:112
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_self
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_all
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_allbutself
  - arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field
```
```
In arch/x86/kernel/apic/apic_numachip.c (ffffffff810828c0)
Location: arch/x86/include/asm/apic.h:112
Inline: False
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff81084220)
Location: arch/x86/include/asm/apic.h:112
Inline: False
```
**Symbols:**

```
ffffffff810828c0-ffffffff810828c9: native_apic_mem_read (STB_LOCAL)
ffffffff81084220-ffffffff81084229: native_apic_mem_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline ⚠️</summary>

```c
u32 native_apic_mem_read(u32 reg);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_apic.c (ffffffff8103f883)
Location: arch/x86/include/asm/apic.h:112
Inline: True
```
```
In arch/x86/kernel/apic/ipi.c (ffffffff8108bab2)
Location: arch/x86/include/asm/apic.h:112
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_self
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_all
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_allbutself
  - arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field
```
```
In arch/x86/kernel/apic/apic_numachip.c (ffffffff810924f0)
Location: arch/x86/include/asm/apic.h:112
Inline: False
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff81094320)
Location: arch/x86/include/asm/apic.h:112
Inline: False
```
**Symbols:**

```
ffffffff810924f0-ffffffff810924ff: native_apic_mem_read (STB_LOCAL)
ffffffff81094320-ffffffff8109432f: native_apic_mem_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Selective Inline ⚠️</summary>

```c
u32 native_apic_mem_read(u32 reg);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_apic.c (ffffffff810490c3)
Location: arch/x86/include/asm/apic.h:110
Inline: True
```
```
In arch/x86/kernel/apic/ipi.c (ffffffff8109ff32)
Location: arch/x86/include/asm/apic.h:110
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_self
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_all
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_allbutself
  - arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field
```
```
In arch/x86/kernel/apic/apic_numachip.c (ffffffff810a7520)
Location: arch/x86/include/asm/apic.h:110
Inline: False
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff810a9bd0)
Location: arch/x86/include/asm/apic.h:110
Inline: False
```
**Symbols:**

```
ffffffff810a7520-ffffffff810a752f: native_apic_mem_read (STB_LOCAL)
ffffffff810a9bd0-ffffffff810a9bdf: native_apic_mem_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Selective Inline ⚠️</summary>

```c
u32 native_apic_mem_read(u32 reg);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_apic.c (ffffffff810492d9)
Location: arch/x86/include/asm/apic.h:112
Inline: True
```
```
In arch/x86/kernel/apic/ipi.c (ffffffff810a2eb2)
Location: arch/x86/include/asm/apic.h:112
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_self
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_all
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_allbutself
  - arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field
```
```
In arch/x86/kernel/apic/apic_numachip.c (ffffffff810aa780)
Location: arch/x86/include/asm/apic.h:112
Inline: False
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff810acf90)
Location: arch/x86/include/asm/apic.h:112
Inline: False
```
**Symbols:**

```
ffffffff810aa780-ffffffff810aa78f: native_apic_mem_read (STB_LOCAL)
ffffffff810acf90-ffffffff810acf9f: native_apic_mem_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
u32 native_apic_mem_read(u32 reg);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_apic.c (ffffffff81050739)
Location: arch/x86/include/asm/apic.h:97
Inline: True
```
```
In arch/x86/kernel/apic/ipi.c (ffffffff810a9dd3)
Location: arch/x86/include/asm/apic.h:97
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_self
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_all
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_allbutself
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_allbutself_phys
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_sequence_phys
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_single_phys
```
```
In arch/x86/kernel/apic/apic_numachip.c (ffffffff810b1800)
Location: arch/x86/include/asm/apic.h:97
Inline: False
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff810b3c40)
Location: arch/x86/include/asm/apic.h:97
Inline: False
```
**Symbols:**

```
ffffffff810b1800-ffffffff810b180f: native_apic_mem_read (STB_LOCAL)
ffffffff810b3c40-ffffffff810b3c4f: native_apic_mem_read (STB_LOCAL)
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
u32 native_apic_mem_read(u32 reg);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_apic.c (ffffffff8102f345)
Location: arch/x86/include/asm/apic.h:112
Inline: True
```
```
In arch/x86/kernel/apic/ipi.c (ffffffff81067842)
Location: arch/x86/include/asm/apic.h:112
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_self
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_all
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_allbutself
  - arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field
```
```
In arch/x86/kernel/apic/apic_numachip.c (ffffffff8106c550)
Location: arch/x86/include/asm/apic.h:112
Inline: False
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff8106d430)
Location: arch/x86/include/asm/apic.h:112
Inline: False
```
**Symbols:**

```
ffffffff8106c550-ffffffff8106c559: native_apic_mem_read (STB_LOCAL)
ffffffff8106d430-ffffffff8106d439: native_apic_mem_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Selective Inline ⚠️</summary>

```c
u32 native_apic_mem_read(u32 reg);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_apic.c (ffffffff8101f28d)
Location: arch/x86/include/asm/apic.h:112
Inline: True
```
```
In arch/x86/kernel/apic/ipi.c (ffffffff81057bb2)
Location: arch/x86/include/asm/apic.h:112
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_self
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_all
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_allbutself
  - arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field
```
```
In arch/x86/kernel/apic/apic_numachip.c (ffffffff8105c870)
Location: arch/x86/include/asm/apic.h:112
Inline: False
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff8105d870)
Location: arch/x86/include/asm/apic.h:112
Inline: False
```
**Symbols:**

```
ffffffff8105c870-ffffffff8105c879: native_apic_mem_read (STB_LOCAL)
ffffffff8105d870-ffffffff8105d879: native_apic_mem_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Selective Inline ⚠️</summary>

```c
u32 native_apic_mem_read(u32 reg);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_apic.c (ffffffff8102f1a5)
Location: arch/x86/include/asm/apic.h:112
Inline: True
```
```
In arch/x86/kernel/apic/ipi.c (ffffffff81067cf2)
Location: arch/x86/include/asm/apic.h:112
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_self
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_all
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_allbutself
  - arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field
```
```
In arch/x86/kernel/apic/apic_numachip.c (ffffffff8106ca00)
Location: arch/x86/include/asm/apic.h:112
Inline: False
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff8106d8e0)
Location: arch/x86/include/asm/apic.h:112
Inline: False
```
**Symbols:**

```
ffffffff8106ca00-ffffffff8106ca09: native_apic_mem_read (STB_LOCAL)
ffffffff8106d8e0-ffffffff8106d8e9: native_apic_mem_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Selective Inline ⚠️</summary>

```c
u32 native_apic_mem_read(u32 reg);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_apic.c (ffffffff8102ffe5)
Location: arch/x86/include/asm/apic.h:112
Inline: True
```
```
In arch/x86/kernel/apic/ipi.c (ffffffff810692d2)
Location: arch/x86/include/asm/apic.h:112
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_self
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_all
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_allbutself
  - arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field
```
```
In arch/x86/kernel/apic/apic_numachip.c (ffffffff8106e100)
Location: arch/x86/include/asm/apic.h:112
Inline: False
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff8106fb60)
Location: arch/x86/include/asm/apic.h:112
Inline: False
```
**Symbols:**

```
ffffffff8106e100-ffffffff8106e109: native_apic_mem_read (STB_LOCAL)
ffffffff8106fb60-ffffffff8106fb69: native_apic_mem_read (STB_LOCAL)
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
