# Function: <code>set_badblock</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void set_badblock(struct badblocks *bb, sector_t s, int num);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/core.c (ffffffff815ebc80)
Location: drivers/nvdimm/core.c:430
Inline: True
Direct callers:
  - drivers/nvdimm/core.c:__add_badblock_range
  - drivers/nvdimm/core.c:__add_badblock_range
```
**Symbols:**

```
ffffffff815ebc80-ffffffff815ebd10: set_badblock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void set_badblock(struct badblocks *bb, sector_t s, int num);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/core.c (ffffffff81618870)
Location: drivers/nvdimm/core.c:401
Inline: True
Direct callers:
  - drivers/nvdimm/core.c:__add_badblock_range
  - drivers/nvdimm/core.c:__add_badblock_range
```
**Symbols:**

```
ffffffff81618870-ffffffff81618900: set_badblock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void set_badblock(struct badblocks *bb, sector_t s, int num);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/core.c (ffffffff8162c710)
Location: drivers/nvdimm/core.c:401
Inline: True
Direct callers:
  - drivers/nvdimm/core.c:__add_badblock_range
  - drivers/nvdimm/core.c:__add_badblock_range
```
**Symbols:**

```
ffffffff8162c710-ffffffff8162c7a0: set_badblock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void set_badblock(struct badblocks *bb, sector_t s, int num);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/badrange.c (ffffffff816a22d0)
Location: drivers/nvdimm/badrange.c:173
Inline: True
Direct callers:
  - drivers/nvdimm/badrange.c:__add_badblock_range
  - drivers/nvdimm/badrange.c:__add_badblock_range
```
**Symbols:**

```
ffffffff816a22d0-ffffffff816a2360: set_badblock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void set_badblock(struct badblocks *bb, sector_t s, int num);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/badrange.c (ffffffff816de460)
Location: drivers/nvdimm/badrange.c:173
Inline: True
Direct callers:
  - drivers/nvdimm/badrange.c:__add_badblock_range
  - drivers/nvdimm/badrange.c:__add_badblock_range
```
**Symbols:**

```
ffffffff816de460-ffffffff816de4f0: set_badblock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void set_badblock(struct badblocks *bb, sector_t s, int num);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/badrange.c (ffffffff81700820)
Location: drivers/nvdimm/badrange.c:173
Inline: True
Direct callers:
  - drivers/nvdimm/badrange.c:__add_badblock_range
  - drivers/nvdimm/badrange.c:__add_badblock_range
```
**Symbols:**

```
ffffffff81700820-ffffffff817008b0: set_badblock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void set_badblock(struct badblocks *bb, sector_t s, int num);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/badrange.c (ffffffff8173abb8)
Location: drivers/nvdimm/badrange.c:165
Inline: True
Direct callers:
  - drivers/nvdimm/badrange.c:__add_badblock_range
  - drivers/nvdimm/badrange.c:__add_badblock_range
```
**Symbols:**

```
ffffffff8173a6c0-ffffffff8173a72d: set_badblock (STB_LOCAL)
ffffffff8173abb8-ffffffff8173abdd: set_badblock.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void set_badblock(struct badblocks *bb, sector_t s, int num);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/badrange.c (ffffffff8175e888)
Location: drivers/nvdimm/badrange.c:165
Inline: True
Direct callers:
  - drivers/nvdimm/badrange.c:__add_badblock_range
  - drivers/nvdimm/badrange.c:__add_badblock_range
```
**Symbols:**

```
ffffffff8175e390-ffffffff8175e3fd: set_badblock (STB_LOCAL)
ffffffff8175e888-ffffffff8175e8ad: set_badblock.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void set_badblock(struct badblocks *bb, sector_t s, int num);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/badrange.c (0)
Location: drivers/nvdimm/badrange.c:165
Inline: False
Direct callers:
  - drivers/nvdimm/badrange.c:__add_badblock_range
  - drivers/nvdimm/badrange.c:__add_badblock_range
```
**Symbols:**

```
ffffffff8181de90-ffffffff8181defd: set_badblock (STB_LOCAL)
ffffffff8181e3fe-ffffffff8181e423: set_badblock.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void set_badblock(struct badblocks *bb, sector_t s, int num);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/badrange.c (0)
Location: drivers/nvdimm/badrange.c:165
Inline: False
Direct callers:
  - drivers/nvdimm/badrange.c:__add_badblock_range
  - drivers/nvdimm/badrange.c:__add_badblock_range
```
**Symbols:**

```
ffffffff8182ce10-ffffffff8182ce7d: set_badblock (STB_LOCAL)
ffffffff81c15e44-ffffffff81c15e69: set_badblock.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void set_badblock(struct badblocks *bb, sector_t s, int num);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/badrange.c (0)
Location: drivers/nvdimm/badrange.c:165
Inline: False
Direct callers:
  - drivers/nvdimm/badrange.c:__add_badblock_range
  - drivers/nvdimm/badrange.c:__add_badblock_range
```
**Symbols:**

```
ffffffff81810160-ffffffff818101cd: set_badblock (STB_LOCAL)
ffffffff81c07bad-ffffffff81c07bd2: set_badblock.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void set_badblock(struct badblocks *bb, sector_t s, int num);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/badrange.c (0)
Location: drivers/nvdimm/badrange.c:165
Inline: False
Direct callers:
  - drivers/nvdimm/badrange.c:__add_badblock_range
  - drivers/nvdimm/badrange.c:__add_badblock_range
```
**Symbols:**

```
ffffffff8189a770-ffffffff8189a7e9: set_badblock (STB_LOCAL)
ffffffff81d0b4cc-ffffffff81d0b506: set_badblock.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void set_badblock(struct badblocks *bb, sector_t s, int num);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/badrange.c (0)
Location: drivers/nvdimm/badrange.c:165
Inline: False
Direct callers:
  - drivers/nvdimm/badrange.c:__add_badblock_range
  - drivers/nvdimm/badrange.c:__add_badblock_range
```
**Symbols:**

```
ffffffff819e3e90-ffffffff819e3f1a: set_badblock (STB_LOCAL)
ffffffff81ed4393-ffffffff81ed43cd: set_badblock.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void set_badblock(struct badblocks *bb, sector_t s, int num);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/badrange.c (0)
Location: drivers/nvdimm/badrange.c:165
Inline: False
Direct callers:
  - drivers/nvdimm/badrange.c:__add_badblock_range
  - drivers/nvdimm/badrange.c:__add_badblock_range
```
**Symbols:**

```
ffffffff81b5fb30-ffffffff81b5fbef: set_badblock (STB_LOCAL)
ffffffff8209b42e-ffffffff8209b443: set_badblock.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void set_badblock(struct badblocks *bb, sector_t s, int num);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/badrange.c (0)
Location: drivers/nvdimm/badrange.c:165
Inline: False
Direct callers:
  - drivers/nvdimm/badrange.c:__add_badblock_range
  - drivers/nvdimm/badrange.c:__add_badblock_range
```
**Symbols:**

```
ffffffff81bb30d0-ffffffff81bb318f: set_badblock (STB_LOCAL)
ffffffff8211c2fd-ffffffff8211c312: set_badblock.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void set_badblock(struct badblocks *bb, sector_t s, int num);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/badrange.c (0)
Location: drivers/nvdimm/badrange.c:165
Inline: False
Direct callers:
  - drivers/nvdimm/badrange.c:__add_badblock_range
  - drivers/nvdimm/badrange.c:__add_badblock_range
```
**Symbols:**

```
ffffffff81c075c0-ffffffff81c0767f: set_badblock (STB_LOCAL)
ffffffff821fa184-ffffffff821fa199: set_badblock.cold (STB_LOCAL)
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
void set_badblock(struct badblocks *bb, sector_t s, int num);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/badrange.c (ffff80001095fa38)
Location: drivers/nvdimm/badrange.c:165
Inline: True
Direct callers:
  - drivers/nvdimm/badrange.c:__add_badblock_range
  - drivers/nvdimm/badrange.c:__add_badblock_range
```
**Symbols:**

```
ffff80001095fa38-ffff80001095fae0: set_badblock (STB_LOCAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void set_badblock(struct badblocks *bb, sector_t s, int num);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/badrange.c (c000000000a12520)
Location: drivers/nvdimm/badrange.c:165
Inline: True
Direct callers:
  - drivers/nvdimm/badrange.c:__add_badblock_range
  - drivers/nvdimm/badrange.c:__add_badblock_range
```
**Symbols:**

```
c000000000a12520-c000000000a12608: set_badblock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void set_badblock(struct badblocks *bb, sector_t s, int num);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/badrange.c (ffffffe0005cd652)
Location: drivers/nvdimm/badrange.c:165
Inline: True
Direct callers:
  - drivers/nvdimm/badrange.c:__add_badblock_range
  - drivers/nvdimm/badrange.c:__add_badblock_range
```
**Symbols:**

```
ffffffe0005cd652-ffffffe0005cd6f4: set_badblock (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
void set_badblock(struct badblocks *bb, sector_t s, int num);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/badrange.c (ffffffff81712f78)
Location: drivers/nvdimm/badrange.c:165
Inline: True
Direct callers:
  - drivers/nvdimm/badrange.c:__add_badblock_range
  - drivers/nvdimm/badrange.c:__add_badblock_range
```
**Symbols:**

```
ffffffff81712a80-ffffffff81712aed: set_badblock (STB_LOCAL)
ffffffff81712f78-ffffffff81712f9d: set_badblock.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
void set_badblock(struct badblocks *bb, sector_t s, int num);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/badrange.c (ffffffff816e69f8)
Location: drivers/nvdimm/badrange.c:165
Inline: True
Direct callers:
  - drivers/nvdimm/badrange.c:__add_badblock_range
  - drivers/nvdimm/badrange.c:__add_badblock_range
```
**Symbols:**

```
ffffffff816e6500-ffffffff816e656d: set_badblock (STB_LOCAL)
ffffffff816e69f8-ffffffff816e6a1d: set_badblock.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
void set_badblock(struct badblocks *bb, sector_t s, int num);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/badrange.c (ffffffff81751d48)
Location: drivers/nvdimm/badrange.c:165
Inline: True
Direct callers:
  - drivers/nvdimm/badrange.c:__add_badblock_range
  - drivers/nvdimm/badrange.c:__add_badblock_range
```
**Symbols:**

```
ffffffff81751850-ffffffff817518bd: set_badblock (STB_LOCAL)
ffffffff81751d48-ffffffff81751d6d: set_badblock.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void set_badblock(struct badblocks *bb, sector_t s, int num);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/badrange.c (ffffffff8176d1ca)
Location: drivers/nvdimm/badrange.c:165
Inline: True
Direct callers:
  - drivers/nvdimm/badrange.c:__add_badblock_range
  - drivers/nvdimm/badrange.c:__add_badblock_range
```
**Symbols:**

```
ffffffff8176cdb0-ffffffff8176ce1d: set_badblock (STB_LOCAL)
ffffffff8176d1ca-ffffffff8176d1ef: set_badblock.cold (STB_LOCAL)
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
