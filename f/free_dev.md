# Function: <code>free_dev</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff816a1fc0)
Location: drivers/md/dm.c:2389
Inline: True
Inline callers:
  - drivers/md/dm.c:__dm_destroy
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81702c42)
Location: drivers/md/dm.c:1556
Inline: True
Inline callers:
  - drivers/md/dm.c:__dm_destroy
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81734b11)
Location: drivers/md/dm.c:1611
Inline: True
Inline callers:
  - drivers/md/dm.c:__dm_destroy
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff8174ded1)
Location: drivers/md/dm.c:1816
Inline: True
Inline callers:
  - drivers/md/dm.c:__dm_destroy
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff817bff46)
Location: drivers/md/dm.c:1796
Inline: True
Inline callers:
  - drivers/md/dm.c:__dm_destroy
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void free_dev(struct mapped_device *md);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm.c (0)
Location: drivers/md/dm.c:1962
Inline: False
Direct callers:
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_create
```
**Symbols:**

```
ffffffff818090c0-ffffffff8180915c: free_dev (STB_LOCAL)
ffffffff8180a9f6-ffffffff8180aa29: free_dev.cold.55 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void free_dev(struct mapped_device *md);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm.c (0)
Location: drivers/md/dm.c:2002
Inline: False
Direct callers:
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_create
```
**Symbols:**

```
ffffffff81835210-ffffffff818352ac: free_dev (STB_LOCAL)
ffffffff818369f6-ffffffff81836a29: free_dev.cold.59 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void free_dev(struct mapped_device *md);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm.c (0)
Location: drivers/md/dm.c:2033
Inline: False
Direct callers:
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_create
```
**Symbols:**

```
ffffffff81877a70-ffffffff81877b0c: free_dev (STB_LOCAL)
ffffffff818795dd-ffffffff8187960e: free_dev.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void free_dev(struct mapped_device *md);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm.c (0)
Location: drivers/md/dm.c:2031
Inline: False
Direct callers:
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_create
```
**Symbols:**

```
ffffffff818a99f0-ffffffff818a9a8c: free_dev (STB_LOCAL)
ffffffff818ab3f7-ffffffff818ab428: free_dev.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void free_dev(struct mapped_device *md);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm.c (0)
Location: drivers/md/dm.c:2034
Inline: False
Direct callers:
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_create
```
**Symbols:**

```
ffffffff81979c30-ffffffff81979ced: free_dev (STB_LOCAL)
ffffffff8197b5c8-ffffffff8197b5f9: free_dev.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void free_dev(struct mapped_device *md);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm.c (0)
Location: drivers/md/dm.c:1919
Inline: False
Direct callers:
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_create
```
**Symbols:**

```
ffffffff8197e550-ffffffff8197e5f8: free_dev (STB_LOCAL)
ffffffff81c280a1-ffffffff81c280d2: free_dev.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void free_dev(struct mapped_device *md);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm.c (0)
Location: drivers/md/dm.c:1938
Inline: False
Direct callers:
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_create
```
**Symbols:**

```
ffffffff819623a0-ffffffff81962448: free_dev (STB_LOCAL)
ffffffff81c1a258-ffffffff81c1a289: free_dev.cold (STB_LOCAL)
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
In drivers/md/dm.c (ffffffff81a09725)
Location: drivers/md/dm.c:1819
Inline: True
Inline callers:
  - drivers/md/dm.c:__dm_destroy
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
In drivers/md/dm.c (ffffffff81b7179f)
Location: drivers/md/dm.c:2038
Inline: True
Inline callers:
  - drivers/md/dm.c:__dm_destroy
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
In drivers/md/dm.c (ffffffff81d0e5ef)
Location: drivers/md/dm.c:2119
Inline: True
Inline callers:
  - drivers/md/dm.c:__dm_destroy
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
In drivers/md/dm.c (ffffffff81d77bf9)
Location: drivers/md/dm.c:2165
Inline: True
Inline callers:
  - drivers/md/dm.c:__dm_destroy
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
In drivers/md/dm.c (ffffffff81e2ee29)
Location: drivers/md/dm.c:2173
Inline: True
Inline callers:
  - drivers/md/dm.c:__dm_destroy
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
void free_dev(struct mapped_device *md);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffff800010afdf88)
Location: drivers/md/dm.c:2031
Inline: False
Direct callers:
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_create
```
**Symbols:**

```
ffff800010afdf88-ffff800010afe04c: free_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void free_dev(struct mapped_device *md);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (c0bdd468)
Location: drivers/md/dm.c:2031
Inline: False
Direct callers:
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_create
```
**Symbols:**

```
c0bdd468-c0bdd510: free_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void free_dev(struct mapped_device *md);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (c000000000bebf20)
Location: drivers/md/dm.c:2031
Inline: False
Direct callers:
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_create
```
**Symbols:**

```
c000000000bebf20-c000000000bec028: free_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void free_dev(struct mapped_device *md);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffe0006efe1c)
Location: drivers/md/dm.c:2031
Inline: False
Direct callers:
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_create
```
**Symbols:**

```
ffffffe0006efe1c-ffffffe0006efee4: free_dev (STB_LOCAL)
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
void free_dev(struct mapped_device *md);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm.c (0)
Location: drivers/md/dm.c:2031
Inline: False
Direct callers:
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_create
```
**Symbols:**

```
ffffffff8184f870-ffffffff8184f90c: free_dev (STB_LOCAL)
ffffffff81851277-ffffffff818512a8: free_dev.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void free_dev(struct mapped_device *md);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm.c (0)
Location: drivers/md/dm.c:2031
Inline: False
Direct callers:
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_create
```
**Symbols:**

```
ffffffff81816e80-ffffffff81816f1c: free_dev (STB_LOCAL)
ffffffff81818887-ffffffff818188b8: free_dev.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void free_dev(struct mapped_device *md);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm.c (0)
Location: drivers/md/dm.c:2031
Inline: False
Direct callers:
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_create
```
**Symbols:**

```
ffffffff8189eea0-ffffffff8189ef3c: free_dev (STB_LOCAL)
ffffffff818a08a7-ffffffff818a08d8: free_dev.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void free_dev(struct mapped_device *md);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm.c (0)
Location: drivers/md/dm.c:2031
Inline: False
Direct callers:
  - drivers/md/dm.c:__dm_destroy
  - drivers/md/dm.c:dm_create
```
**Symbols:**

```
ffffffff818ba670-ffffffff818ba70a: free_dev (STB_LOCAL)
ffffffff818bcace-ffffffff818bcaff: free_dev.cold (STB_LOCAL)
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
