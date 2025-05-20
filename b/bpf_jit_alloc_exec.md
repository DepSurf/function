# Function: <code>bpf_jit_alloc_exec</code>

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
void *bpf_jit_alloc_exec(long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811c0950)
Location: kernel/bpf/core.c:743
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_jit_binary_alloc
```
**Symbols:**

```
ffffffff811c0950-ffffffff811c0960: bpf_jit_alloc_exec (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void *bpf_jit_alloc_exec(long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811d1490)
Location: kernel/bpf/core.c:785
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_jit_binary_alloc
```
**Symbols:**

```
ffffffff811d1490-ffffffff811d14a0: bpf_jit_alloc_exec (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void *bpf_jit_alloc_exec(long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811dda10)
Location: kernel/bpf/core.c:785
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_jit_binary_alloc
```
**Symbols:**

```
ffffffff811dda10-ffffffff811dda20: bpf_jit_alloc_exec (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void *bpf_jit_alloc_exec(long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811fa510)
Location: kernel/bpf/core.c:841
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_jit_binary_alloc
  - kernel/bpf/trampoline.c:bpf_trampoline_lookup
```
**Symbols:**

```
ffffffff811fa510-ffffffff811fa520: bpf_jit_alloc_exec (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void *bpf_jit_alloc_exec(long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811f9630)
Location: kernel/bpf/core.c:838
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_jit_binary_alloc
  - kernel/bpf/trampoline.c:bpf_tramp_image_alloc
```
**Symbols:**

```
ffffffff811f9630-ffffffff811f9640: bpf_jit_alloc_exec (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void *bpf_jit_alloc_exec(long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811fa4d0)
Location: kernel/bpf/core.c:844
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_jit_binary_alloc
  - kernel/bpf/trampoline.c:bpf_trampoline_update
```
**Symbols:**

```
ffffffff811fa4d0-ffffffff811fa4e0: bpf_jit_alloc_exec (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void *bpf_jit_alloc_exec(long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff8122bbe0)
Location: kernel/bpf/core.c:846
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_jit_binary_alloc
  - kernel/bpf/trampoline.c:bpf_trampoline_update
```
**Symbols:**

```
ffffffff8122bbe0-ffffffff8122bbf0: bpf_jit_alloc_exec (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void *bpf_jit_alloc_exec(long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff8126d700)
Location: kernel/bpf/core.c:1023
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_jit_binary_alloc
  - kernel/bpf/trampoline.c:bpf_trampoline_update
  - net/bpf/bpf_dummy_struct_ops.c:bpf_struct_ops_test_run
```
**Symbols:**

```
ffffffff8126d700-ffffffff8126d716: bpf_jit_alloc_exec (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void *bpf_jit_alloc_exec(long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff812c2ae0)
Location: kernel/bpf/core.c:997
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_jit_binary_alloc
  - kernel/bpf/trampoline.c:bpf_trampoline_update
  - kernel/bpf/dispatcher.c:bpf_dispatcher_change_prog
  - net/bpf/bpf_dummy_struct_ops.c:bpf_struct_ops_test_run
```
**Symbols:**

```
ffffffff812c2ae0-ffffffff812c2af6: bpf_jit_alloc_exec (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void *bpf_jit_alloc_exec(long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff812e99d0)
Location: kernel/bpf/core.c:998
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_jit_binary_alloc
  - kernel/bpf/trampoline.c:bpf_trampoline_update
  - kernel/bpf/dispatcher.c:bpf_dispatcher_change_prog
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_alloc
  - net/bpf/bpf_dummy_struct_ops.c:bpf_struct_ops_test_run
```
**Symbols:**

```
ffffffff812e99d0-ffffffff812e99e6: bpf_jit_alloc_exec (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void *bpf_jit_alloc_exec(long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff81307c20)
Location: kernel/bpf/core.c:1041
Inline: False
Direct callers:
  - arch/x86/net/bpf_jit_comp.c:arch_bpf_trampoline_size
  - kernel/bpf/core.c:bpf_jit_binary_alloc
  - kernel/bpf/core.c:bpf_prog_pack_alloc
  - kernel/bpf/core.c:alloc_new_pack
  - kernel/bpf/trampoline.c:arch_alloc_bpf_trampoline
  - kernel/bpf/dispatcher.c:bpf_dispatcher_change_prog
```
**Symbols:**

```
ffffffff81307c20-ffffffff81307c36: bpf_jit_alloc_exec (STB_WEAK)
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
void *bpf_jit_alloc_exec(long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm64/net/bpf_jit_comp.c (ffff8000100b4e60)
Location: arch/arm64/net/bpf_jit_comp.c:967
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_jit_binary_alloc
```
**Symbols:**

```
ffff8000100b4e60-ffff8000100b4f54: bpf_jit_alloc_exec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void *bpf_jit_alloc_exec(long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (c0491e3c)
Location: kernel/bpf/core.c:785
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_jit_binary_alloc
```
**Symbols:**

```
c0491e3c-c0491e58: bpf_jit_alloc_exec (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void *bpf_jit_alloc_exec(long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (c0000000003035c0)
Location: kernel/bpf/core.c:785
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_jit_binary_alloc
```
**Symbols:**

```
c0000000003035c0-c0000000003035f4: bpf_jit_alloc_exec (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void *bpf_jit_alloc_exec(long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffe00019cada)
Location: kernel/bpf/core.c:785
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_jit_binary_alloc
```
**Symbols:**

```
ffffffe00019cada-ffffffe00019cb04: bpf_jit_alloc_exec (STB_WEAK)
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
void *bpf_jit_alloc_exec(long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811d6030)
Location: kernel/bpf/core.c:785
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_jit_binary_alloc
```
**Symbols:**

```
ffffffff811d6030-ffffffff811d6040: bpf_jit_alloc_exec (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void *bpf_jit_alloc_exec(long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811c8df0)
Location: kernel/bpf/core.c:785
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_jit_binary_alloc
```
**Symbols:**

```
ffffffff811c8df0-ffffffff811c8e00: bpf_jit_alloc_exec (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void *bpf_jit_alloc_exec(long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811d3e00)
Location: kernel/bpf/core.c:785
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_jit_binary_alloc
```
**Symbols:**

```
ffffffff811d3e00-ffffffff811d3e10: bpf_jit_alloc_exec (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void *bpf_jit_alloc_exec(long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811e2120)
Location: kernel/bpf/core.c:785
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_jit_binary_alloc
```
**Symbols:**

```
ffffffff811e2120-ffffffff811e2130: bpf_jit_alloc_exec (STB_WEAK)
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
