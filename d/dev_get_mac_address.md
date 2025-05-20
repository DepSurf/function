# Function: <code>dev_get_mac_address</code>

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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int dev_get_mac_address(struct sockaddr *sa, struct net *net, char *dev_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a027b0)
Location: net/core/dev.c:8805
Inline: False
Direct callers:
  - net/core/dev_ioctl.c:dev_ioctl
```
**Symbols:**

```
ffffffff81a027b0-ffffffff81a028eb: dev_get_mac_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int dev_get_mac_address(struct sockaddr *sa, struct net *net, char *dev_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819e9320)
Location: net/core/dev.c:9064
Inline: False
Direct callers:
  - drivers/net/tun.c:__tun_chr_ioctl
  - net/core/dev_ioctl.c:dev_ioctl
```
**Symbols:**

```
ffffffff819e9320-ffffffff819e9450: dev_get_mac_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int dev_get_mac_address(struct sockaddr *sa, struct net *net, char *dev_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a9a150)
Location: net/core/dev.c:9054
Inline: False
Direct callers:
  - drivers/net/tun.c:__tun_chr_ioctl
  - net/core/dev_ioctl.c:dev_ioctl
```
**Symbols:**

```
ffffffff81a9a150-ffffffff81a9a280: dev_get_mac_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int dev_get_mac_address(struct sockaddr *sa, struct net *net, char *dev_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:8818
Inline: False
Direct callers:
  - drivers/net/tun.c:__tun_chr_ioctl
  - net/core/dev_ioctl.c:dev_ioctl
```
**Symbols:**

```
ffffffff81f01cdf-ffffffff81f01ceb: dev_get_mac_address.cold (STB_LOCAL)
ffffffff81c0c1a0-ffffffff81c0c327: dev_get_mac_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int dev_get_mac_address(struct sockaddr *sa, struct net *net, char *dev_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81dc49b0)
Location: net/core/dev.c:8805
Inline: False
Direct callers:
  - drivers/net/tun.c:__tun_chr_ioctl
  - net/core/dev_ioctl.c:dev_ioctl
```
**Symbols:**

```
ffffffff81dc49b0-ffffffff81dc4b43: dev_get_mac_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int dev_get_mac_address(struct sockaddr *sa, struct net *net, char *dev_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81e36190)
Location: net/core/dev.c:8813
Inline: False
Direct callers:
  - drivers/net/tun.c:__tun_chr_ioctl
  - net/core/dev_ioctl.c:dev_ioctl
```
**Symbols:**

```
ffffffff81e36190-ffffffff81e36323: dev_get_mac_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int dev_get_mac_address(struct sockaddr *sa, struct net *net, char *dev_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81ef4450)
Location: net/core/dev.c:8931
Inline: False
Direct callers:
  - drivers/net/tun.c:__tun_chr_ioctl
  - net/core/dev_ioctl.c:dev_ioctl
```
**Symbols:**

```
ffffffff81ef4450-ffffffff81ef45e3: dev_get_mac_address (STB_GLOBAL)
```
</details>
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
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
