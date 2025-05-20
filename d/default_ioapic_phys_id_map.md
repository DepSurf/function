# Function: <code>default_ioapic_phys_id_map</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate ⚠️</summary>

```c
void default_ioapic_phys_id_map(physid_mask_t *phys_map, physid_mask_t *retmap);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/apic.c (ffffffff81025830)
Location: arch/x86/include/asm/apic.h:593
Inline: False
```
```
In arch/x86/kernel/apic/apic_noop.c (ffffffff81054860)
Location: arch/x86/include/asm/apic.h:593
Inline: False
```
**Symbols:**

```
ffffffff81025830-ffffffff81025847: default_ioapic_phys_id_map (STB_LOCAL)
ffffffff81054860-ffffffff81054877: default_ioapic_phys_id_map (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate ⚠️</summary>

```c
void default_ioapic_phys_id_map(physid_mask_t *phys_map, physid_mask_t *retmap);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/apic.c (ffffffff81024c50)
Location: arch/x86/include/asm/apic.h:600
Inline: False
```
```
In arch/x86/kernel/apic/apic_noop.c (ffffffff810549e0)
Location: arch/x86/include/asm/apic.h:600
Inline: False
```
**Symbols:**

```
ffffffff81024c50-ffffffff81024c67: default_ioapic_phys_id_map (STB_LOCAL)
ffffffff810549e0-ffffffff810549f7: default_ioapic_phys_id_map (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate ⚠️</summary>

```c
void default_ioapic_phys_id_map(physid_mask_t *phys_map, physid_mask_t *retmap);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/apic.c (ffffffff81025370)
Location: arch/x86/include/asm/apic.h:600
Inline: False
```
```
In arch/x86/kernel/apic/apic_noop.c (ffffffff810577c0)
Location: arch/x86/include/asm/apic.h:600
Inline: False
```
**Symbols:**

```
ffffffff81025370-ffffffff81025387: default_ioapic_phys_id_map (STB_LOCAL)
ffffffff810577c0-ffffffff810577d7: default_ioapic_phys_id_map (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate ⚠️</summary>

```c
void default_ioapic_phys_id_map(physid_mask_t *phys_map, physid_mask_t *retmap);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/apic.c (ffffffff8101bd70)
Location: arch/x86/include/asm/apic.h:580
Inline: False
```
```
In arch/x86/kernel/apic/apic_noop.c (ffffffff81056fa0)
Location: arch/x86/include/asm/apic.h:580
Inline: False
```
**Symbols:**

```
ffffffff8101bd70-ffffffff8101bd87: default_ioapic_phys_id_map (STB_LOCAL)
ffffffff81056fa0-ffffffff81056fb7: default_ioapic_phys_id_map (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void default_ioapic_phys_id_map(physid_mask_t *phys_map, physid_mask_t *retmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic_common.c (ffffffff8105ac90)
Location: arch/x86/kernel/apic/apic_common.c:24
Inline: False
```
**Symbols:**

```
ffffffff8105ac90-ffffffff8105acac: default_ioapic_phys_id_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void default_ioapic_phys_id_map(physid_mask_t *phys_map, physid_mask_t *retmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic_common.c (ffffffff8105dc90)
Location: arch/x86/kernel/apic/apic_common.c:24
Inline: False
```
**Symbols:**

```
ffffffff8105dc90-ffffffff8105dcac: default_ioapic_phys_id_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void default_ioapic_phys_id_map(physid_mask_t *phys_map, physid_mask_t *retmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic_common.c (ffffffff81063920)
Location: arch/x86/kernel/apic/apic_common.c:24
Inline: False
```
**Symbols:**

```
ffffffff81063920-ffffffff8106393c: default_ioapic_phys_id_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void default_ioapic_phys_id_map(physid_mask_t *phys_map, physid_mask_t *retmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic_common.c (ffffffff81066fe0)
Location: arch/x86/kernel/apic/apic_common.c:24
Inline: False
```
**Symbols:**

```
ffffffff81066fe0-ffffffff81066ffc: default_ioapic_phys_id_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void default_ioapic_phys_id_map(physid_mask_t *phys_map, physid_mask_t *retmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic_common.c (ffffffff81067650)
Location: arch/x86/kernel/apic/apic_common.c:24
Inline: False
```
**Symbols:**

```
ffffffff81067650-ffffffff8106766c: default_ioapic_phys_id_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void default_ioapic_phys_id_map(physid_mask_t *phys_map, physid_mask_t *retmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic_common.c (ffffffff8106e3a0)
Location: arch/x86/kernel/apic/apic_common.c:24
Inline: False
```
**Symbols:**

```
ffffffff8106e3a0-ffffffff8106e3bc: default_ioapic_phys_id_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void default_ioapic_phys_id_map(physid_mask_t *phys_map, physid_mask_t *retmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic_common.c (ffffffff8106f820)
Location: arch/x86/kernel/apic/apic_common.c:24
Inline: False
```
**Symbols:**

```
ffffffff8106f820-ffffffff8106f83c: default_ioapic_phys_id_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void default_ioapic_phys_id_map(physid_mask_t *phys_map, physid_mask_t *retmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic_common.c (ffffffff81070350)
Location: arch/x86/kernel/apic/apic_common.c:24
Inline: False
```
**Symbols:**

```
ffffffff81070350-ffffffff8107036c: default_ioapic_phys_id_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void default_ioapic_phys_id_map(physid_mask_t *phys_map, physid_mask_t *retmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic_common.c (ffffffff8107bef0)
Location: arch/x86/kernel/apic/apic_common.c:24
Inline: False
```
**Symbols:**

```
ffffffff8107bef0-ffffffff8107bf0c: default_ioapic_phys_id_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void default_ioapic_phys_id_map(physid_mask_t *phys_map, physid_mask_t *retmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic_common.c (ffffffff8108b170)
Location: arch/x86/kernel/apic/apic_common.c:24
Inline: False
```
**Symbols:**

```
ffffffff8108b170-ffffffff8108b19a: default_ioapic_phys_id_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void default_ioapic_phys_id_map(physid_mask_t *phys_map, physid_mask_t *retmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic_common.c (ffffffff8109f3b0)
Location: arch/x86/kernel/apic/apic_common.c:24
Inline: False
```
**Symbols:**

```
ffffffff8109f3b0-ffffffff8109f3da: default_ioapic_phys_id_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void default_ioapic_phys_id_map(physid_mask_t *phys_map, physid_mask_t *retmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic_common.c (ffffffff810a2340)
Location: arch/x86/kernel/apic/apic_common.c:24
Inline: False
```
**Symbols:**

```
ffffffff810a2340-ffffffff810a236a: default_ioapic_phys_id_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void default_ioapic_phys_id_map(physid_mask_t *phys_map, physid_mask_t *retmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic_common.c (ffffffff810a90b0)
Location: arch/x86/kernel/apic/apic_common.c:26
Inline: False
```
**Symbols:**

```
ffffffff810a90b0-ffffffff810a90da: default_ioapic_phys_id_map (STB_GLOBAL)
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
void default_ioapic_phys_id_map(physid_mask_t *phys_map, physid_mask_t *retmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic_common.c (ffffffff81067140)
Location: arch/x86/kernel/apic/apic_common.c:24
Inline: False
```
**Symbols:**

```
ffffffff81067140-ffffffff8106715c: default_ioapic_phys_id_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void default_ioapic_phys_id_map(physid_mask_t *phys_map, physid_mask_t *retmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic_common.c (ffffffff81057500)
Location: arch/x86/kernel/apic/apic_common.c:24
Inline: False
```
**Symbols:**

```
ffffffff81057500-ffffffff8105751c: default_ioapic_phys_id_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void default_ioapic_phys_id_map(physid_mask_t *phys_map, physid_mask_t *retmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic_common.c (ffffffff810675f0)
Location: arch/x86/kernel/apic/apic_common.c:24
Inline: False
```
**Symbols:**

```
ffffffff810675f0-ffffffff8106760c: default_ioapic_phys_id_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void default_ioapic_phys_id_map(physid_mask_t *phys_map, physid_mask_t *retmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/apic_common.c (ffffffff81068bd0)
Location: arch/x86/kernel/apic/apic_common.c:24
Inline: False
```
**Symbols:**

```
ffffffff81068bd0-ffffffff81068bec: default_ioapic_phys_id_map (STB_GLOBAL)
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
