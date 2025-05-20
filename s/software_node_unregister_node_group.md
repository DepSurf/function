# Function: <code>software_node_unregister_node_group</code>

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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void software_node_unregister_node_group(const struct software_node **node_group);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff817c3620)
Location: drivers/base/swnode.c:762
Inline: True
```
**Symbols:**

```
ffffffff817c3620-ffffffff817c3685: software_node_unregister_node_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void software_node_unregister_node_group(const struct software_node **node_group);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff817d8310)
Location: drivers/base/swnode.c:766
Inline: True
```
**Symbols:**

```
ffffffff817d8310-ffffffff817d8375: software_node_unregister_node_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void software_node_unregister_node_group(const struct software_node **node_group);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/swnode.c (ffffffff817bc040)
Location: drivers/base/swnode.c:930
Inline: True
```
**Symbols:**

```
ffffffff817bc040-ffffffff817bc0af: software_node_unregister_node_group.part.0 (STB_LOCAL)
ffffffff817bc0b0-ffffffff817bc0c6: software_node_unregister_node_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void software_node_unregister_node_group(const struct software_node **node_group);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/swnode.c (ffffffff818461e0)
Location: drivers/base/swnode.c:932
Inline: True
```
**Symbols:**

```
ffffffff818461e0-ffffffff8184624f: software_node_unregister_node_group.part.0 (STB_LOCAL)
ffffffff81846250-ffffffff81846266: software_node_unregister_node_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void software_node_unregister_node_group(const struct software_node **node_group);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/swnode.c (ffffffff8198ae42)
Location: drivers/base/swnode.c:926
Inline: True
Inline callers:
  - drivers/base/swnode.c:software_node_register_node_group
Direct callers:
  - drivers/base/swnode.c:software_node_register_node_group
```
**Symbols:**

```
ffffffff8198a800-ffffffff8198a8f2: software_node_unregister_node_group.part.0 (STB_LOCAL)
ffffffff8198a900-ffffffff8198a922: software_node_unregister_node_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
void software_node_unregister_node_group(const struct software_node **node_group);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/swnode.c (ffffffff81afa312)
Location: drivers/base/swnode.c:926
Inline: True
Inline callers:
  - drivers/base/swnode.c:software_node_register_node_group
Direct callers:
  - drivers/base/swnode.c:software_node_register_node_group
```
**Symbols:**

```
ffffffff81af9c60-ffffffff81af9d52: software_node_unregister_node_group.part.0 (STB_LOCAL)
ffffffff81af9d70-ffffffff81af9d92: software_node_unregister_node_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
void software_node_unregister_node_group(const struct software_node **node_group);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/swnode.c (ffffffff81b486a2)
Location: drivers/base/swnode.c:865
Inline: True
Inline callers:
  - drivers/base/swnode.c:software_node_register_node_group
Direct callers:
  - drivers/base/swnode.c:software_node_register_node_group
```
**Symbols:**

```
ffffffff81b48100-ffffffff81b481f2: software_node_unregister_node_group.part.0 (STB_LOCAL)
ffffffff81b48210-ffffffff81b48232: software_node_unregister_node_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void software_node_unregister_node_group(const struct software_node **node_group);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/swnode.c (ffffffff81ba0a92)
Location: drivers/base/swnode.c:868
Inline: True
Inline callers:
  - drivers/base/swnode.c:software_node_register_node_group
Direct callers:
  - drivers/base/swnode.c:software_node_register_node_group
```
**Symbols:**

```
ffffffff81ba04f0-ffffffff81ba05e2: software_node_unregister_node_group.part.0 (STB_LOCAL)
ffffffff81ba0600-ffffffff81ba0622: software_node_unregister_node_group (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
