# Function: <code>__bio_associate_blkg</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/bio.c (ffffffff81498100)
Location: block/bio.c:2006
Inline: True
Direct callers:
  - block/bio.c:bio_associate_blkg_from_css
  - block/bio.c:bio_associate_blkg_from_css
  - block/bio.c:__bio_clone_fast
```
**Symbols:**

```
ffffffff81498100-ffffffff814981b4: __bio_associate_blkg.isra.29 (STB_LOCAL)
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
In block/bio.c (ffffffff814c5fa0)
Location: block/bio.c:2040
Inline: True
Direct callers:
  - block/bio.c:bio_associate_blkg_from_css
  - block/bio.c:bio_associate_blkg_from_css
  - block/bio.c:__bio_clone_fast
```
**Symbols:**

```
ffffffff814c5fa0-ffffffff814c603e: __bio_associate_blkg.isra.0 (STB_LOCAL)
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
In block/bio.c (ffffffff814de3a0)
Location: block/bio.c:2082
Inline: True
Direct callers:
  - block/bio.c:bio_associate_blkg_from_css
  - block/bio.c:bio_associate_blkg_from_css
  - block/bio.c:__bio_clone_fast
```
**Symbols:**

```
ffffffff814de3a0-ffffffff814de43e: __bio_associate_blkg.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __bio_associate_blkg(struct bio *bio, struct blkcg_gq *blkg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8153d990)
Location: block/bio.c:1661
Inline: False
Direct callers:
  - block/bio.c:bio_associate_blkg
  - block/bio.c:bio_associate_blkg
  - block/bio.c:bio_associate_blkg_from_page
  - block/bio.c:bio_associate_blkg_from_page
  - block/bio.c:__bio_clone_fast
```
**Symbols:**

```
ffffffff8153d990-ffffffff8153d9f9: __bio_associate_blkg (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
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
In block/bio.c (ffff8000105db728)
Location: block/bio.c:2082
Inline: True
Direct callers:
  - block/bio.c:bio_associate_blkg_from_css
  - block/bio.c:bio_associate_blkg_from_css
  - block/bio.c:__bio_clone_fast
```
**Symbols:**

```
ffff8000105db728-ffff8000105db874: __bio_associate_blkg.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __bio_associate_blkg(struct bio *bio, struct blkcg_gq *blkg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (c07882f4)
Location: block/bio.c:2082
Inline: False
Direct callers:
  - block/bio.c:bio_associate_blkg_from_css
  - block/bio.c:__bio_clone_fast
```
**Symbols:**

```
c07882f4-c0788428: __bio_associate_blkg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/bio.c (c00000000076b610)
Location: block/bio.c:2082
Inline: True
Direct callers:
  - block/bio.c:bio_associate_blkg_from_css
  - block/bio.c:bio_associate_blkg_from_css
  - block/bio.c:__bio_clone_fast
```
**Symbols:**

```
c00000000076b610-c00000000076b774: __bio_associate_blkg.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/bio.c (ffffffe00041e3d0)
Location: block/bio.c:2082
Inline: True
Direct callers:
  - block/bio.c:bio_associate_blkg_from_css
  - block/bio.c:__bio_clone_fast
```
**Symbols:**

```
ffffffe00041e3d0-ffffffe00041e4b2: __bio_associate_blkg.isra.0 (STB_LOCAL)
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
In block/bio.c (ffffffff814d6980)
Location: block/bio.c:2082
Inline: True
Direct callers:
  - block/bio.c:bio_associate_blkg_from_css
  - block/bio.c:bio_associate_blkg_from_css
  - block/bio.c:__bio_clone_fast
```
**Symbols:**

```
ffffffff814d6980-ffffffff814d6a1e: __bio_associate_blkg.isra.0 (STB_LOCAL)
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
In block/bio.c (ffffffff814c7340)
Location: block/bio.c:2082
Inline: True
Direct callers:
  - block/bio.c:bio_associate_blkg_from_css
  - block/bio.c:bio_associate_blkg_from_css
  - block/bio.c:__bio_clone_fast
```
**Symbols:**

```
ffffffff814c7340-ffffffff814c73de: __bio_associate_blkg.isra.0 (STB_LOCAL)
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
In block/bio.c (ffffffff814d2a10)
Location: block/bio.c:2082
Inline: True
Direct callers:
  - block/bio.c:bio_associate_blkg_from_css
  - block/bio.c:bio_associate_blkg_from_css
  - block/bio.c:__bio_clone_fast
```
**Symbols:**

```
ffffffff814d2a10-ffffffff814d2aae: __bio_associate_blkg.isra.0 (STB_LOCAL)
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
In block/bio.c (ffffffff814eb530)
Location: block/bio.c:2082
Inline: True
Direct callers:
  - block/bio.c:bio_clone_blkg_association
  - block/bio.c:bio_associate_blkg_from_css
```
**Symbols:**

```
ffffffff814eb530-ffffffff814eb615: __bio_associate_blkg.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
<b>Arch</b>
<ul>
</ul>
