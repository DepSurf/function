# Function: <code>btf_check_all_types</code>

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
In kernel/bpf/btf.c (ffffffff811c8fe8)
Location: kernel/bpf/btf.c:1923
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
In kernel/bpf/btf.c (ffffffff811dc136)
Location: kernel/bpf/btf.c:2574
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_parse_type_sec
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int btf_check_all_types(struct btf_verifier_env *env);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff811f1870)
Location: kernel/bpf/btf.c:3064
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_new_fd
```
**Symbols:**

```
ffffffff811f1870-ffffffff811f1c78: btf_check_all_types (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int btf_check_all_types(struct btf_verifier_env *env);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff811fdf80)
Location: kernel/bpf/btf.c:3063
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_new_fd
```
**Symbols:**

```
ffffffff811fdf80-ffffffff811fe388: btf_check_all_types (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int btf_check_all_types(struct btf_verifier_env *env);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81224490)
Location: kernel/bpf/btf.c:3173
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_parse
```
**Symbols:**

```
ffffffff81224490-ffffffff81224589: btf_check_all_types (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int btf_check_all_types(struct btf_verifier_env *env);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff8122ac30)
Location: kernel/bpf/btf.c:3957
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_parse
```
**Symbols:**

```
ffffffff8122ac30-ffffffff8122ae0e: btf_check_all_types (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int btf_check_all_types(struct btf_verifier_env *env);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff8122f570)
Location: kernel/bpf/btf.c:4030
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_parse
```
**Symbols:**

```
ffffffff8122f570-ffffffff8122f7fc: btf_check_all_types (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int btf_check_all_types(struct btf_verifier_env *env);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff812682d0)
Location: kernel/bpf/btf.c:4079
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_parse
```
**Symbols:**

```
ffffffff812682d0-ffffffff8126855c: btf_check_all_types (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int btf_check_all_types(struct btf_verifier_env *env);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff812b5600)
Location: kernel/bpf/btf.c:4586
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_parse
```
**Symbols:**

```
ffffffff812b5600-ffffffff812b57e9: btf_check_all_types (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int btf_check_all_types(struct btf_verifier_env *env);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81315c30)
Location: kernel/bpf/btf.c:5017
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_parse
```
**Symbols:**

```
ffffffff81315c30-ffffffff81315e19: btf_check_all_types (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int btf_check_all_types(struct btf_verifier_env *env);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81345c00)
Location: kernel/bpf/btf.c:5087
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_parse
```
**Symbols:**

```
ffffffff81345c00-ffffffff81345dd5: btf_check_all_types (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int btf_check_all_types(struct btf_verifier_env *env);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff8136bb90)
Location: kernel/bpf/btf.c:5095
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_parse
```
**Symbols:**

```
ffffffff8136bb90-ffffffff8136bd65: btf_check_all_types (STB_LOCAL)
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
int btf_check_all_types(struct btf_verifier_env *env);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffff800010284f08)
Location: kernel/bpf/btf.c:3063
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_new_fd
```
**Symbols:**

```
ffff800010284f08-ffff800010285308: btf_check_all_types (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int btf_check_all_types(struct btf_verifier_env *env);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (c04b5520)
Location: kernel/bpf/btf.c:3063
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_new_fd
```
**Symbols:**

```
c04b5520-c04b5970: btf_check_all_types (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int btf_check_all_types(struct btf_verifier_env *env);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (c00000000032f9d0)
Location: kernel/bpf/btf.c:3063
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_new_fd
```
**Symbols:**

```
c00000000032f9d0-c00000000032fecc: btf_check_all_types (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int btf_check_all_types(struct btf_verifier_env *env);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffe0001ba434)
Location: kernel/bpf/btf.c:3063
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_new_fd
```
**Symbols:**

```
ffffffe0001ba434-ffffffe0001ba788: btf_check_all_types (STB_LOCAL)
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
int btf_check_all_types(struct btf_verifier_env *env);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff811f65a0)
Location: kernel/bpf/btf.c:3063
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_new_fd
```
**Symbols:**

```
ffffffff811f65a0-ffffffff811f69a8: btf_check_all_types (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int btf_check_all_types(struct btf_verifier_env *env);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff811e92f0)
Location: kernel/bpf/btf.c:3063
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_new_fd
```
**Symbols:**

```
ffffffff811e92f0-ffffffff811e96f8: btf_check_all_types (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int btf_check_all_types(struct btf_verifier_env *env);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff811f4370)
Location: kernel/bpf/btf.c:3063
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_new_fd
```
**Symbols:**

```
ffffffff811f4370-ffffffff811f4778: btf_check_all_types (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int btf_check_all_types(struct btf_verifier_env *env);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81202880)
Location: kernel/bpf/btf.c:3063
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_new_fd
```
**Symbols:**

```
ffffffff81202880-ffffffff81202c88: btf_check_all_types (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
