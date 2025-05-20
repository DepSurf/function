# Function: <code>ext4_es_can_be_merged</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ext4_es_can_be_merged(struct extent_status *es1, struct extent_status *es2);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff812dad60)
Location: fs/ext4/extents_status.c:380
Inline: False
Direct callers:
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
```
**Symbols:**

```
ffffffff812dad60-ffffffff812dae33: ext4_es_can_be_merged (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ext4_es_can_be_merged(struct extent_status *es1, struct extent_status *es2);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff8130a5e0)
Location: fs/ext4/extents_status.c:380
Inline: False
Direct callers:
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
```
**Symbols:**

```
ffffffff8130a5e0-ffffffff8130a69f: ext4_es_can_be_merged (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ext4_es_can_be_merged(struct extent_status *es1, struct extent_status *es2);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff813205e0)
Location: fs/ext4/extents_status.c:380
Inline: False
Direct callers:
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
```
**Symbols:**

```
ffffffff813205e0-ffffffff8132069f: ext4_es_can_be_merged (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ext4_es_can_be_merged(struct extent_status *es1, struct extent_status *es2);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff812ef5a0)
Location: fs/ext4/extents_status.c:380
Inline: False
Direct callers:
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
```
**Symbols:**

```
ffffffff812ef5a0-ffffffff812ef65c: ext4_es_can_be_merged (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ext4_es_can_be_merged(struct extent_status *es1, struct extent_status *es2);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff813140a0)
Location: fs/ext4/extents_status.c:381
Inline: False
Direct callers:
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
```
**Symbols:**

```
ffffffff813140a0-ffffffff8131415c: ext4_es_can_be_merged (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int ext4_es_can_be_merged(struct extent_status *es1, struct extent_status *es2);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/extents_status.c (0)
Location: fs/ext4/extents_status.c:380
Inline: False
Direct callers:
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
```
**Symbols:**

```
ffffffff81341f60-ffffffff81341ffe: ext4_es_can_be_merged (STB_LOCAL)
ffffffff81343714-ffffffff8134372d: ext4_es_can_be_merged.cold.18 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int ext4_es_can_be_merged(struct extent_status *es1, struct extent_status *es2);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/extents_status.c (0)
Location: fs/ext4/extents_status.c:496
Inline: False
Direct callers:
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
```
**Symbols:**

```
ffffffff813597b0-ffffffff8135984e: ext4_es_can_be_merged (STB_LOCAL)
ffffffff8135b853-ffffffff8135b86c: ext4_es_can_be_merged.cold.20 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int ext4_es_can_be_merged(struct extent_status *es1, struct extent_status *es2);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/extents_status.c (0)
Location: fs/ext4/extents_status.c:496
Inline: False
Direct callers:
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
```
**Symbols:**

```
ffffffff81382780-ffffffff8138282e: ext4_es_can_be_merged (STB_LOCAL)
ffffffff8138488e-ffffffff813848b5: ext4_es_can_be_merged.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int ext4_es_can_be_merged(struct extent_status *es1, struct extent_status *es2);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/extents_status.c (0)
Location: fs/ext4/extents_status.c:496
Inline: False
Direct callers:
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
```
**Symbols:**

```
ffffffff8139acf0-ffffffff8139ad9e: ext4_es_can_be_merged (STB_LOCAL)
ffffffff8139d35f-ffffffff8139d37a: ext4_es_can_be_merged.cold (STB_LOCAL)
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
In fs/ext4/extents_status.c (0)
Location: fs/ext4/extents_status.c:496
Inline: True
Direct callers:
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
```
**Symbols:**

```
ffffffff813e6200-ffffffff813e62a2: ext4_es_can_be_merged.isra.0 (STB_LOCAL)
ffffffff813e89e7-ffffffff813e8a03: ext4_es_can_be_merged.isra.0.cold (STB_LOCAL)
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
In fs/ext4/extents_status.c (0)
Location: fs/ext4/extents_status.c:505
Inline: True
Direct callers:
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
```
**Symbols:**

```
ffffffff813f8560-ffffffff813f8602: ext4_es_can_be_merged.isra.0 (STB_LOCAL)
ffffffff81bec31e-ffffffff81bec33a: ext4_es_can_be_merged.isra.0.cold (STB_LOCAL)
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
In fs/ext4/extents_status.c (0)
Location: fs/ext4/extents_status.c:505
Inline: True
Direct callers:
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
```
**Symbols:**

```
ffffffff813fe9e0-ffffffff813fea81: ext4_es_can_be_merged.isra.0 (STB_LOCAL)
ffffffff81bde3c9-ffffffff81bde3e5: ext4_es_can_be_merged.isra.0.cold (STB_LOCAL)
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
In fs/ext4/extents_status.c (0)
Location: fs/ext4/extents_status.c:505
Inline: True
Direct callers:
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
```
**Symbols:**

```
ffffffff81451200-ffffffff814512a2: ext4_es_can_be_merged.isra.0 (STB_LOCAL)
ffffffff81cc9b26-ffffffff81cc9b42: ext4_es_can_be_merged.isra.0.cold (STB_LOCAL)
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
In fs/ext4/extents_status.c (0)
Location: fs/ext4/extents_status.c:505
Inline: True
Direct callers:
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
```
**Symbols:**

```
ffffffff814ce3c0-ffffffff814ce472: ext4_es_can_be_merged.isra.0 (STB_LOCAL)
ffffffff81e7c81e-ffffffff81e7c83c: ext4_es_can_be_merged.isra.0.cold (STB_LOCAL)
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
In fs/ext4/extents_status.c (ffffffff81566b90)
Location: fs/ext4/extents_status.c:503
Inline: True
Direct callers:
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
```
**Symbols:**

```
ffffffff81566b90-ffffffff81566c95: ext4_es_can_be_merged.isra.0 (STB_LOCAL)
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
In fs/ext4/extents_status.c (ffffffff8159e820)
Location: fs/ext4/extents_status.c:520
Inline: True
Direct callers:
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
```
**Symbols:**

```
ffffffff8159e820-ffffffff8159e928: ext4_es_can_be_merged.isra.0 (STB_LOCAL)
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
In fs/ext4/extents_status.c (ffffffff815d7390)
Location: fs/ext4/extents_status.c:534
Inline: True
Direct callers:
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
```
**Symbols:**

```
ffffffff815d7390-ffffffff815d7498: ext4_es_can_be_merged.isra.0 (STB_LOCAL)
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
int ext4_es_can_be_merged(struct extent_status *es1, struct extent_status *es2);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffff80001046d728)
Location: fs/ext4/extents_status.c:496
Inline: False
Direct callers:
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
```
**Symbols:**

```
ffff80001046d728-ffff80001046d814: ext4_es_can_be_merged (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ext4_es_can_be_merged(struct extent_status *es1, struct extent_status *es2);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (c062ee84)
Location: fs/ext4/extents_status.c:496
Inline: False
Direct callers:
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
```
**Symbols:**

```
c062ee84-c062efac: ext4_es_can_be_merged (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ext4_es_can_be_merged(struct extent_status *es1, struct extent_status *es2);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (c00000000058d630)
Location: fs/ext4/extents_status.c:496
Inline: False
Direct callers:
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
```
**Symbols:**

```
c00000000058d630-c00000000058d720: ext4_es_can_be_merged (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ext4_es_can_be_merged(struct extent_status *es1, struct extent_status *es2);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffe0002faa00)
Location: fs/ext4/extents_status.c:496
Inline: False
Direct callers:
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
```
**Symbols:**

```
ffffffe0002faa00-ffffffe0002faabc: ext4_es_can_be_merged (STB_LOCAL)
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
int ext4_es_can_be_merged(struct extent_status *es1, struct extent_status *es2);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/extents_status.c (0)
Location: fs/ext4/extents_status.c:496
Inline: False
Direct callers:
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
```
**Symbols:**

```
ffffffff813932d0-ffffffff8139337e: ext4_es_can_be_merged (STB_LOCAL)
ffffffff8139593f-ffffffff8139595a: ext4_es_can_be_merged.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int ext4_es_can_be_merged(struct extent_status *es1, struct extent_status *es2);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/extents_status.c (0)
Location: fs/ext4/extents_status.c:496
Inline: False
Direct callers:
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
```
**Symbols:**

```
ffffffff81383d60-ffffffff81383e0e: ext4_es_can_be_merged (STB_LOCAL)
ffffffff813863cf-ffffffff813863ea: ext4_es_can_be_merged.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int ext4_es_can_be_merged(struct extent_status *es1, struct extent_status *es2);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/extents_status.c (0)
Location: fs/ext4/extents_status.c:496
Inline: False
Direct callers:
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
```
**Symbols:**

```
ffffffff81390c30-ffffffff81390cde: ext4_es_can_be_merged (STB_LOCAL)
ffffffff8139329f-ffffffff813932ba: ext4_es_can_be_merged.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int ext4_es_can_be_merged(struct extent_status *es1, struct extent_status *es2);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/extents_status.c (0)
Location: fs/ext4/extents_status.c:496
Inline: False
Direct callers:
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
```
**Symbols:**

```
ffffffff813a4ac0-ffffffff813a4b6e: ext4_es_can_be_merged (STB_LOCAL)
ffffffff813a732c-ffffffff813a7347: ext4_es_can_be_merged.cold (STB_LOCAL)
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
