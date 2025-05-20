# Function: <code>compat_SyS_recv</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
long int compat_SyS_recv(long int fd, long int buf, long int len, long int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/compat.c (ffffffff8173f760)
Location: net/compat.c:734
Inline: True
Inline callers:
  - net/compat.c:compat_SyS_socketcall
```
**Symbols:**

```
ffffffff8173f760-ffffffff8173f778: compat_SyS_recv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
long int compat_SyS_recv(long int fd, long int buf, long int len, long int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/compat.c (ffffffff817ac859)
Location: net/compat.c:748
Inline: True
Inline callers:
  - net/compat.c:compat_SyS_socketcall
```
**Symbols:**

```
ffffffff817ac470-ffffffff817ac488: compat_SyS_recv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
long int compat_SyS_recv(long int fd, long int buf, long int len, long int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/compat.c (ffffffff817dbe79)
Location: net/compat.c:748
Inline: True
Inline callers:
  - net/compat.c:compat_SyS_socketcall
```
**Symbols:**

```
ffffffff817dba90-ffffffff817dbaa8: compat_SyS_recv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
long int compat_SyS_recv(long int fd, long int buf, long int len, long int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/compat.c (ffffffff817fb349)
Location: net/compat.c:747
Inline: True
Inline callers:
  - net/compat.c:compat_SyS_socketcall
```
**Symbols:**

```
ffffffff817fb040-ffffffff817fb058: compat_SyS_recv (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
long int compat_SyS_recv(long int fd, long int buf, long int len, long int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/compat.c (ffffffff81878cd1)
Location: net/compat.c:754
Inline: True
Inline callers:
  - net/compat.c:compat_SyS_socketcall
```
**Symbols:**

```
ffffffff818789c0-ffffffff818789d8: compat_SyS_recv (STB_GLOBAL)
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
