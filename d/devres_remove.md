# Function: <code>devres_remove</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void *devres_remove(struct device *dev, dr_release_t release, dr_match_t match, void *match_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff8154f520)
Location: drivers/base/devres.c:325
Inline: False
Direct callers:
  - drivers/base/devres.c:devres_release
```
**Symbols:**

```
ffffffff8154f520-ffffffff8154f5ed: devres_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void *devres_remove(struct device *dev, dr_release_t release, dr_match_t match, void *match_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff815a12f0)
Location: drivers/base/devres.c:325
Inline: False
Direct callers:
  - drivers/base/devres.c:devres_release
```
**Symbols:**

```
ffffffff815a12f0-ffffffff815a13bd: devres_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void *devres_remove(struct device *dev, dr_release_t release, dr_match_t match, void *match_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff815cf960)
Location: drivers/base/devres.c:326
Inline: False
Direct callers:
  - drivers/base/devres.c:devres_release
```
**Symbols:**

```
ffffffff815cf960-ffffffff815cfa2d: devres_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void *devres_remove(struct device *dev, dr_release_t release, dr_match_t match, void *match_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff815e4340)
Location: drivers/base/devres.c:326
Inline: False
Direct callers:
  - drivers/base/devres.c:devres_release
```
**Symbols:**

```
ffffffff815e4340-ffffffff815e440b: devres_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void *devres_remove(struct device *dev, dr_release_t release, dr_match_t match, void *match_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff8164b610)
Location: drivers/base/devres.c:326
Inline: False
Direct callers:
  - drivers/base/devres.c:devres_release
```
**Symbols:**

```
ffffffff8164b610-ffffffff8164b6dd: devres_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void *devres_remove(struct device *dev, dr_release_t release, dr_match_t match, void *match_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff81686c10)
Location: drivers/base/devres.c:330
Inline: False
Direct callers:
  - drivers/base/devres.c:devres_release
  - drivers/base/devres.c:devres_destroy
```
**Symbols:**

```
ffffffff81686c10-ffffffff81686cdd: devres_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void *devres_remove(struct device *dev, dr_release_t release, dr_match_t match, void *match_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff816a68b0)
Location: drivers/base/devres.c:338
Inline: False
Direct callers:
  - drivers/base/devres.c:devres_release
  - drivers/base/devres.c:devres_destroy
```
**Symbols:**

```
ffffffff816a68b0-ffffffff816a697d: devres_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void *devres_remove(struct device *dev, dr_release_t release, dr_match_t match, void *match_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff816df930)
Location: drivers/base/devres.c:338
Inline: False
Direct callers:
  - drivers/base/devres.c:devres_release
```
**Symbols:**

```
ffffffff816df930-ffffffff816dfa04: devres_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void *devres_remove(struct device *dev, dr_release_t release, dr_match_t match, void *match_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff81703b80)
Location: drivers/base/devres.c:338
Inline: False
Direct callers:
  - drivers/base/devres.c:devres_release
```
**Symbols:**

```
ffffffff81703b80-ffffffff81703c54: devres_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void *devres_remove(struct device *dev, dr_release_t release, dr_match_t match, void *match_data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff817be990)
Location: drivers/base/devres.c:338
Inline: True
```
**Symbols:**

```
ffffffff817be990-ffffffff817bea64: devres_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void *devres_remove(struct device *dev, dr_release_t release, dr_match_t match, void *match_data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff817d3860)
Location: drivers/base/devres.c:354
Inline: True
```
**Symbols:**

```
ffffffff817d3860-ffffffff817d3934: devres_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void *devres_remove(struct device *dev, dr_release_t release, dr_match_t match, void *match_data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff817b7270)
Location: drivers/base/devres.c:354
Inline: True
```
**Symbols:**

```
ffffffff817b7270-ffffffff817b7344: devres_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void *devres_remove(struct device *dev, dr_release_t release, dr_match_t match, void *match_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff81840c20)
Location: drivers/base/devres.c:347
Inline: False
Direct callers:
  - drivers/base/devres.c:devm_free_percpu
  - drivers/base/devres.c:devm_free_pages
  - drivers/base/devres.c:devm_kfree
  - drivers/base/devres.c:devm_release_action
  - drivers/base/devres.c:devm_remove_action
```
**Symbols:**

```
ffffffff81840c20-ffffffff81840d3d: devres_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void *devres_remove(struct device *dev, dr_release_t release, dr_match_t match, void *match_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff81983f00)
Location: drivers/base/devres.c:347
Inline: False
Direct callers:
  - drivers/base/devres.c:devm_free_percpu
  - drivers/base/devres.c:devm_free_pages
  - drivers/base/devres.c:devm_kfree
  - drivers/base/devres.c:devm_release_action
  - drivers/base/devres.c:devm_remove_action
```
**Symbols:**

```
ffffffff81983f00-ffffffff81984067: devres_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void *devres_remove(struct device *dev, dr_release_t release, dr_match_t match, void *match_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff81af1fe0)
Location: drivers/base/devres.c:352
Inline: False
Direct callers:
  - drivers/base/devres.c:devm_free_percpu
  - drivers/base/devres.c:devm_free_pages
  - drivers/base/devres.c:devm_kfree
  - drivers/base/devres.c:devm_release_action
  - drivers/base/devres.c:devm_remove_action
```
**Symbols:**

```
ffffffff81af1fe0-ffffffff81af2135: devres_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void *devres_remove(struct device *dev, dr_release_t release, dr_match_t match, void *match_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff81b40170)
Location: drivers/base/devres.c:352
Inline: False
Direct callers:
  - drivers/base/devres.c:devm_free_percpu
  - drivers/base/devres.c:devm_free_pages
  - drivers/base/devres.c:devm_release_action
  - drivers/base/devres.c:devm_remove_action
```
**Symbols:**

```
ffffffff81b40170-ffffffff81b402e5: devres_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void *devres_remove(struct device *dev, dr_release_t release, dr_match_t match, void *match_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff81b98010)
Location: drivers/base/devres.c:352
Inline: False
Direct callers:
  - drivers/base/devres.c:devm_free_percpu
  - drivers/base/devres.c:devm_free_pages
  - drivers/base/devres.c:devm_release_action
  - drivers/base/devres.c:devm_remove_action
```
**Symbols:**

```
ffffffff81b98010-ffffffff81b98185: devres_remove (STB_GLOBAL)
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
void *devres_remove(struct device *dev, dr_release_t release, dr_match_t match, void *match_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffff8000108f0590)
Location: drivers/base/devres.c:338
Inline: False
Direct callers:
  - drivers/base/devres.c:devres_release
```
**Symbols:**

```
ffff8000108f0590-ffff8000108f06c0: devres_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void *devres_remove(struct device *dev, dr_release_t release, dr_match_t match, void *match_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (c09dcf1c)
Location: drivers/base/devres.c:338
Inline: False
Direct callers:
  - drivers/base/devres.c:devres_release
```
**Symbols:**

```
c09dcf1c-c09dcff4: devres_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void *devres_remove(struct device *dev, dr_release_t release, dr_match_t match, void *match_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (c000000000988ad0)
Location: drivers/base/devres.c:338
Inline: False
Direct callers:
  - drivers/base/devres.c:devres_release
  - drivers/base/devres.c:devres_destroy
```
**Symbols:**

```
c000000000988ad0-c000000000988c50: devres_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void *devres_remove(struct device *dev, dr_release_t release, dr_match_t match, void *match_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffe000581fee)
Location: drivers/base/devres.c:338
Inline: False
Direct callers:
  - drivers/base/devres.c:devres_release
```
**Symbols:**

```
ffffffe000581fee-ffffffe000582096: devres_remove (STB_GLOBAL)
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
void *devres_remove(struct device *dev, dr_release_t release, dr_match_t match, void *match_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff816c92d0)
Location: drivers/base/devres.c:338
Inline: False
Direct callers:
  - drivers/base/devres.c:devres_release
```
**Symbols:**

```
ffffffff816c92d0-ffffffff816c93a4: devres_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void *devres_remove(struct device *dev, dr_release_t release, dr_match_t match, void *match_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff816a4600)
Location: drivers/base/devres.c:338
Inline: False
Direct callers:
  - drivers/base/devres.c:devres_release
```
**Symbols:**

```
ffffffff816a4600-ffffffff816a46d4: devres_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void *devres_remove(struct device *dev, dr_release_t release, dr_match_t match, void *match_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff816f7840)
Location: drivers/base/devres.c:338
Inline: False
Direct callers:
  - drivers/base/devres.c:devres_release
```
**Symbols:**

```
ffffffff816f7840-ffffffff816f7914: devres_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void *devres_remove(struct device *dev, dr_release_t release, dr_match_t match, void *match_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff817120e0)
Location: drivers/base/devres.c:338
Inline: False
Direct callers:
  - drivers/base/devres.c:devres_release
```
**Symbols:**

```
ffffffff817120e0-ffffffff817121b4: devres_remove (STB_GLOBAL)
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
