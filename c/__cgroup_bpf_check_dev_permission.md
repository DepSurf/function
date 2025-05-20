# Function: <code>__cgroup_bpf_check_dev_permission</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __cgroup_bpf_check_dev_permission(short int dev_type, u32 major, u32 minor, short int access, enum bpf_attach_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff811b2280)
Location: kernel/bpf/cgroup.c:526
Inline: False
Direct callers:
  - fs/block_dev.c:__blkdev_get
```
**Symbols:**

```
ffffffff811b2280-ffffffff811b232c: __cgroup_bpf_check_dev_permission (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __cgroup_bpf_check_dev_permission(short int dev_type, u32 major, u32 minor, short int access, enum bpf_attach_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff811d1810)
Location: kernel/bpf/cgroup.c:624
Inline: False
Direct callers:
  - fs/namei.c:inode_permission
  - fs/block_dev.c:__blkdev_get
```
**Symbols:**

```
ffffffff811d1810-ffffffff811d18bc: __cgroup_bpf_check_dev_permission (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __cgroup_bpf_check_dev_permission(short int dev_type, u32 major, u32 minor, short int access, enum bpf_attach_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff811e13d0)
Location: kernel/bpf/cgroup.c:681
Inline: False
Direct callers:
  - fs/namei.c:inode_permission
  - fs/block_dev.c:__blkdev_get
```
**Symbols:**

```
ffffffff811e13d0-ffffffff811e149c: __cgroup_bpf_check_dev_permission (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __cgroup_bpf_check_dev_permission(short int dev_type, u32 major, u32 minor, short int access, enum bpf_attach_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff811f7690)
Location: kernel/bpf/cgroup.c:754
Inline: False
Direct callers:
  - fs/namei.c:inode_permission
  - fs/block_dev.c:__blkdev_get
```
**Symbols:**

```
ffffffff811f7690-ffffffff811f77ae: __cgroup_bpf_check_dev_permission (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __cgroup_bpf_check_dev_permission(short int dev_type, u32 major, u32 minor, short int access, enum bpf_attach_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff81204630)
Location: kernel/bpf/cgroup.c:764
Inline: False
Direct callers:
  - fs/namei.c:inode_permission
  - fs/block_dev.c:__blkdev_get
```
**Symbols:**

```
ffffffff81204630-ffffffff8120474e: __cgroup_bpf_check_dev_permission (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __cgroup_bpf_check_dev_permission(short int dev_type, u32 major, u32 minor, short int access, enum bpf_attach_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff8122e460)
Location: kernel/bpf/cgroup.c:1101
Inline: False
Direct callers:
  - security/device_cgroup.c:devcgroup_check_permission
```
**Symbols:**

```
ffffffff8122e460-ffffffff8122e57e: __cgroup_bpf_check_dev_permission (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __cgroup_bpf_check_dev_permission(short int dev_type, u32 major, u32 minor, short int access, enum bpf_attach_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff812369b0)
Location: kernel/bpf/cgroup.c:1125
Inline: False
Direct callers:
  - security/device_cgroup.c:devcgroup_check_permission
```
**Symbols:**

```
ffffffff812369b0-ffffffff81236ae8: __cgroup_bpf_check_dev_permission (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __cgroup_bpf_check_dev_permission(short int dev_type, u32 major, u32 minor, short int access, enum bpf_attach_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff8123ac10)
Location: kernel/bpf/cgroup.c:1129
Inline: False
Direct callers:
  - security/device_cgroup.c:devcgroup_check_permission
```
**Symbols:**

```
ffffffff8123ac10-ffffffff8123add1: __cgroup_bpf_check_dev_permission (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __cgroup_bpf_check_dev_permission(short int dev_type, u32 major, u32 minor, short int access, enum cgroup_bpf_attach_type atype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff812757f0)
Location: kernel/bpf/cgroup.c:1159
Inline: False
Direct callers:
  - security/device_cgroup.c:devcgroup_check_permission
```
**Symbols:**

```
ffffffff812757f0-ffffffff81275964: __cgroup_bpf_check_dev_permission (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __cgroup_bpf_check_dev_permission(short int dev_type, u32 major, u32 minor, short int access, enum cgroup_bpf_attach_type atype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff812c5250)
Location: kernel/bpf/cgroup.c:1306
Inline: False
Direct callers:
  - security/device_cgroup.c:devcgroup_check_permission
```
**Symbols:**

```
ffffffff812c5250-ffffffff812c53de: __cgroup_bpf_check_dev_permission (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __cgroup_bpf_check_dev_permission(short int dev_type, u32 major, u32 minor, short int access, enum cgroup_bpf_attach_type atype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff8132a780)
Location: kernel/bpf/cgroup.c:1520
Inline: False
Direct callers:
  - security/device_cgroup.c:devcgroup_check_permission
```
**Symbols:**

```
ffffffff8132a780-ffffffff8132a90e: __cgroup_bpf_check_dev_permission (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __cgroup_bpf_check_dev_permission(short int dev_type, u32 major, u32 minor, short int access, enum cgroup_bpf_attach_type atype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff8135a8c0)
Location: kernel/bpf/cgroup.c:1520
Inline: False
Direct callers:
  - security/device_cgroup.c:devcgroup_check_permission
```
**Symbols:**

```
ffffffff8135a8c0-ffffffff8135aa4f: __cgroup_bpf_check_dev_permission (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __cgroup_bpf_check_dev_permission(short int dev_type, u32 major, u32 minor, short int access, enum cgroup_bpf_attach_type atype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff813834b0)
Location: kernel/bpf/cgroup.c:1535
Inline: False
Direct callers:
  - security/device_cgroup.c:devcgroup_check_permission
```
**Symbols:**

```
ffffffff813834b0-ffffffff8138363f: __cgroup_bpf_check_dev_permission (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int __cgroup_bpf_check_dev_permission(short int dev_type, u32 major, u32 minor, short int access, enum bpf_attach_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffff80001028dce0)
Location: kernel/bpf/cgroup.c:764
Inline: False
Direct callers:
  - fs/namei.c:inode_permission
  - fs/block_dev.c:__blkdev_get
```
**Symbols:**

```
ffff80001028dce0-ffff80001028de48: __cgroup_bpf_check_dev_permission (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __cgroup_bpf_check_dev_permission(short int dev_type, u32 major, u32 minor, short int access, enum bpf_attach_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (c04bc6a4)
Location: kernel/bpf/cgroup.c:764
Inline: False
Direct callers:
  - fs/namei.c:inode_permission
  - fs/block_dev.c:__blkdev_get
```
**Symbols:**

```
c04bc6a4-c04bc864: __cgroup_bpf_check_dev_permission (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __cgroup_bpf_check_dev_permission(short int dev_type, u32 major, u32 minor, short int access, enum bpf_attach_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (c00000000033a5d0)
Location: kernel/bpf/cgroup.c:764
Inline: False
Direct callers:
  - fs/namei.c:inode_permission
  - fs/block_dev.c:__blkdev_get
```
**Symbols:**

```
c00000000033a5d0-c00000000033a7c0: __cgroup_bpf_check_dev_permission (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __cgroup_bpf_check_dev_permission(short int dev_type, u32 major, u32 minor, short int access, enum bpf_attach_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffe0001c0a08)
Location: kernel/bpf/cgroup.c:764
Inline: False
Direct callers:
  - fs/namei.c:inode_permission
  - fs/block_dev.c:__blkdev_get
```
**Symbols:**

```
ffffffe0001c0a08-ffffffe0001c0b68: __cgroup_bpf_check_dev_permission (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int __cgroup_bpf_check_dev_permission(short int dev_type, u32 major, u32 minor, short int access, enum bpf_attach_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff811fcc50)
Location: kernel/bpf/cgroup.c:764
Inline: False
Direct callers:
  - fs/namei.c:inode_permission
  - fs/block_dev.c:__blkdev_get
```
**Symbols:**

```
ffffffff811fcc50-ffffffff811fcd6e: __cgroup_bpf_check_dev_permission (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __cgroup_bpf_check_dev_permission(short int dev_type, u32 major, u32 minor, short int access, enum bpf_attach_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff811ef9a0)
Location: kernel/bpf/cgroup.c:764
Inline: False
Direct callers:
  - fs/namei.c:inode_permission
  - fs/block_dev.c:__blkdev_get
```
**Symbols:**

```
ffffffff811ef9a0-ffffffff811efabe: __cgroup_bpf_check_dev_permission (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __cgroup_bpf_check_dev_permission(short int dev_type, u32 major, u32 minor, short int access, enum bpf_attach_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff811faa20)
Location: kernel/bpf/cgroup.c:764
Inline: False
Direct callers:
  - fs/namei.c:inode_permission
  - fs/block_dev.c:__blkdev_get
```
**Symbols:**

```
ffffffff811faa20-ffffffff811fab3e: __cgroup_bpf_check_dev_permission (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __cgroup_bpf_check_dev_permission(short int dev_type, u32 major, u32 minor, short int access, enum bpf_attach_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cgroup.c (ffffffff81209860)
Location: kernel/bpf/cgroup.c:764
Inline: False
Direct callers:
  - fs/namei.c:inode_permission
  - fs/block_dev.c:__blkdev_get
```
**Symbols:**

```
ffffffff81209860-ffffffff812099ae: __cgroup_bpf_check_dev_permission (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>enum cgroup_bpf_attach_type atype</code>
</li>
<li>
<b>Param removed. </b>
<code>enum bpf_attach_type type</code>
</li>
</ul>
</details>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
