# Function: <code>cgroup_dev_is_valid_access</code>

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
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
bool cgroup_dev_is_valid_access(int off, int size, enum bpf_access_type type, struct bpf_insn_access_aux *info);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff811b2620)
Location: kernel/bpf/cgroup.c:567
Inline: True
```
**Symbols:**

```
ffffffff811b2620-ffffffff811b2672: cgroup_dev_is_valid_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
bool cgroup_dev_is_valid_access(int off, int size, enum bpf_access_type type, const struct bpf_prog *prog, struct bpf_insn_access_aux *info);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff811d1ca0)
Location: kernel/bpf/cgroup.c:665
Inline: True
```
**Symbols:**

```
ffffffff811d1ca0-ffffffff811d1cf1: cgroup_dev_is_valid_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
bool cgroup_dev_is_valid_access(int off, int size, enum bpf_access_type type, const struct bpf_prog *prog, struct bpf_insn_access_aux *info);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff811e19f0)
Location: kernel/bpf/cgroup.c:727
Inline: True
```
**Symbols:**

```
ffffffff811e19f0-ffffffff811e1a3f: cgroup_dev_is_valid_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
bool cgroup_dev_is_valid_access(int off, int size, enum bpf_access_type type, const struct bpf_prog *prog, struct bpf_insn_access_aux *info);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff811f7ab0)
Location: kernel/bpf/cgroup.c:812
Inline: True
```
**Symbols:**

```
ffffffff811f7ab0-ffffffff811f7aff: cgroup_dev_is_valid_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
bool cgroup_dev_is_valid_access(int off, int size, enum bpf_access_type type, const struct bpf_prog *prog, struct bpf_insn_access_aux *info);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff81204a50)
Location: kernel/bpf/cgroup.c:822
Inline: True
```
**Symbols:**

```
ffffffff81204a50-ffffffff81204a9f: cgroup_dev_is_valid_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool cgroup_dev_is_valid_access(int off, int size, enum bpf_access_type type, const struct bpf_prog *prog, struct bpf_insn_access_aux *info);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff8122c8d0)
Location: kernel/bpf/cgroup.c:1144
Inline: True
```
**Symbols:**

```
ffffffff8122c8d0-ffffffff8122c91f: cgroup_dev_is_valid_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool cgroup_dev_is_valid_access(int off, int size, enum bpf_access_type type, const struct bpf_prog *prog, struct bpf_insn_access_aux *info);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff81234d50)
Location: kernel/bpf/cgroup.c:1168
Inline: True
```
**Symbols:**

```
ffffffff81234d50-ffffffff81234d9f: cgroup_dev_is_valid_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool cgroup_dev_is_valid_access(int off, int size, enum bpf_access_type type, const struct bpf_prog *prog, struct bpf_insn_access_aux *info);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff812386c0)
Location: kernel/bpf/cgroup.c:1172
Inline: True
```
**Symbols:**

```
ffffffff812386c0-ffffffff8123870f: cgroup_dev_is_valid_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
bool cgroup_dev_is_valid_access(int off, int size, enum bpf_access_type type, const struct bpf_prog *prog, struct bpf_insn_access_aux *info);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff81272ca0)
Location: kernel/bpf/cgroup.c:1202
Inline: True
```
**Symbols:**

```
ffffffff81272ca0-ffffffff81272cef: cgroup_dev_is_valid_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool cgroup_dev_is_valid_access(int off, int size, enum bpf_access_type type, const struct bpf_prog *prog, struct bpf_insn_access_aux *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff812c1770)
Location: kernel/bpf/cgroup.c:1383
Inline: False
```
**Symbols:**

```
ffffffff812c1770-ffffffff812c17e2: cgroup_dev_is_valid_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool cgroup_dev_is_valid_access(int off, int size, enum bpf_access_type type, const struct bpf_prog *prog, struct bpf_insn_access_aux *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff81325de0)
Location: kernel/bpf/cgroup.c:1622
Inline: False
```
**Symbols:**

```
ffffffff81325de0-ffffffff81325e52: cgroup_dev_is_valid_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool cgroup_dev_is_valid_access(int off, int size, enum bpf_access_type type, const struct bpf_prog *prog, struct bpf_insn_access_aux *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff81355fb0)
Location: kernel/bpf/cgroup.c:1622
Inline: False
```
**Symbols:**

```
ffffffff81355fb0-ffffffff81356022: cgroup_dev_is_valid_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool cgroup_dev_is_valid_access(int off, int size, enum bpf_access_type type, const struct bpf_prog *prog, struct bpf_insn_access_aux *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff8137eae0)
Location: kernel/bpf/cgroup.c:1637
Inline: False
```
**Symbols:**

```
ffffffff8137eae0-ffffffff8137eb52: cgroup_dev_is_valid_access (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
bool cgroup_dev_is_valid_access(int off, int size, enum bpf_access_type type, const struct bpf_prog *prog, struct bpf_insn_access_aux *info);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffff80001028ce90)
Location: kernel/bpf/cgroup.c:822
Inline: True
```
**Symbols:**

```
ffff80001028ce90-ffff80001028cf34: cgroup_dev_is_valid_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
bool cgroup_dev_is_valid_access(int off, int size, enum bpf_access_type type, const struct bpf_prog *prog, struct bpf_insn_access_aux *info);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (c04bce18)
Location: kernel/bpf/cgroup.c:822
Inline: True
```
**Symbols:**

```
c04bce18-c04bcea8: cgroup_dev_is_valid_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
bool cgroup_dev_is_valid_access(int off, int size, enum bpf_access_type type, const struct bpf_prog *prog, struct bpf_insn_access_aux *info);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (c000000000339560)
Location: kernel/bpf/cgroup.c:822
Inline: True
```
**Symbols:**

```
c000000000339560-c0000000003395e0: cgroup_dev_is_valid_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
bool cgroup_dev_is_valid_access(int off, int size, enum bpf_access_type type, const struct bpf_prog *prog, struct bpf_insn_access_aux *info);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffe0001c0f80)
Location: kernel/bpf/cgroup.c:822
Inline: True
```
**Symbols:**

```
ffffffe0001c0f80-ffffffe0001c1008: cgroup_dev_is_valid_access (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
bool cgroup_dev_is_valid_access(int off, int size, enum bpf_access_type type, const struct bpf_prog *prog, struct bpf_insn_access_aux *info);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff811fd070)
Location: kernel/bpf/cgroup.c:822
Inline: True
```
**Symbols:**

```
ffffffff811fd070-ffffffff811fd0bf: cgroup_dev_is_valid_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
bool cgroup_dev_is_valid_access(int off, int size, enum bpf_access_type type, const struct bpf_prog *prog, struct bpf_insn_access_aux *info);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff811efdc0)
Location: kernel/bpf/cgroup.c:822
Inline: True
```
**Symbols:**

```
ffffffff811efdc0-ffffffff811efe0f: cgroup_dev_is_valid_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
bool cgroup_dev_is_valid_access(int off, int size, enum bpf_access_type type, const struct bpf_prog *prog, struct bpf_insn_access_aux *info);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff811fae40)
Location: kernel/bpf/cgroup.c:822
Inline: True
```
**Symbols:**

```
ffffffff811fae40-ffffffff811fae8f: cgroup_dev_is_valid_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
bool cgroup_dev_is_valid_access(int off, int size, enum bpf_access_type type, const struct bpf_prog *prog, struct bpf_insn_access_aux *info);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff812099b0)
Location: kernel/bpf/cgroup.c:822
Inline: True
```
**Symbols:**

```
ffffffff812099b0-ffffffff812099ff: cgroup_dev_is_valid_access (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct bpf_prog *prog</code>
</li>
<li>
<b>Param reordered. </b>
<code>off, size, type, info</code> ➡️ <code>off, size, type, prog, info</code>
</li>
</ul>
</details>
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
