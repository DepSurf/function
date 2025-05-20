# Function: <code>set_page_pfns</code>

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
In drivers/virtio/virtio_balloon.c (ffffffff814c3841)
Location: drivers/virtio/virtio_balloon.c:128
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:fill_balloon
  - drivers/virtio/virtio_balloon.c:leak_balloon
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
In drivers/virtio/virtio_balloon.c (ffffffff81513e30)
Location: drivers/virtio/virtio_balloon.c:135
Inline: True
Direct callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:leak_balloon
```
**Symbols:**

```
ffffffff81513e30-ffffffff81513e41: set_page_pfns.isra.6 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_balloon.c (ffffffff81540260)
Location: drivers/virtio/virtio_balloon.c:135
Inline: True
Direct callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:leak_balloon
```
**Symbols:**

```
ffffffff81540260-ffffffff81540278: set_page_pfns.isra.9 (STB_LOCAL)
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
In drivers/virtio/virtio_balloon.c (ffffffff8155419e)
Location: drivers/virtio/virtio_balloon.c:130
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:leak_balloon
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
In drivers/virtio/virtio_balloon.c (ffffffff815b7bde)
Location: drivers/virtio/virtio_balloon.c:130
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:leak_balloon
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_balloon.c (ffffffff815f0128)
Location: drivers/virtio/virtio_balloon.c:130
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:leak_balloon
Direct callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:leak_balloon
```
**Symbols:**

```
ffffffff815f0040-ffffffff815f0058: set_page_pfns.isra.12.part.13 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_balloon.c (ffffffff8160a708)
Location: drivers/virtio/virtio_balloon.c:167
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:leak_balloon
Direct callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:leak_balloon
```
**Symbols:**

```
ffffffff8160a620-ffffffff8160a638: set_page_pfns.isra.12.part.13 (STB_LOCAL)
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
In drivers/virtio/virtio_balloon.c (ffffffff8163e458)
Location: drivers/virtio/virtio_balloon.c:155
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:leak_balloon
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
In drivers/virtio/virtio_balloon.c (ffffffff816609c2)
Location: drivers/virtio/virtio_balloon.c:155
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:leak_balloon
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
In drivers/virtio/virtio_balloon.c (ffffffff817106a3)
Location: drivers/virtio/virtio_balloon.c:195
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:leak_balloon
  - drivers/virtio/virtio_balloon.c:fill_balloon
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
In drivers/virtio/virtio_balloon.c (ffffffff8172d283)
Location: drivers/virtio/virtio_balloon.c:195
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:leak_balloon
  - drivers/virtio/virtio_balloon.c:fill_balloon
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
In drivers/virtio/virtio_balloon.c (ffffffff81710ff0)
Location: drivers/virtio/virtio_balloon.c:195
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:leak_balloon
  - drivers/virtio/virtio_balloon.c:fill_balloon
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
In drivers/virtio/virtio_balloon.c (ffffffff8178db0a)
Location: drivers/virtio/virtio_balloon.c:195
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:leak_balloon
  - drivers/virtio/virtio_balloon.c:fill_balloon
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
In drivers/virtio/virtio_balloon.c (ffffffff818c62c7)
Location: drivers/virtio/virtio_balloon.c:195
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:leak_balloon
  - drivers/virtio/virtio_balloon.c:fill_balloon
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
In drivers/virtio/virtio_balloon.c (ffffffff81a16bf6)
Location: drivers/virtio/virtio_balloon.c:188
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:leak_balloon
  - drivers/virtio/virtio_balloon.c:fill_balloon
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
In drivers/virtio/virtio_balloon.c (ffffffff81a5fc86)
Location: drivers/virtio/virtio_balloon.c:188
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:leak_balloon
  - drivers/virtio/virtio_balloon.c:fill_balloon
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
In drivers/virtio/virtio_balloon.c (ffffffff81ab2496)
Location: drivers/virtio/virtio_balloon.c:193
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:leak_balloon
  - drivers/virtio/virtio_balloon.c:fill_balloon
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
In drivers/virtio/virtio_balloon.c (ffff800010829820)
Location: drivers/virtio/virtio_balloon.c:155
Inline: True
Direct callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:leak_balloon
```
**Symbols:**

```
ffff800010829820-ffff80001082985c: set_page_pfns.isra.0 (STB_LOCAL)
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
In drivers/virtio/virtio_balloon.c (c094761c)
Location: drivers/virtio/virtio_balloon.c:155
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:leak_balloon
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void set_page_pfns(struct virtio_balloon *vb, __virtio32 *pfns, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_balloon.c (c0000000008d6500)
Location: drivers/virtio/virtio_balloon.c:155
Inline: False
Direct callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:leak_balloon
```
**Symbols:**

```
c0000000008d6500-c0000000008d6558: set_page_pfns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void set_page_pfns(struct virtio_balloon *vb, __virtio32 *pfns, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_balloon.c (ffffffe00051fbd0)
Location: drivers/virtio/virtio_balloon.c:155
Inline: False
Direct callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:leak_balloon
```
**Symbols:**

```
ffffffe00051fbd0-ffffffe00051fc04: set_page_pfns (STB_LOCAL)
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
In drivers/virtio/virtio_balloon.c (ffffffff81626832)
Location: drivers/virtio/virtio_balloon.c:155
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:leak_balloon
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
In drivers/virtio/virtio_balloon.c (ffffffff8161aeb2)
Location: drivers/virtio/virtio_balloon.c:155
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:leak_balloon
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
In drivers/virtio/virtio_balloon.c (ffffffff81654802)
Location: drivers/virtio/virtio_balloon.c:155
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:leak_balloon
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
In drivers/virtio/virtio_balloon.c (ffffffff8166f282)
Location: drivers/virtio/virtio_balloon.c:155
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:virtballoon_migratepage
  - drivers/virtio/virtio_balloon.c:leak_balloon
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
