# Function: <code>bpf_prog_get_target_btf</code>

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
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct btf *bpf_prog_get_target_btf(const struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81224b45)
Location: kernel/bpf/btf.c:3662
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_ctx_access
Direct callers:
  - kernel/bpf/verifier.c:check_attach_btf_id
```
**Symbols:**

```
ffffffff81224af0-ffffffff81224b1a: bpf_prog_get_target_btf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct btf *bpf_prog_get_target_btf(const struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff8122b4a4)
Location: kernel/bpf/btf.c:4559
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_ctx_access
```
**Symbols:**

```
ffffffff8122b450-ffffffff8122b479: bpf_prog_get_target_btf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct btf *bpf_prog_get_target_btf(const struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff8122feae)
Location: kernel/bpf/btf.c:4630
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_ctx_access
```
**Symbols:**

```
ffffffff8122fe50-ffffffff8122fe79: bpf_prog_get_target_btf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct btf *bpf_prog_get_target_btf(const struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81268b5e)
Location: kernel/bpf/btf.c:4678
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_ctx_access
```
**Symbols:**

```
ffffffff81268b00-ffffffff81268b29: bpf_prog_get_target_btf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct btf *bpf_prog_get_target_btf(const struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff812b5e6d)
Location: kernel/bpf/btf.c:5197
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_ctx_access
```
**Symbols:**

```
ffffffff812b5e00-ffffffff812b5e39: bpf_prog_get_target_btf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct btf *bpf_prog_get_target_btf(const struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81316cde)
Location: kernel/bpf/btf.c:5785
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_ctx_access
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_get_info_by_fd
```
**Symbols:**

```
ffffffff81316c60-ffffffff81316c99: bpf_prog_get_target_btf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct btf *bpf_prog_get_target_btf(const struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81346bce)
Location: kernel/bpf/btf.c:5863
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_ctx_access
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_get_info_by_fd
```
**Symbols:**

```
ffffffff81346b50-ffffffff81346b89: bpf_prog_get_target_btf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct btf *bpf_prog_get_target_btf(const struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff8136cfbe)
Location: kernel/bpf/btf.c:6033
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_ctx_access
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_get_info_by_fd
```
**Symbols:**

```
ffffffff8136cf40-ffffffff8136cf79: bpf_prog_get_target_btf (STB_GLOBAL)
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
