# Function: <code>security_bpf_prog</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int security_bpf_prog(struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813c74b0)
Location: security/security.c:2457
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_prog_get_type_path
```
**Symbols:**

```
ffffffff813c74b0-ffffffff813c74f9: security_bpf_prog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int security_bpf_prog(struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813f6b30)
Location: security/security.c:1770
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_prog_get_type_path
```
**Symbols:**

```
ffffffff813f6b30-ffffffff813f6b6a: security_bpf_prog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int security_bpf_prog(struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814125e0)
Location: security/security.c:2530
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_prog_get_type_path
```
**Symbols:**

```
ffffffff814125e0-ffffffff8141261a: security_bpf_prog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int security_bpf_prog(struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8143ffb0)
Location: security/security.c:2547
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_prog_get_type_path
```
**Symbols:**

```
ffffffff8143ffb0-ffffffff8143fff1: security_bpf_prog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int security_bpf_prog(struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81459820)
Location: security/security.c:2586
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_prog_get_type_path
```
**Symbols:**

```
ffffffff81459820-ffffffff8145985a: security_bpf_prog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int security_bpf_prog(struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814ac930)
Location: security/security.c:2957
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/inode.c:bpf_prog_get_type_path
```
**Symbols:**

```
ffffffff814ac930-ffffffff814ac96a: security_bpf_prog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int security_bpf_prog(struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814c9f30)
Location: security/security.c:2975
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/inode.c:bpf_prog_get_type_path
```
**Symbols:**

```
ffffffff814c9f30-ffffffff814c9f6a: security_bpf_prog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int security_bpf_prog(struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814d0560)
Location: security/security.c:3038
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/inode.c:bpf_prog_get_type_path
```
**Symbols:**

```
ffffffff814d0560-ffffffff814d059a: security_bpf_prog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int security_bpf_prog(struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81529290)
Location: security/security.c:3046
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/inode.c:bpf_prog_get_type_path
```
**Symbols:**

```
ffffffff81529290-ffffffff815292ca: security_bpf_prog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int security_bpf_prog(struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff815be8e0)
Location: security/security.c:3124
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/inode.c:bpf_prog_get_type_path
```
**Symbols:**

```
ffffffff815be8e0-ffffffff815be92d: security_bpf_prog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int security_bpf_prog(struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8166ab80)
Location: security/security.c:3104
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/inode.c:bpf_prog_get_type_path
```
**Symbols:**

```
ffffffff8166ab80-ffffffff8166abcd: security_bpf_prog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int security_bpf_prog(struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff816a32e0)
Location: security/security.c:5526
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/inode.c:bpf_prog_get_type_path
```
**Symbols:**

```
ffffffff816a32e0-ffffffff816a332d: security_bpf_prog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int security_bpf_prog(struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff816dfd60)
Location: security/security.c:5667
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:bpf_prog_load
  - kernel/bpf/inode.c:bpf_prog_get_type_path
```
**Symbols:**

```
ffffffff816dfd60-ffffffff816dfdad: security_bpf_prog (STB_GLOBAL)
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
int security_bpf_prog(struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffff800010545a20)
Location: security/security.c:2586
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_prog_get_type_path
```
**Symbols:**

```
ffff800010545a20-ffff800010545a70: security_bpf_prog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int security_bpf_prog(struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c06fb878)
Location: security/security.c:2586
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_prog_get_type_path
```
**Symbols:**

```
c06fb878-c06fb8cc: security_bpf_prog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int security_bpf_prog(struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c00000000069c160)
Location: security/security.c:2586
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_prog_get_type_path
```
**Symbols:**

```
c00000000069c160-c00000000069c208: security_bpf_prog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int security_bpf_prog(struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffe0003a1648)
Location: security/security.c:2586
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_prog_get_type_path
```
**Symbols:**

```
ffffffe0003a1648-ffffffe0003a1684: security_bpf_prog (STB_GLOBAL)
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
int security_bpf_prog(struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81451e00)
Location: security/security.c:2586
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_prog_get_type_path
```
**Symbols:**

```
ffffffff81451e00-ffffffff81451e3a: security_bpf_prog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int security_bpf_prog(struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81442850)
Location: security/security.c:2586
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_prog_get_type_path
```
**Symbols:**

```
ffffffff81442850-ffffffff8144288a: security_bpf_prog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int security_bpf_prog(struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8144dea0)
Location: security/security.c:2586
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_prog_get_type_path
```
**Symbols:**

```
ffffffff8144dea0-ffffffff8144deda: security_bpf_prog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int security_bpf_prog(struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81465270)
Location: security/security.c:2586
Inline: False
Direct callers:
  - kernel/bpf/inode.c:bpf_prog_get_type_path
```
**Symbols:**

```
ffffffff81465270-ffffffff814652aa: security_bpf_prog (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
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
