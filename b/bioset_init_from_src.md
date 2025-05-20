# Function: <code>bioset_init_from_src</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int bioset_init_from_src(struct bio_set *bs, struct bio_set *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff81479a60)
Location: block/bio.c:2029
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_swap_table
  - drivers/md/dm.c:dm_swap_table
```
**Symbols:**

```
ffffffff81479a60-ffffffff81479a8d: bioset_init_from_src (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int bioset_init_from_src(struct bio_set *bs, struct bio_set *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff81497ac0)
Location: block/bio.c:1961
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_swap_table
  - drivers/md/dm.c:dm_swap_table
```
**Symbols:**

```
ffffffff81497ac0-ffffffff81497aed: bioset_init_from_src (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int bioset_init_from_src(struct bio_set *bs, struct bio_set *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814c5460)
Location: block/bio.c:1995
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_swap_table
  - drivers/md/dm.c:dm_swap_table
```
**Symbols:**

```
ffffffff814c5460-ffffffff814c548d: bioset_init_from_src (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int bioset_init_from_src(struct bio_set *bs, struct bio_set *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814de370)
Location: block/bio.c:2037
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_swap_table
  - drivers/md/dm.c:dm_swap_table
```
**Symbols:**

```
ffffffff814de370-ffffffff814de39d: bioset_init_from_src (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int bioset_init_from_src(struct bio_set *bs, struct bio_set *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8153ec80)
Location: block/bio.c:1616
Inline: False
Direct callers:
  - drivers/md/dm.c:__bind_mempools
  - drivers/md/dm.c:__bind_mempools
```
**Symbols:**

```
ffffffff8153ec80-ffffffff8153ecad: bioset_init_from_src (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int bioset_init_from_src(struct bio_set *bs, struct bio_set *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8155b490)
Location: block/bio.c:1619
Inline: False
Direct callers:
  - drivers/md/dm.c:__bind_mempools
  - drivers/md/dm.c:__bind_mempools
```
**Symbols:**

```
ffffffff8155b490-ffffffff8155b4bd: bioset_init_from_src (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int bioset_init_from_src(struct bio_set *bs, struct bio_set *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff81563610)
Location: block/bio.c:1584
Inline: False
Direct callers:
  - drivers/md/dm.c:__bind
  - drivers/md/dm.c:__bind
```
**Symbols:**

```
ffffffff81563610-ffffffff8156363d: bioset_init_from_src (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int bioset_init_from_src(struct bio_set *bs, struct bio_set *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff815c7f80)
Location: block/bio.c:1675
Inline: False
Direct callers:
  - drivers/md/dm.c:__bind
  - drivers/md/dm.c:__bind
```
**Symbols:**

```
ffffffff815c7f80-ffffffff815c7fad: bioset_init_from_src (STB_GLOBAL)
```
</details>
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
<summary>In <code>arm64</code>: ✅</summary>

```c
int bioset_init_from_src(struct bio_set *bs, struct bio_set *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffff8000105daa00)
Location: block/bio.c:2037
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_swap_table
  - drivers/md/dm.c:dm_swap_table
```
**Symbols:**

```
ffff8000105daa00-ffff8000105daa54: bioset_init_from_src (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int bioset_init_from_src(struct bio_set *bs, struct bio_set *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (c0787d84)
Location: block/bio.c:2037
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_swap_table
  - drivers/md/dm.c:dm_swap_table
```
**Symbols:**

```
c0787d84-c0787dc0: bioset_init_from_src (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int bioset_init_from_src(struct bio_set *bs, struct bio_set *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (c00000000076afc0)
Location: block/bio.c:2037
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_swap_table
  - drivers/md/dm.c:dm_swap_table
```
**Symbols:**

```
c00000000076afc0-c00000000076b004: bioset_init_from_src (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int bioset_init_from_src(struct bio_set *bs, struct bio_set *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffe00041dfdc)
Location: block/bio.c:2037
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_swap_table
  - drivers/md/dm.c:dm_swap_table
```
**Symbols:**

```
ffffffe00041dfdc-ffffffe00041e022: bioset_init_from_src (STB_GLOBAL)
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
int bioset_init_from_src(struct bio_set *bs, struct bio_set *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814d6950)
Location: block/bio.c:2037
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_swap_table
  - drivers/md/dm.c:dm_swap_table
```
**Symbols:**

```
ffffffff814d6950-ffffffff814d697d: bioset_init_from_src (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int bioset_init_from_src(struct bio_set *bs, struct bio_set *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814c7310)
Location: block/bio.c:2037
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_swap_table
  - drivers/md/dm.c:dm_swap_table
```
**Symbols:**

```
ffffffff814c7310-ffffffff814c733d: bioset_init_from_src (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int bioset_init_from_src(struct bio_set *bs, struct bio_set *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814d29e0)
Location: block/bio.c:2037
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_swap_table
  - drivers/md/dm.c:dm_swap_table
```
**Symbols:**

```
ffffffff814d29e0-ffffffff814d2a0d: bioset_init_from_src (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int bioset_init_from_src(struct bio_set *bs, struct bio_set *src);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814eb500)
Location: block/bio.c:2037
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_swap_table
  - drivers/md/dm.c:dm_swap_table
```
**Symbols:**

```
ffffffff814eb500-ffffffff814eb52d: bioset_init_from_src (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
