# Function: <code>get_desc</code>

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
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct desc_struct *get_desc(short unsigned int sel);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff81983060)
Location: arch/x86/lib/insn-eval.c:570
Inline: True
Direct callers:
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
  - arch/x86/lib/insn-eval.c:insn_get_code_seg_params
```
**Symbols:**

```
ffffffff81983060-ffffffff8198314c: get_desc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct desc_struct *get_desc(short unsigned int sel);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff819df5b0)
Location: arch/x86/lib/insn-eval.c:570
Inline: True
Direct callers:
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
  - arch/x86/lib/insn-eval.c:insn_get_code_seg_params
```
**Symbols:**

```
ffffffff819df5b0-ffffffff819df69c: get_desc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct desc_struct *get_desc(short unsigned int sel);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff81a1a4f0)
Location: arch/x86/lib/insn-eval.c:570
Inline: True
Direct callers:
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
  - arch/x86/lib/insn-eval.c:insn_get_code_seg_params
```
**Symbols:**

```
ffffffff81a1a4f0-ffffffff81a1a5de: get_desc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
bool get_desc(struct desc_struct *out, short unsigned int sel);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff81a8a1d0)
Location: arch/x86/lib/insn-eval.c:573
Inline: True
Direct callers:
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
  - arch/x86/lib/insn-eval.c:insn_get_code_seg_params
```
**Symbols:**

```
ffffffff81a8a1d0-ffffffff81a8a2ce: get_desc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
bool get_desc(struct desc_struct *out, short unsigned int sel);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff81ac1490)
Location: arch/x86/lib/insn-eval.c:573
Inline: True
Direct callers:
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
  - arch/x86/lib/insn-eval.c:insn_get_code_seg_params
```
**Symbols:**

```
ffffffff81ac1490-ffffffff81ac158e: get_desc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool get_desc(struct desc_struct *out, short unsigned int sel);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff815fd8f0)
Location: arch/x86/lib/insn-eval.c:573
Inline: True
Direct callers:
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
  - arch/x86/lib/insn-eval.c:insn_get_code_seg_params
  - arch/x86/lib/insn-eval.c:insn_get_seg_base
```
**Symbols:**

```
ffffffff815fd8f0-ffffffff815fd9ee: get_desc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool get_desc(struct desc_struct *out, short unsigned int sel);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff81622770)
Location: arch/x86/lib/insn-eval.c:603
Inline: True
Direct callers:
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
  - arch/x86/lib/insn-eval.c:insn_get_code_seg_params
  - arch/x86/lib/insn-eval.c:insn_get_seg_base
```
**Symbols:**

```
ffffffff81622770-ffffffff8162286e: get_desc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool get_desc(struct desc_struct *out, short unsigned int sel);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff81605f40)
Location: arch/x86/lib/insn-eval.c:599
Inline: True
Direct callers:
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
  - arch/x86/lib/insn-eval.c:insn_get_code_seg_params
  - arch/x86/lib/insn-eval.c:insn_get_seg_base
```
**Symbols:**

```
ffffffff81605f40-ffffffff8160603e: get_desc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
bool get_desc(struct desc_struct *out, short unsigned int sel);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff81674930)
Location: arch/x86/lib/insn-eval.c:599
Inline: True
Direct callers:
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
  - arch/x86/lib/insn-eval.c:insn_get_code_seg_params
  - arch/x86/lib/insn-eval.c:insn_get_seg_base
```
**Symbols:**

```
ffffffff81674930-ffffffff81674a2e: get_desc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
bool get_desc(struct desc_struct *out, short unsigned int sel);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff8178f180)
Location: arch/x86/lib/insn-eval.c:621
Inline: True
Direct callers:
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
  - arch/x86/lib/insn-eval.c:insn_get_code_seg_params
```
**Symbols:**

```
ffffffff8178f180-ffffffff8178f288: get_desc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
bool get_desc(struct desc_struct *out, short unsigned int sel);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff8204cc80)
Location: arch/x86/lib/insn-eval.c:621
Inline: True
Direct callers:
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
  - arch/x86/lib/insn-eval.c:insn_get_code_seg_params
```
**Symbols:**

```
ffffffff8204cc80-ffffffff8204cd88: get_desc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
bool get_desc(struct desc_struct *out, short unsigned int sel);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff820cb550)
Location: arch/x86/lib/insn-eval.c:621
Inline: True
Direct callers:
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
  - arch/x86/lib/insn-eval.c:insn_get_code_seg_params
```
**Symbols:**

```
ffffffff820cb550-ffffffff820cb655: get_desc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
bool get_desc(struct desc_struct *out, short unsigned int sel);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff821a5d80)
Location: arch/x86/lib/insn-eval.c:621
Inline: True
Direct callers:
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
  - arch/x86/lib/insn-eval.c:insn_get_code_seg_params
```
**Symbols:**

```
ffffffff821a5d80-ffffffff821a5e85: get_desc (STB_LOCAL)
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
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/host/cqhci.c (c0c30f94)
Location: drivers/mmc/host/cqhci.c:34
Inline: True
Inline callers:
  - drivers/mmc/host/cqhci.c:cqhci_request
  - drivers/mmc/host/cqhci.c:cqhci_request
  - drivers/mmc/host/cqhci.c:cqhci_enable
```
</details>
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
bool get_desc(struct desc_struct *out, short unsigned int sel);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff81a602e0)
Location: arch/x86/lib/insn-eval.c:573
Inline: True
Direct callers:
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
  - arch/x86/lib/insn-eval.c:insn_get_code_seg_params
```
**Symbols:**

```
ffffffff81a602e0-ffffffff81a603de: get_desc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
bool get_desc(struct desc_struct *out, short unsigned int sel);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff81a1d3b0)
Location: arch/x86/lib/insn-eval.c:573
Inline: True
Direct callers:
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
  - arch/x86/lib/insn-eval.c:insn_get_code_seg_params
```
**Symbols:**

```
ffffffff81a1d3b0-ffffffff81a1d4ae: get_desc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
bool get_desc(struct desc_struct *out, short unsigned int sel);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff81acc6d0)
Location: arch/x86/lib/insn-eval.c:573
Inline: True
Direct callers:
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
  - arch/x86/lib/insn-eval.c:insn_get_code_seg_params
```
**Symbols:**

```
ffffffff81acc6d0-ffffffff81acc7ce: get_desc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
bool get_desc(struct desc_struct *out, short unsigned int sel);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff81ad8be0)
Location: arch/x86/lib/insn-eval.c:573
Inline: True
Direct callers:
  - arch/x86/lib/insn-eval.c:get_seg_base_limit
  - arch/x86/lib/insn-eval.c:insn_get_code_seg_params
```
**Symbols:**

```
ffffffff81ad8be0-ffffffff81ad8cde: get_desc (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct desc_struct *out</code>
</li>
<li>
<b>Param reordered. </b>
<code>sel</code> ➡️ <code>out, sel</code>
</li>
<li>
<b>Return type changed. </b>
<code>struct desc_struct *</code> ➡️ <code>bool</code>
</li>
</ul>
</details>
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
