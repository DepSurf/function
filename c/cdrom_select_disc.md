# Function: <code>cdrom_select_disc</code>

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
In drivers/cdrom/cdrom.c (ffffffff81602984)
Location: drivers/cdrom/cdrom.c:1404
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:cdrom_ioctl
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
In drivers/cdrom/cdrom.c (ffffffff81662667)
Location: drivers/cdrom/cdrom.c:1404
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:cdrom_ioctl
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
In drivers/cdrom/cdrom.c (ffffffff81690457)
Location: drivers/cdrom/cdrom.c:1404
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:cdrom_ioctl
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
In drivers/cdrom/cdrom.c (ffffffff816a5992)
Location: drivers/cdrom/cdrom.c:1402
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:cdrom_ioctl
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
In drivers/cdrom/cdrom.c (ffffffff81710d4c)
Location: drivers/cdrom/cdrom.c:1402
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:cdrom_ioctl
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
In drivers/cdrom/cdrom.c (ffffffff8174eb17)
Location: drivers/cdrom/cdrom.c:1399
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:cdrom_ioctl
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
In drivers/cdrom/cdrom.c (ffffffff81773657)
Location: drivers/cdrom/cdrom.c:1399
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:cdrom_ioctl
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
In drivers/cdrom/cdrom.c (ffffffff817b15fe)
Location: drivers/cdrom/cdrom.c:1400
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:cdrom_ioctl
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
In drivers/cdrom/cdrom.c (ffffffff817e194e)
Location: drivers/cdrom/cdrom.c:1407
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:cdrom_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int cdrom_select_disc(struct cdrom_device_info *cdi, int slot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff818aec20)
Location: drivers/cdrom/cdrom.c:1410
Inline: False
Direct callers:
  - drivers/cdrom/cdrom.c:cdrom_ioctl_select_disc
  - drivers/cdrom/cdrom.c:cdrom_ioctl_select_disc
```
**Symbols:**

```
ffffffff818aec20-ffffffff818aed9c: cdrom_select_disc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int cdrom_select_disc(struct cdrom_device_info *cdi, int slot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff818bd9c0)
Location: drivers/cdrom/cdrom.c:1410
Inline: False
Direct callers:
  - drivers/cdrom/cdrom.c:cdrom_ioctl_select_disc
  - drivers/cdrom/cdrom.c:cdrom_ioctl_select_disc
```
**Symbols:**

```
ffffffff818bd9c0-ffffffff818bdb1e: cdrom_select_disc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int cdrom_select_disc(struct cdrom_device_info *cdi, int slot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff818a05c0)
Location: drivers/cdrom/cdrom.c:1410
Inline: False
Direct callers:
  - drivers/cdrom/cdrom.c:cdrom_ioctl
```
**Symbols:**

```
ffffffff818a05c0-ffffffff818a071e: cdrom_select_disc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int cdrom_select_disc(struct cdrom_device_info *cdi, int slot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cdrom/cdrom.c (0)
Location: drivers/cdrom/cdrom.c:1410
Inline: False
Direct callers:
  - drivers/cdrom/cdrom.c:cdrom_ioctl
```
**Symbols:**

```
ffffffff81934de0-ffffffff81934f4d: cdrom_select_disc (STB_LOCAL)
ffffffff81d131ba-ffffffff81d131cf: cdrom_select_disc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int cdrom_select_disc(struct cdrom_device_info *cdi, int slot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cdrom/cdrom.c (0)
Location: drivers/cdrom/cdrom.c:1412
Inline: False
Direct callers:
  - drivers/cdrom/cdrom.c:cdrom_ioctl
```
**Symbols:**

```
ffffffff81a8d030-ffffffff81a8d20f: cdrom_select_disc (STB_LOCAL)
ffffffff81ede04e-ffffffff81ede063: cdrom_select_disc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int cdrom_select_disc(struct cdrom_device_info *cdi, int slot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cdrom/cdrom.c (0)
Location: drivers/cdrom/cdrom.c:1412
Inline: False
Direct callers:
  - drivers/cdrom/cdrom.c:cdrom_ioctl
```
**Symbols:**

```
ffffffff81c0dda0-ffffffff81c0df7f: cdrom_select_disc (STB_LOCAL)
ffffffff8209e37f-ffffffff8209e394: cdrom_select_disc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int cdrom_select_disc(struct cdrom_device_info *cdi, int slot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cdrom/cdrom.c (0)
Location: drivers/cdrom/cdrom.c:1395
Inline: False
Direct callers:
  - drivers/cdrom/cdrom.c:cdrom_ioctl
```
**Symbols:**

```
ffffffff81c724f0-ffffffff81c726d5: cdrom_select_disc (STB_LOCAL)
ffffffff8211f75d-ffffffff8211f772: cdrom_select_disc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int cdrom_select_disc(struct cdrom_device_info *cdi, int slot);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cdrom/cdrom.c (0)
Location: drivers/cdrom/cdrom.c:1395
Inline: False
Direct callers:
  - drivers/cdrom/cdrom.c:cdrom_ioctl
```
**Symbols:**

```
ffffffff81d26e10-ffffffff81d27024: cdrom_select_disc (STB_LOCAL)
ffffffff82200f33-ffffffff82200f48: cdrom_select_disc.cold (STB_LOCAL)
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
In drivers/cdrom/cdrom.c (ffff800010a0f7fc)
Location: drivers/cdrom/cdrom.c:1407
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:cdrom_ioctl
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
In drivers/cdrom/cdrom.c (c0ae83b4)
Location: drivers/cdrom/cdrom.c:1407
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:cdrom_ioctl
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
In drivers/cdrom/cdrom.c (c000000000ac6754)
Location: drivers/cdrom/cdrom.c:1407
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:cdrom_ioctl
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
In drivers/cdrom/cdrom.c (ffffffe000635a14)
Location: drivers/cdrom/cdrom.c:1407
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:cdrom_ioctl
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
In drivers/cdrom/cdrom.c (ffffffff81799d2e)
Location: drivers/cdrom/cdrom.c:1407
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:cdrom_ioctl
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
In drivers/cdrom/cdrom.c (ffffffff8178b9fe)
Location: drivers/cdrom/cdrom.c:1407
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:cdrom_ioctl
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
In drivers/cdrom/cdrom.c (ffffffff817d67ce)
Location: drivers/cdrom/cdrom.c:1407
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:cdrom_ioctl
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
In drivers/cdrom/cdrom.c (ffffffff817f0a6e)
Location: drivers/cdrom/cdrom.c:1407
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:cdrom_ioctl
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
