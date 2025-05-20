# Function: <code>hdmi_vendor_infoframe_check_only</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int hdmi_vendor_infoframe_check_only(const struct hdmi_vendor_infoframe *frame);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/hdmi.c (ffffffff815655b0)
Location: drivers/video/hdmi.c:519
Inline: False
Direct callers:
  - drivers/video/hdmi.c:hdmi_vendor_infoframe_check
```
**Symbols:**

```
ffffffff815655b0-ffffffff8156561a: hdmi_vendor_infoframe_check_only (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int hdmi_vendor_infoframe_check_only(const struct hdmi_vendor_infoframe *frame);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/hdmi.c (ffffffff81595950)
Location: drivers/video/hdmi.c:519
Inline: False
Direct callers:
  - drivers/video/hdmi.c:hdmi_vendor_infoframe_check
```
**Symbols:**

```
ffffffff81595950-ffffffff815959ba: hdmi_vendor_infoframe_check_only (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int hdmi_vendor_infoframe_check_only(const struct hdmi_vendor_infoframe *frame);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/hdmi.c (ffffffff815b6bd0)
Location: drivers/video/hdmi.c:519
Inline: False
Direct callers:
  - drivers/video/hdmi.c:hdmi_vendor_infoframe_check
```
**Symbols:**

```
ffffffff815b6bd0-ffffffff815b6c3a: hdmi_vendor_infoframe_check_only (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int hdmi_vendor_infoframe_check_only(const struct hdmi_vendor_infoframe *frame);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/video/hdmi.c (ffffffff816614da)
Location: drivers/video/hdmi.c:515
Inline: True
Inline callers:
  - drivers/video/hdmi.c:hdmi_vendor_infoframe_pack
Direct callers:
  - drivers/video/hdmi.c:hdmi_vendor_infoframe_pack
```
**Symbols:**

```
ffffffff81660890-ffffffff816608fa: hdmi_vendor_infoframe_check_only (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int hdmi_vendor_infoframe_check_only(const struct hdmi_vendor_infoframe *frame);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/video/hdmi.c (ffffffff816828da)
Location: drivers/video/hdmi.c:519
Inline: True
Inline callers:
  - drivers/video/hdmi.c:hdmi_vendor_infoframe_pack
Direct callers:
  - drivers/video/hdmi.c:hdmi_vendor_infoframe_pack
```
**Symbols:**

```
ffffffff81681b50-ffffffff81681bba: hdmi_vendor_infoframe_check_only (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int hdmi_vendor_infoframe_check_only(const struct hdmi_vendor_infoframe *frame);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/video/hdmi.c (ffffffff81665718)
Location: drivers/video/hdmi.c:519
Inline: True
Inline callers:
  - drivers/video/hdmi.c:hdmi_vendor_infoframe_pack
Direct callers:
  - drivers/video/hdmi.c:hdmi_vendor_infoframe_pack
```
**Symbols:**

```
ffffffff81664970-ffffffff816649da: hdmi_vendor_infoframe_check_only (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int hdmi_vendor_infoframe_check_only(const struct hdmi_vendor_infoframe *frame);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/video/hdmi.c (ffffffff816d8718)
Location: drivers/video/hdmi.c:519
Inline: True
Inline callers:
  - drivers/video/hdmi.c:hdmi_vendor_infoframe_pack
Direct callers:
  - drivers/video/hdmi.c:hdmi_vendor_infoframe_pack
```
**Symbols:**

```
ffffffff816d7850-ffffffff816d78ba: hdmi_vendor_infoframe_check_only (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int hdmi_vendor_infoframe_check_only(const struct hdmi_vendor_infoframe *frame);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/video/hdmi.c (ffffffff818027f5)
Location: drivers/video/hdmi.c:519
Inline: True
Inline callers:
  - drivers/video/hdmi.c:hdmi_vendor_infoframe_pack
Direct callers:
  - drivers/video/hdmi.c:hdmi_vendor_infoframe_pack_only
```
**Symbols:**

```
ffffffff81801380-ffffffff818013fe: hdmi_vendor_infoframe_check_only (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int hdmi_vendor_infoframe_check_only(const struct hdmi_vendor_infoframe *frame);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/video/hdmi.c (ffffffff81930575)
Location: drivers/video/hdmi.c:563
Inline: True
Inline callers:
  - drivers/video/hdmi.c:hdmi_vendor_infoframe_pack
Direct callers:
  - drivers/video/hdmi.c:hdmi_vendor_infoframe_pack_only
```
**Symbols:**

```
ffffffff8192ef50-ffffffff8192efce: hdmi_vendor_infoframe_check_only (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int hdmi_vendor_infoframe_check_only(const struct hdmi_vendor_infoframe *frame);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/video/hdmi.c (ffffffff819749c5)
Location: drivers/video/hdmi.c:563
Inline: True
Inline callers:
  - drivers/video/hdmi.c:hdmi_vendor_infoframe_pack
Direct callers:
  - drivers/video/hdmi.c:hdmi_vendor_infoframe_pack_only
```
**Symbols:**

```
ffffffff819733c0-ffffffff8197343e: hdmi_vendor_infoframe_check_only (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int hdmi_vendor_infoframe_check_only(const struct hdmi_vendor_infoframe *frame);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/video/hdmi.c (ffffffff819bea35)
Location: drivers/video/hdmi.c:563
Inline: True
Inline callers:
  - drivers/video/hdmi.c:hdmi_vendor_infoframe_pack
Direct callers:
  - drivers/video/hdmi.c:hdmi_vendor_infoframe_pack_only
```
**Symbols:**

```
ffffffff819bd430-ffffffff819bd4ae: hdmi_vendor_infoframe_check_only (STB_LOCAL)
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
int hdmi_vendor_infoframe_check_only(const struct hdmi_vendor_infoframe *frame);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/hdmi.c (ffff80001073f460)
Location: drivers/video/hdmi.c:519
Inline: False
Direct callers:
  - drivers/video/hdmi.c:hdmi_vendor_infoframe_check
```
**Symbols:**

```
ffff80001073f460-ffff80001073f4f8: hdmi_vendor_infoframe_check_only (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int hdmi_vendor_infoframe_check_only(const struct hdmi_vendor_infoframe *frame);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/hdmi.c (c08c4204)
Location: drivers/video/hdmi.c:519
Inline: False
Direct callers:
  - drivers/video/hdmi.c:hdmi_vendor_infoframe_check
```
**Symbols:**

```
c08c4204-c08c429c: hdmi_vendor_infoframe_check_only (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int hdmi_vendor_infoframe_check_only(const struct hdmi_vendor_infoframe *frame);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/hdmi.c (c000000000898fd0)
Location: drivers/video/hdmi.c:519
Inline: False
Direct callers:
  - drivers/video/hdmi.c:hdmi_vendor_infoframe_check
  - drivers/video/hdmi.c:hdmi_vendor_infoframe_check
```
**Symbols:**

```
c000000000898fd0-c000000000899060: hdmi_vendor_infoframe_check_only (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int hdmi_vendor_infoframe_check_only(const struct hdmi_vendor_infoframe *frame);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/hdmi.c (ffffffe0004ee96c)
Location: drivers/video/hdmi.c:519
Inline: False
Direct callers:
  - drivers/video/hdmi.c:hdmi_vendor_infoframe_check
```
**Symbols:**

```
ffffffe0004ee96c-ffffffe0004ee9e0: hdmi_vendor_infoframe_check_only (STB_LOCAL)
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
int hdmi_vendor_infoframe_check_only(const struct hdmi_vendor_infoframe *frame);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/hdmi.c (ffffffff815aae40)
Location: drivers/video/hdmi.c:519
Inline: False
Direct callers:
  - drivers/video/hdmi.c:hdmi_vendor_infoframe_check
```
**Symbols:**

```
ffffffff815aae40-ffffffff815aaeaa: hdmi_vendor_infoframe_check_only (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int hdmi_vendor_infoframe_check_only(const struct hdmi_vendor_infoframe *frame);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/hdmi.c (ffffffff81599fe0)
Location: drivers/video/hdmi.c:519
Inline: False
Direct callers:
  - drivers/video/hdmi.c:hdmi_vendor_infoframe_check
```
**Symbols:**

```
ffffffff81599fe0-ffffffff8159a04a: hdmi_vendor_infoframe_check_only (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int hdmi_vendor_infoframe_check_only(const struct hdmi_vendor_infoframe *frame);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/hdmi.c (ffffffff815ab3d0)
Location: drivers/video/hdmi.c:519
Inline: False
Direct callers:
  - drivers/video/hdmi.c:hdmi_vendor_infoframe_check
```
**Symbols:**

```
ffffffff815ab3d0-ffffffff815ab43a: hdmi_vendor_infoframe_check_only (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int hdmi_vendor_infoframe_check_only(const struct hdmi_vendor_infoframe *frame);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/hdmi.c (ffffffff815c4d60)
Location: drivers/video/hdmi.c:519
Inline: False
Direct callers:
  - drivers/video/hdmi.c:hdmi_vendor_infoframe_check
```
**Symbols:**

```
ffffffff815c4d60-ffffffff815c4dca: hdmi_vendor_infoframe_check_only (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
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
