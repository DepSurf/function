# Function: <code>hdmi_vendor_any_infoframe_log</code>

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
In drivers/video/hdmi.c (ffffffff8145ce7a)
Location: drivers/video/hdmi.c:938
Inline: True
Inline callers:
  - drivers/video/hdmi.c:hdmi_infoframe_log
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
In drivers/video/hdmi.c (ffffffff814ab04a)
Location: drivers/video/hdmi.c:938
Inline: True
Inline callers:
  - drivers/video/hdmi.c:hdmi_infoframe_log
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
In drivers/video/hdmi.c (ffffffff814cd15a)
Location: drivers/video/hdmi.c:942
Inline: True
Inline callers:
  - drivers/video/hdmi.c:hdmi_infoframe_log
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
In drivers/video/hdmi.c (ffffffff814d8f47)
Location: drivers/video/hdmi.c:942
Inline: True
Inline callers:
  - drivers/video/hdmi.c:hdmi_infoframe_log
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
In drivers/video/hdmi.c (ffffffff81519177)
Location: drivers/video/hdmi.c:947
Inline: True
Inline callers:
  - drivers/video/hdmi.c:hdmi_infoframe_log
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
In drivers/video/hdmi.c (ffffffff8154ecaf)
Location: drivers/video/hdmi.c:950
Inline: True
Inline callers:
  - drivers/video/hdmi.c:hdmi_infoframe_log
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
In drivers/video/hdmi.c (ffffffff8156629f)
Location: drivers/video/hdmi.c:1323
Inline: True
Inline callers:
  - drivers/video/hdmi.c:hdmi_infoframe_log
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
In drivers/video/hdmi.c (ffffffff81596cdf)
Location: drivers/video/hdmi.c:1480
Inline: True
Inline callers:
  - drivers/video/hdmi.c:hdmi_infoframe_log
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
In drivers/video/hdmi.c (ffffffff815b7f5d)
Location: drivers/video/hdmi.c:1480
Inline: True
Inline callers:
  - drivers/video/hdmi.c:hdmi_infoframe_log
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void hdmi_vendor_any_infoframe_log(const char *level, struct device *dev, const union hdmi_vendor_any_infoframe *frame);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/hdmi.c (ffffffff81661cb9)
Location: drivers/video/hdmi.c:1476
Inline: False
Direct callers:
  - drivers/video/hdmi.c:hdmi_infoframe_log
```
**Symbols:**

```
ffffffff81661cb9-ffffffff81661d8e: hdmi_vendor_any_infoframe_log (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void hdmi_vendor_any_infoframe_log(const char *level, struct device *dev, const union hdmi_vendor_any_infoframe *frame);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/hdmi.c (ffffffff81bfe601)
Location: drivers/video/hdmi.c:1480
Inline: False
Direct callers:
  - drivers/video/hdmi.c:hdmi_infoframe_log
```
**Symbols:**

```
ffffffff81bfe601-ffffffff81bfe6d6: hdmi_vendor_any_infoframe_log (STB_LOCAL)
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
In drivers/video/hdmi.c (ffffffff81bf0466)
Location: drivers/video/hdmi.c:1480
Inline: True
Inline callers:
  - drivers/video/hdmi.c:hdmi_infoframe_log
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
In drivers/video/hdmi.c (ffffffff81cebbcb)
Location: drivers/video/hdmi.c:1480
Inline: True
Inline callers:
  - drivers/video/hdmi.c:hdmi_infoframe_log
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
In drivers/video/hdmi.c (ffffffff81eb301b)
Location: drivers/video/hdmi.c:1480
Inline: True
Inline callers:
  - drivers/video/hdmi.c:hdmi_infoframe_log
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
In drivers/video/hdmi.c (ffffffff81930df1)
Location: drivers/video/hdmi.c:1524
Inline: True
Inline callers:
  - drivers/video/hdmi.c:hdmi_infoframe_log
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
In drivers/video/hdmi.c (ffffffff81975241)
Location: drivers/video/hdmi.c:1524
Inline: True
Inline callers:
  - drivers/video/hdmi.c:hdmi_infoframe_log
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
In drivers/video/hdmi.c (ffffffff819bf2b1)
Location: drivers/video/hdmi.c:1524
Inline: True
Inline callers:
  - drivers/video/hdmi.c:hdmi_infoframe_log
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
In drivers/video/hdmi.c (ffff8000107407b4)
Location: drivers/video/hdmi.c:1480
Inline: True
Inline callers:
  - drivers/video/hdmi.c:hdmi_infoframe_log
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
In drivers/video/hdmi.c (c08c5684)
Location: drivers/video/hdmi.c:1480
Inline: True
Inline callers:
  - drivers/video/hdmi.c:hdmi_infoframe_log
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
In drivers/video/hdmi.c (c00000000089a79c)
Location: drivers/video/hdmi.c:1480
Inline: True
Inline callers:
  - drivers/video/hdmi.c:hdmi_infoframe_log
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
In drivers/video/hdmi.c (ffffffe0004efa2c)
Location: drivers/video/hdmi.c:1480
Inline: True
Inline callers:
  - drivers/video/hdmi.c:hdmi_infoframe_log
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
In drivers/video/hdmi.c (ffffffff815ac1cd)
Location: drivers/video/hdmi.c:1480
Inline: True
Inline callers:
  - drivers/video/hdmi.c:hdmi_infoframe_log
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
In drivers/video/hdmi.c (ffffffff8159b36d)
Location: drivers/video/hdmi.c:1480
Inline: True
Inline callers:
  - drivers/video/hdmi.c:hdmi_infoframe_log
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
In drivers/video/hdmi.c (ffffffff815ac75d)
Location: drivers/video/hdmi.c:1480
Inline: True
Inline callers:
  - drivers/video/hdmi.c:hdmi_infoframe_log
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
In drivers/video/hdmi.c (ffffffff815c60ed)
Location: drivers/video/hdmi.c:1480
Inline: True
Inline callers:
  - drivers/video/hdmi.c:hdmi_infoframe_log
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
</ul>
