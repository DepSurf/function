# Function: <code>may_access_direct_pkt_data</code>

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
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff8118e78b)
Location: kernel/bpf/verifier.c:640
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_mem_access
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
In kernel/bpf/verifier.c (ffffffff81195845)
Location: kernel/bpf/verifier.c:707
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_mem_access
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
In kernel/bpf/verifier.c (ffffffff811a3904)
Location: kernel/bpf/verifier.c:868
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_mem_access
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
In kernel/bpf/verifier.c (ffffffff811bab45)
Location: kernel/bpf/verifier.c:1305
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_mem_access
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
In kernel/bpf/verifier.c (ffffffff811ca79f)
Location: kernel/bpf/verifier.c:1491
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_mem_access
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811d77d0)
Location: kernel/bpf/verifier.c:2238
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_mem_access
```
**Symbols:**

```
ffffffff811d77d0-ffffffff811d782e: may_access_direct_pkt_data.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811e3ec0)
Location: kernel/bpf/verifier.c:2239
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_mem_access
```
**Symbols:**

```
ffffffff811e3ec0-ffffffff811e3f1e: may_access_direct_pkt_data.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool may_access_direct_pkt_data(struct bpf_verifier_env *env, const struct bpf_call_arg_meta *meta, enum bpf_access_type t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81201ef0)
Location: kernel/bpf/verifier.c:2605
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_mem_access
```
**Symbols:**

```
ffffffff81201ef0-ffffffff81201f50: may_access_direct_pkt_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool may_access_direct_pkt_data(struct bpf_verifier_env *env, const struct bpf_call_arg_meta *meta, enum bpf_access_type t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81201960)
Location: kernel/bpf/verifier.c:2683
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_mem_access
```
**Symbols:**

```
ffffffff81201960-ffffffff812019d2: may_access_direct_pkt_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool may_access_direct_pkt_data(struct bpf_verifier_env *env, const struct bpf_call_arg_meta *meta, enum bpf_access_type t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff812028c0)
Location: kernel/bpf/verifier.c:3228
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_mem_access
```
**Symbols:**

```
ffffffff812028c0-ffffffff81202943: may_access_direct_pkt_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
bool may_access_direct_pkt_data(struct bpf_verifier_env *env, const struct bpf_call_arg_meta *meta, enum bpf_access_type t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:3303
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_mem_access
```
**Symbols:**

```
ffffffff81235ce0-ffffffff81235d5b: may_access_direct_pkt_data (STB_LOCAL)
ffffffff81cb7c05-ffffffff81cb7c25: may_access_direct_pkt_data.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool may_access_direct_pkt_data(struct bpf_verifier_env *env, const struct bpf_call_arg_meta *meta, enum bpf_access_type t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:3854
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_mem_access
```
**Symbols:**

```
ffffffff812799d0-ffffffff81279a70: may_access_direct_pkt_data (STB_LOCAL)
ffffffff81e68d8e-ffffffff81e68dba: may_access_direct_pkt_data.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
bool may_access_direct_pkt_data(struct bpf_verifier_env *env, const struct bpf_call_arg_meta *meta, enum bpf_access_type t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:4285
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_mem_access
```
**Symbols:**

```
ffffffff812cf6f0-ffffffff812cf790: may_access_direct_pkt_data (STB_LOCAL)
ffffffff8205fa29-ffffffff8205fa55: may_access_direct_pkt_data.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
bool may_access_direct_pkt_data(struct bpf_verifier_env *env, const struct bpf_call_arg_meta *meta, enum bpf_access_type t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:5205
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_kfunc_call
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:add_kfunc_call
```
**Symbols:**

```
ffffffff812f8670-ffffffff812f8710: may_access_direct_pkt_data (STB_LOCAL)
ffffffff820de9a3-ffffffff820de9cf: may_access_direct_pkt_data.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
bool may_access_direct_pkt_data(struct bpf_verifier_env *env, const struct bpf_call_arg_meta *meta, enum bpf_access_type t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:5407
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_kfunc_call
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:add_kfunc_call
```
**Symbols:**

```
ffffffff81317780-ffffffff81317820: may_access_direct_pkt_data (STB_LOCAL)
ffffffff821ba9e3-ffffffff821baa0f: may_access_direct_pkt_data.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (ffff800010266d88)
Location: kernel/bpf/verifier.c:2239
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_mem_access
```
**Symbols:**

```
ffff800010266d88-ffff800010266e44: may_access_direct_pkt_data.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool may_access_direct_pkt_data(struct bpf_verifier_env *env, const struct bpf_call_arg_meta *meta, enum bpf_access_type t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (c049812c)
Location: kernel/bpf/verifier.c:2239
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_mem_access
```
**Symbols:**

```
c049812c-c04981f4: may_access_direct_pkt_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (c00000000030c2b0)
Location: kernel/bpf/verifier.c:2239
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_mem_access
```
**Symbols:**

```
c00000000030c2b0-c00000000030c3a0: may_access_direct_pkt_data.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (ffffffe0001a22a6)
Location: kernel/bpf/verifier.c:2239
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_mem_access
```
**Symbols:**

```
ffffffe0001a22a6-ffffffe0001a233e: may_access_direct_pkt_data.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811dc4e0)
Location: kernel/bpf/verifier.c:2239
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_mem_access
```
**Symbols:**

```
ffffffff811dc4e0-ffffffff811dc53e: may_access_direct_pkt_data.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811cf2a0)
Location: kernel/bpf/verifier.c:2239
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_mem_access
```
**Symbols:**

```
ffffffff811cf2a0-ffffffff811cf2fe: may_access_direct_pkt_data.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811da2b0)
Location: kernel/bpf/verifier.c:2239
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_mem_access
```
**Symbols:**

```
ffffffff811da2b0-ffffffff811da30e: may_access_direct_pkt_data.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811e86c0)
Location: kernel/bpf/verifier.c:2239
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_mem_access
```
**Symbols:**

```
ffffffff811e86c0-ffffffff811e871e: may_access_direct_pkt_data.isra.0 (STB_LOCAL)
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
<b>Arch</b>
<ul>
</ul>
