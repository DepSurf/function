# Function: <code>bpf_map_poll</code>

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
__poll_t bpf_map_poll(struct file *filp, struct poll_table_struct *pts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811fb340)
Location: kernel/bpf/syscall.c:657
Inline: False
```
**Symbols:**

```
ffffffff811fb340-ffffffff811fb375: bpf_map_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
__poll_t bpf_map_poll(struct file *filp, struct poll_table_struct *pts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811fa4a0)
Location: kernel/bpf/syscall.c:664
Inline: False
```
**Symbols:**

```
ffffffff811fa4a0-ffffffff811fa4d5: bpf_map_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
__poll_t bpf_map_poll(struct file *filp, struct poll_table_struct *pts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811fb3e0)
Location: kernel/bpf/syscall.c:665
Inline: False
```
**Symbols:**

```
ffffffff811fb3e0-ffffffff811fb415: bpf_map_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
__poll_t bpf_map_poll(struct file *filp, struct poll_table_struct *pts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff8122cb20)
Location: kernel/bpf/syscall.c:681
Inline: False
```
**Symbols:**

```
ffffffff8122cb20-ffffffff8122cb55: bpf_map_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
__poll_t bpf_map_poll(struct file *filp, struct poll_table_struct *pts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff8126ed70)
Location: kernel/bpf/syscall.c:802
Inline: False
```
**Symbols:**

```
ffffffff8126ed70-ffffffff8126edc3: bpf_map_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
__poll_t bpf_map_poll(struct file *filp, struct poll_table_struct *pts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff812c45c0)
Location: kernel/bpf/syscall.c:901
Inline: False
```
**Symbols:**

```
ffffffff812c45c0-ffffffff812c4613: bpf_map_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
__poll_t bpf_map_poll(struct file *filp, struct poll_table_struct *pts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff812eb5c0)
Location: kernel/bpf/syscall.c:900
Inline: False
```
**Symbols:**

```
ffffffff812eb5c0-ffffffff812eb613: bpf_map_poll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
__poll_t bpf_map_poll(struct file *filp, struct poll_table_struct *pts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff81309b10)
Location: kernel/bpf/syscall.c:930
Inline: False
```
**Symbols:**

```
ffffffff81309b10-ffffffff81309b63: bpf_map_poll (STB_LOCAL)
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
