# Function: <code>__se_sys_socket</code>

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
In net/socket.c (ffffffff81872575)
Location: net/socket.c:1366
Inline: True
Inline callers:
  - net/socket.c:__ia32_sys_socket
  - net/socket.c:__x64_sys_socket
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
In net/socket.c (ffffffff81892ec5)
Location: net/socket.c:1353
Inline: True
Inline callers:
  - net/socket.c:__ia32_sys_socket
  - net/socket.c:__x64_sys_socket
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
In net/socket.c (ffffffff818dd1b5)
Location: net/socket.c:1518
Inline: True
Inline callers:
  - net/socket.c:__ia32_sys_socket
  - net/socket.c:__x64_sys_socket
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
In net/socket.c (ffffffff8190f215)
Location: net/socket.c:1518
Inline: True
Inline callers:
  - net/socket.c:__ia32_sys_socket
  - net/socket.c:__x64_sys_socket
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
In net/socket.c (ffffffff819e0b15)
Location: net/socket.c:1528
Inline: True
Inline callers:
  - net/socket.c:__ia32_sys_socket
  - net/socket.c:__x64_sys_socket
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
In net/socket.c (ffffffff819e0365)
Location: net/socket.c:1506
Inline: True
Inline callers:
  - net/socket.c:__ia32_sys_socket
  - net/socket.c:__x64_sys_socket
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
In net/socket.c (ffffffff819c63c5)
Location: net/socket.c:1497
Inline: True
Inline callers:
  - net/socket.c:__ia32_sys_socket
  - net/socket.c:__x64_sys_socket
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
In net/socket.c (ffffffff81a756e5)
Location: net/socket.c:1567
Inline: True
Inline callers:
  - net/socket.c:__ia32_sys_socket
  - net/socket.c:__x64_sys_socket
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
In net/socket.c (ffffffff81be8655)
Location: net/socket.c:1647
Inline: True
Inline callers:
  - net/socket.c:__ia32_sys_socket
  - net/socket.c:__x64_sys_socket
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
In net/socket.c (ffffffff81d94d55)
Location: net/socket.c:1647
Inline: True
Inline callers:
  - net/socket.c:__ia32_sys_socket
  - net/socket.c:__x64_sys_socket
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
In net/socket.c (ffffffff81e03395)
Location: net/socket.c:1676
Inline: True
Inline callers:
  - net/socket.c:__ia32_sys_socket
  - net/socket.c:__x64_sys_socket
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
In net/socket.c (ffffffff81ebfdc5)
Location: net/socket.c:1718
Inline: True
Inline callers:
  - net/socket.c:__ia32_sys_socket
  - net/socket.c:__x64_sys_socket
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
In net/socket.c (ffff800010ba7340)
Location: net/socket.c:1518
Inline: True
Inline callers:
  - net/socket.c:__arm64_sys_socket
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long int __se_sys_socket(long int family, long int type, long int protocol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (c0cc5e30)
Location: net/socket.c:1518
Inline: False
```
**Symbols:**

```
c0cc5e30-c0cc5e4c: __se_sys_socket (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int __se_sys_socket(long int family, long int type, long int protocol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (c000000000c7b6d0)
Location: net/socket.c:1518
Inline: False
```
**Symbols:**

```
c000000000c7b6d0-c000000000c7b70c: __se_sys_socket (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long int __se_sys_socket(long int family, long int type, long int protocol);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffe00073ae14)
Location: net/socket.c:1518
Inline: False
```
**Symbols:**

```
ffffffe00073ae14-ffffffe00073ae54: __se_sys_socket (STB_GLOBAL)
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
In net/socket.c (ffffffff818af215)
Location: net/socket.c:1518
Inline: True
Inline callers:
  - net/socket.c:__ia32_sys_socket
  - net/socket.c:__x64_sys_socket
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
In net/socket.c (ffffffff81869165)
Location: net/socket.c:1518
Inline: True
Inline callers:
  - net/socket.c:__ia32_sys_socket
  - net/socket.c:__x64_sys_socket
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
In net/socket.c (ffffffff81900215)
Location: net/socket.c:1518
Inline: True
Inline callers:
  - net/socket.c:__ia32_sys_socket
  - net/socket.c:__x64_sys_socket
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
In net/socket.c (ffffffff81921205)
Location: net/socket.c:1518
Inline: True
Inline callers:
  - net/socket.c:__ia32_sys_socket
  - net/socket.c:__x64_sys_socket
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
