# Function: <code>hdmi_vendor_infoframe_check</code>

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
int hdmi_vendor_infoframe_check(struct hdmi_vendor_infoframe *frame);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/hdmi.c (ffffffff81565620)
Location: drivers/video/hdmi.c:545
Inline: False
Direct callers:
  - drivers/video/hdmi.c:hdmi_vendor_any_infoframe_check
  - drivers/video/hdmi.c:hdmi_vendor_infoframe_pack
```
**Symbols:**

```
ffffffff81565620-ffffffff81565657: hdmi_vendor_infoframe_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int hdmi_vendor_infoframe_check(struct hdmi_vendor_infoframe *frame);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/hdmi.c (ffffffff815959c0)
Location: drivers/video/hdmi.c:545
Inline: False
Direct callers:
  - drivers/video/hdmi.c:hdmi_vendor_any_infoframe_check
  - drivers/video/hdmi.c:hdmi_vendor_infoframe_pack
```
**Symbols:**

```
ffffffff815959c0-ffffffff815959f7: hdmi_vendor_infoframe_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int hdmi_vendor_infoframe_check(struct hdmi_vendor_infoframe *frame);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/hdmi.c (ffffffff815b6c40)
Location: drivers/video/hdmi.c:545
Inline: False
Direct callers:
  - drivers/video/hdmi.c:hdmi_vendor_any_infoframe_check
  - drivers/video/hdmi.c:hdmi_vendor_infoframe_pack
```
**Symbols:**

```
ffffffff815b6c40-ffffffff815b6c77: hdmi_vendor_infoframe_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int hdmi_vendor_infoframe_check(struct hdmi_vendor_infoframe *frame);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/video/hdmi.c (ffffffff81661495)
Location: drivers/video/hdmi.c:541
Inline: True
Inline callers:
  - drivers/video/hdmi.c:hdmi_vendor_infoframe_pack
Direct callers:
  - drivers/video/hdmi.c:hdmi_infoframe_pack
  - drivers/video/hdmi.c:hdmi_infoframe_check
```
**Symbols:**

```
ffffffff81661350-ffffffff816613e7: hdmi_vendor_infoframe_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int hdmi_vendor_infoframe_check(struct hdmi_vendor_infoframe *frame);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/video/hdmi.c (ffffffff81682895)
Location: drivers/video/hdmi.c:545
Inline: True
Inline callers:
  - drivers/video/hdmi.c:hdmi_vendor_infoframe_pack
Direct callers:
  - drivers/video/hdmi.c:hdmi_infoframe_pack
  - drivers/video/hdmi.c:hdmi_infoframe_check
```
**Symbols:**

```
ffffffff81682750-ffffffff816827e7: hdmi_vendor_infoframe_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int hdmi_vendor_infoframe_check(struct hdmi_vendor_infoframe *frame);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/video/hdmi.c (ffffffff816656d5)
Location: drivers/video/hdmi.c:545
Inline: True
Inline callers:
  - drivers/video/hdmi.c:hdmi_vendor_infoframe_pack
Direct callers:
  - drivers/video/hdmi.c:hdmi_infoframe_pack
  - drivers/video/hdmi.c:hdmi_infoframe_check
```
**Symbols:**

```
ffffffff816654d0-ffffffff8166555d: hdmi_vendor_infoframe_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int hdmi_vendor_infoframe_check(struct hdmi_vendor_infoframe *frame);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/video/hdmi.c (ffffffff816d86d5)
Location: drivers/video/hdmi.c:545
Inline: True
Inline callers:
  - drivers/video/hdmi.c:hdmi_vendor_infoframe_pack
Direct callers:
  - drivers/video/hdmi.c:hdmi_infoframe_pack
  - drivers/video/hdmi.c:hdmi_infoframe_check
```
**Symbols:**

```
ffffffff816d84d0-ffffffff816d855d: hdmi_vendor_infoframe_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int hdmi_vendor_infoframe_check(struct hdmi_vendor_infoframe *frame);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/video/hdmi.c (ffffffff818027c5)
Location: drivers/video/hdmi.c:545
Inline: True
Inline callers:
  - drivers/video/hdmi.c:hdmi_vendor_infoframe_pack
Direct callers:
  - drivers/video/hdmi.c:hdmi_infoframe_pack
  - drivers/video/hdmi.c:hdmi_infoframe_check
```
**Symbols:**

```
ffffffff81802660-ffffffff81802701: hdmi_vendor_infoframe_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int hdmi_vendor_infoframe_check(struct hdmi_vendor_infoframe *frame);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/video/hdmi.c (ffffffff81930545)
Location: drivers/video/hdmi.c:589
Inline: True
Inline callers:
  - drivers/video/hdmi.c:hdmi_vendor_infoframe_pack
Direct callers:
  - drivers/video/hdmi.c:hdmi_infoframe_pack
  - drivers/video/hdmi.c:hdmi_infoframe_check
```
**Symbols:**

```
ffffffff819303c0-ffffffff81930461: hdmi_vendor_infoframe_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int hdmi_vendor_infoframe_check(struct hdmi_vendor_infoframe *frame);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/video/hdmi.c (ffffffff81974995)
Location: drivers/video/hdmi.c:589
Inline: True
Inline callers:
  - drivers/video/hdmi.c:hdmi_vendor_infoframe_pack
Direct callers:
  - drivers/video/hdmi.c:hdmi_infoframe_pack
  - drivers/video/hdmi.c:hdmi_infoframe_check
```
**Symbols:**

```
ffffffff81974810-ffffffff819748b1: hdmi_vendor_infoframe_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int hdmi_vendor_infoframe_check(struct hdmi_vendor_infoframe *frame);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/video/hdmi.c (ffffffff819bea05)
Location: drivers/video/hdmi.c:589
Inline: True
Inline callers:
  - drivers/video/hdmi.c:hdmi_vendor_infoframe_pack
Direct callers:
  - drivers/video/hdmi.c:hdmi_infoframe_pack
  - drivers/video/hdmi.c:hdmi_infoframe_check
```
**Symbols:**

```
ffffffff819be880-ffffffff819be921: hdmi_vendor_infoframe_check (STB_GLOBAL)
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
int hdmi_vendor_infoframe_check(struct hdmi_vendor_infoframe *frame);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/hdmi.c (ffff80001073f4f8)
Location: drivers/video/hdmi.c:545
Inline: False
Direct callers:
  - drivers/video/hdmi.c:hdmi_vendor_any_infoframe_check
  - drivers/video/hdmi.c:hdmi_vendor_infoframe_pack
```
**Symbols:**

```
ffff80001073f4f8-ffff80001073f54c: hdmi_vendor_infoframe_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int hdmi_vendor_infoframe_check(struct hdmi_vendor_infoframe *frame);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/hdmi.c (c08c429c)
Location: drivers/video/hdmi.c:545
Inline: False
Direct callers:
  - drivers/video/hdmi.c:hdmi_vendor_any_infoframe_check
  - drivers/video/hdmi.c:hdmi_vendor_infoframe_pack
```
**Symbols:**

```
c08c429c-c08c42e0: hdmi_vendor_infoframe_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int hdmi_vendor_infoframe_check(struct hdmi_vendor_infoframe *frame);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/hdmi.c (c000000000899060)
Location: drivers/video/hdmi.c:545
Inline: False
Direct callers:
  - drivers/video/hdmi.c:hdmi_vendor_any_infoframe_check
  - drivers/video/hdmi.c:hdmi_vendor_infoframe_pack
```
**Symbols:**

```
c000000000899060-c0000000008990ac: hdmi_vendor_infoframe_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int hdmi_vendor_infoframe_check(struct hdmi_vendor_infoframe *frame);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/hdmi.c (ffffffe0004ee9e0)
Location: drivers/video/hdmi.c:545
Inline: False
Direct callers:
  - drivers/video/hdmi.c:hdmi_vendor_any_infoframe_check
  - drivers/video/hdmi.c:hdmi_vendor_infoframe_pack
```
**Symbols:**

```
ffffffe0004ee9e0-ffffffe0004eea2a: hdmi_vendor_infoframe_check (STB_GLOBAL)
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
int hdmi_vendor_infoframe_check(struct hdmi_vendor_infoframe *frame);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/hdmi.c (ffffffff815aaeb0)
Location: drivers/video/hdmi.c:545
Inline: False
Direct callers:
  - drivers/video/hdmi.c:hdmi_vendor_any_infoframe_check
  - drivers/video/hdmi.c:hdmi_vendor_infoframe_pack
```
**Symbols:**

```
ffffffff815aaeb0-ffffffff815aaee7: hdmi_vendor_infoframe_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int hdmi_vendor_infoframe_check(struct hdmi_vendor_infoframe *frame);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/hdmi.c (ffffffff8159a050)
Location: drivers/video/hdmi.c:545
Inline: False
Direct callers:
  - drivers/video/hdmi.c:hdmi_vendor_any_infoframe_check
  - drivers/video/hdmi.c:hdmi_vendor_infoframe_pack
```
**Symbols:**

```
ffffffff8159a050-ffffffff8159a087: hdmi_vendor_infoframe_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int hdmi_vendor_infoframe_check(struct hdmi_vendor_infoframe *frame);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/hdmi.c (ffffffff815ab440)
Location: drivers/video/hdmi.c:545
Inline: False
Direct callers:
  - drivers/video/hdmi.c:hdmi_vendor_any_infoframe_check
  - drivers/video/hdmi.c:hdmi_vendor_infoframe_pack
```
**Symbols:**

```
ffffffff815ab440-ffffffff815ab477: hdmi_vendor_infoframe_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int hdmi_vendor_infoframe_check(struct hdmi_vendor_infoframe *frame);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/hdmi.c (ffffffff815c4dd0)
Location: drivers/video/hdmi.c:545
Inline: False
Direct callers:
  - drivers/video/hdmi.c:hdmi_vendor_any_infoframe_check
  - drivers/video/hdmi.c:hdmi_vendor_infoframe_pack
```
**Symbols:**

```
ffffffff815c4dd0-ffffffff815c4e07: hdmi_vendor_infoframe_check (STB_GLOBAL)
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
