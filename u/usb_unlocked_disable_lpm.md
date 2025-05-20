# Function: <code>usb_unlocked_disable_lpm</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int usb_unlocked_disable_lpm(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81605110)
Location: drivers/usb/core/hub.c:4068
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/message.c:usb_disable_device
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
**Symbols:**

```
ffffffff81605110-ffffffff8160515a: usb_unlocked_disable_lpm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int usb_unlocked_disable_lpm(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81664eb0)
Location: drivers/usb/core/hub.c:4069
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/message.c:usb_disable_device
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
**Symbols:**

```
ffffffff81664eb0-ffffffff81664efa: usb_unlocked_disable_lpm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int usb_unlocked_disable_lpm(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff816929d0)
Location: drivers/usb/core/hub.c:3995
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/message.c:usb_disable_device
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
**Symbols:**

```
ffffffff816929d0-ffffffff81692a1a: usb_unlocked_disable_lpm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int usb_unlocked_disable_lpm(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff816a8310)
Location: drivers/usb/core/hub.c:4014
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/message.c:usb_disable_device
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
**Symbols:**

```
ffffffff816a8310-ffffffff816a835a: usb_unlocked_disable_lpm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int usb_unlocked_disable_lpm(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff817134f0)
Location: drivers/usb/core/hub.c:4017
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/message.c:usb_disable_device
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
**Symbols:**

```
ffffffff817134f0-ffffffff8171353a: usb_unlocked_disable_lpm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int usb_unlocked_disable_lpm(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81752350)
Location: drivers/usb/core/hub.c:4068
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/message.c:usb_disable_device
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
**Symbols:**

```
ffffffff81752350-ffffffff8175239a: usb_unlocked_disable_lpm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int usb_unlocked_disable_lpm(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff817767d0)
Location: drivers/usb/core/hub.c:4130
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/message.c:usb_disable_device
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
**Symbols:**

```
ffffffff817767d0-ffffffff8177681a: usb_unlocked_disable_lpm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int usb_unlocked_disable_lpm(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff817b4630)
Location: drivers/usb/core/hub.c:4177
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/message.c:usb_disable_device
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
**Symbols:**

```
ffffffff817b4630-ffffffff817b467b: usb_unlocked_disable_lpm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int usb_unlocked_disable_lpm(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff817e4d60)
Location: drivers/usb/core/hub.c:4225
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/message.c:usb_disable_device
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
**Symbols:**

```
ffffffff817e4d60-ffffffff817e4dab: usb_unlocked_disable_lpm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int usb_unlocked_disable_lpm(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff818b6636)
Location: drivers/usb/core/hub.c:4239
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
Direct callers:
  - drivers/usb/core/message.c:usb_disable_device
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
**Symbols:**

```
ffffffff818b4370-ffffffff818b43bb: usb_unlocked_disable_lpm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int usb_unlocked_disable_lpm(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff818c4f73)
Location: drivers/usb/core/hub.c:4257
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
Direct callers:
  - drivers/usb/core/message.c:usb_disable_device
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
**Symbols:**

```
ffffffff818c2ce0-ffffffff818c2d2b: usb_unlocked_disable_lpm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int usb_unlocked_disable_lpm(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff818a8253)
Location: drivers/usb/core/hub.c:4377
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
Direct callers:
  - drivers/usb/core/message.c:usb_disable_device
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
**Symbols:**

```
ffffffff818a5cd0-ffffffff818a5d1b: usb_unlocked_disable_lpm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int usb_unlocked_disable_lpm(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff8193d0c3)
Location: drivers/usb/core/hub.c:4381
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
Direct callers:
  - drivers/usb/core/message.c:usb_disable_device
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
**Symbols:**

```
ffffffff8193ab30-ffffffff8193ab7b: usb_unlocked_disable_lpm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int usb_unlocked_disable_lpm(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81a927e0)
Location: drivers/usb/core/hub.c:4387
Inline: False
Direct callers:
  - drivers/usb/core/message.c:usb_disable_device
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
**Symbols:**

```
ffffffff81a927e0-ffffffff81a92830: usb_unlocked_disable_lpm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int usb_unlocked_disable_lpm(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81c14960)
Location: drivers/usb/core/hub.c:4378
Inline: False
Direct callers:
  - drivers/usb/core/message.c:usb_disable_device
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
**Symbols:**

```
ffffffff81c14960-ffffffff81c149b0: usb_unlocked_disable_lpm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int usb_unlocked_disable_lpm(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81c7b760)
Location: drivers/usb/core/hub.c:4398
Inline: False
Direct callers:
  - drivers/usb/core/message.c:usb_disable_device
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
**Symbols:**

```
ffffffff81c7b760-ffffffff81c7b7b0: usb_unlocked_disable_lpm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int usb_unlocked_disable_lpm(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81d303b0)
Location: drivers/usb/core/hub.c:4407
Inline: False
Direct callers:
  - drivers/usb/core/message.c:usb_disable_device
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
**Symbols:**

```
ffffffff81d303b0-ffffffff81d30400: usb_unlocked_disable_lpm (STB_GLOBAL)
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
int usb_unlocked_disable_lpm(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffff800010a13668)
Location: drivers/usb/core/hub.c:4225
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/message.c:usb_disable_device
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
**Symbols:**

```
ffff800010a13668-ffff800010a136bc: usb_unlocked_disable_lpm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int usb_unlocked_disable_lpm(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (c0aebee0)
Location: drivers/usb/core/hub.c:4225
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/message.c:usb_disable_device
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
**Symbols:**

```
c0aebee0-c0aebf30: usb_unlocked_disable_lpm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int usb_unlocked_disable_lpm(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (c000000000acb820)
Location: drivers/usb/core/hub.c:4225
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/message.c:usb_disable_device
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
**Symbols:**

```
c000000000acb820-c000000000acb89c: usb_unlocked_disable_lpm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int usb_unlocked_disable_lpm(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffe0006390b4)
Location: drivers/usb/core/hub.c:4225
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/message.c:usb_disable_device
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
**Symbols:**

```
ffffffe0006390b4-ffffffe00063910a: usb_unlocked_disable_lpm (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int usb_unlocked_disable_lpm(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff8179d140)
Location: drivers/usb/core/hub.c:4225
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/message.c:usb_disable_device
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
**Symbols:**

```
ffffffff8179d140-ffffffff8179d18b: usb_unlocked_disable_lpm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int usb_unlocked_disable_lpm(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff8178edd0)
Location: drivers/usb/core/hub.c:4225
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/message.c:usb_disable_device
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
**Symbols:**

```
ffffffff8178edd0-ffffffff8178ee1b: usb_unlocked_disable_lpm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int usb_unlocked_disable_lpm(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff817d9be0)
Location: drivers/usb/core/hub.c:4225
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/message.c:usb_disable_device
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
**Symbols:**

```
ffffffff817d9be0-ffffffff817d9c2b: usb_unlocked_disable_lpm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int usb_unlocked_disable_lpm(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff817f3f50)
Location: drivers/usb/core/hub.c:4225
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/message.c:usb_disable_device
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
**Symbols:**

```
ffffffff817f3f50-ffffffff817f3f9b: usb_unlocked_disable_lpm (STB_GLOBAL)
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
