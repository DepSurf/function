# Function: <code>dwc2_drd_suspend</code>

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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void dwc2_drd_suspend(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/drd.c (ffffffff818e2210)
Location: drivers/usb/dwc2/drd.c:150
Inline: False
Direct callers:
  - drivers/usb/dwc2/platform.c:dwc2_suspend
```
**Symbols:**

```
ffffffff818e2210-ffffffff818e227b: dwc2_drd_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void dwc2_drd_suspend(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/drd.c (ffffffff818c5520)
Location: drivers/usb/dwc2/drd.c:150
Inline: False
Direct callers:
  - drivers/usb/dwc2/platform.c:dwc2_suspend
```
**Symbols:**

```
ffffffff818c5520-ffffffff818c5591: dwc2_drd_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void dwc2_drd_suspend(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/drd.c (0)
Location: drivers/usb/dwc2/drd.c:172
Inline: False
Direct callers:
  - drivers/usb/dwc2/platform.c:dwc2_suspend
```
**Symbols:**

```
ffffffff81d19a40-ffffffff81d19ae1: dwc2_drd_suspend.cold (STB_LOCAL)
ffffffff8195d340-ffffffff8195d46f: dwc2_drd_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void dwc2_drd_suspend(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/drd.c (0)
Location: drivers/usb/dwc2/drd.c:194
Inline: False
Direct callers:
  - drivers/usb/dwc2/platform.c:dwc2_suspend
```
**Symbols:**

```
ffffffff81ee4a7e-ffffffff81ee4b6f: dwc2_drd_suspend.cold (STB_LOCAL)
ffffffff81ab72c0-ffffffff81ab73e5: dwc2_drd_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void dwc2_drd_suspend(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/drd.c (0)
Location: drivers/usb/dwc2/drd.c:194
Inline: False
Direct callers:
  - drivers/usb/dwc2/platform.c:dwc2_suspend
```
**Symbols:**

```
ffffffff820a0a6f-ffffffff820a0b60: dwc2_drd_suspend.cold (STB_LOCAL)
ffffffff81c3fdb0-ffffffff81c3fed5: dwc2_drd_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void dwc2_drd_suspend(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/drd.c (0)
Location: drivers/usb/dwc2/drd.c:195
Inline: False
Direct callers:
  - drivers/usb/dwc2/platform.c:dwc2_suspend
```
**Symbols:**

```
ffffffff82122037-ffffffff82122128: dwc2_drd_suspend.cold (STB_LOCAL)
ffffffff81ca7330-ffffffff81ca7455: dwc2_drd_suspend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void dwc2_drd_suspend(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/drd.c (0)
Location: drivers/usb/dwc2/drd.c:195
Inline: False
Direct callers:
  - drivers/usb/dwc2/platform.c:dwc2_suspend
```
**Symbols:**

```
ffffffff8220380e-ffffffff822038ff: dwc2_drd_suspend.cold (STB_LOCAL)
ffffffff81d5bf80-ffffffff81d5c0a5: dwc2_drd_suspend (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
