# Function: <code>usb_parse_configuration</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int usb_parse_configuration(struct usb_device *dev, int cfgidx, struct usb_host_config *config, unsigned char *buffer, int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/config.c (ffffffff816157e0)
Location: drivers/usb/core/config.c:450
Inline: False
Direct callers:
  - drivers/usb/core/config.c:usb_get_configuration
```
**Symbols:**

```
ffffffff816157e0-ffffffff81616ba3: usb_parse_configuration (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int usb_parse_configuration(struct usb_device *dev, int cfgidx, struct usb_host_config *config, unsigned char *buffer, int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/config.c (ffffffff81675770)
Location: drivers/usb/core/config.c:516
Inline: False
Direct callers:
  - drivers/usb/core/config.c:usb_get_configuration
```
**Symbols:**

```
ffffffff81675770-ffffffff81676c69: usb_parse_configuration (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int usb_parse_configuration(struct usb_device *dev, int cfgidx, struct usb_host_config *config, unsigned char *buffer, int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/config.c (ffffffff816a3400)
Location: drivers/usb/core/config.c:541
Inline: False
Direct callers:
  - drivers/usb/core/config.c:usb_get_configuration
```
**Symbols:**

```
ffffffff816a3400-ffffffff816a4943: usb_parse_configuration (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int usb_parse_configuration(struct usb_device *dev, int cfgidx, struct usb_host_config *config, unsigned char *buffer, int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/config.c (ffffffff816b8550)
Location: drivers/usb/core/config.c:541
Inline: False
Direct callers:
  - drivers/usb/core/config.c:usb_get_configuration
```
**Symbols:**

```
ffffffff816b8550-ffffffff816b9c97: usb_parse_configuration (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int usb_parse_configuration(struct usb_device *dev, int cfgidx, struct usb_host_config *config, unsigned char *buffer, int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/config.c (ffffffff81723e60)
Location: drivers/usb/core/config.c:541
Inline: False
Direct callers:
  - drivers/usb/core/config.c:usb_get_configuration
```
**Symbols:**

```
ffffffff81723e60-ffffffff817255aa: usb_parse_configuration (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int usb_parse_configuration(struct usb_device *dev, int cfgidx, struct usb_host_config *config, unsigned char *buffer, int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/config.c (ffffffff81762c20)
Location: drivers/usb/core/config.c:543
Inline: False
Direct callers:
  - drivers/usb/core/config.c:usb_get_configuration
```
**Symbols:**

```
ffffffff81762c20-ffffffff8176435b: usb_parse_configuration (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int usb_parse_configuration(struct usb_device *dev, int cfgidx, struct usb_host_config *config, unsigned char *buffer, int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/config.c (ffffffff81787260)
Location: drivers/usb/core/config.c:543
Inline: False
Direct callers:
  - drivers/usb/core/config.c:usb_get_configuration
```
**Symbols:**

```
ffffffff81787260-ffffffff817889c0: usb_parse_configuration (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int usb_parse_configuration(struct usb_device *dev, int cfgidx, struct usb_host_config *config, unsigned char *buffer, int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/config.c (0)
Location: drivers/usb/core/config.c:543
Inline: False
Direct callers:
  - drivers/usb/core/config.c:usb_get_configuration
```
**Symbols:**

```
ffffffff817c5de0-ffffffff817c65eb: usb_parse_configuration (STB_LOCAL)
ffffffff817c7043-ffffffff817c743d: usb_parse_configuration.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int usb_parse_configuration(struct usb_device *dev, int cfgidx, struct usb_host_config *config, unsigned char *buffer, int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/config.c (0)
Location: drivers/usb/core/config.c:609
Inline: False
Direct callers:
  - drivers/usb/core/config.c:usb_get_configuration
```
**Symbols:**

```
ffffffff817f68c0-ffffffff817f7053: usb_parse_configuration (STB_LOCAL)
ffffffff817f7ae6-ffffffff817f7f62: usb_parse_configuration.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int usb_parse_configuration(struct usb_device *dev, int cfgidx, struct usb_host_config *config, unsigned char *buffer, int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/config.c (0)
Location: drivers/usb/core/config.c:605
Inline: False
Direct callers:
  - drivers/usb/core/config.c:usb_get_configuration
```
**Symbols:**

```
ffffffff818c6ba0-ffffffff818c70ef: usb_parse_configuration (STB_LOCAL)
ffffffff818c7cc5-ffffffff818c8064: usb_parse_configuration.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int usb_parse_configuration(struct usb_device *dev, int cfgidx, struct usb_host_config *config, unsigned char *buffer, int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/config.c (0)
Location: drivers/usb/core/config.c:605
Inline: False
Direct callers:
  - drivers/usb/core/config.c:usb_get_configuration
```
**Symbols:**

```
ffffffff818d27e0-ffffffff818d2d2f: usb_parse_configuration (STB_LOCAL)
ffffffff81c1d9ff-ffffffff81c1dd9e: usb_parse_configuration.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int usb_parse_configuration(struct usb_device *dev, int cfgidx, struct usb_host_config *config, unsigned char *buffer, int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/config.c (0)
Location: drivers/usb/core/config.c:605
Inline: False
Direct callers:
  - drivers/usb/core/config.c:usb_get_configuration
```
**Symbols:**

```
ffffffff818b5d70-ffffffff818b62bf: usb_parse_configuration (STB_LOCAL)
ffffffff81c0f8d6-ffffffff81c0fc75: usb_parse_configuration.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int usb_parse_configuration(struct usb_device *dev, int cfgidx, struct usb_host_config *config, unsigned char *buffer, int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/config.c (0)
Location: drivers/usb/core/config.c:605
Inline: False
Direct callers:
  - drivers/usb/core/config.c:usb_get_configuration
```
**Symbols:**

```
ffffffff8194b330-ffffffff8194bb79: usb_parse_configuration (STB_LOCAL)
ffffffff81d16a1c-ffffffff81d16cc6: usb_parse_configuration.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int usb_parse_configuration(struct usb_device *dev, int cfgidx, struct usb_host_config *config, unsigned char *buffer, int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/config.c (0)
Location: drivers/usb/core/config.c:605
Inline: False
Direct callers:
  - drivers/usb/core/config.c:usb_get_configuration
```
**Symbols:**

```
ffffffff81aa4160-ffffffff81aa45f1: usb_parse_configuration (STB_LOCAL)
ffffffff81ee15f8-ffffffff81ee1bc7: usb_parse_configuration.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int usb_parse_configuration(struct usb_device *dev, int cfgidx, struct usb_host_config *config, unsigned char *buffer, int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/config.c (ffffffff81c2a220)
Location: drivers/usb/core/config.c:605
Inline: False
Direct callers:
  - drivers/usb/core/config.c:usb_get_configuration
```
**Symbols:**

```
ffffffff81c2a220-ffffffff81c2ad51: usb_parse_configuration (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int usb_parse_configuration(struct usb_device *dev, int cfgidx, struct usb_host_config *config, unsigned char *buffer, int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/config.c (ffffffff81c911d0)
Location: drivers/usb/core/config.c:605
Inline: False
Direct callers:
  - drivers/usb/core/config.c:usb_get_configuration
```
**Symbols:**

```
ffffffff81c911d0-ffffffff81c91ce7: usb_parse_configuration (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int usb_parse_configuration(struct usb_device *dev, int cfgidx, struct usb_host_config *config, unsigned char *buffer, int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/config.c (ffffffff81d45d90)
Location: drivers/usb/core/config.c:605
Inline: False
Direct callers:
  - drivers/usb/core/config.c:usb_get_configuration
```
**Symbols:**

```
ffffffff81d45d90-ffffffff81d468a7: usb_parse_configuration (STB_LOCAL)
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
int usb_parse_configuration(struct usb_device *dev, int cfgidx, struct usb_host_config *config, unsigned char *buffer, int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/config.c (ffff800010a27c00)
Location: drivers/usb/core/config.c:609
Inline: False
Direct callers:
  - drivers/usb/core/config.c:usb_get_configuration
```
**Symbols:**

```
ffff800010a27c00-ffff800010a286c0: usb_parse_configuration (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int usb_parse_configuration(struct usb_device *dev, int cfgidx, struct usb_host_config *config, unsigned char *buffer, int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/config.c (c0afdbe0)
Location: drivers/usb/core/config.c:609
Inline: False
Direct callers:
  - drivers/usb/core/config.c:usb_get_configuration
```
**Symbols:**

```
c0afdbe0-c0afe6d0: usb_parse_configuration (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int usb_parse_configuration(struct usb_device *dev, int cfgidx, struct usb_host_config *config, unsigned char *buffer, int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/config.c (c000000000ae3920)
Location: drivers/usb/core/config.c:609
Inline: False
Direct callers:
  - drivers/usb/core/config.c:usb_get_configuration
```
**Symbols:**

```
c000000000ae3920-c000000000ae45d0: usb_parse_configuration (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int usb_parse_configuration(struct usb_device *dev, int cfgidx, struct usb_host_config *config, unsigned char *buffer, int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/config.c (ffffffe0006498e4)
Location: drivers/usb/core/config.c:609
Inline: False
Direct callers:
  - drivers/usb/core/config.c:usb_get_configuration
```
**Symbols:**

```
ffffffe0006498e4-ffffffe00064a1d2: usb_parse_configuration (STB_LOCAL)
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
int usb_parse_configuration(struct usb_device *dev, int cfgidx, struct usb_host_config *config, unsigned char *buffer, int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/config.c (0)
Location: drivers/usb/core/config.c:609
Inline: False
Direct callers:
  - drivers/usb/core/config.c:usb_get_configuration
```
**Symbols:**

```
ffffffff817aeca0-ffffffff817af433: usb_parse_configuration (STB_LOCAL)
ffffffff817afec6-ffffffff817b0342: usb_parse_configuration.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int usb_parse_configuration(struct usb_device *dev, int cfgidx, struct usb_host_config *config, unsigned char *buffer, int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/config.c (0)
Location: drivers/usb/core/config.c:609
Inline: False
Direct callers:
  - drivers/usb/core/config.c:usb_get_configuration
```
**Symbols:**

```
ffffffff817a06a0-ffffffff817a0e33: usb_parse_configuration (STB_LOCAL)
ffffffff817a18c6-ffffffff817a1d42: usb_parse_configuration.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int usb_parse_configuration(struct usb_device *dev, int cfgidx, struct usb_host_config *config, unsigned char *buffer, int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/config.c (0)
Location: drivers/usb/core/config.c:609
Inline: False
Direct callers:
  - drivers/usb/core/config.c:usb_get_configuration
```
**Symbols:**

```
ffffffff817eb740-ffffffff817ebed3: usb_parse_configuration (STB_LOCAL)
ffffffff817ec966-ffffffff817ecde2: usb_parse_configuration.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int usb_parse_configuration(struct usb_device *dev, int cfgidx, struct usb_host_config *config, unsigned char *buffer, int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/config.c (0)
Location: drivers/usb/core/config.c:609
Inline: False
Direct callers:
  - drivers/usb/core/config.c:usb_get_configuration
```
**Symbols:**

```
ffffffff81805980-ffffffff81806113: usb_parse_configuration (STB_LOCAL)
ffffffff81806ba6-ffffffff81807022: usb_parse_configuration.cold (STB_LOCAL)
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
