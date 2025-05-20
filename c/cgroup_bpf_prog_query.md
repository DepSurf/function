# Function: <code>cgroup_bpf_prog_query</code>

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
int cgroup_bpf_prog_query(const union bpf_attr *attr, union bpf_attr *uattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff811d27f0)
Location: kernel/bpf/cgroup.c:468
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_query
```
**Symbols:**

```
ffffffff811d27f0-ffffffff811d286e: cgroup_bpf_prog_query (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int cgroup_bpf_prog_query(const union bpf_attr *attr, union bpf_attr *uattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff811e2580)
Location: kernel/bpf/cgroup.c:519
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
```
**Symbols:**

```
ffffffff811e2580-ffffffff811e25fe: cgroup_bpf_prog_query (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int cgroup_bpf_prog_query(const union bpf_attr *attr, union bpf_attr *uattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff811f96f0)
Location: kernel/bpf/cgroup.c:577
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
```
**Symbols:**

```
ffffffff811f96f0-ffffffff811f976e: cgroup_bpf_prog_query (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int cgroup_bpf_prog_query(const union bpf_attr *attr, union bpf_attr *uattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff812067c0)
Location: kernel/bpf/cgroup.c:587
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
```
**Symbols:**

```
ffffffff812067c0-ffffffff8120683e: cgroup_bpf_prog_query (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int cgroup_bpf_prog_query(const union bpf_attr *attr, union bpf_attr *uattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff8122e3e0)
Location: kernel/bpf/cgroup.c:924
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_query
```
**Symbols:**

```
ffffffff8122e3e0-ffffffff8122e45e: cgroup_bpf_prog_query (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int cgroup_bpf_prog_query(const union bpf_attr *attr, union bpf_attr *uattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff81236920)
Location: kernel/bpf/cgroup.c:948
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_query
```
**Symbols:**

```
ffffffff81236920-ffffffff812369ad: cgroup_bpf_prog_query (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int cgroup_bpf_prog_query(const union bpf_attr *attr, union bpf_attr *uattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff8123ab80)
Location: kernel/bpf/cgroup.c:948
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
```
**Symbols:**

```
ffffffff8123ab80-ffffffff8123ac0d: cgroup_bpf_prog_query (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int cgroup_bpf_prog_query(const union bpf_attr *attr, union bpf_attr *uattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff81275760)
Location: kernel/bpf/cgroup.c:978
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__sys_bpf
```
**Symbols:**

```
ffffffff81275760-ffffffff812757ed: cgroup_bpf_prog_query (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int cgroup_bpf_prog_query(const union bpf_attr *attr, union bpf_attr *uattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff812c5180)
Location: kernel/bpf/cgroup.c:1103
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__sys_bpf
```
**Symbols:**

```
ffffffff812c5180-ffffffff812c5248: cgroup_bpf_prog_query (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int cgroup_bpf_prog_query(const union bpf_attr *attr, union bpf_attr *uattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff8132a6a0)
Location: kernel/bpf/cgroup.c:1317
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__sys_bpf
```
**Symbols:**

```
ffffffff8132a6a0-ffffffff8132a768: cgroup_bpf_prog_query (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int cgroup_bpf_prog_query(const union bpf_attr *attr, union bpf_attr *uattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff8135a7e0)
Location: kernel/bpf/cgroup.c:1317
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__sys_bpf
```
**Symbols:**

```
ffffffff8135a7e0-ffffffff8135a8a8: cgroup_bpf_prog_query (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int cgroup_bpf_prog_query(const union bpf_attr *attr, union bpf_attr *uattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff813833d0)
Location: kernel/bpf/cgroup.c:1318
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_query
```
**Symbols:**

```
ffffffff813833d0-ffffffff81383498: cgroup_bpf_prog_query (STB_GLOBAL)
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
int cgroup_bpf_prog_query(const union bpf_attr *attr, union bpf_attr *uattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffff80001028fea0)
Location: kernel/bpf/cgroup.c:587
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
```
**Symbols:**

```
ffff80001028fea0-ffff80001028ff90: cgroup_bpf_prog_query (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int cgroup_bpf_prog_query(const union bpf_attr *attr, union bpf_attr *uattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (c04bf550)
Location: kernel/bpf/cgroup.c:587
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
```
**Symbols:**

```
c04bf550-c04bf610: cgroup_bpf_prog_query (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int cgroup_bpf_prog_query(const union bpf_attr *attr, union bpf_attr *uattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (c00000000033cb70)
Location: kernel/bpf/cgroup.c:587
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
```
**Symbols:**

```
c00000000033cb70-c00000000033ccc0: cgroup_bpf_prog_query (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int cgroup_bpf_prog_query(const union bpf_attr *attr, union bpf_attr *uattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffe0001c2abc)
Location: kernel/bpf/cgroup.c:587
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
```
**Symbols:**

```
ffffffe0001c2abc-ffffffe0001c2b78: cgroup_bpf_prog_query (STB_GLOBAL)
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
int cgroup_bpf_prog_query(const union bpf_attr *attr, union bpf_attr *uattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff811fede0)
Location: kernel/bpf/cgroup.c:587
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
```
**Symbols:**

```
ffffffff811fede0-ffffffff811fee5e: cgroup_bpf_prog_query (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int cgroup_bpf_prog_query(const union bpf_attr *attr, union bpf_attr *uattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff811f1b30)
Location: kernel/bpf/cgroup.c:587
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
```
**Symbols:**

```
ffffffff811f1b30-ffffffff811f1bae: cgroup_bpf_prog_query (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int cgroup_bpf_prog_query(const union bpf_attr *attr, union bpf_attr *uattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff811fcbb0)
Location: kernel/bpf/cgroup.c:587
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
```
**Symbols:**

```
ffffffff811fcbb0-ffffffff811fcc2e: cgroup_bpf_prog_query (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int cgroup_bpf_prog_query(const union bpf_attr *attr, union bpf_attr *uattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff8120b840)
Location: kernel/bpf/cgroup.c:587
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
```
**Symbols:**

```
ffffffff8120b840-ffffffff8120b8ca: cgroup_bpf_prog_query (STB_GLOBAL)
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
