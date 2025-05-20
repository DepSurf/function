# Function: <code>btf_parse_hdr</code>

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
In kernel/bpf/btf.c (ffffffff811c893a)
Location: kernel/bpf/btf.c:2070
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
In kernel/bpf/btf.c (ffffffff811dc89f)
Location: kernel/bpf/btf.c:2727
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_new_fd
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int btf_parse_hdr(struct btf_verifier_env *env);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff811ef600)
Location: kernel/bpf/btf.c:3217
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_new_fd
```
**Symbols:**

```
ffffffff811ef600-ffffffff811ef9df: btf_parse_hdr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int btf_parse_hdr(struct btf_verifier_env *env);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff811fbd20)
Location: kernel/bpf/btf.c:3216
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_new_fd
```
**Symbols:**

```
ffffffff811fbd20-ffffffff811fc0ff: btf_parse_hdr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int btf_parse_hdr(struct btf_verifier_env *env);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81220eb0)
Location: kernel/bpf/btf.c:3326
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_parse_vmlinux
  - kernel/bpf/btf.c:btf_parse
```
**Symbols:**

```
ffffffff81220eb0-ffffffff8122107a: btf_parse_hdr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int btf_parse_hdr(struct btf_verifier_env *env);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81223dd0)
Location: kernel/bpf/btf.c:4117
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_parse_module
  - kernel/bpf/btf.c:btf_parse_vmlinux
  - kernel/bpf/btf.c:btf_parse
```
**Symbols:**

```
ffffffff81223dd0-ffffffff81223fa8: btf_parse_hdr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int btf_parse_hdr(struct btf_verifier_env *env);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81228360)
Location: kernel/bpf/btf.c:4190
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_parse_module
  - kernel/bpf/btf.c:btf_parse_vmlinux
  - kernel/bpf/btf.c:btf_parse
```
**Symbols:**

```
ffffffff81228360-ffffffff81228752: btf_parse_hdr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int btf_parse_hdr(struct btf_verifier_env *env);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81260630)
Location: kernel/bpf/btf.c:4239
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_parse_module
  - kernel/bpf/btf.c:btf_parse_vmlinux
  - kernel/bpf/btf.c:btf_parse
```
**Symbols:**

```
ffffffff81260630-ffffffff81260a22: btf_parse_hdr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int btf_parse_hdr(struct btf_verifier_env *env);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff812ab630)
Location: kernel/bpf/btf.c:4740
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_parse_module
  - kernel/bpf/btf.c:btf_parse_vmlinux
  - kernel/bpf/btf.c:btf_parse
```
**Symbols:**

```
ffffffff812ab630-ffffffff812ab9fc: btf_parse_hdr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int btf_parse_hdr(struct btf_verifier_env *env);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff8130b040)
Location: kernel/bpf/btf.c:5171
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_parse_module
  - kernel/bpf/btf.c:btf_parse_vmlinux
  - kernel/bpf/btf.c:btf_parse
```
**Symbols:**

```
ffffffff8130b040-ffffffff8130b40c: btf_parse_hdr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int btf_parse_hdr(struct btf_verifier_env *env);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81339960)
Location: kernel/bpf/btf.c:5241
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_parse_module
  - kernel/bpf/btf.c:btf_parse_vmlinux
  - kernel/bpf/btf.c:btf_parse
```
**Symbols:**

```
ffffffff81339960-ffffffff81339cfd: btf_parse_hdr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int btf_parse_hdr(struct btf_verifier_env *env);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff8135fa90)
Location: kernel/bpf/btf.c:5249
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_parse_module
  - kernel/bpf/btf.c:btf_parse_vmlinux
  - kernel/bpf/btf.c:btf_parse
```
**Symbols:**

```
ffffffff8135fa90-ffffffff8135fe2d: btf_parse_hdr (STB_LOCAL)
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
int btf_parse_hdr(struct btf_verifier_env *env);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffff800010282250)
Location: kernel/bpf/btf.c:3216
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_new_fd
```
**Symbols:**

```
ffff800010282250-ffff8000102825f0: btf_parse_hdr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int btf_parse_hdr(struct btf_verifier_env *env);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (c04b1eb0)
Location: kernel/bpf/btf.c:3216
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_new_fd
```
**Symbols:**

```
c04b1eb0-c04b222c: btf_parse_hdr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int btf_parse_hdr(struct btf_verifier_env *env);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (c00000000032c860)
Location: kernel/bpf/btf.c:3216
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_new_fd
```
**Symbols:**

```
c00000000032c860-c00000000032cc88: btf_parse_hdr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int btf_parse_hdr(struct btf_verifier_env *env);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffe0001b8382)
Location: kernel/bpf/btf.c:3216
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_new_fd
```
**Symbols:**

```
ffffffe0001b8382-ffffffe0001b86a4: btf_parse_hdr (STB_LOCAL)
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
int btf_parse_hdr(struct btf_verifier_env *env);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff811f4340)
Location: kernel/bpf/btf.c:3216
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_new_fd
```
**Symbols:**

```
ffffffff811f4340-ffffffff811f471f: btf_parse_hdr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int btf_parse_hdr(struct btf_verifier_env *env);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff811e7090)
Location: kernel/bpf/btf.c:3216
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_new_fd
```
**Symbols:**

```
ffffffff811e7090-ffffffff811e746f: btf_parse_hdr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int btf_parse_hdr(struct btf_verifier_env *env);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff811f2110)
Location: kernel/bpf/btf.c:3216
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_new_fd
```
**Symbols:**

```
ffffffff811f2110-ffffffff811f24ef: btf_parse_hdr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int btf_parse_hdr(struct btf_verifier_env *env);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81200620)
Location: kernel/bpf/btf.c:3216
Inline: False
Direct callers:
  - kernel/bpf/btf.c:btf_new_fd
```
**Symbols:**

```
ffffffff81200620-ffffffff812009ff: btf_parse_hdr (STB_LOCAL)
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
