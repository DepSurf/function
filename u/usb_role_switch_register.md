# Function: <code>usb_role_switch_register</code>

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
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct usb_role_switch *usb_role_switch_register(struct device *parent, const struct usb_role_switch_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/roles/class.c (ffffffff8192b970)
Location: drivers/usb/roles/class.c:304
Inline: True
Direct callers:
  - drivers/usb/dwc2/drd.c:dwc2_drd_init
```
**Symbols:**

```
ffffffff8192b970-ffffffff8192ba94: usb_role_switch_register.part.0 (STB_LOCAL)
ffffffff8192baa0-ffffffff8192bac5: usb_role_switch_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct usb_role_switch *usb_role_switch_register(struct device *parent, const struct usb_role_switch_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/roles/class.c (ffffffff8190eee0)
Location: drivers/usb/roles/class.c:306
Inline: True
Direct callers:
  - drivers/usb/dwc2/drd.c:dwc2_drd_init
```
**Symbols:**

```
ffffffff8190eee0-ffffffff8190f032: usb_role_switch_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct usb_role_switch *usb_role_switch_register(struct device *parent, const struct usb_role_switch_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/roles/class.c (ffffffff819afd71)
Location: drivers/usb/roles/class.c:315
Inline: True
Direct callers:
  - drivers/usb/dwc2/drd.c:dwc2_drd_init
```
**Symbols:**

```
ffffffff81d2214f-ffffffff81d22164: usb_role_switch_register.cold (STB_LOCAL)
ffffffff819afd40-ffffffff819afea9: usb_role_switch_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct usb_role_switch *usb_role_switch_register(struct device *parent, const struct usb_role_switch_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/roles/class.c (ffffffff81b0e5d1)
Location: drivers/usb/roles/class.c:315
Inline: True
Direct callers:
  - drivers/usb/dwc2/drd.c:dwc2_drd_init
```
**Symbols:**

```
ffffffff81eedd1f-ffffffff81eedd34: usb_role_switch_register.cold (STB_LOCAL)
ffffffff81b0e5a0-ffffffff81b0e72c: usb_role_switch_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct usb_role_switch *usb_role_switch_register(struct device *parent, const struct usb_role_switch_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/roles/class.c (ffffffff81c9e801)
Location: drivers/usb/roles/class.c:318
Inline: True
Direct callers:
  - drivers/usb/dwc2/drd.c:dwc2_drd_init
```
**Symbols:**

```
ffffffff820a5ebb-ffffffff820a5ed0: usb_role_switch_register.cold (STB_LOCAL)
ffffffff81c9e7d0-ffffffff81c9e95c: usb_role_switch_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct usb_role_switch *usb_role_switch_register(struct device *parent, const struct usb_role_switch_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/roles/class.c (ffffffff81d05b41)
Location: drivers/usb/roles/class.c:319
Inline: True
Direct callers:
  - drivers/usb/dwc2/drd.c:dwc2_drd_init
```
**Symbols:**

```
ffffffff821272c5-ffffffff821272da: usb_role_switch_register.cold (STB_LOCAL)
ffffffff81d05b10-ffffffff81d05c99: usb_role_switch_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct usb_role_switch *usb_role_switch_register(struct device *parent, const struct usb_role_switch_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/roles/class.c (ffffffff81dbb85c)
Location: drivers/usb/roles/class.c:327
Inline: True
Direct callers:
  - drivers/usb/dwc2/drd.c:dwc2_drd_init
```
**Symbols:**

```
ffffffff82208c46-ffffffff82208c5b: usb_role_switch_register.cold (STB_LOCAL)
ffffffff81dbb820-ffffffff81dbb9ee: usb_role_switch_register (STB_GLOBAL)
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
struct usb_role_switch *usb_role_switch_register(struct device *parent, const struct usb_role_switch_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/roles/class.c (ffff800010a91a68)
Location: drivers/usb/roles/class.c:285
Inline: True
```
**Symbols:**

```
ffff800010a91a68-ffff800010a91bb4: usb_role_switch_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct usb_role_switch *usb_role_switch_register(struct device *parent, const struct usb_role_switch_desc *desc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/roles/class.c (c0b751f0)
Location: drivers/usb/roles/class.c:285
Inline: True
```
**Symbols:**

```
c0b751f0-c0b752fc: usb_role_switch_register (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
