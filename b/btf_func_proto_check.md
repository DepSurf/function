# Function: <code>btf_func_proto_check</code>

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
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff811dc250)
Location: kernel/bpf/btf.c:2306
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_parse_type_sec
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
In kernel/bpf/btf.c (ffffffff811f1992)
Location: kernel/bpf/btf.c:2790
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_check_all_types
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
In kernel/bpf/btf.c (ffffffff811fe0a2)
Location: kernel/bpf/btf.c:2789
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_check_all_types
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int btf_func_proto_check(struct btf_verifier_env *env, const struct btf_type *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81224260)
Location: kernel/bpf/btf.c:2899
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_check_all_types
```
**Symbols:**

```
ffffffff81224260-ffffffff8122448a: btf_func_proto_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int btf_func_proto_check(struct btf_verifier_env *env, const struct btf_type *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff8122a990)
Location: kernel/bpf/btf.c:3683
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_check_all_types
```
**Symbols:**

```
ffffffff8122a990-ffffffff8122ac26: btf_func_proto_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int btf_func_proto_check(struct btf_verifier_env *env, const struct btf_type *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff8122f2d0)
Location: kernel/bpf/btf.c:3755
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_check_all_types
```
**Symbols:**

```
ffffffff8122f2d0-ffffffff8122f566: btf_func_proto_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int btf_func_proto_check(struct btf_verifier_env *env, const struct btf_type *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81268030)
Location: kernel/bpf/btf.c:3804
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_check_all_types
```
**Symbols:**

```
ffffffff81268030-ffffffff812682c6: btf_func_proto_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int btf_func_proto_check(struct btf_verifier_env *env, const struct btf_type *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff812b5320)
Location: kernel/bpf/btf.c:4305
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_check_all_types
```
**Symbols:**

```
ffffffff812b5320-ffffffff812b55fe: btf_func_proto_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int btf_func_proto_check(struct btf_verifier_env *env, const struct btf_type *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff813158e0)
Location: kernel/bpf/btf.c:4729
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_check_all_types
```
**Symbols:**

```
ffffffff813158e0-ffffffff81315c1f: btf_func_proto_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int btf_func_proto_check(struct btf_verifier_env *env, const struct btf_type *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff813458b0)
Location: kernel/bpf/btf.c:4799
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_check_all_types
```
**Symbols:**

```
ffffffff813458b0-ffffffff81345bea: btf_func_proto_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int btf_func_proto_check(struct btf_verifier_env *env, const struct btf_type *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff8136b840)
Location: kernel/bpf/btf.c:4807
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_check_all_types
```
**Symbols:**

```
ffffffff8136b840-ffffffff8136bb7a: btf_func_proto_check (STB_LOCAL)
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
In kernel/bpf/btf.c (ffff800010285024)
Location: kernel/bpf/btf.c:2789
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_check_all_types
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
In kernel/bpf/btf.c (c04b5648)
Location: kernel/bpf/btf.c:2789
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_check_all_types
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
In kernel/bpf/btf.c (c00000000032fb38)
Location: kernel/bpf/btf.c:2789
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_check_all_types
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
In kernel/bpf/btf.c (ffffffe0001ba53c)
Location: kernel/bpf/btf.c:2789
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_check_all_types
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
In kernel/bpf/btf.c (ffffffff811f66c2)
Location: kernel/bpf/btf.c:2789
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_check_all_types
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
In kernel/bpf/btf.c (ffffffff811e9412)
Location: kernel/bpf/btf.c:2789
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_check_all_types
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
In kernel/bpf/btf.c (ffffffff811f4492)
Location: kernel/bpf/btf.c:2789
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_check_all_types
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
In kernel/bpf/btf.c (ffffffff812029a2)
Location: kernel/bpf/btf.c:2789
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_check_all_types
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
