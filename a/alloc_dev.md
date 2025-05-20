# Function: <code>alloc_dev</code>

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
In drivers/md/dm.c (ffffffff816a32d6)
Location: drivers/md/dm.c:2286
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_create
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
In drivers/md/dm.c (ffffffff81703b45)
Location: drivers/md/dm.c:1450
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
Location: drivers/md/dm.c:1505
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
Location: drivers/md/dm.c:1703
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
Location: drivers/md/dm.c:1683
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
Location: drivers/md/dm.c:1847
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
Location: drivers/md/dm.c:1895
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_create
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
struct mapped_device *alloc_dev(int minor);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm.c (0)
Location: drivers/md/dm.c:1927
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_create
```
**Symbols:**

```
ffffffff81877dd0-ffffffff8187823f: alloc_dev (STB_LOCAL)
ffffffff81879648-ffffffff81879659: alloc_dev.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
struct mapped_device *alloc_dev(int minor);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm.c (0)
Location: drivers/md/dm.c:1920
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_create
```
**Symbols:**

```
ffffffff818a9c00-ffffffff818aa073: alloc_dev (STB_LOCAL)
ffffffff818ab449-ffffffff818ab45a: alloc_dev.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
struct mapped_device *alloc_dev(int minor);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm.c (0)
Location: drivers/md/dm.c:1924
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_create
```
**Symbols:**

```
ffffffff8197a130-ffffffff8197a5dc: alloc_dev (STB_LOCAL)
ffffffff8197b62a-ffffffff8197b63b: alloc_dev.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
struct mapped_device *alloc_dev(int minor);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm.c (0)
Location: drivers/md/dm.c:1810
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_create
```
**Symbols:**

```
ffffffff8197e770-ffffffff8197ec61: alloc_dev (STB_LOCAL)
ffffffff81c280f3-ffffffff81c28104: alloc_dev.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
struct mapped_device *alloc_dev(int minor);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm.c (0)
Location: drivers/md/dm.c:1829
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_create
```
**Symbols:**

```
ffffffff819625c0-ffffffff81962ab1: alloc_dev (STB_LOCAL)
ffffffff81c1a2aa-ffffffff81c1a2bb: alloc_dev.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct mapped_device *alloc_dev(int minor);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm.c (0)
Location: drivers/md/dm.c:1711
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_create
```
**Symbols:**

```
ffffffff81a09800-ffffffff81a09cf6: alloc_dev (STB_LOCAL)
ffffffff81d29f44-ffffffff81d29f55: alloc_dev.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct mapped_device *alloc_dev(int minor);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm.c (0)
Location: drivers/md/dm.c:1922
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_create
```
**Symbols:**

```
ffffffff81b71140-ffffffff81b71683: alloc_dev (STB_LOCAL)
ffffffff81ef61de-ffffffff81ef61ef: alloc_dev.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct mapped_device *alloc_dev(int minor);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81d0df50)
Location: drivers/md/dm.c:2002
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_create
```
**Symbols:**

```
ffffffff81d0df50-ffffffff81d0e4c7: alloc_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct mapped_device *alloc_dev(int minor);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81d77550)
Location: drivers/md/dm.c:2046
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_create
```
**Symbols:**

```
ffffffff81d77550-ffffffff81d77acb: alloc_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct mapped_device *alloc_dev(int minor);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81e2e780)
Location: drivers/md/dm.c:2054
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_create
```
**Symbols:**

```
ffffffff81e2e780-ffffffff81e2ecfb: alloc_dev (STB_LOCAL)
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
struct mapped_device *alloc_dev(int minor);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffff800010aff858)
Location: drivers/md/dm.c:1920
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_create
```
**Symbols:**

```
ffff800010aff858-ffff800010affcc4: alloc_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct mapped_device *alloc_dev(int minor);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (c0bde504)
Location: drivers/md/dm.c:1920
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_create
```
**Symbols:**

```
c0bde504-c0bde900: alloc_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct mapped_device *alloc_dev(int minor);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (c000000000beb3d0)
Location: drivers/md/dm.c:1920
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_create
```
**Symbols:**

```
c000000000beb3d0-c000000000beb9a4: alloc_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct mapped_device *alloc_dev(int minor);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffe0006f0098)
Location: drivers/md/dm.c:1920
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_create
```
**Symbols:**

```
ffffffe0006f0098-ffffffe0006f050e: alloc_dev (STB_LOCAL)
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
struct mapped_device *alloc_dev(int minor);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm.c (0)
Location: drivers/md/dm.c:1920
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_create
```
**Symbols:**

```
ffffffff8184fa80-ffffffff8184fef3: alloc_dev (STB_LOCAL)
ffffffff818512c9-ffffffff818512da: alloc_dev.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
struct mapped_device *alloc_dev(int minor);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm.c (0)
Location: drivers/md/dm.c:1920
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_create
```
**Symbols:**

```
ffffffff81817090-ffffffff81817503: alloc_dev (STB_LOCAL)
ffffffff818188d9-ffffffff818188ea: alloc_dev.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
struct mapped_device *alloc_dev(int minor);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm.c (0)
Location: drivers/md/dm.c:1920
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_create
```
**Symbols:**

```
ffffffff8189f0b0-ffffffff8189f523: alloc_dev (STB_LOCAL)
ffffffff818a08f9-ffffffff818a090a: alloc_dev.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
struct mapped_device *alloc_dev(int minor);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm.c (0)
Location: drivers/md/dm.c:1920
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_create
```
**Symbols:**

```
ffffffff818ba1d0-ffffffff818ba662: alloc_dev (STB_LOCAL)
ffffffff818bcabd-ffffffff818bcace: alloc_dev.cold (STB_LOCAL)
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
