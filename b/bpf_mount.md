# Function: <code>bpf_mount</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct dentry *bpf_mount(struct file_system_type *type, int flags, const char *dev_name, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/inode.c (ffffffff81176c50)
Location: kernel/bpf/inode.c:357
Inline: False
```
**Symbols:**

```
ffffffff81176c50-ffffffff81176c7b: bpf_mount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct dentry *bpf_mount(struct file_system_type *type, int flags, const char *dev_name, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/inode.c (ffffffff81185980)
Location: kernel/bpf/inode.c:357
Inline: False
```
**Symbols:**

```
ffffffff81185980-ffffffff8118599a: bpf_mount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct dentry *bpf_mount(struct file_system_type *type, int flags, const char *dev_name, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/inode.c (ffffffff81192bd0)
Location: kernel/bpf/inode.c:442
Inline: False
```
**Symbols:**

```
ffffffff81192bd0-ffffffff81192bea: bpf_mount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct dentry *bpf_mount(struct file_system_type *type, int flags, const char *dev_name, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/inode.c (ffffffff81199a40)
Location: kernel/bpf/inode.c:467
Inline: False
```
**Symbols:**

```
ffffffff81199a40-ffffffff81199a5a: bpf_mount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct dentry *bpf_mount(struct file_system_type *type, int flags, const char *dev_name, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/inode.c (ffffffff811a8dd0)
Location: kernel/bpf/inode.c:511
Inline: False
```
**Symbols:**

```
ffffffff811a8dd0-ffffffff811a8dea: bpf_mount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct dentry *bpf_mount(struct file_system_type *type, int flags, const char *dev_name, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/inode.c (ffffffff811c02f0)
Location: kernel/bpf/inode.c:656
Inline: False
```
**Symbols:**

```
ffffffff811c02f0-ffffffff811c030a: bpf_mount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct dentry *bpf_mount(struct file_system_type *type, int flags, const char *dev_name, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/inode.c (ffffffff811d1750)
Location: kernel/bpf/inode.c:657
Inline: False
```
**Symbols:**

```
ffffffff811d1750-ffffffff811d176a: bpf_mount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct dentry *bpf_mount(struct file_system_type *type, int flags, const char *dev_name, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/inode.c (ffffffff811e5a80)
Location: kernel/bpf/inode.c:652
Inline: False
```
**Symbols:**

```
ffffffff811e5a80-ffffffff811e5a9a: bpf_mount (STB_LOCAL)
```
</details>
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
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
</ul>
