# Function: <code>uv_write_local_mmr</code>

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
In arch/x86/platform/uv/tlb_uv.c (ffffffff810963d0)
Location: arch/x86/include/asm/uv/uv_hub.h:690
Inline: True
Inline callers:
  - arch/x86/platform/uv/tlb_uv.c:write_mmr_proc_sw_ack
  - arch/x86/platform/uv/tlb_uv.c:write_mmr_sw_ack
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff828ca17c)
Location: arch/x86/include/asm/uv/uv_hub.h:690
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/platform/uv/tlb_uv.c (ffffffff8109b5e0)
Location: arch/x86/include/asm/uv/uv_hub.h:636
Inline: True
Inline callers:
  - arch/x86/platform/uv/tlb_uv.c:write_mmr_proc_sw_ack
  - arch/x86/platform/uv/tlb_uv.c:write_mmr_sw_ack
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff8109f29e)
Location: arch/x86/include/asm/uv/uv_hub.h:636
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/platform/uv/uv_nmi.c (ffffffff8109ada5)
Location: arch/x86/include/asm/uv/uv_hub.h:617
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/platform/uv/uv_nmi.c (ffffffff8109b4e1)
Location: arch/x86/include/asm/uv/uv_hub.h:617
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/platform/uv/uv_nmi.c (ffffffff810ab68d)
Location: arch/x86/include/asm/uv/uv_hub.h:617
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/platform/uv/uv_nmi.c (ffffffff810c1333)
Location: arch/x86/include/asm/uv/uv_hub.h:617
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/platform/uv/uv_nmi.c (ffffffff810ddb73)
Location: arch/x86/include/asm/uv/uv_hub.h:617
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/platform/uv/uv_nmi.c (ffffffff810e9222)
Location: arch/x86/include/asm/uv/uv_hub.h:623
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/platform/uv/uv_nmi.c (ffffffff810f1577)
Location: arch/x86/include/asm/uv/uv_hub.h:623
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_mmrs
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
In arch/x86/platform/uv/tlb_uv.c (ffffffff81098020)
Location: arch/x86/include/asm/uv/uv_hub.h:690
Inline: True
Inline callers:
  - arch/x86/platform/uv/tlb_uv.c:write_mmr_proc_sw_ack
  - arch/x86/platform/uv/tlb_uv.c:write_mmr_sw_ack
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff828cb1b9)
Location: arch/x86/include/asm/uv/uv_hub.h:690
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup
  - arch/x86/platform/uv/uv_nmi.c:uv_handle_nmi
```
</details>
</li>
</ul>

## Differences
