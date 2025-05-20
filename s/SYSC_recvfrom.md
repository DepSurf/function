# Function: <code>SYSC_recvfrom</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long int SYSC_recvfrom(int fd, void *ubuf, size_t size, unsigned int flags, struct sockaddr *addr, int *addr_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff816fdce0)
Location: net/socket.c:1675
Inline: False
Direct callers:
  - net/socket.c:SyS_socketcall
```
**Symbols:**

```
ffffffff816fdce0-ffffffff816fde37: SYSC_recvfrom (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long int SYSC_recvfrom(int fd, void *ubuf, size_t size, unsigned int flags, struct sockaddr *addr, int *addr_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81764800)
Location: net/socket.c:1668
Inline: False
Direct callers:
  - net/socket.c:SyS_socketcall
```
**Symbols:**

```
ffffffff81764800-ffffffff81764950: SYSC_recvfrom (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long int SYSC_recvfrom(int fd, void *ubuf, size_t size, unsigned int flags, struct sockaddr *addr, int *addr_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81791880)
Location: net/socket.c:1711
Inline: False
Direct callers:
  - net/socket.c:SyS_socketcall
```
**Symbols:**

```
ffffffff81791880-ffffffff817919d0: SYSC_recvfrom (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long int SYSC_recvfrom(int fd, void *ubuf, size_t size, unsigned int flags, struct sockaddr *addr, int *addr_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff817aed80)
Location: net/socket.c:1760
Inline: False
Direct callers:
  - net/socket.c:SyS_socketcall
```
**Symbols:**

```
ffffffff817aed80-ffffffff817aeeda: SYSC_recvfrom (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long int SYSC_recvfrom(int fd, void *ubuf, size_t size, unsigned int flags, struct sockaddr *addr, int *addr_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81826e70)
Location: net/socket.c:1753
Inline: False
Direct callers:
  - net/socket.c:SyS_socketcall
```
**Symbols:**

```
ffffffff81826e70-ffffffff81826fca: SYSC_recvfrom (STB_LOCAL)
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
