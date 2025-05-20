# Function: <code>inode_storage_ptr</code>

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
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct bpf_local_storage **inode_storage_ptr(void *owner);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_inode_storage.c (ffffffff81221511)
Location: kernel/bpf/bpf_inode_storage.c:24
Inline: True
Inline callers:
  - kernel/bpf/bpf_inode_storage.c:bpf_inode_storage_get
  - kernel/bpf/bpf_inode_storage.c:bpf_fd_inode_storage_update_elem
```
**Symbols:**

```
ffffffff812213c0-ffffffff812213de: inode_storage_ptr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct bpf_local_storage **inode_storage_ptr(void *owner);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_inode_storage.c (ffffffff812261e1)
Location: kernel/bpf/bpf_inode_storage.c:24
Inline: True
Inline callers:
  - kernel/bpf/bpf_inode_storage.c:bpf_inode_storage_get
  - kernel/bpf/bpf_inode_storage.c:bpf_fd_inode_storage_update_elem
```
**Symbols:**

```
ffffffff81226080-ffffffff8122609e: inode_storage_ptr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct bpf_local_storage **inode_storage_ptr(void *owner);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_inode_storage.c (ffffffff8125e201)
Location: kernel/bpf/bpf_inode_storage.c:24
Inline: True
Inline callers:
  - kernel/bpf/bpf_inode_storage.c:bpf_inode_storage_get
  - kernel/bpf/bpf_inode_storage.c:bpf_fd_inode_storage_update_elem
```
**Symbols:**

```
ffffffff8125e0a0-ffffffff8125e0be: inode_storage_ptr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct bpf_local_storage **inode_storage_ptr(void *owner);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_inode_storage.c (ffffffff812a864b)
Location: kernel/bpf/bpf_inode_storage.c:25
Inline: True
Inline callers:
  - kernel/bpf/bpf_inode_storage.c:bpf_inode_storage_get
  - kernel/bpf/bpf_inode_storage.c:bpf_fd_inode_storage_update_elem
```
**Symbols:**

```
ffffffff812a84c0-ffffffff812a84e6: inode_storage_ptr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct bpf_local_storage **inode_storage_ptr(void *owner);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_inode_storage.c (ffffffff813070ab)
Location: kernel/bpf/bpf_inode_storage.c:25
Inline: True
Inline callers:
  - kernel/bpf/bpf_inode_storage.c:bpf_inode_storage_get
  - kernel/bpf/bpf_inode_storage.c:bpf_fd_inode_storage_update_elem
```
**Symbols:**

```
ffffffff81306f10-ffffffff81306f36: inode_storage_ptr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct bpf_local_storage **inode_storage_ptr(void *owner);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_inode_storage.c (ffffffff81335fa4)
Location: kernel/bpf/bpf_inode_storage.c:25
Inline: True
Inline callers:
  - kernel/bpf/bpf_inode_storage.c:bpf_inode_storage_get
  - kernel/bpf/bpf_inode_storage.c:bpf_fd_inode_storage_update_elem
```
**Symbols:**

```
ffffffff81335df0-ffffffff81335e16: inode_storage_ptr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct bpf_local_storage **inode_storage_ptr(void *owner);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_inode_storage.c (ffffffff8135a604)
Location: kernel/bpf/bpf_inode_storage.c:25
Inline: True
Inline callers:
  - kernel/bpf/bpf_inode_storage.c:bpf_inode_storage_get
  - kernel/bpf/bpf_inode_storage.c:bpf_fd_inode_storage_update_elem
```
**Symbols:**

```
ffffffff8135a450-ffffffff8135a476: inode_storage_ptr (STB_LOCAL)
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
