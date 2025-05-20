# Function: <code>fill_balloon</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void fill_balloon(struct virtio_balloon *vb, size_t num);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_balloon.c (ffffffff814c3910)
Location: drivers/virtio/virtio_balloon.c:138
Inline: False
Direct callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_restore
  - drivers/virtio/virtio_balloon.c:balloon
```
**Symbols:**

```
ffffffff814c3910-ffffffff814c3a39: fill_balloon (STB_LOCAL)
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
In drivers/virtio/virtio_balloon.c (ffffffff8151476b)
Location: drivers/virtio/virtio_balloon.c:147
Inline: True
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
In drivers/virtio/virtio_balloon.c (ffffffff8154081b)
Location: drivers/virtio/virtio_balloon.c:147
Inline: True
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
In drivers/virtio/virtio_balloon.c (ffffffff81554c9a)
Location: drivers/virtio/virtio_balloon.c:144
Inline: True
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
In drivers/virtio/virtio_balloon.c (ffffffff815b8855)
Location: drivers/virtio/virtio_balloon.c:144
Inline: True
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
In drivers/virtio/virtio_balloon.c (ffffffff815f0e17)
Location: drivers/virtio/virtio_balloon.c:144
Inline: True
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
In drivers/virtio/virtio_balloon.c (ffffffff8160b3e7)
Location: drivers/virtio/virtio_balloon.c:181
Inline: True
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
In drivers/virtio/virtio_balloon.c (ffffffff8163f2b9)
Location: drivers/virtio/virtio_balloon.c:169
Inline: True
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
In drivers/virtio/virtio_balloon.c (ffffffff816616d9)
Location: drivers/virtio/virtio_balloon.c:171
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
unsigned int fill_balloon(struct virtio_balloon *vb, size_t num);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_balloon.c (0)
Location: drivers/virtio/virtio_balloon.c:211
Inline: False
Direct callers:
  - drivers/virtio/virtio_balloon.c:update_balloon_size_func
```
**Symbols:**

```
ffffffff8170fda0-ffffffff8170ff83: fill_balloon (STB_LOCAL)
ffffffff817114b5-ffffffff817114d2: fill_balloon.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
unsigned int fill_balloon(struct virtio_balloon *vb, size_t num);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_balloon.c (0)
Location: drivers/virtio/virtio_balloon.c:211
Inline: False
Direct callers:
  - drivers/virtio/virtio_balloon.c:update_balloon_size_func
```
**Symbols:**

```
ffffffff8172ca90-ffffffff8172cc73: fill_balloon (STB_LOCAL)
ffffffff81c049d7-ffffffff81c049f4: fill_balloon.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
unsigned int fill_balloon(struct virtio_balloon *vb, size_t num);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_balloon.c (0)
Location: drivers/virtio/virtio_balloon.c:211
Inline: False
Direct callers:
  - drivers/virtio/virtio_balloon.c:update_balloon_size_func
```
**Symbols:**

```
ffffffff817105a0-ffffffff81710781: fill_balloon (STB_LOCAL)
ffffffff81bf6594-ffffffff81bf65b1: fill_balloon.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
unsigned int fill_balloon(struct virtio_balloon *vb, size_t num);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_balloon.c (0)
Location: drivers/virtio/virtio_balloon.c:211
Inline: False
Direct callers:
  - drivers/virtio/virtio_balloon.c:update_balloon_size_func
```
**Symbols:**

```
ffffffff8178cf80-ffffffff8178d161: fill_balloon (STB_LOCAL)
ffffffff81cf51b9-ffffffff81cf51d6: fill_balloon.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
unsigned int fill_balloon(struct virtio_balloon *vb, size_t num);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_balloon.c (0)
Location: drivers/virtio/virtio_balloon.c:211
Inline: False
Direct callers:
  - drivers/virtio/virtio_balloon.c:update_balloon_size_func
```
**Symbols:**

```
ffffffff818c5080-ffffffff818c525b: fill_balloon (STB_LOCAL)
ffffffff81ebd350-ffffffff81ebd36d: fill_balloon.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
unsigned int fill_balloon(struct virtio_balloon *vb, size_t num);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_balloon.c (ffffffff81a15930)
Location: drivers/virtio/virtio_balloon.c:204
Inline: False
Direct callers:
  - drivers/virtio/virtio_balloon.c:update_balloon_size_func
```
**Symbols:**

```
ffffffff81a15930-ffffffff81a15b28: fill_balloon (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
unsigned int fill_balloon(struct virtio_balloon *vb, size_t num);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_balloon.c (ffffffff81a5e970)
Location: drivers/virtio/virtio_balloon.c:204
Inline: False
Direct callers:
  - drivers/virtio/virtio_balloon.c:update_balloon_size_func
```
**Symbols:**

```
ffffffff81a5e970-ffffffff81a5eb68: fill_balloon (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
unsigned int fill_balloon(struct virtio_balloon *vb, size_t num);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_balloon.c (ffffffff81ab1060)
Location: drivers/virtio/virtio_balloon.c:209
Inline: False
Direct callers:
  - drivers/virtio/virtio_balloon.c:update_balloon_size_func
```
**Symbols:**

```
ffffffff81ab1060-ffffffff81ab1258: fill_balloon (STB_LOCAL)
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
In drivers/virtio/virtio_balloon.c (ffff800010829f10)
Location: drivers/virtio/virtio_balloon.c:171
Inline: True
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
In drivers/virtio/virtio_balloon.c (c0948848)
Location: drivers/virtio/virtio_balloon.c:171
Inline: True
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
In drivers/virtio/virtio_balloon.c (c0000000008d6d78)
Location: drivers/virtio/virtio_balloon.c:171
Inline: True
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
In drivers/virtio/virtio_balloon.c (ffffffe00052007e)
Location: drivers/virtio/virtio_balloon.c:171
Inline: True
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
In drivers/virtio/virtio_balloon.c (ffffffff81627549)
Location: drivers/virtio/virtio_balloon.c:171
Inline: True
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
In drivers/virtio/virtio_balloon.c (ffffffff8161bbc9)
Location: drivers/virtio/virtio_balloon.c:171
Inline: True
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
In drivers/virtio/virtio_balloon.c (ffffffff81655519)
Location: drivers/virtio/virtio_balloon.c:171
Inline: True
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
In drivers/virtio/virtio_balloon.c (ffffffff8167010d)
Location: drivers/virtio/virtio_balloon.c:171
Inline: True
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
