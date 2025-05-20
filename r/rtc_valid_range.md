# Function: <code>rtc_valid_range</code>

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
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/rtc/interface.c (ffffffff817ccb20)
Location: drivers/rtc/interface.c:70
Inline: True
```
**Symbols:**

```
ffffffff817ccb20-ffffffff817ccb7c: rtc_valid_range.part.13 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/rtc/interface.c (ffffffff817f3d30)
Location: drivers/rtc/interface.c:70
Inline: True
```
**Symbols:**

```
ffffffff817f3d30-ffffffff817f3d8c: rtc_valid_range.part.9 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/rtc/interface.c (ffffffff81834a70)
Location: drivers/rtc/interface.c:67
Inline: True
```
**Symbols:**

```
ffffffff81834a70-ffffffff81834acc: rtc_valid_range.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/rtc/interface.c (ffffffff81866390)
Location: drivers/rtc/interface.c:67
Inline: True
```
**Symbols:**

```
ffffffff81866390-ffffffff818663ec: rtc_valid_range.part.0 (STB_LOCAL)
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
In drivers/rtc/interface.c (ffffffff8193a7f8)
Location: drivers/rtc/interface.c:67
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_set_alarm
  - drivers/rtc/interface.c:rtc_set_alarm
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
In drivers/rtc/interface.c (ffffffff81940bd8)
Location: drivers/rtc/interface.c:67
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_set_alarm
  - drivers/rtc/interface.c:rtc_set_alarm
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
In drivers/rtc/interface.c (ffffffff819243aa)
Location: drivers/rtc/interface.c:67
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_set_alarm
  - drivers/rtc/interface.c:rtc_set_alarm
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/rtc/interface.c (ffffffff819c77da)
Location: drivers/rtc/interface.c:67
Inline: True
Inline callers:
  - drivers/rtc/interface.c:rtc_set_alarm
Direct callers:
  - drivers/rtc/interface.c:rtc_set_alarm
```
**Symbols:**

```
ffffffff819c69a0-ffffffff819c6a2b: rtc_valid_range.part.0 (STB_LOCAL)
ffffffff81d25100-ffffffff81d25142: rtc_valid_range.part.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int rtc_valid_range(struct rtc_device *rtc, struct rtc_time *tm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/rtc/interface.c (0)
Location: drivers/rtc/interface.c:67
Inline: False
```
**Symbols:**

```
ffffffff81b275a0-ffffffff81b27649: rtc_valid_range (STB_LOCAL)
ffffffff81ef0eb4-ffffffff81ef0f27: rtc_valid_range.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int rtc_valid_range(struct rtc_device *rtc, struct rtc_time *tm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/rtc/interface.c (0)
Location: drivers/rtc/interface.c:67
Inline: False
Direct callers:
  - drivers/rtc/interface.c:rtc_set_alarm
```
**Symbols:**

```
ffffffff81cbaf60-ffffffff81cbb009: rtc_valid_range (STB_LOCAL)
ffffffff820a736a-ffffffff820a73dd: rtc_valid_range.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int rtc_valid_range(struct rtc_device *rtc, struct rtc_time *tm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/rtc/interface.c (0)
Location: drivers/rtc/interface.c:67
Inline: False
Direct callers:
  - drivers/rtc/interface.c:rtc_set_alarm
```
**Symbols:**

```
ffffffff81d22710-ffffffff81d227b9: rtc_valid_range (STB_LOCAL)
ffffffff8212876d-ffffffff821287e0: rtc_valid_range.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int rtc_valid_range(struct rtc_device *rtc, struct rtc_time *tm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/rtc/interface.c (0)
Location: drivers/rtc/interface.c:67
Inline: False
Direct callers:
  - drivers/rtc/interface.c:rtc_set_alarm
```
**Symbols:**

```
ffffffff81dd8470-ffffffff81dd8519: rtc_valid_range (STB_LOCAL)
ffffffff8220a0ff-ffffffff8220a172: rtc_valid_range.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/rtc/interface.c (ffff800010aa77d8)
Location: drivers/rtc/interface.c:67
Inline: True
```
**Symbols:**

```
ffff800010aa77d8-ffff800010aa7858: rtc_valid_range.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/rtc/interface.c (c0b869dc)
Location: drivers/rtc/interface.c:67
Inline: True
```
**Symbols:**

```
c0b869dc-c0b86a7c: rtc_valid_range.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/rtc/interface.c (c000000000b895a0)
Location: drivers/rtc/interface.c:67
Inline: True
```
**Symbols:**

```
c000000000b895a0-c000000000b89638: rtc_valid_range.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/rtc/interface.c (ffffffe0006b3904)
Location: drivers/rtc/interface.c:67
Inline: True
```
**Symbols:**

```
ffffffe0006b3904-ffffffe0006b3964: rtc_valid_range.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/rtc/interface.c (ffffffff81819040)
Location: drivers/rtc/interface.c:67
Inline: True
```
**Symbols:**

```
ffffffff81819040-ffffffff8181909c: rtc_valid_range.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/rtc/interface.c (ffffffff817e0730)
Location: drivers/rtc/interface.c:67
Inline: True
```
**Symbols:**

```
ffffffff817e0730-ffffffff817e078c: rtc_valid_range.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/rtc/interface.c (ffffffff8185a520)
Location: drivers/rtc/interface.c:67
Inline: True
```
**Symbols:**

```
ffffffff8185a520-ffffffff8185a57c: rtc_valid_range.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/rtc/interface.c (ffffffff81875600)
Location: drivers/rtc/interface.c:67
Inline: True
```
**Symbols:**

```
ffffffff81875600-ffffffff8187565c: rtc_valid_range.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
