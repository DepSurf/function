# Function: <code>bpf_jit_free_exec</code>

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
<summary>In <code>5.0</code>: ✅</summary>

```c
void bpf_jit_free_exec(void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811c0960)
Location: kernel/bpf/core.c:748
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_jit_binary_free
```
**Symbols:**

```
ffffffff811c0960-ffffffff811c0970: bpf_jit_free_exec (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void bpf_jit_free_exec(void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811d14a0)
Location: kernel/bpf/core.c:790
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_jit_binary_free
```
**Symbols:**

```
ffffffff811d14a0-ffffffff811d14b0: bpf_jit_free_exec (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void bpf_jit_free_exec(void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811dda20)
Location: kernel/bpf/core.c:790
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_jit_binary_free
```
**Symbols:**

```
ffffffff811dda20-ffffffff811dda30: bpf_jit_free_exec (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void bpf_jit_free_exec(void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811fa520)
Location: kernel/bpf/core.c:846
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_jit_free
  - kernel/bpf/trampoline.c:bpf_trampoline_put
```
**Symbols:**

```
ffffffff811fa520-ffffffff811fa530: bpf_jit_free_exec (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void bpf_jit_free_exec(void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811f9640)
Location: kernel/bpf/core.c:843
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_jit_free
  - kernel/bpf/trampoline.c:bpf_tramp_image_alloc
  - kernel/bpf/trampoline.c:__bpf_tramp_image_put_deferred
```
**Symbols:**

```
ffffffff811f9640-ffffffff811f9650: bpf_jit_free_exec (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void bpf_jit_free_exec(void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811fa4e0)
Location: kernel/bpf/core.c:849
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_jit_free
  - kernel/bpf/trampoline.c:bpf_trampoline_update
  - kernel/bpf/trampoline.c:__bpf_tramp_image_put_deferred
```
**Symbols:**

```
ffffffff811fa4e0-ffffffff811fa4f0: bpf_jit_free_exec (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void bpf_jit_free_exec(void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff8122bbf0)
Location: kernel/bpf/core.c:851
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_jit_free
  - kernel/bpf/trampoline.c:bpf_trampoline_update
  - kernel/bpf/trampoline.c:__bpf_tramp_image_put_deferred
```
**Symbols:**

```
ffffffff8122bbf0-ffffffff8122bc00: bpf_jit_free_exec (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void bpf_jit_free_exec(void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff8126d720)
Location: kernel/bpf/core.c:1028
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_jit_free
  - kernel/bpf/trampoline.c:bpf_trampoline_update
  - net/bpf/bpf_dummy_struct_ops.c:bpf_struct_ops_test_run
  - net/bpf/bpf_dummy_struct_ops.c:bpf_struct_ops_test_run
  - net/bpf/bpf_dummy_struct_ops.c:bpf_struct_ops_test_run
  - net/bpf/bpf_dummy_struct_ops.c:bpf_struct_ops_test_run
  - net/bpf/bpf_dummy_struct_ops.c:bpf_struct_ops_test_run
  - net/bpf/bpf_dummy_struct_ops.c:bpf_struct_ops_test_run
```
**Symbols:**

```
ffffffff8126d720-ffffffff8126d736: bpf_jit_free_exec (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void bpf_jit_free_exec(void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff812c2b10)
Location: kernel/bpf/core.c:1002
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_jit_free
  - kernel/bpf/trampoline.c:bpf_trampoline_update
  - net/bpf/bpf_dummy_struct_ops.c:bpf_struct_ops_test_run
  - net/bpf/bpf_dummy_struct_ops.c:bpf_struct_ops_test_run
  - net/bpf/bpf_dummy_struct_ops.c:bpf_struct_ops_test_run
  - net/bpf/bpf_dummy_struct_ops.c:bpf_struct_ops_test_run
  - net/bpf/bpf_dummy_struct_ops.c:bpf_struct_ops_test_run
  - net/bpf/bpf_dummy_struct_ops.c:bpf_struct_ops_test_run
```
**Symbols:**

```
ffffffff812c2b10-ffffffff812c2b26: bpf_jit_free_exec (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void bpf_jit_free_exec(void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff812e9a00)
Location: kernel/bpf/core.c:1003
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_jit_free
  - kernel/bpf/trampoline.c:bpf_trampoline_update
  - kernel/bpf/trampoline.c:bpf_trampoline_update
  - kernel/bpf/trampoline.c:__bpf_tramp_image_put_deferred
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_alloc
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_free
  - net/bpf/bpf_dummy_struct_ops.c:bpf_struct_ops_test_run
  - net/bpf/bpf_dummy_struct_ops.c:bpf_struct_ops_test_run
  - net/bpf/bpf_dummy_struct_ops.c:bpf_struct_ops_test_run
  - net/bpf/bpf_dummy_struct_ops.c:bpf_struct_ops_test_run
  - net/bpf/bpf_dummy_struct_ops.c:bpf_struct_ops_test_run
  - net/bpf/bpf_dummy_struct_ops.c:bpf_struct_ops_test_run
```
**Symbols:**

```
ffffffff812e9a00-ffffffff812e9a16: bpf_jit_free_exec (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void bpf_jit_free_exec(void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff81307f50)
Location: kernel/bpf/core.c:1046
Inline: False
Direct callers:
  - arch/x86/net/bpf_jit_comp.c:arch_bpf_trampoline_size
  - kernel/bpf/core.c:bpf_jit_free
  - kernel/bpf/core.c:bpf_prog_pack_free
  - kernel/bpf/core.c:bpf_prog_pack_free
  - kernel/bpf/trampoline.c:arch_free_bpf_trampoline
  - kernel/bpf/trampoline.c:arch_free_bpf_trampoline
```
**Symbols:**

```
ffffffff81307f50-ffffffff81307f66: bpf_jit_free_exec (STB_WEAK)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void bpf_jit_free_exec(void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm64/net/bpf_jit_comp.c (ffff8000100b4f58)
Location: arch/arm64/net/bpf_jit_comp.c:975
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_jit_free
```
**Symbols:**

```
ffff8000100b4f58-ffff8000100b4f84: bpf_jit_free_exec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void bpf_jit_free_exec(void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (c0491e58)
Location: kernel/bpf/core.c:790
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_jit_binary_free
```
**Symbols:**

```
c0491e58-c0491e74: bpf_jit_free_exec (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void bpf_jit_free_exec(void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (c000000000303600)
Location: kernel/bpf/core.c:790
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_jit_free
```
**Symbols:**

```
c000000000303600-c000000000303634: bpf_jit_free_exec (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void bpf_jit_free_exec(void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffe00019cb04)
Location: kernel/bpf/core.c:790
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_jit_free
```
**Symbols:**

```
ffffffe00019cb04-ffffffe00019cb2e: bpf_jit_free_exec (STB_WEAK)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void bpf_jit_free_exec(void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811d6040)
Location: kernel/bpf/core.c:790
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_jit_binary_free
```
**Symbols:**

```
ffffffff811d6040-ffffffff811d6050: bpf_jit_free_exec (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void bpf_jit_free_exec(void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811c8e00)
Location: kernel/bpf/core.c:790
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_jit_binary_free
```
**Symbols:**

```
ffffffff811c8e00-ffffffff811c8e10: bpf_jit_free_exec (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void bpf_jit_free_exec(void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811d3e10)
Location: kernel/bpf/core.c:790
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_jit_binary_free
```
**Symbols:**

```
ffffffff811d3e10-ffffffff811d3e20: bpf_jit_free_exec (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void bpf_jit_free_exec(void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811e2130)
Location: kernel/bpf/core.c:790
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_jit_binary_free
```
**Symbols:**

```
ffffffff811e2130-ffffffff811e2140: bpf_jit_free_exec (STB_WEAK)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
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
