# Function: <code>uncore_msr_box_offset</code>

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
In arch/x86/events/intel/uncore.c (ffffffff81016fe2)
Location: arch/x86/events/intel/uncore.h:176
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_add
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_add
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_add
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_add
```
```
In arch/x86/events/intel/uncore_nhmex.c (ffffffff81017168)
Location: arch/x86/events/intel/uncore.h:176
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_box
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_box
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_box
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff81019462)
Location: arch/x86/events/intel/uncore.h:176
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
In arch/x86/events/intel/uncore.c (ffffffff81016241)
Location: arch/x86/events/intel/uncore.h:184
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_add
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_add
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_add
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_add
```
```
In arch/x86/events/intel/uncore_nhmex.c (ffffffff810164c1)
Location: arch/x86/events/intel/uncore.h:184
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_box
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_box
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101a94a)
Location: arch/x86/events/intel/uncore.h:184
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
In arch/x86/events/intel/uncore.c (ffffffff81016464)
Location: arch/x86/events/intel/uncore.h:189
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_add
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_add
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_add
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_add
```
```
In arch/x86/events/intel/uncore_nhmex.c (ffffffff810166d1)
Location: arch/x86/events/intel/uncore.h:189
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_box
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_box
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101aefa)
Location: arch/x86/events/intel/uncore.h:189
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
In arch/x86/events/intel/uncore.c (ffffffff810148dc)
Location: arch/x86/events/intel/uncore.h:189
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_add
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_add
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_add
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_add
```
```
In arch/x86/events/intel/uncore_nhmex.c (ffffffff81014c51)
Location: arch/x86/events/intel/uncore.h:189
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_box
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_box
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff810192aa)
Location: arch/x86/events/intel/uncore.h:189
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
In arch/x86/events/intel/uncore.c (ffffffff8101513c)
Location: arch/x86/events/intel/uncore.h:190
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_add
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_add
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_add
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_add
```
```
In arch/x86/events/intel/uncore_nhmex.c (ffffffff81016961)
Location: arch/x86/events/intel/uncore.h:190
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_box
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_box
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff81019afa)
Location: arch/x86/events/intel/uncore.h:190
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
In arch/x86/events/intel/uncore.c (ffffffff81015c42)
Location: arch/x86/events/intel/uncore.h:216
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_add
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_add
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_add
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_add
```
```
In arch/x86/events/intel/uncore_nhmex.c (ffffffff81017588)
Location: arch/x86/events/intel/uncore.h:216
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_box
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_box
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101a25a)
Location: arch/x86/events/intel/uncore.h:216
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
In arch/x86/events/intel/uncore.c (ffffffff8101638b)
Location: arch/x86/events/intel/uncore.h:223
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_add
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_add
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_add
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_add
```
```
In arch/x86/events/intel/uncore_nhmex.c (ffffffff81017d08)
Location: arch/x86/events/intel/uncore.h:223
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_box
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_box
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101ac4a)
Location: arch/x86/events/intel/uncore.h:223
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
In arch/x86/events/intel/uncore.c (ffffffff81017a47)
Location: arch/x86/events/intel/uncore.h:235
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_add
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_add
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_add
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_add
```
```
In arch/x86/events/intel/uncore_nhmex.c (ffffffff810192ff)
Location: arch/x86/events/intel/uncore.h:235
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_box
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_box
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101c68a)
Location: arch/x86/events/intel/uncore.h:235
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
In arch/x86/events/intel/uncore.c (ffffffff810183d7)
Location: arch/x86/events/intel/uncore.h:235
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_add
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_add
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_add
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_add
```
```
In arch/x86/events/intel/uncore_nhmex.c (ffffffff81019c7f)
Location: arch/x86/events/intel/uncore.h:235
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_box
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_box
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101d00a)
Location: arch/x86/events/intel/uncore.h:235
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
In arch/x86/events/intel/uncore.c (ffffffff8101905c)
Location: arch/x86/events/intel/uncore.h:236
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_assign_hw_event
  - arch/x86/events/intel/uncore.c:uncore_assign_hw_event
  - arch/x86/events/intel/uncore.c:uncore_assign_hw_event
  - arch/x86/events/intel/uncore.c:uncore_assign_hw_event
```
```
In arch/x86/events/intel/uncore_nhmex.c (ffffffff8101b4b8)
Location: arch/x86/events/intel/uncore.h:236
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_box
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_box
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101ed18)
Location: arch/x86/events/intel/uncore.h:236
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
In arch/x86/events/intel/uncore.c (ffffffff810197de)
Location: arch/x86/events/intel/uncore.h:273
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_assign_hw_event
  - arch/x86/events/intel/uncore.c:uncore_assign_hw_event
  - arch/x86/events/intel/uncore.c:uncore_assign_hw_event
  - arch/x86/events/intel/uncore.c:uncore_assign_hw_event
```
```
In arch/x86/events/intel/uncore_nhmex.c (ffffffff8101b9b8)
Location: arch/x86/events/intel/uncore.h:273
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_box
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_box
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101f478)
Location: arch/x86/events/intel/uncore.h:273
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
In arch/x86/events/intel/uncore.c (ffffffff8101ab03)
Location: arch/x86/events/intel/uncore.h:286
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_assign_hw_event
  - arch/x86/events/intel/uncore.c:uncore_assign_hw_event
  - arch/x86/events/intel/uncore.c:uncore_assign_hw_event
  - arch/x86/events/intel/uncore.c:uncore_assign_hw_event
```
```
In arch/x86/events/intel/uncore_nhmex.c (ffffffff8101cd6f)
Location: arch/x86/events/intel/uncore.h:286
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_box
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_box
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff810206be)
Location: arch/x86/events/intel/uncore.h:286
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:hswep_uncore_sbox_msr_init_box
  - arch/x86/events/intel/uncore_snbep.c:ivbep_uncore_msr_init_box
  - arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_init_box
  - arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_disable_box
```
```
In arch/x86/events/intel/uncore_discovery.c (ffffffff81021920)
Location: arch/x86/events/intel/uncore.h:286
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
In arch/x86/events/intel/uncore.c (ffffffff8101d4e1)
Location: arch/x86/events/intel/uncore.h:287
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_assign_hw_event
  - arch/x86/events/intel/uncore.c:uncore_assign_hw_event
  - arch/x86/events/intel/uncore.c:uncore_assign_hw_event
  - arch/x86/events/intel/uncore.c:uncore_assign_hw_event
```
```
In arch/x86/events/intel/uncore_nhmex.c (ffffffff8101fe47)
Location: arch/x86/events/intel/uncore.h:287
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_box
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_box
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8102430e)
Location: arch/x86/events/intel/uncore.h:287
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:hswep_uncore_sbox_msr_init_box
  - arch/x86/events/intel/uncore_snbep.c:ivbep_uncore_msr_init_box
  - arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_init_box
  - arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_disable_box
```
```
In arch/x86/events/intel/uncore_discovery.c (ffffffff81025680)
Location: arch/x86/events/intel/uncore.h:287
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
In arch/x86/events/intel/uncore.c (ffffffff8101fe55)
Location: arch/x86/events/intel/uncore.h:287
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_assign_hw_event
  - arch/x86/events/intel/uncore.c:uncore_assign_hw_event
  - arch/x86/events/intel/uncore.c:uncore_assign_hw_event
  - arch/x86/events/intel/uncore.c:uncore_assign_hw_event
```
```
In arch/x86/events/intel/uncore_nhmex.c (ffffffff81022d17)
Location: arch/x86/events/intel/uncore.h:287
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_box
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_box
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff810280ee)
Location: arch/x86/events/intel/uncore.h:287
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:hswep_uncore_sbox_msr_init_box
  - arch/x86/events/intel/uncore_snbep.c:ivbep_uncore_msr_init_box
  - arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_init_box
  - arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_disable_box
```
```
In arch/x86/events/intel/uncore_discovery.c (ffffffff810296b0)
Location: arch/x86/events/intel/uncore.h:287
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
In arch/x86/events/intel/uncore.c (ffffffff810246b5)
Location: arch/x86/events/intel/uncore.h:303
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_assign_hw_event
  - arch/x86/events/intel/uncore.c:uncore_assign_hw_event
  - arch/x86/events/intel/uncore.c:uncore_assign_hw_event
  - arch/x86/events/intel/uncore.c:uncore_assign_hw_event
```
```
In arch/x86/events/intel/uncore_nhmex.c (ffffffff810279f7)
Location: arch/x86/events/intel/uncore.h:303
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_box
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_box
```
```
In arch/x86/events/intel/uncore_snb.c (ffffffff81028bb0)
Location: arch/x86/events/intel/uncore.h:303
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snb.c:mtl_uncore_msr_init_box
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8102e63e)
Location: arch/x86/events/intel/uncore.h:303
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:hswep_uncore_sbox_msr_init_box
  - arch/x86/events/intel/uncore_snbep.c:ivbep_uncore_msr_init_box
  - arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_init_box
  - arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_disable_box
```
```
In arch/x86/events/intel/uncore_discovery.c (ffffffff81030100)
Location: arch/x86/events/intel/uncore.h:303
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
In arch/x86/events/intel/uncore.c (ffffffff81024415)
Location: arch/x86/events/intel/uncore.h:306
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_assign_hw_event
  - arch/x86/events/intel/uncore.c:uncore_assign_hw_event
  - arch/x86/events/intel/uncore.c:uncore_assign_hw_event
  - arch/x86/events/intel/uncore.c:uncore_assign_hw_event
```
```
In arch/x86/events/intel/uncore_nhmex.c (ffffffff81027a17)
Location: arch/x86/events/intel/uncore.h:306
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_box
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_box
```
```
In arch/x86/events/intel/uncore_snb.c (ffffffff81028be0)
Location: arch/x86/events/intel/uncore.h:306
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snb.c:mtl_uncore_msr_init_box
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8102e61e)
Location: arch/x86/events/intel/uncore.h:306
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:hswep_uncore_sbox_msr_init_box
  - arch/x86/events/intel/uncore_snbep.c:ivbep_uncore_msr_init_box
  - arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_init_box
  - arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_disable_box
```
```
In arch/x86/events/intel/uncore_discovery.c (ffffffff810300d0)
Location: arch/x86/events/intel/uncore.h:306
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
In arch/x86/events/intel/uncore.c (ffffffff8102a545)
Location: arch/x86/events/intel/uncore.h:306
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_assign_hw_event
  - arch/x86/events/intel/uncore.c:uncore_assign_hw_event
  - arch/x86/events/intel/uncore.c:uncore_assign_hw_event
  - arch/x86/events/intel/uncore.c:uncore_assign_hw_event
```
```
In arch/x86/events/intel/uncore_nhmex.c (ffffffff8102dc67)
Location: arch/x86/events/intel/uncore.h:306
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_box
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_box
```
```
In arch/x86/events/intel/uncore_snb.c (ffffffff8102ed40)
Location: arch/x86/events/intel/uncore.h:306
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snb.c:mtl_uncore_msr_init_box
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8103478e)
Location: arch/x86/events/intel/uncore.h:306
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_snbep.c:hswep_uncore_sbox_msr_init_box
  - arch/x86/events/intel/uncore_snbep.c:ivbep_uncore_msr_init_box
  - arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_init_box
  - arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_snbep.c:snbep_uncore_msr_disable_box
```
```
In arch/x86/events/intel/uncore_discovery.c (ffffffff81036370)
Location: arch/x86/events/intel/uncore.h:306
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
In arch/x86/events/intel/uncore.c (ffffffff810183d7)
Location: arch/x86/events/intel/uncore.h:235
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_add
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_add
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_add
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_add
```
```
In arch/x86/events/intel/uncore_nhmex.c (ffffffff81019c7f)
Location: arch/x86/events/intel/uncore.h:235
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_box
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_box
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101d00a)
Location: arch/x86/events/intel/uncore.h:235
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
In arch/x86/events/intel/uncore.c (ffffffff81017807)
Location: arch/x86/events/intel/uncore.h:235
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_add
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_add
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_add
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_add
```
```
In arch/x86/events/intel/uncore_nhmex.c (ffffffff810191a6)
Location: arch/x86/events/intel/uncore.h:235
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_box
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_box
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101c718)
Location: arch/x86/events/intel/uncore.h:235
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
In arch/x86/events/intel/uncore.c (ffffffff81018397)
Location: arch/x86/events/intel/uncore.h:235
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_add
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_add
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_add
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_add
```
```
In arch/x86/events/intel/uncore_nhmex.c (ffffffff81019c3f)
Location: arch/x86/events/intel/uncore.h:235
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_box
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_box
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101cfca)
Location: arch/x86/events/intel/uncore.h:235
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
In arch/x86/events/intel/uncore.c (ffffffff810185d7)
Location: arch/x86/events/intel/uncore.h:235
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_add
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_add
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_add
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_add
```
```
In arch/x86/events/intel/uncore_nhmex.c (ffffffff81019e7f)
Location: arch/x86/events/intel/uncore.h:235
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_enable_box
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_box
  - arch/x86/events/intel/uncore_nhmex.c:nhmex_uncore_msr_disable_box
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101d21a)
Location: arch/x86/events/intel/uncore.h:235
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
