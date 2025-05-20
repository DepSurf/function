# Function: <code>usb_suspend_both</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int usb_suspend_both(struct usb_device *udev, pm_message_t msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/driver.c (ffffffff816143b0)
Location: drivers/usb/core/driver.c:1286
Inline: False
Direct callers:
  - drivers/usb/core/driver.c:usb_suspend
  - drivers/usb/core/driver.c:usb_runtime_suspend
```
**Symbols:**

```
ffffffff816143b0-ffffffff8161457d: usb_suspend_both (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int usb_suspend_both(struct usb_device *udev, pm_message_t msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/driver.c (ffffffff81674360)
Location: drivers/usb/core/driver.c:1296
Inline: False
Direct callers:
  - drivers/usb/core/driver.c:usb_runtime_suspend
  - drivers/usb/core/driver.c:usb_suspend
```
**Symbols:**

```
ffffffff81674360-ffffffff8167452f: usb_suspend_both (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int usb_suspend_both(struct usb_device *udev, pm_message_t msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/driver.c (ffffffff816a1ff0)
Location: drivers/usb/core/driver.c:1299
Inline: False
Direct callers:
  - drivers/usb/core/driver.c:usb_runtime_suspend
  - drivers/usb/core/driver.c:usb_suspend
```
**Symbols:**

```
ffffffff816a1ff0-ffffffff816a21bf: usb_suspend_both (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int usb_suspend_both(struct usb_device *udev, pm_message_t msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/driver.c (ffffffff816b7010)
Location: drivers/usb/core/driver.c:1299
Inline: False
Direct callers:
  - drivers/usb/core/driver.c:usb_runtime_suspend
  - drivers/usb/core/driver.c:usb_suspend
```
**Symbols:**

```
ffffffff816b7010-ffffffff816b7237: usb_suspend_both (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int usb_suspend_both(struct usb_device *udev, pm_message_t msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/driver.c (ffffffff817228b0)
Location: drivers/usb/core/driver.c:1299
Inline: False
Direct callers:
  - drivers/usb/core/driver.c:usb_runtime_suspend
  - drivers/usb/core/driver.c:usb_suspend
```
**Symbols:**

```
ffffffff817228b0-ffffffff81722ae5: usb_suspend_both (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int usb_suspend_both(struct usb_device *udev, pm_message_t msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/driver.c (ffffffff817614f0)
Location: drivers/usb/core/driver.c:1299
Inline: False
Direct callers:
  - drivers/usb/core/driver.c:usb_runtime_suspend
  - drivers/usb/core/driver.c:usb_suspend
```
**Symbols:**

```
ffffffff817614f0-ffffffff81761725: usb_suspend_both (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int usb_suspend_both(struct usb_device *udev, pm_message_t msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/driver.c (ffffffff817859b0)
Location: drivers/usb/core/driver.c:1296
Inline: False
Direct callers:
  - drivers/usb/core/driver.c:usb_runtime_suspend
  - drivers/usb/core/driver.c:usb_suspend
```
**Symbols:**

```
ffffffff817859b0-ffffffff81785be5: usb_suspend_both (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int usb_suspend_both(struct usb_device *udev, pm_message_t msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/driver.c (0)
Location: drivers/usb/core/driver.c:1291
Inline: False
Direct callers:
  - drivers/usb/core/driver.c:usb_runtime_suspend
  - drivers/usb/core/driver.c:usb_suspend
```
**Symbols:**

```
ffffffff817c3e90-ffffffff817c4097: usb_suspend_both (STB_LOCAL)
ffffffff817c5707-ffffffff817c5740: usb_suspend_both.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int usb_suspend_both(struct usb_device *udev, pm_message_t msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/driver.c (0)
Location: drivers/usb/core/driver.c:1293
Inline: False
Direct callers:
  - drivers/usb/core/driver.c:usb_runtime_suspend
  - drivers/usb/core/driver.c:usb_suspend
```
**Symbols:**

```
ffffffff817f4950-ffffffff817f4b57: usb_suspend_both (STB_LOCAL)
ffffffff817f60c2-ffffffff817f60fb: usb_suspend_both.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int usb_suspend_both(struct usb_device *udev, pm_message_t msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/driver.c (0)
Location: drivers/usb/core/driver.c:1391
Inline: False
Direct callers:
  - drivers/usb/core/driver.c:usb_runtime_suspend
  - drivers/usb/core/driver.c:usb_suspend
```
**Symbols:**

```
ffffffff818c46a0-ffffffff818c48df: usb_suspend_both (STB_LOCAL)
ffffffff818c5fef-ffffffff818c6027: usb_suspend_both.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int usb_suspend_both(struct usb_device *udev, pm_message_t msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/driver.c (0)
Location: drivers/usb/core/driver.c:1401
Inline: False
Direct callers:
  - drivers/usb/core/driver.c:usb_runtime_suspend
  - drivers/usb/core/driver.c:usb_suspend
```
**Symbols:**

```
ffffffff818d0590-ffffffff818d07cf: usb_suspend_both (STB_LOCAL)
ffffffff81c1d406-ffffffff81c1d43e: usb_suspend_both.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int usb_suspend_both(struct usb_device *udev, pm_message_t msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/driver.c (0)
Location: drivers/usb/core/driver.c:1397
Inline: False
Direct callers:
  - drivers/usb/core/driver.c:usb_runtime_suspend
  - drivers/usb/core/driver.c:usb_suspend
```
**Symbols:**

```
ffffffff818b3bc0-ffffffff818b3dec: usb_suspend_both (STB_LOCAL)
ffffffff81c0f2cc-ffffffff81c0f304: usb_suspend_both.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int usb_suspend_both(struct usb_device *udev, pm_message_t msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/driver.c (0)
Location: drivers/usb/core/driver.c:1397
Inline: False
Direct callers:
  - drivers/usb/core/driver.c:usb_runtime_suspend
  - drivers/usb/core/driver.c:usb_suspend
```
**Symbols:**

```
ffffffff81949050-ffffffff81949319: usb_suspend_both (STB_LOCAL)
ffffffff81d1646b-ffffffff81d164a5: usb_suspend_both.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int usb_suspend_both(struct usb_device *udev, pm_message_t msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/driver.c (0)
Location: drivers/usb/core/driver.c:1398
Inline: False
Direct callers:
  - drivers/usb/core/driver.c:usb_runtime_suspend
  - drivers/usb/core/driver.c:usb_suspend
```
**Symbols:**

```
ffffffff81aa1c90-ffffffff81aa1f8a: usb_suspend_both (STB_LOCAL)
ffffffff81ee105e-ffffffff81ee1090: usb_suspend_both.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int usb_suspend_both(struct usb_device *udev, pm_message_t msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/driver.c (ffffffff81c275e0)
Location: drivers/usb/core/driver.c:1398
Inline: False
Direct callers:
  - drivers/usb/core/driver.c:usb_runtime_suspend
  - drivers/usb/core/driver.c:usb_suspend
```
**Symbols:**

```
ffffffff81c275e0-ffffffff81c27906: usb_suspend_both (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int usb_suspend_both(struct usb_device *udev, pm_message_t msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/driver.c (ffffffff81c8e770)
Location: drivers/usb/core/driver.c:1398
Inline: False
Direct callers:
  - drivers/usb/core/driver.c:usb_runtime_suspend
  - drivers/usb/core/driver.c:usb_suspend
```
**Symbols:**

```
ffffffff81c8e770-ffffffff81c8ea8d: usb_suspend_both (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int usb_suspend_both(struct usb_device *udev, pm_message_t msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/driver.c (ffffffff81d432c0)
Location: drivers/usb/core/driver.c:1404
Inline: False
Direct callers:
  - drivers/usb/core/driver.c:usb_runtime_suspend
  - drivers/usb/core/driver.c:usb_suspend
```
**Symbols:**

```
ffffffff81d432c0-ffffffff81d435dd: usb_suspend_both (STB_LOCAL)
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
int usb_suspend_both(struct usb_device *udev, pm_message_t msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/driver.c (ffff800010a25500)
Location: drivers/usb/core/driver.c:1293
Inline: False
Direct callers:
  - drivers/usb/core/driver.c:usb_runtime_suspend
  - drivers/usb/core/driver.c:usb_suspend
```
**Symbols:**

```
ffff800010a25500-ffff800010a2572c: usb_suspend_both (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int usb_suspend_both(struct usb_device *udev, pm_message_t msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/driver.c (c0afbca8)
Location: drivers/usb/core/driver.c:1293
Inline: False
Direct callers:
  - drivers/usb/core/driver.c:usb_runtime_suspend
  - drivers/usb/core/driver.c:usb_suspend
```
**Symbols:**

```
c0afbca8-c0afbec8: usb_suspend_both (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int usb_suspend_both(struct usb_device *udev, pm_message_t msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/driver.c (c000000000ae0890)
Location: drivers/usb/core/driver.c:1293
Inline: False
Direct callers:
  - drivers/usb/core/driver.c:usb_runtime_suspend
  - drivers/usb/core/driver.c:usb_suspend
```
**Symbols:**

```
c000000000ae0890-c000000000ae0bb0: usb_suspend_both (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int usb_suspend_both(struct usb_device *udev, pm_message_t msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/driver.c (ffffffe000647822)
Location: drivers/usb/core/driver.c:1293
Inline: False
Direct callers:
  - drivers/usb/core/driver.c:usb_runtime_suspend
  - drivers/usb/core/driver.c:usb_suspend
```
**Symbols:**

```
ffffffe000647822-ffffffe0006479c0: usb_suspend_both (STB_LOCAL)
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
int usb_suspend_both(struct usb_device *udev, pm_message_t msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/driver.c (0)
Location: drivers/usb/core/driver.c:1293
Inline: False
Direct callers:
  - drivers/usb/core/driver.c:usb_runtime_suspend
  - drivers/usb/core/driver.c:usb_suspend
```
**Symbols:**

```
ffffffff817acd30-ffffffff817acf37: usb_suspend_both (STB_LOCAL)
ffffffff817ae4a2-ffffffff817ae4db: usb_suspend_both.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int usb_suspend_both(struct usb_device *udev, pm_message_t msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/driver.c (0)
Location: drivers/usb/core/driver.c:1293
Inline: False
Direct callers:
  - drivers/usb/core/driver.c:usb_runtime_suspend
  - drivers/usb/core/driver.c:usb_suspend
```
**Symbols:**

```
ffffffff8179e730-ffffffff8179e937: usb_suspend_both (STB_LOCAL)
ffffffff8179fea2-ffffffff8179fedb: usb_suspend_both.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int usb_suspend_both(struct usb_device *udev, pm_message_t msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/driver.c (0)
Location: drivers/usb/core/driver.c:1293
Inline: False
Direct callers:
  - drivers/usb/core/driver.c:usb_runtime_suspend
  - drivers/usb/core/driver.c:usb_suspend
```
**Symbols:**

```
ffffffff817e97d0-ffffffff817e99d7: usb_suspend_both (STB_LOCAL)
ffffffff817eaf42-ffffffff817eaf7b: usb_suspend_both.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int usb_suspend_both(struct usb_device *udev, pm_message_t msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/driver.c (0)
Location: drivers/usb/core/driver.c:1293
Inline: False
Direct callers:
  - drivers/usb/core/driver.c:usb_runtime_suspend
  - drivers/usb/core/driver.c:usb_suspend
```
**Symbols:**

```
ffffffff81803d00-ffffffff81803f07: usb_suspend_both (STB_LOCAL)
ffffffff81805180-ffffffff818051b9: usb_suspend_both.cold (STB_LOCAL)
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
