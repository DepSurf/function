# Function: <code>check_func_arg</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int check_func_arg(struct verifier_env *env, u32 regno, enum bpf_arg_type arg_type, struct bpf_map **mapp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81173cb0)
Location: kernel/bpf/verifier.c:809
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
```
**Symbols:**

```
ffffffff81173cb0-ffffffff81173e7e: check_func_arg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int check_func_arg(struct verifier_env *env, u32 regno, enum bpf_arg_type arg_type, struct bpf_call_arg_meta *meta);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81181fa0)
Location: kernel/bpf/verifier.c:929
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
```
**Symbols:**

```
ffffffff81181fa0-ffffffff811821e5: check_func_arg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int check_func_arg(struct bpf_verifier_env *env, u32 regno, enum bpf_arg_type arg_type, struct bpf_call_arg_meta *meta);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff8118e670)
Location: kernel/bpf/verifier.c:961
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
```
**Symbols:**

```
ffffffff8118e670-ffffffff8118e966: check_func_arg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int check_func_arg(struct bpf_verifier_env *env, u32 regno, enum bpf_arg_type arg_type, struct bpf_call_arg_meta *meta);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81195700)
Location: kernel/bpf/verifier.c:1089
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
```
**Symbols:**

```
ffffffff81195700-ffffffff81195a5c: check_func_arg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int check_func_arg(struct bpf_verifier_env *env, u32 regno, enum bpf_arg_type arg_type, struct bpf_call_arg_meta *meta);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811a3770)
Location: kernel/bpf/verifier.c:1386
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
```
**Symbols:**

```
ffffffff811a3770-ffffffff811a3ae5: check_func_arg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int check_func_arg(struct bpf_verifier_env *env, u32 regno, enum bpf_arg_type arg_type, struct bpf_call_arg_meta *meta);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811baa70)
Location: kernel/bpf/verifier.c:1949
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
```
**Symbols:**

```
ffffffff811baa70-ffffffff811badfd: check_func_arg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int check_func_arg(struct bpf_verifier_env *env, u32 regno, enum bpf_arg_type arg_type, struct bpf_call_arg_meta *meta);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811ca650)
Location: kernel/bpf/verifier.c:2211
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
```
**Symbols:**

```
ffffffff811ca650-ffffffff811caa78: check_func_arg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int check_func_arg(struct bpf_verifier_env *env, u32 regno, enum bpf_arg_type arg_type, struct bpf_call_arg_meta *meta);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811ddd80)
Location: kernel/bpf/verifier.c:3225
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
```
**Symbols:**

```
ffffffff811ddd80-ffffffff811de307: check_func_arg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int check_func_arg(struct bpf_verifier_env *env, u32 regno, enum bpf_arg_type arg_type, struct bpf_call_arg_meta *meta);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811ea540)
Location: kernel/bpf/verifier.c:3226
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
```
**Symbols:**

```
ffffffff811ea540-ffffffff811eaac7: check_func_arg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int check_func_arg(struct bpf_verifier_env *env, u32 regno, enum bpf_arg_type arg_type, struct bpf_call_arg_meta *meta);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81210f10)
Location: kernel/bpf/verifier.c:3737
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_helper_call
```
**Symbols:**

```
ffffffff81210f10-ffffffff8121162e: check_func_arg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int check_func_arg(struct bpf_verifier_env *env, u32 arg, struct bpf_call_arg_meta *meta, const struct bpf_func_proto *fn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81211c30)
Location: kernel/bpf/verifier.c:4148
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_helper_call
```
**Symbols:**

```
ffffffff81211c30-ffffffff812121d4: check_func_arg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int check_func_arg(struct bpf_verifier_env *env, u32 arg, struct bpf_call_arg_meta *meta, const struct bpf_func_proto *fn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81213bb0)
Location: kernel/bpf/verifier.c:4858
Inline: False
```
**Symbols:**

```
ffffffff81213bb0-ffffffff812142fb: check_func_arg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int check_func_arg(struct bpf_verifier_env *env, u32 arg, struct bpf_call_arg_meta *meta, const struct bpf_func_proto *fn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:5022
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_helper_call
```
**Symbols:**

```
ffffffff81249b60-ffffffff8124a596: check_func_arg (STB_LOCAL)
ffffffff81cb8daa-ffffffff81cb8dc7: check_func_arg.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int check_func_arg(struct bpf_verifier_env *env, u32 arg, struct bpf_call_arg_meta *meta, const struct bpf_func_proto *fn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:5842
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_helper_call
```
**Symbols:**

```
ffffffff81290790-ffffffff81291587: check_func_arg (STB_LOCAL)
ffffffff81e6a0a0-ffffffff81e6a0da: check_func_arg.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int check_func_arg(struct bpf_verifier_env *env, u32 arg, struct bpf_call_arg_meta *meta, const struct bpf_func_proto *fn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:6563
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_helper_call
```
**Symbols:**

```
ffffffff812eb0a0-ffffffff812ebc56: check_func_arg (STB_LOCAL)
ffffffff820610da-ffffffff8206110c: check_func_arg.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int check_func_arg(struct bpf_verifier_env *env, u32 arg, struct bpf_call_arg_meta *meta, const struct bpf_func_proto *fn, int insn_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:7923
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_helper_call
```
**Symbols:**

```
ffffffff81317900-ffffffff813184de: check_func_arg (STB_LOCAL)
ffffffff820e053b-ffffffff820e056d: check_func_arg.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int check_func_arg(struct bpf_verifier_env *env, u32 arg, struct bpf_call_arg_meta *meta, const struct bpf_func_proto *fn, int insn_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:8475
Inline: False
```
**Symbols:**

```
ffffffff81334b00-ffffffff813355d4: check_func_arg (STB_LOCAL)
ffffffff821bc6ec-ffffffff821bc701: check_func_arg.cold (STB_LOCAL)
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
int check_func_arg(struct bpf_verifier_env *env, u32 regno, enum bpf_arg_type arg_type, struct bpf_call_arg_meta *meta);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffff80001026dca0)
Location: kernel/bpf/verifier.c:3226
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
```
**Symbols:**

```
ffff80001026dca0-ffff80001026e268: check_func_arg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int check_func_arg(struct bpf_verifier_env *env, u32 regno, enum bpf_arg_type arg_type, struct bpf_call_arg_meta *meta);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (c04a0428)
Location: kernel/bpf/verifier.c:3226
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
```
**Symbols:**

```
c04a0428-c04a0a14: check_func_arg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int check_func_arg(struct bpf_verifier_env *env, u32 regno, enum bpf_arg_type arg_type, struct bpf_call_arg_meta *meta);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (c000000000314730)
Location: kernel/bpf/verifier.c:3226
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
```
**Symbols:**

```
c000000000314730-c000000000314e60: check_func_arg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int check_func_arg(struct bpf_verifier_env *env, u32 regno, enum bpf_arg_type arg_type, struct bpf_call_arg_meta *meta);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffe0001a7c3e)
Location: kernel/bpf/verifier.c:3226
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
```
**Symbols:**

```
ffffffe0001a7c3e-ffffffe0001a80d8: check_func_arg (STB_LOCAL)
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
int check_func_arg(struct bpf_verifier_env *env, u32 regno, enum bpf_arg_type arg_type, struct bpf_call_arg_meta *meta);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811e2b60)
Location: kernel/bpf/verifier.c:3226
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
```
**Symbols:**

```
ffffffff811e2b60-ffffffff811e30e7: check_func_arg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int check_func_arg(struct bpf_verifier_env *env, u32 regno, enum bpf_arg_type arg_type, struct bpf_call_arg_meta *meta);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811d5920)
Location: kernel/bpf/verifier.c:3226
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
```
**Symbols:**

```
ffffffff811d5920-ffffffff811d5ea7: check_func_arg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int check_func_arg(struct bpf_verifier_env *env, u32 regno, enum bpf_arg_type arg_type, struct bpf_call_arg_meta *meta);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811e0930)
Location: kernel/bpf/verifier.c:3226
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
```
**Symbols:**

```
ffffffff811e0930-ffffffff811e0eb7: check_func_arg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int check_func_arg(struct bpf_verifier_env *env, u32 regno, enum bpf_arg_type arg_type, struct bpf_call_arg_meta *meta);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811eed40)
Location: kernel/bpf/verifier.c:3226
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
```
**Symbols:**

```
ffffffff811eed40-ffffffff811ef2c7: check_func_arg (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct bpf_call_arg_meta *meta</code>
</li>
<li>
<b>Param removed. </b>
<code>struct bpf_map **mapp</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.8</code> and <code>4.10</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct verifier_env *env</code> ➡️ <code>struct bpf_verifier_env *env</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>u32 arg</code>
</li>
<li>
<b>Param added. </b>
<code>const struct bpf_func_proto *fn</code>
</li>
<li>
<b>Param removed. </b>
<code>u32 regno</code>
</li>
<li>
<b>Param removed. </b>
<code>enum bpf_arg_type arg_type</code>
</li>
<li>
<b>Param reordered. </b>
<code>env, regno, arg_type, meta</code> ➡️ <code>env, arg, meta, fn</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int insn_idx</code>
</li>
</ul>
</details>
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
