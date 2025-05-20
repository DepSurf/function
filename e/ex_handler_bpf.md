# Function: <code>ex_handler_bpf</code>

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
<summary>In <code>5.8</code>: ✅</summary>

```c
bool ex_handler_bpf(const struct exception_table_entry *x, struct pt_regs *regs, int trapnr, long unsigned int error_code, long unsigned int fault_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (ffffffff810a00f0)
Location: arch/x86/net/bpf_jit_comp.c:643
Inline: False
```
**Symbols:**

```
ffffffff810a00f0-ffffffff810a0119: ex_handler_bpf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool ex_handler_bpf(const struct exception_table_entry *x, struct pt_regs *regs, int trapnr, long unsigned int error_code, long unsigned int fault_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (ffffffff8109b600)
Location: arch/x86/net/bpf_jit_comp.c:761
Inline: False
```
**Symbols:**

```
ffffffff8109b600-ffffffff8109b629: ex_handler_bpf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool ex_handler_bpf(const struct exception_table_entry *x, struct pt_regs *regs, int trapnr, long unsigned int error_code, long unsigned int fault_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (ffffffff8109bb20)
Location: arch/x86/net/bpf_jit_comp.c:844
Inline: False
```
**Symbols:**

```
ffffffff8109bb20-ffffffff8109bb49: ex_handler_bpf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool ex_handler_bpf(const struct exception_table_entry *x, struct pt_regs *regs, int trapnr, long unsigned int error_code, long unsigned int fault_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (ffffffff810abc20)
Location: arch/x86/net/bpf_jit_comp.c:844
Inline: False
```
**Symbols:**

```
ffffffff810abc20-ffffffff810abc49: ex_handler_bpf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool ex_handler_bpf(const struct exception_table_entry *x, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (ffffffff810c5e90)
Location: arch/x86/net/bpf_jit_comp.c:844
Inline: False
Direct callers:
  - arch/x86/mm/extable.c:fixup_exception
```
**Symbols:**

```
ffffffff810c5e90-ffffffff810c5ec1: ex_handler_bpf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool ex_handler_bpf(const struct exception_table_entry *x, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (ffffffff810e2c60)
Location: arch/x86/net/bpf_jit_comp.c:857
Inline: False
Direct callers:
  - arch/x86/mm/extable.c:fixup_exception
```
**Symbols:**

```
ffffffff810e2c60-ffffffff810e2c91: ex_handler_bpf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool ex_handler_bpf(const struct exception_table_entry *x, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (ffffffff810ee330)
Location: arch/x86/net/bpf_jit_comp.c:857
Inline: False
Direct callers:
  - arch/x86/mm/extable.c:fixup_exception
```
**Symbols:**

```
ffffffff810ee330-ffffffff810ee361: ex_handler_bpf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool ex_handler_bpf(const struct exception_table_entry *x, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (ffffffff810f7df0)
Location: arch/x86/net/bpf_jit_comp.c:1046
Inline: False
Direct callers:
  - arch/x86/mm/extable.c:fixup_exception
```
**Symbols:**

```
ffffffff810f7df0-ffffffff810f7e21: ex_handler_bpf (STB_GLOBAL)
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
<code>int trapnr</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int error_code</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int fault_addr</code>
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
