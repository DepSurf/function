# Function: <code>bpf_link_get_curr_or_next</code>

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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct bpf_link *bpf_link_get_curr_or_next(u32 *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff81277d00)
Location: kernel/bpf/syscall.c:4680
Inline: False
Direct callers:
  - kernel/bpf/link_iter.c:bpf_link_seq_next
  - kernel/bpf/link_iter.c:bpf_link_seq_start
```
**Symbols:**

```
ffffffff81277d00-ffffffff81277d68: bpf_link_get_curr_or_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct bpf_link *bpf_link_get_curr_or_next(u32 *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff812ce120)
Location: kernel/bpf/syscall.c:4732
Inline: False
Direct callers:
  - kernel/bpf/link_iter.c:bpf_link_seq_next
  - kernel/bpf/link_iter.c:bpf_link_seq_start
```
**Symbols:**

```
ffffffff812ce120-ffffffff812ce188: bpf_link_get_curr_or_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct bpf_link *bpf_link_get_curr_or_next(u32 *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff812f56b0)
Location: kernel/bpf/syscall.c:4915
Inline: False
Direct callers:
  - kernel/bpf/link_iter.c:bpf_link_seq_next
  - kernel/bpf/link_iter.c:bpf_link_seq_start
```
**Symbols:**

```
ffffffff812f56b0-ffffffff812f5718: bpf_link_get_curr_or_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct bpf_link *bpf_link_get_curr_or_next(u32 *id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff813144b0)
Location: kernel/bpf/syscall.c:5230
Inline: False
Direct callers:
  - kernel/bpf/link_iter.c:bpf_link_seq_next
  - kernel/bpf/link_iter.c:bpf_link_seq_start
```
**Symbols:**

```
ffffffff813144b0-ffffffff81314518: bpf_link_get_curr_or_next (STB_GLOBAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
