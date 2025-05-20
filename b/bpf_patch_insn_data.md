# Function: <code>bpf_patch_insn_data</code>

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
struct bpf_prog *bpf_patch_insn_data(struct bpf_verifier_env *env, u32 off, const struct bpf_insn *patch, u32 len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81194680)
Location: kernel/bpf/verifier.c:3513
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:fixup_bpf_calls
  - kernel/bpf/verifier.c:convert_ctx_accesses
  - kernel/bpf/verifier.c:convert_ctx_accesses
```
**Symbols:**

```
ffffffff81194680-ffffffff8119475d: bpf_patch_insn_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct bpf_prog *bpf_patch_insn_data(struct bpf_verifier_env *env, u32 off, const struct bpf_insn *patch, u32 len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811a2b00)
Location: kernel/bpf/verifier.c:4321
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:fixup_bpf_calls
  - kernel/bpf/verifier.c:fixup_bpf_calls
  - kernel/bpf/verifier.c:fixup_bpf_calls
  - kernel/bpf/verifier.c:fixup_bpf_calls
  - kernel/bpf/verifier.c:convert_ctx_accesses
  - kernel/bpf/verifier.c:convert_ctx_accesses
```
**Symbols:**

```
ffffffff811a2b00-ffffffff811a2c03: bpf_patch_insn_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct bpf_prog *bpf_patch_insn_data(struct bpf_verifier_env *env, u32 off, const struct bpf_insn *patch, u32 len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811b6ee0)
Location: kernel/bpf/verifier.c:5237
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:fixup_bpf_calls
  - kernel/bpf/verifier.c:fixup_bpf_calls
  - kernel/bpf/verifier.c:fixup_bpf_calls
  - kernel/bpf/verifier.c:fixup_bpf_calls
  - kernel/bpf/verifier.c:convert_ctx_accesses
  - kernel/bpf/verifier.c:convert_ctx_accesses
  - kernel/bpf/verifier.c:convert_ctx_accesses
```
**Symbols:**

```
ffffffff811b6ee0-ffffffff811b7018: bpf_patch_insn_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct bpf_prog *bpf_patch_insn_data(struct bpf_verifier_env *env, u32 off, const struct bpf_insn *patch, u32 len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811c6070)
Location: kernel/bpf/verifier.c:6423
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:fixup_bpf_calls
  - kernel/bpf/verifier.c:fixup_bpf_calls
  - kernel/bpf/verifier.c:fixup_bpf_calls
  - kernel/bpf/verifier.c:convert_ctx_accesses
  - kernel/bpf/verifier.c:convert_ctx_accesses
  - kernel/bpf/verifier.c:convert_ctx_accesses
```
**Symbols:**

```
ffffffff811c6070-ffffffff811c61ad: bpf_patch_insn_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct bpf_prog *bpf_patch_insn_data(struct bpf_verifier_env *env, u32 off, const struct bpf_insn *patch, u32 len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811deb70)
Location: kernel/bpf/verifier.c:8126
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:fixup_bpf_calls
  - kernel/bpf/verifier.c:fixup_bpf_calls
  - kernel/bpf/verifier.c:fixup_bpf_calls
  - kernel/bpf/verifier.c:convert_ctx_accesses
  - kernel/bpf/verifier.c:convert_ctx_accesses
  - kernel/bpf/verifier.c:convert_ctx_accesses
```
**Symbols:**

```
ffffffff811deb70-ffffffff811ded17: bpf_patch_insn_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct bpf_prog *bpf_patch_insn_data(struct bpf_verifier_env *env, u32 off, const struct bpf_insn *patch, u32 len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811eb330)
Location: kernel/bpf/verifier.c:8141
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:fixup_bpf_calls
  - kernel/bpf/verifier.c:fixup_bpf_calls
  - kernel/bpf/verifier.c:fixup_bpf_calls
  - kernel/bpf/verifier.c:convert_ctx_accesses
  - kernel/bpf/verifier.c:convert_ctx_accesses
  - kernel/bpf/verifier.c:convert_ctx_accesses
```
**Symbols:**

```
ffffffff811eb330-ffffffff811eb4d7: bpf_patch_insn_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct bpf_prog *bpf_patch_insn_data(struct bpf_verifier_env *env, u32 off, const struct bpf_insn *patch, u32 len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff8120a320)
Location: kernel/bpf/verifier.c:9255
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:fixup_bpf_calls
  - kernel/bpf/verifier.c:fixup_bpf_calls
  - kernel/bpf/verifier.c:fixup_bpf_calls
  - kernel/bpf/verifier.c:convert_ctx_accesses
  - kernel/bpf/verifier.c:convert_ctx_accesses
  - kernel/bpf/verifier.c:convert_ctx_accesses
```
**Symbols:**

```
ffffffff8120a320-ffffffff8120a3e0: bpf_patch_insn_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct bpf_prog *bpf_patch_insn_data(struct bpf_verifier_env *env, u32 off, const struct bpf_insn *patch, u32 len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff8120c490)
Location: kernel/bpf/verifier.c:10184
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:fixup_bpf_calls
  - kernel/bpf/verifier.c:fixup_bpf_calls
  - kernel/bpf/verifier.c:fixup_bpf_calls
  - kernel/bpf/verifier.c:fixup_bpf_calls
  - kernel/bpf/verifier.c:convert_ctx_accesses
  - kernel/bpf/verifier.c:convert_ctx_accesses
  - kernel/bpf/verifier.c:convert_ctx_accesses
```
**Symbols:**

```
ffffffff8120c490-ffffffff8120c58f: bpf_patch_insn_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct bpf_prog *bpf_patch_insn_data(struct bpf_verifier_env *env, u32 off, const struct bpf_insn *patch, u32 len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff8120e0b0)
Location: kernel/bpf/verifier.c:11449
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_misc_fixups
  - kernel/bpf/verifier.c:do_misc_fixups
  - kernel/bpf/verifier.c:do_misc_fixups
  - kernel/bpf/verifier.c:do_misc_fixups
  - kernel/bpf/verifier.c:convert_ctx_accesses
  - kernel/bpf/verifier.c:convert_ctx_accesses
  - kernel/bpf/verifier.c:convert_ctx_accesses
```
**Symbols:**

```
ffffffff8120e0b0-ffffffff8120e1c4: bpf_patch_insn_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct bpf_prog *bpf_patch_insn_data(struct bpf_verifier_env *env, u32 off, const struct bpf_insn *patch, u32 len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81242620)
Location: kernel/bpf/verifier.c:11824
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_misc_fixups
  - kernel/bpf/verifier.c:do_misc_fixups
  - kernel/bpf/verifier.c:do_misc_fixups
  - kernel/bpf/verifier.c:do_misc_fixups
  - kernel/bpf/verifier.c:do_misc_fixups
  - kernel/bpf/verifier.c:do_misc_fixups
  - kernel/bpf/verifier.c:convert_ctx_accesses
  - kernel/bpf/verifier.c:convert_ctx_accesses
  - kernel/bpf/verifier.c:convert_ctx_accesses
```
**Symbols:**

```
ffffffff81242620-ffffffff812428a4: bpf_patch_insn_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct bpf_prog *bpf_patch_insn_data(struct bpf_verifier_env *env, u32 off, const struct bpf_insn *patch, u32 len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81287d20)
Location: kernel/bpf/verifier.c:12883
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_misc_fixups
  - kernel/bpf/verifier.c:do_misc_fixups
  - kernel/bpf/verifier.c:do_misc_fixups
  - kernel/bpf/verifier.c:do_misc_fixups
  - kernel/bpf/verifier.c:do_misc_fixups
  - kernel/bpf/verifier.c:do_misc_fixups
  - kernel/bpf/verifier.c:do_misc_fixups
  - kernel/bpf/verifier.c:do_misc_fixups
  - kernel/bpf/verifier.c:convert_ctx_accesses
  - kernel/bpf/verifier.c:convert_ctx_accesses
  - kernel/bpf/verifier.c:convert_ctx_accesses
```
**Symbols:**

```
ffffffff81287d20-ffffffff81287fb9: bpf_patch_insn_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct bpf_prog *bpf_patch_insn_data(struct bpf_verifier_env *env, u32 off, const struct bpf_insn *patch, u32 len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff812de3d0)
Location: kernel/bpf/verifier.c:14860
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:inline_bpf_loop
  - kernel/bpf/verifier.c:do_misc_fixups
  - kernel/bpf/verifier.c:do_misc_fixups
  - kernel/bpf/verifier.c:do_misc_fixups
  - kernel/bpf/verifier.c:do_misc_fixups
  - kernel/bpf/verifier.c:do_misc_fixups
  - kernel/bpf/verifier.c:do_misc_fixups
  - kernel/bpf/verifier.c:do_misc_fixups
  - kernel/bpf/verifier.c:do_misc_fixups
  - kernel/bpf/verifier.c:convert_ctx_accesses
  - kernel/bpf/verifier.c:convert_ctx_accesses
  - kernel/bpf/verifier.c:convert_ctx_accesses
```
**Symbols:**

```
ffffffff812de3d0-ffffffff812de65b: bpf_patch_insn_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct bpf_prog *bpf_patch_insn_data(struct bpf_verifier_env *env, u32 off, const struct bpf_insn *patch, u32 len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff812fd200)
Location: kernel/bpf/verifier.c:17077
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:inline_bpf_loop
  - kernel/bpf/verifier.c:do_misc_fixups
  - kernel/bpf/verifier.c:do_misc_fixups
  - kernel/bpf/verifier.c:do_misc_fixups
  - kernel/bpf/verifier.c:do_misc_fixups
  - kernel/bpf/verifier.c:do_misc_fixups
  - kernel/bpf/verifier.c:do_misc_fixups
  - kernel/bpf/verifier.c:do_misc_fixups
  - kernel/bpf/verifier.c:do_misc_fixups
  - kernel/bpf/verifier.c:do_misc_fixups
  - kernel/bpf/verifier.c:convert_ctx_accesses
  - kernel/bpf/verifier.c:convert_ctx_accesses
  - kernel/bpf/verifier.c:convert_ctx_accesses
```
**Symbols:**

```
ffffffff812fd200-ffffffff812fd48b: bpf_patch_insn_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct bpf_prog *bpf_patch_insn_data(struct bpf_verifier_env *env, u32 off, const struct bpf_insn *patch, u32 len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff8131c720)
Location: kernel/bpf/verifier.c:18231
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:inline_bpf_loop
  - kernel/bpf/verifier.c:do_misc_fixups
  - kernel/bpf/verifier.c:do_misc_fixups
  - kernel/bpf/verifier.c:do_misc_fixups
  - kernel/bpf/verifier.c:do_misc_fixups
  - kernel/bpf/verifier.c:do_misc_fixups
  - kernel/bpf/verifier.c:do_misc_fixups
  - kernel/bpf/verifier.c:do_misc_fixups
  - kernel/bpf/verifier.c:do_misc_fixups
  - kernel/bpf/verifier.c:do_misc_fixups
  - kernel/bpf/verifier.c:do_misc_fixups
  - kernel/bpf/verifier.c:convert_ctx_accesses
  - kernel/bpf/verifier.c:convert_ctx_accesses
  - kernel/bpf/verifier.c:convert_ctx_accesses
```
**Symbols:**

```
ffffffff8131c720-ffffffff8131c994: bpf_patch_insn_data (STB_LOCAL)
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
struct bpf_prog *bpf_patch_insn_data(struct bpf_verifier_env *env, u32 off, const struct bpf_insn *patch, u32 len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffff80001026ec60)
Location: kernel/bpf/verifier.c:8141
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:fixup_bpf_calls
  - kernel/bpf/verifier.c:fixup_bpf_calls
  - kernel/bpf/verifier.c:fixup_bpf_calls
  - kernel/bpf/verifier.c:fixup_bpf_calls
  - kernel/bpf/verifier.c:fixup_bpf_calls
  - kernel/bpf/verifier.c:fixup_bpf_calls
  - kernel/bpf/verifier.c:convert_ctx_accesses
  - kernel/bpf/verifier.c:convert_ctx_accesses
  - kernel/bpf/verifier.c:convert_ctx_accesses
  - kernel/bpf/verifier.c:convert_ctx_accesses
```
**Symbols:**

```
ffff80001026ec60-ffff80001026ee30: bpf_patch_insn_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct bpf_prog *bpf_patch_insn_data(struct bpf_verifier_env *env, u32 off, const struct bpf_insn *patch, u32 len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (c04a1034)
Location: kernel/bpf/verifier.c:8141
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:fixup_bpf_calls
  - kernel/bpf/verifier.c:fixup_bpf_calls
  - kernel/bpf/verifier.c:fixup_bpf_calls
  - kernel/bpf/verifier.c:convert_ctx_accesses
  - kernel/bpf/verifier.c:convert_ctx_accesses
  - kernel/bpf/verifier.c:convert_ctx_accesses
```
**Symbols:**

```
c04a1034-c04a11e8: bpf_patch_insn_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct bpf_prog *bpf_patch_insn_data(struct bpf_verifier_env *env, u32 off, const struct bpf_insn *patch, u32 len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (c000000000315520)
Location: kernel/bpf/verifier.c:8141
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:fixup_bpf_calls
  - kernel/bpf/verifier.c:fixup_bpf_calls
  - kernel/bpf/verifier.c:fixup_bpf_calls
  - kernel/bpf/verifier.c:fixup_bpf_calls
  - kernel/bpf/verifier.c:fixup_bpf_calls
  - kernel/bpf/verifier.c:convert_ctx_accesses
  - kernel/bpf/verifier.c:convert_ctx_accesses
  - kernel/bpf/verifier.c:convert_ctx_accesses
  - kernel/bpf/verifier.c:convert_ctx_accesses
```
**Symbols:**

```
c000000000315520-c00000000031578c: bpf_patch_insn_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct bpf_prog *bpf_patch_insn_data(struct bpf_verifier_env *env, u32 off, const struct bpf_insn *patch, u32 len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffe0001a87b8)
Location: kernel/bpf/verifier.c:8141
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:fixup_bpf_calls
  - kernel/bpf/verifier.c:fixup_bpf_calls
  - kernel/bpf/verifier.c:fixup_bpf_calls
  - kernel/bpf/verifier.c:fixup_bpf_calls
  - kernel/bpf/verifier.c:fixup_bpf_calls
  - kernel/bpf/verifier.c:convert_ctx_accesses
  - kernel/bpf/verifier.c:convert_ctx_accesses
  - kernel/bpf/verifier.c:convert_ctx_accesses
  - kernel/bpf/verifier.c:convert_ctx_accesses
```
**Symbols:**

```
ffffffe0001a87b8-ffffffe0001a8962: bpf_patch_insn_data (STB_LOCAL)
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
struct bpf_prog *bpf_patch_insn_data(struct bpf_verifier_env *env, u32 off, const struct bpf_insn *patch, u32 len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811e3950)
Location: kernel/bpf/verifier.c:8141
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:fixup_bpf_calls
  - kernel/bpf/verifier.c:fixup_bpf_calls
  - kernel/bpf/verifier.c:fixup_bpf_calls
  - kernel/bpf/verifier.c:convert_ctx_accesses
  - kernel/bpf/verifier.c:convert_ctx_accesses
  - kernel/bpf/verifier.c:convert_ctx_accesses
```
**Symbols:**

```
ffffffff811e3950-ffffffff811e3af7: bpf_patch_insn_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct bpf_prog *bpf_patch_insn_data(struct bpf_verifier_env *env, u32 off, const struct bpf_insn *patch, u32 len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811d6710)
Location: kernel/bpf/verifier.c:8141
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:fixup_bpf_calls
  - kernel/bpf/verifier.c:fixup_bpf_calls
  - kernel/bpf/verifier.c:fixup_bpf_calls
  - kernel/bpf/verifier.c:convert_ctx_accesses
  - kernel/bpf/verifier.c:convert_ctx_accesses
  - kernel/bpf/verifier.c:convert_ctx_accesses
```
**Symbols:**

```
ffffffff811d6710-ffffffff811d68b7: bpf_patch_insn_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct bpf_prog *bpf_patch_insn_data(struct bpf_verifier_env *env, u32 off, const struct bpf_insn *patch, u32 len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811e1720)
Location: kernel/bpf/verifier.c:8141
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:fixup_bpf_calls
  - kernel/bpf/verifier.c:fixup_bpf_calls
  - kernel/bpf/verifier.c:fixup_bpf_calls
  - kernel/bpf/verifier.c:convert_ctx_accesses
  - kernel/bpf/verifier.c:convert_ctx_accesses
  - kernel/bpf/verifier.c:convert_ctx_accesses
```
**Symbols:**

```
ffffffff811e1720-ffffffff811e18c7: bpf_patch_insn_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct bpf_prog *bpf_patch_insn_data(struct bpf_verifier_env *env, u32 off, const struct bpf_insn *patch, u32 len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811efb30)
Location: kernel/bpf/verifier.c:8141
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:fixup_bpf_calls
  - kernel/bpf/verifier.c:fixup_bpf_calls
  - kernel/bpf/verifier.c:fixup_bpf_calls
  - kernel/bpf/verifier.c:convert_ctx_accesses
  - kernel/bpf/verifier.c:convert_ctx_accesses
  - kernel/bpf/verifier.c:convert_ctx_accesses
```
**Symbols:**

```
ffffffff811efb30-ffffffff811efcd7: bpf_patch_insn_data (STB_LOCAL)
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
