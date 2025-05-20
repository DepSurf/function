# Function: <code>bpf_prog_load_check_attach</code>

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
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff81200090)
Location: kernel/bpf/syscall.c:1957
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_load
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811ffa06)
Location: kernel/bpf/syscall.c:1931
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_load
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff812003b1)
Location: kernel/bpf/syscall.c:1939
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_load
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff81231c07)
Location: kernel/bpf/syscall.c:2038
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_load
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff812753a8)
Location: kernel/bpf/syscall.c:2284
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_load
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff812ca2ba)
Location: kernel/bpf/syscall.c:2318
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_load
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int bpf_prog_load_check_attach(enum bpf_prog_type prog_type, enum bpf_attach_type expected_attach_type, struct btf *attach_btf, u32 btf_id, struct bpf_prog *dst_prog);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff812eb730)
Location: kernel/bpf/syscall.c:2397
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_load
```
**Symbols:**

```
ffffffff812eb730-ffffffff812eb8d5: bpf_prog_load_check_attach (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int bpf_prog_load_check_attach(enum bpf_prog_type prog_type, enum bpf_attach_type expected_attach_type, struct btf *attach_btf, u32 btf_id, struct bpf_prog *dst_prog);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff81309c80)
Location: kernel/bpf/syscall.c:2437
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_load
```
**Symbols:**

```
ffffffff81309c80-ffffffff81309e25: bpf_prog_load_check_attach (STB_LOCAL)
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
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
