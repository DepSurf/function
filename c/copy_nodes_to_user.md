# Function: <code>copy_nodes_to_user</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int copy_nodes_to_user(long unsigned int *mask, long unsigned int maxnode, nodemask_t *nodes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff811dffa0)
Location: mm/mempolicy.c:1282
Inline: False
Direct callers:
  - mm/mempolicy.c:compat_SyS_get_mempolicy
```
**Symbols:**

```
ffffffff811dffa0-ffffffff811e0005: copy_nodes_to_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int copy_nodes_to_user(long unsigned int *mask, long unsigned int maxnode, nodemask_t *nodes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff811fe420)
Location: mm/mempolicy.c:1314
Inline: False
Direct callers:
  - mm/mempolicy.c:compat_SyS_get_mempolicy
```
**Symbols:**

```
ffffffff811fe420-ffffffff811fe4ab: copy_nodes_to_user (STB_LOCAL)
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
In mm/mempolicy.c (ffffffff81211081)
Location: mm/mempolicy.c:1316
Inline: True
Inline callers:
  - mm/mempolicy.c:SYSC_get_mempolicy
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
In mm/mempolicy.c (ffffffff8121c9fa)
Location: mm/mempolicy.c:1245
Inline: True
Inline callers:
  - mm/mempolicy.c:SYSC_get_mempolicy
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
In mm/mempolicy.c (ffffffff81237baa)
Location: mm/mempolicy.c:1308
Inline: True
Inline callers:
  - mm/mempolicy.c:SYSC_get_mempolicy
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
In mm/mempolicy.c (ffffffff8125b07c)
Location: mm/mempolicy.c:1299
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_get_mempolicy
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
In mm/mempolicy.c (ffffffff8126f83d)
Location: mm/mempolicy.c:1339
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_get_mempolicy
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff8128ae2a)
Location: mm/mempolicy.c:1385
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_get_mempolicy
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff8129a99a)
Location: mm/mempolicy.c:1388
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_get_mempolicy
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int copy_nodes_to_user(long unsigned int *mask, long unsigned int maxnode, nodemask_t *nodes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff812cc720)
Location: mm/mempolicy.c:1457
Inline: False
Direct callers:
  - mm/mempolicy.c:kernel_get_mempolicy
```
**Symbols:**

```
ffffffff812cc720-ffffffff812cc7b5: copy_nodes_to_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int copy_nodes_to_user(long unsigned int *mask, long unsigned int maxnode, nodemask_t *nodes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff812d80c0)
Location: mm/mempolicy.c:1433
Inline: False
Direct callers:
  - mm/mempolicy.c:kernel_get_mempolicy
```
**Symbols:**

```
ffffffff812d80c0-ffffffff812d8155: copy_nodes_to_user (STB_LOCAL)
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
In mm/mempolicy.c (ffffffff812e0a89)
Location: mm/mempolicy.c:1447
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_get_mempolicy
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
In mm/mempolicy.c (ffffffff81327d80)
Location: mm/mempolicy.c:1415
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_get_mempolicy
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
In mm/mempolicy.c (ffffffff81396f85)
Location: mm/mempolicy.c:1408
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_get_mempolicy
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int copy_nodes_to_user(long unsigned int *mask, long unsigned int maxnode, nodemask_t *nodes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81414b30)
Location: mm/mempolicy.c:1423
Inline: False
Direct callers:
  - mm/mempolicy.c:kernel_get_mempolicy
```
**Symbols:**

```
ffffffff81414b30-ffffffff81414c8b: copy_nodes_to_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int copy_nodes_to_user(long unsigned int *mask, long unsigned int maxnode, nodemask_t *nodes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff814480f0)
Location: mm/mempolicy.c:1440
Inline: False
Direct callers:
  - mm/mempolicy.c:kernel_get_mempolicy
```
**Symbols:**

```
ffffffff814480f0-ffffffff8144821d: copy_nodes_to_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int copy_nodes_to_user(long unsigned int *mask, long unsigned int maxnode, nodemask_t *nodes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81481af0)
Location: mm/mempolicy.c:1424
Inline: False
Direct callers:
  - mm/mempolicy.c:kernel_get_mempolicy
```
**Symbols:**

```
ffffffff81481af0-ffffffff81481c1d: copy_nodes_to_user (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffff8000103396d0)
Location: mm/mempolicy.c:1388
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_get_mempolicy
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (c000000000413df8)
Location: mm/mempolicy.c:1388
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_get_mempolicy
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81292f7a)
Location: mm/mempolicy.c:1388
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_get_mempolicy
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81284b8a)
Location: mm/mempolicy.c:1388
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_get_mempolicy
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81290d8a)
Location: mm/mempolicy.c:1388
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_get_mempolicy
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff812a0bb6)
Location: mm/mempolicy.c:1388
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_get_mempolicy
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
