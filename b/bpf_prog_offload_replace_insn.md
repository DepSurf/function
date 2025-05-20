# Function: <code>bpf_prog_offload_replace_insn</code>

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
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void bpf_prog_offload_replace_insn(struct bpf_verifier_env *env, u32 off, struct bpf_insn *insn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffffffff811f5750)
Location: kernel/bpf/offload.c:178
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:bpf_check
```
**Symbols:**

```
ffffffff811f5750-ffffffff811f57d4: bpf_prog_offload_replace_insn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void bpf_prog_offload_replace_insn(struct bpf_verifier_env *env, u32 off, struct bpf_insn *insn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffffffff81202750)
Location: kernel/bpf/offload.c:178
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:bpf_check
```
**Symbols:**

```
ffffffff81202750-ffffffff812027d4: bpf_prog_offload_replace_insn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void bpf_prog_offload_replace_insn(struct bpf_verifier_env *env, u32 off, struct bpf_insn *insn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffffffff81229d00)
Location: kernel/bpf/offload.c:178
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:opt_hard_wire_dead_code_branches
```
**Symbols:**

```
ffffffff81229d00-ffffffff81229d86: bpf_prog_offload_replace_insn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void bpf_prog_offload_replace_insn(struct bpf_verifier_env *env, u32 off, struct bpf_insn *insn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffffffff81231890)
Location: kernel/bpf/offload.c:178
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:opt_hard_wire_dead_code_branches
```
**Symbols:**

```
ffffffff81231890-ffffffff81231916: bpf_prog_offload_replace_insn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void bpf_prog_offload_replace_insn(struct bpf_verifier_env *env, u32 off, struct bpf_insn *insn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffffffff81235a10)
Location: kernel/bpf/offload.c:178
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:bpf_check
```
**Symbols:**

```
ffffffff81235a10-ffffffff81235a94: bpf_prog_offload_replace_insn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void bpf_prog_offload_replace_insn(struct bpf_verifier_env *env, u32 off, struct bpf_insn *insn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/offload.c (0)
Location: kernel/bpf/offload.c:178
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:bpf_check
```
**Symbols:**

```
ffffffff81cb96a4-ffffffff81cb96e2: bpf_prog_offload_replace_insn.cold (STB_LOCAL)
ffffffff8126fbb0-ffffffff8126fc6b: bpf_prog_offload_replace_insn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void bpf_prog_offload_replace_insn(struct bpf_verifier_env *env, u32 off, struct bpf_insn *insn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/offload.c (0)
Location: kernel/bpf/offload.c:178
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:opt_hard_wire_dead_code_branches
```
**Symbols:**

```
ffffffff81e6aac8-ffffffff81e6ab06: bpf_prog_offload_replace_insn.cold (STB_LOCAL)
ffffffff812bec30-ffffffff812becf7: bpf_prog_offload_replace_insn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void bpf_prog_offload_replace_insn(struct bpf_verifier_env *env, u32 off, struct bpf_insn *insn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/offload.c (0)
Location: kernel/bpf/offload.c:178
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:opt_hard_wire_dead_code_branches
```
**Symbols:**

```
ffffffff82061b5d-ffffffff82061b9b: bpf_prog_offload_replace_insn.cold (STB_LOCAL)
ffffffff813222a0-ffffffff81322367: bpf_prog_offload_replace_insn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void bpf_prog_offload_replace_insn(struct bpf_verifier_env *env, u32 off, struct bpf_insn *insn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/offload.c (0)
Location: kernel/bpf/offload.c:337
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:opt_hard_wire_dead_code_branches
```
**Symbols:**

```
ffffffff820e1232-ffffffff820e1270: bpf_prog_offload_replace_insn.cold (STB_LOCAL)
ffffffff813521c0-ffffffff81352287: bpf_prog_offload_replace_insn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void bpf_prog_offload_replace_insn(struct bpf_verifier_env *env, u32 off, struct bpf_insn *insn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/offload.c (0)
Location: kernel/bpf/offload.c:347
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:opt_hard_wire_dead_code_branches
```
**Symbols:**

```
ffffffff821bda99-ffffffff821bdad7: bpf_prog_offload_replace_insn.cold (STB_LOCAL)
ffffffff813796a0-ffffffff81379767: bpf_prog_offload_replace_insn (STB_GLOBAL)
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
void bpf_prog_offload_replace_insn(struct bpf_verifier_env *env, u32 off, struct bpf_insn *insn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffff80001028ab58)
Location: kernel/bpf/offload.c:178
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:bpf_check
```
**Symbols:**

```
ffff80001028ab58-ffff80001028abfc: bpf_prog_offload_replace_insn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void bpf_prog_offload_replace_insn(struct bpf_verifier_env *env, u32 off, struct bpf_insn *insn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (c04ba420)
Location: kernel/bpf/offload.c:178
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:bpf_check
```
**Symbols:**

```
c04ba420-c04ba4cc: bpf_prog_offload_replace_insn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void bpf_prog_offload_replace_insn(struct bpf_verifier_env *env, u32 off, struct bpf_insn *insn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (c000000000336840)
Location: kernel/bpf/offload.c:178
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:bpf_check
```
**Symbols:**

```
c000000000336840-c00000000033692c: bpf_prog_offload_replace_insn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void bpf_prog_offload_replace_insn(struct bpf_verifier_env *env, u32 off, struct bpf_insn *insn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffffffe0001beada)
Location: kernel/bpf/offload.c:178
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:bpf_check
```
**Symbols:**

```
ffffffe0001beada-ffffffe0001beb64: bpf_prog_offload_replace_insn (STB_GLOBAL)
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
void bpf_prog_offload_replace_insn(struct bpf_verifier_env *env, u32 off, struct bpf_insn *insn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffffffff811fad70)
Location: kernel/bpf/offload.c:178
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:bpf_check
```
**Symbols:**

```
ffffffff811fad70-ffffffff811fadf4: bpf_prog_offload_replace_insn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void bpf_prog_offload_replace_insn(struct bpf_verifier_env *env, u32 off, struct bpf_insn *insn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffffffff811edac0)
Location: kernel/bpf/offload.c:178
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:bpf_check
```
**Symbols:**

```
ffffffff811edac0-ffffffff811edb44: bpf_prog_offload_replace_insn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void bpf_prog_offload_replace_insn(struct bpf_verifier_env *env, u32 off, struct bpf_insn *insn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffffffff811f8b40)
Location: kernel/bpf/offload.c:178
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:bpf_check
```
**Symbols:**

```
ffffffff811f8b40-ffffffff811f8bc4: bpf_prog_offload_replace_insn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void bpf_prog_offload_replace_insn(struct bpf_verifier_env *env, u32 off, struct bpf_insn *insn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffffffff81207480)
Location: kernel/bpf/offload.c:178
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:bpf_check
```
**Symbols:**

```
ffffffff81207480-ffffffff81207504: bpf_prog_offload_replace_insn (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
