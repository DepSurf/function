# Function: <code>hcd_bus_resume</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int hcd_bus_resume(struct usb_device *rhdev, pm_message_t msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff8160f920)
Location: drivers/usb/core/hcd.c:2287
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:hcd_bus_suspend
  - drivers/usb/core/generic.c:generic_resume
```
**Symbols:**

```
ffffffff8160f920-ffffffff8160fb26: hcd_bus_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int hcd_bus_resume(struct usb_device *rhdev, pm_message_t msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff8166f500)
Location: drivers/usb/core/hcd.c:2283
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:hcd_bus_suspend
  - drivers/usb/core/generic.c:generic_resume
```
**Symbols:**

```
ffffffff8166f500-ffffffff8166f70a: hcd_bus_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int hcd_bus_resume(struct usb_device *rhdev, pm_message_t msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff8169d1e0)
Location: drivers/usb/core/hcd.c:2284
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:hcd_bus_suspend
  - drivers/usb/core/generic.c:generic_resume
```
**Symbols:**

```
ffffffff8169d1e0-ffffffff8169d3ea: hcd_bus_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int hcd_bus_resume(struct usb_device *rhdev, pm_message_t msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff816b25b0)
Location: drivers/usb/core/hcd.c:2298
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:hcd_bus_suspend
  - drivers/usb/core/generic.c:generic_resume
```
**Symbols:**

```
ffffffff816b25b0-ffffffff816b27ce: hcd_bus_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int hcd_bus_resume(struct usb_device *rhdev, pm_message_t msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff8171dc30)
Location: drivers/usb/core/hcd.c:2287
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:hcd_bus_suspend
  - drivers/usb/core/generic.c:generic_resume
```
**Symbols:**

```
ffffffff8171dc30-ffffffff8171de54: hcd_bus_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int hcd_bus_resume(struct usb_device *rhdev, pm_message_t msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff8175c8a0)
Location: drivers/usb/core/hcd.c:2293
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:hcd_bus_suspend
  - drivers/usb/core/generic.c:generic_resume
```
**Symbols:**

```
ffffffff8175c8a0-ffffffff8175cafb: hcd_bus_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int hcd_bus_resume(struct usb_device *rhdev, pm_message_t msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff81780e60)
Location: drivers/usb/core/hcd.c:2277
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:hcd_bus_suspend
  - drivers/usb/core/generic.c:generic_resume
```
**Symbols:**

```
ffffffff81780e60-ffffffff817810bb: hcd_bus_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int hcd_bus_resume(struct usb_device *rhdev, pm_message_t msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hcd.c (0)
Location: drivers/usb/core/hcd.c:2166
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:hcd_bus_suspend
  - drivers/usb/core/generic.c:generic_resume
```
**Symbols:**

```
ffffffff817bf83f-ffffffff817bf84c: hcd_bus_resume.cold (STB_LOCAL)
ffffffff817be870-ffffffff817beacf: hcd_bus_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int hcd_bus_resume(struct usb_device *rhdev, pm_message_t msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hcd.c (0)
Location: drivers/usb/core/hcd.c:2163
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:hcd_bus_suspend
  - drivers/usb/core/generic.c:generic_resume
```
**Symbols:**

```
ffffffff817f01b5-ffffffff817f01c2: hcd_bus_resume.cold (STB_LOCAL)
ffffffff817ef1d0-ffffffff817ef446: hcd_bus_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int hcd_bus_resume(struct usb_device *rhdev, pm_message_t msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hcd.c (0)
Location: drivers/usb/core/hcd.c:2160
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:hcd_bus_suspend
  - drivers/usb/core/generic.c:usb_generic_driver_resume
```
**Symbols:**

```
ffffffff818bf877-ffffffff818bf884: hcd_bus_resume.cold (STB_LOCAL)
ffffffff818be7f0-ffffffff818bea65: hcd_bus_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int hcd_bus_resume(struct usb_device *rhdev, pm_message_t msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hcd.c (0)
Location: drivers/usb/core/hcd.c:2170
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:hcd_bus_suspend
  - drivers/usb/core/generic.c:usb_generic_driver_resume
```
**Symbols:**

```
ffffffff81c1ce96-ffffffff81c1cea3: hcd_bus_resume.cold (STB_LOCAL)
ffffffff818cb3f0-ffffffff818cb665: hcd_bus_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int hcd_bus_resume(struct usb_device *rhdev, pm_message_t msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hcd.c (0)
Location: drivers/usb/core/hcd.c:2170
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:hcd_bus_suspend
  - drivers/usb/core/generic.c:usb_generic_driver_resume
```
**Symbols:**

```
ffffffff81c0ed5c-ffffffff81c0ed69: hcd_bus_resume.cold (STB_LOCAL)
ffffffff818aea10-ffffffff818aec85: hcd_bus_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int hcd_bus_resume(struct usb_device *rhdev, pm_message_t msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hcd.c (0)
Location: drivers/usb/core/hcd.c:2321
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:hcd_bus_suspend
  - drivers/usb/core/generic.c:usb_generic_driver_resume
```
**Symbols:**

```
ffffffff81d15ea6-ffffffff81d15eb3: hcd_bus_resume.cold (STB_LOCAL)
ffffffff81943b80-ffffffff81943dfd: hcd_bus_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int hcd_bus_resume(struct usb_device *rhdev, pm_message_t msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hcd.c (0)
Location: drivers/usb/core/hcd.c:2324
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:hcd_bus_suspend
  - drivers/usb/core/generic.c:usb_generic_driver_resume
```
**Symbols:**

```
ffffffff81ee0a49-ffffffff81ee0a56: hcd_bus_resume.cold (STB_LOCAL)
ffffffff81a9c040-ffffffff81a9c29d: hcd_bus_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int hcd_bus_resume(struct usb_device *rhdev, pm_message_t msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff81c20f10)
Location: drivers/usb/core/hcd.c:2318
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:hcd_bus_suspend
  - drivers/usb/core/generic.c:usb_generic_driver_resume
```
**Symbols:**

```
ffffffff81c20f10-ffffffff81c21190: hcd_bus_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int hcd_bus_resume(struct usb_device *rhdev, pm_message_t msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff81c87e90)
Location: drivers/usb/core/hcd.c:2322
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:hcd_bus_suspend
  - drivers/usb/core/generic.c:usb_generic_driver_resume
```
**Symbols:**

```
ffffffff81c87e90-ffffffff81c88110: hcd_bus_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int hcd_bus_resume(struct usb_device *rhdev, pm_message_t msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff81d3c8e0)
Location: drivers/usb/core/hcd.c:2297
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:hcd_bus_suspend
  - drivers/usb/core/generic.c:usb_generic_driver_resume
```
**Symbols:**

```
ffffffff81d3c8e0-ffffffff81d3cb60: hcd_bus_resume (STB_GLOBAL)
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
int hcd_bus_resume(struct usb_device *rhdev, pm_message_t msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffff800010a1f018)
Location: drivers/usb/core/hcd.c:2163
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:hcd_bus_suspend
  - drivers/usb/core/generic.c:generic_resume
```
**Symbols:**

```
ffff800010a1f018-ffff800010a1f32c: hcd_bus_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int hcd_bus_resume(struct usb_device *rhdev, pm_message_t msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (c0af669c)
Location: drivers/usb/core/hcd.c:2163
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:hcd_bus_suspend
  - drivers/usb/core/generic.c:generic_resume
```
**Symbols:**

```
c0af669c-c0af6914: hcd_bus_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int hcd_bus_resume(struct usb_device *rhdev, pm_message_t msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (c000000000ad92d0)
Location: drivers/usb/core/hcd.c:2163
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:hcd_bus_suspend
  - drivers/usb/core/generic.c:generic_resume
```
**Symbols:**

```
c000000000ad92d0-c000000000ad964c: hcd_bus_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int hcd_bus_resume(struct usb_device *rhdev, pm_message_t msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffe0006428bc)
Location: drivers/usb/core/hcd.c:2163
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:hcd_bus_suspend
  - drivers/usb/core/generic.c:generic_resume
```
**Symbols:**

```
ffffffe0006428bc-ffffffe000642b16: hcd_bus_resume (STB_GLOBAL)
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
int hcd_bus_resume(struct usb_device *rhdev, pm_message_t msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hcd.c (0)
Location: drivers/usb/core/hcd.c:2163
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:hcd_bus_suspend
  - drivers/usb/core/generic.c:generic_resume
```
**Symbols:**

```
ffffffff817a8595-ffffffff817a85a2: hcd_bus_resume.cold (STB_LOCAL)
ffffffff817a75b0-ffffffff817a7826: hcd_bus_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int hcd_bus_resume(struct usb_device *rhdev, pm_message_t msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hcd.c (0)
Location: drivers/usb/core/hcd.c:2163
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:hcd_bus_suspend
  - drivers/usb/core/generic.c:generic_resume
```
**Symbols:**

```
ffffffff81799fae-ffffffff81799fbb: hcd_bus_resume.cold (STB_LOCAL)
ffffffff81799000-ffffffff81799270: hcd_bus_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int hcd_bus_resume(struct usb_device *rhdev, pm_message_t msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hcd.c (0)
Location: drivers/usb/core/hcd.c:2163
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:hcd_bus_suspend
  - drivers/usb/core/generic.c:generic_resume
```
**Symbols:**

```
ffffffff817e5035-ffffffff817e5042: hcd_bus_resume.cold (STB_LOCAL)
ffffffff817e4050-ffffffff817e42c6: hcd_bus_resume (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int hcd_bus_resume(struct usb_device *rhdev, pm_message_t msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hcd.c (0)
Location: drivers/usb/core/hcd.c:2163
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:hcd_bus_suspend
  - drivers/usb/core/generic.c:generic_resume
```
**Symbols:**

```
ffffffff817ff2a1-ffffffff817ff2ae: hcd_bus_resume.cold (STB_LOCAL)
ffffffff817fe2f0-ffffffff817fe55d: hcd_bus_resume (STB_GLOBAL)
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
