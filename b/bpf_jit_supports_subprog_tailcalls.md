# Function: <code>bpf_jit_supports_subprog_tailcalls</code>

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
bool bpf_jit_supports_subprog_tailcalls();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (ffffffff810c6e80)
Location: arch/x86/net/bpf_jit_comp.c:2511
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_misc_fixups
  - kernel/bpf/verifier.c:check_map_func_compatibility
```
**Symbols:**

```
ffffffff810c6e80-ffffffff810c6e94: bpf_jit_supports_subprog_tailcalls (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool bpf_jit_supports_subprog_tailcalls();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (ffffffff810e3ec0)
Location: arch/x86/net/bpf_jit_comp.c:2631
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_misc_fixups
  - kernel/bpf/verifier.c:check_map_func_compatibility
```
**Symbols:**

```
ffffffff810e3ec0-ffffffff810e3ed4: bpf_jit_supports_subprog_tailcalls (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool bpf_jit_supports_subprog_tailcalls();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (ffffffff810ef510)
Location: arch/x86/net/bpf_jit_comp.c:2634
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_misc_fixups
  - kernel/bpf/verifier.c:check_map_func_compatibility
```
**Symbols:**

```
ffffffff810ef510-ffffffff810ef524: bpf_jit_supports_subprog_tailcalls (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool bpf_jit_supports_subprog_tailcalls();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (ffffffff810f87f0)
Location: arch/x86/net/bpf_jit_comp.c:3143
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_misc_fixups
  - kernel/bpf/verifier.c:check_map_func_compatibility
```
**Symbols:**

```
ffffffff810f87f0-ffffffff810f8804: bpf_jit_supports_subprog_tailcalls (STB_GLOBAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
