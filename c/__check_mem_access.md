# Function: <code>__check_mem_access</code>

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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __check_mem_access(struct bpf_verifier_env *env, int regno, int off, int size, u32 mem_size, bool zero_size_allowed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81207800)
Location: kernel/bpf/verifier.c:2481
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_packet_access
  - kernel/bpf/verifier.c:check_mem_region_access
  - kernel/bpf/verifier.c:check_mem_region_access
```
**Symbols:**

```
ffffffff81207800-ffffffff812078c3: __check_mem_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __check_mem_access(struct bpf_verifier_env *env, int regno, int off, int size, u32 mem_size, bool zero_size_allowed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff812080f0)
Location: kernel/bpf/verifier.c:2554
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_packet_access
  - kernel/bpf/verifier.c:check_mem_region_access
  - kernel/bpf/verifier.c:check_mem_region_access
```
**Symbols:**

```
ffffffff812080f0-ffffffff812081b3: __check_mem_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __check_mem_access(struct bpf_verifier_env *env, int regno, int off, int size, u32 mem_size, bool zero_size_allowed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81205eb0)
Location: kernel/bpf/verifier.c:3095
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_packet_access
  - kernel/bpf/verifier.c:check_mem_region_access
  - kernel/bpf/verifier.c:check_mem_region_access
```
**Symbols:**

```
ffffffff81205eb0-ffffffff81205fa2: __check_mem_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __check_mem_access(struct bpf_verifier_env *env, int regno, int off, int size, u32 mem_size, bool zero_size_allowed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81238ce0)
Location: kernel/bpf/verifier.c:3161
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_packet_access
  - kernel/bpf/verifier.c:check_mem_region_access
  - kernel/bpf/verifier.c:check_mem_region_access
```
**Symbols:**

```
ffffffff81238ce0-ffffffff81238e26: __check_mem_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int __check_mem_access(struct bpf_verifier_env *env, int regno, int off, int size, u32 mem_size, bool zero_size_allowed);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff8127d350)
Location: kernel/bpf/verifier.c:3524
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:check_packet_access
  - kernel/bpf/verifier.c:check_mem_region_access
  - kernel/bpf/verifier.c:check_mem_region_access
```
**Symbols:**

```
ffffffff8127d350-ffffffff8127d47a: __check_mem_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int __check_mem_access(struct bpf_verifier_env *env, int regno, int off, int size, u32 mem_size, bool zero_size_allowed);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff812d59a0)
Location: kernel/bpf/verifier.c:3966
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:check_packet_access
  - kernel/bpf/verifier.c:check_mem_region_access
  - kernel/bpf/verifier.c:check_mem_region_access
```
**Symbols:**

```
ffffffff812d59a0-ffffffff812d5aca: __check_mem_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int __check_mem_access(struct bpf_verifier_env *env, int regno, int off, int size, u32 mem_size, bool zero_size_allowed);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff812fa780)
Location: kernel/bpf/verifier.c:4851
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:check_packet_access
  - kernel/bpf/verifier.c:check_mem_region_access
  - kernel/bpf/verifier.c:check_mem_region_access
```
**Symbols:**

```
ffffffff812fa780-ffffffff812fa8aa: __check_mem_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int __check_mem_access(struct bpf_verifier_env *env, int regno, int off, int size, u32 mem_size, bool zero_size_allowed);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff8131a030)
Location: kernel/bpf/verifier.c:5009
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:check_packet_access
  - kernel/bpf/verifier.c:check_mem_region_access
  - kernel/bpf/verifier.c:check_mem_region_access
```
**Symbols:**

```
ffffffff8131a030-ffffffff8131a15a: __check_mem_access (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
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
