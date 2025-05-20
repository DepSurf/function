# Function: <code>compat_SyS_fcntl64</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
long int compat_SyS_fcntl64(long int fd, long int cmd, long int arg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/compat.c (ffffffff812644d0)
Location: fs/compat.c:417
Inline: True
Inline callers:
  - fs/compat.c:compat_SyS_fcntl
```
**Symbols:**

```
ffffffff812644d0-ffffffff812646df: compat_SyS_fcntl64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
long int compat_SyS_fcntl64(long int fd, long int cmd, long int arg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/compat.c (ffffffff81290a61)
Location: fs/compat.c:417
Inline: True
Inline callers:
  - fs/compat.c:compat_SyS_fcntl
```
**Symbols:**

```
ffffffff81290800-ffffffff81290a0f: compat_SyS_fcntl64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
long int compat_SyS_fcntl64(long int fd, long int cmd, long int arg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/compat.c (ffffffff812a5a11)
Location: fs/compat.c:403
Inline: True
Inline callers:
  - fs/compat.c:compat_SyS_fcntl
```
**Symbols:**

```
ffffffff812a57b0-ffffffff812a59bf: compat_SyS_fcntl64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
long int compat_SyS_fcntl64(long int fd, long int cmd, long int arg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff8126639a)
Location: fs/fcntl.c:609
Inline: True
Inline callers:
  - fs/fcntl.c:compat_SyS_fcntl
```
**Symbols:**

```
ffffffff812660a0-ffffffff81266342: compat_SyS_fcntl64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
long int compat_SyS_fcntl64(long int fd, long int cmd, long int arg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff81288c5a)
Location: fs/fcntl.c:613
Inline: True
Inline callers:
  - fs/fcntl.c:compat_SyS_fcntl
```
**Symbols:**

```
ffffffff81288980-ffffffff81288c07: compat_SyS_fcntl64 (STB_GLOBAL)
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
