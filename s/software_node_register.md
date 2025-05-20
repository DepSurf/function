# Function: <code>software_node_register</code>

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
In <code>5.0</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int software_node_register(const struct software_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff816e41d0)
Location: drivers/base/swnode.c:757
Inline: False
Direct callers:
  - drivers/base/swnode.c:software_node_register_nodes
```
**Symbols:**

```
ffffffff816e41d0-ffffffff816e4221: software_node_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int software_node_register(const struct software_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff817088d0)
Location: drivers/base/swnode.c:797
Inline: False
Direct callers:
  - drivers/base/swnode.c:software_node_register_nodes
```
**Symbols:**

```
ffffffff817088d0-ffffffff81708921: software_node_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int software_node_register(const struct software_node *node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff817c388e)
Location: drivers/base/swnode.c:782
Inline: True
Inline callers:
  - drivers/base/swnode.c:software_node_register_nodes
```
**Symbols:**

```
ffffffff817c3180-ffffffff817c31d1: software_node_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int software_node_register(const struct software_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff817d7fd0)
Location: drivers/base/swnode.c:782
Inline: False
Direct callers:
  - drivers/base/swnode.c:software_node_register_nodes
```
**Symbols:**

```
ffffffff817d7fd0-ffffffff817d8035: software_node_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int software_node_register(const struct software_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff817bbec0)
Location: drivers/base/swnode.c:950
Inline: False
Direct callers:
  - drivers/base/swnode.c:device_add_software_node
  - drivers/base/swnode.c:software_node_register_nodes
```
**Symbols:**

```
ffffffff817bbec0-ffffffff817bbf22: software_node_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int software_node_register(const struct software_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff81846060)
Location: drivers/base/swnode.c:952
Inline: False
Direct callers:
  - drivers/base/swnode.c:device_add_software_node
  - drivers/base/swnode.c:software_node_register_nodes
```
**Symbols:**

```
ffffffff81846060-ffffffff818460c2: software_node_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int software_node_register(const struct software_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff8198abf0)
Location: drivers/base/swnode.c:946
Inline: False
Direct callers:
  - drivers/base/swnode.c:device_add_software_node
  - drivers/base/swnode.c:device_add_software_node
  - drivers/base/swnode.c:software_node_register_node_group
  - drivers/base/swnode.c:software_node_register_nodes
```
**Symbols:**

```
ffffffff8198abf0-ffffffff8198ad0c: software_node_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int software_node_register(const struct software_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff81afa0a0)
Location: drivers/base/swnode.c:946
Inline: False
Direct callers:
  - drivers/base/swnode.c:device_add_software_node
  - drivers/base/swnode.c:device_add_software_node
  - drivers/base/swnode.c:software_node_register_node_group
  - drivers/base/swnode.c:software_node_register_nodes
```
**Symbols:**

```
ffffffff81afa0a0-ffffffff81afa1bc: software_node_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int software_node_register(const struct software_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff81b48530)
Location: drivers/base/swnode.c:885
Inline: False
Direct callers:
  - drivers/base/swnode.c:device_add_software_node
  - drivers/base/swnode.c:device_add_software_node
  - drivers/base/swnode.c:software_node_register_node_group
```
**Symbols:**

```
ffffffff81b48530-ffffffff81b4864c: software_node_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int software_node_register(const struct software_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff81ba0920)
Location: drivers/base/swnode.c:888
Inline: False
Direct callers:
  - drivers/base/swnode.c:device_add_software_node
  - drivers/base/swnode.c:device_add_software_node
  - drivers/base/swnode.c:software_node_register_node_group
```
**Symbols:**

```
ffffffff81ba0920-ffffffff81ba0a3c: software_node_register (STB_GLOBAL)
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
int software_node_register(const struct software_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffff8000108f6178)
Location: drivers/base/swnode.c:797
Inline: False
Direct callers:
  - drivers/base/swnode.c:software_node_register_nodes
```
**Symbols:**

```
ffff8000108f6178-ffff8000108f61d4: software_node_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int software_node_register(const struct software_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (c09e226c)
Location: drivers/base/swnode.c:797
Inline: False
Direct callers:
  - drivers/base/swnode.c:software_node_register_nodes
```
**Symbols:**

```
c09e226c-c09e22c0: software_node_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int software_node_register(const struct software_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (c0000000009912c0)
Location: drivers/base/swnode.c:797
Inline: False
Direct callers:
  - drivers/base/swnode.c:software_node_register_nodes
```
**Symbols:**

```
c0000000009912c0-c000000000991358: software_node_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int software_node_register(const struct software_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffe00058715a)
Location: drivers/base/swnode.c:797
Inline: False
Direct callers:
  - drivers/base/swnode.c:software_node_register_nodes
```
**Symbols:**

```
ffffffe00058715a-ffffffe0005871b8: software_node_register (STB_GLOBAL)
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
int software_node_register(const struct software_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff816ce020)
Location: drivers/base/swnode.c:797
Inline: False
Direct callers:
  - drivers/base/swnode.c:software_node_register_nodes
```
**Symbols:**

```
ffffffff816ce020-ffffffff816ce071: software_node_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int software_node_register(const struct software_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff816a9350)
Location: drivers/base/swnode.c:797
Inline: False
Direct callers:
  - drivers/base/swnode.c:software_node_register_nodes
```
**Symbols:**

```
ffffffff816a9350-ffffffff816a93a1: software_node_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int software_node_register(const struct software_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff816fc590)
Location: drivers/base/swnode.c:797
Inline: False
Direct callers:
  - drivers/base/swnode.c:software_node_register_nodes
```
**Symbols:**

```
ffffffff816fc590-ffffffff816fc5e1: software_node_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int software_node_register(const struct software_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff81716a00)
Location: drivers/base/swnode.c:797
Inline: False
Direct callers:
  - drivers/base/swnode.c:software_node_register_nodes
```
**Symbols:**

```
ffffffff81716a00-ffffffff81716a51: software_node_register (STB_GLOBAL)
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
