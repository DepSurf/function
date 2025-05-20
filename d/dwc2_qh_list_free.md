# Function: <code>dwc2_qh_list_free</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void dwc2_qh_list_free(struct dwc2_hsotg *hsotg, struct list_head *qh_list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff81629f60)
Location: drivers/usb/dwc2/hcd.c:143
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
```
**Symbols:**

```
ffffffff81629f60-ffffffff8162a08d: dwc2_qh_list_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void dwc2_qh_list_free(struct dwc2_hsotg *hsotg, struct list_head *qh_list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff81689e50)
Location: drivers/usb/dwc2/hcd.c:1722
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
```
**Symbols:**

```
ffffffff81689e50-ffffffff81689fa3: dwc2_qh_list_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void dwc2_qh_list_free(struct dwc2_hsotg *hsotg, struct list_head *qh_list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff816b7fc0)
Location: drivers/usb/dwc2/hcd.c:1752
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
```
**Symbols:**

```
ffffffff816b7fc0-ffffffff816b8113: dwc2_qh_list_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff816cc3e8)
Location: drivers/usb/dwc2/hcd.c:1769
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
```
**Symbols:**

```
ffffffff816cc280-ffffffff816cc3cb: dwc2_qh_list_free.part.48 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff81738968)
Location: drivers/usb/dwc2/hcd.c:1775
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
```
**Symbols:**

```
ffffffff81738800-ffffffff8173894b: dwc2_qh_list_free.part.49 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff81778998)
Location: drivers/usb/dwc2/hcd.c:1819
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
```
**Symbols:**

```
ffffffff81778820-ffffffff81778972: dwc2_qh_list_free.part.53 (STB_LOCAL)
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
In drivers/usb/dwc2/hcd.c (ffffffff8179e948)
Location: drivers/usb/dwc2/hcd.c:1809
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_release
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_release
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_release
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_release
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_release
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_release
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_release
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_release
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_release
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_release
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_release
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_release
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_release
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_release
```
**Symbols:**

```
ffffffff8179e7b0-ffffffff8179e902: dwc2_qh_list_free.part.48 (STB_LOCAL)
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
In drivers/usb/dwc2/hcd.c (ffffffff817dd546)
Location: drivers/usb/dwc2/hcd.c:1619
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_release
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_release
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_release
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_release
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_release
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_release
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_release
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_release
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_release
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_release
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_release
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_release
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_release
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_release
```
**Symbols:**

```
ffffffff817dd3b0-ffffffff817dd50c: dwc2_qh_list_free.part.0 (STB_LOCAL)
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
In drivers/usb/dwc2/hcd.c (ffffffff8180e476)
Location: drivers/usb/dwc2/hcd.c:1619
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_release
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_release
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_release
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_release
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_release
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_release
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_release
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_release
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_release
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_release
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_release
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_release
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_release
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_release
```
**Symbols:**

```
ffffffff8180e2e0-ffffffff8180e43c: dwc2_qh_list_free.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff818df0f6)
Location: drivers/usb/dwc2/hcd.c:1619
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
```
**Symbols:**

```
ffffffff818def80-ffffffff818df0dc: dwc2_qh_list_free.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff818e8f56)
Location: drivers/usb/dwc2/hcd.c:1620
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
```
**Symbols:**

```
ffffffff818e8de0-ffffffff818e8f3c: dwc2_qh_list_free.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff818caa36)
Location: drivers/usb/dwc2/hcd.c:1618
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
```
**Symbols:**

```
ffffffff818ca8c0-ffffffff818caa1c: dwc2_qh_list_free.part.0 (STB_LOCAL)
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
In drivers/usb/dwc2/hcd.c (ffffffff81963bd8)
Location: drivers/usb/dwc2/hcd.c:1618
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
```
**Symbols:**

```
ffffffff81963a60-ffffffff81963bbc: dwc2_qh_list_free.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff81abe0ec)
Location: drivers/usb/dwc2/hcd.c:1614
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
```
**Symbols:**

```
ffffffff81abdf60-ffffffff81abe0ca: dwc2_qh_list_free.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff81c4785c)
Location: drivers/usb/dwc2/hcd.c:1585
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
```
**Symbols:**

```
ffffffff81c476c0-ffffffff81c4782a: dwc2_qh_list_free.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff81caee3c)
Location: drivers/usb/dwc2/hcd.c:1585
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
```
**Symbols:**

```
ffffffff81caeca0-ffffffff81caee0a: dwc2_qh_list_free.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff81d63aec)
Location: drivers/usb/dwc2/hcd.c:1585
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
```
**Symbols:**

```
ffffffff81d63950-ffffffff81d63aba: dwc2_qh_list_free.part.0 (STB_LOCAL)
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
In drivers/usb/dwc2/hcd.c (ffff800010a46fdc)
Location: drivers/usb/dwc2/hcd.c:1619
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
```
**Symbols:**

```
ffff800010a46dc8-ffff800010a46fb8: dwc2_qh_list_free.part.0 (STB_LOCAL)
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
In drivers/usb/dwc2/hcd.c (c0b19680)
Location: drivers/usb/dwc2/hcd.c:1619
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
```
**Symbols:**

```
c0b1951c-c0b1964c: dwc2_qh_list_free.part.0 (STB_LOCAL)
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
In drivers/usb/dwc2/hcd.c (c000000000b0b894)
Location: drivers/usb/dwc2/hcd.c:1619
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
```
**Symbols:**

```
c000000000b0b670-c000000000b0b848: dwc2_qh_list_free.part.0 (STB_LOCAL)
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
In drivers/usb/dwc2/hcd.c (ffffffe0006639ae)
Location: drivers/usb/dwc2/hcd.c:1619
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_free
```
**Symbols:**

```
ffffffe000663856-ffffffe000663976: dwc2_qh_list_free.part.0 (STB_LOCAL)
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
In drivers/usb/dwc2/hcd.c (ffffffff817c6856)
Location: drivers/usb/dwc2/hcd.c:1619
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_release
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_release
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_release
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_release
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_release
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_release
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_release
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_release
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_release
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_release
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_release
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_release
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_release
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_release
```
**Symbols:**

```
ffffffff817c66c0-ffffffff817c681c: dwc2_qh_list_free.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff818032f6)
Location: drivers/usb/dwc2/hcd.c:1619
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_release
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_release
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_release
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_release
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_release
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_release
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_release
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_release
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_release
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_release
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_release
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_release
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_release
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_release
```
**Symbols:**

```
ffffffff81803160-ffffffff818032bc: dwc2_qh_list_free.part.0 (STB_LOCAL)
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
In drivers/usb/dwc2/hcd.c (ffffffff8181d406)
Location: drivers/usb/dwc2/hcd.c:1619
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_release
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_release
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_release
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_release
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_release
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_release
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_release
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_release
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_release
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_release
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_release
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_release
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_release
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_release
```
**Symbols:**

```
ffffffff8181d270-ffffffff8181d3cc: dwc2_qh_list_free.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
</ul>
