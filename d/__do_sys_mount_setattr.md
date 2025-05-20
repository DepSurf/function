# Function: <code>__do_sys_mount_setattr</code>

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
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int __do_sys_mount_setattr(int dfd, const char *path, unsigned int flags, struct mount_attr *uattr, size_t usize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8134f3b0)
Location: fs/namespace.c:4156
Inline: False
Direct callers:
  - fs/namespace.c:__ia32_sys_mount_setattr
  - fs/namespace.c:__x64_sys_mount_setattr
```
**Symbols:**

```
ffffffff8134f3b0-ffffffff8134f56d: __do_sys_mount_setattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int __do_sys_mount_setattr(int dfd, const char *path, unsigned int flags, struct mount_attr *uattr, size_t usize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8139d690)
Location: fs/namespace.c:4235
Inline: False
Direct callers:
  - fs/namespace.c:__ia32_sys_mount_setattr
  - fs/namespace.c:__x64_sys_mount_setattr
```
**Symbols:**

```
ffffffff8139d690-ffffffff8139d84e: __do_sys_mount_setattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int __do_sys_mount_setattr(int dfd, const char *path, unsigned int flags, struct mount_attr *uattr, size_t usize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff814205f0)
Location: fs/namespace.c:4328
Inline: False
Direct callers:
  - fs/namespace.c:__ia32_sys_mount_setattr
  - fs/namespace.c:__x64_sys_mount_setattr
```
**Symbols:**

```
ffffffff814205f0-ffffffff81420809: __do_sys_mount_setattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int __do_sys_mount_setattr(int dfd, const char *path, unsigned int flags, struct mount_attr *uattr, size_t usize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff814acb80)
Location: fs/namespace.c:4437
Inline: False
Direct callers:
  - fs/namespace.c:__ia32_sys_mount_setattr
  - fs/namespace.c:__x64_sys_mount_setattr
```
**Symbols:**

```
ffffffff814acb80-ffffffff814ace4f: __do_sys_mount_setattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff814e18bc)
Location: fs/namespace.c:4629
Inline: True
Inline callers:
  - fs/namespace.c:__ia32_sys_mount_setattr
  - fs/namespace.c:__x64_sys_mount_setattr
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8151598c)
Location: fs/namespace.c:4647
Inline: True
Inline callers:
  - fs/namespace.c:__ia32_sys_mount_setattr
  - fs/namespace.c:__x64_sys_mount_setattr
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
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
</ul>
