# Function: <code>tun_net_change_carrier</code>

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
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int tun_net_change_carrier(struct net_device *dev, bool new_carrier);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff81764989)
Location: drivers/net/tun.c:1258
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
```
**Symbols:**

```
ffffffff8175ffb0-ffffffff8175ffe1: tun_net_change_carrier (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int tun_net_change_carrier(struct net_device *dev, bool new_carrier);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff817a2838)
Location: drivers/net/tun.c:1246
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
```
**Symbols:**

```
ffffffff8179d770-ffffffff8179d7a1: tun_net_change_carrier (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int tun_net_change_carrier(struct net_device *dev, bool new_carrier);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff817c49c8)
Location: drivers/net/tun.c:1246
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
```
**Symbols:**

```
ffffffff817c1210-ffffffff817c1241: tun_net_change_carrier (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int tun_net_change_carrier(struct net_device *dev, bool new_carrier);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff8188a770)
Location: drivers/net/tun.c:1212
Inline: True
```
**Symbols:**

```
ffffffff8188a770-ffffffff8188a7a1: tun_net_change_carrier (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int tun_net_change_carrier(struct net_device *dev, bool new_carrier);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff818988a0)
Location: drivers/net/tun.c:1143
Inline: True
```
**Symbols:**

```
ffffffff818988a0-ffffffff818988d1: tun_net_change_carrier (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int tun_net_change_carrier(struct net_device *dev, bool new_carrier);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff81881059)
Location: drivers/net/tun.c:1151
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
```
**Symbols:**

```
ffffffff8187afe0-ffffffff8187b011: tun_net_change_carrier (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int tun_net_change_carrier(struct net_device *dev, bool new_carrier);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff81912987)
Location: drivers/net/tun.c:1205
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
```
**Symbols:**

```
ffffffff8190c4e0-ffffffff8190c511: tun_net_change_carrier (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int tun_net_change_carrier(struct net_device *dev, bool new_carrier);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff81a65896)
Location: drivers/net/tun.c:1233
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_chr_ioctl
```
**Symbols:**

```
ffffffff81a5f9a0-ffffffff81a5f9e1: tun_net_change_carrier (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int tun_net_change_carrier(struct net_device *dev, bool new_carrier);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff81bf0bb3)
Location: drivers/net/tun.c:1235
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_chr_ioctl
```
**Symbols:**

```
ffffffff81beae70-ffffffff81beaeb1: tun_net_change_carrier (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int tun_net_change_carrier(struct net_device *dev, bool new_carrier);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff81c49054)
Location: drivers/net/tun.c:1235
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_chr_ioctl
```
**Symbols:**

```
ffffffff81c432b0-ffffffff81c432f1: tun_net_change_carrier (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int tun_net_change_carrier(struct net_device *dev, bool new_carrier);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff81cfe9b4)
Location: drivers/net/tun.c:1236
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_chr_ioctl
```
**Symbols:**

```
ffffffff81cf8f50-ffffffff81cf8f91: tun_net_change_carrier (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int tun_net_change_carrier(struct net_device *dev, bool new_carrier);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffff8000109dfc44)
Location: drivers/net/tun.c:1246
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
```
**Symbols:**

```
ffff8000109db410-ffff8000109db470: tun_net_change_carrier (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int tun_net_change_carrier(struct net_device *dev, bool new_carrier);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (c0ac288c)
Location: drivers/net/tun.c:1246
Inline: True
```
**Symbols:**

```
c0ac288c-c0ac28d4: tun_net_change_carrier (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int tun_net_change_carrier(struct net_device *dev, bool new_carrier);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (c000000000aa4b7c)
Location: drivers/net/tun.c:1246
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
```
**Symbols:**

```
c000000000a9e320-c000000000a9e3a8: tun_net_change_carrier (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int tun_net_change_carrier(struct net_device *dev, bool new_carrier);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffe00062672e)
Location: drivers/net/tun.c:1246
Inline: True
```
**Symbols:**

```
ffffffe00062672e-ffffffe00062678a: tun_net_change_carrier (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int tun_net_change_carrier(struct net_device *dev, bool new_carrier);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff817894a8)
Location: drivers/net/tun.c:1246
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
```
**Symbols:**

```
ffffffff81785ce0-ffffffff81785d11: tun_net_change_carrier (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int tun_net_change_carrier(struct net_device *dev, bool new_carrier);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff81768df8)
Location: drivers/net/tun.c:1246
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
```
**Symbols:**

```
ffffffff81765630-ffffffff81765661: tun_net_change_carrier (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int tun_net_change_carrier(struct net_device *dev, bool new_carrier);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff817b9848)
Location: drivers/net/tun.c:1246
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
```
**Symbols:**

```
ffffffff817b6090-ffffffff817b60c1: tun_net_change_carrier (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int tun_net_change_carrier(struct net_device *dev, bool new_carrier);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff817d527d)
Location: drivers/net/tun.c:1246
Inline: True
Inline callers:
  - drivers/net/tun.c:__tun_chr_ioctl
  - drivers/net/tun.c:__tun_chr_ioctl
```
**Symbols:**

```
ffffffff817d0970-ffffffff817d09a1: tun_net_change_carrier (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
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
