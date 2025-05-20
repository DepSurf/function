# Function: <code>rtc_device_register</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct rtc_device *rtc_device_register(const char *name, struct device *dev, const struct rtc_class_ops *ops, struct module *owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/class.c (ffffffff816738e0)
Location: drivers/rtc/class.c:163
Inline: False
Direct callers:
  - drivers/rtc/class.c:devm_rtc_device_register
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
```
**Symbols:**

```
ffffffff816738e0-ffffffff81673bad: rtc_device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct rtc_device *rtc_device_register(const char *name, struct device *dev, const struct rtc_class_ops *ops, struct module *owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/class.c (ffffffff816d40c0)
Location: drivers/rtc/class.c:163
Inline: False
Direct callers:
  - drivers/rtc/class.c:devm_rtc_device_register
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
```
**Symbols:**

```
ffffffff816d40c0-ffffffff816d438d: rtc_device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct rtc_device *rtc_device_register(const char *name, struct device *dev, const struct rtc_class_ops *ops, struct module *owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/class.c (ffffffff81703da0)
Location: drivers/rtc/class.c:163
Inline: False
Direct callers:
  - drivers/rtc/class.c:devm_rtc_device_register
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
```
**Symbols:**

```
ffffffff81703da0-ffffffff8170406d: rtc_device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct rtc_device *rtc_device_register(const char *name, struct device *dev, const struct rtc_class_ops *ops, struct module *owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/class.c (ffffffff81719850)
Location: drivers/rtc/class.c:220
Inline: False
Direct callers:
  - drivers/rtc/class.c:devm_rtc_device_register
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
```
**Symbols:**

```
ffffffff81719850-ffffffff81719a33: rtc_device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct rtc_device *rtc_device_register(const char *name, struct device *dev, const struct rtc_class_ops *ops, struct module *owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/class.c (ffffffff8178aac0)
Location: drivers/rtc/class.c:223
Inline: False
Direct callers:
  - drivers/rtc/class.c:devm_rtc_device_register
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
```
**Symbols:**

```
ffffffff8178aac0-ffffffff8178aca3: rtc_device_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct rtc_device *rtc_device_register(const char *name, struct device *dev, const struct rtc_class_ops *ops, struct module *owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/class.c (ffffffff817cbcc0)
Location: drivers/rtc/class.c:290
Inline: False
Direct callers:
  - drivers/rtc/class.c:devm_rtc_device_register
```
**Symbols:**

```
ffffffff817cbcc0-ffffffff817cbeab: rtc_device_register (STB_GLOBAL)
```
</details>
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
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
</ul>
