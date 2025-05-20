# Function: <code>devinet_ioctl</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int devinet_ioctl(struct net *net, unsigned int cmd, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff81792260)
Location: net/ipv4/devinet.c:914
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:inet_ioctl
```
**Symbols:**

```
ffffffff81792260-ffffffff81792926: devinet_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int devinet_ioctl(struct net *net, unsigned int cmd, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff817ff070)
Location: net/ipv4/devinet.c:918
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:inet_ioctl
```
**Symbols:**

```
ffffffff817ff070-ffffffff817ff72e: devinet_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int devinet_ioctl(struct net *net, unsigned int cmd, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff8182ffd0)
Location: net/ipv4/devinet.c:918
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:inet_ioctl
```
**Symbols:**

```
ffffffff8182ffd0-ffffffff8183068e: devinet_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int devinet_ioctl(struct net *net, unsigned int cmd, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff81851480)
Location: net/ipv4/devinet.c:941
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:inet_ioctl
```
**Symbols:**

```
ffffffff81851480-ffffffff81851b5f: devinet_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int devinet_ioctl(struct net *net, unsigned int cmd, void *arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff818d1250)
Location: net/ipv4/devinet.c:949
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:inet_ioctl
```
**Symbols:**

```
ffffffff818d1250-ffffffff818d1941: devinet_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int devinet_ioctl(struct net *net, unsigned int cmd, struct ifreq *ifr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff819277e0)
Location: net/ipv4/devinet.c:961
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:inet_ioctl
  - net/ipv4/af_inet.c:inet_ioctl
```
**Symbols:**

```
ffffffff819277e0-ffffffff81927e4f: devinet_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int devinet_ioctl(struct net *net, unsigned int cmd, struct ifreq *ifr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff819569b0)
Location: net/ipv4/devinet.c:973
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:inet_ioctl
  - net/ipv4/af_inet.c:inet_ioctl
```
**Symbols:**

```
ffffffff819569b0-ffffffff81957085: devinet_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int devinet_ioctl(struct net *net, unsigned int cmd, struct ifreq *ifr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/devinet.c (0)
Location: net/ipv4/devinet.c:1003
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:inet_ioctl
  - net/ipv4/af_inet.c:inet_ioctl
```
**Symbols:**

```
ffffffff819bcca6-ffffffff819bccb9: devinet_ioctl.cold (STB_LOCAL)
ffffffff819bb3d0-ffffffff819bbacc: devinet_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int devinet_ioctl(struct net *net, unsigned int cmd, struct ifreq *ifr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff819f20c0)
Location: net/ipv4/devinet.c:1003
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:inet_ioctl
  - net/ipv4/af_inet.c:inet_ioctl
```
**Symbols:**

```
ffffffff819f20c0-ffffffff819f27c3: devinet_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int devinet_ioctl(struct net *net, unsigned int cmd, struct ifreq *ifr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff81ae02b0)
Location: net/ipv4/devinet.c:1009
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:inet_ioctl
  - net/ipv4/af_inet.c:inet_ioctl
```
**Symbols:**

```
ffffffff81ae02b0-ffffffff81ae09b7: devinet_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int devinet_ioctl(struct net *net, unsigned int cmd, struct ifreq *ifr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff81aed130)
Location: net/ipv4/devinet.c:1008
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:inet_ioctl
  - net/ipv4/af_inet.c:inet_ioctl
```
**Symbols:**

```
ffffffff81aed130-ffffffff81aed837: devinet_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int devinet_ioctl(struct net *net, unsigned int cmd, struct ifreq *ifr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff81ad8910)
Location: net/ipv4/devinet.c:1008
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:inet_ioctl
  - net/ipv4/af_inet.c:inet_ioctl
```
**Symbols:**

```
ffffffff81ad8910-ffffffff81ad901c: devinet_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int devinet_ioctl(struct net *net, unsigned int cmd, struct ifreq *ifr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/devinet.c (0)
Location: net/ipv4/devinet.c:1008
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:inet_ioctl
  - net/ipv4/af_inet.c:inet_ioctl
```
**Symbols:**

```
ffffffff81d3c2e5-ffffffff81d3c317: devinet_ioctl.cold (STB_LOCAL)
ffffffff81b977b0-ffffffff81b97e97: devinet_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int devinet_ioctl(struct net *net, unsigned int cmd, struct ifreq *ifr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/devinet.c (0)
Location: net/ipv4/devinet.c:1012
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:inet_ioctl
  - net/ipv4/af_inet.c:inet_ioctl
```
**Symbols:**

```
ffffffff81f08b29-ffffffff81f08b50: devinet_ioctl.cold (STB_LOCAL)
ffffffff81d29550-ffffffff81d29c2b: devinet_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int devinet_ioctl(struct net *net, unsigned int cmd, struct ifreq *ifr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/devinet.c (0)
Location: net/ipv4/devinet.c:1013
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:inet_ioctl
  - net/ipv4/af_inet.c:inet_ioctl
```
**Symbols:**

```
ffffffff820b052f-ffffffff820b056b: devinet_ioctl.cold (STB_LOCAL)
ffffffff81ef0ee0-ffffffff81ef16b2: devinet_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int devinet_ioctl(struct net *net, unsigned int cmd, struct ifreq *ifr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/devinet.c (0)
Location: net/ipv4/devinet.c:1016
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:inet_ioctl
  - net/ipv4/af_inet.c:inet_ioctl
```
**Symbols:**

```
ffffffff821317da-ffffffff82131811: devinet_ioctl.cold (STB_LOCAL)
ffffffff81f50950-ffffffff81f510d6: devinet_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int devinet_ioctl(struct net *net, unsigned int cmd, struct ifreq *ifr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/devinet.c (0)
Location: net/ipv4/devinet.c:1033
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:inet_ioctl
  - net/ipv4/af_inet.c:inet_ioctl
```
**Symbols:**

```
ffffffff8221319e-ffffffff822131d5: devinet_ioctl.cold (STB_LOCAL)
ffffffff82016bd0-ffffffff8201735d: devinet_ioctl (STB_GLOBAL)
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
int devinet_ioctl(struct net *net, unsigned int cmd, struct ifreq *ifr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffff800010ca8380)
Location: net/ipv4/devinet.c:1003
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:inet_ioctl
  - net/ipv4/af_inet.c:inet_ioctl
```
**Symbols:**

```
ffff800010ca8380-ffff800010ca8a84: devinet_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int devinet_ioctl(struct net *net, unsigned int cmd, struct ifreq *ifr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (c0db4ae0)
Location: net/ipv4/devinet.c:1003
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:inet_ioctl
  - net/ipv4/af_inet.c:inet_ioctl
```
**Symbols:**

```
c0db4ae0-c0db5210: devinet_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int devinet_ioctl(struct net *net, unsigned int cmd, struct ifreq *ifr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (c000000000dbce60)
Location: net/ipv4/devinet.c:1003
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:inet_ioctl
  - net/ipv4/af_inet.c:inet_ioctl
```
**Symbols:**

```
c000000000dbce60-c000000000dbdacc: devinet_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int devinet_ioctl(struct net *net, unsigned int cmd, struct ifreq *ifr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffe000803194)
Location: net/ipv4/devinet.c:1003
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:inet_ioctl
  - net/ipv4/af_inet.c:inet_ioctl
```
**Symbols:**

```
ffffffe000803194-ffffffe000803802: devinet_ioctl (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int devinet_ioctl(struct net *net, unsigned int cmd, struct ifreq *ifr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff81991e60)
Location: net/ipv4/devinet.c:1003
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:inet_ioctl
  - net/ipv4/af_inet.c:inet_ioctl
```
**Symbols:**

```
ffffffff81991e60-ffffffff81992563: devinet_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int devinet_ioctl(struct net *net, unsigned int cmd, struct ifreq *ifr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff8194b920)
Location: net/ipv4/devinet.c:1003
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:inet_ioctl
  - net/ipv4/af_inet.c:inet_ioctl
```
**Symbols:**

```
ffffffff8194b920-ffffffff8194c023: devinet_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int devinet_ioctl(struct net *net, unsigned int cmd, struct ifreq *ifr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff819fc700)
Location: net/ipv4/devinet.c:1003
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:inet_ioctl
  - net/ipv4/af_inet.c:inet_ioctl
```
**Symbols:**

```
ffffffff819fc700-ffffffff819fce03: devinet_ioctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int devinet_ioctl(struct net *net, unsigned int cmd, struct ifreq *ifr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff81a06a90)
Location: net/ipv4/devinet.c:1003
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:inet_ioctl
  - net/ipv4/af_inet.c:inet_ioctl
```
**Symbols:**

```
ffffffff81a06a90-ffffffff81a07193: devinet_ioctl (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct ifreq *ifr</code>
</li>
<li>
<b>Param removed. </b>
<code>void *arg</code>
</li>
</ul>
</details>
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
