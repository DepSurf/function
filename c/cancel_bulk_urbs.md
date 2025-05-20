# Function: <code>cancel_bulk_urbs</code>

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
In drivers/usb/core/devio.c (ffffffff8161b543)
Location: drivers/usb/core/devio.c:451
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:async_completed
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
In drivers/usb/core/devio.c (ffffffff8167b037)
Location: drivers/usb/core/devio.c:561
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:async_completed
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
In drivers/usb/core/devio.c (ffffffff816a8cf7)
Location: drivers/usb/core/devio.c:561
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:async_completed
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
In drivers/usb/core/devio.c (ffffffff816be07c)
Location: drivers/usb/core/devio.c:555
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:async_completed
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
In drivers/usb/core/devio.c (ffffffff81729a4c)
Location: drivers/usb/core/devio.c:545
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:async_completed
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
In drivers/usb/core/devio.c (ffffffff81768e72)
Location: drivers/usb/core/devio.c:543
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:async_completed
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
In drivers/usb/core/devio.c (ffffffff8178cf25)
Location: drivers/usb/core/devio.c:543
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:async_completed
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
In drivers/usb/core/devio.c (ffffffff817cb113)
Location: drivers/usb/core/devio.c:541
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:async_completed
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
In drivers/usb/core/devio.c (ffffffff817fbd13)
Location: drivers/usb/core/devio.c:553
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:async_completed
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void cancel_bulk_urbs(struct usb_dev_state *ps, unsigned int bulk_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devio.c (ffffffff818cb820)
Location: drivers/usb/core/devio.c:562
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:async_completed
```
**Symbols:**

```
ffffffff818cb820-ffffffff818cb8df: cancel_bulk_urbs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void cancel_bulk_urbs(struct usb_dev_state *ps, unsigned int bulk_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/devio.c (ffffffff818d6910)
Location: drivers/usb/core/devio.c:562
Inline: False
Direct callers:
  - drivers/usb/core/devio.c:async_completed
```
**Symbols:**

```
ffffffff818d6910-ffffffff818d69cf: cancel_bulk_urbs (STB_LOCAL)
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
In drivers/usb/core/devio.c (ffffffff818bbb61)
Location: drivers/usb/core/devio.c:562
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:async_completed
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
In drivers/usb/core/devio.c (ffffffff81952195)
Location: drivers/usb/core/devio.c:563
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:async_completed
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
In drivers/usb/core/devio.c (ffffffff81aa9478)
Location: drivers/usb/core/devio.c:575
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:async_completed
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
In drivers/usb/core/devio.c (ffffffff81c30758)
Location: drivers/usb/core/devio.c:575
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:async_completed
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
In drivers/usb/core/devio.c (ffffffff81c979f8)
Location: drivers/usb/core/devio.c:582
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:async_completed
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
In drivers/usb/core/devio.c (ffffffff81d4c4d9)
Location: drivers/usb/core/devio.c:582
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:async_completed
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
In drivers/usb/core/devio.c (ffff800010a2d75c)
Location: drivers/usb/core/devio.c:553
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:async_completed
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
In drivers/usb/core/devio.c (c0b02770)
Location: drivers/usb/core/devio.c:553
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:async_completed
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
In drivers/usb/core/devio.c (c000000000aeadec)
Location: drivers/usb/core/devio.c:553
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:async_completed
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
In drivers/usb/core/devio.c (ffffffe00064f5c6)
Location: drivers/usb/core/devio.c:553
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:async_completed
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
In drivers/usb/core/devio.c (ffffffff817b40f3)
Location: drivers/usb/core/devio.c:553
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:async_completed
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
In drivers/usb/core/devio.c (ffffffff817a5b23)
Location: drivers/usb/core/devio.c:553
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:async_completed
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
In drivers/usb/core/devio.c (ffffffff817f0b93)
Location: drivers/usb/core/devio.c:553
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:async_completed
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
In drivers/usb/core/devio.c (ffffffff8180add3)
Location: drivers/usb/core/devio.c:553
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:async_completed
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
