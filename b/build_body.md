# Function: <code>build_body</code>

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
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int build_body(struct jit_ctx *ctx, bool extra_pass);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm64/net/bpf_jit_comp.c (ffff8000100b4948)
Location: arch/arm64/net/bpf_jit_comp.c:778
Inline: False
Direct callers:
  - arch/arm64/net/bpf_jit_comp.c:bpf_int_jit_compile
  - arch/arm64/net/bpf_jit_comp.c:bpf_int_jit_compile
```
**Symbols:**

```
ffff8000100b4948-ffff8000100b4a00: build_body (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int build_body(struct jit_ctx *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm/net/bpf_jit_32.c (c032c3e0)
Location: arch/arm/net/bpf_jit_32.c:1807
Inline: False
Direct callers:
  - arch/arm/net/bpf_jit_32.c:bpf_int_jit_compile
  - arch/arm/net/bpf_jit_32.c:bpf_int_jit_compile
```
**Symbols:**

```
c032c3e0-c032c484: build_body (STB_LOCAL)
```
</details>
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int build_body(struct rv_jit_context *ctx, bool extra_pass);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/riscv/net/bpf_jit_comp.c (ffffffe0000bdcb6)
Location: arch/riscv/net/bpf_jit_comp.c:1517
Inline: False
Direct callers:
  - arch/riscv/net/bpf_jit_comp.c:bpf_int_jit_compile
  - arch/riscv/net/bpf_jit_comp.c:bpf_int_jit_compile
```
**Symbols:**

```
ffffffe0000bdcb6-ffffffe0000bdd44: build_body (STB_LOCAL)
```
</details>
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
<b>Arch</b>
<ul>
</ul>
