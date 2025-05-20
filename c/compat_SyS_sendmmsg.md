# Function: <code>compat_SyS_sendmmsg</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
long int compat_SyS_sendmmsg(long int fd, long int mmsg, long int vlen, long int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/compat.c (ffffffff8173f720)
Location: net/compat.c:722
Inline: True
Inline callers:
  - net/compat.c:compat_SyS_socketcall
```
**Symbols:**

```
ffffffff8173f720-ffffffff8173f738: compat_SyS_sendmmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
long int compat_SyS_sendmmsg(long int fd, long int mmsg, long int vlen, long int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/compat.c (ffffffff817ac655)
Location: net/compat.c:736
Inline: True
Inline callers:
  - net/compat.c:compat_SyS_socketcall
```
**Symbols:**

```
ffffffff817ac430-ffffffff817ac448: compat_SyS_sendmmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
long int compat_SyS_sendmmsg(long int fd, long int mmsg, long int vlen, long int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/compat.c (ffffffff817dbc75)
Location: net/compat.c:736
Inline: True
Inline callers:
  - net/compat.c:compat_SyS_socketcall
```
**Symbols:**

```
ffffffff817dba50-ffffffff817dba68: compat_SyS_sendmmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
long int compat_SyS_sendmmsg(long int fd, long int mmsg, long int vlen, long int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/compat.c (ffffffff817fb278)
Location: net/compat.c:735
Inline: True
Inline callers:
  - net/compat.c:compat_SyS_socketcall
```
**Symbols:**

```
ffffffff817fb000-ffffffff817fb018: compat_SyS_sendmmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
long int compat_SyS_sendmmsg(long int fd, long int mmsg, long int vlen, long int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/compat.c (ffffffff81878bfd)
Location: net/compat.c:742
Inline: True
Inline callers:
  - net/compat.c:compat_SyS_socketcall
```
**Symbols:**

```
ffffffff81878980-ffffffff81878998: compat_SyS_sendmmsg (STB_GLOBAL)
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
