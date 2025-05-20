# Function: <code>device_links_purge</code>

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
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff815c7482)
Location: drivers/base/core.c:587
Inline: True
Inline callers:
  - drivers/base/core.c:device_del
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
In drivers/base/core.c (ffffffff815dc160)
Location: drivers/base/core.c:588
Inline: True
Inline callers:
  - drivers/base/core.c:device_del
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
In drivers/base/core.c (ffffffff81643269)
Location: drivers/base/core.c:591
Inline: True
Inline callers:
  - drivers/base/core.c:device_del
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
In drivers/base/core.c (ffffffff8167e3a3)
Location: drivers/base/core.c:624
Inline: True
Inline callers:
  - drivers/base/core.c:device_del
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
In drivers/base/core.c (ffffffff8169ddc0)
Location: drivers/base/core.c:666
Inline: True
Inline callers:
  - drivers/base/core.c:device_del
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
In drivers/base/core.c (ffffffff816d61ad)
Location: drivers/base/core.c:811
Inline: True
Inline callers:
  - drivers/base/core.c:device_del
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
In drivers/base/core.c (ffffffff816fa1ea)
Location: drivers/base/core.c:848
Inline: True
Inline callers:
  - drivers/base/core.c:device_del
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void device_links_purge(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff817b1c20)
Location: drivers/base/core.c:1159
Inline: False
Direct callers:
  - drivers/base/core.c:device_del
```
**Symbols:**

```
ffffffff817b1c20-ffffffff817b1d39: device_links_purge (STB_LOCAL)
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
In drivers/base/core.c (ffffffff817c7c41)
Location: drivers/base/core.c:1433
Inline: True
Inline callers:
  - drivers/base/core.c:device_del
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
In drivers/base/core.c (ffffffff817ab151)
Location: drivers/base/core.c:1515
Inline: True
Inline callers:
  - drivers/base/core.c:device_del
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
In drivers/base/core.c (ffffffff818344b8)
Location: drivers/base/core.c:1530
Inline: True
Inline callers:
  - drivers/base/core.c:device_del
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
In drivers/base/core.c (ffffffff81975f76)
Location: drivers/base/core.c:1542
Inline: True
Inline callers:
  - drivers/base/core.c:device_del
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
In drivers/base/core.c (ffffffff81ae2026)
Location: drivers/base/core.c:1670
Inline: True
Inline callers:
  - drivers/base/core.c:device_del
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
In drivers/base/core.c (ffffffff81b2ff25)
Location: drivers/base/core.c:1609
Inline: True
Inline callers:
  - drivers/base/core.c:device_del
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
In drivers/base/core.c (ffffffff81b87725)
Location: drivers/base/core.c:1612
Inline: True
Inline callers:
  - drivers/base/core.c:device_del
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
In drivers/base/core.c (ffff8000108e49d4)
Location: drivers/base/core.c:848
Inline: True
Inline callers:
  - drivers/base/core.c:device_del
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
In drivers/base/core.c (c09d33f4)
Location: drivers/base/core.c:848
Inline: True
Inline callers:
  - drivers/base/core.c:device_del
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
In drivers/base/core.c (c000000000979e70)
Location: drivers/base/core.c:848
Inline: True
Inline callers:
  - drivers/base/core.c:device_del
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
In drivers/base/core.c (ffffffe000579852)
Location: drivers/base/core.c:848
Inline: True
Inline callers:
  - drivers/base/core.c:device_del
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
In drivers/base/core.c (ffffffff816bf9da)
Location: drivers/base/core.c:848
Inline: True
Inline callers:
  - drivers/base/core.c:device_del
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
In drivers/base/core.c (ffffffff8169ac8a)
Location: drivers/base/core.c:848
Inline: True
Inline callers:
  - drivers/base/core.c:device_del
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
In drivers/base/core.c (ffffffff816edeaa)
Location: drivers/base/core.c:848
Inline: True
Inline callers:
  - drivers/base/core.c:device_del
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
In drivers/base/core.c (ffffffff817086ea)
Location: drivers/base/core.c:848
Inline: True
Inline callers:
  - drivers/base/core.c:device_del
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
