# Function: <code>usb_parse_interface</code>

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
In drivers/usb/core/config.c (ffffffff81615c6b)
Location: drivers/usb/core/config.c:343
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
In drivers/usb/core/config.c (ffffffff81675be3)
Location: drivers/usb/core/config.c:409
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
In drivers/usb/core/config.c (ffffffff816a3877)
Location: drivers/usb/core/config.c:434
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
Location: drivers/usb/core/config.c:434
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
Location: drivers/usb/core/config.c:434
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
In drivers/usb/core/config.c (ffffffff817631a7)
Location: drivers/usb/core/config.c:436
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
In drivers/usb/core/config.c (ffffffff817877e7)
Location: drivers/usb/core/config.c:436
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_configuration
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/config.c (ffffffff817c6192)
Location: drivers/usb/core/config.c:436
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_configuration
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/config.c (ffffffff817f6c3d)
Location: drivers/usb/core/config.c:502
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_configuration
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int usb_parse_interface(struct device *ddev, int cfgno, struct usb_host_config *config, unsigned char *buffer, int size, u8 *inums, u8 *nalts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/config.c (0)
Location: drivers/usb/core/config.c:498
Inline: False
Direct callers:
  - drivers/usb/core/config.c:usb_parse_configuration
```
**Symbols:**

```
ffffffff818c68e0-ffffffff818c6b93: usb_parse_interface (STB_LOCAL)
ffffffff818c7c1c-ffffffff818c7cc5: usb_parse_interface.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int usb_parse_interface(struct device *ddev, int cfgno, struct usb_host_config *config, unsigned char *buffer, int size, u8 *inums, u8 *nalts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/config.c (0)
Location: drivers/usb/core/config.c:498
Inline: False
Direct callers:
  - drivers/usb/core/config.c:usb_parse_configuration
```
**Symbols:**

```
ffffffff818d2520-ffffffff818d27d3: usb_parse_interface (STB_LOCAL)
ffffffff81c1d956-ffffffff81c1d9ff: usb_parse_interface.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int usb_parse_interface(struct device *ddev, int cfgno, struct usb_host_config *config, unsigned char *buffer, int size, u8 *inums, u8 *nalts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/config.c (0)
Location: drivers/usb/core/config.c:498
Inline: False
Direct callers:
  - drivers/usb/core/config.c:usb_parse_configuration
```
**Symbols:**

```
ffffffff818b5ac0-ffffffff818b5d6f: usb_parse_interface (STB_LOCAL)
ffffffff81c0f82d-ffffffff81c0f8d6: usb_parse_interface.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int usb_parse_interface(struct device *ddev, int cfgno, struct usb_host_config *config, unsigned char *buffer, int size, u8 *inums, u8 *nalts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/config.c (0)
Location: drivers/usb/core/config.c:498
Inline: False
Direct callers:
  - drivers/usb/core/config.c:usb_parse_configuration
```
**Symbols:**

```
ffffffff8194b020-ffffffff8194b329: usb_parse_interface (STB_LOCAL)
ffffffff81d1696b-ffffffff81d16a1c: usb_parse_interface.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int usb_parse_interface(struct device *ddev, int cfgno, struct usb_host_config *config, unsigned char *buffer, int size, u8 *inums, u8 *nalts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/config.c (0)
Location: drivers/usb/core/config.c:498
Inline: False
Direct callers:
  - drivers/usb/core/config.c:usb_parse_configuration
```
**Symbols:**

```
ffffffff81aa3df0-ffffffff81aa4154: usb_parse_interface (STB_LOCAL)
ffffffff81ee1576-ffffffff81ee15f8: usb_parse_interface.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int usb_parse_interface(struct device *ddev, int cfgno, struct usb_host_config *config, unsigned char *buffer, int size, u8 *inums, u8 *nalts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/config.c (ffffffff81c29e30)
Location: drivers/usb/core/config.c:498
Inline: False
Direct callers:
  - drivers/usb/core/config.c:usb_parse_configuration
```
**Symbols:**

```
ffffffff81c29e30-ffffffff81c2a206: usb_parse_interface (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int usb_parse_interface(struct device *ddev, int cfgno, struct usb_host_config *config, unsigned char *buffer, int size, u8 *inums, u8 *nalts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/config.c (ffffffff81c90df0)
Location: drivers/usb/core/config.c:498
Inline: False
Direct callers:
  - drivers/usb/core/config.c:usb_parse_configuration
```
**Symbols:**

```
ffffffff81c90df0-ffffffff81c911bc: usb_parse_interface (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int usb_parse_interface(struct device *ddev, int cfgno, struct usb_host_config *config, unsigned char *buffer, int size, u8 *inums, u8 *nalts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/config.c (ffffffff81d459a0)
Location: drivers/usb/core/config.c:498
Inline: False
Direct callers:
  - drivers/usb/core/config.c:usb_parse_configuration
```
**Symbols:**

```
ffffffff81d459a0-ffffffff81d45d76: usb_parse_interface (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/config.c (ffff800010a27fb0)
Location: drivers/usb/core/config.c:502
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_configuration
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/config.c (c0afe04c)
Location: drivers/usb/core/config.c:502
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_configuration
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/config.c (c000000000ae3e40)
Location: drivers/usb/core/config.c:502
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_configuration
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/config.c (ffffffe000649bc4)
Location: drivers/usb/core/config.c:502
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_configuration
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/config.c (ffffffff817af01d)
Location: drivers/usb/core/config.c:502
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_configuration
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/config.c (ffffffff817a0a1d)
Location: drivers/usb/core/config.c:502
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_configuration
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/config.c (ffffffff817ebabd)
Location: drivers/usb/core/config.c:502
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_configuration
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/config.c (ffffffff81805cfd)
Location: drivers/usb/core/config.c:502
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_parse_configuration
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
