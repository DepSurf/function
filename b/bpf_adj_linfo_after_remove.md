# Function: <code>bpf_adj_linfo_after_remove</code>

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
In kernel/bpf/verifier.c (ffffffff811d73a7)
Location: kernel/bpf/verifier.c:8201
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
In kernel/bpf/verifier.c (ffffffff811e3a07)
Location: kernel/bpf/verifier.c:8216
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
int bpf_adj_linfo_after_remove(struct bpf_verifier_env *env, u32 off, u32 cnt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81202bb0)
Location: kernel/bpf/verifier.c:9330
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:verifier_remove_insns
```
**Symbols:**

```
ffffffff81202bb0-ffffffff81202d67: bpf_adj_linfo_after_remove (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int bpf_adj_linfo_after_remove(struct bpf_verifier_env *env, u32 off, u32 cnt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff812028c0)
Location: kernel/bpf/verifier.c:10260
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:verifier_remove_insns
```
**Symbols:**

```
ffffffff812028c0-ffffffff81202a77: bpf_adj_linfo_after_remove (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int bpf_adj_linfo_after_remove(struct bpf_verifier_env *env, u32 off, u32 cnt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff812035d0)
Location: kernel/bpf/verifier.c:11525
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:verifier_remove_insns
```
**Symbols:**

```
ffffffff812035d0-ffffffff81203777: bpf_adj_linfo_after_remove (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int bpf_adj_linfo_after_remove(struct bpf_verifier_env *env, u32 off, u32 cnt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff812357d0)
Location: kernel/bpf/verifier.c:11908
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:verifier_remove_insns
```
**Symbols:**

```
ffffffff812357d0-ffffffff81235a8c: bpf_adj_linfo_after_remove (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int bpf_adj_linfo_after_remove(struct bpf_verifier_env *env, u32 off, u32 cnt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff812794b0)
Location: kernel/bpf/verifier.c:12967
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:verifier_remove_insns
```
**Symbols:**

```
ffffffff812794b0-ffffffff81279783: bpf_adj_linfo_after_remove (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int bpf_adj_linfo_after_remove(struct bpf_verifier_env *env, u32 off, u32 cnt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff812d0150)
Location: kernel/bpf/verifier.c:14944
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:verifier_remove_insns
```
**Symbols:**

```
ffffffff812d0150-ffffffff812d0423: bpf_adj_linfo_after_remove (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int bpf_adj_linfo_after_remove(struct bpf_verifier_env *env, u32 off, u32 cnt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff812fa1d0)
Location: kernel/bpf/verifier.c:17161
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:verifier_remove_insns
```
**Symbols:**

```
ffffffff812fa1d0-ffffffff812fa4cd: bpf_adj_linfo_after_remove (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int bpf_adj_linfo_after_remove(struct bpf_verifier_env *env, u32 off, u32 cnt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81319b10)
Location: kernel/bpf/verifier.c:18315
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:verifier_remove_insns
```
**Symbols:**

```
ffffffff81319b10-ffffffff81319e0c: bpf_adj_linfo_after_remove (STB_LOCAL)
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
In kernel/bpf/verifier.c (ffff800010266884)
Location: kernel/bpf/verifier.c:8216
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
In kernel/bpf/verifier.c (c04993ac)
Location: kernel/bpf/verifier.c:8216
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
In kernel/bpf/verifier.c (c00000000030bc94)
Location: kernel/bpf/verifier.c:8216
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
In kernel/bpf/verifier.c (ffffffe0001a1f20)
Location: kernel/bpf/verifier.c:8216
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
In kernel/bpf/verifier.c (ffffffff811dc027)
Location: kernel/bpf/verifier.c:8216
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
In kernel/bpf/verifier.c (ffffffff811cede7)
Location: kernel/bpf/verifier.c:8216
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
In kernel/bpf/verifier.c (ffffffff811d9df7)
Location: kernel/bpf/verifier.c:8216
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
In kernel/bpf/verifier.c (ffffffff811e8207)
Location: kernel/bpf/verifier.c:8216
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
