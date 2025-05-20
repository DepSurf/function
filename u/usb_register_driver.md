# Function: <code>usb_register_driver</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int usb_register_driver(struct usb_driver *new_driver, struct module *owner, const char *mod_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/driver.c (ffffffff81613dc0)
Location: drivers/usb/core/driver.c:937
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_hub_init
```
**Symbols:**

```
ffffffff81613dc0-ffffffff81613ef6: usb_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int usb_register_driver(struct usb_driver *new_driver, struct module *owner, const char *mod_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/driver.c (ffffffff81673d30)
Location: drivers/usb/core/driver.c:947
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_hub_init
```
**Symbols:**

```
ffffffff81673d30-ffffffff81673e63: usb_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int usb_register_driver(struct usb_driver *new_driver, struct module *owner, const char *mod_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/driver.c (ffffffff816a19c0)
Location: drivers/usb/core/driver.c:950
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_hub_init
```
**Symbols:**

```
ffffffff816a19c0-ffffffff816a1af3: usb_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int usb_register_driver(struct usb_driver *new_driver, struct module *owner, const char *mod_name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/driver.c (ffffffff816b6dd0)
Location: drivers/usb/core/driver.c:950
Inline: True
Direct callers:
  - drivers/usb/core/hub.c:usb_hub_init
```
**Symbols:**

```
ffffffff816b6dd0-ffffffff816b6f17: usb_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int usb_register_driver(struct usb_driver *new_driver, struct module *owner, const char *mod_name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/driver.c (ffffffff81722660)
Location: drivers/usb/core/driver.c:950
Inline: True
Direct callers:
  - drivers/usb/core/hub.c:usb_hub_init
```
**Symbols:**

```
ffffffff81722660-ffffffff817227a7: usb_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int usb_register_driver(struct usb_driver *new_driver, struct module *owner, const char *mod_name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/driver.c (ffffffff817612c0)
Location: drivers/usb/core/driver.c:950
Inline: True
Direct callers:
  - drivers/usb/core/usb.c:usb_init
  - drivers/usb/core/hub.c:usb_hub_init
```
**Symbols:**

```
ffffffff817612c0-ffffffff817613f5: usb_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int usb_register_driver(struct usb_driver *new_driver, struct module *owner, const char *mod_name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/driver.c (ffffffff81785d30)
Location: drivers/usb/core/driver.c:947
Inline: True
Direct callers:
  - drivers/usb/core/usb.c:usb_init
  - drivers/usb/core/hub.c:usb_hub_init
```
**Symbols:**

```
ffffffff81785d30-ffffffff81785e65: usb_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int usb_register_driver(struct usb_driver *new_driver, struct module *owner, const char *mod_name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/core/driver.c (ffffffff817c5740)
Location: drivers/usb/core/driver.c:942
Inline: True
Direct callers:
  - drivers/usb/core/usb.c:usb_init
  - drivers/usb/core/hub.c:usb_hub_init
```
**Symbols:**

```
ffffffff817c5740-ffffffff817c575b: usb_register_driver.cold (STB_LOCAL)
ffffffff817c41e0-ffffffff817c42f5: usb_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int usb_register_driver(struct usb_driver *new_driver, struct module *owner, const char *mod_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/driver.c (0)
Location: drivers/usb/core/driver.c:943
Inline: False
Direct callers:
  - drivers/usb/core/usb.c:usb_init
  - drivers/usb/core/hub.c:usb_hub_init
```
**Symbols:**

```
ffffffff817f5fa6-ffffffff817f5fc1: usb_register_driver.cold (STB_LOCAL)
ffffffff817f4500-ffffffff817f4623: usb_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int usb_register_driver(struct usb_driver *new_driver, struct module *owner, const char *mod_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/driver.c (0)
Location: drivers/usb/core/driver.c:1035
Inline: False
Direct callers:
  - drivers/usb/core/usb.c:usb_init
  - drivers/usb/core/hub.c:usb_hub_init
```
**Symbols:**

```
ffffffff818c5ed3-ffffffff818c5eee: usb_register_driver.cold (STB_LOCAL)
ffffffff818c4070-ffffffff818c4193: usb_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int usb_register_driver(struct usb_driver *new_driver, struct module *owner, const char *mod_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/driver.c (0)
Location: drivers/usb/core/driver.c:1046
Inline: False
Direct callers:
  - drivers/usb/core/usb.c:usb_init
  - drivers/usb/core/hub.c:usb_hub_init
```
**Symbols:**

```
ffffffff81c1d2ea-ffffffff81c1d305: usb_register_driver.cold (STB_LOCAL)
ffffffff818cff60-ffffffff818d0083: usb_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int usb_register_driver(struct usb_driver *new_driver, struct module *owner, const char *mod_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/driver.c (0)
Location: drivers/usb/core/driver.c:1042
Inline: False
Direct callers:
  - drivers/usb/core/usb.c:usb_init
  - drivers/usb/core/hub.c:usb_hub_init
```
**Symbols:**

```
ffffffff81c0f1b0-ffffffff81c0f1cb: usb_register_driver.cold (STB_LOCAL)
ffffffff818b3590-ffffffff818b36b3: usb_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int usb_register_driver(struct usb_driver *new_driver, struct module *owner, const char *mod_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/driver.c (0)
Location: drivers/usb/core/driver.c:1042
Inline: False
Direct callers:
  - drivers/usb/core/usb.c:usb_init
  - drivers/usb/core/hub.c:usb_hub_init
```
**Symbols:**

```
ffffffff81d1634f-ffffffff81d1636a: usb_register_driver.cold (STB_LOCAL)
ffffffff81948a20-ffffffff81948b43: usb_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int usb_register_driver(struct usb_driver *new_driver, struct module *owner, const char *mod_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/driver.c (0)
Location: drivers/usb/core/driver.c:1043
Inline: False
Direct callers:
  - drivers/usb/core/usb.c:usb_init
  - drivers/usb/core/hub.c:usb_hub_init
```
**Symbols:**

```
ffffffff81ee0f38-ffffffff81ee0f53: usb_register_driver.cold (STB_LOCAL)
ffffffff81aa1550-ffffffff81aa1683: usb_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int usb_register_driver(struct usb_driver *new_driver, struct module *owner, const char *mod_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/driver.c (ffffffff81c26ca0)
Location: drivers/usb/core/driver.c:1043
Inline: False
Direct callers:
  - drivers/usb/core/usb.c:usb_init
  - drivers/usb/core/hub.c:usb_hub_init
```
**Symbols:**

```
ffffffff81c26ca0-ffffffff81c26e11: usb_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int usb_register_driver(struct usb_driver *new_driver, struct module *owner, const char *mod_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/driver.c (ffffffff81c8dc60)
Location: drivers/usb/core/driver.c:1043
Inline: False
Direct callers:
  - drivers/usb/core/usb.c:usb_init
  - drivers/usb/core/hub.c:usb_hub_init
```
**Symbols:**

```
ffffffff81c8dc60-ffffffff81c8ddd1: usb_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int usb_register_driver(struct usb_driver *new_driver, struct module *owner, const char *mod_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/driver.c (ffffffff81d42790)
Location: drivers/usb/core/driver.c:1050
Inline: False
Direct callers:
  - drivers/usb/core/usb.c:usb_init
  - drivers/usb/core/hub.c:usb_hub_init
```
**Symbols:**

```
ffffffff81d42790-ffffffff81d428f7: usb_register_driver (STB_GLOBAL)
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
int usb_register_driver(struct usb_driver *new_driver, struct module *owner, const char *mod_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/driver.c (ffff800010a25000)
Location: drivers/usb/core/driver.c:943
Inline: False
Direct callers:
  - drivers/usb/core/usb.c:usb_init
  - drivers/usb/core/hub.c:usb_hub_init
```
**Symbols:**

```
ffff800010a25000-ffff800010a25144: usb_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int usb_register_driver(struct usb_driver *new_driver, struct module *owner, const char *mod_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/driver.c (c0afb648)
Location: drivers/usb/core/driver.c:943
Inline: False
Direct callers:
  - drivers/usb/core/usb.c:usb_init
  - drivers/usb/core/hub.c:usb_hub_init
```
**Symbols:**

```
c0afb648-c0afb788: usb_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int usb_register_driver(struct usb_driver *new_driver, struct module *owner, const char *mod_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/driver.c (c000000000adff70)
Location: drivers/usb/core/driver.c:943
Inline: False
Direct callers:
  - drivers/usb/core/usb.c:usb_init
  - drivers/usb/core/hub.c:usb_hub_init
```
**Symbols:**

```
c000000000adff70-c000000000ae0130: usb_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int usb_register_driver(struct usb_driver *new_driver, struct module *owner, const char *mod_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/driver.c (ffffffe0006472c2)
Location: drivers/usb/core/driver.c:943
Inline: False
Direct callers:
  - drivers/usb/core/usb.c:usb_init
  - drivers/usb/core/hub.c:usb_hub_init
```
**Symbols:**

```
ffffffe0006472c2-ffffffe0006473e4: usb_register_driver (STB_GLOBAL)
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
int usb_register_driver(struct usb_driver *new_driver, struct module *owner, const char *mod_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/driver.c (0)
Location: drivers/usb/core/driver.c:943
Inline: False
Direct callers:
  - drivers/usb/core/usb.c:usb_init
  - drivers/usb/core/hub.c:usb_hub_init
```
**Symbols:**

```
ffffffff817ae386-ffffffff817ae3a1: usb_register_driver.cold (STB_LOCAL)
ffffffff817ac8e0-ffffffff817aca03: usb_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int usb_register_driver(struct usb_driver *new_driver, struct module *owner, const char *mod_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/driver.c (0)
Location: drivers/usb/core/driver.c:943
Inline: False
Direct callers:
  - drivers/usb/core/usb.c:usb_init
  - drivers/usb/core/hub.c:usb_hub_init
```
**Symbols:**

```
ffffffff8179fd86-ffffffff8179fda1: usb_register_driver.cold (STB_LOCAL)
ffffffff8179e2e0-ffffffff8179e403: usb_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int usb_register_driver(struct usb_driver *new_driver, struct module *owner, const char *mod_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/driver.c (0)
Location: drivers/usb/core/driver.c:943
Inline: False
Direct callers:
  - drivers/usb/core/usb.c:usb_init
  - drivers/usb/core/hub.c:usb_hub_init
```
**Symbols:**

```
ffffffff817eae26-ffffffff817eae41: usb_register_driver.cold (STB_LOCAL)
ffffffff817e9380-ffffffff817e94a3: usb_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int usb_register_driver(struct usb_driver *new_driver, struct module *owner, const char *mod_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/driver.c (0)
Location: drivers/usb/core/driver.c:943
Inline: False
Direct callers:
  - drivers/usb/core/usb.c:usb_init
  - drivers/usb/core/hub.c:usb_hub_init
```
**Symbols:**

```
ffffffff81805066-ffffffff81805081: usb_register_driver.cold (STB_LOCAL)
ffffffff818038b0-ffffffff818039d3: usb_register_driver (STB_GLOBAL)
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
