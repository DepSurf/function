# Function: <code>hdmi_audio_infoframe_log</code>

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
In drivers/video/hdmi.c (ffffffff8145cc63)
Location: drivers/video/hdmi.c:875
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
In drivers/video/hdmi.c (ffffffff814aae33)
Location: drivers/video/hdmi.c:875
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
In drivers/video/hdmi.c (ffffffff814ccf43)
Location: drivers/video/hdmi.c:879
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
In drivers/video/hdmi.c (ffffffff814d8d33)
Location: drivers/video/hdmi.c:879
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
In drivers/video/hdmi.c (ffffffff81518f63)
Location: drivers/video/hdmi.c:884
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
In drivers/video/hdmi.c (ffffffff8154eb63)
Location: drivers/video/hdmi.c:887
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
In drivers/video/hdmi.c (ffffffff81566153)
Location: drivers/video/hdmi.c:1260
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
In drivers/video/hdmi.c (ffffffff81596e3a)
Location: drivers/video/hdmi.c:1395
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
In drivers/video/hdmi.c (ffffffff815b80b8)
Location: drivers/video/hdmi.c:1395
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
void hdmi_audio_infoframe_log(const char *level, struct device *dev, const struct hdmi_audio_infoframe *frame);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/hdmi.c (ffffffff81661d8e)
Location: drivers/video/hdmi.c:1391
Inline: False
Direct callers:
  - drivers/video/hdmi.c:hdmi_infoframe_log
```
**Symbols:**

```
ffffffff81661d8e-ffffffff81661eee: hdmi_audio_infoframe_log (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void hdmi_audio_infoframe_log(const char *level, struct device *dev, const struct hdmi_audio_infoframe *frame);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/hdmi.c (ffffffff81bfe6d6)
Location: drivers/video/hdmi.c:1395
Inline: False
Direct callers:
  - drivers/video/hdmi.c:hdmi_infoframe_log
```
**Symbols:**

```
ffffffff81bfe6d6-ffffffff81bfe836: hdmi_audio_infoframe_log (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void hdmi_audio_infoframe_log(const char *level, struct device *dev, const struct hdmi_audio_infoframe *frame);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/hdmi.c (ffffffff81bf009e)
Location: drivers/video/hdmi.c:1395
Inline: False
Direct callers:
  - drivers/video/hdmi.c:hdmi_infoframe_log
```
**Symbols:**

```
ffffffff81bf009e-ffffffff81bf01fe: hdmi_audio_infoframe_log (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void hdmi_audio_infoframe_log(const char *level, struct device *dev, const struct hdmi_audio_infoframe *frame);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/hdmi.c (ffffffff81ceb7cf)
Location: drivers/video/hdmi.c:1395
Inline: False
Direct callers:
  - drivers/video/hdmi.c:hdmi_infoframe_log
```
**Symbols:**

```
ffffffff81ceb7cf-ffffffff81ceb945: hdmi_audio_infoframe_log (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void hdmi_audio_infoframe_log(const char *level, struct device *dev, const struct hdmi_audio_infoframe *frame);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/hdmi.c (ffffffff81eb2bfa)
Location: drivers/video/hdmi.c:1395
Inline: False
Direct callers:
  - drivers/video/hdmi.c:hdmi_infoframe_log
```
**Symbols:**

```
ffffffff81eb2bfa-ffffffff81eb2d81: hdmi_audio_infoframe_log (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void hdmi_audio_infoframe_log(const char *level, struct device *dev, const struct hdmi_audio_infoframe *frame);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/video/hdmi.c (0)
Location: drivers/video/hdmi.c:1439
Inline: False
Direct callers:
  - drivers/video/hdmi.c:hdmi_infoframe_log
```
**Symbols:**

```
ffffffff81930740-ffffffff81930912: hdmi_audio_infoframe_log (STB_LOCAL)
ffffffff82090314-ffffffff82090328: hdmi_audio_infoframe_log.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void hdmi_audio_infoframe_log(const char *level, struct device *dev, const struct hdmi_audio_infoframe *frame);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/video/hdmi.c (0)
Location: drivers/video/hdmi.c:1439
Inline: False
Direct callers:
  - drivers/video/hdmi.c:hdmi_infoframe_log
```
**Symbols:**

```
ffffffff81974b90-ffffffff81974d62: hdmi_audio_infoframe_log (STB_LOCAL)
ffffffff82110674-ffffffff82110688: hdmi_audio_infoframe_log.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void hdmi_audio_infoframe_log(const char *level, struct device *dev, const struct hdmi_audio_infoframe *frame);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/video/hdmi.c (0)
Location: drivers/video/hdmi.c:1439
Inline: False
Direct callers:
  - drivers/video/hdmi.c:hdmi_infoframe_log
```
**Symbols:**

```
ffffffff819bec00-ffffffff819bedd2: hdmi_audio_infoframe_log (STB_LOCAL)
ffffffff821ee471-ffffffff821ee485: hdmi_audio_infoframe_log.cold (STB_LOCAL)
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
In drivers/video/hdmi.c (ffff800010740940)
Location: drivers/video/hdmi.c:1395
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
In drivers/video/hdmi.c (c08c529c)
Location: drivers/video/hdmi.c:1395
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
In drivers/video/hdmi.c (c00000000089a3d4)
Location: drivers/video/hdmi.c:1395
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
In drivers/video/hdmi.c (ffffffe0004efa5c)
Location: drivers/video/hdmi.c:1395
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
In drivers/video/hdmi.c (ffffffff815ac328)
Location: drivers/video/hdmi.c:1395
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
In drivers/video/hdmi.c (ffffffff8159b4c8)
Location: drivers/video/hdmi.c:1395
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
In drivers/video/hdmi.c (ffffffff815ac8b8)
Location: drivers/video/hdmi.c:1395
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
In drivers/video/hdmi.c (ffffffff815c6248)
Location: drivers/video/hdmi.c:1395
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
