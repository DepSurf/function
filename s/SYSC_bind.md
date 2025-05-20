# Function: <code>SYSC_bind</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long int SYSC_bind(int fd, struct sockaddr *umyaddr, int addrlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff816fe360)
Location: net/socket.c:1363
Inline: False
Direct callers:
  - net/socket.c:SyS_socketcall
```
**Symbols:**

```
ffffffff816fe360-ffffffff816fe467: SYSC_bind (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long int SYSC_bind(int fd, struct sockaddr *umyaddr, int addrlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81764d70)
Location: net/socket.c:1356
Inline: False
Direct callers:
  - net/socket.c:SyS_socketcall
```
**Symbols:**

```
ffffffff81764d70-ffffffff81764e77: SYSC_bind (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long int SYSC_bind(int fd, struct sockaddr *umyaddr, int addrlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81791df0)
Location: net/socket.c:1399
Inline: False
Direct callers:
  - net/socket.c:SyS_socketcall
```
**Symbols:**

```
ffffffff81791df0-ffffffff81791ef7: SYSC_bind (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long int SYSC_bind(int fd, struct sockaddr *umyaddr, int addrlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff817b0270)
Location: net/socket.c:1448
Inline: False
Direct callers:
  - net/socket.c:SyS_socketcall
```
**Symbols:**

```
ffffffff817b0270-ffffffff817b0375: SYSC_bind (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long int SYSC_bind(int fd, struct sockaddr *umyaddr, int addrlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff818283f0)
Location: net/socket.c:1442
Inline: False
Direct callers:
  - net/socket.c:SyS_socketcall
```
**Symbols:**

```
ffffffff818283f0-ffffffff818284fb: SYSC_bind (STB_LOCAL)
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
