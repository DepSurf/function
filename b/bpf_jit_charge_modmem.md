# Function: <code>bpf_jit_charge_modmem</code>

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
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811c09a3)
Location: kernel/bpf/core.c:725
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_binary_alloc
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
In kernel/bpf/core.c (ffffffff811d14eb)
Location: kernel/bpf/core.c:767
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_binary_alloc
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
In kernel/bpf/core.c (ffffffff811dda6b)
Location: kernel/bpf/core.c:767
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_binary_alloc
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
In kernel/bpf/core.c (ffffffff811fa57f)
Location: kernel/bpf/core.c:823
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_binary_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int bpf_jit_charge_modmem(u32 pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811f95c0)
Location: kernel/bpf/core.c:820
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_jit_binary_alloc
  - kernel/bpf/trampoline.c:bpf_tramp_image_alloc
```
**Symbols:**

```
ffffffff811f95c0-ffffffff811f9610: bpf_jit_charge_modmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int bpf_jit_charge_modmem(u32 pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811fa460)
Location: kernel/bpf/core.c:826
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_jit_binary_alloc
  - kernel/bpf/trampoline.c:bpf_trampoline_update
```
**Symbols:**

```
ffffffff811fa460-ffffffff811fa4b0: bpf_jit_charge_modmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int bpf_jit_charge_modmem(u32 pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff8122bb60)
Location: kernel/bpf/core.c:828
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_jit_binary_alloc
  - kernel/bpf/trampoline.c:bpf_trampoline_update
```
**Symbols:**

```
ffffffff8122bb60-ffffffff8122bbbe: bpf_jit_charge_modmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int bpf_jit_charge_modmem(u32 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff8126d680)
Location: kernel/bpf/core.c:1006
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_jit_binary_pack_alloc
  - kernel/bpf/core.c:bpf_jit_binary_alloc
  - kernel/bpf/trampoline.c:bpf_trampoline_update
```
**Symbols:**

```
ffffffff8126d680-ffffffff8126d6dd: bpf_jit_charge_modmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int bpf_jit_charge_modmem(u32 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff812c2a30)
Location: kernel/bpf/core.c:980
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_jit_binary_pack_alloc
  - kernel/bpf/core.c:bpf_jit_binary_alloc
  - kernel/bpf/trampoline.c:bpf_trampoline_update
```
**Symbols:**

```
ffffffff812c2a30-ffffffff812c2a92: bpf_jit_charge_modmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int bpf_jit_charge_modmem(u32 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff812e9920)
Location: kernel/bpf/core.c:981
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_jit_binary_pack_alloc
  - kernel/bpf/core.c:bpf_jit_binary_alloc
  - kernel/bpf/trampoline.c:bpf_trampoline_update
```
**Symbols:**

```
ffffffff812e9920-ffffffff812e9982: bpf_jit_charge_modmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int bpf_jit_charge_modmem(u32 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff81307b70)
Location: kernel/bpf/core.c:1024
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_jit_binary_pack_alloc
  - kernel/bpf/core.c:bpf_jit_binary_alloc
  - kernel/bpf/trampoline.c:bpf_trampoline_update
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_alloc
```
**Symbols:**

```
ffffffff81307b70-ffffffff81307bd2: bpf_jit_charge_modmem (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffff80001025e80c)
Location: kernel/bpf/core.c:767
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_binary_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (c0491eb0)
Location: kernel/bpf/core.c:767
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_binary_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (c0000000003036ac)
Location: kernel/bpf/core.c:767
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_binary_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffe00019cb70)
Location: kernel/bpf/core.c:767
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_binary_alloc
```
</details>
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
In kernel/bpf/core.c (ffffffff811d608b)
Location: kernel/bpf/core.c:767
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_binary_alloc
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
In kernel/bpf/core.c (ffffffff811c8e4b)
Location: kernel/bpf/core.c:767
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_binary_alloc
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
In kernel/bpf/core.c (ffffffff811d3e5b)
Location: kernel/bpf/core.c:767
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_binary_alloc
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
In kernel/bpf/core.c (ffffffff811e217b)
Location: kernel/bpf/core.c:767
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_binary_alloc
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>u32 size</code>
</li>
<li>
<b>Param removed. </b>
<code>u32 pages</code>
</li>
</ul>
</details>
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
