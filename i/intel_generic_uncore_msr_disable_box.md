# Function: <code>intel_generic_uncore_msr_disable_box</code>

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
<summary>In <code>5.13</code>: ✅</summary>

```c
void intel_generic_uncore_msr_disable_box(struct intel_uncore_box *box);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore_discovery.c (ffffffff810219a0)
Location: arch/x86/events/intel/uncore_discovery.c:345
Inline: False
```
**Symbols:**

```
ffffffff810219a0-ffffffff810219ec: intel_generic_uncore_msr_disable_box (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void intel_generic_uncore_msr_disable_box(struct intel_uncore_box *box);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore_discovery.c (ffffffff81025700)
Location: arch/x86/events/intel/uncore_discovery.c:345
Inline: False
```
**Symbols:**

```
ffffffff81025700-ffffffff8102574c: intel_generic_uncore_msr_disable_box (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void intel_generic_uncore_msr_disable_box(struct intel_uncore_box *box);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore_discovery.c (ffffffff81029700)
Location: arch/x86/events/intel/uncore_discovery.c:353
Inline: False
```
**Symbols:**

```
ffffffff81029700-ffffffff81029765: intel_generic_uncore_msr_disable_box (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void intel_generic_uncore_msr_disable_box(struct intel_uncore_box *box);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore_discovery.c (ffffffff81030160)
Location: arch/x86/events/intel/uncore_discovery.c:353
Inline: False
```
**Symbols:**

```
ffffffff81030160-ffffffff810301c5: intel_generic_uncore_msr_disable_box (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void intel_generic_uncore_msr_disable_box(struct intel_uncore_box *box);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore_discovery.c (ffffffff81030250)
Location: arch/x86/events/intel/uncore_discovery.c:373
Inline: False
```
**Symbols:**

```
ffffffff81030250-ffffffff810302b5: intel_generic_uncore_msr_disable_box (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void intel_generic_uncore_msr_disable_box(struct intel_uncore_box *box);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore_discovery.c (ffffffff810364f0)
Location: arch/x86/events/intel/uncore_discovery.c:374
Inline: False
```
**Symbols:**

```
ffffffff810364f0-ffffffff81036555: intel_generic_uncore_msr_disable_box (STB_GLOBAL)
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
