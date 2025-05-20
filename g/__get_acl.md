# Function: <code>__get_acl</code>

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
In <code>5.19</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/posix_acl.c (ffffffff81516b06)
Location: fs/posix_acl.c:114
Inline: True
Inline callers:
  - fs/posix_acl.c:vfs_get_acl
  - fs/posix_acl.c:posix_acl_create
  - fs/posix_acl.c:posix_acl_chmod
Direct callers:
  - fs/posix_acl.c:vfs_get_acl
  - fs/posix_acl.c:posix_acl_create
  - fs/posix_acl.c:posix_acl_chmod
```
**Symbols:**

```
ffffffff815168f0-ffffffff81516a63: __get_acl.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/posix_acl.c (ffffffff8154e446)
Location: fs/posix_acl.c:115
Inline: True
Inline callers:
  - fs/posix_acl.c:vfs_get_acl
  - fs/posix_acl.c:posix_acl_create
  - fs/posix_acl.c:posix_acl_chmod
Direct callers:
  - fs/posix_acl.c:vfs_get_acl
  - fs/posix_acl.c:posix_acl_create
  - fs/posix_acl.c:posix_acl_chmod
```
**Symbols:**

```
ffffffff8154e240-ffffffff8154e3aa: __get_acl.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/posix_acl.c (ffffffff81584296)
Location: fs/posix_acl.c:115
Inline: True
Inline callers:
  - fs/posix_acl.c:vfs_get_acl
  - fs/posix_acl.c:posix_acl_create
  - fs/posix_acl.c:posix_acl_chmod
Direct callers:
  - fs/posix_acl.c:vfs_get_acl
  - fs/posix_acl.c:posix_acl_create
  - fs/posix_acl.c:posix_acl_chmod
```
**Symbols:**

```
ffffffff81584090-ffffffff815841fa: __get_acl.part.0 (STB_LOCAL)
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
