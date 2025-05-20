# Function: <code>bpf_jit_supports_kfunc_call</code>

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
bool bpf_jit_supports_kfunc_call();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (ffffffff8109fa00)
Location: arch/x86/net/bpf_jit_comp.c:2369
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:add_kfunc_call
```
**Symbols:**

```
ffffffff8109fa00-ffffffff8109fa10: bpf_jit_supports_kfunc_call (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool bpf_jit_supports_kfunc_call();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (ffffffff810b0e50)
Location: arch/x86/net/bpf_jit_comp.c:2435
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:add_kfunc_call
```
**Symbols:**

```
ffffffff810b0e50-ffffffff810b0e60: bpf_jit_supports_kfunc_call (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool bpf_jit_supports_kfunc_call();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (0)
Location: arch/x86/net/bpf_jit_comp.c:2498
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:add_kfunc_call
```
**Symbols:**

```
ffffffff810c6e30-ffffffff810c6e44: bpf_jit_supports_kfunc_call (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool bpf_jit_supports_kfunc_call();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (0)
Location: arch/x86/net/bpf_jit_comp.c:2618
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:add_kfunc_call
```
**Symbols:**

```
ffffffff810e3e50-ffffffff810e3e64: bpf_jit_supports_kfunc_call (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool bpf_jit_supports_kfunc_call();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (0)
Location: arch/x86/net/bpf_jit_comp.c:2621
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:add_kfunc_call
```
**Symbols:**

```
ffffffff810ef4a0-ffffffff810ef4b4: bpf_jit_supports_kfunc_call (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool bpf_jit_supports_kfunc_call();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (0)
Location: arch/x86/net/bpf_jit_comp.c:3130
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:add_kfunc_call
```
**Symbols:**

```
ffffffff810f8780-ffffffff810f8794: bpf_jit_supports_kfunc_call (STB_GLOBAL)
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
