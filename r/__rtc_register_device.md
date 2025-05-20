# Function: <code>__rtc_register_device</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __rtc_register_device(struct module *owner, struct rtc_device *rtc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/class.c (ffffffff81719230)
Location: drivers/rtc/class.c:426
Inline: False
```
**Symbols:**

```
ffffffff81719230-ffffffff81719375: __rtc_register_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __rtc_register_device(struct module *owner, struct rtc_device *rtc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/class.c (ffffffff8178a490)
Location: drivers/rtc/class.c:429
Inline: False
```
**Symbols:**

```
ffffffff8178a490-ffffffff8178a5d5: __rtc_register_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __rtc_register_device(struct module *owner, struct rtc_device *rtc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/class.c (ffffffff817cb6a0)
Location: drivers/rtc/class.c:499
Inline: False
Direct callers:
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
```
**Symbols:**

```
ffffffff817cb6a0-ffffffff817cb7d8: __rtc_register_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __rtc_register_device(struct module *owner, struct rtc_device *rtc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/class.c (ffffffff817f2c00)
Location: drivers/rtc/class.c:349
Inline: False
Direct callers:
  - drivers/rtc/class.c:devm_rtc_device_register
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
```
**Symbols:**

```
ffffffff817f2c00-ffffffff817f2e07: __rtc_register_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __rtc_register_device(struct module *owner, struct rtc_device *rtc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/rtc/class.c (ffffffff8183401b)
Location: drivers/rtc/class.c:344
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
ffffffff818338d0-ffffffff81833a6e: __rtc_register_device.part.0 (STB_LOCAL)
ffffffff81834045-ffffffff81834099: __rtc_register_device.part.0.cold (STB_LOCAL)
ffffffff81833a70-ffffffff81833a90: __rtc_register_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __rtc_register_device(struct module *owner, struct rtc_device *rtc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/rtc/class.c (ffffffff8186527f)
Location: drivers/rtc/class.c:344
Inline: True
Direct callers:
  - drivers/rtc/class.c:devm_rtc_device_register
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
```
**Symbols:**

```
ffffffff818659a9-ffffffff818659ee: __rtc_register_device.cold (STB_LOCAL)
ffffffff81865210-ffffffff818653fd: __rtc_register_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __rtc_register_device(struct module *owner, struct rtc_device *rtc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/rtc/class.c (ffffffff8193923b)
Location: drivers/rtc/class.c:388
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
ffffffff81938b50-ffffffff81938c1d: __rtc_register_device.part.0 (STB_LOCAL)
ffffffff8193929b-ffffffff81939383: __rtc_register_device.part.0.cold (STB_LOCAL)
ffffffff81938c20-ffffffff81938c60: __rtc_register_device (STB_GLOBAL)
```
</details>
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
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int __rtc_register_device(struct module *owner, struct rtc_device *rtc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/rtc/class.c (ffff800010aa6cf8)
Location: drivers/rtc/class.c:344
Inline: True
Direct callers:
  - drivers/rtc/class.c:devm_rtc_device_register
  - drivers/rtc/rtc-mv.c:mv_rtc_probe
  - drivers/rtc/rtc-xgene.c:xgene_rtc_probe
```
**Symbols:**

```
ffff800010aa6cf8-ffff800010aa6f0c: __rtc_register_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int __rtc_register_device(struct module *owner, struct rtc_device *rtc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/rtc/class.c (c0b857dc)
Location: drivers/rtc/class.c:344
Inline: True
Direct callers:
  - drivers/rtc/class.c:devm_rtc_device_register
  - drivers/rtc/rtc-mv.c:mv_rtc_probe
  - drivers/rtc/rtc-omap.c:omap_rtc_probe
  - drivers/rtc/rtc-pl031.c:pl031_probe
```
**Symbols:**

```
c0b857dc-c0b85a84: __rtc_register_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int __rtc_register_device(struct module *owner, struct rtc_device *rtc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/rtc/class.c (c000000000b87770)
Location: drivers/rtc/class.c:344
Inline: True
Direct callers:
  - drivers/rtc/class.c:devm_rtc_device_register
```
**Symbols:**

```
c000000000b87770-c000000000b879e8: __rtc_register_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int __rtc_register_device(struct module *owner, struct rtc_device *rtc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/rtc/class.c (ffffffe0006b2d7a)
Location: drivers/rtc/class.c:344
Inline: True
Direct callers:
  - drivers/rtc/class.c:devm_rtc_device_register
```
**Symbols:**

```
ffffffe0006b2d7a-ffffffe0006b2f2e: __rtc_register_device (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __rtc_register_device(struct module *owner, struct rtc_device *rtc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/rtc/class.c (ffffffff81817f2f)
Location: drivers/rtc/class.c:344
Inline: True
Direct callers:
  - drivers/rtc/class.c:devm_rtc_device_register
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
```
**Symbols:**

```
ffffffff81818659-ffffffff8181869e: __rtc_register_device.cold (STB_LOCAL)
ffffffff81817ec0-ffffffff818180ad: __rtc_register_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __rtc_register_device(struct module *owner, struct rtc_device *rtc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/rtc/class.c (ffffffff817df61f)
Location: drivers/rtc/class.c:344
Inline: True
Direct callers:
  - drivers/rtc/class.c:devm_rtc_device_register
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
```
**Symbols:**

```
ffffffff817dfd49-ffffffff817dfd8e: __rtc_register_device.cold (STB_LOCAL)
ffffffff817df5b0-ffffffff817df79d: __rtc_register_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __rtc_register_device(struct module *owner, struct rtc_device *rtc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/rtc/class.c (ffffffff8185940f)
Location: drivers/rtc/class.c:344
Inline: True
Direct callers:
  - drivers/rtc/class.c:devm_rtc_device_register
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
```
**Symbols:**

```
ffffffff81859b39-ffffffff81859b7e: __rtc_register_device.cold (STB_LOCAL)
ffffffff818593a0-ffffffff8185958d: __rtc_register_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __rtc_register_device(struct module *owner, struct rtc_device *rtc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/rtc/class.c (ffffffff818744ef)
Location: drivers/rtc/class.c:344
Inline: True
Direct callers:
  - drivers/rtc/class.c:devm_rtc_device_register
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
```
**Symbols:**

```
ffffffff81874c19-ffffffff81874c5e: __rtc_register_device.cold (STB_LOCAL)
ffffffff81874480-ffffffff8187466d: __rtc_register_device (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
