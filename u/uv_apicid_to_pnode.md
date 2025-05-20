# Function: <code>uv_apicid_to_pnode</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff828bd31d)
Location: arch/x86/include/asm/uv/uv_hub.h:609
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_send_IPI_one
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_wakeup_secondary
```
```
In arch/x86/platform/uv/uv_time.c (ffffffff81098f14)
Location: arch/x86/include/asm/uv/uv_hub.h:609
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int uv_apicid_to_pnode(int apicid);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff8107489f)
Location: arch/x86/include/asm/uv/uv_hub.h:555
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_send_IPI_one
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_wakeup_secondary
Direct callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
```
```
In arch/x86/platform/uv/uv_time.c (ffffffff8109e574)
Location: arch/x86/include/asm/uv/uv_hub.h:555
Inline: True
```
**Symbols:**

```
ffffffff810742e0-ffffffff8107432c: uv_apicid_to_pnode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int uv_apicid_to_pnode(int apicid);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff810751fe)
Location: arch/x86/include/asm/uv/uv_hub.h:545
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_send_IPI_one
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_wakeup_secondary
Direct callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
```
```
In arch/x86/platform/uv/uv_time.c (ffffffff8109a0f4)
Location: arch/x86/include/asm/uv/uv_hub.h:545
Inline: True
```
**Symbols:**

```
ffffffff81074de0-ffffffff81074e2c: uv_apicid_to_pnode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int uv_apicid_to_pnode(int apicid);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff81075c9f)
Location: arch/x86/include/asm/uv/uv_hub.h:545
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_send_IPI_one
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_wakeup_secondary
Direct callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
```
```
In arch/x86/platform/uv/uv_time.c (ffffffff8109a8c4)
Location: arch/x86/include/asm/uv/uv_hub.h:545
Inline: True
```
**Symbols:**

```
ffffffff81075890-ffffffff810758dc: uv_apicid_to_pnode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
int uv_apicid_to_pnode(int apicid);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff81083236)
Location: arch/x86/include/asm/uv/uv_hub.h:545
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_send_IPI_one
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_wakeup_secondary
Direct callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
```
```
In arch/x86/platform/uv/uv_time.c (ffffffff810aaa0d)
Location: arch/x86/include/asm/uv/uv_hub.h:545
Inline: True
```
**Symbols:**

```
ffffffff81082f80-ffffffff81082fe3: uv_apicid_to_pnode (STB_LOCAL)
ffffffff81c9e3c5-ffffffff81c9e3e9: uv_apicid_to_pnode.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
int uv_apicid_to_pnode(int apicid);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff810930e5)
Location: arch/x86/include/asm/uv/uv_hub.h:545
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_send_IPI_one
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_wakeup_secondary
Direct callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
```
```
In arch/x86/platform/uv/uv_time.c (ffffffff810c045d)
Location: arch/x86/include/asm/uv/uv_hub.h:545
Inline: True
```
**Symbols:**

```
ffffffff81092d60-ffffffff81092dc4: uv_apicid_to_pnode (STB_LOCAL)
ffffffff81e4d862-ffffffff81e4d886: uv_apicid_to_pnode.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff83e93d29)
Location: arch/x86/include/asm/uv/uv_hub.h:545
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_send_IPI_one
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_wakeup_secondary
```
```
In arch/x86/platform/uv/uv_time.c (ffffffff810dc3cd)
Location: arch/x86/include/asm/uv/uv_hub.h:545
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff836b786f)
Location: arch/x86/include/asm/uv/uv_hub.h:551
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_send_IPI_one
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_wakeup_secondary
```
```
In arch/x86/platform/uv/uv_time.c (ffffffff810e799d)
Location: arch/x86/include/asm/uv/uv_hub.h:551
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff838e81a4)
Location: arch/x86/include/asm/uv/uv_hub.h:551
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_send_IPI_one
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_wakeup_secondary
```
```
In arch/x86/platform/uv/uv_time.c (ffffffff810efd2c)
Location: arch/x86/include/asm/uv/uv_hub.h:551
Inline: True
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff828be34a)
Location: arch/x86/include/asm/uv/uv_hub.h:609
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_send_IPI_one
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_wakeup_secondary
```
```
In arch/x86/platform/uv/uv_time.c (ffffffff8109a3e4)
Location: arch/x86/include/asm/uv/uv_hub.h:609
Inline: True
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
