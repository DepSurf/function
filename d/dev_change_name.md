# Function: <code>dev_change_name</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int dev_change_name(struct net_device *dev, const char *newname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8171d3d0)
Location: net/core/dev.c:1141
Inline: False
Direct callers:
  - net/core/rtnetlink.c:do_setlink
  - net/core/dev_ioctl.c:dev_ifsioc
```
**Symbols:**

```
ffffffff8171d3d0-ffffffff8171d6a9: dev_change_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int dev_change_name(struct net_device *dev, const char *newname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81785ca0)
Location: net/core/dev.c:1145
Inline: False
Direct callers:
  - net/core/rtnetlink.c:do_setlink
  - net/core/dev_ioctl.c:dev_ifsioc
```
**Symbols:**

```
ffffffff81785ca0-ffffffff81785f75: dev_change_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int dev_change_name(struct net_device *dev, const char *newname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817b3260)
Location: net/core/dev.c:1144
Inline: False
Direct callers:
  - net/core/rtnetlink.c:do_setlink
  - net/core/dev_ioctl.c:dev_ifsioc
```
**Symbols:**

```
ffffffff817b3260-ffffffff817b3535: dev_change_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int dev_change_name(struct net_device *dev, const char *newname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817d1bc0)
Location: net/core/dev.c:1176
Inline: False
Direct callers:
  - net/core/rtnetlink.c:do_setlink
  - net/core/dev_ioctl.c:dev_ifsioc
```
**Symbols:**

```
ffffffff817d1bc0-ffffffff817d1eb4: dev_change_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int dev_change_name(struct net_device *dev, const char *newname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8184be20)
Location: net/core/dev.c:1173
Inline: False
Direct callers:
  - net/core/rtnetlink.c:do_setlink
  - net/core/dev_ioctl.c:dev_ifsioc
```
**Symbols:**

```
ffffffff8184be20-ffffffff8184c11d: dev_change_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int dev_change_name(struct net_device *dev, const char *newname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:1173
Inline: False
Direct callers:
  - net/core/rtnetlink.c:do_setlink
  - net/core/dev_ioctl.c:dev_ifsioc
```
**Symbols:**

```
ffffffff81899105-ffffffff81899125: dev_change_name.cold.166 (STB_LOCAL)
ffffffff81896180-ffffffff81896468: dev_change_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int dev_change_name(struct net_device *dev, const char *newname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:1175
Inline: False
Direct callers:
  - net/core/rtnetlink.c:do_setlink
  - net/core/dev_ioctl.c:dev_ifsioc
```
**Symbols:**

```
ffffffff818bb5a7-ffffffff818bb5c7: dev_change_name.cold.173 (STB_LOCAL)
ffffffff818b83f0-ffffffff818b86d8: dev_change_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int dev_change_name(struct net_device *dev, const char *newname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:1171
Inline: False
Direct callers:
  - net/core/rtnetlink.c:do_setlink
  - net/core/dev_ioctl.c:dev_ifsioc
```
**Symbols:**

```
ffffffff819074aa-ffffffff819074e6: dev_change_name.cold (STB_LOCAL)
ffffffff819045a0-ffffffff81904890: dev_change_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int dev_change_name(struct net_device *dev, const char *newname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:1089
Inline: False
Direct callers:
  - net/core/rtnetlink.c:do_setlink
  - net/core/dev_ioctl.c:dev_ifsioc
```
**Symbols:**

```
ffffffff81939a91-ffffffff81939acd: dev_change_name.cold (STB_LOCAL)
ffffffff81936c10-ffffffff81936f00: dev_change_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int dev_change_name(struct net_device *dev, const char *newname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:1281
Inline: False
Direct callers:
  - net/core/rtnetlink.c:do_setlink
  - net/core/dev_ioctl.c:dev_ifsioc
```
**Symbols:**

```
ffffffff81a0f03d-ffffffff81a0f06d: dev_change_name.cold (STB_LOCAL)
ffffffff81a0b710-ffffffff81a0b9f8: dev_change_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int dev_change_name(struct net_device *dev, const char *newname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:1283
Inline: False
Direct callers:
  - net/core/rtnetlink.c:do_setlink
  - net/core/dev_ioctl.c:dev_ifsioc
```
**Symbols:**

```
ffffffff81c31388-ffffffff81c313b8: dev_change_name.cold (STB_LOCAL)
ffffffff81a0cdb0-ffffffff81a0d098: dev_change_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int dev_change_name(struct net_device *dev, const char *newname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:1331
Inline: False
Direct callers:
  - net/core/rtnetlink.c:do_setlink
  - net/core/dev_ioctl.c:dev_ifsioc
```
**Symbols:**

```
ffffffff81c2366d-ffffffff81c2369d: dev_change_name.cold (STB_LOCAL)
ffffffff819f3a60-ffffffff819f3d34: dev_change_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int dev_change_name(struct net_device *dev, const char *newname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:1206
Inline: False
Direct callers:
  - net/core/rtnetlink.c:do_setlink
  - net/core/dev_ioctl.c:dev_ifsioc
```
**Symbols:**

```
ffffffff81d364e0-ffffffff81d36525: dev_change_name.cold (STB_LOCAL)
ffffffff81aa5300-ffffffff81aa55e3: dev_change_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int dev_change_name(struct net_device *dev, const char *newname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:1153
Inline: False
Direct callers:
  - net/core/rtnetlink.c:do_setlink
  - net/core/dev_ioctl.c:dev_ifsioc
```
**Symbols:**

```
ffffffff81f02cab-ffffffff81f02cf9: dev_change_name.cold (STB_LOCAL)
ffffffff81c1ccf0-ffffffff81c1d03c: dev_change_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int dev_change_name(struct net_device *dev, const char *newname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:1153
Inline: False
Direct callers:
  - net/core/rtnetlink.c:do_setlink
  - net/core/dev_ioctl.c:dev_ifsioc
```
**Symbols:**

```
ffffffff820ab6e1-ffffffff820ab6f6: dev_change_name.cold (STB_LOCAL)
ffffffff81dcdda0-ffffffff81dce107: dev_change_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int dev_change_name(struct net_device *dev, const char *newname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:1178
Inline: False
Direct callers:
  - net/core/rtnetlink.c:do_setlink
  - net/core/dev_ioctl.c:dev_ifsioc
```
**Symbols:**

```
ffffffff8212ce5d-ffffffff8212ce72: dev_change_name.cold (STB_LOCAL)
ffffffff81e3e9b0-ffffffff81e3ed0c: dev_change_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int dev_change_name(struct net_device *dev, const char *newname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:1182
Inline: False
Direct callers:
  - net/core/rtnetlink.c:do_setlink
  - net/core/dev_ioctl.c:dev_ifsioc
```
**Symbols:**

```
ffffffff8220ebad-ffffffff8220ebc2: dev_change_name.cold (STB_LOCAL)
ffffffff81efd2d0-ffffffff81efd667: dev_change_name (STB_GLOBAL)
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
int dev_change_name(struct net_device *dev, const char *newname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffff800010bd5360)
Location: net/core/dev.c:1089
Inline: False
Direct callers:
  - net/core/rtnetlink.c:do_setlink
  - net/core/dev_ioctl.c:dev_ifsioc
```
**Symbols:**

```
ffff800010bd5360-ffff800010bd571c: dev_change_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int dev_change_name(struct net_device *dev, const char *newname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c0cf0008)
Location: net/core/dev.c:1089
Inline: False
Direct callers:
  - net/core/rtnetlink.c:do_setlink
  - net/core/dev_ioctl.c:dev_ifsioc
```
**Symbols:**

```
c0cf0008-c0cf0364: dev_change_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int dev_change_name(struct net_device *dev, const char *newname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c000000000cb47c0)
Location: net/core/dev.c:1089
Inline: False
Direct callers:
  - net/core/rtnetlink.c:do_setlink
  - net/core/dev_ioctl.c:dev_ifsioc
```
**Symbols:**

```
c000000000cb47c0-c000000000cb4c64: dev_change_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int dev_change_name(struct net_device *dev, const char *newname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffe00075ee22)
Location: net/core/dev.c:1089
Inline: False
Direct callers:
  - net/core/rtnetlink.c:do_setlink
  - net/core/dev_ioctl.c:dev_ifsioc
```
**Symbols:**

```
ffffffe00075ee22-ffffffe00075f0ee: dev_change_name (STB_GLOBAL)
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
int dev_change_name(struct net_device *dev, const char *newname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:1089
Inline: False
Direct callers:
  - net/core/rtnetlink.c:do_setlink
  - net/core/dev_ioctl.c:dev_ifsioc
```
**Symbols:**

```
ffffffff818d9a61-ffffffff818d9a9d: dev_change_name.cold (STB_LOCAL)
ffffffff818d6be0-ffffffff818d6ed0: dev_change_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int dev_change_name(struct net_device *dev, const char *newname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:1089
Inline: False
Direct callers:
  - net/core/rtnetlink.c:do_setlink
  - net/core/dev_ioctl.c:dev_ifsioc
```
**Symbols:**

```
ffffffff818938a1-ffffffff818938dd: dev_change_name.cold (STB_LOCAL)
ffffffff81890a20-ffffffff81890d10: dev_change_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int dev_change_name(struct net_device *dev, const char *newname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:1089
Inline: False
Direct callers:
  - net/core/rtnetlink.c:do_setlink
  - net/core/dev_ioctl.c:dev_ifsioc
```
**Symbols:**

```
ffffffff8192aa91-ffffffff8192aacd: dev_change_name.cold (STB_LOCAL)
ffffffff81927c10-ffffffff81927f00: dev_change_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int dev_change_name(struct net_device *dev, const char *newname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:1089
Inline: False
Direct callers:
  - net/core/rtnetlink.c:do_setlink
  - net/core/dev_ioctl.c:dev_ifsioc
```
**Symbols:**

```
ffffffff8194c161-ffffffff8194c19d: dev_change_name.cold (STB_LOCAL)
ffffffff819492e0-ffffffff819495d0: dev_change_name (STB_GLOBAL)
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
