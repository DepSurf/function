# Function: <code>__devm_rtc_register_device</code>

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
int __devm_rtc_register_device(struct module *owner, struct rtc_device *rtc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/rtc/class.c (ffffffff8193f3fb)
Location: drivers/rtc/class.c:379
Inline: True
Inline callers:
  - drivers/rtc/class.c:devm_rtc_device_register
Direct callers:
  - drivers/rtc/class.c:devm_rtc_device_register
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
```
**Symbols:**

```
ffffffff8193ed30-ffffffff8193edfe: __devm_rtc_register_device.part.0 (STB_LOCAL)
ffffffff81c244c6-ffffffff81c245e0: __devm_rtc_register_device.part.0.cold (STB_LOCAL)
ffffffff8193ee00-ffffffff8193ee40: __devm_rtc_register_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int __devm_rtc_register_device(struct module *owner, struct rtc_device *rtc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/rtc/class.c (0)
Location: drivers/rtc/class.c:376
Inline: False
Direct callers:
  - drivers/rtc/class.c:devm_rtc_device_register
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
```
**Symbols:**

```
ffffffff81c1659a-ffffffff81c1669d: __devm_rtc_register_device.cold (STB_LOCAL)
ffffffff81922430-ffffffff81922637: __devm_rtc_register_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int __devm_rtc_register_device(struct module *owner, struct rtc_device *rtc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/rtc/class.c (0)
Location: drivers/rtc/class.c:376
Inline: False
Direct callers:
  - drivers/rtc/class.c:devm_rtc_device_register
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
```
**Symbols:**

```
ffffffff81d24fdc-ffffffff81d25100: __devm_rtc_register_device.cold (STB_LOCAL)
ffffffff819c53e0-ffffffff819c55f3: __devm_rtc_register_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int __devm_rtc_register_device(struct module *owner, struct rtc_device *rtc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/rtc/class.c (0)
Location: drivers/rtc/class.c:389
Inline: False
Direct callers:
  - drivers/rtc/class.c:devm_rtc_device_register
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
```
**Symbols:**

```
ffffffff81ef0dbd-ffffffff81ef0eb4: __devm_rtc_register_device.cold (STB_LOCAL)
ffffffff81b25eb0-ffffffff81b26122: __devm_rtc_register_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int __devm_rtc_register_device(struct module *owner, struct rtc_device *rtc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/rtc/class.c (0)
Location: drivers/rtc/class.c:389
Inline: False
Direct callers:
  - drivers/rtc/class.c:devm_rtc_device_register
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
```
**Symbols:**

```
ffffffff820a7356-ffffffff820a736a: __devm_rtc_register_device.cold (STB_LOCAL)
ffffffff81cb94d0-ffffffff81cb9862: __devm_rtc_register_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int __devm_rtc_register_device(struct module *owner, struct rtc_device *rtc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/rtc/class.c (0)
Location: drivers/rtc/class.c:389
Inline: False
Direct callers:
  - drivers/rtc/class.c:devm_rtc_device_register
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
```
**Symbols:**

```
ffffffff82128759-ffffffff8212876d: __devm_rtc_register_device.cold (STB_LOCAL)
ffffffff81d20c00-ffffffff81d20f99: __devm_rtc_register_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int __devm_rtc_register_device(struct module *owner, struct rtc_device *rtc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/rtc/class.c (0)
Location: drivers/rtc/class.c:389
Inline: False
Direct callers:
  - drivers/rtc/class.c:devm_rtc_device_register
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
```
**Symbols:**

```
ffffffff8220a0eb-ffffffff8220a0ff: __devm_rtc_register_device.cold (STB_LOCAL)
ffffffff81dd6930-ffffffff81dd6cc9: __devm_rtc_register_device (STB_GLOBAL)
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
