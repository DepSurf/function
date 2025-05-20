# Function: <code>prepare_seq_file</code>

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
int prepare_seq_file(struct file *file, struct bpf_iter_link *link);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_iter.c (ffffffff812156c0)
Location: kernel/bpf/bpf_iter.c:433
Inline: False
Direct callers:
  - kernel/bpf/bpf_iter.c:bpf_iter_new_fd
  - kernel/bpf/bpf_iter.c:iter_open
```
**Symbols:**

```
ffffffff812156c0-ffffffff812157bf: prepare_seq_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int prepare_seq_file(struct file *file, struct bpf_iter_link *link, const struct bpf_iter_seq_info *seq_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_iter.c (ffffffff81217380)
Location: kernel/bpf/bpf_iter.c:556
Inline: False
Direct callers:
  - kernel/bpf/bpf_iter.c:bpf_iter_new_fd
  - kernel/bpf/bpf_iter.c:iter_open
  - kernel/bpf/bpf_iter.c:iter_open
```
**Symbols:**

```
ffffffff81217380-ffffffff8121748b: prepare_seq_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int prepare_seq_file(struct file *file, struct bpf_iter_link *link, const struct bpf_iter_seq_info *seq_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_iter.c (ffffffff8121a7f0)
Location: kernel/bpf/bpf_iter.c:556
Inline: False
Direct callers:
  - kernel/bpf/bpf_iter.c:bpf_iter_new_fd
  - kernel/bpf/bpf_iter.c:iter_open
  - kernel/bpf/bpf_iter.c:iter_open
```
**Symbols:**

```
ffffffff8121a7f0-ffffffff8121a8fb: prepare_seq_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int prepare_seq_file(struct file *file, struct bpf_iter_link *link, const struct bpf_iter_seq_info *seq_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_iter.c (ffffffff812515f0)
Location: kernel/bpf/bpf_iter.c:579
Inline: False
Direct callers:
  - kernel/bpf/bpf_iter.c:bpf_iter_new_fd
  - kernel/bpf/bpf_iter.c:iter_open
  - kernel/bpf/bpf_iter.c:iter_open
```
**Symbols:**

```
ffffffff812515f0-ffffffff812516fb: prepare_seq_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int prepare_seq_file(struct file *file, struct bpf_iter_link *link, const struct bpf_iter_seq_info *seq_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_iter.c (ffffffff812991f0)
Location: kernel/bpf/bpf_iter.c:578
Inline: False
Direct callers:
  - kernel/bpf/bpf_iter.c:bpf_iter_new_fd
  - kernel/bpf/bpf_iter.c:iter_open
  - kernel/bpf/bpf_iter.c:iter_open
```
**Symbols:**

```
ffffffff812991f0-ffffffff81299308: prepare_seq_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int prepare_seq_file(struct file *file, struct bpf_iter_link *link, const struct bpf_iter_seq_info *seq_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_iter.c (ffffffff812f4f80)
Location: kernel/bpf/bpf_iter.c:591
Inline: False
Direct callers:
  - kernel/bpf/bpf_iter.c:bpf_iter_new_fd
  - kernel/bpf/bpf_iter.c:iter_open
  - kernel/bpf/bpf_iter.c:iter_open
```
**Symbols:**

```
ffffffff812f4f80-ffffffff812f5098: prepare_seq_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int prepare_seq_file(struct file *file, struct bpf_iter_link *link, const struct bpf_iter_seq_info *seq_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_iter.c (ffffffff81322d20)
Location: kernel/bpf/bpf_iter.c:591
Inline: False
Direct callers:
  - kernel/bpf/bpf_iter.c:bpf_iter_new_fd
  - kernel/bpf/bpf_iter.c:iter_open
  - kernel/bpf/bpf_iter.c:iter_open
```
**Symbols:**

```
ffffffff81322d20-ffffffff81322e3f: prepare_seq_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int prepare_seq_file(struct file *file, struct bpf_iter_link *link, const struct bpf_iter_seq_info *seq_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_iter.c (ffffffff81346c50)
Location: kernel/bpf/bpf_iter.c:591
Inline: False
Direct callers:
  - kernel/bpf/bpf_iter.c:bpf_iter_new_fd
  - kernel/bpf/bpf_iter.c:iter_open
  - kernel/bpf/bpf_iter.c:iter_open
```
**Symbols:**

```
ffffffff81346c50-ffffffff81346d6f: prepare_seq_file (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct bpf_iter_seq_info *seq_info</code>
</li>
</ul>
</details>
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
