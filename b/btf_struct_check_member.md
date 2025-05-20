# Function: <code>btf_struct_check_member</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int btf_struct_check_member(struct btf_verifier_env *env, const struct btf_type *struct_type, const struct btf_member *member, const struct btf_type *member_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff811c7300)
Location: kernel/bpf/btf.c:1491
Inline: False
```
**Symbols:**

```
ffffffff811c7300-ffffffff811c734a: btf_struct_check_member (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int btf_struct_check_member(struct btf_verifier_env *env, const struct btf_type *struct_type, const struct btf_member *member, const struct btf_type *member_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff811da140)
Location: kernel/bpf/btf.c:1801
Inline: False
```
**Symbols:**

```
ffffffff811da140-ffffffff811da18a: btf_struct_check_member (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int btf_struct_check_member(struct btf_verifier_env *env, const struct btf_type *struct_type, const struct btf_member *member, const struct btf_type *member_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff811eeff0)
Location: kernel/bpf/btf.c:2031
Inline: False
```
**Symbols:**

```
ffffffff811eeff0-ffffffff811ef03a: btf_struct_check_member (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int btf_struct_check_member(struct btf_verifier_env *env, const struct btf_type *struct_type, const struct btf_member *member, const struct btf_type *member_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff811fb730)
Location: kernel/bpf/btf.c:2031
Inline: False
```
**Symbols:**

```
ffffffff811fb730-ffffffff811fb77a: btf_struct_check_member (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int btf_struct_check_member(struct btf_verifier_env *env, const struct btf_type *struct_type, const struct btf_member *member, const struct btf_type *member_type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81222050)
Location: kernel/bpf/btf.c:2140
Inline: True
```
**Symbols:**

```
ffffffff81222050-ffffffff8122209d: btf_struct_check_member (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int btf_struct_check_member(struct btf_verifier_env *env, const struct btf_type *struct_type, const struct btf_member *member, const struct btf_type *member_type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81225610)
Location: kernel/bpf/btf.c:2864
Inline: True
```
**Symbols:**

```
ffffffff81225610-ffffffff8122565d: btf_struct_check_member (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int btf_struct_check_member(struct btf_verifier_env *env, const struct btf_type *struct_type, const struct btf_member *member, const struct btf_type *member_type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff8122a100)
Location: kernel/bpf/btf.c:2866
Inline: True
```
**Symbols:**

```
ffffffff8122a100-ffffffff8122a14a: btf_struct_check_member (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int btf_struct_check_member(struct btf_verifier_env *env, const struct btf_type *struct_type, const struct btf_member *member, const struct btf_type *member_type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81262880)
Location: kernel/bpf/btf.c:2866
Inline: True
```
**Symbols:**

```
ffffffff81262880-ffffffff812628ca: btf_struct_check_member (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int btf_struct_check_member(struct btf_verifier_env *env, const struct btf_type *struct_type, const struct btf_member *member, const struct btf_type *member_type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff812ae2c0)
Location: kernel/bpf/btf.c:3003
Inline: True
```
**Symbols:**

```
ffffffff812ae2c0-ffffffff812ae323: btf_struct_check_member (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int btf_struct_check_member(struct btf_verifier_env *env, const struct btf_type *struct_type, const struct btf_member *member, const struct btf_type *member_type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff8130e4f0)
Location: kernel/bpf/btf.c:3027
Inline: True
```
**Symbols:**

```
ffffffff8130e4f0-ffffffff8130e553: btf_struct_check_member (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int btf_struct_check_member(struct btf_verifier_env *env, const struct btf_type *struct_type, const struct btf_member *member, const struct btf_type *member_type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff8133db20)
Location: kernel/bpf/btf.c:3057
Inline: True
```
**Symbols:**

```
ffffffff8133db20-ffffffff8133db83: btf_struct_check_member (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int btf_struct_check_member(struct btf_verifier_env *env, const struct btf_type *struct_type, const struct btf_member *member, const struct btf_type *member_type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81363d90)
Location: kernel/bpf/btf.c:3058
Inline: True
```
**Symbols:**

```
ffffffff81363d90-ffffffff81363df3: btf_struct_check_member (STB_LOCAL)
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
int btf_struct_check_member(struct btf_verifier_env *env, const struct btf_type *struct_type, const struct btf_member *member, const struct btf_type *member_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffff800010281a70)
Location: kernel/bpf/btf.c:2031
Inline: False
```
**Symbols:**

```
ffff800010281a70-ffff800010281b0c: btf_struct_check_member (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int btf_struct_check_member(struct btf_verifier_env *env, const struct btf_type *struct_type, const struct btf_member *member, const struct btf_type *member_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (c04b2dec)
Location: kernel/bpf/btf.c:2031
Inline: False
```
**Symbols:**

```
c04b2dec-c04b2e50: btf_struct_check_member (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int btf_struct_check_member(struct btf_verifier_env *env, const struct btf_type *struct_type, const struct btf_member *member, const struct btf_type *member_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (c00000000032bf80)
Location: kernel/bpf/btf.c:2031
Inline: False
```
**Symbols:**

```
c00000000032bf80-c00000000032c010: btf_struct_check_member (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int btf_struct_check_member(struct btf_verifier_env *env, const struct btf_type *struct_type, const struct btf_member *member, const struct btf_type *member_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffe0001b7d38)
Location: kernel/bpf/btf.c:2031
Inline: False
```
**Symbols:**

```
ffffffe0001b7d38-ffffffe0001b7daa: btf_struct_check_member (STB_LOCAL)
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
int btf_struct_check_member(struct btf_verifier_env *env, const struct btf_type *struct_type, const struct btf_member *member, const struct btf_type *member_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff811f3d50)
Location: kernel/bpf/btf.c:2031
Inline: False
```
**Symbols:**

```
ffffffff811f3d50-ffffffff811f3d9a: btf_struct_check_member (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int btf_struct_check_member(struct btf_verifier_env *env, const struct btf_type *struct_type, const struct btf_member *member, const struct btf_type *member_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff811e6aa0)
Location: kernel/bpf/btf.c:2031
Inline: False
```
**Symbols:**

```
ffffffff811e6aa0-ffffffff811e6aea: btf_struct_check_member (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int btf_struct_check_member(struct btf_verifier_env *env, const struct btf_type *struct_type, const struct btf_member *member, const struct btf_type *member_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff811f1b20)
Location: kernel/bpf/btf.c:2031
Inline: False
```
**Symbols:**

```
ffffffff811f1b20-ffffffff811f1b6a: btf_struct_check_member (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int btf_struct_check_member(struct btf_verifier_env *env, const struct btf_type *struct_type, const struct btf_member *member, const struct btf_type *member_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81200030)
Location: kernel/bpf/btf.c:2031
Inline: False
```
**Symbols:**

```
ffffffff81200030-ffffffff8120007a: btf_struct_check_member (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
