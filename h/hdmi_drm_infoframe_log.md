# Function: <code>hdmi_drm_infoframe_log</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/video/hdmi.c (ffffffff81596f4a)
Location: drivers/video/hdmi.c:1422
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
In drivers/video/hdmi.c (ffffffff815b81c8)
Location: drivers/video/hdmi.c:1422
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
void hdmi_drm_infoframe_log(const char *level, struct device *dev, const struct hdmi_drm_infoframe *frame);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/hdmi.c (ffffffff81661b83)
Location: drivers/video/hdmi.c:1418
Inline: False
Direct callers:
  - drivers/video/hdmi.c:hdmi_infoframe_log
```
**Symbols:**

```
ffffffff81661b83-ffffffff81661cb9: hdmi_drm_infoframe_log (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void hdmi_drm_infoframe_log(const char *level, struct device *dev, const struct hdmi_drm_infoframe *frame);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/hdmi.c (ffffffff81bfe4cb)
Location: drivers/video/hdmi.c:1422
Inline: False
Direct callers:
  - drivers/video/hdmi.c:hdmi_infoframe_log
```
**Symbols:**

```
ffffffff81bfe4cb-ffffffff81bfe601: hdmi_drm_infoframe_log (STB_LOCAL)
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
In drivers/video/hdmi.c (ffffffff81bf061c)
Location: drivers/video/hdmi.c:1422
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
In drivers/video/hdmi.c (ffffffff81cebd81)
Location: drivers/video/hdmi.c:1422
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
In drivers/video/hdmi.c (ffffffff81eb31d6)
Location: drivers/video/hdmi.c:1422
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
In drivers/video/hdmi.c (ffffffff81930c65)
Location: drivers/video/hdmi.c:1466
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
In drivers/video/hdmi.c (ffffffff819750b5)
Location: drivers/video/hdmi.c:1466
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
In drivers/video/hdmi.c (ffffffff819bf125)
Location: drivers/video/hdmi.c:1466
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
In drivers/video/hdmi.c (ffff800010740a70)
Location: drivers/video/hdmi.c:1422
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
In drivers/video/hdmi.c (c08c5138)
Location: drivers/video/hdmi.c:1422
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
In drivers/video/hdmi.c (c00000000089a7c8)
Location: drivers/video/hdmi.c:1422
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
In drivers/video/hdmi.c (ffffffe0004ef8ea)
Location: drivers/video/hdmi.c:1422
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
In drivers/video/hdmi.c (ffffffff815ac438)
Location: drivers/video/hdmi.c:1422
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
In drivers/video/hdmi.c (ffffffff8159b5d8)
Location: drivers/video/hdmi.c:1422
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
In drivers/video/hdmi.c (ffffffff815ac9c8)
Location: drivers/video/hdmi.c:1422
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
In drivers/video/hdmi.c (ffffffff815c6358)
Location: drivers/video/hdmi.c:1422
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
