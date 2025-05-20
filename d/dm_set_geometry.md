# Function: <code>dm_set_geometry</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int dm_set_geometry(struct mapped_device *md, struct hd_geometry *geo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff816a3190)
Location: drivers/md/dm.c:898
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:dev_set_geometry
```
**Symbols:**

```
ffffffff816a3190-ffffffff816a31dd: dm_set_geometry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int dm_set_geometry(struct mapped_device *md, struct hd_geometry *geo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81703a00)
Location: drivers/md/dm.c:732
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:dev_set_geometry
```
**Symbols:**

```
ffffffff81703a00-ffffffff81703a4d: dm_set_geometry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int dm_set_geometry(struct mapped_device *md, struct hd_geometry *geo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff817358c0)
Location: drivers/md/dm.c:732
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:dev_set_geometry
```
**Symbols:**

```
ffffffff817358c0-ffffffff8173590d: dm_set_geometry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int dm_set_geometry(struct mapped_device *md, struct hd_geometry *geo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff8174ecc0)
Location: drivers/md/dm.c:733
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:dev_set_geometry
```
**Symbols:**

```
ffffffff8174ecc0-ffffffff8174ed11: dm_set_geometry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int dm_set_geometry(struct mapped_device *md, struct hd_geometry *geo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff817c0f10)
Location: drivers/md/dm.c:741
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:dev_set_geometry
```
**Symbols:**

```
ffffffff817c0f10-ffffffff817c0f61: dm_set_geometry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int dm_set_geometry(struct mapped_device *md, struct hd_geometry *geo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm.c (0)
Location: drivers/md/dm.c:834
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:dev_set_geometry
```
**Symbols:**

```
ffffffff8180aa47-ffffffff8180aa5d: dm_set_geometry.cold.57 (STB_LOCAL)
ffffffff81809630-ffffffff8180966f: dm_set_geometry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int dm_set_geometry(struct mapped_device *md, struct hd_geometry *geo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm.c (0)
Location: drivers/md/dm.c:889
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:dev_set_geometry
```
**Symbols:**

```
ffffffff81836a47-ffffffff81836a5d: dm_set_geometry.cold.61 (STB_LOCAL)
ffffffff81835740-ffffffff8183577f: dm_set_geometry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int dm_set_geometry(struct mapped_device *md, struct hd_geometry *geo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm.c (0)
Location: drivers/md/dm.c:871
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:dev_set_geometry
```
**Symbols:**

```
ffffffff81879659-ffffffff8187966f: dm_set_geometry.cold (STB_LOCAL)
ffffffff818785b0-ffffffff818785ef: dm_set_geometry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int dm_set_geometry(struct mapped_device *md, struct hd_geometry *geo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm.c (0)
Location: drivers/md/dm.c:871
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:dev_set_geometry
```
**Symbols:**

```
ffffffff818ab45a-ffffffff818ab470: dm_set_geometry.cold (STB_LOCAL)
ffffffff818aa3f0-ffffffff818aa42f: dm_set_geometry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int dm_set_geometry(struct mapped_device *md, struct hd_geometry *geo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm.c (0)
Location: drivers/md/dm.c:884
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:dev_set_geometry
```
**Symbols:**

```
ffffffff8197b63b-ffffffff8197b651: dm_set_geometry.cold (STB_LOCAL)
ffffffff8197a860-ffffffff8197a89f: dm_set_geometry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int dm_set_geometry(struct mapped_device *md, struct hd_geometry *geo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm.c (0)
Location: drivers/md/dm.c:880
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:dev_set_geometry
```
**Symbols:**

```
ffffffff81c28114-ffffffff81c2812a: dm_set_geometry.cold (STB_LOCAL)
ffffffff8197f0a0-ffffffff8197f0df: dm_set_geometry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int dm_set_geometry(struct mapped_device *md, struct hd_geometry *geo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm.c (0)
Location: drivers/md/dm.c:883
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:dev_set_geometry
```
**Symbols:**

```
ffffffff81c1a2cb-ffffffff81c1a2e2: dm_set_geometry.cold (STB_LOCAL)
ffffffff819631c0-ffffffff819631fa: dm_set_geometry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int dm_set_geometry(struct mapped_device *md, struct hd_geometry *geo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm.c (0)
Location: drivers/md/dm.c:763
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:dev_set_geometry
```
**Symbols:**

```
ffffffff81d29f55-ffffffff81d29f6c: dm_set_geometry.cold (STB_LOCAL)
ffffffff81a0a1e0-ffffffff81a0a21a: dm_set_geometry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int dm_set_geometry(struct mapped_device *md, struct hd_geometry *geo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm.c (0)
Location: drivers/md/dm.c:867
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:dev_set_geometry
```
**Symbols:**

```
ffffffff81ef627a-ffffffff81ef629b: dm_set_geometry.cold (STB_LOCAL)
ffffffff81b736e0-ffffffff81b73724: dm_set_geometry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int dm_set_geometry(struct mapped_device *md, struct hd_geometry *geo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81d10290)
Location: drivers/md/dm.c:848
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:dev_set_geometry
```
**Symbols:**

```
ffffffff81d10290-ffffffff81d102f1: dm_set_geometry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int dm_set_geometry(struct mapped_device *md, struct hd_geometry *geo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81d79700)
Location: drivers/md/dm.c:855
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:dev_set_geometry
```
**Symbols:**

```
ffffffff81d79700-ffffffff81d79761: dm_set_geometry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int dm_set_geometry(struct mapped_device *md, struct hd_geometry *geo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81e308a0)
Location: drivers/md/dm.c:841
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:dev_set_geometry
```
**Symbols:**

```
ffffffff81e308a0-ffffffff81e30901: dm_set_geometry (STB_GLOBAL)
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
int dm_set_geometry(struct mapped_device *md, struct hd_geometry *geo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffff800010b00310)
Location: drivers/md/dm.c:871
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:dev_set_geometry
```
**Symbols:**

```
ffff800010b00310-ffff800010b0037c: dm_set_geometry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int dm_set_geometry(struct mapped_device *md, struct hd_geometry *geo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (c0bdfd5c)
Location: drivers/md/dm.c:871
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:dev_set_geometry
```
**Symbols:**

```
c0bdfd5c-c0bdfde0: dm_set_geometry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int dm_set_geometry(struct mapped_device *md, struct hd_geometry *geo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (c000000000bef710)
Location: drivers/md/dm.c:871
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:dev_set_geometry
```
**Symbols:**

```
c000000000bef710-c000000000bef78c: dm_set_geometry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int dm_set_geometry(struct mapped_device *md, struct hd_geometry *geo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffe0006f087a)
Location: drivers/md/dm.c:871
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:dev_set_geometry
```
**Symbols:**

```
ffffffe0006f087a-ffffffe0006f08dc: dm_set_geometry (STB_GLOBAL)
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
int dm_set_geometry(struct mapped_device *md, struct hd_geometry *geo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm.c (0)
Location: drivers/md/dm.c:871
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:dev_set_geometry
```
**Symbols:**

```
ffffffff818512da-ffffffff818512f0: dm_set_geometry.cold (STB_LOCAL)
ffffffff81850270-ffffffff818502af: dm_set_geometry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int dm_set_geometry(struct mapped_device *md, struct hd_geometry *geo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm.c (0)
Location: drivers/md/dm.c:871
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:dev_set_geometry
```
**Symbols:**

```
ffffffff818188ea-ffffffff81818900: dm_set_geometry.cold (STB_LOCAL)
ffffffff81817880-ffffffff818178bf: dm_set_geometry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int dm_set_geometry(struct mapped_device *md, struct hd_geometry *geo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm.c (0)
Location: drivers/md/dm.c:871
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:dev_set_geometry
```
**Symbols:**

```
ffffffff818a090a-ffffffff818a0920: dm_set_geometry.cold (STB_LOCAL)
ffffffff8189f8a0-ffffffff8189f8df: dm_set_geometry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int dm_set_geometry(struct mapped_device *md, struct hd_geometry *geo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm.c (0)
Location: drivers/md/dm.c:871
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:dev_set_geometry
```
**Symbols:**

```
ffffffff818bcb4a-ffffffff818bcb60: dm_set_geometry.cold (STB_LOCAL)
ffffffff818bbb00-ffffffff818bbb3f: dm_set_geometry (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
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
