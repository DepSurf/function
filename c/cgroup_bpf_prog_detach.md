# Function: <code>cgroup_bpf_prog_detach</code>

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
int cgroup_bpf_prog_detach(const union bpf_attr *attr, enum bpf_prog_type ptype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff811d2730)
Location: kernel/bpf/cgroup.c:446
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_detach
```
**Symbols:**

```
ffffffff811d2730-ffffffff811d27eb: cgroup_bpf_prog_detach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int cgroup_bpf_prog_detach(const union bpf_attr *attr, enum bpf_prog_type ptype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff811e24c0)
Location: kernel/bpf/cgroup.c:497
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
```
**Symbols:**

```
ffffffff811e24c0-ffffffff811e257b: cgroup_bpf_prog_detach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int cgroup_bpf_prog_detach(const union bpf_attr *attr, enum bpf_prog_type ptype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff811f9630)
Location: kernel/bpf/cgroup.c:555
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
```
**Symbols:**

```
ffffffff811f9630-ffffffff811f96eb: cgroup_bpf_prog_detach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int cgroup_bpf_prog_detach(const union bpf_attr *attr, enum bpf_prog_type ptype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff81206700)
Location: kernel/bpf/cgroup.c:565
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
```
**Symbols:**

```
ffffffff81206700-ffffffff812067bb: cgroup_bpf_prog_detach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int cgroup_bpf_prog_detach(const union bpf_attr *attr, enum bpf_prog_type ptype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff8122e1d0)
Location: kernel/bpf/cgroup.c:780
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_detach
```
**Symbols:**

```
ffffffff8122e1d0-ffffffff8122e289: cgroup_bpf_prog_detach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int cgroup_bpf_prog_detach(const union bpf_attr *attr, enum bpf_prog_type ptype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff812366f0)
Location: kernel/bpf/cgroup.c:791
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_detach
```
**Symbols:**

```
ffffffff812366f0-ffffffff812367b5: cgroup_bpf_prog_detach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int cgroup_bpf_prog_detach(const union bpf_attr *attr, enum bpf_prog_type ptype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff8123a950)
Location: kernel/bpf/cgroup.c:791
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
```
**Symbols:**

```
ffffffff8123a950-ffffffff8123aa15: cgroup_bpf_prog_detach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int cgroup_bpf_prog_detach(const union bpf_attr *attr, enum bpf_prog_type ptype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff81275530)
Location: kernel/bpf/cgroup.c:821
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__sys_bpf
```
**Symbols:**

```
ffffffff81275530-ffffffff812755f5: cgroup_bpf_prog_detach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int cgroup_bpf_prog_detach(const union bpf_attr *attr, enum bpf_prog_type ptype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff812c4eb0)
Location: kernel/bpf/cgroup.c:946
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__sys_bpf
```
**Symbols:**

```
ffffffff812c4eb0-ffffffff812c4fdc: cgroup_bpf_prog_detach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int cgroup_bpf_prog_detach(const union bpf_attr *attr, enum bpf_prog_type ptype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff8132a3b0)
Location: kernel/bpf/cgroup.c:1158
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__sys_bpf
```
**Symbols:**

```
ffffffff8132a3b0-ffffffff8132a4dc: cgroup_bpf_prog_detach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int cgroup_bpf_prog_detach(const union bpf_attr *attr, enum bpf_prog_type ptype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff8135a4f0)
Location: kernel/bpf/cgroup.c:1158
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__sys_bpf
```
**Symbols:**

```
ffffffff8135a4f0-ffffffff8135a61c: cgroup_bpf_prog_detach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int cgroup_bpf_prog_detach(const union bpf_attr *attr, enum bpf_prog_type ptype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff813830b0)
Location: kernel/bpf/cgroup.c:1159
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_detach
```
**Symbols:**

```
ffffffff813830b0-ffffffff813831dc: cgroup_bpf_prog_detach (STB_GLOBAL)
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
int cgroup_bpf_prog_detach(const union bpf_attr *attr, enum bpf_prog_type ptype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffff80001028fd68)
Location: kernel/bpf/cgroup.c:565
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
```
**Symbols:**

```
ffff80001028fd68-ffff80001028fe9c: cgroup_bpf_prog_detach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int cgroup_bpf_prog_detach(const union bpf_attr *attr, enum bpf_prog_type ptype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (c04bf440)
Location: kernel/bpf/cgroup.c:565
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
```
**Symbols:**

```
c04bf440-c04bf550: cgroup_bpf_prog_detach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int cgroup_bpf_prog_detach(const union bpf_attr *attr, enum bpf_prog_type ptype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (c00000000033c9b0)
Location: kernel/bpf/cgroup.c:565
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
```
**Symbols:**

```
c00000000033c9b0-c00000000033cb70: cgroup_bpf_prog_detach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int cgroup_bpf_prog_detach(const union bpf_attr *attr, enum bpf_prog_type ptype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffe0001c29de)
Location: kernel/bpf/cgroup.c:565
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
```
**Symbols:**

```
ffffffe0001c29de-ffffffe0001c2abc: cgroup_bpf_prog_detach (STB_GLOBAL)
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
int cgroup_bpf_prog_detach(const union bpf_attr *attr, enum bpf_prog_type ptype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff811fed20)
Location: kernel/bpf/cgroup.c:565
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
```
**Symbols:**

```
ffffffff811fed20-ffffffff811feddb: cgroup_bpf_prog_detach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int cgroup_bpf_prog_detach(const union bpf_attr *attr, enum bpf_prog_type ptype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff811f1a70)
Location: kernel/bpf/cgroup.c:565
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
```
**Symbols:**

```
ffffffff811f1a70-ffffffff811f1b2b: cgroup_bpf_prog_detach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int cgroup_bpf_prog_detach(const union bpf_attr *attr, enum bpf_prog_type ptype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff811fcaf0)
Location: kernel/bpf/cgroup.c:565
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
```
**Symbols:**

```
ffffffff811fcaf0-ffffffff811fcbab: cgroup_bpf_prog_detach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int cgroup_bpf_prog_detach(const union bpf_attr *attr, enum bpf_prog_type ptype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff8120b770)
Location: kernel/bpf/cgroup.c:565
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
```
**Symbols:**

```
ffffffff8120b770-ffffffff8120b838: cgroup_bpf_prog_detach (STB_GLOBAL)
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
