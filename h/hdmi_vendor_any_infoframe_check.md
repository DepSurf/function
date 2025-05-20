# Function: <code>hdmi_vendor_any_infoframe_check</code>

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
int hdmi_vendor_any_infoframe_check(union hdmi_vendor_any_infoframe *frame);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/hdmi.c (ffffffff81565660)
Location: drivers/video/hdmi.c:657
Inline: False
Direct callers:
  - drivers/video/hdmi.c:hdmi_infoframe_pack
  - drivers/video/hdmi.c:hdmi_infoframe_check
```
**Symbols:**

```
ffffffff81565660-ffffffff8156568d: hdmi_vendor_any_infoframe_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int hdmi_vendor_any_infoframe_check(union hdmi_vendor_any_infoframe *frame);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/hdmi.c (ffffffff81595a40)
Location: drivers/video/hdmi.c:801
Inline: False
Direct callers:
  - drivers/video/hdmi.c:hdmi_infoframe_pack
  - drivers/video/hdmi.c:hdmi_infoframe_check
```
**Symbols:**

```
ffffffff81595a40-ffffffff81595a6d: hdmi_vendor_any_infoframe_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int hdmi_vendor_any_infoframe_check(union hdmi_vendor_any_infoframe *frame);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/hdmi.c (ffffffff815b6cc0)
Location: drivers/video/hdmi.c:801
Inline: False
Direct callers:
  - drivers/video/hdmi.c:hdmi_infoframe_pack
```
**Symbols:**

```
ffffffff815b6cc0-ffffffff815b6ced: hdmi_vendor_any_infoframe_check (STB_LOCAL)
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
In drivers/video/hdmi.c (ffffffff816617d3)
Location: drivers/video/hdmi.c:797
Inline: True
Inline callers:
  - drivers/video/hdmi.c:hdmi_infoframe_pack
  - drivers/video/hdmi.c:hdmi_infoframe_check
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/video/hdmi.c (ffffffff81682bd3)
Location: drivers/video/hdmi.c:801
Inline: True
Inline callers:
  - drivers/video/hdmi.c:hdmi_infoframe_pack
  - drivers/video/hdmi.c:hdmi_infoframe_check
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
In drivers/video/hdmi.c (ffffffff816659e7)
Location: drivers/video/hdmi.c:801
Inline: True
Inline callers:
  - drivers/video/hdmi.c:hdmi_infoframe_pack
  - drivers/video/hdmi.c:hdmi_infoframe_check
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
In drivers/video/hdmi.c (ffffffff816d89e7)
Location: drivers/video/hdmi.c:801
Inline: True
Inline callers:
  - drivers/video/hdmi.c:hdmi_infoframe_pack
  - drivers/video/hdmi.c:hdmi_infoframe_check
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
In drivers/video/hdmi.c (ffffffff8180295d)
Location: drivers/video/hdmi.c:801
Inline: True
Inline callers:
  - drivers/video/hdmi.c:hdmi_infoframe_pack
  - drivers/video/hdmi.c:hdmi_infoframe_check
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
In drivers/video/hdmi.c (ffffffff819306ed)
Location: drivers/video/hdmi.c:845
Inline: True
Inline callers:
  - drivers/video/hdmi.c:hdmi_infoframe_pack
  - drivers/video/hdmi.c:hdmi_infoframe_check
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
In drivers/video/hdmi.c (ffffffff81974b35)
Location: drivers/video/hdmi.c:845
Inline: True
Inline callers:
  - drivers/video/hdmi.c:hdmi_infoframe_pack
  - drivers/video/hdmi.c:hdmi_infoframe_check
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
In drivers/video/hdmi.c (ffffffff819beba5)
Location: drivers/video/hdmi.c:845
Inline: True
Inline callers:
  - drivers/video/hdmi.c:hdmi_infoframe_pack
  - drivers/video/hdmi.c:hdmi_infoframe_check
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
int hdmi_vendor_any_infoframe_check(union hdmi_vendor_any_infoframe *frame);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/hdmi.c (ffff80001073f5a8)
Location: drivers/video/hdmi.c:801
Inline: False
Direct callers:
  - drivers/video/hdmi.c:hdmi_infoframe_pack
  - drivers/video/hdmi.c:hdmi_infoframe_check
```
**Symbols:**

```
ffff80001073f5a8-ffff80001073f600: hdmi_vendor_any_infoframe_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int hdmi_vendor_any_infoframe_check(union hdmi_vendor_any_infoframe *frame);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/hdmi.c (c08c4328)
Location: drivers/video/hdmi.c:801
Inline: False
Direct callers:
  - drivers/video/hdmi.c:hdmi_infoframe_pack
```
**Symbols:**

```
c08c4328-c08c4374: hdmi_vendor_any_infoframe_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int hdmi_vendor_any_infoframe_check(union hdmi_vendor_any_infoframe *frame);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/hdmi.c (c000000000899100)
Location: drivers/video/hdmi.c:801
Inline: False
Direct callers:
  - drivers/video/hdmi.c:hdmi_infoframe_pack
  - drivers/video/hdmi.c:hdmi_infoframe_check
```
**Symbols:**

```
c000000000899100-c000000000899148: hdmi_vendor_any_infoframe_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int hdmi_vendor_any_infoframe_check(union hdmi_vendor_any_infoframe *frame);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/hdmi.c (ffffffe0004eea6e)
Location: drivers/video/hdmi.c:801
Inline: False
Direct callers:
  - drivers/video/hdmi.c:hdmi_infoframe_pack
  - drivers/video/hdmi.c:hdmi_infoframe_check
```
**Symbols:**

```
ffffffe0004eea6e-ffffffe0004eeabc: hdmi_vendor_any_infoframe_check (STB_LOCAL)
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
int hdmi_vendor_any_infoframe_check(union hdmi_vendor_any_infoframe *frame);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/hdmi.c (ffffffff815aaf30)
Location: drivers/video/hdmi.c:801
Inline: False
Direct callers:
  - drivers/video/hdmi.c:hdmi_infoframe_pack
```
**Symbols:**

```
ffffffff815aaf30-ffffffff815aaf5d: hdmi_vendor_any_infoframe_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int hdmi_vendor_any_infoframe_check(union hdmi_vendor_any_infoframe *frame);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/hdmi.c (ffffffff8159a0d0)
Location: drivers/video/hdmi.c:801
Inline: False
Direct callers:
  - drivers/video/hdmi.c:hdmi_infoframe_pack
```
**Symbols:**

```
ffffffff8159a0d0-ffffffff8159a0fd: hdmi_vendor_any_infoframe_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int hdmi_vendor_any_infoframe_check(union hdmi_vendor_any_infoframe *frame);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/hdmi.c (ffffffff815ab4c0)
Location: drivers/video/hdmi.c:801
Inline: False
Direct callers:
  - drivers/video/hdmi.c:hdmi_infoframe_pack
```
**Symbols:**

```
ffffffff815ab4c0-ffffffff815ab4ed: hdmi_vendor_any_infoframe_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int hdmi_vendor_any_infoframe_check(union hdmi_vendor_any_infoframe *frame);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/hdmi.c (ffffffff815c4e50)
Location: drivers/video/hdmi.c:801
Inline: False
Direct callers:
  - drivers/video/hdmi.c:hdmi_infoframe_pack
```
**Symbols:**

```
ffffffff815c4e50-ffffffff815c4e7d: hdmi_vendor_any_infoframe_check (STB_LOCAL)
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
