# Function: <code>create_mnt_ns</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
struct mnt_namespace *create_mnt_ns(struct vfsmount *m);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8122d080)
Location: fs/namespace.c:2854
Inline: True
Direct callers:
  - fs/namespace.c:mnt_init
  - fs/namespace.c:mount_subtree
```
**Symbols:**

```
ffffffff8122d080-ffffffff8122d105: create_mnt_ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct mnt_namespace *create_mnt_ns(struct vfsmount *m);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81255870)
Location: fs/namespace.c:2841
Inline: True
Direct callers:
  - fs/namespace.c:mount_subtree
  - fs/namespace.c:mnt_init
```
**Symbols:**

```
ffffffff81255870-ffffffff812558f5: create_mnt_ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct mnt_namespace *create_mnt_ns(struct vfsmount *m);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81268c60)
Location: fs/namespace.c:2984
Inline: True
Direct callers:
  - fs/namespace.c:mount_subtree
  - fs/namespace.c:mnt_init
```
**Symbols:**

```
ffffffff81268c60-ffffffff81268ce9: create_mnt_ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct mnt_namespace *create_mnt_ns(struct vfsmount *m);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812763b0)
Location: fs/namespace.c:2926
Inline: True
Direct callers:
  - fs/namespace.c:mount_subtree
  - fs/namespace.c:mnt_init
```
**Symbols:**

```
ffffffff812763b0-ffffffff81276439: create_mnt_ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct mnt_namespace *create_mnt_ns(struct vfsmount *m);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81298d00)
Location: fs/namespace.c:2999
Inline: True
Direct callers:
  - fs/namespace.c:mount_subtree
  - fs/namespace.c:mnt_init
```
**Symbols:**

```
ffffffff81298d00-ffffffff81298d89: create_mnt_ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct mnt_namespace *create_mnt_ns(struct vfsmount *m);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812beef0)
Location: fs/namespace.c:3030
Inline: True
Direct callers:
  - fs/namespace.c:mount_subtree
  - fs/namespace.c:mnt_init
```
**Symbols:**

```
ffffffff812beef0-ffffffff812bef7e: create_mnt_ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct mnt_namespace *create_mnt_ns(struct vfsmount *m);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812d41eb)
Location: fs/namespace.c:3002
Inline: True
Direct callers:
  - fs/namespace.c:mount_subtree
  - fs/namespace.c:mnt_init
```
**Symbols:**

```
ffffffff812d4260-ffffffff812d42ee: create_mnt_ns (STB_LOCAL)
```
</details>
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
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
</ul>
