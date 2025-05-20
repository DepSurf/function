# Function: <code>hdmi_avi_infoframe_log</code>

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
In drivers/video/hdmi.c (ffffffff8145cf08)
Location: drivers/video/hdmi.c:662
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
In drivers/video/hdmi.c (ffffffff814ab0d8)
Location: drivers/video/hdmi.c:662
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
In drivers/video/hdmi.c (ffffffff814cd1e8)
Location: drivers/video/hdmi.c:666
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
In drivers/video/hdmi.c (ffffffff814d8fd5)
Location: drivers/video/hdmi.c:666
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
In drivers/video/hdmi.c (ffffffff81519205)
Location: drivers/video/hdmi.c:671
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
In drivers/video/hdmi.c (ffffffff8154edd7)
Location: drivers/video/hdmi.c:674
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
In drivers/video/hdmi.c (ffffffff815663c7)
Location: drivers/video/hdmi.c:1047
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
In drivers/video/hdmi.c (ffffffff81596adc)
Location: drivers/video/hdmi.c:1194
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
In drivers/video/hdmi.c (ffffffff815b7d5a)
Location: drivers/video/hdmi.c:1194
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
void hdmi_avi_infoframe_log(const char *level, struct device *dev, const struct hdmi_avi_infoframe *frame);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/hdmi.c (ffffffff81661fe3)
Location: drivers/video/hdmi.c:1190
Inline: False
Direct callers:
  - drivers/video/hdmi.c:hdmi_infoframe_log
```
**Symbols:**

```
ffffffff81661fe3-ffffffff81662241: hdmi_avi_infoframe_log (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void hdmi_avi_infoframe_log(const char *level, struct device *dev, const struct hdmi_avi_infoframe *frame);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/hdmi.c (ffffffff81bfe92b)
Location: drivers/video/hdmi.c:1194
Inline: False
Direct callers:
  - drivers/video/hdmi.c:hdmi_infoframe_log
```
**Symbols:**

```
ffffffff81bfe92b-ffffffff81bfeb89: hdmi_avi_infoframe_log (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void hdmi_avi_infoframe_log(const char *level, struct device *dev, const struct hdmi_avi_infoframe *frame);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/hdmi.c (ffffffff81bf01fe)
Location: drivers/video/hdmi.c:1194
Inline: False
Direct callers:
  - drivers/video/hdmi.c:hdmi_infoframe_log
```
**Symbols:**

```
ffffffff81bf01fe-ffffffff81bf045c: hdmi_avi_infoframe_log (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void hdmi_avi_infoframe_log(const char *level, struct device *dev, const struct hdmi_avi_infoframe *frame);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/hdmi.c (ffffffff81ceb945)
Location: drivers/video/hdmi.c:1194
Inline: False
Direct callers:
  - drivers/video/hdmi.c:hdmi_infoframe_log
```
**Symbols:**

```
ffffffff81ceb945-ffffffff81cebbc1: hdmi_avi_infoframe_log (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void hdmi_avi_infoframe_log(const char *level, struct device *dev, const struct hdmi_avi_infoframe *frame);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/hdmi.c (ffffffff81eb2d81)
Location: drivers/video/hdmi.c:1194
Inline: False
Direct callers:
  - drivers/video/hdmi.c:hdmi_infoframe_log
```
**Symbols:**

```
ffffffff81eb2d81-ffffffff81eb3011: hdmi_avi_infoframe_log (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void hdmi_avi_infoframe_log(const char *level, struct device *dev, const struct hdmi_avi_infoframe *frame);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/video/hdmi.c (0)
Location: drivers/video/hdmi.c:1238
Inline: False
Direct callers:
  - drivers/video/hdmi.c:hdmi_infoframe_log
```
**Symbols:**

```
ffffffff81930930-ffffffff81930c00: hdmi_avi_infoframe_log (STB_LOCAL)
ffffffff82090328-ffffffff8209033d: hdmi_avi_infoframe_log.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void hdmi_avi_infoframe_log(const char *level, struct device *dev, const struct hdmi_avi_infoframe *frame);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/video/hdmi.c (0)
Location: drivers/video/hdmi.c:1238
Inline: False
Direct callers:
  - drivers/video/hdmi.c:hdmi_infoframe_log
```
**Symbols:**

```
ffffffff81974d80-ffffffff81975050: hdmi_avi_infoframe_log (STB_LOCAL)
ffffffff82110688-ffffffff8211069d: hdmi_avi_infoframe_log.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void hdmi_avi_infoframe_log(const char *level, struct device *dev, const struct hdmi_avi_infoframe *frame);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/video/hdmi.c (0)
Location: drivers/video/hdmi.c:1238
Inline: False
Direct callers:
  - drivers/video/hdmi.c:hdmi_infoframe_log
```
**Symbols:**

```
ffffffff819bedf0-ffffffff819bf0c0: hdmi_avi_infoframe_log (STB_LOCAL)
ffffffff821ee485-ffffffff821ee49a: hdmi_avi_infoframe_log.cold (STB_LOCAL)
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
In drivers/video/hdmi.c (ffff800010740580)
Location: drivers/video/hdmi.c:1194
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
In drivers/video/hdmi.c (c08c53ec)
Location: drivers/video/hdmi.c:1194
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
In drivers/video/hdmi.c (c00000000089a51c)
Location: drivers/video/hdmi.c:1194
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
In drivers/video/hdmi.c (ffffffe0004efc2c)
Location: drivers/video/hdmi.c:1194
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
In drivers/video/hdmi.c (ffffffff815abfca)
Location: drivers/video/hdmi.c:1194
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
In drivers/video/hdmi.c (ffffffff8159b16a)
Location: drivers/video/hdmi.c:1194
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
In drivers/video/hdmi.c (ffffffff815ac55a)
Location: drivers/video/hdmi.c:1194
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
In drivers/video/hdmi.c (ffffffff815c5eea)
Location: drivers/video/hdmi.c:1194
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
