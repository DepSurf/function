# Function: <code>compat_SyS_recvfrom</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
long int compat_SyS_recvfrom(long int fd, long int buf, long int len, long int flags, long int addr, long int addrlen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/compat.c (ffffffff8173f780)
Location: net/compat.c:739
Inline: True
Inline callers:
  - net/compat.c:compat_SyS_socketcall
```
**Symbols:**

```
ffffffff8173f780-ffffffff8173f798: compat_SyS_recvfrom (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
long int compat_SyS_recvfrom(long int fd, long int buf, long int len, long int flags, long int addr, long int addrlen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/compat.c (ffffffff817ac811)
Location: net/compat.c:753
Inline: True
Inline callers:
  - net/compat.c:compat_SyS_socketcall
```
**Symbols:**

```
ffffffff817ac490-ffffffff817ac4a8: compat_SyS_recvfrom (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
long int compat_SyS_recvfrom(long int fd, long int buf, long int len, long int flags, long int addr, long int addrlen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/compat.c (ffffffff817dbe31)
Location: net/compat.c:753
Inline: True
Inline callers:
  - net/compat.c:compat_SyS_socketcall
```
**Symbols:**

```
ffffffff817dbab0-ffffffff817dbac8: compat_SyS_recvfrom (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
long int compat_SyS_recvfrom(long int fd, long int buf, long int len, long int flags, long int addr, long int addrlen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/compat.c (ffffffff817fb385)
Location: net/compat.c:752
Inline: True
Inline callers:
  - net/compat.c:compat_SyS_socketcall
```
**Symbols:**

```
ffffffff817fb060-ffffffff817fb078: compat_SyS_recvfrom (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
long int compat_SyS_recvfrom(long int fd, long int buf, long int len, long int flags, long int addr, long int addrlen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/compat.c (ffffffff81878d0d)
Location: net/compat.c:759
Inline: True
Inline callers:
  - net/compat.c:compat_SyS_socketcall
```
**Symbols:**

```
ffffffff818789e0-ffffffff818789f8: compat_SyS_recvfrom (STB_GLOBAL)
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
