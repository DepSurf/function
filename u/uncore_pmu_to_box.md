# Function: <code>uncore_pmu_to_box</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct intel_uncore_box *uncore_pmu_to_box(struct intel_uncore_pmu *pmu, int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff810155a0)
Location: arch/x86/events/intel/uncore.c:90
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_change_context
  - arch/x86/events/intel/uncore.c:uncore_change_context
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_init
  - arch/x86/events/intel/uncore.c:uncore_event_to_box
Direct callers:
  - arch/x86/events/intel/uncore.c:uncore_change_context
  - arch/x86/events/intel/uncore.c:uncore_change_context
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_init
  - arch/x86/events/intel/uncore.c:uncore_event_to_box
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_event_init
```
**Symbols:**

```
ffffffff810155a0-ffffffff8101566f: uncore_pmu_to_box.part.17 (STB_LOCAL)
ffffffff81016630-ffffffff8101665c: uncore_pmu_to_box (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct intel_uncore_box *uncore_pmu_to_box(struct intel_uncore_pmu *pmu, int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff810151ab)
Location: arch/x86/events/intel/uncore.c:101
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_init
Direct callers:
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_event_init
```
**Symbols:**

```
ffffffff81015a40-ffffffff81015a70: uncore_pmu_to_box (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct intel_uncore_box *uncore_pmu_to_box(struct intel_uncore_pmu *pmu, int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff8101528b)
Location: arch/x86/events/intel/uncore.c:101
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_init
Direct callers:
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_event_init
```
**Symbols:**

```
ffffffff81015c00-ffffffff81015c3f: uncore_pmu_to_box (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct intel_uncore_box *uncore_pmu_to_box(struct intel_uncore_pmu *pmu, int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff810137a6)
Location: arch/x86/events/intel/uncore.c:101
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_init
Direct callers:
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_event_init
```
**Symbols:**

```
ffffffff810140b0-ffffffff810140ef: uncore_pmu_to_box (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct intel_uncore_box *uncore_pmu_to_box(struct intel_uncore_pmu *pmu, int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff81013fe6)
Location: arch/x86/events/intel/uncore.c:101
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_init
Direct callers:
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_event_init
```
**Symbols:**

```
ffffffff810148e0-ffffffff8101491f: uncore_pmu_to_box (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct intel_uncore_box *uncore_pmu_to_box(struct intel_uncore_pmu *pmu, int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff81014716)
Location: arch/x86/events/intel/uncore.c:101
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_init
Direct callers:
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_event_init
```
**Symbols:**

```
ffffffff81015420-ffffffff8101545a: uncore_pmu_to_box (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct intel_uncore_box *uncore_pmu_to_box(struct intel_uncore_pmu *pmu, int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff81014e16)
Location: arch/x86/events/intel/uncore.c:101
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_init
Direct callers:
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_event_init
```
**Symbols:**

```
ffffffff81015b30-ffffffff81015b6a: uncore_pmu_to_box (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct intel_uncore_box *uncore_pmu_to_box(struct intel_uncore_pmu *pmu, int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff81016458)
Location: arch/x86/events/intel/uncore.c:103
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_init
Direct callers:
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_event_init
```
**Symbols:**

```
ffffffff810170e0-ffffffff81017121: uncore_pmu_to_box (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct intel_uncore_box *uncore_pmu_to_box(struct intel_uncore_pmu *pmu, int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff81016471)
Location: arch/x86/events/intel/uncore.c:103
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_disable
  - arch/x86/events/intel/uncore.c:uncore_pmu_enable
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_init
Direct callers:
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_event_init
```
**Symbols:**

```
ffffffff81017a90-ffffffff81017ad1: uncore_pmu_to_box (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct intel_uncore_box *uncore_pmu_to_box(struct intel_uncore_pmu *pmu, int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff810189c1)
Location: arch/x86/events/intel/uncore.c:103
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_disable
  - arch/x86/events/intel/uncore.c:uncore_pmu_enable
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_init
Direct callers:
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_event_init
```
**Symbols:**

```
ffffffff81019640-ffffffff81019681: uncore_pmu_to_box (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct intel_uncore_box *uncore_pmu_to_box(struct intel_uncore_pmu *pmu, int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff81019141)
Location: arch/x86/events/intel/uncore.c:105
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_disable
  - arch/x86/events/intel/uncore.c:uncore_pmu_enable
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_init
Direct callers:
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_event_init
```
**Symbols:**

```
ffffffff81019c80-ffffffff81019cc1: uncore_pmu_to_box (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct intel_uncore_box *uncore_pmu_to_box(struct intel_uncore_pmu *pmu, int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff8101a461)
Location: arch/x86/events/intel/uncore.c:122
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_disable
  - arch/x86/events/intel/uncore.c:uncore_pmu_enable
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_init
Direct callers:
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_event_init
```
**Symbols:**

```
ffffffff8101b000-ffffffff8101b041: uncore_pmu_to_box (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct intel_uncore_box *uncore_pmu_to_box(struct intel_uncore_pmu *pmu, int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff8101cdaf)
Location: arch/x86/events/intel/uncore.c:122
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_disable
  - arch/x86/events/intel/uncore.c:uncore_pmu_enable
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_init
Direct callers:
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_event_init
```
**Symbols:**

```
ffffffff8101d900-ffffffff8101d972: uncore_pmu_to_box (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct intel_uncore_box *uncore_pmu_to_box(struct intel_uncore_pmu *pmu, int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff8101f5bf)
Location: arch/x86/events/intel/uncore.c:122
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_disable
  - arch/x86/events/intel/uncore.c:uncore_pmu_enable
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_init
Direct callers:
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_event_init
```
**Symbols:**

```
ffffffff81020300-ffffffff8102037a: uncore_pmu_to_box (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct intel_uncore_box *uncore_pmu_to_box(struct intel_uncore_pmu *pmu, int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff81023d2f)
Location: arch/x86/events/intel/uncore.c:122
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_disable
  - arch/x86/events/intel/uncore.c:uncore_pmu_enable
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_init
Direct callers:
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_event_init
```
**Symbols:**

```
ffffffff81024bd0-ffffffff81024c4a: uncore_pmu_to_box (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct intel_uncore_box *uncore_pmu_to_box(struct intel_uncore_pmu *pmu, int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff81023a4f)
Location: arch/x86/events/intel/uncore.c:137
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_disable
  - arch/x86/events/intel/uncore.c:uncore_pmu_enable
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_init
Direct callers:
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_event_init
```
**Symbols:**

```
ffffffff81024ad0-ffffffff81024b4a: uncore_pmu_to_box (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct intel_uncore_box *uncore_pmu_to_box(struct intel_uncore_pmu *pmu, int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff81029b7f)
Location: arch/x86/events/intel/uncore.c:137
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_disable
  - arch/x86/events/intel/uncore.c:uncore_pmu_enable
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_init
Direct callers:
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_event_init
```
**Symbols:**

```
ffffffff8102ac30-ffffffff8102aca7: uncore_pmu_to_box (STB_GLOBAL)
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
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
struct intel_uncore_box *uncore_pmu_to_box(struct intel_uncore_pmu *pmu, int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff81016471)
Location: arch/x86/events/intel/uncore.c:103
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_disable
  - arch/x86/events/intel/uncore.c:uncore_pmu_enable
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_init
Direct callers:
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_event_init
```
**Symbols:**

```
ffffffff81017a90-ffffffff81017ad1: uncore_pmu_to_box (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct intel_uncore_box *uncore_pmu_to_box(struct intel_uncore_pmu *pmu, int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff810158a1)
Location: arch/x86/events/intel/uncore.c:103
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_disable
  - arch/x86/events/intel/uncore.c:uncore_pmu_enable
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_init
Direct callers:
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_event_init
```
**Symbols:**

```
ffffffff81016ec0-ffffffff81016f01: uncore_pmu_to_box (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct intel_uncore_box *uncore_pmu_to_box(struct intel_uncore_pmu *pmu, int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff81016431)
Location: arch/x86/events/intel/uncore.c:103
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_disable
  - arch/x86/events/intel/uncore.c:uncore_pmu_enable
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_init
Direct callers:
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_event_init
```
**Symbols:**

```
ffffffff81017a50-ffffffff81017a91: uncore_pmu_to_box (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct intel_uncore_box *uncore_pmu_to_box(struct intel_uncore_pmu *pmu, int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore.c (ffffffff81016671)
Location: arch/x86/events/intel/uncore.c:103
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pmu_disable
  - arch/x86/events/intel/uncore.c:uncore_pmu_enable
  - arch/x86/events/intel/uncore.c:uncore_pmu_event_init
Direct callers:
  - arch/x86/events/intel/uncore_snb.c:snb_uncore_imc_event_init
```
**Symbols:**

```
ffffffff81017c90-ffffffff81017cd1: uncore_pmu_to_box (STB_GLOBAL)
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
