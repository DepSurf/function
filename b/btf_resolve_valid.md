# Function: <code>btf_resolve_valid</code>

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
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff811c91c1)
Location: kernel/bpf/btf.c:1890
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_new_fd
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
In kernel/bpf/btf.c (ffffffff811dbd64)
Location: kernel/bpf/btf.c:2508
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_resolve
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
In kernel/bpf/btf.c (ffffffff811f1704)
Location: kernel/bpf/btf.c:2994
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_resolve
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
In kernel/bpf/btf.c (ffffffff811fde14)
Location: kernel/bpf/btf.c:2993
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_resolve
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff812240f0)
Location: kernel/bpf/btf.c:3103
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_resolve
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool btf_resolve_valid(struct btf_verifier_env *env, const struct btf_type *t, u32 type_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff8122a660)
Location: kernel/bpf/btf.c:3887
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_resolve
```
**Symbols:**

```
ffffffff8122a660-ffffffff8122a865: btf_resolve_valid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool btf_resolve_valid(struct btf_verifier_env *env, const struct btf_type *t, u32 type_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff8122efa0)
Location: kernel/bpf/btf.c:3960
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_resolve
```
**Symbols:**

```
ffffffff8122efa0-ffffffff8122f1a4: btf_resolve_valid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool btf_resolve_valid(struct btf_verifier_env *env, const struct btf_type *t, u32 type_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81267ca0)
Location: kernel/bpf/btf.c:4009
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_resolve
```
**Symbols:**

```
ffffffff81267ca0-ffffffff81267ea4: btf_resolve_valid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool btf_resolve_valid(struct btf_verifier_env *env, const struct btf_type *t, u32 type_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff812b4ec0)
Location: kernel/bpf/btf.c:4512
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_resolve
```
**Symbols:**

```
ffffffff812b4ec0-ffffffff812b5183: btf_resolve_valid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool btf_resolve_valid(struct btf_verifier_env *env, const struct btf_type *t, u32 type_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81315460)
Location: kernel/bpf/btf.c:4943
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_resolve
```
**Symbols:**

```
ffffffff81315460-ffffffff81315723: btf_resolve_valid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool btf_resolve_valid(struct btf_verifier_env *env, const struct btf_type *t, u32 type_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81345410)
Location: kernel/bpf/btf.c:5013
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_resolve
```
**Symbols:**

```
ffffffff81345410-ffffffff813456f3: btf_resolve_valid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool btf_resolve_valid(struct btf_verifier_env *env, const struct btf_type *t, u32 type_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff8136b3a0)
Location: kernel/bpf/btf.c:5021
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_resolve
```
**Symbols:**

```
ffffffff8136b3a0-ffffffff8136b683: btf_resolve_valid (STB_LOCAL)
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
In kernel/bpf/btf.c (ffff800010284d80)
Location: kernel/bpf/btf.c:2993
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_resolve
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
In kernel/bpf/btf.c (c04b539c)
Location: kernel/bpf/btf.c:2993
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_resolve
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
In kernel/bpf/btf.c (c00000000032f804)
Location: kernel/bpf/btf.c:2993
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_resolve
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
In kernel/bpf/btf.c (ffffffe0001ba2f2)
Location: kernel/bpf/btf.c:2993
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_resolve
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
In kernel/bpf/btf.c (ffffffff811f6434)
Location: kernel/bpf/btf.c:2993
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_resolve
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
In kernel/bpf/btf.c (ffffffff811e9184)
Location: kernel/bpf/btf.c:2993
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_resolve
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
In kernel/bpf/btf.c (ffffffff811f4204)
Location: kernel/bpf/btf.c:2993
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_resolve
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
In kernel/bpf/btf.c (ffffffff81202714)
Location: kernel/bpf/btf.c:2993
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_resolve
```
</details>
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
