# Function: <code>compat_sock_setsockopt</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int compat_sock_setsockopt(struct socket *sock, int level, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/compat.c (ffffffff8173e670)
Location: net/compat.c:354
Inline: False
Direct callers:
  - net/compat.c:compat_SyS_socketcall
```
**Symbols:**

```
ffffffff8173e670-ffffffff8173e815: compat_sock_setsockopt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int compat_sock_setsockopt(struct socket *sock, int level, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/compat.c (ffffffff817ab380)
Location: net/compat.c:367
Inline: False
Direct callers:
  - net/compat.c:compat_SyS_socketcall
```
**Symbols:**

```
ffffffff817ab380-ffffffff817ab4a2: compat_sock_setsockopt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int compat_sock_setsockopt(struct socket *sock, int level, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/compat.c (ffffffff817da9a0)
Location: net/compat.c:367
Inline: False
Direct callers:
  - net/compat.c:compat_SyS_socketcall
```
**Symbols:**

```
ffffffff817da9a0-ffffffff817daac2: compat_sock_setsockopt (STB_LOCAL)
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
In net/compat.c (ffffffff817f9ee0)
Location: net/compat.c:366
Inline: True
Direct callers:
  - net/compat.c:compat_SyS_socketcall
```
**Symbols:**

```
ffffffff817f9ee0-ffffffff817fa01e: compat_sock_setsockopt.constprop.6 (STB_LOCAL)
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
In net/compat.c (ffffffff81877800)
Location: net/compat.c:373
Inline: True
Direct callers:
  - net/compat.c:compat_SyS_socketcall
```
**Symbols:**

```
ffffffff81877800-ffffffff81877956: compat_sock_setsockopt.constprop.6 (STB_LOCAL)
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
In net/compat.c (ffffffff818c9395)
Location: net/compat.c:373
Inline: True
Inline callers:
  - net/compat.c:__compat_sys_setsockopt
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
In net/compat.c (ffffffff818f425e)
Location: net/compat.c:373
Inline: True
Inline callers:
  - net/compat.c:__compat_sys_setsockopt
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/compat.c (ffffffff81953dad)
Location: net/compat.c:353
Inline: True
Inline callers:
  - net/compat.c:__compat_sys_setsockopt
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/compat.c (ffffffff8198a2fd)
Location: net/compat.c:353
Inline: True
Inline callers:
  - net/compat.c:__compat_sys_setsockopt
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/compat.c (ffffffff81a6268d)
Location: net/compat.c:372
Inline: True
Inline callers:
  - net/compat.c:__compat_sys_setsockopt
```
</details>
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
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/compat.c (ffff800010c32dc8)
Location: net/compat.c:353
Inline: True
Inline callers:
  - net/compat.c:__compat_sys_setsockopt
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/compat.c (c000000000d2bdb0)
Location: net/compat.c:353
Inline: True
Inline callers:
  - net/compat.c:__compat_sys_setsockopt
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/compat.c (ffffffff8192a16d)
Location: net/compat.c:353
Inline: True
Inline callers:
  - net/compat.c:__compat_sys_setsockopt
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/compat.c (ffffffff818e3f1d)
Location: net/compat.c:353
Inline: True
Inline callers:
  - net/compat.c:__compat_sys_setsockopt
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/compat.c (ffffffff8197b2fd)
Location: net/compat.c:353
Inline: True
Inline callers:
  - net/compat.c:__compat_sys_setsockopt
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/compat.c (ffffffff8199d84d)
Location: net/compat.c:353
Inline: True
Inline callers:
  - net/compat.c:__compat_sys_setsockopt
```
</details>
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
