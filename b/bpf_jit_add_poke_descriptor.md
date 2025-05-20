# Function: <code>bpf_jit_add_poke_descriptor</code>

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
int bpf_jit_add_poke_descriptor(struct bpf_prog *prog, struct bpf_jit_poke_descriptor *poke);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811fa430)
Location: kernel/bpf/core.c:766
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:fixup_bpf_calls
```
**Symbols:**

```
ffffffff811fa430-ffffffff811fa4fe: bpf_jit_add_poke_descriptor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int bpf_jit_add_poke_descriptor(struct bpf_prog *prog, struct bpf_jit_poke_descriptor *poke);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811f9490)
Location: kernel/bpf/core.c:762
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:fixup_bpf_calls
  - kernel/bpf/verifier.c:jit_subprogs
```
**Symbols:**

```
ffffffff811f9490-ffffffff811f95a8: bpf_jit_add_poke_descriptor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int bpf_jit_add_poke_descriptor(struct bpf_prog *prog, struct bpf_jit_poke_descriptor *poke);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811fa320)
Location: kernel/bpf/core.c:768
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_misc_fixups
```
**Symbols:**

```
ffffffff811fa320-ffffffff811fa450: bpf_jit_add_poke_descriptor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int bpf_jit_add_poke_descriptor(struct bpf_prog *prog, struct bpf_jit_poke_descriptor *poke);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/core.c (0)
Location: kernel/bpf/core.c:769
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_misc_fixups
```
**Symbols:**

```
ffffffff81cb7900-ffffffff81cb791d: bpf_jit_add_poke_descriptor.cold (STB_LOCAL)
ffffffff8122b9f0-ffffffff8122bb44: bpf_jit_add_poke_descriptor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int bpf_jit_add_poke_descriptor(struct bpf_prog *prog, struct bpf_jit_poke_descriptor *poke);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/core.c (0)
Location: kernel/bpf/core.c:772
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_misc_fixups
```
**Symbols:**

```
ffffffff81e68a3d-ffffffff81e68a5a: bpf_jit_add_poke_descriptor.cold (STB_LOCAL)
ffffffff8126d4f0-ffffffff8126d65c: bpf_jit_add_poke_descriptor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int bpf_jit_add_poke_descriptor(struct bpf_prog *prog, struct bpf_jit_poke_descriptor *poke);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/core.c (0)
Location: kernel/bpf/core.c:780
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_misc_fixups
```
**Symbols:**

```
ffffffff8205f6d7-ffffffff8205f6f4: bpf_jit_add_poke_descriptor.cold (STB_LOCAL)
ffffffff812c26b0-ffffffff812c281c: bpf_jit_add_poke_descriptor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int bpf_jit_add_poke_descriptor(struct bpf_prog *prog, struct bpf_jit_poke_descriptor *poke);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/core.c (0)
Location: kernel/bpf/core.c:781
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_misc_fixups
```
**Symbols:**

```
ffffffff820de5fe-ffffffff820de61b: bpf_jit_add_poke_descriptor.cold (STB_LOCAL)
ffffffff812e9570-ffffffff812e9704: bpf_jit_add_poke_descriptor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int bpf_jit_add_poke_descriptor(struct bpf_prog *prog, struct bpf_jit_poke_descriptor *poke);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/core.c (0)
Location: kernel/bpf/core.c:824
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_misc_fixups
```
**Symbols:**

```
ffffffff821ba498-ffffffff821ba4b5: bpf_jit_add_poke_descriptor.cold (STB_LOCAL)
ffffffff81307960-ffffffff81307af4: bpf_jit_add_poke_descriptor (STB_GLOBAL)
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
