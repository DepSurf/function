# Function: <code>add_memory_resource</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int add_memory_resource(int nid, struct resource *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff818199c0)
Location: mm/memory_hotplug.c:1235
Inline: False
Direct callers:
  - mm/memory_hotplug.c:add_memory
  - drivers/xen/balloon.c:reserve_additional_memory
```
**Symbols:**

```
ffffffff818199c0-ffffffff81819b39: add_memory_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int add_memory_resource(int nid, struct resource *res, bool online);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81894510)
Location: mm/memory_hotplug.c:1350
Inline: False
Direct callers:
  - mm/memory_hotplug.c:add_memory
  - drivers/xen/balloon.c:reserve_additional_memory
```
**Symbols:**

```
ffffffff81894510-ffffffff818946d7: add_memory_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int add_memory_resource(int nid, struct resource *res, bool online);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff818c8c20)
Location: mm/memory_hotplug.c:1342
Inline: False
Direct callers:
  - mm/memory_hotplug.c:add_memory
  - drivers/xen/balloon.c:reserve_additional_memory
```
**Symbols:**

```
ffffffff818c8c20-ffffffff818c8dc5: add_memory_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int add_memory_resource(int nid, struct resource *res, bool online);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81900180)
Location: mm/memory_hotplug.c:1138
Inline: False
Direct callers:
  - mm/memory_hotplug.c:add_memory
  - drivers/xen/balloon.c:reserve_additional_memory
```
**Symbols:**

```
ffffffff81900180-ffffffff8190035f: add_memory_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int add_memory_resource(int nid, struct resource *res, bool online);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff8198a120)
Location: mm/memory_hotplug.c:1126
Inline: False
Direct callers:
  - mm/memory_hotplug.c:add_memory
  - drivers/xen/balloon.c:reserve_additional_memory
```
**Symbols:**

```
ffffffff8198a120-ffffffff8198a2ff: add_memory_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int add_memory_resource(int nid, struct resource *res, bool online);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff819e6a40)
Location: mm/memory_hotplug.c:1112
Inline: False
Direct callers:
  - mm/memory_hotplug.c:add_memory
  - drivers/xen/balloon.c:reserve_additional_memory
```
**Symbols:**

```
ffffffff819e6a40-ffffffff819e6c2f: add_memory_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int add_memory_resource(int nid, struct resource *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81a21eb0)
Location: mm/memory_hotplug.c:1094
Inline: False
Direct callers:
  - mm/memory_hotplug.c:__add_memory
  - drivers/xen/balloon.c:reserve_additional_memory
```
**Symbols:**

```
ffffffff81a21eb0-ffffffff81a22075: add_memory_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int add_memory_resource(int nid, struct resource *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81a91ce0)
Location: mm/memory_hotplug.c:1070
Inline: False
Direct callers:
  - mm/memory_hotplug.c:__add_memory
  - drivers/xen/balloon.c:reserve_additional_memory
```
**Symbols:**

```
ffffffff81a91ce0-ffffffff81a91edf: add_memory_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int add_memory_resource(int nid, struct resource *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81ac9470)
Location: mm/memory_hotplug.c:1045
Inline: False
Direct callers:
  - mm/memory_hotplug.c:__add_memory
  - drivers/xen/balloon.c:reserve_additional_memory
```
**Symbols:**

```
ffffffff81ac9470-ffffffff81ac966f: add_memory_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int add_memory_resource(int nid, struct resource *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81bc1b30)
Location: mm/memory_hotplug.c:1028
Inline: False
Direct callers:
  - mm/memory_hotplug.c:add_memory_driver_managed
  - mm/memory_hotplug.c:__add_memory
  - drivers/xen/balloon.c:reserve_additional_memory
```
**Symbols:**

```
ffffffff81bc1b30-ffffffff81bc1deb: add_memory_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int add_memory_resource(int nid, struct resource *res, mhp_t mhp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81c3abd0)
Location: mm/memory_hotplug.c:1033
Inline: False
Direct callers:
  - mm/memory_hotplug.c:add_memory_driver_managed
  - mm/memory_hotplug.c:__add_memory
  - drivers/xen/balloon.c:reserve_additional_memory
```
**Symbols:**

```
ffffffff81c3abd0-ffffffff81c3aeb0: add_memory_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int add_memory_resource(int nid, struct resource *res, mhp_t mhp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81c2d1f0)
Location: mm/memory_hotplug.c:1200
Inline: False
Direct callers:
  - mm/memory_hotplug.c:add_memory_driver_managed
  - mm/memory_hotplug.c:__add_memory
  - drivers/xen/balloon.c:reserve_additional_memory
```
**Symbols:**

```
ffffffff81c2d1f0-ffffffff81c2d4e2: add_memory_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int add_memory_resource(int nid, struct resource *res, mhp_t mhp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81d4baa0)
Location: mm/memory_hotplug.c:1357
Inline: False
Direct callers:
  - mm/memory_hotplug.c:add_memory_driver_managed
  - mm/memory_hotplug.c:__add_memory
  - drivers/xen/balloon.c:reserve_additional_memory
```
**Symbols:**

```
ffffffff81d4baa0-ffffffff81d4bdb6: add_memory_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int add_memory_resource(int nid, struct resource *res, mhp_t mhp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81f1b390)
Location: mm/memory_hotplug.c:1321
Inline: False
Direct callers:
  - mm/memory_hotplug.c:add_memory_driver_managed
  - mm/memory_hotplug.c:__add_memory
  - drivers/xen/balloon.c:reserve_additional_memory
```
**Symbols:**

```
ffffffff81f1b390-ffffffff81f1b670: add_memory_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int add_memory_resource(int nid, struct resource *res, mhp_t mhp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff820c3300)
Location: mm/memory_hotplug.c:1319
Inline: False
Direct callers:
  - mm/memory_hotplug.c:add_memory_driver_managed
  - mm/memory_hotplug.c:__add_memory
  - drivers/xen/balloon.c:reserve_additional_memory
```
**Symbols:**

```
ffffffff820c3300-ffffffff820c35e0: add_memory_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int add_memory_resource(int nid, struct resource *res, mhp_t mhp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff821470e0)
Location: mm/memory_hotplug.c:1294
Inline: False
Direct callers:
  - mm/memory_hotplug.c:add_memory_driver_managed
  - mm/memory_hotplug.c:__add_memory
  - drivers/xen/balloon.c:reserve_additional_memory
```
**Symbols:**

```
ffffffff821470e0-ffffffff821473c0: add_memory_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int add_memory_resource(int nid, struct resource *res, mhp_t mhp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff82229850)
Location: mm/memory_hotplug.c:1482
Inline: False
Direct callers:
  - mm/memory_hotplug.c:add_memory_driver_managed
  - mm/memory_hotplug.c:__add_memory
  - drivers/xen/balloon.c:reserve_additional_memory
```
**Symbols:**

```
ffffffff82229850-ffffffff82229bd5: add_memory_resource (STB_GLOBAL)
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
int add_memory_resource(int nid, struct resource *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffff800010d9d238)
Location: mm/memory_hotplug.c:1045
Inline: False
Direct callers:
  - mm/memory_hotplug.c:__add_memory
  - drivers/xen/balloon.c:reserve_additional_memory
```
**Symbols:**

```
ffff800010d9d238-ffff800010d9d460: add_memory_resource (STB_GLOBAL)
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
int add_memory_resource(int nid, struct resource *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (c000000000430170)
Location: mm/memory_hotplug.c:1045
Inline: False
Direct callers:
  - mm/memory_hotplug.c:__add_memory
```
**Symbols:**

```
c000000000430170-c000000000430458: add_memory_resource (STB_GLOBAL)
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
int add_memory_resource(int nid, struct resource *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81a682e0)
Location: mm/memory_hotplug.c:1045
Inline: False
Direct callers:
  - mm/memory_hotplug.c:__add_memory
```
**Symbols:**

```
ffffffff81a682e0-ffffffff81a684df: add_memory_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int add_memory_resource(int nid, struct resource *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81a24da0)
Location: mm/memory_hotplug.c:1045
Inline: False
Direct callers:
  - mm/memory_hotplug.c:__add_memory
```
**Symbols:**

```
ffffffff81a24da0-ffffffff81a24f9f: add_memory_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int add_memory_resource(int nid, struct resource *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81ad46f0)
Location: mm/memory_hotplug.c:1045
Inline: False
Direct callers:
  - mm/memory_hotplug.c:__add_memory
  - drivers/xen/balloon.c:reserve_additional_memory
```
**Symbols:**

```
ffffffff81ad46f0-ffffffff81ad48ef: add_memory_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int add_memory_resource(int nid, struct resource *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81ae0bd0)
Location: mm/memory_hotplug.c:1045
Inline: False
Direct callers:
  - mm/memory_hotplug.c:__add_memory
  - drivers/xen/balloon.c:reserve_additional_memory
```
**Symbols:**

```
ffffffff81ae0bd0-ffffffff81ae0dcf: add_memory_resource (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool online</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>bool online</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>mhp_t mhp_flags</code>
</li>
</ul>
</details>
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
