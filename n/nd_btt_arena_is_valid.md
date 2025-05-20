# Function: <code>nd_btt_arena_is_valid</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
bool nd_btt_arena_is_valid(struct nd_btt *nd_btt, struct btt_sb *super);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/btt_devs.c (ffffffff815a14d0)
Location: drivers/nvdimm/btt_devs.c:225
Inline: True
Direct callers:
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
```
**Symbols:**

```
ffffffff815a14d0-ffffffff815a159d: nd_btt_arena_is_valid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
bool nd_btt_arena_is_valid(struct nd_btt *nd_btt, struct btt_sb *super);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/btt_devs.c (ffffffff815f78f0)
Location: drivers/nvdimm/btt_devs.c:244
Inline: True
Direct callers:
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
```
**Symbols:**

```
ffffffff815f78f0-ffffffff815f79bd: nd_btt_arena_is_valid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
bool nd_btt_arena_is_valid(struct nd_btt *nd_btt, struct btt_sb *super);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/btt_devs.c (ffffffff81625b60)
Location: drivers/nvdimm/btt_devs.c:244
Inline: True
Direct callers:
  - drivers/nvdimm/btt_devs.c:nd_btt_probe
```
**Symbols:**

```
ffffffff81625b60-ffffffff81625c2d: nd_btt_arena_is_valid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool nd_btt_arena_is_valid(struct nd_btt *nd_btt, struct btt_sb *super);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/btt_devs.c (ffffffff8163aba0)
Location: drivers/nvdimm/btt_devs.c:237
Inline: False
```
**Symbols:**

```
ffffffff8163aba0-ffffffff8163ac69: nd_btt_arena_is_valid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool nd_btt_arena_is_valid(struct nd_btt *nd_btt, struct btt_sb *super);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/btt_devs.c (ffffffff816a37a0)
Location: drivers/nvdimm/btt_devs.c:237
Inline: False
```
**Symbols:**

```
ffffffff816a37a0-ffffffff816a3869: nd_btt_arena_is_valid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool nd_btt_arena_is_valid(struct nd_btt *nd_btt, struct btt_sb *super);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/btt_devs.c (ffffffff816df910)
Location: drivers/nvdimm/btt_devs.c:237
Inline: False
```
**Symbols:**

```
ffffffff816df910-ffffffff816df9d9: nd_btt_arena_is_valid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool nd_btt_arena_is_valid(struct nd_btt *nd_btt, struct btt_sb *super);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/btt_devs.c (ffffffff81701cc0)
Location: drivers/nvdimm/btt_devs.c:237
Inline: False
```
**Symbols:**

```
ffffffff81701cc0-ffffffff81701d89: nd_btt_arena_is_valid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
bool nd_btt_arena_is_valid(struct nd_btt *nd_btt, struct btt_sb *super);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/btt_devs.c (0)
Location: drivers/nvdimm/btt_devs.c:245
Inline: False
```
**Symbols:**

```
ffffffff8173c127-ffffffff8173c140: nd_btt_arena_is_valid.cold (STB_LOCAL)
ffffffff8173bb30-ffffffff8173bbe1: nd_btt_arena_is_valid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
bool nd_btt_arena_is_valid(struct nd_btt *nd_btt, struct btt_sb *super);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/btt_devs.c (0)
Location: drivers/nvdimm/btt_devs.c:245
Inline: False
```
**Symbols:**

```
ffffffff8175fdc4-ffffffff8175fddd: nd_btt_arena_is_valid.cold (STB_LOCAL)
ffffffff8175f850-ffffffff8175f901: nd_btt_arena_is_valid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
bool nd_btt_arena_is_valid(struct nd_btt *nd_btt, struct btt_sb *super);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/btt_devs.c (0)
Location: drivers/nvdimm/btt_devs.c:245
Inline: False
Direct callers:
  - drivers/nvdimm/btt_devs.c:nd_btt_version
  - drivers/nvdimm/btt_devs.c:nd_btt_version
```
**Symbols:**

```
ffffffff8181f8d6-ffffffff8181f8ef: nd_btt_arena_is_valid.cold (STB_LOCAL)
ffffffff8181ef30-ffffffff8181efe1: nd_btt_arena_is_valid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
bool nd_btt_arena_is_valid(struct nd_btt *nd_btt, struct btt_sb *super);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/btt_devs.c (0)
Location: drivers/nvdimm/btt_devs.c:245
Inline: False
Direct callers:
  - drivers/nvdimm/btt_devs.c:nd_btt_version
  - drivers/nvdimm/btt_devs.c:nd_btt_version
```
**Symbols:**

```
ffffffff81c15e8a-ffffffff81c15ea3: nd_btt_arena_is_valid.cold (STB_LOCAL)
ffffffff8182de70-ffffffff8182df27: nd_btt_arena_is_valid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
bool nd_btt_arena_is_valid(struct nd_btt *nd_btt, struct btt_sb *super);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/btt_devs.c (0)
Location: drivers/nvdimm/btt_devs.c:245
Inline: False
Direct callers:
  - drivers/nvdimm/btt_devs.c:nd_btt_version
  - drivers/nvdimm/btt_devs.c:nd_btt_version
```
**Symbols:**

```
ffffffff81c07bf3-ffffffff81c07c0c: nd_btt_arena_is_valid.cold (STB_LOCAL)
ffffffff81811140-ffffffff818111f7: nd_btt_arena_is_valid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
bool nd_btt_arena_is_valid(struct nd_btt *nd_btt, struct btt_sb *super);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/btt_devs.c (0)
Location: drivers/nvdimm/btt_devs.c:245
Inline: False
Direct callers:
  - drivers/nvdimm/btt_devs.c:nd_btt_version
  - drivers/nvdimm/btt_devs.c:nd_btt_version
```
**Symbols:**

```
ffffffff81d0b58e-ffffffff81d0b5a7: nd_btt_arena_is_valid.cold (STB_LOCAL)
ffffffff8189bd80-ffffffff8189be37: nd_btt_arena_is_valid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool nd_btt_arena_is_valid(struct nd_btt *nd_btt, struct btt_sb *super);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/btt_devs.c (0)
Location: drivers/nvdimm/btt_devs.c:247
Inline: False
Direct callers:
  - drivers/nvdimm/btt_devs.c:nd_btt_version
  - drivers/nvdimm/btt_devs.c:nd_btt_version
```
**Symbols:**

```
ffffffff81ed4456-ffffffff81ed446a: nd_btt_arena_is_valid.cold (STB_LOCAL)
ffffffff819e5570-ffffffff819e5676: nd_btt_arena_is_valid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool nd_btt_arena_is_valid(struct nd_btt *nd_btt, struct btt_sb *super);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/btt_devs.c (ffffffff81b61410)
Location: drivers/nvdimm/btt_devs.c:247
Inline: False
Direct callers:
  - drivers/nvdimm/btt_devs.c:nd_btt_version
  - drivers/nvdimm/btt_devs.c:nd_btt_version
```
**Symbols:**

```
ffffffff81b61410-ffffffff81b61523: nd_btt_arena_is_valid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool nd_btt_arena_is_valid(struct nd_btt *nd_btt, struct btt_sb *super);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/btt_devs.c (ffffffff81bb49c0)
Location: drivers/nvdimm/btt_devs.c:247
Inline: False
Direct callers:
  - drivers/nvdimm/btt_devs.c:nd_btt_version
  - drivers/nvdimm/btt_devs.c:nd_btt_version
```
**Symbols:**

```
ffffffff81bb49c0-ffffffff81bb4aee: nd_btt_arena_is_valid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool nd_btt_arena_is_valid(struct nd_btt *nd_btt, struct btt_sb *super);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/btt_devs.c (ffffffff81c08f40)
Location: drivers/nvdimm/btt_devs.c:247
Inline: False
Direct callers:
  - drivers/nvdimm/btt_devs.c:nd_btt_version
  - drivers/nvdimm/btt_devs.c:nd_btt_version
```
**Symbols:**

```
ffffffff81c08f40-ffffffff81c0906e: nd_btt_arena_is_valid (STB_GLOBAL)
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
bool nd_btt_arena_is_valid(struct nd_btt *nd_btt, struct btt_sb *super);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/btt_devs.c (ffff8000109611f0)
Location: drivers/nvdimm/btt_devs.c:245
Inline: False
```
**Symbols:**

```
ffff8000109611f0-ffff8000109612e8: nd_btt_arena_is_valid (STB_GLOBAL)
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
bool nd_btt_arena_is_valid(struct nd_btt *nd_btt, struct btt_sb *super);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/btt_devs.c (c000000000a14550)
Location: drivers/nvdimm/btt_devs.c:245
Inline: False
```
**Symbols:**

```
c000000000a14550-c000000000a14704: nd_btt_arena_is_valid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
bool nd_btt_arena_is_valid(struct nd_btt *nd_btt, struct btt_sb *super);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/btt_devs.c (ffffffe0005cea04)
Location: drivers/nvdimm/btt_devs.c:245
Inline: True
```
**Symbols:**

```
ffffffe0005cea04-ffffffe0005ceac0: nd_btt_arena_is_valid (STB_GLOBAL)
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
bool nd_btt_arena_is_valid(struct nd_btt *nd_btt, struct btt_sb *super);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/btt_devs.c (0)
Location: drivers/nvdimm/btt_devs.c:245
Inline: False
```
**Symbols:**

```
ffffffff817144b4-ffffffff817144cd: nd_btt_arena_is_valid.cold (STB_LOCAL)
ffffffff81713f40-ffffffff81713ff1: nd_btt_arena_is_valid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
bool nd_btt_arena_is_valid(struct nd_btt *nd_btt, struct btt_sb *super);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/btt_devs.c (0)
Location: drivers/nvdimm/btt_devs.c:245
Inline: False
Direct callers:
  - drivers/nvdimm/btt.c:discover_arenas
```
**Symbols:**

```
ffffffff816e7f34-ffffffff816e7f4d: nd_btt_arena_is_valid.cold (STB_LOCAL)
ffffffff816e79c0-ffffffff816e7a71: nd_btt_arena_is_valid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
bool nd_btt_arena_is_valid(struct nd_btt *nd_btt, struct btt_sb *super);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/btt_devs.c (0)
Location: drivers/nvdimm/btt_devs.c:245
Inline: False
```
**Symbols:**

```
ffffffff81753284-ffffffff8175329d: nd_btt_arena_is_valid.cold (STB_LOCAL)
ffffffff81752d10-ffffffff81752dc1: nd_btt_arena_is_valid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
bool nd_btt_arena_is_valid(struct nd_btt *nd_btt, struct btt_sb *super);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/btt_devs.c (0)
Location: drivers/nvdimm/btt_devs.c:245
Inline: False
```
**Symbols:**

```
ffffffff8176e6f4-ffffffff8176e70d: nd_btt_arena_is_valid.cold (STB_LOCAL)
ffffffff8176e180-ffffffff8176e231: nd_btt_arena_is_valid (STB_GLOBAL)
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
