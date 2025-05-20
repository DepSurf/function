# Function: <code>sock_setbindtodevice_locked</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int sock_setbindtodevice_locked(struct sock *sk, int ifindex);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff818df680)
Location: net/core/sock.c:572
Inline: False
Direct callers:
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
```
**Symbols:**

```
ffffffff818df680-ffffffff818df6ff: sock_setbindtodevice_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int sock_setbindtodevice_locked(struct sock *sk, int ifindex);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81911850)
Location: net/core/sock.c:572
Inline: False
Direct callers:
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
```
**Symbols:**

```
ffffffff81911850-ffffffff819118cf: sock_setbindtodevice_locked (STB_LOCAL)
```
</details>
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
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int sock_setbindtodevice_locked(struct sock *sk, int ifindex);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffff800010baac60)
Location: net/core/sock.c:572
Inline: False
Direct callers:
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
```
**Symbols:**

```
ffff800010baac60-ffff800010baacfc: sock_setbindtodevice_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int sock_setbindtodevice_locked(struct sock *sk, int ifindex);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (c0cca1f8)
Location: net/core/sock.c:572
Inline: False
Direct callers:
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
```
**Symbols:**

```
c0cca1f8-c0cca29c: sock_setbindtodevice_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int sock_setbindtodevice_locked(struct sock *sk, int ifindex);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (c000000000c7e480)
Location: net/core/sock.c:572
Inline: False
Direct callers:
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
```
**Symbols:**

```
c000000000c7e480-c000000000c7e560: sock_setbindtodevice_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int sock_setbindtodevice_locked(struct sock *sk, int ifindex);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffe00073c896)
Location: net/core/sock.c:572
Inline: False
Direct callers:
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
```
**Symbols:**

```
ffffffe00073c896-ffffffe00073c904: sock_setbindtodevice_locked (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int sock_setbindtodevice_locked(struct sock *sk, int ifindex);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff818b1850)
Location: net/core/sock.c:572
Inline: False
Direct callers:
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
```
**Symbols:**

```
ffffffff818b1850-ffffffff818b18cf: sock_setbindtodevice_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int sock_setbindtodevice_locked(struct sock *sk, int ifindex);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff8186b7a0)
Location: net/core/sock.c:572
Inline: False
Direct callers:
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
```
**Symbols:**

```
ffffffff8186b7a0-ffffffff8186b81f: sock_setbindtodevice_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int sock_setbindtodevice_locked(struct sock *sk, int ifindex);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81902850)
Location: net/core/sock.c:572
Inline: False
Direct callers:
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
```
**Symbols:**

```
ffffffff81902850-ffffffff819028cf: sock_setbindtodevice_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int sock_setbindtodevice_locked(struct sock *sk, int ifindex);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff819237f0)
Location: net/core/sock.c:572
Inline: False
Direct callers:
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
```
**Symbols:**

```
ffffffff819237f0-ffffffff8192386f: sock_setbindtodevice_locked (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
