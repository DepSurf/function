# Function: <code>set_port_feature</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int set_port_feature(struct usb_device *hdev, int port1, int feature);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81603bc0)
Location: drivers/usb/core/hub.c:406
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_set_lpm_timeout
  - drivers/usb/core/hub.c:usb_set_lpm_timeout
  - drivers/usb/core/hub.c:hub_port_disable
  - drivers/usb/core/hub.c:hub_port_disable
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_power_on
  - drivers/usb/core/hub.c:usb_hub_set_port_power
  - drivers/usb/core/hub.c:hub_suspend
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:hub_port_connect
```
**Symbols:**

```
ffffffff81603bc0-ffffffff81603c0a: set_port_feature (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int set_port_feature(struct usb_device *hdev, int port1, int feature);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff816638a0)
Location: drivers/usb/core/hub.c:408
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:usb_set_lpm_timeout
  - drivers/usb/core/hub.c:usb_set_lpm_timeout
  - drivers/usb/core/hub.c:hub_suspend
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_disable
  - drivers/usb/core/hub.c:hub_port_disable
  - drivers/usb/core/hub.c:hub_power_on
  - drivers/usb/core/hub.c:usb_hub_set_port_power
```
**Symbols:**

```
ffffffff816638a0-ffffffff816638ea: set_port_feature (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int set_port_feature(struct usb_device *hdev, int port1, int feature);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff816916a0)
Location: drivers/usb/core/hub.c:411
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_disable
  - drivers/usb/core/hub.c:hub_port_disable
  - drivers/usb/core/hub.c:usb_set_lpm_timeout
  - drivers/usb/core/hub.c:usb_set_lpm_timeout
  - drivers/usb/core/hub.c:hub_suspend
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_power_on
  - drivers/usb/core/hub.c:usb_hub_set_port_power
```
**Symbols:**

```
ffffffff816916a0-ffffffff816916ea: set_port_feature (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int set_port_feature(struct usb_device *hdev, int port1, int feature);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff816a6c10)
Location: drivers/usb/core/hub.c:420
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_disable
  - drivers/usb/core/hub.c:hub_port_disable
  - drivers/usb/core/hub.c:usb_set_lpm_timeout
  - drivers/usb/core/hub.c:usb_set_lpm_timeout
  - drivers/usb/core/hub.c:hub_suspend
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_power_on
  - drivers/usb/core/hub.c:usb_hub_set_port_power
```
**Symbols:**

```
ffffffff816a6c10-ffffffff816a6c46: set_port_feature (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int set_port_feature(struct usb_device *hdev, int port1, int feature);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81711fe0)
Location: drivers/usb/core/hub.c:420
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_disable
  - drivers/usb/core/hub.c:hub_port_disable
  - drivers/usb/core/hub.c:usb_set_lpm_timeout
  - drivers/usb/core/hub.c:usb_set_lpm_timeout
  - drivers/usb/core/hub.c:hub_suspend
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_power_on
```
**Symbols:**

```
ffffffff81711fe0-ffffffff81712016: set_port_feature (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int set_port_feature(struct usb_device *hdev, int port1, int feature);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81750d50)
Location: drivers/usb/core/hub.c:423
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_disable
  - drivers/usb/core/hub.c:hub_port_disable
  - drivers/usb/core/hub.c:usb_set_lpm_timeout
  - drivers/usb/core/hub.c:usb_set_lpm_timeout
  - drivers/usb/core/hub.c:hub_suspend
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_power_on
```
**Symbols:**

```
ffffffff81750d50-ffffffff81750d86: set_port_feature (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int set_port_feature(struct usb_device *hdev, int port1, int feature);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff817751b0)
Location: drivers/usb/core/hub.c:424
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_disable
  - drivers/usb/core/hub.c:hub_port_disable
  - drivers/usb/core/hub.c:usb_set_lpm_timeout
  - drivers/usb/core/hub.c:usb_set_lpm_timeout
  - drivers/usb/core/hub.c:hub_suspend
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_power_on
```
**Symbols:**

```
ffffffff817751b0-ffffffff817751e6: set_port_feature (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int set_port_feature(struct usb_device *hdev, int port1, int feature);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff817b3330)
Location: drivers/usb/core/hub.c:426
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_disable
  - drivers/usb/core/hub.c:hub_port_disable
  - drivers/usb/core/hub.c:usb_set_lpm_timeout
  - drivers/usb/core/hub.c:usb_set_lpm_timeout
  - drivers/usb/core/hub.c:usb_set_lpm_timeout
  - drivers/usb/core/hub.c:hub_suspend
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_power_on
```
**Symbols:**

```
ffffffff817b3330-ffffffff817b336a: set_port_feature (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int set_port_feature(struct usb_device *hdev, int port1, int feature);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff817e3a60)
Location: drivers/usb/core/hub.c:428
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_disable
  - drivers/usb/core/hub.c:hub_port_disable
  - drivers/usb/core/hub.c:usb_set_lpm_timeout
  - drivers/usb/core/hub.c:usb_set_lpm_timeout
  - drivers/usb/core/hub.c:usb_set_lpm_timeout
  - drivers/usb/core/hub.c:hub_suspend
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_power_on
```
**Symbols:**

```
ffffffff817e3a60-ffffffff817e3a9a: set_port_feature (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff818b89a3)
Location: drivers/usb/core/hub.c:430
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_disable
  - drivers/usb/core/hub.c:hub_port_disable
  - drivers/usb/core/hub.c:usb_set_lpm_timeout
  - drivers/usb/core/hub.c:hub_suspend
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_power_on
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff818c727b)
Location: drivers/usb/core/hub.c:430
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_disable
  - drivers/usb/core/hub.c:hub_port_disable
  - drivers/usb/core/hub.c:usb_set_lpm_timeout
  - drivers/usb/core/hub.c:hub_suspend
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_power_on
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff818aa669)
Location: drivers/usb/core/hub.c:437
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_disable
  - drivers/usb/core/hub.c:hub_port_disable
  - drivers/usb/core/hub.c:usb_set_lpm_timeout
  - drivers/usb/core/hub.c:hub_suspend
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_power_on
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff8193f598)
Location: drivers/usb/core/hub.c:437
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_disable
  - drivers/usb/core/hub.c:hub_port_disable
  - drivers/usb/core/hub.c:usb_set_lpm_timeout
  - drivers/usb/core/hub.c:hub_suspend
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_power_on
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81a977e3)
Location: drivers/usb/core/hub.c:437
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_disable
  - drivers/usb/core/hub.c:hub_port_disable
  - drivers/usb/core/hub.c:usb_set_lpm_timeout
  - drivers/usb/core/hub.c:hub_suspend
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_power_on
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81c1a37d)
Location: drivers/usb/core/hub.c:441
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_disable
  - drivers/usb/core/hub.c:hub_port_disable
  - drivers/usb/core/hub.c:usb_set_lpm_timeout
  - drivers/usb/core/hub.c:hub_suspend
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_power_on
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81c813a0)
Location: drivers/usb/core/hub.c:441
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_disable
  - drivers/usb/core/hub.c:hub_port_disable
  - drivers/usb/core/hub.c:usb_set_lpm_timeout
  - drivers/usb/core/hub.c:hub_suspend
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_power_on
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81d35dcb)
Location: drivers/usb/core/hub.c:461
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_disable
  - drivers/usb/core/hub.c:hub_port_disable
  - drivers/usb/core/hub.c:usb_set_lpm_timeout
  - drivers/usb/core/hub.c:hub_suspend
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_power_on
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
int set_port_feature(struct usb_device *hdev, int port1, int feature);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffff800010a12158)
Location: drivers/usb/core/hub.c:428
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_disable
  - drivers/usb/core/hub.c:hub_port_disable
  - drivers/usb/core/hub.c:usb_set_lpm_timeout
  - drivers/usb/core/hub.c:usb_set_lpm_timeout
  - drivers/usb/core/hub.c:usb_set_lpm_timeout
  - drivers/usb/core/hub.c:hub_suspend
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_power_on
```
**Symbols:**

```
ffff800010a12158-ffff800010a121c8: set_port_feature (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int set_port_feature(struct usb_device *hdev, int port1, int feature);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (c0aea66c)
Location: drivers/usb/core/hub.c:428
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_disable
  - drivers/usb/core/hub.c:hub_port_disable
  - drivers/usb/core/hub.c:usb_set_lpm_timeout
  - drivers/usb/core/hub.c:usb_set_lpm_timeout
  - drivers/usb/core/hub.c:usb_set_lpm_timeout
  - drivers/usb/core/hub.c:hub_suspend
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_power_on
  - drivers/usb/core/hub.c:set_port_led
```
**Symbols:**

```
c0aea66c-c0aea6c8: set_port_feature (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int set_port_feature(struct usb_device *hdev, int port1, int feature);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (c000000000ac9520)
Location: drivers/usb/core/hub.c:428
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_disable
  - drivers/usb/core/hub.c:hub_port_disable
  - drivers/usb/core/hub.c:usb_set_lpm_timeout
  - drivers/usb/core/hub.c:usb_set_lpm_timeout
  - drivers/usb/core/hub.c:hub_suspend
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_power_on
  - drivers/usb/core/hub.c:set_port_led
```
**Symbols:**

```
c000000000ac9520-c000000000ac9584: set_port_feature (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int set_port_feature(struct usb_device *hdev, int port1, int feature);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffe000637b6a)
Location: drivers/usb/core/hub.c:428
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_disable
  - drivers/usb/core/hub.c:hub_port_disable
  - drivers/usb/core/hub.c:usb_set_lpm_timeout
  - drivers/usb/core/hub.c:usb_set_lpm_timeout
  - drivers/usb/core/hub.c:hub_suspend
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_power_on
  - drivers/usb/core/hub.c:set_port_led
```
**Symbols:**

```
ffffffe000637b6a-ffffffe000637bce: set_port_feature (STB_LOCAL)
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
int set_port_feature(struct usb_device *hdev, int port1, int feature);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff8179be40)
Location: drivers/usb/core/hub.c:428
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_disable
  - drivers/usb/core/hub.c:hub_port_disable
  - drivers/usb/core/hub.c:usb_set_lpm_timeout
  - drivers/usb/core/hub.c:usb_set_lpm_timeout
  - drivers/usb/core/hub.c:usb_set_lpm_timeout
  - drivers/usb/core/hub.c:hub_suspend
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_power_on
```
**Symbols:**

```
ffffffff8179be40-ffffffff8179be7a: set_port_feature (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int set_port_feature(struct usb_device *hdev, int port1, int feature);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff8178dad0)
Location: drivers/usb/core/hub.c:428
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_disable
  - drivers/usb/core/hub.c:hub_port_disable
  - drivers/usb/core/hub.c:usb_set_lpm_timeout
  - drivers/usb/core/hub.c:usb_set_lpm_timeout
  - drivers/usb/core/hub.c:usb_set_lpm_timeout
  - drivers/usb/core/hub.c:hub_suspend
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_power_on
```
**Symbols:**

```
ffffffff8178dad0-ffffffff8178db0a: set_port_feature (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int set_port_feature(struct usb_device *hdev, int port1, int feature);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff817d88e0)
Location: drivers/usb/core/hub.c:428
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_disable
  - drivers/usb/core/hub.c:hub_port_disable
  - drivers/usb/core/hub.c:usb_set_lpm_timeout
  - drivers/usb/core/hub.c:usb_set_lpm_timeout
  - drivers/usb/core/hub.c:usb_set_lpm_timeout
  - drivers/usb/core/hub.c:hub_suspend
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_power_on
```
**Symbols:**

```
ffffffff817d88e0-ffffffff817d891a: set_port_feature (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int set_port_feature(struct usb_device *hdev, int port1, int feature);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff817f2c50)
Location: drivers/usb/core/hub.c:428
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_disable
  - drivers/usb/core/hub.c:hub_port_disable
  - drivers/usb/core/hub.c:usb_set_lpm_timeout
  - drivers/usb/core/hub.c:usb_set_lpm_timeout
  - drivers/usb/core/hub.c:usb_set_lpm_timeout
  - drivers/usb/core/hub.c:hub_suspend
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_power_on
```
**Symbols:**

```
ffffffff817f2c50-ffffffff817f2c8a: set_port_feature (STB_LOCAL)
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
