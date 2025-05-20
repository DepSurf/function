# Function: <code>__se_sys_accept</code>

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
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81872cf5)
Location: net/socket.c:1640
Inline: True
Inline callers:
  - net/socket.c:__ia32_sys_accept
  - net/socket.c:__x64_sys_accept
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
In net/socket.c (ffffffff81893645)
Location: net/socket.c:1627
Inline: True
Inline callers:
  - net/socket.c:__ia32_sys_accept
  - net/socket.c:__x64_sys_accept
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
In net/socket.c (ffffffff818dd955)
Location: net/socket.c:1792
Inline: True
Inline callers:
  - net/socket.c:__ia32_sys_accept
  - net/socket.c:__x64_sys_accept
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
In net/socket.c (ffffffff8190f9b5)
Location: net/socket.c:1792
Inline: True
Inline callers:
  - net/socket.c:__ia32_sys_accept
  - net/socket.c:__x64_sys_accept
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
In net/socket.c (ffffffff819e1345)
Location: net/socket.c:1821
Inline: True
Inline callers:
  - net/socket.c:__ia32_sys_accept
  - net/socket.c:__x64_sys_accept
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819e0b95)
Location: net/socket.c:1800
Inline: True
Inline callers:
  - net/socket.c:__ia32_sys_accept
  - net/socket.c:__x64_sys_accept
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819c6bd5)
Location: net/socket.c:1791
Inline: True
Inline callers:
  - net/socket.c:__ia32_sys_accept
  - net/socket.c:__x64_sys_accept
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81a75f25)
Location: net/socket.c:1864
Inline: True
Inline callers:
  - net/socket.c:__ia32_sys_accept
  - net/socket.c:__x64_sys_accept
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81be8fa5)
Location: net/socket.c:1944
Inline: True
Inline callers:
  - net/socket.c:__ia32_sys_accept
  - net/socket.c:__x64_sys_accept
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81d95705)
Location: net/socket.c:1941
Inline: True
Inline callers:
  - net/socket.c:__ia32_sys_accept
  - net/socket.c:__x64_sys_accept
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81e03d35)
Location: net/socket.c:1971
Inline: True
Inline callers:
  - net/socket.c:__ia32_sys_accept
  - net/socket.c:__x64_sys_accept
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81ec0765)
Location: net/socket.c:2013
Inline: True
Inline callers:
  - net/socket.c:__ia32_sys_accept
  - net/socket.c:__x64_sys_accept
```
</details>
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
In net/socket.c (ffff800010ba7b70)
Location: net/socket.c:1792
Inline: True
Inline callers:
  - net/socket.c:__arm64_sys_accept
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long int __se_sys_accept(long int fd, long int upeer_sockaddr, long int upeer_addrlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (c0cc6534)
Location: net/socket.c:1792
Inline: False
```
**Symbols:**

```
c0cc6534-c0cc6554: __se_sys_accept (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int __se_sys_accept(long int fd, long int upeer_sockaddr, long int upeer_addrlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (c000000000c7c160)
Location: net/socket.c:1792
Inline: False
```
**Symbols:**

```
c000000000c7c160-c000000000c7c198: __se_sys_accept (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long int __se_sys_accept(long int fd, long int upeer_sockaddr, long int upeer_addrlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffe00073b444)
Location: net/socket.c:1792
Inline: False
```
**Symbols:**

```
ffffffe00073b444-ffffffe00073b482: __se_sys_accept (STB_GLOBAL)
```
</details>
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
In net/socket.c (ffffffff818af9b5)
Location: net/socket.c:1792
Inline: True
Inline callers:
  - net/socket.c:__ia32_sys_accept
  - net/socket.c:__x64_sys_accept
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
In net/socket.c (ffffffff81869905)
Location: net/socket.c:1792
Inline: True
Inline callers:
  - net/socket.c:__ia32_sys_accept
  - net/socket.c:__x64_sys_accept
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
In net/socket.c (ffffffff819009b5)
Location: net/socket.c:1792
Inline: True
Inline callers:
  - net/socket.c:__ia32_sys_accept
  - net/socket.c:__x64_sys_accept
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
In net/socket.c (ffffffff819219a5)
Location: net/socket.c:1792
Inline: True
Inline callers:
  - net/socket.c:__ia32_sys_accept
  - net/socket.c:__x64_sys_accept
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
