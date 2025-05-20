# Function: <code>pwm_device_link_add</code>

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
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pwm/core.c (ffffffff81555861)
Location: drivers/pwm/core.c:630
Inline: True
Inline callers:
  - drivers/pwm/core.c:pwm_get
  - drivers/pwm/core.c:pwm_get
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
In drivers/pwm/core.c (ffffffff81576ea1)
Location: drivers/pwm/core.c:631
Inline: True
Inline callers:
  - drivers/pwm/core.c:pwm_get
  - drivers/pwm/core.c:pwm_get
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
In drivers/pwm/core.c (ffffffff8161c2b8)
Location: drivers/pwm/core.c:759
Inline: True
Inline callers:
  - drivers/pwm/core.c:pwm_get
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
In drivers/pwm/core.c (ffffffff81642a8c)
Location: drivers/pwm/core.c:759
Inline: True
Inline callers:
  - drivers/pwm/core.c:pwm_get
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
In drivers/pwm/core.c (ffffffff816258a8)
Location: drivers/pwm/core.c:729
Inline: True
Inline callers:
  - drivers/pwm/core.c:pwm_get
  - drivers/pwm/core.c:pwm_get
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
In drivers/pwm/core.c (ffffffff81695182)
Location: drivers/pwm/core.c:717
Inline: True
Inline callers:
  - drivers/pwm/core.c:pwm_get
  - drivers/pwm/core.c:pwm_get
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
In drivers/pwm/core.c (ffffffff817b5dd8)
Location: drivers/pwm/core.c:771
Inline: True
Inline callers:
  - drivers/pwm/core.c:pwm_get
  - drivers/pwm/core.c:pwm_get
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
In drivers/pwm/core.c (ffffffff818d01a8)
Location: drivers/pwm/core.c:700
Inline: True
Inline callers:
  - drivers/pwm/core.c:pwm_get
  - drivers/pwm/core.c:pwm_get
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
In drivers/pwm/core.c (ffffffff81913138)
Location: drivers/pwm/core.c:643
Inline: True
Inline callers:
  - drivers/pwm/core.c:pwm_get
  - drivers/pwm/core.c:pwm_get
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
In drivers/pwm/core.c (ffffffff8195b074)
Location: drivers/pwm/core.c:627
Inline: True
Inline callers:
  - drivers/pwm/core.c:pwm_get
  - drivers/pwm/core.c:pwm_get
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
In drivers/pwm/core.c (ffff8000106d7c78)
Location: drivers/pwm/core.c:631
Inline: True
Direct callers:
  - drivers/pwm/core.c:pwm_get
  - drivers/pwm/core.c:of_pwm_get
```
**Symbols:**

```
ffff8000106d7c78-ffff8000106d7d04: pwm_device_link_add.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct device_link *pwm_device_link_add(struct device *dev, struct pwm_device *pwm);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pwm/core.c (c0875034)
Location: drivers/pwm/core.c:631
Inline: True
Direct callers:
  - drivers/pwm/core.c:pwm_get
  - drivers/pwm/core.c:of_pwm_get
```
**Symbols:**

```
c0875034-c08750b0: pwm_device_link_add (STB_LOCAL)
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
In drivers/pwm/core.c (c00000000084f4c0)
Location: drivers/pwm/core.c:631
Inline: True
Direct callers:
  - drivers/pwm/core.c:pwm_get
  - drivers/pwm/core.c:of_pwm_get
```
**Symbols:**

```
c00000000084f4c0-c00000000084f578: pwm_device_link_add.isra.0 (STB_LOCAL)
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
In drivers/pwm/core.c (ffffffe0004b17fc)
Location: drivers/pwm/core.c:631
Inline: True
Direct callers:
  - drivers/pwm/core.c:pwm_get
  - drivers/pwm/core.c:of_pwm_get
```
**Symbols:**

```
ffffffe0004b17fc-ffffffe0004b1872: pwm_device_link_add.isra.0 (STB_LOCAL)
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
In drivers/pwm/core.c (ffffffff8156bcb1)
Location: drivers/pwm/core.c:631
Inline: True
Inline callers:
  - drivers/pwm/core.c:pwm_get
  - drivers/pwm/core.c:pwm_get
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
In drivers/pwm/core.c (ffffffff8156abf1)
Location: drivers/pwm/core.c:631
Inline: True
Inline callers:
  - drivers/pwm/core.c:pwm_get
  - drivers/pwm/core.c:pwm_get
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
In drivers/pwm/core.c (ffffffff815850f1)
Location: drivers/pwm/core.c:631
Inline: True
Inline callers:
  - drivers/pwm/core.c:pwm_get
  - drivers/pwm/core.c:pwm_get
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
