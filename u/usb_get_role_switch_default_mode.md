# Function: <code>usb_get_role_switch_default_mode</code>

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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
enum usb_dr_mode usb_get_role_switch_default_mode(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/common/common.c (ffffffff819377a0)
Location: drivers/usb/common/common.c:210
Inline: False
```
**Symbols:**

```
ffffffff819377a0-ffffffff81937808: usb_get_role_switch_default_mode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
enum usb_dr_mode usb_get_role_switch_default_mode(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/common/common.c (ffffffff81a8ee30)
Location: drivers/usb/common/common.c:210
Inline: False
Direct callers:
  - drivers/usb/dwc2/drd.c:dwc2_drd_init
```
**Symbols:**

```
ffffffff81a8ee30-ffffffff81a8eea8: usb_get_role_switch_default_mode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
enum usb_dr_mode usb_get_role_switch_default_mode(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/common/common.c (ffffffff81c107f0)
Location: drivers/usb/common/common.c:210
Inline: False
Direct callers:
  - drivers/usb/dwc2/drd.c:dwc2_drd_init
```
**Symbols:**

```
ffffffff81c107f0-ffffffff81c10868: usb_get_role_switch_default_mode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
enum usb_dr_mode usb_get_role_switch_default_mode(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/common/common.c (ffffffff81c77480)
Location: drivers/usb/common/common.c:210
Inline: False
Direct callers:
  - drivers/usb/dwc2/drd.c:dwc2_drd_init
```
**Symbols:**

```
ffffffff81c77480-ffffffff81c774f8: usb_get_role_switch_default_mode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
enum usb_dr_mode usb_get_role_switch_default_mode(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/common/common.c (ffffffff81d2be80)
Location: drivers/usb/common/common.c:211
Inline: False
Direct callers:
  - drivers/usb/dwc2/drd.c:dwc2_drd_init
```
**Symbols:**

```
ffffffff81d2be80-ffffffff81d2bef8: usb_get_role_switch_default_mode (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
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
