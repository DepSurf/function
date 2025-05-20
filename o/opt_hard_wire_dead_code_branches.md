# Function: <code>opt_hard_wire_dead_code_branches</code>

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
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811e4e7b)
Location: kernel/bpf/verifier.c:8332
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
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
In kernel/bpf/verifier.c (ffffffff811f16db)
Location: kernel/bpf/verifier.c:8347
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void opt_hard_wire_dead_code_branches(struct bpf_verifier_env *env);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff812028f0)
Location: kernel/bpf/verifier.c:9461
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:bpf_check
```
**Symbols:**

```
ffffffff812028f0-ffffffff812029fa: opt_hard_wire_dead_code_branches (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void opt_hard_wire_dead_code_branches(struct bpf_verifier_env *env);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81202600)
Location: kernel/bpf/verifier.c:10391
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:bpf_check
```
**Symbols:**

```
ffffffff81202600-ffffffff81202705: opt_hard_wire_dead_code_branches (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81217a8b)
Location: kernel/bpf/verifier.c:11657
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff8124e119)
Location: kernel/bpf/verifier.c:12040
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void opt_hard_wire_dead_code_branches(struct bpf_verifier_env *env);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:13099
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:bpf_check
```
**Symbols:**

```
ffffffff81279790-ffffffff812798b9: opt_hard_wire_dead_code_branches (STB_LOCAL)
ffffffff81e68d4f-ffffffff81e68d7a: opt_hard_wire_dead_code_branches.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void opt_hard_wire_dead_code_branches(struct bpf_verifier_env *env);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:15076
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:bpf_check
```
**Symbols:**

```
ffffffff812cfce0-ffffffff812cfdfe: opt_hard_wire_dead_code_branches (STB_LOCAL)
ffffffff8205faa1-ffffffff8205facc: opt_hard_wire_dead_code_branches.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void opt_hard_wire_dead_code_branches(struct bpf_verifier_env *env);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:17293
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:bpf_check
```
**Symbols:**

```
ffffffff812f9c90-ffffffff812f9dae: opt_hard_wire_dead_code_branches (STB_LOCAL)
ffffffff820dec4e-ffffffff820dec79: opt_hard_wire_dead_code_branches.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void opt_hard_wire_dead_code_branches(struct bpf_verifier_env *env);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:18447
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:bpf_check
```
**Symbols:**

```
ffffffff81319560-ffffffff813196a5: opt_hard_wire_dead_code_branches (STB_LOCAL)
ffffffff821bace7-ffffffff821bad14: opt_hard_wire_dead_code_branches.cold (STB_LOCAL)
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
In kernel/bpf/verifier.c (ffff800010274df0)
Location: kernel/bpf/verifier.c:8347
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
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
In kernel/bpf/verifier.c (c04a7434)
Location: kernel/bpf/verifier.c:8347
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
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
In kernel/bpf/verifier.c (c00000000031cc54)
Location: kernel/bpf/verifier.c:8347
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
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
In kernel/bpf/verifier.c (ffffffe0001ad618)
Location: kernel/bpf/verifier.c:8347
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
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
In kernel/bpf/verifier.c (ffffffff811e9cfb)
Location: kernel/bpf/verifier.c:8347
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
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
In kernel/bpf/verifier.c (ffffffff811dcabb)
Location: kernel/bpf/verifier.c:8347
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
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
In kernel/bpf/verifier.c (ffffffff811e7acb)
Location: kernel/bpf/verifier.c:8347
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
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
In kernel/bpf/verifier.c (ffffffff811f5e7b)
Location: kernel/bpf/verifier.c:8347
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
