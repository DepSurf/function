# Function: <code>virtio_balloon_report_free_page</code>

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
In drivers/virtio/virtio_balloon.c (ffffffff8160b8fb)
Location: drivers/virtio/virtio_balloon.c:657
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:report_free_page_func
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void virtio_balloon_report_free_page(struct virtio_balloon *vb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_balloon.c (0)
Location: drivers/virtio/virtio_balloon.c:648
Inline: False
Direct callers:
  - drivers/virtio/virtio_balloon.c:report_free_page_func
```
**Symbols:**

```
ffffffff8163f5b0-ffffffff8163f7f3: virtio_balloon_report_free_page (STB_LOCAL)
ffffffff8163fa71-ffffffff8163fa9f: virtio_balloon_report_free_page.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void virtio_balloon_report_free_page(struct virtio_balloon *vb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_balloon.c (0)
Location: drivers/virtio/virtio_balloon.c:652
Inline: False
Direct callers:
  - drivers/virtio/virtio_balloon.c:report_free_page_func
```
**Symbols:**

```
ffffffff816619d0-ffffffff81661c13: virtio_balloon_report_free_page (STB_LOCAL)
ffffffff81662031-ffffffff8166205f: virtio_balloon_report_free_page.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void virtio_balloon_report_free_page(struct virtio_balloon *vb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_balloon.c (0)
Location: drivers/virtio/virtio_balloon.c:705
Inline: False
Direct callers:
  - drivers/virtio/virtio_balloon.c:report_free_page_func
```
**Symbols:**

```
ffffffff8170fbe0-ffffffff8170fd1e: virtio_balloon_report_free_page (STB_LOCAL)
ffffffff81711489-ffffffff817114b5: virtio_balloon_report_free_page.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void virtio_balloon_report_free_page(struct virtio_balloon *vb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_balloon.c (0)
Location: drivers/virtio/virtio_balloon.c:697
Inline: False
Direct callers:
  - drivers/virtio/virtio_balloon.c:report_free_page_func
```
**Symbols:**

```
ffffffff8172c950-ffffffff8172ca8e: virtio_balloon_report_free_page (STB_LOCAL)
ffffffff81c049ab-ffffffff81c049d7: virtio_balloon_report_free_page.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void virtio_balloon_report_free_page(struct virtio_balloon *vb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_balloon.c (0)
Location: drivers/virtio/virtio_balloon.c:697
Inline: False
Direct callers:
  - drivers/virtio/virtio_balloon.c:report_free_page_func
```
**Symbols:**

```
ffffffff81711920-ffffffff81711b5e: virtio_balloon_report_free_page (STB_LOCAL)
ffffffff81bf65ff-ffffffff81bf662d: virtio_balloon_report_free_page.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void virtio_balloon_report_free_page(struct virtio_balloon *vb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_balloon.c (0)
Location: drivers/virtio/virtio_balloon.c:697
Inline: False
Direct callers:
  - drivers/virtio/virtio_balloon.c:report_free_page_func
```
**Symbols:**

```
ffffffff8178e390-ffffffff8178e5ce: virtio_balloon_report_free_page (STB_LOCAL)
ffffffff81cf524e-ffffffff81cf527c: virtio_balloon_report_free_page.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void virtio_balloon_report_free_page(struct virtio_balloon *vb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_balloon.c (0)
Location: drivers/virtio/virtio_balloon.c:697
Inline: False
Direct callers:
  - drivers/virtio/virtio_balloon.c:report_free_page_func
```
**Symbols:**

```
ffffffff818c4c30-ffffffff818c4ee3: virtio_balloon_report_free_page (STB_LOCAL)
ffffffff81ebd30b-ffffffff81ebd350: virtio_balloon_report_free_page.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void virtio_balloon_report_free_page(struct virtio_balloon *vb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_balloon.c (ffffffff81a15460)
Location: drivers/virtio/virtio_balloon.c:690
Inline: False
Direct callers:
  - drivers/virtio/virtio_balloon.c:report_free_page_func
```
**Symbols:**

```
ffffffff81a15460-ffffffff81a15752: virtio_balloon_report_free_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void virtio_balloon_report_free_page(struct virtio_balloon *vb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_balloon.c (ffffffff81a5e520)
Location: drivers/virtio/virtio_balloon.c:690
Inline: False
Direct callers:
  - drivers/virtio/virtio_balloon.c:report_free_page_func
```
**Symbols:**

```
ffffffff81a5e520-ffffffff81a5e812: virtio_balloon_report_free_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void virtio_balloon_report_free_page(struct virtio_balloon *vb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_balloon.c (ffffffff81ab0c10)
Location: drivers/virtio/virtio_balloon.c:729
Inline: False
Direct callers:
  - drivers/virtio/virtio_balloon.c:report_free_page_func
```
**Symbols:**

```
ffffffff81ab0c10-ffffffff81ab0f02: virtio_balloon_report_free_page (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void virtio_balloon_report_free_page(struct virtio_balloon *vb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_balloon.c (ffff80001082a298)
Location: drivers/virtio/virtio_balloon.c:652
Inline: False
Direct callers:
  - drivers/virtio/virtio_balloon.c:report_free_page_func
```
**Symbols:**

```
ffff80001082a298-ffff80001082a56c: virtio_balloon_report_free_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void virtio_balloon_report_free_page(struct virtio_balloon *vb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_balloon.c (c09477dc)
Location: drivers/virtio/virtio_balloon.c:652
Inline: False
Direct callers:
  - drivers/virtio/virtio_balloon.c:report_free_page_func
```
**Symbols:**

```
c09477dc-c0947a3c: virtio_balloon_report_free_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void virtio_balloon_report_free_page(struct virtio_balloon *vb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_balloon.c (c0000000008d7050)
Location: drivers/virtio/virtio_balloon.c:652
Inline: False
Direct callers:
  - drivers/virtio/virtio_balloon.c:report_free_page_func
```
**Symbols:**

```
c0000000008d7050-c0000000008d73e4: virtio_balloon_report_free_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void virtio_balloon_report_free_page(struct virtio_balloon *vb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_balloon.c (ffffffe0005202c6)
Location: drivers/virtio/virtio_balloon.c:652
Inline: False
Direct callers:
  - drivers/virtio/virtio_balloon.c:report_free_page_func
```
**Symbols:**

```
ffffffe0005202c6-ffffffe000520544: virtio_balloon_report_free_page (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void virtio_balloon_report_free_page(struct virtio_balloon *vb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_balloon.c (0)
Location: drivers/virtio/virtio_balloon.c:652
Inline: False
Direct callers:
  - drivers/virtio/virtio_balloon.c:report_free_page_func
```
**Symbols:**

```
ffffffff81627840-ffffffff81627a83: virtio_balloon_report_free_page (STB_LOCAL)
ffffffff81627ea1-ffffffff81627ecf: virtio_balloon_report_free_page.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void virtio_balloon_report_free_page(struct virtio_balloon *vb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_balloon.c (0)
Location: drivers/virtio/virtio_balloon.c:652
Inline: False
Direct callers:
  - drivers/virtio/virtio_balloon.c:report_free_page_func
```
**Symbols:**

```
ffffffff8161bec0-ffffffff8161c0fd: virtio_balloon_report_free_page (STB_LOCAL)
ffffffff8161c511-ffffffff8161c53f: virtio_balloon_report_free_page.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void virtio_balloon_report_free_page(struct virtio_balloon *vb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_balloon.c (0)
Location: drivers/virtio/virtio_balloon.c:652
Inline: False
Direct callers:
  - drivers/virtio/virtio_balloon.c:report_free_page_func
```
**Symbols:**

```
ffffffff81655810-ffffffff81655a53: virtio_balloon_report_free_page (STB_LOCAL)
ffffffff81655e71-ffffffff81655e9f: virtio_balloon_report_free_page.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void virtio_balloon_report_free_page(struct virtio_balloon *vb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_balloon.c (0)
Location: drivers/virtio/virtio_balloon.c:652
Inline: False
Direct callers:
  - drivers/virtio/virtio_balloon.c:report_free_page_func
```
**Symbols:**

```
ffffffff8166ee90-ffffffff8166f0ca: virtio_balloon_report_free_page (STB_LOCAL)
ffffffff816703dd-ffffffff8167040b: virtio_balloon_report_free_page.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
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
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
