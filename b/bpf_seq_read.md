# Function: <code>bpf_seq_read</code>

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
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
ssize_t bpf_seq_read(struct file *file, char *buf, size_t size, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/bpf_iter.c (0)
Location: kernel/bpf/bpf_iter.c:77
Inline: False
```
**Symbols:**

```
ffffffff812157f0-ffffffff81215bc4: bpf_seq_read (STB_LOCAL)
ffffffff812160ce-ffffffff812160e7: bpf_seq_read.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
ssize_t bpf_seq_read(struct file *file, char *buf, size_t size, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/bpf_iter.c (0)
Location: kernel/bpf/bpf_iter.c:89
Inline: False
```
**Symbols:**

```
ffffffff81217670-ffffffff81217a56: bpf_seq_read (STB_LOCAL)
ffffffff81be655b-ffffffff81be6574: bpf_seq_read.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
ssize_t bpf_seq_read(struct file *file, char *buf, size_t size, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/bpf_iter.c (0)
Location: kernel/bpf/bpf_iter.c:89
Inline: False
```
**Symbols:**

```
ffffffff8121aae0-ffffffff8121aecc: bpf_seq_read (STB_LOCAL)
ffffffff81bd825b-ffffffff81bd8274: bpf_seq_read.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
ssize_t bpf_seq_read(struct file *file, char *buf, size_t size, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/bpf_iter.c (0)
Location: kernel/bpf/bpf_iter.c:89
Inline: False
```
**Symbols:**

```
ffffffff812518e0-ffffffff81251ccc: bpf_seq_read (STB_LOCAL)
ffffffff81cb91a9-ffffffff81cb91c2: bpf_seq_read.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
ssize_t bpf_seq_read(struct file *file, char *buf, size_t size, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/bpf_iter.c (0)
Location: kernel/bpf/bpf_iter.c:90
Inline: False
```
**Symbols:**

```
ffffffff81299520-ffffffff8129990a: bpf_seq_read (STB_LOCAL)
ffffffff81e6a472-ffffffff81e6a48b: bpf_seq_read.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ssize_t bpf_seq_read(struct file *file, char *buf, size_t size, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_iter.c (ffffffff812f5300)
Location: kernel/bpf/bpf_iter.c:94
Inline: False
```
**Symbols:**

```
ffffffff812f5300-ffffffff812f573c: bpf_seq_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ssize_t bpf_seq_read(struct file *file, char *buf, size_t size, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_iter.c (ffffffff813230a0)
Location: kernel/bpf/bpf_iter.c:94
Inline: False
```
**Symbols:**

```
ffffffff813230a0-ffffffff813234dc: bpf_seq_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ssize_t bpf_seq_read(struct file *file, char *buf, size_t size, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_iter.c (ffffffff81346fd0)
Location: kernel/bpf/bpf_iter.c:94
Inline: False
```
**Symbols:**

```
ffffffff81346fd0-ffffffff8134740c: bpf_seq_read (STB_LOCAL)
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
