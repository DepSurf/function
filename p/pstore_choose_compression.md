# Function: <code>pstore_choose_compression</code>

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
void pstore_choose_compression();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pstore/platform.c (ffffffff827155fe)
Location: fs/pstore/platform.c:751
Inline: False
Direct callers:
  - fs/pstore/inode.c:init_pstore_fs
```
**Symbols:**

```
ffffffff827155fe-ffffffff8271565c: pstore_choose_compression (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void pstore_choose_compression();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pstore/platform.c (ffffffff828ccaa2)
Location: fs/pstore/platform.c:802
Inline: False
Direct callers:
  - fs/pstore/platform.c:pstore_init
```
**Symbols:**

```
ffffffff828ccaa2-ffffffff828ccaea: pstore_choose_compression (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void pstore_choose_compression();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pstore/platform.c (ffffffff828e642c)
Location: fs/pstore/platform.c:796
Inline: False
Direct callers:
  - fs/pstore/platform.c:pstore_init
```
**Symbols:**

```
ffffffff828e642c-ffffffff828e6474: pstore_choose_compression (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void pstore_choose_compression();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pstore/platform.c (ffffffff828eeee5)
Location: fs/pstore/platform.c:796
Inline: False
Direct callers:
  - fs/pstore/platform.c:pstore_init
```
**Symbols:**

```
ffffffff828eeee5-ffffffff828eef2d: pstore_choose_compression (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/pstore/platform.c (ffffffff82d041e9)
Location: fs/pstore/platform.c:804
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/pstore/platform.c (ffffffff82ff15b6)
Location: fs/pstore/platform.c:804
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/pstore/platform.c (ffffffff831fbe66)
Location: fs/pstore/platform.c:807
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/pstore/platform.c (ffffffff832e2eb8)
Location: fs/pstore/platform.c:807
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/pstore/platform.c (ffffffff8349917c)
Location: fs/pstore/platform.c:805
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_init
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/pstore/platform.c (ffffffff83ecf045)
Location: fs/pstore/platform.c:821
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_init
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/pstore/platform.c (ffffffff836f40d5)
Location: fs/pstore/platform.c:821
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_init
```
</details>
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
void pstore_choose_compression();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pstore/platform.c (ffff800011468adc)
Location: fs/pstore/platform.c:796
Inline: False
Direct callers:
  - fs/pstore/platform.c:pstore_init
```
**Symbols:**

```
ffff800011468adc-ffff800011468b3c: pstore_choose_compression (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void pstore_choose_compression();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pstore/platform.c (c1541490)
Location: fs/pstore/platform.c:796
Inline: False
Direct callers:
  - fs/pstore/platform.c:pstore_init
```
**Symbols:**

```
c1541490-c15414f4: pstore_choose_compression (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void pstore_choose_compression();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pstore/platform.c (c0000000013969b8)
Location: fs/pstore/platform.c:796
Inline: False
Direct callers:
  - fs/pstore/platform.c:pstore_init
```
**Symbols:**

```
c0000000013969b8-c000000001396a40: pstore_choose_compression (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void pstore_choose_compression();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pstore/platform.c (ffffffe000023d56)
Location: fs/pstore/platform.c:796
Inline: False
Direct callers:
  - fs/pstore/platform.c:pstore_init
```
**Symbols:**

```
ffffffe000023d56-ffffffe000023daa: pstore_choose_compression (STB_GLOBAL)
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
void pstore_choose_compression();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pstore/platform.c (ffffffff828d7d99)
Location: fs/pstore/platform.c:796
Inline: False
Direct callers:
  - fs/pstore/platform.c:pstore_init
```
**Symbols:**

```
ffffffff828d7d99-ffffffff828d7de1: pstore_choose_compression (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void pstore_choose_compression();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pstore/platform.c (ffffffff828d04b5)
Location: fs/pstore/platform.c:796
Inline: False
Direct callers:
  - fs/pstore/platform.c:pstore_init
```
**Symbols:**

```
ffffffff828d04b5-ffffffff828d04fd: pstore_choose_compression (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void pstore_choose_compression();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pstore/platform.c (ffffffff828eab19)
Location: fs/pstore/platform.c:796
Inline: False
Direct callers:
  - fs/pstore/platform.c:pstore_init
```
**Symbols:**

```
ffffffff828eab19-ffffffff828eab61: pstore_choose_compression (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void pstore_choose_compression();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pstore/platform.c (ffffffff828eff2f)
Location: fs/pstore/platform.c:796
Inline: False
Direct callers:
  - fs/pstore/platform.c:pstore_init
```
**Symbols:**

```
ffffffff828eff2f-ffffffff828eff77: pstore_choose_compression (STB_GLOBAL)
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
