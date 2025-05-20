# Function: <code>vme_master_rmw</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
unsigned int vme_master_rmw(struct vme_resource *resource, unsigned int mask, unsigned int compare, unsigned int swap, loff_t offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vme/vme.c (ffffffff816f1050)
Location: drivers/vme/vme.c:622
Inline: False
```
**Symbols:**

```
ffffffff816f1050-ffffffff816f10d1: vme_master_rmw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
unsigned int vme_master_rmw(struct vme_resource *resource, unsigned int mask, unsigned int compare, unsigned int swap, loff_t offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vme/vme.c (ffffffff81756090)
Location: drivers/vme/vme.c:622
Inline: False
```
**Symbols:**

```
ffffffff81756090-ffffffff81756111: vme_master_rmw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
unsigned int vme_master_rmw(struct vme_resource *resource, unsigned int mask, unsigned int compare, unsigned int swap, loff_t offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vme/vme.c (ffffffff81782650)
Location: drivers/vme/vme.c:625
Inline: False
```
**Symbols:**

```
ffffffff81782650-ffffffff817826d1: vme_master_rmw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
unsigned int vme_master_rmw(struct vme_resource *resource, unsigned int mask, unsigned int compare, unsigned int swap, loff_t offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vme/vme.c (ffffffff817a13e0)
Location: drivers/vme/vme.c:773
Inline: False
```
**Symbols:**

```
ffffffff817a13e0-ffffffff817a1461: vme_master_rmw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
unsigned int vme_master_rmw(struct vme_resource *resource, unsigned int mask, unsigned int compare, unsigned int swap, loff_t offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vme/vme.c (ffffffff81818500)
Location: drivers/vme/vme.c:769
Inline: False
```
**Symbols:**

```
ffffffff81818500-ffffffff81818584: vme_master_rmw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
unsigned int vme_master_rmw(struct vme_resource *resource, unsigned int mask, unsigned int compare, unsigned int swap, loff_t offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vme/vme.c (0)
Location: drivers/vme/vme.c:769
Inline: False
```
**Symbols:**

```
ffffffff81862cd6-ffffffff81862d02: vme_master_rmw.cold.31 (STB_LOCAL)
ffffffff81861e90-ffffffff81861ef6: vme_master_rmw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
unsigned int vme_master_rmw(struct vme_resource *resource, unsigned int mask, unsigned int compare, unsigned int swap, loff_t offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vme/vme.c (0)
Location: drivers/vme/vme.c:769
Inline: False
```
**Symbols:**

```
ffffffff81882469-ffffffff81882495: vme_master_rmw.cold.31 (STB_LOCAL)
ffffffff81881680-ffffffff818816e6: vme_master_rmw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
unsigned int vme_master_rmw(struct vme_resource *resource, unsigned int mask, unsigned int compare, unsigned int swap, loff_t offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vme/vme.c (0)
Location: drivers/vme/vme.c:765
Inline: False
```
**Symbols:**

```
ffffffff818cca9d-ffffffff818ccac9: vme_master_rmw.cold (STB_LOCAL)
ffffffff818cbc70-ffffffff818cbcd6: vme_master_rmw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
unsigned int vme_master_rmw(struct vme_resource *resource, unsigned int mask, unsigned int compare, unsigned int swap, loff_t offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vme/vme.c (0)
Location: drivers/vme/vme.c:765
Inline: False
```
**Symbols:**

```
ffffffff818fee8d-ffffffff818feeb9: vme_master_rmw.cold (STB_LOCAL)
ffffffff818fe060-ffffffff818fe0c6: vme_master_rmw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
unsigned int vme_master_rmw(struct vme_resource *resource, unsigned int mask, unsigned int compare, unsigned int swap, loff_t offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vme/vme.c (0)
Location: drivers/vme/vme.c:765
Inline: False
```
**Symbols:**

```
ffffffff819d589f-ffffffff819d58cb: vme_master_rmw.cold (STB_LOCAL)
ffffffff819d4170-ffffffff819d41d0: vme_master_rmw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
unsigned int vme_master_rmw(struct vme_resource *resource, unsigned int mask, unsigned int compare, unsigned int swap, loff_t offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vme/vme.c (0)
Location: drivers/vme/vme.c:756
Inline: False
```
**Symbols:**

```
ffffffff81c2f889-ffffffff81c2f8b5: vme_master_rmw.cold (STB_LOCAL)
ffffffff819d3cf0-ffffffff819d3d50: vme_master_rmw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
unsigned int vme_master_rmw(struct vme_resource *resource, unsigned int mask, unsigned int compare, unsigned int swap, loff_t offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vme/vme.c (0)
Location: drivers/vme/vme.c:756
Inline: False
```
**Symbols:**

```
ffffffff81c21b4f-ffffffff81c21b7b: vme_master_rmw.cold (STB_LOCAL)
ffffffff819b8fb0-ffffffff819b9010: vme_master_rmw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
unsigned int vme_master_rmw(struct vme_resource *resource, unsigned int mask, unsigned int compare, unsigned int swap, loff_t offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vme/vme.c (0)
Location: drivers/vme/vme.c:756
Inline: False
```
**Symbols:**

```
ffffffff81d338b2-ffffffff81d338de: vme_master_rmw.cold (STB_LOCAL)
ffffffff81a67ee0-ffffffff81a67f40: vme_master_rmw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
unsigned int vme_master_rmw(struct vme_resource *resource, unsigned int mask, unsigned int compare, unsigned int swap, loff_t offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vme/vme.c (0)
Location: drivers/vme/vme.c:756
Inline: False
```
**Symbols:**

```
ffffffff81effcf2-ffffffff81effd16: vme_master_rmw.cold (STB_LOCAL)
ffffffff81bd9680-ffffffff81bd96ef: vme_master_rmw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
unsigned int vme_master_rmw(struct vme_resource *resource, unsigned int mask, unsigned int compare, unsigned int swap, loff_t offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/staging/vme_user/vme.c (ffffffff81d6ad40)
Location: drivers/staging/vme_user/vme.c:756
Inline: False
```
**Symbols:**

```
ffffffff81d6ad40-ffffffff81d6ade0: vme_master_rmw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
unsigned int vme_master_rmw(struct vme_resource *resource, unsigned int mask, unsigned int compare, unsigned int swap, loff_t offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/staging/vme_user/vme.c (ffffffff81dd8020)
Location: drivers/staging/vme_user/vme.c:756
Inline: False
```
**Symbols:**

```
ffffffff81dd8020-ffffffff81dd80c0: vme_master_rmw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
unsigned int vme_master_rmw(struct vme_resource *resource, unsigned int mask, unsigned int compare, unsigned int swap, loff_t offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/staging/vme_user/vme.c (ffffffff81e91c60)
Location: drivers/staging/vme_user/vme.c:719
Inline: False
```
**Symbols:**

```
ffffffff81e91c60-ffffffff81e91d03: vme_master_rmw (STB_GLOBAL)
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
unsigned int vme_master_rmw(struct vme_resource *resource, unsigned int mask, unsigned int compare, unsigned int swap, loff_t offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vme/vme.c (ffff800010b8dd78)
Location: drivers/vme/vme.c:765
Inline: False
```
**Symbols:**

```
ffff800010b8dd78-ffff800010b8de18: vme_master_rmw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
unsigned int vme_master_rmw(struct vme_resource *resource, unsigned int mask, unsigned int compare, unsigned int swap, loff_t offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vme/vme.c (c0c76cf0)
Location: drivers/vme/vme.c:765
Inline: False
```
**Symbols:**

```
c0c76cf0-c0c76d84: vme_master_rmw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
unsigned int vme_master_rmw(struct vme_resource *resource, unsigned int mask, unsigned int compare, unsigned int swap, loff_t offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vme/vme.c (c000000000c6bf30)
Location: drivers/vme/vme.c:765
Inline: False
```
**Symbols:**

```
c000000000c6bf30-c000000000c6c008: vme_master_rmw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
unsigned int vme_master_rmw(struct vme_resource *resource, unsigned int mask, unsigned int compare, unsigned int swap, loff_t offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vme/vme.c (ffffffe000733c3e)
Location: drivers/vme/vme.c:765
Inline: False
```
**Symbols:**

```
ffffffe000733c3e-ffffffe000733cc8: vme_master_rmw (STB_GLOBAL)
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
unsigned int vme_master_rmw(struct vme_resource *resource, unsigned int mask, unsigned int compare, unsigned int swap, loff_t offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vme/vme.c (0)
Location: drivers/vme/vme.c:765
Inline: False
```
**Symbols:**

```
ffffffff818a01bd-ffffffff818a01e9: vme_master_rmw.cold (STB_LOCAL)
ffffffff8189f390-ffffffff8189f3f6: vme_master_rmw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
unsigned int vme_master_rmw(struct vme_resource *resource, unsigned int mask, unsigned int compare, unsigned int swap, loff_t offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vme/vme.c (0)
Location: drivers/vme/vme.c:765
Inline: False
```
**Symbols:**

```
ffffffff8185b92d-ffffffff8185b959: vme_master_rmw.cold (STB_LOCAL)
ffffffff8185ab00-ffffffff8185ab66: vme_master_rmw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
unsigned int vme_master_rmw(struct vme_resource *resource, unsigned int mask, unsigned int compare, unsigned int swap, loff_t offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vme/vme.c (0)
Location: drivers/vme/vme.c:765
Inline: False
```
**Symbols:**

```
ffffffff818ef8ad-ffffffff818ef8d9: vme_master_rmw.cold (STB_LOCAL)
ffffffff818eea80-ffffffff818eeae6: vme_master_rmw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
unsigned int vme_master_rmw(struct vme_resource *resource, unsigned int mask, unsigned int compare, unsigned int swap, loff_t offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vme/vme.c (0)
Location: drivers/vme/vme.c:765
Inline: False
```
**Symbols:**

```
ffffffff81910985-ffffffff819109b1: vme_master_rmw.cold (STB_LOCAL)
ffffffff8190fc70-ffffffff8190fcd6: vme_master_rmw (STB_GLOBAL)
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
