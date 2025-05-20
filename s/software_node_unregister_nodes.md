# Function: <code>software_node_unregister_nodes</code>

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
void software_node_unregister_nodes(const struct software_node *nodes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff816e3a50)
Location: drivers/base/swnode.c:740
Inline: False
Direct callers:
  - drivers/base/swnode.c:software_node_register_nodes
```
**Symbols:**

```
ffffffff816e3a50-ffffffff816e3a93: software_node_unregister_nodes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void software_node_unregister_nodes(const struct software_node *nodes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff81708930)
Location: drivers/base/swnode.c:780
Inline: False
Direct callers:
  - drivers/base/swnode.c:software_node_register_nodes
```
**Symbols:**

```
ffffffff81708930-ffffffff81708973: software_node_unregister_nodes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void software_node_unregister_nodes(const struct software_node *nodes);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff817c38c8)
Location: drivers/base/swnode.c:721
Inline: True
Inline callers:
  - drivers/base/swnode.c:software_node_register_nodes
```
**Symbols:**

```
ffffffff817c35c0-ffffffff817c3620: software_node_unregister_nodes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void software_node_unregister_nodes(const struct software_node *nodes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff817d8040)
Location: drivers/base/swnode.c:725
Inline: False
Direct callers:
  - drivers/base/swnode.c:software_node_register_nodes
```
**Symbols:**

```
ffffffff817d8040-ffffffff817d80a0: software_node_unregister_nodes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void software_node_unregister_nodes(const struct software_node *nodes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff817bbf30)
Location: drivers/base/swnode.c:875
Inline: False
Direct callers:
  - drivers/base/swnode.c:software_node_register_nodes
```
**Symbols:**

```
ffffffff817bbf30-ffffffff817bbfa7: software_node_unregister_nodes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void software_node_unregister_nodes(const struct software_node *nodes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff818460d0)
Location: drivers/base/swnode.c:877
Inline: False
Direct callers:
  - drivers/base/swnode.c:software_node_register_nodes
```
**Symbols:**

```
ffffffff818460d0-ffffffff81846147: software_node_unregister_nodes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void software_node_unregister_nodes(const struct software_node *nodes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff8198a700)
Location: drivers/base/swnode.c:871
Inline: False
Direct callers:
  - drivers/base/swnode.c:software_node_register_nodes
```
**Symbols:**

```
ffffffff8198a700-ffffffff8198a7f3: software_node_unregister_nodes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void software_node_unregister_nodes(const struct software_node *nodes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff81af9b50)
Location: drivers/base/swnode.c:871
Inline: False
Direct callers:
  - drivers/base/swnode.c:software_node_register_nodes
```
**Symbols:**

```
ffffffff81af9b50-ffffffff81af9c43: software_node_unregister_nodes (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void software_node_unregister_nodes(const struct software_node *nodes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffff8000108f61d8)
Location: drivers/base/swnode.c:780
Inline: False
Direct callers:
  - drivers/base/swnode.c:software_node_register_nodes
```
**Symbols:**

```
ffff8000108f61d8-ffff8000108f6230: software_node_unregister_nodes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void software_node_unregister_nodes(const struct software_node *nodes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (c09e1a78)
Location: drivers/base/swnode.c:780
Inline: False
Direct callers:
  - drivers/base/swnode.c:software_node_register_nodes
```
**Symbols:**

```
c09e1a78-c09e1ac4: software_node_unregister_nodes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void software_node_unregister_nodes(const struct software_node *nodes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (c000000000991360)
Location: drivers/base/swnode.c:780
Inline: False
Direct callers:
  - drivers/base/swnode.c:software_node_register_nodes
```
**Symbols:**

```
c000000000991360-c0000000009913e8: software_node_unregister_nodes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void software_node_unregister_nodes(const struct software_node *nodes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffe0005871b8)
Location: drivers/base/swnode.c:780
Inline: False
Direct callers:
  - drivers/base/swnode.c:software_node_register_nodes
```
**Symbols:**

```
ffffffe0005871b8-ffffffe00058720a: software_node_unregister_nodes (STB_GLOBAL)
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
void software_node_unregister_nodes(const struct software_node *nodes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff816ce080)
Location: drivers/base/swnode.c:780
Inline: False
Direct callers:
  - drivers/base/swnode.c:software_node_register_nodes
```
**Symbols:**

```
ffffffff816ce080-ffffffff816ce0c3: software_node_unregister_nodes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void software_node_unregister_nodes(const struct software_node *nodes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff816a93b0)
Location: drivers/base/swnode.c:780
Inline: False
Direct callers:
  - drivers/base/swnode.c:software_node_register_nodes
```
**Symbols:**

```
ffffffff816a93b0-ffffffff816a93f3: software_node_unregister_nodes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void software_node_unregister_nodes(const struct software_node *nodes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff816fc5f0)
Location: drivers/base/swnode.c:780
Inline: False
Direct callers:
  - drivers/base/swnode.c:software_node_register_nodes
```
**Symbols:**

```
ffffffff816fc5f0-ffffffff816fc633: software_node_unregister_nodes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void software_node_unregister_nodes(const struct software_node *nodes);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/swnode.c (ffffffff81716280)
Location: drivers/base/swnode.c:780
Inline: False
Direct callers:
  - drivers/base/swnode.c:software_node_register_nodes
```
**Symbols:**

```
ffffffff81716280-ffffffff817162c3: software_node_unregister_nodes (STB_GLOBAL)
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
