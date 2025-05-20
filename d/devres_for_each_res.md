# Function: <code>devres_for_each_res</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void devres_for_each_res(struct device *dev, dr_release_t release, dr_match_t match, void *match_data, void (*fn)(struct device *, void *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff8154f380)
Location: drivers/base/devres.c:163
Inline: False
Direct callers:
  - drivers/base/firmware_class.c:dev_cache_fw_image
```
**Symbols:**

```
ffffffff8154f380-ffffffff8154f454: devres_for_each_res (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void devres_for_each_res(struct device *dev, dr_release_t release, dr_match_t match, void *match_data, void (*fn)(struct device *, void *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff815a1150)
Location: drivers/base/devres.c:163
Inline: False
Direct callers:
  - drivers/base/firmware_class.c:dev_cache_fw_image
```
**Symbols:**

```
ffffffff815a1150-ffffffff815a1228: devres_for_each_res (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void devres_for_each_res(struct device *dev, dr_release_t release, dr_match_t match, void *match_data, void (*fn)(struct device *, void *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff815cf7c0)
Location: drivers/base/devres.c:164
Inline: False
Direct callers:
  - drivers/base/firmware_class.c:dev_cache_fw_image
```
**Symbols:**

```
ffffffff815cf7c0-ffffffff815cf898: devres_for_each_res (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void devres_for_each_res(struct device *dev, dr_release_t release, dr_match_t match, void *match_data, void (*fn)(struct device *, void *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff815e4620)
Location: drivers/base/devres.c:164
Inline: True
Direct callers:
  - drivers/base/firmware_class.c:dev_cache_fw_image
```
**Symbols:**

```
ffffffff815e4620-ffffffff815e46e9: devres_for_each_res (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void devres_for_each_res(struct device *dev, dr_release_t release, dr_match_t match, void *match_data, void (*fn)(struct device *, void *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff8164b8f0)
Location: drivers/base/devres.c:164
Inline: True
Direct callers:
  - drivers/base/firmware_class.c:dev_cache_fw_image
```
**Symbols:**

```
ffffffff8164b8f0-ffffffff8164b9be: devres_for_each_res (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void devres_for_each_res(struct device *dev, dr_release_t release, dr_match_t match, void *match_data, void (*fn)(struct device *, void *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff81686ef0)
Location: drivers/base/devres.c:168
Inline: True
Direct callers:
  - drivers/base/firmware_loader/main.c:dev_cache_fw_image
```
**Symbols:**

```
ffffffff81686ef0-ffffffff81686fcc: devres_for_each_res (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void devres_for_each_res(struct device *dev, dr_release_t release, dr_match_t match, void *match_data, void (*fn)(struct device *, void *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff816a6b90)
Location: drivers/base/devres.c:176
Inline: True
Direct callers:
  - drivers/base/firmware_loader/main.c:dev_cache_fw_image
```
**Symbols:**

```
ffffffff816a6b90-ffffffff816a6c6c: devres_for_each_res (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void devres_for_each_res(struct device *dev, dr_release_t release, dr_match_t match, void *match_data, void (*fn)(struct device *, void *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff816dfc60)
Location: drivers/base/devres.c:176
Inline: True
Direct callers:
  - drivers/base/firmware_loader/main.c:dev_cache_fw_image
```
**Symbols:**

```
ffffffff816dfc60-ffffffff816dfd32: devres_for_each_res (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void devres_for_each_res(struct device *dev, dr_release_t release, dr_match_t match, void *match_data, void (*fn)(struct device *, void *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff81703ea0)
Location: drivers/base/devres.c:176
Inline: True
Direct callers:
  - drivers/base/firmware_loader/main.c:dev_cache_fw_image
```
**Symbols:**

```
ffffffff81703ea0-ffffffff81703f72: devres_for_each_res (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void devres_for_each_res(struct device *dev, dr_release_t release, dr_match_t match, void *match_data, void (*fn)(struct device *, void *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff817be070)
Location: drivers/base/devres.c:176
Inline: True
Direct callers:
  - drivers/base/firmware_loader/main.c:dev_cache_fw_image
```
**Symbols:**

```
ffffffff817be070-ffffffff817be142: devres_for_each_res (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void devres_for_each_res(struct device *dev, dr_release_t release, dr_match_t match, void *match_data, void (*fn)(struct device *, void *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff817d2dc0)
Location: drivers/base/devres.c:192
Inline: True
Direct callers:
  - drivers/base/firmware_loader/main.c:dev_cache_fw_image
```
**Symbols:**

```
ffffffff817d2dc0-ffffffff817d2e92: devres_for_each_res (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void devres_for_each_res(struct device *dev, dr_release_t release, dr_match_t match, void *match_data, void (*fn)(struct device *, void *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff817b67d0)
Location: drivers/base/devres.c:192
Inline: True
Direct callers:
  - drivers/base/firmware_loader/main.c:dev_cache_fw_image
```
**Symbols:**

```
ffffffff817b67d0-ffffffff817b68a2: devres_for_each_res (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void devres_for_each_res(struct device *dev, dr_release_t release, dr_match_t match, void *match_data, void (*fn)(struct device *, void *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff8183fdb0)
Location: drivers/base/devres.c:185
Inline: True
Direct callers:
  - drivers/base/firmware_loader/main.c:dev_cache_fw_image
```
**Symbols:**

```
ffffffff8183fdb0-ffffffff8183fe82: devres_for_each_res (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void devres_for_each_res(struct device *dev, dr_release_t release, dr_match_t match, void *match_data, void (*fn)(struct device *, void *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff81982f70)
Location: drivers/base/devres.c:185
Inline: True
Direct callers:
  - drivers/base/firmware_loader/main.c:dev_cache_fw_image
```
**Symbols:**

```
ffffffff81982f70-ffffffff81983057: devres_for_each_res (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void devres_for_each_res(struct device *dev, dr_release_t release, dr_match_t match, void *match_data, void (*fn)(struct device *, void *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff81af0f00)
Location: drivers/base/devres.c:190
Inline: True
Direct callers:
  - drivers/base/firmware_loader/main.c:dev_cache_fw_image
```
**Symbols:**

```
ffffffff81af0f00-ffffffff81af0fe7: devres_for_each_res (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void devres_for_each_res(struct device *dev, dr_release_t release, dr_match_t match, void *match_data, void (*fn)(struct device *, void *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff81b3f040)
Location: drivers/base/devres.c:190
Inline: True
Direct callers:
  - drivers/base/firmware_loader/main.c:dev_cache_fw_image
```
**Symbols:**

```
ffffffff81b3f040-ffffffff81b3f12d: devres_for_each_res (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void devres_for_each_res(struct device *dev, dr_release_t release, dr_match_t match, void *match_data, void (*fn)(struct device *, void *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff81b96ec0)
Location: drivers/base/devres.c:190
Inline: True
Direct callers:
  - drivers/base/firmware_loader/main.c:dev_cache_fw_image
```
**Symbols:**

```
ffffffff81b96ec0-ffffffff81b96fad: devres_for_each_res (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void devres_for_each_res(struct device *dev, dr_release_t release, dr_match_t match, void *match_data, void (*fn)(struct device *, void *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffff8000108f0328)
Location: drivers/base/devres.c:176
Inline: True
Direct callers:
  - drivers/base/firmware_loader/main.c:dev_cache_fw_image
```
**Symbols:**

```
ffff8000108f0328-ffff8000108f0474: devres_for_each_res (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void devres_for_each_res(struct device *dev, dr_release_t release, dr_match_t match, void *match_data, void (*fn)(struct device *, void *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (c09dd26c)
Location: drivers/base/devres.c:176
Inline: True
Direct callers:
  - drivers/base/firmware_loader/main.c:dev_cache_fw_image
```
**Symbols:**

```
c09dd26c-c09dd348: devres_for_each_res (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void devres_for_each_res(struct device *dev, dr_release_t release, dr_match_t match, void *match_data, void (*fn)(struct device *, void *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (c000000000989780)
Location: drivers/base/devres.c:176
Inline: True
Direct callers:
  - drivers/base/firmware_loader/main.c:dev_cache_fw_image
```
**Symbols:**

```
c000000000989780-c0000000009898ec: devres_for_each_res (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void devres_for_each_res(struct device *dev, dr_release_t release, dr_match_t match, void *match_data, void (*fn)(struct device *, void *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffe000582314)
Location: drivers/base/devres.c:176
Inline: True
```
**Symbols:**

```
ffffffe000582314-ffffffe0005823d0: devres_for_each_res (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void devres_for_each_res(struct device *dev, dr_release_t release, dr_match_t match, void *match_data, void (*fn)(struct device *, void *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff816c95f0)
Location: drivers/base/devres.c:176
Inline: True
Direct callers:
  - drivers/base/firmware_loader/main.c:dev_cache_fw_image
```
**Symbols:**

```
ffffffff816c95f0-ffffffff816c96c2: devres_for_each_res (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void devres_for_each_res(struct device *dev, dr_release_t release, dr_match_t match, void *match_data, void (*fn)(struct device *, void *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff816a4920)
Location: drivers/base/devres.c:176
Inline: True
Direct callers:
  - drivers/base/firmware_loader/main.c:dev_cache_fw_image
```
**Symbols:**

```
ffffffff816a4920-ffffffff816a49f2: devres_for_each_res (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void devres_for_each_res(struct device *dev, dr_release_t release, dr_match_t match, void *match_data, void (*fn)(struct device *, void *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff816f7b60)
Location: drivers/base/devres.c:176
Inline: True
Direct callers:
  - drivers/base/firmware_loader/main.c:dev_cache_fw_image
```
**Symbols:**

```
ffffffff816f7b60-ffffffff816f7c32: devres_for_each_res (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void devres_for_each_res(struct device *dev, dr_release_t release, dr_match_t match, void *match_data, void (*fn)(struct device *, void *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff81712400)
Location: drivers/base/devres.c:176
Inline: True
Direct callers:
  - drivers/base/firmware_loader/main.c:dev_cache_fw_image
```
**Symbols:**

```
ffffffff81712400-ffffffff817124d2: devres_for_each_res (STB_GLOBAL)
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
