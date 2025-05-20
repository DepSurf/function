# Function: <code>memblocks_present</code>

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
<summary>In <code>5.0</code>: ✅</summary>

```c
void memblocks_present();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff828bfc85)
Location: mm/sparse.c:247
Inline: False
```
**Symbols:**

```
ffffffff828bfc85-ffffffff828bfcd4: memblocks_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void memblocks_present();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff828d8fed)
Location: mm/sparse.c:296
Inline: False
```
**Symbols:**

```
ffffffff828d8fed-ffffffff828d903c: memblocks_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void memblocks_present();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff828e1440)
Location: mm/sparse.c:298
Inline: False
```
**Symbols:**

```
ffffffff828e1440-ffffffff828e148f: memblocks_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void memblocks_present();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff82cfea67)
Location: mm/sparse.c:293
Inline: False
```
**Symbols:**

```
ffffffff82cfea67-ffffffff82cfeab6: memblocks_present (STB_GLOBAL)
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
In mm/sparse.c (ffffffff82feb47f)
Location: mm/sparse.c:292
Inline: True
Inline callers:
  - mm/sparse.c:sparse_init
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
In mm/sparse.c (ffffffff831f5de6)
Location: mm/sparse.c:292
Inline: True
Inline callers:
  - mm/sparse.c:sparse_init
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
In mm/sparse.c (ffffffff832dc4bc)
Location: mm/sparse.c:266
Inline: True
Inline callers:
  - mm/sparse.c:sparse_init
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
In mm/sparse.c (ffffffff83491ce4)
Location: mm/sparse.c:266
Inline: True
Inline callers:
  - mm/sparse.c:sparse_init
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
In mm/sparse.c (ffffffff83ec5545)
Location: mm/sparse.c:266
Inline: True
Inline callers:
  - mm/sparse.c:sparse_init
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
In mm/sparse.c (ffffffff836ea605)
Location: mm/sparse.c:266
Inline: True
Inline callers:
  - mm/sparse.c:sparse_init
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff8391d9c5)
Location: mm/sparse.c:265
Inline: True
Inline callers:
  - mm/sparse.c:sparse_init
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
void memblocks_present();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffff80001145a5dc)
Location: mm/sparse.c:298
Inline: False
Direct callers:
  - arch/arm64/mm/init.c:bootmem_init
```
**Symbols:**

```
ffff80001145a5dc-ffff80001145a64c: memblocks_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/arm/mm/init.c (0)
Location: include/linux/mmzone.h:852
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void memblocks_present();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (c000000001384624)
Location: mm/sparse.c:298
Inline: False
```
**Symbols:**

```
c000000001384624-c0000000013846b0: memblocks_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void memblocks_present();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffe000018722)
Location: mm/sparse.c:298
Inline: False
Direct callers:
  - arch/riscv/mm/init.c:paging_init
```
**Symbols:**

```
ffffffe000018722-ffffffe00001878c: memblocks_present (STB_GLOBAL)
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
void memblocks_present();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff828ca2f4)
Location: mm/sparse.c:298
Inline: False
```
**Symbols:**

```
ffffffff828ca2f4-ffffffff828ca343: memblocks_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void memblocks_present();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff828c2a19)
Location: mm/sparse.c:298
Inline: False
```
**Symbols:**

```
ffffffff828c2a19-ffffffff828c2a68: memblocks_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void memblocks_present();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff828dd074)
Location: mm/sparse.c:298
Inline: False
```
**Symbols:**

```
ffffffff828dd074-ffffffff828dd0c3: memblocks_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void memblocks_present();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff828e248b)
Location: mm/sparse.c:298
Inline: False
```
**Symbols:**

```
ffffffff828e248b-ffffffff828e24da: memblocks_present (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
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
