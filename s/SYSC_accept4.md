# Function: <code>SYSC_accept4</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long int SYSC_accept4(int fd, struct sockaddr *upeer_sockaddr, int *upeer_addrlen, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff816fd460)
Location: net/socket.c:1425
Inline: False
Direct callers:
  - net/socket.c:SyS_accept
  - net/socket.c:SyS_socketcall
```
**Symbols:**

```
ffffffff816fd460-ffffffff816fd662: SYSC_accept4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long int SYSC_accept4(int fd, struct sockaddr *upeer_sockaddr, int *upeer_addrlen, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81763f90)
Location: net/socket.c:1418
Inline: False
Direct callers:
  - net/socket.c:SyS_socketcall
  - net/socket.c:SyS_accept
```
**Symbols:**

```
ffffffff81763f90-ffffffff81764192: SYSC_accept4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long int SYSC_accept4(int fd, struct sockaddr *upeer_sockaddr, int *upeer_addrlen, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81790fc0)
Location: net/socket.c:1461
Inline: False
Direct callers:
  - net/socket.c:SyS_socketcall
  - net/socket.c:SyS_accept
```
**Symbols:**

```
ffffffff81790fc0-ffffffff817911c2: SYSC_accept4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long int SYSC_accept4(int fd, struct sockaddr *upeer_sockaddr, int *upeer_addrlen, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff817ae990)
Location: net/socket.c:1510
Inline: False
Direct callers:
  - net/socket.c:SyS_socketcall
  - net/socket.c:SyS_accept
```
**Symbols:**

```
ffffffff817ae990-ffffffff817aeb97: SYSC_accept4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long int SYSC_accept4(int fd, struct sockaddr *upeer_sockaddr, int *upeer_addrlen, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81826a70)
Location: net/socket.c:1504
Inline: False
Direct callers:
  - net/socket.c:SyS_socketcall
  - net/socket.c:SyS_accept
```
**Symbols:**

```
ffffffff81826a70-ffffffff81826c7b: SYSC_accept4 (STB_LOCAL)
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
