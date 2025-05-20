# Function: <code>bpf_prog_offload_remove_insns</code>

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
void bpf_prog_offload_remove_insns(struct bpf_verifier_env *env, u32 off, u32 cnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffffffff811f57e0)
Location: kernel/bpf/offload.c:197
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:verifier_remove_insns
```
**Symbols:**

```
ffffffff811f57e0-ffffffff811f5864: bpf_prog_offload_remove_insns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void bpf_prog_offload_remove_insns(struct bpf_verifier_env *env, u32 off, u32 cnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffffffff812027e0)
Location: kernel/bpf/offload.c:197
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:verifier_remove_insns
```
**Symbols:**

```
ffffffff812027e0-ffffffff81202864: bpf_prog_offload_remove_insns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void bpf_prog_offload_remove_insns(struct bpf_verifier_env *env, u32 off, u32 cnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffffffff81229d90)
Location: kernel/bpf/offload.c:197
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:verifier_remove_insns
```
**Symbols:**

```
ffffffff81229d90-ffffffff81229e16: bpf_prog_offload_remove_insns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void bpf_prog_offload_remove_insns(struct bpf_verifier_env *env, u32 off, u32 cnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffffffff81231920)
Location: kernel/bpf/offload.c:197
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:verifier_remove_insns
```
**Symbols:**

```
ffffffff81231920-ffffffff812319a6: bpf_prog_offload_remove_insns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void bpf_prog_offload_remove_insns(struct bpf_verifier_env *env, u32 off, u32 cnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffffffff81235aa0)
Location: kernel/bpf/offload.c:197
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:verifier_remove_insns
```
**Symbols:**

```
ffffffff81235aa0-ffffffff81235b24: bpf_prog_offload_remove_insns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void bpf_prog_offload_remove_insns(struct bpf_verifier_env *env, u32 off, u32 cnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/offload.c (0)
Location: kernel/bpf/offload.c:197
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:verifier_remove_insns
```
**Symbols:**

```
ffffffff81cb96e2-ffffffff81cb9718: bpf_prog_offload_remove_insns.cold (STB_LOCAL)
ffffffff8126fc70-ffffffff8126fd28: bpf_prog_offload_remove_insns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void bpf_prog_offload_remove_insns(struct bpf_verifier_env *env, u32 off, u32 cnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/offload.c (0)
Location: kernel/bpf/offload.c:197
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:verifier_remove_insns
```
**Symbols:**

```
ffffffff81e6ab06-ffffffff81e6ab3c: bpf_prog_offload_remove_insns.cold (STB_LOCAL)
ffffffff812bed00-ffffffff812bedc4: bpf_prog_offload_remove_insns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void bpf_prog_offload_remove_insns(struct bpf_verifier_env *env, u32 off, u32 cnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/offload.c (0)
Location: kernel/bpf/offload.c:197
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:verifier_remove_insns
```
**Symbols:**

```
ffffffff82061b9b-ffffffff82061bd1: bpf_prog_offload_remove_insns.cold (STB_LOCAL)
ffffffff81322380-ffffffff81322444: bpf_prog_offload_remove_insns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void bpf_prog_offload_remove_insns(struct bpf_verifier_env *env, u32 off, u32 cnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/offload.c (0)
Location: kernel/bpf/offload.c:356
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:verifier_remove_insns
```
**Symbols:**

```
ffffffff820e1270-ffffffff820e12a6: bpf_prog_offload_remove_insns.cold (STB_LOCAL)
ffffffff813522a0-ffffffff81352364: bpf_prog_offload_remove_insns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void bpf_prog_offload_remove_insns(struct bpf_verifier_env *env, u32 off, u32 cnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/offload.c (0)
Location: kernel/bpf/offload.c:366
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:verifier_remove_insns
```
**Symbols:**

```
ffffffff821bdad7-ffffffff821bdb0d: bpf_prog_offload_remove_insns.cold (STB_LOCAL)
ffffffff81379780-ffffffff81379844: bpf_prog_offload_remove_insns (STB_GLOBAL)
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
void bpf_prog_offload_remove_insns(struct bpf_verifier_env *env, u32 off, u32 cnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffff80001028ac00)
Location: kernel/bpf/offload.c:197
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:verifier_remove_insns
```
**Symbols:**

```
ffff80001028ac00-ffff80001028aca4: bpf_prog_offload_remove_insns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void bpf_prog_offload_remove_insns(struct bpf_verifier_env *env, u32 off, u32 cnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (c04ba4cc)
Location: kernel/bpf/offload.c:197
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:verifier_remove_insns
```
**Symbols:**

```
c04ba4cc-c04ba578: bpf_prog_offload_remove_insns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void bpf_prog_offload_remove_insns(struct bpf_verifier_env *env, u32 off, u32 cnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (c000000000336930)
Location: kernel/bpf/offload.c:197
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:verifier_remove_insns
```
**Symbols:**

```
c000000000336930-c000000000336a1c: bpf_prog_offload_remove_insns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void bpf_prog_offload_remove_insns(struct bpf_verifier_env *env, u32 off, u32 cnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffffffe0001beb64)
Location: kernel/bpf/offload.c:197
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:verifier_remove_insns
```
**Symbols:**

```
ffffffe0001beb64-ffffffe0001bebee: bpf_prog_offload_remove_insns (STB_GLOBAL)
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
void bpf_prog_offload_remove_insns(struct bpf_verifier_env *env, u32 off, u32 cnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffffffff811fae00)
Location: kernel/bpf/offload.c:197
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:verifier_remove_insns
```
**Symbols:**

```
ffffffff811fae00-ffffffff811fae84: bpf_prog_offload_remove_insns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void bpf_prog_offload_remove_insns(struct bpf_verifier_env *env, u32 off, u32 cnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffffffff811edb50)
Location: kernel/bpf/offload.c:197
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:verifier_remove_insns
```
**Symbols:**

```
ffffffff811edb50-ffffffff811edbd4: bpf_prog_offload_remove_insns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void bpf_prog_offload_remove_insns(struct bpf_verifier_env *env, u32 off, u32 cnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffffffff811f8bd0)
Location: kernel/bpf/offload.c:197
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:verifier_remove_insns
```
**Symbols:**

```
ffffffff811f8bd0-ffffffff811f8c54: bpf_prog_offload_remove_insns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void bpf_prog_offload_remove_insns(struct bpf_verifier_env *env, u32 off, u32 cnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/offload.c (ffffffff81207510)
Location: kernel/bpf/offload.c:197
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:verifier_remove_insns
```
**Symbols:**

```
ffffffff81207510-ffffffff81207594: bpf_prog_offload_remove_insns (STB_GLOBAL)
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
