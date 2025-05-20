# Function: <code>check_pseudo_btf_id</code>

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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int check_pseudo_btf_id(struct bpf_verifier_env *env, struct bpf_insn *insn, struct bpf_insn_aux_data *aux);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81205d50)
Location: kernel/bpf/verifier.c:9727
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:resolve_pseudo_ldimm64
```
**Symbols:**

```
ffffffff81205d50-ffffffff81205ff7: check_pseudo_btf_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int check_pseudo_btf_id(struct bpf_verifier_env *env, struct bpf_insn *insn, struct bpf_insn_aux_data *aux);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81207b80)
Location: kernel/bpf/verifier.c:10929
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:resolve_pseudo_ldimm64
```
**Symbols:**

```
ffffffff81207b80-ffffffff81207f31: check_pseudo_btf_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int check_pseudo_btf_id(struct bpf_verifier_env *env, struct bpf_insn *insn, struct bpf_insn_aux_data *aux);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff8123b410)
Location: kernel/bpf/verifier.c:11276
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:resolve_pseudo_ldimm64
```
**Symbols:**

```
ffffffff8123b410-ffffffff8123b7f9: check_pseudo_btf_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int check_pseudo_btf_id(struct bpf_verifier_env *env, struct bpf_insn *insn, struct bpf_insn_aux_data *aux);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81280f40)
Location: kernel/bpf/verifier.c:12332
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:resolve_pseudo_ldimm64
```
**Symbols:**

```
ffffffff81280f40-ffffffff81281330: check_pseudo_btf_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int check_pseudo_btf_id(struct bpf_verifier_env *env, struct bpf_insn *insn, struct bpf_insn_aux_data *aux);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff812d8cb0)
Location: kernel/bpf/verifier.c:14351
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:resolve_pseudo_ldimm64
```
**Symbols:**

```
ffffffff812d8cb0-ffffffff812d90a0: check_pseudo_btf_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int check_pseudo_btf_id(struct bpf_verifier_env *env, struct bpf_insn *insn, struct bpf_insn_aux_data *aux);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff812f7dc0)
Location: kernel/bpf/verifier.c:16562
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:resolve_pseudo_ldimm64
```
**Symbols:**

```
ffffffff812f7dc0-ffffffff812f81bb: check_pseudo_btf_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int check_pseudo_btf_id(struct bpf_verifier_env *env, struct bpf_insn *insn, struct bpf_insn_aux_data *aux);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81316260)
Location: kernel/bpf/verifier.c:17718
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:resolve_pseudo_ldimm64
```
**Symbols:**

```
ffffffff81316260-ffffffff8131665b: check_pseudo_btf_id (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
