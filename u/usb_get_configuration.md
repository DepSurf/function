# Function: <code>usb_get_configuration</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int usb_get_configuration(struct usb_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/config.c (ffffffff81616cd0)
Location: drivers/usb/core/config.c:696
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_new_device
```
**Symbols:**

```
ffffffff81616cd0-ffffffff81616fed: usb_get_configuration (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int usb_get_configuration(struct usb_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/config.c (ffffffff81676d90)
Location: drivers/usb/core/config.c:762
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_new_device
```
**Symbols:**

```
ffffffff81676d90-ffffffff816770ce: usb_get_configuration (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int usb_get_configuration(struct usb_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/config.c (ffffffff816a4a70)
Location: drivers/usb/core/config.c:787
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_new_device
```
**Symbols:**

```
ffffffff816a4a70-ffffffff816a4dae: usb_get_configuration (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int usb_get_configuration(struct usb_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/config.c (ffffffff816b9e30)
Location: drivers/usb/core/config.c:787
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_new_device
```
**Symbols:**

```
ffffffff816b9e30-ffffffff816ba164: usb_get_configuration (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int usb_get_configuration(struct usb_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/config.c (ffffffff81725730)
Location: drivers/usb/core/config.c:797
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_new_device
```
**Symbols:**

```
ffffffff81725730-ffffffff81725a64: usb_get_configuration (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int usb_get_configuration(struct usb_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/config.c (ffffffff817644e0)
Location: drivers/usb/core/config.c:799
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_new_device
```
**Symbols:**

```
ffffffff817644e0-ffffffff81764818: usb_get_configuration (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int usb_get_configuration(struct usb_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/config.c (ffffffff81788b40)
Location: drivers/usb/core/config.c:799
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_new_device
```
**Symbols:**

```
ffffffff81788b40-ffffffff81788e78: usb_get_configuration (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int usb_get_configuration(struct usb_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/config.c (0)
Location: drivers/usb/core/config.c:799
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_new_device
```
**Symbols:**

```
ffffffff817c743d-ffffffff817c75a8: usb_get_configuration.cold (STB_LOCAL)
ffffffff817c6770-ffffffff817c698a: usb_get_configuration (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int usb_get_configuration(struct usb_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/config.c (0)
Location: drivers/usb/core/config.c:865
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_new_device
```
**Symbols:**

```
ffffffff817f7f62-ffffffff817f80cd: usb_get_configuration.cold (STB_LOCAL)
ffffffff817f71e0-ffffffff817f73fa: usb_get_configuration (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int usb_get_configuration(struct usb_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/config.c (0)
Location: drivers/usb/core/config.c:861
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_new_device
```
**Symbols:**

```
ffffffff818c8064-ffffffff818c8183: usb_get_configuration.cold (STB_LOCAL)
ffffffff818c72f0-ffffffff818c74d6: usb_get_configuration (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int usb_get_configuration(struct usb_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/config.c (0)
Location: drivers/usb/core/config.c:861
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_new_device
```
**Symbols:**

```
ffffffff81c1dd9e-ffffffff81c1deba: usb_get_configuration.cold (STB_LOCAL)
ffffffff818d2f30-ffffffff818d3116: usb_get_configuration (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int usb_get_configuration(struct usb_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/config.c (0)
Location: drivers/usb/core/config.c:861
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_new_device
```
**Symbols:**

```
ffffffff81c0fc75-ffffffff81c0fd8a: usb_get_configuration.cold (STB_LOCAL)
ffffffff818b64c0-ffffffff818b66a3: usb_get_configuration (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int usb_get_configuration(struct usb_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/config.c (0)
Location: drivers/usb/core/config.c:861
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_new_device
```
**Symbols:**

```
ffffffff81d16cc6-ffffffff81d16ddb: usb_get_configuration.cold (STB_LOCAL)
ffffffff8194bdc0-ffffffff8194bfa3: usb_get_configuration (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int usb_get_configuration(struct usb_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/config.c (0)
Location: drivers/usb/core/config.c:861
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_new_device
```
**Symbols:**

```
ffffffff81ee1bc7-ffffffff81ee1cf0: usb_get_configuration.cold (STB_LOCAL)
ffffffff81aa4860-ffffffff81aa4a60: usb_get_configuration (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int usb_get_configuration(struct usb_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/config.c (ffffffff81c2aff0)
Location: drivers/usb/core/config.c:861
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_new_device
```
**Symbols:**

```
ffffffff81c2aff0-ffffffff81c2b2f1: usb_get_configuration (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int usb_get_configuration(struct usb_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/config.c (ffffffff81c91f80)
Location: drivers/usb/core/config.c:861
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_new_device
```
**Symbols:**

```
ffffffff81c91f80-ffffffff81c9228c: usb_get_configuration (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int usb_get_configuration(struct usb_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/config.c (ffffffff81d46b40)
Location: drivers/usb/core/config.c:861
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_new_device
```
**Symbols:**

```
ffffffff81d46b40-ffffffff81d46e7b: usb_get_configuration (STB_GLOBAL)
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
int usb_get_configuration(struct usb_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/config.c (ffff800010a28850)
Location: drivers/usb/core/config.c:865
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_new_device
```
**Symbols:**

```
ffff800010a28850-ffff800010a28b20: usb_get_configuration (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int usb_get_configuration(struct usb_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/config.c (c0afe82c)
Location: drivers/usb/core/config.c:865
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_new_device
```
**Symbols:**

```
c0afe82c-c0afeb0c: usb_get_configuration (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int usb_get_configuration(struct usb_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/config.c (c000000000ae4820)
Location: drivers/usb/core/config.c:865
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_new_device
```
**Symbols:**

```
c000000000ae4820-c000000000ae4c04: usb_get_configuration (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int usb_get_configuration(struct usb_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/config.c (ffffffe00064a344)
Location: drivers/usb/core/config.c:865
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_new_device
```
**Symbols:**

```
ffffffe00064a344-ffffffe00064a608: usb_get_configuration (STB_GLOBAL)
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
int usb_get_configuration(struct usb_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/config.c (0)
Location: drivers/usb/core/config.c:865
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_new_device
```
**Symbols:**

```
ffffffff817b0342-ffffffff817b04ad: usb_get_configuration.cold (STB_LOCAL)
ffffffff817af5c0-ffffffff817af7da: usb_get_configuration (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int usb_get_configuration(struct usb_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/config.c (0)
Location: drivers/usb/core/config.c:865
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_new_device
```
**Symbols:**

```
ffffffff817a1d42-ffffffff817a1ead: usb_get_configuration.cold (STB_LOCAL)
ffffffff817a0fc0-ffffffff817a11da: usb_get_configuration (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int usb_get_configuration(struct usb_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/config.c (0)
Location: drivers/usb/core/config.c:865
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_new_device
```
**Symbols:**

```
ffffffff817ecde2-ffffffff817ecf4d: usb_get_configuration.cold (STB_LOCAL)
ffffffff817ec060-ffffffff817ec27a: usb_get_configuration (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int usb_get_configuration(struct usb_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/config.c (0)
Location: drivers/usb/core/config.c:865
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_new_device
```
**Symbols:**

```
ffffffff81807022-ffffffff8180718d: usb_get_configuration.cold (STB_LOCAL)
ffffffff818062a0-ffffffff818064ba: usb_get_configuration (STB_GLOBAL)
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
