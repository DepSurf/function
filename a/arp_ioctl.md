# Function: <code>arp_ioctl</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int arp_ioctl(struct net *net, unsigned int cmd, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/arp.c (ffffffff8178d800)
Location: net/ipv4/arp.c:1121
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:inet_ioctl
```
**Symbols:**

```
ffffffff8178d800-ffffffff8178db5d: arp_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int arp_ioctl(struct net *net, unsigned int cmd, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/arp.c (ffffffff817fadc0)
Location: net/ipv4/arp.c:1134
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:inet_ioctl
```
**Symbols:**

```
ffffffff817fadc0-ffffffff817fb148: arp_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int arp_ioctl(struct net *net, unsigned int cmd, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/arp.c (ffffffff8182bc70)
Location: net/ipv4/arp.c:1134
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:inet_ioctl
```
**Symbols:**

```
ffffffff8182bc70-ffffffff8182bff8: arp_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int arp_ioctl(struct net *net, unsigned int cmd, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/arp.c (ffffffff8184d040)
Location: net/ipv4/arp.c:1172
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:inet_ioctl
```
**Symbols:**

```
ffffffff8184d040-ffffffff8184d43e: arp_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int arp_ioctl(struct net *net, unsigned int cmd, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/arp.c (ffffffff818ccd70)
Location: net/ipv4/arp.c:1177
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:inet_ioctl
```
**Symbols:**

```
ffffffff818ccd70-ffffffff818cd174: arp_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int arp_ioctl(struct net *net, unsigned int cmd, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/arp.c (0)
Location: net/ipv4/arp.c:1177
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:inet_ioctl
```
**Symbols:**

```
ffffffff819236a2-ffffffff819236ae: arp_ioctl.cold.33 (STB_LOCAL)
ffffffff81923260-ffffffff8192366a: arp_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int arp_ioctl(struct net *net, unsigned int cmd, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/arp.c (0)
Location: net/ipv4/arp.c:1177
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:inet_ioctl
```
**Symbols:**

```
ffffffff81952492-ffffffff8195249e: arp_ioctl.cold.33 (STB_LOCAL)
ffffffff81952050-ffffffff8195245a: arp_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int arp_ioctl(struct net *net, unsigned int cmd, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/arp.c (0)
Location: net/ipv4/arp.c:1173
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:inet_ioctl
```
**Symbols:**

```
ffffffff819b6d55-ffffffff819b6d61: arp_ioctl.cold (STB_LOCAL)
ffffffff819b6910-ffffffff819b6d05: arp_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int arp_ioctl(struct net *net, unsigned int cmd, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/arp.c (0)
Location: net/ipv4/arp.c:1173
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:inet_ioctl
```
**Symbols:**

```
ffffffff819eda62-ffffffff819eda6e: arp_ioctl.cold (STB_LOCAL)
ffffffff819ed630-ffffffff819eda25: arp_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int arp_ioctl(struct net *net, unsigned int cmd, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/arp.c (ffffffff81adb630)
Location: net/ipv4/arp.c:1173
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:inet_ioctl
```
**Symbols:**

```
ffffffff81adb630-ffffffff81adb829: arp_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int arp_ioctl(struct net *net, unsigned int cmd, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/arp.c (ffffffff81ae8100)
Location: net/ipv4/arp.c:1179
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:inet_ioctl
```
**Symbols:**

```
ffffffff81ae8100-ffffffff81ae82f9: arp_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int arp_ioctl(struct net *net, unsigned int cmd, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/arp.c (ffffffff81ad33c0)
Location: net/ipv4/arp.c:1179
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:inet_ioctl
```
**Symbols:**

```
ffffffff81ad33c0-ffffffff81ad358f: arp_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int arp_ioctl(struct net *net, unsigned int cmd, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/arp.c (ffffffff81b92010)
Location: net/ipv4/arp.c:1179
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:inet_ioctl
```
**Symbols:**

```
ffffffff81b92010-ffffffff81b921df: arp_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int arp_ioctl(struct net *net, unsigned int cmd, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/arp.c (ffffffff81d23770)
Location: net/ipv4/arp.c:1184
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:inet_ioctl
```
**Symbols:**

```
ffffffff81d23770-ffffffff81d2399d: arp_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int arp_ioctl(struct net *net, unsigned int cmd, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/arp.c (ffffffff81eead90)
Location: net/ipv4/arp.c:1205
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:inet_ioctl
```
**Symbols:**

```
ffffffff81eead90-ffffffff81eeafbd: arp_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int arp_ioctl(struct net *net, unsigned int cmd, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/arp.c (ffffffff81f4a6f0)
Location: net/ipv4/arp.c:1205
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:inet_ioctl
```
**Symbols:**

```
ffffffff81f4a6f0-ffffffff81f4a8d9: arp_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int arp_ioctl(struct net *net, unsigned int cmd, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/arp.c (ffffffff82010800)
Location: net/ipv4/arp.c:1206
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:inet_ioctl
```
**Symbols:**

```
ffffffff82010800-ffffffff820109e9: arp_ioctl (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int arp_ioctl(struct net *net, unsigned int cmd, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/arp.c (ffff800010ca2f78)
Location: net/ipv4/arp.c:1173
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:inet_ioctl
```
**Symbols:**

```
ffff800010ca2f78-ffff800010ca356c: arp_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int arp_ioctl(struct net *net, unsigned int cmd, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/arp.c (c0dafdb4)
Location: net/ipv4/arp.c:1173
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:inet_ioctl
```
**Symbols:**

```
c0dafdb4-c0db013c: arp_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int arp_ioctl(struct net *net, unsigned int cmd, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/arp.c (c000000000db6800)
Location: net/ipv4/arp.c:1173
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:inet_ioctl
```
**Symbols:**

```
c000000000db6800-c000000000db6c48: arp_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int arp_ioctl(struct net *net, unsigned int cmd, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/arp.c (ffffffe0007ff140)
Location: net/ipv4/arp.c:1173
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:inet_ioctl
```
**Symbols:**

```
ffffffe0007ff140-ffffffe0007ff3aa: arp_ioctl (STB_GLOBAL)
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
int arp_ioctl(struct net *net, unsigned int cmd, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/arp.c (0)
Location: net/ipv4/arp.c:1173
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:inet_ioctl
```
**Symbols:**

```
ffffffff8198d802-ffffffff8198d80e: arp_ioctl.cold (STB_LOCAL)
ffffffff8198d3d0-ffffffff8198d7c5: arp_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int arp_ioctl(struct net *net, unsigned int cmd, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/arp.c (0)
Location: net/ipv4/arp.c:1173
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:inet_ioctl
```
**Symbols:**

```
ffffffff819472c2-ffffffff819472ce: arp_ioctl.cold (STB_LOCAL)
ffffffff81946e90-ffffffff81947285: arp_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int arp_ioctl(struct net *net, unsigned int cmd, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/arp.c (0)
Location: net/ipv4/arp.c:1173
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:inet_ioctl
```
**Symbols:**

```
ffffffff819f80a2-ffffffff819f80ae: arp_ioctl.cold (STB_LOCAL)
ffffffff819f7c70-ffffffff819f8065: arp_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int arp_ioctl(struct net *net, unsigned int cmd, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/arp.c (0)
Location: net/ipv4/arp.c:1173
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:inet_ioctl
```
**Symbols:**

```
ffffffff81a022e2-ffffffff81a022ee: arp_ioctl.cold (STB_LOCAL)
ffffffff81a01eb0-ffffffff81a022a5: arp_ioctl (STB_GLOBAL)
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
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
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
