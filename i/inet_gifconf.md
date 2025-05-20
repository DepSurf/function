# Function: <code>inet_gifconf</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int inet_gifconf(struct net_device *dev, char *buf, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff8178fb30)
Location: net/ipv4/devinet.c:1156
Inline: False
```
**Symbols:**

```
ffffffff8178fb30-ffffffff8178fc38: inet_gifconf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int inet_gifconf(struct net_device *dev, char *buf, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff817fd220)
Location: net/ipv4/devinet.c:1160
Inline: False
```
**Symbols:**

```
ffffffff817fd220-ffffffff817fd359: inet_gifconf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int inet_gifconf(struct net_device *dev, char *buf, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff8182e180)
Location: net/ipv4/devinet.c:1160
Inline: False
```
**Symbols:**

```
ffffffff8182e180-ffffffff8182e2b9: inet_gifconf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int inet_gifconf(struct net_device *dev, char *buf, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff8184f620)
Location: net/ipv4/devinet.c:1183
Inline: False
```
**Symbols:**

```
ffffffff8184f620-ffffffff8184f782: inet_gifconf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int inet_gifconf(struct net_device *dev, char *buf, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff818cf250)
Location: net/ipv4/devinet.c:1191
Inline: False
```
**Symbols:**

```
ffffffff818cf250-ffffffff818cf3b2: inet_gifconf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int inet_gifconf(struct net_device *dev, char *buf, int len, int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff819259d0)
Location: net/ipv4/devinet.c:1196
Inline: False
```
**Symbols:**

```
ffffffff819259d0-ffffffff81925ba5: inet_gifconf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int inet_gifconf(struct net_device *dev, char *buf, int len, int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff81954960)
Location: net/ipv4/devinet.c:1208
Inline: False
```
**Symbols:**

```
ffffffff81954960-ffffffff81954b35: inet_gifconf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int inet_gifconf(struct net_device *dev, char *buf, int len, int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/devinet.c (0)
Location: net/ipv4/devinet.c:1241
Inline: False
```
**Symbols:**

```
ffffffff819b9510-ffffffff819b967e: inet_gifconf (STB_LOCAL)
ffffffff819bcc43-ffffffff819bcc65: inet_gifconf.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int inet_gifconf(struct net_device *dev, char *buf, int len, int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/devinet.c (0)
Location: net/ipv4/devinet.c:1241
Inline: False
```
**Symbols:**

```
ffffffff819f0210-ffffffff819f0380: inet_gifconf (STB_LOCAL)
ffffffff819f38f3-ffffffff819f38ff: inet_gifconf.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int inet_gifconf(struct net_device *dev, char *buf, int len, int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/devinet.c (0)
Location: net/ipv4/devinet.c:1247
Inline: False
```
**Symbols:**

```
ffffffff81add8e0-ffffffff81adda3f: inet_gifconf (STB_LOCAL)
ffffffff81ae1bd7-ffffffff81ae1be3: inet_gifconf.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int inet_gifconf(struct net_device *dev, char *buf, int len, int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/devinet.c (0)
Location: net/ipv4/devinet.c:1246
Inline: False
```
**Symbols:**

```
ffffffff81aea630-ffffffff81aea811: inet_gifconf (STB_LOCAL)
ffffffff81c3287f-ffffffff81c32897: inet_gifconf.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int inet_gifconf(struct net_device *dev, char *buf, int len, int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/devinet.c (0)
Location: net/ipv4/devinet.c:1246
Inline: False
```
**Symbols:**

```
ffffffff81ad5d80-ffffffff81ad5f5d: inet_gifconf (STB_LOCAL)
ffffffff81c24b53-ffffffff81c24b6b: inet_gifconf.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int inet_gifconf(struct net_device *dev, char *buf, int len, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/devinet.c (0)
Location: net/ipv4/devinet.c:1246
Inline: False
Direct callers:
  - net/core/dev_ioctl.c:dev_ifconf
  - net/core/dev_ioctl.c:dev_ifconf
```
**Symbols:**

```
ffffffff81d3c317-ffffffff81d3c32f: inet_gifconf.cold (STB_LOCAL)
ffffffff81b97ea0-ffffffff81b9807d: inet_gifconf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int inet_gifconf(struct net_device *dev, char *buf, int len, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/devinet.c (0)
Location: net/ipv4/devinet.c:1250
Inline: False
Direct callers:
  - net/core/dev_ioctl.c:dev_ifconf
  - net/core/dev_ioctl.c:dev_ifconf
```
**Symbols:**

```
ffffffff81f08b50-ffffffff81f08b68: inet_gifconf.cold (STB_LOCAL)
ffffffff81d29c30-ffffffff81d29e46: inet_gifconf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int inet_gifconf(struct net_device *dev, char *buf, int len, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff81ef16d0)
Location: net/ipv4/devinet.c:1251
Inline: False
Direct callers:
  - net/core/dev_ioctl.c:dev_ifconf
  - net/core/dev_ioctl.c:dev_ifconf
```
**Symbols:**

```
ffffffff81ef16d0-ffffffff81ef18fa: inet_gifconf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int inet_gifconf(struct net_device *dev, char *buf, int len, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff81f510f0)
Location: net/ipv4/devinet.c:1254
Inline: False
Direct callers:
  - net/core/dev_ioctl.c:dev_ifconf
  - net/core/dev_ioctl.c:dev_ifconf
```
**Symbols:**

```
ffffffff81f510f0-ffffffff81f51318: inet_gifconf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int inet_gifconf(struct net_device *dev, char *buf, int len, int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff82017370)
Location: net/ipv4/devinet.c:1271
Inline: False
Direct callers:
  - net/core/dev_ioctl.c:dev_ifconf
  - net/core/dev_ioctl.c:dev_ifconf
```
**Symbols:**

```
ffffffff82017370-ffffffff82017598: inet_gifconf (STB_GLOBAL)
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
int inet_gifconf(struct net_device *dev, char *buf, int len, int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffff800010ca6708)
Location: net/ipv4/devinet.c:1241
Inline: False
```
**Symbols:**

```
ffff800010ca6708-ffff800010ca6998: inet_gifconf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int inet_gifconf(struct net_device *dev, char *buf, int len, int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (c0db2afc)
Location: net/ipv4/devinet.c:1241
Inline: False
```
**Symbols:**

```
c0db2afc-c0db2ca8: inet_gifconf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int inet_gifconf(struct net_device *dev, char *buf, int len, int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (c000000000dba530)
Location: net/ipv4/devinet.c:1241
Inline: False
```
**Symbols:**

```
c000000000dba530-c000000000dba770: inet_gifconf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int inet_gifconf(struct net_device *dev, char *buf, int len, int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffe00080195c)
Location: net/ipv4/devinet.c:1241
Inline: False
```
**Symbols:**

```
ffffffe00080195c-ffffffe000801a52: inet_gifconf (STB_LOCAL)
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
int inet_gifconf(struct net_device *dev, char *buf, int len, int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/devinet.c (0)
Location: net/ipv4/devinet.c:1241
Inline: False
```
**Symbols:**

```
ffffffff8198ffb0-ffffffff81990120: inet_gifconf (STB_LOCAL)
ffffffff81993693-ffffffff8199369f: inet_gifconf.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int inet_gifconf(struct net_device *dev, char *buf, int len, int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/devinet.c (0)
Location: net/ipv4/devinet.c:1241
Inline: False
```
**Symbols:**

```
ffffffff81949a70-ffffffff81949be0: inet_gifconf (STB_LOCAL)
ffffffff8194d153-ffffffff8194d15f: inet_gifconf.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int inet_gifconf(struct net_device *dev, char *buf, int len, int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/devinet.c (0)
Location: net/ipv4/devinet.c:1241
Inline: False
```
**Symbols:**

```
ffffffff819fa850-ffffffff819fa9c0: inet_gifconf (STB_LOCAL)
ffffffff819fdf33-ffffffff819fdf3f: inet_gifconf.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int inet_gifconf(struct net_device *dev, char *buf, int len, int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/devinet.c (0)
Location: net/ipv4/devinet.c:1241
Inline: False
```
**Symbols:**

```
ffffffff81a04ba0-ffffffff81a04d10: inet_gifconf (STB_LOCAL)
ffffffff81a082c3-ffffffff81a082cf: inet_gifconf.cold (STB_LOCAL)
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
<code>int size</code>
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
