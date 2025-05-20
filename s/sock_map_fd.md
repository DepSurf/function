# Function: <code>sock_map_fd</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int sock_map_fd(struct socket *sock, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff816fd380)
Location: net/socket.c:391
Inline: False
Direct callers:
  - net/socket.c:SyS_socketcall
```
**Symbols:**

```
ffffffff816fd380-ffffffff816fd3e2: sock_map_fd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int sock_map_fd(struct socket *sock, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81763eb0)
Location: net/socket.c:391
Inline: False
Direct callers:
  - net/socket.c:SyS_socketcall
```
**Symbols:**

```
ffffffff81763eb0-ffffffff81763f14: sock_map_fd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int sock_map_fd(struct socket *sock, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81790ee0)
Location: net/socket.c:433
Inline: False
Direct callers:
  - net/socket.c:SyS_socketcall
```
**Symbols:**

```
ffffffff81790ee0-ffffffff81790f44: sock_map_fd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int sock_map_fd(struct socket *sock, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff817ae800)
Location: net/socket.c:431
Inline: False
Direct callers:
  - net/socket.c:SyS_socketcall
```
**Symbols:**

```
ffffffff817ae800-ffffffff817ae864: sock_map_fd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int sock_map_fd(struct socket *sock, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff818268d0)
Location: net/socket.c:435
Inline: False
Direct callers:
  - net/socket.c:SyS_socketcall
```
**Symbols:**

```
ffffffff818268d0-ffffffff81826949: sock_map_fd (STB_LOCAL)
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
In net/socket.c (ffffffff818724cb)
Location: net/socket.c:429
Inline: True
Inline callers:
  - net/socket.c:__sys_socket
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
In net/socket.c (ffffffff81892e1b)
Location: net/socket.c:408
Inline: True
Inline callers:
  - net/socket.c:__sys_socket
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
In net/socket.c (ffffffff818dd10f)
Location: net/socket.c:411
Inline: True
Inline callers:
  - net/socket.c:__sys_socket
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
In net/socket.c (ffffffff8190f16f)
Location: net/socket.c:411
Inline: True
Inline callers:
  - net/socket.c:__sys_socket
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
In net/socket.c (ffffffff819e0a6f)
Location: net/socket.c:426
Inline: True
Inline callers:
  - net/socket.c:__sys_socket
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
In net/socket.c (ffffffff819e02bf)
Location: net/socket.c:426
Inline: True
Inline callers:
  - net/socket.c:__sys_socket
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
In net/socket.c (ffffffff819c631f)
Location: net/socket.c:427
Inline: True
Inline callers:
  - net/socket.c:__sys_socket
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
In net/socket.c (ffffffff81a7563f)
Location: net/socket.c:477
Inline: True
Inline callers:
  - net/socket.c:__sys_socket
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
In net/socket.c (ffffffff81be85b4)
Location: net/socket.c:478
Inline: True
Inline callers:
  - net/socket.c:__sys_socket
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
In net/socket.c (ffffffff81d94c94)
Location: net/socket.c:480
Inline: True
Inline callers:
  - net/socket.c:__sys_socket
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
In net/socket.c (ffffffff81e032d4)
Location: net/socket.c:483
Inline: True
Inline callers:
  - net/socket.c:__sys_socket
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
In net/socket.c (ffffffff81ebfd0a)
Location: net/socket.c:485
Inline: True
Inline callers:
  - net/socket.c:__sys_socket
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
In net/socket.c (ffff800010ba72a0)
Location: net/socket.c:411
Inline: True
Inline callers:
  - net/socket.c:__sys_socket
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/socket.c (c0cc5dac)
Location: net/socket.c:411
Inline: True
Inline callers:
  - net/socket.c:__sys_socket
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/socket.c (c000000000c7b5e0)
Location: net/socket.c:411
Inline: True
Inline callers:
  - net/socket.c:__sys_socket
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffe00073ada2)
Location: net/socket.c:411
Inline: True
Inline callers:
  - net/socket.c:__sys_socket
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
In net/socket.c (ffffffff818af16f)
Location: net/socket.c:411
Inline: True
Inline callers:
  - net/socket.c:__sys_socket
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
In net/socket.c (ffffffff818690bf)
Location: net/socket.c:411
Inline: True
Inline callers:
  - net/socket.c:__sys_socket
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
In net/socket.c (ffffffff8190016f)
Location: net/socket.c:411
Inline: True
Inline callers:
  - net/socket.c:__sys_socket
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
In net/socket.c (ffffffff8192115f)
Location: net/socket.c:411
Inline: True
Inline callers:
  - net/socket.c:__sys_socket
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
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
</ul>
