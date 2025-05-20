# Function: <code>timespec_trunc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct timespec timespec_trunc(struct timespec t, unsigned int gran);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff810eaf70)
Location: kernel/time/time.c:297
Inline: False
Direct callers:
  - kernel/time/time.c:current_fs_time
  - fs/attr.c:setattr_copy
  - fs/attr.c:setattr_copy
  - fs/attr.c:setattr_copy
```
**Symbols:**

```
ffffffff810eaf70-ffffffff810eafe3: timespec_trunc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct timespec timespec_trunc(struct timespec t, unsigned int gran);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff810f1c40)
Location: kernel/time/time.c:297
Inline: False
Direct callers:
  - kernel/time/time.c:current_fs_time
  - fs/attr.c:setattr_copy
  - fs/attr.c:setattr_copy
  - fs/attr.c:setattr_copy
```
**Symbols:**

```
ffffffff810f1c40-ffffffff810f1cb3: timespec_trunc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct timespec timespec_trunc(struct timespec t, unsigned int gran);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff810f8dc0)
Location: kernel/time/time.c:297
Inline: False
Direct callers:
  - kernel/time/time.c:current_fs_time
  - fs/inode.c:current_time
  - fs/attr.c:setattr_copy
  - fs/attr.c:setattr_copy
  - fs/attr.c:setattr_copy
```
**Symbols:**

```
ffffffff810f8dc0-ffffffff810f8e33: timespec_trunc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct timespec timespec_trunc(struct timespec t, unsigned int gran);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff810faf00)
Location: kernel/time/time.c:387
Inline: False
Direct callers:
  - fs/inode.c:current_time
  - fs/attr.c:setattr_copy
  - fs/attr.c:setattr_copy
  - fs/attr.c:setattr_copy
  - fs/configfs/inode.c:configfs_setattr
  - fs/configfs/inode.c:configfs_setattr
  - fs/configfs/inode.c:configfs_setattr
```
**Symbols:**

```
ffffffff810faf00-ffffffff810faf66: timespec_trunc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct timespec timespec_trunc(struct timespec t, unsigned int gran);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff81105890)
Location: kernel/time/time.c:353
Inline: False
Direct callers:
  - fs/inode.c:current_time
  - fs/attr.c:setattr_copy
  - fs/attr.c:setattr_copy
  - fs/attr.c:setattr_copy
  - fs/configfs/inode.c:configfs_setattr
  - fs/configfs/inode.c:configfs_setattr
  - fs/configfs/inode.c:configfs_setattr
```
**Symbols:**

```
ffffffff81105890-ffffffff81105901: timespec_trunc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct timespec timespec_trunc(struct timespec t, unsigned int gran);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/time.c (ffffffff811109e0)
Location: kernel/time/time.c:355
Inline: False
```
**Symbols:**

```
ffffffff811109e0-ffffffff81110a49: timespec_trunc (STB_GLOBAL)
```
</details>
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
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
</ul>
