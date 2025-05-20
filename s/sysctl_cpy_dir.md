# Function: <code>sysctl_cpy_dir</code>

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
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff811f7d80)
Location: kernel/bpf/cgroup.c:1126
Inline: True
Direct callers:
  - kernel/bpf/cgroup.c:bpf_sysctl_get_name
```
**Symbols:**

```
ffffffff811f7d80-ffffffff811f7e28: sysctl_cpy_dir.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff81204d20)
Location: kernel/bpf/cgroup.c:1145
Inline: True
Direct callers:
  - kernel/bpf/cgroup.c:bpf_sysctl_get_name
```
**Symbols:**

```
ffffffff81204d20-ffffffff81204dc8: sysctl_cpy_dir.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
ssize_t sysctl_cpy_dir(const struct ctl_dir *dir, char **bufp, size_t *lenp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff8122c770)
Location: kernel/bpf/cgroup.c:1466
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:bpf_sysctl_get_name
  - kernel/bpf/cgroup.c:sysctl_cpy_dir
```
**Symbols:**

```
ffffffff8122c770-ffffffff8122c815: sysctl_cpy_dir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
ssize_t sysctl_cpy_dir(const struct ctl_dir *dir, char **bufp, size_t *lenp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/cgroup.c (0)
Location: kernel/bpf/cgroup.c:1496
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:bpf_sysctl_get_name
  - kernel/bpf/cgroup.c:sysctl_cpy_dir
```
**Symbols:**

```
ffffffff81234ba0-ffffffff81234c96: sysctl_cpy_dir (STB_LOCAL)
ffffffff81be6612-ffffffff81be661e: sysctl_cpy_dir.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
ssize_t sysctl_cpy_dir(const struct ctl_dir *dir, char **bufp, size_t *lenp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/cgroup.c (0)
Location: kernel/bpf/cgroup.c:1582
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:bpf_sysctl_get_name
  - kernel/bpf/cgroup.c:sysctl_cpy_dir
```
**Symbols:**

```
ffffffff81238510-ffffffff81238605: sysctl_cpy_dir (STB_LOCAL)
ffffffff81bd8312-ffffffff81bd831e: sysctl_cpy_dir.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
ssize_t sysctl_cpy_dir(const struct ctl_dir *dir, char **bufp, size_t *lenp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/cgroup.c (0)
Location: kernel/bpf/cgroup.c:1612
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:bpf_sysctl_get_name
  - kernel/bpf/cgroup.c:sysctl_cpy_dir
```
**Symbols:**

```
ffffffff81272af0-ffffffff81272be5: sysctl_cpy_dir (STB_LOCAL)
ffffffff81cb973b-ffffffff81cb9747: sysctl_cpy_dir.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
ssize_t sysctl_cpy_dir(const struct ctl_dir *dir, char **bufp, size_t *lenp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/cgroup.c (0)
Location: kernel/bpf/cgroup.c:1744
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:bpf_sysctl_get_name
  - kernel/bpf/cgroup.c:sysctl_cpy_dir
```
**Symbols:**

```
ffffffff812c23b0-ffffffff812c24c6: sysctl_cpy_dir (STB_LOCAL)
ffffffff81e6ab83-ffffffff81e6ab8f: sysctl_cpy_dir.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ssize_t sysctl_cpy_dir(const struct ctl_dir *dir, char **bufp, size_t *lenp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff813264e0)
Location: kernel/bpf/cgroup.c:1983
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:bpf_sysctl_get_name
  - kernel/bpf/cgroup.c:sysctl_cpy_dir
```
**Symbols:**

```
ffffffff813264e0-ffffffff81326602: sysctl_cpy_dir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ssize_t sysctl_cpy_dir(const struct ctl_dir *dir, char **bufp, size_t *lenp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff81356830)
Location: kernel/bpf/cgroup.c:2001
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:bpf_sysctl_get_name
  - kernel/bpf/cgroup.c:sysctl_cpy_dir
```
**Symbols:**

```
ffffffff81356830-ffffffff81356952: sysctl_cpy_dir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ssize_t sysctl_cpy_dir(const struct ctl_dir *dir, char **bufp, size_t *lenp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff8137f360)
Location: kernel/bpf/cgroup.c:2019
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:bpf_sysctl_get_name
  - kernel/bpf/cgroup.c:sysctl_cpy_dir
```
**Symbols:**

```
ffffffff8137f360-ffffffff8137f482: sysctl_cpy_dir (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/cgroup.c (ffff80001028d348)
Location: kernel/bpf/cgroup.c:1145
Inline: True
Direct callers:
  - kernel/bpf/cgroup.c:bpf_sysctl_get_name
```
**Symbols:**

```
ffff80001028d348-ffff80001028d444: sysctl_cpy_dir.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
ssize_t sysctl_cpy_dir(const struct ctl_dir *dir, char **bufp, size_t *lenp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (c04bcc5c)
Location: kernel/bpf/cgroup.c:1145
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:bpf_sysctl_get_name
  - kernel/bpf/cgroup.c:sysctl_cpy_dir
```
**Symbols:**

```
c04bcc5c-c04bcd2c: sysctl_cpy_dir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/cgroup.c (c000000000339a20)
Location: kernel/bpf/cgroup.c:1145
Inline: True
Direct callers:
  - kernel/bpf/cgroup.c:bpf_sysctl_get_name
```
**Symbols:**

```
c000000000339a20-c000000000339b68: sysctl_cpy_dir.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffe0001c13a6)
Location: kernel/bpf/cgroup.c:1145
Inline: True
Direct callers:
  - kernel/bpf/cgroup.c:bpf_sysctl_get_name
```
**Symbols:**

```
ffffffe0001c13a6-ffffffe0001c1468: sysctl_cpy_dir.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff811fd340)
Location: kernel/bpf/cgroup.c:1145
Inline: True
Direct callers:
  - kernel/bpf/cgroup.c:bpf_sysctl_get_name
```
**Symbols:**

```
ffffffff811fd340-ffffffff811fd3e8: sysctl_cpy_dir.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff811f0090)
Location: kernel/bpf/cgroup.c:1145
Inline: True
Direct callers:
  - kernel/bpf/cgroup.c:bpf_sysctl_get_name
```
**Symbols:**

```
ffffffff811f0090-ffffffff811f0138: sysctl_cpy_dir.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff811fb110)
Location: kernel/bpf/cgroup.c:1145
Inline: True
Direct callers:
  - kernel/bpf/cgroup.c:bpf_sysctl_get_name
```
**Symbols:**

```
ffffffff811fb110-ffffffff811fb1b8: sysctl_cpy_dir.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff81209c80)
Location: kernel/bpf/cgroup.c:1145
Inline: True
Direct callers:
  - kernel/bpf/cgroup.c:bpf_sysctl_get_name
```
**Symbols:**

```
ffffffff81209c80-ffffffff81209d28: sysctl_cpy_dir.isra.0 (STB_LOCAL)
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
<b>Arch</b>
<ul>
</ul>
