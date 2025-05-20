# Function: <code>__xapic_wait_icr_idle</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/ipi.c (ffffffff81054bb7)
Location: arch/x86/include/asm/ipi.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_sequence_phys
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_allbutself_phys
```
```
In arch/x86/kernel/apic/apic_numachip.c (ffffffff810593ca)
Location: arch/x86/include/asm/ipi.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_numachip.c:numachip_send_IPI_one
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff8105a594)
Location: arch/x86/include/asm/ipi.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_flat_64.c:flat_send_IPI_mask_allbutself
  - arch/x86/kernel/apic/apic_flat_64.c:flat_send_IPI_allbutself
```
```
In arch/x86/kernel/apic/probe_64.c (ffffffff8105a8d6)
Location: arch/x86/include/asm/ipi.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/apic/probe_64.c:apic_send_IPI_self
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/ipi.c (ffffffff81054d24)
Location: arch/x86/include/asm/ipi.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field
  - arch/x86/kernel/apic/ipi.c:__default_send_IPI_shortcut
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/ipi.c (ffffffff81057ae4)
Location: arch/x86/include/asm/ipi.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field
  - arch/x86/kernel/apic/ipi.c:__default_send_IPI_shortcut
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/ipi.c (ffffffff81057264)
Location: arch/x86/include/asm/ipi.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field
  - arch/x86/kernel/apic/ipi.c:__default_send_IPI_shortcut
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/ipi.c (ffffffff8105aef4)
Location: arch/x86/include/asm/ipi.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field
  - arch/x86/kernel/apic/ipi.c:__default_send_IPI_shortcut
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/ipi.c (ffffffff8105dea5)
Location: arch/x86/include/asm/ipi.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field
  - arch/x86/kernel/apic/ipi.c:__default_send_IPI_shortcut
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/ipi.c (ffffffff81063b35)
Location: arch/x86/include/asm/ipi.h:54
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field
  - arch/x86/kernel/apic/ipi.c:__default_send_IPI_shortcut
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/ipi.c (ffffffff810671f5)
Location: arch/x86/include/asm/ipi.h:53
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field
  - arch/x86/kernel/apic/ipi.c:__default_send_IPI_shortcut
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/ipi.c (0)
Location: arch/x86/kernel/apic/ipi.c:104
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_self
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_all
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_allbutself
  - arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/ipi.c (0)
Location: arch/x86/kernel/apic/ipi.c:104
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_self
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_all
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_allbutself
  - arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field
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
In arch/x86/kernel/apic/ipi.c (0)
Location: arch/x86/kernel/apic/ipi.c:105
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_self
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_all
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_allbutself
  - arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field
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
In arch/x86/kernel/apic/ipi.c (ffffffff81070a70)
Location: arch/x86/kernel/apic/ipi.c:105
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_self
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_all
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_allbutself
  - arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field
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
In arch/x86/kernel/apic/ipi.c (ffffffff8107c6f0)
Location: arch/x86/kernel/apic/ipi.c:105
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_self
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_all
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_allbutself
  - arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field
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
In arch/x86/kernel/apic/ipi.c (ffffffff8108bab0)
Location: arch/x86/kernel/apic/ipi.c:105
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_self
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_all
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_allbutself
  - arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field
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
In arch/x86/kernel/apic/ipi.c (ffffffff8109ff30)
Location: arch/x86/kernel/apic/ipi.c:105
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_self
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_all
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_allbutself
  - arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field
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
In arch/x86/kernel/apic/ipi.c (ffffffff810a2eb0)
Location: arch/x86/kernel/apic/ipi.c:105
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_self
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_all
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_allbutself
  - arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field
```
</details>
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/ipi.c (0)
Location: arch/x86/kernel/apic/ipi.c:104
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_self
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_all
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_allbutself
  - arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/ipi.c (0)
Location: arch/x86/kernel/apic/ipi.c:104
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_self
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_all
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_allbutself
  - arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/ipi.c (0)
Location: arch/x86/kernel/apic/ipi.c:104
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_self
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_all
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_allbutself
  - arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/ipi.c (0)
Location: arch/x86/kernel/apic/ipi.c:104
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_self
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_all
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_allbutself
  - arch/x86/kernel/apic/ipi.c:__default_send_IPI_dest_field
```
</details>
</li>
</ul>

## Differences
