# Function: <code>SYSC_getpeername</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long int SYSC_getpeername(int fd, struct sockaddr *usockaddr, int *usockaddr_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff816fd750)
Location: net/socket.c:1587
Inline: False
Direct callers:
  - net/socket.c:SyS_socketcall
```
**Symbols:**

```
ffffffff816fd750-ffffffff816fd848: SYSC_getpeername (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long int SYSC_getpeername(int fd, struct sockaddr *usockaddr, int *usockaddr_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81764280)
Location: net/socket.c:1580
Inline: False
Direct callers:
  - net/socket.c:SyS_socketcall
```
**Symbols:**

```
ffffffff81764280-ffffffff81764378: SYSC_getpeername (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long int SYSC_getpeername(int fd, struct sockaddr *usockaddr, int *usockaddr_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff817912b0)
Location: net/socket.c:1623
Inline: False
Direct callers:
  - net/socket.c:SyS_socketcall
```
**Symbols:**

```
ffffffff817912b0-ffffffff817913a8: SYSC_getpeername (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long int SYSC_getpeername(int fd, struct sockaddr *usockaddr, int *usockaddr_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff817aec80)
Location: net/socket.c:1672
Inline: False
Direct callers:
  - net/socket.c:SyS_socketcall
```
**Symbols:**

```
ffffffff817aec80-ffffffff817aed78: SYSC_getpeername (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long int SYSC_getpeername(int fd, struct sockaddr *usockaddr, int *usockaddr_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81826d70)
Location: net/socket.c:1665
Inline: False
Direct callers:
  - net/socket.c:SyS_socketcall
```
**Symbols:**

```
ffffffff81826d70-ffffffff81826e6e: SYSC_getpeername (STB_LOCAL)
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
