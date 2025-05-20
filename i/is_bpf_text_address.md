# Function: <code>is_bpf_text_address</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool is_bpf_text_address(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff8118f3b0)
Location: kernel/bpf/core.c:451
Inline: False
Direct callers:
  - kernel/extable.c:kernel_text_address
  - kernel/extable.c:__kernel_text_address
```
**Symbols:**

```
ffffffff8118f3b0-ffffffff8118f3c6: is_bpf_text_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool is_bpf_text_address(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff8119d820)
Location: kernel/bpf/core.c:460
Inline: False
```
**Symbols:**

```
ffffffff8119d820-ffffffff8119d836: is_bpf_text_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool is_bpf_text_address(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811b1fc0)
Location: kernel/bpf/core.c:539
Inline: False
Direct callers:
  - kernel/extable.c:kernel_text_address
```
**Symbols:**

```
ffffffff811b1fc0-ffffffff811b1fd6: is_bpf_text_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool is_bpf_text_address(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811c0870)
Location: kernel/bpf/core.c:662
Inline: False
Direct callers:
  - kernel/extable.c:kernel_text_address
```
**Symbols:**

```
ffffffff811c0870-ffffffff811c0886: is_bpf_text_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool is_bpf_text_address(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811d13b0)
Location: kernel/bpf/core.c:704
Inline: False
Direct callers:
  - kernel/extable.c:kernel_text_address
```
**Symbols:**

```
ffffffff811d13b0-ffffffff811d13c6: is_bpf_text_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool is_bpf_text_address(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811dd930)
Location: kernel/bpf/core.c:704
Inline: False
Direct callers:
  - kernel/extable.c:kernel_text_address
```
**Symbols:**

```
ffffffff811dd930-ffffffff811dd946: is_bpf_text_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool is_bpf_text_address(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811fa300)
Location: kernel/bpf/core.c:700
Inline: False
Direct callers:
  - arch/x86/net/bpf_jit_comp.c:bpf_arch_text_poke
```
**Symbols:**

```
ffffffff811fa300-ffffffff811fa316: is_bpf_text_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool is_bpf_text_address(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811f9330)
Location: kernel/bpf/core.c:696
Inline: False
Direct callers:
  - arch/x86/net/bpf_jit_comp.c:bpf_arch_text_poke
```
**Symbols:**

```
ffffffff811f9330-ffffffff811f9353: is_bpf_text_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool is_bpf_text_address(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811fa1c0)
Location: kernel/bpf/core.c:702
Inline: False
Direct callers:
  - arch/x86/net/bpf_jit_comp.c:bpf_arch_text_poke
```
**Symbols:**

```
ffffffff811fa1c0-ffffffff811fa1e3: is_bpf_text_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool is_bpf_text_address(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff8122b890)
Location: kernel/bpf/core.c:703
Inline: False
Direct callers:
  - arch/x86/net/bpf_jit_comp.c:bpf_arch_text_poke
```
**Symbols:**

```
ffffffff8122b890-ffffffff8122b8b3: is_bpf_text_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool is_bpf_text_address(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff8126d350)
Location: kernel/bpf/core.c:706
Inline: False
Direct callers:
  - arch/x86/net/bpf_jit_comp.c:bpf_arch_text_poke
```
**Symbols:**

```
ffffffff8126d350-ffffffff8126d384: is_bpf_text_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool is_bpf_text_address(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff812c24e0)
Location: kernel/bpf/core.c:714
Inline: False
Direct callers:
  - arch/x86/net/bpf_jit_comp.c:bpf_arch_text_poke
```
**Symbols:**

```
ffffffff812c24e0-ffffffff812c2514: is_bpf_text_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool is_bpf_text_address(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff812e93a0)
Location: kernel/bpf/core.c:715
Inline: False
Direct callers:
  - arch/x86/net/bpf_jit_comp.c:bpf_arch_text_poke
```
**Symbols:**

```
ffffffff812e93a0-ffffffff812e93d4: is_bpf_text_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool is_bpf_text_address(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff81307720)
Location: kernel/bpf/core.c:758
Inline: False
Direct callers:
  - arch/x86/net/bpf_jit_comp.c:bpf_arch_text_poke
```
**Symbols:**

```
ffffffff81307720-ffffffff81307754: is_bpf_text_address (STB_GLOBAL)
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
bool is_bpf_text_address(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffff80001025e628)
Location: kernel/bpf/core.c:704
Inline: False
Direct callers:
  - kernel/extable.c:kernel_text_address
  - kernel/extable.c:kernel_text_address
```
**Symbols:**

```
ffff80001025e628-ffff80001025e65c: is_bpf_text_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool is_bpf_text_address(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (c0491d40)
Location: kernel/bpf/core.c:704
Inline: False
Direct callers:
  - kernel/extable.c:kernel_text_address
```
**Symbols:**

```
c0491d40-c0491d64: is_bpf_text_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool is_bpf_text_address(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (c000000000303420)
Location: kernel/bpf/core.c:704
Inline: False
Direct callers:
  - kernel/extable.c:kernel_text_address
```
**Symbols:**

```
c000000000303420-c000000000303458: is_bpf_text_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool is_bpf_text_address(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffe00019c9ca)
Location: kernel/bpf/core.c:704
Inline: False
Direct callers:
  - kernel/extable.c:kernel_text_address
  - kernel/extable.c:kernel_text_address
```
**Symbols:**

```
ffffffe00019c9ca-ffffffe00019c9f8: is_bpf_text_address (STB_GLOBAL)
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
bool is_bpf_text_address(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811d5f50)
Location: kernel/bpf/core.c:704
Inline: False
Direct callers:
  - kernel/extable.c:kernel_text_address
```
**Symbols:**

```
ffffffff811d5f50-ffffffff811d5f66: is_bpf_text_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool is_bpf_text_address(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811c8d10)
Location: kernel/bpf/core.c:704
Inline: False
Direct callers:
  - kernel/extable.c:kernel_text_address
```
**Symbols:**

```
ffffffff811c8d10-ffffffff811c8d26: is_bpf_text_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool is_bpf_text_address(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811d3d20)
Location: kernel/bpf/core.c:704
Inline: False
Direct callers:
  - kernel/extable.c:kernel_text_address
```
**Symbols:**

```
ffffffff811d3d20-ffffffff811d3d36: is_bpf_text_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool is_bpf_text_address(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811e2020)
Location: kernel/bpf/core.c:704
Inline: False
Direct callers:
  - kernel/extable.c:kernel_text_address
```
**Symbols:**

```
ffffffff811e2020-ffffffff811e204f: is_bpf_text_address (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
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
