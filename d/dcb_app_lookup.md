# Function: <code>dcb_app_lookup</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
struct dcb_app_type *dcb_app_lookup(const struct dcb_app *app, int ifindex, int prio);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/dcb/dcbnl.c (ffffffff81812a30)
Location: net/dcb/dcbnl.c:1757
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_getapp
  - net/dcb/dcbnl.c:dcb_ieee_getapp_mask
  - net/dcb/dcbnl.c:dcb_setapp
Direct callers:
  - net/dcb/dcbnl.c:dcb_ieee_setapp
  - net/dcb/dcbnl.c:dcb_ieee_delapp
```
**Symbols:**

```
ffffffff81812a30-ffffffff81812a8a: dcb_app_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct dcb_app_type *dcb_app_lookup(const struct dcb_app *app, int ifindex, int prio);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/dcb/dcbnl.c (ffffffff81885a0e)
Location: net/dcb/dcbnl.c:1757
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_ieee_getapp_mask
  - net/dcb/dcbnl.c:dcb_setapp
  - net/dcb/dcbnl.c:dcb_getapp
Direct callers:
  - net/dcb/dcbnl.c:dcb_ieee_delapp
  - net/dcb/dcbnl.c:dcb_ieee_setapp
```
**Symbols:**

```
ffffffff81885900-ffffffff8188595a: dcb_app_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct dcb_app_type *dcb_app_lookup(const struct dcb_app *app, int ifindex, int prio);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/dcb/dcbnl.c (ffffffff818ba27e)
Location: net/dcb/dcbnl.c:1758
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_ieee_getapp_mask
  - net/dcb/dcbnl.c:dcb_setapp
  - net/dcb/dcbnl.c:dcb_getapp
Direct callers:
  - net/dcb/dcbnl.c:dcb_ieee_delapp
  - net/dcb/dcbnl.c:dcb_ieee_setapp
```
**Symbols:**

```
ffffffff818ba170-ffffffff818ba1ca: dcb_app_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct dcb_app_type *dcb_app_lookup(const struct dcb_app *app, int ifindex, int prio);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/dcb/dcbnl.c (ffffffff818e0c9e)
Location: net/dcb/dcbnl.c:1759
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_ieee_getapp_mask
  - net/dcb/dcbnl.c:dcb_setapp
  - net/dcb/dcbnl.c:dcb_getapp
Direct callers:
  - net/dcb/dcbnl.c:dcb_ieee_delapp
  - net/dcb/dcbnl.c:dcb_ieee_setapp
```
**Symbols:**

```
ffffffff818e0b90-ffffffff818e0bea: dcb_app_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct dcb_app_type *dcb_app_lookup(const struct dcb_app *app, int ifindex, int prio);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/dcb/dcbnl.c (ffffffff819669be)
Location: net/dcb/dcbnl.c:1759
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_ieee_getapp_mask
  - net/dcb/dcbnl.c:dcb_setapp
  - net/dcb/dcbnl.c:dcb_getapp
Direct callers:
  - net/dcb/dcbnl.c:dcb_ieee_delapp
  - net/dcb/dcbnl.c:dcb_ieee_setapp
```
**Symbols:**

```
ffffffff819668b0-ffffffff8196690a: dcb_app_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/dcb/dcbnl.c (ffffffff819c024d)
Location: net/dcb/dcbnl.c:1780
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_ieee_getapp_mask
  - net/dcb/dcbnl.c:dcb_setapp
  - net/dcb/dcbnl.c:dcb_getapp
Direct callers:
  - net/dcb/dcbnl.c:dcb_ieee_delapp
  - net/dcb/dcbnl.c:dcb_ieee_setapp
```
**Symbols:**

```
ffffffff819c0f00-ffffffff819c0f55: dcb_app_lookup.isra.11 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/dcb/dcbnl.c (ffffffff819f740d)
Location: net/dcb/dcbnl.c:1780
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_ieee_getapp_mask
  - net/dcb/dcbnl.c:dcb_setapp
  - net/dcb/dcbnl.c:dcb_getapp
Direct callers:
  - net/dcb/dcbnl.c:dcb_ieee_delapp
  - net/dcb/dcbnl.c:dcb_ieee_setapp
```
**Symbols:**

```
ffffffff819f8460-ffffffff819f84b5: dcb_app_lookup.isra.10 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/dcb/dcbnl.c (ffffffff81a6693d)
Location: net/dcb/dcbnl.c:1789
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_ieee_getapp_mask
  - net/dcb/dcbnl.c:dcb_setapp
  - net/dcb/dcbnl.c:dcb_getapp
Direct callers:
  - net/dcb/dcbnl.c:dcb_ieee_delapp
  - net/dcb/dcbnl.c:dcb_ieee_setapp
```
**Symbols:**

```
ffffffff81a679a0-ffffffff81a679fa: dcb_app_lookup.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/dcb/dcbnl.c (ffffffff81a9d45d)
Location: net/dcb/dcbnl.c:1789
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_ieee_getapp_mask
  - net/dcb/dcbnl.c:dcb_setapp
  - net/dcb/dcbnl.c:dcb_getapp
Direct callers:
  - net/dcb/dcbnl.c:dcb_ieee_delapp
  - net/dcb/dcbnl.c:dcb_ieee_setapp
```
**Symbols:**

```
ffffffff81a9e300-ffffffff81a9e35a: dcb_app_lookup.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct dcb_app_type *dcb_app_lookup(const struct dcb_app *app, int ifindex, int prio);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/dcb/dcbnl.c (ffffffff81b99d7d)
Location: net/dcb/dcbnl.c:1797
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_ieee_getapp_mask
  - net/dcb/dcbnl.c:dcb_setapp
  - net/dcb/dcbnl.c:dcb_getapp
Direct callers:
  - net/dcb/dcbnl.c:dcb_ieee_delapp
  - net/dcb/dcbnl.c:dcb_ieee_setapp
```
**Symbols:**

```
ffffffff81b98d60-ffffffff81b98dbe: dcb_app_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct dcb_app_type *dcb_app_lookup(const struct dcb_app *app, int ifindex, int prio);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/dcb/dcbnl.c (ffffffff81ba9a7d)
Location: net/dcb/dcbnl.c:1799
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_ieee_getapp_mask
  - net/dcb/dcbnl.c:dcb_setapp
  - net/dcb/dcbnl.c:dcb_getapp
Direct callers:
  - net/dcb/dcbnl.c:dcb_ieee_delapp
  - net/dcb/dcbnl.c:dcb_ieee_setapp
```
**Symbols:**

```
ffffffff81ba8a30-ffffffff81ba8a8e: dcb_app_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct dcb_app_type *dcb_app_lookup(const struct dcb_app *app, int ifindex, int prio);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/dcb/dcbnl.c (ffffffff81b98c0d)
Location: net/dcb/dcbnl.c:1799
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_ieee_getapp_mask
  - net/dcb/dcbnl.c:dcb_setapp
  - net/dcb/dcbnl.c:dcb_getapp
Direct callers:
  - net/dcb/dcbnl.c:dcb_ieee_delapp
  - net/dcb/dcbnl.c:dcb_ieee_setapp
```
**Symbols:**

```
ffffffff81b97bc0-ffffffff81b97c1b: dcb_app_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct dcb_app_type *dcb_app_lookup(const struct dcb_app *app, int ifindex, int prio);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/dcb/dcbnl.c (ffffffff81c65901)
Location: net/dcb/dcbnl.c:1799
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_ieee_getapp_mask
  - net/dcb/dcbnl.c:dcb_setapp
  - net/dcb/dcbnl.c:dcb_getapp
Direct callers:
  - net/dcb/dcbnl.c:dcb_ieee_delapp
  - net/dcb/dcbnl.c:dcb_ieee_setapp
```
**Symbols:**

```
ffffffff81c64640-ffffffff81c6469b: dcb_app_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct dcb_app_type *dcb_app_lookup(const struct dcb_app *app, int ifindex, int prio);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/dcb/dcbnl.c (ffffffff81e08661)
Location: net/dcb/dcbnl.c:1799
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_ieee_getapp_mask
  - net/dcb/dcbnl.c:dcb_setapp
  - net/dcb/dcbnl.c:dcb_getapp
Direct callers:
  - net/dcb/dcbnl.c:dcb_ieee_delapp
  - net/dcb/dcbnl.c:dcb_ieee_setapp
```
**Symbols:**

```
ffffffff81e07150-ffffffff81e071c9: dcb_app_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct dcb_app_type *dcb_app_lookup(const struct dcb_app *app, int ifindex, int prio);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/dcb/dcbnl.c (ffffffff81fddc11)
Location: net/dcb/dcbnl.c:1942
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_ieee_getapp_mask
  - net/dcb/dcbnl.c:dcb_setapp
  - net/dcb/dcbnl.c:dcb_getapp
Direct callers:
  - net/dcb/dcbnl.c:dcb_ieee_delapp
  - net/dcb/dcbnl.c:dcb_ieee_setapp
```
**Symbols:**

```
ffffffff81fdc5a0-ffffffff81fdc619: dcb_app_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct dcb_app_type *dcb_app_lookup(const struct dcb_app *app, int ifindex, int prio);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/dcb/dcbnl.c (ffffffff82059e41)
Location: net/dcb/dcbnl.c:1986
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_ieee_getapp_mask
  - net/dcb/dcbnl.c:dcb_setapp
  - net/dcb/dcbnl.c:dcb_getapp
Direct callers:
  - net/dcb/dcbnl.c:dcb_ieee_delapp
  - net/dcb/dcbnl.c:dcb_ieee_setapp
```
**Symbols:**

```
ffffffff82058360-ffffffff820583d9: dcb_app_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct dcb_app_type *dcb_app_lookup(const struct dcb_app *app, int ifindex, int prio);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/dcb/dcbnl.c (ffffffff8212c9c1)
Location: net/dcb/dcbnl.c:1986
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_ieee_getapp_mask
  - net/dcb/dcbnl.c:dcb_setapp
  - net/dcb/dcbnl.c:dcb_getapp
Direct callers:
  - net/dcb/dcbnl.c:dcb_ieee_delapp
  - net/dcb/dcbnl.c:dcb_ieee_setapp
```
**Symbols:**

```
ffffffff8212aeb0-ffffffff8212af29: dcb_app_lookup (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/dcb/dcbnl.c (ffff800010d6fe64)
Location: net/dcb/dcbnl.c:1789
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_ieee_getapp_mask
  - net/dcb/dcbnl.c:dcb_setapp
  - net/dcb/dcbnl.c:dcb_getapp
Direct callers:
  - net/dcb/dcbnl.c:dcb_ieee_delapp
  - net/dcb/dcbnl.c:dcb_ieee_setapp
```
**Symbols:**

```
ffff800010d6ee70-ffff800010d6ef20: dcb_app_lookup.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct dcb_app_type *dcb_app_lookup(const struct dcb_app *app, int ifindex, int prio);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/dcb/dcbnl.c (c0e6ba34)
Location: net/dcb/dcbnl.c:1789
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_ieee_getapp_mask
  - net/dcb/dcbnl.c:dcb_setapp
  - net/dcb/dcbnl.c:dcb_getapp
Direct callers:
  - net/dcb/dcbnl.c:dcb_ieee_delapp
  - net/dcb/dcbnl.c:dcb_ieee_setapp
```
**Symbols:**

```
c0e6b8b8-c0e6b94c: dcb_app_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/dcb/dcbnl.c (c000000000eac030)
Location: net/dcb/dcbnl.c:1789
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_ieee_getapp_mask
  - net/dcb/dcbnl.c:dcb_setapp
  - net/dcb/dcbnl.c:dcb_getapp
Direct callers:
  - net/dcb/dcbnl.c:dcb_ieee_delapp
  - net/dcb/dcbnl.c:dcb_ieee_setapp
```
**Symbols:**

```
c000000000eada50-c000000000eadaf0: dcb_app_lookup.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/dcb/dcbnl.c (ffffffe00089fda6)
Location: net/dcb/dcbnl.c:1789
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_ieee_getapp_mask
  - net/dcb/dcbnl.c:dcb_setapp
  - net/dcb/dcbnl.c:dcb_getapp
Direct callers:
  - net/dcb/dcbnl.c:dcb_ieee_delapp
  - net/dcb/dcbnl.c:dcb_ieee_setapp
```
**Symbols:**

```
ffffffe0008a099e-ffffffe0008a0a26: dcb_app_lookup.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/dcb/dcbnl.c (ffffffff81a3c7ed)
Location: net/dcb/dcbnl.c:1789
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_ieee_getapp_mask
  - net/dcb/dcbnl.c:dcb_setapp
  - net/dcb/dcbnl.c:dcb_getapp
Direct callers:
  - net/dcb/dcbnl.c:dcb_ieee_delapp
  - net/dcb/dcbnl.c:dcb_ieee_setapp
```
**Symbols:**

```
ffffffff81a3d690-ffffffff81a3d6ea: dcb_app_lookup.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/dcb/dcbnl.c (ffffffff819f93dd)
Location: net/dcb/dcbnl.c:1789
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_ieee_getapp_mask
  - net/dcb/dcbnl.c:dcb_setapp
  - net/dcb/dcbnl.c:dcb_getapp
Direct callers:
  - net/dcb/dcbnl.c:dcb_ieee_delapp
  - net/dcb/dcbnl.c:dcb_ieee_setapp
```
**Symbols:**

```
ffffffff819fa280-ffffffff819fa2da: dcb_app_lookup.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/dcb/dcbnl.c (ffffffff81aa869d)
Location: net/dcb/dcbnl.c:1789
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_ieee_getapp_mask
  - net/dcb/dcbnl.c:dcb_setapp
  - net/dcb/dcbnl.c:dcb_getapp
Direct callers:
  - net/dcb/dcbnl.c:dcb_ieee_delapp
  - net/dcb/dcbnl.c:dcb_ieee_setapp
```
**Symbols:**

```
ffffffff81aa9540-ffffffff81aa959a: dcb_app_lookup.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/dcb/dcbnl.c (ffffffff81ab4a0d)
Location: net/dcb/dcbnl.c:1789
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_ieee_getapp_mask
  - net/dcb/dcbnl.c:dcb_setapp
  - net/dcb/dcbnl.c:dcb_getapp
Direct callers:
  - net/dcb/dcbnl.c:dcb_ieee_delapp
  - net/dcb/dcbnl.c:dcb_ieee_setapp
```
**Symbols:**

```
ffffffff81ab58b0-ffffffff81ab590a: dcb_app_lookup.isra.0 (STB_LOCAL)
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
</ul>
