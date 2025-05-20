# Function: <code>usb_reset_and_verify_device</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int usb_reset_and_verify_device(struct usb_device *udev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81606bd0)
Location: drivers/usb/core/hub.c:5399
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_device
  - drivers/usb/core/hub.c:usb_reset_device
  - drivers/usb/core/hub.c:usb_port_resume
```
**Symbols:**

```
ffffffff81606bd0-ffffffff81607037: usb_reset_and_verify_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int usb_reset_and_verify_device(struct usb_device *udev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81666940)
Location: drivers/usb/core/hub.c:5417
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_device
  - drivers/usb/core/hub.c:usb_reset_device
  - drivers/usb/core/hub.c:usb_port_resume
```
**Symbols:**

```
ffffffff81666940-ffffffff81666d97: usb_reset_and_verify_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int usb_reset_and_verify_device(struct usb_device *udev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff816943d0)
Location: drivers/usb/core/hub.c:5393
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_device
  - drivers/usb/core/hub.c:usb_reset_device
  - drivers/usb/core/hub.c:usb_port_resume
```
**Symbols:**

```
ffffffff816943d0-ffffffff81694ac5: usb_reset_and_verify_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int usb_reset_and_verify_device(struct usb_device *udev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff816a9ae0)
Location: drivers/usb/core/hub.c:5414
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_device
  - drivers/usb/core/hub.c:usb_reset_device
  - drivers/usb/core/hub.c:usb_port_resume
```
**Symbols:**

```
ffffffff816a9ae0-ffffffff816a9f2d: usb_reset_and_verify_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int usb_reset_and_verify_device(struct usb_device *udev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81714f30)
Location: drivers/usb/core/hub.c:5452
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_device
  - drivers/usb/core/hub.c:usb_reset_device
  - drivers/usb/core/hub.c:usb_port_resume
```
**Symbols:**

```
ffffffff81714f30-ffffffff8171537d: usb_reset_and_verify_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int usb_reset_and_verify_device(struct usb_device *udev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81753d70)
Location: drivers/usb/core/hub.c:5524
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_device
  - drivers/usb/core/hub.c:usb_reset_device
  - drivers/usb/core/hub.c:usb_port_resume
```
**Symbols:**

```
ffffffff81753d70-ffffffff8175419a: usb_reset_and_verify_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int usb_reset_and_verify_device(struct usb_device *udev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff817781f0)
Location: drivers/usb/core/hub.c:5624
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_device
  - drivers/usb/core/hub.c:usb_reset_device
  - drivers/usb/core/hub.c:usb_port_resume
```
**Symbols:**

```
ffffffff817781f0-ffffffff817785f4: usb_reset_and_verify_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int usb_reset_and_verify_device(struct usb_device *udev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:5671
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_device
  - drivers/usb/core/hub.c:usb_reset_device
  - drivers/usb/core/hub.c:usb_port_resume
```
**Symbols:**

```
ffffffff817b6110-ffffffff817b6452: usb_reset_and_verify_device (STB_LOCAL)
ffffffff817ba5a7-ffffffff817ba66c: usb_reset_and_verify_device.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int usb_reset_and_verify_device(struct usb_device *udev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:5720
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_device
  - drivers/usb/core/hub.c:usb_reset_device
  - drivers/usb/core/hub.c:usb_port_resume
```
**Symbols:**

```
ffffffff817e6840-ffffffff817e6b82: usb_reset_and_verify_device (STB_LOCAL)
ffffffff817eadf5-ffffffff817eaeba: usb_reset_and_verify_device.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int usb_reset_and_verify_device(struct usb_device *udev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:5767
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_device
  - drivers/usb/core/hub.c:usb_reset_device
  - drivers/usb/core/hub.c:finish_port_resume
```
**Symbols:**

```
ffffffff818b6590-ffffffff818b6948: usb_reset_and_verify_device (STB_LOCAL)
ffffffff818ba2cb-ffffffff818ba398: usb_reset_and_verify_device.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int usb_reset_and_verify_device(struct usb_device *udev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:5782
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_device
  - drivers/usb/core/hub.c:usb_reset_device
  - drivers/usb/core/hub.c:finish_port_resume
```
**Symbols:**

```
ffffffff818c4ed0-ffffffff818c525d: usb_reset_and_verify_device (STB_LOCAL)
ffffffff81c1adf9-ffffffff81c1aebe: usb_reset_and_verify_device.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int usb_reset_and_verify_device(struct usb_device *udev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:5911
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_device
  - drivers/usb/core/hub.c:usb_reset_device
  - drivers/usb/core/hub.c:finish_port_resume
```
**Symbols:**

```
ffffffff818a81b0-ffffffff818a853d: usb_reset_and_verify_device (STB_LOCAL)
ffffffff81c0cc67-ffffffff81c0cd2c: usb_reset_and_verify_device.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int usb_reset_and_verify_device(struct usb_device *udev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:5924
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_device
  - drivers/usb/core/hub.c:usb_reset_device
  - drivers/usb/core/hub.c:finish_port_resume
```
**Symbols:**

```
ffffffff8193d020-ffffffff8193d413: usb_reset_and_verify_device (STB_LOCAL)
ffffffff81d13c17-ffffffff81d13cdc: usb_reset_and_verify_device.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int usb_reset_and_verify_device(struct usb_device *udev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:5941
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_device
  - drivers/usb/core/hub.c:usb_reset_device
  - drivers/usb/core/hub.c:finish_port_resume
```
**Symbols:**

```
ffffffff81a94d50-ffffffff81a9510c: usb_reset_and_verify_device (STB_LOCAL)
ffffffff81ede9c1-ffffffff81edea68: usb_reset_and_verify_device.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int usb_reset_and_verify_device(struct usb_device *udev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81c172c0)
Location: drivers/usb/core/hub.c:5965
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_device
  - drivers/usb/core/hub.c:usb_reset_device
  - drivers/usb/core/hub.c:finish_port_resume
```
**Symbols:**

```
ffffffff81c172c0-ffffffff81c17786: usb_reset_and_verify_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int usb_reset_and_verify_device(struct usb_device *udev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81c7e2f0)
Location: drivers/usb/core/hub.c:6036
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_device
  - drivers/usb/core/hub.c:usb_reset_device
  - drivers/usb/core/hub.c:finish_port_resume
```
**Symbols:**

```
ffffffff81c7e2f0-ffffffff81c7e78e: usb_reset_and_verify_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int usb_reset_and_verify_device(struct usb_device *udev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81d32cc0)
Location: drivers/usb/core/hub.c:6052
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_device
  - drivers/usb/core/hub.c:usb_reset_device
  - drivers/usb/core/hub.c:finish_port_resume
```
**Symbols:**

```
ffffffff81d32cc0-ffffffff81d3315e: usb_reset_and_verify_device (STB_LOCAL)
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
int usb_reset_and_verify_device(struct usb_device *udev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffff800010a156a0)
Location: drivers/usb/core/hub.c:5720
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_device
  - drivers/usb/core/hub.c:usb_reset_device
  - drivers/usb/core/hub.c:usb_port_resume
```
**Symbols:**

```
ffff800010a156a0-ffff800010a15a88: usb_reset_and_verify_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int usb_reset_and_verify_device(struct usb_device *udev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (c0aed9d0)
Location: drivers/usb/core/hub.c:5720
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_device
  - drivers/usb/core/hub.c:usb_reset_device
  - drivers/usb/core/hub.c:usb_port_resume
```
**Symbols:**

```
c0aed9d0-c0aeddc8: usb_reset_and_verify_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int usb_reset_and_verify_device(struct usb_device *udev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (c000000000acdb00)
Location: drivers/usb/core/hub.c:5720
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_device
  - drivers/usb/core/hub.c:usb_reset_device
  - drivers/usb/core/hub.c:usb_port_resume
```
**Symbols:**

```
c000000000acdb00-c000000000acdff0: usb_reset_and_verify_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int usb_reset_and_verify_device(struct usb_device *udev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffe00063a70c)
Location: drivers/usb/core/hub.c:5720
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_device
  - drivers/usb/core/hub.c:usb_reset_device
  - drivers/usb/core/hub.c:usb_port_resume
```
**Symbols:**

```
ffffffe00063a70c-ffffffe00063ace2: usb_reset_and_verify_device (STB_LOCAL)
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
int usb_reset_and_verify_device(struct usb_device *udev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:5720
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_device
  - drivers/usb/core/hub.c:usb_reset_device
  - drivers/usb/core/hub.c:usb_port_resume
```
**Symbols:**

```
ffffffff8179ec20-ffffffff8179ef62: usb_reset_and_verify_device (STB_LOCAL)
ffffffff817a31d5-ffffffff817a329a: usb_reset_and_verify_device.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int usb_reset_and_verify_device(struct usb_device *udev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:5720
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_device
  - drivers/usb/core/hub.c:usb_reset_device
  - drivers/usb/core/hub.c:usb_port_resume
```
**Symbols:**

```
ffffffff817908a0-ffffffff81790be2: usb_reset_and_verify_device (STB_LOCAL)
ffffffff81795015-ffffffff817950da: usb_reset_and_verify_device.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int usb_reset_and_verify_device(struct usb_device *udev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:5720
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_device
  - drivers/usb/core/hub.c:usb_reset_device
  - drivers/usb/core/hub.c:usb_port_resume
```
**Symbols:**

```
ffffffff817db6c0-ffffffff817dba02: usb_reset_and_verify_device (STB_LOCAL)
ffffffff817dfc75-ffffffff817dfd3a: usb_reset_and_verify_device.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int usb_reset_and_verify_device(struct usb_device *udev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:5720
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_device
  - drivers/usb/core/hub.c:usb_reset_device
  - drivers/usb/core/hub.c:usb_port_resume
```
**Symbols:**

```
ffffffff817f5950-ffffffff817f5c92: usb_reset_and_verify_device (STB_LOCAL)
ffffffff817f9f65-ffffffff817fa02a: usb_reset_and_verify_device.cold (STB_LOCAL)
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
