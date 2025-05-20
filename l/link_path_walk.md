# Function: <code>link_path_walk</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int link_path_walk(const char *name, struct nameidata *nd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81219f90)
Location: fs/namei.c:1896
Inline: False
Direct callers:
  - fs/namei.c:path_parentat
  - fs/namei.c:path_lookupat
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_openat
```
**Symbols:**

```
ffffffff81219f90-ffffffff8121a53b: link_path_walk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int link_path_walk(const char *name, struct nameidata *nd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81240610)
Location: fs/namei.c:2039
Inline: False
Direct callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_parentat
  - fs/namei.c:path_lookupat
```
**Symbols:**

```
ffffffff81240610-ffffffff81240c35: link_path_walk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int link_path_walk(const char *name, struct nameidata *nd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81252af0)
Location: fs/namei.c:2032
Inline: False
Direct callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_parentat
  - fs/namei.c:path_lookupat
```
**Symbols:**

```
ffffffff81252af0-ffffffff8125311a: link_path_walk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int link_path_walk(const char *name, struct nameidata *nd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8125ecd0)
Location: fs/namei.c:2042
Inline: False
Direct callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_parentat
  - fs/namei.c:path_lookupat
```
**Symbols:**

```
ffffffff8125ecd0-ffffffff8125f25a: link_path_walk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int link_path_walk(const char *name, struct nameidata *nd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81281030)
Location: fs/namei.c:2040
Inline: False
Direct callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_parentat
  - fs/namei.c:path_lookupat
```
**Symbols:**

```
ffffffff81281030-ffffffff812815cc: link_path_walk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int link_path_walk(const char *name, struct nameidata *nd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812a7d50)
Location: fs/namei.c:2027
Inline: False
Direct callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_mountpoint
```
**Symbols:**

```
ffffffff812a7d50-ffffffff812a828a: link_path_walk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/namei.c (ffffffff812bf6e9)
Location: fs/namei.c:2068
Inline: True
Inline callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_mountpoint
Direct callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_mountpoint
```
**Symbols:**

```
ffffffff812bcdf0-ffffffff812bd321: link_path_walk.part.42 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/namei.c (ffffffff812dd314)
Location: fs/namei.c:2066
Inline: True
Inline callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_mountpoint
Direct callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_mountpoint
```
**Symbols:**

```
ffffffff812d9900-ffffffff812d9e42: link_path_walk.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/namei.c (ffffffff812eee24)
Location: fs/namei.c:2059
Inline: True
Inline callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_mountpoint
Direct callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_mountpoint
```
**Symbols:**

```
ffffffff812eb410-ffffffff812eb952: link_path_walk.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/namei.c (ffffffff813263a5)
Location: fs/namei.c:2105
Inline: True
Inline callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_parentat
  - fs/namei.c:path_lookupat
Direct callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_parentat
  - fs/namei.c:path_lookupat
```
**Symbols:**

```
ffffffff81324340-ffffffff81324690: link_path_walk.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/namei.c (ffffffff81331845)
Location: fs/namei.c:2101
Inline: True
Inline callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_parentat
  - fs/namei.c:path_lookupat
Direct callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_parentat
  - fs/namei.c:path_lookupat
```
**Symbols:**

```
ffffffff8132fb40-ffffffff8132fe8f: link_path_walk.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/namei.c (ffffffff81338205)
Location: fs/namei.c:2187
Inline: True
Inline callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_parentat
  - fs/namei.c:path_lookupat
Direct callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_parentat
  - fs/namei.c:path_lookupat
```
**Symbols:**

```
ffffffff81334db0-ffffffff81335114: link_path_walk.part.0.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/namei.c (ffffffff81385c65)
Location: fs/namei.c:2215
Inline: True
Inline callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_parentat
  - fs/namei.c:path_lookupat
Direct callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_parentat
  - fs/namei.c:path_lookupat
```
**Symbols:**

```
ffffffff813827c0-ffffffff81382b1e: link_path_walk.part.0.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/namei.c (ffffffff81406ac9)
Location: fs/namei.c:2261
Inline: True
Inline callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_parentat
  - fs/namei.c:path_lookupat
Direct callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_parentat
  - fs/namei.c:path_lookupat
```
**Symbols:**

```
ffffffff81405c10-ffffffff81405fec: link_path_walk.part.0.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/namei.c (ffffffff81490e19)
Location: fs/namei.c:2238
Inline: True
Inline callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_parentat
  - fs/namei.c:path_lookupat
Direct callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_parentat
  - fs/namei.c:path_lookupat
```
**Symbols:**

```
ffffffff8148ff30-ffffffff8149031f: link_path_walk.part.0.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/namei.c (ffffffff814c6635)
Location: fs/namei.c:2243
Inline: True
Inline callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_parentat
  - fs/namei.c:path_lookupat
Direct callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_parentat
  - fs/namei.c:path_lookupat
```
**Symbols:**

```
ffffffff814c5330-ffffffff814c56e7: link_path_walk.part.0.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/namei.c (ffffffff814f8f25)
Location: fs/namei.c:2250
Inline: True
Inline callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_parentat
  - fs/namei.c:path_lookupat
Direct callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_parentat
  - fs/namei.c:path_lookupat
```
**Symbols:**

```
ffffffff814f7b10-ffffffff814f7ec9: link_path_walk.part.0.constprop.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/namei.c (ffff8000103985e4)
Location: fs/namei.c:2059
Inline: True
Inline callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_mountpoint
Direct callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_mountpoint
```
**Symbols:**

```
ffff800010394be0-ffff8000103950dc: link_path_walk.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/namei.c (c057ec7c)
Location: fs/namei.c:2059
Inline: True
Inline callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_parentat
  - fs/namei.c:path_lookupat
Direct callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_parentat
  - fs/namei.c:path_lookupat
```
**Symbols:**

```
c057cc90-c057d1b8: link_path_walk.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/namei.c (c000000000492840)
Location: fs/namei.c:2059
Inline: True
Inline callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_mountpoint
Direct callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_mountpoint
```
**Symbols:**

```
c000000000490150-c000000000490808: link_path_walk.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/namei.c (ffffffe000266290)
Location: fs/namei.c:2059
Inline: True
Inline callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_parentat
  - fs/namei.c:path_lookupat
Direct callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_mountpoint
  - fs/namei.c:path_parentat
  - fs/namei.c:path_lookupat
```
**Symbols:**

```
ffffffe0002635d4-ffffffe0002639a0: link_path_walk.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/namei.c (ffffffff812e7404)
Location: fs/namei.c:2059
Inline: True
Inline callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_mountpoint
Direct callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_mountpoint
```
**Symbols:**

```
ffffffff812e39f0-ffffffff812e3f32: link_path_walk.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/namei.c (ffffffff812d8044)
Location: fs/namei.c:2059
Inline: True
Inline callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_mountpoint
Direct callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_mountpoint
```
**Symbols:**

```
ffffffff812d4630-ffffffff812d4b72: link_path_walk.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/namei.c (ffffffff812e5214)
Location: fs/namei.c:2059
Inline: True
Inline callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_mountpoint
Direct callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_mountpoint
```
**Symbols:**

```
ffffffff812e1800-ffffffff812e1d42: link_path_walk.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/namei.c (ffffffff812f6194)
Location: fs/namei.c:2059
Inline: True
Inline callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_mountpoint
Direct callers:
  - fs/namei.c:path_openat
  - fs/namei.c:path_mountpoint
```
**Symbols:**

```
ffffffff812f45c0-ffffffff812f4af1: link_path_walk.part.0 (STB_LOCAL)
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
</ul>
