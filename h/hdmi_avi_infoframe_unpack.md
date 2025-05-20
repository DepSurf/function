# Function: <code>hdmi_avi_infoframe_unpack</code>

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
In drivers/video/hdmi.c (ffffffff8145c8f1)
Location: drivers/video/hdmi.c:1006
Inline: True
Inline callers:
  - drivers/video/hdmi.c:hdmi_infoframe_unpack
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
In drivers/video/hdmi.c (ffffffff814aaa92)
Location: drivers/video/hdmi.c:1006
Inline: True
Inline callers:
  - drivers/video/hdmi.c:hdmi_infoframe_unpack
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
In drivers/video/hdmi.c (ffffffff814ccba2)
Location: drivers/video/hdmi.c:1010
Inline: True
Inline callers:
  - drivers/video/hdmi.c:hdmi_infoframe_unpack
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
In drivers/video/hdmi.c (ffffffff814d892a)
Location: drivers/video/hdmi.c:1010
Inline: True
Inline callers:
  - drivers/video/hdmi.c:hdmi_infoframe_unpack
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
In drivers/video/hdmi.c (ffffffff81518b2e)
Location: drivers/video/hdmi.c:1015
Inline: True
Inline callers:
  - drivers/video/hdmi.c:hdmi_infoframe_unpack
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
In drivers/video/hdmi.c (ffffffff8154e7bd)
Location: drivers/video/hdmi.c:1018
Inline: True
Inline callers:
  - drivers/video/hdmi.c:hdmi_infoframe_unpack
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
In drivers/video/hdmi.c (ffffffff81565d19)
Location: drivers/video/hdmi.c:1392
Inline: True
Inline callers:
  - drivers/video/hdmi.c:hdmi_infoframe_unpack
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
In drivers/video/hdmi.c (ffffffff8159620e)
Location: drivers/video/hdmi.c:1552
Inline: True
Inline callers:
  - drivers/video/hdmi.c:hdmi_infoframe_unpack
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
In drivers/video/hdmi.c (ffffffff815b748e)
Location: drivers/video/hdmi.c:1552
Inline: True
Inline callers:
  - drivers/video/hdmi.c:hdmi_infoframe_unpack
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int hdmi_avi_infoframe_unpack(struct hdmi_avi_infoframe *frame, const void *buffer, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/hdmi.c (ffffffff81661580)
Location: drivers/video/hdmi.c:1548
Inline: False
Direct callers:
  - drivers/video/hdmi.c:hdmi_infoframe_unpack
```
**Symbols:**

```
ffffffff81661580-ffffffff81661707: hdmi_avi_infoframe_unpack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int hdmi_avi_infoframe_unpack(struct hdmi_avi_infoframe *frame, const void *buffer, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/hdmi.c (ffffffff81682980)
Location: drivers/video/hdmi.c:1552
Inline: False
Direct callers:
  - drivers/video/hdmi.c:hdmi_infoframe_unpack
```
**Symbols:**

```
ffffffff81682980-ffffffff81682b07: hdmi_avi_infoframe_unpack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int hdmi_avi_infoframe_unpack(struct hdmi_avi_infoframe *frame, const void *buffer, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/hdmi.c (ffffffff816657a0)
Location: drivers/video/hdmi.c:1552
Inline: False
Direct callers:
  - drivers/video/hdmi.c:hdmi_infoframe_unpack
```
**Symbols:**

```
ffffffff816657a0-ffffffff81665927: hdmi_avi_infoframe_unpack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int hdmi_avi_infoframe_unpack(struct hdmi_avi_infoframe *frame, const void *buffer, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/hdmi.c (ffffffff816d87a0)
Location: drivers/video/hdmi.c:1552
Inline: False
Direct callers:
  - drivers/video/hdmi.c:hdmi_infoframe_unpack
```
**Symbols:**

```
ffffffff816d87a0-ffffffff816d8927: hdmi_avi_infoframe_unpack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int hdmi_avi_infoframe_unpack(struct hdmi_avi_infoframe *frame, const void *buffer, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/hdmi.c (ffffffff81802010)
Location: drivers/video/hdmi.c:1552
Inline: False
Direct callers:
  - drivers/video/hdmi.c:hdmi_infoframe_unpack
```
**Symbols:**

```
ffffffff81802010-ffffffff8180219f: hdmi_avi_infoframe_unpack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int hdmi_avi_infoframe_unpack(struct hdmi_avi_infoframe *frame, const void *buffer, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/hdmi.c (ffffffff8192f0a0)
Location: drivers/video/hdmi.c:1596
Inline: False
Direct callers:
  - drivers/video/hdmi.c:hdmi_infoframe_unpack
```
**Symbols:**

```
ffffffff8192f0a0-ffffffff8192f22f: hdmi_avi_infoframe_unpack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int hdmi_avi_infoframe_unpack(struct hdmi_avi_infoframe *frame, const void *buffer, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/hdmi.c (ffffffff81973510)
Location: drivers/video/hdmi.c:1596
Inline: False
Direct callers:
  - drivers/video/hdmi.c:hdmi_infoframe_unpack
```
**Symbols:**

```
ffffffff81973510-ffffffff8197369f: hdmi_avi_infoframe_unpack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int hdmi_avi_infoframe_unpack(struct hdmi_avi_infoframe *frame, const void *buffer, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/hdmi.c (ffffffff819bd580)
Location: drivers/video/hdmi.c:1596
Inline: False
Direct callers:
  - drivers/video/hdmi.c:hdmi_infoframe_unpack
```
**Symbols:**

```
ffffffff819bd580-ffffffff819bd70f: hdmi_avi_infoframe_unpack (STB_LOCAL)
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
In drivers/video/hdmi.c (ffff80001073feec)
Location: drivers/video/hdmi.c:1552
Inline: True
Inline callers:
  - drivers/video/hdmi.c:hdmi_infoframe_unpack
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
In drivers/video/hdmi.c (c08c4d1c)
Location: drivers/video/hdmi.c:1552
Inline: True
Inline callers:
  - drivers/video/hdmi.c:hdmi_infoframe_unpack
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
In drivers/video/hdmi.c (c000000000899c00)
Location: drivers/video/hdmi.c:1552
Inline: True
Inline callers:
  - drivers/video/hdmi.c:hdmi_infoframe_unpack
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
In drivers/video/hdmi.c (ffffffe0004ef3ba)
Location: drivers/video/hdmi.c:1552
Inline: True
Inline callers:
  - drivers/video/hdmi.c:hdmi_infoframe_unpack
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
In drivers/video/hdmi.c (ffffffff815ab6fe)
Location: drivers/video/hdmi.c:1552
Inline: True
Inline callers:
  - drivers/video/hdmi.c:hdmi_infoframe_unpack
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
In drivers/video/hdmi.c (ffffffff8159a89e)
Location: drivers/video/hdmi.c:1552
Inline: True
Inline callers:
  - drivers/video/hdmi.c:hdmi_infoframe_unpack
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
In drivers/video/hdmi.c (ffffffff815abc8e)
Location: drivers/video/hdmi.c:1552
Inline: True
Inline callers:
  - drivers/video/hdmi.c:hdmi_infoframe_unpack
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
In drivers/video/hdmi.c (ffffffff815c561e)
Location: drivers/video/hdmi.c:1552
Inline: True
Inline callers:
  - drivers/video/hdmi.c:hdmi_infoframe_unpack
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
