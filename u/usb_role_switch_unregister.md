# Function: <code>usb_role_switch_unregister</code>

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
<summary>In <code>5.11</code>: ✅</summary>

```c
void usb_role_switch_unregister(struct usb_role_switch *sw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/roles/class.c (ffffffff8192b730)
Location: drivers/usb/roles/class.c:352
Inline: False
Direct callers:
  - drivers/usb/dwc2/drd.c:dwc2_drd_exit
```
**Symbols:**

```
ffffffff8192b730-ffffffff8192b74f: usb_role_switch_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void usb_role_switch_unregister(struct usb_role_switch *sw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/roles/class.c (ffffffff8190eca0)
Location: drivers/usb/roles/class.c:354
Inline: False
Direct callers:
  - drivers/usb/dwc2/drd.c:dwc2_drd_exit
```
**Symbols:**

```
ffffffff8190eca0-ffffffff8190ecbf: usb_role_switch_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void usb_role_switch_unregister(struct usb_role_switch *sw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/roles/class.c (ffffffff819afaa0)
Location: drivers/usb/roles/class.c:363
Inline: False
Direct callers:
  - drivers/usb/dwc2/drd.c:dwc2_drd_exit
```
**Symbols:**

```
ffffffff819afaa0-ffffffff819afabf: usb_role_switch_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void usb_role_switch_unregister(struct usb_role_switch *sw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/roles/class.c (ffffffff81b0e420)
Location: drivers/usb/roles/class.c:363
Inline: False
Direct callers:
  - drivers/usb/dwc2/drd.c:dwc2_drd_exit
```
**Symbols:**

```
ffffffff81b0e420-ffffffff81b0e44b: usb_role_switch_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void usb_role_switch_unregister(struct usb_role_switch *sw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/roles/class.c (ffffffff81c9e610)
Location: drivers/usb/roles/class.c:366
Inline: False
Direct callers:
  - drivers/usb/dwc2/drd.c:dwc2_drd_exit
```
**Symbols:**

```
ffffffff81c9e610-ffffffff81c9e63b: usb_role_switch_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void usb_role_switch_unregister(struct usb_role_switch *sw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/roles/class.c (ffffffff81d05950)
Location: drivers/usb/roles/class.c:367
Inline: False
Direct callers:
  - drivers/usb/dwc2/drd.c:dwc2_drd_exit
```
**Symbols:**

```
ffffffff81d05950-ffffffff81d0597b: usb_role_switch_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void usb_role_switch_unregister(struct usb_role_switch *sw);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/roles/class.c (ffffffff81dbb630)
Location: drivers/usb/roles/class.c:378
Inline: True
Direct callers:
  - drivers/usb/dwc2/drd.c:dwc2_drd_exit
```
**Symbols:**

```
ffffffff81dbb630-ffffffff81dbb662: usb_role_switch_unregister (STB_GLOBAL)
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
void usb_role_switch_unregister(struct usb_role_switch *sw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/roles/class.c (ffff800010a91600)
Location: drivers/usb/roles/class.c:331
Inline: False
```
**Symbols:**

```
ffff800010a91600-ffff800010a91638: usb_role_switch_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void usb_role_switch_unregister(struct usb_role_switch *sw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/roles/class.c (c0b74e3c)
Location: drivers/usb/roles/class.c:331
Inline: False
```
**Symbols:**

```
c0b74e3c-c0b74e68: usb_role_switch_unregister (STB_GLOBAL)
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
