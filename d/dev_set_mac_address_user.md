# Function: <code>dev_set_mac_address_user</code>

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
int dev_set_mac_address_user(struct net_device *dev, struct sockaddr *sa, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a01ce0)
Location: net/core/dev.c:8793
Inline: False
Direct callers:
  - net/core/rtnetlink.c:do_setlink
  - net/core/dev_ioctl.c:dev_ifsioc
```
**Symbols:**

```
ffffffff81a01ce0-ffffffff81a01d2c: dev_set_mac_address_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int dev_set_mac_address_user(struct net_device *dev, struct sockaddr *sa, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819e84b0)
Location: net/core/dev.c:9052
Inline: False
Direct callers:
  - drivers/net/tun.c:__tun_chr_ioctl
  - net/core/rtnetlink.c:do_setlink
  - net/core/dev_ioctl.c:dev_ifsioc
```
**Symbols:**

```
ffffffff819e84b0-ffffffff819e84fc: dev_set_mac_address_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int dev_set_mac_address_user(struct net_device *dev, struct sockaddr *sa, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a994b0)
Location: net/core/dev.c:9042
Inline: False
Direct callers:
  - drivers/net/tun.c:__tun_chr_ioctl
  - net/core/rtnetlink.c:do_setlink
  - net/core/dev_ioctl.c:dev_ifsioc
```
**Symbols:**

```
ffffffff81a994b0-ffffffff81a994fc: dev_set_mac_address_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int dev_set_mac_address_user(struct net_device *dev, struct sockaddr *sa, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81c11540)
Location: net/core/dev.c:8806
Inline: False
Direct callers:
  - drivers/net/tun.c:__tun_chr_ioctl
  - net/core/rtnetlink.c:do_setlink
  - net/core/dev_ioctl.c:dev_ifsioc
```
**Symbols:**

```
ffffffff81c11540-ffffffff81c11592: dev_set_mac_address_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int dev_set_mac_address_user(struct net_device *dev, struct sockaddr *sa, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81dc1a80)
Location: net/core/dev.c:8793
Inline: False
Direct callers:
  - drivers/net/tun.c:__tun_chr_ioctl
  - net/core/rtnetlink.c:do_setlink
  - net/core/dev_ioctl.c:dev_ifsioc
```
**Symbols:**

```
ffffffff81dc1a80-ffffffff81dc1ad2: dev_set_mac_address_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int dev_set_mac_address_user(struct net_device *dev, struct sockaddr *sa, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81e3a010)
Location: net/core/dev.c:8801
Inline: False
Direct callers:
  - drivers/net/tun.c:__tun_chr_ioctl
  - net/core/rtnetlink.c:do_setlink
  - net/core/dev_ioctl.c:dev_ifsioc
```
**Symbols:**

```
ffffffff81e3a010-ffffffff81e3a062: dev_set_mac_address_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int dev_set_mac_address_user(struct net_device *dev, struct sockaddr *sa, struct netlink_ext_ack *extack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81ef8300)
Location: net/core/dev.c:8919
Inline: False
Direct callers:
  - drivers/net/tun.c:__tun_chr_ioctl
  - net/core/rtnetlink.c:do_setlink
  - net/core/dev_ioctl.c:dev_ifsioc
```
**Symbols:**

```
ffffffff81ef8300-ffffffff81ef8352: dev_set_mac_address_user (STB_GLOBAL)
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
