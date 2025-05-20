# Function: <code>bpf_link_inc</code>

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
void bpf_link_inc(struct bpf_link *link);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff812013a1)
Location: kernel/bpf/syscall.c:2300
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_link_get_from_fd
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_do_get
```
**Symbols:**

```
ffffffff81200cd0-ffffffff81200cdf: bpf_link_inc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void bpf_link_inc(struct bpf_link *link);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff81200c91)
Location: kernel/bpf/syscall.c:2316
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_link_get_from_fd
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_do_get
```
**Symbols:**

```
ffffffff812001a0-ffffffff812001af: bpf_link_inc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void bpf_link_inc(struct bpf_link *link);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff812016e1)
Location: kernel/bpf/syscall.c:2324
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_link_get_from_fd
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_get_user
```
**Symbols:**

```
ffffffff81200b50-ffffffff81200b5f: bpf_link_inc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void bpf_link_inc(struct bpf_link *link);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff81233651)
Location: kernel/bpf/syscall.c:2434
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_link_get_from_fd
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_get_user
```
**Symbols:**

```
ffffffff812328c0-ffffffff812328cf: bpf_link_inc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void bpf_link_inc(struct bpf_link *link);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff8126f301)
Location: kernel/bpf/syscall.c:2682
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_link_get_from_fd
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_get_user
```
**Symbols:**

```
ffffffff81275ce0-ffffffff81275cf5: bpf_link_inc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void bpf_link_inc(struct bpf_link *link);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff812c4bf1)
Location: kernel/bpf/syscall.c:2716
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_link_get_from_fd
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/trampoline.c:bpf_trampoline_link_cgroup_shim
```
**Symbols:**

```
ffffffff812cbdf0-ffffffff812cbe05: bpf_link_inc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void bpf_link_inc(struct bpf_link *link);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff812ebd14)
Location: kernel/bpf/syscall.c:2829
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_link_get_from_fd
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/trampoline.c:bpf_trampoline_link_cgroup_shim
```
**Symbols:**

```
ffffffff812f3760-ffffffff812f3775: bpf_link_inc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void bpf_link_inc(struct bpf_link *link);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff8130a264)
Location: kernel/bpf/syscall.c:2893
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_link_get_from_fd
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_get_user
  - kernel/bpf/trampoline.c:bpf_trampoline_link_cgroup_shim
```
**Symbols:**

```
ffffffff813125f0-ffffffff81312605: bpf_link_inc (STB_GLOBAL)
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
