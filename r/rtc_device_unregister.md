# Function: <code>rtc_device_unregister</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void rtc_device_unregister(struct rtc_device *rtc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/class.c (ffffffff816734d0)
Location: drivers/rtc/class.c:267
Inline: False
Direct callers:
  - drivers/rtc/class.c:devm_rtc_device_release
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
  - drivers/rtc/rtc-cmos.c:cmos_do_remove
```
**Symbols:**

```
ffffffff816734d0-ffffffff81673526: rtc_device_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void rtc_device_unregister(struct rtc_device *rtc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/class.c (ffffffff816d3cc0)
Location: drivers/rtc/class.c:267
Inline: False
Direct callers:
  - drivers/rtc/class.c:devm_rtc_device_release
  - drivers/rtc/rtc-cmos.c:cmos_do_remove
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
```
**Symbols:**

```
ffffffff816d3cc0-ffffffff816d3d16: rtc_device_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void rtc_device_unregister(struct rtc_device *rtc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/class.c (ffffffff817039a0)
Location: drivers/rtc/class.c:267
Inline: False
Direct callers:
  - drivers/rtc/class.c:devm_rtc_device_release
  - drivers/rtc/rtc-cmos.c:cmos_do_remove
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
```
**Symbols:**

```
ffffffff817039a0-ffffffff817039f6: rtc_device_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void rtc_device_unregister(struct rtc_device *rtc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/class.c (ffffffff81719180)
Location: drivers/rtc/class.c:291
Inline: False
Direct callers:
  - drivers/rtc/class.c:devm_rtc_release_device
  - drivers/rtc/class.c:devm_rtc_device_release
  - drivers/rtc/rtc-cmos.c:cmos_do_remove
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
```
**Symbols:**

```
ffffffff81719180-ffffffff817191da: rtc_device_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void rtc_device_unregister(struct rtc_device *rtc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/class.c (ffffffff8178a3e0)
Location: drivers/rtc/class.c:294
Inline: False
Direct callers:
  - drivers/rtc/class.c:devm_rtc_release_device
  - drivers/rtc/class.c:devm_rtc_device_release
  - drivers/rtc/rtc-cmos.c:cmos_do_remove
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
```
**Symbols:**

```
ffffffff8178a3e0-ffffffff8178a43a: rtc_device_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void rtc_device_unregister(struct rtc_device *rtc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/class.c (ffffffff817cb4f0)
Location: drivers/rtc/class.c:363
Inline: False
Direct callers:
  - drivers/rtc/class.c:devm_rtc_release_device
  - drivers/rtc/class.c:devm_rtc_device_release
```
**Symbols:**

```
ffffffff817cb4f0-ffffffff817cb545: rtc_device_unregister (STB_GLOBAL)
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
In drivers/rtc/class.c (ffffffff817f2b70)
Location: drivers/rtc/class.c:285
Inline: True
Inline callers:
  - drivers/rtc/class.c:devm_rtc_release_device
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
In drivers/rtc/class.c (ffffffff81833843)
Location: drivers/rtc/class.c:280
Inline: True
Inline callers:
  - drivers/rtc/class.c:devm_rtc_release_device
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
In drivers/rtc/class.c (ffffffff81865183)
Location: drivers/rtc/class.c:280
Inline: True
Inline callers:
  - drivers/rtc/class.c:devm_rtc_release_device
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
In drivers/rtc/class.c (ffffffff819389d3)
Location: drivers/rtc/class.c:324
Inline: True
Inline callers:
  - drivers/rtc/class.c:devm_rtc_release_device
```
</details>
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
In drivers/rtc/class.c (ffff800010aa69ec)
Location: drivers/rtc/class.c:280
Inline: True
Inline callers:
  - drivers/rtc/class.c:devm_rtc_release_device
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
In drivers/rtc/class.c (c0b85528)
Location: drivers/rtc/class.c:280
Inline: True
Inline callers:
  - drivers/rtc/class.c:devm_rtc_release_device
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
In drivers/rtc/class.c (c000000000b8767c)
Location: drivers/rtc/class.c:280
Inline: True
Inline callers:
  - drivers/rtc/class.c:devm_rtc_release_device
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
In drivers/rtc/class.c (ffffffe0006b2cdc)
Location: drivers/rtc/class.c:280
Inline: True
Inline callers:
  - drivers/rtc/class.c:devm_rtc_release_device
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
In drivers/rtc/class.c (ffffffff81817e33)
Location: drivers/rtc/class.c:280
Inline: True
Inline callers:
  - drivers/rtc/class.c:devm_rtc_release_device
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
In drivers/rtc/class.c (ffffffff817df523)
Location: drivers/rtc/class.c:280
Inline: True
Inline callers:
  - drivers/rtc/class.c:devm_rtc_release_device
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
In drivers/rtc/class.c (ffffffff81859313)
Location: drivers/rtc/class.c:280
Inline: True
Inline callers:
  - drivers/rtc/class.c:devm_rtc_release_device
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
In drivers/rtc/class.c (ffffffff818743f3)
Location: drivers/rtc/class.c:280
Inline: True
Inline callers:
  - drivers/rtc/class.c:devm_rtc_release_device
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
</ul>
