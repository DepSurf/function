# Function: <code>ncsi_unregister_netlink</code>

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
<summary>In <code>4.18</code>: ✅</summary>

```c
int ncsi_unregister_netlink(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-netlink.c (ffffffff819cb410)
Location: net/ncsi/ncsi-netlink.c:411
Inline: False
Direct callers:
  - net/ncsi/ncsi-manage.c:ncsi_unregister_dev
```
**Symbols:**

```
ffffffff819cb410-ffffffff819cb454: ncsi_unregister_netlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ncsi_unregister_netlink(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-netlink.c (ffffffff81a044d0)
Location: net/ncsi/ncsi-netlink.c:779
Inline: False
Direct callers:
  - net/ncsi/ncsi-manage.c:ncsi_unregister_dev
```
**Symbols:**

```
ffffffff81a044d0-ffffffff81a04514: ncsi_unregister_netlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int ncsi_unregister_netlink(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ncsi/ncsi-netlink.c (0)
Location: net/ncsi/ncsi-netlink.c:780
Inline: False
Direct callers:
  - net/ncsi/ncsi-manage.c:ncsi_unregister_dev
```
**Symbols:**

```
ffffffff81a739ef-ffffffff81a73a09: ncsi_unregister_netlink.cold (STB_LOCAL)
ffffffff81a73710-ffffffff81a7373e: ncsi_unregister_netlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int ncsi_unregister_netlink(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ncsi/ncsi-netlink.c (0)
Location: net/ncsi/ncsi-netlink.c:780
Inline: False
Direct callers:
  - net/ncsi/ncsi-manage.c:ncsi_unregister_dev
```
**Symbols:**

```
ffffffff81aaa0e2-ffffffff81aaa0fc: ncsi_unregister_netlink.cold (STB_LOCAL)
ffffffff81aa9f00-ffffffff81aa9f2e: ncsi_unregister_netlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int ncsi_unregister_netlink(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ncsi/ncsi-netlink.c (0)
Location: net/ncsi/ncsi-netlink.c:780
Inline: False
Direct callers:
  - net/ncsi/ncsi-manage.c:ncsi_unregister_dev
```
**Symbols:**

```
ffffffff81ba642b-ffffffff81ba6445: ncsi_unregister_netlink.cold (STB_LOCAL)
ffffffff81ba61b0-ffffffff81ba61dc: ncsi_unregister_netlink (STB_GLOBAL)
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
<summary>In <code>arm64</code>: ✅</summary>

```c
int ncsi_unregister_netlink(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-netlink.c (ffff800010d7dc18)
Location: net/ncsi/ncsi-netlink.c:780
Inline: False
Direct callers:
  - net/ncsi/ncsi-manage.c:ncsi_unregister_dev
```
**Symbols:**

```
ffff800010d7dc18-ffff800010d7dc68: ncsi_unregister_netlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ncsi_unregister_netlink(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-netlink.c (c0e78764)
Location: net/ncsi/ncsi-netlink.c:780
Inline: False
Direct callers:
  - net/ncsi/ncsi-manage.c:ncsi_unregister_dev
```
**Symbols:**

```
c0e78764-c0e787ac: ncsi_unregister_netlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ncsi_unregister_netlink(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-netlink.c (c000000000ebd820)
Location: net/ncsi/ncsi-netlink.c:780
Inline: False
Direct callers:
  - net/ncsi/ncsi-manage.c:ncsi_unregister_dev
```
**Symbols:**

```
c000000000ebd820-c000000000ebd894: ncsi_unregister_netlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ncsi_unregister_netlink(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-netlink.c (ffffffe0008ab3ca)
Location: net/ncsi/ncsi-netlink.c:780
Inline: False
Direct callers:
  - net/ncsi/ncsi-manage.c:ncsi_unregister_dev
```
**Symbols:**

```
ffffffe0008ab3ca-ffffffe0008ab418: ncsi_unregister_netlink (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int ncsi_unregister_netlink(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ncsi/ncsi-netlink.c (0)
Location: net/ncsi/ncsi-netlink.c:780
Inline: False
Direct callers:
  - net/ncsi/ncsi-manage.c:ncsi_unregister_dev
```
**Symbols:**

```
ffffffff81a49472-ffffffff81a4948c: ncsi_unregister_netlink.cold (STB_LOCAL)
ffffffff81a49290-ffffffff81a492be: ncsi_unregister_netlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int ncsi_unregister_netlink(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ncsi/ncsi-netlink.c (0)
Location: net/ncsi/ncsi-netlink.c:780
Inline: False
Direct callers:
  - net/ncsi/ncsi-manage.c:ncsi_unregister_dev
```
**Symbols:**

```
ffffffff81a06062-ffffffff81a0607c: ncsi_unregister_netlink.cold (STB_LOCAL)
ffffffff81a05e80-ffffffff81a05eae: ncsi_unregister_netlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int ncsi_unregister_netlink(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ncsi/ncsi-netlink.c (0)
Location: net/ncsi/ncsi-netlink.c:780
Inline: False
Direct callers:
  - net/ncsi/ncsi-manage.c:ncsi_unregister_dev
```
**Symbols:**

```
ffffffff81ab5322-ffffffff81ab533c: ncsi_unregister_netlink.cold (STB_LOCAL)
ffffffff81ab5140-ffffffff81ab516e: ncsi_unregister_netlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int ncsi_unregister_netlink(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ncsi/ncsi-netlink.c (0)
Location: net/ncsi/ncsi-netlink.c:780
Inline: False
Direct callers:
  - net/ncsi/ncsi-manage.c:ncsi_unregister_dev
```
**Symbols:**

```
ffffffff81ac16c2-ffffffff81ac16dc: ncsi_unregister_netlink.cold (STB_LOCAL)
ffffffff81ac14e0-ffffffff81ac150e: ncsi_unregister_netlink (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
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
