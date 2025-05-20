# Function: <code>intel_generic_uncore_mmio_init_box</code>

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
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void intel_generic_uncore_mmio_init_box(struct intel_uncore_box *box);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/uncore_discovery.c (0)
Location: arch/x86/events/intel/uncore_discovery.c:457
Inline: False
```
**Symbols:**

```
ffffffff81021690-ffffffff81021717: intel_generic_uncore_mmio_init_box (STB_LOCAL)
ffffffff81bc487f-ffffffff81bc48c8: intel_generic_uncore_mmio_init_box.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void intel_generic_uncore_mmio_init_box(struct intel_uncore_box *box);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/uncore_discovery.c (0)
Location: arch/x86/events/intel/uncore_discovery.c:457
Inline: False
```
**Symbols:**

```
ffffffff81c96dbb-ffffffff81c96e04: intel_generic_uncore_mmio_init_box.cold (STB_LOCAL)
ffffffff810253f0-ffffffff81025477: intel_generic_uncore_mmio_init_box (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void intel_generic_uncore_mmio_init_box(struct intel_uncore_box *box);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/uncore_discovery.c (0)
Location: arch/x86/events/intel/uncore_discovery.c:465
Inline: False
```
**Symbols:**

```
ffffffff81e46211-ffffffff81e4625e: intel_generic_uncore_mmio_init_box.cold (STB_LOCAL)
ffffffff810292c0-ffffffff81029358: intel_generic_uncore_mmio_init_box (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void intel_generic_uncore_mmio_init_box(struct intel_uncore_box *box);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore_discovery.c (ffffffff8102fbf0)
Location: arch/x86/events/intel/uncore_discovery.c:465
Inline: False
```
**Symbols:**

```
ffffffff8102fbf0-ffffffff8102fcce: intel_generic_uncore_mmio_init_box (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void intel_generic_uncore_mmio_init_box(struct intel_uncore_box *box);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore_discovery.c (ffffffff8102fce0)
Location: arch/x86/events/intel/uncore_discovery.c:485
Inline: False
```
**Symbols:**

```
ffffffff8102fce0-ffffffff8102fdbe: intel_generic_uncore_mmio_init_box (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void intel_generic_uncore_mmio_init_box(struct intel_uncore_box *box);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore_discovery.c (ffffffff81035f80)
Location: arch/x86/events/intel/uncore_discovery.c:486
Inline: False
```
**Symbols:**

```
ffffffff81035f80-ffffffff8103605e: intel_generic_uncore_mmio_init_box (STB_GLOBAL)
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
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
