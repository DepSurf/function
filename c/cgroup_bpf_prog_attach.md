# Function: <code>cgroup_bpf_prog_attach</code>

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
int cgroup_bpf_prog_attach(const union bpf_attr *attr, enum bpf_prog_type ptype, struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff811d26a0)
Location: kernel/bpf/cgroup.c:430
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_attach
```
**Symbols:**

```
ffffffff811d26a0-ffffffff811d2725: cgroup_bpf_prog_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int cgroup_bpf_prog_attach(const union bpf_attr *attr, enum bpf_prog_type ptype, struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff811e2430)
Location: kernel/bpf/cgroup.c:481
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
```
**Symbols:**

```
ffffffff811e2430-ffffffff811e24b5: cgroup_bpf_prog_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int cgroup_bpf_prog_attach(const union bpf_attr *attr, enum bpf_prog_type ptype, struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff811f95a0)
Location: kernel/bpf/cgroup.c:539
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
```
**Symbols:**

```
ffffffff811f95a0-ffffffff811f9625: cgroup_bpf_prog_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int cgroup_bpf_prog_attach(const union bpf_attr *attr, enum bpf_prog_type ptype, struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff81206670)
Location: kernel/bpf/cgroup.c:549
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
```
**Symbols:**

```
ffffffff81206670-ffffffff812066f5: cgroup_bpf_prog_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int cgroup_bpf_prog_attach(const union bpf_attr *attr, enum bpf_prog_type ptype, struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff8122e0a0)
Location: kernel/bpf/cgroup.c:751
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_attach
```
**Symbols:**

```
ffffffff8122e0a0-ffffffff8122e1cb: cgroup_bpf_prog_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int cgroup_bpf_prog_attach(const union bpf_attr *attr, enum bpf_prog_type ptype, struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff812365a0)
Location: kernel/bpf/cgroup.c:762
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_attach
```
**Symbols:**

```
ffffffff812365a0-ffffffff812366e3: cgroup_bpf_prog_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int cgroup_bpf_prog_attach(const union bpf_attr *attr, enum bpf_prog_type ptype, struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff8123a800)
Location: kernel/bpf/cgroup.c:762
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_attach
```
**Symbols:**

```
ffffffff8123a800-ffffffff8123a943: cgroup_bpf_prog_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int cgroup_bpf_prog_attach(const union bpf_attr *attr, enum bpf_prog_type ptype, struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff812753e0)
Location: kernel/bpf/cgroup.c:792
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_attach
```
**Symbols:**

```
ffffffff812753e0-ffffffff81275523: cgroup_bpf_prog_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int cgroup_bpf_prog_attach(const union bpf_attr *attr, enum bpf_prog_type ptype, struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff812c4ce0)
Location: kernel/bpf/cgroup.c:917
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_attach
```
**Symbols:**

```
ffffffff812c4ce0-ffffffff812c4eaf: cgroup_bpf_prog_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int cgroup_bpf_prog_attach(const union bpf_attr *attr, enum bpf_prog_type ptype, struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff8132a1d0)
Location: kernel/bpf/cgroup.c:1129
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_attach
```
**Symbols:**

```
ffffffff8132a1d0-ffffffff8132a39f: cgroup_bpf_prog_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int cgroup_bpf_prog_attach(const union bpf_attr *attr, enum bpf_prog_type ptype, struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff8135a310)
Location: kernel/bpf/cgroup.c:1129
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_attach
```
**Symbols:**

```
ffffffff8135a310-ffffffff8135a4dd: cgroup_bpf_prog_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int cgroup_bpf_prog_attach(const union bpf_attr *attr, enum bpf_prog_type ptype, struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff81382ed0)
Location: kernel/bpf/cgroup.c:1130
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_attach
```
**Symbols:**

```
ffffffff81382ed0-ffffffff8138309d: cgroup_bpf_prog_attach (STB_GLOBAL)
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
int cgroup_bpf_prog_attach(const union bpf_attr *attr, enum bpf_prog_type ptype, struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffff80001028fc78)
Location: kernel/bpf/cgroup.c:549
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
```
**Symbols:**

```
ffff80001028fc78-ffff80001028fd68: cgroup_bpf_prog_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int cgroup_bpf_prog_attach(const union bpf_attr *attr, enum bpf_prog_type ptype, struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (c04bf380)
Location: kernel/bpf/cgroup.c:549
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
```
**Symbols:**

```
c04bf380-c04bf440: cgroup_bpf_prog_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int cgroup_bpf_prog_attach(const union bpf_attr *attr, enum bpf_prog_type ptype, struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (c00000000033c860)
Location: kernel/bpf/cgroup.c:549
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
```
**Symbols:**

```
c00000000033c860-c00000000033c9b0: cgroup_bpf_prog_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int cgroup_bpf_prog_attach(const union bpf_attr *attr, enum bpf_prog_type ptype, struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffe0001c291c)
Location: kernel/bpf/cgroup.c:549
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
```
**Symbols:**

```
ffffffe0001c291c-ffffffe0001c29de: cgroup_bpf_prog_attach (STB_GLOBAL)
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
int cgroup_bpf_prog_attach(const union bpf_attr *attr, enum bpf_prog_type ptype, struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff811fec90)
Location: kernel/bpf/cgroup.c:549
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
```
**Symbols:**

```
ffffffff811fec90-ffffffff811fed15: cgroup_bpf_prog_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int cgroup_bpf_prog_attach(const union bpf_attr *attr, enum bpf_prog_type ptype, struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff811f19e0)
Location: kernel/bpf/cgroup.c:549
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
```
**Symbols:**

```
ffffffff811f19e0-ffffffff811f1a65: cgroup_bpf_prog_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int cgroup_bpf_prog_attach(const union bpf_attr *attr, enum bpf_prog_type ptype, struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff811fca60)
Location: kernel/bpf/cgroup.c:549
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
```
**Symbols:**

```
ffffffff811fca60-ffffffff811fcae5: cgroup_bpf_prog_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int cgroup_bpf_prog_attach(const union bpf_attr *attr, enum bpf_prog_type ptype, struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff8120b6d0)
Location: kernel/bpf/cgroup.c:549
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
```
**Symbols:**

```
ffffffff8120b6d0-ffffffff8120b761: cgroup_bpf_prog_attach (STB_GLOBAL)
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
