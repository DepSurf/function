# Function: <code>nd_namespace_blk_size</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff8159b820)
Location: drivers/nvdimm/namespace_devs.c:264
Inline: True
```
**Symbols:**

```
ffffffff8159b820-ffffffff8159b8c3: nd_namespace_blk_size.isra.5 (STB_LOCAL)
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
In drivers/nvdimm/namespace_devs.c (ffffffff815f1890)
Location: drivers/nvdimm/namespace_devs.c:261
Inline: True
```
**Symbols:**

```
ffffffff815f1890-ffffffff815f1934: nd_namespace_blk_size.isra.5 (STB_LOCAL)
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
In drivers/nvdimm/namespace_devs.c (ffffffff8161efd0)
Location: drivers/nvdimm/namespace_devs.c:280
Inline: True
```
**Symbols:**

```
ffffffff8161efd0-ffffffff8161f074: nd_namespace_blk_size.isra.7 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff81633420)
Location: drivers/nvdimm/namespace_devs.c:299
Inline: True
Direct callers:
  - drivers/nvdimm/namespace_devs.c:nd_namespace_label_update
```
**Symbols:**

```
ffffffff81633420-ffffffff816334c4: nd_namespace_blk_size.isra.8 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff8169bd90)
Location: drivers/nvdimm/namespace_devs.c:299
Inline: True
Direct callers:
  - drivers/nvdimm/namespace_devs.c:nd_namespace_label_update
```
**Symbols:**

```
ffffffff8169bd90-ffffffff8169be34: nd_namespace_blk_size.isra.8 (STB_LOCAL)
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
In drivers/nvdimm/namespace_devs.c (ffffffff816d81c0)
Location: drivers/nvdimm/namespace_devs.c:299
Inline: True
Direct callers:
  - drivers/nvdimm/namespace_devs.c:nd_namespace_label_update
```
**Symbols:**

```
ffffffff816d81c0-ffffffff816d8264: nd_namespace_blk_size.isra.12 (STB_LOCAL)
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
In drivers/nvdimm/namespace_devs.c (ffffffff816fa1e0)
Location: drivers/nvdimm/namespace_devs.c:302
Inline: True
Direct callers:
  - drivers/nvdimm/namespace_devs.c:nd_namespace_label_update
```
**Symbols:**

```
ffffffff816fa1e0-ffffffff816fa284: nd_namespace_blk_size.isra.13 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff81733ca0)
Location: drivers/nvdimm/namespace_devs.c:294
Inline: True
Direct callers:
  - drivers/nvdimm/namespace_devs.c:nd_namespace_label_update
```
**Symbols:**

```
ffffffff81733ca0-ffffffff81733d44: nd_namespace_blk_size.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff81757a30)
Location: drivers/nvdimm/namespace_devs.c:294
Inline: True
Direct callers:
  - drivers/nvdimm/namespace_devs.c:nd_namespace_label_update
```
**Symbols:**

```
ffffffff81757a30-ffffffff81757ad4: nd_namespace_blk_size.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
resource_size_t nd_namespace_blk_size(struct nd_namespace_blk *nsblk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff81816460)
Location: drivers/nvdimm/namespace_devs.c:269
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:__nvdimm_namespace_capacity
  - drivers/nvdimm/namespace_devs.c:nd_namespace_label_update
```
**Symbols:**

```
ffffffff81816460-ffffffff8181650c: nd_namespace_blk_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
resource_size_t nd_namespace_blk_size(struct nd_namespace_blk *nsblk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff818255b0)
Location: drivers/nvdimm/namespace_devs.c:269
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:__nvdimm_namespace_capacity
  - drivers/nvdimm/namespace_devs.c:nd_namespace_label_update
```
**Symbols:**

```
ffffffff818255b0-ffffffff8182565c: nd_namespace_blk_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
resource_size_t nd_namespace_blk_size(struct nd_namespace_blk *nsblk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff81808950)
Location: drivers/nvdimm/namespace_devs.c:269
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:__nvdimm_namespace_capacity
  - drivers/nvdimm/namespace_devs.c:nd_namespace_label_update
```
**Symbols:**

```
ffffffff81808950-ffffffff818089fc: nd_namespace_blk_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
resource_size_t nd_namespace_blk_size(struct nd_namespace_blk *nsblk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff81893110)
Location: drivers/nvdimm/namespace_devs.c:269
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:__nvdimm_namespace_capacity
  - drivers/nvdimm/namespace_devs.c:nd_namespace_label_update
```
**Symbols:**

```
ffffffff81893110-ffffffff818931bc: nd_namespace_blk_size (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
In drivers/nvdimm/namespace_devs.c (ffff800010959048)
Location: drivers/nvdimm/namespace_devs.c:294
Inline: True
Direct callers:
  - drivers/nvdimm/namespace_devs.c:nd_namespace_label_update
```
**Symbols:**

```
ffff800010959048-ffff800010959104: nd_namespace_blk_size.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
resource_size_t nd_namespace_blk_size(struct nd_namespace_blk *nsblk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (c000000000a07180)
Location: drivers/nvdimm/namespace_devs.c:294
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:nd_namespace_label_update
```
**Symbols:**

```
c000000000a07180-c000000000a07454: nd_namespace_blk_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
resource_size_t nd_namespace_blk_size(struct nd_namespace_blk *nsblk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffe0005c7520)
Location: drivers/nvdimm/namespace_devs.c:294
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:nd_namespace_label_update
```
**Symbols:**

```
ffffffe0005c7520-ffffffe0005c759c: nd_namespace_blk_size (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff8170c120)
Location: drivers/nvdimm/namespace_devs.c:294
Inline: True
Direct callers:
  - drivers/nvdimm/namespace_devs.c:nd_namespace_label_update
```
**Symbols:**

```
ffffffff8170c120-ffffffff8170c1c4: nd_namespace_blk_size.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff816dfba0)
Location: drivers/nvdimm/namespace_devs.c:294
Inline: True
Direct callers:
  - drivers/nvdimm/namespace_devs.c:nd_namespace_label_update
```
**Symbols:**

```
ffffffff816dfba0-ffffffff816dfc44: nd_namespace_blk_size.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff8174aef0)
Location: drivers/nvdimm/namespace_devs.c:294
Inline: True
Direct callers:
  - drivers/nvdimm/namespace_devs.c:nd_namespace_label_update
```
**Symbols:**

```
ffffffff8174aef0-ffffffff8174af94: nd_namespace_blk_size.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff81766370)
Location: drivers/nvdimm/namespace_devs.c:294
Inline: True
Direct callers:
  - drivers/nvdimm/namespace_devs.c:nd_namespace_label_update
```
**Symbols:**

```
ffffffff81766370-ffffffff81766414: nd_namespace_blk_size.isra.0 (STB_LOCAL)
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
</ul>
<b>Arch</b>
<ul>
</ul>
