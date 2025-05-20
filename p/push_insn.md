# Function: <code>push_insn</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81173e90)
Location: kernel/bpf/verifier.c:1438
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
```
**Symbols:**

```
ffffffff81173e90-ffffffff81173fcd: push_insn.isra.4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81182200)
Location: kernel/bpf/verifier.c:1903
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
```
**Symbols:**

```
ffffffff81182200-ffffffff8118234f: push_insn.isra.5 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff8118eaa0)
Location: kernel/bpf/verifier.c:2296
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:check_cfg
  - kernel/bpf/verifier.c:check_cfg
  - kernel/bpf/verifier.c:check_cfg
  - kernel/bpf/verifier.c:check_cfg
  - kernel/bpf/verifier.c:check_cfg
```
**Symbols:**

```
ffffffff8118eaa0-ffffffff8118ebef: push_insn.isra.10 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81194d30)
Location: kernel/bpf/verifier.c:2705
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:check_cfg
  - kernel/bpf/verifier.c:check_cfg
  - kernel/bpf/verifier.c:check_cfg
  - kernel/bpf/verifier.c:check_cfg
  - kernel/bpf/verifier.c:check_cfg
```
**Symbols:**

```
ffffffff81194d30-ffffffff81194e4e: push_insn.isra.15 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int push_insn(int t, int w, int e, struct bpf_verifier_env *env);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811a3380)
Location: kernel/bpf/verifier.c:3307
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
```
**Symbols:**

```
ffffffff811a3380-ffffffff811a34ab: push_insn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int push_insn(int t, int w, int e, struct bpf_verifier_env *env);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811b7ba0)
Location: kernel/bpf/verifier.c:4124
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
```
**Symbols:**

```
ffffffff811b7ba0-ffffffff811b7cb8: push_insn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int push_insn(int t, int w, int e, struct bpf_verifier_env *env);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811cd360)
Location: kernel/bpf/verifier.c:4836
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
```
**Symbols:**

```
ffffffff811cd360-ffffffff811cd4d9: push_insn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int push_insn(int t, int w, int e, struct bpf_verifier_env *env, bool loop_ok);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811e0100)
Location: kernel/bpf/verifier.c:6222
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
```
**Symbols:**

```
ffffffff811e0100-ffffffff811e02aa: push_insn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int push_insn(int t, int w, int e, struct bpf_verifier_env *env, bool loop_ok);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811ec8c0)
Location: kernel/bpf/verifier.c:6237
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
```
**Symbols:**

```
ffffffff811ec8c0-ffffffff811eca6a: push_insn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int push_insn(int t, int w, int e, struct bpf_verifier_env *env, bool loop_ok);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff8120eea0)
Location: kernel/bpf/verifier.c:7363
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_cfg
  - kernel/bpf/verifier.c:check_cfg
  - kernel/bpf/verifier.c:check_cfg
  - kernel/bpf/verifier.c:check_cfg
  - kernel/bpf/verifier.c:check_cfg
```
**Symbols:**

```
ffffffff8120eea0-ffffffff8120f039: push_insn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int push_insn(int t, int w, int e, struct bpf_verifier_env *env, bool loop_ok);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff8120faa0)
Location: kernel/bpf/verifier.c:8099
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:visit_insn
  - kernel/bpf/verifier.c:visit_insn
  - kernel/bpf/verifier.c:visit_insn
  - kernel/bpf/verifier.c:visit_insn
  - kernel/bpf/verifier.c:visit_insn
  - kernel/bpf/verifier.c:visit_insn
```
**Symbols:**

```
ffffffff8120faa0-ffffffff8120fc40: push_insn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int push_insn(int t, int w, int e, struct bpf_verifier_env *env, bool loop_ok);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81211420)
Location: kernel/bpf/verifier.c:9263
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:visit_insn
  - kernel/bpf/verifier.c:visit_insn
  - kernel/bpf/verifier.c:visit_insn
  - kernel/bpf/verifier.c:visit_insn
```
**Symbols:**

```
ffffffff81211420-ffffffff812115c1: push_insn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int push_insn(int t, int w, int e, struct bpf_verifier_env *env, bool loop_ok);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:9578
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:visit_insn
  - kernel/bpf/verifier.c:visit_insn
  - kernel/bpf/verifier.c:visit_insn
  - kernel/bpf/verifier.c:visit_insn
```
**Symbols:**

```
ffffffff812465f0-ffffffff812467a0: push_insn (STB_LOCAL)
ffffffff81cb89e9-ffffffff81cb89fd: push_insn.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int push_insn(int t, int w, int e, struct bpf_verifier_env *env, bool loop_ok);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:10560
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:visit_insn
  - kernel/bpf/verifier.c:visit_insn
  - kernel/bpf/verifier.c:visit_insn
  - kernel/bpf/verifier.c:visit_insn
```
**Symbols:**

```
ffffffff8128c680-ffffffff8128c85d: push_insn (STB_LOCAL)
ffffffff81e69c5f-ffffffff81e69c74: push_insn.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int push_insn(int t, int w, int e, struct bpf_verifier_env *env, bool loop_ok);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:12536
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:visit_insn
  - kernel/bpf/verifier.c:visit_insn
  - kernel/bpf/verifier.c:visit_insn
  - kernel/bpf/verifier.c:visit_insn
  - kernel/bpf/verifier.c:visit_func_call_insn
  - kernel/bpf/verifier.c:visit_func_call_insn
```
**Symbols:**

```
ffffffff812e5420-ffffffff812e5605: push_insn (STB_LOCAL)
ffffffff82060b9f-ffffffff82060bb4: push_insn.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int push_insn(int t, int w, int e, struct bpf_verifier_env *env, bool loop_ok);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:14496
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:visit_insn
  - kernel/bpf/verifier.c:visit_insn
  - kernel/bpf/verifier.c:visit_insn
  - kernel/bpf/verifier.c:visit_insn
  - kernel/bpf/verifier.c:visit_func_call_insn
  - kernel/bpf/verifier.c:visit_func_call_insn
```
**Symbols:**

```
ffffffff812fc1d0-ffffffff812fc3b5: push_insn (STB_LOCAL)
ffffffff820ded1c-ffffffff820ded31: push_insn.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int push_insn(int t, int w, int e, struct bpf_verifier_env *env);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:15439
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:visit_insn
  - kernel/bpf/verifier.c:visit_insn
  - kernel/bpf/verifier.c:visit_insn
  - kernel/bpf/verifier.c:visit_insn
  - kernel/bpf/verifier.c:visit_func_call_insn
  - kernel/bpf/verifier.c:visit_func_call_insn
```
**Symbols:**

```
ffffffff81318460-ffffffff8131863a: push_insn (STB_LOCAL)
ffffffff821bab28-ffffffff821bab3d: push_insn.cold (STB_LOCAL)
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
int push_insn(int t, int w, int e, struct bpf_verifier_env *env, bool loop_ok);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffff8000102701b0)
Location: kernel/bpf/verifier.c:6237
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
```
**Symbols:**

```
ffff8000102701b0-ffff800010270394: push_insn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int push_insn(int t, int w, int e, struct bpf_verifier_env *env, bool loop_ok);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (c04a245c)
Location: kernel/bpf/verifier.c:6237
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
```
**Symbols:**

```
c04a245c-c04a260c: push_insn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int push_insn(int t, int w, int e, struct bpf_verifier_env *env, bool loop_ok);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (c0000000003170d0)
Location: kernel/bpf/verifier.c:6237
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
```
**Symbols:**

```
c0000000003170d0-c000000000317358: push_insn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int push_insn(int t, int w, int e, struct bpf_verifier_env *env, bool loop_ok);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffe0001a98ea)
Location: kernel/bpf/verifier.c:6237
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
```
**Symbols:**

```
ffffffe0001a98ea-ffffffe0001a9a6e: push_insn (STB_LOCAL)
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
int push_insn(int t, int w, int e, struct bpf_verifier_env *env, bool loop_ok);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811e4ee0)
Location: kernel/bpf/verifier.c:6237
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
```
**Symbols:**

```
ffffffff811e4ee0-ffffffff811e508a: push_insn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int push_insn(int t, int w, int e, struct bpf_verifier_env *env, bool loop_ok);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811d7ca0)
Location: kernel/bpf/verifier.c:6237
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
```
**Symbols:**

```
ffffffff811d7ca0-ffffffff811d7e4a: push_insn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int push_insn(int t, int w, int e, struct bpf_verifier_env *env, bool loop_ok);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811e2cb0)
Location: kernel/bpf/verifier.c:6237
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
```
**Symbols:**

```
ffffffff811e2cb0-ffffffff811e2e5a: push_insn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int push_insn(int t, int w, int e, struct bpf_verifier_env *env, bool loop_ok);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811f1080)
Location: kernel/bpf/verifier.c:6237
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
```
**Symbols:**

```
ffffffff811f1080-ffffffff811f122a: push_insn (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool loop_ok</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>bool loop_ok</code>
</li>
</ul>
</details>
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
