# Function: <code>usb_dump_config</code>

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
In drivers/usb/core/devices.c (ffffffff8161e48f)
Location: drivers/usb/core/devices.c:339
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usb_device_dump
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
In drivers/usb/core/devices.c (ffffffff8167ec85)
Location: drivers/usb/core/devices.c:332
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usb_device_dump
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
In drivers/usb/core/devices.c (ffffffff816aca05)
Location: drivers/usb/core/devices.c:326
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usb_device_dump
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
In drivers/usb/core/devices.c (ffffffff816c1c5e)
Location: drivers/usb/core/devices.c:326
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usb_device_dump
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
In drivers/usb/core/devices.c (ffffffff8172da2e)
Location: drivers/usb/core/devices.c:313
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usb_device_dump
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
In drivers/usb/core/devices.c (ffffffff8176c868)
Location: drivers/usb/core/devices.c:313
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usb_device_dump
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
In drivers/usb/core/devices.c (ffffffff81790eb8)
Location: drivers/usb/core/devices.c:313
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usb_device_dump
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
In drivers/usb/core/devices.c (ffffffff817cf4e5)
Location: drivers/usb/core/devices.c:313
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usb_dump_desc
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
In drivers/usb/core/devices.c (ffffffff81800355)
Location: drivers/usb/core/devices.c:313
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usb_dump_desc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
char *usb_dump_config(int speed, char *start, char *end, const struct usb_host_config *config, int active);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devices.c (ffffffff818d0810)
Location: drivers/usb/core/devices.c:313
Inline: False
Direct callers:
  - drivers/usb/core/devices.c:usb_dump_desc
```
**Symbols:**

```
ffffffff818d0810-ffffffff818d0cf9: usb_dump_config (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
char *usb_dump_config(int speed, char *start, char *end, const struct usb_host_config *config, int active);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devices.c (ffffffff818dac70)
Location: drivers/usb/core/devices.c:294
Inline: False
Direct callers:
  - drivers/usb/core/devices.c:usb_dump_desc
```
**Symbols:**

```
ffffffff818dac70-ffffffff818db16f: usb_dump_config (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
char *usb_dump_config(int speed, char *start, char *end, const struct usb_host_config *config, int active);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devices.c (ffffffff818be0d0)
Location: drivers/usb/core/devices.c:281
Inline: False
Direct callers:
  - drivers/usb/core/devices.c:usb_dump_desc
```
**Symbols:**

```
ffffffff818be0d0-ffffffff818be53c: usb_dump_config (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
char *usb_dump_config(int speed, char *start, char *end, const struct usb_host_config *config, int active);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devices.c (ffffffff81954420)
Location: drivers/usb/core/devices.c:281
Inline: False
Direct callers:
  - drivers/usb/core/devices.c:usb_dump_desc
```
**Symbols:**

```
ffffffff81954420-ffffffff81954a88: usb_dump_config (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
char *usb_dump_config(int speed, char *start, char *end, const struct usb_host_config *config, int active);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devices.c (ffffffff81aadd50)
Location: drivers/usb/core/devices.c:279
Inline: False
Direct callers:
  - drivers/usb/core/devices.c:usb_dump_desc
```
**Symbols:**

```
ffffffff81aadd50-ffffffff81aae38a: usb_dump_config (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
char *usb_dump_config(int speed, char *start, char *end, const struct usb_host_config *config, int active);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devices.c (ffffffff81c35780)
Location: drivers/usb/core/devices.c:279
Inline: False
Direct callers:
  - drivers/usb/core/devices.c:usb_dump_desc
```
**Symbols:**

```
ffffffff81c35780-ffffffff81c35dba: usb_dump_config (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
char *usb_dump_config(int speed, char *start, char *end, const struct usb_host_config *config, int active);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devices.c (ffffffff81c9caa0)
Location: drivers/usb/core/devices.c:279
Inline: False
Direct callers:
  - drivers/usb/core/devices.c:usb_dump_desc
```
**Symbols:**

```
ffffffff81c9caa0-ffffffff81c9d0df: usb_dump_config (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
char *usb_dump_config(int speed, char *start, char *end, const struct usb_host_config *config, int active);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devices.c (ffffffff81d51650)
Location: drivers/usb/core/devices.c:279
Inline: False
Direct callers:
  - drivers/usb/core/devices.c:usb_dump_desc
```
**Symbols:**

```
ffffffff81d51650-ffffffff81d51c8f: usb_dump_config (STB_LOCAL)
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
In drivers/usb/core/devices.c (ffff800010a341d8)
Location: drivers/usb/core/devices.c:313
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usb_dump_desc
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
In drivers/usb/core/devices.c (c0b07a1c)
Location: drivers/usb/core/devices.c:313
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usb_dump_desc
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
In drivers/usb/core/devices.c (c000000000af1b60)
Location: drivers/usb/core/devices.c:313
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usb_dump_desc
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
In drivers/usb/core/devices.c (ffffffe000651e08)
Location: drivers/usb/core/devices.c:313
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usb_dump_desc
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
In drivers/usb/core/devices.c (ffffffff817b8735)
Location: drivers/usb/core/devices.c:313
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usb_dump_desc
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
In drivers/usb/core/devices.c (ffffffff817aa165)
Location: drivers/usb/core/devices.c:313
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usb_dump_desc
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
In drivers/usb/core/devices.c (ffffffff817f51d5)
Location: drivers/usb/core/devices.c:313
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usb_dump_desc
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
In drivers/usb/core/devices.c (ffffffff8180f415)
Location: drivers/usb/core/devices.c:313
Inline: True
Inline callers:
  - drivers/usb/core/devices.c:usb_dump_desc
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
