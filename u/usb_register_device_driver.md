# Function: <code>usb_register_device_driver</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int usb_register_device_driver(struct usb_device_driver *new_udriver, struct module *owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/driver.c (ffffffff81613b40)
Location: drivers/usb/core/driver.c:876
Inline: False
```
**Symbols:**

```
ffffffff81613b40-ffffffff81613be8: usb_register_device_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int usb_register_device_driver(struct usb_device_driver *new_udriver, struct module *owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/driver.c (ffffffff81673b20)
Location: drivers/usb/core/driver.c:886
Inline: False
```
**Symbols:**

```
ffffffff81673b20-ffffffff81673bc2: usb_register_device_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int usb_register_device_driver(struct usb_device_driver *new_udriver, struct module *owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/driver.c (ffffffff816a17b0)
Location: drivers/usb/core/driver.c:889
Inline: False
```
**Symbols:**

```
ffffffff816a17b0-ffffffff816a1852: usb_register_device_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int usb_register_device_driver(struct usb_device_driver *new_udriver, struct module *owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/driver.c (ffffffff816b68b0)
Location: drivers/usb/core/driver.c:889
Inline: False
```
**Symbols:**

```
ffffffff816b68b0-ffffffff816b694e: usb_register_device_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int usb_register_device_driver(struct usb_device_driver *new_udriver, struct module *owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/driver.c (ffffffff81722140)
Location: drivers/usb/core/driver.c:889
Inline: False
```
**Symbols:**

```
ffffffff81722140-ffffffff817221de: usb_register_device_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int usb_register_device_driver(struct usb_device_driver *new_udriver, struct module *owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/driver.c (0)
Location: drivers/usb/core/driver.c:889
Inline: False
Direct callers:
  - drivers/usb/core/usb.c:usb_init
```
**Symbols:**

```
ffffffff81762ae0-ffffffff81762b18: usb_register_device_driver.cold.22 (STB_LOCAL)
ffffffff81760e70-ffffffff81760edf: usb_register_device_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int usb_register_device_driver(struct usb_device_driver *new_udriver, struct module *owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/driver.c (0)
Location: drivers/usb/core/driver.c:886
Inline: False
Direct callers:
  - drivers/usb/core/usb.c:usb_init
```
**Symbols:**

```
ffffffff8178711f-ffffffff81787157: usb_register_device_driver.cold.21 (STB_LOCAL)
ffffffff81785430-ffffffff8178549f: usb_register_device_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int usb_register_device_driver(struct usb_device_driver *new_udriver, struct module *owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/driver.c (0)
Location: drivers/usb/core/driver.c:881
Inline: False
Direct callers:
  - drivers/usb/core/usb.c:usb_init
```
**Symbols:**

```
ffffffff817c559f-ffffffff817c55d7: usb_register_device_driver.cold (STB_LOCAL)
ffffffff817c39c0-ffffffff817c3a2f: usb_register_device_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int usb_register_device_driver(struct usb_device_driver *new_udriver, struct module *owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/driver.c (0)
Location: drivers/usb/core/driver.c:881
Inline: False
Direct callers:
  - drivers/usb/core/usb.c:usb_init
```
**Symbols:**

```
ffffffff817f5f3f-ffffffff817f5f77: usb_register_device_driver.cold (STB_LOCAL)
ffffffff817f4340-ffffffff817f43ba: usb_register_device_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int usb_register_device_driver(struct usb_device_driver *new_udriver, struct module *owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/driver.c (0)
Location: drivers/usb/core/driver.c:966
Inline: False
Direct callers:
  - drivers/usb/core/usb.c:usb_init
```
**Symbols:**

```
ffffffff818c5e52-ffffffff818c5ea4: usb_register_device_driver.cold (STB_LOCAL)
ffffffff818c3ea0-ffffffff818c3f2c: usb_register_device_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int usb_register_device_driver(struct usb_device_driver *new_udriver, struct module *owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/driver.c (0)
Location: drivers/usb/core/driver.c:978
Inline: False
Direct callers:
  - drivers/usb/core/usb.c:usb_init
```
**Symbols:**

```
ffffffff81c1d269-ffffffff81c1d2bb: usb_register_device_driver.cold (STB_LOCAL)
ffffffff818cfd90-ffffffff818cfe1c: usb_register_device_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int usb_register_device_driver(struct usb_device_driver *new_udriver, struct module *owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/driver.c (0)
Location: drivers/usb/core/driver.c:974
Inline: False
Direct callers:
  - drivers/usb/core/usb.c:usb_init
```
**Symbols:**

```
ffffffff81c0f12f-ffffffff81c0f181: usb_register_device_driver.cold (STB_LOCAL)
ffffffff818b33c0-ffffffff818b344c: usb_register_device_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int usb_register_device_driver(struct usb_device_driver *new_udriver, struct module *owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/driver.c (0)
Location: drivers/usb/core/driver.c:974
Inline: False
Direct callers:
  - drivers/usb/core/usb.c:usb_init
```
**Symbols:**

```
ffffffff81d162ce-ffffffff81d16320: usb_register_device_driver.cold (STB_LOCAL)
ffffffff81948810-ffffffff8194889c: usb_register_device_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int usb_register_device_driver(struct usb_device_driver *new_udriver, struct module *owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/driver.c (0)
Location: drivers/usb/core/driver.c:975
Inline: False
Direct callers:
  - drivers/usb/core/usb.c:usb_init
```
**Symbols:**

```
ffffffff81ee0ead-ffffffff81ee0efd: usb_register_device_driver.cold (STB_LOCAL)
ffffffff81aa1330-ffffffff81aa13b9: usb_register_device_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int usb_register_device_driver(struct usb_device_driver *new_udriver, struct module *owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/driver.c (ffffffff81c269c0)
Location: drivers/usb/core/driver.c:975
Inline: False
Direct callers:
  - drivers/usb/core/usb.c:usb_init
```
**Symbols:**

```
ffffffff81c269c0-ffffffff81c26aa0: usb_register_device_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int usb_register_device_driver(struct usb_device_driver *new_udriver, struct module *owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/driver.c (ffffffff81c8d980)
Location: drivers/usb/core/driver.c:975
Inline: False
Direct callers:
  - drivers/usb/core/usb.c:usb_init
```
**Symbols:**

```
ffffffff81c8d980-ffffffff81c8da60: usb_register_device_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int usb_register_device_driver(struct usb_device_driver *new_udriver, struct module *owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/driver.c (ffffffff81d42650)
Location: drivers/usb/core/driver.c:983
Inline: False
Direct callers:
  - drivers/usb/core/usb.c:usb_init
```
**Symbols:**

```
ffffffff81d42650-ffffffff81d42726: usb_register_device_driver (STB_GLOBAL)
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
int usb_register_device_driver(struct usb_device_driver *new_udriver, struct module *owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/driver.c (ffff800010a24de8)
Location: drivers/usb/core/driver.c:881
Inline: False
Direct callers:
  - drivers/usb/core/usb.c:usb_init
```
**Symbols:**

```
ffff800010a24de8-ffff800010a24ea0: usb_register_device_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int usb_register_device_driver(struct usb_device_driver *new_udriver, struct module *owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/driver.c (c0afb414)
Location: drivers/usb/core/driver.c:881
Inline: False
Direct callers:
  - drivers/usb/core/usb.c:usb_init
```
**Symbols:**

```
c0afb414-c0afb4dc: usb_register_device_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int usb_register_device_driver(struct usb_device_driver *new_udriver, struct module *owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/driver.c (c000000000adfca0)
Location: drivers/usb/core/driver.c:881
Inline: False
Direct callers:
  - drivers/usb/core/usb.c:usb_init
```
**Symbols:**

```
c000000000adfca0-c000000000adfda0: usb_register_device_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int usb_register_device_driver(struct usb_device_driver *new_udriver, struct module *owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/driver.c (ffffffe0006470d4)
Location: drivers/usb/core/driver.c:881
Inline: False
Direct callers:
  - drivers/usb/core/usb.c:usb_init
```
**Symbols:**

```
ffffffe0006470d4-ffffffe000647182: usb_register_device_driver (STB_GLOBAL)
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
int usb_register_device_driver(struct usb_device_driver *new_udriver, struct module *owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/driver.c (0)
Location: drivers/usb/core/driver.c:881
Inline: False
Direct callers:
  - drivers/usb/core/usb.c:usb_init
```
**Symbols:**

```
ffffffff817ae31f-ffffffff817ae357: usb_register_device_driver.cold (STB_LOCAL)
ffffffff817ac720-ffffffff817ac79a: usb_register_device_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int usb_register_device_driver(struct usb_device_driver *new_udriver, struct module *owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/driver.c (0)
Location: drivers/usb/core/driver.c:881
Inline: False
Direct callers:
  - drivers/usb/core/usb.c:usb_init
```
**Symbols:**

```
ffffffff8179fd1f-ffffffff8179fd57: usb_register_device_driver.cold (STB_LOCAL)
ffffffff8179e120-ffffffff8179e19a: usb_register_device_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int usb_register_device_driver(struct usb_device_driver *new_udriver, struct module *owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/driver.c (0)
Location: drivers/usb/core/driver.c:881
Inline: False
Direct callers:
  - drivers/usb/core/usb.c:usb_init
```
**Symbols:**

```
ffffffff817eadbf-ffffffff817eadf7: usb_register_device_driver.cold (STB_LOCAL)
ffffffff817e91c0-ffffffff817e923a: usb_register_device_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int usb_register_device_driver(struct usb_device_driver *new_udriver, struct module *owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/driver.c (0)
Location: drivers/usb/core/driver.c:881
Inline: False
Direct callers:
  - drivers/usb/core/usb.c:usb_init
```
**Symbols:**

```
ffffffff81804fff-ffffffff81805037: usb_register_device_driver.cold (STB_LOCAL)
ffffffff818036f0-ffffffff8180376a: usb_register_device_driver (STB_GLOBAL)
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
