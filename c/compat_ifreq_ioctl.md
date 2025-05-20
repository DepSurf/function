# Function: <code>compat_ifreq_ioctl</code>

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
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81891d67)
Location: net/socket.c:2994
Inline: True
Inline callers:
  - net/socket.c:compat_sock_ioctl
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
In net/socket.c (ffffffff818dbcbf)
Location: net/socket.c:3173
Inline: True
Inline callers:
  - net/socket.c:compat_sock_ioctl
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
In net/socket.c (ffffffff8190e819)
Location: net/socket.c:3253
Inline: True
Inline callers:
  - net/socket.c:compat_sock_ioctl
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
In net/socket.c (ffffffff819e04cd)
Location: net/socket.c:3287
Inline: True
Inline callers:
  - net/socket.c:compat_sock_ioctl_trans
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int compat_ifreq_ioctl(struct net *net, struct socket *sock, unsigned int cmd, struct compat_ifreq *uifr32);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819dd890)
Location: net/socket.c:3281
Inline: False
Direct callers:
  - net/socket.c:compat_sock_ioctl_trans
```
**Symbols:**

```
ffffffff819dd890-ffffffff819dd9c9: compat_ifreq_ioctl (STB_LOCAL)
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
In net/socket.c (ffffffff819c5a92)
Location: net/socket.c:3267
Inline: True
Inline callers:
  - net/socket.c:compat_sock_ioctl_trans
```
</details>
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
In net/socket.c (ffff800010ba6fd8)
Location: net/socket.c:3253
Inline: True
Inline callers:
  - net/socket.c:compat_sock_ioctl
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
In net/socket.c (c000000000c7b26c)
Location: net/socket.c:3253
Inline: True
Inline callers:
  - net/socket.c:compat_sock_ioctl
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
In net/socket.c (ffffffff818ae819)
Location: net/socket.c:3253
Inline: True
Inline callers:
  - net/socket.c:compat_sock_ioctl
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
In net/socket.c (ffffffff81868769)
Location: net/socket.c:3253
Inline: True
Inline callers:
  - net/socket.c:compat_sock_ioctl
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
In net/socket.c (ffffffff818ff819)
Location: net/socket.c:3253
Inline: True
Inline callers:
  - net/socket.c:compat_sock_ioctl
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
In net/socket.c (ffffffff81920809)
Location: net/socket.c:3253
Inline: True
Inline callers:
  - net/socket.c:compat_sock_ioctl
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
