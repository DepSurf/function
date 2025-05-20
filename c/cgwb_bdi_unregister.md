# Function: <code>cgwb_bdi_unregister</code>

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
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff811e125c)
Location: mm/backing-dev.c:703
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
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
In mm/backing-dev.c (ffffffff811f726c)
Location: mm/backing-dev.c:718
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
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
In mm/backing-dev.c (ffffffff8121849a)
Location: mm/backing-dev.c:699
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
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
In mm/backing-dev.c (ffffffff8122b3ea)
Location: mm/backing-dev.c:702
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
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
In mm/backing-dev.c (ffffffff8123b038)
Location: mm/backing-dev.c:689
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
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
In mm/backing-dev.c (ffffffff81249559)
Location: mm/backing-dev.c:712
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void cgwb_bdi_unregister(struct backing_dev_info *bdi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff812771e0)
Location: mm/backing-dev.c:711
Inline: False
Direct callers:
  - mm/backing-dev.c:bdi_unregister
```
**Symbols:**

```
ffffffff812771e0-ffffffff81277342: cgwb_bdi_unregister (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void cgwb_bdi_unregister(struct backing_dev_info *bdi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff81281ad0)
Location: mm/backing-dev.c:611
Inline: False
Direct callers:
  - mm/backing-dev.c:bdi_unregister
```
**Symbols:**

```
ffffffff81281ad0-ffffffff81281c32: cgwb_bdi_unregister (STB_LOCAL)
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
In mm/backing-dev.c (ffffffff81286f3e)
Location: mm/backing-dev.c:610
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
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
In mm/backing-dev.c (ffffffff812c64fa)
Location: mm/backing-dev.c:633
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
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
In mm/backing-dev.c (ffffffff8132318a)
Location: mm/backing-dev.c:622
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
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
In mm/backing-dev.c (ffffffff8139799a)
Location: mm/backing-dev.c:749
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
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
In mm/backing-dev.c (ffffffff813ca92a)
Location: mm/backing-dev.c:762
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
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
In mm/backing-dev.c (ffffffff813f539a)
Location: mm/backing-dev.c:757
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
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
In mm/backing-dev.c (ffff8000102dec78)
Location: mm/backing-dev.c:712
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
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
In mm/backing-dev.c (c0503bf4)
Location: mm/backing-dev.c:712
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
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
In mm/backing-dev.c (c00000000039e59c)
Location: mm/backing-dev.c:712
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
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
In mm/backing-dev.c (ffffffe0001f6b0c)
Location: mm/backing-dev.c:712
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
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
In mm/backing-dev.c (ffffffff81241ba9)
Location: mm/backing-dev.c:712
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
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
In mm/backing-dev.c (ffffffff81234b99)
Location: mm/backing-dev.c:712
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
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
In mm/backing-dev.c (ffffffff8123f949)
Location: mm/backing-dev.c:712
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
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
In mm/backing-dev.c (ffffffff8124f0c9)
Location: mm/backing-dev.c:712
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_unregister
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
