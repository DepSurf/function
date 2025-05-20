# Function: <code>apparmor_inode</code>

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
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff81624b97)
Location: security/apparmor/include/inode.h:29
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:apparmor_inode_create
  - security/apparmor/lsm.c:apparmor_d_instantiate
  - security/apparmor/lsm.c:apparmor_inode_init_security
  - security/apparmor/lsm.c:apparmor_inode_init_security
  - security/apparmor/lsm.c:apparmor_inode_free_security
  - security/apparmor/lsm.c:apparmor_inode_alloc_security
```
```
In security/apparmor/file.c (ffffffff81628d35)
Location: security/apparmor/include/inode.h:29
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_file_perm
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff816d8978)
Location: security/apparmor/include/inode.h:29
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:apparmor_inode_create
  - security/apparmor/lsm.c:apparmor_d_instantiate
  - security/apparmor/lsm.c:apparmor_inode_init_security
  - security/apparmor/lsm.c:apparmor_inode_init_security
  - security/apparmor/lsm.c:apparmor_inode_free_security
  - security/apparmor/lsm.c:apparmor_inode_alloc_security
```
```
In security/apparmor/file.c (ffffffff816dd5b9)
Location: security/apparmor/include/inode.h:29
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_file_perm
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff8171178d)
Location: security/apparmor/include/inode.h:29
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:apparmor_inode_create
  - security/apparmor/lsm.c:apparmor_d_instantiate
  - security/apparmor/lsm.c:apparmor_inode_init_security
  - security/apparmor/lsm.c:apparmor_inode_init_security
  - security/apparmor/lsm.c:apparmor_inode_free_security
  - security/apparmor/lsm.c:apparmor_inode_alloc_security
```
```
In security/apparmor/file.c (ffffffff81716bcc)
Location: security/apparmor/include/inode.h:29
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_file_perm
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff8174faf4)
Location: security/apparmor/include/inode.h:29
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_file_open
  - security/apparmor/lsm.c:apparmor_inode_create
  - security/apparmor/lsm.c:apparmor_d_instantiate
  - security/apparmor/lsm.c:apparmor_inode_init_security
  - security/apparmor/lsm.c:apparmor_inode_init_security
  - security/apparmor/lsm.c:apparmor_inode_free_security
  - security/apparmor/lsm.c:apparmor_inode_alloc_security
```
```
In security/apparmor/file.c (ffffffff8175572c)
Location: security/apparmor/include/inode.h:29
Inline: True
Inline callers:
  - security/apparmor/file.c:aa_file_perm
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
