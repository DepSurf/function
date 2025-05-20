# Function: <code>setxattr_copy</code>

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
<summary>In <code>5.19</code>: ✅</summary>

```c
int setxattr_copy(const char *name, struct xattr_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff81429450)
Location: fs/xattr.c:569
Inline: False
Direct callers:
  - fs/xattr.c:setxattr
  - io_uring/io_uring.c:io_fsetxattr_prep
```
**Symbols:**

```
ffffffff81429450-ffffffff814294e5: setxattr_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int setxattr_copy(const char *name, struct xattr_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff814b63c0)
Location: fs/xattr.c:596
Inline: False
Direct callers:
  - fs/xattr.c:setxattr
  - io_uring/xattr.c:io_fsetxattr_prep
```
**Symbols:**

```
ffffffff814b63c0-ffffffff814b6455: setxattr_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int setxattr_copy(const char *name, struct xattr_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff814eb0d0)
Location: fs/xattr.c:594
Inline: False
Direct callers:
  - fs/xattr.c:setxattr
  - io_uring/xattr.c:io_fsetxattr_prep
```
**Symbols:**

```
ffffffff814eb0d0-ffffffff814eb165: setxattr_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int setxattr_copy(const char *name, struct xattr_ctx *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff8151ef70)
Location: fs/xattr.c:594
Inline: False
Direct callers:
  - fs/xattr.c:setxattr
  - io_uring/xattr.c:io_fsetxattr_prep
```
**Symbols:**

```
ffffffff8151ef70-ffffffff8151f005: setxattr_copy (STB_GLOBAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
