# Function: <code>compat_SyS_setsockopt</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
long int compat_SyS_setsockopt(long int fd, long int level, long int optname, long int optval, long int optlen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/compat.c (ffffffff8173f540)
Location: net/compat.c:366
Inline: True
Inline callers:
  - net/compat.c:compat_SyS_socketcall
```
**Symbols:**

```
ffffffff8173f540-ffffffff8173f612: compat_SyS_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
long int compat_SyS_setsockopt(long int fd, long int level, long int optname, long int optval, long int optlen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/compat.c (ffffffff817ac79a)
Location: net/compat.c:380
Inline: True
Inline callers:
  - net/compat.c:compat_SyS_socketcall
```
**Symbols:**

```
ffffffff817ac250-ffffffff817ac322: compat_SyS_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
long int compat_SyS_setsockopt(long int fd, long int level, long int optname, long int optval, long int optlen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/compat.c (ffffffff817dbdba)
Location: net/compat.c:380
Inline: True
Inline callers:
  - net/compat.c:compat_SyS_socketcall
```
**Symbols:**

```
ffffffff817db870-ffffffff817db942: compat_SyS_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
long int compat_SyS_setsockopt(long int fd, long int level, long int optname, long int optval, long int optlen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/compat.c (ffffffff817fb3bb)
Location: net/compat.c:379
Inline: True
Inline callers:
  - net/compat.c:compat_SyS_socketcall
```
**Symbols:**

```
ffffffff817fae40-ffffffff817faf0d: compat_SyS_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
long int compat_SyS_setsockopt(long int fd, long int level, long int optname, long int optval, long int optlen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/compat.c (ffffffff81878d43)
Location: net/compat.c:386
Inline: True
Inline callers:
  - net/compat.c:compat_SyS_socketcall
```
**Symbols:**

```
ffffffff818787c0-ffffffff8187888d: compat_SyS_setsockopt (STB_GLOBAL)
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
