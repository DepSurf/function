# Function: <code>uv_undefined</code>

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
<summary>In <code>5.4</code>: ✅</summary>

```c
long unsigned int uv_undefined(char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff8106d94a)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:56
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34
  - arch/x86/platform/uv/tlb_uv.c:uv_bau_init
  - arch/x86/platform/uv/tlb_uv.c:init_per_cpu
  - arch/x86/platform/uv/tlb_uv.c:init_per_cpu
  - arch/x86/platform/uv/tlb_uv.c:enable_timeouts
  - arch/x86/platform/uv/tlb_uv.c:enable_timeouts
  - arch/x86/platform/uv/tlb_uv.c:enable_timeouts
  - arch/x86/platform/uv/tlb_uv.c:enable_timeouts
  - arch/x86/platform/uv/tlb_uv.c:read_gmmr_sw_ack
  - arch/x86/platform/uv/tlb_uv.c:read_mmr_sw_ack
  - arch/x86/platform/uv/tlb_uv.c:write_gmmr_sw_ack
  - arch/x86/platform/uv/tlb_uv.c:write_mmr_sw_ack
  - arch/x86/platform/uv/tlb_uv.c:write_mmr_payload_last
  - arch/x86/platform/uv/tlb_uv.c:write_mmr_payload_first
```
**Symbols:**

```
ffffffff8106d94a-ffffffff8106d97d: uv_undefined (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long unsigned int uv_undefined(char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff81074c27)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:59
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34
  - arch/x86/platform/uv/tlb_uv.c:calculate_destination_timeout
  - arch/x86/platform/uv/tlb_uv.c:calculate_destination_timeout
  - arch/x86/platform/uv/tlb_uv.c:pq_init
  - arch/x86/platform/uv/tlb_uv.c:enable_timeouts
  - arch/x86/platform/uv/tlb_uv.c:enable_timeouts
  - arch/x86/platform/uv/tlb_uv.c:enable_timeouts
  - arch/x86/platform/uv/tlb_uv.c:enable_timeouts
  - arch/x86/platform/uv/tlb_uv.c:read_gmmr_sw_ack
  - arch/x86/platform/uv/tlb_uv.c:read_mmr_sw_ack
  - arch/x86/platform/uv/tlb_uv.c:write_gmmr_sw_ack
  - arch/x86/platform/uv/tlb_uv.c:write_mmr_sw_ack
  - arch/x86/platform/uv/tlb_uv.c:write_mmr_payload_last
  - arch/x86/platform/uv/tlb_uv.c:write_mmr_payload_first
```
**Symbols:**

```
ffffffff81074c27-ffffffff81074c45: uv_undefined (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long unsigned int uv_undefined(char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff81bd7628)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:61
Inline: False
```
**Symbols:**

```
ffffffff81bd7628-ffffffff81bd7646: uv_undefined (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long unsigned int uv_undefined(char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff81bc97c0)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:61
Inline: False
```
**Symbols:**

```
ffffffff81bc97c0-ffffffff81bc97de: uv_undefined (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long unsigned int uv_undefined(char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff81c9e332)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:61
Inline: False
```
**Symbols:**

```
ffffffff81c9e332-ffffffff81c9e350: uv_undefined (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long unsigned int uv_undefined(char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff81e4d7d4)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:61
Inline: False
```
**Symbols:**

```
ffffffff81e4d7d4-ffffffff81e4d7fa: uv_undefined (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
long unsigned int uv_undefined(char *str);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff810a82b0)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:61
Inline: True
```
**Symbols:**

```
ffffffff810a82b0-ffffffff810a82d9: uv_undefined (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
long unsigned int uv_undefined(char *str);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff810ab520)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:61
Inline: True
```
**Symbols:**

```
ffffffff810ab520-ffffffff810ab549: uv_undefined (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
long unsigned int uv_undefined(char *str);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff810b2390)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:63
Inline: True
```
**Symbols:**

```
ffffffff810b2390-ffffffff810b23b9: uv_undefined (STB_GLOBAL)
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
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long unsigned int uv_undefined(char *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff8106f01a)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:56
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34
  - arch/x86/platform/uv/tlb_uv.c:uv_bau_init
  - arch/x86/platform/uv/tlb_uv.c:init_per_cpu
  - arch/x86/platform/uv/tlb_uv.c:init_per_cpu
  - arch/x86/platform/uv/tlb_uv.c:enable_timeouts
  - arch/x86/platform/uv/tlb_uv.c:enable_timeouts
  - arch/x86/platform/uv/tlb_uv.c:enable_timeouts
  - arch/x86/platform/uv/tlb_uv.c:enable_timeouts
  - arch/x86/platform/uv/tlb_uv.c:read_gmmr_sw_ack
  - arch/x86/platform/uv/tlb_uv.c:read_mmr_sw_ack
  - arch/x86/platform/uv/tlb_uv.c:write_gmmr_sw_ack
  - arch/x86/platform/uv/tlb_uv.c:write_mmr_sw_ack
  - arch/x86/platform/uv/tlb_uv.c:write_mmr_payload_last
  - arch/x86/platform/uv/tlb_uv.c:write_mmr_payload_first
```
**Symbols:**

```
ffffffff8106f01a-ffffffff8106f04d: uv_undefined (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
