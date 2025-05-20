# Function: <code>quirks_param_set</code>

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
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int quirks_param_set(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/quirks.c (ffffffff8172d0e0)
Location: drivers/usb/core/quirks.c:28
Inline: True
```
**Symbols:**

```
ffffffff8172d0e0-ffffffff8172d390: quirks_param_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int quirks_param_set(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/quirks.c (ffffffff8176bf40)
Location: drivers/usb/core/quirks.c:28
Inline: True
```
**Symbols:**

```
ffffffff8176bf40-ffffffff8176c1da: quirks_param_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int quirks_param_set(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/quirks.c (ffffffff81790510)
Location: drivers/usb/core/quirks.c:28
Inline: True
```
**Symbols:**

```
ffffffff81790510-ffffffff81790829: quirks_param_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int quirks_param_set(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/core/quirks.c (ffffffff817cedb0)
Location: drivers/usb/core/quirks.c:28
Inline: True
```
**Symbols:**

```
ffffffff817cedb0-ffffffff817cf0d2: quirks_param_set.part.0 (STB_LOCAL)
ffffffff817cf0e0-ffffffff817cf103: quirks_param_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int quirks_param_set(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/core/quirks.c (ffffffff817ffbc0)
Location: drivers/usb/core/quirks.c:28
Inline: True
```
**Symbols:**

```
ffffffff817ffbc0-ffffffff817ffee2: quirks_param_set.part.0 (STB_LOCAL)
ffffffff817ffef0-ffffffff817fff13: quirks_param_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int quirks_param_set(const char *value, const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/quirks.c (ffffffff818d0280)
Location: drivers/usb/core/quirks.c:28
Inline: False
```
**Symbols:**

```
ffffffff818d0280-ffffffff818d05d2: quirks_param_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int quirks_param_set(const char *value, const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/quirks.c (ffffffff818da6e0)
Location: drivers/usb/core/quirks.c:28
Inline: False
```
**Symbols:**

```
ffffffff818da6e0-ffffffff818daa32: quirks_param_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int quirks_param_set(const char *value, const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/quirks.c (ffffffff818bdb40)
Location: drivers/usb/core/quirks.c:28
Inline: False
```
**Symbols:**

```
ffffffff818bdb40-ffffffff818bde9e: quirks_param_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int quirks_param_set(const char *value, const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/quirks.c (ffffffff81953ea0)
Location: drivers/usb/core/quirks.c:28
Inline: False
```
**Symbols:**

```
ffffffff81953ea0-ffffffff819541fe: quirks_param_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int quirks_param_set(const char *value, const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/quirks.c (ffffffff81aad790)
Location: drivers/usb/core/quirks.c:28
Inline: False
```
**Symbols:**

```
ffffffff81aad790-ffffffff81aadaf8: quirks_param_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int quirks_param_set(const char *value, const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/quirks.c (ffffffff81c35150)
Location: drivers/usb/core/quirks.c:28
Inline: False
```
**Symbols:**

```
ffffffff81c35150-ffffffff81c354b8: quirks_param_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int quirks_param_set(const char *value, const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/quirks.c (ffffffff81c9c470)
Location: drivers/usb/core/quirks.c:28
Inline: False
```
**Symbols:**

```
ffffffff81c9c470-ffffffff81c9c7d4: quirks_param_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int quirks_param_set(const char *value, const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/quirks.c (ffffffff81d51010)
Location: drivers/usb/core/quirks.c:28
Inline: False
```
**Symbols:**

```
ffffffff81d51010-ffffffff81d51388: quirks_param_set (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
int quirks_param_set(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/core/quirks.c (ffff800010a339f8)
Location: drivers/usb/core/quirks.c:28
Inline: True
```
**Symbols:**

```
ffff800010a339f8-ffff800010a33ce8: quirks_param_set.part.0 (STB_LOCAL)
ffff800010a33ce8-ffff800010a33d28: quirks_param_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
int quirks_param_set(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/core/quirks.c (c0b0729c)
Location: drivers/usb/core/quirks.c:28
Inline: True
```
**Symbols:**

```
c0b0729c-c0b07578: quirks_param_set.part.0 (STB_LOCAL)
c0b07578-c0b075a8: quirks_param_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
int quirks_param_set(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/core/quirks.c (c000000000af1050)
Location: drivers/usb/core/quirks.c:28
Inline: True
```
**Symbols:**

```
c000000000af1050-c000000000af1474: quirks_param_set.part.0 (STB_LOCAL)
c000000000af1480-c000000000af14e8: quirks_param_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
int quirks_param_set(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/core/quirks.c (ffffffe000651752)
Location: drivers/usb/core/quirks.c:28
Inline: True
```
**Symbols:**

```
ffffffe000651752-ffffffe000651994: quirks_param_set.part.0 (STB_LOCAL)
ffffffe000651994-ffffffe0006519d2: quirks_param_set (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
int quirks_param_set(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/core/quirks.c (ffffffff817b7fa0)
Location: drivers/usb/core/quirks.c:28
Inline: True
```
**Symbols:**

```
ffffffff817b7fa0-ffffffff817b82c2: quirks_param_set.part.0 (STB_LOCAL)
ffffffff817b82d0-ffffffff817b82f3: quirks_param_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
int quirks_param_set(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/core/quirks.c (ffffffff817a99d0)
Location: drivers/usb/core/quirks.c:28
Inline: True
```
**Symbols:**

```
ffffffff817a99d0-ffffffff817a9cf2: quirks_param_set.part.0 (STB_LOCAL)
ffffffff817a9d00-ffffffff817a9d23: quirks_param_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
int quirks_param_set(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/core/quirks.c (ffffffff817f4a40)
Location: drivers/usb/core/quirks.c:28
Inline: True
```
**Symbols:**

```
ffffffff817f4a40-ffffffff817f4d62: quirks_param_set.part.0 (STB_LOCAL)
ffffffff817f4d70-ffffffff817f4d93: quirks_param_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
int quirks_param_set(const char *val, const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/core/quirks.c (ffffffff8180ec80)
Location: drivers/usb/core/quirks.c:28
Inline: True
```
**Symbols:**

```
ffffffff8180ec80-ffffffff8180efa2: quirks_param_set.part.0 (STB_LOCAL)
ffffffff8180efb0-ffffffff8180efd3: quirks_param_set (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const char *value</code>
</li>
<li>
<b>Param removed. </b>
<code>const char *val</code>
</li>
</ul>
</details>
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
