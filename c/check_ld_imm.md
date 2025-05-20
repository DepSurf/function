# Function: <code>check_ld_imm</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff8117483f)
Location: kernel/bpf/verifier.c:1281
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:do_check
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81182fe1)
Location: kernel/bpf/verifier.c:1745
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:do_check
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff8118facd)
Location: kernel/bpf/verifier.c:2128
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:do_check
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81195ec9)
Location: kernel/bpf/verifier.c:2546
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:do_check
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811a6617)
Location: kernel/bpf/verifier.c:3107
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:do_check
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811bc570)
Location: kernel/bpf/verifier.c:3906
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:do_check
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811cdab5)
Location: kernel/bpf/verifier.c:4608
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:do_check
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811e2daf)
Location: kernel/bpf/verifier.c:5943
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:do_check
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811ef62c)
Location: kernel/bpf/verifier.c:5953
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:do_check
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int check_ld_imm(struct bpf_verifier_env *env, struct bpf_insn *insn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81209f60)
Location: kernel/bpf/verifier.c:7028
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
```
**Symbols:**

```
ffffffff81209f60-ffffffff8120a13f: check_ld_imm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int check_ld_imm(struct bpf_verifier_env *env, struct bpf_insn *insn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff8120c000)
Location: kernel/bpf/verifier.c:7734
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
```
**Symbols:**

```
ffffffff8120c000-ffffffff8120c206: check_ld_imm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int check_ld_imm(struct bpf_verifier_env *env, struct bpf_insn *insn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff8120db60)
Location: kernel/bpf/verifier.c:8887
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
```
**Symbols:**

```
ffffffff8120db60-ffffffff8120ddee: check_ld_imm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int check_ld_imm(struct bpf_verifier_env *env, struct bpf_insn *insn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81241ed0)
Location: kernel/bpf/verifier.c:9180
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
```
**Symbols:**

```
ffffffff81241ed0-ffffffff81242184: check_ld_imm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int check_ld_imm(struct bpf_verifier_env *env, struct bpf_insn *insn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff812874d0)
Location: kernel/bpf/verifier.c:10162
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
```
**Symbols:**

```
ffffffff812874d0-ffffffff812877fe: check_ld_imm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int check_ld_imm(struct bpf_verifier_env *env, struct bpf_insn *insn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff812ddb80)
Location: kernel/bpf/verifier.c:12098
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
```
**Symbols:**

```
ffffffff812ddb80-ffffffff812dde90: check_ld_imm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int check_ld_imm(struct bpf_verifier_env *env, struct bpf_insn *insn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81308a90)
Location: kernel/bpf/verifier.c:14044
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
```
**Symbols:**

```
ffffffff81308a90-ffffffff81308d9f: check_ld_imm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int check_ld_imm(struct bpf_verifier_env *env, struct bpf_insn *insn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff8132c240)
Location: kernel/bpf/verifier.c:14991
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
```
**Symbols:**

```
ffffffff8132c240-ffffffff8132c57c: check_ld_imm (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffff800010272e00)
Location: kernel/bpf/verifier.c:5953
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:do_check
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (c04a5500)
Location: kernel/bpf/verifier.c:5953
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:do_check
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (c00000000031a7d4)
Location: kernel/bpf/verifier.c:5953
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:do_check
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffe0001abbf6)
Location: kernel/bpf/verifier.c:5953
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:do_check
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811e7c4c)
Location: kernel/bpf/verifier.c:5953
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:do_check
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811daa0c)
Location: kernel/bpf/verifier.c:5953
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:do_check
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811e5a1c)
Location: kernel/bpf/verifier.c:5953
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:do_check
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811f3de4)
Location: kernel/bpf/verifier.c:5953
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:do_check
```
</details>
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
