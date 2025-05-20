# Function: <code>return_free_pages_to_mm</code>

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
<summary>In <code>5.0</code>: ✅</summary>

```c
long unsigned int return_free_pages_to_mm(struct virtio_balloon *vb, long unsigned int num_to_return);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_balloon.c (ffffffff8160b6c0)
Location: drivers/virtio/virtio_balloon.c:383
Inline: False
Direct callers:
  - drivers/virtio/virtio_balloon.c:virtio_balloon_shrinker_scan
  - drivers/virtio/virtio_balloon.c:report_free_page_func
```
**Symbols:**

```
ffffffff8160b6c0-ffffffff8160b7b4: return_free_pages_to_mm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long unsigned int return_free_pages_to_mm(struct virtio_balloon *vb, long unsigned int num_to_return);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_balloon.c (ffffffff8163f800)
Location: drivers/virtio/virtio_balloon.c:371
Inline: False
Direct callers:
  - drivers/virtio/virtio_balloon.c:virtio_balloon_shrinker_scan
  - drivers/virtio/virtio_balloon.c:report_free_page_func
```
**Symbols:**

```
ffffffff8163f800-ffffffff8163f8e0: return_free_pages_to_mm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long unsigned int return_free_pages_to_mm(struct virtio_balloon *vb, long unsigned int num_to_return);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_balloon.c (ffffffff81661c20)
Location: drivers/virtio/virtio_balloon.c:373
Inline: False
Direct callers:
  - drivers/virtio/virtio_balloon.c:remove_common
  - drivers/virtio/virtio_balloon.c:virtio_balloon_shrinker_scan
  - drivers/virtio/virtio_balloon.c:report_free_page_func
```
**Symbols:**

```
ffffffff81661c20-ffffffff81661d00: return_free_pages_to_mm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long unsigned int return_free_pages_to_mm(struct virtio_balloon *vb, long unsigned int num_to_return);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_balloon.c (ffffffff81710bf0)
Location: drivers/virtio/virtio_balloon.c:413
Inline: False
Direct callers:
  - drivers/virtio/virtio_balloon.c:remove_common
  - drivers/virtio/virtio_balloon.c:virtio_balloon_shrinker_scan
  - drivers/virtio/virtio_balloon.c:report_free_page_func
```
**Symbols:**

```
ffffffff81710bf0-ffffffff81710cd0: return_free_pages_to_mm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long unsigned int return_free_pages_to_mm(struct virtio_balloon *vb, long unsigned int num_to_return);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_balloon.c (ffffffff8172d890)
Location: drivers/virtio/virtio_balloon.c:410
Inline: False
Direct callers:
  - drivers/virtio/virtio_balloon.c:remove_common
  - drivers/virtio/virtio_balloon.c:virtio_balloon_shrinker_scan
  - drivers/virtio/virtio_balloon.c:report_free_page_func
```
**Symbols:**

```
ffffffff8172d890-ffffffff8172d970: return_free_pages_to_mm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long unsigned int return_free_pages_to_mm(struct virtio_balloon *vb, long unsigned int num_to_return);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_balloon.c (ffffffff81711b60)
Location: drivers/virtio/virtio_balloon.c:410
Inline: False
Direct callers:
  - drivers/virtio/virtio_balloon.c:remove_common
  - drivers/virtio/virtio_balloon.c:virtio_balloon_shrinker_scan
  - drivers/virtio/virtio_balloon.c:report_free_page_func
```
**Symbols:**

```
ffffffff81711b60-ffffffff81711c40: return_free_pages_to_mm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long unsigned int return_free_pages_to_mm(struct virtio_balloon *vb, long unsigned int num_to_return);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_balloon.c (ffffffff8178e5d0)
Location: drivers/virtio/virtio_balloon.c:410
Inline: False
Direct callers:
  - drivers/virtio/virtio_balloon.c:remove_common
  - drivers/virtio/virtio_balloon.c:virtio_balloon_shrinker_scan
  - drivers/virtio/virtio_balloon.c:report_free_page_func
```
**Symbols:**

```
ffffffff8178e5d0-ffffffff8178e6b0: return_free_pages_to_mm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
long unsigned int return_free_pages_to_mm(struct virtio_balloon *vb, long unsigned int num_to_return);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_balloon.c (ffffffff818c6657)
Location: drivers/virtio/virtio_balloon.c:410
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:remove_common
  - drivers/virtio/virtio_balloon.c:report_free_page_func
Direct callers:
  - drivers/virtio/virtio_balloon.c:virtio_balloon_shrinker_scan
```
**Symbols:**

```
ffffffff818c4ef0-ffffffff818c4fd3: return_free_pages_to_mm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
long unsigned int return_free_pages_to_mm(struct virtio_balloon *vb, long unsigned int num_to_return);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_balloon.c (ffffffff81a16fa7)
Location: drivers/virtio/virtio_balloon.c:403
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:remove_common
  - drivers/virtio/virtio_balloon.c:report_free_page_func
Direct callers:
  - drivers/virtio/virtio_balloon.c:virtio_balloon_shrinker_scan
```
**Symbols:**

```
ffffffff81a15770-ffffffff81a15853: return_free_pages_to_mm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
long unsigned int return_free_pages_to_mm(struct virtio_balloon *vb, long unsigned int num_to_return);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_balloon.c (ffffffff81a60037)
Location: drivers/virtio/virtio_balloon.c:403
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:remove_common
  - drivers/virtio/virtio_balloon.c:report_free_page_func
Direct callers:
  - drivers/virtio/virtio_balloon.c:virtio_balloon_shrinker_scan
```
**Symbols:**

```
ffffffff81a5e830-ffffffff81a5e908: return_free_pages_to_mm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
long unsigned int return_free_pages_to_mm(struct virtio_balloon *vb, long unsigned int num_to_return);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_balloon.c (ffffffff81ab2877)
Location: drivers/virtio/virtio_balloon.c:412
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:remove_common
  - drivers/virtio/virtio_balloon.c:report_free_page_func
Direct callers:
  - drivers/virtio/virtio_balloon.c:virtio_balloon_shrinker_scan
```
**Symbols:**

```
ffffffff81ab0f20-ffffffff81ab0ff8: return_free_pages_to_mm (STB_LOCAL)
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
long unsigned int return_free_pages_to_mm(struct virtio_balloon *vb, long unsigned int num_to_return);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_balloon.c (ffff80001082a570)
Location: drivers/virtio/virtio_balloon.c:373
Inline: False
Direct callers:
  - drivers/virtio/virtio_balloon.c:remove_common
  - drivers/virtio/virtio_balloon.c:virtio_balloon_shrinker_scan
  - drivers/virtio/virtio_balloon.c:report_free_page_func
```
**Symbols:**

```
ffff80001082a570-ffff80001082a69c: return_free_pages_to_mm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long unsigned int return_free_pages_to_mm(struct virtio_balloon *vb, long unsigned int num_to_return);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_balloon.c (c09472d8)
Location: drivers/virtio/virtio_balloon.c:373
Inline: False
Direct callers:
  - drivers/virtio/virtio_balloon.c:remove_common
  - drivers/virtio/virtio_balloon.c:virtio_balloon_shrinker_scan
  - drivers/virtio/virtio_balloon.c:report_free_page_func
```
**Symbols:**

```
c09472d8-c0947394: return_free_pages_to_mm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long unsigned int return_free_pages_to_mm(struct virtio_balloon *vb, long unsigned int num_to_return);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_balloon.c (c0000000008d73f0)
Location: drivers/virtio/virtio_balloon.c:373
Inline: False
Direct callers:
  - drivers/virtio/virtio_balloon.c:remove_common
  - drivers/virtio/virtio_balloon.c:virtio_balloon_shrinker_scan
  - drivers/virtio/virtio_balloon.c:report_free_page_func
```
**Symbols:**

```
c0000000008d73f0-c0000000008d7568: return_free_pages_to_mm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long unsigned int return_free_pages_to_mm(struct virtio_balloon *vb, long unsigned int num_to_return);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_balloon.c (ffffffe000520cc2)
Location: drivers/virtio/virtio_balloon.c:373
Inline: False
Direct callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_remove
  - drivers/virtio/virtio_balloon.c:virtio_balloon_shrinker_scan
  - drivers/virtio/virtio_balloon.c:report_free_page_func
```
**Symbols:**

```
ffffffe000520cc2-ffffffe000520dbe: return_free_pages_to_mm (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
long unsigned int return_free_pages_to_mm(struct virtio_balloon *vb, long unsigned int num_to_return);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_balloon.c (ffffffff81627a90)
Location: drivers/virtio/virtio_balloon.c:373
Inline: False
Direct callers:
  - drivers/virtio/virtio_balloon.c:remove_common
  - drivers/virtio/virtio_balloon.c:virtio_balloon_shrinker_scan
  - drivers/virtio/virtio_balloon.c:report_free_page_func
```
**Symbols:**

```
ffffffff81627a90-ffffffff81627b70: return_free_pages_to_mm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long unsigned int return_free_pages_to_mm(struct virtio_balloon *vb, long unsigned int num_to_return);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_balloon.c (ffffffff8161c100)
Location: drivers/virtio/virtio_balloon.c:373
Inline: False
Direct callers:
  - drivers/virtio/virtio_balloon.c:remove_common
  - drivers/virtio/virtio_balloon.c:virtio_balloon_shrinker_scan
  - drivers/virtio/virtio_balloon.c:report_free_page_func
```
**Symbols:**

```
ffffffff8161c100-ffffffff8161c1da: return_free_pages_to_mm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long unsigned int return_free_pages_to_mm(struct virtio_balloon *vb, long unsigned int num_to_return);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_balloon.c (ffffffff81655a60)
Location: drivers/virtio/virtio_balloon.c:373
Inline: False
Direct callers:
  - drivers/virtio/virtio_balloon.c:remove_common
  - drivers/virtio/virtio_balloon.c:virtio_balloon_shrinker_scan
  - drivers/virtio/virtio_balloon.c:report_free_page_func
```
**Symbols:**

```
ffffffff81655a60-ffffffff81655b40: return_free_pages_to_mm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long unsigned int return_free_pages_to_mm(struct virtio_balloon *vb, long unsigned int num_to_return);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_balloon.c (ffffffff8166ec30)
Location: drivers/virtio/virtio_balloon.c:373
Inline: False
Direct callers:
  - drivers/virtio/virtio_balloon.c:remove_common
  - drivers/virtio/virtio_balloon.c:virtio_balloon_shrinker_scan
  - drivers/virtio/virtio_balloon.c:report_free_page_func
```
**Symbols:**

```
ffffffff8166ec30-ffffffff8166ed07: return_free_pages_to_mm (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
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
