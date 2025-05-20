# Function: <code>check_ld_abs</code>

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
In kernel/bpf/verifier.c (ffffffff81174fcd)
Location: kernel/bpf/verifier.c:1338
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
In kernel/bpf/verifier.c (ffffffff81183640)
Location: kernel/bpf/verifier.c:1802
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
In kernel/bpf/verifier.c (ffffffff81190290)
Location: kernel/bpf/verifier.c:2195
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
In kernel/bpf/verifier.c (ffffffff81196c28)
Location: kernel/bpf/verifier.c:2608
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
In kernel/bpf/verifier.c (ffffffff811a7216)
Location: kernel/bpf/verifier.c:3168
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
In kernel/bpf/verifier.c (ffffffff811bd30e)
Location: kernel/bpf/verifier.c:3967
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
In kernel/bpf/verifier.c (ffffffff811ce83d)
Location: kernel/bpf/verifier.c:4669
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
In kernel/bpf/verifier.c (ffffffff811e3492)
Location: kernel/bpf/verifier.c:6017
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
In kernel/bpf/verifier.c (ffffffff811efcdf)
Location: kernel/bpf/verifier.c:6027
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
int check_ld_abs(struct bpf_verifier_env *env, struct bpf_insn *insn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81212050)
Location: kernel/bpf/verifier.c:7102
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
```
**Symbols:**

```
ffffffff81212050-ffffffff81212280: check_ld_abs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int check_ld_abs(struct bpf_verifier_env *env, struct bpf_insn *insn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81212da0)
Location: kernel/bpf/verifier.c:7830
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
```
**Symbols:**

```
ffffffff81212da0-ffffffff81212fc0: check_ld_abs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int check_ld_abs(struct bpf_verifier_env *env, struct bpf_insn *insn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81215250)
Location: kernel/bpf/verifier.c:9001
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
```
**Symbols:**

```
ffffffff81215250-ffffffff8121546f: check_ld_abs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int check_ld_abs(struct bpf_verifier_env *env, struct bpf_insn *insn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff8124b7d0)
Location: kernel/bpf/verifier.c:9299
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
```
**Symbols:**

```
ffffffff8124b7d0-ffffffff8124ba41: check_ld_abs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int check_ld_abs(struct bpf_verifier_env *env, struct bpf_insn *insn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff8128b760)
Location: kernel/bpf/verifier.c:10281
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
```
**Symbols:**

```
ffffffff8128b760-ffffffff8128b9c0: check_ld_abs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int check_ld_abs(struct bpf_verifier_env *env, struct bpf_insn *insn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:12217
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
```
**Symbols:**

```
ffffffff812e3fc0-ffffffff812e4248: check_ld_abs (STB_LOCAL)
ffffffff82060b18-ffffffff82060b33: check_ld_abs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int check_ld_abs(struct bpf_verifier_env *env, struct bpf_insn *insn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:14163
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
```
**Symbols:**

```
ffffffff8130ed30-ffffffff8130efb7: check_ld_abs (STB_LOCAL)
ffffffff820dff36-ffffffff820dff51: check_ld_abs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int check_ld_abs(struct bpf_verifier_env *env, struct bpf_insn *insn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:15110
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
```
**Symbols:**

```
ffffffff8132ef50-ffffffff8132f265: check_ld_abs (STB_LOCAL)
ffffffff821bc295-ffffffff821bc2b0: check_ld_abs.cold (STB_LOCAL)
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
In kernel/bpf/verifier.c (ffff8000102733c8)
Location: kernel/bpf/verifier.c:6027
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
In kernel/bpf/verifier.c (c04a5c1c)
Location: kernel/bpf/verifier.c:6027
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
In kernel/bpf/verifier.c (c00000000031ae80)
Location: kernel/bpf/verifier.c:6027
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
In kernel/bpf/verifier.c (ffffffe0001abab8)
Location: kernel/bpf/verifier.c:6027
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
In kernel/bpf/verifier.c (ffffffff811e82ff)
Location: kernel/bpf/verifier.c:6027
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
In kernel/bpf/verifier.c (ffffffff811db0bf)
Location: kernel/bpf/verifier.c:6027
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
In kernel/bpf/verifier.c (ffffffff811e60cf)
Location: kernel/bpf/verifier.c:6027
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
In kernel/bpf/verifier.c (ffffffff811f448d)
Location: kernel/bpf/verifier.c:6027
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
