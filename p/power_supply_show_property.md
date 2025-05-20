# Function: <code>power_supply_show_property</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
ssize_t power_supply_show_property(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/power/power_supply_sysfs.c (ffffffff8167f930)
Location: drivers/power/power_supply_sysfs.c:43
Inline: False
Direct callers:
  - drivers/power/power_supply_sysfs.c:power_supply_uevent
```
**Symbols:**

```
ffffffff8167f930-ffffffff8167fb7e: power_supply_show_property (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
ssize_t power_supply_show_property(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/power/power_supply_sysfs.c (ffffffff816e07a0)
Location: drivers/power/power_supply_sysfs.c:43
Inline: False
Direct callers:
  - drivers/power/power_supply_sysfs.c:power_supply_uevent
```
**Symbols:**

```
ffffffff816e07a0-ffffffff816e09e7: power_supply_show_property (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
ssize_t power_supply_show_property(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/power/supply/power_supply_sysfs.c (ffffffff81710c10)
Location: drivers/power/supply/power_supply_sysfs.c:43
Inline: False
Direct callers:
  - drivers/power/supply/power_supply_sysfs.c:power_supply_uevent
```
**Symbols:**

```
ffffffff81710c10-ffffffff81710e57: power_supply_show_property (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
ssize_t power_supply_show_property(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/power/supply/power_supply_sysfs.c (ffffffff81729010)
Location: drivers/power/supply/power_supply_sysfs.c:76
Inline: False
Direct callers:
  - drivers/power/supply/power_supply_sysfs.c:power_supply_uevent
```
**Symbols:**

```
ffffffff81729010-ffffffff8172925d: power_supply_show_property (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
ssize_t power_supply_show_property(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/power/supply/power_supply_sysfs.c (ffffffff8179a7a0)
Location: drivers/power/supply/power_supply_sysfs.c:76
Inline: False
Direct callers:
  - drivers/power/supply/power_supply_sysfs.c:power_supply_uevent
```
**Symbols:**

```
ffffffff8179a7a0-ffffffff8179a9ed: power_supply_show_property (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
ssize_t power_supply_show_property(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/power/supply/power_supply_sysfs.c (ffffffff817e1c40)
Location: drivers/power/supply/power_supply_sysfs.c:116
Inline: False
Direct callers:
  - drivers/power/supply/power_supply_sysfs.c:power_supply_uevent
```
**Symbols:**

```
ffffffff817e1c40-ffffffff817e1f1a: power_supply_show_property (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
ssize_t power_supply_show_property(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/power/supply/power_supply_sysfs.c (ffffffff8180d440)
Location: drivers/power/supply/power_supply_sysfs.c:116
Inline: False
Direct callers:
  - drivers/power/supply/power_supply_sysfs.c:power_supply_uevent
```
**Symbols:**

```
ffffffff8180d440-ffffffff8180d770: power_supply_show_property (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
ssize_t power_supply_show_property(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/power/supply/power_supply_sysfs.c (0)
Location: drivers/power/supply/power_supply_sysfs.c:115
Inline: False
Direct callers:
  - drivers/power/supply/power_supply_sysfs.c:power_supply_uevent
```
**Symbols:**

```
ffffffff8184f110-ffffffff8184f405: power_supply_show_property (STB_LOCAL)
ffffffff8184f627-ffffffff8184f65e: power_supply_show_property.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
ssize_t power_supply_show_property(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/power/supply/power_supply_sysfs.c (0)
Location: drivers/power/supply/power_supply_sysfs.c:115
Inline: False
Direct callers:
  - drivers/power/supply/power_supply_sysfs.c:power_supply_uevent
```
**Symbols:**

```
ffffffff81880b20-ffffffff81880e15: power_supply_show_property (STB_LOCAL)
ffffffff81881037-ffffffff8188106e: power_supply_show_property.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
ssize_t power_supply_show_property(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/power/supply/power_supply_sysfs.c (0)
Location: drivers/power/supply/power_supply_sysfs.c:258
Inline: False
```
**Symbols:**

```
ffffffff8194f2e0-ffffffff8194f478: power_supply_show_property (STB_LOCAL)
ffffffff8194f6de-ffffffff8194f6f9: power_supply_show_property.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
ssize_t power_supply_show_property(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/power/supply/power_supply_sysfs.c (0)
Location: drivers/power/supply/power_supply_sysfs.c:263
Inline: False
```
**Symbols:**

```
ffffffff81954d00-ffffffff81954e98: power_supply_show_property (STB_LOCAL)
ffffffff81c2538c-ffffffff81c253a7: power_supply_show_property.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
ssize_t power_supply_show_property(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/power/supply/power_supply_sysfs.c (0)
Location: drivers/power/supply/power_supply_sysfs.c:263
Inline: False
```
**Symbols:**

```
ffffffff81938aa0-ffffffff81938cc1: power_supply_show_property (STB_LOCAL)
ffffffff81c1741c-ffffffff81c17451: power_supply_show_property.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
ssize_t power_supply_show_property(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/power/supply/power_supply_sysfs.c (0)
Location: drivers/power/supply/power_supply_sysfs.c:263
Inline: False
```
**Symbols:**

```
ffffffff819dd050-ffffffff819dd2d5: power_supply_show_property (STB_LOCAL)
ffffffff81d263cc-ffffffff81d26401: power_supply_show_property.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
ssize_t power_supply_show_property(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/power/supply/power_supply_sysfs.c (0)
Location: drivers/power/supply/power_supply_sysfs.c:272
Inline: False
```
**Symbols:**

```
ffffffff81b414b0-ffffffff81b4176a: power_supply_show_property (STB_LOCAL)
ffffffff81ef220c-ffffffff81ef2241: power_supply_show_property.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ssize_t power_supply_show_property(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/power/supply/power_supply_sysfs.c (ffffffff81cd7a50)
Location: drivers/power/supply/power_supply_sysfs.c:272
Inline: False
```
**Symbols:**

```
ffffffff81cd7a50-ffffffff81cd7d3a: power_supply_show_property (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ssize_t power_supply_show_property(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/power/supply/power_supply_sysfs.c (ffffffff81d3fa80)
Location: drivers/power/supply/power_supply_sysfs.c:273
Inline: False
```
**Symbols:**

```
ffffffff81d3fa80-ffffffff81d3fd83: power_supply_show_property (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ssize_t power_supply_show_property(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/power/supply/power_supply_sysfs.c (ffffffff81df6430)
Location: drivers/power/supply/power_supply_sysfs.c:274
Inline: False
```
**Symbols:**

```
ffffffff81df6430-ffffffff81df6733: power_supply_show_property (STB_LOCAL)
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
ssize_t power_supply_show_property(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/power/supply/power_supply_sysfs.c (ffff800010accee0)
Location: drivers/power/supply/power_supply_sysfs.c:115
Inline: False
Direct callers:
  - drivers/power/supply/power_supply_sysfs.c:power_supply_uevent
```
**Symbols:**

```
ffff800010accee0-ffff800010acd220: power_supply_show_property (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
ssize_t power_supply_show_property(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/power/supply/power_supply_sysfs.c (c0bad724)
Location: drivers/power/supply/power_supply_sysfs.c:115
Inline: False
Direct callers:
  - drivers/power/supply/power_supply_sysfs.c:power_supply_uevent
```
**Symbols:**

```
c0bad724-c0badb84: power_supply_show_property (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
ssize_t power_supply_show_property(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/power/supply/power_supply_sysfs.c (c000000000baf550)
Location: drivers/power/supply/power_supply_sysfs.c:115
Inline: False
Direct callers:
  - drivers/power/supply/power_supply_sysfs.c:power_supply_uevent
```
**Symbols:**

```
c000000000baf550-c000000000bafb28: power_supply_show_property (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
ssize_t power_supply_show_property(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/power/supply/power_supply_sysfs.c (ffffffe0006c9f9e)
Location: drivers/power/supply/power_supply_sysfs.c:115
Inline: False
Direct callers:
  - drivers/power/supply/power_supply_sysfs.c:power_supply_uevent
```
**Symbols:**

```
ffffffe0006c9f9e-ffffffe0006ca2a2: power_supply_show_property (STB_LOCAL)
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
ssize_t power_supply_show_property(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/power/supply/power_supply_sysfs.c (0)
Location: drivers/power/supply/power_supply_sysfs.c:115
Inline: False
Direct callers:
  - drivers/power/supply/power_supply_sysfs.c:power_supply_uevent
```
**Symbols:**

```
ffffffff81829090-ffffffff81829385: power_supply_show_property (STB_LOCAL)
ffffffff818295a7-ffffffff818295de: power_supply_show_property.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
ssize_t power_supply_show_property(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/power/supply/power_supply_sysfs.c (0)
Location: drivers/power/supply/power_supply_sysfs.c:115
Inline: False
Direct callers:
  - drivers/power/supply/power_supply_sysfs.c:power_supply_uevent
```
**Symbols:**

```
ffffffff817f0720-ffffffff817f0a15: power_supply_show_property (STB_LOCAL)
ffffffff817f0c37-ffffffff817f0c6e: power_supply_show_property.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
ssize_t power_supply_show_property(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/power/supply/power_supply_sysfs.c (0)
Location: drivers/power/supply/power_supply_sysfs.c:115
Inline: False
Direct callers:
  - drivers/power/supply/power_supply_sysfs.c:power_supply_uevent
```
**Symbols:**

```
ffffffff81875fd0-ffffffff818762c5: power_supply_show_property (STB_LOCAL)
ffffffff818764e7-ffffffff8187651e: power_supply_show_property.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
ssize_t power_supply_show_property(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/power/supply/power_supply_sysfs.c (0)
Location: drivers/power/supply/power_supply_sysfs.c:115
Inline: False
Direct callers:
  - drivers/power/supply/power_supply_sysfs.c:power_supply_uevent
```
**Symbols:**

```
ffffffff81891970-ffffffff81891c65: power_supply_show_property (STB_LOCAL)
ffffffff81891e87-ffffffff81891ebe: power_supply_show_property.cold (STB_LOCAL)
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
