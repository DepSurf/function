# Function: <code>__bpf_arch_text_poke</code>

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
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int __bpf_arch_text_poke(void *ip, enum bpf_text_poke_type t, void *old_addr, void *new_addr, const bool text_live);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (0)
Location: arch/x86/net/bpf_jit_comp.c:283
Inline: False
Direct callers:
  - arch/x86/net/bpf_jit_comp.c:bpf_tail_call_direct_fixup
  - arch/x86/net/bpf_jit_comp.c:bpf_arch_text_poke
```
**Symbols:**

```
ffffffff810a21f0-ffffffff810a237e: __bpf_arch_text_poke (STB_LOCAL)
ffffffff810a3261-ffffffff810a3295: __bpf_arch_text_poke.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int __bpf_arch_text_poke(void *ip, enum bpf_text_poke_type t, void *old_addr, void *new_addr, const bool text_live);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (0)
Location: arch/x86/net/bpf_jit_comp.c:317
Inline: False
Direct callers:
  - arch/x86/net/bpf_jit_comp.c:bpf_tail_call_direct_fixup
  - arch/x86/net/bpf_jit_comp.c:bpf_tail_call_direct_fixup
  - arch/x86/net/bpf_jit_comp.c:bpf_arch_text_poke
```
**Symbols:**

```
ffffffff8109bde0-ffffffff8109bf78: __bpf_arch_text_poke (STB_LOCAL)
ffffffff81bdae7f-ffffffff81bdaeb3: __bpf_arch_text_poke.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int __bpf_arch_text_poke(void *ip, enum bpf_text_poke_type t, void *old_addr, void *new_addr, const bool text_live);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (0)
Location: arch/x86/net/bpf_jit_comp.c:329
Inline: False
Direct callers:
  - arch/x86/net/bpf_jit_comp.c:bpf_tail_call_direct_fixup
  - arch/x86/net/bpf_jit_comp.c:bpf_tail_call_direct_fixup
  - arch/x86/net/bpf_jit_comp.c:bpf_arch_text_poke
```
**Symbols:**

```
ffffffff8109c420-ffffffff8109c5ba: __bpf_arch_text_poke (STB_LOCAL)
ffffffff81bcced0-ffffffff81bccf01: __bpf_arch_text_poke.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int __bpf_arch_text_poke(void *ip, enum bpf_text_poke_type t, void *old_addr, void *new_addr, const bool text_live);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (0)
Location: arch/x86/net/bpf_jit_comp.c:325
Inline: False
Direct callers:
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
  - arch/x86/net/bpf_jit_comp.c:bpf_arch_text_poke
```
**Symbols:**

```
ffffffff810abf00-ffffffff810ac09a: __bpf_arch_text_poke (STB_LOCAL)
ffffffff81ca34b1-ffffffff81ca34e2: __bpf_arch_text_poke.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int __bpf_arch_text_poke(void *ip, enum bpf_text_poke_type t, void *old_addr, void *new_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (0)
Location: arch/x86/net/bpf_jit_comp.c:348
Inline: False
Direct callers:
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
  - arch/x86/net/bpf_jit_comp.c:bpf_arch_text_poke
```
**Symbols:**

```
ffffffff810c1ac0-ffffffff810c1c5b: __bpf_arch_text_poke (STB_LOCAL)
ffffffff81e52c57-ffffffff81e52c7f: __bpf_arch_text_poke.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __bpf_arch_text_poke(void *ip, enum bpf_text_poke_type t, void *old_addr, void *new_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (ffffffff810de5d0)
Location: arch/x86/net/bpf_jit_comp.c:356
Inline: False
Direct callers:
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
  - arch/x86/net/bpf_jit_comp.c:bpf_arch_text_poke
```
**Symbols:**

```
ffffffff810de5d0-ffffffff810de793: __bpf_arch_text_poke (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __bpf_arch_text_poke(void *ip, enum bpf_text_poke_type t, void *old_addr, void *new_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (ffffffff810e9bd0)
Location: arch/x86/net/bpf_jit_comp.c:356
Inline: False
Direct callers:
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
  - arch/x86/net/bpf_jit_comp.c:bpf_arch_text_poke
```
**Symbols:**

```
ffffffff810e9bd0-ffffffff810e9d95: __bpf_arch_text_poke (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __bpf_arch_text_poke(void *ip, enum bpf_text_poke_type t, void *old_addr, void *new_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (ffffffff810f2280)
Location: arch/x86/net/bpf_jit_comp.c:478
Inline: False
Direct callers:
  - arch/x86/net/bpf_jit_comp.c:bpf_arch_poke_desc_update
  - arch/x86/net/bpf_jit_comp.c:bpf_arch_poke_desc_update
  - arch/x86/net/bpf_jit_comp.c:bpf_arch_poke_desc_update
  - arch/x86/net/bpf_jit_comp.c:bpf_arch_poke_desc_update
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
  - arch/x86/net/bpf_jit_comp.c:bpf_arch_text_poke
```
**Symbols:**

```
ffffffff810f2280-ffffffff810f2445: __bpf_arch_text_poke (STB_LOCAL)
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
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
<b>Param removed. </b>
<code>const bool text_live</code>
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
