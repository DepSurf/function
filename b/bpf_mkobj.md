# Function: <code>bpf_mkobj</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int bpf_mkobj(struct inode *dir, struct dentry *dentry, umode_t mode, dev_t devt);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/inode.c (ffffffff81176e90)
Location: kernel/bpf/inode.c:171
Inline: True
```
**Symbols:**

```
ffffffff81176e90-ffffffff81176ef9: bpf_mkobj (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int bpf_mkobj(struct inode *dir, struct dentry *dentry, umode_t mode, dev_t devt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/inode.c (ffffffff81185830)
Location: kernel/bpf/inode.c:160
Inline: False
```
**Symbols:**

```
ffffffff81185830-ffffffff8118589e: bpf_mkobj (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int bpf_mkobj(struct inode *dir, struct dentry *dentry, umode_t mode, dev_t devt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/inode.c (ffffffff81192db0)
Location: kernel/bpf/inode.c:168
Inline: False
```
**Symbols:**

```
ffffffff81192db0-ffffffff81192e65: bpf_mkobj (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int bpf_mkobj(struct inode *dir, struct dentry *dentry, umode_t mode, dev_t devt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/inode.c (ffffffff81199c40)
Location: kernel/bpf/inode.c:169
Inline: False
```
**Symbols:**

```
ffffffff81199c40-ffffffff81199cfc: bpf_mkobj (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int bpf_mkobj(struct inode *dir, struct dentry *dentry, umode_t mode, dev_t devt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/inode.c (ffffffff811a8fd0)
Location: kernel/bpf/inode.c:169
Inline: False
```
**Symbols:**

```
ffffffff811a8fd0-ffffffff811a908c: bpf_mkobj (STB_LOCAL)
```
</details>
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
</ul>
