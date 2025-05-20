# Function: <code>check_helper_call</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int check_helper_call(struct bpf_verifier_env *env, int func_id, int insn_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811bae00)
Location: kernel/bpf/verifier.c:2457
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
```
**Symbols:**

```
ffffffff811bae00-ffffffff811bb6e3: check_helper_call (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int check_helper_call(struct bpf_verifier_env *env, int func_id, int insn_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811caa80)
Location: kernel/bpf/verifier.c:2846
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
```
**Symbols:**

```
ffffffff811caa80-ffffffff811cb807: check_helper_call (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int check_helper_call(struct bpf_verifier_env *env, int func_id, int insn_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811e1b60)
Location: kernel/bpf/verifier.c:3938
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
```
**Symbols:**

```
ffffffff811e1b60-ffffffff811e2b58: check_helper_call (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int check_helper_call(struct bpf_verifier_env *env, int func_id, int insn_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811ee360)
Location: kernel/bpf/verifier.c:3941
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
```
**Symbols:**

```
ffffffff811ee360-ffffffff811ef3de: check_helper_call (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int check_helper_call(struct bpf_verifier_env *env, int func_id, int insn_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81211630)
Location: kernel/bpf/verifier.c:4596
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
```
**Symbols:**

```
ffffffff81211630-ffffffff8121204e: check_helper_call (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int check_helper_call(struct bpf_verifier_env *env, int func_id, int insn_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff812121e0)
Location: kernel/bpf/verifier.c:5048
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
```
**Symbols:**

```
ffffffff812121e0-ffffffff81212d9d: check_helper_call (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81214300)
Location: kernel/bpf/verifier.c:5938
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:do_check
```
**Symbols:**

```
ffffffff81214300-ffffffff81215245: check_helper_call.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int check_helper_call(struct bpf_verifier_env *env, struct bpf_insn *insn, int *insn_idx_p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:6213
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
```
**Symbols:**

```
ffffffff8124a5a0-ffffffff8124b7c3: check_helper_call (STB_LOCAL)
ffffffff81cb8dc7-ffffffff81cb8e50: check_helper_call.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int check_helper_call(struct bpf_verifier_env *env, struct bpf_insn *insn, int *insn_idx_p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:7110
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
```
**Symbols:**

```
ffffffff81291590-ffffffff81292bef: check_helper_call (STB_LOCAL)
ffffffff81e6a0da-ffffffff81e6a110: check_helper_call.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int check_helper_call(struct bpf_verifier_env *env, struct bpf_insn *insn, int *insn_idx_p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:7911
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
```
**Symbols:**

```
ffffffff812ebc70-ffffffff812ed60a: check_helper_call (STB_LOCAL)
ffffffff8206110c-ffffffff820611cf: check_helper_call.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int check_helper_call(struct bpf_verifier_env *env, struct bpf_insn *insn, int *insn_idx_p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:9348
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
```
**Symbols:**

```
ffffffff813184f0-ffffffff81319f5b: check_helper_call (STB_LOCAL)
ffffffff820e056d-ffffffff820e0651: check_helper_call.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:10056
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:do_check
```
**Symbols:**

```
ffffffff813399f0-ffffffff8133b8d2: check_helper_call.isra.0 (STB_LOCAL)
ffffffff821bcb52-ffffffff821bcceb: check_helper_call.isra.0.cold (STB_LOCAL)
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
int check_helper_call(struct bpf_verifier_env *env, int func_id, int insn_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffff800010271d30)
Location: kernel/bpf/verifier.c:3941
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
```
**Symbols:**

```
ffff800010271d30-ffff800010272bec: check_helper_call (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int check_helper_call(struct bpf_verifier_env *env, int func_id, int insn_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (c04a4090)
Location: kernel/bpf/verifier.c:3941
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
```
**Symbols:**

```
c04a4090-c04a5294: check_helper_call (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int check_helper_call(struct bpf_verifier_env *env, int func_id, int insn_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (c000000000319230)
Location: kernel/bpf/verifier.c:3941
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
```
**Symbols:**

```
c000000000319230-c00000000031a4e4: check_helper_call (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int check_helper_call(struct bpf_verifier_env *env, int func_id, int insn_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffe0001aaf4c)
Location: kernel/bpf/verifier.c:3941
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
```
**Symbols:**

```
ffffffe0001aaf4c-ffffffe0001ab9f8: check_helper_call (STB_LOCAL)
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
int check_helper_call(struct bpf_verifier_env *env, int func_id, int insn_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811e6980)
Location: kernel/bpf/verifier.c:3941
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
```
**Symbols:**

```
ffffffff811e6980-ffffffff811e79fe: check_helper_call (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int check_helper_call(struct bpf_verifier_env *env, int func_id, int insn_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811d9740)
Location: kernel/bpf/verifier.c:3941
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
```
**Symbols:**

```
ffffffff811d9740-ffffffff811da7be: check_helper_call (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int check_helper_call(struct bpf_verifier_env *env, int func_id, int insn_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811e4750)
Location: kernel/bpf/verifier.c:3941
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
```
**Symbols:**

```
ffffffff811e4750-ffffffff811e57ce: check_helper_call (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int check_helper_call(struct bpf_verifier_env *env, int func_id, int insn_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811f2b20)
Location: kernel/bpf/verifier.c:3941
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
```
**Symbols:**

```
ffffffff811f2b20-ffffffff811f3b9e: check_helper_call (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
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
