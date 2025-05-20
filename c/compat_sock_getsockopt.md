# Function: <code>compat_sock_getsockopt</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int compat_sock_getsockopt(struct socket *sock, int level, int optname, char *optval, int *optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/compat.c (ffffffff8173e550)
Location: net/compat.c:422
Inline: False
Direct callers:
  - net/compat.c:compat_SyS_socketcall
```
**Symbols:**

```
ffffffff8173e550-ffffffff8173e669: compat_sock_getsockopt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int compat_sock_getsockopt(struct socket *sock, int level, int optname, char *optval, int *optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/compat.c (ffffffff817ab260)
Location: net/compat.c:436
Inline: False
Direct callers:
  - net/compat.c:compat_SyS_socketcall
```
**Symbols:**

```
ffffffff817ab260-ffffffff817ab377: compat_sock_getsockopt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int compat_sock_getsockopt(struct socket *sock, int level, int optname, char *optval, int *optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/compat.c (ffffffff817da880)
Location: net/compat.c:436
Inline: False
Direct callers:
  - net/compat.c:compat_SyS_socketcall
```
**Symbols:**

```
ffffffff817da880-ffffffff817da997: compat_sock_getsockopt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/compat.c (ffffffff817f9db0)
Location: net/compat.c:435
Inline: True
Direct callers:
  - net/compat.c:compat_SyS_socketcall
```
**Symbols:**

```
ffffffff817f9db0-ffffffff817f9ed7: compat_sock_getsockopt.constprop.4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/compat.c (ffffffff818776c0)
Location: net/compat.c:442
Inline: True
Direct callers:
  - net/compat.c:compat_SyS_socketcall
```
**Symbols:**

```
ffffffff818776c0-ffffffff818777f9: compat_sock_getsockopt.constprop.4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/compat.c (ffffffff818c9176)
Location: net/compat.c:449
Inline: True
Inline callers:
  - net/compat.c:__compat_sys_getsockopt
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/compat.c (ffffffff818f4026)
Location: net/compat.c:453
Inline: True
Inline callers:
  - net/compat.c:__compat_sys_getsockopt
```
</details>
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
</ul>
