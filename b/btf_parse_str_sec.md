# Function: <code>btf_parse_str_sec</code>

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
In kernel/bpf/btf.c (ffffffff811c8c97)
Location: kernel/bpf/btf.c:1978
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
In kernel/bpf/btf.c (ffffffff811dcade)
Location: kernel/bpf/btf.c:2635
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_new_fd
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
In kernel/bpf/btf.c (ffffffff811f200f)
Location: kernel/bpf/btf.c:3125
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_new_fd
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
In kernel/bpf/btf.c (ffffffff811fe71f)
Location: kernel/bpf/btf.c:3124
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_new_fd
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int btf_parse_str_sec(struct btf_verifier_env *env);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81220680)
Location: kernel/bpf/btf.c:3234
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_parse_vmlinux
  - kernel/bpf/btf.c:btf_parse
```
**Symbols:**

```
ffffffff81220680-ffffffff812206ec: btf_parse_str_sec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int btf_parse_str_sec(struct btf_verifier_env *env);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81223700)
Location: kernel/bpf/btf.c:4020
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_parse_module
  - kernel/bpf/btf.c:btf_parse_vmlinux
  - kernel/bpf/btf.c:btf_parse
```
**Symbols:**

```
ffffffff81223700-ffffffff81223780: btf_parse_str_sec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int btf_parse_str_sec(struct btf_verifier_env *env);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff812281a0)
Location: kernel/bpf/btf.c:4093
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_parse_module
  - kernel/bpf/btf.c:btf_parse_vmlinux
  - kernel/bpf/btf.c:btf_parse
```
**Symbols:**

```
ffffffff812281a0-ffffffff81228220: btf_parse_str_sec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int btf_parse_str_sec(struct btf_verifier_env *env);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81260470)
Location: kernel/bpf/btf.c:4142
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_parse_module
  - kernel/bpf/btf.c:btf_parse_vmlinux
  - kernel/bpf/btf.c:btf_parse
```
**Symbols:**

```
ffffffff81260470-ffffffff812604f0: btf_parse_str_sec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int btf_parse_str_sec(struct btf_verifier_env *env);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff812ab3a0)
Location: kernel/bpf/btf.c:4643
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_parse_module
  - kernel/bpf/btf.c:btf_parse_vmlinux
  - kernel/bpf/btf.c:btf_parse
```
**Symbols:**

```
ffffffff812ab3a0-ffffffff812ab45b: btf_parse_str_sec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int btf_parse_str_sec(struct btf_verifier_env *env);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff8130ad20)
Location: kernel/bpf/btf.c:5074
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_parse_module
  - kernel/bpf/btf.c:btf_parse_vmlinux
  - kernel/bpf/btf.c:btf_parse
```
**Symbols:**

```
ffffffff8130ad20-ffffffff8130addb: btf_parse_str_sec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int btf_parse_str_sec(struct btf_verifier_env *env);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81339310)
Location: kernel/bpf/btf.c:5144
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_parse_module
  - kernel/bpf/btf.c:btf_parse_vmlinux
  - kernel/bpf/btf.c:btf_parse
```
**Symbols:**

```
ffffffff81339310-ffffffff813393cb: btf_parse_str_sec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int btf_parse_str_sec(struct btf_verifier_env *env);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff8135f440)
Location: kernel/bpf/btf.c:5152
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_parse_module
  - kernel/bpf/btf.c:btf_parse_vmlinux
  - kernel/bpf/btf.c:btf_parse
```
**Symbols:**

```
ffffffff8135f440-ffffffff8135f4fb: btf_parse_str_sec (STB_LOCAL)
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
In kernel/bpf/btf.c (ffff8000102857ec)
Location: kernel/bpf/btf.c:3124
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_new_fd
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
In kernel/bpf/btf.c (c04b5d7c)
Location: kernel/bpf/btf.c:3124
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_new_fd
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
In kernel/bpf/btf.c (c0000000003305e4)
Location: kernel/bpf/btf.c:3124
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_new_fd
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
In kernel/bpf/btf.c (ffffffe0001bab3e)
Location: kernel/bpf/btf.c:3124
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_new_fd
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
In kernel/bpf/btf.c (ffffffff811f6d3f)
Location: kernel/bpf/btf.c:3124
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_new_fd
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
In kernel/bpf/btf.c (ffffffff811e9a8f)
Location: kernel/bpf/btf.c:3124
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_new_fd
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
In kernel/bpf/btf.c (ffffffff811f4b0f)
Location: kernel/bpf/btf.c:3124
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_new_fd
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
In kernel/bpf/btf.c (ffffffff8120302f)
Location: kernel/bpf/btf.c:3124
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_new_fd
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
