# Function: <code>xa_delete_node</code>

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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void xa_delete_node(struct xa_node *node, xa_update_node_t update);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81620c20)
Location: lib/xarray.c:2173
Inline: False
Direct callers:
  - mm/workingset.c:shadow_lru_isolate
```
**Symbols:**

```
ffffffff81620c20-ffffffff81620c9a: xa_delete_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void xa_delete_node(struct xa_node *node, xa_update_node_t update);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81604400)
Location: lib/xarray.c:2174
Inline: False
Direct callers:
  - mm/workingset.c:shadow_lru_isolate
```
**Symbols:**

```
ffffffff81604400-ffffffff8160447a: xa_delete_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void xa_delete_node(struct xa_node *node, xa_update_node_t update);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/xarray.c (0)
Location: lib/xarray.c:2174
Inline: False
Direct callers:
  - mm/workingset.c:shadow_lru_isolate
```
**Symbols:**

```
ffffffff81ce00dd-ffffffff81ce0101: xa_delete_node.cold (STB_LOCAL)
ffffffff81672cb0-ffffffff81672d61: xa_delete_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void xa_delete_node(struct xa_node *node, xa_update_node_t update);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/xarray.c (0)
Location: lib/xarray.c:2181
Inline: False
Direct callers:
  - mm/workingset.c:shadow_lru_isolate
```
**Symbols:**

```
ffffffff81ea67d6-ffffffff81ea67fa: xa_delete_node.cold (STB_LOCAL)
ffffffff8178d1c0-ffffffff8178d27f: xa_delete_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void xa_delete_node(struct xa_node *node, xa_update_node_t update);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/xarray.c (0)
Location: lib/xarray.c:2181
Inline: False
Direct callers:
  - mm/workingset.c:shadow_lru_isolate
```
**Symbols:**

```
ffffffff820b805c-ffffffff820b8080: xa_delete_node.cold (STB_LOCAL)
ffffffff8204a800-ffffffff8204a8bf: xa_delete_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void xa_delete_node(struct xa_node *node, xa_update_node_t update);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/xarray.c (0)
Location: lib/xarray.c:2179
Inline: False
Direct callers:
  - mm/workingset.c:shadow_lru_isolate
```
**Symbols:**

```
ffffffff8213943d-ffffffff82139461: xa_delete_node.cold (STB_LOCAL)
ffffffff820c9100-ffffffff820c91bf: xa_delete_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void xa_delete_node(struct xa_node *node, xa_update_node_t update);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/xarray.c (0)
Location: lib/xarray.c:2185
Inline: False
Direct callers:
  - mm/workingset.c:shadow_lru_isolate
```
**Symbols:**

```
ffffffff8221b1e2-ffffffff8221b206: xa_delete_node.cold (STB_LOCAL)
ffffffff821a3a80-ffffffff821a3b3f: xa_delete_node (STB_GLOBAL)
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
