# Function: <code>compat_SyS_recvmsg</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
long int compat_SyS_recvmsg(long int fd, long int msg, long int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/compat.c (ffffffff8173f740)
Location: net/compat.c:729
Inline: True
Inline callers:
  - net/compat.c:compat_SyS_socketcall
```
**Symbols:**

```
ffffffff8173f740-ffffffff8173f756: compat_SyS_recvmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
long int compat_SyS_recvmsg(long int fd, long int msg, long int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/compat.c (ffffffff817ac6eb)
Location: net/compat.c:743
Inline: True
Inline callers:
  - net/compat.c:compat_SyS_socketcall
```
**Symbols:**

```
ffffffff817ac450-ffffffff817ac466: compat_SyS_recvmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
long int compat_SyS_recvmsg(long int fd, long int msg, long int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/compat.c (ffffffff817dbd0b)
Location: net/compat.c:743
Inline: True
Inline callers:
  - net/compat.c:compat_SyS_socketcall
```
**Symbols:**

```
ffffffff817dba70-ffffffff817dba86: compat_SyS_recvmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
long int compat_SyS_recvmsg(long int fd, long int msg, long int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/compat.c (ffffffff817fb4d1)
Location: net/compat.c:742
Inline: True
Inline callers:
  - net/compat.c:compat_SyS_socketcall
```
**Symbols:**

```
ffffffff817fb020-ffffffff817fb036: compat_SyS_recvmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
long int compat_SyS_recvmsg(long int fd, long int msg, long int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/compat.c (ffffffff81878e5d)
Location: net/compat.c:749
Inline: True
Inline callers:
  - net/compat.c:compat_SyS_socketcall
```
**Symbols:**

```
ffffffff818789a0-ffffffff818789b6: compat_SyS_recvmsg (STB_GLOBAL)
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
