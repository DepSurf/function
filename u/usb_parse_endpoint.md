# Function: <code>usb_parse_endpoint</code>

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
In drivers/usb/core/config.c (ffffffff81616030)
Location: drivers/usb/core/config.c:174
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_configuration
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
In drivers/usb/core/config.c (ffffffff81675f97)
Location: drivers/usb/core/config.c:199
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_configuration
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
In drivers/usb/core/config.c (ffffffff816a3c38)
Location: drivers/usb/core/config.c:204
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_configuration
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
In drivers/usb/core/config.c (ffffffff816b8a3f)
Location: drivers/usb/core/config.c:204
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_configuration
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
In drivers/usb/core/config.c (ffffffff81724350)
Location: drivers/usb/core/config.c:204
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_configuration
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
In drivers/usb/core/config.c (ffffffff81763471)
Location: drivers/usb/core/config.c:206
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_configuration
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
In drivers/usb/core/config.c (ffffffff81787ab1)
Location: drivers/usb/core/config.c:206
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_configuration
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
In drivers/usb/core/config.c (0)
Location: drivers/usb/core/config.c:206
Inline: True
Direct callers:
  - drivers/usb/core/config.c:usb_parse_configuration
```
**Symbols:**

```
ffffffff817c57f0-ffffffff817c5dd1: usb_parse_endpoint.isra.0 (STB_LOCAL)
ffffffff817c6c25-ffffffff817c7043: usb_parse_endpoint.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int usb_parse_endpoint(struct device *ddev, int cfgno, struct usb_host_config *config, int inum, int asnum, struct usb_host_interface *ifp, int num_ep, unsigned char *buffer, int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/config.c (0)
Location: drivers/usb/core/config.c:254
Inline: False
Direct callers:
  - drivers/usb/core/config.c:usb_parse_configuration
```
**Symbols:**

```
ffffffff817f6190-ffffffff817f68b4: usb_parse_endpoint (STB_LOCAL)
ffffffff817f7695-ffffffff817f7ae6: usb_parse_endpoint.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int usb_parse_endpoint(struct device *ddev, int cfgno, struct usb_host_config *config, int inum, int asnum, struct usb_host_interface *ifp, int num_ep, unsigned char *buffer, int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/config.c (0)
Location: drivers/usb/core/config.c:254
Inline: False
Direct callers:
  - drivers/usb/core/config.c:usb_parse_interface
```
**Symbols:**

```
ffffffff818c6370-ffffffff818c68d7: usb_parse_endpoint (STB_LOCAL)
ffffffff818c7a00-ffffffff818c7c1c: usb_parse_endpoint.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int usb_parse_endpoint(struct device *ddev, int cfgno, struct usb_host_config *config, int inum, int asnum, struct usb_host_interface *ifp, int num_ep, unsigned char *buffer, int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/config.c (0)
Location: drivers/usb/core/config.c:254
Inline: False
Direct callers:
  - drivers/usb/core/config.c:usb_parse_interface
```
**Symbols:**

```
ffffffff818d1fb0-ffffffff818d2518: usb_parse_endpoint (STB_LOCAL)
ffffffff81c1d756-ffffffff81c1d956: usb_parse_endpoint.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int usb_parse_endpoint(struct device *ddev, int cfgno, struct usb_host_config *config, int inum, int asnum, struct usb_host_interface *ifp, int num_ep, unsigned char *buffer, int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/config.c (0)
Location: drivers/usb/core/config.c:254
Inline: False
Direct callers:
  - drivers/usb/core/config.c:usb_parse_interface
```
**Symbols:**

```
ffffffff818b54b0-ffffffff818b5ab4: usb_parse_endpoint (STB_LOCAL)
ffffffff81c0f618-ffffffff81c0f82d: usb_parse_endpoint.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int usb_parse_endpoint(struct device *ddev, int cfgno, struct usb_host_config *config, int inum, int asnum, struct usb_host_interface *ifp, int num_ep, unsigned char *buffer, int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/config.c (0)
Location: drivers/usb/core/config.c:254
Inline: False
Direct callers:
  - drivers/usb/core/config.c:usb_parse_interface
```
**Symbols:**

```
ffffffff8194aa30-ffffffff8194b020: usb_parse_endpoint (STB_LOCAL)
ffffffff81d167b9-ffffffff81d1696b: usb_parse_endpoint.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int usb_parse_endpoint(struct device *ddev, int cfgno, struct usb_host_config *config, int inum, int asnum, struct usb_host_interface *ifp, int num_ep, unsigned char *buffer, int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/config.c (0)
Location: drivers/usb/core/config.c:254
Inline: False
Direct callers:
  - drivers/usb/core/config.c:usb_parse_interface
```
**Symbols:**

```
ffffffff81aa3780-ffffffff81aa3de1: usb_parse_endpoint (STB_LOCAL)
ffffffff81ee13a0-ffffffff81ee1576: usb_parse_endpoint.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int usb_parse_endpoint(struct device *ddev, int cfgno, struct usb_host_config *config, int inum, int asnum, struct usb_host_interface *ifp, int num_ep, unsigned char *buffer, int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/config.c (ffffffff81c295b0)
Location: drivers/usb/core/config.c:254
Inline: False
Direct callers:
  - drivers/usb/core/config.c:usb_parse_interface
```
**Symbols:**

```
ffffffff81c295b0-ffffffff81c29e18: usb_parse_endpoint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int usb_parse_endpoint(struct device *ddev, int cfgno, struct usb_host_config *config, int inum, int asnum, struct usb_host_interface *ifp, int num_ep, unsigned char *buffer, int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/config.c (ffffffff81c90580)
Location: drivers/usb/core/config.c:254
Inline: False
Direct callers:
  - drivers/usb/core/config.c:usb_parse_interface
```
**Symbols:**

```
ffffffff81c90580-ffffffff81c90ddb: usb_parse_endpoint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int usb_parse_endpoint(struct device *ddev, int cfgno, struct usb_host_config *config, int inum, int asnum, struct usb_host_interface *ifp, int num_ep, unsigned char *buffer, int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/config.c (ffffffff81d45130)
Location: drivers/usb/core/config.c:254
Inline: False
Direct callers:
  - drivers/usb/core/config.c:usb_parse_interface
```
**Symbols:**

```
ffffffff81d45130-ffffffff81d4598b: usb_parse_endpoint (STB_LOCAL)
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
int usb_parse_endpoint(struct device *ddev, int cfgno, struct usb_host_config *config, int inum, int asnum, struct usb_host_interface *ifp, int num_ep, unsigned char *buffer, int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/config.c (ffff800010a271d0)
Location: drivers/usb/core/config.c:254
Inline: False
Direct callers:
  - drivers/usb/core/config.c:usb_parse_configuration
```
**Symbols:**

```
ffff800010a271d0-ffff800010a27be0: usb_parse_endpoint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int usb_parse_endpoint(struct device *ddev, int cfgno, struct usb_host_config *config, int inum, int asnum, struct usb_host_interface *ifp, int num_ep, unsigned char *buffer, int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/config.c (c0afd13c)
Location: drivers/usb/core/config.c:254
Inline: False
Direct callers:
  - drivers/usb/core/config.c:usb_parse_configuration
```
**Symbols:**

```
c0afd13c-c0afdbe0: usb_parse_endpoint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int usb_parse_endpoint(struct device *ddev, int cfgno, struct usb_host_config *config, int inum, int asnum, struct usb_host_interface *ifp, int num_ep, unsigned char *buffer, int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/config.c (c000000000ae2cd0)
Location: drivers/usb/core/config.c:254
Inline: False
Direct callers:
  - drivers/usb/core/config.c:usb_parse_configuration
```
**Symbols:**

```
c000000000ae2cd0-c000000000ae38f0: usb_parse_endpoint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int usb_parse_endpoint(struct device *ddev, int cfgno, struct usb_host_config *config, int inum, int asnum, struct usb_host_interface *ifp, int num_ep, unsigned char *buffer, int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/config.c (ffffffe000648ef8)
Location: drivers/usb/core/config.c:254
Inline: False
Direct callers:
  - drivers/usb/core/config.c:usb_parse_configuration
```
**Symbols:**

```
ffffffe000648ef8-ffffffe00064987e: usb_parse_endpoint (STB_LOCAL)
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
int usb_parse_endpoint(struct device *ddev, int cfgno, struct usb_host_config *config, int inum, int asnum, struct usb_host_interface *ifp, int num_ep, unsigned char *buffer, int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/config.c (0)
Location: drivers/usb/core/config.c:254
Inline: False
Direct callers:
  - drivers/usb/core/config.c:usb_parse_configuration
```
**Symbols:**

```
ffffffff817ae570-ffffffff817aec94: usb_parse_endpoint (STB_LOCAL)
ffffffff817afa75-ffffffff817afec6: usb_parse_endpoint.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int usb_parse_endpoint(struct device *ddev, int cfgno, struct usb_host_config *config, int inum, int asnum, struct usb_host_interface *ifp, int num_ep, unsigned char *buffer, int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/config.c (0)
Location: drivers/usb/core/config.c:254
Inline: False
Direct callers:
  - drivers/usb/core/config.c:usb_parse_configuration
```
**Symbols:**

```
ffffffff8179ff70-ffffffff817a0694: usb_parse_endpoint (STB_LOCAL)
ffffffff817a1475-ffffffff817a18c6: usb_parse_endpoint.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int usb_parse_endpoint(struct device *ddev, int cfgno, struct usb_host_config *config, int inum, int asnum, struct usb_host_interface *ifp, int num_ep, unsigned char *buffer, int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/config.c (0)
Location: drivers/usb/core/config.c:254
Inline: False
Direct callers:
  - drivers/usb/core/config.c:usb_parse_configuration
```
**Symbols:**

```
ffffffff817eb010-ffffffff817eb734: usb_parse_endpoint (STB_LOCAL)
ffffffff817ec515-ffffffff817ec966: usb_parse_endpoint.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int usb_parse_endpoint(struct device *ddev, int cfgno, struct usb_host_config *config, int inum, int asnum, struct usb_host_interface *ifp, int num_ep, unsigned char *buffer, int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/config.c (0)
Location: drivers/usb/core/config.c:254
Inline: False
Direct callers:
  - drivers/usb/core/config.c:usb_parse_configuration
```
**Symbols:**

```
ffffffff81805250-ffffffff81805974: usb_parse_endpoint (STB_LOCAL)
ffffffff81806755-ffffffff81806ba6: usb_parse_endpoint.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
