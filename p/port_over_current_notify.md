# Function: <code>port_over_current_notify</code>

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
In drivers/usb/core/hub.c (ffffffff8177baa7)
Location: drivers/usb/core/hub.c:5171
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:port_event
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
In drivers/usb/core/hub.c (ffffffff817b9400)
Location: drivers/usb/core/hub.c:5218
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:port_event
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
In drivers/usb/core/hub.c (ffffffff817e9c50)
Location: drivers/usb/core/hub.c:5263
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:port_event
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void port_over_current_notify(struct usb_port *port_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff818b2e90)
Location: drivers/usb/core/hub.c:5387
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:port_event
```
**Symbols:**

```
ffffffff818b2e90-ffffffff818b2f7a: port_over_current_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void port_over_current_notify(struct usb_port *port_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff818c1800)
Location: drivers/usb/core/hub.c:5402
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:port_event
```
**Symbols:**

```
ffffffff818c1800-ffffffff818c18ea: port_over_current_notify (STB_LOCAL)
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
In drivers/usb/core/hub.c (ffffffff818ab015)
Location: drivers/usb/core/hub.c:5526
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:port_event
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
In drivers/usb/core/hub.c (ffffffff8193ff95)
Location: drivers/usb/core/hub.c:5539
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:port_event
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
In drivers/usb/core/hub.c (ffffffff81a98156)
Location: drivers/usb/core/hub.c:5546
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:port_event
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
In drivers/usb/core/hub.c (ffffffff81c1af67)
Location: drivers/usb/core/hub.c:5556
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:port_event
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
In drivers/usb/core/hub.c (ffffffff81c81e96)
Location: drivers/usb/core/hub.c:5627
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:port_event
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
In drivers/usb/core/hub.c (ffffffff81d367d6)
Location: drivers/usb/core/hub.c:5628
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:port_event
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
In drivers/usb/core/hub.c (ffff800010a1947c)
Location: drivers/usb/core/hub.c:5263
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:port_event
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
In drivers/usb/core/hub.c (c0af16b0)
Location: drivers/usb/core/hub.c:5263
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:port_event
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
In drivers/usb/core/hub.c (c000000000ad2960)
Location: drivers/usb/core/hub.c:5263
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:port_event
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
In drivers/usb/core/hub.c (ffffffe00063dff4)
Location: drivers/usb/core/hub.c:5263
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:port_event
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
In drivers/usb/core/hub.c (ffffffff817a2030)
Location: drivers/usb/core/hub.c:5263
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:port_event
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
In drivers/usb/core/hub.c (ffffffff81793e70)
Location: drivers/usb/core/hub.c:5263
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:port_event
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
In drivers/usb/core/hub.c (ffffffff817dead0)
Location: drivers/usb/core/hub.c:5263
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:port_event
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
In drivers/usb/core/hub.c (ffffffff817f8dc0)
Location: drivers/usb/core/hub.c:5263
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:port_event
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
