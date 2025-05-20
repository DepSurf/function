# Function: <code>sysctl_func_proto</code>

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
In <code>5.0</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
const struct bpf_func_proto *sysctl_func_proto(enum bpf_func_id func_id, const struct bpf_prog *prog);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff811f7d10)
Location: kernel/bpf/cgroup.c:1275
Inline: False
```
**Symbols:**

```
ffffffff811f7d10-ffffffff811f7d31: sysctl_func_proto (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
const struct bpf_func_proto *sysctl_func_proto(enum bpf_func_id func_id, const struct bpf_prog *prog);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff81204cb0)
Location: kernel/bpf/cgroup.c:1294
Inline: False
```
**Symbols:**

```
ffffffff81204cb0-ffffffff81204cd1: sysctl_func_proto (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
const struct bpf_func_proto *sysctl_func_proto(enum bpf_func_id func_id, const struct bpf_prog *prog);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff8122cf30)
Location: kernel/bpf/cgroup.c:1615
Inline: False
```
**Symbols:**

```
ffffffff8122cf30-ffffffff8122cf86: sysctl_func_proto (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
const struct bpf_func_proto *sysctl_func_proto(enum bpf_func_id func_id, const struct bpf_prog *prog);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff812353f0)
Location: kernel/bpf/cgroup.c:1645
Inline: False
```
**Symbols:**

```
ffffffff812353f0-ffffffff81235446: sysctl_func_proto (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
const struct bpf_func_proto *sysctl_func_proto(enum bpf_func_id func_id, const struct bpf_prog *prog);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff81238b70)
Location: kernel/bpf/cgroup.c:1731
Inline: False
```
**Symbols:**

```
ffffffff81238b70-ffffffff81238bc6: sysctl_func_proto (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
const struct bpf_func_proto *sysctl_func_proto(enum bpf_func_id func_id, const struct bpf_prog *prog);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff81272e30)
Location: kernel/bpf/cgroup.c:1761
Inline: False
```
**Symbols:**

```
ffffffff81272e30-ffffffff81272ed3: sysctl_func_proto (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
const struct bpf_func_proto *sysctl_func_proto(enum bpf_func_id func_id, const struct bpf_prog *prog);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff812c26e0)
Location: kernel/bpf/cgroup.c:1893
Inline: False
```
**Symbols:**

```
ffffffff812c26e0-ffffffff812c27c3: sysctl_func_proto (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
const struct bpf_func_proto *sysctl_func_proto(enum bpf_func_id func_id, const struct bpf_prog *prog);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff813293d0)
Location: kernel/bpf/cgroup.c:2132
Inline: True
```
**Symbols:**

```
ffffffff813293d0-ffffffff813295b9: sysctl_func_proto (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
const struct bpf_func_proto *sysctl_func_proto(enum bpf_func_id func_id, const struct bpf_prog *prog);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff813596b0)
Location: kernel/bpf/cgroup.c:2150
Inline: True
```
**Symbols:**

```
ffffffff813596b0-ffffffff813597ca: sysctl_func_proto (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
const struct bpf_func_proto *sysctl_func_proto(enum bpf_func_id func_id, const struct bpf_prog *prog);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff81382260)
Location: kernel/bpf/cgroup.c:2168
Inline: True
```
**Symbols:**

```
ffffffff81382260-ffffffff8138237a: sysctl_func_proto (STB_LOCAL)
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
const struct bpf_func_proto *sysctl_func_proto(enum bpf_func_id func_id, const struct bpf_prog *prog);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffff80001028d278)
Location: kernel/bpf/cgroup.c:1294
Inline: False
```
**Symbols:**

```
ffff80001028d278-ffff80001028d2c8: sysctl_func_proto (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
const struct bpf_func_proto *sysctl_func_proto(enum bpf_func_id func_id, const struct bpf_prog *prog);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (c04bd21c)
Location: kernel/bpf/cgroup.c:1294
Inline: False
```
**Symbols:**

```
c04bd21c-c04bd254: sysctl_func_proto (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
const struct bpf_func_proto *sysctl_func_proto(enum bpf_func_id func_id, const struct bpf_prog *prog);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (c000000000339970)
Location: kernel/bpf/cgroup.c:1294
Inline: False
```
**Symbols:**

```
c000000000339970-c0000000003399b4: sysctl_func_proto (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
const struct bpf_func_proto *sysctl_func_proto(enum bpf_func_id func_id, const struct bpf_prog *prog);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffe0001c12fa)
Location: kernel/bpf/cgroup.c:1294
Inline: False
```
**Symbols:**

```
ffffffe0001c12fa-ffffffe0001c134c: sysctl_func_proto (STB_LOCAL)
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
const struct bpf_func_proto *sysctl_func_proto(enum bpf_func_id func_id, const struct bpf_prog *prog);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff811fd2d0)
Location: kernel/bpf/cgroup.c:1294
Inline: False
```
**Symbols:**

```
ffffffff811fd2d0-ffffffff811fd2f1: sysctl_func_proto (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
const struct bpf_func_proto *sysctl_func_proto(enum bpf_func_id func_id, const struct bpf_prog *prog);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff811f0020)
Location: kernel/bpf/cgroup.c:1294
Inline: False
```
**Symbols:**

```
ffffffff811f0020-ffffffff811f0041: sysctl_func_proto (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
const struct bpf_func_proto *sysctl_func_proto(enum bpf_func_id func_id, const struct bpf_prog *prog);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff811fb0a0)
Location: kernel/bpf/cgroup.c:1294
Inline: False
```
**Symbols:**

```
ffffffff811fb0a0-ffffffff811fb0c1: sysctl_func_proto (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
const struct bpf_func_proto *sysctl_func_proto(enum bpf_func_id func_id, const struct bpf_prog *prog);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff81209c10)
Location: kernel/bpf/cgroup.c:1294
Inline: False
```
**Symbols:**

```
ffffffff81209c10-ffffffff81209c31: sysctl_func_proto (STB_LOCAL)
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
