# Function: <code>regsafe</code>

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
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
bool regsafe(struct bpf_reg_state *rold, struct bpf_reg_state *rcur, struct idpair *idmap);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811a45b0)
Location: kernel/bpf/verifier.c:3502
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
```
**Symbols:**

```
ffffffff811a45b0-ffffffff811a4765: regsafe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
bool regsafe(struct bpf_reg_state *rold, struct bpf_reg_state *rcur, struct idpair *idmap);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811b70b0)
Location: kernel/bpf/verifier.c:4331
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
```
**Symbols:**

```
ffffffff811b70b0-ffffffff811b725a: regsafe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
bool regsafe(struct bpf_reg_state *rold, struct bpf_reg_state *rcur, struct idpair *idmap);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811c6440)
Location: kernel/bpf/verifier.c:5409
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
```
**Symbols:**

```
ffffffff811c6440-ffffffff811c65d8: regsafe (STB_LOCAL)
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
In kernel/bpf/verifier.c (ffffffff811d7c80)
Location: kernel/bpf/verifier.c:6811
Inline: True
```
**Symbols:**

```
ffffffff811d7c80-ffffffff811d7e4c: regsafe.part.0 (STB_LOCAL)
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
In kernel/bpf/verifier.c (ffffffff811e4370)
Location: kernel/bpf/verifier.c:6826
Inline: True
```
**Symbols:**

```
ffffffff811e4370-ffffffff811e453c: regsafe.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81203bcc)
Location: kernel/bpf/verifier.c:7959
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:func_states_equal
  - kernel/bpf/verifier.c:stacksafe
Direct callers:
  - kernel/bpf/verifier.c:func_states_equal
  - kernel/bpf/verifier.c:stacksafe
```
**Symbols:**

```
ffffffff812038c0-ffffffff81203a8c: regsafe.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81203b5c)
Location: kernel/bpf/verifier.c:8747
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:func_states_equal
  - kernel/bpf/verifier.c:stacksafe
Direct callers:
  - kernel/bpf/verifier.c:func_states_equal
  - kernel/bpf/verifier.c:stacksafe
```
**Symbols:**

```
ffffffff81202c50-ffffffff81202df2: regsafe.part.0 (STB_LOCAL)
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
In kernel/bpf/verifier.c (ffffffff812038b0)
Location: kernel/bpf/verifier.c:9918
Inline: True
```
**Symbols:**

```
ffffffff812038b0-ffffffff81203a83: regsafe.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff8123714d)
Location: kernel/bpf/verifier.c:10249
Inline: True
```
**Symbols:**

```
ffffffff81236df0-ffffffff81237046: regsafe.part.0 (STB_LOCAL)
ffffffff81cb7c61-ffffffff81cb7ca9: regsafe.part.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool regsafe(struct bpf_verifier_env *env, struct bpf_reg_state *rold, struct bpf_reg_state *rcur, struct bpf_id_pair *idmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:11306
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:states_equal
  - kernel/bpf/verifier.c:states_equal
```
**Symbols:**

```
ffffffff8127b440-ffffffff8127b6b4: regsafe (STB_LOCAL)
ffffffff81e68e00-ffffffff81e68e48: regsafe.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
bool regsafe(struct bpf_verifier_env *env, struct bpf_reg_state *rold, struct bpf_reg_state *rcur, struct bpf_id_pair *idmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:13278
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:func_states_equal
  - kernel/bpf/verifier.c:func_states_equal
```
**Symbols:**

```
ffffffff812d34e0-ffffffff812d37c5: regsafe (STB_LOCAL)
ffffffff8205fbc3-ffffffff8205fbed: regsafe.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
bool regsafe(struct bpf_verifier_env *env, struct bpf_reg_state *rold, struct bpf_reg_state *rcur, struct bpf_idmap *idmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:15288
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:states_equal
  - kernel/bpf/verifier.c:stacksafe
```
**Symbols:**

```
ffffffff812ff5f0-ffffffff812ff86e: regsafe (STB_LOCAL)
ffffffff820def73-ffffffff820def9d: regsafe.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
bool regsafe(struct bpf_verifier_env *env, struct bpf_reg_state *rold, struct bpf_reg_state *rcur, struct bpf_idmap *idmap, bool exact);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:16329
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:states_equal
  - kernel/bpf/verifier.c:stacksafe
```
**Symbols:**

```
ffffffff8131f0f0-ffffffff8131f375: regsafe (STB_LOCAL)
ffffffff821bb050-ffffffff821bb07a: regsafe.cold (STB_LOCAL)
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
In kernel/bpf/verifier.c (ffff8000102677d0)
Location: kernel/bpf/verifier.c:6826
Inline: True
```
**Symbols:**

```
ffff8000102677d0-ffff8000102679d4: regsafe.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (c0499860)
Location: kernel/bpf/verifier.c:6826
Inline: True
```
**Symbols:**

```
c0499860-c0499a5c: regsafe.part.0 (STB_LOCAL)
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
In kernel/bpf/verifier.c (c00000000030d000)
Location: kernel/bpf/verifier.c:6826
Inline: True
```
**Symbols:**

```
c00000000030d000-c00000000030d330: regsafe.part.0 (STB_LOCAL)
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
In kernel/bpf/verifier.c (ffffffe0001a2ca4)
Location: kernel/bpf/verifier.c:6826
Inline: True
```
**Symbols:**

```
ffffffe0001a2ca4-ffffffe0001a2e1e: regsafe.part.0 (STB_LOCAL)
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
In kernel/bpf/verifier.c (ffffffff811dc990)
Location: kernel/bpf/verifier.c:6826
Inline: True
```
**Symbols:**

```
ffffffff811dc990-ffffffff811dcb5c: regsafe.part.0 (STB_LOCAL)
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
In kernel/bpf/verifier.c (ffffffff811cf750)
Location: kernel/bpf/verifier.c:6826
Inline: True
```
**Symbols:**

```
ffffffff811cf750-ffffffff811cf91c: regsafe.part.0 (STB_LOCAL)
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
In kernel/bpf/verifier.c (ffffffff811da760)
Location: kernel/bpf/verifier.c:6826
Inline: True
```
**Symbols:**

```
ffffffff811da760-ffffffff811da92c: regsafe.part.0 (STB_LOCAL)
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
In kernel/bpf/verifier.c (ffffffff811e8b70)
Location: kernel/bpf/verifier.c:6826
Inline: True
```
**Symbols:**

```
ffffffff811e8b70-ffffffff811e8d3c: regsafe.part.0 (STB_LOCAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct bpf_id_pair *idmap</code> ➡️ <code>struct bpf_idmap *idmap</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool exact</code>
</li>
</ul>
</details>
</li>
</ul>
