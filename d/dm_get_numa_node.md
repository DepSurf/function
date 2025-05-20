# Function: <code>dm_get_numa_node</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81703b45)
Location: drivers/md/dm.c:161
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_create
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
In drivers/md/dm.c (ffffffff81735a08)
Location: drivers/md/dm.c:161
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_create
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
In drivers/md/dm.c (ffffffff8174ee38)
Location: drivers/md/dm.c:156
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_create
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
In drivers/md/dm.c (ffffffff817c1058)
Location: drivers/md/dm.c:163
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_create
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff818096d5)
Location: drivers/md/dm.c:217
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_create
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff818357e5)
Location: drivers/md/dm.c:217
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_create
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
unsigned int dm_get_numa_node();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81876b10)
Location: drivers/md/dm.c:214
Inline: False
Direct callers:
  - drivers/md/dm.c:alloc_dev
```
**Symbols:**

```
ffffffff81876b10-ffffffff81876b61: dm_get_numa_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
unsigned int dm_get_numa_node();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff818a8910)
Location: drivers/md/dm.c:214
Inline: False
Direct callers:
  - drivers/md/dm.c:alloc_dev
```
**Symbols:**

```
ffffffff818a8910-ffffffff818a8961: dm_get_numa_node (STB_LOCAL)
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
In drivers/md/dm.c (ffffffff8197a135)
Location: drivers/md/dm.c:218
Inline: True
Inline callers:
  - drivers/md/dm.c:alloc_dev
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
In drivers/md/dm.c (ffffffff8197e775)
Location: drivers/md/dm.c:228
Inline: True
Inline callers:
  - drivers/md/dm.c:alloc_dev
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
In drivers/md/dm.c (ffffffff819625c5)
Location: drivers/md/dm.c:233
Inline: True
Inline callers:
  - drivers/md/dm.c:alloc_dev
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
In drivers/md/dm.c (ffffffff81a09805)
Location: drivers/md/dm.c:189
Inline: True
Inline callers:
  - drivers/md/dm.c:alloc_dev
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
In drivers/md/dm.c (ffffffff81b71145)
Location: drivers/md/dm.c:198
Inline: True
Inline callers:
  - drivers/md/dm.c:alloc_dev
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
In drivers/md/dm.c (ffffffff81d0df55)
Location: drivers/md/dm.c:194
Inline: True
Inline callers:
  - drivers/md/dm.c:alloc_dev
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
In drivers/md/dm.c (ffffffff81d77555)
Location: drivers/md/dm.c:196
Inline: True
Inline callers:
  - drivers/md/dm.c:alloc_dev
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
In drivers/md/dm.c (ffffffff81e2e785)
Location: drivers/md/dm.c:196
Inline: True
Inline callers:
  - drivers/md/dm.c:alloc_dev
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
unsigned int dm_get_numa_node();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffff800010afd028)
Location: drivers/md/dm.c:214
Inline: False
Direct callers:
  - drivers/md/dm.c:alloc_dev
```
**Symbols:**

```
ffff800010afd028-ffff800010afd0b8: dm_get_numa_node (STB_LOCAL)
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
In drivers/md/dm.c (c0bde51c)
Location: drivers/md/dm.c:214
Inline: True
Inline callers:
  - drivers/md/dm.c:alloc_dev
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (c000000000beb3f8)
Location: drivers/md/dm.c:214
Inline: True
Inline callers:
  - drivers/md/dm.c:alloc_dev
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffe0006f00b6)
Location: drivers/md/dm.c:214
Inline: True
Inline callers:
  - drivers/md/dm.c:alloc_dev
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
unsigned int dm_get_numa_node();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff8184e790)
Location: drivers/md/dm.c:214
Inline: False
Direct callers:
  - drivers/md/dm.c:alloc_dev
```
**Symbols:**

```
ffffffff8184e790-ffffffff8184e7e1: dm_get_numa_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
unsigned int dm_get_numa_node();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81815db0)
Location: drivers/md/dm.c:214
Inline: False
Direct callers:
  - drivers/md/dm.c:alloc_dev
```
**Symbols:**

```
ffffffff81815db0-ffffffff81815e01: dm_get_numa_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
unsigned int dm_get_numa_node();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff8189ddc0)
Location: drivers/md/dm.c:214
Inline: False
Direct callers:
  - drivers/md/dm.c:alloc_dev
```
**Symbols:**

```
ffffffff8189ddc0-ffffffff8189de11: dm_get_numa_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
unsigned int dm_get_numa_node();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff818ba170)
Location: drivers/md/dm.c:214
Inline: False
Direct callers:
  - drivers/md/dm.c:alloc_dev
```
**Symbols:**

```
ffffffff818ba170-ffffffff818ba1c1: dm_get_numa_node (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
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
