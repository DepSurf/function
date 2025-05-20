# Function: <code>uncore_msr_box_ctl</code>

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
In arch/x86/events/intel/uncore_nhmex.c (ffffffff81017156)
Location: arch/x86/events/intel/uncore.h:184
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_box
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_box
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff81019454)
Location: arch/x86/events/intel/uncore.h:184
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_disable_box
  - arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_init_box
  - arch/x86/events/intel/uncore_snbep.c:ivbep_uncore_msr_init_box
  - arch/x86/events/intel/uncore_snbep.c:hswep_uncore_sbox_msr_init_box
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore_nhmex.c (ffffffff810164b3)
Location: arch/x86/events/intel/uncore.h:192
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_box
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101a93a)
Location: arch/x86/events/intel/uncore.h:192
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:hswep_uncore_sbox_msr_init_box
  - arch/x86/events/intel/uncore_snbep.c:ivbep_uncore_msr_init_box
  - arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_init_box
  - arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_disable_box
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore_nhmex.c (ffffffff810166c3)
Location: arch/x86/events/intel/uncore.h:197
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_box
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101aeea)
Location: arch/x86/events/intel/uncore.h:197
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:hswep_uncore_sbox_msr_init_box
  - arch/x86/events/intel/uncore_snbep.c:ivbep_uncore_msr_init_box
  - arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_init_box
  - arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_disable_box
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore_nhmex.c (ffffffff81014c43)
Location: arch/x86/events/intel/uncore.h:197
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_box
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101929a)
Location: arch/x86/events/intel/uncore.h:197
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:hswep_uncore_sbox_msr_init_box
  - arch/x86/events/intel/uncore_snbep.c:ivbep_uncore_msr_init_box
  - arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_init_box
  - arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_disable_box
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore_nhmex.c (ffffffff81016953)
Location: arch/x86/events/intel/uncore.h:198
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_box
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff81019aea)
Location: arch/x86/events/intel/uncore.h:198
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:hswep_uncore_sbox_msr_init_box
  - arch/x86/events/intel/uncore_snbep.c:ivbep_uncore_msr_init_box
  - arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_init_box
  - arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_disable_box
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore_nhmex.c (ffffffff81017573)
Location: arch/x86/events/intel/uncore.h:224
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_box
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101a24a)
Location: arch/x86/events/intel/uncore.h:224
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:hswep_uncore_sbox_msr_init_box
  - arch/x86/events/intel/uncore_snbep.c:ivbep_uncore_msr_init_box
  - arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_init_box
  - arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_disable_box
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore_nhmex.c (ffffffff81017cf3)
Location: arch/x86/events/intel/uncore.h:231
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_box
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101ac3a)
Location: arch/x86/events/intel/uncore.h:231
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:hswep_uncore_sbox_msr_init_box
  - arch/x86/events/intel/uncore_snbep.c:ivbep_uncore_msr_init_box
  - arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_init_box
  - arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_disable_box
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore_nhmex.c (ffffffff810192e3)
Location: arch/x86/events/intel/uncore.h:243
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_box
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101c67a)
Location: arch/x86/events/intel/uncore.h:243
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:hswep_uncore_sbox_msr_init_box
  - arch/x86/events/intel/uncore_snbep.c:ivbep_uncore_msr_init_box
  - arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_init_box
  - arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_disable_box
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore_nhmex.c (ffffffff81019c63)
Location: arch/x86/events/intel/uncore.h:243
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_box
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101cffa)
Location: arch/x86/events/intel/uncore.h:243
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:hswep_uncore_sbox_msr_init_box
  - arch/x86/events/intel/uncore_snbep.c:ivbep_uncore_msr_init_box
  - arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_init_box
  - arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_disable_box
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
In arch/x86/events/intel/uncore_nhmex.c (ffffffff8101b495)
Location: arch/x86/events/intel/uncore.h:244
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_box
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101ef45)
Location: arch/x86/events/intel/uncore.h:244
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:hswep_uncore_sbox_msr_init_box
  - arch/x86/events/intel/uncore_snbep.c:ivbep_uncore_msr_init_box
  - arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_init_box
  - arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_disable_box
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore_nhmex.c (ffffffff8101b995)
Location: arch/x86/events/intel/uncore.h:281
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_box
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101f6a5)
Location: arch/x86/events/intel/uncore.h:281
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:hswep_uncore_sbox_msr_init_box
  - arch/x86/events/intel/uncore_snbep.c:ivbep_uncore_msr_init_box
  - arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_init_box
  - arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_disable_box
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore_nhmex.c (ffffffff8101cd45)
Location: arch/x86/events/intel/uncore.h:294
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_box
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff810206a5)
Location: arch/x86/events/intel/uncore.h:294
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:hswep_uncore_sbox_msr_init_box
  - arch/x86/events/intel/uncore_snbep.c:ivbep_uncore_msr_init_box
  - arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_init_box
  - arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_disable_box
```
```
In arch/x86/events/intel/uncore_discovery.c (ffffffff81021905)
Location: arch/x86/events/intel/uncore.h:294
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_discovery.c:intel_generic_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_discovery.c:intel_generic_uncore_msr_disable_box
  - arch/x86/events/intel/uncore_discovery.c:intel_generic_uncore_msr_init_box
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore_nhmex.c (ffffffff8101fe15)
Location: arch/x86/events/intel/uncore.h:295
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_box
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff810242f5)
Location: arch/x86/events/intel/uncore.h:295
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:hswep_uncore_sbox_msr_init_box
  - arch/x86/events/intel/uncore_snbep.c:ivbep_uncore_msr_init_box
  - arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_init_box
  - arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_disable_box
```
```
In arch/x86/events/intel/uncore_discovery.c (ffffffff81025665)
Location: arch/x86/events/intel/uncore.h:295
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_discovery.c:intel_generic_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_discovery.c:intel_generic_uncore_msr_disable_box
  - arch/x86/events/intel/uncore_discovery.c:intel_generic_uncore_msr_init_box
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore_nhmex.c (ffffffff81022ce5)
Location: arch/x86/events/intel/uncore.h:295
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_box
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff810280d5)
Location: arch/x86/events/intel/uncore.h:295
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:hswep_uncore_sbox_msr_init_box
  - arch/x86/events/intel/uncore_snbep.c:ivbep_uncore_msr_init_box
  - arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_init_box
  - arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_disable_box
```
```
In arch/x86/events/intel/uncore_discovery.c (ffffffff81029695)
Location: arch/x86/events/intel/uncore.h:295
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_discovery.c:intel_generic_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_discovery.c:intel_generic_uncore_msr_disable_box
  - arch/x86/events/intel/uncore_discovery.c:intel_generic_uncore_msr_init_box
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
In arch/x86/events/intel/uncore_nhmex.c (ffffffff810279c5)
Location: arch/x86/events/intel/uncore.h:311
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_box
```
```
In arch/x86/events/intel/uncore_snb.c (ffffffff81028b95)
Location: arch/x86/events/intel/uncore.h:311
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snb.c:mtl_uncore_msr_init_box
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8102e625)
Location: arch/x86/events/intel/uncore.h:311
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:hswep_uncore_sbox_msr_init_box
  - arch/x86/events/intel/uncore_snbep.c:ivbep_uncore_msr_init_box
  - arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_init_box
  - arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_disable_box
```
```
In arch/x86/events/intel/uncore_discovery.c (ffffffff810300e5)
Location: arch/x86/events/intel/uncore.h:311
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_discovery.c:intel_generic_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_discovery.c:intel_generic_uncore_msr_disable_box
  - arch/x86/events/intel/uncore_discovery.c:intel_generic_uncore_msr_init_box
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
In arch/x86/events/intel/uncore_nhmex.c (ffffffff810279e5)
Location: arch/x86/events/intel/uncore.h:314
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_box
```
```
In arch/x86/events/intel/uncore_snb.c (ffffffff81028bc5)
Location: arch/x86/events/intel/uncore.h:314
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snb.c:mtl_uncore_msr_init_box
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8102e605)
Location: arch/x86/events/intel/uncore.h:314
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:hswep_uncore_sbox_msr_init_box
  - arch/x86/events/intel/uncore_snbep.c:ivbep_uncore_msr_init_box
  - arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_init_box
  - arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_disable_box
```
```
In arch/x86/events/intel/uncore_discovery.c (ffffffff810300b5)
Location: arch/x86/events/intel/uncore.h:314
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_discovery.c:intel_generic_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_discovery.c:intel_generic_uncore_msr_disable_box
  - arch/x86/events/intel/uncore_discovery.c:intel_generic_uncore_msr_init_box
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
In arch/x86/events/intel/uncore_nhmex.c (ffffffff8102dc35)
Location: arch/x86/events/intel/uncore.h:314
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_box
```
```
In arch/x86/events/intel/uncore_snb.c (ffffffff8102ed25)
Location: arch/x86/events/intel/uncore.h:314
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snb.c:mtl_uncore_msr_init_box
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff81034775)
Location: arch/x86/events/intel/uncore.h:314
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:hswep_uncore_sbox_msr_init_box
  - arch/x86/events/intel/uncore_snbep.c:ivbep_uncore_msr_init_box
  - arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_init_box
  - arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_disable_box
```
```
In arch/x86/events/intel/uncore_discovery.c (ffffffff81036355)
Location: arch/x86/events/intel/uncore.h:314
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_discovery.c:intel_generic_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_discovery.c:intel_generic_uncore_msr_disable_box
  - arch/x86/events/intel/uncore_discovery.c:intel_generic_uncore_msr_init_box
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
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore_nhmex.c (ffffffff81019c63)
Location: arch/x86/events/intel/uncore.h:243
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_box
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101cffa)
Location: arch/x86/events/intel/uncore.h:243
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:hswep_uncore_sbox_msr_init_box
  - arch/x86/events/intel/uncore_snbep.c:ivbep_uncore_msr_init_box
  - arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_init_box
  - arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_disable_box
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore_nhmex.c (ffffffff81019198)
Location: arch/x86/events/intel/uncore.h:243
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_box
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101c70a)
Location: arch/x86/events/intel/uncore.h:243
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:hswep_uncore_sbox_msr_init_box
  - arch/x86/events/intel/uncore_snbep.c:ivbep_uncore_msr_init_box
  - arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_init_box
  - arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_disable_box
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore_nhmex.c (ffffffff81019c23)
Location: arch/x86/events/intel/uncore.h:243
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_box
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101cfba)
Location: arch/x86/events/intel/uncore.h:243
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:hswep_uncore_sbox_msr_init_box
  - arch/x86/events/intel/uncore_snbep.c:ivbep_uncore_msr_init_box
  - arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_init_box
  - arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_disable_box
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore_nhmex.c (ffffffff81019e63)
Location: arch/x86/events/intel/uncore.h:243
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_box
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101d20a)
Location: arch/x86/events/intel/uncore.h:243
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:hswep_uncore_sbox_msr_init_box
  - arch/x86/events/intel/uncore_snbep.c:ivbep_uncore_msr_init_box
  - arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_init_box
  - arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_disable_box
```
</details>
</li>
</ul>

## Differences
