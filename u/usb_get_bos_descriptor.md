# Function: <code>usb_get_bos_descriptor</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int usb_get_bos_descriptor(struct usb_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/config.c (ffffffff81617030)
Location: drivers/usb/core/config.c:810
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hcd.c:usb_add_hcd
```
**Symbols:**

```
ffffffff81617030-ffffffff8161728b: usb_get_bos_descriptor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int usb_get_bos_descriptor(struct usb_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/config.c (ffffffff81677110)
Location: drivers/usb/core/config.c:876
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hcd.c:usb_add_hcd
```
**Symbols:**

```
ffffffff81677110-ffffffff81677371: usb_get_bos_descriptor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int usb_get_bos_descriptor(struct usb_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/config.c (ffffffff816a4df0)
Location: drivers/usb/core/config.c:901
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hcd.c:usb_add_hcd
```
**Symbols:**

```
ffffffff816a4df0-ffffffff816a5051: usb_get_bos_descriptor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int usb_get_bos_descriptor(struct usb_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/config.c (ffffffff816ba1b0)
Location: drivers/usb/core/config.c:901
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hcd.c:usb_add_hcd
```
**Symbols:**

```
ffffffff816ba1b0-ffffffff816ba3f0: usb_get_bos_descriptor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int usb_get_bos_descriptor(struct usb_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/config.c (ffffffff81725ab0)
Location: drivers/usb/core/config.c:920
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hcd.c:usb_add_hcd
```
**Symbols:**

```
ffffffff81725ab0-ffffffff81725d75: usb_get_bos_descriptor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int usb_get_bos_descriptor(struct usb_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/config.c (ffffffff81764860)
Location: drivers/usb/core/config.c:922
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hcd.c:usb_add_hcd
```
**Symbols:**

```
ffffffff81764860-ffffffff81764b3d: usb_get_bos_descriptor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int usb_get_bos_descriptor(struct usb_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/config.c (ffffffff81788ec0)
Location: drivers/usb/core/config.c:922
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hcd.c:usb_add_hcd
```
**Symbols:**

```
ffffffff81788ec0-ffffffff817891b7: usb_get_bos_descriptor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int usb_get_bos_descriptor(struct usb_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/config.c (0)
Location: drivers/usb/core/config.c:918
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hcd.c:usb_add_hcd
```
**Symbols:**

```
ffffffff817c75a8-ffffffff817c7639: usb_get_bos_descriptor.cold (STB_LOCAL)
ffffffff817c69d0-ffffffff817c6c25: usb_get_bos_descriptor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int usb_get_bos_descriptor(struct usb_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/config.c (0)
Location: drivers/usb/core/config.c:984
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hcd.c:usb_add_hcd
```
**Symbols:**

```
ffffffff817f80cd-ffffffff817f815e: usb_get_bos_descriptor.cold (STB_LOCAL)
ffffffff817f7440-ffffffff817f7695: usb_get_bos_descriptor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int usb_get_bos_descriptor(struct usb_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/config.c (0)
Location: drivers/usb/core/config.c:978
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hcd.c:register_root_hub
```
**Symbols:**

```
ffffffff818c8183-ffffffff818c8214: usb_get_bos_descriptor.cold (STB_LOCAL)
ffffffff818c7520-ffffffff818c778e: usb_get_bos_descriptor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int usb_get_bos_descriptor(struct usb_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/config.c (0)
Location: drivers/usb/core/config.c:978
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hcd.c:register_root_hub
```
**Symbols:**

```
ffffffff81c1deba-ffffffff81c1df48: usb_get_bos_descriptor.cold (STB_LOCAL)
ffffffff818d3160-ffffffff818d33ce: usb_get_bos_descriptor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int usb_get_bos_descriptor(struct usb_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/config.c (0)
Location: drivers/usb/core/config.c:978
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hcd.c:register_root_hub
```
**Symbols:**

```
ffffffff81c0fd8a-ffffffff81c0fe18: usb_get_bos_descriptor.cold (STB_LOCAL)
ffffffff818b66f0-ffffffff818b695e: usb_get_bos_descriptor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int usb_get_bos_descriptor(struct usb_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/config.c (0)
Location: drivers/usb/core/config.c:978
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hcd.c:register_root_hub
```
**Symbols:**

```
ffffffff81d16ddb-ffffffff81d16e69: usb_get_bos_descriptor.cold (STB_LOCAL)
ffffffff8194bff0-ffffffff8194c268: usb_get_bos_descriptor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int usb_get_bos_descriptor(struct usb_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/config.c (0)
Location: drivers/usb/core/config.c:978
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hcd.c:register_root_hub
```
**Symbols:**

```
ffffffff81ee1cf0-ffffffff81ee1d96: usb_get_bos_descriptor.cold (STB_LOCAL)
ffffffff81aa4ab0-ffffffff81aa4d30: usb_get_bos_descriptor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int usb_get_bos_descriptor(struct usb_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/config.c (ffffffff81c2b370)
Location: drivers/usb/core/config.c:978
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hcd.c:register_root_hub
```
**Symbols:**

```
ffffffff81c2b370-ffffffff81c2b69c: usb_get_bos_descriptor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int usb_get_bos_descriptor(struct usb_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/config.c (ffffffff81c92300)
Location: drivers/usb/core/config.c:978
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hcd.c:register_root_hub
```
**Symbols:**

```
ffffffff81c92300-ffffffff81c9263c: usb_get_bos_descriptor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int usb_get_bos_descriptor(struct usb_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/config.c (ffffffff81d46ef0)
Location: drivers/usb/core/config.c:978
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hcd.c:register_root_hub
```
**Symbols:**

```
ffffffff81d46ef0-ffffffff81d4729f: usb_get_bos_descriptor (STB_GLOBAL)
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
int usb_get_bos_descriptor(struct usb_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/config.c (ffff800010a28b60)
Location: drivers/usb/core/config.c:984
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hcd.c:usb_add_hcd
```
**Symbols:**

```
ffff800010a28b60-ffff800010a28e4c: usb_get_bos_descriptor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int usb_get_bos_descriptor(struct usb_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/config.c (c0afeb4c)
Location: drivers/usb/core/config.c:984
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hcd.c:usb_add_hcd
```
**Symbols:**

```
c0afeb4c-c0afee40: usb_get_bos_descriptor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int usb_get_bos_descriptor(struct usb_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/config.c (c000000000ae4c80)
Location: drivers/usb/core/config.c:984
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hcd.c:usb_add_hcd
```
**Symbols:**

```
c000000000ae4c80-c000000000ae5068: usb_get_bos_descriptor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int usb_get_bos_descriptor(struct usb_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/config.c (ffffffe00064a648)
Location: drivers/usb/core/config.c:984
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hcd.c:usb_add_hcd
```
**Symbols:**

```
ffffffe00064a648-ffffffe00064a89e: usb_get_bos_descriptor (STB_GLOBAL)
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
int usb_get_bos_descriptor(struct usb_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/config.c (0)
Location: drivers/usb/core/config.c:984
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hcd.c:usb_add_hcd
```
**Symbols:**

```
ffffffff817b04ad-ffffffff817b053e: usb_get_bos_descriptor.cold (STB_LOCAL)
ffffffff817af820-ffffffff817afa75: usb_get_bos_descriptor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int usb_get_bos_descriptor(struct usb_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/config.c (0)
Location: drivers/usb/core/config.c:984
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hcd.c:usb_add_hcd
```
**Symbols:**

```
ffffffff817a1ead-ffffffff817a1f3e: usb_get_bos_descriptor.cold (STB_LOCAL)
ffffffff817a1220-ffffffff817a1475: usb_get_bos_descriptor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int usb_get_bos_descriptor(struct usb_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/config.c (0)
Location: drivers/usb/core/config.c:984
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hcd.c:usb_add_hcd
```
**Symbols:**

```
ffffffff817ecf4d-ffffffff817ecfde: usb_get_bos_descriptor.cold (STB_LOCAL)
ffffffff817ec2c0-ffffffff817ec515: usb_get_bos_descriptor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int usb_get_bos_descriptor(struct usb_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/config.c (0)
Location: drivers/usb/core/config.c:984
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hcd.c:usb_add_hcd
```
**Symbols:**

```
ffffffff8180718d-ffffffff8180721e: usb_get_bos_descriptor.cold (STB_LOCAL)
ffffffff81806500-ffffffff81806755: usb_get_bos_descriptor (STB_GLOBAL)
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
