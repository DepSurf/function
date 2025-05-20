# Function: <code>insn_decode_mmio</code>

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
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
enum mmio_type insn_decode_mmio(struct insn *insn, int *bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff817907d0)
Location: arch/x86/lib/insn-eval.c:1600
Inline: False
Direct callers:
  - arch/x86/coco/tdx/tdx.c:handle_mmio
  - arch/x86/kernel/sev.c:vc_handle_mmio
```
**Symbols:**

```
ffffffff817907d0-ffffffff81790933: insn_decode_mmio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
enum insn_mmio_type insn_decode_mmio(struct insn *insn, int *bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff8204e400)
Location: arch/x86/lib/insn-eval.c:1600
Inline: False
Direct callers:
  - arch/x86/coco/tdx/tdx.c:handle_mmio
  - arch/x86/kernel/sev.c:vc_handle_mmio
```
**Symbols:**

```
ffffffff8204e400-ffffffff8204e563: insn_decode_mmio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
enum insn_mmio_type insn_decode_mmio(struct insn *insn, int *bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff820ccc90)
Location: arch/x86/lib/insn-eval.c:1600
Inline: False
Direct callers:
  - arch/x86/coco/tdx/tdx.c:handle_mmio
  - arch/x86/kernel/sev.c:vc_handle_mmio
```
**Symbols:**

```
ffffffff820ccc90-ffffffff820ccdef: insn_decode_mmio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
enum insn_mmio_type insn_decode_mmio(struct insn *insn, int *bytes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff821a74b0)
Location: arch/x86/lib/insn-eval.c:1600
Inline: False
Direct callers:
  - arch/x86/coco/tdx/tdx.c:handle_mmio
  - arch/x86/kernel/sev.c:vc_handle_mmio
```
**Symbols:**

```
ffffffff821a74b0-ffffffff821a760f: insn_decode_mmio (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>enum mmio_type</code> ➡️ <code>enum insn_mmio_type</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
