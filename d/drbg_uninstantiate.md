# Function: <code>drbg_uninstantiate</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int drbg_uninstantiate(struct drbg_state *drbg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/drbg.c (ffffffff813ee220)
Location: crypto/drbg.c:1520
Inline: False
Direct callers:
  - crypto/drbg.c:drbg_kcapi_seed
  - crypto/drbg.c:drbg_kcapi_cleanup
```
**Symbols:**

```
ffffffff813ee220-ffffffff813ee2d6: drbg_uninstantiate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int drbg_uninstantiate(struct drbg_state *drbg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/drbg.c (ffffffff81407a60)
Location: crypto/drbg.c:1527
Inline: False
Direct callers:
  - crypto/drbg.c:drbg_kcapi_seed
  - crypto/drbg.c:drbg_kcapi_cleanup
```
**Symbols:**

```
ffffffff81407a60-ffffffff81407b16: drbg_uninstantiate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int drbg_uninstantiate(struct drbg_state *drbg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/drbg.c (ffffffff81415190)
Location: crypto/drbg.c:1527
Inline: False
Direct callers:
  - crypto/drbg.c:drbg_kcapi_seed
  - crypto/drbg.c:drbg_kcapi_cleanup
```
**Symbols:**

```
ffffffff81415190-ffffffff81415246: drbg_uninstantiate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int drbg_uninstantiate(struct drbg_state *drbg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/drbg.c (ffffffff8143f960)
Location: crypto/drbg.c:1527
Inline: False
Direct callers:
  - crypto/drbg.c:drbg_kcapi_seed
  - crypto/drbg.c:drbg_kcapi_cleanup
```
**Symbols:**

```
ffffffff8143f960-ffffffff8143fa1c: drbg_uninstantiate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int drbg_uninstantiate(struct drbg_state *drbg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/drbg.c (ffffffff81472790)
Location: crypto/drbg.c:1529
Inline: False
Direct callers:
  - crypto/drbg.c:drbg_kcapi_seed
  - crypto/drbg.c:drbg_kcapi_seed
  - crypto/drbg.c:drbg_kcapi_cleanup
```
**Symbols:**

```
ffffffff81472790-ffffffff8147285c: drbg_uninstantiate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int drbg_uninstantiate(struct drbg_state *drbg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/drbg.c (ffffffff8148fbe0)
Location: crypto/drbg.c:1527
Inline: False
Direct callers:
  - crypto/drbg.c:drbg_kcapi_seed
  - crypto/drbg.c:drbg_kcapi_seed
  - crypto/drbg.c:drbg_kcapi_cleanup
```
**Symbols:**

```
ffffffff8148fbe0-ffffffff8148fcac: drbg_uninstantiate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int drbg_uninstantiate(struct drbg_state *drbg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/drbg.c (ffffffff814bd0d0)
Location: crypto/drbg.c:1615
Inline: False
Direct callers:
  - crypto/drbg.c:drbg_kcapi_seed
  - crypto/drbg.c:drbg_kcapi_seed
  - crypto/drbg.c:drbg_kcapi_cleanup
```
**Symbols:**

```
ffffffff814bd0d0-ffffffff814bd19c: drbg_uninstantiate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int drbg_uninstantiate(struct drbg_state *drbg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/drbg.c (ffffffff814d5d70)
Location: crypto/drbg.c:1615
Inline: False
Direct callers:
  - crypto/drbg.c:drbg_kcapi_seed
  - crypto/drbg.c:drbg_kcapi_seed
  - crypto/drbg.c:drbg_kcapi_cleanup
```
**Symbols:**

```
ffffffff814d5d70-ffffffff814d5e3c: drbg_uninstantiate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In crypto/drbg.c (ffffffff81534710)
Location: crypto/drbg.c:1629
Inline: True
Direct callers:
  - crypto/drbg.c:drbg_kcapi_cleanup
  - crypto/drbg.c:drbg_instantiate
  - crypto/drbg.c:drbg_instantiate
```
**Symbols:**

```
ffffffff81534710-ffffffff815347eb: drbg_uninstantiate.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In crypto/drbg.c (ffffffff81551660)
Location: crypto/drbg.c:1629
Inline: True
Direct callers:
  - crypto/drbg.c:drbg_kcapi_cleanup
  - crypto/drbg.c:drbg_instantiate
  - crypto/drbg.c:drbg_instantiate
```
**Symbols:**

```
ffffffff81551660-ffffffff8155173b: drbg_uninstantiate.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In crypto/drbg.c (ffffffff81559e50)
Location: crypto/drbg.c:1630
Inline: True
Direct callers:
  - crypto/drbg.c:drbg_kcapi_seed
  - crypto/drbg.c:drbg_kcapi_cleanup
```
**Symbols:**

```
ffffffff81559e50-ffffffff81559f2b: drbg_uninstantiate.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In crypto/drbg.c (ffffffff815bb0d0)
Location: crypto/drbg.c:1630
Inline: True
Direct callers:
  - crypto/drbg.c:drbg_kcapi_seed
  - crypto/drbg.c:drbg_kcapi_cleanup
```
**Symbols:**

```
ffffffff815bb0d0-ffffffff815bb1ab: drbg_uninstantiate.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In crypto/drbg.c (ffffffff81664af0)
Location: crypto/drbg.c:1639
Inline: True
Direct callers:
  - crypto/drbg.c:drbg_kcapi_seed
  - crypto/drbg.c:drbg_kcapi_cleanup
```
**Symbols:**

```
ffffffff81664af0-ffffffff81664bb3: drbg_uninstantiate.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In crypto/drbg.c (ffffffff8171ee60)
Location: crypto/drbg.c:1639
Inline: True
Direct callers:
  - crypto/drbg.c:drbg_kcapi_seed
  - crypto/drbg.c:drbg_kcapi_cleanup
```
**Symbols:**

```
ffffffff8171ee60-ffffffff8171ef23: drbg_uninstantiate.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In crypto/drbg.c (ffffffff8175a770)
Location: crypto/drbg.c:1639
Inline: True
Direct callers:
  - crypto/drbg.c:drbg_kcapi_seed
  - crypto/drbg.c:drbg_kcapi_cleanup
```
**Symbols:**

```
ffffffff8175a770-ffffffff8175a833: drbg_uninstantiate.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In crypto/drbg.c (ffffffff8179c670)
Location: crypto/drbg.c:1623
Inline: True
Direct callers:
  - crypto/drbg.c:drbg_kcapi_seed
  - crypto/drbg.c:drbg_kcapi_cleanup
```
**Symbols:**

```
ffffffff8179c670-ffffffff8179c733: drbg_uninstantiate.isra.0 (STB_LOCAL)
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
int drbg_uninstantiate(struct drbg_state *drbg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/drbg.c (ffff8000105d1868)
Location: crypto/drbg.c:1615
Inline: False
Direct callers:
  - crypto/drbg.c:drbg_kcapi_seed
  - crypto/drbg.c:drbg_kcapi_seed
  - crypto/drbg.c:drbg_kcapi_cleanup
```
**Symbols:**

```
ffff8000105d1868-ffff8000105d18fc: drbg_uninstantiate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int drbg_uninstantiate(struct drbg_state *drbg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/drbg.c (c077f4f0)
Location: crypto/drbg.c:1615
Inline: False
Direct callers:
  - crypto/drbg.c:drbg_kcapi_seed
  - crypto/drbg.c:drbg_kcapi_seed
  - crypto/drbg.c:drbg_kcapi_cleanup
```
**Symbols:**

```
c077f4f0-c077f59c: drbg_uninstantiate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int drbg_uninstantiate(struct drbg_state *drbg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/drbg.c (c00000000075e990)
Location: crypto/drbg.c:1615
Inline: False
Direct callers:
  - crypto/drbg.c:drbg_kcapi_seed
  - crypto/drbg.c:drbg_kcapi_cleanup
```
**Symbols:**

```
c00000000075e990-c00000000075ea84: drbg_uninstantiate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int drbg_uninstantiate(struct drbg_state *drbg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/drbg.c (ffffffe00041657c)
Location: crypto/drbg.c:1615
Inline: False
Direct callers:
  - crypto/drbg.c:drbg_kcapi_seed
  - crypto/drbg.c:drbg_kcapi_cleanup
```
**Symbols:**

```
ffffffe00041657c-ffffffe00041661a: drbg_uninstantiate (STB_LOCAL)
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
int drbg_uninstantiate(struct drbg_state *drbg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/drbg.c (ffffffff814ce350)
Location: crypto/drbg.c:1615
Inline: False
Direct callers:
  - crypto/drbg.c:drbg_kcapi_seed
  - crypto/drbg.c:drbg_kcapi_seed
  - crypto/drbg.c:drbg_kcapi_cleanup
```
**Symbols:**

```
ffffffff814ce350-ffffffff814ce41c: drbg_uninstantiate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int drbg_uninstantiate(struct drbg_state *drbg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/drbg.c (ffffffff814bed70)
Location: crypto/drbg.c:1615
Inline: False
Direct callers:
  - crypto/drbg.c:drbg_kcapi_seed
  - crypto/drbg.c:drbg_kcapi_seed
  - crypto/drbg.c:drbg_kcapi_cleanup
```
**Symbols:**

```
ffffffff814bed70-ffffffff814bee3c: drbg_uninstantiate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int drbg_uninstantiate(struct drbg_state *drbg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/drbg.c (ffffffff814ca3e0)
Location: crypto/drbg.c:1615
Inline: False
Direct callers:
  - crypto/drbg.c:drbg_kcapi_seed
  - crypto/drbg.c:drbg_kcapi_seed
  - crypto/drbg.c:drbg_kcapi_cleanup
```
**Symbols:**

```
ffffffff814ca3e0-ffffffff814ca4ac: drbg_uninstantiate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int drbg_uninstantiate(struct drbg_state *drbg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/drbg.c (ffffffff814e2eb0)
Location: crypto/drbg.c:1615
Inline: False
Direct callers:
  - crypto/drbg.c:drbg_kcapi_seed
  - crypto/drbg.c:drbg_kcapi_seed
  - crypto/drbg.c:drbg_kcapi_cleanup
```
**Symbols:**

```
ffffffff814e2eb0-ffffffff814e2f7c: drbg_uninstantiate (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
