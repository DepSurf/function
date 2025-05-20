# Function: <code>usb_register_dev</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int usb_register_dev(struct usb_interface *intf, struct usb_class_driver *class_driver);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/file.c (ffffffff81617360)
Location: drivers/usb/core/file.c:151
Inline: False
```
**Symbols:**

```
ffffffff81617360-ffffffff8161762e: usb_register_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int usb_register_dev(struct usb_interface *intf, struct usb_class_driver *class_driver);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/file.c (ffffffff81677450)
Location: drivers/usb/core/file.c:152
Inline: False
```
**Symbols:**

```
ffffffff81677450-ffffffff816776ec: usb_register_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int usb_register_dev(struct usb_interface *intf, struct usb_class_driver *class_driver);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/file.c (ffffffff816a5130)
Location: drivers/usb/core/file.c:154
Inline: False
```
**Symbols:**

```
ffffffff816a5130-ffffffff816a53cc: usb_register_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int usb_register_dev(struct usb_interface *intf, struct usb_class_driver *class_driver);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/file.c (ffffffff816ba4c0)
Location: drivers/usb/core/file.c:156
Inline: True
```
**Symbols:**

```
ffffffff816ba4c0-ffffffff816ba749: usb_register_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int usb_register_dev(struct usb_interface *intf, struct usb_class_driver *class_driver);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/file.c (ffffffff81725e90)
Location: drivers/usb/core/file.c:156
Inline: True
```
**Symbols:**

```
ffffffff81725e90-ffffffff8172611f: usb_register_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
int usb_register_dev(struct usb_interface *intf, struct usb_class_driver *class_driver);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/core/file.c (0)
Location: drivers/usb/core/file.c:156
Inline: True
```
**Symbols:**

```
ffffffff81764fe3-ffffffff81765023: usb_register_dev.cold.5 (STB_LOCAL)
ffffffff81764c50-ffffffff81764eb2: usb_register_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
int usb_register_dev(struct usb_interface *intf, struct usb_class_driver *class_driver);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/core/file.c (ffffffff81789340)
Location: drivers/usb/core/file.c:156
Inline: True
```
**Symbols:**

```
ffffffff81789663-ffffffff817896a3: usb_register_dev.cold.5 (STB_LOCAL)
ffffffff817892d0-ffffffff81789532: usb_register_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int usb_register_dev(struct usb_interface *intf, struct usb_class_driver *class_driver);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/core/file.c (ffffffff817c77d2)
Location: drivers/usb/core/file.c:156
Inline: True
```
**Symbols:**

```
ffffffff817c7af3-ffffffff817c7b33: usb_register_dev.cold (STB_LOCAL)
ffffffff817c7760-ffffffff817c79bf: usb_register_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int usb_register_dev(struct usb_interface *intf, struct usb_class_driver *class_driver);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/core/file.c (ffffffff817f82f2)
Location: drivers/usb/core/file.c:156
Inline: True
```
**Symbols:**

```
ffffffff817f8613-ffffffff817f8653: usb_register_dev.cold (STB_LOCAL)
ffffffff817f8280-ffffffff817f84df: usb_register_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int usb_register_dev(struct usb_interface *intf, struct usb_class_driver *class_driver);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/core/file.c (ffffffff818c8300)
Location: drivers/usb/core/file.c:156
Inline: True
```
**Symbols:**

```
ffffffff818c8300-ffffffff818c846a: usb_register_dev.part.0 (STB_LOCAL)
ffffffff818c8550-ffffffff818c85c1: usb_register_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int usb_register_dev(struct usb_interface *intf, struct usb_class_driver *class_driver);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/core/file.c (ffffffff818d34b0)
Location: drivers/usb/core/file.c:156
Inline: True
```
**Symbols:**

```
ffffffff818d34b0-ffffffff818d361a: usb_register_dev.part.0 (STB_LOCAL)
ffffffff818d3700-ffffffff818d3771: usb_register_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int usb_register_dev(struct usb_interface *intf, struct usb_class_driver *class_driver);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/core/file.c (ffffffff818b6ac5)
Location: drivers/usb/core/file.c:156
Inline: True
```
**Symbols:**

```
ffffffff81c0fe18-ffffffff81c0fe58: usb_register_dev.cold (STB_LOCAL)
ffffffff818b6a40-ffffffff818b6cdb: usb_register_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int usb_register_dev(struct usb_interface *intf, struct usb_class_driver *class_driver);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/core/file.c (ffffffff8194c445)
Location: drivers/usb/core/file.c:156
Inline: True
```
**Symbols:**

```
ffffffff81d16e69-ffffffff81d16ea8: usb_register_dev.cold (STB_LOCAL)
ffffffff8194c3c0-ffffffff8194c6ce: usb_register_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int usb_register_dev(struct usb_interface *intf, struct usb_class_driver *class_driver);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/file.c (0)
Location: drivers/usb/core/file.c:156
Inline: False
```
**Symbols:**

```
ffffffff81ee1d96-ffffffff81ee1dd3: usb_register_dev.cold (STB_LOCAL)
ffffffff81aa4e90-ffffffff81aa51d3: usb_register_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int usb_register_dev(struct usb_interface *intf, struct usb_class_driver *class_driver);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/file.c (ffffffff81c2b830)
Location: drivers/usb/core/file.c:156
Inline: False
```
**Symbols:**

```
ffffffff81c2b830-ffffffff81c2bbb6: usb_register_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int usb_register_dev(struct usb_interface *intf, struct usb_class_driver *class_driver);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/file.c (ffffffff81c927e0)
Location: drivers/usb/core/file.c:156
Inline: False
```
**Symbols:**

```
ffffffff81c927e0-ffffffff81c92b4f: usb_register_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int usb_register_dev(struct usb_interface *intf, struct usb_class_driver *class_driver);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/file.c (ffffffff81d47440)
Location: drivers/usb/core/file.c:110
Inline: False
```
**Symbols:**

```
ffffffff81d47440-ffffffff81d4766b: usb_register_dev (STB_GLOBAL)
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
int usb_register_dev(struct usb_interface *intf, struct usb_class_driver *class_driver);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/file.c (ffff800010a28f58)
Location: drivers/usb/core/file.c:156
Inline: True
```
**Symbols:**

```
ffff800010a28f58-ffff800010a291e4: usb_register_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int usb_register_dev(struct usb_interface *intf, struct usb_class_driver *class_driver);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/file.c (c0afef34)
Location: drivers/usb/core/file.c:156
Inline: True
```
**Symbols:**

```
c0afef34-c0aff1b4: usb_register_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int usb_register_dev(struct usb_interface *intf, struct usb_class_driver *class_driver);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/file.c (c000000000ae5200)
Location: drivers/usb/core/file.c:156
Inline: True
```
**Symbols:**

```
c000000000ae5200-c000000000ae5588: usb_register_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int usb_register_dev(struct usb_interface *intf, struct usb_class_driver *class_driver);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/file.c (ffffffe00064a98c)
Location: drivers/usb/core/file.c:156
Inline: True
```
**Symbols:**

```
ffffffe00064a98c-ffffffe00064abda: usb_register_dev (STB_GLOBAL)
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
int usb_register_dev(struct usb_interface *intf, struct usb_class_driver *class_driver);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/core/file.c (ffffffff817b06d2)
Location: drivers/usb/core/file.c:156
Inline: True
```
**Symbols:**

```
ffffffff817b09f3-ffffffff817b0a33: usb_register_dev.cold (STB_LOCAL)
ffffffff817b0660-ffffffff817b08bf: usb_register_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int usb_register_dev(struct usb_interface *intf, struct usb_class_driver *class_driver);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/file.c (0)
Location: drivers/usb/core/file.c:156
Inline: False
```
**Symbols:**

```
ffffffff817a2423-ffffffff817a2463: usb_register_dev.cold (STB_LOCAL)
ffffffff817a2020-ffffffff817a22a5: usb_register_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
int usb_register_dev(struct usb_interface *intf, struct usb_class_driver *class_driver);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/core/file.c (ffffffff817ed172)
Location: drivers/usb/core/file.c:156
Inline: True
```
**Symbols:**

```
ffffffff817ed493-ffffffff817ed4d3: usb_register_dev.cold (STB_LOCAL)
ffffffff817ed100-ffffffff817ed35f: usb_register_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
int usb_register_dev(struct usb_interface *intf, struct usb_class_driver *class_driver);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/core/file.c (ffffffff818073b2)
Location: drivers/usb/core/file.c:156
Inline: True
```
**Symbols:**

```
ffffffff818076d3-ffffffff81807713: usb_register_dev.cold (STB_LOCAL)
ffffffff81807340-ffffffff8180759f: usb_register_dev (STB_GLOBAL)
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
