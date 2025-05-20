# Function: <code>usb_put_invalidate_rhdev</code>

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
In drivers/usb/core/hcd.c (ffffffff8160da6e)
Location: drivers/usb/core/hcd.c:2687
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
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
In drivers/usb/core/hcd.c (ffffffff8166d626)
Location: drivers/usb/core/hcd.c:2691
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
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
In drivers/usb/core/hcd.c (ffffffff8169b326)
Location: drivers/usb/core/hcd.c:2690
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
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
In drivers/usb/core/hcd.c (ffffffff816b0689)
Location: drivers/usb/core/hcd.c:2716
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
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
In drivers/usb/core/hcd.c (ffffffff8171bca2)
Location: drivers/usb/core/hcd.c:2703
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
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
In drivers/usb/core/hcd.c (ffffffff8175a8e8)
Location: drivers/usb/core/hcd.c:2719
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
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
In drivers/usb/core/hcd.c (ffffffff8177ef18)
Location: drivers/usb/core/hcd.c:2703
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
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
In drivers/usb/core/hcd.c (ffffffff817bf070)
Location: drivers/usb/core/hcd.c:2614
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
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
In drivers/usb/core/hcd.c (ffffffff817ef9f0)
Location: drivers/usb/core/hcd.c:2613
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void usb_put_invalidate_rhdev(struct usb_hcd *hcd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff818bed10)
Location: drivers/usb/core/hcd.c:2610
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
```
**Symbols:**

```
ffffffff818bed10-ffffffff818bed50: usb_put_invalidate_rhdev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void usb_put_invalidate_rhdev(struct usb_hcd *hcd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff81c1c33d)
Location: drivers/usb/core/hcd.c:2622
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
```
**Symbols:**

```
ffffffff81c1c33d-ffffffff81c1c37d: usb_put_invalidate_rhdev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void usb_put_invalidate_rhdev(struct usb_hcd *hcd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff81c0e223)
Location: drivers/usb/core/hcd.c:2622
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
```
**Symbols:**

```
ffffffff81c0e223-ffffffff81c0e263: usb_put_invalidate_rhdev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void usb_put_invalidate_rhdev(struct usb_hcd *hcd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff81d1533b)
Location: drivers/usb/core/hcd.c:2773
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
```
**Symbols:**

```
ffffffff81d1533b-ffffffff81d1537b: usb_put_invalidate_rhdev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void usb_put_invalidate_rhdev(struct usb_hcd *hcd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hcd.c (ffffffff81edfebc)
Location: drivers/usb/core/hcd.c:2776
Inline: False
Direct callers:
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
```
**Symbols:**

```
ffffffff81edfebc-ffffffff81edff02: usb_put_invalidate_rhdev (STB_LOCAL)
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
In drivers/usb/core/hcd.c (ffffffff81c1eb74)
Location: drivers/usb/core/hcd.c:2770
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
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
In drivers/usb/core/hcd.c (ffffffff81c85a74)
Location: drivers/usb/core/hcd.c:2774
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
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
In drivers/usb/core/hcd.c (ffffffff81d3a134)
Location: drivers/usb/core/hcd.c:2749
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
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
In drivers/usb/core/hcd.c (ffff800010a1fc78)
Location: drivers/usb/core/hcd.c:2613
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
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
In drivers/usb/core/hcd.c (c0af6ec0)
Location: drivers/usb/core/hcd.c:2613
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
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
In drivers/usb/core/hcd.c (c000000000ad9e00)
Location: drivers/usb/core/hcd.c:2613
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
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
In drivers/usb/core/hcd.c (ffffffe00064308c)
Location: drivers/usb/core/hcd.c:2613
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
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
In drivers/usb/core/hcd.c (ffffffff817a7dd0)
Location: drivers/usb/core/hcd.c:2613
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
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
In drivers/usb/core/hcd.c (ffffffff817997e9)
Location: drivers/usb/core/hcd.c:2613
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
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
In drivers/usb/core/hcd.c (ffffffff817e4870)
Location: drivers/usb/core/hcd.c:2613
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
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
In drivers/usb/core/hcd.c (ffffffff817feadc)
Location: drivers/usb/core/hcd.c:2613
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:usb_remove_hcd
  - drivers/usb/core/hcd.c:usb_add_hcd
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
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
</ul>
