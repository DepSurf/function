# Function: <code>usb_enable_lpm</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void usb_enable_lpm(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81604f80)
Location: drivers/usb/core/hub.c:4092
Inline: True
Direct callers:
  - drivers/usb/core/hub.c:usb_unlocked_enable_lpm
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_set_configuration
```
**Symbols:**

```
ffffffff81604f80-ffffffff81605012: usb_enable_lpm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void usb_enable_lpm(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81664cc0)
Location: drivers/usb/core/hub.c:4093
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_unlocked_enable_lpm
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/port.c:usb3_lpm_permit_store
```
**Symbols:**

```
ffffffff81664cc0-ffffffff81664dbe: usb_enable_lpm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void usb_enable_lpm(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff816927e0)
Location: drivers/usb/core/hub.c:4019
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_unlocked_enable_lpm
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/port.c:usb3_lpm_permit_store
```
**Symbols:**

```
ffffffff816927e0-ffffffff816928de: usb_enable_lpm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void usb_enable_lpm(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff816a8110)
Location: drivers/usb/core/hub.c:4038
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_unlocked_enable_lpm
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/port.c:usb3_lpm_permit_store
```
**Symbols:**

```
ffffffff816a8110-ffffffff816a820f: usb_enable_lpm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void usb_enable_lpm(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff817132f0)
Location: drivers/usb/core/hub.c:4041
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_unlocked_enable_lpm
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/port.c:usb3_lpm_permit_store
```
**Symbols:**

```
ffffffff817132f0-ffffffff817133ef: usb_enable_lpm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void usb_enable_lpm(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81752160)
Location: drivers/usb/core/hub.c:4092
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_unlocked_enable_lpm
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/port.c:usb3_lpm_permit_store
```
**Symbols:**

```
ffffffff81752160-ffffffff8175225e: usb_enable_lpm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void usb_enable_lpm(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff817765e0)
Location: drivers/usb/core/hub.c:4154
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_unlocked_enable_lpm
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/port.c:usb3_lpm_permit_store
```
**Symbols:**

```
ffffffff817765e0-ffffffff817766de: usb_enable_lpm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void usb_enable_lpm(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff817b4440)
Location: drivers/usb/core/hub.c:4201
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_unlocked_enable_lpm
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/port.c:usb3_lpm_permit_store
```
**Symbols:**

```
ffffffff817b4440-ffffffff817b453b: usb_enable_lpm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void usb_enable_lpm(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff817e4b70)
Location: drivers/usb/core/hub.c:4249
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_unlocked_enable_lpm
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/port.c:usb3_lpm_permit_store
```
**Symbols:**

```
ffffffff817e4b70-ffffffff817e4c6b: usb_enable_lpm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void usb_enable_lpm(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff818b4190)
Location: drivers/usb/core/hub.c:4263
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/port.c:usb3_lpm_permit_store
```
**Symbols:**

```
ffffffff818b4190-ffffffff818b42bb: usb_enable_lpm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void usb_enable_lpm(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff818c2b00)
Location: drivers/usb/core/hub.c:4281
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/port.c:usb3_lpm_permit_store
```
**Symbols:**

```
ffffffff818c2b00-ffffffff818c2c2b: usb_enable_lpm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void usb_enable_lpm(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff818a5af0)
Location: drivers/usb/core/hub.c:4401
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/port.c:usb3_lpm_permit_store
```
**Symbols:**

```
ffffffff818a5af0-ffffffff818a5c1b: usb_enable_lpm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void usb_enable_lpm(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff8193a950)
Location: drivers/usb/core/hub.c:4405
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/port.c:usb3_lpm_permit_store
```
**Symbols:**

```
ffffffff8193a950-ffffffff8193aa7b: usb_enable_lpm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void usb_enable_lpm(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81a925d0)
Location: drivers/usb/core/hub.c:4411
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:usb_disable_lpm
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/port.c:usb3_lpm_permit_store
```
**Symbols:**

```
ffffffff81a925d0-ffffffff81a92719: usb_enable_lpm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void usb_enable_lpm(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81c14750)
Location: drivers/usb/core/hub.c:4402
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:usb_disable_lpm
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/port.c:usb3_lpm_permit_store
```
**Symbols:**

```
ffffffff81c14750-ffffffff81c14872: usb_enable_lpm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void usb_enable_lpm(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81c7b550)
Location: drivers/usb/core/hub.c:4422
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:usb_disable_lpm
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/port.c:usb3_lpm_permit_store
```
**Symbols:**

```
ffffffff81c7b550-ffffffff81c7b672: usb_enable_lpm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void usb_enable_lpm(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81d301a0)
Location: drivers/usb/core/hub.c:4431
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:usb_disable_lpm
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/port.c:usb3_lpm_permit_store
```
**Symbols:**

```
ffffffff81d301a0-ffffffff81d302c2: usb_enable_lpm (STB_GLOBAL)
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
void usb_enable_lpm(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffff800010a13468)
Location: drivers/usb/core/hub.c:4249
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_unlocked_enable_lpm
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/port.c:usb3_lpm_permit_store
```
**Symbols:**

```
ffff800010a13468-ffff800010a1355c: usb_enable_lpm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void usb_enable_lpm(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (c0aebcc4)
Location: drivers/usb/core/hub.c:4249
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_unlocked_enable_lpm
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/port.c:usb3_lpm_permit_store
```
**Symbols:**

```
c0aebcc4-c0aebdcc: usb_enable_lpm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void usb_enable_lpm(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (c000000000aca2d0)
Location: drivers/usb/core/hub.c:4249
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_unlocked_enable_lpm
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/port.c:usb3_lpm_permit_store
```
**Symbols:**

```
c000000000aca2d0-c000000000aca420: usb_enable_lpm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void usb_enable_lpm(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffe000638436)
Location: drivers/usb/core/hub.c:4249
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_unlocked_enable_lpm
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/port.c:usb3_lpm_permit_store
```
**Symbols:**

```
ffffffe000638436-ffffffe0006384f4: usb_enable_lpm (STB_GLOBAL)
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
void usb_enable_lpm(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff8179cf50)
Location: drivers/usb/core/hub.c:4249
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_unlocked_enable_lpm
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/port.c:usb3_lpm_permit_store
```
**Symbols:**

```
ffffffff8179cf50-ffffffff8179d04b: usb_enable_lpm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void usb_enable_lpm(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff8178ebe0)
Location: drivers/usb/core/hub.c:4249
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_unlocked_enable_lpm
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/port.c:usb3_lpm_permit_store
```
**Symbols:**

```
ffffffff8178ebe0-ffffffff8178ecdb: usb_enable_lpm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void usb_enable_lpm(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff817d99f0)
Location: drivers/usb/core/hub.c:4249
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_unlocked_enable_lpm
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/port.c:usb3_lpm_permit_store
```
**Symbols:**

```
ffffffff817d99f0-ffffffff817d9aeb: usb_enable_lpm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void usb_enable_lpm(struct usb_device *udev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff817f3d60)
Location: drivers/usb/core/hub.c:4249
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_unlocked_enable_lpm
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_reset_configuration
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/message.c:usb_set_interface
  - drivers/usb/core/port.c:usb3_lpm_permit_store
```
**Symbols:**

```
ffffffff817f3d60-ffffffff817f3e5b: usb_enable_lpm (STB_GLOBAL)
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
