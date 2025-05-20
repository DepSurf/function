# Function: <code>report_wakeup_requests</code>

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
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff8177910f)
Location: drivers/usb/core/hub.c:3684
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_resume
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
In drivers/usb/core/hub.c (ffffffff817b6f7f)
Location: drivers/usb/core/hub.c:3727
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_resume
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
In drivers/usb/core/hub.c (ffffffff817e769f)
Location: drivers/usb/core/hub.c:3775
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_resume
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void report_wakeup_requests(struct usb_hub *hub);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff818b3730)
Location: drivers/usb/core/hub.c:3789
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_resume
```
**Symbols:**

```
ffffffff818b3730-ffffffff818b37ed: report_wakeup_requests (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void report_wakeup_requests(struct usb_hub *hub);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff818c20a0)
Location: drivers/usb/core/hub.c:3807
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_resume
```
**Symbols:**

```
ffffffff818c20a0-ffffffff818c215d: report_wakeup_requests (STB_LOCAL)
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
In drivers/usb/core/hub.c (ffffffff818a6afa)
Location: drivers/usb/core/hub.c:3883
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_resume
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
In drivers/usb/core/hub.c (ffffffff8193b987)
Location: drivers/usb/core/hub.c:3887
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_resume
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
In drivers/usb/core/hub.c (ffffffff81a93667)
Location: drivers/usb/core/hub.c:3893
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_resume
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
In drivers/usb/core/hub.c (ffffffff81c15897)
Location: drivers/usb/core/hub.c:3908
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_resume
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
In drivers/usb/core/hub.c (ffffffff81c7c6a7)
Location: drivers/usb/core/hub.c:3928
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_resume
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
In drivers/usb/core/hub.c (ffffffff81d312f7)
Location: drivers/usb/core/hub.c:3930
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_resume
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
In drivers/usb/core/hub.c (ffff800010a16680)
Location: drivers/usb/core/hub.c:3775
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_resume
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
In drivers/usb/core/hub.c (c0aee9ac)
Location: drivers/usb/core/hub.c:3775
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_resume
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
In drivers/usb/core/hub.c (c000000000acf018)
Location: drivers/usb/core/hub.c:3775
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_resume
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
In drivers/usb/core/hub.c (ffffffe00063b7d8)
Location: drivers/usb/core/hub.c:3775
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_resume
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
In drivers/usb/core/hub.c (ffffffff8179fa7f)
Location: drivers/usb/core/hub.c:3775
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_resume
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
In drivers/usb/core/hub.c (ffffffff817916ff)
Location: drivers/usb/core/hub.c:3775
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_resume
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
In drivers/usb/core/hub.c (ffffffff817dc51f)
Location: drivers/usb/core/hub.c:3775
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_resume
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
In drivers/usb/core/hub.c (ffffffff817f67af)
Location: drivers/usb/core/hub.c:3775
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_resume
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
