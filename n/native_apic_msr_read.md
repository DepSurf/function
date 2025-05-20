# Function: <code>native_apic_msr_read</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Selective Inline ⚠️</summary>

```c
u32 native_apic_msr_read(u32 reg);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff81f711bc)
Location: arch/x86/include/asm/apic.h:195
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:setup_nox2apic
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff81059740)
Location: arch/x86/include/asm/apic.h:195
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff81059ef0)
Location: arch/x86/include/asm/apic.h:195
Inline: True
```
**Symbols:**

```
ffffffff81059740-ffffffff8105978e: native_apic_msr_read (STB_LOCAL)
ffffffff81059ef0-ffffffff81059f3e: native_apic_msr_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
u32 native_apic_msr_read(u32 reg);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff81f998c9)
Location: arch/x86/include/asm/apic.h:202
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:setup_nox2apic
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff810599a0)
Location: arch/x86/include/asm/apic.h:202
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8105a1e0)
Location: arch/x86/include/asm/apic.h:202
Inline: True
```
**Symbols:**

```
ffffffff810599a0-ffffffff810599c4: native_apic_msr_read (STB_LOCAL)
ffffffff8105a1e0-ffffffff8105a204: native_apic_msr_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Selective Inline ⚠️</summary>

```c
u32 native_apic_msr_read(u32 reg);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff81fd4d9f)
Location: arch/x86/include/asm/apic.h:201
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:setup_nox2apic
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8105c750)
Location: arch/x86/include/asm/apic.h:201
Inline: True
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8105cf30)
Location: arch/x86/include/asm/apic.h:201
Inline: True
```
**Symbols:**

```
ffffffff8105c750-ffffffff8105c774: native_apic_msr_read (STB_LOCAL)
ffffffff8105cf30-ffffffff8105cf54: native_apic_msr_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
u32 native_apic_msr_read(u32 reg);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff820b5a52)
Location: arch/x86/include/asm/apic.h:200
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:setup_nox2apic
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8105bca0)
Location: arch/x86/include/asm/apic.h:200
Inline: False
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8105c160)
Location: arch/x86/include/asm/apic.h:200
Inline: False
```
**Symbols:**

```
ffffffff8105bca0-ffffffff8105bcc4: native_apic_msr_read (STB_LOCAL)
ffffffff8105c160-ffffffff8105c184: native_apic_msr_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
u32 native_apic_msr_read(u32 reg);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff826bc3ad)
Location: arch/x86/include/asm/apic.h:216
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:setup_nox2apic
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8105fd40)
Location: arch/x86/include/asm/apic.h:216
Inline: False
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff810601e0)
Location: arch/x86/include/asm/apic.h:216
Inline: False
```
**Symbols:**

```
ffffffff8105fd40-ffffffff8105fd64: native_apic_msr_read (STB_LOCAL)
ffffffff810601e0-ffffffff81060204: native_apic_msr_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Selective Inline ⚠️</summary>

```c
u32 native_apic_msr_read(u32 reg);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff826e615b)
Location: arch/x86/include/asm/apic.h:217
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:setup_nox2apic
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff81062e50)
Location: arch/x86/include/asm/apic.h:217
Inline: False
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff810632c0)
Location: arch/x86/include/asm/apic.h:217
Inline: False
```
**Symbols:**

```
ffffffff81062e50-ffffffff81062e74: native_apic_msr_read (STB_LOCAL)
ffffffff810632c0-ffffffff810632e4: native_apic_msr_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Selective Inline ⚠️</summary>

```c
u32 native_apic_msr_read(u32 reg);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff8289cc9e)
Location: arch/x86/include/asm/apic.h:217
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:setup_nox2apic
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff81068b50)
Location: arch/x86/include/asm/apic.h:217
Inline: False
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff81068fc0)
Location: arch/x86/include/asm/apic.h:217
Inline: False
```
**Symbols:**

```
ffffffff81068b50-ffffffff81068b74: native_apic_msr_read (STB_LOCAL)
ffffffff81068fc0-ffffffff81068fe4: native_apic_msr_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Selective Inline ⚠️</summary>

```c
u32 native_apic_msr_read(u32 reg);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff828b4f87)
Location: arch/x86/include/asm/apic.h:219
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:setup_nox2apic
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8106c360)
Location: arch/x86/include/asm/apic.h:219
Inline: False
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8106c7e0)
Location: arch/x86/include/asm/apic.h:219
Inline: False
```
**Symbols:**

```
ffffffff8106c360-ffffffff8106c384: native_apic_msr_read (STB_LOCAL)
ffffffff8106c7e0-ffffffff8106c804: native_apic_msr_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Selective Inline ⚠️</summary>

```c
u32 native_apic_msr_read(u32 reg);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff828b83e4)
Location: arch/x86/include/asm/apic.h:224
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:setup_nox2apic
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff8106cf10)
Location: arch/x86/include/asm/apic.h:224
Inline: False
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8106da60)
Location: arch/x86/include/asm/apic.h:224
Inline: False
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8106df30)
Location: arch/x86/include/asm/apic.h:224
Inline: False
```
**Symbols:**

```
ffffffff8106cf10-ffffffff8106cf34: native_apic_msr_read (STB_LOCAL)
ffffffff8106da60-ffffffff8106da84: native_apic_msr_read (STB_LOCAL)
ffffffff8106df30-ffffffff8106df54: native_apic_msr_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
u32 native_apic_msr_read(u32 reg);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff82cdd5a7)
Location: arch/x86/include/asm/apic.h:224
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:setup_nox2apic
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff81074290)
Location: arch/x86/include/asm/apic.h:224
Inline: False
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff81074f40)
Location: arch/x86/include/asm/apic.h:224
Inline: False
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff81075400)
Location: arch/x86/include/asm/apic.h:224
Inline: False
```
**Symbols:**

```
ffffffff81074290-ffffffff810742b4: native_apic_msr_read (STB_LOCAL)
ffffffff81074f40-ffffffff81074f64: native_apic_msr_read (STB_LOCAL)
ffffffff81075400-ffffffff81075424: native_apic_msr_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline ⚠️</summary>

```c
u32 native_apic_msr_read(u32 reg);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff82fc993b)
Location: arch/x86/include/asm/apic.h:214
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:setup_nox2apic
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff81074e40)
Location: arch/x86/include/asm/apic.h:214
Inline: False
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff81075550)
Location: arch/x86/include/asm/apic.h:214
Inline: False
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff81075a40)
Location: arch/x86/include/asm/apic.h:214
Inline: False
```
**Symbols:**

```
ffffffff81074e40-ffffffff81074e64: native_apic_msr_read (STB_LOCAL)
ffffffff81075550-ffffffff81075574: native_apic_msr_read (STB_LOCAL)
ffffffff81075a40-ffffffff81075a64: native_apic_msr_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
u32 native_apic_msr_read(u32 reg);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff831d4196)
Location: arch/x86/include/asm/apic.h:215
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:setup_nox2apic
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff810758f0)
Location: arch/x86/include/asm/apic.h:215
Inline: False
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff81075ff0)
Location: arch/x86/include/asm/apic.h:215
Inline: False
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff810764e0)
Location: arch/x86/include/asm/apic.h:215
Inline: False
```
**Symbols:**

```
ffffffff810758f0-ffffffff81075914: native_apic_msr_read (STB_LOCAL)
ffffffff81075ff0-ffffffff81076014: native_apic_msr_read (STB_LOCAL)
ffffffff810764e0-ffffffff81076504: native_apic_msr_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
u32 native_apic_msr_read(u32 reg);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff832b6d22)
Location: arch/x86/include/asm/apic.h:215
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:setup_nox2apic
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff81082dc0)
Location: arch/x86/include/asm/apic.h:215
Inline: False
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff810835f0)
Location: arch/x86/include/asm/apic.h:215
Inline: False
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff81083b30)
Location: arch/x86/include/asm/apic.h:215
Inline: False
```
**Symbols:**

```
ffffffff81082dc0-ffffffff81082de4: native_apic_msr_read (STB_LOCAL)
ffffffff810835f0-ffffffff81083614: native_apic_msr_read (STB_LOCAL)
ffffffff81083b30-ffffffff81083b54: native_apic_msr_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline ⚠️</summary>

```c
u32 native_apic_msr_read(u32 reg);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff83468827)
Location: arch/x86/include/asm/apic.h:215
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:setup_nox2apic
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff81092b00)
Location: arch/x86/include/asm/apic.h:215
Inline: False
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff810934c0)
Location: arch/x86/include/asm/apic.h:215
Inline: False
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff81093b70)
Location: arch/x86/include/asm/apic.h:215
Inline: False
```
**Symbols:**

```
ffffffff81092b00-ffffffff81092b53: native_apic_msr_read (STB_LOCAL)
ffffffff810934c0-ffffffff81093513: native_apic_msr_read (STB_LOCAL)
ffffffff81093b70-ffffffff81093bc3: native_apic_msr_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Selective Inline ⚠️</summary>

```c
u32 native_apic_msr_read(u32 reg);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff83e8ceb7)
Location: arch/x86/include/asm/apic.h:213
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:setup_nox2apic
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff810a7ca0)
Location: arch/x86/include/asm/apic.h:213
Inline: False
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff810a8a30)
Location: arch/x86/include/asm/apic.h:213
Inline: False
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff810a9290)
Location: arch/x86/include/asm/apic.h:213
Inline: False
```
**Symbols:**

```
ffffffff810a7ca0-ffffffff810a7cf3: native_apic_msr_read (STB_LOCAL)
ffffffff810a8a30-ffffffff810a8a83: native_apic_msr_read (STB_LOCAL)
ffffffff810a9290-ffffffff810a92e3: native_apic_msr_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Selective Inline ⚠️</summary>

```c
u32 native_apic_msr_read(u32 reg);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff836b0747)
Location: arch/x86/include/asm/apic.h:215
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:setup_nox2apic
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff810aaf10)
Location: arch/x86/include/asm/apic.h:215
Inline: False
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff810abc60)
Location: arch/x86/include/asm/apic.h:215
Inline: False
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff810ac4b0)
Location: arch/x86/include/asm/apic.h:215
Inline: False
```
**Symbols:**

```
ffffffff810aaf10-ffffffff810aaf63: native_apic_msr_read (STB_LOCAL)
ffffffff810abc60-ffffffff810abcb3: native_apic_msr_read (STB_LOCAL)
ffffffff810ac4b0-ffffffff810ac503: native_apic_msr_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
u32 native_apic_msr_read(u32 reg);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff838e0e77)
Location: arch/x86/include/asm/apic.h:203
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:setup_nox2apic
  - arch/x86/kernel/apic/apic.c:apic_read_boot_cpu_id
  - arch/x86/kernel/apic/apic.c:apic_read_boot_cpu_id
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff810b1ef0)
Location: arch/x86/include/asm/apic.h:203
Inline: False
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff810b2ad0)
Location: arch/x86/include/asm/apic.h:203
Inline: False
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff810b31d0)
Location: arch/x86/include/asm/apic.h:203
Inline: False
```
**Symbols:**

```
ffffffff810b1ef0-ffffffff810b1f43: native_apic_msr_read (STB_LOCAL)
ffffffff810b2ad0-ffffffff810b2b23: native_apic_msr_read (STB_LOCAL)
ffffffff810b31d0-ffffffff810b3223: native_apic_msr_read (STB_LOCAL)
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
u32 native_apic_msr_read(u32 reg);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff828a63eb)
Location: arch/x86/include/asm/apic.h:224
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:setup_nox2apic
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8106ca00)
Location: arch/x86/include/asm/apic.h:224
Inline: False
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8106ced0)
Location: arch/x86/include/asm/apic.h:224
Inline: False
```
**Symbols:**

```
ffffffff8106ca00-ffffffff8106ca24: native_apic_msr_read (STB_LOCAL)
ffffffff8106ced0-ffffffff8106cef4: native_apic_msr_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Selective Inline ⚠️</summary>

```c
u32 native_apic_msr_read(u32 reg);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff8289e50c)
Location: arch/x86/include/asm/apic.h:224
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:setup_nox2apic
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8105ce20)
Location: arch/x86/include/asm/apic.h:224
Inline: False
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8105d3c0)
Location: arch/x86/include/asm/apic.h:224
Inline: False
```
**Symbols:**

```
ffffffff8105ce20-ffffffff8105ce63: native_apic_msr_read (STB_LOCAL)
ffffffff8105d3c0-ffffffff8105d403: native_apic_msr_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Selective Inline ⚠️</summary>

```c
u32 native_apic_msr_read(u32 reg);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff828b92fb)
Location: arch/x86/include/asm/apic.h:224
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:setup_nox2apic
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8106ceb0)
Location: arch/x86/include/asm/apic.h:224
Inline: False
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8106d380)
Location: arch/x86/include/asm/apic.h:224
Inline: False
```
**Symbols:**

```
ffffffff8106ceb0-ffffffff8106ced4: native_apic_msr_read (STB_LOCAL)
ffffffff8106d380-ffffffff8106d3a4: native_apic_msr_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Selective Inline ⚠️</summary>

```c
u32 native_apic_msr_read(u32 reg);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic.c (ffffffff828b93fc)
Location: arch/x86/include/asm/apic.h:224
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic.c:setup_nox2apic
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff8106e5d0)
Location: arch/x86/include/asm/apic.h:224
Inline: False
```
```
In arch/x86/kernel/apic/x2apic_phys.c (ffffffff8106f130)
Location: arch/x86/include/asm/apic.h:224
Inline: False
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff8106f600)
Location: arch/x86/include/asm/apic.h:224
Inline: False
```
**Symbols:**

```
ffffffff8106e5d0-ffffffff8106e5f4: native_apic_msr_read (STB_LOCAL)
ffffffff8106f130-ffffffff8106f154: native_apic_msr_read (STB_LOCAL)
ffffffff8106f600-ffffffff8106f624: native_apic_msr_read (STB_LOCAL)
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
