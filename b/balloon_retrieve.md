# Function: <code>balloon_retrieve</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct page *balloon_retrieve(bool require_lowmem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/balloon.c (ffffffff814c63a0)
Location: drivers/xen/balloon.c:188
Inline: False
Direct callers:
  - drivers/xen/balloon.c:balloon_process
  - drivers/xen/balloon.c:alloc_xenballooned_pages
```
**Symbols:**

```
ffffffff814c63a0-ffffffff814c6405: balloon_retrieve (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/balloon.c (ffffffff81517020)
Location: drivers/xen/balloon.c:187
Inline: True
Direct callers:
  - drivers/xen/balloon.c:alloc_xenballooned_pages
  - drivers/xen/balloon.c:balloon_process
```
**Symbols:**

```
ffffffff81517020-ffffffff8151708c: balloon_retrieve.constprop.6 (STB_LOCAL)
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
In drivers/xen/balloon.c (ffffffff81543ab6)
Location: drivers/xen/balloon.c:186
Inline: True
Inline callers:
  - drivers/xen/balloon.c:alloc_xenballooned_pages
  - drivers/xen/balloon.c:balloon_process
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
In drivers/xen/balloon.c (ffffffff81557984)
Location: drivers/xen/balloon.c:187
Inline: True
Inline callers:
  - drivers/xen/balloon.c:alloc_xenballooned_pages
  - drivers/xen/balloon.c:balloon_process
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
In drivers/xen/balloon.c (ffffffff815bbac5)
Location: drivers/xen/balloon.c:187
Inline: True
Inline callers:
  - drivers/xen/balloon.c:alloc_xenballooned_pages
  - drivers/xen/balloon.c:balloon_process
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
In drivers/xen/balloon.c (ffffffff815f40a7)
Location: drivers/xen/balloon.c:187
Inline: True
Inline callers:
  - drivers/xen/balloon.c:alloc_xenballooned_pages
  - drivers/xen/balloon.c:balloon_process
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
In drivers/xen/balloon.c (ffffffff8160ef57)
Location: drivers/xen/balloon.c:181
Inline: True
Inline callers:
  - drivers/xen/balloon.c:alloc_xenballooned_pages
  - drivers/xen/balloon.c:balloon_process
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
In drivers/xen/balloon.c (ffffffff81642d39)
Location: drivers/xen/balloon.c:178
Inline: True
Inline callers:
  - drivers/xen/balloon.c:alloc_xenballooned_pages
  - drivers/xen/balloon.c:balloon_process
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
In drivers/xen/balloon.c (ffffffff816652e2)
Location: drivers/xen/balloon.c:175
Inline: True
Inline callers:
  - drivers/xen/balloon.c:alloc_xenballooned_pages
  - drivers/xen/balloon.c:balloon_process
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
In drivers/xen/balloon.c (ffffffff81714aea)
Location: drivers/xen/balloon.c:174
Inline: True
Inline callers:
  - drivers/xen/balloon.c:alloc_xenballooned_pages
  - drivers/xen/balloon.c:increase_reservation
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
In drivers/xen/balloon.c (ffffffff8173174a)
Location: drivers/xen/balloon.c:173
Inline: True
Inline callers:
  - drivers/xen/balloon.c:alloc_xenballooned_pages
  - drivers/xen/balloon.c:increase_reservation
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
In drivers/xen/balloon.c (ffffffff81715159)
Location: drivers/xen/balloon.c:173
Inline: True
Inline callers:
  - drivers/xen/balloon.c:alloc_xenballooned_pages
  - drivers/xen/balloon.c:balloon_process
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
In drivers/xen/balloon.c (ffffffff81792169)
Location: drivers/xen/balloon.c:180
Inline: True
Inline callers:
  - drivers/xen/balloon.c:alloc_xenballooned_pages
  - drivers/xen/balloon.c:balloon_thread
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
In drivers/xen/balloon.c (ffffffff818ca3ec)
Location: drivers/xen/balloon.c:182
Inline: True
Inline callers:
  - drivers/xen/balloon.c:xen_alloc_ballooned_pages
  - drivers/xen/balloon.c:balloon_thread
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
In drivers/xen/balloon.c (ffffffff81a1b92c)
Location: drivers/xen/balloon.c:182
Inline: True
Inline callers:
  - drivers/xen/balloon.c:xen_alloc_ballooned_pages
  - drivers/xen/balloon.c:balloon_thread
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
In drivers/xen/balloon.c (ffffffff81a64acc)
Location: drivers/xen/balloon.c:164
Inline: True
Inline callers:
  - drivers/xen/balloon.c:xen_alloc_ballooned_pages
  - drivers/xen/balloon.c:balloon_thread
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
In drivers/xen/balloon.c (ffffffff81ab732c)
Location: drivers/xen/balloon.c:163
Inline: True
Inline callers:
  - drivers/xen/balloon.c:xen_alloc_ballooned_pages
  - drivers/xen/balloon.c:balloon_thread
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
In drivers/xen/balloon.c (ffff80001082eab0)
Location: drivers/xen/balloon.c:175
Inline: True
Direct callers:
  - drivers/xen/balloon.c:alloc_xenballooned_pages
  - drivers/xen/balloon.c:balloon_process
```
**Symbols:**

```
ffff80001082eab0-ffff80001082eb30: balloon_retrieve.isra.0 (STB_LOCAL)
```
</details>
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
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/balloon.c (ffffffff8162af03)
Location: drivers/xen/balloon.c:175
Inline: True
Inline callers:
  - drivers/xen/balloon.c:alloc_xenballooned_pages
  - drivers/xen/balloon.c:balloon_process
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
In drivers/xen/balloon.c (ffffffff81659122)
Location: drivers/xen/balloon.c:175
Inline: True
Inline callers:
  - drivers/xen/balloon.c:alloc_xenballooned_pages
  - drivers/xen/balloon.c:balloon_process
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
In drivers/xen/balloon.c (ffffffff81673722)
Location: drivers/xen/balloon.c:175
Inline: True
Inline callers:
  - drivers/xen/balloon.c:alloc_xenballooned_pages
  - drivers/xen/balloon.c:balloon_process
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
