# Function: <code>usb_role_switch_get_role</code>

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
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
enum usb_role usb_role_switch_get_role(struct usb_role_switch *sw);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/roles/class.c (ffffffff8192b880)
Location: drivers/usb/roles/class.c:70
Inline: True
Direct callers:
  - drivers/usb/roles/class.c:role_show
```
**Symbols:**

```
ffffffff8192b880-ffffffff8192b8ec: usb_role_switch_get_role (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
enum usb_role usb_role_switch_get_role(struct usb_role_switch *sw);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/roles/class.c (ffffffff8190edf0)
Location: drivers/usb/roles/class.c:70
Inline: True
Direct callers:
  - drivers/usb/roles/class.c:role_show
```
**Symbols:**

```
ffffffff8190edf0-ffffffff8190ee5c: usb_role_switch_get_role (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
enum usb_role usb_role_switch_get_role(struct usb_role_switch *sw);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/roles/class.c (ffffffff819afc40)
Location: drivers/usb/roles/class.c:70
Inline: True
Direct callers:
  - drivers/usb/roles/class.c:role_show
```
**Symbols:**

```
ffffffff819afc40-ffffffff819afcac: usb_role_switch_get_role (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
enum usb_role usb_role_switch_get_role(struct usb_role_switch *sw);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/roles/class.c (ffffffff81b0e7c5)
Location: drivers/usb/roles/class.c:70
Inline: True
Inline callers:
  - drivers/usb/roles/class.c:role_show
Direct callers:
  - drivers/usb/dwc2/drd.c:dwc2_drd_resume
```
**Symbols:**

```
ffffffff81b0e150-ffffffff81b0e1be: usb_role_switch_get_role (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
enum usb_role usb_role_switch_get_role(struct usb_role_switch *sw);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/roles/class.c (ffffffff81c9ea15)
Location: drivers/usb/roles/class.c:70
Inline: True
Inline callers:
  - drivers/usb/roles/class.c:role_show
Direct callers:
  - drivers/usb/dwc2/drd.c:dwc2_drd_resume
```
**Symbols:**

```
ffffffff81c9e2a0-ffffffff81c9e30e: usb_role_switch_get_role (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
enum usb_role usb_role_switch_get_role(struct usb_role_switch *sw);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/roles/class.c (ffffffff81d05d55)
Location: drivers/usb/roles/class.c:72
Inline: True
Inline callers:
  - drivers/usb/roles/class.c:role_show
Direct callers:
  - drivers/usb/dwc2/drd.c:dwc2_drd_resume
```
**Symbols:**

```
ffffffff81d05600-ffffffff81d0566e: usb_role_switch_get_role (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
enum usb_role usb_role_switch_get_role(struct usb_role_switch *sw);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/roles/class.c (ffffffff81dbb6c6)
Location: drivers/usb/roles/class.c:77
Inline: True
Direct callers:
  - drivers/usb/dwc2/drd.c:dwc2_drd_resume
  - drivers/usb/roles/class.c:role_show
```
**Symbols:**

```
ffffffff82208c31-ffffffff82208c46: usb_role_switch_get_role.cold (STB_LOCAL)
ffffffff81dbb680-ffffffff81dbb70a: usb_role_switch_get_role (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
enum usb_role usb_role_switch_get_role(struct usb_role_switch *sw);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/roles/class.c (ffff800010a91884)
Location: drivers/usb/roles/class.c:68
Inline: True
Inline callers:
  - drivers/usb/roles/class.c:role_show
Direct callers:
  - drivers/usb/roles/class.c:role_show
```
**Symbols:**

```
ffff800010a917b0-ffff800010a9181c: usb_role_switch_get_role.part.0 (STB_LOCAL)
ffff800010a91820-ffff800010a91868: usb_role_switch_get_role (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
enum usb_role usb_role_switch_get_role(struct usb_role_switch *sw);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/roles/class.c (c0b75048)
Location: drivers/usb/roles/class.c:68
Inline: True
Inline callers:
  - drivers/usb/roles/class.c:role_show
Direct callers:
  - drivers/usb/roles/class.c:role_show
```
**Symbols:**

```
c0b74fac-c0b75000: usb_role_switch_get_role.part.0 (STB_LOCAL)
c0b75000-c0b75034: usb_role_switch_get_role (STB_GLOBAL)
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
