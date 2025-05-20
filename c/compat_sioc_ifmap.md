# Function: <code>compat_sioc_ifmap</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff816fc235)
Location: net/socket.c:2903
Inline: True
Inline callers:
  - net/socket.c:compat_sock_ioctl_trans
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81762e90)
Location: net/socket.c:2905
Inline: True
Inline callers:
  - net/socket.c:compat_sock_ioctl_trans
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff8178ff80)
Location: net/socket.c:2952
Inline: True
Inline callers:
  - net/socket.c:compat_sock_ioctl_trans
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff817af90c)
Location: net/socket.c:3002
Inline: True
Inline callers:
  - net/socket.c:compat_sock_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff81827a72)
Location: net/socket.c:3004
Inline: True
Inline callers:
  - net/socket.c:compat_sock_ioctl
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
In net/socket.c (ffffffff8187202f)
Location: net/socket.c:2976
Inline: True
Inline callers:
  - net/socket.c:compat_sock_ioctl
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
In net/socket.c (ffffffff81891f69)
Location: net/socket.c:3042
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
In net/socket.c (ffffffff818dbfbf)
Location: net/socket.c:3221
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
In net/socket.c (ffffffff8190ea32)
Location: net/socket.c:3301
Inline: True
Inline callers:
  - net/socket.c:compat_sock_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int compat_sioc_ifmap(struct net *net, unsigned int cmd, struct compat_ifreq *uifr32);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819ddbc0)
Location: net/socket.c:3335
Inline: False
Direct callers:
  - net/socket.c:compat_sock_ioctl_trans
```
**Symbols:**

```
ffffffff819ddbc0-ffffffff819ddd66: compat_sioc_ifmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int compat_sioc_ifmap(struct net *net, unsigned int cmd, struct compat_ifreq *uifr32);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffff819dd5b0)
Location: net/socket.c:3329
Inline: False
Direct callers:
  - net/socket.c:compat_sock_ioctl_trans
```
**Symbols:**

```
ffffffff819dd5b0-ffffffff819dd742: compat_sioc_ifmap (STB_LOCAL)
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
In net/socket.c (ffffffff819c5e36)
Location: net/socket.c:3315
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
<summary>In <code>arm64</code>: ✅</summary>

```c
int compat_sioc_ifmap(struct net *net, unsigned int cmd, struct compat_ifreq *uifr32);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffff800010ba2e08)
Location: net/socket.c:3301
Inline: False
Direct callers:
  - net/socket.c:compat_sock_ioctl
```
**Symbols:**

```
ffff800010ba2e08-ffff800010ba36d8: compat_sioc_ifmap (STB_LOCAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int compat_sioc_ifmap(struct net *net, unsigned int cmd, struct compat_ifreq *uifr32);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (c000000000c790b0)
Location: net/socket.c:3301
Inline: False
Direct callers:
  - net/socket.c:compat_sock_ioctl
```
**Symbols:**

```
c000000000c790b0-c000000000c79874: compat_sioc_ifmap (STB_LOCAL)
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
In net/socket.c (ffffffff818aea32)
Location: net/socket.c:3301
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
In net/socket.c (ffffffff81868982)
Location: net/socket.c:3301
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
In net/socket.c (ffffffff818ffa32)
Location: net/socket.c:3301
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
In net/socket.c (ffffffff81920a22)
Location: net/socket.c:3301
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
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
</ul>
