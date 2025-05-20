# Function: <code>bpf_jit_uncharge_modmem</code>

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
In kernel/bpf/core.c (ffffffff811c0a71)
Location: kernel/bpf/core.c:738
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_binary_free
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
In kernel/bpf/core.c (ffffffff811d15b1)
Location: kernel/bpf/core.c:780
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_binary_free
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
In kernel/bpf/core.c (ffffffff811ddb31)
Location: kernel/bpf/core.c:780
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_binary_free
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
In kernel/bpf/core.c (ffffffff811fa6d4)
Location: kernel/bpf/core.c:836
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_free
  - kernel/bpf/core.c:bpf_jit_binary_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void bpf_jit_uncharge_modmem(u32 pages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811f97b4)
Location: kernel/bpf/core.c:833
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_free
  - kernel/bpf/core.c:bpf_jit_binary_alloc
Direct callers:
  - kernel/bpf/trampoline.c:bpf_tramp_image_alloc
  - kernel/bpf/trampoline.c:__bpf_tramp_image_put_deferred
```
**Symbols:**

```
ffffffff811f9610-ffffffff811f9625: bpf_jit_uncharge_modmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void bpf_jit_uncharge_modmem(u32 pages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811fa657)
Location: kernel/bpf/core.c:839
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_free
  - kernel/bpf/core.c:bpf_jit_binary_alloc
Direct callers:
  - kernel/bpf/trampoline.c:bpf_trampoline_update
  - kernel/bpf/trampoline.c:bpf_trampoline_update
  - kernel/bpf/trampoline.c:__bpf_tramp_image_put_deferred
```
**Symbols:**

```
ffffffff811fa4b0-ffffffff811fa4c5: bpf_jit_uncharge_modmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void bpf_jit_uncharge_modmem(u32 pages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff8122bd67)
Location: kernel/bpf/core.c:841
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_free
  - kernel/bpf/core.c:bpf_jit_binary_alloc
Direct callers:
  - kernel/bpf/trampoline.c:bpf_trampoline_update
  - kernel/bpf/trampoline.c:bpf_trampoline_update
  - kernel/bpf/trampoline.c:__bpf_tramp_image_put_deferred
```
**Symbols:**

```
ffffffff8122bbc0-ffffffff8122bbd5: bpf_jit_uncharge_modmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void bpf_jit_uncharge_modmem(u32 size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff8126d8e1)
Location: kernel/bpf/core.c:1018
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_free
  - kernel/bpf/core.c:bpf_jit_binary_pack_free
  - kernel/bpf/core.c:bpf_jit_binary_pack_alloc
  - kernel/bpf/core.c:bpf_jit_binary_pack_alloc
  - kernel/bpf/core.c:bpf_jit_binary_alloc
Direct callers:
  - kernel/bpf/trampoline.c:bpf_trampoline_update
  - kernel/bpf/trampoline.c:bpf_trampoline_update
```
**Symbols:**

```
ffffffff8126d6e0-ffffffff8126d6fb: bpf_jit_uncharge_modmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void bpf_jit_uncharge_modmem(u32 size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff812c2d01)
Location: kernel/bpf/core.c:992
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_free
  - kernel/bpf/core.c:bpf_jit_binary_pack_free
  - kernel/bpf/core.c:bpf_jit_binary_pack_alloc
  - kernel/bpf/core.c:bpf_jit_binary_pack_alloc
  - kernel/bpf/core.c:bpf_jit_binary_alloc
Direct callers:
  - kernel/bpf/trampoline.c:bpf_trampoline_update
  - kernel/bpf/trampoline.c:bpf_trampoline_update
```
**Symbols:**

```
ffffffff812c2ab0-ffffffff812c2acb: bpf_jit_uncharge_modmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void bpf_jit_uncharge_modmem(u32 size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff812e9bf1)
Location: kernel/bpf/core.c:993
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_free
  - kernel/bpf/core.c:bpf_jit_binary_pack_free
  - kernel/bpf/core.c:bpf_jit_binary_pack_alloc
  - kernel/bpf/core.c:bpf_jit_binary_pack_alloc
  - kernel/bpf/core.c:bpf_jit_binary_alloc
Direct callers:
  - kernel/bpf/trampoline.c:bpf_trampoline_update
  - kernel/bpf/trampoline.c:bpf_trampoline_update
  - kernel/bpf/trampoline.c:bpf_trampoline_update
  - kernel/bpf/trampoline.c:__bpf_tramp_image_put_deferred
```
**Symbols:**

```
ffffffff812e99a0-ffffffff812e99bb: bpf_jit_uncharge_modmem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void bpf_jit_uncharge_modmem(u32 size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff81308141)
Location: kernel/bpf/core.c:1036
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_free
  - kernel/bpf/core.c:bpf_jit_binary_pack_free
  - kernel/bpf/core.c:bpf_jit_binary_pack_alloc
  - kernel/bpf/core.c:bpf_jit_binary_pack_alloc
  - kernel/bpf/core.c:bpf_jit_binary_alloc
Direct callers:
  - kernel/bpf/trampoline.c:bpf_trampoline_update
  - kernel/bpf/trampoline.c:bpf_trampoline_update
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_alloc
  - kernel/bpf/bpf_struct_ops.c:__bpf_struct_ops_map_free
```
**Symbols:**

```
ffffffff81307bf0-ffffffff81307c0b: bpf_jit_uncharge_modmem (STB_GLOBAL)
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
In kernel/bpf/core.c (ffff80001025e9e4)
Location: kernel/bpf/core.c:780
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_free
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
In kernel/bpf/core.c (c0491fb8)
Location: kernel/bpf/core.c:780
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_binary_free
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
In kernel/bpf/core.c (c0000000003038c0)
Location: kernel/bpf/core.c:780
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_free
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
In kernel/bpf/core.c (ffffffe00019ccb2)
Location: kernel/bpf/core.c:780
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_free
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
In kernel/bpf/core.c (ffffffff811d6151)
Location: kernel/bpf/core.c:780
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_binary_free
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
In kernel/bpf/core.c (ffffffff811c8f11)
Location: kernel/bpf/core.c:780
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_binary_free
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
In kernel/bpf/core.c (ffffffff811d3f21)
Location: kernel/bpf/core.c:780
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_binary_free
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
In kernel/bpf/core.c (ffffffff811e2241)
Location: kernel/bpf/core.c:780
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_binary_free
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
