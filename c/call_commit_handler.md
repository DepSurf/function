# Function: <code>call_commit_handler</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int call_commit_handler(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/wireless/wext-core.c (ffffffff81809b40)
Location: net/wireless/wext-core.c:894
Inline: True
Inline callers:
  - net/wireless/wext-core.c:ioctl_standard_call
Direct callers:
  - net/wireless/wext-core.c:ioctl_standard_call
  - net/wireless/wext-priv.c:ioctl_private_call
  - net/wireless/wext-priv.c:compat_private_call
```
**Symbols:**

```
ffffffff81809b40-ffffffff81809b69: call_commit_handler.part.7 (STB_LOCAL)
ffffffff8180a600-ffffffff8180a61c: call_commit_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int call_commit_handler(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/wireless/wext-core.c (ffffffff8187bfac)
Location: net/wireless/wext-core.c:897
Inline: True
Inline callers:
  - net/wireless/wext-core.c:ioctl_standard_call
Direct callers:
  - net/wireless/wext-core.c:ioctl_standard_call
  - net/wireless/wext-priv.c:compat_private_call
  - net/wireless/wext-priv.c:ioctl_private_call
```
**Symbols:**

```
ffffffff8187b640-ffffffff8187b669: call_commit_handler.part.9 (STB_LOCAL)
ffffffff8187c160-ffffffff8187c17c: call_commit_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

```c
int call_commit_handler(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/wireless/wext-core.c (ffffffff818b086c)
Location: net/wireless/wext-core.c:897
Inline: True
Inline callers:
  - net/wireless/wext-core.c:ioctl_standard_call
Direct callers:
  - net/wireless/wext-core.c:ioctl_standard_call
  - net/wireless/wext-priv.c:compat_private_call
  - net/wireless/wext-priv.c:ioctl_private_call
```
**Symbols:**

```
ffffffff818aff00-ffffffff818aff29: call_commit_handler.part.9 (STB_LOCAL)
ffffffff818b0a20-ffffffff818b0a3c: call_commit_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int call_commit_handler(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/wireless/wext-core.c (ffffffff818d71e9)
Location: net/wireless/wext-core.c:897
Inline: True
Inline callers:
  - net/wireless/wext-core.c:ioctl_standard_call
Direct callers:
  - net/wireless/wext-core.c:ioctl_standard_call
  - net/wireless/wext-priv.c:compat_private_call
  - net/wireless/wext-priv.c:ioctl_private_call
```
**Symbols:**

```
ffffffff818d68e0-ffffffff818d6908: call_commit_handler.part.10 (STB_LOCAL)
ffffffff818d73a0-ffffffff818d73bc: call_commit_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int call_commit_handler(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/wireless/wext-core.c (ffffffff8195cdbb)
Location: net/wireless/wext-core.c:897
Inline: True
Inline callers:
  - net/wireless/wext-core.c:ioctl_standard_call
Direct callers:
  - net/wireless/wext-core.c:ioctl_standard_call
  - net/wireless/wext-priv.c:compat_private_call
  - net/wireless/wext-priv.c:ioctl_private_call
```
**Symbols:**

```
ffffffff8195c4b0-ffffffff8195c4db: call_commit_handler.part.10 (STB_LOCAL)
ffffffff8195cf80-ffffffff8195cf9c: call_commit_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int call_commit_handler(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/wireless/wext-core.c (ffffffff819b65bb)
Location: net/wireless/wext-core.c:895
Inline: True
Inline callers:
  - net/wireless/wext-core.c:ioctl_standard_call
Direct callers:
  - net/wireless/wext-priv.c:compat_private_call
  - net/wireless/wext-priv.c:ioctl_private_call
```
**Symbols:**

```
ffffffff819b6790-ffffffff819b67c4: call_commit_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int call_commit_handler(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/wireless/wext-core.c (ffffffff819ed87b)
Location: net/wireless/wext-core.c:895
Inline: True
Inline callers:
  - net/wireless/wext-core.c:ioctl_standard_call
Direct callers:
  - net/wireless/wext-priv.c:compat_private_call
  - net/wireless/wext-priv.c:ioctl_private_call
```
**Symbols:**

```
ffffffff819eda50-ffffffff819eda84: call_commit_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int call_commit_handler(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/wireless/wext-core.c (ffffffff81a5ca00)
Location: net/wireless/wext-core.c:895
Inline: True
Inline callers:
  - net/wireless/wext-core.c:ioctl_standard_call
Direct callers:
  - net/wireless/wext-priv.c:compat_private_call
  - net/wireless/wext-priv.c:ioctl_private_call
```
**Symbols:**

```
ffffffff81a5cbd0-ffffffff81a5cc04: call_commit_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int call_commit_handler(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/wireless/wext-core.c (ffffffff81a93680)
Location: net/wireless/wext-core.c:896
Inline: True
Inline callers:
  - net/wireless/wext-core.c:ioctl_standard_call
Direct callers:
  - net/wireless/wext-priv.c:compat_private_call
  - net/wireless/wext-priv.c:ioctl_private_call
```
**Symbols:**

```
ffffffff81a93850-ffffffff81a93884: call_commit_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int call_commit_handler(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/wireless/wext-core.c (ffffffff81b8eb3b)
Location: net/wireless/wext-core.c:896
Inline: True
Inline callers:
  - net/wireless/wext-core.c:ioctl_standard_call
Direct callers:
  - net/wireless/wext-priv.c:compat_private_call
  - net/wireless/wext-priv.c:ioctl_private_call
```
**Symbols:**

```
ffffffff81b8ece0-ffffffff81b8ed14: call_commit_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int call_commit_handler(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/wireless/wext-core.c (ffffffff81b9e7db)
Location: net/wireless/wext-core.c:896
Inline: True
Inline callers:
  - net/wireless/wext-core.c:ioctl_standard_call
Direct callers:
  - net/wireless/wext-priv.c:compat_private_call
  - net/wireless/wext-priv.c:ioctl_private_call
```
**Symbols:**

```
ffffffff81b9e990-ffffffff81b9e9c9: call_commit_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int call_commit_handler(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/wireless/wext-core.c (ffffffff81b8d8bb)
Location: net/wireless/wext-core.c:896
Inline: True
Inline callers:
  - net/wireless/wext-core.c:ioctl_standard_call
Direct callers:
  - net/wireless/wext-priv.c:compat_private_call
  - net/wireless/wext-priv.c:ioctl_private_call
```
**Symbols:**

```
ffffffff81b8da70-ffffffff81b8daa9: call_commit_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int call_commit_handler(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/wireless/wext-core.c (ffffffff81c59d0d)
Location: net/wireless/wext-core.c:896
Inline: True
Inline callers:
  - net/wireless/wext-core.c:ioctl_standard_call
Direct callers:
  - net/wireless/wext-priv.c:compat_private_call
  - net/wireless/wext-priv.c:ioctl_private_call
```
**Symbols:**

```
ffffffff81c59ee0-ffffffff81c59f19: call_commit_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int call_commit_handler(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/wireless/wext-core.c (ffffffff81dfb564)
Location: net/wireless/wext-core.c:896
Inline: True
Inline callers:
  - net/wireless/wext-core.c:ioctl_standard_call
Direct callers:
  - net/wireless/wext-priv.c:compat_private_call
  - net/wireless/wext-priv.c:ioctl_private_call
```
**Symbols:**

```
ffffffff81dfb770-ffffffff81dfb7c8: call_commit_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int call_commit_handler(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/wireless/wext-core.c (ffffffff81fcfdf0)
Location: net/wireless/wext-core.c:899
Inline: False
Direct callers:
  - net/wireless/wext-core.c:ioctl_standard_call
  - net/wireless/wext-priv.c:compat_private_call
  - net/wireless/wext-priv.c:ioctl_private_call
```
**Symbols:**

```
ffffffff81fcfdf0-ffffffff81fcfe48: call_commit_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int call_commit_handler(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/wireless/wext-core.c (ffffffff8204b8b0)
Location: net/wireless/wext-core.c:921
Inline: False
Direct callers:
  - net/wireless/wext-core.c:ioctl_standard_call
  - net/wireless/wext-priv.c:compat_private_call
  - net/wireless/wext-priv.c:ioctl_private_call
```
**Symbols:**

```
ffffffff8204b8b0-ffffffff8204b908: call_commit_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int call_commit_handler(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/wireless/wext-core.c (ffffffff8211dd30)
Location: net/wireless/wext-core.c:921
Inline: False
Direct callers:
  - net/wireless/wext-core.c:ioctl_standard_call
  - net/wireless/wext-priv.c:compat_private_call
  - net/wireless/wext-priv.c:ioctl_private_call
```
**Symbols:**

```
ffffffff8211dd30-ffffffff8211dd8b: call_commit_handler (STB_GLOBAL)
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
int call_commit_handler(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/wireless/wext-core.c (ffff800010d6180c)
Location: net/wireless/wext-core.c:896
Inline: True
Inline callers:
  - net/wireless/wext-core.c:ioctl_standard_call
Direct callers:
  - net/wireless/wext-priv.c:compat_private_call
  - net/wireless/wext-priv.c:ioctl_private_call
```
**Symbols:**

```
ffff800010d61a58-ffff800010d61abc: call_commit_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int call_commit_handler(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/wireless/wext-core.c (c0e60c74)
Location: net/wireless/wext-core.c:896
Inline: True
Inline callers:
  - net/wireless/wext-core.c:ioctl_standard_call
Direct callers:
  - net/wireless/wext-priv.c:ioctl_private_call
```
**Symbols:**

```
c0e60df0-c0e60e48: call_commit_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int call_commit_handler(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/wireless/wext-core.c (c000000000e9cb68)
Location: net/wireless/wext-core.c:896
Inline: True
Inline callers:
  - net/wireless/wext-core.c:ioctl_standard_call
Direct callers:
  - net/wireless/wext-priv.c:compat_private_call
  - net/wireless/wext-priv.c:ioctl_private_call
```
**Symbols:**

```
c000000000e9ce40-c000000000e9cebc: call_commit_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int call_commit_handler(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/wireless/wext-core.c (ffffffe0008963da)
Location: net/wireless/wext-core.c:896
Inline: True
Inline callers:
  - net/wireless/wext-core.c:ioctl_standard_call
Direct callers:
  - net/wireless/wext-priv.c:ioctl_private_call
```
**Symbols:**

```
ffffffe0008964cc-ffffffe00089650a: call_commit_handler (STB_GLOBAL)
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
int call_commit_handler(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/wireless/wext-core.c (ffffffff81a32d10)
Location: net/wireless/wext-core.c:896
Inline: True
Inline callers:
  - net/wireless/wext-core.c:ioctl_standard_call
Direct callers:
  - net/wireless/wext-priv.c:compat_private_call
  - net/wireless/wext-priv.c:ioctl_private_call
```
**Symbols:**

```
ffffffff81a32ee0-ffffffff81a32f14: call_commit_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int call_commit_handler(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/wireless/wext-core.c (ffffffff819f0010)
Location: net/wireless/wext-core.c:896
Inline: True
```
**Symbols:**

```
ffffffff819f0010-ffffffff819f001d: call_commit_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int call_commit_handler(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/wireless/wext-core.c (ffffffff81a9e8c0)
Location: net/wireless/wext-core.c:896
Inline: True
Inline callers:
  - net/wireless/wext-core.c:ioctl_standard_call
Direct callers:
  - net/wireless/wext-priv.c:compat_private_call
  - net/wireless/wext-priv.c:ioctl_private_call
```
**Symbols:**

```
ffffffff81a9ea90-ffffffff81a9eac4: call_commit_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int call_commit_handler(struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/wireless/wext-core.c (ffffffff81aaaac0)
Location: net/wireless/wext-core.c:896
Inline: True
Inline callers:
  - net/wireless/wext-core.c:ioctl_standard_call
Direct callers:
  - net/wireless/wext-priv.c:compat_private_call
  - net/wireless/wext-priv.c:ioctl_private_call
```
**Symbols:**

```
ffffffff81aaac90-ffffffff81aaacc4: call_commit_handler (STB_GLOBAL)
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
