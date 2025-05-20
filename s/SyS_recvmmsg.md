# Function: <code>SyS_recvmmsg</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
long int SyS_recvmmsg(long int fd, long int mmsg, long int vlen, long int flags, long int timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff816ffa20)
Location: net/socket.c:2268
Inline: True
Inline callers:
  - net/socket.c:SyS_socketcall
```
**Symbols:**

```
ffffffff816ffa20-ffffffff816ffaf6: SyS_recvmmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
long int SyS_recvmmsg(long int fd, long int mmsg, long int vlen, long int flags, long int timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81766b15)
Location: net/socket.c:2270
Inline: True
Inline callers:
  - net/socket.c:SyS_socketcall
```
**Symbols:**

```
ffffffff817664c0-ffffffff81766596: SyS_recvmmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
long int SyS_recvmmsg(long int fd, long int mmsg, long int vlen, long int flags, long int timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81793b95)
Location: net/socket.c:2317
Inline: True
Inline callers:
  - net/socket.c:SyS_socketcall
```
**Symbols:**

```
ffffffff81793540-ffffffff81793616: SyS_recvmmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
long int SyS_recvmmsg(long int fd, long int mmsg, long int vlen, long int flags, long int timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff817b1b86)
Location: net/socket.c:2367
Inline: True
Inline callers:
  - net/socket.c:SyS_socketcall
```
**Symbols:**

```
ffffffff817b1990-ffffffff817b1a67: SyS_recvmmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
long int SyS_recvmmsg(long int fd, long int mmsg, long int vlen, long int flags, long int timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81829d2e)
Location: net/socket.c:2360
Inline: True
Inline callers:
  - net/socket.c:SyS_socketcall
```
**Symbols:**

```
ffffffff81829b30-ffffffff81829c07: SyS_recvmmsg (STB_GLOBAL)
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
