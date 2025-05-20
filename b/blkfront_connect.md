# Function: <code>blkfront_connect</code>

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
In drivers/block/xen-blkfront.c (ffffffff81578a24)
Location: drivers/block/xen-blkfront.c:1993
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkback_changed
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
In drivers/block/xen-blkfront.c (ffffffff815cd81f)
Location: drivers/block/xen-blkfront.c:2366
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkback_changed
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void blkfront_connect(struct blkfront_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff815fa280)
Location: drivers/block/xen-blkfront.c:2342
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkback_changed
```
**Symbols:**

```
ffffffff815fa280-ffffffff815fa9d1: blkfront_connect (STB_LOCAL)
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
In drivers/block/xen-blkfront.c (ffffffff8160e50a)
Location: drivers/block/xen-blkfront.c:2312
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkback_changed
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
In drivers/block/xen-blkfront.c (ffffffff81676d8a)
Location: drivers/block/xen-blkfront.c:2312
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkback_changed
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
In drivers/block/xen-blkfront.c (ffffffff816b2de0)
Location: drivers/block/xen-blkfront.c:2315
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkback_changed
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
In drivers/block/xen-blkfront.c (ffffffff816d4040)
Location: drivers/block/xen-blkfront.c:2334
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkback_changed
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void blkfront_connect(struct blkfront_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/block/xen-blkfront.c (0)
Location: drivers/block/xen-blkfront.c:2334
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkback_changed
```
**Symbols:**

```
ffffffff8170e340-ffffffff8170e724: blkfront_connect (STB_LOCAL)
ffffffff8170fe00-ffffffff8170fe43: blkfront_connect.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void blkfront_connect(struct blkfront_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/block/xen-blkfront.c (0)
Location: drivers/block/xen-blkfront.c:2334
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkback_changed
```
**Symbols:**

```
ffffffff81732640-ffffffff81732a24: blkfront_connect (STB_LOCAL)
ffffffff817340ea-ffffffff8173412d: blkfront_connect.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void blkfront_connect(struct blkfront_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/block/xen-blkfront.c (0)
Location: drivers/block/xen-blkfront.c:2342
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkback_changed
```
**Symbols:**

```
ffffffff817f1010-ffffffff817f1389: blkfront_connect (STB_LOCAL)
ffffffff817f16e3-ffffffff817f170b: blkfront_connect.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void blkfront_connect(struct blkfront_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/block/xen-blkfront.c (0)
Location: drivers/block/xen-blkfront.c:2346
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkback_changed
```
**Symbols:**

```
ffffffff81805920-ffffffff81805c99: blkfront_connect (STB_LOCAL)
ffffffff81c0fdc6-ffffffff81c0fde9: blkfront_connect.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void blkfront_connect(struct blkfront_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/block/xen-blkfront.c (0)
Location: drivers/block/xen-blkfront.c:2346
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkback_changed
```
**Symbols:**

```
ffffffff817ea4d0-ffffffff817ea849: blkfront_connect (STB_LOCAL)
ffffffff81c01f6a-ffffffff81c01f8d: blkfront_connect.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void blkfront_connect(struct blkfront_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/block/xen-blkfront.c (0)
Location: drivers/block/xen-blkfront.c:2323
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkback_changed
```
**Symbols:**

```
ffffffff81876c00-ffffffff81877106: blkfront_connect (STB_LOCAL)
ffffffff81d05cd8-ffffffff81d05cfa: blkfront_connect.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void blkfront_connect(struct blkfront_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/block/xen-blkfront.c (0)
Location: drivers/block/xen-blkfront.c:2310
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkback_changed
```
**Symbols:**

```
ffffffff819bede0-ffffffff819bf333: blkfront_connect (STB_LOCAL)
ffffffff81ece5ec-ffffffff81ece60e: blkfront_connect.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void blkfront_connect(struct blkfront_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff81b34530)
Location: drivers/block/xen-blkfront.c:2313
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkback_changed
```
**Symbols:**

```
ffffffff81b34530-ffffffff81b34aa6: blkfront_connect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void blkfront_connect(struct blkfront_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff81b87a10)
Location: drivers/block/xen-blkfront.c:2314
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkback_changed
```
**Symbols:**

```
ffffffff81b87a10-ffffffff81b87f81: blkfront_connect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void blkfront_connect(struct blkfront_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff81bdb8c0)
Location: drivers/block/xen-blkfront.c:2314
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkback_changed
```
**Symbols:**

```
ffffffff81bdb8c0-ffffffff81bdbe31: blkfront_connect (STB_LOCAL)
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
void blkfront_connect(struct blkfront_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffff800010929a78)
Location: drivers/block/xen-blkfront.c:2334
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkback_changed
```
**Symbols:**

```
ffff800010929a78-ffff800010929eb0: blkfront_connect (STB_LOCAL)
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
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void blkfront_connect(struct blkfront_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/block/xen-blkfront.c (0)
Location: drivers/block/xen-blkfront.c:2363
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkback_changed
```
**Symbols:**

```
ffffffff816f85e0-ffffffff816f89d7: blkfront_connect (STB_LOCAL)
ffffffff816fa17e-ffffffff816fa1c1: blkfront_connect.cold (STB_LOCAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void blkfront_connect(struct blkfront_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/block/xen-blkfront.c (0)
Location: drivers/block/xen-blkfront.c:2334
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkback_changed
```
**Symbols:**

```
ffffffff81725b00-ffffffff81725ee4: blkfront_connect (STB_LOCAL)
ffffffff817275aa-ffffffff817275ed: blkfront_connect.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void blkfront_connect(struct blkfront_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/block/xen-blkfront.c (0)
Location: drivers/block/xen-blkfront.c:2334
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkback_changed
```
**Symbols:**

```
ffffffff81740f50-ffffffff81741334: blkfront_connect (STB_LOCAL)
ffffffff817429f7-ffffffff81742a3a: blkfront_connect.cold (STB_LOCAL)
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
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
