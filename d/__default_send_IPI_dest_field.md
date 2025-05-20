# Function: <code>__default_send_IPI_dest_field</code>

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
In arch/x86/kernel/apic/ipi.c (ffffffff81054b75)
Location: arch/x86/include/asm/ipi.h:93
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_sequence_phys
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_allbutself_phys
```
```
In arch/x86/kernel/apic/apic_numachip.c (ffffffff810593c5)
Location: arch/x86/include/asm/ipi.h:93
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_numachip.c:numachip_send_IPI_one
```
```
In arch/x86/kernel/apic/apic_flat_64.c (ffffffff8105a5ec)
Location: arch/x86/include/asm/ipi.h:93
Inline: True
Inline callers:
  - arch/x86/kernel/apic/apic_flat_64.c:flat_send_IPI_mask_allbutself
  - arch/x86/kernel/apic/apic_flat_64.c:flat_send_IPI_allbutself
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __default_send_IPI_dest_field(unsigned int mask, int vector, unsigned int dest);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/ipi.c (ffffffff81054d10)
Location: arch/x86/kernel/apic/ipi.c:51
Inline: False
Direct callers:
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_allbutself_phys
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_sequence_phys
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_single_phys
  - arch/x86/kernel/apic/apic_numachip.c:numachip_send_IPI_one
  - arch/x86/kernel/apic/apic_flat_64.c:_flat_send_IPI_mask
```
**Symbols:**

```
ffffffff81054d10-ffffffff81054d73: __default_send_IPI_dest_field (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __default_send_IPI_dest_field(unsigned int mask, int vector, unsigned int dest);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/ipi.c (ffffffff81057ad0)
Location: arch/x86/kernel/apic/ipi.c:51
Inline: False
Direct callers:
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_allbutself_phys
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_sequence_phys
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_single_phys
  - arch/x86/kernel/apic/apic_numachip.c:numachip_send_IPI_one
  - arch/x86/kernel/apic/apic_flat_64.c:_flat_send_IPI_mask
```
**Symbols:**

```
ffffffff81057ad0-ffffffff81057b33: __default_send_IPI_dest_field (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __default_send_IPI_dest_field(unsigned int mask, int vector, unsigned int dest);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/ipi.c (ffffffff81057250)
Location: arch/x86/kernel/apic/ipi.c:51
Inline: False
Direct callers:
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_allbutself_phys
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_sequence_phys
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_single_phys
  - arch/x86/kernel/apic/apic_numachip.c:numachip_send_IPI_one
  - arch/x86/kernel/apic/apic_flat_64.c:_flat_send_IPI_mask
```
**Symbols:**

```
ffffffff81057250-ffffffff810572b3: __default_send_IPI_dest_field (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __default_send_IPI_dest_field(unsigned int mask, int vector, unsigned int dest);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/ipi.c (ffffffff8105aee0)
Location: arch/x86/kernel/apic/ipi.c:52
Inline: False
Direct callers:
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_allbutself_phys
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_sequence_phys
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_single_phys
  - arch/x86/kernel/apic/apic_numachip.c:numachip_send_IPI_one
  - arch/x86/kernel/apic/apic_flat_64.c:_flat_send_IPI_mask
```
**Symbols:**

```
ffffffff8105aee0-ffffffff8105af46: __default_send_IPI_dest_field (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __default_send_IPI_dest_field(unsigned int mask, int vector, unsigned int dest);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/ipi.c (ffffffff8105dee0)
Location: arch/x86/kernel/apic/ipi.c:52
Inline: False
Direct callers:
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_allbutself_phys
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_sequence_phys
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_single_phys
  - arch/x86/kernel/apic/apic_numachip.c:numachip_send_IPI_one
  - arch/x86/kernel/apic/apic_flat_64.c:_flat_send_IPI_mask
```
**Symbols:**

```
ffffffff8105dee0-ffffffff8105df46: __default_send_IPI_dest_field (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __default_send_IPI_dest_field(unsigned int mask, int vector, unsigned int dest);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/ipi.c (ffffffff81063b70)
Location: arch/x86/kernel/apic/ipi.c:52
Inline: False
Direct callers:
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_allbutself_phys
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_sequence_phys
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_single_phys
  - arch/x86/kernel/apic/apic_numachip.c:numachip_send_IPI_one
  - arch/x86/kernel/apic/apic_flat_64.c:_flat_send_IPI_mask
```
**Symbols:**

```
ffffffff81063b70-ffffffff81063bd6: __default_send_IPI_dest_field (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __default_send_IPI_dest_field(unsigned int mask, int vector, unsigned int dest);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/ipi.c (ffffffff81067230)
Location: arch/x86/kernel/apic/ipi.c:52
Inline: False
Direct callers:
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_allbutself_phys
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_sequence_phys
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_single_phys
  - arch/x86/kernel/apic/apic_numachip.c:numachip_send_IPI_one
  - arch/x86/kernel/apic/apic_flat_64.c:_flat_send_IPI_mask
```
**Symbols:**

```
ffffffff81067230-ffffffff81067298: __default_send_IPI_dest_field (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __default_send_IPI_dest_field(unsigned int mask, int vector, unsigned int dest);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/ipi.c (ffffffff81067a80)
Location: arch/x86/kernel/apic/ipi.c:145
Inline: False
Direct callers:
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_allbutself_phys
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_sequence_phys
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_single_phys
  - arch/x86/kernel/apic/apic_numachip.c:numachip_send_IPI_one
  - arch/x86/kernel/apic/apic_flat_64.c:_flat_send_IPI_mask
```
**Symbols:**

```
ffffffff81067a80-ffffffff81067ae8: __default_send_IPI_dest_field (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __default_send_IPI_dest_field(unsigned int mask, int vector, unsigned int dest);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/ipi.c (ffffffff8106e7d0)
Location: arch/x86/kernel/apic/ipi.c:145
Inline: False
Direct callers:
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_allbutself_phys
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_sequence_phys
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_single_phys
  - arch/x86/kernel/apic/apic_numachip.c:numachip_send_IPI_one
  - arch/x86/kernel/apic/apic_flat_64.c:_flat_send_IPI_mask
```
**Symbols:**

```
ffffffff8106e7d0-ffffffff8106e837: __default_send_IPI_dest_field (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __default_send_IPI_dest_field(unsigned int mask, int vector, unsigned int dest);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/ipi.c (ffffffff8106fc50)
Location: arch/x86/kernel/apic/ipi.c:146
Inline: False
Direct callers:
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_allbutself_phys
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_sequence_phys
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_single_phys
  - arch/x86/kernel/apic/apic_numachip.c:numachip_send_IPI_one
  - arch/x86/kernel/apic/apic_flat_64.c:_flat_send_IPI_mask
```
**Symbols:**

```
ffffffff8106fc50-ffffffff8106fcb7: __default_send_IPI_dest_field (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __default_send_IPI_dest_field(unsigned int mask, int vector, unsigned int dest);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/ipi.c (ffffffff81070780)
Location: arch/x86/kernel/apic/ipi.c:146
Inline: False
Direct callers:
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_allbutself_phys
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_sequence_phys
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_single_phys
  - arch/x86/kernel/apic/apic_numachip.c:numachip_send_IPI_one
  - arch/x86/kernel/apic/apic_flat_64.c:_flat_send_IPI_mask
```
**Symbols:**

```
ffffffff81070780-ffffffff810707e7: __default_send_IPI_dest_field (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __default_send_IPI_dest_field(unsigned int mask, int vector, unsigned int dest);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/ipi.c (ffffffff8107c350)
Location: arch/x86/kernel/apic/ipi.c:146
Inline: False
Direct callers:
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_allbutself_phys
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_sequence_phys
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_single_phys
  - arch/x86/kernel/apic/apic_numachip.c:numachip_send_IPI_one
  - arch/x86/kernel/apic/apic_flat_64.c:_flat_send_IPI_mask
```
**Symbols:**

```
ffffffff8107c350-ffffffff8107c3b7: __default_send_IPI_dest_field (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __default_send_IPI_dest_field(unsigned int mask, int vector, unsigned int dest);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/ipi.c (ffffffff8108b700)
Location: arch/x86/kernel/apic/ipi.c:146
Inline: False
Direct callers:
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_allbutself_phys
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_sequence_phys
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_single_phys
  - arch/x86/kernel/apic/apic_numachip.c:numachip_send_IPI_one
  - arch/x86/kernel/apic/apic_flat_64.c:_flat_send_IPI_mask
```
**Symbols:**

```
ffffffff8108b700-ffffffff8108b76b: __default_send_IPI_dest_field (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __default_send_IPI_dest_field(unsigned int mask, int vector, unsigned int dest);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/ipi.c (ffffffff8109fb00)
Location: arch/x86/kernel/apic/ipi.c:146
Inline: False
Direct callers:
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_allbutself_phys
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_sequence_phys
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_single_phys
  - arch/x86/kernel/apic/apic_numachip.c:numachip_send_IPI_one
  - arch/x86/kernel/apic/apic_flat_64.c:_flat_send_IPI_mask
```
**Symbols:**

```
ffffffff8109fb00-ffffffff8109fb6b: __default_send_IPI_dest_field (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __default_send_IPI_dest_field(unsigned int mask, int vector, unsigned int dest);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/ipi.c (ffffffff810a2a90)
Location: arch/x86/kernel/apic/ipi.c:146
Inline: False
Direct callers:
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_allbutself_phys
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_sequence_phys
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_single_phys
  - arch/x86/kernel/apic/apic_numachip.c:numachip_send_IPI_one
  - arch/x86/kernel/apic/apic_flat_64.c:_flat_send_IPI_mask
```
**Symbols:**

```
ffffffff810a2a90-ffffffff810a2afb: __default_send_IPI_dest_field (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void __default_send_IPI_dest_field(unsigned int dest_mask, int vector, unsigned int dest_mode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/ipi.c (ffffffff810a9b6c)
Location: arch/x86/kernel/apic/ipi.c:173
Inline: True
Inline callers:
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_allbutself_phys
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_sequence_phys
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_single_phys
Direct callers:
  - arch/x86/kernel/apic/apic_numachip.c:numachip_send_IPI_one
  - arch/x86/kernel/apic/apic_flat_64.c:_flat_send_IPI_mask
```
**Symbols:**

```
ffffffff810a97d0-ffffffff810a9862: __default_send_IPI_dest_field (STB_GLOBAL)
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
void __default_send_IPI_dest_field(unsigned int mask, int vector, unsigned int dest);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/ipi.c (ffffffff81067570)
Location: arch/x86/kernel/apic/ipi.c:145
Inline: False
Direct callers:
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_allbutself_phys
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_sequence_phys
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_single_phys
  - arch/x86/kernel/apic/apic_numachip.c:numachip_send_IPI_one
  - arch/x86/kernel/apic/apic_flat_64.c:_flat_send_IPI_mask
```
**Symbols:**

```
ffffffff81067570-ffffffff810675d8: __default_send_IPI_dest_field (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __default_send_IPI_dest_field(unsigned int mask, int vector, unsigned int dest);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/ipi.c (ffffffff81057930)
Location: arch/x86/kernel/apic/ipi.c:145
Inline: False
Direct callers:
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_allbutself_phys
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_sequence_phys
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_single_phys
  - arch/x86/kernel/apic/apic_numachip.c:numachip_send_IPI_one
  - arch/x86/kernel/apic/apic_flat_64.c:_flat_send_IPI_mask
```
**Symbols:**

```
ffffffff81057930-ffffffff81057998: __default_send_IPI_dest_field (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __default_send_IPI_dest_field(unsigned int mask, int vector, unsigned int dest);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/ipi.c (ffffffff81067a20)
Location: arch/x86/kernel/apic/ipi.c:145
Inline: False
Direct callers:
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_allbutself_phys
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_sequence_phys
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_single_phys
  - arch/x86/kernel/apic/apic_numachip.c:numachip_send_IPI_one
  - arch/x86/kernel/apic/apic_flat_64.c:_flat_send_IPI_mask
```
**Symbols:**

```
ffffffff81067a20-ffffffff81067a88: __default_send_IPI_dest_field (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __default_send_IPI_dest_field(unsigned int mask, int vector, unsigned int dest);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/ipi.c (ffffffff81069000)
Location: arch/x86/kernel/apic/ipi.c:145
Inline: False
Direct callers:
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_allbutself_phys
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_sequence_phys
  - arch/x86/kernel/apic/ipi.c:default_send_IPI_single_phys
  - arch/x86/kernel/apic/apic_numachip.c:numachip_send_IPI_one
  - arch/x86/kernel/apic/apic_flat_64.c:_flat_send_IPI_mask
```
**Symbols:**

```
ffffffff81069000-ffffffff81069068: __default_send_IPI_dest_field (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int dest_mask</code>
</li>
<li>
<b>Param added. </b>
<code>unsigned int dest_mode</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned int mask</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned int dest</code>
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
