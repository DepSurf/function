# Function: <code>adjust_subprog_starts_after_remove</code>

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
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:8145
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:verifier_remove_insns
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
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:8160
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:verifier_remove_insns
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int adjust_subprog_starts_after_remove(struct bpf_verifier_env *env, u32 off, u32 cnt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81202a00)
Location: kernel/bpf/verifier.c:9274
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:verifier_remove_insns
```
**Symbols:**

```
ffffffff81202a00-ffffffff81202bac: adjust_subprog_starts_after_remove (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int adjust_subprog_starts_after_remove(struct bpf_verifier_env *env, u32 off, u32 cnt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81202710)
Location: kernel/bpf/verifier.c:10204
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:verifier_remove_insns
```
**Symbols:**

```
ffffffff81202710-ffffffff812028b9: adjust_subprog_starts_after_remove (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int adjust_subprog_starts_after_remove(struct bpf_verifier_env *env, u32 off, u32 cnt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81203420)
Location: kernel/bpf/verifier.c:11469
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:verifier_remove_insns
```
**Symbols:**

```
ffffffff81203420-ffffffff812035ce: adjust_subprog_starts_after_remove (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int adjust_subprog_starts_after_remove(struct bpf_verifier_env *env, u32 off, u32 cnt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81235470)
Location: kernel/bpf/verifier.c:11852
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:verifier_remove_insns
```
**Symbols:**

```
ffffffff81235470-ffffffff812357c7: adjust_subprog_starts_after_remove (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int adjust_subprog_starts_after_remove(struct bpf_verifier_env *env, u32 off, u32 cnt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81279180)
Location: kernel/bpf/verifier.c:12911
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:verifier_remove_insns
```
**Symbols:**

```
ffffffff81279180-ffffffff812794af: adjust_subprog_starts_after_remove (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int adjust_subprog_starts_after_remove(struct bpf_verifier_env *env, u32 off, u32 cnt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff812cfe10)
Location: kernel/bpf/verifier.c:14888
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:verifier_remove_insns
```
**Symbols:**

```
ffffffff812cfe10-ffffffff812d013f: adjust_subprog_starts_after_remove (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int adjust_subprog_starts_after_remove(struct bpf_verifier_env *env, u32 off, u32 cnt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:17105
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:verifier_remove_insns
```
**Symbols:**

```
ffffffff812f9dc0-ffffffff812fa1b8: adjust_subprog_starts_after_remove (STB_LOCAL)
ffffffff820dec79-ffffffff820decc4: adjust_subprog_starts_after_remove.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int adjust_subprog_starts_after_remove(struct bpf_verifier_env *env, u32 off, u32 cnt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:18259
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:verifier_remove_insns
```
**Symbols:**

```
ffffffff813196c0-ffffffff81319af1: adjust_subprog_starts_after_remove (STB_LOCAL)
ffffffff821bad14-ffffffff821bad5f: adjust_subprog_starts_after_remove.cold (STB_LOCAL)
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
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:8160
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:verifier_remove_insns
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
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:8160
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:verifier_remove_insns
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
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:8160
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:verifier_remove_insns
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
In kernel/bpf/verifier.c (ffffffe0001a1e8a)
Location: kernel/bpf/verifier.c:8160
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:verifier_remove_insns
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
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:8160
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:verifier_remove_insns
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
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:8160
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:verifier_remove_insns
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
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:8160
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:verifier_remove_insns
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
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:8160
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:verifier_remove_insns
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
