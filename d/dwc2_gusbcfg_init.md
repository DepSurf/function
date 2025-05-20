# Function: <code>dwc2_gusbcfg_init</code>

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
In drivers/usb/dwc2/core.c (ffffffff81622455)
Location: drivers/usb/dwc2/core.c:729
Inline: True
Inline callers:
  - drivers/usb/dwc2/core.c:dwc2_core_init
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
In drivers/usb/dwc2/hcd.c (ffffffff81685d46)
Location: drivers/usb/dwc2/hcd.c:310
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
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
In drivers/usb/dwc2/hcd.c (ffffffff816b3f94)
Location: drivers/usb/dwc2/hcd.c:311
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
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
In drivers/usb/dwc2/hcd.c (ffffffff816c833f)
Location: drivers/usb/dwc2/hcd.c:327
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
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
In drivers/usb/dwc2/hcd.c (ffffffff81734815)
Location: drivers/usb/dwc2/hcd.c:333
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
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
In drivers/usb/dwc2/hcd.c (ffffffff81776680)
Location: drivers/usb/dwc2/hcd.c:324
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
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
In drivers/usb/dwc2/hcd.c (ffffffff8179c16b)
Location: drivers/usb/dwc2/hcd.c:324
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
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
In drivers/usb/dwc2/hcd.c (ffffffff817db19b)
Location: drivers/usb/dwc2/hcd.c:134
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
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
In drivers/usb/dwc2/hcd.c (ffffffff8180c0bb)
Location: drivers/usb/dwc2/hcd.c:134
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void dwc2_gusbcfg_init(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff818d93d0)
Location: drivers/usb/dwc2/hcd.c:134
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
```
**Symbols:**

```
ffffffff818d93d0-ffffffff818d9468: dwc2_gusbcfg_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void dwc2_gusbcfg_init(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff818e3320)
Location: drivers/usb/dwc2/hcd.c:134
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
```
**Symbols:**

```
ffffffff818e3320-ffffffff818e33b8: dwc2_gusbcfg_init (STB_LOCAL)
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
In drivers/usb/dwc2/hcd.c (ffffffff818c8e03)
Location: drivers/usb/dwc2/hcd.c:132
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
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
In drivers/usb/dwc2/hcd.c (ffffffff819619f1)
Location: drivers/usb/dwc2/hcd.c:132
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
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
In drivers/usb/dwc2/hcd.c (ffffffff81abbe37)
Location: drivers/usb/dwc2/hcd.c:132
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
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
In drivers/usb/dwc2/hcd.c (ffffffff81c453d4)
Location: drivers/usb/dwc2/hcd.c:103
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
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
In drivers/usb/dwc2/hcd.c (ffffffff81cac9d1)
Location: drivers/usb/dwc2/hcd.c:103
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
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
In drivers/usb/dwc2/hcd.c (ffffffff81d61681)
Location: drivers/usb/dwc2/hcd.c:103
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
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
In drivers/usb/dwc2/hcd.c (ffff800010a447dc)
Location: drivers/usb/dwc2/hcd.c:134
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
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
In drivers/usb/dwc2/hcd.c (c0b16f80)
Location: drivers/usb/dwc2/hcd.c:134
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
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
In drivers/usb/dwc2/hcd.c (c000000000b07804)
Location: drivers/usb/dwc2/hcd.c:134
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
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
In drivers/usb/dwc2/hcd.c (ffffffe000660f72)
Location: drivers/usb/dwc2/hcd.c:134
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
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
In drivers/usb/dwc2/hcd.c (ffffffff817c449b)
Location: drivers/usb/dwc2/hcd.c:134
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff81800f3b)
Location: drivers/usb/dwc2/hcd.c:134
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
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
In drivers/usb/dwc2/hcd.c (ffffffff8181b04b)
Location: drivers/usb/dwc2/hcd.c:134
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_core_init
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
