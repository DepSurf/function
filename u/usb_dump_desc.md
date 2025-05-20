# Function: <code>usb_dump_desc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devices.c (ffffffff8161e181)
Location: drivers/usb/core/devices.c:426
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usb_device_dump
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devices.c (ffffffff8167e956)
Location: drivers/usb/core/devices.c:419
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usb_device_dump
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devices.c (ffffffff816ac6d6)
Location: drivers/usb/core/devices.c:413
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usb_device_dump
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devices.c (ffffffff816c193b)
Location: drivers/usb/core/devices.c:413
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usb_device_dump
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devices.c (ffffffff8172d70b)
Location: drivers/usb/core/devices.c:400
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usb_device_dump
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devices.c (ffffffff8176c53f)
Location: drivers/usb/core/devices.c:400
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usb_device_dump
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devices.c (ffffffff81790b8f)
Location: drivers/usb/core/devices.c:400
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usb_device_dump
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
char *usb_dump_desc(char *start, char *end, struct usb_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devices.c (ffffffff817cf320)
Location: drivers/usb/core/devices.c:400
Inline: False
Direct callers:
  - drivers/usb/core/devices.c:usb_device_dump
```
**Symbols:**

```
ffffffff817cf320-ffffffff817cf9ea: usb_dump_desc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
char *usb_dump_desc(char *start, char *end, struct usb_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devices.c (ffffffff81800190)
Location: drivers/usb/core/devices.c:400
Inline: False
Direct callers:
  - drivers/usb/core/devices.c:usb_device_dump
```
**Symbols:**

```
ffffffff81800190-ffffffff8180085a: usb_dump_desc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
char *usb_dump_desc(char *start, char *end, struct usb_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devices.c (ffffffff818d0d00)
Location: drivers/usb/core/devices.c:400
Inline: False
Direct callers:
  - drivers/usb/core/devices.c:usb_device_dump
```
**Symbols:**

```
ffffffff818d0d00-ffffffff818d0ef0: usb_dump_desc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
char *usb_dump_desc(char *start, char *end, struct usb_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devices.c (ffffffff818db170)
Location: drivers/usb/core/devices.c:381
Inline: False
Direct callers:
  - drivers/usb/core/devices.c:usb_device_dump
```
**Symbols:**

```
ffffffff818db170-ffffffff818db360: usb_dump_desc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
char *usb_dump_desc(char *start, char *end, struct usb_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devices.c (ffffffff818be540)
Location: drivers/usb/core/devices.c:368
Inline: False
Direct callers:
  - drivers/usb/core/devices.c:usb_device_dump
```
**Symbols:**

```
ffffffff818be540-ffffffff818be737: usb_dump_desc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
char *usb_dump_desc(char *start, char *end, struct usb_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devices.c (ffffffff81954a90)
Location: drivers/usb/core/devices.c:368
Inline: False
Direct callers:
  - drivers/usb/core/devices.c:usb_device_dump
```
**Symbols:**

```
ffffffff81954a90-ffffffff81954d94: usb_dump_desc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
char *usb_dump_desc(char *start, char *end, struct usb_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devices.c (ffffffff81aae390)
Location: drivers/usb/core/devices.c:364
Inline: False
Direct callers:
  - drivers/usb/core/devices.c:usb_device_dump
```
**Symbols:**

```
ffffffff81aae390-ffffffff81aae693: usb_dump_desc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
char *usb_dump_desc(char *start, char *end, struct usb_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devices.c (ffffffff81c35dd0)
Location: drivers/usb/core/devices.c:364
Inline: False
Direct callers:
  - drivers/usb/core/devices.c:usb_device_dump
```
**Symbols:**

```
ffffffff81c35dd0-ffffffff81c360d3: usb_dump_desc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
char *usb_dump_desc(char *start, char *end, struct usb_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devices.c (ffffffff81c9d0f0)
Location: drivers/usb/core/devices.c:364
Inline: False
Direct callers:
  - drivers/usb/core/devices.c:usb_device_dump
```
**Symbols:**

```
ffffffff81c9d0f0-ffffffff81c9d3cd: usb_dump_desc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
char *usb_dump_desc(char *start, char *end, struct usb_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devices.c (ffffffff81d51ca0)
Location: drivers/usb/core/devices.c:364
Inline: False
Direct callers:
  - drivers/usb/core/devices.c:usb_device_dump
```
**Symbols:**

```
ffffffff81d51ca0-ffffffff81d51f7d: usb_dump_desc (STB_LOCAL)
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
char *usb_dump_desc(char *start, char *end, struct usb_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devices.c (ffff800010a34050)
Location: drivers/usb/core/devices.c:400
Inline: False
Direct callers:
  - drivers/usb/core/devices.c:usb_device_dump
```
**Symbols:**

```
ffff800010a34050-ffff800010a346ec: usb_dump_desc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
char *usb_dump_desc(char *start, char *end, struct usb_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devices.c (c0b0786c)
Location: drivers/usb/core/devices.c:400
Inline: False
Direct callers:
  - drivers/usb/core/devices.c:usb_device_dump
```
**Symbols:**

```
c0b0786c-c0b07f88: usb_dump_desc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
char *usb_dump_desc(char *start, char *end, struct usb_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devices.c (c000000000af1910)
Location: drivers/usb/core/devices.c:400
Inline: False
Direct callers:
  - drivers/usb/core/devices.c:usb_device_dump
```
**Symbols:**

```
c000000000af1910-c000000000af20c4: usb_dump_desc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
char *usb_dump_desc(char *start, char *end, struct usb_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devices.c (ffffffe000651c8e)
Location: drivers/usb/core/devices.c:400
Inline: False
Direct callers:
  - drivers/usb/core/devices.c:usb_device_dump
```
**Symbols:**

```
ffffffe000651c8e-ffffffe000652234: usb_dump_desc (STB_LOCAL)
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
char *usb_dump_desc(char *start, char *end, struct usb_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devices.c (ffffffff817b8570)
Location: drivers/usb/core/devices.c:400
Inline: False
Direct callers:
  - drivers/usb/core/devices.c:usb_device_dump
```
**Symbols:**

```
ffffffff817b8570-ffffffff817b8c3a: usb_dump_desc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
char *usb_dump_desc(char *start, char *end, struct usb_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devices.c (ffffffff817a9fa0)
Location: drivers/usb/core/devices.c:400
Inline: False
Direct callers:
  - drivers/usb/core/devices.c:usb_device_dump
```
**Symbols:**

```
ffffffff817a9fa0-ffffffff817aa66a: usb_dump_desc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
char *usb_dump_desc(char *start, char *end, struct usb_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devices.c (ffffffff817f5010)
Location: drivers/usb/core/devices.c:400
Inline: False
Direct callers:
  - drivers/usb/core/devices.c:usb_device_dump
```
**Symbols:**

```
ffffffff817f5010-ffffffff817f56da: usb_dump_desc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
char *usb_dump_desc(char *start, char *end, struct usb_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devices.c (ffffffff8180f250)
Location: drivers/usb/core/devices.c:400
Inline: False
Direct callers:
  - drivers/usb/core/devices.c:usb_device_dump
```
**Symbols:**

```
ffffffff8180f250-ffffffff8180f91a: usb_dump_desc (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
