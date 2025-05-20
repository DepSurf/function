# Function: <code>vme_lm_attach</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int vme_lm_attach(struct vme_resource *resource, int monitor, void (*callback)(int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vme/vme.c (ffffffff816f11e0)
Location: drivers/vme/vme.c:1323
Inline: False
```
**Symbols:**

```
ffffffff816f11e0-ffffffff816f124c: vme_lm_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int vme_lm_attach(struct vme_resource *resource, int monitor, void (*callback)(int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vme/vme.c (ffffffff81756220)
Location: drivers/vme/vme.c:1323
Inline: False
```
**Symbols:**

```
ffffffff81756220-ffffffff8175628c: vme_lm_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int vme_lm_attach(struct vme_resource *resource, int monitor, void (*callback)(void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vme/vme.c (ffffffff817827e0)
Location: drivers/vme/vme.c:1326
Inline: False
```
**Symbols:**

```
ffffffff817827e0-ffffffff81782856: vme_lm_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int vme_lm_attach(struct vme_resource *resource, int monitor, void (*callback)(void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vme/vme.c (ffffffff817a1570)
Location: drivers/vme/vme.c:1675
Inline: False
```
**Symbols:**

```
ffffffff817a1570-ffffffff817a15e6: vme_lm_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int vme_lm_attach(struct vme_resource *resource, int monitor, void (*callback)(void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vme/vme.c (ffffffff81818690)
Location: drivers/vme/vme.c:1649
Inline: False
```
**Symbols:**

```
ffffffff81818690-ffffffff81818709: vme_lm_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int vme_lm_attach(struct vme_resource *resource, int monitor, void (*callback)(void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vme/vme.c (0)
Location: drivers/vme/vme.c:1649
Inline: False
```
**Symbols:**

```
ffffffff81862d5a-ffffffff81862d86: vme_lm_attach.cold.34 (STB_LOCAL)
ffffffff81861fc0-ffffffff8186201b: vme_lm_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int vme_lm_attach(struct vme_resource *resource, int monitor, void (*callback)(void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vme/vme.c (0)
Location: drivers/vme/vme.c:1649
Inline: False
```
**Symbols:**

```
ffffffff818824ed-ffffffff81882519: vme_lm_attach.cold.34 (STB_LOCAL)
ffffffff818817b0-ffffffff8188180b: vme_lm_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int vme_lm_attach(struct vme_resource *resource, int monitor, void (*callback)(void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vme/vme.c (0)
Location: drivers/vme/vme.c:1645
Inline: False
```
**Symbols:**

```
ffffffff818ccb21-ffffffff818ccb4d: vme_lm_attach.cold (STB_LOCAL)
ffffffff818cbda0-ffffffff818cbdfb: vme_lm_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int vme_lm_attach(struct vme_resource *resource, int monitor, void (*callback)(void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vme/vme.c (0)
Location: drivers/vme/vme.c:1645
Inline: False
```
**Symbols:**

```
ffffffff818fef11-ffffffff818fef3d: vme_lm_attach.cold (STB_LOCAL)
ffffffff818fe190-ffffffff818fe1eb: vme_lm_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int vme_lm_attach(struct vme_resource *resource, int monitor, void (*callback)(void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vme/vme.c (0)
Location: drivers/vme/vme.c:1645
Inline: False
```
**Symbols:**

```
ffffffff819d5990-ffffffff819d59bc: vme_lm_attach.cold (STB_LOCAL)
ffffffff819d4340-ffffffff819d4395: vme_lm_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int vme_lm_attach(struct vme_resource *resource, int monitor, void (*callback)(void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vme/vme.c (0)
Location: drivers/vme/vme.c:1636
Inline: False
```
**Symbols:**

```
ffffffff81c2f97a-ffffffff81c2f9a6: vme_lm_attach.cold (STB_LOCAL)
ffffffff819d3ec0-ffffffff819d3f15: vme_lm_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int vme_lm_attach(struct vme_resource *resource, int monitor, void (*callback)(void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vme/vme.c (0)
Location: drivers/vme/vme.c:1636
Inline: False
```
**Symbols:**

```
ffffffff81c21c41-ffffffff81c21c6d: vme_lm_attach.cold (STB_LOCAL)
ffffffff819b9180-ffffffff819b91d5: vme_lm_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int vme_lm_attach(struct vme_resource *resource, int monitor, void (*callback)(void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vme/vme.c (0)
Location: drivers/vme/vme.c:1636
Inline: False
```
**Symbols:**

```
ffffffff81d339a6-ffffffff81d339d2: vme_lm_attach.cold (STB_LOCAL)
ffffffff81a68120-ffffffff81a68175: vme_lm_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int vme_lm_attach(struct vme_resource *resource, int monitor, void (*callback)(void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vme/vme.c (0)
Location: drivers/vme/vme.c:1636
Inline: False
```
**Symbols:**

```
ffffffff81effdad-ffffffff81effdd1: vme_lm_attach.cold (STB_LOCAL)
ffffffff81bd9840-ffffffff81bd98a1: vme_lm_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int vme_lm_attach(struct vme_resource *resource, int monitor, void (*callback)(void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/staging/vme_user/vme.c (ffffffff81d6afe0)
Location: drivers/staging/vme_user/vme.c:1636
Inline: False
```
**Symbols:**

```
ffffffff81d6afe0-ffffffff81d6b05a: vme_lm_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int vme_lm_attach(struct vme_resource *resource, int monitor, void (*callback)(void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/staging/vme_user/vme.c (ffffffff81dd82c0)
Location: drivers/staging/vme_user/vme.c:1636
Inline: False
```
**Symbols:**

```
ffffffff81dd82c0-ffffffff81dd833a: vme_lm_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int vme_lm_attach(struct vme_resource *resource, int monitor, void (*callback)(void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/staging/vme_user/vme.c (ffffffff81e91a80)
Location: drivers/staging/vme_user/vme.c:1603
Inline: False
```
**Symbols:**

```
ffffffff81e91a80-ffffffff81e91b0c: vme_lm_attach (STB_GLOBAL)
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
int vme_lm_attach(struct vme_resource *resource, int monitor, void (*callback)(void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vme/vme.c (ffff800010b8df48)
Location: drivers/vme/vme.c:1645
Inline: False
```
**Symbols:**

```
ffff800010b8df48-ffff800010b8dfdc: vme_lm_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int vme_lm_attach(struct vme_resource *resource, int monitor, void (*callback)(void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vme/vme.c (c0c76fbc)
Location: drivers/vme/vme.c:1645
Inline: False
```
**Symbols:**

```
c0c76fbc-c0c77040: vme_lm_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int vme_lm_attach(struct vme_resource *resource, int monitor, void (*callback)(void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vme/vme.c (c000000000c6c190)
Location: drivers/vme/vme.c:1645
Inline: False
```
**Symbols:**

```
c000000000c6c190-c000000000c6c250: vme_lm_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int vme_lm_attach(struct vme_resource *resource, int monitor, void (*callback)(void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/vme/vme.c (ffffffe000733dd0)
Location: drivers/vme/vme.c:1645
Inline: False
```
**Symbols:**

```
ffffffe000733dd0-ffffffe000733e54: vme_lm_attach (STB_GLOBAL)
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
int vme_lm_attach(struct vme_resource *resource, int monitor, void (*callback)(void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vme/vme.c (0)
Location: drivers/vme/vme.c:1645
Inline: False
```
**Symbols:**

```
ffffffff818a0241-ffffffff818a026d: vme_lm_attach.cold (STB_LOCAL)
ffffffff8189f4c0-ffffffff8189f51b: vme_lm_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int vme_lm_attach(struct vme_resource *resource, int monitor, void (*callback)(void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vme/vme.c (0)
Location: drivers/vme/vme.c:1645
Inline: False
```
**Symbols:**

```
ffffffff8185b9b1-ffffffff8185b9dd: vme_lm_attach.cold (STB_LOCAL)
ffffffff8185ac30-ffffffff8185ac8b: vme_lm_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int vme_lm_attach(struct vme_resource *resource, int monitor, void (*callback)(void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vme/vme.c (0)
Location: drivers/vme/vme.c:1645
Inline: False
```
**Symbols:**

```
ffffffff818ef931-ffffffff818ef95d: vme_lm_attach.cold (STB_LOCAL)
ffffffff818eebb0-ffffffff818eec0b: vme_lm_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int vme_lm_attach(struct vme_resource *resource, int monitor, void (*callback)(void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/vme/vme.c (0)
Location: drivers/vme/vme.c:1645
Inline: False
```
**Symbols:**

```
ffffffff81910a09-ffffffff81910a35: vme_lm_attach.cold (STB_LOCAL)
ffffffff8190fda0-ffffffff8190fdfb: vme_lm_attach (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.8</code> and <code>4.10</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>void *data</code>
</li>
<li>
<b>Param type changed. </b>
<code>void (*callback)(int)</code> ➡️ <code>void (*callback)(void *)</code>
</li>
</ul>
</details>
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
