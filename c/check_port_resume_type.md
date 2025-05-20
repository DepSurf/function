# Function: <code>check_port_resume_type</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff8160913a)
Location: drivers/usb/core/hub.c:2968
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_port_resume
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81668e4f)
Location: drivers/usb/core/hub.c:2965
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_port_resume
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81696b6f)
Location: drivers/usb/core/hub.c:2891
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_port_resume
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff816abe19)
Location: drivers/usb/core/hub.c:2919
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_port_resume
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81717279)
Location: drivers/usb/core/hub.c:2922
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_port_resume
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff817560db)
Location: drivers/usb/core/hub.c:2966
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_port_resume
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
In drivers/usb/core/hub.c (ffffffff8177a5c6)
Location: drivers/usb/core/hub.c:2989
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_port_resume
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
In drivers/usb/core/hub.c (ffffffff817b8104)
Location: drivers/usb/core/hub.c:3029
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_port_resume
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
In drivers/usb/core/hub.c (ffffffff817e88d9)
Location: drivers/usb/core/hub.c:3073
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_port_resume
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int check_port_resume_type(struct usb_device *udev, struct usb_hub *hub, int port1, int status, u16 portchange, u16 portstatus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff818b50f0)
Location: drivers/usb/core/hub.c:3078
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_port_resume
```
**Symbols:**

```
ffffffff818b50f0-ffffffff818b5317: check_port_resume_type (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int check_port_resume_type(struct usb_device *udev, struct usb_hub *hub, int port1, int status, u16 portchange, u16 portstatus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff818c3a50)
Location: drivers/usb/core/hub.c:3096
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_port_resume
```
**Symbols:**

```
ffffffff818c3a50-ffffffff818c3c63: check_port_resume_type (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int check_port_resume_type(struct usb_device *udev, struct usb_hub *hub, int port1, int status, u16 portchange, u16 portstatus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff818a6bc0)
Location: drivers/usb/core/hub.c:3151
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_port_resume
```
**Symbols:**

```
ffffffff818a6bc0-ffffffff818a6de2: check_port_resume_type (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int check_port_resume_type(struct usb_device *udev, struct usb_hub *hub, int port1, int status, u16 portchange, u16 portstatus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff8193ba50)
Location: drivers/usb/core/hub.c:3155
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_port_resume
```
**Symbols:**

```
ffffffff8193ba50-ffffffff8193bc77: check_port_resume_type (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int check_port_resume_type(struct usb_device *udev, struct usb_hub *hub, int port1, int status, u16 portchange, u16 portstatus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81a93740)
Location: drivers/usb/core/hub.c:3161
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_port_resume
```
**Symbols:**

```
ffffffff81a93740-ffffffff81a93968: check_port_resume_type (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int check_port_resume_type(struct usb_device *udev, struct usb_hub *hub, int port1, int status, u16 portchange, u16 portstatus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81c15980)
Location: drivers/usb/core/hub.c:3180
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_port_resume
```
**Symbols:**

```
ffffffff81c15980-ffffffff81c15ba8: check_port_resume_type (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int check_port_resume_type(struct usb_device *udev, struct usb_hub *hub, int port1, int status, u16 portchange, u16 portstatus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81c7c790)
Location: drivers/usb/core/hub.c:3200
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_port_resume
```
**Symbols:**

```
ffffffff81c7c790-ffffffff81c7c9b8: check_port_resume_type (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int check_port_resume_type(struct usb_device *udev, struct usb_hub *hub, int port1, int status, u16 portchange, u16 portstatus);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81d313e0)
Location: drivers/usb/core/hub.c:3202
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_port_resume
```
**Symbols:**

```
ffffffff81d313e0-ffffffff81d31608: check_port_resume_type (STB_LOCAL)
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
In drivers/usb/core/hub.c (ffff800010a17f1c)
Location: drivers/usb/core/hub.c:3073
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_port_resume
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
In drivers/usb/core/hub.c (c0aeffb8)
Location: drivers/usb/core/hub.c:3073
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_port_resume
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
In drivers/usb/core/hub.c (c000000000ad0e40)
Location: drivers/usb/core/hub.c:3073
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_port_resume
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
In drivers/usb/core/hub.c (ffffffe00063ccca)
Location: drivers/usb/core/hub.c:3073
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_port_resume
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
In drivers/usb/core/hub.c (ffffffff817a0cb9)
Location: drivers/usb/core/hub.c:3073
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_port_resume
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
In drivers/usb/core/hub.c (ffffffff81792af9)
Location: drivers/usb/core/hub.c:3073
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_port_resume
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
In drivers/usb/core/hub.c (ffffffff817dd759)
Location: drivers/usb/core/hub.c:3073
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_port_resume
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
In drivers/usb/core/hub.c (ffffffff817f7a29)
Location: drivers/usb/core/hub.c:3073
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_port_resume
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
