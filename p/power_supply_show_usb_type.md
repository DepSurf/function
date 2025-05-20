# Function: <code>power_supply_show_usb_type</code>

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
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/power/supply/power_supply_sysfs.c (ffffffff817e1d35)
Location: drivers/power/supply/power_supply_sysfs.c:81
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_sysfs.c:power_supply_show_property
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
In drivers/power/supply/power_supply_sysfs.c (ffffffff8180d562)
Location: drivers/power/supply/power_supply_sysfs.c:81
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_sysfs.c:power_supply_show_property
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
In drivers/power/supply/power_supply_sysfs.c (ffffffff8184f275)
Location: drivers/power/supply/power_supply_sysfs.c:80
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_sysfs.c:power_supply_show_property
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
In drivers/power/supply/power_supply_sysfs.c (ffffffff81880c85)
Location: drivers/power/supply/power_supply_sysfs.c:80
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_sysfs.c:power_supply_show_property
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
ssize_t power_supply_show_usb_type(struct device *dev, const struct power_supply_desc *desc, union power_supply_propval *value, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/power/supply/power_supply_sysfs.c (0)
Location: drivers/power/supply/power_supply_sysfs.c:224
Inline: False
Direct callers:
  - drivers/power/supply/power_supply_sysfs.c:power_supply_show_property
```
**Symbols:**

```
ffffffff8194f220-ffffffff8194f2df: power_supply_show_usb_type (STB_LOCAL)
ffffffff8194f6c2-ffffffff8194f6de: power_supply_show_usb_type.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
ssize_t power_supply_show_usb_type(struct device *dev, const struct power_supply_desc *desc, union power_supply_propval *value, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/power/supply/power_supply_sysfs.c (0)
Location: drivers/power/supply/power_supply_sysfs.c:229
Inline: False
Direct callers:
  - drivers/power/supply/power_supply_sysfs.c:power_supply_show_property
```
**Symbols:**

```
ffffffff81954c40-ffffffff81954cff: power_supply_show_usb_type (STB_LOCAL)
ffffffff81c25370-ffffffff81c2538c: power_supply_show_usb_type.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/power/supply/power_supply_sysfs.c (ffffffff81938bb0)
Location: drivers/power/supply/power_supply_sysfs.c:229
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_sysfs.c:power_supply_show_property
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/power/supply/power_supply_sysfs.c (ffffffff819dd160)
Location: drivers/power/supply/power_supply_sysfs.c:229
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_sysfs.c:power_supply_show_property
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/power/supply/power_supply_sysfs.c (ffffffff81b415af)
Location: drivers/power/supply/power_supply_sysfs.c:238
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_sysfs.c:power_supply_show_property
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/power/supply/power_supply_sysfs.c (ffffffff81cd7b4f)
Location: drivers/power/supply/power_supply_sysfs.c:238
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_sysfs.c:power_supply_show_property
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/power/supply/power_supply_sysfs.c (ffffffff81d3fba4)
Location: drivers/power/supply/power_supply_sysfs.c:239
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_sysfs.c:power_supply_show_property
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/power/supply/power_supply_sysfs.c (ffffffff81df6554)
Location: drivers/power/supply/power_supply_sysfs.c:240
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_sysfs.c:power_supply_show_property
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
In drivers/power/supply/power_supply_sysfs.c (ffff800010acd064)
Location: drivers/power/supply/power_supply_sysfs.c:80
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_sysfs.c:power_supply_show_property
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
In drivers/power/supply/power_supply_sysfs.c (c0bad960)
Location: drivers/power/supply/power_supply_sysfs.c:80
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_sysfs.c:power_supply_show_property
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
In drivers/power/supply/power_supply_sysfs.c (c000000000baf7d0)
Location: drivers/power/supply/power_supply_sysfs.c:80
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_sysfs.c:power_supply_show_property
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
In drivers/power/supply/power_supply_sysfs.c (ffffffe0006ca096)
Location: drivers/power/supply/power_supply_sysfs.c:80
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_sysfs.c:power_supply_show_property
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
In drivers/power/supply/power_supply_sysfs.c (ffffffff818291f5)
Location: drivers/power/supply/power_supply_sysfs.c:80
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_sysfs.c:power_supply_show_property
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
In drivers/power/supply/power_supply_sysfs.c (ffffffff817f0885)
Location: drivers/power/supply/power_supply_sysfs.c:80
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_sysfs.c:power_supply_show_property
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
In drivers/power/supply/power_supply_sysfs.c (ffffffff81876135)
Location: drivers/power/supply/power_supply_sysfs.c:80
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_sysfs.c:power_supply_show_property
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
In drivers/power/supply/power_supply_sysfs.c (ffffffff81891ad5)
Location: drivers/power/supply/power_supply_sysfs.c:80
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_sysfs.c:power_supply_show_property
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
</ul>
