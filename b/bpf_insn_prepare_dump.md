# Function: <code>bpf_insn_prepare_dump</code>

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
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811b45c7)
Location: kernel/bpf/syscall.c:1803
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811c28df)
Location: kernel/bpf/syscall.c:2005
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811d3472)
Location: kernel/bpf/syscall.c:2225
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811df769)
Location: kernel/bpf/syscall.c:2248
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct bpf_insn *bpf_insn_prepare_dump(const struct bpf_prog *prog, const struct cred *f_cred);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811fbea0)
Location: kernel/bpf/syscall.c:3140
Inline: False
```
**Symbols:**

```
ffffffff811fbea0-ffffffff811fc08b: bpf_insn_prepare_dump (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct bpf_insn *bpf_insn_prepare_dump(const struct bpf_prog *prog, const struct cred *f_cred);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811faf70)
Location: kernel/bpf/syscall.c:3307
Inline: False
```
**Symbols:**

```
ffffffff811faf70-ffffffff811fb1b0: bpf_insn_prepare_dump (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct bpf_insn *bpf_insn_prepare_dump(const struct bpf_prog *prog, const struct cred *f_cred);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811fbd60)
Location: kernel/bpf/syscall.c:3330
Inline: False
```
**Symbols:**

```
ffffffff811fbd60-ffffffff811fbfa0: bpf_insn_prepare_dump (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct bpf_insn *bpf_insn_prepare_dump(const struct bpf_prog *prog, const struct cred *f_cred);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff8122d350)
Location: kernel/bpf/syscall.c:3513
Inline: False
```
**Symbols:**

```
ffffffff8122d350-ffffffff8122d590: bpf_insn_prepare_dump (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct bpf_insn *bpf_insn_prepare_dump(const struct bpf_prog *prog, const struct cred *f_cred);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff8126f880)
Location: kernel/bpf/syscall.c:3771
Inline: False
```
**Symbols:**

```
ffffffff8126f880-ffffffff8126fa83: bpf_insn_prepare_dump (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct bpf_insn *bpf_insn_prepare_dump(const struct bpf_prog *prog, const struct cred *f_cred);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff812c5190)
Location: kernel/bpf/syscall.c:3814
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_get_info_by_fd
```
**Symbols:**

```
ffffffff812c5190-ffffffff812c5393: bpf_insn_prepare_dump (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct bpf_insn *bpf_insn_prepare_dump(const struct bpf_prog *prog, const struct cred *f_cred);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff812ec2d0)
Location: kernel/bpf/syscall.c:3950
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_get_info_by_fd
```
**Symbols:**

```
ffffffff812ec2d0-ffffffff812ec4d3: bpf_insn_prepare_dump (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct bpf_insn *bpf_insn_prepare_dump(const struct bpf_prog *prog, const struct cred *f_cred);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff8130a9e0)
Location: kernel/bpf/syscall.c:4287
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_get_info_by_fd
```
**Symbols:**

```
ffffffff8130a9e0-ffffffff8130abe3: bpf_insn_prepare_dump (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffff8000102619d0)
Location: kernel/bpf/syscall.c:2248
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (c049460c)
Location: kernel/bpf/syscall.c:2248
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_get_info_by_fd
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (c0000000003061dc)
Location: kernel/bpf/syscall.c:2248
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffe00019e722)
Location: kernel/bpf/syscall.c:2248
Inline: True
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811d7d89)
Location: kernel/bpf/syscall.c:2248
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811cab49)
Location: kernel/bpf/syscall.c:2248
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811d5b59)
Location: kernel/bpf/syscall.c:2248
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811e3ec9)
Location: kernel/bpf/syscall.c:2248
Inline: True
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
