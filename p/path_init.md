# Function: <code>path_init</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
const char *path_init(struct nameidata *nd, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81218ef0)
Location: fs/namei.c:1996
Inline: False
Direct callers:
  - fs/namei.c:path_parentat
  - fs/namei.c:path_lookupat
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_openat
```
**Symbols:**

```
ffffffff81218ef0-ffffffff812192a6: path_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
const char *path_init(struct nameidata *nd, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8123de80)
Location: fs/namei.c:2139
Inline: False
Direct callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_parentat
  - fs/namei.c:path_lookupat
```
**Symbols:**

```
ffffffff8123de80-ffffffff8123e1a4: path_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
const char *path_init(struct nameidata *nd, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81250c60)
Location: fs/namei.c:2133
Inline: False
Direct callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_parentat
  - fs/namei.c:path_lookupat
```
**Symbols:**

```
ffffffff81250c60-ffffffff81250f84: path_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
const char *path_init(struct nameidata *nd, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8125c340)
Location: fs/namei.c:2143
Inline: False
Direct callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_parentat
  - fs/namei.c:path_lookupat
```
**Symbols:**

```
ffffffff8125c340-ffffffff8125c626: path_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
const char *path_init(struct nameidata *nd, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8127e7a0)
Location: fs/namei.c:2141
Inline: False
Direct callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_parentat
  - fs/namei.c:path_lookupat
```
**Symbols:**

```
ffffffff8127e7a0-ffffffff8127ea8f: path_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
const char *path_init(struct nameidata *nd, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812a7680)
Location: fs/namei.c:2128
Inline: False
Direct callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_mountpoint
```
**Symbols:**

```
ffffffff812a7680-ffffffff812a7970: path_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
const char *path_init(struct nameidata *nd, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812bc720)
Location: fs/namei.c:2172
Inline: False
Direct callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_mountpoint
```
**Symbols:**

```
ffffffff812bc720-ffffffff812bca02: path_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
const char *path_init(struct nameidata *nd, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812d91f0)
Location: fs/namei.c:2170
Inline: False
Direct callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_mountpoint
```
**Symbols:**

```
ffffffff812d91f0-ffffffff812d9505: path_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
const char *path_init(struct nameidata *nd, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812ead00)
Location: fs/namei.c:2163
Inline: False
Direct callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_mountpoint
```
**Symbols:**

```
ffffffff812ead00-ffffffff812eb015: path_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Collision, Selective Inline ⚠️</summary>

```c
const char *path_init(struct nameidata *nd, unsigned int flags);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff813229c0)
Location: fs/namei.c:2204
Inline: False
Direct callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_parentat
  - fs/namei.c:path_lookupat
```
```
In drivers/interconnect/core.c (ffffffff819dc6a4)
Location: drivers/interconnect/core.c:149
Inline: True
Inline callers:
  - drivers/interconnect/core.c:path_find
```
**Symbols:**

```
ffffffff813229c0-ffffffff81322dc4: path_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision, Selective Inline ⚠️</summary>

```c
const char *path_init(struct nameidata *nd, unsigned int flags);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8132df60)
Location: fs/namei.c:2202
Inline: False
Direct callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_parentat
  - fs/namei.c:path_lookupat
```
```
In drivers/interconnect/core.c (ffffffff819dbd04)
Location: drivers/interconnect/core.c:151
Inline: True
Inline callers:
  - drivers/interconnect/core.c:path_find
```
**Symbols:**

```
ffffffff8132df60-ffffffff8132e33f: path_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision, Selective Inline ⚠️</summary>

```c
const char *path_init(struct nameidata *nd, unsigned int flags);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81334590)
Location: fs/namei.c:2290
Inline: False
Direct callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_parentat
  - fs/namei.c:path_lookupat
```
```
In drivers/interconnect/core.c (ffffffff819c1fb4)
Location: drivers/interconnect/core.c:151
Inline: True
Inline callers:
  - drivers/interconnect/core.c:path_find
```
**Symbols:**

```
ffffffff81334590-ffffffff81334973: path_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision, Selective Inline ⚠️</summary>

```c
const char *path_init(struct nameidata *nd, unsigned int flags);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81381ee0)
Location: fs/namei.c:2318
Inline: False
Direct callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_parentat
  - fs/namei.c:path_lookupat
```
```
In drivers/interconnect/core.c (ffffffff81a71834)
Location: drivers/interconnect/core.c:151
Inline: True
Inline callers:
  - drivers/interconnect/core.c:path_find
```
**Symbols:**

```
ffffffff81381ee0-ffffffff813822be: path_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision, Selective Inline ⚠️</summary>

```c
const char *path_init(struct nameidata *nd, unsigned int flags);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81403be0)
Location: fs/namei.c:2364
Inline: False
Direct callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_parentat
  - fs/namei.c:path_lookupat
```
```
In drivers/interconnect/core.c (ffffffff81be329c)
Location: drivers/interconnect/core.c:151
Inline: True
Inline callers:
  - drivers/interconnect/core.c:path_find
```
**Symbols:**

```
ffffffff81403be0-ffffffff81403f8f: path_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision, Selective Inline ⚠️</summary>

```c
const char *path_init(struct nameidata *nd, unsigned int flags);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8148e040)
Location: fs/namei.c:2341
Inline: False
Direct callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_parentat
  - fs/namei.c:path_lookupat
```
```
In drivers/interconnect/core.c (ffffffff81d8eefc)
Location: drivers/interconnect/core.c:151
Inline: True
Inline callers:
  - drivers/interconnect/core.c:path_find
```
**Symbols:**

```
ffffffff8148e040-ffffffff8148e3fb: path_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision ⚠️</summary>

```c
const char *path_init(struct nameidata *nd, unsigned int flags);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff814c3780)
Location: fs/namei.c:2346
Inline: False
Direct callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_parentat
  - fs/namei.c:path_lookupat
```
```
In drivers/interconnect/core.c (0)
Location: drivers/interconnect/core.c:150
Inline: False
```
**Symbols:**

```
ffffffff814c3780-ffffffff814c3b47: path_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision, Selective Inline ⚠️</summary>

```c
const char *path_init(struct nameidata *nd, unsigned int flags);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff814f5c50)
Location: fs/namei.c:2353
Inline: False
Direct callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_parentat
  - fs/namei.c:path_lookupat
```
```
In drivers/interconnect/core.c (ffffffff81eb383c)
Location: drivers/interconnect/core.c:166
Inline: True
Inline callers:
  - drivers/interconnect/core.c:path_find
```
**Symbols:**

```
ffffffff814f5c50-ffffffff814f6017: path_init (STB_LOCAL)
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
const char *path_init(struct nameidata *nd, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffff8000103943c0)
Location: fs/namei.c:2163
Inline: False
Direct callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_mountpoint
```
**Symbols:**

```
ffff8000103943c0-ffff800010394700: path_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
const char *path_init(struct nameidata *nd, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (c0578960)
Location: fs/namei.c:2163
Inline: False
Direct callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_parentat
  - fs/namei.c:path_lookupat
```
**Symbols:**

```
c0578960-c0578d48: path_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
const char *path_init(struct nameidata *nd, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (c00000000048a490)
Location: fs/namei.c:2163
Inline: False
Direct callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_mountpoint
```
**Symbols:**

```
c00000000048a490-c00000000048a928: path_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
const char *path_init(struct nameidata *nd, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffe000262f4a)
Location: fs/namei.c:2163
Inline: False
Direct callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_parentat
  - fs/namei.c:path_lookupat
```
**Symbols:**

```
ffffffe000262f4a-ffffffe0002631fa: path_init (STB_LOCAL)
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
const char *path_init(struct nameidata *nd, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812e32e0)
Location: fs/namei.c:2163
Inline: False
Direct callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_mountpoint
```
**Symbols:**

```
ffffffff812e32e0-ffffffff812e35f5: path_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
const char *path_init(struct nameidata *nd, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812d3f20)
Location: fs/namei.c:2163
Inline: False
Direct callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_mountpoint
```
**Symbols:**

```
ffffffff812d3f20-ffffffff812d4235: path_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
const char *path_init(struct nameidata *nd, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812e10f0)
Location: fs/namei.c:2163
Inline: False
Direct callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_mountpoint
```
**Symbols:**

```
ffffffff812e10f0-ffffffff812e1405: path_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
const char *path_init(struct nameidata *nd, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812f0130)
Location: fs/namei.c:2163
Inline: False
Direct callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_mountpoint
```
**Symbols:**

```
ffffffff812f0130-ffffffff812f0447: path_init (STB_LOCAL)
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
