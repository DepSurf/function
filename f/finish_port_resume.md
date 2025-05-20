# Function: <code>finish_port_resume</code>

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
In drivers/usb/core/hub.c (ffffffff81609344)
Location: drivers/usb/core/hub.c:3293
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
In drivers/usb/core/hub.c (ffffffff81668fac)
Location: drivers/usb/core/hub.c:3290
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
In drivers/usb/core/hub.c (ffffffff81696ccc)
Location: drivers/usb/core/hub.c:3216
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
In drivers/usb/core/hub.c (ffffffff816abfc6)
Location: drivers/usb/core/hub.c:3236
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
In drivers/usb/core/hub.c (ffffffff81717426)
Location: drivers/usb/core/hub.c:3239
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
In drivers/usb/core/hub.c (ffffffff81756541)
Location: drivers/usb/core/hub.c:3283
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
In drivers/usb/core/hub.c (ffffffff8177aa1d)
Location: drivers/usb/core/hub.c:3304
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
In drivers/usb/core/hub.c (ffffffff817b8550)
Location: drivers/usb/core/hub.c:3345
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
In drivers/usb/core/hub.c (ffffffff817e8d8a)
Location: drivers/usb/core/hub.c:3389
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
int finish_port_resume(struct usb_device *udev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff818b6950)
Location: drivers/usb/core/hub.c:3403
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_port_resume
```
**Symbols:**

```
ffffffff818b6950-ffffffff818b6b3a: finish_port_resume (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int finish_port_resume(struct usb_device *udev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff818c5260)
Location: drivers/usb/core/hub.c:3421
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_port_resume
```
**Symbols:**

```
ffffffff818c5260-ffffffff818c544a: finish_port_resume (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int finish_port_resume(struct usb_device *udev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff818a8540)
Location: drivers/usb/core/hub.c:3497
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_port_resume
```
**Symbols:**

```
ffffffff818a8540-ffffffff818a872a: finish_port_resume (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int finish_port_resume(struct usb_device *udev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff8193d420)
Location: drivers/usb/core/hub.c:3501
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_port_resume
```
**Symbols:**

```
ffffffff8193d420-ffffffff8193d601: finish_port_resume (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int finish_port_resume(struct usb_device *udev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81a95110)
Location: drivers/usb/core/hub.c:3507
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_port_resume
```
**Symbols:**

```
ffffffff81a95110-ffffffff81a95302: finish_port_resume (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int finish_port_resume(struct usb_device *udev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81c177a0)
Location: drivers/usb/core/hub.c:3526
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_port_resume
```
**Symbols:**

```
ffffffff81c177a0-ffffffff81c17992: finish_port_resume (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int finish_port_resume(struct usb_device *udev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81c7e7a0)
Location: drivers/usb/core/hub.c:3546
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_port_resume
```
**Symbols:**

```
ffffffff81c7e7a0-ffffffff81c7e992: finish_port_resume (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int finish_port_resume(struct usb_device *udev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81d33170)
Location: drivers/usb/core/hub.c:3548
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_port_resume
```
**Symbols:**

```
ffffffff81d33170-ffffffff81d33362: finish_port_resume (STB_LOCAL)
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
In drivers/usb/core/hub.c (ffff800010a1838c)
Location: drivers/usb/core/hub.c:3389
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
In drivers/usb/core/hub.c (c0af04d0)
Location: drivers/usb/core/hub.c:3389
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
In drivers/usb/core/hub.c (c000000000ad13c4)
Location: drivers/usb/core/hub.c:3389
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
In drivers/usb/core/hub.c (ffffffe00063cd82)
Location: drivers/usb/core/hub.c:3389
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
In drivers/usb/core/hub.c (ffffffff817a116a)
Location: drivers/usb/core/hub.c:3389
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
In drivers/usb/core/hub.c (ffffffff81792faa)
Location: drivers/usb/core/hub.c:3389
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
In drivers/usb/core/hub.c (ffffffff817ddc0a)
Location: drivers/usb/core/hub.c:3389
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
In drivers/usb/core/hub.c (ffffffff817f7eda)
Location: drivers/usb/core/hub.c:3389
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
