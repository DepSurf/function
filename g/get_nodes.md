# Function: <code>get_nodes</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int get_nodes(nodemask_t *nodes, const long unsigned int *nmask, long unsigned int maxnode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff811e0460)
Location: mm/mempolicy.c:1236
Inline: False
Direct callers:
  - mm/mempolicy.c:SyS_migrate_pages
  - mm/mempolicy.c:SyS_migrate_pages
  - mm/mempolicy.c:compat_SyS_set_mempolicy
  - mm/mempolicy.c:compat_SyS_mbind
```
**Symbols:**

```
ffffffff811e0460-ffffffff811e0547: get_nodes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int get_nodes(nodemask_t *nodes, const long unsigned int *nmask, long unsigned int maxnode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff811fe740)
Location: mm/mempolicy.c:1268
Inline: False
Direct callers:
  - mm/mempolicy.c:compat_SyS_mbind
  - mm/mempolicy.c:compat_SyS_set_mempolicy
  - mm/mempolicy.c:SyS_migrate_pages
  - mm/mempolicy.c:SyS_migrate_pages
```
**Symbols:**

```
ffffffff811fe740-ffffffff811fe80d: get_nodes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int get_nodes(nodemask_t *nodes, const long unsigned int *nmask, long unsigned int maxnode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff8120f670)
Location: mm/mempolicy.c:1270
Inline: False
Direct callers:
  - mm/mempolicy.c:SYSC_migrate_pages
  - mm/mempolicy.c:SYSC_migrate_pages
  - mm/mempolicy.c:SYSC_set_mempolicy
  - mm/mempolicy.c:SYSC_mbind
```
**Symbols:**

```
ffffffff8120f670-ffffffff8120f7b8: get_nodes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int get_nodes(nodemask_t *nodes, const long unsigned int *nmask, long unsigned int maxnode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff8121baa0)
Location: mm/mempolicy.c:1199
Inline: False
Direct callers:
  - mm/mempolicy.c:SYSC_migrate_pages
  - mm/mempolicy.c:SYSC_migrate_pages
  - mm/mempolicy.c:SYSC_set_mempolicy
  - mm/mempolicy.c:SYSC_mbind
```
**Symbols:**

```
ffffffff8121baa0-ffffffff8121bbdf: get_nodes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int get_nodes(nodemask_t *nodes, const long unsigned int *nmask, long unsigned int maxnode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81236da0)
Location: mm/mempolicy.c:1262
Inline: False
Direct callers:
  - mm/mempolicy.c:SYSC_migrate_pages
  - mm/mempolicy.c:SYSC_migrate_pages
  - mm/mempolicy.c:SYSC_set_mempolicy
  - mm/mempolicy.c:SYSC_mbind
```
**Symbols:**

```
ffffffff81236da0-ffffffff81236edf: get_nodes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int get_nodes(nodemask_t *nodes, const long unsigned int *nmask, long unsigned int maxnode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81259dc0)
Location: mm/mempolicy.c:1238
Inline: False
Direct callers:
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:kernel_set_mempolicy
  - mm/mempolicy.c:kernel_mbind
```
**Symbols:**

```
ffffffff81259dc0-ffffffff81259f37: get_nodes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int get_nodes(nodemask_t *nodes, const long unsigned int *nmask, long unsigned int maxnode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff8126d850)
Location: mm/mempolicy.c:1278
Inline: False
Direct callers:
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:kernel_set_mempolicy
  - mm/mempolicy.c:kernel_mbind
```
**Symbols:**

```
ffffffff8126d850-ffffffff8126d9c7: get_nodes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int get_nodes(nodemask_t *nodes, const long unsigned int *nmask, long unsigned int maxnode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81288d80)
Location: mm/mempolicy.c:1324
Inline: False
Direct callers:
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:kernel_set_mempolicy
  - mm/mempolicy.c:kernel_mbind
```
**Symbols:**

```
ffffffff81288d80-ffffffff81288ed9: get_nodes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int get_nodes(nodemask_t *nodes, const long unsigned int *nmask, long unsigned int maxnode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff812988f0)
Location: mm/mempolicy.c:1327
Inline: False
Direct callers:
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:kernel_set_mempolicy
  - mm/mempolicy.c:kernel_mbind
```
**Symbols:**

```
ffffffff812988f0-ffffffff81298a49: get_nodes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int get_nodes(nodemask_t *nodes, const long unsigned int *nmask, long unsigned int maxnode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff812cc7c0)
Location: mm/mempolicy.c:1396
Inline: False
Direct callers:
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:kernel_set_mempolicy
  - mm/mempolicy.c:kernel_mbind
```
**Symbols:**

```
ffffffff812cc7c0-ffffffff812cc91b: get_nodes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int get_nodes(nodemask_t *nodes, const long unsigned int *nmask, long unsigned int maxnode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff812d8160)
Location: mm/mempolicy.c:1372
Inline: False
Direct callers:
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:kernel_set_mempolicy
  - mm/mempolicy.c:kernel_mbind
```
**Symbols:**

```
ffffffff812d8160-ffffffff812d82bb: get_nodes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int get_nodes(nodemask_t *nodes, const long unsigned int *nmask, long unsigned int maxnode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff812dfa70)
Location: mm/mempolicy.c:1386
Inline: False
Direct callers:
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:kernel_set_mempolicy
  - mm/mempolicy.c:kernel_mbind
```
**Symbols:**

```
ffffffff812dfa70-ffffffff812dfbcb: get_nodes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int get_nodes(nodemask_t *nodes, const long unsigned int *nmask, long unsigned int maxnode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81327140)
Location: mm/mempolicy.c:1379
Inline: False
Direct callers:
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:kernel_set_mempolicy
  - mm/mempolicy.c:kernel_mbind
```
**Symbols:**

```
ffffffff81327140-ffffffff81327231: get_nodes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int get_nodes(nodemask_t *nodes, const long unsigned int *nmask, long unsigned int maxnode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81396080)
Location: mm/mempolicy.c:1372
Inline: False
Direct callers:
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:kernel_set_mempolicy
  - mm/mempolicy.c:kernel_mbind
```
**Symbols:**

```
ffffffff81396080-ffffffff813961c0: get_nodes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int get_nodes(nodemask_t *nodes, const long unsigned int *nmask, long unsigned int maxnode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81415b00)
Location: mm/mempolicy.c:1387
Inline: False
Direct callers:
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:kernel_set_mempolicy
  - mm/mempolicy.c:kernel_mbind
```
**Symbols:**

```
ffffffff81415b00-ffffffff81415c40: get_nodes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int get_nodes(nodemask_t *nodes, const long unsigned int *nmask, long unsigned int maxnode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81448f60)
Location: mm/mempolicy.c:1404
Inline: False
Direct callers:
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:kernel_set_mempolicy
  - mm/mempolicy.c:kernel_mbind
```
**Symbols:**

```
ffffffff81448f60-ffffffff814490a0: get_nodes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int get_nodes(nodemask_t *nodes, const long unsigned int *nmask, long unsigned int maxnode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81482930)
Location: mm/mempolicy.c:1388
Inline: False
Direct callers:
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:kernel_set_mempolicy
  - mm/mempolicy.c:kernel_mbind
```
**Symbols:**

```
ffffffff81482930-ffffffff81482a70: get_nodes (STB_LOCAL)
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
int get_nodes(nodemask_t *nodes, const long unsigned int *nmask, long unsigned int maxnode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffff8000103379d0)
Location: mm/mempolicy.c:1327
Inline: False
Direct callers:
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:kernel_set_mempolicy
  - mm/mempolicy.c:kernel_mbind
```
**Symbols:**

```
ffff8000103379d0-ffff800010337c0c: get_nodes (STB_LOCAL)
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
int get_nodes(nodemask_t *nodes, const long unsigned int *nmask, long unsigned int maxnode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (c000000000412780)
Location: mm/mempolicy.c:1327
Inline: False
Direct callers:
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:kernel_set_mempolicy
  - mm/mempolicy.c:kernel_mbind
```
**Symbols:**

```
c000000000412780-c0000000004129e8: get_nodes (STB_LOCAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
int get_nodes(nodemask_t *nodes, const long unsigned int *nmask, long unsigned int maxnode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81290ed0)
Location: mm/mempolicy.c:1327
Inline: False
Direct callers:
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:kernel_set_mempolicy
  - mm/mempolicy.c:kernel_mbind
```
**Symbols:**

```
ffffffff81290ed0-ffffffff81291029: get_nodes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int get_nodes(nodemask_t *nodes, const long unsigned int *nmask, long unsigned int maxnode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81282b50)
Location: mm/mempolicy.c:1327
Inline: False
Direct callers:
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:kernel_set_mempolicy
  - mm/mempolicy.c:kernel_mbind
```
**Symbols:**

```
ffffffff81282b50-ffffffff81282ca9: get_nodes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int get_nodes(nodemask_t *nodes, const long unsigned int *nmask, long unsigned int maxnode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff8128ece0)
Location: mm/mempolicy.c:1327
Inline: False
Direct callers:
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:kernel_set_mempolicy
  - mm/mempolicy.c:kernel_mbind
```
**Symbols:**

```
ffffffff8128ece0-ffffffff8128ee39: get_nodes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int get_nodes(nodemask_t *nodes, const long unsigned int *nmask, long unsigned int maxnode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff8129ebe0)
Location: mm/mempolicy.c:1327
Inline: False
Direct callers:
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:kernel_set_mempolicy
  - mm/mempolicy.c:kernel_mbind
```
**Symbols:**

```
ffffffff8129ebe0-ffffffff8129ed39: get_nodes (STB_LOCAL)
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
