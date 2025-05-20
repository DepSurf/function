# Function: <code>cdrom_dvd_rw_close_write</code>

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
In drivers/cdrom/cdrom.c (ffffffff815fde2f)
Location: drivers/cdrom/cdrom.c:942
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:cdrom_release
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
In drivers/cdrom/cdrom.c (ffffffff8165ddaf)
Location: drivers/cdrom/cdrom.c:942
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:cdrom_release
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
In drivers/cdrom/cdrom.c (ffffffff8168bb9f)
Location: drivers/cdrom/cdrom.c:942
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:cdrom_release
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
In drivers/cdrom/cdrom.c (ffffffff816a0b5d)
Location: drivers/cdrom/cdrom.c:940
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:cdrom_release
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
In drivers/cdrom/cdrom.c (ffffffff8170bd4d)
Location: drivers/cdrom/cdrom.c:940
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:cdrom_release
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
In drivers/cdrom/cdrom.c (ffffffff8174b17d)
Location: drivers/cdrom/cdrom.c:940
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:cdrom_release
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
In drivers/cdrom/cdrom.c (ffffffff8176f39d)
Location: drivers/cdrom/cdrom.c:940
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:cdrom_release
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
In drivers/cdrom/cdrom.c (ffffffff817ad210)
Location: drivers/cdrom/cdrom.c:941
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:cdrom_release
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
In drivers/cdrom/cdrom.c (ffffffff817dd4f0)
Location: drivers/cdrom/cdrom.c:941
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:cdrom_release
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void cdrom_dvd_rw_close_write(struct cdrom_device_info *cdi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cdrom/cdrom.c (0)
Location: drivers/cdrom/cdrom.c:944
Inline: False
Direct callers:
  - drivers/cdrom/cdrom.c:cdrom_release
  - drivers/cdrom/cdrom.c:cdrom_release
```
**Symbols:**

```
ffffffff818abf10-ffffffff818abfb2: cdrom_dvd_rw_close_write (STB_LOCAL)
ffffffff818b0ccb-ffffffff818b0d7c: cdrom_dvd_rw_close_write.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void cdrom_dvd_rw_close_write(struct cdrom_device_info *cdi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cdrom/cdrom.c (0)
Location: drivers/cdrom/cdrom.c:944
Inline: False
Direct callers:
  - drivers/cdrom/cdrom.c:cdrom_release
  - drivers/cdrom/cdrom.c:cdrom_release
```
**Symbols:**

```
ffffffff818bab50-ffffffff818babf2: cdrom_dvd_rw_close_write (STB_LOCAL)
ffffffff81c1a4c1-ffffffff81c1a572: cdrom_dvd_rw_close_write.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void cdrom_dvd_rw_close_write(struct cdrom_device_info *cdi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cdrom/cdrom.c (0)
Location: drivers/cdrom/cdrom.c:944
Inline: False
Direct callers:
  - drivers/cdrom/cdrom.c:cdrom_release
  - drivers/cdrom/cdrom.c:cdrom_release
```
**Symbols:**

```
ffffffff8189df20-ffffffff8189dfc2: cdrom_dvd_rw_close_write (STB_LOCAL)
ffffffff81c0c3ad-ffffffff81c0c45e: cdrom_dvd_rw_close_write.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void cdrom_dvd_rw_close_write(struct cdrom_device_info *cdi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cdrom/cdrom.c (0)
Location: drivers/cdrom/cdrom.c:944
Inline: False
Direct callers:
  - drivers/cdrom/cdrom.c:cdrom_release
  - drivers/cdrom/cdrom.c:cdrom_release
```
**Symbols:**

```
ffffffff81932690-ffffffff8193274a: cdrom_dvd_rw_close_write (STB_LOCAL)
ffffffff81d12c14-ffffffff81d12cef: cdrom_dvd_rw_close_write.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void cdrom_dvd_rw_close_write(struct cdrom_device_info *cdi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cdrom/cdrom.c (0)
Location: drivers/cdrom/cdrom.c:944
Inline: False
Direct callers:
  - drivers/cdrom/cdrom.c:cdrom_release
  - drivers/cdrom/cdrom.c:cdrom_release
```
**Symbols:**

```
ffffffff81a89cd0-ffffffff81a89dae: cdrom_dvd_rw_close_write (STB_LOCAL)
ffffffff81edda90-ffffffff81eddb65: cdrom_dvd_rw_close_write.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void cdrom_dvd_rw_close_write(struct cdrom_device_info *cdi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cdrom/cdrom.c (0)
Location: drivers/cdrom/cdrom.c:944
Inline: False
Direct callers:
  - drivers/cdrom/cdrom.c:cdrom_release
  - drivers/cdrom/cdrom.c:cdrom_release
```
**Symbols:**

```
ffffffff81c10180-ffffffff81c1031c: cdrom_dvd_rw_close_write (STB_LOCAL)
ffffffff8209e5e9-ffffffff8209e613: cdrom_dvd_rw_close_write.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void cdrom_dvd_rw_close_write(struct cdrom_device_info *cdi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cdrom/cdrom.c (0)
Location: drivers/cdrom/cdrom.c:945
Inline: False
Direct callers:
  - drivers/cdrom/cdrom.c:cdrom_release
  - drivers/cdrom/cdrom.c:cdrom_release
```
**Symbols:**

```
ffffffff81c71e10-ffffffff81c71fa2: cdrom_dvd_rw_close_write (STB_LOCAL)
ffffffff8211f68c-ffffffff8211f6b6: cdrom_dvd_rw_close_write.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void cdrom_dvd_rw_close_write(struct cdrom_device_info *cdi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cdrom/cdrom.c (0)
Location: drivers/cdrom/cdrom.c:945
Inline: False
Direct callers:
  - drivers/cdrom/cdrom.c:cdrom_release
  - drivers/cdrom/cdrom.c:cdrom_release
```
**Symbols:**

```
ffffffff81d266c0-ffffffff81d26852: cdrom_dvd_rw_close_write (STB_LOCAL)
ffffffff82200e62-ffffffff82200e8c: cdrom_dvd_rw_close_write.cold (STB_LOCAL)
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
In drivers/cdrom/cdrom.c (ffff800010a0a900)
Location: drivers/cdrom/cdrom.c:941
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:cdrom_release
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
In drivers/cdrom/cdrom.c (c0ae253c)
Location: drivers/cdrom/cdrom.c:941
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:cdrom_release
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
In drivers/cdrom/cdrom.c (c000000000ac03dc)
Location: drivers/cdrom/cdrom.c:941
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:cdrom_release
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
In drivers/cdrom/cdrom.c (ffffffe0006316a4)
Location: drivers/cdrom/cdrom.c:941
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:cdrom_release
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
In drivers/cdrom/cdrom.c (ffffffff817958d0)
Location: drivers/cdrom/cdrom.c:941
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:cdrom_release
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
In drivers/cdrom/cdrom.c (ffffffff817875a0)
Location: drivers/cdrom/cdrom.c:941
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:cdrom_release
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
In drivers/cdrom/cdrom.c (ffffffff817d2370)
Location: drivers/cdrom/cdrom.c:941
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:cdrom_release
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
In drivers/cdrom/cdrom.c (ffffffff817ec610)
Location: drivers/cdrom/cdrom.c:941
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:cdrom_release
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
